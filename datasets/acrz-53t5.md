# Freight - Grain Processing Facilities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/freight-grain-processing-facilities) |
| Metadata | [Link](https://data.iowa.gov/api/views/acrz-53t5) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/acrz-53t5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/acrz-53t5/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | acrz-53t5 |
| Name | Freight - Grain Processing Facilities |
| Attribution | Iowa Department of Transportation - Office of Systems Planning |
| Category | Transportation & Utilities |
| Tags | reference, rail, freight, grain, processing, iowa dot, iowa department of transportation |
| Created | 2016-06-09T20:03:39Z |
| Publication Date | 2016-06-09T20:04:33Z |

## Description

This layer depicts the grain processing facilities in the state.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| Yes      | series tag     | city_name          | CITY_NAME          | text      | text        |
| Yes      | numeric metric | number_facilities  | NUMBER_FACILITIES  | number    | number      |
| Yes      | numeric metric | prev_yr_facilities | PREV_YR_FACILITIES | number    | number      |
| Yes      | series tag     | active             | ACTIVE             | text      | text        |
| No       |                | date_inactive      | DATE_INACTIVE      | date      | date        |
| Yes      | time           | mod_date           | MOD_DATE           | date      | date        |
| Yes      | series tag     | objectid           | OBJECTID           | text      | number      |
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
series e:acrz-53t5 d:2015-01-15T13:22:43.000Z t:active=Y t:objectid=1 m:number_facilities=2 m:prev_yr_facilities=2

series e:acrz-53t5 d:2015-01-15T13:22:43.000Z t:active=Y t:objectid=2 m:number_facilities=3 m:prev_yr_facilities=3

series e:acrz-53t5 d:2015-01-15T13:22:43.000Z t:active=Y t:objectid=3 m:number_facilities=1 m:prev_yr_facilities=1
```

## Meta Commands

```ls
metric m:number_facilities p:integer l:NUMBER_FACILITIES d:"Number of Facilities" t:dataTypeName=number

metric m:prev_yr_facilities p:integer l:PREV_YR_FACILITIES d:"Previous Year Facilities" t:dataTypeName=number

entity e:acrz-53t5 l:"Freight - Grain Processing Facilities" t:attribution="Iowa Department of Transportation - Office of Systems Planning" t:url=https://data.iowa.gov/api/views/acrz-53t5

property e:acrz-53t5 t:meta.view v:id=acrz-53t5 v:category="Transportation & Utilities" v:attributionLink=https://gis.iowadot.gov/public/rest/services/Systems_Planning/Freight/MapServer/1 v:averageRating=0 v:name="Freight - Grain Processing Facilities" v:attribution="Iowa Department of Transportation - Office of Systems Planning"

property e:acrz-53t5 t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:acrz-53t5 t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```

## Top Records

```ls
| city_name | number_facilities | prev_yr_facilities | active | date_inactive | mod_date   | objectid | 
| ========= | ================= | ================== | ====== | ============= | ========== | ======== | 
|           | 2                 | 2                  | Y      |               | 1421328163 | 1        | 
|           | 3                 | 3                  | Y      |               | 1421328163 | 2        | 
|           | 1                 | 1                  | Y      |               | 1421328163 | 3        | 
|           | 1                 | 1                  | Y      |               | 1421328163 | 4        | 
|           | 1                 | 1                  | Y      |               | 1421328163 | 5        | 
|           | 2                 | 2                  | Y      |               | 1421328163 | 6        | 
|           | 1                 | 1                  | Y      |               | 1421328163 | 7        | 
|           | 1                 | 1                  | Y      |               | 1421328163 | 8        | 
|           | 1                 | 1                  | Y      |               | 1421328163 | 9        | 
|           | 1                 | 1                  | Y      |               | 1421328163 | 10       | 
```