# Finance - Performance Metrics

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/finance-performance-metrics) |
| Metadata | [Link](https://data.lacity.org/api/views/7y6s-y8bd) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/7y6s-y8bd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/7y6s-y8bd/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | 7y6s-y8bd |
| Name | Finance - Performance Metrics |
| Attribution | Office of Finance |
| Category | A Well Run City |
| Tags | finance, performance, metrics |
| Created | 2014-07-30T01:08:29Z |
| Publication Date | 2015-04-15T17:30:42Z |

## Description

This dataset contains metrics that measure the operational performance of the office of Finance. These metrics are used on a regular basis by the department and the Mayor to evaluate progress and inform decision making.  Performance management forms the foundation of a data-driven culture of innovation and excellence in the City of Los Angeles.

## Columns

```ls
| Included | Schema Type    | Field Name                                                     | Name                                                              | Data Type     | Render Type   |
| ======== | ============== | ============================================================== | ================================================================= | ============= | ============= |
| Yes      | time           | date                                                           | Date                                                              | calendar_date | calendar_date |
| Yes      | series tag     | month_year                                                     | Month-Year                                                        | text          | text          |
| No       |                | quarter_fy                                                     | Quarter-FY                                                        | text          | text          |
| Yes      | series tag     | annual_fy                                                      | Annual-FY                                                         | text          | text          |
| Yes      | numeric metric | audit_penetration_rate_fytd_monthly                            | Audit penetration Rate FYTD (Monthly)                             | percent       | percent       |
| Yes      | numeric metric | target_audit_penetration_rate_fytd_monthly                     | TARGET: Audit Penetration Rate FYTD (Monthly)                     | percent       | percent       |
| Yes      | numeric metric | of_lien_cases_resolved_fytd_monthly                            | % of lien cases resolved FYTD (Monthly)                           | percent       | percent       |
| Yes      | numeric metric | target_of_lien_cases_resolved_fytd_monthly                     | TARGET: % of lien cases resolved FYTD (Monthly)                   | percent       | percent       |
| Yes      | numeric metric | of_call_center_calls_answered_monthly_2                        | # of call center calls answered (Monthly)                         | number        | number        |
| Yes      | numeric metric | yoy_benchmark_of_call_center_calls_answered_monthly_2          | YOY BENCHMARK: # of call center calls answered (Monthly)          | number        | number        |
| Yes      | numeric metric | of_call_center_calls_answered_monthly                          | % of call center calls answered (Monthly)                         | percent       | percent       |
| Yes      | numeric metric | yoy_benchmark_of_call_center_calls_answered_monthly            | YOY BENCHMARK: % of call center calls answered (Monthly)          | percent       | percent       |
| Yes      | series tag     | monthly_investment_report_finding_on_compliance_monthly        | Monthly Investment Report finding on Compliance (Monthly)         | text          | text          |
| Yes      | series tag     | target_monthly_investment_report_finding_on_compliance_monthly | TARGET: Monthly Investment Report finding on Compliance (Monthly) | text          | text          |
| Yes      | numeric metric | of_business_tax_renewal_from_web_sources_annual_fy             | % of Business Tax renewal from web sources (Annual FY)            | percent       | percent       |
| Yes      | numeric metric | target_of_business_tax_renewal_from_web_sources_annual_fy      | TARGET: % of Business Tax renewal from web sources (Annual FY)    | percent       | percent       |
| Yes      | series tag     | milestones_paperless_program_project                           | Milestones: Paperless Program (Project)                           | text          | text          |
| Yes      | series tag     | target_paperless_program                                       | TARGET: Paperless Program                                         | text          | text          |
| Yes      | series tag     | status_paperless_program                                       | STATUS: Paperless Program                                         | text          | text          |
| Yes      | series tag     | milestones_customer_satisfaction_survey_project                | Milestones: Customer Satisfaction Survey (Project)                | text          | text          |
| Yes      | series tag     | target_customer_satisfaction_survey                            | TARGET: Customer Satisfaction Survey                              | text          | text          |
| Yes      | series tag     | status_customer_satisfaction_survey                            | STATUS: Customer Satisfaction Survey                              | text          | text          |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = quarter_fy
```

## Data Commands

```ls
series e:7y6s-y8bd d:2010-06-30T00:00:00.000Z t:annual_fy="FY 2010" t:month_year=Jun-10 m:of_business_tax_renewal_from_web_sources_annual_fy=47

series e:7y6s-y8bd d:2011-06-30T00:00:00.000Z t:annual_fy="FY 2011" t:month_year=Jun-11 m:of_business_tax_renewal_from_web_sources_annual_fy=58

series e:7y6s-y8bd d:2012-06-30T00:00:00.000Z t:annual_fy="FY 2012" t:month_year=Jun-12 m:audit_penetration_rate_fytd_monthly=6.5 m:of_business_tax_renewal_from_web_sources_annual_fy=62 m:of_lien_cases_resolved_fytd_monthly=65
```

## Meta Commands

```ls
metric m:audit_penetration_rate_fytd_monthly p:float l:"Audit penetration Rate FYTD (Monthly)" t:dataTypeName=percent

metric m:target_audit_penetration_rate_fytd_monthly p:float l:"TARGET: Audit Penetration Rate FYTD (Monthly)" t:dataTypeName=percent

metric m:of_lien_cases_resolved_fytd_monthly p:float l:"% of lien cases resolved FYTD (Monthly)" t:dataTypeName=percent

metric m:target_of_lien_cases_resolved_fytd_monthly p:float l:"TARGET: % of lien cases resolved FYTD (Monthly)" t:dataTypeName=percent

metric m:of_call_center_calls_answered_monthly_2 p:float l:"# of call center calls answered (Monthly)" t:dataTypeName=number

metric m:yoy_benchmark_of_call_center_calls_answered_monthly_2 p:float l:"YOY BENCHMARK: # of call center calls answered (Monthly)" t:dataTypeName=number

metric m:of_call_center_calls_answered_monthly p:float l:"% of call center calls answered (Monthly)" t:dataTypeName=percent

metric m:yoy_benchmark_of_call_center_calls_answered_monthly p:float l:"YOY BENCHMARK: % of call center calls answered (Monthly)" t:dataTypeName=percent

metric m:of_business_tax_renewal_from_web_sources_annual_fy p:float l:"% of Business Tax renewal from web sources (Annual FY)" t:dataTypeName=percent

metric m:target_of_business_tax_renewal_from_web_sources_annual_fy p:float l:"TARGET: % of Business Tax renewal from web sources (Annual FY)" t:dataTypeName=percent

entity e:7y6s-y8bd l:"Finance - Performance Metrics" t:attribution="Office of Finance" t:url=https://data.lacity.org/api/views/7y6s-y8bd

property e:7y6s-y8bd t:meta.view v:id=7y6s-y8bd v:category="A Well Run City" v:averageRating=0 v:name="Finance - Performance Metrics" v:attribution="Office of Finance"

property e:7y6s-y8bd t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:7y6s-y8bd t:meta.view.owner v:id=c255-4shb v:profileImageUrlMedium=/api/users/c255-4shb/profile_images/THUMB v:profileImageUrlLarge=/api/users/c255-4shb/profile_images/LARGE v:screenName="Office of Finance OpenData" v:profileImageUrlSmall=/api/users/c255-4shb/profile_images/TINY v:displayName="Office of Finance OpenData"

property e:7y6s-y8bd t:meta.view.tableauthor v:id=c255-4shb v:profileImageUrlMedium=/api/users/c255-4shb/profile_images/THUMB v:profileImageUrlLarge=/api/users/c255-4shb/profile_images/LARGE v:screenName="Office of Finance OpenData" v:profileImageUrlSmall=/api/users/c255-4shb/profile_images/TINY v:roleName=publisher v:displayName="Office of Finance OpenData"
```

## Top Records

```ls
| date                | month_year | quarter_fy | annual_fy | audit_penetration_rate_fytd_monthly | target_audit_penetration_rate_fytd_monthly | of_lien_cases_resolved_fytd_monthly | target_of_lien_cases_resolved_fytd_monthly | of_call_center_calls_answered_monthly_2 | yoy_benchmark_of_call_center_calls_answered_monthly_2 | of_call_center_calls_answered_monthly | yoy_benchmark_of_call_center_calls_answered_monthly | monthly_investment_report_finding_on_compliance_monthly | target_monthly_investment_report_finding_on_compliance_monthly | of_business_tax_renewal_from_web_sources_annual_fy | target_of_business_tax_renewal_from_web_sources_annual_fy | milestones_paperless_program_project | target_paperless_program | status_paperless_program | milestones_customer_satisfaction_survey_project | target_customer_satisfaction_survey | status_customer_satisfaction_survey | 
| =================== | ========== | ========== | ========= | =================================== | ========================================== | =================================== | ========================================== | ======================================= | ===================================================== | ===================================== | =================================================== | ======================================================= | ============================================================== | ================================================== | ========================================================= | ==================================== | ======================== | ======================== | =============================================== | =================================== | =================================== | 
| 2010-06-30T00:00:00 | Jun-10     | QF FY10    | FY 2010   |                                     |                                            |                                     |                                            |                                         |                                                       |                                       |                                                     |                                                         |                                                                | 47.00                                              |                                                           |                                      |                          |                          |                                                 |                                     |                                     | 
| 2011-06-30T00:00:00 | Jun-11     | Q4 FY11    | FY 2011   |                                     |                                            |                                     |                                            |                                         |                                                       |                                       |                                                     |                                                         |                                                                | 58.00                                              |                                                           |                                      |                          |                          |                                                 |                                     |                                     | 
| 2012-06-30T00:00:00 | Jun-12     | Q4 FY12    | FY 2012   | 6.50                                |                                            | 65.00                               |                                            |                                         |                                                       |                                       |                                                     |                                                         |                                                                | 62.00                                              |                                                           |                                      |                          |                          |                                                 |                                     |                                     | 
| 2012-07-31T00:00:00 | Jul-12     |            |           |                                     |                                            |                                     |                                            |                                         |                                                       | 100.00                                |                                                     |                                                         |                                                                |                                                    |                                                           |                                      |                          |                          |                                                 |                                     |                                     | 
| 2012-08-31T00:00:00 | Aug-12     |            |           |                                     |                                            |                                     |                                            |                                         |                                                       | 100.00                                |                                                     |                                                         |                                                                |                                                    |                                                           |                                      |                          |                          |                                                 |                                     |                                     | 
| 2012-09-30T00:00:00 | Sep-12     | Q1 FY13    |           |                                     |                                            |                                     |                                            |                                         |                                                       | 100.00                                |                                                     |                                                         |                                                                |                                                    |                                                           |                                      |                          |                          |                                                 |                                     |                                     | 
| 2012-10-31T00:00:00 | Oct-12     |            |           |                                     |                                            |                                     |                                            |                                         |                                                       | 100.00                                |                                                     |                                                         |                                                                |                                                    |                                                           |                                      |                          |                          |                                                 |                                     |                                     | 
| 2012-11-30T00:00:00 | Nov-12     |            |           |                                     |                                            |                                     |                                            |                                         |                                                       | 98.00                                 |                                                     |                                                         |                                                                |                                                    |                                                           |                                      |                          |                          |                                                 |                                     |                                     | 
| 2012-12-31T00:00:00 | Dec-12     | Q2 FY13    |           |                                     |                                            |                                     |                                            |                                         |                                                       | 100.00                                |                                                     |                                                         |                                                                |                                                    |                                                           |                                      |                          |                          |                                                 |                                     |                                     | 
| 2013-01-31T00:00:00 | Jan-13     |            |           |                                     |                                            |                                     |                                            | 13498.00                                |                                                       | 76.00                                 |                                                     |                                                         |                                                                |                                                    |                                                           |                                      |                          |                          |                                                 |                                     |                                     | 
```