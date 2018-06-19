# Chicago Traffic Tracker - Congestion Estimates by Segments

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/chicago-traffic-tracker-congestion-estimates-by-segments-0b9d7) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/n4j6-wkkf) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/n4j6-wkkf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/n4j6-wkkf/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | n4j6-wkkf |
| Name | Chicago Traffic Tracker - Congestion Estimates by Segments |
| Attribution | City of Chicago |
| Category | Transportation |
| Tags | traffic, sustainability |
| Created | 2011-11-20T03:28:25Z |
| Publication Date | 2014-09-26T21:18:26Z |

## Description

This dataset contains the current estimated speed for about 1250 segments covering 300 miles of arterial roads. For a more detailed description, go to: http://bit.ly/Q9AZAD. 

The Chicago Traffic Tracker estimates traffic congestion on Chicago?s arterial streets (nonfreeway
streets) in real-time by continuously monitoring and analyzing GPS traces received from Chicago Transit Authority (CTA) buses. Two types of congestion estimates are produced every ten minutes: 1) by Traffic Segments and 2) by Traffic Regions or Zones. Congestion estimate by traffic segments gives the observed speed typically for one-half mile of a street in one direction of traffic.

Traffic Segment level congestion is available for about 300 miles of principal arterials. Congestion by Traffic Region gives the average traffic condition for all arterial street segments within a region. A traffic region is comprised of two or three community areas with comparable traffic patterns. 29 regions are created to cover the entire city (except O?Hare airport area).
This dataset contains the current estimated speed for about 1250 segments covering 300 miles of arterial roads.
There is much volatility in traffic segment speed. However, the congestion estimates for the traffic regions remain consistent for relatively longer period. Most volatility in arterial speed comes from the very nature of the arterials themselves. Due to a myriad of factors, including but not limited to frequent
intersections, traffic signals, transit movements, availability of alternative routes, crashes, short length of the segments, etc. speed on individual arterial segments can fluctuate from heavily congested to no congestion and back in a few minutes. The segment speed and traffic region congestion estimates
together may give a better understanding of the actual traffic conditions.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name            | Data Type | Render Type |
| ======== | ============== | =========== | =============== | ========= | =========== |
| No       | time           | :updated_at | updated_at      | meta_data | meta_data   |
| Yes      | series tag     | segmentid   | SEGMENTID       | text      | text        |
| Yes      | series tag     | street      | STREET          | text      | text        |
| Yes      | series tag     | direction   | DIRECTION       | text      | text        |
| Yes      | series tag     | fromst      | FROM_STREET     | text      | text        |
| Yes      | series tag     | tost        | TO_STREET       | text      | text        |
| Yes      | numeric metric | length      | LENGTH          | number    | text        |
| Yes      | series tag     | strheading  | STREET_HEADING  | text      | text        |
| Yes      | series tag     | comments    | COMMENTS        | text      | text        |
| Yes      | numeric metric | start_lon   | START_LONGITUDE | number    | text        |
| No       |                | lif_lat     | START_LATITUDE  | number    | text        |
| Yes      | numeric metric | lit_lon     | END_LONGITUDE   | number    | text        |
| No       |                | lit_lat     | END_LATITUDE    | number    | text        |
| Yes      | numeric metric | traffic     | CURRENT_SPEED   | number    | text        |
| Yes      | series tag     | last_updt   | LAST_UPDATED    | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = lif_lat,lit_lat
```

## Data Commands

```ls
series e:n4j6-wkkf d:2017-04-21T07:34:10.000Z t:direction=EB t:street=Garfield t:fromst=Racine t:strheading=W t:tost=Halsted t:last_updt="2017-04-21 02:20:36.0" t:segmentid=8 m:traffic=-1 m:length=0.5 m:start_lon=-87.6548756951 m:lit_lon=-87.6451618298

series e:n4j6-wkkf d:2017-04-21T07:34:10.000Z t:direction=NB t:street=Pulaski t:fromst=Grand t:strheading=N t:tost="North Ave" t:last_updt="2017-04-21 02:20:36.0" t:segmentid=47 m:traffic=16 m:length=0.5 m:start_lon=-87.7262240305 m:lit_lon=-87.7261823777

