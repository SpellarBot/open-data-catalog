# Cancelled Projects

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cancelled-projects) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/cwqt-nvfg) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/cwqt-nvfg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/cwqt-nvfg/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | cwqt-nvfg |
| Name | Cancelled Projects |
| Attribution | NYC School Construction Authority (SCA) |
| Category | Education |
| Tags | sca, constructions, projects |
| Created | 2016-05-31T21:48:27Z |
| Publication Date | 2016-05-31T21:53:30Z |

## Description

Projects removed from the plan.

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| No       | time        | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag  | district         | District         | text      | number      |
| Yes      | series tag  | bld_id           | Bld ID           | text      | text        |
| Yes      | series tag  | school           | School           | text      | text        |
| Yes      | series tag  | boro             | Boro             | text      | text        |
| Yes      | series tag  | program_category | Program Category | text      | text        |
| Yes      | series tag  | reason           | Reason           | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:cwqt-nvfg d:2016-05-31T14:48:56.000Z t:boro=X t:school="P.S. 71" t:reason="Alternate Project Prioritized" t:program_category=Toilets-Students t:bld_id=X071 t:district=8 m:row_number.cwqt-nvfg=1

series e:cwqt-nvfg d:2016-05-31T14:48:56.000Z t:boro=X t:school="I.S. 232" t:reason="Alternate Project Prioritized" t:program_category=Toilets-Students t:bld_id=X082 t:district=9 m:row_number.cwqt-nvfg=2

series e:cwqt-nvfg d:2016-05-31T14:48:56.000Z t:boro=Q t:school="P.S. 71" t:reason="Alternate Project Prioritized" t:program_category=Toilets-Students t:bld_id=Q071 t:district=24 m:row_number.cwqt-nvfg=3
```

## Meta Commands

```ls
metric m:row_number.cwqt-nvfg p:long l:"Row Number"

entity e:cwqt-nvfg l:"Cancelled Projects" t:attribution="NYC School Construction Authority (SCA)" t:url=https://data.cityofnewyork.us/api/views/cwqt-nvfg

property e:cwqt-nvfg t:meta.view v:id=cwqt-nvfg v:category=Education v:averageRating=0 v:name="Cancelled Projects" v:attribution="NYC School Construction Authority (SCA)"

property e:cwqt-nvfg t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:cwqt-nvfg t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | district | bld_id | school              | boro | program_category                      | reason                        | 
| =========== | ======== | ====== | =================== | ==== | ===================================== | ============================= | 
| 1464706136  | 8        | X071   | P.S. 71             | X    | Toilets-Students                      | Alternate Project Prioritized | 
| 1464706136  | 9        | X082   | I.S. 232            | X    | Toilets-Students                      | Alternate Project Prioritized | 
| 1464706136  | 24       | Q071   | P.S. 71             | Q    | Toilets-Students                      | Alternate Project Prioritized | 
| 1464706136  | 24       | Q071   | P.S. 71             | Q    | Toilets-Staff                         | Alternate Project Prioritized | 
| 1464706136  | 27       | Q210   | I.S. 210            | Q    | Cafeteria / Multipurpose Room Upgrade | Alternate Project Prioritized | 
| 1464706136  | 78       | X451   | STEVENSON AF        | X    | Athletic Fields                       | Alternate Project Prioritized | 
| 1464706136  | 1        | M110   | P.S. 110            | M    | Lighting Fixtures                     | No Capital Work Required      | 
| 1464706136  | 6        | M132   | P.S. 132            | M    | Low-Voltage Electrical Systems        | No Capital Work Required      | 
| 1464706136  | 6        | M132   | P.S. 132            | M    | Heating Plant Upgrade                 | No Capital Work Required      | 
| 1464706136  | 6        | M847   | P.S. 178 MINISCHOOL | M    | Low-Voltage Electrical Systems        | No Capital Work Required      | 
```