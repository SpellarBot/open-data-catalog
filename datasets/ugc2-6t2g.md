# DOF: Summary of Neighborhood Sales Citywide for Class 1-, 2- and 3-Family homes - 2008

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dof-summary-of-neighborhood-sales-citywide-for-class-1-2-and-3-family-homes-2008-eb957) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ugc2-6t2g) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ugc2-6t2g/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ugc2-6t2g/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ugc2-6t2g |
| Name | DOF: Summary of Neighborhood Sales Citywide for Class 1-, 2- and 3-Family homes - 2008 |
| Attribution | Department of Finance (DOF) |
| Category | Housing & Development |
| Tags | department of finance, finance, dof, property, properties, neighborhoods, sales, neighborhood sales, homes, family homes, class-1, class-2, class-3, borough, citywide |
| Created | 2011-10-05T18:37:16Z |
| Publication Date | 2013-06-26T17:07:43Z |

## Description

The Department of Finance (DOF) maintains records for all property sales in New York City, including sales of family homes in each borough. This list is a summary of all neighborhood sales for Class 1-, 2- and 3-Family homes Citywide in 2008.

This list includes all sales of 1-, 2-, and 3-Family Homes' from January 1st, 2008 to December 31, 2008, whose sale price is equal to or more than $150,000.  The Building Class Category for Sales is based on the Building Class at the time of the sale.

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
Value = 2008
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ugc2-6t2g d:2008-01-01T00:00:00.000Z t:building_class_category="01 ONE FAMILY HOMES" t:borough=1 m:minimum_sale_price_=331500 m:median_sale_price_=5414549 m:average_sale_price_=8926012 m:maximum_sale_price_=49000000 m:number_of_sales_=68

series e:ugc2-6t2g d:2008-01-01T00:00:00.000Z t:building_class_category="02 TWO FAMILY HOMES" t:borough=1 m:minimum_sale_price_=200000 m:median_sale_price_=4150000 m:average_sale_price_=4671561 m:maximum_sale_price_=17000000 m:number_of_sales_=61

series e:ugc2-6t2g d:2008-01-01T00:00:00.000Z t:building_class_category="03 THREE FAMILY HOMES" t:borough=1 m:minimum_sale_price_=175000 m:median_sale_price_=3425000 m:average_sale_price_=3868956 m:maximum_sale_price_=13500000 m:number_of_sales_=42
```

## Meta Commands

```ls
metric m:number_of_sales_ p:integer l:"NUMBER OF SALES" t:dataTypeName=number

metric m:minimum_sale_price_ p:integer l:"MINIMUM SALE PRICE" t:dataTypeName=number

metric m:average_sale_price_ p:integer l:"AVERAGE SALE PRICE" t:dataTypeName=number

metric m:median_sale_price_ p:integer l:"MEDIAN SALE PRICE" t:dataTypeName=number

metric m:maximum_sale_price_ p:integer l:"MAXIMUM SALE PRICE" t:dataTypeName=number

entity e:ugc2-6t2g l:"DOF: Summary of Neighborhood Sales Citywide for Class 1-, 2- and 3-Family homes - 2008" t:attribution="Department of Finance (DOF)" t:url=https://data.cityofnewyork.us/api/views/ugc2-6t2g

property e:ugc2-6t2g t:meta.view v:id=ugc2-6t2g v:category="Housing & Development" v:averageRating=0 v:name="DOF: Summary of Neighborhood Sales Citywide for Class 1-, 2- and 3-Family homes - 2008" v:attribution="Department of Finance (DOF)"

property e:ugc2-6t2g t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ugc2-6t2g t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| borough | building_class_category | number_of_sales_ | minimum_sale_price_ | average_sale_price_ | median_sale_price_ | maximum_sale_price_ | 
| ======= | ======================= | ================ | =================== | =================== | ================== | =================== | 
| 1       | 01 ONE FAMILY HOMES     | 68               | 331500              | 8926012             | 5414549            | 49000000            | 
| 1       | 02 TWO FAMILY HOMES     | 61               | 200000              | 4671561             | 4150000            | 17000000            | 
| 1       | 03 THREE FAMILY HOMES   | 42               | 175000              | 3868956             | 3425000            | 13500000            | 
| 2       | 01 ONE FAMILY HOMES     | 606              | 150000              | 441962              | 391200             | 3956150             | 
| 2       | 02 TWO FAMILY HOMES     | 906              | 150000              | 482934              | 480000             | 975000              | 
| 2       | 03 THREE FAMILY HOMES   | 469              | 153000              | 558828              | 575000             | 1550000             | 
| 3       | 01 ONE FAMILY HOMES     | 1577             | 151117              | 642727              | 515000             | 8450000             | 
| 3       | 02 TWO FAMILY HOMES     | 2906             | 150000              | 656988              | 600000             | 10800000            | 
| 3       | 03 THREE FAMILY HOMES   | 1081             | 150000              | 733439              | 695000             | 3100000             | 
| 4       | 01 ONE FAMILY HOMES     | 5078             | 150000              | 513661              | 465000             | 5617500             | 
```