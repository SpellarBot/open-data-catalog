# Port of Los Angeles - Historic Tonage Data MMRT

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/port-of-los-angeles-historic-tonage-data-mmrt-2cfa3) |
| Metadata | [Link](https://data.lacity.org/api/views/i9rh-q5gx) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/i9rh-q5gx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/i9rh-q5gx/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | i9rh-q5gx |
| Name | Port of Los Angeles - Historic Tonage Data MMRT |
| Attribution | Port of Los Angeles |
| Category | A Prosperous City |
| Tags | jobs, economy, business, port, historic tonage, mmrt, tonnage |
| Created | 2014-03-24T21:29:23Z |
| Publication Date | 2016-10-26T22:16:46Z |

## Description

Port of Los Angeles - Historic Tonage Data MMRT

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| Yes      | time           | year          | Year          | number    | text        |
| Yes      | numeric metric | dry_bulk      | Dry Bulk      | number    | number      |
| Yes      | numeric metric | liquid_bulk   | Liquid Bulk   | number    | number      |
| Yes      | numeric metric | general_cargo | General Cargo | number    | number      |
| Yes      | numeric metric | total         | Total         | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:i9rh-q5gx d:2015-01-01T00:00:00.000Z m:total=176.7 m:liquid_bulk=10.3 m:dry_bulk=1.4 m:general_cargo=165

series e:i9rh-q5gx d:2014-01-01T00:00:00.000Z m:total=176.5 m:liquid_bulk=10.5 m:dry_bulk=1 m:general_cargo=165

series e:i9rh-q5gx d:2013-01-01T00:00:00.000Z m:total=165.1 m:liquid_bulk=7.8 m:dry_bulk=1 m:general_cargo=156.3
```

## Meta Commands

```ls
metric m:dry_bulk p:float l:"Dry Bulk" t:dataTypeName=number

metric m:liquid_bulk p:float l:"Liquid Bulk" t:dataTypeName=number

metric m:general_cargo p:float l:"General Cargo" t:dataTypeName=number

metric m:total p:float l:Total t:dataTypeName=number

entity e:i9rh-q5gx l:"Port of Los Angeles - Historic Tonage Data MMRT" t:attribution="Port of Los Angeles" t:url=https://data.lacity.org/api/views/i9rh-q5gx

property e:i9rh-q5gx t:meta.view v:id=i9rh-q5gx v:category="A Prosperous City" v:averageRating=0 v:name="Port of Los Angeles - Historic Tonage Data MMRT" v:attribution="Port of Los Angeles"

property e:i9rh-q5gx t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:i9rh-q5gx t:meta.view.owner v:id=2ib6-ssvz v:profileImageUrlMedium=/api/users/2ib6-ssvz/profile_images/THUMB v:profileImageUrlLarge=/api/users/2ib6-ssvz/profile_images/LARGE v:screenName="Port of Los Angeles" v:profileImageUrlSmall=/api/users/2ib6-ssvz/profile_images/TINY v:displayName="Port of Los Angeles"

property e:i9rh-q5gx t:meta.view.tableauthor v:id=2ib6-ssvz v:profileImageUrlMedium=/api/users/2ib6-ssvz/profile_images/THUMB v:profileImageUrlLarge=/api/users/2ib6-ssvz/profile_images/LARGE v:screenName="Port of Los Angeles" v:profileImageUrlSmall=/api/users/2ib6-ssvz/profile_images/TINY v:roleName=publisher v:displayName="Port of Los Angeles"
```

## Top Records

```ls
| year | dry_bulk | liquid_bulk | general_cargo | total | 
| ==== | ======== | =========== | ============= | ===== | 
| 2015 | 1.4      | 10.3        | 165           | 176.7 | 
| 2014 | 1        | 10.5        | 165           | 176.5 | 
| 2013 | 1        | 7.8         | 156.3         | 165.1 | 
| 2012 | 1.1      | 9.9         | 163.9         | 174.9 | 
| 2011 | 1.2      | 10.6        | 149.1         | 160.9 | 
| 2010 | 1.4      | 10.7        | 145.8         | 157.9 | 
| 2009 | 2        | 11.1        | 144.3         | 157.4 | 
| 2008 | 1.9      | 6.2         | 161.9         | 170   | 
| 2007 | 2.8      | 15.4        | 171.9         | 190.1 | 
| 2006 | 3.6      | 22.8        | 155.2         | 181.6 | 
```