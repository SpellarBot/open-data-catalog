# DOP Juvenile Case Count By Type

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dop-juvenile-case-count-by-type) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/c49b-3kmd) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/c49b-3kmd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/c49b-3kmd/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | c49b-3kmd |
| Name | DOP Juvenile Case Count By Type |
| Attribution | Department of Probation (DOP) |
| Category | Public Safety |
| Tags | dop, probation, case |
| Created | 2016-11-21T15:48:19Z |
| Publication Date | 2017-03-31T21:56:00Z |

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
series e:c49b-3kmd d:2016-09-01T00:00:00.000Z t:borough=Citywide t:supervision_caseload_type="General Supervision" m:supervision_caseload_count=632

series e:c49b-3kmd d:2016-09-01T00:00:00.000Z t:borough=Citywide t:supervision_caseload_type="Pathways to Excellence Achievement and Knowledge" m:supervision_caseload_count=9

series e:c49b-3kmd d:2016-09-01T00:00:00.000Z t:borough=Citywide t:supervision_caseload_type="Every Child Has An Opportunity To Excel And Succeed" m:supervision_caseload_count=33
```

## Meta Commands

```ls
metric m:supervision_caseload_count p:integer l:"Supervision Caseload Count" t:dataTypeName=number

entity e:c49b-3kmd l:"DOP Juvenile Case Count By Type" t:attribution="Department of Probation (DOP)" t:url=https://data.cityofnewyork.us/api/views/c49b-3kmd

property e:c49b-3kmd t:meta.view v:id=c49b-3kmd v:category="Public Safety" v:averageRating=0 v:name="DOP Juvenile Case Count By Type" v:attribution="Department of Probation (DOP)"

property e:c49b-3kmd t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:c49b-3kmd t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| borough  | supervision_caseload_type                           | month     | year | supervision_caseload_count | 
| ======== | =================================================== | ========= | ==== | ========================== | 
| Citywide | General Supervision                                 | September | 2016 | 632                        | 
| Citywide | Pathways to Excellence Achievement and Knowledge    | September | 2016 | 9                          | 
| Citywide | Every Child Has An Opportunity To Excel And Succeed | September | 2016 | 33                         | 
| Citywide | IMPACT                                              | September | 2016 | 53                         | 
| Citywide | Juvenile Justice Initiative                         | September | 2016 | 189                        | 
| Citywide | Advocate Intervene Mentor                           | September | 2016 | 76                         | 
| Citywide | Enhanced Supervision Program                        | September | 2016 | 201                        | 
| Citywide | General Supervision                                 | October   | 2016 | 632                        | 
| Citywide | Pathways to Excellence Achievement and Knowledge    | October   | 2016 | 6                          | 
| Citywide | Every Child Has An Opportunity To Excel And Succeed | October   | 2016 | 32                         | 
```