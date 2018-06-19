# Police Beat and Precinct Centerpoints

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/police-beat-and-precinct-centerpoints-58cf4) |
| Metadata | [Link](https://data.seattle.gov/api/views/4khs-fz35) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/4khs-fz35/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/4khs-fz35/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | 4khs-fz35 |
| Name | Police Beat and Precinct Centerpoints |
| Category | Land Base |
| Created | 2014-03-03T22:56:28Z |
| Publication Date | 2014-03-04T00:23:30Z |

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | beat_name   | Name       | text      | text        |
| No       |             | latitude    | Latitude   | number    | number      |
| No       |             | longitude   | Longitude  | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = latitude,longitude
```

## Data Commands

```ls
series e:4khs-fz35 d:2014-03-03T14:56:31.000Z t:beat_name=E m:row_number.4khs-fz35=1

series e:4khs-fz35 d:2014-03-03T14:56:31.000Z t:beat_name=C1 m:row_number.4khs-fz35=2

series e:4khs-fz35 d:2014-03-03T14:56:31.000Z t:beat_name=C3 m:row_number.4khs-fz35=3
```

## Meta Commands

```ls
metric m:row_number.4khs-fz35 p:long l:"Row Number"

entity e:4khs-fz35 l:"Police Beat and Precinct Centerpoints" t:url=https://data.seattle.gov/api/views/4khs-fz35

property e:4khs-fz35 t:meta.view v:id=4khs-fz35 v:category="Land Base" v:averageRating=0 v:name="Police Beat and Precinct Centerpoints"

property e:4khs-fz35 t:meta.view.owner v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:displayName="Seattle IT"

property e:4khs-fz35 t:meta.view.tableauthor v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```

## Top Records

```ls
| :updated_at | beat_name | latitude           | longitude           | 
| =========== | ========= | ================== | =================== | 
| 1393858591  | E         | 47.620154274814404 | -122.304782602556   | 
| 1393858591  | C1        | 47.6342500180223   | -122.315684762418   | 
| 1393858591  | C3        | 47.630079288747403 | -122.292087128251   | 
| 1393858591  | D2        | 47.625654887604902 | -122.331370005506   | 
| 1393858591  | E1        | 47.620348688207301 | -122.324419823241   | 
| 1393858591  | C2        | 47.619238575299597 | -122.313557430551   | 
| 1393858591  | G1        | 47.609137330649403 | -122.30789961679299 | 
| 1393858591  | E2        | 47.611843267110203 | -122.32016086570999 | 
| 1393858591  | D3        | 47.6103493249325   | -122.32865370619901 | 
| 1393858591  | G3        | 47.603182188167501 | -122.292398835358   | 
```