# Parks - Facilities & Features

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/parks-facilities-features-c4402) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/y7qa-tvqx) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/y7qa-tvqx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/y7qa-tvqx/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | y7qa-tvqx |
| Name | Parks - Facilities & Features |
| Attribution | Chicago Park District |
| Category | Parks & Recreation |
| Tags | parks, facilities, chicago park district, recreation, park, district, features, sustainability |
| Created | 2012-09-18T19:30:07Z |
| Publication Date | 2012-09-18T19:35:36Z |

## Description

Facilities located in Chicago Park District parks

## Columns

```ls
| Included | Schema Type | Field Name    | Name          | Data Type | Render Type |
| ======== | =========== | ============= | ============= | ========= | =========== |
| No       | time        | :updated_at   | updated_at    | meta_data | meta_data   |
| Yes      | series tag  | park          | PARK          | text      | text        |
| Yes      | series tag  | park_number   | PARK NUMBER   | text      | number      |
| Yes      | series tag  | facility_name | FACILITY NAME | text      | text        |
| Yes      | series tag  | facility_type | FACILITY TYPE | text      | text        |
| No       |             | x_coordinate  | X COORDINATE  | number    | number      |
| No       |             | y_coordinate  | Y COORDINATE  | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = x_coordinate,y_coordinate
```

## Data Commands

```ls
series e:y7qa-tvqx d:2012-09-18T12:30:09.000Z t:facility_name=PLAYGROUND t:park="ABBOTT (ROBERT)" t:park_number=259 t:facility_type=OUTDOOR m:row_number.y7qa-tvqx=1

series e:y7qa-tvqx d:2012-09-18T12:30:09.000Z t:facility_name="SENIOR CENTER" t:park="ABBOTT (ROBERT)" t:park_number=259 t:facility_type=INDOOR m:row_number.y7qa-tvqx=2

series e:y7qa-tvqx d:2012-09-18T12:30:09.000Z t:facility_name="SPRAY FEATURE" t:park="ABBOTT (ROBERT)" t:park_number=259 t:facility_type=OUTDOOR m:row_number.y7qa-tvqx=3
```

## Meta Commands

```ls
metric m:row_number.y7qa-tvqx p:long l:"Row Number"

entity e:y7qa-tvqx l:"Parks - Facilities & Features" t:attribution="Chicago Park District" t:url=https://data.cityofchicago.org/api/views/y7qa-tvqx

property e:y7qa-tvqx t:meta.view v:id=y7qa-tvqx v:category="Parks & Recreation" v:attributionLink=http://www.chicagoparkdistrict.com v:averageRating=0 v:name="Parks - Facilities & Features" v:attribution="Chicago Park District"

property e:y7qa-tvqx t:meta.view.license v:name="Public Domain"

property e:y7qa-tvqx t:meta.view.owner v:id=48zk-zxis v:profileImageUrlMedium=/api/users/48zk-zxis/profile_images/THUMB v:profileImageUrlLarge=/api/users/48zk-zxis/profile_images/LARGE v:screenName="CPD IT" v:profileImageUrlSmall=/api/users/48zk-zxis/profile_images/TINY v:displayName="CPD IT"

property e:y7qa-tvqx t:meta.view.tableauthor v:id=48zk-zxis v:profileImageUrlMedium=/api/users/48zk-zxis/profile_images/THUMB v:profileImageUrlLarge=/api/users/48zk-zxis/profile_images/LARGE v:screenName="CPD IT" v:profileImageUrlSmall=/api/users/48zk-zxis/profile_images/TINY v:roleName=editor v:displayName="CPD IT"
```

## Top Records

```ls
| :updated_at | park            | park_number | facility_name | facility_type | x_coordinate       | y_coordinate       | 
| =========== | =============== | =========== | ============= | ============= | ================== | ================== | 
| 1347971409  | ABBOTT (ROBERT) | 259         | PLAYGROUND    | OUTDOOR       | 1178619.54153      | 1841712.82415      | 
| 1347971409  | ABBOTT (ROBERT) | 259         | SENIOR CENTER | INDOOR        | 1178491.24651      | 1841782.61436      | 
| 1347971409  | ABBOTT (ROBERT) | 259         | SPRAY FEATURE | OUTDOOR       | 1178475.8803999999 | 1841904.3723200001 | 
| 1347971409  | ABBOTT (ROBERT) | 259         | SPRAY FEATURE | OUTDOOR       | 1178306.43389      | 1841899.4609099999 | 
| 1347971409  | ABBOTT (ROBERT) | 259         | BASEBALL SR   | OUTDOOR       | 1178678.4794000001 | 1841175.63001      | 
| 1347971409  | ABBOTT (ROBERT) | 259         | BASEBALL SR   | OUTDOOR       | 1178160.31705      | 1841164.5791799999 | 
| 1347971409  | ABBOTT (ROBERT) | 259         | TENNIS COURT  | OUTDOOR       | 1178080.5052100001 | 1841614.59436      | 
| 1347971409  | ABBOTT (ROBERT) | 259         | TENNIS COURT  | OUTDOOR       | 1178125.93655      | 1841614.59436      | 
| 1347971409  | ABBOTT (ROBERT) | 259         | TRACK         | OUTDOOR       | 1178253.6354400001 | 1840687.55061      | 
| 1347971409  | ABBOTT (ROBERT) | 259         | VOLLEYBALL    | OUTDOOR       | 1178064.5429700001 | 1841736.15383      | 
```