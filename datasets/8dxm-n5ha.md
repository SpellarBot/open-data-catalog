# DOP Adult Cases Snapshot by Fiscal Year

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dop-adult-cases-snapshot-by-fiscal-year-2629f) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/8dxm-n5ha) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/8dxm-n5ha/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/8dxm-n5ha/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 8dxm-n5ha |
| Name | DOP Adult Cases Snapshot by Fiscal Year |
| Attribution | Department of Probation (DOP) |
| Category | City Government |
| Tags | dop, probation, adult cases, snapshot, fiscal year |
| Created | 2014-06-17T16:44:55Z |
| Publication Date | 2016-09-16T00:42:10Z |

## Description

The number of active adult probation supervision cases on the last day of the reporting period (June 30)

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                         | Data Type | Render Type |
| ======== | ============== | =========================== | ============================ | ========= | =========== |
| Yes      | series tag     | borough                     | Borough                      | text      | text        |
| Yes      | time           | fiscal_year_ending_in_june_ | Fiscal Year (ending in June) | number    | number      |
| Yes      | numeric metric | supervision_caseload_count  | Supervision Caseload Count   | number    | number      |
```

## Time Field

```ls
Value = fiscal_year_ending_in_june_
Format & Zone = yyyy
```

## Data Commands

```ls
series e:8dxm-n5ha d:2006-01-01T00:00:00.000Z t:borough=Bronx m:supervision_caseload_count=8760

series e:8dxm-n5ha d:2007-01-01T00:00:00.000Z t:borough=Bronx m:supervision_caseload_count=8277

series e:8dxm-n5ha d:2008-01-01T00:00:00.000Z t:borough=Bronx m:supervision_caseload_count=8019
```

## Meta Commands

```ls
metric m:supervision_caseload_count p:integer l:"Supervision Caseload Count" d:"The number of active adult probation supervision cases on the last day of the reporting period (June 30)." t:dataTypeName=number

entity e:8dxm-n5ha l:"DOP Adult Cases Snapshot by Fiscal Year" t:attribution="Department of Probation (DOP)" t:url=https://data.cityofnewyork.us/api/views/8dxm-n5ha

property e:8dxm-n5ha t:meta.view v:id=8dxm-n5ha v:category="City Government" v:averageRating=0 v:name="DOP Adult Cases Snapshot by Fiscal Year" v:attribution="Department of Probation (DOP)"

property e:8dxm-n5ha t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:8dxm-n5ha t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| borough  | fiscal_year_ending_in_june_ | supervision_caseload_count | 
| ======== | =========================== | ========================== | 
| Bronx    | 2006                        | 8760                       | 
| Bronx    | 2007                        | 8277                       | 
| Bronx    | 2008                        | 8019                       | 
| Bronx    | 2009                        | 7362                       | 
| Bronx    | 2010                        | 6708                       | 
| Bronx    | 2011                        | 6320                       | 
| Bronx    | 2012                        | 6261                       | 
| Bronx    | 2013                        | 6492                       | 
| Brooklyn | 2006                        | 7583                       | 
| Brooklyn | 2007                        | 7424                       | 
```