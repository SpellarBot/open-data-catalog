# Precincts

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/precincts-4604b) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/cidw-fyff) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/cidw-fyff/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/cidw-fyff/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | cidw-fyff |
| Name | Precincts |
| Category | Election operations |
| Tags | election, king county, voter, precincts |
| Created | 2012-09-03T18:39:48Z |
| Publication Date | 2012-09-05T02:20:43Z |

## Description

Precincts for King County Elections

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| No       | time           | :updated_at                | updated_at                 | meta_data | meta_data   |
| Yes      | series tag     | precinct_id                | precinct_id                | text      | number      |
| Yes      | series tag     | status                     | status                     | text      | text        |
| Yes      | series tag     | reason_id                  | reason_id                  | text      | number      |
| Yes      | numeric metric | division                   | division                   | number    | number      |
| Yes      | series tag     | users_id                   | users_id                   | text      | number      |
| Yes      | series tag     | precinct                   | precinct                   | text      | number      |
| Yes      | numeric metric | portion                    | portion                    | number    | number      |
| Yes      | series tag     | name                       | name                       | text      | text        |
| Yes      | numeric metric | map                        | map                        | number    | number      |
| Yes      | series tag     | poll_id                    | poll_id                    | text      | number      |
| Yes      | series tag     | default_worker_id          | default_worker_id          | text      | number      |
| Yes      | series tag     | default_consolidation      | default_consolidation      | text      | text        |
| Yes      | series tag     | default_split              | default_split              | text      | text        |
| Yes      | series tag     | default_consolidation_name | default_consolidation_name | text      | text        |
| Yes      | numeric metric | reporting_unit             | reporting_unit             | number    | number      |
| Yes      | series tag     | non_voter                  | non_voter                  | text      | text        |
| Yes      | series tag     | comment_id                 | comment_id                 | text      | number      |
| Yes      | series tag     | precinct_trans_id          | precinct_trans_id          | text      | number      |
| Yes      | series tag     | ltd                        | ltd                        | text      | text        |
| Yes      | series tag     | timestamp                  | timestamp                  | text      | text        |
| Yes      | series tag     | vbm_flag                   | vbm_flag                   | text      | text        |
| Yes      | series tag     | gen_field                  | gen_field                  | text      | text        |
| Yes      | series tag     | billing_code               | billing_code               | text      | text        |
| Yes      | series tag     | newspaper                  | newspaper                  | text      | text        |
| Yes      | series tag     | depot_id                   | depot_id                   | text      | number      |
| Yes      | series tag     | agency                     | agency                     | text      | text        |
| Yes      | series tag     | route                      | route                      | text      | text        |
| Yes      | numeric metric | sequence                   | sequence                   | number    | number      |
| Yes      | series tag     | return_center              | return_center              | text      | text        |
| Yes      | series tag     | trouble_shooter_id         | trouble_shooter_id         | text      | number      |
| Yes      | series tag     | jurisdiction               | jurisdiction               | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:cidw-fyff d:2012-09-03T11:39:51.000Z t:timestamp=0000000015B8DF8D t:precinct_id=0 t:status=I t:name="NO PRECINCT ENTERED" t:precinct_trans_id=7105 t:non_voter=Y t:ltd=08:41.8 t:poll_id=9019 t:vbm_flag=N m:sequence=0

series e:cidw-fyff d:2012-09-03T11:39:51.000Z t:comment_id=0 t:status=A t:reason_id=0 t:precinct_trans_id=0 t:users_id=0 t:vbm_flag=N t:poll_id=9019 t:timestamp=0000000015B8DF8F t:precinct=568 t:precinct_id=4 t:name=JUTLAND t:non_voter=N t:default_worker_id=0 t:ltd=33:09.5 m:reporting_unit=0 m:sequence=0 m:map=79 m:portion=25

series e:cidw-fyff d:2012-09-03T11:39:51.000Z t:comment_id=0 t:status=A t:reason_id=0 t:precinct_trans_id=0 t:users_id=0 t:vbm_flag=N t:poll_id=9019 t:timestamp=0000000015B8DF90 t:precinct=471 t:precinct_id=5 t:name=GLENDALE t:non_voter=N t:default_worker_id=0 t:ltd=33:09.5 m:reporting_unit=0 m:sequence=0 m:map=304 m:portion=28
```

## Meta Commands

```ls
metric m:division p:integer l:division t:dataTypeName=number

metric m:portion p:integer l:portion t:dataTypeName=number

metric m:map p:integer l:map t:dataTypeName=number

metric m:reporting_unit p:integer l:reporting_unit t:dataTypeName=number

metric m:sequence p:integer l:sequence t:dataTypeName=number

