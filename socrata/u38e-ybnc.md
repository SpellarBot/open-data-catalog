# MTS Trail west of I-90 Bridge

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/mts-trail-west-of-i-90-bridge-572ae) |
| Metadata | [Link](https://data.seattle.gov/api/views/u38e-ybnc) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/u38e-ybnc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/u38e-ybnc/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | u38e-ybnc |
| Name | MTS Trail west of I-90 Bridge |
| Attribution | SDOT |
| Category | Transportation |
| Tags | seattle, bike, counts, sdot, monthly data, bicycle, pedestrian |
| Created | 2014-02-04T16:36:38Z |
| Publication Date | 2017-04-03T21:46:19Z |

## Description

These sensors counts both people riding bikes and pedestrians. Separate volumes are tallied for each travel mode. Wires in a diamond formation in the concrete detect bikes and an infrared sensor mounted on a wooden post detects pedestrians. The counters also capture the direction of travel for both bikes and pedestrians.

## Columns

```ls
| Included | Schema Type    | Field Name                          | Name                                | Data Type     | Render Type   |
| ======== | ============== | =================================== | =================================== | ============= | ============= |
| Yes      | time           | date                                | Date                                | calendar_date | calendar_date |
| Yes      | numeric metric | mts_trail_west_of_i_90_bridge_total | MTS Trail West of I-90 Bridge Total | number        | number        |
| Yes      | numeric metric | ped_north                           | Ped East                            | number        | number        |
| Yes      | numeric metric | ped_south                           | Ped West                            | number        | number        |
| Yes      | numeric metric | bike_north                          | Bike East                           | number        | number        |
| Yes      | numeric metric | bike_south                          | Bike West                           | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:u38e-ybnc d:2014-01-01T00:00:00.000Z m:bike_south=0 m:ped_south=1 m:ped_north=0 m:mts_trail_west_of_i_90_bridge_total=1 m:bike_north=0

series e:u38e-ybnc d:2014-01-01T01:00:00.000Z m:bike_south=0 m:ped_south=0 m:ped_north=0 m:mts_trail_west_of_i_90_bridge_total=0 m:bike_north=0

series e:u38e-ybnc d:2014-01-01T02:00:00.000Z m:bike_south=1 m:ped_south=2 m:ped_north=0 m:mts_trail_west_of_i_90_bridge_total=4 m:bike_north=1
```

## Meta Commands

```ls
metric m:mts_trail_west_of_i_90_bridge_total p:integer l:"MTS Trail West of I-90 Bridge Total" t:dataTypeName=number

metric m:ped_north p:integer l:"Ped East" t:dataTypeName=number

metric m:ped_south p:integer l:"Ped West" t:dataTypeName=number

metric m:bike_north p:integer l:"Bike East" t:dataTypeName=number

metric m:bike_south p:integer l:"Bike West" t:dataTypeName=number

entity e:u38e-ybnc l:"MTS Trail west of I-90 Bridge" t:attribution=SDOT t:url=https://data.seattle.gov/api/views/u38e-ybnc

property e:u38e-ybnc t:meta.view v:id=u38e-ybnc v:category=Transportation v:averageRating=0 v:name="MTS Trail west of I-90 Bridge" v:attribution=SDOT

property e:u38e-ybnc t:meta.view.license v:name="Public Domain"

property e:u38e-ybnc t:meta.view.owner v:id=psms-jbhq v:profileImageUrlMedium=/api/users/psms-jbhq/profile_images/THUMB v:profileImageUrlLarge=/api/users/psms-jbhq/profile_images/LARGE v:screenName="Zuniga, Rafael" v:profileImageUrlSmall=/api/users/psms-jbhq/profile_images/TINY v:displayName="Zuniga, Rafael"

property e:u38e-ybnc t:meta.view.tableauthor v:id=psms-jbhq v:profileImageUrlMedium=/api/users/psms-jbhq/profile_images/THUMB v:profileImageUrlLarge=/api/users/psms-jbhq/profile_images/LARGE v:screenName="Zuniga, Rafael" v:profileImageUrlSmall=/api/users/psms-jbhq/profile_images/TINY v:roleName=publisher v:displayName="Zuniga, Rafael"
```

## Top Records

```ls
| date                | mts_trail_west_of_i_90_bridge_total | ped_north | ped_south | bike_north | bike_south | 
| =================== | =================================== | ========= | ========= | ========== | ========== | 
| 2014-01-01T00:00:00 | 1                                   | 0         | 1         | 0          | 0          | 
| 2014-01-01T01:00:00 | 0                                   | 0         | 0         | 0          | 0          | 
| 2014-01-01T02:00:00 | 4                                   | 0         | 2         | 1          | 1          | 
| 2014-01-01T03:00:00 | 1                                   | 0         | 1         | 0          | 0          | 
| 2014-01-01T04:00:00 | 1                                   | 0         | 0         | 1          | 0          | 
| 2014-01-01T05:00:00 | 2                                   | 0         | 1         | 0          | 1          | 
| 2014-01-01T06:00:00 | 1                                   | 0         | 0         | 0          | 1          | 
| 2014-01-01T07:00:00 | 1                                   | 0         | 0         | 0          | 1          | 
| 2014-01-01T08:00:00 | 14                                  | 0         | 0         | 6          | 8          | 
| 2014-01-01T09:00:00 | 35                                  | 5         | 3         | 11         | 16         | 
```