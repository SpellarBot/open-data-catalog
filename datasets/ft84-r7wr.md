# Food Inspection - LIVES standard

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/food-inspection-lives-standard) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/ft84-r7wr) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/ft84-r7wr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/ft84-r7wr/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | ft84-r7wr |
| Name | Food Inspection - LIVES standard |
| Category | Health and Human Services |
| Tags | lives, food, inspection, violations, closures, restaurant, yelp, standard |
| Created | 2015-11-03T18:39:45Z |
| Publication Date | 2015-11-03T18:48:16Z |

## Description

Current food Inspection dataset published using LIVES data standard.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type     | Render Type   |
| ======== | ============== | ===================== | ===================== | ============= | ============= |
| Yes      | series tag     | business_id           | business_id           | text          | text          |
| Yes      | series tag     | business_name         | business_name         | text          | text          |
| No       |                | business_address      | business_address      | text          | text          |
| Yes      | series tag     | business_city         | business_city         | text          | text          |
| Yes      | series tag     | business_state        | business_state        | text          | text          |
| Yes      | series tag     | business_postal_code  | business_postal_code  | text          | text          |
| No       |                | business_latitude     | business_latitude     | number        | number        |
| Yes      | numeric metric | business_longitude    | business_longitude    | number        | number        |
| Yes      | series tag     | inspection_id         | inspection_id         | text          | text          |
| Yes      | time           | inspection_date       | inspection_date       | calendar_date | calendar_date |
| Yes      | series tag     | inspection_result     | inspection_result     | text          | text          |
| Yes      | series tag     | inspection_type       | inspection_type       | text          | text          |
| Yes      | series tag     | violation_id          | violation_id          | text          | text          |
| Yes      | series tag     | violation_description | violation_description | text          | text          |
| Yes      | series tag     | violation_critical    | violation_critical    | text          | text          |
```

## Time Field

```ls
Value = inspection_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = business_address,business_latitude
```

## Data Commands

```ls
series e:ft84-r7wr d:2016-03-10T00:00:00.000Z t:business_name="FLOWER HILL ELEMENTARY" t:inspection_result=PASS t:business_postal_code=20879 t:inspection_id=938_2016-03-10 t:business_id=938 t:inspection_type=routine t:business_city=GAITHERSBURG t:business_state=MD m:business_longitude=-77.171

series e:ft84-r7wr d:2016-01-06T00:00:00.000Z t:business_name="SHOPPERS FOOD WAREHOUSE" t:inspection_result=PASS t:business_postal_code=20895 t:inspection_id=11598_2016-01-06 t:business_id=11598 t:inspection_type=routine t:business_city=KENSINGTON t:business_state=MD m:business_longitude=-77.1047

series e:ft84-r7wr d:2016-02-08T00:00:00.000Z t:business_name="ROCK CAF?" t:inspection_result=PASS t:business_postal_code=20817 t:inspection_id=1187_2016-02-08 t:business_id=1187 t:inspection_type=routine t:business_city=BETHESDA t:business_state=MD m:business_longitude=-77.1335
```

## Meta Commands

```ls
metric m:business_longitude p:float l:business_longitude t:dataTypeName=number

entity e:ft84-r7wr l:"Food Inspection - LIVES standard" t:url=https://data.montgomerycountymd.gov/api/views/ft84-r7wr

property e:ft84-r7wr t:meta.view v:id=ft84-r7wr v:category="Health and Human Services" v:averageRating=0 v:name="Food Inspection - LIVES standard"

property e:ft84-r7wr t:meta.view.owner v:id=trc9-69xh v:profileImageUrlMedium=/api/users/trc9-69xh/profile_images/THUMB v:profileImageUrlLarge=/api/users/trc9-69xh/profile_images/LARGE v:screenName="Socrata (DoNotDelete)" v:profileImageUrlSmall=/api/users/trc9-69xh/profile_images/TINY v:displayName="Socrata (DoNotDelete)"

