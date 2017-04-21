# DOF: Summary of Neighborhood Sales in Queens for Class 1-, 2- and 3-Family homes - 2008

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dof-summary-of-neighborhood-sales-in-queens-for-class-1-2-and-3-family-homes-2008-9d611) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/aa5u-mys6) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/aa5u-mys6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/aa5u-mys6/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | aa5u-mys6 |
| Name | DOF: Summary of Neighborhood Sales in Queens for Class 1-, 2- and 3-Family homes - 2008 |
| Attribution | Department of Finance (DOF) |
| Category | Housing & Development |
| Tags | department of finance, finance, dof, property, properties, neighborhoods, sales, neighborhood sales, homes, family homes, class-1, class-2, class-3, borough, queens |
| Created | 2011-10-05T20:44:57Z |
| Publication Date | 2013-06-21T20:54:31Z |

## Description

The Department of Finance (DOF) maintains records for all property sales in New York City, including sales of family homes in each borough. This list is a summary of neighborhood sales for Class 1-, 2- and 3-Family homes in Queens in 2008.

This list includes all sales of 1-, 2-, and 3-Family Homes' from January 1st, 2008 to December 31, 2008, whose sale price is equal to or more than $150,000.  The Building Class Category for Sales is based on the Building Class at the time of the sale.

Update Schedule: Annually

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
series e:aa5u-mys6 d:2008-01-01T00:00:00.000Z t:neighborhood="AIRPORT LA GUARDIA" t:type_of_home="01 ONE FAMILY HOMES" m:average_sale_price=425000 m:lowest_sale_price=425000 m:median_sale_price=425000 m:highest_sale_price=425000 m:number_of_sales=1

series e:aa5u-mys6 d:2008-01-01T00:00:00.000Z t:neighborhood="AIRPORT LA GUARDIA" t:type_of_home="02 TWO FAMILY HOMES" m:average_sale_price=575000 m:lowest_sale_price=575000 m:median_sale_price=575000 m:highest_sale_price=575000 m:number_of_sales=1

series e:aa5u-mys6 d:2008-01-01T00:00:00.000Z t:neighborhood=ARVERNE t:type_of_home="01 ONE FAMILY HOMES" m:average_sale_price=295315 m:lowest_sale_price=150000 m:median_sale_price=273667 m:highest_sale_price=705000 m:number_of_sales=35
```

## Meta Commands

```ls
metric m:number_of_sales p:integer l:"NUMBER OF SALES" t:dataTypeName=number

metric m:lowest_sale_price p:integer l:"LOWEST SALE PRICE" t:dataTypeName=money

metric m:average_sale_price p:integer l:"AVERAGE SALE PRICE" t:dataTypeName=money

metric m:median_sale_price p:integer l:"MEDIAN SALE PRICE" t:dataTypeName=money

metric m:highest_sale_price p:integer l:"HIGHEST SALE PRICE" t:dataTypeName=money

entity e:aa5u-mys6 l:"DOF: Summary of Neighborhood Sales in Queens for Class 1-, 2- and 3-Family homes - 2008" t:attribution="Department of Finance (DOF)" t:url=https://data.cityofnewyork.us/api/views/aa5u-mys6

property e:aa5u-mys6 t:meta.view v:id=aa5u-mys6 v:category="Housing & Development" v:averageRating=0 v:name="DOF: Summary of Neighborhood Sales in Queens for Class 1-, 2- and 3-Family homes - 2008" v:attribution="Department of Finance (DOF)"

property e:aa5u-mys6 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:aa5u-mys6 t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| neighborhood       | type_of_home          | number_of_sales | lowest_sale_price | average_sale_price | median_sale_price | highest_sale_price | 
| ================== | ===================== | =============== | ================= | ================== | ================= | ================== | 
| AIRPORT LA GUARDIA | 01 ONE FAMILY HOMES   | 1               | 425000            | 425000             | 425000            | 425000             | 
| AIRPORT LA GUARDIA | 02 TWO FAMILY HOMES   | 1               | 575000            | 575000             | 575000            | 575000             | 
| ARVERNE            | 01 ONE FAMILY HOMES   | 35              | 150000            | 295315             | 273667            | 705000             | 
| ARVERNE            | 02 TWO FAMILY HOMES   | 156             | 210000            | 513853             | 542337            | 967337             | 
| ARVERNE            | 03 THREE FAMILY HOMES | 8               | 286500            | 422919             | 444500            | 525000             | 
| ASTORIA            | 01 ONE FAMILY HOMES   | 48              | 262896            | 641873             | 582500            | 999900             | 
| ASTORIA            | 02 TWO FAMILY HOMES   | 139             | 232500            | 761839             | 735000            | 3100000            | 
| ASTORIA            | 03 THREE FAMILY HOMES | 57              | 162000            | 751511             | 770000            | 2133334            | 
| BAYSIDE            | 01 ONE FAMILY HOMES   | 259             | 165898            | 637605             | 625000            | 1451000            | 
| BAYSIDE            | 02 TWO FAMILY HOMES   | 94              | 151112            | 779426             | 800000            | 1425550            | 
```