# Freight - Ethanol Plants

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/freight-ethanol-plants) |
| Metadata | [Link](https://data.iowa.gov/api/views/jy2j-p83k) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/jy2j-p83k/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/jy2j-p83k/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | jy2j-p83k |
| Name | Freight - Ethanol Plants |
| Attribution | Iowa Department of Transportation - Office of Systems Planning |
| Category | Transportation & Utilities |
| Tags | reference, rail, freight, ethanol, energy, iowa dot, iowa department of transportation |
| Created | 2016-06-09T20:08:29Z |
| Publication Date | 2016-06-09T20:09:23Z |

## Description

This layer depicts the ethanol plants in the state. Note: not all of the plants have access to a railroad.

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
series e:jy2j-p83k d:2015-07-22T08:01:59.000Z t:city_name=Eddyville t:name="Cargill, Inc" t:active=Y t:objectid=1 m:prev_yr_capacity=35 m:capacity=35

series e:jy2j-p83k d:2015-07-22T08:03:22.000Z t:city_name="Fort Dodge" t:name="Cargill, Inc" t:active=Y t:objectid=2 m:prev_yr_capacity=115 m:capacity=115

series e:jy2j-p83k d:2015-07-22T09:03:04.000Z t:city_name=Muscatine t:name="Grain Processing Corporation" t:active=Y t:objectid=3 m:prev_yr_capacity=20 m:capacity=20
```

## Meta Commands

```ls
metric m:capacity p:integer l:CAPACITY d:Capacity t:dataTypeName=number

metric m:prev_yr_capacity p:integer l:PREV_YR_CAPACITY d:"Previous Year Capacity" t:dataTypeName=number

entity e:jy2j-p83k l:"Freight - Ethanol Plants" t:attribution="Iowa Department of Transportation - Office of Systems Planning" t:url=https://data.iowa.gov/api/views/jy2j-p83k

property e:jy2j-p83k t:meta.view v:id=jy2j-p83k v:category="Transportation & Utilities" v:attributionLink=https://gis.iowadot.gov/public/rest/services/Systems_Planning/Freight/MapServer/6 v:averageRating=0 v:name="Freight - Ethanol Plants" v:attribution="Iowa Department of Transportation - Office of Systems Planning"

property e:jy2j-p83k t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:jy2j-p83k t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```

## Top Records

```ls
| city_name      | capacity | prev_yr_capacity | active | date_inactive | mod_date   | name                             | objectid | 
| ============== | ======== | ================ | ====== | ============= | ========== | ================================ | ======== | 
| Eddyville      | 35       | 35               | Y      |               | 1437552119 | Cargill, Inc                     | 1        | 
| Fort Dodge     | 115      | 115              | Y      |               | 1437552202 | Cargill, Inc                     | 2        | 
| Muscatine      | 20       | 20               | Y      |               | 1437555784 | Grain Processing Corporation     | 3        | 
| Council Bluffs | 118      | 115              | Y      |               | 1437557730 | Southwest Iowa Renewable Energy  | 4        | 
| Emmetsburg     | 55       | 55               | Y      |               | 1437557503 | POET - Emmetsburg                | 5        | 
| Emmetsburg     | 20       | 20               | Y      |               | 1437557537 | POET - DSM Advanced Biofuel, LLC | 6        | 
| Hamburg        |          | 8                | Y      |               | 1437551362 | Manildra Milling                 | 7        | 
| Blairstown     | 6        | 6                | Y      |               | 1437555485 | Fiberight, LLC                   | 8        | 
| Nevada         | 30       | 30               | N      |               | 1437552328 | DuPont Nevada Cellulosic Ethanol | 9        | 
| Mason City     | 115      | 110              | Y      |               | 1437555749 | Golden Grain Energy              | 10       | 
```