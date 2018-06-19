# DOP Juvenile Supervision Passthrough by Fiscal Year

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dop-juvenile-supervision-passthrough-by-fiscal-year-e278d) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/3f5y-5web) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/3f5y-5web/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/3f5y-5web/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 3f5y-5web |
| Name | DOP Juvenile Supervision Passthrough by Fiscal Year |
| Attribution | Department of Probation (DOP) |
| Category | City Government |
| Tags | dop, probation, juvenile supervision, passthrough, fiscal year |
| Created | 2014-06-17T16:47:32Z |
| Publication Date | 2015-09-15T17:04:05Z |

## Description

The sum of: the number of cases on the first day of the reporting period, and all cases added during the reporting period

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                         | Data Type | Render Type |
| ======== | ============== | =========================== | ============================ | ========= | =========== |
| Yes      | series tag     | borough                     | Borough                      | text      | text        |
| Yes      | time           | fiscal_year_ending_in_june_ | Fiscal Year (ending in June) | number    | number      |
| Yes      | numeric metric | passthrough_count           | Passthrough Count            | number    | number      |
```

## Time Field

```ls
Value = fiscal_year_ending_in_june_
Format & Zone = yyyy
```

## Data Commands

```ls
series e:3f5y-5web d:2006-01-01T00:00:00.000Z t:borough=Bronx m:passthrough_count=1506

series e:3f5y-5web d:2007-01-01T00:00:00.000Z t:borough=Bronx m:passthrough_count=1493

series e:3f5y-5web d:2008-01-01T00:00:00.000Z t:borough=Bronx m:passthrough_count=1464
```

## Meta Commands

```ls
metric m:passthrough_count p:integer l:"Passthrough Count" d:"The sum of: the number of cases on the first day of the reporting period, and all cases added during the reporting period." t:dataTypeName=number

entity e:3f5y-5web l:"DOP Juvenile Supervision Passthrough by Fiscal Year" t:attribution="Department of Probation (DOP)" t:url=https://data.cityofnewyork.us/api/views/3f5y-5web

property e:3f5y-5web t:meta.view v:id=3f5y-5web v:category="City Government" v:averageRating=0 v:name="DOP Juvenile Supervision Passthrough by Fiscal Year" v:attribution="Department of Probation (DOP)"

property e:3f5y-5web t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:3f5y-5web t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| borough  | fiscal_year_ending_in_june_ | passthrough_count | 
| ======== | =========================== | ================= | 
| Bronx    | 2006                        | 1506              | 
| Bronx    | 2007                        | 1493              | 
| Bronx    | 2008                        | 1464              | 
| Bronx    | 2009                        | 1470              | 
| Bronx    | 2010                        | 1489              | 
| Bronx    | 2011                        | 1509              | 
| Bronx    | 2012                        | 1445              | 
| Bronx    | 2013                        | 1303              | 
| Brooklyn | 2006                        | 1813              | 
| Brooklyn | 2007                        | 1766              | 
```