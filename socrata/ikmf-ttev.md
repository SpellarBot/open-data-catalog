# ISTHA Coordinates for Mileposts on the Illinois Tollway, I-90

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/istha-coordinates-for-mileposts-on-the-illinois-tollway-i-90-f1254) |
| Metadata | [Link](https://data.illinois.gov/api/views/ikmf-ttev) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/ikmf-ttev/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/ikmf-ttev/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | ikmf-ttev |
| Name | ISTHA Coordinates for Mileposts on the Illinois Tollway, I-90 |
| Tags | tollway, i-90, jane addams memorial tollway, mileposts, mile marker, istha |
| Created | 2012-01-24T19:28:24Z |
| Publication Date | 2012-01-24T19:30:20Z |

## Description

This dataset has a record for every milepost on I-90 of the Illinois Tollway that includes the route number, the milepost and the latitude and longitude. It lists a milepost every tenth of mile, and every quarter of a mile, but there is actually only a physical milepost every quarter of a mile.

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | route       | Route      | text      | number      |
| Yes      | series tag  | milepost    | Milepost   | text      | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ikmf-ttev d:2012-01-24T11:28:31.000Z t:milepost=0 t:route=90 m:row_number.ikmf-ttev=1

series e:ikmf-ttev d:2012-01-24T11:28:31.000Z t:milepost=0.1 t:route=90 m:row_number.ikmf-ttev=2

series e:ikmf-ttev d:2012-01-24T11:28:31.000Z t:milepost=0.2 t:route=90 m:row_number.ikmf-ttev=3
```

## Meta Commands

```ls
metric m:row_number.ikmf-ttev p:long l:"Row Number"

entity e:ikmf-ttev l:"ISTHA Coordinates for Mileposts on the Illinois Tollway, I-90" t:url=https://data.illinois.gov/api/views/ikmf-ttev

property e:ikmf-ttev t:meta.view v:id=ikmf-ttev v:averageRating=0 v:name="ISTHA Coordinates for Mileposts on the Illinois Tollway, I-90"

property e:ikmf-ttev t:meta.view.owner v:id=vtpi-ktes v:profileImageUrlMedium=/api/users/vtpi-ktes/profile_images/THUMB v:profileImageUrlLarge=/api/users/vtpi-ktes/profile_images/LARGE v:screenName=Brad v:profileImageUrlSmall=/api/users/vtpi-ktes/profile_images/TINY v:displayName=Brad

property e:ikmf-ttev t:meta.view.tableauthor v:id=vtpi-ktes v:profileImageUrlMedium=/api/users/vtpi-ktes/profile_images/THUMB v:profileImageUrlLarge=/api/users/vtpi-ktes/profile_images/LARGE v:screenName=Brad v:profileImageUrlSmall=/api/users/vtpi-ktes/profile_images/TINY v:roleName=publisher v:displayName=Brad
```

## Top Records

```ls
| :updated_at | route | milepost | 
| =========== | ===== | ======== | 
| 1327404511  | 90    | 0        | 
| 1327404511  | 90    | 0.1      | 
| 1327404511  | 90    | 0.2      | 
| 1327404511  | 90    | 0.25     | 
| 1327404511  | 90    | 0.3      | 
| 1327404511  | 90    | 0.4      | 
| 1327404511  | 90    | 0.5      | 
| 1327404511  | 90    | 0.6      | 
| 1327404511  | 90    | 0.7      | 
| 1327404511  | 90    | 0.75     | 
```