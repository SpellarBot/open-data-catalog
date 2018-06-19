# King County Elections Ballot Return Locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/king-county-elections-ballot-return-locations) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/ytse-z2dz) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/ytse-z2dz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/ytse-z2dz/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | ytse-z2dz |
| Name | King County Elections Ballot Return Locations |
| Attribution | King County Elections |
| Category | Election operations |
| Created | 2016-11-07T19:19:39Z |
| Publication Date | 2016-11-07T19:21:13Z |

## Description

Drop Boxes, effective Nov 2016 // data set provided per request - do not delete

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type | Render Type |
| ======== | =========== | ================== | ================== | ========= | =========== |
| No       | time        | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag  | drop_box_locations | Drop Box Locations | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ytse-z2dz d:2016-11-07T19:19:41.000Z t:drop_box_locations="Auburn Library" m:row_number.ytse-z2dz=1

series e:ytse-z2dz d:2016-11-07T19:19:41.000Z t:drop_box_locations="Muckleshoot Tribe - Philip Starr Building" m:row_number.ytse-z2dz=2

series e:ytse-z2dz d:2016-11-07T19:19:41.000Z t:drop_box_locations="Bellevue Regional Library" m:row_number.ytse-z2dz=3
```

## Meta Commands

```ls
metric m:row_number.ytse-z2dz p:long l:"Row Number"

entity e:ytse-z2dz l:"King County Elections Ballot Return Locations" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/ytse-z2dz

property e:ytse-z2dz t:meta.view v:id=ytse-z2dz v:category="Election operations" v:attributionLink=http://kingcounty.gov/elections v:averageRating=0 v:name="King County Elections Ballot Return Locations" v:attribution="King County Elections"

property e:ytse-z2dz t:meta.view.license v:name="Public Domain"

property e:ytse-z2dz t:meta.view.owner v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:displayName="Kathy Gill"

property e:ytse-z2dz t:meta.view.tableauthor v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:roleName=publisher v:displayName="Kathy Gill"
```

## Top Records

```ls
| :updated_at | drop_box_locations                        | 
| =========== | ========================================= | 
| 1478546381  | Auburn Library                            | 
| 1478546381  | Muckleshoot Tribe - Philip Starr Building | 
| 1478546381  | Bellevue Regional Library                 | 
| 1478546381  | Crossroads Shopping Center                | 
| 1478546381  | Bothell City Hall                         | 
| 1478546381  | City of Burien - Town Square Park         | 
| 1478546381  | Covington Library                         | 
| 1478546381  | Highline College                          | 
| 1478546381  | Enumclaw Library                          | 
| 1478546381  | Federal Way City Hall                     | 
```