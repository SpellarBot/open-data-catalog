# IDOR SIC Report Q3 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idor-sic-report-q3-2010-95c27) |
| Metadata | [Link](https://data.illinois.gov/api/views/uwtt-n6qv) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/uwtt-n6qv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/uwtt-n6qv/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | uwtt-n6qv |
| Name | IDOR SIC Report Q3 2010 |
| Attribution | Illinois Department of Revenue |
| Category | Economics |
| Tags | revenue, tax |
| Created | 2011-06-15T17:26:04Z |
| Publication Date | 2011-06-15T17:26:04Z |

## Description

The SIC report is compiled to provide detail information regarding the types of business collecting the various taxes connected to the retailing of tangible personal property. This report shows the amount of each tax type, by a category grouping and totals for each incorporated municipality and the unincorporated areas of each county.   Information is for liability periods July 2010 thru September 2010 which were collected in August 2010 thru October 2010.

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
series e:uwtt-n6qv d:2010-01-01T00:00:00.000Z t:local_government_name="ADAMS COUNTY GOVERNMENT" t:multi_county_indicator=N t:tax_type_indicator=ST m:apparel_category=0 m:run_type_indicator=2 m:drinking_eating_places_category=14975.03 m:general_merchandise_category=0 m:lumber_building_hardware_category=123815.82 m:agriculture_all_others_category=272044.75 m:automative_filling_stations_category=86328.92 m:food_category=479.43 m:ending_liability_period=201009 m:manufacturers_category=56585.7 m:number_of_taxpayers=219 m:drugs_misc_retail_category=96213.62 m:funiture_h_h_radio_category=4539.46 m:total_tax_receipts=655709.93

series e:uwtt-n6qv d:2010-01-01T00:00:00.000Z t:local_government_name="ADAMS COUNTY GOVERNMENT" t:multi_county_indicator=N t:tax_type_indicator=CT m:apparel_category=0 m:run_type_indicator=2 m:drinking_eating_places_category=3020.45 m:general_merchandise_category=0 m:lumber_building_hardware_category=24729.01 m:agriculture_all_others_category=55606 m:automative_filling_stations_category=17506.71 m:food_category=117.49 m:ending_liability_period=201009 m:manufacturers_category=11691.69 m:number_of_taxpayers=0 m:drugs_misc_retail_category=19908.49 m:funiture_h_h_radio_category=907.89 m:total_tax_receipts=133633.17

series e:uwtt-n6qv d:2010-01-01T00:00:00.000Z t:local_government_name="ADAMS COUNTY GOVERNMENT" t:multi_county_indicator=N t:tax_type_indicator=CST m:apparel_category=0 m:run_type_indicator=2 m:drinking_eating_places_category=748.79 m:general_merchandise_category=0 m:lumber_building_hardware_category=6182.29 m:agriculture_all_others_category=13597.67 m:automative_filling_stations_category=4313.56 m:food_category=23.98 m:ending_liability_period=201009 m:manufacturers_category=2829.1 m:number_of_taxpayers=0 m:drugs_misc_retail_category=4805.22 m:funiture_h_h_radio_category=226.97 m:total_tax_receipts=32763.94
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

entity e:uwtt-n6qv l:"IDOR SIC Report Q3 2010" t:attribution="Illinois Department of Revenue" t:url=https://data.illinois.gov/api/views/uwtt-n6qv

property e:uwtt-n6qv t:meta.view v:id=uwtt-n6qv v:category=Economics v:averageRating=0 v:name="IDOR SIC Report Q3 2010" v:attribution="Illinois Department of Revenue"

property e:uwtt-n6qv t:meta.view.owner v:id=jkb2-496s v:profileImageUrlMedium=/api/users/jkb2-496s/profile_images/THUMB v:profileImageUrlLarge=/api/users/jkb2-496s/profile_images/LARGE v:screenName=wilcoxd v:profileImageUrlSmall=/api/users/jkb2-496s/profile_images/TINY v:displayName=wilcoxd

property e:uwtt-n6qv t:meta.view.tableauthor v:id=jkb2-496s v:profileImageUrlMedium=/api/users/jkb2-496s/profile_images/THUMB v:profileImageUrlLarge=/api/users/jkb2-496s/profile_images/LARGE v:screenName=wilcoxd v:profileImageUrlSmall=/api/users/jkb2-496s/profile_images/TINY v:roleName=publisher v:displayName=wilcoxd
```

## Top Records

```ls
| ending_liability_period | run_type_indicator | local_government_name   | multi_county_indicator | tax_type_indicator | number_of_taxpayers | total_tax_receipts | general_merchandise_category | food_category | drinking_eating_places_category | apparel_category | funiture_h_h_radio_category | lumber_building_hardware_category | automative_filling_stations_category | drugs_misc_retail_category | agriculture_all_others_category | manufacturers_category | 
| ======================= | ================== | ======================= | ====================== | ================== | =================== | ================== | ============================ | ============= | =============================== | ================ | =========================== | ================================= | ==================================== | ========================== | =============================== | ====================== | 
| 201009                  | 2                  | ADAMS COUNTY GOVERNMENT | N                      | ST                 | 219                 | 655709.93          | 0.00                         | 479.43        | 14975.03                        | 0.00             | 4539.46                     | 123815.82                         | 86328.92                             | 96213.62                   | 272044.75                       | 56585.70               | 
| 201009                  | 2                  | ADAMS COUNTY GOVERNMENT | N                      | CT                 | 0                   | 133633.17          | 0.00                         | 117.49        | 3020.45                         | 0.00             | 907.89                      | 24729.01                          | 17506.71                             | 19908.49                   | 55606.00                        | 11691.69               | 
| 201009                  | 2                  | ADAMS COUNTY GOVERNMENT | N                      | CST                | 0                   | 32763.94           | 0.00                         | 23.98         | 748.79                          | 0.00             | 226.97                      | 6182.29                           | 4313.56                              | 4805.22                    | 13597.67                        | 2829.10                | 
| 201009                  | 2                  | CAMP POINT              | N                      | ST                 | 55                  | 122195.82          | 0.00                         | 0.00          | 23891.53                        | 0.00             | 0.00                        | 0.00                              | 56416.23                             | 19029.17                   | 2991.12                         | 1072.13                | 
| 201009                  | 2                  | CAMP POINT              | N                      | MT                 | 0                   | 29031.73           | 0.00                         | 0.00          | 5024.82                         | 0.00             | 0.00                        | 0.00                              | 11690.79                             | 4656.78                    | 614.92                          | 256.99                 | 
| 201009                  | 2                  | CAMP POINT              | N                      | CST                | 0                   | 6113.55            | 0.00                         | 0.00          | 1194.53                         | 0.00             | 0.00                        | 0.00                              | 2820.73                              | 955.39                     | 149.55                          | 53.62                  | 
| 201009                  | 2                  | CLAYTON                 | N                      | ST                 | 21                  | 36638.22           | 0.00                         | 0.00          | 0.00                            | 0.00             | 0.00                        | 0.00                              | 0.00                                 | 2485.85                    | 0.00                            | 194.92                 | 
| 201009                  | 2                  | CLAYTON                 | N                      | MT                 | 0                   | 7530.17            | 0.00                         | 0.00          | 0.00                            | 0.00             | 0.00                        | 0.00                              | 0.00                                 | 500.09                     | 0.00                            | 50.77                  | 
| 201009                  | 2                  | CLAYTON                 | N                      | CST                | 0                   | 1831.54            | 0.00                         | 0.00          | 0.00                            | 0.00             | 0.00                        | 0.00                              | 0.00                                 | 124.30                     | 0.00                            | 9.75                   | 
| 201009                  | 2                  | COATSBURG               | N                      | ST                 | 6                   | 1748.30            | 0.00                         | 0.00          | 0.00                            | 0.00             | 0.00                        | 0.00                              | 1598.93                              | 0.00                       | 0.00                            | 0.00                   | 
```