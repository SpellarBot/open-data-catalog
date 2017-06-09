# DOF: Summary of Neighborhood Sales for the Bronx for Class 1-, 2- and 3-Family homes - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dof-summary-of-neighborhood-sales-for-the-bronx-for-class-1-2-and-3-family-homes-2009-11c00) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/w4v6-3sdt) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/w4v6-3sdt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/w4v6-3sdt/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | w4v6-3sdt |
| Name | DOF: Summary of Neighborhood Sales for the Bronx for Class 1-, 2- and 3-Family homes - 2009 |
| Attribution | Department of Finance (DOF) |
| Category | Housing & Development |
| Tags | department of finance, finance, dof, property, properties, neighborhoods, sales, neighborhood sales, homes, family homes, class-1, class-2, class-3, borough, bronx |
| Created | 2011-10-05T17:23:15Z |
| Publication Date | 2013-06-21T20:54:26Z |

## Description

The Department of Finance (DOF) maintains records for all property sales in New York City, including sales of family homes in each borough. This list is a summary of neighborhood sales for Class 1-, 2- and 3-Family homes in the Bronx in 2009.
Update Schedule: Annually

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                    | Data Type | Render Type |
| ======== | ============== | ====================== | ======================= | ========= | =========== |
| Yes      | series tag     | neighborhood           | NEIGHBORHOOD            | text      | text        |
| Yes      | series tag     | type_of_home           | TYPE OF HOME            | text      | text        |
| Yes      | numeric metric | total_no_of_properties | TOTAL NO. OF PROPERTIES | number    | number      |
| Yes      | numeric metric | number_of_sales        | NUMBER OF SALES         | number    | number      |
| Yes      | numeric metric | lowest_sale_price      | LOWEST SALE PRICE       | money     | money       |
| Yes      | numeric metric | average_sale_price     | AVERAGE SALE PRICE      | money     | money       |
| Yes      | numeric metric | median_sale_price      | MEDIAN SALE PRICE       | money     | money       |
| Yes      | numeric metric | highest_sale_price     | HIGHEST SALE PRICE      | money     | money       |
```

## Time Field

```ls
Value = 2009
Format & Zone = yyyy
```

## Data Commands

```ls
series e:w4v6-3sdt d:2009-01-01T00:00:00.000Z t:neighborhood=BATHGATE t:type_of_home="01 ONE FAMILY HOMES" m:average_sale_price=345752 m:lowest_sale_price=345752 m:median_sale_price=345752 m:highest_sale_price=345752 m:number_of_sales=1 m:total_no_of_properties=87

series e:w4v6-3sdt d:2009-01-01T00:00:00.000Z t:neighborhood=BATHGATE t:type_of_home="02 TWO FAMILY HOMES" m:average_sale_price=327310 m:lowest_sale_price=183028 m:median_sale_price=334750 m:highest_sale_price=415440 m:number_of_sales=8 m:total_no_of_properties=308

series e:w4v6-3sdt d:2009-01-01T00:00:00.000Z t:neighborhood=BATHGATE t:type_of_home="03 THREE FAMILY HOMES" m:average_sale_price=536674 m:lowest_sale_price=162240 m:median_sale_price=602500 m:highest_sale_price=640000 m:number_of_sales=10 m:total_no_of_properties=131
```

## Meta Commands

```ls
metric m:total_no_of_properties p:integer l:"TOTAL NO. OF PROPERTIES" t:dataTypeName=number

metric m:number_of_sales p:integer l:"NUMBER OF SALES" t:dataTypeName=number

metric m:lowest_sale_price p:integer l:"LOWEST SALE PRICE" t:dataTypeName=money

metric m:average_sale_price p:integer l:"AVERAGE SALE PRICE" t:dataTypeName=money

metric m:median_sale_price p:integer l:"MEDIAN SALE PRICE" t:dataTypeName=money

metric m:highest_sale_price p:integer l:"HIGHEST SALE PRICE" t:dataTypeName=money

entity e:w4v6-3sdt l:"DOF: Summary of Neighborhood Sales for the Bronx for Class 1-, 2- and 3-Family homes - 2009" t:attribution="Department of Finance (DOF)" t:url=https://data.cityofnewyork.us/api/views/w4v6-3sdt

property e:w4v6-3sdt t:meta.view d:2017-06-09T13:56:45.445Z v:id=w4v6-3sdt v:category="Housing & Development" v:averageRating=0 v:name="DOF: Summary of Neighborhood Sales for the Bronx for Class 1-, 2- and 3-Family homes - 2009" v:attribution="Department of Finance (DOF)"

property e:w4v6-3sdt t:meta.view.owner d:2017-06-09T13:56:45.445Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1496414226 v:displayName="NYC OpenData"

property e:w4v6-3sdt t:meta.view.tableauthor d:2017-06-09T13:56:45.445Z v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| neighborhood         | type_of_home          | total_no_of_properties | number_of_sales | lowest_sale_price | average_sale_price | median_sale_price | highest_sale_price | 
| ==================== | ===================== | ====================== | =============== | ================= | ================== | ================= | ================== | 
| BATHGATE             | 01 ONE FAMILY HOMES   | 87                     | 1               | 345752            | 345752             | 345752            | 345752             | 
| BATHGATE             | 02 TWO FAMILY HOMES   | 308                    | 8               | 183028            | 327310             | 334750            | 415440             | 
| BATHGATE             | 03 THREE FAMILY HOMES | 131                    | 10              | 162240            | 536674             | 602500            | 640000             | 
| BAYCHESTER           | 01 ONE FAMILY HOMES   | 2493                   | 48              | 165000            | 340465             | 342500            | 500000             | 
| BAYCHESTER           | 02 TWO FAMILY HOMES   | 2965                   | 74              | 200000            | 458667             | 495000            | 636000             | 
| BAYCHESTER           | 03 THREE FAMILY HOMES | 896                    | 9               | 330000            | 478589             | 508800            | 575000             | 
| BEDFORD PARK/NORWOOD | 01 ONE FAMILY HOMES   | 296                    | 12              | 150500            | 319987             | 309000            | 530000             | 
| BEDFORD PARK/NORWOOD | 02 TWO FAMILY HOMES   | 616                    | 14              | 228714            | 420917             | 435000            | 620000             | 
| BEDFORD PARK/NORWOOD | 03 THREE FAMILY HOMES | 259                    | 11              | 224000            | 511940             | 527845            | 685000             | 
| BELMONT              | 02 TWO FAMILY HOMES   | 313                    | 11              | 200000            | 402303             | 407000            | 731000             | 
```