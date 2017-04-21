# Freight - Intermodal Facilities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/freight-intermodal-facilities) |
| Metadata | [Link](https://data.iowa.gov/api/views/94pv-pzzh) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/94pv-pzzh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/94pv-pzzh/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | 94pv-pzzh |
| Name | Freight - Intermodal Facilities |
| Attribution | Iowa Department of Transportation - Office of Systems Planning |
| Category | Transportation & Utilities |
| Tags | reference, rail, freight, intermodal, iowa dot, iowa department of transportation |
| Created | 2016-06-09T20:12:09Z |
| Publication Date | 2016-06-09T20:13:16Z |

## Description

Intermodal Facilities in Iowa.

## Columns

```ls
| Included | Schema Type | Field Name | Name      | Data Type | Render Type |
| ======== | =========== | ========== | ========= | ========= | =========== |
| Yes      | series tag  | name       | NAME      | text      | text        |
| Yes      | series tag  | type       | TYPE      | text      | text        |
| Yes      | series tag  | railroads  | RAILROADS | text      | text        |
| Yes      | time        | mod_date   | MOD_DATE  | date      | date        |
| Yes      | series tag  | objectid   | OBJECTID  | text      | number      |
```

## Time Field

```ls
Value = mod_date
Format & Zone = seconds
```

## Data Commands

```ls
series e:94pv-pzzh d:2015-01-15T12:04:53.000Z t:name="Council Bluffs" t:objectid=1 t:type=Trailer/Container m:row_number.94pv-pzzh=1
```

## Meta Commands

```ls
metric m:row_number.94pv-pzzh p:long l:"Row Number"

entity e:94pv-pzzh l:"Freight - Intermodal Facilities" t:attribution="Iowa Department of Transportation - Office of Systems Planning" t:url=https://data.iowa.gov/api/views/94pv-pzzh

property e:94pv-pzzh t:meta.view v:id=94pv-pzzh v:category="Transportation & Utilities" v:attributionLink=https://gis.iowadot.gov/public/rest/services/Systems_Planning/Freight/MapServer/0 v:averageRating=0 v:name="Freight - Intermodal Facilities" v:attribution="Iowa Department of Transportation - Office of Systems Planning"

property e:94pv-pzzh t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:94pv-pzzh t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```

## Top Records

```ls
| name           | type              | railroads | mod_date   | objectid | 
| ============== | ================= | ========= | ========== | ======== | 
| Council Bluffs | Trailer/Container |           | 1421323493 | 1        | 
```