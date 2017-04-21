# Freight - Biodiesel Plants

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/freight-biodiesel-plants) |
| Metadata | [Link](https://data.iowa.gov/api/views/rx6n-da6a) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/rx6n-da6a/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/rx6n-da6a/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | rx6n-da6a |
| Name | Freight - Biodiesel Plants |
| Attribution | Iowa Department of Transportation - Office of Systems Planning |
| Category | Transportation & Utilities |
| Tags | reference, rail, freight, biodiesel, energy, iowa dot, iowa department of transportation |
| Created | 2016-06-09T20:07:10Z |
| Publication Date | 2016-06-09T20:08:15Z |

## Description

This layer depicts the biodiesel plants in the state. Note: not all of the plants have access to a railroad.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | series tag     | city_name        | CITY_NAME        | text      | text        |
| Yes      | numeric metric | capacity         | CAPACITY         | number    | number      |
| Yes      | numeric metric | prev_yr_capacity | PREV_YR_CAPACITY | number    | number      |
| Yes      | series tag     | active           | ACTIVE           | text      | text        |
| No       |                | date_inactive    | DATE_INACTIVE    | date      | date        |
| Yes      | time           | mod_date         | MOD_DATE         | date      | date        |
| Yes      | series tag     | name             | NAME             | text      | text        |
| Yes      | series tag     | objectid         | OBJECTID         | text      | number      |
```

## Time Field

```ls
Value = mod_date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = date_inactive
```

## Data Commands

```ls
series e:rx6n-da6a d:2015-07-22T13:08:02.000Z t:city_name="Iowa Falls" t:name=Cargill t:active=Y t:objectid=1 m:prev_yr_capacity=38 m:capacity=56

series e:rx6n-da6a d:2015-07-22T12:53:55.000Z t:city_name=Newton t:name="Renewable Energy Group" t:active=Y t:objectid=2 m:prev_yr_capacity=30 m:capacity=30

series e:rx6n-da6a d:2015-07-22T12:53:05.000Z t:city_name=Clinton t:name="Clinton County Bio Energy" t:active=Y t:objectid=3 m:prev_yr_capacity=10 m:capacity=10
```

## Meta Commands

```ls
metric m:capacity p:integer l:CAPACITY d:Capacity t:dataTypeName=number

metric m:prev_yr_capacity p:integer l:PREV_YR_CAPACITY d:"Previous Year Capacity" t:dataTypeName=number

entity e:rx6n-da6a l:"Freight - Biodiesel Plants" t:attribution="Iowa Department of Transportation - Office of Systems Planning" t:url=https://data.iowa.gov/api/views/rx6n-da6a

property e:rx6n-da6a t:meta.view v:id=rx6n-da6a v:category="Transportation & Utilities" v:attributionLink=https://gis.iowadot.gov/public/rest/services/Systems_Planning/Freight/MapServer/5 v:averageRating=0 v:name="Freight - Biodiesel Plants" v:attribution="Iowa Department of Transportation - Office of Systems Planning"

property e:rx6n-da6a t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:rx6n-da6a t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```

## Top Records

```ls
| city_name      | capacity | prev_yr_capacity | active | date_inactive | mod_date   | name                      | objectid | 
| ============== | ======== | ================ | ====== | ============= | ========== | ========================= | ======== | 
| Iowa Falls     | 56       | 38               | Y      |               | 1437570482 | Cargill                   | 1        | 
| Newton         | 30       | 30               | Y      |               | 1437569635 | Renewable Energy Group    | 2        | 
| Clinton        | 10       | 10               | Y      |               | 1437569585 | Clinton County Bio Energy | 3        | 
| Algona         | 60       | 60               | Y      |               | 1437569500 | Ag Processing Inc (AGP)   | 4        | 
| Mason City     | 30       | 30               | Y      |               | 1437569658 | Renewable Energy Group    | 5        | 
| Washington     | 30       | 30               | Y      |               | 1437569610 | Iowa Renewable Energy     | 6        | 
| Galva          | 5        | 5                | Y      |               | 1440417776 |                           | 7        | 
| Ralston        | 12       | 12               | Y      |               | 1437569676 | Renewable Energy Group    | 8        | 
| Crawfordsville | 10       | 10               | Y      |               | 1437569723 | W2 Fuel                   | 9        | 
|                |          | 2                | I      | 1377648000    | 1437569465 |                           | 10       | 
```