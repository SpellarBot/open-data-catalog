# DOF: Summary of Neighborhood Sales in Queens for Class 1-, 2- and 3-Family homes - 2005

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dof-summary-of-neighborhood-sales-in-queens-for-class-1-2-and-3-family-homes-2005-b805f) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/7fnf-kyf4) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/7fnf-kyf4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/7fnf-kyf4/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 7fnf-kyf4 |
| Name | DOF: Summary of Neighborhood Sales in Queens for Class 1-, 2- and 3-Family homes - 2005 |
| Attribution | Department of Finance (DOF) |
| Category | Housing & Development |
| Tags | department of finance, finance, dof, property, properties, neighborhoods, sales, neighborhood sales, homes, family homes, class-1, class-2, class-3, borough, queens |
| Created | 2011-10-05T20:57:46Z |
| Publication Date | 2013-06-21T20:53:39Z |

## Description

The Department of Finance (DOF) maintains records for all property sales in New York City, including sales of family homes in each borough. This list is a summary of neighborhood sales for Class 1-, 2- and 3-Family homes in Queens in 2005.

This list includes all sales of 1-, 2-, and 3-Family Homes' from January 1st, 2005 to December 31, 2005, whose sale price is equal to or more than $150,000.  The Building Class Category for Sales is based on the Building Class at the time of the

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
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:7fnf-kyf4 d:2005-01-01T00:00:00.000Z t:neighborhood="AIRPORT LA GUARDIA" t:type_of_home="01 ONE FAMILY HOMES" m:average_sale_price=445958 m:lowest_sale_price=178750 m:median_sale_price=490000 m:highest_sale_price=530000 m:number_of_sales=6

series e:7fnf-kyf4 d:2005-01-01T00:00:00.000Z t:neighborhood="AIRPORT LA GUARDIA" t:type_of_home="02 TWO FAMILY HOMES" m:average_sale_price=507500 m:lowest_sale_price=475000 m:median_sale_price=507500 m:highest_sale_price=540000 m:number_of_sales=2

series e:7fnf-kyf4 d:2005-01-01T00:00:00.000Z t:neighborhood="AIRPORT LA GUARDIA" t:type_of_home="03 THREE FAMILY HOMES" m:average_sale_price=745000 m:lowest_sale_price=745000 m:median_sale_price=745000 m:highest_sale_price=745000 m:number_of_sales=1
```

## Meta Commands

```ls
metric m:number_of_sales p:integer l:"NUMBER OF SALES" t:dataTypeName=number

metric m:lowest_sale_price p:integer l:"LOWEST SALE PRICE" t:dataTypeName=money

metric m:average_sale_price p:integer l:"AVERAGE SALE PRICE" t:dataTypeName=money

metric m:median_sale_price p:integer l:"MEDIAN SALE PRICE" t:dataTypeName=money

metric m:highest_sale_price p:integer l:"HIGHEST SALE PRICE" t:dataTypeName=money

entity e:7fnf-kyf4 l:"DOF: Summary of Neighborhood Sales in Queens for Class 1-, 2- and 3-Family homes - 2005" t:attribution="Department of Finance (DOF)" t:url=https://data.cityofnewyork.us/api/views/7fnf-kyf4

property e:7fnf-kyf4 t:meta.view v:id=7fnf-kyf4 v:category="Housing & Development" v:averageRating=0 v:name="DOF: Summary of Neighborhood Sales in Queens for Class 1-, 2- and 3-Family homes - 2005" v:attribution="Department of Finance (DOF)"

property e:7fnf-kyf4 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:7fnf-kyf4 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| neighborhood       | type_of_home          | number_of_sales | lowest_sale_price | average_sale_price | median_sale_price | highest_sale_price | 
| ================== | ===================== | =============== | ================= | ================== | ================= | ================== | 
| AIRPORT LA GUARDIA | 01 ONE FAMILY HOMES   | 6               | 178750            | 445958             | 490000            | 530000             | 
| AIRPORT LA GUARDIA | 02 TWO FAMILY HOMES   | 2               | 475000            | 507500             | 507500            | 540000             | 
| AIRPORT LA GUARDIA | 03 THREE FAMILY HOMES | 1               | 745000            | 745000             | 745000            | 745000             | 
| ARVERNE            | 01 ONE FAMILY HOMES   | 87              | 160000            | 305615             | 295000            | 700000             | 
| ARVERNE            | 02 TWO FAMILY HOMES   | 180             | 150000            | 414127             | 417500            | 540000             | 
| ARVERNE            | 03 THREE FAMILY HOMES | 20              | 220000            | 475373             | 471000            | 890000             | 
| ASTORIA            | 01 ONE FAMILY HOMES   | 85              | 200000            | 578771             | 564000            | 2175000            | 
| ASTORIA            | 02 TWO FAMILY HOMES   | 210             | 175000            | 685243             | 670000            | 2000000            | 
| ASTORIA            | 03 THREE FAMILY HOMES | 83              | 150000            | 715707             | 740000            | 1075000            | 
| BAYSIDE            | 01 ONE FAMILY HOMES   | 424             | 180000            | 651426             | 634500            | 2000000            | 
```