# King County History Timeline

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/king-county-history-timeline) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/fuh5-64id) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/fuh5-64id/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/fuh5-64id/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | fuh5-64id |
| Name | King County History Timeline |
| Attribution | King County Archives |
| Category | Records |
| Created | 2015-04-24T20:06:49Z |
| Publication Date | 2015-04-24T21:09:04Z |

## Description

Milestones in the history of King County, Washington

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type     | Render Type   |
| ======== | ============== | ========== | ========== | ============= | ============= |
| Yes      | time           | start_time | Year       | calendar_date | calendar_date |
| Yes      | series tag     | notes      | Event      | text          | text          |
| Yes      | numeric metric | population | Population | number        | number        |
```

## Time Field

```ls
Value = start_time
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:fuh5-64id d:1860-01-01T00:00:00.000Z t:notes="Population of King County is 305 residents." m:population=305

series e:fuh5-64id d:1870-01-01T00:00:00.000Z t:notes="Population of King County is 2,120." m:population=2120

series e:fuh5-64id d:1880-01-01T00:00:00.000Z t:notes="Population of King County is 6,910." m:population=6910
```

## Meta Commands

```ls
metric m:population p:integer l:Population t:dataTypeName=number

entity e:fuh5-64id l:"King County History Timeline" t:attribution="King County Archives" t:url=https://data.kingcounty.gov/api/views/fuh5-64id

property e:fuh5-64id t:meta.view v:id=fuh5-64id v:category=Records v:attributionLink=http://www.kingcounty.gov/archives v:averageRating=0 v:name="King County History Timeline" v:attribution="King County Archives"

property e:fuh5-64id t:meta.view.license v:name="Public Domain"

property e:fuh5-64id t:meta.view.owner v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"

property e:fuh5-64id t:meta.view.tableauthor v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"
```

## Top Records

```ls
| start_time          | notes                                                                                                                                                       | population | 
| =================== | =========================================================================================================================================================== | ========== | 
| 1848-08-14T00:00:00 | U.S. establishes Territory of Oregon on August 14, 1848, while California gold rush spurs western migration.                                                |            | 
| 1850-09-27T00:00:00 | The federal Donation Land Act granting each Oregon settler 320 acres of "free" land becomes effective September 27, 1850; it terminates in 1855.            |            | 
| 1852-12-22T00:00:00 | Oregon Territorial Assembly creates King County on December 22, 1852.                                                                                       |            | 
| 1853-01-23T00:00:00 | Doc Maynard issues King County's first marriage license and officiates as David Denny and Louisa Boren married on January 23, 1853.                         |            | 
| 1853-03-02T00:00:00 | The Oregon Territorial Assembly appoints J.N. Lowe, L.M. Collins, and A.A. Denny as Commissioners, H.L. Yesler as Probate Clerk, and C.D. Boren as Sheriff. |            | 
| 1853-03-05T00:00:00 | First meeting of King County Commissioners is held at the home of D. S. Maynard on March 5, 1853.                                                           |            | 
| 1853-03-01T00:00:00 | First recording in King County, the donation-land claim of D.T. Denny is made.                                                                              |            | 
| 1860-01-01T00:00:00 | Population of King County is 305 residents.                                                                                                                 | 305        | 
| 1860-01-01T00:00:00 | Military Road is completed between Fort Vancouver on the Columbia River and Seattle.                                                                        |            | 
| 1863-01-01T00:00:00 | First annual fair of the King County Agricultural Society is held.                                                                                          |            | 
```