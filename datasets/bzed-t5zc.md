# City Budget and Actual Revenue

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-budget-and-actual-revenue) |
| Metadata | [Link](https://data.iowa.gov/api/views/bzed-t5zc) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/bzed-t5zc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/bzed-t5zc/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | bzed-t5zc |
| Name | City Budget and Actual Revenue |
| Attribution | Iowa Department of Management, Certified City Budgets |
| Category | Government |
| Tags | city, revenue, budget, actuals |
| Created | 2015-07-23T19:30:31Z |
| Publication Date | 2017-01-18T21:19:06Z |

## Description

This dataset contains the budget and actual revenue self-reported by each city via their yearly budget forms filed with the Department of Management. Actual revenue data lags budget expenditures by a couple of fiscal years.

## Columns

```ls
| Included | Schema Type    | Field Name                             | Name                                   | Data Type | Render Type |
| ======== | ============== | ====================================== | ====================================== | ========= | =========== |
| Yes      | time           | fiscal_year                            | Fiscal Year                            | number    | number      |
| Yes      | series tag     | gnis_feature_id                        | GNIS Feature ID                        | text      | number      |
| Yes      | series tag     | city_fips                              | City FIPS                              | text      | number      |
| Yes      | series tag     | city_code                              | City Code                              | text      | text        |
| Yes      | series tag     | city_name                              | City Name                              | text      | text        |
| Yes      | numeric metric | property_taxes_budget                  | Property Taxes Budget                  | money     | money       |
| Yes      | numeric metric | tif_revenues_budget                    | TIF Revenues Budget                    | money     | money       |
| Yes      | numeric metric | other_city_taxes_budget                | Other City Taxes Budget                | money     | money       |
| Yes      | numeric metric | licenses_permits_budget                | Licenses/Permits Budget                | money     | money       |
| Yes      | numeric metric | use_of_money_property_budget           | Use of Money Property Budget           | money     | money       |
| Yes      | numeric metric | intergovernmental_budget               | Intergovernmental Budget               | money     | money       |
| Yes      | numeric metric | charges_for_service_budget             | Charges for Service Budget             | money     | money       |
| Yes      | numeric metric | special_assessments_budget             | Special Assessments Budget             | money     | money       |
| Yes      | numeric metric | miscellaneous_budget                   | Miscellaneous Budget                   | money     | money       |
| Yes      | numeric metric | total_transfers_in_budget              | Total Transfers In Budget              | money     | money       |
| Yes      | numeric metric | proceeds_of_debt_budget                | Proceeds of Debt Budget                | money     | money       |
| Yes      | numeric metric | proceeds_of_capital_asset_sales_budget | Proceeds of Capital Asset Sales Budget | money     | money       |
| Yes      | numeric metric | total_budget                           | Total Budget                           | money     | money       |
| Yes      | numeric metric | property_taxes_actual                  | Property Taxes Actual                  | money     | money       |
| Yes      | numeric metric | tif_revenues_actual                    | TIF Revenues Actual                    | money     | money       |
| Yes      | numeric metric | other_city_taxes_actual                | Other City Taxes Actual                | money     | money       |
| Yes      | numeric metric | licenses_permits_actual                | Licenses/Permits Actual                | money     | money       |
| Yes      | numeric metric | use_of_money_property_actual           | Use of Money Property Actual           | money     | money       |
| Yes      | numeric metric | intergovernmental_actual               | Intergovernmental Actual               | money     | money       |
| Yes      | numeric metric | charges_for_service_actual             | Charges for Service Actual             | money     | money       |
| Yes      | numeric metric | special_assessments_actual             | Special Assessments Actual             | money     | money       |
| Yes      | numeric metric | miscellaneous_actual                   | Miscellaneous Actual                   | money     | money       |
| Yes      | numeric metric | total_transfers_in_actual              | Total Transfers In Actual              | money     | money       |
| Yes      | numeric metric | proceeds_of_debt_actual                | Proceeds of Debt Actual                | money     | money       |
| Yes      | numeric metric | proceeds_of_capital_asset_sales_actual | Proceeds of Capital Asset Sales Actual | money     | money       |
| Yes      | numeric metric | total_actual                           | Total Actual                           | money     | money       |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:bzed-t5zc d:2007-01-01T00:00:00.000Z t:city_name=ACKLEY t:gnis_feature_id=454084 t:city_fips=1900190 t:city_code=42G388 m:other_city_taxes_actual=163508 m:proceeds_of_capital_asset_sales_budget=0 m:other_city_taxes_budget=149971 m:miscellaneous_budget=46550 m:total_transfers_in_budget=175291 m:tif_revenues_actual=0 m:intergovernmental_budget=167594 m:intergovernmental_actual=195484 m:special_assessments_actual=1343 m:use_of_money_property_budget=102592 m:licenses_permits_budget=3660 m:proceeds_of_debt_actual=0 m:miscellaneous_actual=52564 m:use_of_money_property_actual=44016 m:licenses_permits_actual=3959 m:total_transfers_in_actual=67926 m:tif_revenues_budget=0 m:proceeds_of_capital_asset_sales_actual=0 m:property_taxes_budget=449058 m:total_actual=1634939 m:proceeds_of_debt_budget=0 m:charges_for_service_budget=658562 m:total_budget=1757278 m:special_assessments_budget=4000 m:property_taxes_actual=465543 m:charges_for_service_actual=640596

series e:bzed-t5zc d:2007-01-01T00:00:00.000Z t:city_name=ACKWORTH t:gnis_feature_id=454086 t:city_fips=1900235 t:city_code=91G869 m:other_city_taxes_actual=0 m:proceeds_of_capital_asset_sales_budget=0 m:other_city_taxes_budget=576 m:miscellaneous_budget=0 m:total_transfers_in_budget=0 m:tif_revenues_actual=0 m:intergovernmental_budget=55700 m:intergovernmental_actual=50553 m:special_assessments_actual=0 m:use_of_money_property_budget=500 m:licenses_permits_budget=0 m:proceeds_of_debt_actual=0 m:miscellaneous_actual=40 m:use_of_money_property_actual=2214 m:licenses_permits_actual=45 m:total_transfers_in_actual=0 m:tif_revenues_budget=0 m:proceeds_of_capital_asset_sales_actual=0 m:property_taxes_budget=8424 m:total_actual=61966 m:proceeds_of_debt_budget=0 m:charges_for_service_budget=0 m:total_budget=65200 m:special_assessments_budget=0 m:property_taxes_actual=9114 m:charges_for_service_actual=0

series e:bzed-t5zc d:2007-01-01T00:00:00.000Z t:city_name=ADAIR t:gnis_feature_id=454088 t:city_fips=1900370 t:city_code=01G001 m:other_city_taxes_actual=84764 m:proceeds_of_capital_asset_sales_budget=0 m:other_city_taxes_budget=73288 m:miscellaneous_budget=100 m:total_transfers_in_budget=0 m:tif_revenues_actual=0 m:intergovernmental_budget=286929 m:intergovernmental_actual=271321 m:special_assessments_actual=0 m:use_of_money_property_budget=3000 m:licenses_permits_budget=750 m:proceeds_of_debt_actual=0 m:miscellaneous_actual=10436 m:use_of_money_property_actual=8505 m:licenses_permits_actual=3028 m:total_transfers_in_actual=0 m:tif_revenues_budget=108614 m:proceeds_of_capital_asset_sales_actual=0 m:property_taxes_budget=253540 m:total_actual=1171653 m:proceeds_of_debt_budget=0 m:charges_for_service_budget=436260 m:total_budget=1162481 m:special_assessments_budget=0 m:property_taxes_actual=382976 m:charges_for_service_actual=410623
```

## Meta Commands

```ls
metric m:property_taxes_budget p:integer l:"Property Taxes Budget" d:"Includes levied property taxes but does not include state property tax replacements against those taxes." t:dataTypeName=money

metric m:tif_revenues_budget p:integer l:"TIF Revenues Budget" d:"Includes tax increment financing revenue." t:dataTypeName=money

metric m:other_city_taxes_budget p:integer l:"Other City Taxes Budget" d:"Includes revenue from other city taxes, local option taxes, gambling taxes" t:dataTypeName=money

metric m:licenses_permits_budget p:integer l:"Licenses/Permits Budget" d:"Includes revenue from building structure and environmental permits, health and environmental licenses and permits, and other licenses and permits." t:dataTypeName=money

metric m:use_of_money_property_budget p:integer l:"Use of Money Property Budget" d:"Includes earnings from investments, rents, royalties and other miscellaneous related income. Does not include proceeds from sale of property." t:dataTypeName=money

metric m:intergovernmental_budget p:integer l:"Intergovernmental Budget" d:"Includes state-shared revenues, state and federal grants and reimbursements, contributions and reimbursements from other governmental units and agencies, and payments in lieu of taxes." t:dataTypeName=money

metric m:charges_for_service_budget p:integer l:"Charges for Service Budget" d:"Includes charges for pertinent utility service, as well as related charges and connect/re-connect and penalty/forfeiture fees charged. Also includes any charges for other city service." t:dataTypeName=money

metric m:special_assessments_budget p:integer l:"Special Assessments Budget" d:"Includes charges for any city assessments." t:dataTypeName=money

metric m:miscellaneous_budget p:integer l:"Miscellaneous Budget" d:"Includes contributions, deposits and refunds, sale of merchandise, fines and internal service charges." t:dataTypeName=money

metric m:total_transfers_in_budget p:integer l:"Total Transfers In Budget" d:"Budgeted amount of interfund transfer revenue." t:dataTypeName=money

metric m:proceeds_of_debt_budget p:integer l:"Proceeds of Debt Budget" d:"Budgeted total of proceeds from debt." t:dataTypeName=money

metric m:proceeds_of_capital_asset_sales_budget p:integer l:"Proceeds of Capital Asset Sales Budget" d:"Budgeted amount of revenue from the sale of capital assets" t:dataTypeName=money

metric m:total_budget p:integer l:"Total Budget" t:dataTypeName=money

metric m:property_taxes_actual p:integer l:"Property Taxes Actual" d:"Includes levied property taxes but does not include state property tax replacements against those taxes." t:dataTypeName=money

metric m:tif_revenues_actual p:integer l:"TIF Revenues Actual" d:"Includes tax increment financing revenue." t:dataTypeName=money

metric m:other_city_taxes_actual p:integer l:"Other City Taxes Actual" d:"Includes revenue from other city taxes, local option taxes, gambling taxes" t:dataTypeName=money

metric m:licenses_permits_actual p:integer l:"Licenses/Permits Actual" d:"Includes revenue from building structure and environmental permits, health and environmental licenses and permits, and other licenses and permits." t:dataTypeName=money

metric m:use_of_money_property_actual p:integer l:"Use of Money Property Actual" d:"Includes earnings from investments, rents, royalties and other miscellaneous related income. Does not include proceeds from sale of property." t:dataTypeName=money

metric m:intergovernmental_actual p:integer l:"Intergovernmental Actual" d:"Includes state-shared revenues, state and federal grants and reimbursements, contributions and reimbursements from other governmental units and agencies, and payments in lieu of taxes." t:dataTypeName=money

metric m:charges_for_service_actual p:integer l:"Charges for Service Actual" d:"Includes charges for pertinent utility service, as well as related charges and connect/re-connect and penalty/forfeiture fees charged. Also includes any charges for other city service." t:dataTypeName=money

metric m:special_assessments_actual p:integer l:"Special Assessments Actual" d:"Includes charges for any city assessments." t:dataTypeName=money

metric m:miscellaneous_actual p:integer l:"Miscellaneous Actual" d:"Includes contributions, deposits and refunds, sale of merchandise, fines and internal service charges." t:dataTypeName=money

metric m:total_transfers_in_actual p:integer l:"Total Transfers In Actual" d:"Actual amount of interfund transfer revenue" t:dataTypeName=money

metric m:proceeds_of_debt_actual p:integer l:"Proceeds of Debt Actual" d:"Actual amount of revenue from debt issuance" t:dataTypeName=money

metric m:proceeds_of_capital_asset_sales_actual p:integer l:"Proceeds of Capital Asset Sales Actual" d:"Actual revenue from the sales of capital assets" t:dataTypeName=money

metric m:total_actual p:integer l:"Total Actual" t:dataTypeName=money

entity e:bzed-t5zc l:"City Budget and Actual Revenue" t:attribution="Iowa Department of Management, Certified City Budgets" t:url=https://data.iowa.gov/api/views/bzed-t5zc

property e:bzed-t5zc t:meta.view v:id=bzed-t5zc v:category=Government v:averageRating=0 v:name="City Budget and Actual Revenue" v:attribution="Iowa Department of Management, Certified City Budgets"

property e:bzed-t5zc t:meta.view.license v:name="Public Domain"

property e:bzed-t5zc t:meta.view.owner v:id=58aa-5akg v:profileImageUrlMedium=/api/users/58aa-5akg/profile_images/THUMB v:profileImageUrlLarge=/api/users/58aa-5akg/profile_images/LARGE v:screenName="IDOM, Local Budget & Finance" v:profileImageUrlSmall=/api/users/58aa-5akg/profile_images/TINY v:displayName="IDOM, Local Budget & Finance"

property e:bzed-t5zc t:meta.view.tableauthor v:id=58aa-5akg v:profileImageUrlMedium=/api/users/58aa-5akg/profile_images/THUMB v:profileImageUrlLarge=/api/users/58aa-5akg/profile_images/LARGE v:screenName="IDOM, Local Budget & Finance" v:profileImageUrlSmall=/api/users/58aa-5akg/profile_images/TINY v:roleName=editor v:displayName="IDOM, Local Budget & Finance"
```

## Top Records

```ls
| fiscal_year | gnis_feature_id | city_fips | city_code | city_name   | property_taxes_budget | tif_revenues_budget | other_city_taxes_budget | licenses_permits_budget | use_of_money_property_budget | intergovernmental_budget | charges_for_service_budget | special_assessments_budget | miscellaneous_budget | total_transfers_in_budget | proceeds_of_debt_budget | proceeds_of_capital_asset_sales_budget | total_budget | property_taxes_actual | tif_revenues_actual | other_city_taxes_actual | licenses_permits_actual | use_of_money_property_actual | intergovernmental_actual | charges_for_service_actual | special_assessments_actual | miscellaneous_actual | total_transfers_in_actual | proceeds_of_debt_actual | proceeds_of_capital_asset_sales_actual | total_actual | 
| =========== | =============== | ========= | ========= | =========== | ===================== | =================== | ======================= | ======================= | ============================ | ======================== | ========================== | ========================== | ==================== | ========================= | ======================= | ====================================== | ============ | ===================== | =================== | ======================= | ======================= | ============================ | ======================== | ========================== | ========================== | ==================== | ========================= | ======================= | ====================================== | ============ | 
| 2007        | 454084          | 1900190   | 42G388    | ACKLEY      | 449058                | 0                   | 149971                  | 3660                    | 102592                       | 167594                   | 658562                     | 4000                       | 46550                | 175291                    | 0                       | 0                                      | 1757278      | 465543                | 0                   | 163508                  | 3959                    | 44016                        | 195484                   | 640596                     | 1343                       | 52564                | 67926                     | 0                       | 0                                      | 1634939      | 
| 2007        | 454086          | 1900235   | 91G869    | ACKWORTH    | 8424                  | 0                   | 576                     | 0                       | 500                          | 55700                    | 0                          | 0                          | 0                    | 0                         | 0                       | 0                                      | 65200        | 9114                  | 0                   | 0                       | 45                      | 2214                         | 50553                    | 0                          | 0                          | 40                   | 0                         | 0                       | 0                                      | 61966        | 
| 2007        | 454088          | 1900370   | 01G001    | ADAIR       | 253540                | 108614              | 73288                   | 750                     | 3000                         | 286929                   | 436260                     | 0                          | 100                  | 0                         | 0                       | 0                                      | 1162481      | 382976                | 0                   | 84764                   | 3028                    | 8505                         | 271321                   | 410623                     | 0                          | 10436                | 0                         | 0                       | 0                                      | 1171653      | 
| 2007        | 454097          | 1900505   | 25G228    | ADEL        | 1269711               | 330000              | 48464                   | 66115                   | 53940                        | 381923                   | 1225314                    | 55000                      | 134070               | 491739                    | 0                       | 0                                      | 4056276      | 1306736               | 335343              | 6355                    | 57008                   | 127367                       | 359553                   | 1263837                    | 206648                     | 130880               | 490625                    | 1773300                 | 5511                                   | 6063163      | 
| 2007        | 454101          | 1900595   | 88G846    | AFTON       | 130686                | 0                   | 73543                   | 1430                    | 14000                        | 205834                   | 833870                     | 0                          | 6620                 | 99012                     | 0                       | 0                                      | 1364995      | 134684                | 0                   | 96442                   | 1210                    | 29710                        | 138312                   | 807579                     | 0                          | 54736                | 185092                    | 0                       | 0                                      | 1447765      | 
| 2007        | 454105          | 1900640   | 90G862    | AGENCY      | 68797                 | 0                   | 56229                   | 250                     | 8600                         | 50000                    | 165800                     | 0                          | 2200                 | 40563                     | 0                       | 0                                      | 392439       | 68854                 | 0                   | 69346                   | 240                     | 12508                        | 51840                    | 167190                     | 0                          | 4356                 | 40563                     | 0                       | 0                                      | 414897       | 
| 2007        | 454107          | 1900730   | 92G882    | AINSWORTH   | 40361                 | 6500                | 30245                   | 1200                    | 2000                         | 44000                    | 137000                     | 0                          | 1000                 | 0                         | 0                       | 0                                      | 262306       | 40872                 | 6361                | 43833                   | 2222                    | 1170                         | 178058                   | 142770                     | 0                          | 1336                 | 19416                     | 148000                  | 0                                      | 584038       | 
| 2007        | 454109          | 1900775   | 75G692    | AKRON       | 342699                | 42748               | 124327                  | 3400                    | 21260                        | 205561                   | 3254422                    | 0                          | 58400                | 467564                    | 200000                  | 40000                                  | 4760381      | 353051                | 48478               | 177378                  | 3356                    | 36072                        | 244460                   | 3395250                    | 0                          | 224019               | 1099482                   | 0                       | 81715                                  | 5663261      | 
| 2007        | 454113          | 1900865   | 11G083    | ALBERT CITY | 193765                | 0                   | 72204                   | 1840                    | 16742                        | 72475                    | 228310                     | 0                          | 21980                | 47453                     | 0                       | 0                                      | 654769       | 214984                | 0                   | 76099                   | 1050                    | 26648                        | 76381                    | 240272                     | 0                          | 43473                | 61159                     | 0                       | 0                                      | 740066       | 
| 2007        | 454114          | 1900910   | 68G641    | ALBIA       | 1143434               | 0                   | 697637                  | 9425                    | 5800                         | 341910                   | 1594351                    | 0                          | 13000                | 0                         | 0                       | 0                                      | 3805557      | 1171575               | 0                   | 802383                  | 10027                   | 59201                        | 601607                   | 1575617                    | 0                          | 156772               | 679720                    | 535626                  | 5553                                   | 5598081      | 
```