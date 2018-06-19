# DOF: Summary of Neighborhood Sales in Brooklyn for Class 1-, 2- and 3-Family homes - 2008

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dof-summary-of-neighborhood-sales-in-brooklyn-for-class-1-2-and-3-family-homes-2008-3b04a) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/thrx-b6bc) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/thrx-b6bc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/thrx-b6bc/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | thrx-b6bc |
| Name | DOF: Summary of Neighborhood Sales in Brooklyn for Class 1-, 2- and 3-Family homes - 2008 |
| Attribution | Department of Finance (DOF) |
| Category | Housing & Development |
| Tags | family homes, class-1, class-2, class-3, borough, brooklyn |
| Created | 2011-10-05T20:35:53Z |
| Publication Date | 2013-06-26T17:04:05Z |

## Description

The Department of Finance (DOF) maintains records for all property sales in New York City, including sales of family homes in each borough. This list is a summary of neighborhood sales for Class 1-, 2- and 3-Family homes in Brooklyn in 2008.

This list includes all sales of 1-, 2-, and 3-Family Homes' from January 1st, 2008 to December 31, 2008, whose sale price is equal to or more than $150,000.  The Building Class Category for Sales is based on the Building Class at the time of the sale.
Update Frequency: Annually

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
series e:thrx-b6bc d:2008-01-01T00:00:00.000Z t:neighborhood="BATH BEACH" t:type_of_home="01 ONE FAMILY HOMES" m:average_sale_price=580235 m:lowest_sale_price=400000 m:median_sale_price=530000 m:highest_sale_price=1135000 m:number_of_sales=17

series e:thrx-b6bc d:2008-01-01T00:00:00.000Z t:neighborhood="BATH BEACH" t:type_of_home="02 TWO FAMILY HOMES" m:average_sale_price=616902 m:lowest_sale_price=200000 m:median_sale_price=630000 m:highest_sale_price=1080000 m:number_of_sales=61

series e:thrx-b6bc d:2008-01-01T00:00:00.000Z t:neighborhood="BATH BEACH" t:type_of_home="03 THREE FAMILY HOMES" m:average_sale_price=829985 m:lowest_sale_price=288000 m:median_sale_price=770000 m:highest_sale_price=1440000 m:number_of_sales=31
```

## Meta Commands

```ls
metric m:number_of_sales p:integer l:"NUMBER OF SALES" t:dataTypeName=number

metric m:lowest_sale_price p:integer l:"LOWEST SALE PRICE" t:dataTypeName=money

metric m:average_sale_price p:integer l:"AVERAGE SALE PRICE" t:dataTypeName=money

metric m:median_sale_price p:integer l:"MEDIAN SALE PRICE" t:dataTypeName=money

metric m:highest_sale_price p:integer l:"HIGHEST SALE PRICE" t:dataTypeName=money

entity e:thrx-b6bc l:"DOF: Summary of Neighborhood Sales in Brooklyn for Class 1-, 2- and 3-Family homes - 2008" t:attribution="Department of Finance (DOF)" t:url=https://data.cityofnewyork.us/api/views/thrx-b6bc

property e:thrx-b6bc t:meta.view v:id=thrx-b6bc v:category="Housing & Development" v:averageRating=0 v:name="DOF: Summary of Neighborhood Sales in Brooklyn for Class 1-, 2- and 3-Family homes - 2008" v:attribution="Department of Finance (DOF)"

property e:thrx-b6bc t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:thrx-b6bc t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| neighborhood       | type_of_home          | number_of_sales | lowest_sale_price | average_sale_price | median_sale_price | highest_sale_price | 
| ================== | ===================== | =============== | ================= | ================== | ================= | ================== | 
| BATH BEACH         | 01 ONE FAMILY HOMES   | 17              | 400000            | 580235             | 530000            | 1135000            | 
| BATH BEACH         | 02 TWO FAMILY HOMES   | 61              | 200000            | 616902             | 630000            | 1080000            | 
| BATH BEACH         | 03 THREE FAMILY HOMES | 31              | 288000            | 829985             | 770000            | 1440000            | 
| BAY RIDGE          | 01 ONE FAMILY HOMES   | 100             | 200000            | 766359             | 707500            | 2350000            | 
| BAY RIDGE          | 02 TWO FAMILY HOMES   | 110             | 170000            | 762034             | 762500            | 2065000            | 
| BAY RIDGE          | 03 THREE FAMILY HOMES | 14              | 208830            | 733345             | 791000            | 999000             | 
| BEDFORD STUYVESANT | 01 ONE FAMILY HOMES   | 33              | 152100            | 439342             | 402500            | 725000             | 
| BEDFORD STUYVESANT | 02 TWO FAMILY HOMES   | 268             | 169000            | 516732             | 509750            | 968200             | 
| BEDFORD STUYVESANT | 03 THREE FAMILY HOMES | 147             | 220000            | 619159             | 634438            | 1207000            | 
| BENSONHURST        | 01 ONE FAMILY HOMES   | 34              | 350000            | 604909             | 575000            | 1210000            | 
```