# DOP Juvenile Investigations by Fiscal Year

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dop-juvenile-investigations-by-fiscal-year-a1f62) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/3mji-gpg5) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/3mji-gpg5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/3mji-gpg5/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 3mji-gpg5 |
| Name | DOP Juvenile Investigations by Fiscal Year |
| Attribution | Department of Probation (DOP) |
| Category | City Government |
| Tags | dop, investigations, fiscal year, juvenile |
| Created | 2014-02-26T21:30:43Z |
| Publication Date | 2016-09-16T01:04:03Z |

## Description

The number of presentence investigation reports completed for juveniles during the reporting period.

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                         | Data Type | Render Type |
| ======== | ============== | =========================== | ============================ | ========= | =========== |
| Yes      | series tag     | borough                     | Borough                      | text      | text        |
| Yes      | time           | fiscal_year_ending_in_june_ | Fiscal Year (ending in June) | number    | number      |
| Yes      | numeric metric | invenstigation_count        | Investigation Count          | number    | number      |
```

## Time Field

```ls
Value = fiscal_year_ending_in_june_
Format & Zone = yyyy
```

## Data Commands

```ls
series e:3mji-gpg5 d:2006-01-01T00:00:00.000Z t:borough=Bronx m:invenstigation_count=1987

series e:3mji-gpg5 d:2007-01-01T00:00:00.000Z t:borough=Bronx m:invenstigation_count=1528

series e:3mji-gpg5 d:2008-01-01T00:00:00.000Z t:borough=Bronx m:invenstigation_count=1134
```

## Meta Commands

```ls
metric m:invenstigation_count p:integer l:"Investigation Count" d:"The number of presentence investigation reports completed for juveniles during the reporting period." t:dataTypeName=number

entity e:3mji-gpg5 l:"DOP Juvenile Investigations by Fiscal Year" t:attribution="Department of Probation (DOP)" t:url=https://data.cityofnewyork.us/api/views/3mji-gpg5

property e:3mji-gpg5 t:meta.view v:id=3mji-gpg5 v:category="City Government" v:averageRating=0 v:name="DOP Juvenile Investigations by Fiscal Year" v:attribution="Department of Probation (DOP)"

property e:3mji-gpg5 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:3mji-gpg5 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| borough  | fiscal_year_ending_in_june_ | invenstigation_count | 
| ======== | =========================== | ==================== | 
| Bronx    | 2006                        | 1987                 | 
| Bronx    | 2007                        | 1528                 | 
| Bronx    | 2008                        | 1134                 | 
| Bronx    | 2009                        | 1426                 | 
| Bronx    | 2010                        | 1707                 | 
| Bronx    | 2011                        | 1174                 | 
| Bronx    | 2012                        | 900                  | 
| Brooklyn | 2006                        | 1228                 | 
| Brooklyn | 2007                        | 947                  | 
| Brooklyn | 2008                        | 983                  | 
```