entity e:cidw-fyff l:Precincts t:url=https://data.kingcounty.gov/api/views/cidw-fyff

property e:cidw-fyff t:meta.view v:id=cidw-fyff v:category="Election operations" v:attributionLink=http://www.kingcounty.gov/elections v:averageRating=0 v:name=Precincts

property e:cidw-fyff t:meta.view.owner v:id=bkmh-fhfb v:screenName="Asera Khatun" v:displayName="Asera Khatun"

property e:cidw-fyff t:meta.view.tableauthor v:id=bkmh-fhfb v:screenName="Asera Khatun" v:roleName=publisher v:displayName="Asera Khatun"
```

## Top Records

```ls
| :updated_at | precinct_id | status | reason_id | division | users_id | precinct | portion | name                | map | poll_id | default_worker_id | default_consolidation | default_split | default_consolidation_name | reporting_unit | non_voter | comment_id | precinct_trans_id | ltd     | timestamp        | vbm_flag | gen_field | billing_code | newspaper | depot_id | agency | route | sequence | return_center | trouble_shooter_id | jurisdiction | 
| =========== | =========== | ====== | ========= | ======== | ======== | ======== | ======= | =================== | === | ======= | ================= | ===================== | ============= | ========================== | ============== | ========= | ========== | ================= | ======= | ================ | ======== | ========= | ============ | ========= | ======== | ====== | ===== | ======== | ============= | ================== | ============ | 
| 1346672391  | 0           | I      |           |          |          |          |         | NO PRECINCT ENTERED |     | 9019    |                   |                       |               |                            |                | Y         |            | 7105              | 08:41.8 | 0000000015B8DF8D | N        |           |              |           |          |        |       | 0        |               |                    |              | 
| 1346672391  | 4           | A      | 0         |          | 0        | 568      | 25      | JUTLAND             | 79  | 9019    | 0                 |                       |               |                            | 0              | N         | 0          | 0                 | 33:09.5 | 0000000015B8DF8F | N        |           |              |           |          |        |       | 0        |               |                    |              | 
| 1346672391  | 5           | A      | 0         |          | 0        | 471      | 28      | GLENDALE            | 304 | 9019    | 0                 |                       |               |                            | 0              | N         | 0          | 0                 | 33:09.5 | 0000000015B8DF90 | N        |           |              |           |          |        |       | 0        |               |                    |              | 
| 1346672391  | 6           | A      | 0         |          | 0        | 568      | 29      | JUTLAND             | 304 | 9019    | 0                 |                       |               |                            | 0              | N         | 0          | 0                 | 33:09.6 | 0000000015B8DF91 | N        |           |              |           |          |        |       | 0        |               |                    |              | 
| 1346672391  | 7           | A      | 0         |          | 0        | 1257     | 30      | SEA 34-1257         | 311 | 9019    | 0                 |                       |               |                            | 0              | N         | 0          | 0                 | 33:09.6 | 0000000015B8DF92 | N        |           |              |           |          |        |       | 0        |               |                    |              | 
| 1346672391  | 8           | A      | 0         |          | 0        | 1258     | 31      | SEA 34-1258         | 300 | 9019    | 0                 |                       |               |                            | 0              | N         | 0          | 0                 | 33:09.6 | 0000000015B8DF93 | N        |           |              |           |          |        |       | 0        |               |                    |              | 
| 1346672391  | 9           | A      | 0         |          | 0        | 1259     | 32      | SEA 34-1259         | 310 | 9019    | 0                 |                       |               |                            | 0              | N         | 0          | 45232             | 13:15.5 | 000000001E8595CD | N        |           |              |           | 0        |        |       | 0        |               | 0                  |              | 
| 1346672391  | 10          | A      | 0         |          | 0        | 1543     | 33      | SEA 34-1543         | 310 | 9019    | 0                 |                       |               |                            | 0              | N         | 0          | 0                 | 33:09.7 | 0000000015B8DF95 | N        |           |              |           |          |        |       | 0        |               |                    |              | 
| 1346672391  | 11          | A      | 0         |          | 0        | 1530     | 35      | SEA 34-1530         | 300 | 9019    | 0                 |                       |               |                            | 0              | N         | 0          | 0                 | 33:09.7 | 0000000015B8DF96 | N        |           |              |           |          |        |       | 0        |               |                    |              | 
| 1346672391  | 12          | A      | 0         |          | 0        | 1534     | 36      | SEA 34-1534         | 75  | 9019    | 0                 |                       |               |                            | 0              | N         | 0          | 0                 | 33:09.7 | 0000000015B8DF97 | N        |           |              |           |          |        |       | 0        |               |                    |              | 
```