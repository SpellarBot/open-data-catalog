# DOP Eligible Diversion Rate for Juveniles by Calendar Year

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dop-eligible-diversion-rate-for-juveniles-by-calendar-year-2410e) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/qnwe-j5my) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/qnwe-j5my/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/qnwe-j5my/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | qnwe-j5my |
| Name | DOP Eligible Diversion Rate for Juveniles by Calendar Year |
| Attribution | Department of Probation (DOP) |
| Category | City Government |
| Tags | dop, probation, eligible diversion rate, juvenile, calendar year |
| Created | 2014-06-17T16:46:09Z |
| Publication Date | 2017-03-08T21:03:59Z |

## Description

The percent of juvenile delinquency Intake cases opened for adjustment services (individual / family counseling, substance abuse treatment, etc.) rather than being immediately referred to family court for adjudication. Derived by dividing the number of eligible adjustment cases by all new Intake cases

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type | Render Type |
| ======== | ============== | ========================= | ========================= | ========= | =========== |
| Yes      | series tag     | borough                   | Borough                   | text      | text        |
| Yes      | time           | calendar_year             | Calendar Year             | number    | number      |
| Yes      | numeric metric | diversion_rate_percentage | Diversion Rate Percentage | percent   | percent     |
```

## Time Field

```ls
Value = calendar_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:qnwe-j5my d:2009-01-01T00:00:00.000Z t:borough=Bronx m:diversion_rate_percentage=29

series e:qnwe-j5my d:2010-01-01T00:00:00.000Z t:borough=Bronx m:diversion_rate_percentage=35

series e:qnwe-j5my d:2011-01-01T00:00:00.000Z t:borough=Bronx m:diversion_rate_percentage=44
```

## Meta Commands

```ls
metric m:diversion_rate_percentage p:integer l:"Diversion Rate Percentage" d:"The percent of juvenile delinquency Intake cases opened for adjustment services (individual / family counseling, substance abuse treatment, etc.) rather than being immediately referred to family court for adjudication. Derived by dividing the number of eligible adjustment cases by all new Intake cases" t:dataTypeName=percent

entity e:qnwe-j5my l:"DOP Eligible Diversion Rate for Juveniles by Calendar Year" t:attribution="Department of Probation (DOP)" t:url=https://data.cityofnewyork.us/api/views/qnwe-j5my

property e:qnwe-j5my t:meta.view v:id=qnwe-j5my v:category="City Government" v:averageRating=0 v:name="DOP Eligible Diversion Rate for Juveniles by Calendar Year" v:attribution="Department of Probation (DOP)"

property e:qnwe-j5my t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:qnwe-j5my t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| borough  | calendar_year | diversion_rate_percentage | 
| ======== | ============= | ========================= | 
| Bronx    | 2009          | 29                        | 
| Bronx    | 2010          | 35                        | 
| Bronx    | 2011          | 44                        | 
| Bronx    | 2012          | 43                        | 
| Bronx    | 2013          | 26                        | 
| Brooklyn | 2009          | 27                        | 
| Brooklyn | 2010          | 34                        | 
| Brooklyn | 2011          | 39                        | 
| Brooklyn | 2012          | 34                        | 
| Brooklyn | 2013          | 32                        | 
```