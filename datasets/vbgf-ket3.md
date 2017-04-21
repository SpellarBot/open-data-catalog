# DOP Juvenile Violations of Probation Filed by Calendar Year

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dop-juvenile-violations-of-probation-filed-by-calendar-year-d34fb) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/vbgf-ket3) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/vbgf-ket3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/vbgf-ket3/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | vbgf-ket3 |
| Name | DOP Juvenile Violations of Probation Filed by Calendar Year |
| Attribution | Department of Probation (DOP) |
| Category | City Government |
| Tags | dop, juvenile, violation, probation, filed, calendar year |
| Created | 2014-04-07T16:22:29Z |
| Publication Date | 2017-03-08T21:30:37Z |

## Description

The number of ?violation of probation? filings sent by the Department to local courts, in response to misconduct by the probation client, during the reporting period

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type | Render Type |
| ======== | ============== | ===================== | ===================== | ========= | =========== |
| Yes      | series tag     | borough               | Borough               | text      | text        |
| Yes      | time           | calendar_year         | Calendar Year         | number    | number      |
| Yes      | numeric metric | filed_violation_count | Filed Violation Count | number    | number      |
```

## Time Field

```ls
Value = calendar_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:vbgf-ket3 d:2006-01-01T00:00:00.000Z t:borough=Bronx m:filed_violation_count=210

series e:vbgf-ket3 d:2007-01-01T00:00:00.000Z t:borough=Bronx m:filed_violation_count=211

series e:vbgf-ket3 d:2008-01-01T00:00:00.000Z t:borough=Bronx m:filed_violation_count=209
```

## Meta Commands

```ls
metric m:filed_violation_count p:integer l:"Filed Violation Count" d:"The number of ""violation of probation"" filings sent by the Department to local courts, based on misconduct by the probation client, during the reporting period." t:dataTypeName=number

entity e:vbgf-ket3 l:"DOP Juvenile Violations of Probation Filed by Calendar Year" t:attribution="Department of Probation (DOP)" t:url=https://data.cityofnewyork.us/api/views/vbgf-ket3

property e:vbgf-ket3 t:meta.view v:id=vbgf-ket3 v:category="City Government" v:averageRating=0 v:name="DOP Juvenile Violations of Probation Filed by Calendar Year" v:attribution="Department of Probation (DOP)"

property e:vbgf-ket3 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:vbgf-ket3 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| borough  | calendar_year | filed_violation_count | 
| ======== | ============= | ===================== | 
| Bronx    | 2006          | 210                   | 
| Bronx    | 2007          | 211                   | 
| Bronx    | 2008          | 209                   | 
| Bronx    | 2009          | 216                   | 
| Bronx    | 2010          | 193                   | 
| Bronx    | 2011          | 145                   | 
| Bronx    | 2012          | 152                   | 
| Bronx    | 2013          | 161                   | 
| Brooklyn | 2006          | 371                   | 
| Brooklyn | 2007          | 219                   | 
```