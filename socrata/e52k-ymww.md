# Fish Stocking Lists (Actual): Beginning 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fish-stocking-lists-actual-beginning-2011) |
| Metadata | [Link](https://data.ny.gov/api/views/e52k-ymww) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/e52k-ymww/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/e52k-ymww/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | e52k-ymww |
| Name | Fish Stocking Lists (Actual): Beginning 2011 |
| Attribution | NYSDEC |
| Category | Recreation |
| Tags | stocking, river, lakes, ponds, streams, brook trout, brown trout, rainbow trout, lake trout, chinook, coho, steelhead, landlocked salmon, walleye, muskellunge, tiger muskellunge |
| Created | 2016-06-09T15:03:01Z |
| Publication Date | 2016-06-23T16:24:17Z |

## Description

DEC stocks approximately 900,000 pounds of fish into more than 1,200 public streams, rivers, lakes and ponds across the state. Also included in the data are public stockings by Essex, Onondaga and Warren counties.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name          | Data Type | Render Type |
| ======== | ============== | =========== | ============= | ========= | =========== |
| No       |                | year        | Year          | number    | number      |
| Yes      | series tag     | county      | County        | text      | text        |
| Yes      | series tag     | waterbody   | Waterbody     | text      | text        |
| Yes      | series tag     | town        | Town          | text      | text        |
| No       |                | month       | Month         | text      | text        |
| Yes      | numeric metric | number      | Number        | number    | number      |
| Yes      | series tag     | species     | Species       | text      | text        |
| Yes      | numeric metric | size_inches | Size (Inches) | number    | number      |
```

## Time Field

```ls
Value = year-month
Format & Zone = yyyy-MMMM
```

## Series Fields

```ls
Excluded Fields = year,month
```

## Data Commands

```ls
series e:e52k-ymww d:2011-04-01T00:00:00.000Z t:species="Brown Trout" t:county=Albany t:waterbody="Basic Creek" t:town=Westerlo m:size_inches=8.3 m:number=420

series e:e52k-ymww d:2011-04-01T00:00:00.000Z t:species="Brown Trout" t:county=Albany t:waterbody="Catskill Creek" t:town=Rensselaerville m:size_inches=8.8 m:number=720

series e:e52k-ymww d:2011-05-01T00:00:00.000Z t:species="Brown Trout" t:county=Albany t:waterbody="Catskill Creek" t:town=Rensselaerville m:size_inches=8.8 m:number=170
```

## Meta Commands

```ls
metric m:number p:integer l:Number d:"Number of fish stocked." t:dataTypeName=number

metric m:size_inches p:float l:"Size (Inches)" d:"Size range of fish stocked." t:dataTypeName=number

entity e:e52k-ymww l:"Fish Stocking Lists (Actual): Beginning 2011" t:attribution=NYSDEC t:url=https://data.ny.gov/api/views/e52k-ymww

property e:e52k-ymww t:meta.view v:id=e52k-ymww v:category=Recreation v:attributionLink=http://www.dec.ny.gov/outdoor/7739.html v:averageRating=0 v:name="Fish Stocking Lists (Actual): Beginning 2011" v:attribution=NYSDEC

property e:e52k-ymww t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:e52k-ymww t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| year | county | waterbody         | town            | month     | number | species           | size_inches | 
| ==== | ====== | ================= | =============== | ========= | ====== | ================= | =========== | 
| 2011 | Albany | Basic Creek       | Westerlo        | April     | 420    | Brown Trout       | 8.3         | 
| 2011 | Albany | Catskill Creek    | Rensselaerville | April     | 720    | Brown Trout       | 8.8         | 
| 2011 | Albany | Catskill Creek    | Rensselaerville | May       | 170    | Brown Trout       | 8.8         | 
| 2011 | Albany | Hannacrois Creek  | Coeymans        | April     | 680    | Brown Trout       | 8.3         | 
| 2011 | Albany | Hannacrois Creek  | Coeymans        | April     | 1020   | Brown Trout       | 8.3         | 
| 2011 | Albany | Hannacrois Creek  | Coeymans        | April     | 130    | Brown Trout       | 13          | 
| 2011 | Albany | Lisha Kill        | Colonie         | March     | 340    | Brown Trout       | 7.8         | 
| 2011 | Albany | Mohawk River      | Colonie         | September | 5700   | Tiger Muskellunge | 9.6         | 
| 2011 | Albany | Onesquethaw Creek | New Scotland    | April     | 1100   | Brown Trout       | 8.3         | 
| 2011 | Albany | Onesquethaw Creek | New Scotland    | April     | 100    | Brown Trout       | 13          | 
```