# ISTHA Coordinates for Mileposts on the Illinois Tollway, I-94

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/istha-coordinates-for-mileposts-on-the-illinois-tollway-i-94-cee8f) |
| Metadata | [Link](https://data.illinois.gov/api/views/g8gh-wnt9) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/g8gh-wnt9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/g8gh-wnt9/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | g8gh-wnt9 |
| Name | ISTHA Coordinates for Mileposts on the Illinois Tollway, I-94 |
| Category | Transportation |
| Tags | tollway, i-94, tri-state tollway, mileposts, mile marker, istha |
| Created | 2012-01-24T19:34:52Z |
| Publication Date | 2012-01-24T19:36:36Z |

## Description

This dataset has a record for every milepost on I-94 of the Illinois Tollway that includes the route number, the milepost and the latitude and longitude. It lists a milepost every tenth of mile, and every quarter of a mile, but there is actually only a physical milepost every quarter of a mile.

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
series e:g8gh-wnt9 d:2012-01-24T11:35:02.000Z t:milepost=0 t:route=94 m:row_number.g8gh-wnt9=1

series e:g8gh-wnt9 d:2012-01-24T11:35:02.000Z t:milepost=0.1 t:route=94 m:row_number.g8gh-wnt9=2

series e:g8gh-wnt9 d:2012-01-24T11:35:02.000Z t:milepost=0.2 t:route=94 m:row_number.g8gh-wnt9=3
```

## Meta Commands

```ls
metric m:row_number.g8gh-wnt9 p:long l:"Row Number"

entity e:g8gh-wnt9 l:"ISTHA Coordinates for Mileposts on the Illinois Tollway, I-94" t:url=https://data.illinois.gov/api/views/g8gh-wnt9

property e:g8gh-wnt9 t:meta.view v:id=g8gh-wnt9 v:category=Transportation v:averageRating=0 v:name="ISTHA Coordinates for Mileposts on the Illinois Tollway, I-94"

property e:g8gh-wnt9 t:meta.view.owner v:id=vtpi-ktes v:profileImageUrlMedium=/api/users/vtpi-ktes/profile_images/THUMB v:profileImageUrlLarge=/api/users/vtpi-ktes/profile_images/LARGE v:screenName=Brad v:profileImageUrlSmall=/api/users/vtpi-ktes/profile_images/TINY v:displayName=Brad

property e:g8gh-wnt9 t:meta.view.tableauthor v:id=vtpi-ktes v:profileImageUrlMedium=/api/users/vtpi-ktes/profile_images/THUMB v:profileImageUrlLarge=/api/users/vtpi-ktes/profile_images/LARGE v:screenName=Brad v:profileImageUrlSmall=/api/users/vtpi-ktes/profile_images/TINY v:roleName=publisher v:displayName=Brad
```

## Top Records

```ls
| :updated_at | route | milepost | 
| =========== | ===== | ======== | 
| 1327404902  | 94    | 0        | 
| 1327404902  | 94    | 0.1      | 
| 1327404902  | 94    | 0.2      | 
| 1327404902  | 94    | 0.25     | 
| 1327404902  | 94    | 0.3      | 
| 1327404902  | 94    | 0.4      | 
| 1327404902  | 94    | 0.5      | 
| 1327404902  | 94    | 0.6      | 
| 1327404902  | 94    | 0.7      | 
| 1327404902  | 94    | 0.75     | 
```