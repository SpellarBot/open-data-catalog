# Libraries Material Inventory 2005 - 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/libraries-material-inventory-2005-2012-98af5) |
| Metadata | [Link](https://data.hawaii.gov/api/views/cip4-gcsk) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/cip4-gcsk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/cip4-gcsk/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | cip4-gcsk |
| Name | Libraries Material Inventory 2005 - 2012 |
| Attribution | Hawaii State Public Library System |
| Category | Formal Education |
| Tags | library |
| Created | 2012-07-30T23:50:59Z |
| Publication Date | 2012-07-31T21:04:34Z |

## Description

Inventory of materials and their value for all libraries statewide

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| Yes      | time           | year                 | Year                 | number    | number      |
| Yes      | series tag     | island               | ISLAND               | text      | text        |
| Yes      | series tag     | library              | LIBRARY              | text      | text        |
| Yes      | series tag     | inventory_descriptor | INVENTORY DESCRIPTOR | text      | text        |
| Yes      | numeric metric | items                | ITEMS                | number    | number      |
| Yes      | numeric metric | sum_price            | SUM PRICE            | money     | money       |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:cip4-gcsk d:2005-01-01T00:00:00.000Z t:library="Bond Memorial" t:inventory_descriptor="Library Materials Books" t:island=Hawaii m:sum_price=238457.06 m:items=15485

series e:cip4-gcsk d:2005-01-01T00:00:00.000Z t:library="Bond Memorial" t:inventory_descriptor="Library Materials Compact Disc" t:island=Hawaii m:sum_price=6041.87 m:items=302

series e:cip4-gcsk d:2005-01-01T00:00:00.000Z t:library="Bond Memorial" t:inventory_descriptor="Library Materials DVD" t:island=Hawaii m:sum_price=10058.39 m:items=411
```

## Meta Commands

```ls
metric m:items p:integer l:ITEMS t:dataTypeName=number

metric m:sum_price p:double l:"SUM PRICE" t:dataTypeName=money

entity e:cip4-gcsk l:"Libraries Material Inventory 2005 - 2012" t:attribution="Hawaii State Public Library System" t:url=https://data.hawaii.gov/api/views/cip4-gcsk

property e:cip4-gcsk t:meta.view v:id=cip4-gcsk v:category="Formal Education" v:attributionLink=http://www.librarieshawaii.org/ v:averageRating=0 v:name="Libraries Material Inventory 2005 - 2012" v:attribution="Hawaii State Public Library System"

property e:cip4-gcsk t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:cip4-gcsk t:meta.view.owner v:id=4hgi-fxu8 v:screenName="Paola Saibene" v:displayName="Paola Saibene"

property e:cip4-gcsk t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```

## Top Records

```ls
| year | island | library       | inventory_descriptor           | items  | sum_price  | 
| ==== | ====== | ============= | ============================== | ====== | ========== | 
| 2005 | Hawaii | Bond Memorial | Library Materials Books        | 15485  | 238457.06  | 
| 2005 | Hawaii | Bond Memorial | Library Materials Compact Disc | 302    | 6041.87    | 
| 2005 | Hawaii | Bond Memorial | Library Materials DVD          | 411    | 10058.39   | 
| 2005 | Hawaii | Bond Memorial | Library Materials Phonotape    | 196    | 4173.71    | 
| 2005 | Hawaii | Bond Memorial | Library Materials Videotape    | 521    | 10028.23   | 
| 2005 | Hawaii | Hilo          | Library Materials Books        | 206026 | 3313672.62 | 
| 2005 | Hawaii | Hilo          | Library Materials Compact Disc | 2149   | 39455.6    | 
| 2005 | Hawaii | Hilo          | Library Materials CD-ROM       | 4      | 159.8      | 
| 2005 | Hawaii | Hilo          | Library Materials DVD          | 814    | 19438.26   | 
| 2005 | Hawaii | Hilo          | Library Materials Microform    | 1      | 42.5       | 
```