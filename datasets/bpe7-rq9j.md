# AADT Turning Traffic 2008

## Dataset

* [Dataset URL](https://data.iowa.gov/api/views/bpe7-rq9j/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/aadt-turning-traffic-2008)
* [Metadata URL](https://data.iowa.gov/api/views/bpe7-rq9j)
* Id = bpe7-rq9j
* Name = AADT Turning Traffic 2008
* Attribution = Iowa Department of Transportation - Office of Systems Planning
* Category = Transportation & Utilities
* Tags = [asset, classification, total aadt, passenger, single unit, combo unit, leg label, aadt, turning movement, traffic, iowa dot, iowa department of transportation]
* Created = 2016-09-29T18:51:26Z
* Publication Date = 2016-09-29T18:53:02Z
* Rows Updated = 2016-09-29T18:51:26Z

## Description

Iowa turning traffic data (AADT) for intersections on the primary, secondary and municipal roadway systems for 2008. The state is divided into 4 quadrants and each quadrant is counted every 4 years.

The Turning Movements application includes all AADT Turning Traffic data for years 1998-2015 and can be found on the Iowa DOT Interactive Map Portal: http://iowadot.maps.arcgis.com/apps/Viewer/index.html?appid=a29e44be6e314799b612335342a13f62

## Columns

```ls
| Name                 | Field Name           | Data Type | Render Type | Schema Type    | Included | 
| ==================== | ==================== | ========= | =========== | ============== | ======== | 
| updated_at           | :updated_at          | meta_data | meta_data   | time           | No       | 
| STATION              | station              | number    | text        | numeric metric | Yes      | 
| INTERSECTION_LEG     | intersection_leg     | number    | text        | numeric metric | Yes      | 
| TOTAL_AADT           | total_aadt           | number    | text        | numeric metric | Yes      | 
| PASSENGER_AADT       | passenger_aadt       | number    | text        | numeric metric | Yes      | 
| SINGLE_UNIT_AADT     | single_unit_aadt     | number    | text        | numeric metric | Yes      | 
| COMBO_UNIT_AADT      | combo_unit_aadt      | number    | text        | numeric metric | Yes      | 
| TURNING_MOVEMENT_URL | turning_movement_url | text      | text        | series tag     | Yes      | 
| OBJECTID             | objectid             | text      | number      | series tag     | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls
series e:bpe7-rq9j d:1970-01-01T00:00:00.000Z t:turning_movement_url=http://www.iowadotmaps.com/msp/traffic/turning_movements/2008/01114933099.pdf t:objectid=1 m:station=1114933099

series e:bpe7-rq9j d:1970-01-01T00:00:00.000Z t:turning_movement_url=http://www.iowadotmaps.com/msp/traffic/turning_movements/2008/01134917099.pdf t:objectid=2 m:station=1134917099

series e:bpe7-rq9j d:1970-01-01T00:00:00.000Z t:turning_movement_url=http://www.iowadotmaps.com/msp/traffic/turning_movements/2008/01134949099.pdf t:objectid=3 m:station=1134949099
```

## Meta Commands

```ls
metric m:station p:long l:STATION d:Station t:dataTypeName=number

metric m:intersection_leg l:INTERSECTION_LEG d:"Intersection Leg" t:dataTypeName=number

metric m:total_aadt l:TOTAL_AADT d:"Total AADT" t:dataTypeName=number

metric m:passenger_aadt l:PASSENGER_AADT d:"Passenger AADT" t:dataTypeName=number

metric m:single_unit_aadt l:SINGLE_UNIT_AADT d:"Single Unit AADT" t:dataTypeName=number

metric m:combo_unit_aadt l:COMBO_UNIT_AADT d:"Combo Unit AADT" t:dataTypeName=number

entity e:bpe7-rq9j l:"AADT Turning Traffic 2008" t:attribution="Iowa Department of Transportation - Office of Systems Planning" t:url=https://data.iowa.gov/api/views/bpe7-rq9j

property e:bpe7-rq9j t:meta.view d:2017-03-07T18:48:18.823Z v:id=bpe7-rq9j v:category="Transportation & Utilities" v:averageRating=0 v:name="AADT Turning Traffic 2008" v:attribution="Iowa Department of Transportation - Office of Systems Planning"

property e:bpe7-rq9j t:meta.view.owner d:2017-03-07T18:48:18.823Z v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"

property e:bpe7-rq9j t:meta.view.tableauthor d:2017-03-07T18:48:18.823Z v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```