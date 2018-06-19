# CTA - List of CTA Datasets

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cta-list-of-cta-datasets-de795) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/pnau-cf66) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/pnau-cf66/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/pnau-cf66/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | pnau-cf66 |
| Name | CTA - List of CTA Datasets |
| Attribution | Chicago Transit Authority |
| Category | Transportation |
| Tags | cta, public transit, chicago transit authority |
| Created | 2011-08-12T00:02:54Z |
| Publication Date | 2014-06-23T19:39:13Z |

## Description

This lists datasets published by CTA in the City of Chicago Data Portal.

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type | Render Type |
| ======== | =========== | =========== | =========== | ========= | =========== |
| No       | time        | :updated_at | updated_at  | meta_data | meta_data   |
| Yes      | series tag  | link        | Link        | url       | url         |
| Yes      | series tag  | description | Description | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:pnau-cf66 d:2011-08-12T10:57:48.000Z t:description="Point data representing bus garage and facilities maintenance locations. To view or use these files, special GIS software, such as Google Earth, is required." t:link=http://data.cityofchicago.org/dataset/CTA-KML-Bus-Garage-Locations/t52q-6zfs m:row_number.pnau-cf66=1

series e:pnau-cf66 d:2011-08-12T10:58:06.000Z t:description="Lines representing approximately where the CTA 'L' (rail) lines are. To view or use these files, special GIS software, such as Google Earth, is required." t:link=http://data.cityofchicago.org/dataset/CTA-KML-L-Rail-Lines/m3d6-pubu m:row_number.pnau-cf66=2

series e:pnau-cf66 d:2011-08-12T10:58:26.000Z t:description="This dataset shows monthly averages, by day type (weekday, Saturday or Sunday/Holiday) and monthly totals for all CTA bus routes, back to 2001. See attached readme file for information on how these numbers are calculated." t:link=http://data.cityofchicago.org/dataset/CTA-Ridership-Bus-Routes-Monthly-Day-Type-Averages/bynn-gwxy m:row_number.pnau-cf66=3
```

## Meta Commands

```ls
metric m:row_number.pnau-cf66 p:long l:"Row Number"

entity e:pnau-cf66 l:"CTA - List of CTA Datasets" t:attribution="Chicago Transit Authority" t:url=https://data.cityofchicago.org/api/views/pnau-cf66

property e:pnau-cf66 t:meta.view v:id=pnau-cf66 v:category=Transportation v:attributionLink=http://www.transitchicago.com v:averageRating=0 v:name="CTA - List of CTA Datasets" v:attribution="Chicago Transit Authority"

property e:pnau-cf66 t:meta.view.owner v:id=6bsn-5494 v:profileImageUrlMedium=/api/users/6bsn-5494/profile_images/THUMB v:profileImageUrlLarge=/api/users/6bsn-5494/profile_images/LARGE v:screenName="cta web" v:profileImageUrlSmall=/api/users/6bsn-5494/profile_images/TINY v:displayName="cta web"

