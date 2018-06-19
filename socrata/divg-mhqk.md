# Produce Carts

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/produce-carts-17e2b) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/divg-mhqk) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/divg-mhqk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/divg-mhqk/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | divg-mhqk |
| Name | Produce Carts |
| Attribution | City of Chicago |
| Category | Community & Economic Development |
| Tags | food, food desert |
| Created | 2013-08-27T03:47:09Z |
| Publication Date | 2013-08-27T03:48:52Z |

## Description

Neighbor Capital is a social enterprise that runs a produce cart program that employs difficult to employ people who manage and operate a cart on a public sidewalk or private plaza across the city. The City of Chicago legalized this business model in 2012 with the requirement that half be set up in low-food access areas. Each cart carries a full line of fresh locally grown produce on an 8 feet by 6 foot stand generally between early morning and early evening hours.

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| No       |             | address     | ADDRESS    | text      | text        |
| No       |             | latitude    | LATITUDE   | number    | number      |
| No       |             | longitude   | LONGITUDE  | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address,latitude,longitude
```

## Data Commands

```ls
series e:divg-mhqk d:2013-08-26T20:48:36.000Z m:row_number.divg-mhqk=1

series e:divg-mhqk d:2013-08-26T20:48:36.000Z m:row_number.divg-mhqk=2

series e:divg-mhqk d:2013-08-26T20:48:36.000Z m:row_number.divg-mhqk=3
```

## Meta Commands

```ls
metric m:row_number.divg-mhqk p:long l:"Row Number"

entity e:divg-mhqk l:"Produce Carts" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/divg-mhqk

property e:divg-mhqk t:meta.view v:id=divg-mhqk v:category="Community & Economic Development" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Produce Carts" v:attribution="City of Chicago"

property e:divg-mhqk t:meta.view.owner v:id=3qqc-w7ag v:profileImageUrlMedium=/api/users/3qqc-w7ag/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qqc-w7ag/profile_images/LARGE v:screenName="Tom Schenk Jr" v:profileImageUrlSmall=/api/users/3qqc-w7ag/profile_images/TINY v:lastNotificationSeenAt=1491330280 v:displayName="Tom Schenk Jr"

property e:divg-mhqk t:meta.view.tableauthor v:id=3qqc-w7ag v:profileImageUrlMedium=/api/users/3qqc-w7ag/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qqc-w7ag/profile_images/LARGE v:screenName="Tom Schenk Jr" v:profileImageUrlSmall=/api/users/3qqc-w7ag/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491330280 v:displayName="Tom Schenk Jr"
```

## Top Records

```ls
| :updated_at | address               | latitude    | longitude    | 
| =========== | ===================== | =========== | ============ | 
| 1377550116  | 721 N LA SALLE DR     | 41.89557507 | -87.63254328 | 
| 1377550116  | 4602 N BROADWAY       | 41.96547764 | -87.65768753 | 
| 1377550116  | 25 E CHICAGO AVE      | 41.89658176 | -87.62708766 | 
| 1377550116  | 3758 W OGDEN AVE      | 41.85307985 | -87.71965154 | 
| 1377550116  | 4020 W 26TH ST        | 41.84435111 | -87.72545519 | 
| 1377550116  | 1601 W DIVISION ST    | 41.90323582 | -87.66755407 | 
| 1377550116  | 1550 N DAMEN AVE      | 41.90967936 | -87.67759021 | 
| 1377550116  | 944 W ARMITAGE AVE    | 41.91822458 | -87.65272001 | 
| 1377550116  | 2650 S CALIFORNIA AVE | 41.84323835 | -87.69476454 | 
| 1377550116  | 3060 W 26TH ST        | 41.84466604 | -87.70254001 | 
```