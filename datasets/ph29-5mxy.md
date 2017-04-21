# DOP Adult Cases Snapshot by Calendar Year

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dop-adult-cases-snapshot-by-calendar-year-08165) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ph29-5mxy) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ph29-5mxy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ph29-5mxy/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ph29-5mxy |
| Name | DOP Adult Cases Snapshot by Calendar Year |
| Attribution | Department of Probation (DOP) |
| Category | City Government |
| Tags | dop, probation, adult cases, snapshot, calendar year |
| Created | 2014-06-17T16:44:42Z |
| Publication Date | 2017-03-08T18:01:29Z |

## Description

The number of active adult probation supervision cases on the last day of the reporting period (December 31)

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | series tag     | borough                    | Borough                    | text      | text        |
| Yes      | time           | calendar_year              | Calendar Year              | number    | number      |
| Yes      | numeric metric | supervision_caseload_count | Supervision Caseload Count | number    | number      |
```

## Time Field

```ls
Value = calendar_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ph29-5mxy d:2006-01-01T00:00:00.000Z t:borough=Bronx m:supervision_caseload_count=8426

series e:ph29-5mxy d:2007-01-01T00:00:00.000Z t:borough=Bronx m:supervision_caseload_count=8142

series e:ph29-5mxy d:2008-01-01T00:00:00.000Z t:borough=Bronx m:supervision_caseload_count=7792
```

## Meta Commands

```ls
metric m:supervision_caseload_count p:integer l:"Supervision Caseload Count" d:"The number of active adult probation supervision cases on the last day of the reporting period (December 31)." t:dataTypeName=number

entity e:ph29-5mxy l:"DOP Adult Cases Snapshot by Calendar Year" t:attribution="Department of Probation (DOP)" t:url=https://data.cityofnewyork.us/api/views/ph29-5mxy

property e:ph29-5mxy t:meta.view v:id=ph29-5mxy v:category="City Government" v:averageRating=0 v:name="DOP Adult Cases Snapshot by Calendar Year" v:attribution="Department of Probation (DOP)"

property e:ph29-5mxy t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ph29-5mxy t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| borough  | calendar_year | supervision_caseload_count | 
| ======== | ============= | ========================== | 
| Bronx    | 2006          | 8426                       | 
| Bronx    | 2007          | 8142                       | 
| Bronx    | 2008          | 7792                       | 
| Bronx    | 2009          | 7390                       | 
| Bronx    | 2010          | 6264                       | 
| Bronx    | 2011          | 6282                       | 
| Bronx    | 2012          | 6440                       | 
| Bronx    | 2013          | 6692                       | 
| Brooklyn | 2006          | 7193                       | 
| Brooklyn | 2007          | 7401                       | 
```