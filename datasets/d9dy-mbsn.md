# Oregon Cities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oregon-cities-35294) |
| Metadata | [Link](https://data.oregon.gov/api/views/d9dy-mbsn) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/d9dy-mbsn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/d9dy-mbsn/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | d9dy-mbsn |
| Name | Oregon Cities |
| Category | Administrative |
| Created | 2011-10-10T17:06:46Z |
| Publication Date | 2014-01-08T19:41:01Z |

## Description

This data is based on 2010 Census information.

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type | Render Type |
| ======== | =========== | =============== | =============== | ========= | =========== |
| No       | time        | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag  | feature_id      | Feature ID      | text      | text        |
| Yes      | series tag  | city            | City            | text      | text        |
| Yes      | series tag  | former_fipscode | Former FIPScode | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:d9dy-mbsn d:2011-10-26T13:16:49.000Z t:former_fipscode=10750 t:feature_id=2409974 t:city=Canby m:row_number.d9dy-mbsn=1

series e:d9dy-mbsn d:2011-10-26T13:16:49.000Z t:former_fipscode=10850 t:feature_id=2409975 t:city="Cannon Beach" m:row_number.d9dy-mbsn=2

series e:d9dy-mbsn d:2011-10-26T13:16:49.000Z t:former_fipscode=11000 t:feature_id=2409980 t:city=Canyonville m:row_number.d9dy-mbsn=3
```

## Meta Commands

```ls
metric m:row_number.d9dy-mbsn p:long l:"Row Number"

entity e:d9dy-mbsn l:"Oregon Cities" t:url=https://data.oregon.gov/api/views/d9dy-mbsn

property e:d9dy-mbsn t:meta.view v:id=d9dy-mbsn v:category=Administrative v:averageRating=0 v:name="Oregon Cities"

property e:d9dy-mbsn t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:d9dy-mbsn t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| :updated_at | feature_id | city          | former_fipscode | 
| =========== | ========== | ============= | =============== | 
| 1319635009  | 2409974    | Canby         | 10750           | 
| 1319635009  | 2409975    | Cannon Beach  | 10850           | 
| 1319635009  | 2409980    | Canyonville   | 11000           | 
| 1319635009  | 2409986    | Carlton       | 11150           | 
| 1319635009  | 2409403    | Cascade Locks | 11600           | 
| 1319635009  | 2409414    | Cave Junction | 11850           | 
| 1319635009  | 2409428    | Central Point | 12400           | 
| 1319635009  | 2409451    | Chiloquin     | 13050           | 
| 1319635009  | 2409472    | Clatskanie    | 13750           | 
| 1319635009  | 2409497    | Coburg        | 14400           | 
```