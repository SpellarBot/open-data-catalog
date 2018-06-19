# DOP Adult Supervision Passthrough by Calendar Year

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dop-adult-supervision-passthrough-by-calendar-year-d6048) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/3av7-txd8) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/3av7-txd8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/3av7-txd8/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 3av7-txd8 |
| Name | DOP Adult Supervision Passthrough by Calendar Year |
| Attribution | Department of Probation (DOP) |
| Category | City Government |
| Tags | dop, probation, adult supervision, passthrough, calendar year |
| Created | 2014-06-17T16:45:42Z |
| Publication Date | 2017-03-24T15:07:19Z |

## Description

The sum of: the number of cases on the first day of the reporting period, plus all cases added during the reporting period.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | series tag     | borough           | Region            | text      | text        |
| Yes      | time           | calendar_year     | Calendar Year     | number    | number      |
| Yes      | numeric metric | passthrough_count | Passthrough Count | number    | number      |
```

## Time Field

```ls
Value = calendar_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:3av7-txd8 d:2006-01-01T00:00:00.000Z t:borough=Bronx m:passthrough_count=10764

series e:3av7-txd8 d:2007-01-01T00:00:00.000Z t:borough=Bronx m:passthrough_count=10107

series e:3av7-txd8 d:2008-01-01T00:00:00.000Z t:borough=Bronx m:passthrough_count=9854
```

## Meta Commands

```ls
metric m:passthrough_count p:integer l:"Passthrough Count" d:"The sum of: the number of cases on the first day of the reporting period, plus all cases added during the reporting period." t:dataTypeName=number

entity e:3av7-txd8 l:"DOP Adult Supervision Passthrough by Calendar Year" t:attribution="Department of Probation (DOP)" t:url=https://data.cityofnewyork.us/api/views/3av7-txd8

property e:3av7-txd8 t:meta.view v:id=3av7-txd8 v:category="City Government" v:averageRating=0 v:name="DOP Adult Supervision Passthrough by Calendar Year" v:attribution="Department of Probation (DOP)"

property e:3av7-txd8 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:3av7-txd8 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| borough  | calendar_year | passthrough_count | 
| ======== | ============= | ================= | 
| Bronx    | 2006          | 10764             | 
| Bronx    | 2007          | 10107             | 
| Bronx    | 2008          | 9854              | 
| Bronx    | 2009          | 9285              | 
| Bronx    | 2010          | 8554              | 
| Bronx    | 2011          | 7565              | 
| Bronx    | 2012          | 7472              | 
| Bronx    | 2013          | 7733              | 
| Brooklyn | 2006          | 9811              | 
| Brooklyn | 2007          | 8854              | 
```