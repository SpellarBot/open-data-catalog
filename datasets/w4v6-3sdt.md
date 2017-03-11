# DOF: Summary of Neighborhood Sales for the Bronx for Class 1-, 2- and 3-Family homes - 2009

## Dataset

* [Dataset URL](https://data.cityofnewyork.us/api/views/w4v6-3sdt/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/dof-summary-of-neighborhood-sales-for-the-bronx-for-class-1-2-and-3-family-homes-2009-11c00)
* Id = w4v6-3sdt
* Name = DOF: Summary of Neighborhood Sales for the Bronx for Class 1-, 2- and 3-Family homes - 2009
* Attribution = Department of Finance (DOF)
* Category = Housing & Development
* Tags = [department of finance, finance, dof, property, properties, neighborhoods, sales, neighborhood sales, homes, family homes, class-1, class-2, class-3, borough, bronx]
* Created = 2011-10-05T17:23:15Z
* Publication Date = 2013-06-21T20:54:26Z
* Rows Updated = 2013-06-21T20:54:23Z

## Description

The Department of Finance (DOF) maintains records for all property sales in New York City, including sales of family homes in each borough. This list is a summary of neighborhood sales for Class 1-, 2- and 3-Family homes in the Bronx in 2009.
Update Schedule: Annually

## Columns

```ls
| Name                    | Field Name             | Data Type | Render Type | Schema Type    | Included | 
| ======================= | ====================== | ========= | =========== | ============== | ======== | 
| updated_at              | :updated_at            | meta_data | meta_data   | time           | Yes      | 
| NEIGHBORHOOD            | neighborhood           | text      | text        | series tag     | Yes      | 
| TYPE OF HOME            | type_of_home           | text      | text        | series tag     | Yes      | 
| TOTAL NO. OF PROPERTIES | total_no_of_properties | number    | number      | numeric metric | Yes      | 
| NUMBER OF SALES         | number_of_sales        | number    | number      | numeric metric | Yes      | 
| LOWEST SALE PRICE       | lowest_sale_price      | money     | money       | numeric metric | Yes      | 
| AVERAGE SALE PRICE      | average_sale_price     | money     | money       | numeric metric | Yes      | 
| MEDIAN SALE PRICE       | median_sale_price      | money     | money       | numeric metric | Yes      | 
| HIGHEST SALE PRICE      | highest_sale_price     | money     | money       | numeric metric | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls
series e:w4v6-3sdt d:2011-10-05T10:23:17.000Z t:neighborhood=BATHGATE t:type_of_home="01 ONE FAMILY HOMES" m:average_sale_price=345752 m:lowest_sale_price=345752 m:median_sale_price=345752 m:highest_sale_price=345752 m:total_no_of_properties=87 m:number_of_sales=1

series e:w4v6-3sdt d:2011-10-05T10:23:17.000Z t:neighborhood=BATHGATE t:type_of_home="02 TWO FAMILY HOMES" m:average_sale_price=327310 m:lowest_sale_price=183028 m:median_sale_price=334750 m:highest_sale_price=415440 m:total_no_of_properties=308 m:number_of_sales=8

series e:w4v6-3sdt d:2011-10-05T10:23:17.000Z t:neighborhood=BATHGATE t:type_of_home="03 THREE FAMILY HOMES" m:average_sale_price=536674 m:lowest_sale_price=162240 m:median_sale_price=602500 m:highest_sale_price=640000 m:total_no_of_properties=131 m:number_of_sales=10
```

## Meta Commands

```ls
metric m:total_no_of_properties p:integer l:"TOTAL NO. OF PROPERTIES" t:dataTypeName=number

metric m:number_of_sales p:integer l:"NUMBER OF SALES" t:dataTypeName=number

entity e:w4v6-3sdt l:"DOF: Summary of Neighborhood Sales for the Bronx for Class 1-, 2- and 3-Family homes - 2009" t:attribution="Department of Finance (DOF)" t:url=https://data.cityofnewyork.us/api/views/w4v6-3sdt

property e:w4v6-3sdt t:meta.view d:2017-03-03T14:39:58.869Z v:id=w4v6-3sdt v:category="Housing & Development" v:averageRating=0 v:name="DOF: Summary of Neighborhood Sales for the Bronx for Class 1-, 2- and 3-Family homes - 2009" v:attribution="Department of Finance (DOF)"

property e:w4v6-3sdt t:meta.view.owner d:2017-03-03T14:39:58.869Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"

property e:w4v6-3sdt t:meta.view.tableauthor d:2017-03-03T14:39:58.869Z v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```