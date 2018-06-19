# Results Schedule - April 17, 2012 Special Elections

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/results-schedule-april-17-2012-special-elections-944fb) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/cthj-5vde) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/cthj-5vde/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/cthj-5vde/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | cthj-5vde |
| Name | Results Schedule - April 17, 2012 Special Elections |
| Attribution | King County Elections |
| Category | Election operations |
| Tags | elections, king county, 2012, results |
| Created | 2012-03-27T22:05:03Z |
| Publication Date | 2012-03-27T22:07:11Z |

## Columns

```ls
| Included | Schema Type | Field Name | Name  | Data Type | Render Type |
| ======== | =========== | ========== | ===== | ========= | =========== |
| No       |             | date       | Date  | text      | text        |
| Yes      | series tag  | time       | Time  | text      | text        |
| Yes      | series tag  | event      | Event | text      | text        |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = date
```

## Data Commands

```ls
series e:cthj-5vde d:2012-01-01T00:00:00.000Z t:time="8:15 p.m." t:event="Election day results posted to the web." m:row_number.cthj-5vde=1

series e:cthj-5vde d:2012-01-01T00:00:00.000Z t:time="4:30 p.m." t:event="Results posted, including votes cast at the accessible voting centers." m:row_number.cthj-5vde=2

series e:cthj-5vde d:2012-01-01T00:00:00.000Z t:time="4:30 p.m." t:event="Results posted." m:row_number.cthj-5vde=3
```

## Meta Commands

```ls
metric m:row_number.cthj-5vde p:long l:"Row Number"

entity e:cthj-5vde l:"Results Schedule - April 17, 2012 Special Elections" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/cthj-5vde

property e:cthj-5vde t:meta.view v:id=cthj-5vde v:category="Election operations" v:attributionLink=http://kingcounty.gov/elections v:averageRating=0 v:name="Results Schedule - April 17, 2012 Special Elections" v:attribution="King County Elections"

property e:cthj-5vde t:meta.view.license v:name="Public Domain"

property e:cthj-5vde t:meta.view.owner v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:displayName="Kathy Gill"

property e:cthj-5vde t:meta.view.tableauthor v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:roleName=publisher v:displayName="Kathy Gill"
```

## Top Records

```ls
| date               | time       | event                                                                              | 
| ================== | ========== | ================================================================================== | 
|  Tuesday, Apr. 17  | 8:15 p.m.  | Election day results posted to the web.                                            | 
| Wednesday, Apr. 18 | 4:30 p.m.  | Results posted, including votes cast at the accessible voting centers.             | 
| Thursday, Apr. 19  | 4:30 p.m.  | Results posted.                                                                    | 
| Friday, Apr. 20    | 4:30 p.m.  | Results posted, and unofficial election day abstract of results posted to the web. | 
| Monday, Apr. 23    | 4:30 p.m.  | Results posted.                                                                    | 
| Tuesday, Apr. 24   | 4:30 p.m.  | Results posted.                                                                    | 
| Wednesday, Apr. 25 | 4:30 p.m.  | Results posted.                                                                    | 
| Thursday, Apr. 26  | 4:30 p.m.  | Results posted.                                                                    | 
| Friday, Apr. 27    | 11:00 a.m. | Canvassing Board convenes to certify final election results.                       | 
| Friday, Apr. 27    | 1:00 p.m.  | Final results posted.                                                              | 
```