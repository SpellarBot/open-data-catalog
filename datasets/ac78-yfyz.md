# IDOR SIC Report Q1 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idor-sic-report-q1-2011-f10b3) |
| Metadata | [Link](https://data.illinois.gov/api/views/ac78-yfyz) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/ac78-yfyz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/ac78-yfyz/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | ac78-yfyz |
| Name | IDOR SIC Report Q1 2011 |
| Attribution | Illinois Department of Revenue |
| Category | Economics |
| Tags | revenue, tax |
| Created | 2011-06-15T17:22:58Z |
| Publication Date | 2011-06-15T17:22:58Z |

## Description

The SIC report is compiled to provide detail information regarding the types of business collecting the various taxes connected to the retailing of tangible personal property. This report shows the amount of each tax type, by a category grouping and totals for each incorporated municipality and the unincorporated areas of each county.   Information is for liability periods January 2011 thru March 2011 which were collected in February 2011 thru April 2011

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
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ac78-yfyz d:2011-01-01T00:00:00.000Z t:local_government_name="ADAMS COUNTY GOVERNMENT" t:multi_county_indicator=N t:tax_type_indicator=ST m:apparel_category=0 m:run_type_indicator=2 m:drinking_eating_places_category=11528.12 m:general_merchandise_category=0 m:lumber_building_hardware_category=58097.62 m:agriculture_all_others_category=203800.94 m:automative_filling_stations_category=91067.11 m:food_category=217.54 m:ending_liability_period=201103 m:manufacturers_category=31497.84 m:number_of_taxpayers=220 m:drugs_misc_retail_category=99684.83 m:funiture_h_h_radio_category=3640.19 m:total_tax_receipts=500262.87

series e:ac78-yfyz d:2011-01-01T00:00:00.000Z t:local_government_name="ADAMS COUNTY GOVERNMENT" t:multi_county_indicator=N t:tax_type_indicator=CT m:apparel_category=0 m:run_type_indicator=2 m:drinking_eating_places_category=2310.41 m:general_merchandise_category=0 m:lumber_building_hardware_category=11654.5 m:agriculture_all_others_category=40831.85 m:automative_filling_stations_category=18084.91 m:food_category=110.25 m:ending_liability_period=201103 m:manufacturers_category=6502.23 m:number_of_taxpayers=0 m:drugs_misc_retail_category=20377.84 m:funiture_h_h_radio_category=728.02 m:total_tax_receipts=100745.74

series e:ac78-yfyz d:2011-01-01T00:00:00.000Z t:local_government_name="ADAMS COUNTY GOVERNMENT" t:multi_county_indicator=N t:tax_type_indicator=CST m:apparel_category=0 m:run_type_indicator=2 m:drinking_eating_places_category=576.3 m:general_merchandise_category=0 m:lumber_building_hardware_category=2902.09 m:agriculture_all_others_category=10184.12 m:automative_filling_stations_category=4483.12 m:food_category=10.88 m:ending_liability_period=201103 m:manufacturers_category=1574.87 m:number_of_taxpayers=0 m:drugs_misc_retail_category=4969.31 m:funiture_h_h_radio_category=181.99 m:total_tax_receipts=24919.11
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

entity e:ac78-yfyz l:"IDOR SIC Report Q1 2011" t:attribution="Illinois Department of Revenue" t:url=https://data.illinois.gov/api/views/ac78-yfyz

property e:ac78-yfyz t:meta.view v:id=ac78-yfyz v:category=Economics v:averageRating=0 v:name="IDOR SIC Report Q1 2011" v:attribution="Illinois Department of Revenue"

property e:ac78-yfyz t:meta.view.owner v:id=jkb2-496s v:profileImageUrlMedium=/api/users/jkb2-496s/profile_images/THUMB v:profileImageUrlLarge=/api/users/jkb2-496s/profile_images/LARGE v:screenName=wilcoxd v:profileImageUrlSmall=/api/users/jkb2-496s/profile_images/TINY v:displayName=wilcoxd

property e:ac78-yfyz t:meta.view.tableauthor v:id=jkb2-496s v:profileImageUrlMedium=/api/users/jkb2-496s/profile_images/THUMB v:profileImageUrlLarge=/api/users/jkb2-496s/profile_images/LARGE v:screenName=wilcoxd v:profileImageUrlSmall=/api/users/jkb2-496s/profile_images/TINY v:roleName=publisher v:displayName=wilcoxd
```

## Top Records

```ls
| ending_liability_period | run_type_indicator | local_government_name   | multi_county_indicator | tax_type_indicator | number_of_taxpayers | total_tax_receipts | general_merchandise_category | food_category | drinking_eating_places_category | apparel_category | funiture_h_h_radio_category | lumber_building_hardware_category | automative_filling_stations_category | drugs_misc_retail_category | agriculture_all_others_category | manufacturers_category | 
| ======================= | ================== | ======================= | ====================== | ================== | =================== | ================== | ============================ | ============= | =============================== | ================ | =========================== | ================================= | ==================================== | ========================== | =============================== | ====================== | 
| 201103                  | 2                  | ADAMS COUNTY GOVERNMENT | N                      | ST                 | 220                 | 500262.87          | 0.00                         | 217.54        | 11528.12                        | 0.00             | 3640.19                     | 58097.62                          | 91067.11                             | 99684.83                   | 203800.94                       | 31497.84               | 
| 201103                  | 2                  | ADAMS COUNTY GOVERNMENT | N                      | CT                 | 0                   | 100745.74          | 0.00                         | 110.25        | 2310.41                         | 0.00             | 728.02                      | 11654.50                          | 18084.91                             | 20377.84                   | 40831.85                        | 6502.23                | 
| 201103                  | 2                  | ADAMS COUNTY GOVERNMENT | N                      | CST                | 0                   | 24919.11           | 0.00                         | 10.88         | 576.30                          | 0.00             | 181.99                      | 2902.09                           | 4483.12                              | 4969.31                    | 10184.12                        | 1574.87                | 
| 201103                  | 2                  | CAMP POINT              | N                      | ST                 | 54                  | 103526.34          | 0.00                         | 0.00          | 22306.92                        | 0.00             | 0.00                        | 0.00                              | 58365.43                             | 5944.71                    | 660.88                          | 824.19                 | 
| 201103                  | 2                  | CAMP POINT              | N                      | MT                 | 0                   | 25332.95           | 0.00                         | 0.00          | 4634.91                         | 0.00             | 0.00                        | 0.00                              | 11972.57                             | 1209.35                    | 148.04                          | 189.40                 | 
| 201103                  | 2                  | CAMP POINT              | N                      | CST                | 0                   | 5175.07            | 0.00                         | 0.00          | 1115.34                         | 0.00             | 0.00                        | 0.00                              | 2917.04                              | 297.24                     | 33.04                           | 41.23                  | 
| 201103                  | 2                  | CLAYTON                 | N                      | ST                 | 20                  | 27758.20           | 0.00                         | 0.00          | 0.00                            | 0.00             | 0.00                        | 0.00                              | 0.00                                 | 2008.84                    | 0.00                            | 146.64                 | 
| 201103                  | 2                  | CLAYTON                 | N                      | MT                 | 0                   | 5693.04            | 0.00                         | 0.00          | 0.00                            | 0.00             | 0.00                        | 0.00                              | 0.00                                 | 404.68                     | 0.00                            | 35.15                  | 
| 201103                  | 2                  | CLAYTON                 | N                      | CST                | 0                   | 1387.87            | 0.00                         | 0.00          | 0.00                            | 0.00             | 0.00                        | 0.00                              | 0.00                                 | 100.43                     | 0.00                            | 7.32                   | 
| 201103                  | 2                  | COATSBURG               | N                      | ST                 | 7                   | 10533.09           | 0.00                         | 0.00          | 0.00                            | 0.00             | 0.00                        | 0.00                              | 0.00                                 | 164.28                     | 0.00                            | 0.00                   | 
```