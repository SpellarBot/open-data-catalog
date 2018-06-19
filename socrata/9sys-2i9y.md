# DOP Adult Violations of Probation Disposed by Fiscal Year

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dop-adult-violations-of-probation-disposed-by-fiscal-year-839b5) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/9sys-2i9y) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/9sys-2i9y/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/9sys-2i9y/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 9sys-2i9y |
| Name | DOP Adult Violations of Probation Disposed by Fiscal Year |
| Attribution | Department of Probation (DOP) |
| Category | City Government |
| Tags | dop, adult, violation, probation, disposed, fiscal year |
| Created | 2014-04-07T16:22:39Z |
| Publication Date | 2016-09-16T00:59:06Z |

## Description

The number of dispositions issued by local courts for "violation of probation" proceedings during the reporting period.  Categorized by type of disposition: jail (revocation); prison (revocation); restored (probation continued); terminated (probation sentence ended).

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                         | Data Type | Render Type |
| ======== | ============== | =========================== | ============================ | ========= | =========== |
| Yes      | series tag     | borough                     | Borough                      | text      | text        |
| Yes      | time           | fiscal_year_ending_in_june_ | Fiscal Year (ending in June) | number    | number      |
| Yes      | series tag     | violation_type              | Violation Type               | text      | text        |
| Yes      | numeric metric | disposed_violation_count    | Disposed Violation Count     | number    | number      |
```

## Time Field

```ls
Value = fiscal_year_ending_in_june_
Format & Zone = yyyy
```

## Data Commands

```ls
series e:9sys-2i9y d:2006-01-01T00:00:00.000Z t:violation_type=Jail t:borough=Bronx m:disposed_violation_count=407

series e:9sys-2i9y d:2007-01-01T00:00:00.000Z t:violation_type=Jail t:borough=Bronx m:disposed_violation_count=479

series e:9sys-2i9y d:2008-01-01T00:00:00.000Z t:violation_type=Jail t:borough=Bronx m:disposed_violation_count=488
```

## Meta Commands

```ls
metric m:disposed_violation_count p:integer l:"Disposed Violation Count" d:"The number of ""violation of probation"" dispostions by type during the reporting period." t:dataTypeName=number

entity e:9sys-2i9y l:"DOP Adult Violations of Probation Disposed by Fiscal Year" t:attribution="Department of Probation (DOP)" t:url=https://data.cityofnewyork.us/api/views/9sys-2i9y

property e:9sys-2i9y t:meta.view v:id=9sys-2i9y v:category="City Government" v:averageRating=0 v:name="DOP Adult Violations of Probation Disposed by Fiscal Year" v:attribution="Department of Probation (DOP)"

property e:9sys-2i9y t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:9sys-2i9y t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| borough | fiscal_year_ending_in_june_ | violation_type | disposed_violation_count | 
| ======= | =========================== | ============== | ======================== | 
| Bronx   | 2006                        | Jail           | 407                      | 
| Bronx   | 2007                        | Jail           | 479                      | 
| Bronx   | 2008                        | Jail           | 488                      | 
| Bronx   | 2009                        | Jail           | 613                      | 
| Bronx   | 2010                        | Jail           | 702                      | 
| Bronx   | 2011                        | Jail           | 442                      | 
| Bronx   | 2012                        | Jail           | 263                      | 
| Bronx   | 2013                        | Jail           | 225                      | 
| Bronx   | 2006                        | Prison         | 41                       | 
| Bronx   | 2007                        | Prison         | 144                      | 
```