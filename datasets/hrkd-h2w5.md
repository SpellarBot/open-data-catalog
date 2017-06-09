# Part III - Compiled EZ Assessor Reports Reporting Years 2015-2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/part-iii-compiled-ez-assessor-reports-reporting-years-2015-2016) |
| Metadata | [Link](https://data.oregon.gov/api/views/hrkd-h2w5) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/hrkd-h2w5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/hrkd-h2w5/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | hrkd-h2w5 |
| Name | Part III - Compiled EZ Assessor Reports Reporting Years 2015-2016 |
| Tags | enterprise zones; assessor reports; enterprise zones composite assessor reports; 2015; 2016 |
| Created | 2016-11-25T01:40:50Z |
| Publication Date | 2016-11-25T01:45:38Z |

## Description

This composite report "Part III. Recent Investments Expected to Begin Exemption - Next Property Tax Year" includes data from all Enterprise Zone County Assessor Reports for both 2015 and 2016, and is Part III of a three (3) part report. For more information: http://www.oregon.gov/transparency/Pages/TaxExpenditures.aspx.

## Columns

```ls
| Included | Schema Type    | Field Name                                                              | Name                                                                     | Data Type | Render Type |
| ======== | ============== | ======================================================================= | ======================================================================== | ========= | =========== |
| Yes      | time           | reporting_year                                                          | Reporting Year                                                           | number    | number      |
| Yes      | series tag     | property_tax_year                                                       | Property Tax Year                                                        | text      | text        |
| Yes      | series tag     | county                                                                  | County                                                                   | text      | text        |
| Yes      | series tag     | enterprise_zone                                                         | Enterprise Zone                                                          | text      | text        |
| Yes      | series tag     | name_of_qualified_firm                                                  | Name of Qualified Firm                                                   | text      | text        |
| Yes      | numeric metric | expected_total_years_of_exemption_3_4_or_5                              | Expected Total Years of Exemption(3, 4 or 5)                             | number    | number      |
| Yes      | numeric metric | preexisting_zone_employment_annual_average_in_authorization_application | Preexisting Zone Employment(annual average in authorization application) | number    | number      |
| Yes      | numeric metric | reported_total_zone_employment_on_or_before_april_1_of_reporting_year   | Reported Total Zone Employment on or before April 1 of Reporting Year    | number    | number      |
| Yes      | series tag     | tax_code_area                                                           | Tax Code Area                                                            | text      | text        |
| Yes      | series tag     | notes                                                                   | Notes                                                                    | text      | text        |
```

## Time Field

```ls
Value = reporting_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:hrkd-h2w5 d:2016-01-01T00:00:00.000Z t:tax_code_area=501 t:county=Baker t:name_of_qualified_firm="Natural Structures" t:property_tax_year=2015-2016 t:enterprise_zone="Baker County" m:preexisting_zone_employment_annual_average_in_authorization_application=5 m:reported_total_zone_employment_on_or_before_april_1_of_reporting_year=49 m:expected_total_years_of_exemption_3_4_or_5=3

series e:hrkd-h2w5 d:2016-01-01T00:00:00.000Z t:tax_code_area=501 t:county=Baker t:name_of_qualified_firm="Glacier 45 LLC" t:property_tax_year=2015-2016 t:enterprise_zone="Baker County" m:preexisting_zone_employment_annual_average_in_authorization_application=1 m:reported_total_zone_employment_on_or_before_april_1_of_reporting_year=0 m:expected_total_years_of_exemption_3_4_or_5=3

series e:hrkd-h2w5 d:2016-01-01T00:00:00.000Z t:tax_code_area=501 t:county=Baker t:name_of_qualified_firm="Hop Heaven Inc" t:property_tax_year=2015-2016 t:enterprise_zone="Baker County" m:preexisting_zone_employment_annual_average_in_authorization_application=2 m:reported_total_zone_employment_on_or_before_april_1_of_reporting_year=0 m:expected_total_years_of_exemption_3_4_or_5=3
```

## Meta Commands

```ls
metric m:expected_total_years_of_exemption_3_4_or_5 p:integer l:"Expected Total Years of Exemption(3, 4 or 5)" t:dataTypeName=number

metric m:preexisting_zone_employment_annual_average_in_authorization_application p:integer l:"Preexisting Zone Employment(annual average in authorization application)" t:dataTypeName=number

metric m:reported_total_zone_employment_on_or_before_april_1_of_reporting_year p:integer l:"Reported Total Zone Employment on or before April 1 of Reporting Year" t:dataTypeName=number

entity e:hrkd-h2w5 l:"Part III - Compiled EZ Assessor Reports Reporting Years 2015-2016" t:url=https://data.oregon.gov/api/views/hrkd-h2w5

property e:hrkd-h2w5 t:meta.view d:2017-06-09T13:55:43.371Z v:id=hrkd-h2w5 v:averageRating=0 v:name="Part III - Compiled EZ Assessor Reports Reporting Years 2015-2016"

property e:hrkd-h2w5 t:meta.view.owner d:2017-06-09T13:55:43.371Z v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1495038840 v:displayName="Paula N."

property e:hrkd-h2w5 t:meta.view.tableauthor d:2017-06-09T13:55:43.371Z v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1495038840 v:displayName="Paula N."
```

## Top Records

```ls
| reporting_year | property_tax_year | county    | enterprise_zone       | name_of_qualified_firm                     | expected_total_years_of_exemption_3_4_or_5 | preexisting_zone_employment_annual_average_in_authorization_application | reported_total_zone_employment_on_or_before_april_1_of_reporting_year | tax_code_area | notes | 
| ============== | ================= | ========= | ===================== | ========================================== | ========================================== | ======================================================================= | ===================================================================== | ============= | ===== | 
| 2016           | 2015-2016         | Baker     | Baker County          | Natural Structures                         | 3                                          | 5                                                                       | 49                                                                    | 501           |       | 
| 2016           | 2015-2016         | Baker     | Baker County          | Glacier 45 LLC                             | 3                                          | 1                                                                       | 0                                                                     | 501           |       | 
| 2016           | 2015-2016         | Baker     | Baker County          | Hop Heaven Inc                             | 3                                          | 2                                                                       | 0                                                                     | 501           |       | 
| 2016           | 2015-2016         | Benton    | Corvallis/Benton      | Forbidden Fruit Ciderhouse LLC             | 3                                          | 0                                                                       | 10                                                                    | 905           |       | 
| 2016           | 2015-2016         | Benton    | Corvallis/Benton      | Block 15 Brewing Company                   | 3                                          | 1                                                                       | 3                                                                     | 905           |       | 
| 2016           | 2015-2016         | Clackamas | Estacada              |                                            |                                            |                                                                         |                                                                       |               |       | 
| 2016           | 2015-2016         | Clackamas | Molalla               | Pacific Fibre Products                     | 5                                          | 0                                                                       | 7                                                                     | 035-002       |       | 
| 2016           | 2015-2016         | Clackamas | Oregon City           |                                            |                                            |                                                                         |                                                                       |               |       | 
| 2016           | 2015-2016         | Clackamas | North Urban Clackamas | Boydstun Equipment Manufacturing - Herbert | 3                                          | 0                                                                       | 24                                                                    | 012-051       |       | 
| 2016           | 2015-2016         | Clackamas | North Urban Clackamas | General Sheet Metal                        | 5                                          | 85                                                                      | 98                                                                    | 012-051       |       | 
```