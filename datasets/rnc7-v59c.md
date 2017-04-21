# ISTHA Coordinates for Mileposts on the Illinois Tollway, I-294 Tri-State

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/istha-coordinates-for-mileposts-on-the-illinois-tollway-i-294-tri-state-323c2) |
| Metadata | [Link](https://data.illinois.gov/api/views/rnc7-v59c) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/rnc7-v59c/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/rnc7-v59c/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | rnc7-v59c |
| Name | ISTHA Coordinates for Mileposts on the Illinois Tollway, I-294 Tri-State |
| Category | Transportation |
| Tags | tollway, i-294, tri-state tollway, mileposts, mile marker, istha |
| Created | 2012-01-24T18:45:37Z |
| Publication Date | 2012-01-24T18:52:34Z |

## Description

This dataset has a record for every milepost on I-294 of the Illinois Tollway that includes the route number, the milepost and the latitude and longitude. It lists a milepost every tenth of mile, and every quarter of a mile, but there is actually only a physical milepost every quarter of a mile.

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
series e:rnc7-v59c d:2012-01-24T10:45:43.000Z t:milepost=0 t:route=294 m:row_number.rnc7-v59c=1

series e:rnc7-v59c d:2012-01-24T10:45:43.000Z t:milepost=0.1 t:route=294 m:row_number.rnc7-v59c=2

series e:rnc7-v59c d:2012-01-24T10:45:43.000Z t:milepost=0.2 t:route=294 m:row_number.rnc7-v59c=3
```

## Meta Commands

```ls
metric m:row_number.rnc7-v59c p:long l:"Row Number"

entity e:rnc7-v59c l:"ISTHA Coordinates for Mileposts on the Illinois Tollway, I-294 Tri-State" t:url=https://data.illinois.gov/api/views/rnc7-v59c

property e:rnc7-v59c t:meta.view v:id=rnc7-v59c v:category=Transportation v:averageRating=0 v:name="ISTHA Coordinates for Mileposts on the Illinois Tollway, I-294 Tri-State"

property e:rnc7-v59c t:meta.view.owner v:id=vtpi-ktes v:profileImageUrlMedium=/api/users/vtpi-ktes/profile_images/THUMB v:profileImageUrlLarge=/api/users/vtpi-ktes/profile_images/LARGE v:screenName=Brad v:profileImageUrlSmall=/api/users/vtpi-ktes/profile_images/TINY v:displayName=Brad

property e:rnc7-v59c t:meta.view.tableauthor v:id=vtpi-ktes v:profileImageUrlMedium=/api/users/vtpi-ktes/profile_images/THUMB v:profileImageUrlLarge=/api/users/vtpi-ktes/profile_images/LARGE v:screenName=Brad v:profileImageUrlSmall=/api/users/vtpi-ktes/profile_images/TINY v:roleName=publisher v:displayName=Brad
```

## Top Records

```ls
| :updated_at | route | milepost | 
| =========== | ===== | ======== | 
| 1327401943  | 294   | 0        | 
| 1327401943  | 294   | 0.1      | 
| 1327401943  | 294   | 0.2      | 
| 1327401943  | 294   | 0.25     | 
| 1327401943  | 294   | 0.3      | 
| 1327401943  | 294   | 0.4      | 
| 1327401943  | 294   | 0.5      | 
| 1327401943  | 294   | 0.6      | 
| 1327401943  | 294   | 0.7      | 
| 1327401943  | 294   | 0.75     | 
```