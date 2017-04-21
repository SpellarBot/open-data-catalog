# DOF: Summary of Neighborhood Sales Citywide for Class 1-, 2- and 3-Family homes - 2007

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dof-summary-of-neighborhood-sales-citywide-for-class-1-2-and-3-family-homes-2007-64284) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/hdu7-ujt4) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/hdu7-ujt4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/hdu7-ujt4/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | hdu7-ujt4 |
| Name | DOF: Summary of Neighborhood Sales Citywide for Class 1-, 2- and 3-Family homes - 2007 |
| Attribution | Department of Finance (DOF) |
| Category | Housing & Development |
| Tags | department of finance, finance, dof, property, properties, neighborhoods, sales, neighborhood sales, homes, family homes, class-1, class-2, class-3, borough, citywide |
| Created | 2011-10-05T18:43:01Z |
| Publication Date | 2013-06-26T17:06:45Z |

## Description

The Department of Finance (DOF) maintains records for all property sales in New York City, including sales of family homes in each borough. This list is a summary of all neighborhood sales for Class 1-, 2- and 3-Family homes Citywide in 2007.

This list includes all sales of 1-, 2-, and 3-Family Homes' from January 1st, 2007 to December 31, 2007, whose sale price is equal to or more than $150,000.  The Building Class Category for Sales is based on the Building Class at the time of the sale.
Update Frequency: Annually

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | series tag     | borough                 | BOROUGH                 | text      | text        |
| Yes      | series tag     | building_class_category | BUILDING CLASS CATEGORY | text      | text        |
| Yes      | numeric metric | number_of_sales_        | NUMBER OF SALES         | number    | number      |
| Yes      | numeric metric | minimum_sale_price_     | MINIMUM SALE PRICE      | number    | number      |
| Yes      | numeric metric | average_sale_price_     | AVERAGE SALE PRICE      | number    | number      |
| Yes      | numeric metric | median_sale_price_      | MEDIAN SALE PRICE       | number    | number      |
| Yes      | numeric metric | maximum_sale_price_     | MAXIMUM SALE PRICE      | number    | number      |
```

## Time Field

```ls
Value = 2007
Format & Zone = yyyy
```

## Data Commands

```ls
series e:hdu7-ujt4 d:2007-01-01T00:00:00.000Z t:building_class_category="01 ONE FAMILY HOMES" t:borough=1 m:minimum_sale_price_=300000 m:median_sale_price_=4925000 m:average_sale_price_=7383111 m:maximum_sale_price_=50000000 m:number_of_sales_=102

series e:hdu7-ujt4 d:2007-01-01T00:00:00.000Z t:building_class_category="02 TWO FAMILY HOMES" t:borough=1 m:minimum_sale_price_=200000 m:median_sale_price_=3185000 m:average_sale_price_=4126525 m:maximum_sale_price_=19075000 m:number_of_sales_=104

series e:hdu7-ujt4 d:2007-01-01T00:00:00.000Z t:building_class_category="03 THREE FAMILY HOMES" t:borough=1 m:minimum_sale_price_=250000 m:median_sale_price_=1520208 m:average_sale_price_=2748050 m:maximum_sale_price_=14400000 m:number_of_sales_=50
```

## Meta Commands

```ls
metric m:number_of_sales_ p:integer l:"NUMBER OF SALES" t:dataTypeName=number

metric m:minimum_sale_price_ p:integer l:"MINIMUM SALE PRICE" t:dataTypeName=number

metric m:average_sale_price_ p:integer l:"AVERAGE SALE PRICE" t:dataTypeName=number

metric m:median_sale_price_ p:integer l:"MEDIAN SALE PRICE" t:dataTypeName=number

metric m:maximum_sale_price_ p:integer l:"MAXIMUM SALE PRICE" t:dataTypeName=number

entity e:hdu7-ujt4 l:"DOF: Summary of Neighborhood Sales Citywide for Class 1-, 2- and 3-Family homes - 2007" t:attribution="Department of Finance (DOF)" t:url=https://data.cityofnewyork.us/api/views/hdu7-ujt4

property e:hdu7-ujt4 t:meta.view v:id=hdu7-ujt4 v:category="Housing & Development" v:averageRating=0 v:name="DOF: Summary of Neighborhood Sales Citywide for Class 1-, 2- and 3-Family homes - 2007" v:attribution="Department of Finance (DOF)"

property e:hdu7-ujt4 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:hdu7-ujt4 t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| borough | building_class_category | number_of_sales_ | minimum_sale_price_ | average_sale_price_ | median_sale_price_ | maximum_sale_price_ | 
| ======= | ======================= | ================ | =================== | =================== | ================== | =================== | 
| 1       | 01 ONE FAMILY HOMES     | 102              | 300000              | 7383111             | 4925000            | 50000000            | 
| 1       | 02 TWO FAMILY HOMES     | 104              | 200000              | 4126525             | 3185000            | 19075000            | 
| 1       | 03 THREE FAMILY HOMES   | 50               | 250000              | 2748050             | 1520208            | 14400000            | 
| 2       | 01 ONE FAMILY HOMES     | 942              | 150000              | 451970              | 420000             | 4500000             | 
| 2       | 02 TWO FAMILY HOMES     | 1378             | 150000              | 517028              | 520060             | 1400000             | 
| 2       | 03 THREE FAMILY HOMES   | 627              | 150000              | 603445              | 600000             | 10691871            | 
| 3       | 01 ONE FAMILY HOMES     | 2280             | 150000              | 645548              | 520000             | 10000000            | 
| 3       | 02 TWO FAMILY HOMES     | 4063             | 150000              | 688668              | 624500             | 8000000             | 
| 3       | 03 THREE FAMILY HOMES   | 1518             | 150000              | 744142              | 712888             | 3500000             | 
| 4       | 01 ONE FAMILY HOMES     | 6794             | 150000              | 547530              | 500000             | 5300000             | 
```