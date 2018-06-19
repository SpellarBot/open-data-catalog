# DOP Adult Investigations by Fiscal Year

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dop-adult-investigations-by-fiscal-year-a6d57) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/vvym-pu7g) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/vvym-pu7g/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/vvym-pu7g/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | vvym-pu7g |
| Name | DOP Adult Investigations by Fiscal Year |
| Attribution | Department of Probation (DOP) |
| Category | City Government |
| Tags | dop, investigations, fiscal year, adult |
| Created | 2014-02-26T21:30:28Z |
| Publication Date | 2016-09-16T00:57:24Z |

## Description

The number of presentence investigation reports ordered for adults during the reporting period, categorized by conviction type: felony and misdemeanor.

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                         | Data Type | Render Type |
| ======== | ============== | =========================== | ============================ | ========= | =========== |
| Yes      | series tag     | borough                     | Borough                      | text      | text        |
| Yes      | time           | fiscal_year_ending_in_june_ | Fiscal Year (ending in June) | number    | number      |
| Yes      | series tag     | charge_type                 | Charge Type                  | text      | text        |
| Yes      | numeric metric | investigation_count         | Investigation Count          | number    | number      |
```

## Time Field

```ls
Value = fiscal_year_ending_in_june_
Format & Zone = yyyy
```

## Data Commands

```ls
series e:vvym-pu7g d:2006-01-01T00:00:00.000Z t:charge_type=Misdemeanors t:borough=Bronx m:investigation_count=1446

series e:vvym-pu7g d:2007-01-01T00:00:00.000Z t:charge_type=Misdemeanors t:borough=Bronx m:investigation_count=1987

series e:vvym-pu7g d:2008-01-01T00:00:00.000Z t:charge_type=Misdemeanors t:borough=Bronx m:investigation_count=1500
```

## Meta Commands

```ls
metric m:investigation_count p:integer l:"Investigation Count" d:"The number of presentence investigation reports ordered for adults during the reporting period." t:dataTypeName=number

entity e:vvym-pu7g l:"DOP Adult Investigations by Fiscal Year" t:attribution="Department of Probation (DOP)" t:url=https://data.cityofnewyork.us/api/views/vvym-pu7g

property e:vvym-pu7g t:meta.view v:id=vvym-pu7g v:category="City Government" v:averageRating=0 v:name="DOP Adult Investigations by Fiscal Year" v:attribution="Department of Probation (DOP)"

property e:vvym-pu7g t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:vvym-pu7g t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| borough | fiscal_year_ending_in_june_ | charge_type  | investigation_count | 
| ======= | =========================== | ============ | =================== | 
| Bronx   | 2006                        | Misdemeanors | 1446                | 
| Bronx   | 2007                        | Misdemeanors | 1987                | 
| Bronx   | 2008                        | Misdemeanors | 1500                | 
| Bronx   | 2009                        | Misdemeanors | 1350                | 
| Bronx   | 2010                        | Misdemeanors | 1183                | 
| Bronx   | 2011                        | Misdemeanors | 1117                | 
| Bronx   | 2012                        | Misdemeanors | 1255                | 
| Bronx   | 2013                        | Misdemeanors | 1044                | 
| Bronx   | 2006                        | Felonies     | 3699                | 
| Bronx   | 2007                        | Felonies     | 3159                | 
```