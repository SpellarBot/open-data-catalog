# DOP Juvenile Supervision Intakes by Calendar Year

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dop-juvenile-supervision-intakes-by-calendar-year-78ba5) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/tgqn-na2n) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/tgqn-na2n/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/tgqn-na2n/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | tgqn-na2n |
| Name | DOP Juvenile Supervision Intakes by Calendar Year |
| Attribution | Department of Probation (DOP) |
| Category | City Government |
| Tags | dop, supervision, calendar year, juvenile |
| Created | 2014-04-07T16:21:47Z |
| Publication Date | 2017-03-08T21:19:09Z |

## Description

The number of youths sentenced to probation supervision during the reporting period.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| Yes      | series tag     | borough       | Borough       | text      | text        |
| Yes      | time           | calendar_year | Calendar Year | number    | number      |
| Yes      | series tag     | case_type     | Case Type     | text      | text        |
| Yes      | numeric metric | client_total  | Client Total  | number    | number      |
```

## Time Field

```ls
Value = calendar_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:tgqn-na2n d:2006-01-01T00:00:00.000Z t:borough=Bronx t:case_type=JD m:client_total=556

series e:tgqn-na2n d:2007-01-01T00:00:00.000Z t:borough=Bronx t:case_type=JD m:client_total=516

series e:tgqn-na2n d:2008-01-01T00:00:00.000Z t:borough=Bronx t:case_type=JD m:client_total=445
```

## Meta Commands

```ls
metric m:client_total p:integer l:"Client Total" d:"The number of youths sentenced to probation supervision during the reporting period." t:dataTypeName=number

entity e:tgqn-na2n l:"DOP Juvenile Supervision Intakes by Calendar Year" t:attribution="Department of Probation (DOP)" t:url=https://data.cityofnewyork.us/api/views/tgqn-na2n

property e:tgqn-na2n t:meta.view v:id=tgqn-na2n v:category="City Government" v:averageRating=0 v:name="DOP Juvenile Supervision Intakes by Calendar Year" v:attribution="Department of Probation (DOP)"

property e:tgqn-na2n t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:tgqn-na2n t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| borough | calendar_year | case_type | client_total | 
| ======= | ============= | ========= | ============ | 
| Bronx   | 2006          | JD        | 556          | 
| Bronx   | 2007          | JD        | 516          | 
| Bronx   | 2008          | JD        | 445          | 
| Bronx   | 2009          | JD        | 457          | 
| Bronx   | 2010          | JD        | 431          | 
| Bronx   | 2011          | JD        | 419          | 
| Bronx   | 2012          | JD        | 367          | 
| Bronx   | 2013          | JD        | 324          | 
| Bronx   | 2006          | ESP       | 190          | 
| Bronx   | 2007          | ESP       | 167          | 
```