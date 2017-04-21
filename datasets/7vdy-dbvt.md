# Part I - Compiled EZ Assessor Reports - Reporting Years 2015-2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/part-i-compiled-ez-assessor-reports-reporting-years-2015-2016) |
| Metadata | [Link](https://data.oregon.gov/api/views/7vdy-dbvt) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/7vdy-dbvt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/7vdy-dbvt/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 7vdy-dbvt |
| Name | Part I - Compiled EZ Assessor Reports - Reporting Years 2015-2016 |
| Tags | enterprise zones; assessor reports; 2015; 2016 |
| Created | 2016-11-25T00:26:35Z |
| Publication Date | 2016-11-25T01:04:33Z |

## Description

This composite report "Part I. Exemptions on Qualified Property during the Current Property Tax Year" includes data from all Enterprise Zone County Assessor Reports for both 2015 and 2016, and is Part I of a three (3) part report. For more information: http://www.oregon.gov/transparency/Pages/TaxExpenditures.aspx.

## Columns

```ls
| Included | Schema Type    | Field Name                                                              | Name                                                                       | Data Type | Render Type |
| ======== | ============== | ======================================================================= | ========================================================================== | ========= | =========== |
| Yes      | time           | reporting_year                                                          | Reporting Year                                                             | number    | number      |
| Yes      | series tag     | property_tax_year                                                       | Property Tax Year                                                          | text      | text        |
| Yes      | series tag     | county                                                                  | County                                                                     | text      | text        |
| Yes      | series tag     | enterprise_zone                                                         | Enterprise Zone                                                            | text      | text        |
| Yes      | series tag     | name_of_qualified_firm                                                  | Name of Qualified Firm                                                     | text      | text        |
| Yes      | numeric metric | total_years_of_exemption_2_3_4_or_5                                     | Total Years of Exemption (2, 3, 4 or 5)                                    | number    | number      |
| Yes      | numeric metric | first_year_claim_filed                                                  | First Year Claim Filed                                                     | number    | number      |
| Yes      | numeric metric | assessed_value_of_exempt_property                                       | Assessed Value of Exempt Property ($)                                      | money     | money       |
| Yes      | series tag     | tax_code_area                                                           | Tax Code Area                                                              | text      | text        |
| Yes      | numeric metric | taxes_exempt                                                            | Taxes Exempt ($)                                                           | money     | money       |
| Yes      | numeric metric | preexisting_zone_employment_annual_average_in_authorization_application | Preexisting Zone Employment(annual average in authorization application)   | number    | number      |
| Yes      | numeric metric | zone_employment_annual_average_reported_for_the_previous_calendar_year  | Zone Employment (annual average - reported for the previous calendar year) | number    | number      |
| Yes      | series tag     | notes                                                                   | Notes                                                                      | text      | text        |
```

## Time Field

```ls
Value = reporting_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:7vdy-dbvt d:2016-01-01T00:00:00.000Z t:tax_code_area=501 t:county=Baker t:property_tax_year=2015-2016 t:name_of_qualified_firm="Windmill Enterprises DBA Baker City Brewing" t:enterprise_zone="Baker County" m:preexisting_zone_employment_annual_average_in_authorization_application=0 m:total_years_of_exemption_2_3_4_or_5=3 m:assessed_value_of_exempt_property=352540 m:taxes_exempt=5288 m:first_year_claim_filed=2014 m:zone_employment_annual_average_reported_for_the_previous_calendar_year=3

series e:7vdy-dbvt d:2016-01-01T00:00:00.000Z t:tax_code_area=905 t:county=Benton t:property_tax_year=2015-2016 t:name_of_qualified_firm="T Gerding Construction Co" t:enterprise_zone=Corvallis/Benton m:preexisting_zone_employment_annual_average_in_authorization_application=8 m:total_years_of_exemption_2_3_4_or_5=5 m:assessed_value_of_exempt_property=814948 m:taxes_exempt=11682 m:first_year_claim_filed=2010 m:zone_employment_annual_average_reported_for_the_previous_calendar_year=16

series e:7vdy-dbvt d:2016-01-01T00:00:00.000Z t:tax_code_area=901 t:county=Benton t:property_tax_year=2015-2016 t:name_of_qualified_firm=Nuscale t:enterprise_zone=Corvallis/Benton m:preexisting_zone_employment_annual_average_in_authorization_application=70 m:total_years_of_exemption_2_3_4_or_5=3 m:assessed_value_of_exempt_property=882968 m:taxes_exempt=16252 m:first_year_claim_filed=2013 m:zone_employment_annual_average_reported_for_the_previous_calendar_year=175
```

## Meta Commands

```ls
metric m:total_years_of_exemption_2_3_4_or_5 p:integer l:"Total Years of Exemption (2, 3, 4 or 5)" t:dataTypeName=number

metric m:first_year_claim_filed p:integer l:"First Year Claim Filed" t:dataTypeName=number

metric m:assessed_value_of_exempt_property p:integer l:"Assessed Value of Exempt Property ($)" t:dataTypeName=money

metric m:taxes_exempt p:double l:"Taxes Exempt ($)" t:dataTypeName=money

metric m:preexisting_zone_employment_annual_average_in_authorization_application p:integer l:"Preexisting Zone Employment(annual average in authorization application)" t:dataTypeName=number

metric m:zone_employment_annual_average_reported_for_the_previous_calendar_year p:integer l:"Zone Employment (annual average - reported for the previous calendar year)" t:dataTypeName=number

entity e:7vdy-dbvt l:"Part I - Compiled EZ Assessor Reports - Reporting Years 2015-2016" t:url=https://data.oregon.gov/api/views/7vdy-dbvt

property e:7vdy-dbvt t:meta.view v:id=7vdy-dbvt v:averageRating=0 v:name="Part I - Compiled EZ Assessor Reports - Reporting Years 2015-2016"

property e:7vdy-dbvt t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:7vdy-dbvt t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| reporting_year | property_tax_year | county    | enterprise_zone       | name_of_qualified_firm                      | total_years_of_exemption_2_3_4_or_5 | first_year_claim_filed | assessed_value_of_exempt_property | tax_code_area | taxes_exempt | preexisting_zone_employment_annual_average_in_authorization_application | zone_employment_annual_average_reported_for_the_previous_calendar_year | notes | 
| ============== | ================= | ========= | ===================== | =========================================== | =================================== | ====================== | ================================= | ============= | ============ | ======================================================================= | ====================================================================== | ===== | 
| 2016           | 2015-2016         | Baker     | Baker County          | Windmill Enterprises DBA Baker City Brewing | 3                                   | 2014                   | 352540                            | 501           | 5288         | 0                                                                       | 3                                                                      |       | 
| 2016           | 2015-2016         | Benton    | Corvallis/Benton      | T Gerding Construction Co                   | 5                                   | 2010                   | 814948                            | 905           | 11682        | 8                                                                       | 16                                                                     |       | 
| 2016           | 2015-2016         | Benton    | Corvallis/Benton      | Nuscale                                     | 3                                   | 2013                   | 882968                            | 901           | 16252        | 70                                                                      | 175                                                                    |       | 
| 2016           | 2015-2016         | Benton    | Corvallis/Benton      | Perpetua Power Source Technologies Inc      | 3                                   | 2014                   | 105120                            | 905           | 1507         | 14                                                                      | 14                                                                     |       | 
| 2016           | 2015-2016         | Clackamas | Estacada              | Northwest Technologies Inc - 2010 Auth      | 3                                   | 2011                   | 797260                            | 708-002       | 12850        | 47                                                                      | 80                                                                     |       | 
| 2016           | 2015-2016         | Clackamas | Estacada              | North west Techologies Inc - 2013 Auth      | 3                                   | 2014                   | 748410                            | 108-002       | 12062        | 71                                                                      | 78                                                                     |       | 
| 2016           | 2015-2016         | Clackamas | Molalla               |                                             |                                     |                        |                                   |               |              |                                                                         |                                                                        |       | 
| 2016           | 2015-2016         | Clackamas | Oregon City           |                                             |                                     |                        |                                   |               |              |                                                                         |                                                                        |       | 
| 2016           | 2015-2016         | Clackamas | North Urban Clackamas | Alpine Food Distributing Inc - 2011 Auth    | 3                                   | 2012                   | 10749991                          | 012-002       | 203130       | 0                                                                       | 128                                                                    |       | 
| 2016           | 2015-2016         | Clackamas | North Urban Clackamas | Alpine Food Distributing Inc - 2014 Auth    | 3                                   | 2015                   | 1051344                           | 012-002       | 20301        | 95                                                                      | 117                                                                    |       | 
```