# DOP Adult Violations of Probation Disposed by Calendar Year

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dop-adult-violations-of-probation-disposed-by-calendar-year-d9e0b) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/f2cz-q2ik) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/f2cz-q2ik/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/f2cz-q2ik/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | f2cz-q2ik |
| Name | DOP Adult Violations of Probation Disposed by Calendar Year |
| Attribution | Department of Probation (DOP) |
| Category | City Government |
| Tags | dop, adult, violation, probation, disposed, calendar year |
| Created | 2014-04-07T16:22:49Z |
| Publication Date | 2017-03-08T20:19:02Z |

## Description

The number of dispositions issued by local courts for "violation of probation" proceedings during the reporting period.  Categorized by type of disposition: jail (revocation); prison (revocation); restored (probation continued); terminated (probation sentence ended).

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
series e:f2cz-q2ik d:2006-01-01T00:00:00.000Z t:violation_type=Jail t:borough=Bronx m:disposed_violation_count=437

series e:f2cz-q2ik d:2007-01-01T00:00:00.000Z t:violation_type=Jail t:borough=Bronx m:disposed_violation_count=517

series e:f2cz-q2ik d:2008-01-01T00:00:00.000Z t:violation_type=Jail t:borough=Bronx m:disposed_violation_count=571
```

## Meta Commands

```ls
metric m:disposed_violation_count p:integer l:"Disposed Violation Count" d:"The number of ""violation of probation"" dispostions by type during the reporting period." t:dataTypeName=number

entity e:f2cz-q2ik l:"DOP Adult Violations of Probation Disposed by Calendar Year" t:attribution="Department of Probation (DOP)" t:url=https://data.cityofnewyork.us/api/views/f2cz-q2ik

property e:f2cz-q2ik t:meta.view v:id=f2cz-q2ik v:category="City Government" v:averageRating=0 v:name="DOP Adult Violations of Probation Disposed by Calendar Year" v:attribution="Department of Probation (DOP)"

property e:f2cz-q2ik t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:f2cz-q2ik t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| borough | calendar_year | violation_type | disposed_violation_count | 
| ======= | ============= | ============== | ======================== | 
| Bronx   | 2006          | Jail           | 437                      | 
| Bronx   | 2007          | Jail           | 517                      | 
| Bronx   | 2008          | Jail           | 571                      | 
| Bronx   | 2009          | Jail           | 618                      | 
| Bronx   | 2010          | Jail           | 633                      | 
| Bronx   | 2011          | Jail           | 325                      | 
| Bronx   | 2012          | Jail           | 216                      | 
| Bronx   | 2013          | Jail           | 247                      | 
| Bronx   | 2006          | Prison         | 54                       | 
| Bronx   | 2007          | Prison         | 175                      | 
```