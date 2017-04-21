# DOP Juvenile Violations of Probation Filed by Fiscal Year

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dop-juvenile-violations-of-probation-filed-by-fiscal-year-2b21d) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/mzy5-smmw) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/mzy5-smmw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/mzy5-smmw/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | mzy5-smmw |
| Name | DOP Juvenile Violations of Probation Filed by Fiscal Year |
| Attribution | Department of Probation (DOP) |
| Category | City Government |
| Tags | dop, juvenile, violation, probation, filed, fiscal year |
| Created | 2014-04-07T16:22:19Z |
| Publication Date | 2016-09-16T01:05:57Z |

## Description

The number of ?violation of probation? filings sent by the Department to local courts, in response to misconduct by the probation client, during the reporting period

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                         | Data Type | Render Type |
| ======== | ============== | =========================== | ============================ | ========= | =========== |
| Yes      | series tag     | borough                     | Borough                      | text      | text        |
| Yes      | time           | fiscal_year_ending_in_june_ | Fiscal Year (ending in June) | number    | number      |
| Yes      | numeric metric | filed_violation_count       | Filed Violation Count        | number    | number      |
```

## Time Field

```ls
Value = fiscal_year_ending_in_june_
Format & Zone = yyyy
```

## Data Commands

```ls
series e:mzy5-smmw d:2006-01-01T00:00:00.000Z t:borough=Bronx m:filed_violation_count=222

series e:mzy5-smmw d:2007-01-01T00:00:00.000Z t:borough=Bronx m:filed_violation_count=180

series e:mzy5-smmw d:2008-01-01T00:00:00.000Z t:borough=Bronx m:filed_violation_count=217
```

## Meta Commands

```ls
metric m:filed_violation_count p:integer l:"Filed Violation Count" d:"The number of ""violation of probation"" filings sent by the Department to local courts, based on misconduct by the probation client, during the reporting period." t:dataTypeName=number

entity e:mzy5-smmw l:"DOP Juvenile Violations of Probation Filed by Fiscal Year" t:attribution="Department of Probation (DOP)" t:url=https://data.cityofnewyork.us/api/views/mzy5-smmw

property e:mzy5-smmw t:meta.view v:id=mzy5-smmw v:category="City Government" v:averageRating=0 v:name="DOP Juvenile Violations of Probation Filed by Fiscal Year" v:attribution="Department of Probation (DOP)"

property e:mzy5-smmw t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:mzy5-smmw t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| borough  | fiscal_year_ending_in_june_ | filed_violation_count | 
| ======== | =========================== | ===================== | 
| Bronx    | 2006                        | 222                   | 
| Bronx    | 2007                        | 180                   | 
| Bronx    | 2008                        | 217                   | 
| Bronx    | 2009                        | 216                   | 
| Bronx    | 2010                        | 222                   | 
| Bronx    | 2011                        | 153                   | 
| Bronx    | 2012                        | 168                   | 
| Bronx    | 2013                        | 133                   | 
| Brooklyn | 2006                        | 314                   | 
| Brooklyn | 2007                        | 274                   | 
```