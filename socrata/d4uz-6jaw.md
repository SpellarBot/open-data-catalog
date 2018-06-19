# Inmate Arrests

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/inmate-arrests-1474b) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/d4uz-6jaw) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/d4uz-6jaw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/d4uz-6jaw/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | d4uz-6jaw |
| Name | Inmate Arrests |
| Attribution | Department of Correction (DOC) |
| Category | Public Safety |
| Tags | corrections, jail, prison, inmate, facility, rikers, population, arrest |
| Created | 2011-10-07T00:13:46Z |
| Publication Date | 2013-06-26T17:13:26Z |

## Description

Inmate Arrests by fiscal year

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
series e:d4uz-6jaw d:2010-01-01T00:00:00.000Z m:number_of_arrests=526

series e:d4uz-6jaw d:2009-01-01T00:00:00.000Z m:number_of_arrests=567

series e:d4uz-6jaw d:2008-01-01T00:00:00.000Z m:number_of_arrests=751
```

## Meta Commands

```ls
metric m:number_of_arrests p:integer l:"Number of Arrests" t:dataTypeName=number

entity e:d4uz-6jaw l:"Inmate Arrests" t:attribution="Department of Correction (DOC)" t:url=https://data.cityofnewyork.us/api/views/d4uz-6jaw

property e:d4uz-6jaw t:meta.view v:id=d4uz-6jaw v:category="Public Safety" v:averageRating=0 v:name="Inmate Arrests" v:attribution="Department of Correction (DOC)"

property e:d4uz-6jaw t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:d4uz-6jaw t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| fiscal_year | number_of_arrests | 
| =========== | ================= | 
| 2010        | 526               | 
| 2009        | 567               | 
| 2008        | 751               | 
| 2007        | 738               | 
| 2006        | 654               | 
| 2005        | 684               | 
| 2004        | 628               | 
| 2003        | 671               | 
| 2002        | 576               | 
| 2001        | 853               | 
```