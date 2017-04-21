# 2016 Elections DropBoxes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2016-elections-dropboxes) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/sk5x-mxgz) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/sk5x-mxgz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/sk5x-mxgz/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | sk5x-mxgz |
| Name | 2016 Elections DropBoxes |
| Category | Election operations |
| Created | 2016-11-08T22:16:43Z |
| Publication Date | 2016-11-08T23:06:18Z |

## Description

All drop boxes operating during the 2012 November general election.

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type | Render Type |
| ======== | =========== | ================== | ================== | ========= | =========== |
| Yes      | series tag  | drop_box_locations | Drop Box Locations | text      | text        |
| Yes      | series tag  | time               | Hours              | text      | text        |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:sk5x-mxgz d:2016-01-01T00:00:00.000Z t:time="Closes at 8 pm" t:drop_box_locations="Auburn Library" m:row_number.sk5x-mxgz=1

series e:sk5x-mxgz d:2016-01-01T00:00:00.000Z t:time="Closes at 8 pm" t:drop_box_locations="Muckleshoot Tribe - Philip Starr Building" m:row_number.sk5x-mxgz=2

series e:sk5x-mxgz d:2016-01-01T00:00:00.000Z t:time="Closes at 8 pm" t:drop_box_locations="Bellevue Regional Library" m:row_number.sk5x-mxgz=3
```

## Meta Commands

```ls
metric m:row_number.sk5x-mxgz p:long l:"Row Number"

entity e:sk5x-mxgz l:"2016 Elections DropBoxes" t:url=https://data.kingcounty.gov/api/views/sk5x-mxgz

property e:sk5x-mxgz t:meta.view v:id=sk5x-mxgz v:category="Election operations" v:averageRating=0 v:name="2016 Elections DropBoxes"

property e:sk5x-mxgz t:meta.view.license v:name="Public Domain"

property e:sk5x-mxgz t:meta.view.owner v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:displayName="Kathy Gill"

property e:sk5x-mxgz t:meta.view.tableauthor v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:roleName=publisher v:displayName="Kathy Gill"
```

## Top Records

```ls
| drop_box_locations                        | time           | 
| ========================================= | ============== | 
| Auburn Library                            | Closes at 8 pm | 
| Muckleshoot Tribe - Philip Starr Building | Closes at 8 pm | 
| Bellevue Regional Library                 | Closes at 8 pm | 
| Crossroads Shopping Center                | Closes at 8 pm | 
| Bothell City Hall                         | Closes at 8 pm | 
| City of Burien - Town Square Park         | Closes at 8 pm | 
| Covington Library                         | Closes at 8 pm | 
| Highline College                          | Closes at 8 pm | 
| Enumclaw Library                          | Closes at 8 pm | 
| Federal Way City Hall                     | Closes at 8 pm | 
```