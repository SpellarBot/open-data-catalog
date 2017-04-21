# DOP Adult Violations of Probation Filed by Calendar Year

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dop-adult-violations-of-probation-filed-by-calendar-year-1276a) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/k2ye-5mmh) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/k2ye-5mmh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/k2ye-5mmh/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | k2ye-5mmh |
| Name | DOP Adult Violations of Probation Filed by Calendar Year |
| Attribution | Department of Probation (DOP) |
| Category | City Government |
| Tags | dop, adult, violation, probation, calendar year |
| Created | 2014-04-07T16:22:08Z |
| Publication Date | 2017-03-08T20:25:59Z |

## Description

The number of ?violation of probation? filings sent by the Department to local courts, in response to misconduct by the probation client, during the reporting period.  Categorized by type of violation: rearrest; technical (rules) violation; or absconder.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type | Render Type |
| ======== | ============== | ===================== | ===================== | ========= | =========== |
| Yes      | series tag     | borough               | Borough               | text      | text        |
| Yes      | time           | calendar_year         | Calendar Year         | number    | number      |
| Yes      | series tag     | violation_type        | Violation Type        | text      | text        |
| Yes      | numeric metric | filed_violation_count | Filed Violation Count | number    | number      |
```

## Time Field

```ls
Value = calendar_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:k2ye-5mmh d:2006-01-01T00:00:00.000Z t:violation_type=Rearrests t:borough=Bronx m:filed_violation_count=964

series e:k2ye-5mmh d:2007-01-01T00:00:00.000Z t:violation_type=Rearrests t:borough=Bronx m:filed_violation_count=925

series e:k2ye-5mmh d:2008-01-01T00:00:00.000Z t:violation_type=Rearrests t:borough=Bronx m:filed_violation_count=900
```

## Meta Commands

```ls
metric m:filed_violation_count p:integer l:"Filed Violation Count" d:"Number of violations filed by type during the reporting period." t:dataTypeName=number

entity e:k2ye-5mmh l:"DOP Adult Violations of Probation Filed by Calendar Year" t:attribution="Department of Probation (DOP)" t:url=https://data.cityofnewyork.us/api/views/k2ye-5mmh

property e:k2ye-5mmh t:meta.view v:id=k2ye-5mmh v:category="City Government" v:averageRating=0 v:name="DOP Adult Violations of Probation Filed by Calendar Year" v:attribution="Department of Probation (DOP)"

property e:k2ye-5mmh t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:k2ye-5mmh t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| borough | calendar_year | violation_type | filed_violation_count | 
| ======= | ============= | ============== | ===================== | 
| Bronx   | 2006          | Rearrests      | 964                   | 
| Bronx   | 2007          | Rearrests      | 925                   | 
| Bronx   | 2008          | Rearrests      | 900                   | 
| Bronx   | 2009          | Rearrests      | 918                   | 
| Bronx   | 2010          | Rearrests      | 749                   | 
| Bronx   | 2011          | Rearrests      | 441                   | 
| Bronx   | 2012          | Rearrests      | 413                   | 
| Bronx   | 2013          | Rearrests      | 395                   | 
| Bronx   | 2006          | Absconder      | 216                   | 
| Bronx   | 2007          | Absconder      | 138                   | 
```