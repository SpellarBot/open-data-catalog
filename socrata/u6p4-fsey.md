# DOP Adult Case Closings By Reason

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dop-adult-case-closings-by-reason) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/u6p4-fsey) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/u6p4-fsey/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/u6p4-fsey/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | u6p4-fsey |
| Name | DOP Adult Case Closings By Reason |
| Attribution | Department of Probation (DOP) |
| Category | Public Safety |
| Tags | dop, probation, case |
| Created | 2016-11-21T15:48:03Z |
| Publication Date | 2017-03-31T21:09:50Z |

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | series tag     | borough                    | Region                     | text      | text        |
| Yes      | series tag     | supervision_closing_reason | Supervision Closing Reason | text      | text        |
| No       |                | month                      | Month                      | text      | text        |
| No       |                | year                       | Year                       | number    | number      |
| Yes      | numeric metric | supervision_closing_count  | Supervision Closing Count  | number    | number      |
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
series e:u6p4-fsey d:2016-09-01T00:00:00.000Z t:borough=Citywide t:supervision_closing_reason="Maximum Expiration Date" m:supervision_closing_count=345

series e:u6p4-fsey d:2016-09-01T00:00:00.000Z t:borough=Citywide t:supervision_closing_reason=Death m:supervision_closing_count=5

series e:u6p4-fsey d:2016-09-01T00:00:00.000Z t:borough=Citywide t:supervision_closing_reason="Early Discharge" m:supervision_closing_count=55
```

## Meta Commands

```ls
metric m:supervision_closing_count p:integer l:"Supervision Closing Count" t:dataTypeName=number

entity e:u6p4-fsey l:"DOP Adult Case Closings By Reason" t:attribution="Department of Probation (DOP)" t:url=https://data.cityofnewyork.us/api/views/u6p4-fsey

property e:u6p4-fsey t:meta.view v:id=u6p4-fsey v:category="Public Safety" v:averageRating=0 v:name="DOP Adult Case Closings By Reason" v:attribution="Department of Probation (DOP)"

property e:u6p4-fsey t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:u6p4-fsey t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| borough  | supervision_closing_reason | month     | year | supervision_closing_count | 
| ======== | ========================== | ========= | ==== | ========================= | 
| Citywide | Maximum Expiration Date    | September | 2016 | 345                       | 
| Citywide | Death                      | September | 2016 | 5                         | 
| Citywide | Early Discharge            | September | 2016 | 55                        | 
| Citywide | Violation of Probation     | September | 2016 | 93                        | 
| Citywide | Other                      | September | 2016 | 79                        | 
| Citywide | Maximum Expiration Date    | November  | 2016 | 334                       | 
| Citywide | Death                      | November  | 2016 | 7                         | 
| Citywide | Early Discharge            | November  | 2016 | 113                       | 
| Citywide | Violation of Probation     | November  | 2016 | 81                        | 
| Citywide | Other                      | November  | 2016 | 85                        | 
```