property e:pnau-cf66 t:meta.view.tableauthor v:id=6bsn-5494 v:profileImageUrlMedium=/api/users/6bsn-5494/profile_images/THUMB v:profileImageUrlLarge=/api/users/6bsn-5494/profile_images/LARGE v:screenName="cta web" v:profileImageUrlSmall=/api/users/6bsn-5494/profile_images/TINY v:roleName=designer v:displayName="cta web"
```

## Top Records

```ls
| :updated_at | link                                                                                                                                                                       | description                                                                                                                                                                                                                                                                                                                                                                                                                              | 
| =========== | ========================================================================================================================================================================== | ======================================================================================================================================================================================================================================================================================================================================================================================================================================== | 
| 1313146668  | [http://data.cityofchicago.org/dataset/CTA-KML-Bus-Garage-Locations/t52q-6zfs, KML - Bus Garage Locations]                                                                 | Point data representing bus garage and facilities maintenance locations. To view or use these files, special GIS software, such as Google Earth, is required.                                                                                                                                                                                                                                                                            | 
| 1313146686  | [http://data.cityofchicago.org/dataset/CTA-KML-L-Rail-Lines/m3d6-pubu, KML - 'L' (Rail) Lines]                                                                             | Lines representing approximately where the CTA 'L' (rail) lines are. To view or use these files, special GIS software, such as Google Earth, is required.                                                                                                                                                                                                                                                                                | 
| 1313146706  | [http://data.cityofchicago.org/dataset/CTA-Ridership-Bus-Routes-Monthly-Day-Type-Averages/bynn-gwxy, Ridership - Bus Routes - Monthly Day-Type Averages & Totals]          | This dataset shows monthly averages, by day type (weekday, Saturday or Sunday/Holiday) and monthly totals for all CTA bus routes, back to 2001. See attached readme file for information on how these numbers are calculated.                                                                                                                                                                                                            | 
| 1313146714  | [http://data.cityofchicago.org/dataset/CTA-Ridership-L-Stations-Daily-Totals/5neh-572f, Ridership - 'L' Station Entries - Daily Totals]                                    | This list shows daily totals of ridership, by station entry, for each 'L' station dating back to 2001. Dataset shows entries at all turnstiles, combined, for each station. Daytypes are as follows: W=Weekday, A=Saturday, U=Sunday/Holiday. See attached readme file for information on how these numbers are calculated.                                                                                                              | 
| 1313146717  | [http://data.cityofchicago.org/dataset/CTA-Ridership-L-Stations-Monthly-Day-Type-Averages/t2rn-p8d7, Ridership - 'L' Station Entries - Monthly Day-Type Averages & Totals] | This dataset lists monthly station entry averages, by day type (Weekday, Saturday or Sunday/Holiday), as well as monthly totals, beginning in 2001. Note that some stations (such as on the Cermak Branch--now Pink Line) and Skokie did not have Saturday and/or Sunday/holiday service until more recent years, although, in cases where weekday service ran past midnight, late evening fares may appear as part of Saturday tallies. | 
| 1313146672  | [http://data.cityofchicago.org/dataset/CTA-KML-Bus-Routes/atza-xq2n, KML - Bus Routes]                                                                                     | Line data representing CTA bus routes. To view or use these files, special GIS software, such as Google Earth, is required.                                                                                                                                                                                                                                                                                                              | 
| 1313146675  | [http://data.cityofchicago.org/dataset/CTA-KML-Bus-Stops/fxnt-b8ay, KML - Bus Stops]                                                                                       | Point data representing over 11,000 CTA bus stops. The Stop ID is used to get Bus Tracker information. Current stops (coded as 1 in status field), Flag Stops ? status 2, and stops both Temporarily in Service (Status 5) or Out of service (Status 6) are included. To view or use these files, special GIS software, such as Google Earth, is required.                                                                               | 
| 1313146679  | [http://data.cityofchicago.org/dataset/CTA-KML-Bus-Turnarounds/4rqm-6f79, KML - Bus Turnarounds]                                                                           | Point data representing locations of all bus turnarounds, including those that are not located at rail stations. To view or use these files, special GIS software, such as Google Earth, is required.                                                                                                                                                                                                                                    | 
| 1313146683  | [http://data.cityofchicago.org/dataset/CTA-KML-Fare-Media-Sales-Locations/uwhj-p95a, KML - Fare Media Sales Locations]                                                     | Point data representing sites that sell/vend CTA Fare Media. Details include location type (ex. rail station, store) type of media sold (ex. Visitor Pass, Chicago Card) and for many locations the form of payment accepted.                                                                                                                                                                                                            | 
| 1313146694  | [http://data.cityofchicago.org/dataset/CTA-List-of-Fare-Media-Sales-Outlets/73v3-mm4z, List of Fare Media Sales Outlets]                                                   | This list shows sales outlets that sell CTA fare media, including rail stations, currency exchanges and other retail outlets.                                                                                                                                                                                                                                                                                                            | 
```