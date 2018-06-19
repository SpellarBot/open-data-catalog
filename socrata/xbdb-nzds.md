# OTDA LIM - Lottery Intercept Match

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/otda-lim-lottery-intercept-match) |
| Metadata | [Link](https://data.ny.gov/api/views/xbdb-nzds) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/xbdb-nzds/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/xbdb-nzds/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | xbdb-nzds |
| Name | OTDA LIM - Lottery Intercept Match |
| Attribution | Office of Temporary and Disability Assistance (OTDA) |
| Category | Human Services |
| Created | 2015-11-27T14:42:40Z |
| Publication Date | 2017-04-18T22:00:24Z |

## Description

This dataset from the Office of Temporary and Disability Assistance (OTDA) Audit public assistance (PA) recoveries through lottery intercept matches (LIM).  The dataset provides information on intercepts of lottery winnings of PA recipients to repay PA benefits received, aggregated by month, year, district and total amount recovered for that district by assistance type.

## Columns

```ls
| Included | Schema Type    | Field Name                                                       | Name                                                                                 | Data Type | Render Type |
| ======== | ============== | ================================================================ | ==================================================================================== | ========= | =========== |
| No       |                | year                                                             | Year                                                                                 | number    | number      |
| No       |                | month                                                            | Month                                                                                | text      | text        |
| Yes      | series tag     | month_code                                                       | Month Code                                                                           | text      | number      |
| Yes      | series tag     | district_code                                                    | District Code                                                                        | text      | text        |
| Yes      | series tag     | district                                                         | District                                                                             | text      | text        |
| Yes      | numeric metric | number_of_intercepts                                             | Number of Intercepts                                                                 | number    | number      |
| Yes      | numeric metric | federally_participating_family_assistance_intercept_amount       | Federally Participating Family Assistance Intercepts                                 | money     | money       |
| Yes      | numeric metric | federally_participating_safety_net_non_cash_intercept_amount     | Federally Participating Safety Net Non-Cash Intercepts                               | money     | money       |
| Yes      | numeric metric | federally_non_participating_pg_adc_amount                        | Federally Non-Participating Predetermined Grant/Aid to Dependent Children Intercepts | money     | money       |
| Yes      | numeric metric | federally_non_participating_safety_net_cash_intercept_amount     | Federally Non-Participating Safety Net Cash Intercepts                               | money     | money       |
| Yes      | numeric metric | federally_non_participating_safety_net_non_cash_intercept_amount | Federally Non-Participating Safety Net Non-Cash Intercepts                           | money     | money       |
| Yes      | numeric metric | emergency_assistance_for_families_intercept_amount               | Emergency Assistance for Families Intercepts                                         | money     | money       |
| Yes      | numeric metric | excess_intercept_amount                                          | Excess Intercepts                                                                    | money     | money       |
```

## Time Field

```ls
Value = year-month
Format & Zone = yyyy-MMMM
```

## Series Fields

```ls
Excluded Fields = year,month
```

## Data Commands

```ls
series e:xbdb-nzds d:2013-08-01T00:00:00.000Z t:district_code=01 t:month_code=8 t:district=Albany m:federally_non_participating_pg_adc_amount=0 m:federally_non_participating_safety_net_non_cash_intercept_amount=139.87 m:excess_intercept_amount=0 m:number_of_intercepts=7 m:federally_participating_safety_net_non_cash_intercept_amount=0 m:federally_participating_family_assistance_intercept_amount=917.22 m:emergency_assistance_for_families_intercept_amount=1143.91 m:federally_non_participating_safety_net_cash_intercept_amount=1202.65

series e:xbdb-nzds d:2013-08-01T00:00:00.000Z t:district_code=02 t:month_code=8 t:district=Allegany m:federally_non_participating_pg_adc_amount=0 m:federally_non_participating_safety_net_non_cash_intercept_amount=0 m:excess_intercept_amount=0 m:number_of_intercepts=0 m:federally_participating_safety_net_non_cash_intercept_amount=0 m:federally_participating_family_assistance_intercept_amount=0 m:emergency_assistance_for_families_intercept_amount=0 m:federally_non_participating_safety_net_cash_intercept_amount=0

series e:xbdb-nzds d:2013-08-01T00:00:00.000Z t:district_code=03 t:month_code=8 t:district=Broome m:federally_non_participating_pg_adc_amount=0 m:federally_non_participating_safety_net_non_cash_intercept_amount=0 m:excess_intercept_amount=0 m:number_of_intercepts=4 m:federally_participating_safety_net_non_cash_intercept_amount=0 m:federally_participating_family_assistance_intercept_amount=375 m:emergency_assistance_for_families_intercept_amount=221 m:federally_non_participating_safety_net_cash_intercept_amount=0
```

## Meta Commands

```ls
metric m:number_of_intercepts p:integer l:"Number of Intercepts" d:"Total number of persons with winnings intercepted credited to each Social Service District for the month." t:dataTypeName=number

metric m:federally_participating_family_assistance_intercept_amount p:double l:"Federally Participating Family Assistance Intercepts" d:"Amount of intercepted prize winnings offsetting Federally Participating Family Assistance." t:dataTypeName=money

metric m:federally_participating_safety_net_non_cash_intercept_amount p:double l:"Federally Participating Safety Net Non-Cash Intercepts" d:"Amount of intercepted prize winnings offsetting Federally Participating Safety Net Non-Cash Assistance." t:dataTypeName=money

metric m:federally_non_participating_pg_adc_amount p:double l:"Federally Non-Participating Predetermined Grant/Aid to Dependent Children Intercepts" d:"Amount of intercepted prize winnings offsetting Federally Non-Participating Predetermination Grant/Aid to Dependent Children Assistance." t:dataTypeName=money

metric m:federally_non_participating_safety_net_cash_intercept_amount p:double l:"Federally Non-Participating Safety Net Cash Intercepts" d:"Amount of intercepted prize winnings offsetting Federally Non-Participating Safety Net Cash Assistance." t:dataTypeName=money

metric m:federally_non_participating_safety_net_non_cash_intercept_amount p:double l:"Federally Non-Participating Safety Net Non-Cash Intercepts" d:"Amount of intercepted prize winnings offsetting Federally Non-Participating Safety Net Non-Cash Assistance." t:dataTypeName=money

metric m:emergency_assistance_for_families_intercept_amount p:double l:"Emergency Assistance for Families Intercepts" d:"Amount of intercepted prize winnings offsetting Emergency Assistance for Families." t:dataTypeName=money

metric m:excess_intercept_amount p:double l:"Excess Intercepts" d:"Amount of intercepted prize winnings that surpassed recipient?s Public Assistance obligation." t:dataTypeName=money

entity e:xbdb-nzds l:"OTDA LIM - Lottery Intercept Match" t:attribution="Office of Temporary and Disability Assistance (OTDA)" t:url=https://data.ny.gov/api/views/xbdb-nzds

property e:xbdb-nzds t:meta.view v:id=xbdb-nzds v:category="Human Services" v:attributionLink=http://otda.ny.gov/about/ v:averageRating=0 v:name="OTDA LIM - Lottery Intercept Match" v:attribution="Office of Temporary and Disability Assistance (OTDA)"

property e:xbdb-nzds t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:xbdb-nzds t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| year | month  | month_code | district_code | district    | number_of_intercepts | federally_participating_family_assistance_intercept_amount | federally_participating_safety_net_non_cash_intercept_amount | federally_non_participating_pg_adc_amount | federally_non_participating_safety_net_cash_intercept_amount | federally_non_participating_safety_net_non_cash_intercept_amount | emergency_assistance_for_families_intercept_amount | excess_intercept_amount | 
| ==== | ====== | ========== | ============= | =========== | ==================== | ========================================================== | ============================================================ | ========================================= | ============================================================ | ================================================================ | ================================================== | ======================= | 
| 2013 | August | 8          | 01            | Albany      | 7                    | 917.22                                                     | 0                                                            | 0                                         | 1202.65                                                      | 139.87                                                           | 1143.91                                            | 0                       | 
| 2013 | August | 8          | 02            | Allegany    | 0                    | 0                                                          | 0                                                            | 0                                         | 0                                                            | 0                                                                | 0                                                  | 0                       | 
| 2013 | August | 8          | 03            | Broome      | 4                    | 375                                                        | 0                                                            | 0                                         | 0                                                            | 0                                                                | 221                                                | 0                       | 
| 2013 | August | 8          | 04            | Cattaraugus | 0                    | 0                                                          | 0                                                            | 0                                         | 0                                                            | 0                                                                | 0                                                  | 0                       | 
| 2013 | August | 8          | 05            | Cayuga      | 0                    | 0                                                          | 0                                                            | 0                                         | 0                                                            | 0                                                                | 0                                                  | 0                       | 
| 2013 | August | 8          | 06            | Chautauqua  | 4                    | 4119                                                       | 0                                                            | 0                                         | 0                                                            | 0                                                                | 0                                                  | 0                       | 
| 2013 | August | 8          | 07            | Chemung     | 2                    | 951.86                                                     | 0                                                            | 0                                         | 0                                                            | 0                                                                | 0                                                  | 0                       | 
| 2013 | August | 8          | 08            | Chenango    | 1                    | 0                                                          | 0                                                            | 0                                         | 565.2                                                        | 0                                                                | 0                                                  | 0                       | 
| 2013 | August | 8          | 09            | Clinton     | 0                    | 0                                                          | 0                                                            | 0                                         | 0                                                            | 0                                                                | 0                                                  | 0                       | 
| 2013 | August | 8          | 10            | Columbia    | 0                    | 0                                                          | 0                                                            | 0                                         | 0                                                            | 0                                                                | 0                                                  | 0                       | 
```