# DOP Juvenile Violations of Probation Disposed by Fiscal Year

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dop-juvenile-violations-of-probation-disposed-by-fiscal-year-9a3df) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/gi3h-3i8t) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/gi3h-3i8t/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/gi3h-3i8t/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | gi3h-3i8t |
| Name | DOP Juvenile Violations of Probation Disposed by Fiscal Year |
| Attribution | Department of Probation (DOP) |
| Category | City Government |
| Tags | dop, juvenile, violation, probation, disposed, fiscal year |
| Created | 2014-04-07T16:23:00Z |
| Publication Date | 2016-09-16T01:05:54Z |

## Description

The number of dispositions issued by local courts for "violation of probation" proceedings during the reporting period.  Categorized by type of disposition: dismissed; probation continued; probation revoked; discharged (probation sentence ended).

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
series e:gi3h-3i8t d:2006-01-01T00:00:00.000Z t:violation_type=Dismissed t:borough=Bronx m:disposed_violation_count=4

series e:gi3h-3i8t d:2007-01-01T00:00:00.000Z t:violation_type=Dismissed t:borough=Bronx m:disposed_violation_count=8

series e:gi3h-3i8t d:2008-01-01T00:00:00.000Z t:violation_type=Dismissed t:borough=Bronx m:disposed_violation_count=10
```

## Meta Commands

```ls
metric m:disposed_violation_count p:integer l:"Disposed Violation Count" d:"The number of dispositions issued by local courts for ""violation of probation"" proceedings during the reporting period." t:dataTypeName=number

entity e:gi3h-3i8t l:"DOP Juvenile Violations of Probation Disposed by Fiscal Year" t:attribution="Department of Probation (DOP)" t:url=https://data.cityofnewyork.us/api/views/gi3h-3i8t

property e:gi3h-3i8t t:meta.view v:id=gi3h-3i8t v:category="City Government" v:averageRating=0 v:name="DOP Juvenile Violations of Probation Disposed by Fiscal Year" v:attribution="Department of Probation (DOP)"

property e:gi3h-3i8t t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:gi3h-3i8t t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| borough | fiscal_year_ending_in_june_ | violation_type | disposed_violation_count | 
| ======= | =========================== | ============== | ======================== | 
| Bronx   | 2006                        | Dismissed      | 4                        | 
| Bronx   | 2007                        | Dismissed      | 8                        | 
| Bronx   | 2008                        | Dismissed      | 10                       | 
| Bronx   | 2009                        | Dismissed      | 5                        | 
| Bronx   | 2010                        | Dismissed      | 9                        | 
| Bronx   | 2011                        | Dismissed      | 1                        | 
| Bronx   | 2012                        | Dismissed      | 6                        | 
| Bronx   | 2013                        | Dismissed      | 21                       | 
| Bronx   | 2006                        | Continued      | 36                       | 
| Bronx   | 2007                        | Continued      | 61                       | 
```