property e:ft84-r7wr t:meta.view.tableauthor v:id=trc9-69xh v:profileImageUrlMedium=/api/users/trc9-69xh/profile_images/THUMB v:profileImageUrlLarge=/api/users/trc9-69xh/profile_images/LARGE v:screenName="Socrata (DoNotDelete)" v:profileImageUrlSmall=/api/users/trc9-69xh/profile_images/TINY v:displayName="Socrata (DoNotDelete)"
```

## Top Records

```ls
| business_id | business_name           | business_address         | business_city | business_state | business_postal_code | business_latitude | business_longitude | inspection_id    | inspection_date     | inspection_result | inspection_type | violation_id                               | violation_description                          | violation_critical | 
| =========== | ======================= | ======================== | ============= | ============== | ==================== | ================= | ================== | ================ | =================== | ================= | =============== | ========================================== | ============================================== | ================== | 
| 938         | FLOWER HILL ELEMENTARY  | 18425 FLOWER HILL WAY    | GAITHERSBURG  | MD             | 20879                | 39.1592           | -77.171            | 938_2016-03-10   | 2016-03-10T00:00:00 | PASS              | routine         |                                            |                                                |                    | 
| 11598       | SHOPPERS FOOD WAREHOUSE | 5110 NICHOLSON LN.       | KENSINGTON    | MD             | 20895                | 39.0445           | -77.1047           | 11598_2016-01-06 | 2016-01-06T00:00:00 | PASS              | routine         |                                            |                                                |                    | 
| 1187        | ROCK CAF?               | 6600 ROCKLEDGE DR.       | BETHESDA      | MD             | 20817                | 39.0276           | -77.1335           | 1187_2016-02-08  | 2016-02-08T00:00:00 | PASS              | routine         |                                            |                                                |                    | 
| 19057       | CAVA MEZZE GRILL        | 9713 TRAVILLE GATEWAY DR | ROCKVILLE     | MD             | 20850                | 39.0915           | -77.2039           | 19057_2015-05-05 | 2015-05-05T00:00:00 | PASS              | routine         |                                            |                                                |                    | 
| 19057       | CAVA MEZZE GRILL        | 9713 TRAVILLE GATEWAY DR | ROCKVILLE     | MD             | 20850                | 39.0915           | -77.2039           | 19057_2016-02-04 | 2016-02-04T00:00:00 | PASS              | routine         | 19057_2016-02-04_ColdHoldingTemperature(C) | Standard not met: Cold Holding Temperature (C) | true               | 
| 18858       | CAF? 2020               | 4870 BOILING BROOK PKWY. | ROCKVILLE     | MD             | 20852                | 39.046            | -77.0996           | 18858_2015-10-31 | 2015-10-31T00:00:00 | PASS              | routine         | 18858_2015-10-31_RodentandInsects          | Standard not met: Rodent and Insects           | false              | 
| 18420       | SKKY MARKET             | 108-G OLDE TOWNE AVE.    | GAITHERSBURG  | MD             | 20877                | 39.1409           | -77.1947           | 18420_2016-02-08 | 2016-02-08T00:00:00 | PASS              | routine         | 18420_2016-02-08_ColdHoldingTemperature(C) | Standard not met: Cold Holding Temperature (C) | true               | 
| 23829       | UPTOWN PIEDMONT, LLC    | 6720-A ROCKLEDGE DRIVE   | BETHESDA      | MD             | 20817                | 39.0291           | -77.1377           | 23829_2016-02-08 | 2016-02-08T00:00:00 | PASS              | routine         | 23829_2016-02-08_ColdHoldingTemperature(C) | Standard not met: Cold Holding Temperature (C) | true               | 
| 28110       | CAVA MEZZE GRILL        | 7101 DEMOCRACY BLVD      | BETHESDA      | MD             | 20817                | 39.0221           | -77.1471           | 28110_2015-09-11 | 2015-09-11T00:00:00 | PASS              | routine         |                                            |                                                |                    | 
| 18420       | SKKY MARKET             | 108-G OLDE TOWNE AVE.    | GAITHERSBURG  | MD             | 20877                | 39.1409           | -77.1947           | 18420_2016-02-08 | 2016-02-08T00:00:00 | PASS              | routine         | 18420_2016-02-08_RodentandInsects          | Standard not met: Rodent and Insects           | false              | 
```