# 2013 : Current Election Results Posting Schedule

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2013-current-election-results-posting-schedule-10399) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/3e7p-a4dt) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/3e7p-a4dt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/3e7p-a4dt/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | 3e7p-a4dt |
| Name | 2013 : Current Election Results Posting Schedule |
| Attribution | King County Elections |
| Category | Election operations |
| Tags | elections |
| Created | 2013-01-23T22:57:22Z |
| Publication Date | 2013-03-09T00:39:35Z |

## Description

Election results posting schedule for current 2013 election; King County Elections. Washington.

## Columns

```ls
| Included | Schema Type | Field Name | Name    | Data Type | Render Type |
| ======== | =========== | ========== | ======= | ========= | =========== |
| No       |             | date       | Date    | text      | text        |
| Yes      | series tag  | time       | Time    | text      | text        |
| Yes      | series tag  | purpose    | Purpose | text      | text        |
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
series e:3e7p-a4dt d:2013-01-01T00:00:00.000Z t:time="4:30 p.m." t:purpose="Results posted, including votes cast at the accessible voting centers." m:row_number.3e7p-a4dt=1

series e:3e7p-a4dt d:2013-01-01T00:00:00.000Z t:time="4:30 p.m." t:purpose="Results posted." m:row_number.3e7p-a4dt=2

series e:3e7p-a4dt d:2013-01-01T00:00:00.000Z t:time="4:30 p.m." t:purpose="Results posted, and unofficial election day abstract of results posted to the web." m:row_number.3e7p-a4dt=3
```

## Meta Commands

```ls
metric m:row_number.3e7p-a4dt p:long l:"Row Number"

entity e:3e7p-a4dt l:"2013 : Current Election Results Posting Schedule" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/3e7p-a4dt

property e:3e7p-a4dt t:meta.view v:id=3e7p-a4dt v:category="Election operations" v:attributionLink=http://kingcounty.gov/elections v:averageRating=0 v:name="2013 : Current Election Results Posting Schedule" v:attribution="King County Elections"

property e:3e7p-a4dt t:meta.view.license v:name="Public Domain"

property e:3e7p-a4dt t:meta.view.owner v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:displayName="Kathy Gill"

property e:3e7p-a4dt t:meta.view.tableauthor v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:roleName=publisher v:displayName="Kathy Gill"
```

## Top Records

```ls
| date               | time      | purpose                                                                            | 
| ================== | ========= | ================================================================================== | 
| Wednesday, Feb. 13 | 4:30 p.m. | Results posted, including votes cast at the accessible voting centers.             | 
| Thursday, Feb. 14  | 4:30 p.m. | Results posted.                                                                    | 
| Friday, Feb. 15    | 4:30 p.m. | Results posted, and unofficial election day abstract of results posted to the web. | 
| Tuesday, Feb. 19   | 4:30 p.m. | Results posted.                                                                    | 
| Wednesday, Feb. 20 | 4:30 p.m. | Results posted.                                                                    | 
| Thursday, Feb. 21  | 4:30 p.m. | Results posted.                                                                    | 
| Friday, Feb. 22    | 4:30 p.m. | Results posted.                                                                    | 
| Monday, Feb. 25    | 4:30 p.m. | Results posted.                                                                    | 
| Tuesday, Feb. 26   | 3:00 p.m. | Canvassing Board convenes to certify final election results.                       | 
| Tuesday, Feb. 26   | 4:30 p.m. | Final results posted.                                                              | 
```