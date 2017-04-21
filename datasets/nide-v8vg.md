# Oregon Forest Revenues to State and Local Governments

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oregon-forest-revenues-to-state-and-local-governments) |
| Metadata | [Link](https://data.oregon.gov/api/views/nide-v8vg) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/nide-v8vg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/nide-v8vg/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | nide-v8vg |
| Name | Oregon Forest Revenues to State and Local Governments |
| Attribution | Oregon Department of Forestry |
| Category | Revenue & Expense |
| Tags | forestry, forest industry, timber harvest, revenues, forest revenues |
| Created | 2015-10-27T21:54:56Z |
| Publication Date | 2015-10-27T22:06:38Z |

## Description

Data is collected annually and adjusted for inflation using the GDP Deflator.

## Columns

```ls
| Included | Schema Type    | Field Name                               | Name                                     | Data Type | Render Type |
| ======== | ============== | ======================================== | ======================================== | ========= | =========== |
| Yes      | time           | year                                     | Year                                     | number    | text        |
| Yes      | numeric metric | usda_forest_service_usfs                 | USDA Forest Service (USFS)*              | money     | money       |
| Yes      | numeric metric | bureau_of_land_management_blm            | Bureau of Land Management (BLM)*         | money     | money       |
| Yes      | numeric metric | payments_in_lieu_of_taxes_pilt           | Payments in Lieu of Taxes (PILT)         | money     | money       |
| Yes      | numeric metric | board_of_forestry_bof                    | Board of Forestry (BOF)                  | money     | money       |
| Yes      | numeric metric | common_school_fund_csf                   | Common School Fund (CSF)                 | money     | money       |
| Yes      | numeric metric | county_forest_land                       | County Forest Land                       | money     | money       |
| Yes      | numeric metric | forest_products_harvest_tax              | Forest Products Harvest Tax              | money     | money       |
| Yes      | numeric metric | privilege_severance_tax_receipts         | Privilege/ Severance Tax Receipts        | money     | money       |
| Yes      | numeric metric | industrial_property_tax                  | Industrial Property Tax                  | money     | money       |
| Yes      | numeric metric | forestland_property_tax                  | Forestland Property Tax                  | money     | money       |
| Yes      | numeric metric | forest_fire_protection_services_payments | Forest/Fire Protection Services Payments | money     | money       |
| Yes      | numeric metric | corporate_income_and_excisetaxes         | Corporate Income and ExciseTaxes         | money     | money       |
| Yes      | numeric metric | weight_mile_tax_revenue                  | Weight-Mile Tax Revenue                  | money     | money       |
| Yes      | numeric metric | personal_income_tax                      | Personal Income Tax                      | money     | money       |
| Yes      | numeric metric | total_revenue                            | Total Revenue                            | money     | money       |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:nide-v8vg d:2000-01-01T00:00:00.000Z m:common_school_fund_csf=32050027 m:privilege_severance_tax_receipts=43175214 m:forest_fire_protection_services_payments=18668490 m:forestland_property_tax=7350900 m:board_of_forestry_bof=57172372 m:usda_forest_service_usfs=100342878 m:corporate_income_and_excisetaxes=9570459 m:weight_mile_tax_revenue=10716112 m:industrial_property_tax=41578980 m:total_revenue=433116844 m:payments_in_lieu_of_taxes_pilt=5931136 m:forest_products_harvest_tax=14590022 m:county_forest_land=9883239 m:personal_income_tax=0 m:bureau_of_land_management_blm=82087016

series e:nide-v8vg d:2001-01-01T00:00:00.000Z m:common_school_fund_csf=21575170 m:privilege_severance_tax_receipts=29764595 m:forest_fire_protection_services_payments=13035354 m:forestland_property_tax=21872585 m:board_of_forestry_bof=44476014 m:usda_forest_service_usfs=198916571 m:corporate_income_and_excisetaxes=3785577 m:weight_mile_tax_revenue=10080079 m:industrial_property_tax=41039098 m:total_revenue=795755310 m:payments_in_lieu_of_taxes_pilt=8850183 m:forest_products_harvest_tax=13510335 m:county_forest_land=11747481 m:personal_income_tax=236138649 m:bureau_of_land_management_blm=140963618

series e:nide-v8vg d:2002-01-01T00:00:00.000Z m:common_school_fund_csf=17305244 m:privilege_severance_tax_receipts=21345600 m:forest_fire_protection_services_payments=19313507 m:forestland_property_tax=24061157 m:board_of_forestry_bof=54037630 m:usda_forest_service_usfs=197476195 m:corporate_income_and_excisetaxes=3358957 m:weight_mile_tax_revenue=9222040 m:industrial_property_tax=42555040 m:total_revenue=799547685 m:payments_in_lieu_of_taxes_pilt=9616570 m:forest_products_harvest_tax=11752177 m:county_forest_land=10906386 m:personal_income_tax=238654300 m:bureau_of_land_management_blm=139942882
```

## Meta Commands

```ls
metric m:usda_forest_service_usfs p:integer l:"USDA Forest Service (USFS)*" t:dataTypeName=money

metric m:bureau_of_land_management_blm p:integer l:"Bureau of Land Management (BLM)*" t:dataTypeName=money

metric m:payments_in_lieu_of_taxes_pilt p:integer l:"Payments in Lieu of Taxes (PILT)" t:dataTypeName=money

metric m:board_of_forestry_bof p:integer l:"Board of Forestry (BOF)" t:dataTypeName=money

metric m:common_school_fund_csf p:integer l:"Common School Fund (CSF)" t:dataTypeName=money

metric m:county_forest_land p:integer l:"County Forest Land" t:dataTypeName=money

metric m:forest_products_harvest_tax p:integer l:"Forest Products Harvest Tax" t:dataTypeName=money

metric m:privilege_severance_tax_receipts p:integer l:"Privilege/ Severance Tax Receipts" t:dataTypeName=money

metric m:industrial_property_tax p:integer l:"Industrial Property Tax" t:dataTypeName=money

metric m:forestland_property_tax p:integer l:"Forestland Property Tax" t:dataTypeName=money

metric m:forest_fire_protection_services_payments p:integer l:"Forest/Fire Protection Services Payments" t:dataTypeName=money

metric m:corporate_income_and_excisetaxes p:integer l:"Corporate Income and ExciseTaxes" t:dataTypeName=money

metric m:weight_mile_tax_revenue p:integer l:"Weight-Mile Tax Revenue" t:dataTypeName=money

metric m:personal_income_tax p:integer l:"Personal Income Tax" t:dataTypeName=money

metric m:total_revenue p:integer l:"Total Revenue" t:dataTypeName=money

entity e:nide-v8vg l:"Oregon Forest Revenues to State and Local Governments" t:attribution="Oregon Department of Forestry" t:url=https://data.oregon.gov/api/views/nide-v8vg

property e:nide-v8vg t:meta.view v:id=nide-v8vg v:category="Revenue & Expense" v:averageRating=0 v:name="Oregon Forest Revenues to State and Local Governments" v:attribution="Oregon Department of Forestry"

property e:nide-v8vg t:meta.view.owner v:id=s5qg-kz93 v:screenName="Brandon Kaetzel" v:displayName="Brandon Kaetzel"

property e:nide-v8vg t:meta.view.tableauthor v:id=s5qg-kz93 v:screenName="Brandon Kaetzel" v:roleName=editor v:displayName="Brandon Kaetzel"
```

## Top Records

```ls
| year | usda_forest_service_usfs | bureau_of_land_management_blm | payments_in_lieu_of_taxes_pilt | board_of_forestry_bof | common_school_fund_csf | county_forest_land | forest_products_harvest_tax | privilege_severance_tax_receipts | industrial_property_tax | forestland_property_tax | forest_fire_protection_services_payments | corporate_income_and_excisetaxes | weight_mile_tax_revenue | personal_income_tax | total_revenue | 
| ==== | ======================== | ============================= | ============================== | ===================== | ====================== | ================== | =========================== | ================================ | ======================= | ======================= | ======================================== | ================================ | ======================= | =================== | ============= | 
| 2000 | 100342878                | 82087016                      | 5931136                        | 57172372              | 32050027               | 9883239            | 14590022                    | 43175214                         | 41578980                | 7350900                 | 18668490                                 | 9570459                          | 10716112                | 0                   | 433116844     | 
| 2001 | 198916571                | 140963618                     | 8850183                        | 44476014              | 21575170               | 11747481           | 13510335                    | 29764595                         | 41039098                | 21872585                | 13035354                                 | 3785577                          | 10080079                | 236138649           | 795755310     | 
| 2002 | 197476195                | 139942882                     | 9616570                        | 54037630              | 17305244               | 10906386           | 11752177                    | 21345600                         | 42555040                | 24061157                | 19313507                                 | 3358957                          | 9222040                 | 238654300           | 799547685     | 
| 2003 | 195941005                | 138854958                     | 7459090                        | 61806703              | 10611040               | 10749757           | 13692080                    | 14865077                         | 48664815                | 23949284                | 19535977                                 | 2708868                          | 9635956                 | 236789146           | 795263757     | 
| 2004 | 193192244                | 136907033                     | 7543794                        | 57882357              | 18554106               | 12195199           | 15538817                    | 1538391                          | 52036429                | 20396463                | 19738936                                 | 6185131                          | 21813695                | 241177888           | 804700484     | 
| 2005 | 191490775                | 135701273                     | 7523545                        | 56868611              | 22345229               | 13983173           | 14388103                    | 1482916                          | 58608250                | 22934007                | 19771623                                 | 13999055                         | 19817125                | 243318656           | 822232341     | 
| 2006 | 187631009                | 132966023                     | 7488778                        | 65852559              | 10964494               | 15068195           | 13395531                    | 1088651                          | 53689472                | 18432346                | 20206819                                 | 9974322                          | 18210081                | 238013925           | 792982205     | 
| 2007 | 182405691                | 128145427                     | 7273492                        | 63385798              | 13925763               | 11151612           | 12190034                    | 507178                           | 52331947                | 18845958                | 20256613                                 | 179454                           | 16632297                | 226499885           | 753731150     | 
| 2008 | 160326653                | 114334713                     | 10934490                       | 55525298              | 10201475               | 7997094            | 11044467                    | 549586                           | 27897946                | 16926747                | 19529714                                 | 8669692                          | 15059675                | 203380676           | 662378227     | 
| 2009 | 143197354                | 102119182                     | 16109716                       | 45725438              | 14608208               | 10218767           | 12886411                    | 234337                           | 31420747                | 20063192                | 12607449                                 | 3589187                          | 14079161                | 162661382           | 589520532     | 
```