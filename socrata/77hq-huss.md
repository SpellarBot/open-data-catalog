# Chicago Traffic Tracker - Historical Congestion Estimates by Segment

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/chicago-traffic-tracker-historical-congestion-estimates-by-segment-2fdbf) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/77hq-huss) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/77hq-huss/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/77hq-huss/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 77hq-huss |
| Name | Chicago Traffic Tracker - Historical Congestion Estimates by Segment |
| Attribution | City of Chicago |
| Category | Transportation |
| Tags | traffic, sustainability |
| Created | 2013-03-22T18:18:45Z |
| Publication Date | 2015-02-11T16:57:53Z |

## Description

This dataset contains the historical estimated congestion for  1270 traffic segments. The Chicago Traffic Tracker estimates traffic congestion on Chicago?s arterial streets (non-freeway streets) in real-time by continuously monitoring and analyzing GPS traces received from Chicago Transit Authority (CTA) buses. Two types of congestion estimates are produced every 10 minutes: 1) by Traffic Segments and 2) by Traffic Regions or Zones. Congestion estimates by traffic segments gives observed speed typically for one-half mile of a street in one direction of traffic. Traffic Segment level congestion is available for about 300 miles of principal arterials. Congestion by Traffic Region gives the average traffic condition for all arterial street segments within a region. A traffic region is comprised of two or three community areas with comparable traffic patterns. 29 regions are created to cover the entire city (except O?Hare airport area). There is much volatility in traffic segment speed. However, the congestion estimates for the traffic regions remain consistent for a relatively longer period. Most volatility in arterial speed comes from the very nature of the arterials themselves. Due to a myriad of factors, including but not limited to frequent intersections, traffic signals, transit movements, availability of alternative routes, crashes, short length of the segments, etc. Speed on individual arterial segments can fluctuate from heavily congested to no congestion and back in a few minutes. The segment speed and traffic region congestion estimates together may give a better understanding of the actual traffic conditions. Current estimates of traffic congestion by region are available at http://bit.ly/Vz3rIh.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name          | Data Type     | Render Type   |
| ======== | ============== | =========== | ============= | ============= | ============= |
| Yes      | time           | last_update | TIME          | calendar_date | calendar_date |
| Yes      | series tag     | segment_id  | SEGMENTID     | text          | number        |
| Yes      | numeric metric | bus_count   | BUS COUNT     | number        | number        |
| Yes      | numeric metric | msg_count   | MESSAGE COUNT | number        | number        |
| Yes      | numeric metric | traffic     | SPEED         | number        | number        |
| No       |                | id          | ID            | text          | text          |
```

## Time Field

```ls
Value = last_update
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = id
```

## Data Commands

```ls
series e:77hq-huss d:2013-01-16T23:50:32.000Z t:segment_id=116 m:msg_count=7 m:traffic=18 m:bus_count=2

series e:77hq-huss d:2013-02-24T23:50:32.000Z t:segment_id=54 m:msg_count=11 m:traffic=23 m:bus_count=2

series e:77hq-huss d:2013-02-17T23:50:32.000Z t:segment_id=597 m:msg_count=0 m:traffic=-1 m:bus_count=0
```

## Meta Commands

```ls
metric m:bus_count p:integer l:"BUS COUNT" d:"Number of buses providing a GPS feed used to estimate congestion." t:dataTypeName=number

metric m:msg_count p:integer l:"MESSAGE COUNT" d:"Number of GPS probes received(or used) for estimating the speed for that segment." t:dataTypeName=number

metric m:traffic p:integer l:SPEED d:"Real-time estimated speed in miles per hour. For congestion advisory and traffic maps, this value is compared to a 0-9, 10-20, and 21 & over scale to display heavy, medium, and free flow conditions for the traffic segment. Segments which has insufficien" t:dataTypeName=number

entity e:77hq-huss l:"Chicago Traffic Tracker - Historical Congestion Estimates by Segment" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/77hq-huss

property e:77hq-huss t:meta.view v:id=77hq-huss v:category=Transportation v:attributionLink=http://www.chicagotraffictracker.com/ v:averageRating=0 v:name="Chicago Traffic Tracker - Historical Congestion Estimates by Segment" v:attribution="City of Chicago"

property e:77hq-huss t:meta.view.owner v:id=3qqc-w7ag v:profileImageUrlMedium=/api/users/3qqc-w7ag/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qqc-w7ag/profile_images/LARGE v:screenName="Tom Schenk Jr" v:profileImageUrlSmall=/api/users/3qqc-w7ag/profile_images/TINY v:lastNotificationSeenAt=1491330280 v:displayName="Tom Schenk Jr"

property e:77hq-huss t:meta.view.tableauthor v:id=3qqc-w7ag v:profileImageUrlMedium=/api/users/3qqc-w7ag/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qqc-w7ag/profile_images/LARGE v:screenName="Tom Schenk Jr" v:profileImageUrlSmall=/api/users/3qqc-w7ag/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491330280 v:displayName="Tom Schenk Jr"
```

## Top Records

```ls
| last_update         | segment_id | bus_count | msg_count | traffic | id                                       | 
| =================== | ========== | ========= | ========= | ======= | ======================================== | 
| 2013-01-16T23:50:32 | 116        | 2         | 7         | 18      | a9b36413b0bd50d9cb8f53e32972ac6e4fa8d315 | 
| 2013-02-24T23:50:32 | 54         | 2         | 11        | 23      | 26b44d4117c8bae8791703afbe59c4f9f13a28be | 
| 2013-02-17T23:50:32 | 597        | 0         | 0         | -1      | 89a5fc3a547476a516385530060a9a147f51e0e4 | 
| 2013-02-23T23:50:32 | 363        | 1         | 4         | 25      | 6a9e4f5a26694e1615928dbc78d92daee4f26045 | 
| 2014-12-01T23:50:32 | 203        | 0         | 0         | -1      | 44cf8541a4c252d6f74519aed680aa2c0de7dda0 | 
| 2014-12-24T23:50:32 | 926        | 0         | 0         | -1      | a874a22b4e845557a93939841d03668036941ac1 | 
| 2014-12-05T23:50:32 | 1204       | 0         | 0         | -1      | d98225e5f9020a7b31a2efc0b5c6b04163adcdc1 | 
| 2014-12-11T23:50:32 | 634        | 0         | 0         | -1      | 37dcf1192ab2b29cfd482e41b2005015b8d01c35 | 
| 2014-12-24T23:50:32 | 55         | 1         | 8         | 18      | cc717fb4a6e6dc3904c85f30ab7ce36ce14a99cc | 
| 2014-12-01T23:50:32 | 1183       | 0         | 0         | -1      | 198d1720f48105e67a31657a7ce9003cd98bcff6 | 
```