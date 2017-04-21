# DOP Adult Violations of Probation Filed by Fiscal Year

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dop-adult-violations-of-probation-filed-by-fiscal-year-b7ad4) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/fve3-eee8) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/fve3-eee8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/fve3-eee8/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | fve3-eee8 |
| Name | DOP Adult Violations of Probation Filed by Fiscal Year |
| Attribution | Department of Probation (DOP) |
| Category | City Government |
| Tags | dop, adult, violation, probation, filed, fiscal year |
| Created | 2014-04-07T16:21:57Z |
| Publication Date | 2016-09-16T00:59:58Z |

## Description

The number of ?violation of probation? filings sent by the Department to local courts, in response to misconduct by the probation client, during the reporting period.  Categorized by type of violation: rearrest; technical (rules) violation; or absconder.

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                         | Data Type | Render Type |
| ======== | ============== | =========================== | ============================ | ========= | =========== |
| Yes      | series tag     | borough                     | Borough                      | text      | text        |
| Yes      | time           | fiscal_year_ending_in_june_ | Fiscal Year (ending in June) | number    | number      |
| Yes      | series tag     | violation_type              | Violation Type               | text      | text        |
| Yes      | numeric metric | filed_violation_count       | Filed Violation Count        | number    | number      |
```

## Time Field

```ls
Value = fiscal_year_ending_in_june_
Format & Zone = yyyy
```

## Data Commands

```ls
series e:fve3-eee8 d:2006-01-01T00:00:00.000Z t:violation_type=Rearrests t:borough=Bronx m:filed_violation_count=862

series e:fve3-eee8 d:2007-01-01T00:00:00.000Z t:violation_type=Rearrests t:borough=Bronx m:filed_violation_count=949

series e:fve3-eee8 d:2008-01-01T00:00:00.000Z t:violation_type=Rearrests t:borough=Bronx m:filed_violation_count=957
```

## Meta Commands

```ls
metric m:filed_violation_count p:integer l:"Filed Violation Count" d:"Number of violations filed by type during the reporting period." t:dataTypeName=number

entity e:fve3-eee8 l:"DOP Adult Violations of Probation Filed by Fiscal Year" t:attribution="Department of Probation (DOP)" t:url=https://data.cityofnewyork.us/api/views/fve3-eee8

property e:fve3-eee8 t:meta.view v:id=fve3-eee8 v:category="City Government" v:averageRating=0 v:name="DOP Adult Violations of Probation Filed by Fiscal Year" v:attribution="Department of Probation (DOP)"

property e:fve3-eee8 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:fve3-eee8 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| borough | fiscal_year_ending_in_june_ | violation_type | filed_violation_count | 
| ======= | =========================== | ============== | ===================== | 
| Bronx   | 2006                        | Rearrests      | 862                   | 
| Bronx   | 2007                        | Rearrests      | 949                   | 
| Bronx   | 2008                        | Rearrests      | 957                   | 
| Bronx   | 2009                        | Rearrests      | 914                   | 
| Bronx   | 2010                        | Rearrests      | 904                   | 
| Bronx   | 2011                        | Rearrests      | 493                   | 
| Bronx   | 2012                        | Rearrests      | 480                   | 
| Bronx   | 2013                        | Rearrests      | 340                   | 
| Bronx   | 2006                        | Absconder      | 113                   | 
| Bronx   | 2007                        | Absconder      | 207                   | 
```