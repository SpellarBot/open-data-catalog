# Part II - Compiled EZ Assessor Reports - Reporting Years 2015-2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/part-ii-compiled-ez-assessor-reports-reporting-years-2015-2016) |
| Metadata | [Link](https://data.oregon.gov/api/views/stw7-n6cr) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/stw7-n6cr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/stw7-n6cr/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | stw7-n6cr |
| Name | Part II - Compiled EZ Assessor Reports - Reporting Years 2015-2016 |
| Tags | enterprise zones; assessor reports; enterprise zones composite assessor reports; 2015; 2016 |
| Created | 2016-11-25T01:15:19Z |
| Publication Date | 2016-11-25T01:32:14Z |

## Description

This composite report "Part II. Exemptions Concluding in the Current Property Tax Year" includes data from all Enterprise Zone County Assessor Reports for both 2015 and 2016, and is Part II of a three (3) part report. For more information: http://www.oregon.gov/transparency/Pages/TaxExpenditures.aspx.

## Columns

```ls
| Included | Schema Type    | Field Name                                                                                                   | Name                                                                                                              | Data Type | Render Type |
| ======== | ============== | ============================================================================================================ | ================================================================================================================= | ========= | =========== |
| Yes      | time           | reporting_year                                                                                               | Reporting Year                                                                                                    | number    | number      |
| Yes      | series tag     | property_tax_year                                                                                            | Property Tax Year                                                                                                 | text      | text        |
| Yes      | series tag     | county                                                                                                       | County                                                                                                            | text      | text        |
| Yes      | series tag     | enterprise_zone                                                                                              | Enterprise Zone                                                                                                   | text      | text        |
| Yes      | series tag     | name_of_qualified_firm                                                                                       | Name of Qualified Firm                                                                                            | text      | text        |
| Yes      | numeric metric | total_years_of_exemption                                                                                     | Total Years of Exemption                                                                                          | number    | number      |
| Yes      | numeric metric | first_year_claim_filed                                                                                       | First Year Claim Filed                                                                                            | number    | number      |
| Yes      | series tag     | tax_code_area                                                                                                | Tax code Area                                                                                                     | text      | text        |
| Yes      | numeric metric | preexisting_zone_employment_annual_average_in_authorization_application                                      | Preexisting Zone Employment(annual average in authorization application)                                          | number    | number      |
| Yes      | numeric metric | zone_employment_annual_average_reported_for_the_previous_calendar_year                                       | Zone Employment (annual average - reported for the previous calendar year)                                        | number    | number      |
| Yes      | numeric metric | estimated_assessed_value_of_newly_non_exempt_property_in_the_next_property_tax_year                          | Estimated Assessed Value of Newly Non-Exempt Property in the Next Property Tax Year ($)                           | money     | money       |
| Yes      | numeric metric | estimated_new_non_exempt_taxes_next_property_tax_year                                                        | Estimated New Non-Exempt Taxes Next Property Tax Year ($)                                                         | money     | money       |
| Yes      | numeric metric | estimated_total_assessed_value_of_newly_non_exempt_property_in_enterprise_zone_in_the_next_property_tax_year | Estimated TOTAL Assessed Value of Newly Non-Exempt Property in Enterprise Zone in the Next Property Tax Year ($)  | money     | money       |
| Yes      | series tag     | notes                                                                                                        | Notes                                                                                                             | text      | text        |
```

## Time Field

```ls
Value = reporting_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:stw7-n6cr d:2016-01-01T00:00:00.000Z t:county=Clackamas t:property_tax_year=2015-2016 t:name_of_qualified_firm="Northwest Innovators" t:enterprise_zone=Estacada m:estimated_assessed_value_of_newly_non_exempt_property_in_the_next_property_tax_year=1430230

series e:stw7-n6cr d:2016-01-01T00:00:00.000Z t:county=Clackamas t:property_tax_year=2015-2016 t:name_of_qualified_firm="Alpine Food Distributing Inc - 2011 Auth" t:enterprise_zone="North Urban Clackamas" m:estimated_assessed_value_of_newly_non_exempt_property_in_the_next_property_tax_year=9635814

series e:stw7-n6cr d:2016-01-01T00:00:00.000Z t:county=Clackamas t:property_tax_year=2015-2016 t:name_of_qualified_firm="Northwest Innovaters" t:enterprise_zone="North Urban Clackamas" m:estimated_assessed_value_of_newly_non_exempt_property_in_the_next_property_tax_year=150526
```

## Meta Commands

```ls
metric m:total_years_of_exemption p:integer l:"Total Years of Exemption" t:dataTypeName=number

metric m:first_year_claim_filed p:integer l:"First Year Claim Filed" t:dataTypeName=number

metric m:preexisting_zone_employment_annual_average_in_authorization_application p:integer l:"Preexisting Zone Employment(annual average in authorization application)" t:dataTypeName=number

metric m:zone_employment_annual_average_reported_for_the_previous_calendar_year p:integer l:"Zone Employment (annual average - reported for the previous calendar year)" t:dataTypeName=number

metric m:estimated_assessed_value_of_newly_non_exempt_property_in_the_next_property_tax_year p:integer l:"Estimated Assessed Value of Newly Non-Exempt Property in the Next Property Tax Year ($)" t:dataTypeName=money

metric m:estimated_new_non_exempt_taxes_next_property_tax_year p:double l:"Estimated New Non-Exempt Taxes Next Property Tax Year ($)" t:dataTypeName=money

metric m:estimated_total_assessed_value_of_newly_non_exempt_property_in_enterprise_zone_in_the_next_property_tax_year p:integer l:"Estimated TOTAL Assessed Value of Newly Non-Exempt Property in Enterprise Zone in the Next Property Tax Year ($)" t:dataTypeName=money

entity e:stw7-n6cr l:"Part II - Compiled EZ Assessor Reports - Reporting Years 2015-2016" t:url=https://data.oregon.gov/api/views/stw7-n6cr

property e:stw7-n6cr t:meta.view v:id=stw7-n6cr v:averageRating=0 v:name="Part II - Compiled EZ Assessor Reports - Reporting Years 2015-2016"

property e:stw7-n6cr t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:stw7-n6cr t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| reporting_year | property_tax_year | county    | enterprise_zone         | name_of_qualified_firm                   | total_years_of_exemption | first_year_claim_filed | tax_code_area | preexisting_zone_employment_annual_average_in_authorization_application | zone_employment_annual_average_reported_for_the_previous_calendar_year | estimated_assessed_value_of_newly_non_exempt_property_in_the_next_property_tax_year | estimated_new_non_exempt_taxes_next_property_tax_year | estimated_total_assessed_value_of_newly_non_exempt_property_in_enterprise_zone_in_the_next_property_tax_year | notes                                           | 
| ============== | ================= | ========= | ======================= | ======================================== | ======================== | ====================== | ============= | ======================================================================= | ====================================================================== | =================================================================================== | ===================================================== | ============================================================================================================ | =============================================== | 
| 2016           | 2015-2016         | Baker     | Baker County            |                                          |                          |                        |               |                                                                         |                                                                        |                                                                                     |                                                       |                                                                                                              |                                                 | 
| 2016           | 2015-2016         | Benton    | Corvallis/Benton        |                                          |                          |                        |               |                                                                         |                                                                        |                                                                                     |                                                       |                                                                                                              |                                                 | 
| 2016           | 2015-2016         | Clackamas | Estacada                | Northwest Innovators                     |                          |                        |               |                                                                         |                                                                        | 1430230                                                                             |                                                       |                                                                                                              |                                                 | 
| 2016           | 2015-2016         | Clackamas | Molalla                 |                                          |                          |                        |               |                                                                         |                                                                        |                                                                                     |                                                       |                                                                                                              |                                                 | 
| 2016           | 2015-2016         | Clackamas | Oregon City             |                                          |                          |                        |               |                                                                         |                                                                        |                                                                                     |                                                       |                                                                                                              |                                                 | 
| 2016           | 2015-2016         | Clackamas | North Urban Clackamas   | Alpine Food Distributing Inc - 2011 Auth |                          |                        |               |                                                                         |                                                                        | 9635814                                                                             |                                                       |                                                                                                              |                                                 | 
| 2016           | 2015-2016         | Clackamas | North Urban Clackamas   | Northwest Innovaters                     |                          |                        |               |                                                                         |                                                                        | 150526                                                                              |                                                       |                                                                                                              |                                                 | 
| 2016           | 2015-2016         | Clackamas | North Urban Clackamas   | United Streetcar                         |                          |                        |               |                                                                         |                                                                        | 5577076                                                                             |                                                       |                                                                                                              | Disqualified for 2016 due to loss of employment | 
| 2016           | 2015-2016         | Clackamas | Sandy                   |                                          |                          |                        |               |                                                                         |                                                                        |                                                                                     |                                                       |                                                                                                              |                                                 | 
| 2016           | 2015-2016         | Columbia  | Lower Columbia Maritime |                                          |                          |                        |               |                                                                         |                                                                        |                                                                                     |                                                       | 2500000                                                                                                      |                                                 | 
```