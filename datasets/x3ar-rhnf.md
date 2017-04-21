# AADT Turning Traffic 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/aadt-turning-traffic-2014) |
| Metadata | [Link](https://data.iowa.gov/api/views/x3ar-rhnf) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/x3ar-rhnf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/x3ar-rhnf/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | x3ar-rhnf |
| Name | AADT Turning Traffic 2014 |
| Attribution | Iowa Department of Transportation - Office of Systems Planning |
| Category | Transportation & Utilities |
| Tags | asset, classification, total aadt, passenger, single unit, combo unit, leg label, aadt, turning movement, traffic, iowa dot, iowa department of transportation |
| Created | 2016-09-29T18:36:58Z |
| Publication Date | 2016-09-29T18:39:23Z |

## Description

Iowa turning traffic data (AADT) for intersections on the primary, secondary and municipal roadway systems for 2014. The state is divided into 4 quadrants and each quadrant is counted every 4 years.

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
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:x3ar-rhnf d:2014-01-01T00:00:00.000Z t:intersection_leg=N t:turning_movement_url=http://www.iowadot.gov/maps/msp/traffic/turning_movements/2014/04128848099.pdf t:station=04128848099 t:objectid=1 m:passenger_aadt=148 m:combo_unit_aadt=5 m:single_unit_aadt=5 m:total_aadt=157

series e:x3ar-rhnf d:2014-01-01T00:00:00.000Z t:intersection_leg=S t:turning_movement_url=http://www.iowadot.gov/maps/msp/traffic/turning_movements/2014/04128848099.pdf t:station=04128848099 t:objectid=2 m:passenger_aadt=407 m:combo_unit_aadt=5 m:single_unit_aadt=35 m:total_aadt=446

series e:x3ar-rhnf d:2014-01-01T00:00:00.000Z t:intersection_leg=E t:turning_movement_url=http://www.iowadot.gov/maps/msp/traffic/turning_movements/2014/04128848099.pdf t:station=04128848099 t:objectid=3 m:passenger_aadt=1494 m:combo_unit_aadt=86 m:single_unit_aadt=77 m:total_aadt=1657
```

## Meta Commands

```ls
metric m:total_aadt p:integer l:TOTAL_AADT d:"Total AADT" t:dataTypeName=number

metric m:passenger_aadt p:integer l:PASSENGER_AADT d:"Passenger AADT" t:dataTypeName=number

metric m:single_unit_aadt p:integer l:SINGLE_UNIT_AADT d:"Single Unit AADT" t:dataTypeName=number

metric m:combo_unit_aadt p:integer l:COMBO_UNIT_AADT d:"Combo Unit AADT" t:dataTypeName=number

entity e:x3ar-rhnf l:"AADT Turning Traffic 2014" t:attribution="Iowa Department of Transportation - Office of Systems Planning" t:url=https://data.iowa.gov/api/views/x3ar-rhnf

property e:x3ar-rhnf t:meta.view v:id=x3ar-rhnf v:category="Transportation & Utilities" v:averageRating=0 v:name="AADT Turning Traffic 2014" v:attribution="Iowa Department of Transportation - Office of Systems Planning"

property e:x3ar-rhnf t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:x3ar-rhnf t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```

## Top Records

```ls
| station     | intersection_leg | total_aadt | passenger_aadt | single_unit_aadt | combo_unit_aadt | turning_movement_url                                                           | objectid | 
| =========== | ================ | ========== | ============== | ================ | =============== | ============================================================================== | ======== | 
| 04128848099 | N                | 157        | 148            | 5                | 5               | http://www.iowadot.gov/maps/msp/traffic/turning_movements/2014/04128848099.pdf | 1        | 
| 04128848099 | S                | 446        | 407            | 35               | 5               | http://www.iowadot.gov/maps/msp/traffic/turning_movements/2014/04128848099.pdf | 2        | 
| 04128848099 | E                | 1657       | 1494           | 77               | 86              | http://www.iowadot.gov/maps/msp/traffic/turning_movements/2014/04128848099.pdf | 3        | 
| 04128848099 | W                | 1352       | 1211           | 58               | 82              | http://www.iowadot.gov/maps/msp/traffic/turning_movements/2014/04128848099.pdf | 4        | 
| 04231901099 | N                | 2727       | 2585           | 62               | 80              | http://www.iowadot.gov/maps/msp/traffic/turning_movements/2014/04231901099.pdf | 5        | 
| 04231901099 | E                | 908        | 883            | 24               | 2               | http://www.iowadot.gov/maps/msp/traffic/turning_movements/2014/04231901099.pdf | 6        | 
| 04231901099 | S                | 2016       | 1881           | 57               | 79              | http://www.iowadot.gov/maps/msp/traffic/turning_movements/2014/04231901099.pdf | 7        | 
| 04236501099 | N                | 4054       | 3875           | 75               | 104             | http://www.iowadot.gov/maps/msp/traffic/turning_movements/2014/04236501099.pdf | 8        | 
| 04236501099 | W                | 1332       | 1251           | 44               | 38              | http://www.iowadot.gov/maps/msp/traffic/turning_movements/2014/04236501099.pdf | 9        | 
| 04236501099 | E                | 219        | 202            | 10               | 9               | http://www.iowadot.gov/maps/msp/traffic/turning_movements/2014/04236501099.pdf | 10       | 
```