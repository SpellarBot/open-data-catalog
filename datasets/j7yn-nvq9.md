# DOF: Summary of Neighborhood Sales in Queens for Class 1-, 2- and 3-Family homes - 2006

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dof-summary-of-neighborhood-sales-in-queens-for-class-1-2-and-3-family-homes-2006-bbd82) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/j7yn-nvq9) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/j7yn-nvq9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/j7yn-nvq9/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | j7yn-nvq9 |
| Name | DOF: Summary of Neighborhood Sales in Queens for Class 1-, 2- and 3-Family homes - 2006 |
| Attribution | Department of Finance (DOF) |
| Category | Housing & Development |
| Tags | family homes, class-1, class-2, class-3, borough, queens |
| Created | 2011-10-05T20:54:29Z |
| Publication Date | 2013-06-26T17:03:52Z |

## Description

The Department of Finance (DOF) maintains records for all property sales in New York City, including sales of family homes in each borough. This list is a summary of neighborhood sales for Class 1-, 2- and 3-Family homes in Queens in 2006.

This list includes all sales of 1-, 2-, and 3-Family Homes' from January 1st, 2006 to December 31, 2006, whose sale price is equal to or more than $150,000.  The Building Class Category for Sales is based on the Building Class at the time of the sale.

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
Value = 2006
Format & Zone = yyyy
```

## Data Commands

```ls
series e:j7yn-nvq9 d:2006-01-01T00:00:00.000Z t:neighborhood="AIRPORT LA GUARDIA" t:type_of_home="01 ONE FAMILY HOMES" m:average_sale_price=488000 m:lowest_sale_price=475000 m:median_sale_price=488000 m:highest_sale_price=501000 m:number_of_sales=2

series e:j7yn-nvq9 d:2006-01-01T00:00:00.000Z t:neighborhood="AIRPORT LA GUARDIA" t:type_of_home="03 THREE FAMILY HOMES" m:average_sale_price=825000 m:lowest_sale_price=825000 m:median_sale_price=825000 m:highest_sale_price=825000 m:number_of_sales=1

series e:j7yn-nvq9 d:2006-01-01T00:00:00.000Z t:neighborhood=ARVERNE t:type_of_home="01 ONE FAMILY HOMES" m:average_sale_price=316933 m:lowest_sale_price=150000 m:median_sale_price=335629 m:highest_sale_price=600000 m:number_of_sales=93
```

## Meta Commands

```ls
metric m:number_of_sales p:integer l:"NUMBER OF SALES" t:dataTypeName=number

metric m:lowest_sale_price p:integer l:"LOWEST SALE PRICE" t:dataTypeName=money

metric m:average_sale_price p:integer l:"AVERAGE SALE PRICE" t:dataTypeName=money

metric m:median_sale_price p:integer l:"MEDIAN SALE PRICE" t:dataTypeName=money

metric m:highest_sale_price p:integer l:"HIGHEST SALE PRICE" t:dataTypeName=money

entity e:j7yn-nvq9 l:"DOF: Summary of Neighborhood Sales in Queens for Class 1-, 2- and 3-Family homes - 2006" t:attribution="Department of Finance (DOF)" t:url=https://data.cityofnewyork.us/api/views/j7yn-nvq9

property e:j7yn-nvq9 t:meta.view v:id=j7yn-nvq9 v:category="Housing & Development" v:averageRating=0 v:name="DOF: Summary of Neighborhood Sales in Queens for Class 1-, 2- and 3-Family homes - 2006" v:attribution="Department of Finance (DOF)"

property e:j7yn-nvq9 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:j7yn-nvq9 t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| neighborhood       | type_of_home          | number_of_sales | lowest_sale_price | average_sale_price | median_sale_price | highest_sale_price | 
| ================== | ===================== | =============== | ================= | ================== | ================= | ================== | 
| AIRPORT LA GUARDIA | 01 ONE FAMILY HOMES   | 2               | 475000            | 488000             | 488000            | 501000             | 
| AIRPORT LA GUARDIA | 03 THREE FAMILY HOMES | 1               | 825000            | 825000             | 825000            | 825000             | 
| ARVERNE            | 01 ONE FAMILY HOMES   | 93              | 150000            | 316933             | 335629            | 600000             | 
| ARVERNE            | 02 TWO FAMILY HOMES   | 218             | 155000            | 472534             | 484500            | 700000             | 
| ARVERNE            | 03 THREE FAMILY HOMES | 24              | 355000            | 511327             | 514000            | 690000             | 
| ASTORIA            | 01 ONE FAMILY HOMES   | 80              | 260000            | 598629             | 567500            | 1375000            | 
| ASTORIA            | 02 TWO FAMILY HOMES   | 172             | 227500            | 750228             | 749250            | 1650000            | 
| ASTORIA            | 03 THREE FAMILY HOMES | 81              | 200000            | 822494             | 830000            | 1300000            | 
| BAYSIDE            | 01 ONE FAMILY HOMES   | 312             | 150000            | 692745             | 652500            | 2500000            | 
| BAYSIDE            | 02 TWO FAMILY HOMES   | 136             | 194321            | 772739             | 770000            | 1602000            | 
```