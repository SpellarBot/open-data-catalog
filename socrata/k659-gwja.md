# DOP Adult Investigations by Calendar Year

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dop-adult-investigations-by-calendar-year-522ab) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/k659-gwja) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/k659-gwja/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/k659-gwja/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | k659-gwja |
| Name | DOP Adult Investigations by Calendar Year |
| Attribution | Department of Probation (DOP) |
| Category | City Government |
| Tags | dop, investigations, calendar year, adult |
| Created | 2014-02-26T17:30:51Z |
| Publication Date | 2017-03-08T19:53:14Z |

## Description

The number of presentence investigation reports ordered for adults during the reporting period, categorized by conviction type: felony and misdemeanor.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| Yes      | series tag     | borough             | Borough             | text      | text        |
| Yes      | time           | calendar_year       | Calendar Year       | number    | number      |
| Yes      | series tag     | charge_type         | Charge Type         | text      | text        |
| Yes      | numeric metric | investigation_count | Investigation Count | number    | number      |
```

## Time Field

```ls
Value = calendar_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:k659-gwja d:2006-01-01T00:00:00.000Z t:charge_type=Misdemeanors t:borough=Bronx m:investigation_count=1606

series e:k659-gwja d:2007-01-01T00:00:00.000Z t:charge_type=Misdemeanors t:borough=Bronx m:investigation_count=1854

series e:k659-gwja d:2008-01-01T00:00:00.000Z t:charge_type=Misdemeanors t:borough=Bronx m:investigation_count=1395
```

## Meta Commands

```ls
metric m:investigation_count p:integer l:"Investigation Count" d:"The number of presentence investigation reports ordered for adults during the reporting period." t:dataTypeName=number

entity e:k659-gwja l:"DOP Adult Investigations by Calendar Year" t:attribution="Department of Probation (DOP)" t:url=https://data.cityofnewyork.us/api/views/k659-gwja

property e:k659-gwja t:meta.view v:id=k659-gwja v:category="City Government" v:averageRating=0 v:name="DOP Adult Investigations by Calendar Year" v:attribution="Department of Probation (DOP)"

property e:k659-gwja t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:k659-gwja t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| borough | calendar_year | charge_type  | investigation_count | 
| ======= | ============= | ============ | =================== | 
| Bronx   | 2006          | Misdemeanors | 1606                | 
| Bronx   | 2007          | Misdemeanors | 1854                | 
| Bronx   | 2008          | Misdemeanors | 1395                | 
| Bronx   | 2009          | Misdemeanors | 1346                | 
| Bronx   | 2010          | Misdemeanors | 1076                | 
| Bronx   | 2011          | Misdemeanors | 1161                | 
| Bronx   | 2012          | Misdemeanors | 1127                | 
| Bronx   | 2006          | Felonies     | 3469                | 
| Bronx   | 2007          | Felonies     | 3619                | 
| Bronx   | 2008          | Felonies     | 3524                | 
```