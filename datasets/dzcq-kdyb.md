# ISTHA - Coordinates for Mileposts on the Illinois Tollway, I-88

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/istha-coordinates-for-mileposts-on-the-illinois-tollway-i-88-aa013) |
| Metadata | [Link](https://data.illinois.gov/api/views/dzcq-kdyb) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/dzcq-kdyb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/dzcq-kdyb/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | dzcq-kdyb |
| Name | ISTHA - Coordinates for Mileposts on the Illinois Tollway, I-88 |
| Category | Transportation |
| Tags | tollway, i-88, ronald reagan memorial tollway, mileposts, mile marker, istha |
| Created | 2012-01-24T18:20:20Z |
| Publication Date | 2012-01-24T18:31:07Z |

## Description

This dataset has a record for every milepost on I-88 of the Illinois Tollway that includes the route number, the milepost and the latitude and longitude. It lists a milepost every tenth of mile, and every quarter of a mile, but there is actually only a physical milepost every quarter of a mile.

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
series e:dzcq-kdyb d:2012-01-24T10:20:27.000Z m:row_number.dzcq-kdyb=1

series e:dzcq-kdyb d:2012-01-24T10:20:27.000Z t:milepost=43.8 t:route=88 m:row_number.dzcq-kdyb=2

series e:dzcq-kdyb d:2012-01-24T10:20:27.000Z t:milepost=43.9 t:route=88 m:row_number.dzcq-kdyb=3
```

## Meta Commands

```ls
metric m:row_number.dzcq-kdyb p:long l:"Row Number"

entity e:dzcq-kdyb l:"ISTHA - Coordinates for Mileposts on the Illinois Tollway, I-88" t:url=https://data.illinois.gov/api/views/dzcq-kdyb

property e:dzcq-kdyb t:meta.view v:id=dzcq-kdyb v:category=Transportation v:averageRating=0 v:name="ISTHA - Coordinates for Mileposts on the Illinois Tollway, I-88"

property e:dzcq-kdyb t:meta.view.owner v:id=vtpi-ktes v:profileImageUrlMedium=/api/users/vtpi-ktes/profile_images/THUMB v:profileImageUrlLarge=/api/users/vtpi-ktes/profile_images/LARGE v:screenName=Brad v:profileImageUrlSmall=/api/users/vtpi-ktes/profile_images/TINY v:displayName=Brad

property e:dzcq-kdyb t:meta.view.tableauthor v:id=vtpi-ktes v:profileImageUrlMedium=/api/users/vtpi-ktes/profile_images/THUMB v:profileImageUrlLarge=/api/users/vtpi-ktes/profile_images/LARGE v:screenName=Brad v:profileImageUrlSmall=/api/users/vtpi-ktes/profile_images/TINY v:roleName=publisher v:displayName=Brad
```

## Top Records

```ls
| :updated_at | route | milepost | 
| =========== | ===== | ======== | 
| 1327400427  |       |          | 
| 1327400427  | 88    | 43.8     | 
| 1327400427  | 88    | 43.9     | 
| 1327400427  | 88    | 44       | 
| 1327400427  | 88    | 44.1     | 
| 1327400427  | 88    | 44.2     | 
| 1327400427  | 88    | 44.21    | 
| 1327400427  | 88    | 44.25    | 
| 1327400427  | 88    | 44.3     | 
| 1327400427  | 88    | 44.4     | 
```