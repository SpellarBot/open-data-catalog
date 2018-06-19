# DOF: Summary of Neighborhood Sales for Manhattan for Class 1-, 2- and 3-Family homes - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dof-summary-of-neighborhood-sales-for-manhattan-for-class-1-2-and-3-family-homes-2009-24052) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/5yay-3jd5) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/5yay-3jd5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/5yay-3jd5/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 5yay-3jd5 |
| Name | DOF: Summary of Neighborhood Sales for Manhattan for Class 1-, 2- and 3-Family homes - 2009 |
| Attribution | Department of Finance (DOF) |
| Category | Housing & Development |
| Tags | department of finance, finance, dof, property, properties, neighborhoods, sales, neighborhood sales, homes, family homes, class-1, class-2, class-3, borough, manhattan |
| Created | 2011-10-05T17:52:44Z |
| Publication Date | 2013-06-26T16:56:12Z |

## Description

The Department of Finance (DOF) maintains records for all property sales in New York City, including sales of family homes in each borough. This list is a summary of neighborhood sales for Class 1-, 2- and 3-Family homes in Manhattan in 2009.

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
series e:5yay-3jd5 d:2009-01-01T00:00:00.000Z t:neighborhood=CHELSEA t:type_of_home="02 TWO FAMILY HOMES" m:average_sale_price=2872500 m:lowest_sale_price=995000 m:median_sale_price=2872500 m:highest_sale_price=4750000 m:total_no_of_properties=81 m:number_of_sales=2

series e:5yay-3jd5 d:2009-01-01T00:00:00.000Z t:neighborhood=CHELSEA t:type_of_home="03 THREE FAMILY HOMES" m:average_sale_price=3800000 m:lowest_sale_price=3800000 m:median_sale_price=3800000 m:highest_sale_price=3800000 m:total_no_of_properties=64 m:number_of_sales=1

series e:5yay-3jd5 d:2009-01-01T00:00:00.000Z t:neighborhood="EAST VILLAGE" t:type_of_home="01 ONE FAMILY HOMES" m:average_sale_price=7926432 m:lowest_sale_price=7926432 m:median_sale_price=7926432 m:highest_sale_price=7926432 m:total_no_of_properties=22 m:number_of_sales=1
```

## Meta Commands

```ls
metric m:total_no_of_properties p:integer l:"TOTAL NO. OF PROPERTIES" t:dataTypeName=number

metric m:number_of_sales p:integer l:"NUMBER OF SALES" t:dataTypeName=number

metric m:lowest_sale_price p:integer l:"LOWEST SALE PRICE" t:dataTypeName=money

metric m:average_sale_price p:double l:"AVERAGE SALE PRICE" t:dataTypeName=money

metric m:median_sale_price p:double l:"MEDIAN SALE PRICE" t:dataTypeName=money

metric m:highest_sale_price p:double l:"HIGHEST SALE PRICE" t:dataTypeName=money

entity e:5yay-3jd5 l:"DOF: Summary of Neighborhood Sales for Manhattan for Class 1-, 2- and 3-Family homes - 2009" t:attribution="Department of Finance (DOF)" t:url=https://data.cityofnewyork.us/api/views/5yay-3jd5

property e:5yay-3jd5 t:meta.view v:id=5yay-3jd5 v:category="Housing & Development" v:averageRating=0 v:name="DOF: Summary of Neighborhood Sales for Manhattan for Class 1-, 2- and 3-Family homes - 2009" v:attribution="Department of Finance (DOF)"

property e:5yay-3jd5 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:5yay-3jd5 t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| neighborhood              | type_of_home          | total_no_of_properties | number_of_sales | lowest_sale_price | average_sale_price | median_sale_price | highest_sale_price | 
| ========================= | ===================== | ====================== | =============== | ================= | ================== | ================= | ================== | 
| CHELSEA                   | 02 TWO FAMILY HOMES   | 81                     | 2               | 995000            | 2872500            | 2872500           | 4750000            | 
| CHELSEA                   | 03 THREE FAMILY HOMES | 64                     | 1               | 3800000           | 3800000            | 3800000           | 3800000            | 
| EAST VILLAGE              | 01 ONE FAMILY HOMES   | 22                     | 1               | 7926432           | 7926432            | 7926432           | 7926432            | 
| EAST VILLAGE              | 02 TWO FAMILY HOMES   | 39                     | 2               | 3085000           | 3892500            | 3892500           | 4700000            | 
| EAST VILLAGE              | 03 THREE FAMILY HOMES | 18                     | 1               | 2400000           | 2400000            | 2400000           | 2400000            | 
| GRAMERCY                  | 03 THREE FAMILY HOMES | 13                     | 1               | 3450000           | 3450000            | 3450000           | 3450000            | 
| GREENWICH VILLAGE-CENTRAL | 01 ONE FAMILY HOMES   | 72                     | 3               | 2100000           | 9798000            | 12219000          | 15075000           | 
| GREENWICH VILLAGE-CENTRAL | 02 TWO FAMILY HOMES   | 55                     | 4               | 2350000           | 6662500            | 4450000           | 15400000           | 
| GREENWICH VILLAGE-WEST    | 01 ONE FAMILY HOMES   | 253                    | 4               | 1764000           | 6034750            | 4712500           | 12950000           | 
| GREENWICH VILLAGE-WEST    | 02 TWO FAMILY HOMES   | 281                    | 10              | 3325000           | 5371486            | 5337430           | 8250000            | 
```