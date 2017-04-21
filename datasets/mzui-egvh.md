# Residential Energy Tax Credit Program: Fiscal Year 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/residential-energy-tax-credit-program-fiscal-year-2013-7e83d) |
| Metadata | [Link](https://data.oregon.gov/api/views/mzui-egvh) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/mzui-egvh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/mzui-egvh/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | mzui-egvh |
| Name | Residential Energy Tax Credit Program: Fiscal Year 2013 |
| Category | Revenue & Expense |
| Tags | residential energy tax credit program, residential energy, residential tax credit, energy credit program, energy program |
| Created | 2013-11-07T17:25:02Z |
| Publication Date | 2015-12-27T22:37:17Z |

## Description

For more information go to: http://www.oregon.gov/transparency/Pages/Tax-Expenditures.aspx#Energy_Related_-_Tax_Expenditures_

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type     | Render Type   |
| ======== | ============== | ============================== | ============================== | ============= | ============= |
| Yes      | series tag     | agency_issuing_tax_expenditure | Agency Issuing Tax Expenditure | text          | text          |
| No       |                | final_year                     | Final Year                     | number        | number        |
| Yes      | time           | final_date                     | Final Date                     | calendar_date | calendar_date |
| Yes      | series tag     | applicant_name                 | Applicant Name                 | text          | text          |
| Yes      | series tag     | site_city                      | Site City                      | text          | text          |
| Yes      | series tag     | site_zip                       | Site Zip                       | text          | number        |
| Yes      | series tag     | site_county                    | Site County                    | text          | text          |
| Yes      | series tag     | system                         | System                         | text          | text          |
| Yes      | numeric metric | final_certified_project_cost   | Final Certified Project Cost   | number        | number        |
| Yes      | numeric metric | tax_credit                     | Tax Credit                     | number        | number        |
| Yes      | numeric metric | percentage                     | Percentage                     | number        | number        |
| Yes      | numeric metric | net_tax_credit                 | Net Tax Credit                 | number        | number        |
| Yes      | numeric metric | total_energy_mmbtu             | Total Energy (MMBtu)           | number        | number        |
| Yes      | numeric metric | units_capacity                 | UNITS CAPACITY                 | number        | number        |
| Yes      | series tag     | units_name                     | UNITS NAME                     | text          | text          |
| Yes      | series tag     | application                    | Application #                  | text          | number        |
```

## Time Field

```ls
Value = final_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = final_year
```

## Data Commands

```ls
series e:mzui-egvh d:2013-06-05T00:00:00.000Z t:site_city=Tigard t:system=Photovoltaic t:application=781693 t:site_zip=97224 t:site_county=Wash t:agency_issuing_tax_expenditure="Oregon Department of Energy" t:units_name=watts t:applicant_name="Werner Knebel" m:final_certified_project_cost=11565 m:percentage=100 m:tax_credit=5733 m:total_energy_mmbtu=9.04 m:units_capacity=2688 m:net_tax_credit=5733

series e:mzui-egvh d:2013-04-15T00:00:00.000Z t:site_city=Portland t:system=Photovoltaic t:application=813750 t:site_zip=97214 t:site_county=Mult t:agency_issuing_tax_expenditure="Oregon Department of Energy" t:units_name=watts t:applicant_name="Allen Poole and Brita Johnson" m:final_certified_project_cost=16848 m:percentage=100 m:tax_credit=6000 m:total_energy_mmbtu=9.04 m:units_capacity=3240 m:net_tax_credit=6000

series e:mzui-egvh d:2012-08-03T00:00:00.000Z t:site_city=Albany t:system=Photovoltaic t:application=813754 t:site_zip=97321 t:site_county=Bent t:agency_issuing_tax_expenditure="Oregon Department of Energy" t:units_name=watts t:applicant_name="William John Kinkley" m:final_certified_project_cost=15633 m:percentage=100 m:tax_credit=6000 m:total_energy_mmbtu=9.04 m:units_capacity=3220 m:net_tax_credit=6000
```

## Meta Commands

```ls
metric m:final_certified_project_cost p:integer l:"Final Certified Project Cost" t:dataTypeName=number

metric m:tax_credit p:integer l:"Tax Credit" t:dataTypeName=number

metric m:percentage p:integer l:Percentage t:dataTypeName=number

metric m:net_tax_credit p:integer l:"Net Tax Credit" t:dataTypeName=number

metric m:total_energy_mmbtu p:float l:"Total Energy (MMBtu)" t:dataTypeName=number

metric m:units_capacity p:integer l:"UNITS CAPACITY" t:dataTypeName=number

entity e:mzui-egvh l:"Residential Energy Tax Credit Program: Fiscal Year 2013" t:url=https://data.oregon.gov/api/views/mzui-egvh

property e:mzui-egvh t:meta.view v:id=mzui-egvh v:category="Revenue & Expense" v:averageRating=0 v:name="Residential Energy Tax Credit Program: Fiscal Year 2013"

property e:mzui-egvh t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:mzui-egvh t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| agency_issuing_tax_expenditure | final_year | final_date          | applicant_name                | site_city   | site_zip | site_county | system       | final_certified_project_cost | tax_credit | percentage | net_tax_credit | total_energy_mmbtu | units_capacity | units_name | application | 
| ============================== | ========== | =================== | ============================= | =========== | ======== | =========== | ============ | ============================ | ========== | ========== | ============== | ================== | ============== | ========== | =========== | 
| Oregon Department of Energy    | 2013       | 2013-06-05T00:00:00 | Werner Knebel                 | Tigard      | 97224    | Wash        | Photovoltaic | 11565                        | 5733       | 100        | 5733           | 9.04               | 2688           | watts      | 781693      | 
| Oregon Department of Energy    | 2013       | 2013-04-15T00:00:00 | Allen Poole and Brita Johnson | Portland    | 97214    | Mult        | Photovoltaic | 16848                        | 6000       | 100        | 6000           | 9.04               | 3240           | watts      | 813750      | 
| Oregon Department of Energy    | 2012       | 2012-08-03T00:00:00 | William John Kinkley          | Albany      | 97321    | Bent        | Photovoltaic | 15633                        | 6000       | 100        | 6000           | 9.04               | 3220           | watts      | 813754      | 
| Oregon Department of Energy    | 2012       | 2012-12-07T00:00:00 | Alan Conner                   | Bend        | 97702    | Desc        | Photovoltaic | 15956                        | 6000       | 100        | 6000           | 9.04               | 3290           | watts      | 813755      | 
| Oregon Department of Energy    | 2012       | 2012-08-29T00:00:00 | Chris Barlow                  | Bend        | 97701    | Desc        | Photovoltaic | 15132                        | 6000       | 100        | 6000           | 9.04               | 3120           | watts      | 813756      | 
| Oregon Department of Energy    | 2013       | 2013-01-24T00:00:00 | Mike Pinker                   | Milwaukie   | 97222    | Clac        | Photovoltaic | 17108                        | 6000       | 100        | 6000           | 9.04               | 3290           | watts      | 814575      | 
| Oregon Department of Energy    | 2013       | 2013-03-05T00:00:00 | Scott Walker                  | Silverton   | 97381    | Mari        | Photovoltaic | 26136                        | 6000       | 100        | 6000           | 9.04               | 5940           | watts      | 814576      | 
| Oregon Department of Energy    | 2012       | 2012-09-07T00:00:00 | Robin Cash                    | Portland    | 97213    | Mult        | Photovoltaic | 15956                        | 6000       | 100        | 6000           | 9.04               | 3290           | watts      | 814579      | 
| Oregon Department of Energy    | 2012       | 2012-07-25T00:00:00 | Patti and Paul Jarrett        | Oregon City | 97045    | Clac        | Photovoltaic | 17108                        | 6000       | 100        | 6000           | 9.04               | 3290           | watts      | 814902      | 
| Oregon Department of Energy    | 2012       | 2012-08-23T00:00:00 | Tim Clairmont                 | Beaverton   | 97007    | Wash        | Photovoltaic | 19400                        | 6000       | 100        | 6000           | 9.04               | 4000           | watts      | 814905      | 
```