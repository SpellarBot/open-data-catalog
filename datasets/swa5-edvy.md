# AADT Turning Traffic 2003

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/aadt-turning-traffic-2003) |
| Metadata | [Link](https://data.iowa.gov/api/views/swa5-edvy) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/swa5-edvy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/swa5-edvy/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | swa5-edvy |
| Name | AADT Turning Traffic 2003 |
| Attribution | Iowa Department of Transportation - Office of Systems Planning |
| Category | Transportation & Utilities |
| Tags | asset, classification, total aadt, passenger, single unit, combo unit, leg label, aadt, turning movement, traffic, iowa dot, iowa department of transportation |
| Created | 2016-09-29T19:01:09Z |
| Publication Date | 2016-09-29T19:02:48Z |

## Description

Iowa turning traffic data (AADT) for intersections on the primary, secondary and municipal roadway systems for 2003. The state is divided into 4 quadrants and each quadrant is counted every 4 years.

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
Value = 2003
Format & Zone = yyyy
```

## Data Commands

```ls
series e:swa5-edvy d:2003-01-01T00:00:00.000Z t:turning_movement_url=http://www.iowadotmaps.com/msp/traffic/turning_movements/2003/03342519099.pdf t:station=03342519099 t:objectid=1 m:row_number.swa5-edvy=1

series e:swa5-edvy d:2003-01-01T00:00:00.000Z t:turning_movement_url=http://www.iowadotmaps.com/msp/traffic/turning_movements/2003/03345483099.pdf t:station=03345483099 t:objectid=2 m:row_number.swa5-edvy=2

series e:swa5-edvy d:2003-01-01T00:00:00.000Z t:turning_movement_url=http://www.iowadotmaps.com/msp/traffic/turning_movements/2003/08131052099.pdf t:station=08131052099 t:objectid=3 m:row_number.swa5-edvy=3
```

## Meta Commands

```ls
metric m:row_number.swa5-edvy p:long l:"Row Number"

entity e:swa5-edvy l:"AADT Turning Traffic 2003" t:attribution="Iowa Department of Transportation - Office of Systems Planning" t:url=https://data.iowa.gov/api/views/swa5-edvy

property e:swa5-edvy t:meta.view v:id=swa5-edvy v:category="Transportation & Utilities" v:averageRating=0 v:name="AADT Turning Traffic 2003" v:attribution="Iowa Department of Transportation - Office of Systems Planning"

property e:swa5-edvy t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:swa5-edvy t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```

## Top Records

```ls
| station     | intersection_leg | total_aadt | passenger_aadt | single_unit_aadt | combo_unit_aadt | turning_movement_url                                                          | objectid | 
| =========== | ================ | ========== | ============== | ================ | =============== | ============================================================================= | ======== | 
| 03342519099 |                  |            |                |                  |                 | http://www.iowadotmaps.com/msp/traffic/turning_movements/2003/03342519099.pdf | 1        | 
| 03345483099 |                  |            |                |                  |                 | http://www.iowadotmaps.com/msp/traffic/turning_movements/2003/03345483099.pdf | 2        | 
| 08131052099 |                  |            |                |                  |                 | http://www.iowadotmaps.com/msp/traffic/turning_movements/2003/08131052099.pdf | 3        | 
| 08141501099 |                  |            |                |                  |                 | http://www.iowadotmaps.com/msp/traffic/turning_movements/2003/08141501099.pdf | 4        | 
| 08141701099 |                  |            |                |                  |                 | http://www.iowadotmaps.com/msp/traffic/turning_movements/2003/08141701099.pdf | 5        | 
| 08221781099 |                  |            |                |                  |                 | http://www.iowadotmaps.com/msp/traffic/turning_movements/2003/08221781099.pdf | 6        | 
| 08229017199 |                  |            |                |                  |                 | http://www.iowadotmaps.com/msp/traffic/turning_movements/2003/08229017199.pdf | 7        | 
| 08229017599 |                  |            |                |                  |                 | http://www.iowadotmaps.com/msp/traffic/turning_movements/2003/08229017599.pdf | 8        | 
| 08229401099 |                  |            |                |                  |                 | http://www.iowadotmaps.com/msp/traffic/turning_movements/2003/08229401099.pdf | 9        | 
| 08241701099 |                  |            |                |                  |                 | http://www.iowadotmaps.com/msp/traffic/turning_movements/2003/08241701099.pdf | 10       | 
```