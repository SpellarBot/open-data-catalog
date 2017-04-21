# Recycled Water Delivered in the City of Los Angeles

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/recycled-water-delivered-in-the-city-of-los-angeles-57576) |
| Metadata | [Link](https://data.lacity.org/api/views/f4qc-fg29) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/f4qc-fg29/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/f4qc-fg29/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | f4qc-fg29 |
| Name | Recycled Water Delivered in the City of Los Angeles |
| Attribution | LADWP |
| Category | A Livable and Sustainable City |
| Created | 2014-05-12T22:55:56Z |
| Publication Date | 2017-03-13T21:45:16Z |

## Description

Recycled Water delivered in the City of Los Angeles in Acre-Feet. An Acre Foot is a unit of volume equal to one foot water in depth spread across one Acre (325,853.38 gallons).

## Columns

```ls
| Included | Schema Type    | Field Name       | Name               | Data Type | Render Type |
| ======== | ============== | ================ | ================== | ========= | =========== |
| Yes      | time           | month            | Month-Year         | text      | text        |
| Yes      | numeric metric | actual_acre_feet | Actual (Acre Feet) | number    | number      |
```

## Time Field

```ls
Value = month
Format & Zone = MMM-yy
```

## Data Commands

```ls
series e:f4qc-fg29 d:2012-07-01T00:00:00.000Z m:actual_acre_feet=880

series e:f4qc-fg29 d:2012-08-01T00:00:00.000Z m:actual_acre_feet=567

series e:f4qc-fg29 d:2012-09-01T00:00:00.000Z m:actual_acre_feet=578
```

## Meta Commands

```ls
metric m:actual_acre_feet p:integer l:"Actual (Acre Feet)" t:dataTypeName=number

entity e:f4qc-fg29 l:"Recycled Water Delivered in the City of Los Angeles" t:attribution=LADWP t:url=https://data.lacity.org/api/views/f4qc-fg29

property e:f4qc-fg29 t:meta.view v:id=f4qc-fg29 v:category="A Livable and Sustainable City" v:averageRating=0 v:name="Recycled Water Delivered in the City of Los Angeles" v:attribution=LADWP

property e:f4qc-fg29 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:f4qc-fg29 t:meta.view.owner v:id=hb8e-gdsp v:profileImageUrlMedium=/api/users/hb8e-gdsp/profile_images/THUMB v:profileImageUrlLarge=/api/users/hb8e-gdsp/profile_images/LARGE v:screenName="LA DWP OpenData" v:profileImageUrlSmall=/api/users/hb8e-gdsp/profile_images/TINY v:displayName="LA DWP OpenData"

property e:f4qc-fg29 t:meta.view.tableauthor v:id=hb8e-gdsp v:profileImageUrlMedium=/api/users/hb8e-gdsp/profile_images/THUMB v:profileImageUrlLarge=/api/users/hb8e-gdsp/profile_images/LARGE v:screenName="LA DWP OpenData" v:profileImageUrlSmall=/api/users/hb8e-gdsp/profile_images/TINY v:roleName=publisher v:displayName="LA DWP OpenData"
```

## Top Records

```ls
| month  | actual_acre_feet | 
| ====== | ================ | 
| Jul-12 | 880              | 
| Aug-12 | 567              | 
| Sep-12 | 578              | 
| Oct-12 | 727              | 
| Nov-12 | 430              | 
| Dec-12 | 256              | 
| Jan-13 | 0                | 
| Feb-13 | 1061.00          | 
| Mar-13 | 449.7            | 
| Apr-13 | 715.1            | 
```