series e:n4j6-wkkf d:2017-04-21T07:34:10.000Z t:direction=WB t:street=Roosevelt t:fromst=Kedzie t:strheading=W t:tost="Central Park" t:last_updt="2017-04-21 02:20:37.0" t:segmentid=235 m:traffic=-1 m:length=0.5 m:start_lon=-87.7056678592 m:lit_lon=-87.7154194668
```

## Meta Commands

```ls
metric m:length p:double l:LENGTH d:"Length of the segment in miles." t:dataTypeName=number

metric m:start_lon p:double l:START_LONGITUDE d:"The longitude associated with the starting point of the segment in the direction of traffic flow. For two-way streets it is roughly at the middle of the half that the segment is representing. For one-way streets this is the street center line. The startin" t:dataTypeName=number

metric m:lit_lon p:double l:END_LONGITUDE t:dataTypeName=number

metric m:traffic p:integer l:CURRENT_SPEED t:dataTypeName=number

entity e:n4j6-wkkf l:"Chicago Traffic Tracker - Congestion Estimates by Segments" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/n4j6-wkkf

property e:n4j6-wkkf t:meta.view v:id=n4j6-wkkf v:category=Transportation v:attributionLink=http://www.chicagotraffictracker.com/ v:averageRating=100 v:name="Chicago Traffic Tracker - Congestion Estimates by Segments" v:attribution="City of Chicago"

property e:n4j6-wkkf t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:n4j6-wkkf t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| :updated_at | segmentid | street              | direction | fromst     | tost         | length | strheading | comments                                   | start_lon      | lif_lat       | lit_lon        | lit_lat       | traffic | last_updt             | 
| =========== | ========= | =================== | ========= | ========== | ============ | ====== | ========== | ========================================== | ============== | ============= | ============== | ============= | ======= | ===================== | 
| 1492760050  | 8         | Garfield            | EB        | Racine     | Halsted      | 0.5    | W          |                                            | -87.6548756951 | 41.7940346735 | -87.6451618298 | 41.7941646462 | -1      | 2017-04-21 02:20:36.0 | 
| 1492760050  | 47        | Pulaski             | NB        | Grand      | North Ave    | 0.5    | N          |                                            | -87.7262240305 | 41.9061550576 | -87.7261823777 | 41.9098857185 | 16      | 2017-04-21 02:20:36.0 | 
| 1492760050  | 235       | Roosevelt           | WB        | Kedzie     | Central Park | 0.5    | W          |                                            | -87.7056678592 | 41.8665425122 | -87.7154194668 | 41.8664270139 | -1      | 2017-04-21 02:20:37.0 | 
| 1492760050  | 342       | Western             | NB        | 51st       | 47th         | 0.5    | S          | Western Blvd Run Parallel on the East Side | -87.684040664  | 41.8011451454 | -87.6842419673 | 41.8084247143 | 26      | 2017-04-21 02:20:37.0 | 
| 1492760050  | 949       | Washington          | WB        | Western    | California   | 0.5    | W          |                                            | -87.686483181  | 41.8831334079 | -87.696333691  | 41.8830349349 | -1      | 2017-04-21 02:20:40.0 | 
| 1411741096  | 1002      | Touhy               | EB        | California | Western      | 0.48   | W          |                                            | -87.6997466265 | 42.0119763841 | -87.6902422854 | 42.0121628852 | -1      | 2011-10-28 11:50:50.0 | 
| 1492760050  | 693       | Dr Martin L King Jr | NB        | Garfield   | 51st         | 0.51   | S          |                                            | -87.615791142  | 41.7946755473 | -87.6159748727 | 41.8021096226 | -1      | 2017-04-21 02:20:38.0 | 
| 1411741096  | 1004      | Touhy               | EB        | Rogers     | Clark        | 0.41   | W          |                                            | -87.6826977229 | 42.0123768207 | -87.6746953394 | 42.0125192492 | -1      | 2010-07-21 14:51:08.0 | 
| 1411741096  | 1005      | Touhy               | EB        | Clark      | Sheridan     | 0.57   | W          |                                            | -87.6746953394 | 42.0125192492 | -87.6634484746 | 42.0127106157 | -1      | 2010-07-21 14:51:08.0 | 
| 1411741096  | 1006      | Touhy               | WB        | Mannheim   | I-90 Expy    | 0.98   | W          | outside city limits                        | -87.885791874  | 42.0097669164 | -87.9048826492 | 42.0090329667 | -1      | 2010-07-21 14:51:10.0 | 
```