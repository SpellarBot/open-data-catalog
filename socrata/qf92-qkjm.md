# DOP Juvenile Violations of Probation Disposed by Calendar Year

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dop-juvenile-violations-of-probation-disposed-by-calendar-year-b0926) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/qf92-qkjm) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/qf92-qkjm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/qf92-qkjm/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | qf92-qkjm |
| Name | DOP Juvenile Violations of Probation Disposed by Calendar Year |
| Attribution | Department of Probation (DOP) |
| Category | City Government |
| Tags | dop, juvenile, violation, probation, disposed, calendar year |
| Created | 2014-04-07T16:23:11Z |
| Publication Date | 2017-03-08T21:20:48Z |

## Description

The number of dispositions issued by local courts for "violation of probation" proceedings during the reporting period.  Categorized by type of disposition: dismissed; probation continued; probation revoked; discharged (probation sentence ended).

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| Yes      | series tag     | borough                  | Borough                  | text      | text        |
| Yes      | time           | calendar_year            | Calendar Year            | number    | number      |
| Yes      | series tag     | violation_type           | Violation Type           | text      | text        |
| Yes      | numeric metric | disposed_violation_count | Disposed Violation Count | number    | number      |
```

## Time Field

```ls
Value = calendar_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:qf92-qkjm d:2006-01-01T00:00:00.000Z t:violation_type=Dismissed t:borough=Bronx m:disposed_violation_count=10

series e:qf92-qkjm d:2007-01-01T00:00:00.000Z t:violation_type=Dismissed t:borough=Bronx m:disposed_violation_count=9

series e:qf92-qkjm d:2008-01-01T00:00:00.000Z t:violation_type=Dismissed t:borough=Bronx m:disposed_violation_count=7
```

## Meta Commands

```ls
metric m:disposed_violation_count p:integer l:"Disposed Violation Count" d:"The number of dispositions issued by local courts for ""violation of probation"" proceedings during the reporting period." t:dataTypeName=number

entity e:qf92-qkjm l:"DOP Juvenile Violations of Probation Disposed by Calendar Year" t:attribution="Department of Probation (DOP)" t:url=https://data.cityofnewyork.us/api/views/qf92-qkjm

property e:qf92-qkjm t:meta.view v:id=qf92-qkjm v:category="City Government" v:averageRating=0 v:name="DOP Juvenile Violations of Probation Disposed by Calendar Year" v:attribution="Department of Probation (DOP)"

property e:qf92-qkjm t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:qf92-qkjm t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| borough | calendar_year | violation_type | disposed_violation_count | 
| ======= | ============= | ============== | ======================== | 
| Bronx   | 2006          | Dismissed      | 10                       | 
| Bronx   | 2007          | Dismissed      | 9                        | 
| Bronx   | 2008          | Dismissed      | 7                        | 
| Bronx   | 2009          | Dismissed      | 5                        | 
| Bronx   | 2010          | Dismissed      | 6                        | 
| Bronx   | 2011          | Dismissed      | 3                        | 
| Bronx   | 2012          | Dismissed      | 13                       | 
| Bronx   | 2013          | Dismissed      | 16                       | 
| Bronx   | 2006          | Continued      | 48                       | 
| Bronx   | 2007          | Continued      | 44                       | 
```