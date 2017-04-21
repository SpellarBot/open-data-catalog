# ISTHA Illinois Tollway Oases

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/istha-illinois-tollway-oases-ee998) |
| Metadata | [Link](https://data.illinois.gov/api/views/zyh4-gim7) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/zyh4-gim7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/zyh4-gim7/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | zyh4-gim7 |
| Name | ISTHA Illinois Tollway Oases |
| Category | Transportation |
| Tags | tollway, istha, oasis, oases, restaurant, food, fuel, travel |
| Created | 2011-07-22T16:59:53Z |
| Publication Date | 2012-01-26T16:33:21Z |

## Description

Information for all seven Tollway Oases on the Illinois Tollway system including location and vendors

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| No       | time           | :updated_at | updated_at  | meta_data | meta_data   |
| Yes      | series tag     | name        | Name        | text      | text        |
| Yes      | series tag     | route       | Route       | text      | number      |
| Yes      | series tag     | milepost    | Milepost    | text      | number      |
| Yes      | series tag     | city        | City        | text      | text        |
| Yes      | numeric metric | opened      | Opened      | number    | text        |
| Yes      | series tag     | reopened    | Reopened    | text      | text        |
| Yes      | series tag     | merchant_1  | Merchant 1  | text      | text        |
| Yes      | series tag     | merchant_2  | Merchant 2  | text      | text        |
| Yes      | series tag     | merchant_3  | Merchant 3  | text      | text        |
| Yes      | series tag     | merchant_4  | Merchant 4  | text      | text        |
| Yes      | series tag     | merchant_5  | Merchant 5  | text      | text        |
| Yes      | series tag     | merchant_6  | Merchant 6  | text      | text        |
| Yes      | series tag     | merchant7   | Merchant7   | text      | text        |
| Yes      | series tag     | merchant_8  | Merchant 8  | text      | text        |
| Yes      | series tag     | merchant_9  | Merchant 9  | text      | text        |
| Yes      | series tag     | merchant_10 | Merchant 10 | text      | text        |
| Yes      | series tag     | merchant_11 | Merchant 11 | text      | text        |
| Yes      | series tag     | merchant_12 | Merchant 12 | text      | text        |
| Yes      | series tag     | merchant_13 | Merchant 13 | text      | text        |
| Yes      | series tag     | merchant_14 | Merchant 14 | text      | text        |
| Yes      | series tag     | merchant_15 | Merchant 15 | text      | text        |
| Yes      | series tag     | merchant_16 | Merchant 16 | text      | text        |
| Yes      | series tag     | free_wi_fi  | Free Wi-Fi  | text      | text        |
| Yes      | series tag     | hyperlink   | Hyperlink   | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:zyh4-gim7 d:2011-07-22T09:59:55.000Z t:merchant_1="Illinois Tollway Customer Service Center" t:merchant_2="Auntie Anne's" t:merchant_5="Jaffa Bakery" t:merchant_6=McDonald's t:milepost=38 t:merchant_3="A&A Electronics" t:merchant_4="Illinois Lottery" t:free_wi_fi=Y t:city="Schiller Park" t:reopened=6/30/04 t:merchant_13="7-Eleven Convenience Store" t:merchant_8=Starbucks t:merchant_12="Fifth Third Bank ATM" t:route=294 t:merchant_9="Kronos Gyros" t:name="O'Hare Oasis" t:hyperlink="http://www.illinoistollway.com/portal/page?_dad=portal&_schema=PORTAL&_pageid=133,1401312" t:merchant7="Panda Express" t:merchant_11="Travel Mart" t:merchant_10=Subway m:opened=1959

series e:zyh4-gim7 d:2011-07-22T09:59:55.000Z t:merchant_1="Ashby's Sterling Ice Cream" t:merchant_2="Auntie Anne's" t:merchant_5=McDonald's t:merchant_6="Panda Express" t:milepost=25 t:merchant_3="Kronos Gyros" t:merchant_4="Illinois Lottery" t:free_wi_fi=Y t:city=Hinsdale t:reopened=2/18/05 t:merchant_13="7-Eleven Convenience Store" t:merchant_8=Starbucks t:merchant_12="Mobile I-PASS" t:route=294 t:merchant_9=Subway t:name="Hinsdale Oasis" t:hyperlink="http://www.illinoistollway.com/portal/page?_dad=portal&_schema=PORTAL&_pageid=133,1401313" t:merchant7="Pagecomm Wireless" t:merchant_11="Fifth Third Bank ATM" t:merchant_10="Travel Mart" m:opened=1959

series e:zyh4-gim7 d:2011-07-22T09:59:55.000Z t:merchant_1="Illinois Tollway Customer Service Center" t:merchant_2="Auntie Anne's" t:merchant_5=Starbucks t:merchant_6=Subway t:milepost=1 t:merchant_3=McDonald's t:merchant_4="Panda Express" t:free_wi_fi=Y t:city="South Holland" t:reopened=2/24/06 t:merchant_8="Illinois Lottery" t:route=294 t:merchant_9="Fifth Third Bank ATM" t:name="Chicago Southland Lincoln Oasis" t:hyperlink="http://www.illinoistollway.com/portal/page?_dad=portal&_schema=PORTAL&_pageid=133,1401314" t:merchant7="Travel Mart" t:merchant_10="7-Eleven Convenience Store" m:opened=1968
```

## Meta Commands

```ls
metric m:opened p:integer l:Opened t:dataTypeName=number

entity e:zyh4-gim7 l:"ISTHA Illinois Tollway Oases" t:url=https://data.illinois.gov/api/views/zyh4-gim7

property e:zyh4-gim7 t:meta.view v:id=zyh4-gim7 v:category=Transportation v:attributionLink=http://www.illinoistollway.com/ v:averageRating=0 v:name="ISTHA Illinois Tollway Oases"

property e:zyh4-gim7 t:meta.view.license v:name="Public Domain"

property e:zyh4-gim7 t:meta.view.owner v:id=vtpi-ktes v:profileImageUrlMedium=/api/users/vtpi-ktes/profile_images/THUMB v:profileImageUrlLarge=/api/users/vtpi-ktes/profile_images/LARGE v:screenName=Brad v:profileImageUrlSmall=/api/users/vtpi-ktes/profile_images/TINY v:displayName=Brad

property e:zyh4-gim7 t:meta.view.tableauthor v:id=vtpi-ktes v:profileImageUrlMedium=/api/users/vtpi-ktes/profile_images/THUMB v:profileImageUrlLarge=/api/users/vtpi-ktes/profile_images/LARGE v:screenName=Brad v:profileImageUrlSmall=/api/users/vtpi-ktes/profile_images/TINY v:roleName=publisher v:displayName=Brad
```

## Top Records

```ls
| :updated_at | name                            | route | milepost | city          | opened | reopened | merchant_1                               | merchant_2                 | merchant_3      | merchant_4       | merchant_5       | merchant_6           | merchant7         | merchant_8                 | merchant_9           | merchant_10                | merchant_11          | merchant_12          | merchant_13                | merchant_14                | merchant_15                | merchant_16                | free_wi_fi | hyperlink                                                                                         | 
| =========== | =============================== | ===== | ======== | ============= | ====== | ======== | ======================================== | ========================== | =============== | ================ | ================ | ==================== | ================= | ========================== | ==================== | ========================== | ==================== | ==================== | ========================== | ========================== | ========================== | ========================== | ========== | ================================================================================================= | 
| 1311328795  | O'Hare Oasis                    | 294   | 38       | Schiller Park | 1959   | 6/30/04  | Illinois Tollway Customer Service Center | Auntie Anne's              | A&A Electronics | Illinois Lottery | Jaffa Bakery     | McDonald's           | Panda Express     | Starbucks                  | Kronos Gyros         | Subway                     | Travel Mart          | Fifth Third Bank ATM | 7-Eleven Convenience Store |                            |                            |                            | Y          | [http://www.illinoistollway.com/portal/page?_dad=portal&_schema=PORTAL&_pageid=133,1401312, null] | 
| 1311328795  | Hinsdale Oasis                  | 294   | 25       | Hinsdale      | 1959   | 2/18/05  | Ashby's Sterling Ice Cream               | Auntie Anne's              | Kronos Gyros    | Illinois Lottery | McDonald's       | Panda Express        | Pagecomm Wireless | Starbucks                  | Subway               | Travel Mart                | Fifth Third Bank ATM | Mobile I-PASS        | 7-Eleven Convenience Store |                            |                            |                            | Y          | [http://www.illinoistollway.com/portal/page?_dad=portal&_schema=PORTAL&_pageid=133,1401313, null] | 
| 1311328795  | Chicago Southland Lincoln Oasis | 294   | 1        | South Holland | 1968   | 2/24/06  | Illinois Tollway Customer Service Center | Auntie Anne's              | McDonald's      | Panda Express    | Starbucks        | Subway               | Travel Mart       | Illinois Lottery           | Fifth Third Bank ATM | 7-Eleven Convenience Store |                      |                      |                            |                            |                            |                            | Y          | [http://www.illinoistollway.com/portal/page?_dad=portal&_schema=PORTAL&_pageid=133,1401314, null] | 
| 1311328795  | Lake Forest Oasis               | 94    | 18       | Lake Forest   | 1959   | 2/18/05  | Illinois Tollway Customer Service Center | American Trade Links       | Auntie Anne's   | Illinois Lottery | Kronos Gyros     | McDonald's           | Merry Berry       | Pagecomm Wireless          | Panda Express        | Sbarro                     | Subway               | Starbucks            | Taco Bell / KFC            | Travel Mart                | Fifth Third Bank ATM       | 7-Eleven Convenience Store | Y          | [http://www.illinoistollway.com/portal/page?_dad=portal&_schema=PORTAL&_pageid=133,1401290, null] | 
| 1311328795  | Des Plaines Oasis               | 90    | 74.5     | Des Plaines   | 1959   | 8/10/05  | Illinois Tollway Customer Service Center | Auntie Anne's              | A&A Electronics | Baskin-Robbins   | Illinois Lottery | McDonald's           | Panda Express     | Sbarro                     | Starbucks            | Subway                     | Taco Bell/KFC        | Travel Mart          | Fifth Third Bank ATM       | 7-Eleven Convenience Store |                            |                            | Y          | [http://www.illinoistollway.com/portal/page?_dad=portal&_schema=PORTAL&_pageid=133,1401316, null] | 
| 1311328795  | Belvidere Oasis                 | 90    | 24       | Belvidere     | 1959   | 6/30/04  | Customer Service Center                  | Ashby's Sterling Ice Cream | Auntie Anne's   | Illinois Lottery | IM Wireless      | McDonald's           | Panda Express     | Starbucks                  | Kronos Gyros         | Sbarro                     | Subway               | Travel Mart          | Taco Bell                  | Fifth Third Bank ATM       | 7-Eleven Convenience Store |                            | Y          | [http://www.illinoistollway.com/portal/page?_dad=portal&_schema=PORTAL&_pageid=133,1401315, null] | 
| 1311328795  | DeKalb Oasis                    | 88    | 93       | DeKalb        | 1975   | 7/21/05  | McDonald's                               | Panda Express              | Starbucks       | Subway           | Travel Mart      | Fifth Third Bank ATM | Mobile I-PASS     | 7-Eleven Convenience Store |                      |                            |                      |                      |                            |                            |                            |                            | Y          | [http://www.illinoistollway.com/portal/page?_dad=portal&_schema=PORTAL&_pageid=133,1389668, null] | 
```