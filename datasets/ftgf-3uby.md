# Number of businesses in the State

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/number-of-businesses-in-the-state) |
| Metadata | [Link](https://data.maryland.gov/api/views/ftgf-3uby) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/ftgf-3uby/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/ftgf-3uby/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | ftgf-3uby |
| Name | Number of businesses in the State |
| Attribution | Department of Assessments and Taxation |
| Category | Business and Economy |
| Tags | business, sdat, department of assessments and taxation, charter |
| Created | 2016-07-05T13:48:47Z |
| Publication Date | 2017-04-03T13:40:42Z |

## Description

Number of Businesses in the State of Maryland that are in 'Good Standing'.

## Columns

```ls
| Included | Schema Type    | Field Name                              | Name                                    | Data Type     | Render Type   |
| ======== | ============== | ======================================= | ======================================= | ============= | ============= |
| Yes      | time           | date                                    | Date                                    | calendar_date | calendar_date |
| Yes      | series tag     | month                                   | Month                                   | text          | text          |
| Yes      | numeric metric | number_of_business                      | Number of Business                      | number        | number        |
| Yes      | numeric metric | 01_financial                            | 01 Financial                            | number        | number        |
| Yes      | numeric metric | 02_bank                                 | 02 Bank                                 | number        | number        |
| Yes      | numeric metric | 03_ordinary_business                    | 03 Ordinary Business - Stock            | number        | number        |
| Yes      | numeric metric | 04_ordinary_business_non_stock          | 04 Ordinary Business - Non Stock        | number        | number        |
| Yes      | numeric metric | 05_savings_bank_building_loan           | 05 Savings Bank, Building & Loan        | number        | number        |
| Yes      | numeric metric | 06_professional                         | 06 Professional                         | number        | number        |
| Yes      | numeric metric | 07_public_utility_railroad              | 07 Public Utility & Railroad            | number        | number        |
| Yes      | numeric metric | 08_unincorporated_public_utility        | 08 Unincorporated Public Utility        | number        | number        |
| Yes      | numeric metric | 09_cooperative_stock_domestic           | 09 Cooperative - Stock (Domestic)       | number        | number        |
| Yes      | numeric metric | 10_cooperative_non_stock_domestic       | 10 Cooperative - Non Stock (Domestic)   | number        | number        |
| Yes      | numeric metric | 11_credit_union                         | 11 Credit Union                         | number        | number        |
| Yes      | numeric metric | 12_interstate_foreign                   | 12 Interstate (Foreign)                 | number        | number        |
| Yes      | numeric metric | 13_investment_trust                     | 13 Investment Trust                     | number        | number        |
| Yes      | numeric metric | 14_insurance_foreign                    | 14 Insurance (Foreign)                  | number        | number        |
| Yes      | numeric metric | 15_utility_cooperative                  | 15 Utility Cooperative                  | number        | number        |
| Yes      | numeric metric | 16_church                               | 16 Church                               | number        | number        |
| Yes      | numeric metric | 17_cable_incorporated                   | 17 Cable / Incorporated                 | number        | number        |
| Yes      | numeric metric | 18_cable_unincorporated                 | 18 Cable / Unincorporated               | number        | number        |
| Yes      | series tag     | 19_g_p_statement_of_authority           | 19 G.P. - Statement of Authority        | text          | number        |
| Yes      | numeric metric | 20_entities_other_than_corporations     | 20 Entities Other Than Corporations     | number        | number        |
| Yes      | numeric metric | 21_non_utility_generator                | 21 Non-Utility Generator                | number        | number        |
| Yes      | numeric metric | 22_unincorporated_non_utility_generator | 22 Unincorporated Non-Utility Generator | number        | number        |
| Yes      | numeric metric | 25_family_farm                          | 25 Family Farm                          | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:ftgf-3uby d:2016-08-01T00:00:00.000Z t:month="August, 2016" t:19_g_p_statement_of_authority=0 m:05_savings_bank_building_loan=0 m:20_entities_other_than_corporations=163739 m:17_cable_incorporated=6 m:02_bank=98 m:03_ordinary_business=86425 m:08_unincorporated_public_utility=0 m:07_public_utility_railroad=0 m:15_utility_cooperative=0 m:13_investment_trust=349 m:22_unincorporated_non_utility_generator=46 m:18_cable_unincorporated=0 m:14_insurance_foreign=0 m:11_credit_union=0 m:number_of_business=283252 m:21_non_utility_generator=0 m:09_cooperative_stock_domestic=0 m:06_professional=5158 m:16_church=2709 m:01_financial=0 m:12_interstate_foreign=145 m:10_cooperative_non_stock_domestic=0 m:25_family_farm=549 m:04_ordinary_business_non_stock=24028

series e:ftgf-3uby d:2016-09-01T00:00:00.000Z t:month="September, 2016" t:19_g_p_statement_of_authority=0 m:05_savings_bank_building_loan=0 m:20_entities_other_than_corporations=170818 m:17_cable_incorporated=6 m:02_bank=100 m:03_ordinary_business=89045 m:08_unincorporated_public_utility=0 m:07_public_utility_railroad=0 m:15_utility_cooperative=0 m:13_investment_trust=352 m:22_unincorporated_non_utility_generator=47 m:18_cable_unincorporated=0 m:14_insurance_foreign=0 m:11_credit_union=0 m:number_of_business=294252 m:21_non_utility_generator=0 m:09_cooperative_stock_domestic=0 m:06_professional=5278 m:16_church=2885 m:01_financial=0 m:12_interstate_foreign=148 m:10_cooperative_non_stock_domestic=0 m:25_family_farm=561 m:04_ordinary_business_non_stock=25012

series e:ftgf-3uby d:2016-10-01T00:00:00.000Z t:month="October, 2016" t:19_g_p_statement_of_authority=0 m:05_savings_bank_building_loan=0 m:20_entities_other_than_corporations=178004 m:17_cable_incorporated=6 m:02_bank=100 m:03_ordinary_business=91816 m:08_unincorporated_public_utility=0 m:07_public_utility_railroad=0 m:15_utility_cooperative=0 m:13_investment_trust=358 m:22_unincorporated_non_utility_generator=47 m:18_cable_unincorporated=0 m:14_insurance_foreign=0 m:11_credit_union=0 m:number_of_business=305411 m:21_non_utility_generator=0 m:09_cooperative_stock_domestic=0 m:06_professional=5388 m:16_church=3033 m:01_financial=0 m:12_interstate_foreign=148 m:10_cooperative_non_stock_domestic=0 m:25_family_farm=573 m:04_ordinary_business_non_stock=25938
```

## Meta Commands

```ls
metric m:number_of_business p:integer l:"Number of Business" d:"Number of Businesses in 'Good Standing'" t:dataTypeName=number

metric m:01_financial p:integer l:"01 Financial" t:dataTypeName=number

metric m:02_bank p:integer l:"02 Bank" t:dataTypeName=number

metric m:03_ordinary_business p:integer l:"03 Ordinary Business - Stock" t:dataTypeName=number

metric m:04_ordinary_business_non_stock p:integer l:"04 Ordinary Business - Non Stock" t:dataTypeName=number

metric m:05_savings_bank_building_loan p:integer l:"05 Savings Bank, Building & Loan" t:dataTypeName=number

metric m:06_professional p:integer l:"06 Professional" t:dataTypeName=number

metric m:07_public_utility_railroad p:integer l:"07 Public Utility & Railroad" t:dataTypeName=number

metric m:08_unincorporated_public_utility p:integer l:"08 Unincorporated Public Utility" t:dataTypeName=number

metric m:09_cooperative_stock_domestic p:integer l:"09 Cooperative - Stock (Domestic)" t:dataTypeName=number

metric m:10_cooperative_non_stock_domestic p:integer l:"10 Cooperative - Non Stock (Domestic)" t:dataTypeName=number

metric m:11_credit_union p:integer l:"11 Credit Union" t:dataTypeName=number

metric m:12_interstate_foreign p:integer l:"12 Interstate (Foreign)" t:dataTypeName=number

metric m:13_investment_trust p:integer l:"13 Investment Trust" t:dataTypeName=number

metric m:14_insurance_foreign p:integer l:"14 Insurance (Foreign)" t:dataTypeName=number

metric m:15_utility_cooperative p:integer l:"15 Utility Cooperative" t:dataTypeName=number

metric m:16_church p:integer l:"16 Church" t:dataTypeName=number

metric m:17_cable_incorporated p:integer l:"17 Cable / Incorporated" t:dataTypeName=number

metric m:18_cable_unincorporated p:integer l:"18 Cable / Unincorporated" t:dataTypeName=number

metric m:20_entities_other_than_corporations p:integer l:"20 Entities Other Than Corporations" t:dataTypeName=number

metric m:21_non_utility_generator p:integer l:"21 Non-Utility Generator" t:dataTypeName=number

metric m:22_unincorporated_non_utility_generator p:integer l:"22 Unincorporated Non-Utility Generator" t:dataTypeName=number

metric m:25_family_farm p:integer l:"25 Family Farm" t:dataTypeName=number

entity e:ftgf-3uby l:"Number of businesses in the State" t:attribution="Department of Assessments and Taxation" t:url=https://data.maryland.gov/api/views/ftgf-3uby

property e:ftgf-3uby t:meta.view v:id=ftgf-3uby v:category="Business and Economy" v:attributionLink=http://dat.maryland.gov/Pages/default.aspx v:averageRating=0 v:name="Number of businesses in the State" v:attribution="Department of Assessments and Taxation"

property e:ftgf-3uby t:meta.view.license v:name="Public Domain"

property e:ftgf-3uby t:meta.view.owner v:id=2sdx-rthb v:screenName=Thor v:displayName=Thor

property e:ftgf-3uby t:meta.view.tableauthor v:id=2sdx-rthb v:screenName=Thor v:roleName=editor v:displayName=Thor
```

## Top Records

```ls
| date                | month           | number_of_business | 01_financial | 02_bank | 03_ordinary_business | 04_ordinary_business_non_stock | 05_savings_bank_building_loan | 06_professional | 07_public_utility_railroad | 08_unincorporated_public_utility | 09_cooperative_stock_domestic | 10_cooperative_non_stock_domestic | 11_credit_union | 12_interstate_foreign | 13_investment_trust | 14_insurance_foreign | 15_utility_cooperative | 16_church | 17_cable_incorporated | 18_cable_unincorporated | 19_g_p_statement_of_authority | 20_entities_other_than_corporations | 21_non_utility_generator | 22_unincorporated_non_utility_generator | 25_family_farm | 
| =================== | =============== | ================== | ============ | ======= | ==================== | ============================== | ============================= | =============== | ========================== | ================================ | ============================= | ================================= | =============== | ===================== | =================== | ==================== | ====================== | ========= | ===================== | ======================= | ============================= | =================================== | ======================== | ======================================= | ============== | 
| 2016-08-01T00:00:00 | August, 2016    | 283252             | 0            | 98      | 86425                | 24028                          | 0                             | 5158            | 0                          | 0                                | 0                             | 0                                 | 0               | 145                   | 349                 | 0                    | 0                      | 2709      | 6                     | 0                       | 0                             | 163739                              | 0                        | 46                                      | 549            | 
| 2016-09-01T00:00:00 | September, 2016 | 294252             | 0            | 100     | 89045                | 25012                          | 0                             | 5278            | 0                          | 0                                | 0                             | 0                                 | 0               | 148                   | 352                 | 0                    | 0                      | 2885      | 6                     | 0                       | 0                             | 170818                              | 0                        | 47                                      | 561            | 
| 2016-10-01T00:00:00 | October, 2016   | 305411             | 0            | 100     | 91816                | 25938                          | 0                             | 5388            | 0                          | 0                                | 0                             | 0                                 | 0               | 148                   | 358                 | 0                    | 0                      | 3033      | 6                     | 0                       | 0                             | 178004                              | 0                        | 47                                      | 573            | 
| 2016-11-01T00:00:00 | November, 2016  | 314089             | 0            | 96      | 93480                | 26641                          | 0                             | 5456            | 0                          | 0                                | 0                             | 0                                 | 0               | 148                   | 355                 | 0                    | 0                      | 3147      | 6                     | 0                       | 0                             | 184134                              | 0                        | 47                                      | 579            | 
| 2016-12-01T00:00:00 | December, 2016  | 324141             | 0            | 102     | 95836                | 27780                          | 0                             | 5532            | 0                          | 0                                | 0                             | 0                                 | 0               | 153                   | 352                 | 0                    | 0                      | 3296      | 6                     | 0                       | 0                             | 190447                              | 0                        | 49                                      | 588            | 
| 2017-01-03T00:00:00 | January, 2017   | 337912             | 0            | 107     | 100212               | 29081                          | 0                             | 5575            | 0                          | 0                                | 0                             | 0                                 | 0               | 156                   | 347                 | 0                    | 0                      | 3442      | 6                     | 0                       | 0                             | 198347                              | 0                        | 49                                      | 590            | 
| 2017-02-01T00:00:00 | February, 2017  | 345585             | 0            | 109     | 101344               | 29739                          | 0                             | 5594            | 0                          | 0                                | 0                             | 0                                 | 0               | 164                   | 348                 | 0                    | 0                      | 3713      | 6                     | 0                       | 0                             | 203925                              | 0                        | 48                                      | 595            | 
| 2017-03-01T00:00:00 | March, 2017     | 352904             | 0            | 112     | 102455               | 30426                          | 0                             | 5619            | 0                          | 0                                | 0                             | 0                                 | 0               | 169                   | 340                 | 0                    | 0                      | 3913      | 6                     | 0                       | 0                             | 209213                              | 0                        | 48                                      | 603            | 
| 2017-04-01T00:00:00 | April, 2017     | 361805             | 0            | 113     | 103804               | 31253                          | 0                             | 5632            | 0                          | 0                                | 0                             | 0                                 | 0               | 174                   | 343                 | 0                    | 0                      | 4103      | 6                     | 0                       | 0                             | 215715                              | 0                        | 48                                      | 614            | 
```