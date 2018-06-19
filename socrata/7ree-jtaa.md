# DOP Juvenile Intakes by Calendar Year

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dop-juvenile-intakes-by-calendar-year-0dc78) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/7ree-jtaa) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/7ree-jtaa/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/7ree-jtaa/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 7ree-jtaa |
| Name | DOP Juvenile Intakes by Calendar Year |
| Attribution | Department of Probation (DOP) |
| Category | City Government |
| Tags | dop, intakes, calendar year, juvenile |
| Created | 2014-04-07T16:21:27Z |
| Publication Date | 2017-03-08T21:07:04Z |

## Description

The number of youth received in probation intake (pre-adjudication services) during the reporting period.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| Yes      | series tag     | borough       | Borough       | text      | text        |
| Yes      | time           | calendar_year | Calendar Year | number    | number      |
| Yes      | numeric metric | client_total  | Client Total  | number    | number      |
```

## Time Field

```ls
Value = calendar_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:7ree-jtaa d:2006-01-01T00:00:00.000Z t:borough=Bronx m:client_total=2515

series e:7ree-jtaa d:2007-01-01T00:00:00.000Z t:borough=Bronx m:client_total=2922

series e:7ree-jtaa d:2008-01-01T00:00:00.000Z t:borough=Bronx m:client_total=3491
```

## Meta Commands

```ls
metric m:client_total p:integer l:"Client Total" d:"The number of youth received in probation intake (pre-adjudication services) during the reporting period." t:dataTypeName=number

entity e:7ree-jtaa l:"DOP Juvenile Intakes by Calendar Year" t:attribution="Department of Probation (DOP)" t:url=https://data.cityofnewyork.us/api/views/7ree-jtaa

property e:7ree-jtaa t:meta.view v:id=7ree-jtaa v:category="City Government" v:averageRating=0 v:name="DOP Juvenile Intakes by Calendar Year" v:attribution="Department of Probation (DOP)"

property e:7ree-jtaa t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:7ree-jtaa t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| borough  | calendar_year | client_total | 
| ======== | ============= | ============ | 
| Bronx    | 2006          | 2515         | 
| Bronx    | 2007          | 2922         | 
| Bronx    | 2008          | 3491         | 
| Bronx    | 2009          | 3782         | 
| Bronx    | 2010          | 4016         | 
| Bronx    | 2011          | 3827         | 
| Bronx    | 2012          | 2643         | 
| Bronx    | 2013          | 1984         | 
| Brooklyn | 2006          | 3268         | 
| Brooklyn | 2007          | 3471         | 
```