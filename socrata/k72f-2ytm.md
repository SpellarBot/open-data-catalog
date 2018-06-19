# DOP Adult Case Closings By Type

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dop-adult-case-closings-by-type) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/k72f-2ytm) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/k72f-2ytm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/k72f-2ytm/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | k72f-2ytm |
| Name | DOP Adult Case Closings By Type |
| Attribution | Department of Probation (DOP) |
| Category | Public Safety |
| Tags | dop, case, probation |
| Created | 2016-11-21T15:48:03Z |
| Publication Date | 2017-03-08T19:17:59Z |

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type | Render Type |
| ======== | ============== | ========================= | ========================= | ========= | =========== |
| Yes      | series tag     | borough                   | Borough                   | text      | text        |
| Yes      | series tag     | supervision_closing_type  | Supervision Closing Type  | text      | text        |
| No       |                | month                     | Month                     | text      | text        |
| No       |                | year                      | Year                      | number    | number      |
| Yes      | numeric metric | supervision_closing_count | Supervision Closing Count | number    | number      |
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
series e:k72f-2ytm d:2016-11-01T00:00:00.000Z t:supervision_closing_type="Intensive Engagement" t:borough=Citywide m:supervision_closing_count=38

series e:k72f-2ytm d:2016-11-01T00:00:00.000Z t:supervision_closing_type="Client Development" t:borough=Citywide m:supervision_closing_count=50

series e:k72f-2ytm d:2016-11-01T00:00:00.000Z t:supervision_closing_type="Community Progression" t:borough=Citywide m:supervision_closing_count=418
```

## Meta Commands

```ls
metric m:supervision_closing_count p:integer l:"Supervision Closing Count" t:dataTypeName=number

entity e:k72f-2ytm l:"DOP Adult Case Closings By Type" t:attribution="Department of Probation (DOP)" t:url=https://data.cityofnewyork.us/api/views/k72f-2ytm

property e:k72f-2ytm t:meta.view v:id=k72f-2ytm v:category="Public Safety" v:averageRating=0 v:name="DOP Adult Case Closings By Type" v:attribution="Department of Probation (DOP)"

property e:k72f-2ytm t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:k72f-2ytm t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| borough  | supervision_closing_type              | month     | year | supervision_closing_count | 
| ======== | ===================================== | ========= | ==== | ========================= | 
| Citywide | Intensive Engagement                  | November  | 2016 | 38                        | 
| Citywide | Client Development                    | November  | 2016 | 50                        | 
| Citywide | Community Progression                 | November  | 2016 | 418                       | 
| Citywide | ACE Anyone Can Excel                  | November  | 2016 | 17                        | 
| Citywide | NeON Neighborhood Opportunity Network | November  | 2016 | 50                        | 
| Citywide | Special Program                       | November  | 2016 | 7                         | 
| Citywide | Central Interstate Unit               | November  | 2016 | 36                        | 
| Citywide | Other                                 | November  | 2016 | 4                         | 
| Citywide | Intensive Engagement                  | September | 2016 | 24                        | 
| Citywide | Client Development                    | September | 2016 | 56                        | 
```