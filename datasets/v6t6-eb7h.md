# Rail Containers Moved Through Port Authority of NY NJ Facilities: Beginning 2000

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/rail-containers-moved-through-port-authority-of-ny-nj-facilities-beginning-2000) |
| Metadata | [Link](https://data.ny.gov/api/views/v6t6-eb7h) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/v6t6-eb7h/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/v6t6-eb7h/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | v6t6-eb7h |
| Name | Rail Containers Moved Through Port Authority of NY NJ Facilities: Beginning 2000 |
| Attribution | Port Authority of NY&NJ |
| Category | Transportation |
| Tags | rail containers, freight, port, port authority |
| Created | 2013-05-10T11:48:22Z |
| Publication Date | 2016-03-10T17:23:03Z |

## Description

This dataset represents the total number of Rail Containers moved through Port Authority facilities in the Port of New York and New Jersey on a monthly basis from 2000 to the present

## Columns

```ls
| Included | Schema Type    | Field Name | Name                            | Data Type | Render Type |
| ======== | ============== | ========== | =============================== | ========= | =========== |
| No       |                | year       | Year                            | number    | number      |
| No       |                | month      | Month                           | text      | text        |
| Yes      | numeric metric | volume     | Number of Rail Containers Moved | number    | number      |
```

## Time Field

```ls
Value = year-month
Format & Zone = yyyy-MMMM
```

## Series Fields

```ls
Excluded Fields = year,month
```

## Data Commands

```ls
series e:v6t6-eb7h d:2012-01-01T00:00:00.000Z m:volume=33989

series e:v6t6-eb7h d:2012-02-01T00:00:00.000Z m:volume=34482

series e:v6t6-eb7h d:2012-03-01T00:00:00.000Z m:volume=42505
```

## Meta Commands

```ls
metric m:volume p:integer l:"Number of Rail Containers Moved" d:"In Twenty Foot Equivalent Units (TEUs)" t:dataTypeName=number

entity e:v6t6-eb7h l:"Rail Containers Moved Through Port Authority of NY NJ Facilities:  Beginning 2000" t:attribution="Port Authority of NY&NJ" t:url=https://data.ny.gov/api/views/v6t6-eb7h

property e:v6t6-eb7h t:meta.view v:id=v6t6-eb7h v:category=Transportation v:attributionLink=http://www.panynj.gov/port/pdf/port-trade-statistics-summary-2001-2011.pdf v:averageRating=0 v:name="Rail Containers Moved Through Port Authority of NY NJ Facilities:  Beginning 2000" v:attribution="Port Authority of NY&NJ"

property e:v6t6-eb7h t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:v6t6-eb7h t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:v6t6-eb7h t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| year | month     | volume | 
| ==== | ========= | ====== | 
| 2012 | January   | 33989  | 
| 2012 | February  | 34482  | 
| 2012 | March     | 42505  | 
| 2012 | April     | 38538  | 
| 2012 | May       | 40191  | 
| 2012 | June      | 38570  | 
| 2012 | July      | 40357  | 
| 2012 | August    | 40976  | 
| 2012 | September | 35739  | 
| 2012 | October   | 33589  | 
```