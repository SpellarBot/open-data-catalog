# DOP Juvenile Supervision Intakes by Fiscal Year

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dop-juvenile-supervision-intakes-by-fiscal-year-41df5) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/xdqu-utzq) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/xdqu-utzq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/xdqu-utzq/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | xdqu-utzq |
| Name | DOP Juvenile Supervision Intakes by Fiscal Year |
| Attribution | Department of Probation (DOP) |
| Category | City Government |
| Tags | dop, supervision, fiscal year, juvenile |
| Created | 2014-04-07T16:21:37Z |
| Publication Date | 2016-09-16T01:04:52Z |

## Description

The number of youths sentenced to probation supervision during the reporting period.

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                         | Data Type | Render Type |
| ======== | ============== | =========================== | ============================ | ========= | =========== |
| Yes      | series tag     | borough                     | Borough                      | text      | text        |
| Yes      | time           | fiscal_year_ending_in_june_ | Fiscal Year (ending in June) | number    | number      |
| Yes      | series tag     | case_type                   | Case Type                    | text      | text        |
| Yes      | numeric metric | client_total                | Client Total                 | number    | number      |
```

## Time Field

```ls
Value = fiscal_year_ending_in_june_
Format & Zone = yyyy
```

## Data Commands

```ls
series e:xdqu-utzq d:2006-01-01T00:00:00.000Z t:borough=Bronx t:case_type=JD m:client_total=586

series e:xdqu-utzq d:2007-01-01T00:00:00.000Z t:borough=Bronx t:case_type=JD m:client_total=526

series e:xdqu-utzq d:2008-01-01T00:00:00.000Z t:borough=Bronx t:case_type=JD m:client_total=491
```

## Meta Commands

```ls
metric m:client_total p:integer l:"Client Total" d:"The number of youths sentenced to probation supervision during the reporting period." t:dataTypeName=number

entity e:xdqu-utzq l:"DOP Juvenile Supervision Intakes by Fiscal Year" t:attribution="Department of Probation (DOP)" t:url=https://data.cityofnewyork.us/api/views/xdqu-utzq

property e:xdqu-utzq t:meta.view v:id=xdqu-utzq v:category="City Government" v:averageRating=0 v:name="DOP Juvenile Supervision Intakes by Fiscal Year" v:attribution="Department of Probation (DOP)"

property e:xdqu-utzq t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:xdqu-utzq t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| borough | fiscal_year_ending_in_june_ | case_type | client_total | 
| ======= | =========================== | ========= | ============ | 
| Bronx   | 2006                        | JD        | 586          | 
| Bronx   | 2007                        | JD        | 526          | 
| Bronx   | 2008                        | JD        | 491          | 
| Bronx   | 2009                        | JD        | 455          | 
| Bronx   | 2010                        | JD        | 449          | 
| Bronx   | 2011                        | JD        | 408          | 
| Bronx   | 2012                        | JD        | 407          | 
| Bronx   | 2013                        | JD        | 327          | 
| Bronx   | 2006                        | ESP       | 205          | 
| Bronx   | 2007                        | ESP       | 172          | 
```