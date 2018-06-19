# Total and Affordable Housing Units

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/total-and-affordable-housing-units) |
| Metadata | [Link](https://data.lacity.org/api/views/rckt-8prm) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/rckt-8prm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/rckt-8prm/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | rckt-8prm |
| Name | Total and Affordable Housing Units |
| Category | A Livable and Sustainable City |
| Tags | housing, affordable housing, building permits |
| Created | 2016-06-16T22:48:03Z |
| Publication Date | 2017-03-16T22:20:44Z |

## Description

In October 2015, Mayor Garcetti released Executive Directive 13, Support for Affordable Housing (ED 13). ED 13 is a ?Back to Basics? operational directive that helps streamline the development of critical new housing developments that address our housing shortage.

This dataset tracks the City's progress towards the goals outlined in the directive: (1) Permitting 100,000 new units from the start of Mayor Garcetti's administration through the end of fiscal year 2021, and (2) Building or preserving 15,000 affordable housing units for low-income households in this same time period.

## Columns

```ls
| Included | Schema Type    | Field Name                                                                     | Name                                                                                 | Data Type | Render Type |
| ======== | ============== | ============================================================================== | ==================================================================================== | ========= | =========== |
| No       | time           | :updated_at                                                                    | updated_at                                                                           | meta_data | meta_data   |
| Yes      | series tag     | fiscal_year                                                                    | Fiscal Year                                                                          | text      | text        |
| Yes      | series tag     | quarter                                                                        | Quarter                                                                              | text      | text        |
| Yes      | numeric metric | new_housing_units                                                              | New Housing Units                                                                    | number    | number      |
| Yes      | numeric metric | cumulative_new_housing_units                                                   | Cumulative New Housing Units                                                         | number    | number      |
| Yes      | numeric metric | new_affordable_units_financed_by_hcidla_with_new_construction_rehab_tax_credit | New Affordable Units Financed by HCIDLA (with new construction, rehab, & tax credit) | number    | number      |
| Yes      | numeric metric | affordable_units_preserved                                                     | Affordable Units Preserved                                                           | number    | number      |
| Yes      | numeric metric | affordable_units_produced_w_land_use_incentives                                | Affordable Units Produced w/ Land Use Incentives                                     | number    | number      |
| Yes      | numeric metric | first_time_homebuyer_program_loans_closed                                      | First-Time Homebuyer Program Loans Closed                                            | number    | number      |
| Yes      | numeric metric | other_affordable_units_includes_county_state_financed                          | Other Affordable Units (Includes County/State Financed)                              | number    | number      |
| Yes      | numeric metric | affordable_units_recapitalized                                                 | Affordable Units Recapitalized                                                       | number    | number      |
| Yes      | numeric metric | total_affordable_housing                                                       | Total Affordable Housing                                                             | number    | number      |
| Yes      | numeric metric | cumulative_affordable_housing                                                  | Cumulative Affordable Housing                                                        | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:rckt-8prm d:2016-11-19T04:59:11.000Z t:fiscal_year=2013-2014 t:quarter=Q1 m:affordable_units_produced_w_land_use_incentives=44 m:cumulative_affordable_housing=865 m:cumulative_new_housing_units=1665 m:first_time_homebuyer_program_loans_closed=49 m:affordable_units_recapitalized=0 m:affordable_units_preserved=179 m:other_affordable_units_includes_county_state_financed=0 m:new_affordable_units_financed_by_hcidla_with_new_construction_rehab_tax_credit=593 m:total_affordable_housing=865 m:new_housing_units=1665

series e:rckt-8prm d:2016-11-19T04:59:11.000Z t:fiscal_year=2013-2014 t:quarter=Q2 m:affordable_units_produced_w_land_use_incentives=137 m:cumulative_affordable_housing=1369 m:cumulative_new_housing_units=4642 m:first_time_homebuyer_program_loans_closed=52 m:affordable_units_recapitalized=0 m:affordable_units_preserved=161 m:other_affordable_units_includes_county_state_financed=0 m:new_affordable_units_financed_by_hcidla_with_new_construction_rehab_tax_credit=154 m:total_affordable_housing=504 m:new_housing_units=2977

series e:rckt-8prm d:2016-11-19T04:59:11.000Z t:fiscal_year=2013-2014 t:quarter=Q3 m:affordable_units_produced_w_land_use_incentives=60 m:cumulative_affordable_housing=1885 m:cumulative_new_housing_units=7889 m:first_time_homebuyer_program_loans_closed=35 m:affordable_units_recapitalized=0 m:affordable_units_preserved=72 m:other_affordable_units_includes_county_state_financed=0 m:new_affordable_units_financed_by_hcidla_with_new_construction_rehab_tax_credit=349 m:total_affordable_housing=516 m:new_housing_units=3247
```

## Meta Commands

```ls
metric m:new_housing_units p:integer l:"New Housing Units" d:"Includes projected numbers towards the goal of 100,000 units." t:dataTypeName=number

metric m:cumulative_new_housing_units p:integer l:"Cumulative New Housing Units" d:"Includes projected numbers towards the goal of 100,000 units." t:dataTypeName=number

metric m:new_affordable_units_financed_by_hcidla_with_new_construction_rehab_tax_credit p:integer l:"New Affordable Units Financed by HCIDLA (with new construction, rehab, & tax credit)" t:dataTypeName=number

metric m:affordable_units_preserved p:integer l:"Affordable Units Preserved" t:dataTypeName=number

metric m:affordable_units_produced_w_land_use_incentives p:integer l:"Affordable Units Produced w/ Land Use Incentives" t:dataTypeName=number

metric m:first_time_homebuyer_program_loans_closed p:integer l:"First-Time Homebuyer Program Loans Closed" t:dataTypeName=number

metric m:other_affordable_units_includes_county_state_financed p:integer l:"Other Affordable Units (Includes County/State Financed)" t:dataTypeName=number

metric m:affordable_units_recapitalized p:integer l:"Affordable Units Recapitalized" t:dataTypeName=number

metric m:total_affordable_housing p:integer l:"Total Affordable Housing" d:"Includes projected numbers towards the goal of 15,000 affordable units." t:dataTypeName=number

metric m:cumulative_affordable_housing p:integer l:"Cumulative Affordable Housing" d:"Includes projected numbers towards the goal of 15,000 affordable units." t:dataTypeName=number

entity e:rckt-8prm l:"Total and Affordable Housing Units" t:url=https://data.lacity.org/api/views/rckt-8prm

property e:rckt-8prm t:meta.view v:id=rckt-8prm v:category="A Livable and Sustainable City" v:averageRating=0 v:name="Total and Affordable Housing Units"

property e:rckt-8prm t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:rckt-8prm t:meta.view.owner v:id=95pg-i79k v:profileImageUrlMedium=/api/users/95pg-i79k/profile_images/THUMB v:profileImageUrlLarge=/api/users/95pg-i79k/profile_images/LARGE v:screenName=ChelseaU v:profileImageUrlSmall=/api/users/95pg-i79k/profile_images/TINY v:displayName=ChelseaU

property e:rckt-8prm t:meta.view.tableauthor v:id=95pg-i79k v:profileImageUrlMedium=/api/users/95pg-i79k/profile_images/THUMB v:profileImageUrlLarge=/api/users/95pg-i79k/profile_images/LARGE v:screenName=ChelseaU v:profileImageUrlSmall=/api/users/95pg-i79k/profile_images/TINY v:roleName=administrator v:displayName=ChelseaU
```

## Top Records

```ls
| :updated_at | fiscal_year | quarter | new_housing_units | cumulative_new_housing_units | new_affordable_units_financed_by_hcidla_with_new_construction_rehab_tax_credit | affordable_units_preserved | affordable_units_produced_w_land_use_incentives | first_time_homebuyer_program_loans_closed | other_affordable_units_includes_county_state_financed | affordable_units_recapitalized | total_affordable_housing | cumulative_affordable_housing | 
| =========== | =========== | ======= | ================= | ============================ | ============================================================================== | ========================== | =============================================== | ========================================= | ===================================================== | ============================== | ======================== | ============================= | 
| 1479531551  | 2013-2014   | Q1      | 1665              | 1665                         | 593                                                                            | 179                        | 44                                              | 49                                        | 0                                                     | 0                              | 865                      | 865                           | 
| 1479531551  | 2013-2014   | Q2      | 2977              | 4642                         | 154                                                                            | 161                        | 137                                             | 52                                        | 0                                                     | 0                              | 504                      | 1369                          | 
| 1479531551  | 2013-2014   | Q3      | 3247              | 7889                         | 349                                                                            | 72                         | 60                                              | 35                                        | 0                                                     | 0                              | 516                      | 1885                          | 
| 1479531551  | 2013-2014   | Q4      | 3146              | 11035                        | 211                                                                            | 79                         | 42                                              | 31                                        | 154                                                   | 0                              | 517                      | 2402                          | 
| 1479531551  | 2014-2015   | Q1      | 2580              | 13615                        | 53                                                                             | 88                         | 59                                              | 22                                        | 64                                                    | 270                            | 286                      | 2688                          | 
| 1479531551  | 2014-2015   | Q2      | 3420              | 17035                        | 250                                                                            | 108                        | 97                                              | 37                                        | 0                                                     | 158                            | 492                      | 3180                          | 
| 1479531551  | 2014-2015   | Q3      | 4518              | 21553                        | 283                                                                            | 280                        | 35                                              | 25                                        | 0                                                     | 0                              | 623                      | 3803                          | 
| 1479531551  | 2014-2015   | Q4      | 4376              | 25929                        | 0                                                                              | 0                          | 119                                             | 37                                        | 0                                                     | 0                              | 156                      | 3959                          | 
| 1479531551  | 2015-2016   | Q1      | 3819              | 29748                        | 193                                                                            | 108                        | 63                                              | 29                                        | 0                                                     | 0                              | 393                      | 4352                          | 
| 1479531551  | 2015-2016   | Q2      | 4523              | 34271                        | 134                                                                            | 0                          | 101                                             | 36                                        | 77                                                    | 48                             | 348                      | 4700                          | 
```