# IDOR SIC Report CY 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idor-sic-report-cy-2010-7cd5d) |
| Metadata | [Link](https://data.illinois.gov/api/views/9rcx-nbsc) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/9rcx-nbsc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/9rcx-nbsc/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 9rcx-nbsc |
| Name | IDOR SIC Report CY 2010 |
| Attribution | Illinois Department of Revenue |
| Category | Economics |
| Tags | revenue, tax |
| Created | 2011-06-15T18:53:04Z |
| Publication Date | 2011-06-15T18:53:04Z |

## Description

The SIC report is compiled to provide detail information regarding the types of business collecting the various taxes connected to the retailing of tangible personal property. This report shows the amount of each tax type, by a category grouping and totals for each incorporated municipality and the unincorporated areas of each county.   Information is for liability periods January 2010 thru December 2010 which were collected in February 2010 thru January 2011.

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
series e:9rcx-nbsc d:2010-01-01T00:00:00.000Z t:local_government_name="ADAMS COUNTY GOVERNMENT" t:multi_county_indicator=N t:tax_type_indicator=ST m:apparel_category=0 m:run_type_indicator=3 m:drinking_eating_places_category=50081.08 m:general_merchandise_category=0 m:lumber_building_hardware_category=382099.3 m:agriculture_all_others_category=961359.64 m:automative_filling_stations_category=1065254.26 m:food_category=-6365.76 m:ending_liability_period=201012 m:manufacturers_category=189401.04 m:number_of_taxpayers=350 m:drugs_misc_retail_category=386049.49 m:funiture_h_h_radio_category=19876.3 m:total_tax_receipts=3070628.21

series e:9rcx-nbsc d:2010-01-01T00:00:00.000Z t:local_government_name="ADAMS COUNTY GOVERNMENT" t:multi_county_indicator=N t:tax_type_indicator=CT m:apparel_category=0 m:run_type_indicator=3 m:drinking_eating_places_category=10077.63 m:general_merchandise_category=0 m:lumber_building_hardware_category=76338.15 m:agriculture_all_others_category=196673.92 m:automative_filling_stations_category=213854.18 m:food_category=-569.16 m:ending_liability_period=201012 m:manufacturers_category=39253.42 m:number_of_taxpayers=0 m:drugs_misc_retail_category=80476.2 m:funiture_h_h_radio_category=4037.46 m:total_tax_receipts=625185.99

series e:9rcx-nbsc d:2010-01-01T00:00:00.000Z t:local_government_name="ADAMS COUNTY GOVERNMENT" t:multi_county_indicator=N t:tax_type_indicator=CST m:apparel_category=0 m:run_type_indicator=3 m:drinking_eating_places_category=2502.77 m:general_merchandise_category=0 m:lumber_building_hardware_category=19082.56 m:agriculture_all_others_category=48031.19 m:automative_filling_stations_category=53241.43 m:food_category=-318.21 m:ending_liability_period=201012 m:manufacturers_category=9468.5 m:number_of_taxpayers=0 m:drugs_misc_retail_category=19258.39 m:funiture_h_h_radio_category=993.68 m:total_tax_receipts=153403.91
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

entity e:9rcx-nbsc l:"IDOR SIC Report CY 2010" t:attribution="Illinois Department of Revenue" t:url=https://data.illinois.gov/api/views/9rcx-nbsc

property e:9rcx-nbsc t:meta.view v:id=9rcx-nbsc v:category=Economics v:averageRating=0 v:name="IDOR SIC Report CY 2010" v:attribution="Illinois Department of Revenue"

property e:9rcx-nbsc t:meta.view.owner v:id=jkb2-496s v:profileImageUrlMedium=/api/users/jkb2-496s/profile_images/THUMB v:profileImageUrlLarge=/api/users/jkb2-496s/profile_images/LARGE v:screenName=wilcoxd v:profileImageUrlSmall=/api/users/jkb2-496s/profile_images/TINY v:displayName=wilcoxd

property e:9rcx-nbsc t:meta.view.tableauthor v:id=jkb2-496s v:profileImageUrlMedium=/api/users/jkb2-496s/profile_images/THUMB v:profileImageUrlLarge=/api/users/jkb2-496s/profile_images/LARGE v:screenName=wilcoxd v:profileImageUrlSmall=/api/users/jkb2-496s/profile_images/TINY v:roleName=publisher v:displayName=wilcoxd
```

## Top Records

```ls
| ending_liability_period | run_type_indicator | local_government_name   | multi_county_indicator | tax_type_indicator | number_of_taxpayers | total_tax_receipts | general_merchandise_category | food_category | drinking_eating_places_category | apparel_category | funiture_h_h_radio_category | lumber_building_hardware_category | automative_filling_stations_category | drugs_misc_retail_category | agriculture_all_others_category | manufacturers_category | 
| ======================= | ================== | ======================= | ====================== | ================== | =================== | ================== | ============================ | ============= | =============================== | ================ | =========================== | ================================= | ==================================== | ========================== | =============================== | ====================== | 
| 201012                  | 3                  | ADAMS COUNTY GOVERNMENT | N                      | ST                 | 350                 | 3070628.21         | 0.00                         | -6365.76      | 50081.08                        | 0.00             | 19876.30                    | 382099.30                         | 1065254.26                           | 386049.49                  | 961359.64                       | 189401.04              | 
| 201012                  | 3                  | ADAMS COUNTY GOVERNMENT | N                      | CT                 | 0                   | 625185.99          | 0.00                         | -569.16       | 10077.63                        | 0.00             | 4037.46                     | 76338.15                          | 213854.18                            | 80476.20                   | 196673.92                       | 39253.42               | 
| 201012                  | 3                  | ADAMS COUNTY GOVERNMENT | N                      | CST                | 0                   | 153403.91          | 0.00                         | -318.21       | 2502.77                         | 0.00             | 993.68                      | 19082.56                          | 53241.43                             | 19258.39                   | 48031.19                        | 9468.50                | 
| 201012                  | 3                  | CAMP POINT              | N                      | ST                 | 78                  | 442264.24          | 0.00                         | 24452.35      | 92128.06                        | 0.00             | 0.00                        | 17851.74                          | 224363.02                            | 65912.92                   | 7258.42                         | 4331.24                | 
| 201012                  | 3                  | CAMP POINT              | N                      | MT                 | 0                   | 106613.79          | 0.00                         | 17515.45      | 19249.57                        | 0.00             | 0.00                        | 3570.35                           | 46280.60                             | 16232.99                   | 1515.59                         | 1055.96                | 
| 201012                  | 3                  | CAMP POINT              | N                      | CST                | 0                   | 22113.48           | 0.00                         | 1222.57       | 4606.31                         | 0.00             | 0.00                        | 892.60                            | 11214.69                             | 3299.52                    | 362.92                          | 216.55                 | 
| 201012                  | 3                  | CLAYTON                 | N                      | ST                 | 35                  | 129989.40          | 0.00                         | 0.00          | 0.00                            | 0.00             | 66.10                       | 0.00                              | 28438.29                             | 11909.33                   | 2026.71                         | 671.15                 | 
| 201012                  | 3                  | CLAYTON                 | N                      | MT                 | 0                   | 26776.41           | 0.00                         | 0.00          | 0.00                            | 0.00             | 13.22                       | 0.00                              | 5687.65                              | 2383.52                    | 408.27                          | 237.31                 | 
| 201012                  | 3                  | CLAYTON                 | N                      | CST                | 0                   | 6497.27            | 0.00                         | 0.00          | 0.00                            | 0.00             | 3.31                        | 0.00                              | 1421.91                              | 594.26                     | 101.35                          | 33.55                  | 
| 201012                  | 3                  | COATSBURG               | N                      | ST                 | 12                  | 26808.29           | 0.00                         | 0.00          | 0.00                            | 0.00             | 0.00                        | 0.00                              | 0.00                                 | 411.27                     | 0.00                            | 0.00                   | 
```