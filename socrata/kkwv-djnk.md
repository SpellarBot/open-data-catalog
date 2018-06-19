# DOP Adult Investigations Ordered

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dop-adult-investigations-ordered) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/kkwv-djnk) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/kkwv-djnk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/kkwv-djnk/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | kkwv-djnk |
| Name | DOP Adult Investigations Ordered |
| Attribution | Department of Probation (DOP) |
| Category | Public Safety |
| Tags | dop, investigation, probation |
| Created | 2016-11-21T15:48:10Z |
| Publication Date | 2017-03-31T21:25:18Z |

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                         | Data Type | Render Type |
| ======== | ============== | ============================ | ============================ | ========= | =========== |
| Yes      | series tag     | borough                      | Region                       | text      | text        |
| Yes      | series tag     | investigations_ordered_type  | Investigations Ordered Type  | text      | text        |
| No       |                | month                        | Month                        | text      | text        |
| No       |                | year                         | Year                         | number    | number      |
| Yes      | numeric metric | investigations_ordered_count | Investigations Ordered Count | number    | number      |
```

## Time Field

```ls
Value = year-month
Format & Zone = yyyy-MMMM
```

## Series Fields

```ls
Excluded Fields = year,month
```

## Data Commands

```ls
series e:kkwv-djnk d:2016-09-01T00:00:00.000Z t:investigations_ordered_type=Jail t:borough=Citywide m:investigations_ordered_count=626

series e:kkwv-djnk d:2016-09-01T00:00:00.000Z t:investigations_ordered_type=Bail t:borough=Citywide m:investigations_ordered_count=726

series e:kkwv-djnk d:2016-11-01T00:00:00.000Z t:investigations_ordered_type=Jail t:borough=Citywide m:investigations_ordered_count=567
```

## Meta Commands

```ls
metric m:investigations_ordered_count p:integer l:"Investigations Ordered Count" d:"The number of pre-sentence investigation reports ordered for adults during the reporting period." t:dataTypeName=number

entity e:kkwv-djnk l:"DOP Adult Investigations Ordered" t:attribution="Department of Probation (DOP)" t:url=https://data.cityofnewyork.us/api/views/kkwv-djnk

property e:kkwv-djnk t:meta.view v:id=kkwv-djnk v:category="Public Safety" v:averageRating=0 v:name="DOP Adult Investigations Ordered" v:attribution="Department of Probation (DOP)"

property e:kkwv-djnk t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:kkwv-djnk t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| borough  | investigations_ordered_type | month     | year | investigations_ordered_count | 
| ======== | =========================== | ========= | ==== | ============================ | 
| Citywide | Jail                        | September | 2016 | 626                          | 
| Citywide | Bail                        | September | 2016 | 726                          | 
| Citywide | Jail                        | November  | 2016 | 567                          | 
| Citywide | Bail                        | November  | 2016 | 588                          | 
| Citywide | Jail                        | December  | 2016 | 533                          | 
| Citywide | Bail                        | December  | 2016 | 557                          | 
| Citywide | Jail                        | January   | 2017 | 559                          | 
| Citywide | Bail                        | January   | 2017 | 722                          | 
| Citywide | Jail                        | February  | 2017 | 601                          | 
| Citywide | Bail                        | February  | 2017 | 667                          | 
```