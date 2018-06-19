# DOP Juvenile Investigations by Calendar Year

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dop-juvenile-investigations-by-calendar-year-6f34c) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/fsis-j6x5) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/fsis-j6x5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/fsis-j6x5/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | fsis-j6x5 |
| Name | DOP Juvenile Investigations by Calendar Year |
| Attribution | Department of Probation (DOP) |
| Category | City Government |
| Tags | dop, investigations, calendar year, juvenile |
| Created | 2014-02-26T21:30:43Z |
| Publication Date | 2017-03-08T21:17:10Z |

## Description

The number of presentence investigation reports completed for juveniles during the reporting period.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| Yes      | series tag     | borough             | Borough             | text      | text        |
| Yes      | time           | calendar_year       | Calendar Year       | number    | number      |
| Yes      | numeric metric | investigation_count | Investigation Count | number    | number      |
```

## Time Field

```ls
Value = calendar_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:fsis-j6x5 d:2006-01-01T00:00:00.000Z t:borough=Bronx m:investigation_count=1829

series e:fsis-j6x5 d:2007-01-01T00:00:00.000Z t:borough=Bronx m:investigation_count=1293

series e:fsis-j6x5 d:2008-01-01T00:00:00.000Z t:borough=Bronx m:investigation_count=1123
```

## Meta Commands

```ls
metric m:investigation_count p:integer l:"Investigation Count" d:"The number of presentence investigation reports completed for juveniles during the reporting period." t:dataTypeName=number

entity e:fsis-j6x5 l:"DOP Juvenile Investigations by Calendar Year" t:attribution="Department of Probation (DOP)" t:url=https://data.cityofnewyork.us/api/views/fsis-j6x5

property e:fsis-j6x5 t:meta.view v:id=fsis-j6x5 v:category="City Government" v:averageRating=0 v:name="DOP Juvenile Investigations by Calendar Year" v:attribution="Department of Probation (DOP)"

property e:fsis-j6x5 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:fsis-j6x5 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| borough  | calendar_year | investigation_count | 
| ======== | ============= | =================== | 
| Bronx    | 2006          | 1829                | 
| Bronx    | 2007          | 1293                | 
| Bronx    | 2008          | 1123                | 
| Bronx    | 2009          | 1827                | 
| Bronx    | 2010          | 1404                | 
| Bronx    | 2011          | 932                 | 
| Brooklyn | 2006          | 1088                | 
| Brooklyn | 2007          | 931                 | 
| Brooklyn | 2008          | 1000                | 
| Brooklyn | 2009          | 939                 | 
```