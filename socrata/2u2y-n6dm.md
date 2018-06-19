# Parks - Buildings

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/parks-buildings-6a6d0) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/2u2y-n6dm) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/2u2y-n6dm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/2u2y-n6dm/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 2u2y-n6dm |
| Name | Parks - Buildings |
| Attribution | Chicago Park District |
| Category | Parks & Recreation |
| Tags | parks, recreation, buildings, park buildings, chicago, chicago parks, chicago park district, park district, sustainability |
| Created | 2012-09-18T20:20:44Z |
| Publication Date | 2012-09-18T20:23:00Z |

## Description

Buildings located in Chicago Park District Parks.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| No       | time           | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag     | park            | PARK            | text      | text        |
| Yes      | series tag     | park_number     | PARK NUMBER     | text      | number      |
| Yes      | series tag     | building_type   | BUILDING TYPE   | text      | text        |
| Yes      | series tag     | building_status | BUILDING STATUS | text      | text        |
| Yes      | series tag     | ward            | WARD            | text      | number      |
| Yes      | series tag     | community_area  | COMMUNITY AREA  | text      | number      |
| Yes      | series tag     | region          | REGION          | text      | text        |
| Yes      | series tag     | building_name   | BUILDING NAME   | text      | text        |
| Yes      | numeric metric | demolished      | DEMOLISHED      | number    | number      |
| Yes      | numeric metric | year_built      | YEAR BUILT      | number    | number      |
| No       |                | x_coordinate    | X COORDINATE    | number    | number      |
| No       |                | y_coordinate    | Y COORDINATE    | number    | number      |
| No       |                | location        | LOCATION        | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = x_coordinate,y_coordinate,location
```

## Data Commands

```ls
series e:2u2y-n6dm d:2012-09-18T13:20:46.000Z t:region=N t:ward=47 t:park="REVERE (PAUL)" t:park_number=185 t:building_status=ACTIVE t:community_area=5 t:building_type="FIELDHOUSE B1" m:year_built=0

series e:2u2y-n6dm d:2012-09-18T13:20:46.000Z t:region=S t:ward=19 t:park=RIDGE t:park_number=175 t:building_status=ACTIVE t:community_area=72 t:building_type="UTILITY STRUCTURE" m:year_built=0

series e:2u2y-n6dm d:2012-09-18T13:20:46.000Z t:region=S t:building_name="RIDGE PARK" t:ward=19 t:park=RIDGE t:park_number=175 t:building_status=ACTIVE t:community_area=72 t:building_type="FIELDHOUSE A2" m:year_built=0
```

## Meta Commands

```ls
metric m:demolished p:long l:DEMOLISHED t:dataTypeName=number

metric m:year_built p:integer l:"YEAR BUILT" t:dataTypeName=number

entity e:2u2y-n6dm l:"Parks - Buildings" t:attribution="Chicago Park District" t:url=https://data.cityofchicago.org/api/views/2u2y-n6dm

property e:2u2y-n6dm t:meta.view v:id=2u2y-n6dm v:category="Parks & Recreation" v:attributionLink=http://www.chicagoparkdistrict.com v:averageRating=0 v:name="Parks - Buildings" v:attribution="Chicago Park District"

property e:2u2y-n6dm t:meta.view.license v:name="Public Domain"

property e:2u2y-n6dm t:meta.view.owner v:id=48zk-zxis v:profileImageUrlMedium=/api/users/48zk-zxis/profile_images/THUMB v:profileImageUrlLarge=/api/users/48zk-zxis/profile_images/LARGE v:screenName="CPD IT" v:profileImageUrlSmall=/api/users/48zk-zxis/profile_images/TINY v:displayName="CPD IT"

property e:2u2y-n6dm t:meta.view.tableauthor v:id=48zk-zxis v:profileImageUrlMedium=/api/users/48zk-zxis/profile_images/THUMB v:profileImageUrlLarge=/api/users/48zk-zxis/profile_images/LARGE v:screenName="CPD IT" v:profileImageUrlSmall=/api/users/48zk-zxis/profile_images/TINY v:roleName=editor v:displayName="CPD IT"
```

## Top Records

```ls
| :updated_at | park          | park_number | building_type     | building_status | ward | community_area | region | building_name | demolished | year_built | x_coordinate       | y_coordinate       | location                | 
| =========== | ============= | =========== | ================= | =============== | ==== | ============== | ====== | ============= | ========== | ========== | ================== | ================== | ======================= | 
| 1347974446  | REVERE (PAUL) | 185         | FIELDHOUSE B1     | ACTIVE          | 47   | 5              | N      |               |            | 0          | 1158687.38815      | 1926350.46426      | (41.953644, -87.692044) | 
| 1347974446  | RIDGE         | 175         | UTILITY STRUCTURE | ACTIVE          | 19   | 72             | S      |               |            | 0          | 1165999.8640099999 | 1840625.5907600001 | (41.718253, -87.667605) | 
| 1347974446  | RIDGE         | 175         | FIELDHOUSE A2     | ACTIVE          | 19   | 72             | S      | RIDGE PARK    |            | 0          | 1165816.8571599999 | 1840063.1338800001 | (41.716714, -87.668292) | 
| 1347974446  | RIDGE         | 175         | FIELDHOUSE A2     | ACTIVE          | 19   | 72             | S      | RIDGE PARK    |            | 0          | 1165956.0461899999 | 1840740.2079799999 | (41.718569, -87.667763) | 
| 1347974446  | RIIS (JACOB)  | 123         | FIELDHOUSE A3     | ACTIVE          | 29   | 19             | N      | RIIS PARK     |            | 0          | 1135219.6893499999 | 1915450.76657      | (41.924184, -87.778574) | 
| 1347974446  | RIIS (JACOB)  | 123         | UNIDENTIFIED      | ACTIVE          | 29   | 19             | N      |               |            | 0          | 1134392.5043299999 | 1916301.0752300001 | (41.926532, -87.781594) | 
| 1347974446  | RIIS (JACOB)  | 123         | UNIDENTIFIED      | ACTIVE          | 29   | 19             | N      |               |            | 0          | 1134900.8622399999 | 1916437.91157      | (41.926898, -87.779722) | 
| 1347974446  | RIIS (JACOB)  | 123         | POOL BUILDING     | ACTIVE          | 29   | 19             | N      |               |            | 0          | 1134903.6250199999 | 1915421.7449700001 | (41.92411, -87.779736)  | 
| 1347974446  | RIIS (JACOB)  | 123         | FIELDHOUSE A3     | ACTIVE          | 29   | 19             | N      | RIIS PARK     |            | 0          | 1134985.7337799999 | 1915667.0414       | (41.924781, -87.779429) | 
| 1347974446  | RIIS (JACOB)  | 123         | MAINTENANCE       | ACTIVE          | 29   | 19             | N      |               |            | 0          | 1134057.66215      | 1915420.7849999999 | (41.924122, -87.782845) | 
```