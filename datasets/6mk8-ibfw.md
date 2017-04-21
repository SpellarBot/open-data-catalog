# Freight - Grain Elevators

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/freight-grain-elevators) |
| Metadata | [Link](https://data.iowa.gov/api/views/6mk8-ibfw) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/6mk8-ibfw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/6mk8-ibfw/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | 6mk8-ibfw |
| Name | Freight - Grain Elevators |
| Attribution | Iowa Department of Transportation - Office of Systems Planning |
| Category | Transportation & Utilities |
| Tags | reference, rail, freight, grain, iowa dot, iowa department of transportation |
| Created | 2016-06-09T20:04:46Z |
| Publication Date | 2016-06-09T20:05:47Z |

## Description

This layer depicts the grain elevators with access to rail in the state. It does not include grain elevators that are not located on rail lines.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| Yes      | series tag     | city_name           | CITY_NAME           | text      | text        |
| Yes      | numeric metric | hopper_cap          | HOPPER_CAP          | number    | number      |
| Yes      | numeric metric | storage_cap         | STORAGE_CAP         | number    | number      |
| Yes      | numeric metric | number_elevators    | NUMBER_ELEVATORS    | number    | number      |
| Yes      | numeric metric | prev_yr_hopper_cap  | PREV_YR_HOPPER_CAP  | number    | number      |
| Yes      | numeric metric | prev_yr_storage_cap | PREV_YR_STORAGE_CAP | number    | number      |
| Yes      | series tag     | active              | ACTIVE              | text      | text        |
| No       |                | date_inactive       | DATE_INACTIVE       | date      | date        |
| Yes      | time           | mod_date            | MOD_DATE            | date      | date        |
| Yes      | series tag     | facility_name       | FACILITY_NAME       | text      | text        |
| Yes      | series tag     | objectid            | OBJECTID            | text      | number      |
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
series e:6mk8-ibfw d:2015-08-03T08:54:13.000Z t:city_name=RUDD t:facility_name="Viafield ACooperative" t:active=Y t:objectid=1 m:prev_yr_storage_cap=2461 m:storage_cap=2461 m:prev_yr_hopper_cap=25 m:hopper_cap=25

series e:6mk8-ibfw d:2015-07-28T08:41:56.000Z t:city_name="NORA SPRINGS" t:facility_name="Cartersville Elevator, Inc" t:active=Y t:objectid=2 m:prev_yr_storage_cap=1464 m:storage_cap=1464 m:prev_yr_hopper_cap=13 m:number_elevators=2 m:hopper_cap=13

series e:6mk8-ibfw d:2015-07-28T10:28:57.000Z t:city_name=ROCKFORD t:facility_name="FTF, Inc." t:active=Y t:objectid=3 m:prev_yr_storage_cap=463 m:storage_cap=461 m:prev_yr_hopper_cap=10 m:hopper_cap=10
```

## Meta Commands

```ls
metric m:hopper_cap p:integer l:HOPPER_CAP d:"Hopper Capacity" t:dataTypeName=number

metric m:storage_cap p:integer l:STORAGE_CAP d:"Storage Capacity" t:dataTypeName=number

metric m:number_elevators p:integer l:NUMBER_ELEVATORS d:"Number of Elevators" t:dataTypeName=number

metric m:prev_yr_hopper_cap p:integer l:PREV_YR_HOPPER_CAP d:"Previous Year Hopper Capacity" t:dataTypeName=number

metric m:prev_yr_storage_cap p:integer l:PREV_YR_STORAGE_CAP d:"Previous Year Storage Capacity" t:dataTypeName=number

entity e:6mk8-ibfw l:"Freight - Grain Elevators" t:attribution="Iowa Department of Transportation - Office of Systems Planning" t:url=https://data.iowa.gov/api/views/6mk8-ibfw

property e:6mk8-ibfw t:meta.view v:id=6mk8-ibfw v:category="Transportation & Utilities" v:attributionLink=https://gis.iowadot.gov/public/rest/services/Systems_Planning/Freight/MapServer/3 v:averageRating=0 v:name="Freight - Grain Elevators" v:attribution="Iowa Department of Transportation - Office of Systems Planning"

property e:6mk8-ibfw t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:6mk8-ibfw t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```

## Top Records

```ls
| city_name    | hopper_cap | storage_cap | number_elevators | prev_yr_hopper_cap | prev_yr_storage_cap | active | date_inactive | mod_date   | facility_name              | objectid | 
| ============ | ========== | =========== | ================ | ================== | =================== | ====== | ============= | ========== | ========================== | ======== | 
| RUDD         | 25         | 2461        |                  | 25                 | 2461                | Y      |               | 1438592053 | Viafield ACooperative      | 1        | 
| NORA SPRINGS | 13         | 1464        | 2                | 13                 | 1464                | Y      |               | 1438072916 | Cartersville Elevator, Inc | 2        | 
| ROCKFORD     | 10         | 461         |                  | 10                 | 463                 | Y      |               | 1438079337 | FTF, Inc.                  | 3        | 
| MARBLE ROCK  | 25         | 1941        |                  | 10                 | 1941                | Y      |               | 1438068381 | Viafield A Coop            | 4        | 
| CHARLES CITY | 25         | 682         |                  | 25                 | 682                 | Y      |               | 1437387823 | Farmers Feed & Grain Co    | 5        | 
| CHARLES CITY | 10         | 1011        |                  | 10                 | 1011                | Y      |               | 1437387840 | Growmark Inc               | 6        | 
| IONIA        | 10         | 558         |                  | 10                 | 178                 | Y      |               | 1437722964 | Five Start Coop            | 7        | 
| NEW HAMPTON  | 25         | 3660        |                  | 25                 | 3660                | Y      |               | 1438068780 | Five Star Coop             | 8        | 
| NASHUA       | 10         | 1351        | 2                | 10                 | 1351                | Y      |               | 1438068739 | Five Star Coop             | 9        | 
| LAWLER       | 10         | 1364        | 2                | 10                 | 1365                | Y      |               | 1438011222 | Come and Save Here, Inc.   | 10       | 
```