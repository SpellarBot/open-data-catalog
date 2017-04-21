# Port of Los Angeles - Historic Tonage Data Short Ton (1920-1970)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/port-of-los-angeles-historic-tonage-data-short-ton-1920-1970-a94a5) |
| Metadata | [Link](https://data.lacity.org/api/views/5a4i-e2zs) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/5a4i-e2zs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/5a4i-e2zs/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | 5a4i-e2zs |
| Name | Port of Los Angeles - Historic Tonage Data Short Ton (1920-1970) |
| Attribution | Port of Los Angeles |
| Category | A Prosperous City |
| Tags | jobs, economy, business, port, historic tonage, short ton, tonnage |
| Created | 2014-03-24T19:41:31Z |
| Publication Date | 2014-03-24T19:42:24Z |

## Description

Port of Los Angeles - Historic Tonage Data Short Ton(1920-1970)

## Columns

```ls
| Included | Schema Type    | Field Name | Name | Data Type | Render Type |
| ======== | ============== | ========== | ==== | ========= | =========== |
| Yes      | time           | year       | Year | number    | text        |
| Yes      | numeric metric | tons       | Tons | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:5a4i-e2zs d:1970-01-01T00:00:00.000Z m:tons=25937196

series e:5a4i-e2zs d:1969-01-01T00:00:00.000Z m:tons=26946622

series e:5a4i-e2zs d:1968-01-01T00:00:00.000Z m:tons=28931577
```

## Meta Commands

```ls
metric m:tons p:integer l:Tons t:dataTypeName=number

entity e:5a4i-e2zs l:"Port of Los Angeles - Historic Tonage Data Short Ton (1920-1970)" t:attribution="Port of Los Angeles" t:url=https://data.lacity.org/api/views/5a4i-e2zs

property e:5a4i-e2zs t:meta.view v:id=5a4i-e2zs v:category="A Prosperous City" v:averageRating=0 v:name="Port of Los Angeles - Historic Tonage Data Short Ton (1920-1970)" v:attribution="Port of Los Angeles"

property e:5a4i-e2zs t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:5a4i-e2zs t:meta.view.owner v:id=2ib6-ssvz v:profileImageUrlMedium=/api/users/2ib6-ssvz/profile_images/THUMB v:profileImageUrlLarge=/api/users/2ib6-ssvz/profile_images/LARGE v:screenName="Port of Los Angeles" v:profileImageUrlSmall=/api/users/2ib6-ssvz/profile_images/TINY v:displayName="Port of Los Angeles"

property e:5a4i-e2zs t:meta.view.tableauthor v:id=2ib6-ssvz v:profileImageUrlMedium=/api/users/2ib6-ssvz/profile_images/THUMB v:profileImageUrlLarge=/api/users/2ib6-ssvz/profile_images/LARGE v:screenName="Port of Los Angeles" v:profileImageUrlSmall=/api/users/2ib6-ssvz/profile_images/TINY v:roleName=publisher v:displayName="Port of Los Angeles"
```

## Top Records

```ls
| year | tons     | 
| ==== | ======== | 
| 1970 | 25937196 | 
| 1969 | 26946622 | 
| 1968 | 28931577 | 
| 1967 | 26293560 | 
| 1966 | 26182113 | 
| 1965 | 25125011 | 
| 1964 | 24494049 | 
| 1963 | 24351976 | 
| 1962 | 26088015 | 
| 1961 | 25012412 | 
```