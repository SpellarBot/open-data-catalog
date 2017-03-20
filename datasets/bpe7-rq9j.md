# AADT Turning Traffic 2008

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/aadt-turning-traffic-2008) |
| Metadata | [Link](https://data.iowa.gov/api/views/bpe7-rq9j) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/bpe7-rq9j/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/bpe7-rq9j/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | bpe7-rq9j |
| Name | AADT Turning Traffic 2008 |
| Attribution | Iowa Department of Transportation - Office of Systems Planning |
| Category | Transportation & Utilities |
| Tags | asset, classification, total aadt, passenger, single unit, combo unit, leg label, aadt, turning movement, traffic, iowa dot, iowa department of transportation |
| Created | 2016-09-29T18:51:26Z |
| Publication Date | 2016-09-29T18:53:02Z |
| Rows Updated | 2016-09-29T18:51:26Z |

## Description

Iowa turning traffic data (AADT) for intersections on the primary, secondary and municipal roadway systems for 2008. The state is divided into 4 quadrants and each quadrant is counted every 4 years.

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
series e:bpe7-rq9j d:2008-01-01T00:00:00.000Z t:turning_movement_url=http://www.iowadotmaps.com/msp/traffic/turning_movements/2008/01114933099.pdf t:station=01114933099 t:objectid=1 m:row_number.bpe7-rq9j=1

series e:bpe7-rq9j d:2008-01-01T00:00:00.000Z t:turning_movement_url=http://www.iowadotmaps.com/msp/traffic/turning_movements/2008/01134917099.pdf t:station=01134917099 t:objectid=2 m:row_number.bpe7-rq9j=2

series e:bpe7-rq9j d:2008-01-01T00:00:00.000Z t:turning_movement_url=http://www.iowadotmaps.com/msp/traffic/turning_movements/2008/01134949099.pdf t:station=01134949099 t:objectid=3 m:row_number.bpe7-rq9j=3
```

## Meta Commands

```ls
metric m:row_number.bpe7-rq9j p:long l:"Row Number"

entity e:bpe7-rq9j l:"AADT Turning Traffic 2008" t:attribution="Iowa Department of Transportation - Office of Systems Planning" t:url=https://data.iowa.gov/api/views/bpe7-rq9j

property e:bpe7-rq9j t:meta.view v:id=bpe7-rq9j v:category="Transportation & Utilities" v:averageRating=0 v:name="AADT Turning Traffic 2008" v:attribution="Iowa Department of Transportation - Office of Systems Planning"

property e:bpe7-rq9j t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"

property e:bpe7-rq9j t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```