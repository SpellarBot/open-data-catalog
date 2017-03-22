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
| Rows Updated | 2016-11-25T01:41:16Z |

## Description

This composite report "Part III. Recent Investments Expected to Begin Exemption - Next Property Tax Year" includes data from all Enterprise Zone County Assessor Reports for both 2015 and 2016, and is Part III of a three (3) part report. For more information: http://www.oregon.gov/transparency/Pages/TaxExpenditures.aspx.

## Columns

```ls
| Included | Schema Type    | Field Name                                                              | Name                                                                     | Data Type | Render Type |
| ======== | ============== | ======================================================================= | ======================================================================== | ========= | =========== |
| Yes      | time           | reporting_year                                                          | Reporting Year                                                           | number    | number      |
| No       |                | property_tax_year                                                       | Property Tax Year                                                        | text      | text        |
| Yes      | series tag     | county                                                                  | County                                                                   | text      | text        |
| Yes      | series tag     | enterprise_zone                                                         | Enterprise Zone                                                          | text      | text        |
| Yes      | series tag     | name_of_qualified_firm                                                  | Name of Qualified Firm                                                   | text      | text        |
| Yes      | numeric metric | expected_total_years_of_exemption_3_4_or_5                              | Expected Total Years of Exemption(3, 4 or 5)                             | number    | number      |
| Yes      | numeric metric | preexisting_zone_employment_annual_average_in_authorization_application | Preexisting Zone Employment(annual average in authorization application) | number    | number      |
| No       |                | reported_total_zone_employment_on_or_before_april_1_of_reporting_year   | Reported Total Zone Employment on or before April 1 of Reporting Year    | number    | number      |
| Yes      | series tag     | tax_code_area                                                           | Tax Code Area                                                            | text      | text        |
| Yes      | series tag     | notes                                                                   | Notes                                                                    | text      | text        |
```

## Time Field

```ls
Value = reporting_year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = property_tax_year,reported_total_zone_employment_on_or_before_april_1_of_reporting_year
```

## Data Commands

```ls
series e:hrkd-h2w5 d:2016-01-01T00:00:00.000Z t:tax_code_area=501 t:county=Baker t:name_of_qualified_firm="Natural Structures" t:enterprise_zone="Baker County" m:preexisting_zone_employment_annual_average_in_authorization_application=5 m:expected_total_years_of_exemption_3_4_or_5=3

series e:hrkd-h2w5 d:2016-01-01T00:00:00.000Z t:tax_code_area=501 t:county=Baker t:name_of_qualified_firm="Glacier 45 LLC" t:enterprise_zone="Baker County" m:preexisting_zone_employment_annual_average_in_authorization_application=1 m:expected_total_years_of_exemption_3_4_or_5=3

series e:hrkd-h2w5 d:2016-01-01T00:00:00.000Z t:tax_code_area=501 t:county=Baker t:name_of_qualified_firm="Hop Heaven Inc" t:enterprise_zone="Baker County" m:preexisting_zone_employment_annual_average_in_authorization_application=2 m:expected_total_years_of_exemption_3_4_or_5=3
```

## Meta Commands

```ls
metric m:expected_total_years_of_exemption_3_4_or_5 p:integer l:"Expected Total Years of Exemption(3, 4 or 5)" t:dataTypeName=number

metric m:preexisting_zone_employment_annual_average_in_authorization_application p:integer l:"Preexisting Zone Employment(annual average in authorization application)" t:dataTypeName=number

entity e:hrkd-h2w5 l:"Part III - Compiled EZ Assessor Reports Reporting Years 2015-2016" t:url=https://data.oregon.gov/api/views/hrkd-h2w5

property e:hrkd-h2w5 t:meta.view v:id=hrkd-h2w5 v:averageRating=0 v:name="Part III - Compiled EZ Assessor Reports Reporting Years 2015-2016"

property e:hrkd-h2w5 t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:displayName="Paula N."

property e:hrkd-h2w5 t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:displayName="Paula N."
```