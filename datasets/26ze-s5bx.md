# Average Daily Inmate Population

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/average-daily-inmate-population-edd3c) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/26ze-s5bx) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/26ze-s5bx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/26ze-s5bx/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 26ze-s5bx |
| Name | Average Daily Inmate Population |
| Attribution | Department of Correction (DOC) |
| Category | Public Safety |
| Tags | corrections, jail, prison, inmate, facility, rikers, population, arrest |
| Created | 2011-10-06T23:50:47Z |
| Publication Date | 2013-06-26T17:13:35Z |

## Description

Average daily inmate population by fiscal year Note: The data for each of these indicators is based upon year of report, not year of occurrence.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | time           | fiscal_year       | Fiscal year       | number    | number      |
| Yes      | numeric metric | inmate_population | Inmate Population | number    | number      |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:26ze-s5bx d:2010-01-01T00:00:00.000Z m:inmate_population=13049

series e:26ze-s5bx d:2009-01-01T00:00:00.000Z m:inmate_population=13362

series e:26ze-s5bx d:2008-01-01T00:00:00.000Z m:inmate_population=13850
```

## Meta Commands

```ls
metric m:inmate_population p:integer l:"Inmate Population" t:dataTypeName=number

entity e:26ze-s5bx l:"Average Daily Inmate Population" t:attribution="Department of Correction (DOC)" t:url=https://data.cityofnewyork.us/api/views/26ze-s5bx

property e:26ze-s5bx t:meta.view v:id=26ze-s5bx v:category="Public Safety" v:averageRating=0 v:name="Average Daily Inmate Population" v:attribution="Department of Correction (DOC)"

property e:26ze-s5bx t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:26ze-s5bx t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| fiscal_year | inmate_population | 
| =========== | ================= | 
| 2010        | 13049             | 
| 2009        | 13362             | 
| 2008        | 13850             | 
| 2007        | 13987             | 
| 2006        | 13497             | 
| 2005        | 13576             | 
| 2004        | 13751             | 
| 2003        | 14533             | 
| 2002        | 13934             | 
| 2001        | 14490             | 
```