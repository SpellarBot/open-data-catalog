# IDOR SIC Report Q1 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idor-sic-report-q1-2010-f5be8) |
| Metadata | [Link](https://data.illinois.gov/api/views/pdek-iinb) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/pdek-iinb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/pdek-iinb/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | pdek-iinb |
| Name | IDOR SIC Report Q1 2010 |
| Attribution | Illinois Department of Revenue |
| Category | Economics |
| Tags | revenue, tax |
| Created | 2011-06-15T17:07:15Z |
| Publication Date | 2011-06-15T17:07:15Z |

## Description

The SIC report is compiled to provide detail information regarding the types of business collecting the various taxes connected to the retailing of tangible personal property. This report shows the amount of each tax type, by a category grouping and totals for each incorporated municipality and the unincorporated areas of each county.   Information is for liability periods January 2010 thru March 2010 which were collected in February 2010 thru April 2010.

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
series e:pdek-iinb d:2010-01-01T00:00:00.000Z t:local_government_name="ADAMS COUNTY GOVERNMENT" t:multi_county_indicator=N t:tax_type_indicator=ST m:apparel_category=0 m:run_type_indicator=2 m:drinking_eating_places_category=10511.82 m:general_merchandise_category=0 m:lumber_building_hardware_category=99591.48 m:agriculture_all_others_category=160641.2 m:automative_filling_stations_category=92365.23 m:food_category=-7255.7 m:ending_liability_period=201003 m:manufacturers_category=35509.01 m:number_of_taxpayers=218 m:drugs_misc_retail_category=92025.39 m:funiture_h_h_radio_category=6351.51 m:total_tax_receipts=498989.08

series e:pdek-iinb d:2010-01-01T00:00:00.000Z t:local_government_name="ADAMS COUNTY GOVERNMENT" t:multi_county_indicator=N t:tax_type_indicator=CT m:apparel_category=0 m:run_type_indicator=2 m:drinking_eating_places_category=2102.34 m:general_merchandise_category=0 m:lumber_building_hardware_category=20102.97 m:agriculture_all_others_category=32335.63 m:automative_filling_stations_category=18661.39 m:food_category=-1452.54 m:ending_liability_period=201003 m:manufacturers_category=7403.4 m:number_of_taxpayers=0 m:drugs_misc_retail_category=19015.81 m:funiture_h_h_radio_category=1270.3 m:total_tax_receipts=101512.12

series e:pdek-iinb d:2010-01-01T00:00:00.000Z t:local_government_name="ADAMS COUNTY GOVERNMENT" t:multi_county_indicator=N t:tax_type_indicator=CST m:apparel_category=0 m:run_type_indicator=2 m:drinking_eating_places_category=525.59 m:general_merchandise_category=0 m:lumber_building_hardware_category=4979.55 m:agriculture_all_others_category=8031.29 m:automative_filling_stations_category=4616.16 m:food_category=-362.72 m:ending_liability_period=201003 m:manufacturers_category=1774.13 m:number_of_taxpayers=0 m:drugs_misc_retail_category=4600.52 m:funiture_h_h_radio_category=317.57 m:total_tax_receipts=24944.52
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

entity e:pdek-iinb l:"IDOR SIC Report Q1 2010" t:attribution="Illinois Department of Revenue" t:url=https://data.illinois.gov/api/views/pdek-iinb

property e:pdek-iinb t:meta.view v:id=pdek-iinb v:category=Economics v:averageRating=0 v:name="IDOR SIC Report Q1 2010" v:attribution="Illinois Department of Revenue"

property e:pdek-iinb t:meta.view.owner v:id=jkb2-496s v:profileImageUrlMedium=/api/users/jkb2-496s/profile_images/THUMB v:profileImageUrlLarge=/api/users/jkb2-496s/profile_images/LARGE v:screenName=wilcoxd v:profileImageUrlSmall=/api/users/jkb2-496s/profile_images/TINY v:displayName=wilcoxd

property e:pdek-iinb t:meta.view.tableauthor v:id=jkb2-496s v:profileImageUrlMedium=/api/users/jkb2-496s/profile_images/THUMB v:profileImageUrlLarge=/api/users/jkb2-496s/profile_images/LARGE v:screenName=wilcoxd v:profileImageUrlSmall=/api/users/jkb2-496s/profile_images/TINY v:roleName=publisher v:displayName=wilcoxd
```

## Top Records

```ls
| ending_liability_period | run_type_indicator | local_government_name   | multi_county_indicator | tax_type_indicator | number_of_taxpayers | total_tax_receipts | general_merchandise_category | food_category | drinking_eating_places_category | apparel_category | funiture_h_h_radio_category | lumber_building_hardware_category | automative_filling_stations_category | drugs_misc_retail_category | agriculture_all_others_category | manufacturers_category | 
| ======================= | ================== | ======================= | ====================== | ================== | =================== | ================== | ============================ | ============= | =============================== | ================ | =========================== | ================================= | ==================================== | ========================== | =============================== | ====================== | 
| 201003                  | 2                  | ADAMS COUNTY GOVERNMENT | N                      | ST                 | 218                 | 498989.08          | 0.00                         | -7255.70      | 10511.82                        | 0.00             | 6351.51                     | 99591.48                          | 92365.23                             | 92025.39                   | 160641.20                       | 35509.01               | 
| 201003                  | 2                  | ADAMS COUNTY GOVERNMENT | N                      | CT                 | 0                   | 101512.12          | 0.00                         | -1452.54      | 2102.34                         | 0.00             | 1270.30                     | 20102.97                          | 18661.39                             | 19015.81                   | 32335.63                        | 7403.40                | 
| 201003                  | 2                  | ADAMS COUNTY GOVERNMENT | N                      | CST                | 0                   | 24944.52           | 0.00                         | -362.72       | 525.59                          | 0.00             | 317.57                      | 4979.55                           | 4616.16                              | 4600.52                    | 8031.29                         | 1774.13                | 
| 201003                  | 2                  | CAMP POINT              | N                      | ST                 | 57                  | 89864.39           | 0.00                         | 0.00          | 21040.79                        | 0.00             | 0.00                        | 4696.54                           | 44585.24                             | 15126.27                   | 699.46                          | 857.28                 | 
| 201003                  | 2                  | CAMP POINT              | N                      | MT                 | 0                   | 22089.45           | 0.00                         | 0.00          | 4358.46                         | 0.00             | 0.00                        | 939.31                            | 9195.98                              | 3839.86                    | 159.45                          | 228.15                 | 
| 201003                  | 2                  | CAMP POINT              | N                      | CST                | 0                   | 4493.17            | 0.00                         | 0.00          | 1052.04                         | 0.00             | 0.00                        | 234.84                            | 2229.19                              | 756.31                     | 34.98                           | 42.86                  | 
| 201003                  | 2                  | CLAYTON                 | N                      | ST                 | 23                  | 24500.57           | 0.00                         | 0.00          | 0.00                            | 0.00             | 0.00                        | 0.00                              | 0.00                                 | 3292.33                    | 508.31                          | 102.92                 | 
| 201003                  | 2                  | CLAYTON                 | N                      | MT                 | 0                   | 5106.18            | 0.00                         | 0.00          | 0.00                            | 0.00             | 0.00                        | 0.00                              | 0.00                                 | 659.37                     | 104.53                          | 88.33                  | 
| 201003                  | 2                  | CLAYTON                 | N                      | CST                | 0                   | 1225.07            | 0.00                         | 0.00          | 0.00                            | 0.00             | 0.00                        | 0.00                              | 0.00                                 | 164.67                     | 25.43                           | 5.15                   | 
| 201003                  | 2                  | COATSBURG               | N                      | ST                 | 9                   | 6906.26            | 0.00                         | 0.00          | 0.00                            | 0.00             | 0.00                        | 0.00                              | 0.00                                 | 51.06                      | 0.00                            | 0.00                   | 
```