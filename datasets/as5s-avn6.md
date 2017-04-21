# AADT Turning Traffic 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/aadt-turning-traffic-2011) |
| Metadata | [Link](https://data.iowa.gov/api/views/as5s-avn6) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/as5s-avn6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/as5s-avn6/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | as5s-avn6 |
| Name | AADT Turning Traffic 2011 |
| Attribution | Iowa Department of Transportation - Office of Systems Planning |
| Category | Transportation & Utilities |
| Tags | asset, classification, total aadt, passenger, single unit, combo unit, leg label, aadt, turning movement, traffic, iowa dot, iowa department of transportation |
| Created | 2016-09-29T18:43:50Z |
| Publication Date | 2016-09-29T18:45:13Z |

## Description

Iowa turning traffic data (AADT) for intersections on the primary, secondary and municipal roadway systems for 2011. The state is divided into 4 quadrants and each quadrant is counted every 4 years.

The Turning Movements application includes all AADT Turning Traffic data for years 1998-2015 and can be found on the Iowa DOT Interactive Map Portal: http://iowadot.maps.arcgis.com/apps/Viewer/index.html?appid=a29e44be6e314799b612335342a13f62

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| Yes      | series tag     | station              | STATION              | text      | text        |
| Yes      | series tag     | intersection_leg     | INTERSECTION_LEG     | text      | text        |
| Yes      | numeric metric | total_aadt           | TOTAL_AADT           | number    | text        |
| Yes      | numeric metric | passenger_aadt       | PASSENGER_AADT       | number    | text        |
| Yes      | numeric metric | single_unit_aadt     | SINGLE_UNIT_AADT     | number    | text        |
| Yes      | numeric metric | combo_unit_aadt      | COMBO_UNIT_AADT      | number    | text        |
| Yes      | series tag     | turning_movement_url | TURNING_MOVEMENT_URL | text      | text        |
| Yes      | series tag     | objectid             | OBJECTID             | text      | number      |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:as5s-avn6 d:2011-01-01T00:00:00.000Z t:intersection_leg=S t:turning_movement_url=http://www.iowadotmaps.com/msp/traffic/turning_movements/2011/07314994099.pdf t:station=07314994099 t:objectid=1 m:passenger_aadt=2976 m:combo_unit_aadt=10 m:single_unit_aadt=67 m:total_aadt=3053

series e:as5s-avn6 d:2011-01-01T00:00:00.000Z t:intersection_leg=E t:turning_movement_url=http://www.iowadotmaps.com/msp/traffic/turning_movements/2011/07314994099.pdf t:station=07314994099 t:objectid=2 m:passenger_aadt=21780 m:combo_unit_aadt=64 m:single_unit_aadt=198 m:total_aadt=22042

series e:as5s-avn6 d:2011-01-01T00:00:00.000Z t:intersection_leg=N t:turning_movement_url=http://www.iowadotmaps.com/msp/traffic/turning_movements/2011/07314994099.pdf t:station=07314994099 t:objectid=3 m:passenger_aadt=435 m:combo_unit_aadt=0 m:single_unit_aadt=2 m:total_aadt=437
```

## Meta Commands

```ls
metric m:total_aadt p:integer l:TOTAL_AADT d:"Total AADT" t:dataTypeName=number

metric m:passenger_aadt p:integer l:PASSENGER_AADT d:"Passenger AADT" t:dataTypeName=number

metric m:single_unit_aadt p:integer l:SINGLE_UNIT_AADT d:"Single Unit AADT" t:dataTypeName=number

metric m:combo_unit_aadt p:integer l:COMBO_UNIT_AADT d:"Combo Unit AADT" t:dataTypeName=number

entity e:as5s-avn6 l:"AADT Turning Traffic 2011" t:attribution="Iowa Department of Transportation - Office of Systems Planning" t:url=https://data.iowa.gov/api/views/as5s-avn6

property e:as5s-avn6 t:meta.view v:id=as5s-avn6 v:category="Transportation & Utilities" v:averageRating=0 v:name="AADT Turning Traffic 2011" v:attribution="Iowa Department of Transportation - Office of Systems Planning"

property e:as5s-avn6 t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:as5s-avn6 t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```

## Top Records

```ls
| station     | intersection_leg | total_aadt | passenger_aadt | single_unit_aadt | combo_unit_aadt | turning_movement_url                                                          | objectid | 
| =========== | ================ | ========== | ============== | ================ | =============== | ============================================================================= | ======== | 
| 07314994099 | S                | 3053       | 2976           | 67               | 10              | http://www.iowadotmaps.com/msp/traffic/turning_movements/2011/07314994099.pdf | 1        | 
| 07314994099 | E                | 22042      | 21780          | 198              | 64              | http://www.iowadotmaps.com/msp/traffic/turning_movements/2011/07314994099.pdf | 2        | 
| 07314994099 | N                | 437        | 435            | 2                | 0               | http://www.iowadotmaps.com/msp/traffic/turning_movements/2011/07314994099.pdf | 3        | 
| 07314994099 | W                | 24398      | 24113          | 214              | 71              | http://www.iowadotmaps.com/msp/traffic/turning_movements/2011/07314994099.pdf | 4        | 
| 07323053099 | N                | 283        | 271            | 13               | 0               | http://www.iowadotmaps.com/msp/traffic/turning_movements/2011/07323053099.pdf | 5        | 
| 07323053099 | W                | 10269      | 10045          | 186              | 39              | http://www.iowadotmaps.com/msp/traffic/turning_movements/2011/07323053099.pdf | 6        | 
| 07323053099 | E                | 10138      | 9918           | 182              | 39              | http://www.iowadotmaps.com/msp/traffic/turning_movements/2011/07323053099.pdf | 7        | 
| 07323053099 | S                | 152        | 143            | 9                | 0               | http://www.iowadotmaps.com/msp/traffic/turning_movements/2011/07323053099.pdf | 8        | 
| 07323245099 | N                | 1150       | 1124           | 22               | 3               | http://www.iowadotmaps.com/msp/traffic/turning_movements/2011/07323245099.pdf | 9        | 
| 07323245099 | W                | 14140      | 13896          | 204              | 40              | http://www.iowadotmaps.com/msp/traffic/turning_movements/2011/07323245099.pdf | 10       | 
```