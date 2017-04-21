# AADT Turning Traffic 2006

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/aadt-turning-traffic-2006) |
| Metadata | [Link](https://data.iowa.gov/api/views/hpc6-nhr3) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/hpc6-nhr3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/hpc6-nhr3/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | hpc6-nhr3 |
| Name | AADT Turning Traffic 2006 |
| Attribution | Iowa Department of Transportation - Office of Systems Planning |
| Category | Transportation & Utilities |
| Tags | asset, classification, total aadt, passenger, single unit, combo unit, leg label, aadt, turning movement, traffic, iowa dot, iowa department of transportation |
| Created | 2016-09-29T18:55:22Z |
| Publication Date | 2016-09-29T18:57:06Z |

## Description

Iowa turning traffic data (AADT) for intersections on the primary, secondary and municipal roadway systems for 2006. The state is divided into 4 quadrants and each quadrant is counted every 4 years.

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
Value = 2006
Format & Zone = yyyy
```

## Data Commands

```ls
series e:hpc6-nhr3 d:2006-01-01T00:00:00.000Z t:turning_movement_url=http://www.iowadotmaps.com/msp/traffic/turning_movements/2006/04128848099.pdf t:station=04128848099 t:objectid=1 m:row_number.hpc6-nhr3=1

series e:hpc6-nhr3 d:2006-01-01T00:00:00.000Z t:turning_movement_url=http://www.iowadotmaps.com/msp/traffic/turning_movements/2006/04226557099.pdf t:station=04226557099 t:objectid=2 m:row_number.hpc6-nhr3=2

series e:hpc6-nhr3 d:2006-01-01T00:00:00.000Z t:turning_movement_url=http://www.iowadotmaps.com/msp/traffic/turning_movements/2006/04236501099.pdf t:station=04236501099 t:objectid=3 m:row_number.hpc6-nhr3=3
```

## Meta Commands

```ls
metric m:row_number.hpc6-nhr3 p:long l:"Row Number"

entity e:hpc6-nhr3 l:"AADT Turning Traffic 2006" t:attribution="Iowa Department of Transportation - Office of Systems Planning" t:url=https://data.iowa.gov/api/views/hpc6-nhr3

property e:hpc6-nhr3 t:meta.view v:id=hpc6-nhr3 v:category="Transportation & Utilities" v:averageRating=0 v:name="AADT Turning Traffic 2006" v:attribution="Iowa Department of Transportation - Office of Systems Planning"

property e:hpc6-nhr3 t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:hpc6-nhr3 t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```

## Top Records

```ls
| station     | intersection_leg | total_aadt | passenger_aadt | single_unit_aadt | combo_unit_aadt | turning_movement_url                                                          | objectid | 
| =========== | ================ | ========== | ============== | ================ | =============== | ============================================================================= | ======== | 
| 04128848099 |                  |            |                |                  |                 | http://www.iowadotmaps.com/msp/traffic/turning_movements/2006/04128848099.pdf | 1        | 
| 04226557099 |                  |            |                |                  |                 | http://www.iowadotmaps.com/msp/traffic/turning_movements/2006/04226557099.pdf | 2        | 
| 04236501099 |                  |            |                |                  |                 | http://www.iowadotmaps.com/msp/traffic/turning_movements/2006/04236501099.pdf | 3        | 
| 04245164099 |                  |            |                |                  |                 | http://www.iowadotmaps.com/msp/traffic/turning_movements/2006/04245164099.pdf | 4        | 
| 04312545099 |                  |            |                |                  |                 | http://www.iowadotmaps.com/msp/traffic/turning_movements/2006/04312545099.pdf | 5        | 
| 04320988099 |                  |            |                |                  |                 | http://www.iowadotmaps.com/msp/traffic/turning_movements/2006/04320988099.pdf | 6        | 
| 04320992099 |                  |            |                |                  |                 | http://www.iowadotmaps.com/msp/traffic/turning_movements/2006/04320992099.pdf | 7        | 
| 04321748099 |                  |            |                |                  |                 | http://www.iowadotmaps.com/msp/traffic/turning_movements/2006/04321748099.pdf | 8        | 
| 04330201099 |                  |            |                |                  |                 | http://www.iowadotmaps.com/msp/traffic/turning_movements/2006/04330201099.pdf | 9        | 
| 04330901099 |                  |            |                |                  |                 | http://www.iowadotmaps.com/msp/traffic/turning_movements/2006/04330901099.pdf | 10       | 
```