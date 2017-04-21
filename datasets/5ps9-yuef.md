# DOF: Summary of Neighborhood Sales Citywide for Class 1-, 2- and 3-Family homes - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dof-summary-of-neighborhood-sales-citywide-for-class-1-2-and-3-family-homes-2009-2f670) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/5ps9-yuef) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/5ps9-yuef/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/5ps9-yuef/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 5ps9-yuef |
| Name | DOF: Summary of Neighborhood Sales Citywide for Class 1-, 2- and 3-Family homes - 2009 |
| Attribution | Department of Finance (DOF) |
| Category | Housing & Development |
| Tags | department of finance, finance, dof, property, properties, neighborhoods, sales, neighborhood sales, homes, family homes, class-1, class-2, class-3, borough, citywide |
| Created | 2011-10-05T18:19:00Z |
| Publication Date | 2013-06-21T20:53:44Z |

## Description

The Department of Finance (DOF) maintains records for all property sales in New York City, including sales of family homes in each borough. This list is a summary of all neighborhood sales for Class 1-, 2- and 3-Family homes Citywide in 2009.

This list includes all sales of 1-, 2-, and 3-Family Homes' from January 1st, 2009 to December 31, 2009, whose sale price is equal to or more than $150,000.  The Building Class Category for Sales is based on the Building Class at the time of the sale.
Update Schedule: Annually

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
Value = 2009
Format & Zone = yyyy
```

## Data Commands

```ls
series e:5ps9-yuef d:2009-01-01T00:00:00.000Z t:building_class_category="01 ONE FAMILY HOMES" t:borough=1 m:minimum_sale_price_=408771 m:median_sale_price_=5075000 m:average_sale_price_=6812888 m:maximum_sale_price_=25000000 m:number_of_sales_=55

series e:5ps9-yuef d:2009-01-01T00:00:00.000Z t:building_class_category="02 TWO FAMILY HOMES" t:borough=1 m:minimum_sale_price_=320000 m:median_sale_price_=3085000 m:average_sale_price_=3736718 m:maximum_sale_price_=15400000 m:number_of_sales_=47

series e:5ps9-yuef d:2009-01-01T00:00:00.000Z t:building_class_category="03 THREE FAMILY HOMES" t:borough=1 m:minimum_sale_price_=449249 m:median_sale_price_=1100000 m:average_sale_price_=2857128 m:maximum_sale_price_=19500000 m:number_of_sales_=33
```

## Meta Commands

```ls
metric m:number_of_sales_ p:integer l:"NUMBER OF SALES" t:dataTypeName=number

metric m:minimum_sale_price_ p:integer l:"MINIMUM SALE PRICE" t:dataTypeName=number

metric m:average_sale_price_ p:integer l:"AVERAGE SALE PRICE" t:dataTypeName=number

metric m:median_sale_price_ p:integer l:"MEDIAN SALE PRICE" t:dataTypeName=number

metric m:maximum_sale_price_ p:integer l:"MAXIMUM SALE PRICE" t:dataTypeName=number

entity e:5ps9-yuef l:"DOF: Summary of Neighborhood Sales Citywide for Class 1-, 2- and 3-Family homes - 2009" t:attribution="Department of Finance (DOF)" t:url=https://data.cityofnewyork.us/api/views/5ps9-yuef

property e:5ps9-yuef t:meta.view v:id=5ps9-yuef v:category="Housing & Development" v:averageRating=0 v:name="DOF: Summary of Neighborhood Sales Citywide for Class 1-, 2- and 3-Family homes - 2009" v:attribution="Department of Finance (DOF)"

property e:5ps9-yuef t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:5ps9-yuef t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| borough | building_class_category | number_of_sales_ | minimum_sale_price_ | average_sale_price_ | median_sale_price_ | maximum_sale_price_ | 
| ======= | ======================= | ================ | =================== | =================== | ================== | =================== | 
| 1       | 01 ONE FAMILY HOMES     | 55               | 408771              | 6812888             | 5075000            | 25000000            | 
| 1       | 02 TWO FAMILY HOMES     | 47               | 320000              | 3736718             | 3085000            | 15400000            | 
| 1       | 03 THREE FAMILY HOMES   | 33               | 449249              | 2857128             | 1100000            | 19500000            | 
| 2       | 01 ONE FAMILY HOMES     | 516              | 150000              | 405594              | 349995             | 5000000             | 
| 2       | 02 TWO FAMILY HOMES     | 771              | 150000              | 421473              | 428786             | 1000000             | 
| 2       | 03 THREE FAMILY HOMES   | 276              | 150000              | 477090              | 496240             | 943750              | 
| 3       | 01 ONE FAMILY HOMES     | 1394             | 150000              | 580687              | 475000             | 10260000            | 
| 3       | 02 TWO FAMILY HOMES     | 2375             | 150000              | 591108              | 538888             | 10979100            | 
| 3       | 03 THREE FAMILY HOMES   | 841              | 150000              | 618201              | 586354             | 3310000             | 
| 4       | 01 ONE FAMILY HOMES     | 4714             | 150000              | 461437              | 425000             | 3775000             | 
```