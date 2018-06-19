# DOC Visitor Arrests

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/doc-visitor-arrests-4f77e) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/hm7r-w4y9) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/hm7r-w4y9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/hm7r-w4y9/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | hm7r-w4y9 |
| Name | DOC Visitor Arrests |
| Attribution | Department of Correction (DOC) |
| Category | Public Safety |
| Tags | corrections, jail, prison, inmate, facility, rikers, population, visitor, arrest |
| Created | 2011-10-07T00:16:47Z |
| Publication Date | 2013-06-26T17:14:18Z |

## Description

Visitor arrests by fiscal year

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | time           | fiscal_year       | Fiscal Year       | number    | number      |
| Yes      | numeric metric | number_of_arrests | Number of Arrests | number    | number      |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:hm7r-w4y9 d:2010-01-01T00:00:00.000Z m:number_of_arrests=292

series e:hm7r-w4y9 d:2009-01-01T00:00:00.000Z m:number_of_arrests=264

series e:hm7r-w4y9 d:2008-01-01T00:00:00.000Z m:number_of_arrests=201
```

## Meta Commands

```ls
metric m:number_of_arrests p:integer l:"Number of Arrests" t:dataTypeName=number

entity e:hm7r-w4y9 l:"DOC Visitor Arrests" t:attribution="Department of Correction (DOC)" t:url=https://data.cityofnewyork.us/api/views/hm7r-w4y9

property e:hm7r-w4y9 t:meta.view v:id=hm7r-w4y9 v:category="Public Safety" v:averageRating=0 v:name="DOC Visitor Arrests" v:attribution="Department of Correction (DOC)"

property e:hm7r-w4y9 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:hm7r-w4y9 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| fiscal_year | number_of_arrests | 
| =========== | ================= | 
| 2010        | 292               | 
| 2009        | 264               | 
| 2008        | 201               | 
| 2007        | 318               | 
| 2006        | 295               | 
| 2005        | 367               | 
| 2004        | 360               | 
| 2003        | 341               | 
| 2002        | 313               | 
| 2001        | 392               | 
```