# DOF: Summary of Neighborhood Sales in Staten Island for Class 1-, 2- and 3-Family homes - 2008

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dof-summary-of-neighborhood-sales-in-staten-island-for-class-1-2-and-3-family-homes-2008-99780) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/rp8m-vm93) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/rp8m-vm93/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/rp8m-vm93/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | rp8m-vm93 |
| Name | DOF: Summary of Neighborhood Sales in Staten Island for Class 1-, 2- and 3-Family homes - 2008 |
| Attribution | Department of Finance (DOF) |
| Category | Housing & Development |
| Tags | department of finance, finance, dof, property, properties, neighborhoods, sales, neighborhood sales, homes, family homes, class-1, class-2, class-3, borough, staten island |
| Created | 2011-10-05T19:25:50Z |
| Publication Date | 2013-06-26T17:03:59Z |

## Description

The Department of Finance (DOF) maintains records for all property sales in New York City, including sales of family homes in each borough. This list is a summary of neighborhood sales for Class 1-, 2- and 3-Family homes in Staten Island in 2008.


This list includes all sales of 1-, 2-, and 3-Family Homes' from January 1st, 2008 to December 31, 2008, whose sale price is equal to or more than $150,000.  The Building Class Category for Sales is based on the Building Class at the time of the sale.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| Yes      | series tag     | neighborhood       | NEIGHBORHOOD       | text      | text        |
| Yes      | series tag     | type_of_home       | TYPE OF HOME       | text      | text        |
| Yes      | numeric metric | number_of_sales    | NUMBER OF SALES    | number    | number      |
| Yes      | numeric metric | lowest_sale_price  | LOWEST SALE PRICE  | money     | money       |
| Yes      | numeric metric | average_sale_price | AVERAGE SALE PRICE | money     | money       |
| Yes      | numeric metric | median_sale_price  | MEDIAN SALE PRICE  | money     | money       |
| Yes      | numeric metric | highest_sale_price | HIGHEST SALE PRICE | money     | money       |
```

## Time Field

```ls
Value = 2008
Format & Zone = yyyy
```

## Data Commands

```ls
series e:rp8m-vm93 d:2008-01-01T00:00:00.000Z t:neighborhood=ANNADALE t:type_of_home="01 ONE FAMILY HOMES" m:average_sale_price=566350 m:lowest_sale_price=155230 m:median_sale_price=495000 m:highest_sale_price=2170000 m:number_of_sales=55

series e:rp8m-vm93 d:2008-01-01T00:00:00.000Z t:neighborhood=ANNADALE t:type_of_home="02 TWO FAMILY HOMES" m:average_sale_price=616840 m:lowest_sale_price=464000 m:median_sale_price=574802 m:highest_sale_price=1250000 m:number_of_sales=26

series e:rp8m-vm93 d:2008-01-01T00:00:00.000Z t:neighborhood="ARDEN HEIGHTS" t:type_of_home="01 ONE FAMILY HOMES" m:average_sale_price=334236 m:lowest_sale_price=150000 m:median_sale_price=320000 m:highest_sale_price=560037 m:number_of_sales=149
```

## Meta Commands

```ls
metric m:number_of_sales p:integer l:"NUMBER OF SALES" t:dataTypeName=number

metric m:lowest_sale_price p:integer l:"LOWEST SALE PRICE" t:dataTypeName=money

metric m:average_sale_price p:integer l:"AVERAGE SALE PRICE" t:dataTypeName=money

metric m:median_sale_price p:integer l:"MEDIAN SALE PRICE" t:dataTypeName=money

metric m:highest_sale_price p:integer l:"HIGHEST SALE PRICE" t:dataTypeName=money

entity e:rp8m-vm93 l:"DOF: Summary of Neighborhood Sales in Staten Island for Class 1-, 2- and 3-Family homes - 2008" t:attribution="Department of Finance (DOF)" t:url=https://data.cityofnewyork.us/api/views/rp8m-vm93

property e:rp8m-vm93 t:meta.view v:id=rp8m-vm93 v:category="Housing & Development" v:averageRating=0 v:name="DOF: Summary of Neighborhood Sales in Staten Island for Class 1-, 2- and 3-Family homes - 2008" v:attribution="Department of Finance (DOF)"

property e:rp8m-vm93 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:rp8m-vm93 t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| neighborhood         | type_of_home        | number_of_sales | lowest_sale_price | average_sale_price | median_sale_price | highest_sale_price | 
| ==================== | =================== | =============== | ================= | ================== | ================= | ================== | 
| ANNADALE             | 01 ONE FAMILY HOMES | 55              | 155230            | 566350             | 495000            | 2170000            | 
| ANNADALE             | 02 TWO FAMILY HOMES | 26              | 464000            | 616840             | 574802            | 1250000            | 
| ARDEN HEIGHTS        | 01 ONE FAMILY HOMES | 149             | 150000            | 334236             | 320000            | 560037             | 
| ARDEN HEIGHTS        | 02 TWO FAMILY HOMES | 16              | 398000            | 536761             | 510000            | 740267             | 
| ARROCHAR             | 01 ONE FAMILY HOMES | 15              | 350000            | 479797             | 442000            | 950000             | 
| ARROCHAR-SHORE ACRES | 01 ONE FAMILY HOMES | 3               | 345000            | 385667             | 390000            | 422000             | 
| ARROCHAR-SHORE ACRES | 02 TWO FAMILY HOMES | 1               | 472500            | 472500             | 472500            | 472500             | 
| BLOOMFIELD           | 02 TWO FAMILY HOMES | 1               | 1350000           | 1350000            | 1350000           | 1350000            | 
| BULLS HEAD           | 01 ONE FAMILY HOMES | 54              | 166000            | 346410             | 339795            | 675000             | 
| BULLS HEAD           | 02 TWO FAMILY HOMES | 38              | 180000            | 468593             | 489984            | 670000             | 
```