# Number of LADWP Customer Accounts

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/number-of-ladwp-customer-accounts-f169f) |
| Metadata | [Link](https://data.lacity.org/api/views/4z5w-yabs) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/4z5w-yabs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/4z5w-yabs/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | 4z5w-yabs |
| Name | Number of LADWP Customer Accounts |
| Attribution | LADWP |
| Category | A Prosperous City |
| Tags | customer accounts |
| Created | 2014-05-23T21:51:21Z |
| Publication Date | 2014-05-23T21:53:12Z |

## Description

Total number of Customer Accounts at LADWP from year to year.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| Yes      | time           | year        | Year        | number    | number      |
| Yes      | numeric metric | residential | Residential | number    | number      |
| Yes      | numeric metric | commercial  | Commercial  | number    | number      |
| Yes      | numeric metric | industrial  | Industrial  | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:4z5w-yabs d:1992-01-01T00:00:00.000Z m:industrial=17833 m:residential=1165743 m:commercial=116242

series e:4z5w-yabs d:1993-01-01T00:00:00.000Z m:industrial=17220 m:residential=1162104 m:commercial=114929

series e:4z5w-yabs d:1994-01-01T00:00:00.000Z m:industrial=16760 m:residential=1147666 m:commercial=114095
```

## Meta Commands

```ls
metric m:residential p:integer l:Residential t:dataTypeName=number

metric m:commercial p:integer l:Commercial t:dataTypeName=number

metric m:industrial p:integer l:Industrial t:dataTypeName=number

entity e:4z5w-yabs l:"Number of LADWP Customer Accounts" t:attribution=LADWP t:url=https://data.lacity.org/api/views/4z5w-yabs

property e:4z5w-yabs t:meta.view v:id=4z5w-yabs v:category="A Prosperous City" v:averageRating=0 v:name="Number of LADWP Customer Accounts" v:attribution=LADWP

property e:4z5w-yabs t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:4z5w-yabs t:meta.view.owner v:id=7q7s-tyf3 v:screenName="Steve Baule" v:displayName="Steve Baule"

property e:4z5w-yabs t:meta.view.tableauthor v:id=7q7s-tyf3 v:screenName="Steve Baule" v:roleName=publisher v:displayName="Steve Baule"
```

## Top Records

```ls
| year | residential | commercial | industrial | 
| ==== | =========== | ========== | ========== | 
| 1992 | 1165743     | 116242     | 17833      | 
| 1993 | 1162104     | 114929     | 17220      | 
| 1994 | 1147666     | 114095     | 16760      | 
| 1995 | 1149850     | 113882     | 16328      | 
| 1996 | 1155349     | 115087     | 16192      | 
| 1997 | 1165787     | 115662     | 16057      | 
| 1998 | 1175951     | 116422     | 15966      | 
| 1999 | 1191701     | 117442     | 15829      | 
| 2000 | 1204270     | 119991     | 15773      | 
| 2001 | 1211225     | 119098     | 15536      | 
```