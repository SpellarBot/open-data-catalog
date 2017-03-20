# AADT Turning Traffic 2001

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/aadt-turning-traffic-2001) |
| Metadata | [Link](https://data.iowa.gov/api/views/8z8t-apms) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/8z8t-apms/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/8z8t-apms/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | 8z8t-apms |
| Name | AADT Turning Traffic 2001 |
| Attribution | Iowa Department of Transportation - Office of Systems Planning |
| Category | Transportation & Utilities |
| Tags | asset, classification, total aadt, passenger, single unit, combo unit, leg label, aadt, turning movement, traffic, iowa dot, iowa department of transportation |
| Created | 2016-09-29T19:04:42Z |
| Publication Date | 2016-09-29T19:06:02Z |
| Rows Updated | 2016-09-29T19:04:42Z |

## Description

Iowa turning traffic data (AADT) for intersections on the primary, secondary and municipal roadway systems for 2001. The state is divided into 4 quadrants and each quadrant is counted every 4 years.

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
series e:8z8t-apms d:2001-01-01T00:00:00.000Z t:turning_movement_url=http://www.iowadotmaps.com/msp/traffic/turning_movements/2001/03110233099.pdf t:station=03110233099 t:objectid=1 m:row_number.8z8t-apms=1

series e:8z8t-apms d:2001-01-01T00:00:00.000Z t:turning_movement_url=http://www.iowadotmaps.com/msp/traffic/turning_movements/2001/03110433099.pdf t:station=03110433099 t:objectid=2 m:row_number.8z8t-apms=2

series e:8z8t-apms d:2001-01-01T00:00:00.000Z t:turning_movement_url=http://www.iowadotmaps.com/msp/traffic/turning_movements/2001/03110633099.pdf t:station=03110633099 t:objectid=3 m:row_number.8z8t-apms=3
```

## Meta Commands

```ls
metric m:row_number.8z8t-apms p:long l:"Row Number"

entity e:8z8t-apms l:"AADT Turning Traffic 2001" t:attribution="Iowa Department of Transportation - Office of Systems Planning" t:url=https://data.iowa.gov/api/views/8z8t-apms

property e:8z8t-apms t:meta.view v:id=8z8t-apms v:category="Transportation & Utilities" v:averageRating=0 v:name="AADT Turning Traffic 2001" v:attribution="Iowa Department of Transportation - Office of Systems Planning"

property e:8z8t-apms t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"

property e:8z8t-apms t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```