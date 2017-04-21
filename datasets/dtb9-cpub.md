# ISTHA Coordinates for Mileposts on the Illinois Tollway, I-355

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/istha-coordinates-for-mileposts-on-the-illinois-tollway-i-355-3380d) |
| Metadata | [Link](https://data.illinois.gov/api/views/dtb9-cpub) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/dtb9-cpub/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/dtb9-cpub/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | dtb9-cpub |
| Name | ISTHA Coordinates for Mileposts on the Illinois Tollway, I-355 |
| Category | Transportation |
| Tags | tollway, i-355, veterans memorial tollway, mileposts, mile marker, istha |
| Created | 2012-01-24T18:57:21Z |
| Publication Date | 2012-01-24T18:59:40Z |

## Description

This dataset has a record for every milepost on I-355 of the Illinois Tollway that includes the route number, the milepost and the latitude and longitude. It lists a milepost every tenth of mile, and every quarter of a mile, but there is actually only a physical milepost every quarter of a mile.

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
series e:dtb9-cpub d:2012-01-24T10:57:25.000Z t:milepost=0 t:route=355 m:row_number.dtb9-cpub=1

series e:dtb9-cpub d:2012-01-24T10:57:25.000Z t:milepost=0.1 t:route=355 m:row_number.dtb9-cpub=2

series e:dtb9-cpub d:2012-01-24T10:57:25.000Z t:milepost=0.2 t:route=355 m:row_number.dtb9-cpub=3
```

## Meta Commands

```ls
metric m:row_number.dtb9-cpub p:long l:"Row Number"

entity e:dtb9-cpub l:"ISTHA Coordinates for Mileposts on the Illinois Tollway, I-355" t:url=https://data.illinois.gov/api/views/dtb9-cpub

property e:dtb9-cpub t:meta.view v:id=dtb9-cpub v:category=Transportation v:averageRating=0 v:name="ISTHA Coordinates for Mileposts on the Illinois Tollway, I-355"

property e:dtb9-cpub t:meta.view.owner v:id=vtpi-ktes v:profileImageUrlMedium=/api/users/vtpi-ktes/profile_images/THUMB v:profileImageUrlLarge=/api/users/vtpi-ktes/profile_images/LARGE v:screenName=Brad v:profileImageUrlSmall=/api/users/vtpi-ktes/profile_images/TINY v:displayName=Brad

property e:dtb9-cpub t:meta.view.tableauthor v:id=vtpi-ktes v:profileImageUrlMedium=/api/users/vtpi-ktes/profile_images/THUMB v:profileImageUrlLarge=/api/users/vtpi-ktes/profile_images/LARGE v:screenName=Brad v:profileImageUrlSmall=/api/users/vtpi-ktes/profile_images/TINY v:roleName=publisher v:displayName=Brad
```

## Top Records

```ls
| :updated_at | route | milepost | 
| =========== | ===== | ======== | 
| 1327402645  | 355   | 0        | 
| 1327402645  | 355   | 0.1      | 
| 1327402645  | 355   | 0.2      | 
| 1327402645  | 355   | 0.25     | 
| 1327402645  | 355   | 0.3      | 
| 1327402645  | 355   | 0.4      | 
| 1327402645  | 355   | 0.5      | 
| 1327402645  | 355   | 0.6      | 
| 1327402645  | 355   | 0.7      | 
| 1327402645  | 355   | 0.75     | 
```