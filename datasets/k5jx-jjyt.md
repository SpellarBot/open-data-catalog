# Residential Energy Tax Credit Program: Fiscal Year 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/residential-energy-tax-credit-program-fiscal-year-2014-a1155) |
| Metadata | [Link](https://data.oregon.gov/api/views/k5jx-jjyt) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/k5jx-jjyt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/k5jx-jjyt/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | k5jx-jjyt |
| Name | Residential Energy Tax Credit Program: Fiscal Year 2014 |
| Category | Revenue & Expense |
| Tags | residential energy tax credit program, residential energy, residential tax credit, energy credit program, energy program, 2014 |
| Created | 2014-12-31T03:44:08Z |
| Publication Date | 2015-12-27T22:35:27Z |

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
| Yes      | numeric metric | final_certified_project_cost   | Final Certified Project Cost   | money         | money         |
| Yes      | numeric metric | tax_credit                     | Tax Credit                     | money         | money         |
| Yes      | numeric metric | percentage                     | Percentage                     | number        | number        |
| Yes      | numeric metric | net_tax_credit                 | Net Tax Credit                 | number        | number        |
| Yes      | numeric metric | total_energy_million_btu       | Total Energy (Million Btu)     | number        | number        |
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
series e:k5jx-jjyt d:2013-07-01T00:00:00.000Z t:site_city=Portland t:system=Photovoltaic t:application=825182 t:site_zip=97229 t:site_county=Wash t:agency_issuing_tax_expenditure="Oregon Department of Energy" t:units_name=watts t:applicant_name="Naren Nayak" m:final_certified_project_cost=21168 m:percentage=100 m:tax_credit=6000 m:total_energy_million_btu=9.04 m:units_capacity=4320 m:net_tax_credit=6000

series e:k5jx-jjyt d:2013-07-01T00:00:00.000Z t:site_city=Corvallis t:system=Photovoltaic t:application=826483 t:site_zip=97333 t:site_county=Bent t:agency_issuing_tax_expenditure="Oregon Department of Energy" t:units_name=watts t:applicant_name="Dave Straub" m:final_certified_project_cost=19208 m:percentage=100 m:tax_credit=6000 m:total_energy_million_btu=9.04 m:units_capacity=3920 m:net_tax_credit=6000

series e:k5jx-jjyt d:2013-07-01T00:00:00.000Z t:site_city=Portland t:system=Photovoltaic t:application=826488 t:site_zip=97229 t:site_county=Wash t:agency_issuing_tax_expenditure="Oregon Department of Energy" t:units_name=watts t:applicant_name="Vijay Gopalswamy" m:final_certified_project_cost=26411 m:percentage=100 m:tax_credit=6000 m:total_energy_million_btu=9.04 m:units_capacity=5390 m:net_tax_credit=6000
```

## Meta Commands

```ls
metric m:final_certified_project_cost p:integer l:"Final Certified Project Cost" t:dataTypeName=money

metric m:tax_credit p:integer l:"Tax Credit" t:dataTypeName=money

metric m:percentage p:integer l:Percentage t:dataTypeName=number

metric m:net_tax_credit p:integer l:"Net Tax Credit" t:dataTypeName=number

metric m:total_energy_million_btu p:float l:"Total Energy (Million Btu)" t:dataTypeName=number

metric m:units_capacity p:integer l:"UNITS CAPACITY" t:dataTypeName=number

entity e:k5jx-jjyt l:"Residential Energy Tax Credit Program: Fiscal Year 2014" t:url=https://data.oregon.gov/api/views/k5jx-jjyt

property e:k5jx-jjyt t:meta.view v:id=k5jx-jjyt v:category="Revenue & Expense" v:averageRating=0 v:name="Residential Energy Tax Credit Program: Fiscal Year 2014"

property e:k5jx-jjyt t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:k5jx-jjyt t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| agency_issuing_tax_expenditure | final_year | final_date          | applicant_name   | site_city    | site_zip | site_county | system       | final_certified_project_cost | tax_credit | percentage | net_tax_credit | total_energy_million_btu | units_capacity | units_name | application | 
| ============================== | ========== | =================== | ================ | ============ | ======== | =========== | ============ | ============================ | ========== | ========== | ============== | ======================== | ============== | ========== | =========== | 
| Oregon Department of Energy    | 2013       | 2013-07-01T00:00:00 | Naren Nayak      | Portland     | 97229    | Wash        | Photovoltaic | 21168                        | 6000       | 100        | 6000           | 9.0399999999999991       | 4320           | watts      | 825182      | 
| Oregon Department of Energy    | 2013       | 2013-07-01T00:00:00 | Dave Straub      | Corvallis    | 97333    | Bent        | Photovoltaic | 19208                        | 6000       | 100        | 6000           | 9.0399999999999991       | 3920           | watts      | 826483      | 
| Oregon Department of Energy    | 2013       | 2013-07-01T00:00:00 | Vijay Gopalswamy | Portland     | 97229    | Wash        | Photovoltaic | 26411                        | 6000       | 100        | 6000           | 9.0399999999999991       | 5390           | watts      | 826488      | 
| Oregon Department of Energy    | 2013       | 2013-07-01T00:00:00 | Daniel Apperson  | Independence | 97351    | Polk        | Photovoltaic | 54022                        | 6000       | 100        | 6000           | 9.0399999999999991       | 11025          | watts      | 826769      | 
| Oregon Department of Energy    | 2013       | 2013-07-01T00:00:00 | Jessica Ward     | Oregon City  | 97045    | Clac        | Photovoltaic | 52822                        | 6000       | 100        | 6000           | 9.0399999999999991       | 10780          | watts      | 826770      | 
| Oregon Department of Energy    | 2013       | 2013-07-01T00:00:00 | Jeff McCaw       | Hood River   | 97031    | Hood        | Photovoltaic | 31213                        | 6000       | 100        | 6000           | 9.0399999999999991       | 6370           | watts      | 827099      | 
| Oregon Department of Energy    | 2013       | 2013-07-01T00:00:00 | Tom Fletcher     | Sherwood     | 97140    | Wash        | Photovoltaic | 35280                        | 6000       | 100        | 6000           | 9.0399999999999991       | 7200           | watts      | 827102      | 
| Oregon Department of Energy    | 2013       | 2013-07-01T00:00:00 | Poramek Dengsot  | Portland     | 97211    | Mult        | Photovoltaic | 13205                        | 5660       | 100        | 5660           | 9.0399999999999991       | 2695           | watts      | 827377      | 
| Oregon Department of Energy    | 2013       | 2013-07-01T00:00:00 | Ron Kurahara     | Hood River   | 97031    | Hood        | Photovoltaic | 60025                        | 6000       | 100        | 6000           | 9.0399999999999991       | 12250          | watts      | 827380      | 
| Oregon Department of Energy    | 2013       | 2013-07-01T00:00:00 | Kristen Brooks   | Bend         | 97701    | Desc        | Photovoltaic | 26850                        | 6000       | 100        | 6000           | 9.0399999999999991       | 7020           | watts      | 829822      | 
```