# Motor Vehicle Crashes - Case Information: Three Year Window

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/motor-vehicle-crashes-case-information-beginning-2009) |
| Metadata | [Link](https://data.ny.gov/api/views/e8ky-4vqe) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/e8ky-4vqe/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/e8ky-4vqe/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | e8ky-4vqe |
| Name | Motor Vehicle Crashes - Case Information: Three Year Window |
| Attribution | NYS Department of Motor Vehicles |
| Category | Transportation |
| Tags | crash, accident, fatalities |
| Created | 2013-05-28T19:01:41Z |
| Publication Date | 2015-08-10T20:01:37Z |

## Description

Attributes about each crash case which may consist of a single or multiple reports occurring during the year.

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                          | Data Type     | Render Type   |
| ======== | ============== | ============================= | ============================= | ============= | ============= |
| No       |                | year                          | Year                          | number        | number        |
| Yes      | series tag     | accident_descriptor           | Crash Descriptor              | text          | text          |
| Yes      | series tag     | time                          | Time                          | text          | text          |
| Yes      | time           | date                          | Date                          | calendar_date | calendar_date |
| No       |                | day_of_week                   | Day of Week                   | text          | text          |
| Yes      | series tag     | police_report                 | Police Report                 | text          | text          |
| Yes      | series tag     | lighting_conditions           | Lighting Conditions           | text          | text          |
| Yes      | series tag     | municipality                  | Municipality                  | text          | text          |
| Yes      | series tag     | collision_type_descriptor     | Collision Type Descriptor     | text          | text          |
| Yes      | series tag     | county_name                   | County Name                   | text          | text          |
| Yes      | series tag     | road_descriptor               | Road Descriptor               | text          | text          |
| Yes      | series tag     | weather_conditions            | Weather Conditions            | text          | text          |
| Yes      | series tag     | traffic_control_device        | Traffic Control Device        | text          | text          |
| Yes      | series tag     | road_surface_conditions       | Road Surface Conditions       | text          | text          |
| Yes      | series tag     | dot_reference_marker_location | DOT Reference Marker Location | text          | text          |
| Yes      | series tag     | pedestrian_bicyclist_action   | Pedestrian Bicyclist Action   | text          | text          |
| Yes      | series tag     | event_descriptor              | Event Descriptor              | text          | text          |
| Yes      | numeric metric | number_of_vehicles_involved   | Number of Vehicles Involved   | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = day_of_week,year
```

## Data Commands

```ls
series e:e8ky-4vqe d:2013-10-20T00:00:00.000Z t:time=15:15 t:collision_type_descriptor=OTHER t:lighting_conditions=Daylight t:police_report=Y t:event_descriptor="Bicyclist, Collision With" t:pedestrian_bicyclist_action=Unknown t:municipality=BRONX t:road_descriptor="Straight and Level" t:weather_conditions=Clear t:accident_descriptor="Injury Accident" t:county_name=BRONX t:road_surface_conditions=Dry t:traffic_control_device=None m:number_of_vehicles_involved=1

series e:e8ky-4vqe d:2013-04-14T00:00:00.000Z t:time=18:00 t:collision_type_descriptor="REAR END" t:lighting_conditions=Unknown t:police_report=N t:event_descriptor="Other Motor Vehicle, Collision With" t:pedestrian_bicyclist_action="Not Applicable" t:municipality=KINGS t:road_descriptor=Unknown t:weather_conditions=Unknown t:accident_descriptor="Injury Accident" t:county_name=KINGS t:road_surface_conditions=Unknown t:traffic_control_device=Unknown m:number_of_vehicles_involved=2

series e:e8ky-4vqe d:2012-11-10T00:00:00.000Z t:time=18:23 t:collision_type_descriptor=OTHER t:lighting_conditions="Dark-Road Unlighted" t:police_report=Y t:event_descriptor=Deer t:pedestrian_bicyclist_action="Not Applicable" t:municipality=ROME t:road_descriptor="Straight and Level" t:weather_conditions=Cloudy t:accident_descriptor="Property Damage Accident" t:county_name=ONEIDA t:road_surface_conditions=Dry t:traffic_control_device="No Passing Zone" m:number_of_vehicles_involved=1
```

## Meta Commands

```ls
metric m:number_of_vehicles_involved p:integer l:"Number of Vehicles Involved" d:"The reported number of vehicles in the crash" t:dataTypeName=number

entity e:e8ky-4vqe l:"Motor Vehicle Crashes - Case Information: Three Year Window" t:attribution="NYS Department of Motor Vehicles" t:url=https://data.ny.gov/api/views/e8ky-4vqe

property e:e8ky-4vqe t:meta.view v:id=e8ky-4vqe v:category=Transportation v:attributionLink=http://www.dmv.ny.gov/stats.htm v:averageRating=0 v:name="Motor Vehicle Crashes - Case Information: Three Year Window" v:attribution="NYS Department of Motor Vehicles"

property e:e8ky-4vqe t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:e8ky-4vqe t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:e8ky-4vqe t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| year | accident_descriptor      | time  | date                | day_of_week | police_report | lighting_conditions | municipality | collision_type_descriptor | county_name | road_descriptor    | weather_conditions | traffic_control_device | road_surface_conditions | dot_reference_marker_location | pedestrian_bicyclist_action | event_descriptor                    | number_of_vehicles_involved | 
| ==== | ======================== | ===== | =================== | =========== | ============= | =================== | ============ | ========================= | =========== | ================== | ================== | ====================== | ======================= | ============================= | =========================== | =================================== | =========================== | 
| 2013 | Injury Accident          | 15:15 | 2013-10-20T00:00:00 | Sunday      | Y             | Daylight            | BRONX        | OTHER                     | BRONX       | Straight and Level | Clear              | None                   | Dry                     |                               | Unknown                     | Bicyclist, Collision With           | 1                           | 
| 2013 | Injury Accident          | 18:00 | 2013-04-14T00:00:00 | Sunday      | N             | Unknown             | KINGS        | REAR END                  | KINGS       | Unknown            | Unknown            | Unknown                | Unknown                 |                               | Not Applicable              | Other Motor Vehicle, Collision With | 2                           | 
| 2012 | Property Damage Accident | 18:23 | 2012-11-10T00:00:00 | Saturday    | Y             | Dark-Road Unlighted | ROME         | OTHER                     | ONEIDA      | Straight and Level | Cloudy             | No Passing Zone        | Dry                     |                               | Not Applicable              | Deer                                | 1                           | 
| 2013 | Property Damage Accident | 22:21 | 2013-06-14T00:00:00 | Friday      | Y             | Dark-Road Unlighted | SCOTT        | OTHER                     | CORTLAND    | Straight and Grade | Clear              | None                   | Dry                     | 41 32033093                   | Not Applicable              | Deer                                | 1                           | 
| 2012 | Property Damage Accident | 18:25 | 2012-09-16T00:00:00 | Sunday      | Y             | Dusk                | LIVONIA      | OTHER                     | LIVINGSTON  | Straight and Grade | Clear              | None                   | Dry                     |                               | Not Applicable              | Animal, Collision With              | 1                           | 
| 2012 | Injury Accident          | 14:36 | 2012-04-22T00:00:00 | Sunday      | Y             | Daylight            | KINGS        | REAR END                  | KINGS       | Straight and Level | Clear              | None                   | Dry                     |                               | Not Applicable              | Other Motor Vehicle, Collision With | 2                           | 
| 2012 | Injury Accident          | 12:00 | 2012-06-03T00:00:00 | Sunday      | Y             | Daylight            | QUEENS       | OTHER                     | QUEENS      | Curve and Level    | Clear              | None                   | Dry                     |                               | Not Applicable              | Other*, Non-Collision               | 1                           | 
| 2013 | Injury Accident          | 17:51 | 2013-05-10T00:00:00 | Friday      | Y             | Daylight            | HERKIMER     | OTHER                     | HERKIMER    | Straight and Level | Clear              | None                   | Dry                     |                               | Other Actions in Roadway    | Other Pedestrian                    | 1                           | 
| 2012 | Injury Accident          | 16:47 | 2012-03-30T00:00:00 | Friday      | N             | Unknown             | QUEENS       | Unknown                   | QUEENS      | Unknown            | Unknown            | Unknown                | Unknown                 |                               | Not Applicable              | Other Motor Vehicle, Collision With | 2                           | 
| 2013 | Property Damage Accident | 22:23 | 2013-10-03T00:00:00 | Thursday    | Y             | Dark-Road Unlighted | STAFFORD     | OTHER                     | GENESEE     | Straight and Level | Rain               | None                   | Wet                     |                               | Not Applicable              | Deer                                | 1                           | 
```