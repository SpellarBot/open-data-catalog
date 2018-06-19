# IDOR SIC Report Q4 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idor-sic-report-q4-2010-12600) |
| Metadata | [Link](https://data.illinois.gov/api/views/k5hg-a9v2) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/k5hg-a9v2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/k5hg-a9v2/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | k5hg-a9v2 |
| Name | IDOR SIC Report Q4 2010 |
| Attribution | Illinois Department of Revenue |
| Category | Economics |
| Tags | revenue, tax |
| Created | 2011-06-15T18:47:04Z |
| Publication Date | 2011-06-15T18:47:04Z |

## Description

The SIC report is compiled to provide detail information regarding the types of business collecting the various taxes connected to the retailing of tangible personal property. This report shows the amount of each tax type, by a category grouping and totals for each incorporated municipality and the unincorporated areas of each county.   Information is for liability periods October 2010 thru December 2010 which were collected in November 2010 thru January 2011.

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
series e:k5hg-a9v2 d:2010-01-01T00:00:00.000Z t:local_government_name="ADAMS COUNTY GOVERNMENT" t:multi_county_indicator=N t:tax_type_indicator=ST m:apparel_category=0 m:run_type_indicator=2 m:drinking_eating_places_category=11537.56 m:general_merchandise_category=0 m:lumber_building_hardware_category=94737.19 m:agriculture_all_others_category=274944.28 m:automative_filling_stations_category=786327.57 m:food_category=334.31 m:ending_liability_period=201012 m:manufacturers_category=46355.93 m:number_of_taxpayers=278 m:drugs_misc_retail_category=96790.6 m:funiture_h_h_radio_category=4247.23 m:total_tax_receipts=1316274.65

series e:k5hg-a9v2 d:2010-01-01T00:00:00.000Z t:local_government_name="ADAMS COUNTY GOVERNMENT" t:multi_county_indicator=N t:tax_type_indicator=CT m:apparel_category=0 m:run_type_indicator=2 m:drinking_eating_places_category=2320.26 m:general_merchandise_category=0 m:lumber_building_hardware_category=18942 m:agriculture_all_others_category=57554.3 m:automative_filling_stations_category=157441.22 m:food_category=726.9 m:ending_liability_period=201012 m:manufacturers_category=9623.71 m:number_of_taxpayers=0 m:drugs_misc_retail_category=20782.87 m:funiture_h_h_radio_category=911.67 m:total_tax_receipts=268502.93

series e:k5hg-a9v2 d:2010-01-01T00:00:00.000Z t:local_government_name="ADAMS COUNTY GOVERNMENT" t:multi_county_indicator=N t:tax_type_indicator=CST m:apparel_category=0 m:run_type_indicator=2 m:drinking_eating_places_category=576.87 m:general_merchandise_category=0 m:lumber_building_hardware_category=4735.48 m:agriculture_all_others_category=13715.92 m:automative_filling_stations_category=39307.96 m:food_category=16.72 m:ending_liability_period=201012 m:manufacturers_category=2317.76 m:number_of_taxpayers=0 m:drugs_misc_retail_category=4809.89 m:funiture_h_h_radio_category=212.22 m:total_tax_receipts=65742.82
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

entity e:k5hg-a9v2 l:"IDOR SIC Report Q4 2010" t:attribution="Illinois Department of Revenue" t:url=https://data.illinois.gov/api/views/k5hg-a9v2

property e:k5hg-a9v2 t:meta.view v:id=k5hg-a9v2 v:category=Economics v:averageRating=0 v:name="IDOR SIC Report Q4 2010" v:attribution="Illinois Department of Revenue"

property e:k5hg-a9v2 t:meta.view.owner v:id=jkb2-496s v:profileImageUrlMedium=/api/users/jkb2-496s/profile_images/THUMB v:profileImageUrlLarge=/api/users/jkb2-496s/profile_images/LARGE v:screenName=wilcoxd v:profileImageUrlSmall=/api/users/jkb2-496s/profile_images/TINY v:displayName=wilcoxd

property e:k5hg-a9v2 t:meta.view.tableauthor v:id=jkb2-496s v:profileImageUrlMedium=/api/users/jkb2-496s/profile_images/THUMB v:profileImageUrlLarge=/api/users/jkb2-496s/profile_images/LARGE v:screenName=wilcoxd v:profileImageUrlSmall=/api/users/jkb2-496s/profile_images/TINY v:roleName=publisher v:displayName=wilcoxd
```

## Top Records

```ls
| ending_liability_period | run_type_indicator | local_government_name   | multi_county_indicator | tax_type_indicator | number_of_taxpayers | total_tax_receipts | general_merchandise_category | food_category | drinking_eating_places_category | apparel_category | funiture_h_h_radio_category | lumber_building_hardware_category | automative_filling_stations_category | drugs_misc_retail_category | agriculture_all_others_category | manufacturers_category | 
| ======================= | ================== | ======================= | ====================== | ================== | =================== | ================== | ============================ | ============= | =============================== | ================ | =========================== | ================================= | ==================================== | ========================== | =============================== | ====================== | 
| 201012                  | 2                  | ADAMS COUNTY GOVERNMENT | N                      | ST                 | 278                 | 1316274.65         | 0.00                         | 334.31        | 11537.56                        | 0.00             | 4247.23                     | 94737.19                          | 786327.57                            | 96790.60                   | 274944.28                       | 46355.93               | 
| 201012                  | 2                  | ADAMS COUNTY GOVERNMENT | N                      | CT                 | 0                   | 268502.93          | 0.00                         | 726.90        | 2320.26                         | 0.00             | 911.67                      | 18942.00                          | 157441.22                            | 20782.87                   | 57554.30                        | 9623.71                | 
| 201012                  | 2                  | ADAMS COUNTY GOVERNMENT | N                      | CST                | 0                   | 65742.82           | 0.00                         | 16.72         | 576.87                          | 0.00             | 212.22                      | 4735.48                           | 39307.96                             | 4809.89                    | 13715.92                        | 2317.76                | 
| 201012                  | 2                  | CAMP POINT              | N                      | ST                 | 54                  | 111758.85          | 0.00                         | 0.00          | 20827.14                        | 0.00             | 0.00                        | 0.00                              | 63780.27                             | 13539.13                   | 1566.61                         | 1382.32                | 
| 201012                  | 2                  | CAMP POINT              | N                      | MT                 | 0                   | 27320.37           | 0.00                         | 0.00          | 4378.39                         | 0.00             | 0.00                        | 0.00                              | 13104.28                             | 3267.59                    | 325.19                          | 312.86                 | 
| 201012                  | 2                  | CAMP POINT              | N                      | CST                | 0                   | 5584.58            | 0.00                         | 0.00          | 1041.38                         | 0.00             | 0.00                        | 0.00                              | 3185.67                              | 676.94                     | 78.34                           | 69.09                  | 
| 201012                  | 2                  | CLAYTON                 | N                      | ST                 | 24                  | 32495.72           | 0.00                         | 0.00          | 0.00                            | 0.00             | 0.00                        | 0.00                              | 5577.60                              | 3004.41                    | 0.00                            | 176.81                 | 
| 201012                  | 2                  | CLAYTON                 | N                      | MT                 | 0                   | 6678.48            | 0.00                         | 0.00          | 0.00                            | 0.00             | 0.00                        | 0.00                              | 1115.52                              | 595.84                     | 0.00                            | 47.11                  | 
| 201012                  | 2                  | CLAYTON                 | N                      | CST                | 0                   | 1622.93            | 0.00                         | 0.00          | 0.00                            | 0.00             | 0.00                        | 0.00                              | 278.88                               | 148.94                     | 0.00                            | 8.82                   | 
| 201012                  | 2                  | COATSBURG               | N                      | ST                 | 8                   | 8069.50            | 0.00                         | 0.00          | 0.00                            | 0.00             | 0.00                        | 0.00                              | 0.00                                 | 110.94                     | 0.00                            | 0.00                   | 
```