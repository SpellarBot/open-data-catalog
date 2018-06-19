# Results Posting Schedule April 23 2013 Special Election

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/results-posting-schedule-april-23-2013-special-election-0073f) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/ssqh-wqa4) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/ssqh-wqa4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/ssqh-wqa4/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | ssqh-wqa4 |
| Name | Results Posting Schedule April 23 2013 Special Election |
| Category | Election operations |
| Tags | elections |
| Created | 2013-04-04T15:18:30Z |
| Publication Date | 2013-04-29T15:39:17Z |

## Columns

```ls
| Included | Schema Type | Field Name | Name    | Data Type | Render Type |
| ======== | =========== | ========== | ======= | ========= | =========== |
| No       |             | date       | Date    | text      | text        |
| Yes      | series tag  | time       | Time    | text      | text        |
| Yes      | series tag  | details    | Details | text      | text        |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = date
```

## Data Commands

```ls
series e:ssqh-wqa4 d:2013-01-01T00:00:00.000Z t:time="8:15 p.m." t:details="Election day results posted to the web." m:row_number.ssqh-wqa4=1

series e:ssqh-wqa4 d:2013-01-01T00:00:00.000Z t:time="4:30 p.m." t:details="Results posted, including votes cast at the accessible voting centers." m:row_number.ssqh-wqa4=2

series e:ssqh-wqa4 d:2013-01-01T00:00:00.000Z t:time="4:30 p.m." t:details="Results posted." m:row_number.ssqh-wqa4=3
```

## Meta Commands

```ls
metric m:row_number.ssqh-wqa4 p:long l:"Row Number"

entity e:ssqh-wqa4 l:"Results Posting Schedule April 23 2013 Special Election" t:url=https://data.kingcounty.gov/api/views/ssqh-wqa4

property e:ssqh-wqa4 t:meta.view v:id=ssqh-wqa4 v:category="Election operations" v:averageRating=0 v:name="Results Posting Schedule April 23 2013 Special Election"

property e:ssqh-wqa4 t:meta.view.license v:name="Public Domain"

property e:ssqh-wqa4 t:meta.view.owner v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:displayName="Kathy Gill"

property e:ssqh-wqa4 t:meta.view.tableauthor v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:roleName=publisher v:displayName="Kathy Gill"
```

## Top Records

```ls
| date               | time      | details                                                                                                                                                                                                                       | 
| ================== | ========= | ============================================================================================================================================================================================================================= | 
|  Tuesday, Apr. 23  | 8:15 p.m. | Election day results posted to the web.                                                                                                                                                                                       | 
| Wednesday, Apr. 24 | 4:30 p.m. | Results posted, including votes cast at the accessible voting centers.                                                                                                                                                        | 
| Thursday, Apr. 25  | 4:30 p.m. | Results posted.                                                                                                                                                                                                               | 
| Tuesday, May 7     | 3:00 p.m. | Canvassing Board convenes to certify final election results.                                                                                                                                                                  | 
| Tuesday, May 7     | 4:30 p.m. | Final results posted.                                                                                                                                                                                                         | 
| Friday, May 10     | 4:30 p.m. | Official canvass report: results of the election detailed by precinct and summarized by district electronically (on CD) are available for purchase and on the web. Advance orders are recommended and will be given priority. | 
| Tuesday, May 14    | 4:30 p.m. | A PDF copy of the official canvass report will be available on the web.                                                                                                                                                       | 
| Friday, Apr. 26    | 4:30 p.m. | Unofficial election day abstract of results posted to the web.                                                                                                                                                                | 
| Monday, Apr. 29    | 4:30 p.m. | No results posted.                                                                                                                                                                                                            | 
| Tuesday, Apr. 30   | 4:30 p.m. | Results posted.                                                                                                                                                                                                               | 
```