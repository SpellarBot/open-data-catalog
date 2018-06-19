# DOP Adult Case Count By Type

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dop-adult-case-count-by-type) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/y3gq-zv28) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/y3gq-zv28/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/y3gq-zv28/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | y3gq-zv28 |
| Name | DOP Adult Case Count By Type |
| Attribution | Department of Probation (DOP) |
| Category | Public Safety |
| Tags | dop, probation, case |
| Created | 2016-11-21T15:48:07Z |
| Publication Date | 2017-03-31T21:22:41Z |

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | series tag     | borough                    | Region                     | text      | text        |
| Yes      | series tag     | supervision_caseload_type  | Supervision Caseload Type  | text      | text        |
| No       |                | month                      | Month                      | text      | text        |
| No       |                | year                       | Year                       | number    | number      |
| Yes      | numeric metric | supervision_caseload_count | Supervision Caseload Count | number    | number      |
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
series e:y3gq-zv28 d:2016-09-01T00:00:00.000Z t:borough=Citywide t:supervision_caseload_type="Intensive Engagement" m:supervision_caseload_count=1584

series e:y3gq-zv28 d:2016-09-01T00:00:00.000Z t:borough=Citywide t:supervision_caseload_type="Client Development" m:supervision_caseload_count=2931

series e:y3gq-zv28 d:2016-09-01T00:00:00.000Z t:borough=Citywide t:supervision_caseload_type="Community Progression" m:supervision_caseload_count=11891
```

## Meta Commands

```ls
metric m:supervision_caseload_count p:integer l:"Supervision Caseload Count" t:dataTypeName=number

entity e:y3gq-zv28 l:"DOP Adult Case Count By Type" t:attribution="Department of Probation (DOP)" t:url=https://data.cityofnewyork.us/api/views/y3gq-zv28

property e:y3gq-zv28 t:meta.view v:id=y3gq-zv28 v:category="Public Safety" v:averageRating=0 v:name="DOP Adult Case Count By Type" v:attribution="Department of Probation (DOP)"

property e:y3gq-zv28 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:y3gq-zv28 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| borough  | supervision_caseload_type             | month     | year | supervision_caseload_count | 
| ======== | ===================================== | ========= | ==== | ========================== | 
| Citywide | Intensive Engagement                  | September | 2016 | 1584                       | 
| Citywide | Client Development                    | September | 2016 | 2931                       | 
| Citywide | Community Progression                 | September | 2016 | 11891                      | 
| Citywide | ACE Anyone Can Excel                  | September | 2016 | 1137                       | 
| Citywide | NeON Neighborhood Opportunity Network | September | 2016 | 2497                       | 
| Citywide | Special Program                       | September | 2016 | 160                        | 
| Citywide | Central Interstate Unit               | September | 2016 | 610                        | 
| Citywide | Intensive Engagement                  | November  | 2016 | 1586                       | 
| Citywide | Client Development                    | November  | 2016 | 3089                       | 
| Citywide | Community Progression                 | November  | 2016 | 11272                      | 
```