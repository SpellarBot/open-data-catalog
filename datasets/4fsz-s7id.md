# DOP Adult Supervision Intakes by Fiscal Year

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dop-adult-supervision-intakes-by-fiscal-year-75475) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/4fsz-s7id) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/4fsz-s7id/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/4fsz-s7id/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 4fsz-s7id |
| Name | DOP Adult Supervision Intakes by Fiscal Year |
| Attribution | Department of Probation (DOP) |
| Category | City Government |
| Tags | dop, intakes, fiscal year, adults |
| Created | 2014-04-07T16:20:58Z |
| Publication Date | 2016-09-16T00:58:22Z |

## Description

The number of adults sentenced to probation supervision during the reporting period.

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                         | Data Type | Render Type |
| ======== | ============== | =========================== | ============================ | ========= | =========== |
| Yes      | series tag     | borough                     | Borough                      | text      | text        |
| Yes      | time           | fiscal_year_ending_in_june_ | Fiscal Year (ending in June) | number    | number      |
| Yes      | numeric metric | client_total                | Client Total                 | number    | number      |
```

## Time Field

```ls
Value = fiscal_year_ending_in_june_
Format & Zone = yyyy
```

## Data Commands

```ls
series e:4fsz-s7id d:2006-01-01T00:00:00.000Z t:borough=Bronx m:client_total=1836

series e:4fsz-s7id d:2007-01-01T00:00:00.000Z t:borough=Bronx m:client_total=1596

series e:4fsz-s7id d:2008-01-01T00:00:00.000Z t:borough=Bronx m:client_total=1721
```

## Meta Commands

```ls
metric m:client_total p:integer l:"Client Total" d:"The number of adults sentenced to probation supervision during the reporting period." t:dataTypeName=number

entity e:4fsz-s7id l:"DOP Adult Supervision Intakes by Fiscal Year" t:attribution="Department of Probation (DOP)" t:url=https://data.cityofnewyork.us/api/views/4fsz-s7id

property e:4fsz-s7id t:meta.view v:id=4fsz-s7id v:category="City Government" v:averageRating=0 v:name="DOP Adult Supervision Intakes by Fiscal Year" v:attribution="Department of Probation (DOP)"

property e:4fsz-s7id t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:4fsz-s7id t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| borough  | fiscal_year_ending_in_june_ | client_total | 
| ======== | =========================== | ============ | 
| Bronx    | 2006                        | 1836         | 
| Bronx    | 2007                        | 1596         | 
| Bronx    | 2008                        | 1721         | 
| Bronx    | 2009                        | 1598         | 
| Bronx    | 2010                        | 1349         | 
| Bronx    | 2011                        | 1224         | 
| Bronx    | 2012                        | 1291         | 
| Bronx    | 2013                        | 1172         | 
| Brooklyn | 2006                        | 1596         | 
| Brooklyn | 2007                        | 1753         | 
```