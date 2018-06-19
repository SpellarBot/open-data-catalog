# Website visits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/website-visits) |
| Metadata | [Link](https://data.wa.gov/api/views/gia4-fgdb) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/gia4-fgdb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/gia4-fgdb/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | gia4-fgdb |
| Name | Website visits |
| Created | 2016-05-03T19:01:18Z |
| Publication Date | 2016-05-03T20:50:43Z |

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | month       | Month      | text      | text        |
| Yes      | numeric metric | visits      | Visits     | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:gia4-fgdb d:2016-05-03T12:13:41.000Z t:month=January m:visits=1000

series e:gia4-fgdb d:2016-05-03T12:13:55.000Z t:month=February m:visits=1200

series e:gia4-fgdb d:2016-05-03T12:13:57.000Z t:month=March m:visits=1300
```

## Meta Commands

```ls
metric m:visits p:integer l:Visits t:dataTypeName=number

entity e:gia4-fgdb l:"Website visits" t:url=https://data.wa.gov/api/views/gia4-fgdb

property e:gia4-fgdb t:meta.view v:id=gia4-fgdb v:averageRating=0 v:name="Website visits"

property e:gia4-fgdb t:meta.view.owner v:id=bjfs-pe5a v:screenName=justinb.ocio v:displayName=justinb.ocio

property e:gia4-fgdb t:meta.view.tableauthor v:id=bjfs-pe5a v:screenName=justinb.ocio v:roleName=publisher v:displayName=justinb.ocio
```

## Top Records

```ls
| :updated_at | month     | visits | 
| =========== | ========= | ====== | 
| 1462277621  | January   | 1000   | 
| 1462277635  | February  | 1200   | 
| 1462277637  | March     | 1300   | 
| 1462277639  | April     | 1400   | 
| 1462277640  | May       | 1250   | 
| 1462277647  | June      | 1600   | 
| 1462277649  | July      | 1700   | 
| 1462277649  | August    | 1900   | 
| 1462277655  | September | 2100   | 
| 1462277656  | October   | 2000   | 
```