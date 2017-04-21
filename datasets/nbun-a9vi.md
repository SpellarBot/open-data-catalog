# DOF: Summary of Neighborhood Sales for Brooklyn for Class 1-, 2- and 3-Family homes - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dof-summary-of-neighborhood-sales-for-brooklyn-for-class-1-2-and-3-family-homes-2009-f96b7) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/nbun-a9vi) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/nbun-a9vi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/nbun-a9vi/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | nbun-a9vi |
| Name | DOF: Summary of Neighborhood Sales for Brooklyn for Class 1-, 2- and 3-Family homes - 2009 |
| Attribution | Department of Finance (DOF) |
| Category | Housing & Development |
| Tags | department of finance, finance, dof, property, properties, neighborhoods, sales, neighborhood sales, homes, family homes, class-1, class-2, class-3, borough, brooklyn |
| Created | 2011-10-05T17:47:26Z |
| Publication Date | 2013-06-26T16:56:49Z |

## Description

The Department of Finance (DOF) maintains records for all property sales in New York City, including sales of family homes in each borough. This list is a summary of neighborhood sales for Class 1-, 2- and 3-Family homes in Brooklyn in 2009.
Update Frequency: Annually

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
series e:nbun-a9vi d:2009-01-01T00:00:00.000Z t:neighborhood="BATH BEACH" t:type_of_home="01 ONE FAMILY HOMES" m:average_sale_price=551466 m:lowest_sale_price=155356 m:median_sale_price=500000 m:highest_sale_price=1500000 m:total_no_of_properties=547 m:number_of_sales=19

series e:nbun-a9vi d:2009-01-01T00:00:00.000Z t:neighborhood="BATH BEACH" t:type_of_home="02 TWO FAMILY HOMES" m:average_sale_price=603588 m:lowest_sale_price=150000 m:median_sale_price=615000 m:highest_sale_price=945000 m:total_no_of_properties=2031 m:number_of_sales=52

series e:nbun-a9vi d:2009-01-01T00:00:00.000Z t:neighborhood="BATH BEACH" t:type_of_home="03 THREE FAMILY HOMES" m:average_sale_price=877756 m:lowest_sale_price=500000 m:median_sale_price=896848 m:highest_sale_price=1180000 m:total_no_of_properties=837 m:number_of_sales=20
```

## Meta Commands

```ls
metric m:total_no_of_properties p:integer l:"TOTAL NO. OF PROPERTIES" t:dataTypeName=number

metric m:number_of_sales p:integer l:"NUMBER OF SALES" t:dataTypeName=number

metric m:lowest_sale_price p:integer l:"LOWEST SALE PRICE" t:dataTypeName=money

metric m:average_sale_price p:double l:"AVERAGE SALE PRICE" t:dataTypeName=money

metric m:median_sale_price p:integer l:"MEDIAN SALE PRICE" t:dataTypeName=money

metric m:highest_sale_price p:integer l:"HIGHEST SALE PRICE" t:dataTypeName=money

entity e:nbun-a9vi l:"DOF: Summary of Neighborhood Sales for Brooklyn for Class 1-, 2- and 3-Family homes - 2009" t:attribution="Department of Finance (DOF)" t:url=https://data.cityofnewyork.us/api/views/nbun-a9vi

property e:nbun-a9vi t:meta.view v:id=nbun-a9vi v:category="Housing & Development" v:averageRating=0 v:name="DOF: Summary of Neighborhood Sales for Brooklyn for Class 1-, 2- and 3-Family homes - 2009" v:attribution="Department of Finance (DOF)"

property e:nbun-a9vi t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:nbun-a9vi t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| neighborhood       | type_of_home          | total_no_of_properties | number_of_sales | lowest_sale_price | average_sale_price | median_sale_price | highest_sale_price | 
| ================== | ===================== | ====================== | =============== | ================= | ================== | ================= | ================== | 
| BATH BEACH         | 01 ONE FAMILY HOMES   | 547                    | 19              | 155356            | 551466             | 500000            | 1500000            | 
| BATH BEACH         | 02 TWO FAMILY HOMES   | 2031                   | 52              | 150000            | 603588             | 615000            | 945000             | 
| BATH BEACH         | 03 THREE FAMILY HOMES | 837                    | 20              | 500000            | 877756             | 896848            | 1180000            | 
| BAY RIDGE          | 01 ONE FAMILY HOMES   | 3749                   | 99              | 349500            | 752953             | 645000            | 2525000            | 
| BAY RIDGE          | 02 TWO FAMILY HOMES   | 4548                   | 97              | 150000            | 690439             | 710000            | 1300000            | 
| BAY RIDGE          | 03 THREE FAMILY HOMES | 685                    | 7               | 375000            | 762857             | 730000            | 1300000            | 
| BEDFORD STUYVESANT | 01 ONE FAMILY HOMES   | 825                    | 23              | 150000            | 402858             | 310000            | 890854             | 
| BEDFORD STUYVESANT | 02 TWO FAMILY HOMES   | 5762                   | 186             | 165000            | 457947             | 449500            | 1550000            | 
| BEDFORD STUYVESANT | 03 THREE FAMILY HOMES | 3390                   | 112             | 200000            | 492884             | 480000            | 1400000            | 
| BENSONHURST        | 01 ONE FAMILY HOMES   | 1394                   | 32              | 300000            | 596578             | 574500            | 1318000            | 
```