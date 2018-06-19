# DOF: Summary of Neighborhood Sales in Queens for Class 1-, 2- and 3-Family homes - 2007

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dof-summary-of-neighborhood-sales-in-queens-for-class-1-2-and-3-family-homes-2007-77b40) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/hcv4-fhfs) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/hcv4-fhfs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/hcv4-fhfs/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | hcv4-fhfs |
| Name | DOF: Summary of Neighborhood Sales in Queens for Class 1-, 2- and 3-Family homes - 2007 |
| Attribution | Department of Finance (DOF) |
| Category | Housing & Development |
| Tags | department of finance, finance, dof, property, properties, neighborhoods, sales, neighborhood sales, homes, family homes, class-1, class-2, class-3, borough, queens |
| Created | 2011-10-05T20:50:18Z |
| Publication Date | 2013-06-21T20:55:46Z |

## Description

The Department of Finance (DOF) maintains records for all property sales in New York City, including sales of family homes in each borough. This list is a summary of neighborhood sales for Class 1-, 2- and 3-Family homes in Queens in 2007.

This list includes all sales of 1-, 2-, and 3-Family Homes' from January 1st, 2007 to December 31, 2007, whose sale price is equal to or more than $150,000.  The Building Class Category for Sales is based on the Building Class at the time of the sale.

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
Value = 2007
Format & Zone = yyyy
```

## Data Commands

```ls
series e:hcv4-fhfs d:2007-01-01T00:00:00.000Z t:neighborhood="AIRPORT LA GUARDIA" t:type_of_home="01 ONE FAMILY HOMES" m:average_sale_price=580000 m:lowest_sale_price=580000 m:median_sale_price=580000 m:highest_sale_price=580000 m:number_of_sales=1

series e:hcv4-fhfs d:2007-01-01T00:00:00.000Z t:neighborhood=ARVERNE t:type_of_home="01 ONE FAMILY HOMES" m:average_sale_price=333479 m:lowest_sale_price=165000 m:median_sale_price=335629 m:highest_sale_price=485000 m:number_of_sales=101

series e:hcv4-fhfs d:2007-01-01T00:00:00.000Z t:neighborhood=ARVERNE t:type_of_home="02 TWO FAMILY HOMES" m:average_sale_price=498358 m:lowest_sale_price=270000 m:median_sale_price=495666 m:highest_sale_price=749330 m:number_of_sales=130
```

## Meta Commands

```ls
metric m:number_of_sales p:integer l:"NUMBER OF SALES" t:dataTypeName=number

metric m:lowest_sale_price p:integer l:"LOWEST SALE PRICE" t:dataTypeName=money

metric m:average_sale_price p:integer l:"AVERAGE SALE PRICE" t:dataTypeName=money

metric m:median_sale_price p:integer l:"MEDIAN SALE PRICE" t:dataTypeName=money

metric m:highest_sale_price p:integer l:"HIGHEST SALE PRICE" t:dataTypeName=money

entity e:hcv4-fhfs l:"DOF: Summary of Neighborhood Sales in Queens for Class 1-, 2- and 3-Family homes - 2007" t:attribution="Department of Finance (DOF)" t:url=https://data.cityofnewyork.us/api/views/hcv4-fhfs

property e:hcv4-fhfs t:meta.view v:id=hcv4-fhfs v:category="Housing & Development" v:averageRating=0 v:name="DOF: Summary of Neighborhood Sales in Queens for Class 1-, 2- and 3-Family homes - 2007" v:attribution="Department of Finance (DOF)"

property e:hcv4-fhfs t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:hcv4-fhfs t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| neighborhood       | type_of_home          | number_of_sales | lowest_sale_price | average_sale_price | median_sale_price | highest_sale_price | 
| ================== | ===================== | =============== | ================= | ================== | ================= | ================== | 
| AIRPORT LA GUARDIA | 01 ONE FAMILY HOMES   | 1               | 580000            | 580000             | 580000            | 580000             | 
| ARVERNE            | 01 ONE FAMILY HOMES   | 101             | 165000            | 333479             | 335629            | 485000             | 
| ARVERNE            | 02 TWO FAMILY HOMES   | 130             | 270000            | 498358             | 495666            | 749330             | 
| ARVERNE            | 03 THREE FAMILY HOMES | 8               | 405000            | 528130             | 512387            | 680000             | 
| ASTORIA            | 01 ONE FAMILY HOMES   | 70              | 158000            | 623038             | 601500            | 1900000            | 
| ASTORIA            | 02 TWO FAMILY HOMES   | 148             | 250000            | 748302             | 755000            | 2025000            | 
| ASTORIA            | 03 THREE FAMILY HOMES | 57              | 150000            | 902231             | 898000            | 2885000            | 
| BAYSIDE            | 01 ONE FAMILY HOMES   | 342             | 150000            | 683919             | 644000            | 2000000            | 
| BAYSIDE            | 02 TWO FAMILY HOMES   | 133             | 170000            | 814165             | 835000            | 1500000            | 
| BAYSIDE            | 03 THREE FAMILY HOMES | 18              | 530000            | 841735             | 903000            | 997885             | 
```