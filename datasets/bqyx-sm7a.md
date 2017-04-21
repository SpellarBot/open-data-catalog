# IDOR SIC Report Q2 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idor-sic-report-q2-2010-d7cdd) |
| Metadata | [Link](https://data.illinois.gov/api/views/bqyx-sm7a) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/bqyx-sm7a/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/bqyx-sm7a/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | bqyx-sm7a |
| Name | IDOR SIC Report Q2 2010 |
| Attribution | Illinois Department of Revenue |
| Category | Economics |
| Tags | revenue, tax |
| Created | 2011-06-15T17:16:15Z |
| Publication Date | 2011-06-15T17:16:15Z |

## Description

The SIC report is compiled to provide detail information regarding the types of business collecting the various taxes connected to the retailing of tangible personal property. This report shows the amount of each tax type, by a category grouping and totals for each incorporated municipality and the unincorporated areas of each county.   Information is for liability periods April 2010 thru June 2010 which were collected in May 2010 thru July 2010.

## Columns

```ls
| Included | Schema Type    | Field Name                           | Name                                   | Data Type | Render Type |
| ======== | ============== | ==================================== | ====================================== | ========= | =========== |
| Yes      | numeric metric | ending_liability_period              | Ending Liability Period                | number    | text        |
| Yes      | numeric metric | run_type_indicator                   | Run Type Indicator                     | number    | text        |
| Yes      | series tag     | local_government_name                | Local Government Name                  | text      | text        |
| Yes      | series tag     | multi_county_indicator               | Multi-County Indicator                 | text      | text        |
| Yes      | series tag     | tax_type_indicator                   | Tax Type Indicator                     | text      | text        |
| Yes      | numeric metric | number_of_taxpayers                  | Number of Taxpayers                    | number    | number      |
| Yes      | numeric metric | total_tax_receipts                   | Total Tax Receipts                     | money     | money       |
| Yes      | numeric metric | general_merchandise_category         | General Merchandise Category           | money     | money       |
| Yes      | numeric metric | food_category                        | Food Category                          | money     | money       |
| Yes      | numeric metric | drinking_eating_places_category      | Drinking & Eating Places Category      | money     | money       |
| Yes      | numeric metric | apparel_category                     | Apparel Category                       | money     | money       |
| Yes      | numeric metric | funiture_h_h_radio_category          | Funiture, H.H. & Radio Category        | money     | money       |
| Yes      | numeric metric | lumber_building_hardware_category    | Lumber, Building & Hardware Category   | money     | money       |
| Yes      | numeric metric | automative_filling_stations_category | Automative & Filling Stations Category | money     | money       |
| Yes      | numeric metric | drugs_misc_retail_category           | Drugs & Misc. Retail Category          | money     | money       |
| Yes      | numeric metric | agriculture_all_others_category      | Agriculture & All Others Category      | money     | money       |
| Yes      | numeric metric | manufacturers_category               | Manufacturers Category                 | money     | money       |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:bqyx-sm7a d:2010-01-01T00:00:00.000Z t:local_government_name="ADAMS COUNTY GOVERNMENT" t:multi_county_indicator=N t:tax_type_indicator=ST m:apparel_category=0 m:run_type_indicator=2 m:drinking_eating_places_category=13056.67 m:general_merchandise_category=0 m:lumber_building_hardware_category=63954.81 m:agriculture_all_others_category=253729.41 m:automative_filling_stations_category=100232.54 m:food_category=0 m:ending_liability_period=201006 m:manufacturers_category=50950.4 m:number_of_taxpayers=208 m:drugs_misc_retail_category=101019.88 m:funiture_h_h_radio_category=4738.1 m:total_tax_receipts=599654.55

series e:bqyx-sm7a d:2010-01-01T00:00:00.000Z t:local_government_name="ADAMS COUNTY GOVERNMENT" t:multi_county_indicator=N t:tax_type_indicator=CT m:apparel_category=0 m:run_type_indicator=2 m:drinking_eating_places_category=2634.58 m:general_merchandise_category=0 m:lumber_building_hardware_category=12564.17 m:agriculture_all_others_category=51177.99 m:automative_filling_stations_category=20244.86 m:food_category=0 m:ending_liability_period=201006 m:manufacturers_category=10534.62 m:number_of_taxpayers=0 m:drugs_misc_retail_category=20769.03 m:funiture_h_h_radio_category=947.6 m:total_tax_receipts=121537.77

series e:bqyx-sm7a d:2010-01-01T00:00:00.000Z t:local_government_name="ADAMS COUNTY GOVERNMENT" t:multi_county_indicator=N t:tax_type_indicator=CST m:apparel_category=0 m:run_type_indicator=2 m:drinking_eating_places_category=651.52 m:general_merchandise_category=0 m:lumber_building_hardware_category=3185.24 m:agriculture_all_others_category=12686.31 m:automative_filling_stations_category=5003.75 m:food_category=0 m:ending_liability_period=201006 m:manufacturers_category=2547.51 m:number_of_taxpayers=0 m:drugs_misc_retail_category=5042.76 m:funiture_h_h_radio_category=236.92 m:total_tax_receipts=29952.63
```

## Meta Commands

```ls
metric m:ending_liability_period p:integer l:"Ending Liability Period" t:dataTypeName=number

metric m:run_type_indicator p:integer l:"Run Type Indicator" t:dataTypeName=number

metric m:number_of_taxpayers p:integer l:"Number of Taxpayers" t:dataTypeName=number

metric m:total_tax_receipts p:double l:"Total Tax Receipts" t:dataTypeName=money

metric m:general_merchandise_category p:double l:"General Merchandise Category" t:dataTypeName=money

metric m:food_category p:double l:"Food Category" t:dataTypeName=money

metric m:drinking_eating_places_category p:double l:"Drinking & Eating Places Category" t:dataTypeName=money

metric m:apparel_category p:double l:"Apparel Category" t:dataTypeName=money

metric m:funiture_h_h_radio_category p:double l:"Funiture, H.H. & Radio Category" t:dataTypeName=money

metric m:lumber_building_hardware_category p:double l:"Lumber, Building & Hardware Category" t:dataTypeName=money

metric m:automative_filling_stations_category p:double l:"Automative & Filling Stations Category" t:dataTypeName=money

metric m:drugs_misc_retail_category p:double l:"Drugs & Misc. Retail Category" t:dataTypeName=money

metric m:agriculture_all_others_category p:double l:"Agriculture & All Others Category" t:dataTypeName=money

metric m:manufacturers_category p:double l:"Manufacturers Category" t:dataTypeName=money

entity e:bqyx-sm7a l:"IDOR SIC Report Q2 2010" t:attribution="Illinois Department of Revenue" t:url=https://data.illinois.gov/api/views/bqyx-sm7a

property e:bqyx-sm7a t:meta.view v:id=bqyx-sm7a v:category=Economics v:averageRating=0 v:name="IDOR SIC Report Q2 2010" v:attribution="Illinois Department of Revenue"

property e:bqyx-sm7a t:meta.view.owner v:id=jkb2-496s v:profileImageUrlMedium=/api/users/jkb2-496s/profile_images/THUMB v:profileImageUrlLarge=/api/users/jkb2-496s/profile_images/LARGE v:screenName=wilcoxd v:profileImageUrlSmall=/api/users/jkb2-496s/profile_images/TINY v:displayName=wilcoxd

property e:bqyx-sm7a t:meta.view.tableauthor v:id=jkb2-496s v:profileImageUrlMedium=/api/users/jkb2-496s/profile_images/THUMB v:profileImageUrlLarge=/api/users/jkb2-496s/profile_images/LARGE v:screenName=wilcoxd v:profileImageUrlSmall=/api/users/jkb2-496s/profile_images/TINY v:roleName=publisher v:displayName=wilcoxd
```

## Top Records

```ls
| ending_liability_period | run_type_indicator | local_government_name   | multi_county_indicator | tax_type_indicator | number_of_taxpayers | total_tax_receipts | general_merchandise_category | food_category | drinking_eating_places_category | apparel_category | funiture_h_h_radio_category | lumber_building_hardware_category | automative_filling_stations_category | drugs_misc_retail_category | agriculture_all_others_category | manufacturers_category | 
| ======================= | ================== | ======================= | ====================== | ================== | =================== | ================== | ============================ | ============= | =============================== | ================ | =========================== | ================================= | ==================================== | ========================== | =============================== | ====================== | 
| 201006                  | 2                  | ADAMS COUNTY GOVERNMENT | N                      | ST                 | 208                 | 599654.55          | 0.00                         | 0.00          | 13056.67                        | 0.00             | 4738.10                     | 63954.81                          | 100232.54                            | 101019.88                  | 253729.41                       | 50950.40               | 
| 201006                  | 2                  | ADAMS COUNTY GOVERNMENT | N                      | CT                 | 0                   | 121537.77          | 0.00                         | 0.00          | 2634.58                         | 0.00             | 947.60                      | 12564.17                          | 20244.86                             | 20769.03                   | 51177.99                        | 10534.62               | 
| 201006                  | 2                  | ADAMS COUNTY GOVERNMENT | N                      | CST                | 0                   | 29952.63           | 0.00                         | 0.00          | 651.52                          | 0.00             | 236.92                      | 3185.24                           | 5003.75                              | 5042.76                    | 12686.31                        | 2547.51                | 
| 201006                  | 2                  | CAMP POINT              | N                      | ST                 | 54                  | 118445.18          | 0.00                         | 0.00          | 26368.60                        | 0.00             | 0.00                        | 0.00                              | 59581.28                             | 18218.35                   | 2001.23                         | 1019.51                | 
| 201006                  | 2                  | CAMP POINT              | N                      | MT                 | 0                   | 28172.24           | 0.00                         | 0.00          | 5487.90                         | 0.00             | 0.00                        | 0.00                              | 12289.55                             | 4468.76                    | 416.03                          | 257.96                 | 
| 201006                  | 2                  | CAMP POINT              | N                      | CST                | 0                   | 5922.18            | 0.00                         | 0.00          | 1318.36                         | 0.00             | 0.00                        | 0.00                              | 2979.10                              | 910.88                     | 100.05                          | 50.98                  | 
| 201006                  | 2                  | CLAYTON                 | N                      | ST                 | 21                  | 36354.89           | 0.00                         | 0.00          | 0.00                            | 0.00             | 0.00                        | 0.00                              | 0.00                                 | 3126.74                    | 0.00                            | 0.00                   | 
| 201006                  | 2                  | CLAYTON                 | N                      | MT                 | 0                   | 7461.58            | 0.00                         | 0.00          | 0.00                            | 0.00             | 0.00                        | 0.00                              | 0.00                                 | 628.22                     | 0.00                            | 0.00                   | 
| 201006                  | 2                  | CLAYTON                 | N                      | CST                | 0                   | 1817.73            | 0.00                         | 0.00          | 0.00                            | 0.00             | 0.00                        | 0.00                              | 0.00                                 | 156.35                     | 0.00                            | 0.00                   | 
| 201006                  | 2                  | COATSBURG               | N                      | ST                 | 6                   | 10084.23           | 0.00                         | 0.00          | 0.00                            | 0.00             | 0.00                        | 0.00                              | 0.00                                 | 0.00                       | 0.00                            | 0.00                   | 
```