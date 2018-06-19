# DOP Juvenile Intakes by Fiscal Year

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dop-juvenile-intakes-by-fiscal-year-4340e) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ff9v-9yzg) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ff9v-9yzg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ff9v-9yzg/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ff9v-9yzg |
| Name | DOP Juvenile Intakes by Fiscal Year |
| Attribution | Department of Probation (DOP) |
| Category | City Government |
| Tags | dop, intakes, fiscal year, juvenile |
| Created | 2014-04-07T16:21:18Z |
| Publication Date | 2016-09-16T01:03:13Z |

## Description

The number of youth received in probation intake (pre-adjudication services) during the reporting period.

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
series e:ff9v-9yzg d:2006-01-01T00:00:00.000Z t:borough=Bronx m:client_total=2562

series e:ff9v-9yzg d:2007-01-01T00:00:00.000Z t:borough=Bronx m:client_total=2570

series e:ff9v-9yzg d:2008-01-01T00:00:00.000Z t:borough=Bronx m:client_total=3308
```

## Meta Commands

```ls
metric m:client_total p:integer l:"Client Total" d:"The number of youth received in probation intake (pre-adjudication services) during the reporting period." t:dataTypeName=number

entity e:ff9v-9yzg l:"DOP Juvenile Intakes by Fiscal Year" t:attribution="Department of Probation (DOP)" t:url=https://data.cityofnewyork.us/api/views/ff9v-9yzg

property e:ff9v-9yzg t:meta.view v:id=ff9v-9yzg v:category="City Government" v:averageRating=0 v:name="DOP Juvenile Intakes by Fiscal Year" v:attribution="Department of Probation (DOP)"

property e:ff9v-9yzg t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ff9v-9yzg t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| borough  | fiscal_year_ending_in_june_ | client_total | 
| ======== | =========================== | ============ | 
| Bronx    | 2006                        | 2562         | 
| Bronx    | 2007                        | 2570         | 
| Bronx    | 2008                        | 3308         | 
| Bronx    | 2009                        | 3654         | 
| Bronx    | 2010                        | 3868         | 
| Bronx    | 2011                        | 3885         | 
| Bronx    | 2012                        | 3615         | 
| Bronx    | 2013                        | 1959         | 
| Brooklyn | 2006                        | 3217         | 
| Brooklyn | 2007                        | 3275         | 
```