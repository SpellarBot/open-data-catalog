# AADT Turning Traffic 1999

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/aadt-turning-traffic-1999) |
| Metadata | [Link](https://data.iowa.gov/api/views/9bnf-mwkb) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/9bnf-mwkb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/9bnf-mwkb/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | 9bnf-mwkb |
| Name | AADT Turning Traffic 1999 |
| Attribution | Iowa Department of Transportation - Office of Systems Planning |
| Category | Transportation & Utilities |
| Tags | asset, classification, total aadt, passenger, single unit, combo unit, leg label, aadt, turning movement, traffic, iowa dot, iowa department of transportation |
| Created | 2016-09-29T19:08:21Z |
| Publication Date | 2016-09-29T19:09:55Z |
| Rows Updated | 2016-09-29T19:08:21Z |

## Description

Iowa turning traffic data (AADT) for intersections on the primary, secondary and municipal roadway systems for 1999. The state is divided into 4 quadrants and each quadrant is counted every 4 years.

The Turning Movements application includes all AADT Turning Traffic data for years 1998-2015 and can be found on the Iowa DOT Interactive Map Portal: http://iowadot.maps.arcgis.com/apps/Viewer/index.html?appid=a29e44be6e314799b612335342a13f62

## Columns

```ls
| Included | Schema Type | Field Name           | Name                 | Data Type | Render Type |
| ======== | =========== | ==================== | ==================== | ========= | =========== |
| Yes      | series tag  | station              | STATION              | text      | text        |
| Yes      | series tag  | intersection_leg     | INTERSECTION_LEG     | text      | text        |
| Yes      | series tag  | total_aadt           | TOTAL_AADT           | text      | text        |
| Yes      | series tag  | passenger_aadt       | PASSENGER_AADT       | text      | text        |
| Yes      | series tag  | single_unit_aadt     | SINGLE_UNIT_AADT     | text      | text        |
| Yes      | series tag  | combo_unit_aadt      | COMBO_UNIT_AADT      | text      | text        |
| Yes      | series tag  | turning_movement_url | TURNING_MOVEMENT_URL | text      | text        |
| Yes      | series tag  | objectid             | OBJECTID             | text      | number      |
```

## Time Field

```ls
Value = 
Format & Zone = yyyy
```

## Data Commands

```ls
series e:9bnf-mwkb d:1999-01-01T00:00:00.000Z t:turning_movement_url=http://www.iowadotmaps.com/msp/traffic/turning_movements/1999/08131052099.pdf t:station=08131052099 t:objectid=1 m:row_number.9bnf-mwkb=1

series e:9bnf-mwkb d:1999-01-01T00:00:00.000Z t:turning_movement_url=http://www.iowadotmaps.com/msp/traffic/turning_movements/1999/08141501099.pdf t:station=08141501099 t:objectid=2 m:row_number.9bnf-mwkb=2

series e:9bnf-mwkb d:1999-01-01T00:00:00.000Z t:turning_movement_url=http://www.iowadotmaps.com/msp/traffic/turning_movements/1999/08141701099.pdf t:station=08141701099 t:objectid=3 m:row_number.9bnf-mwkb=3
```

## Meta Commands

```ls
metric m:row_number.9bnf-mwkb p:long l:"Row Number"

entity e:9bnf-mwkb l:"AADT Turning Traffic 1999" t:attribution="Iowa Department of Transportation - Office of Systems Planning" t:url=https://data.iowa.gov/api/views/9bnf-mwkb

property e:9bnf-mwkb t:meta.view v:id=9bnf-mwkb v:category="Transportation & Utilities" v:averageRating=0 v:name="AADT Turning Traffic 1999" v:attribution="Iowa Department of Transportation - Office of Systems Planning"

property e:9bnf-mwkb t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:9bnf-mwkb t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```