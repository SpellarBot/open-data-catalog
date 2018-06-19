# Chicago Traffic Tracker - Congestion Estimates by Regions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/chicago-traffic-tracker-congestion-estimates-by-regions-a7daf) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/t2qc-9pjd) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/t2qc-9pjd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/t2qc-9pjd/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | t2qc-9pjd |
| Name | Chicago Traffic Tracker - Congestion Estimates by Regions |
| Category | Transportation |
| Tags | traffic, sustainability |
| Created | 2011-11-20T03:43:27Z |
| Publication Date | 2014-09-12T20:08:47Z |

## Description

This dataset contains the current estimated congestion for the 29 traffic regions. For a detailed description, go to: http://bitly.com/TeqrNv. 

The Chicago Traffic Tracker estimates traffic congestion on Chicago?s arterial streets (non-freeway streets) in real-time by continuously monitoring and analyzing GPS traces received from Chicago Transit Authority (CTA) buses. Two types of congestion estimates are produced every 10 minutes: 1) by Traffic Segments and 2) by Traffic Regions or Zones. Congestion estimates by traffic segments gives observed speed typically for one-half mile of a street in one direction of traffic. Traffic Segment level congestion is available for about 300 miles of principal arterials. Congestion by Traffic Region gives the average traffic condition for all arterial street segments within a region. A traffic region is comprised of two or three community areas with comparable traffic patterns. 29 regions are created to cover the entire city (except O?Hare airport area). 

There is much volatility in traffic segment speed. However, the congestion estimates for the traffic regions remain consistent for a relatively longer period. Most volatility in arterial speed comes from the very nature of the arterials themselves. Due to a myriad of factors, including but not limited to frequent intersections, traffic signals, transit movements, availability of alternative routes, crashes, short length of the segments, etc. Speed on individual arterial segments can fluctuate from heavily congested to no congestion and back in a few minutes. The segment speed and traffic region congestion estimates together may give a better understanding of the actual traffic conditions.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| No       | time           | :updated_at   | updated_at    | meta_data | meta_data   |
| Yes      | series tag     | region        | REGION        | text      | text        |
| Yes      | series tag     | region_id     | REGION_ID     | text      | number      |
| Yes      | numeric metric | west          | WEST          | number    | number      |
| Yes      | numeric metric | east          | EAST          | number    | number      |
| Yes      | numeric metric | south         | SOUTH         | number    | number      |
| Yes      | numeric metric | north         | NORTH         | number    | number      |
| Yes      | series tag     | description   | DESCRIPTION   | text      | text        |
| Yes      | numeric metric | current_speed | CURRENT_SPEED | number    | number      |
| Yes      | series tag     | last_updt     | LAST_UPDATED  | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:t2qc-9pjd d:2017-04-21T09:18:25.000Z t:region="Irving Park-Avondale-North Ctr" t:description="Diversey to Montrose. Cicero to Ravenswood" t:region_id=6 t:last_updt="2017-04-21 04:10:23.0" m:south=41.931841 m:east=-87.67459 m:north=41.960669 m:current_speed=0 m:west=-87.747456

series e:t2qc-9pjd d:2017-04-21T09:18:25.000Z t:region="Lawndale N/S" t:description="Pershing to Roosevel. Cicero to Western" t:region_id=14 t:last_updt="2017-04-21 04:10:23.0" m:south=41.822792 m:east=-87.685372 m:north=41.866129 m:current_speed=0 m:west=-87.747456

series e:t2qc-9pjd d:2017-04-21T09:18:25.000Z t:region="South West Side" t:description="71st to Pershing. Cicero to Western" t:region_id=18 t:last_updt="2017-04-21 04:10:23.0" m:south=41.764066 m:east=-87.68373 m:north=41.822792 m:current_speed=0 m:west=-87.747456
```

## Meta Commands

```ls
metric m:west p:double l:WEST t:dataTypeName=number

metric m:east p:double l:EAST t:dataTypeName=number

metric m:south p:double l:SOUTH t:dataTypeName=number

metric m:north p:double l:NORTH t:dataTypeName=number

metric m:current_speed p:float l:CURRENT_SPEED t:dataTypeName=number

entity e:t2qc-9pjd l:"Chicago Traffic Tracker - Congestion Estimates by Regions" t:url=https://data.cityofchicago.org/api/views/t2qc-9pjd

property e:t2qc-9pjd t:meta.view v:id=t2qc-9pjd v:category=Transportation v:averageRating=0 v:name="Chicago Traffic Tracker - Congestion Estimates by Regions"

property e:t2qc-9pjd t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:t2qc-9pjd t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| :updated_at | region                            | region_id | west       | east       | south     | north     | description                                     | current_speed | last_updt             | 
| =========== | ================================= | ========= | ========== | ========== | ========= | ========= | =============================================== | ============= | ===================== | 
| 1492766305  | Irving Park-Avondale-North Ctr    | 6         | -87.747456 | -87.67459  | 41.931841 | 41.960669 | Diversey to Montrose. Cicero to Ravenswood      | 0             | 2017-04-21 04:10:23.0 | 
| 1492766305  | Lawndale N/S                      | 14        | -87.747456 | -87.685372 | 41.822792 | 41.866129 | Pershing to Roosevel. Cicero to Western         | 0             | 2017-04-21 04:10:23.0 | 
| 1492766305  | South West Side                   | 18        | -87.747456 | -87.68373  | 41.764066 | 41.822792 | 71st to Pershing. Cicero to Western             | 0             | 2017-04-21 04:10:23.0 | 
| 1492766305  | Edge Water-Uptown                 | 4         | -87.67459  | -87.646438 | 41.960669 | 41.997946 | Montrose to Devon. Ravenswood to Lake Shore     | 0             | 2017-04-21 04:10:23.0 | 
| 1492766305  | Near South-Douglas                | 16        | -87.636322 | -87.597952 | 41.822792 | 41.866129 | Pershing to Roosevelt. Stewart to Lake Shore    | 0             | 2017-04-21 04:10:23.0 | 
| 1492766305  | Lincoln Park-Lake View            | 8         | -87.67459  | -87.619112 | 41.910561 | 41.960669 | North Ave to Montrose. Ravenswood to Lake Shore | 0             | 2017-04-21 04:10:23.0 | 
| 1492766305  | Bridgeport-McKinley-Lower West    | 15        | -87.685372 | -87.636322 | 41.822792 | 41.866129 | Pershing to Roosevel. Western to Stewart        | 0             | 2017-04-21 04:10:23.0 | 
| 1492766305  | New City-Englewood-W Englewood    | 19        | -87.68373  | -87.636322 | 41.764066 | 41.822792 | 71st to Pershing. Western to Steward            | 0             | 2017-04-21 04:10:23.0 | 
| 1492766305  | Fuller-Grand Blvd-Washington Park | 20        | -87.636322 | -87.606334 | 41.764066 | 41.822792 | 71st to Pershing. Steward to Cottage Grove      | 0             | 2017-04-21 04:10:23.0 | 
| 1492766305  | Auburn Gresham-Chatham            | 23        | -87.67298  | -87.606334 | 41.728472 | 41.764066 | 91st to 71st. Damen to Cottage Grove            | 0             | 2017-04-21 04:10:23.0 | 
```