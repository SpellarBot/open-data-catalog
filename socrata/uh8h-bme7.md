# Chief Sealth Trail North of Thistle

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/chief-sealth-trail-north-of-thistle-a52dc) |
| Metadata | [Link](https://data.seattle.gov/api/views/uh8h-bme7) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/uh8h-bme7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/uh8h-bme7/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | uh8h-bme7 |
| Name | Chief Sealth Trail North of Thistle |
| Attribution | SDOT |
| Category | Transportation |
| Tags | seattle, bike, counts, sdot, monthly data, bicycle, pedestrian |
| Created | 2014-02-04T16:28:11Z |
| Publication Date | 2015-12-02T20:32:04Z |

## Description

These sensors counts both people riding bikes and pedestrians. Separate volumes are tallied for each travel mode. Wires in a diamond formation in the concrete detect bikes and an infrared sensor mounted on a wooden post detects pedestrians. The counters also capture the direction of travel for both bikes and pedestrians.

## Columns

```ls
| Included | Schema Type    | Field Name                              | Name                                    | Data Type     | Render Type   |
| ======== | ============== | ======================================= | ======================================= | ============= | ============= |
| Yes      | time           | date                                    | Date                                    | calendar_date | calendar_date |
| Yes      | numeric metric | chief_sealth_trl_north_of_thistle_total | Chief Sealth TRL North of Thistle Total | number        | number        |
| Yes      | numeric metric | ped_south                               | Ped South                               | number        | number        |
| Yes      | numeric metric | ped_north                               | Ped North                               | number        | number        |
| Yes      | numeric metric | bike_south                              | Bike South                              | number        | number        |
| Yes      | numeric metric | bike_north                              | Bike North                              | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:uh8h-bme7 d:2014-01-01T00:00:00.000Z m:bike_south=0 m:chief_sealth_trl_north_of_thistle_total=0 m:ped_south=0 m:ped_north=0 m:bike_north=0

series e:uh8h-bme7 d:2014-01-01T01:00:00.000Z m:bike_south=0 m:chief_sealth_trl_north_of_thistle_total=0 m:ped_south=0 m:ped_north=0 m:bike_north=0

series e:uh8h-bme7 d:2014-01-01T02:00:00.000Z m:bike_south=0 m:chief_sealth_trl_north_of_thistle_total=0 m:ped_south=0 m:ped_north=0 m:bike_north=0
```

## Meta Commands

```ls
metric m:chief_sealth_trl_north_of_thistle_total p:integer l:"Chief Sealth TRL North of Thistle Total" t:dataTypeName=number

metric m:ped_south p:integer l:"Ped South" t:dataTypeName=number

metric m:ped_north p:integer l:"Ped North" t:dataTypeName=number

metric m:bike_south p:integer l:"Bike South" t:dataTypeName=number

metric m:bike_north p:integer l:"Bike North" t:dataTypeName=number

entity e:uh8h-bme7 l:"Chief Sealth Trail North of Thistle" t:attribution=SDOT t:url=https://data.seattle.gov/api/views/uh8h-bme7

property e:uh8h-bme7 t:meta.view v:id=uh8h-bme7 v:category=Transportation v:averageRating=0 v:name="Chief Sealth Trail North of Thistle" v:attribution=SDOT

property e:uh8h-bme7 t:meta.view.license v:name="Public Domain"

property e:uh8h-bme7 t:meta.view.owner v:id=psms-jbhq v:profileImageUrlMedium=/api/users/psms-jbhq/profile_images/THUMB v:profileImageUrlLarge=/api/users/psms-jbhq/profile_images/LARGE v:screenName="Zuniga, Rafael" v:profileImageUrlSmall=/api/users/psms-jbhq/profile_images/TINY v:displayName="Zuniga, Rafael"

property e:uh8h-bme7 t:meta.view.tableauthor v:id=psms-jbhq v:profileImageUrlMedium=/api/users/psms-jbhq/profile_images/THUMB v:profileImageUrlLarge=/api/users/psms-jbhq/profile_images/LARGE v:screenName="Zuniga, Rafael" v:profileImageUrlSmall=/api/users/psms-jbhq/profile_images/TINY v:roleName=publisher v:displayName="Zuniga, Rafael"
```

## Top Records

```ls
| date                | chief_sealth_trl_north_of_thistle_total | ped_south | ped_north | bike_south | bike_north | 
| =================== | ======================================= | ========= | ========= | ========== | ========== | 
| 2014-01-01T00:00:00 | 0                                       | 0         | 0         | 0          | 0          | 
| 2014-01-01T01:00:00 | 0                                       | 0         | 0         | 0          | 0          | 
| 2014-01-01T02:00:00 | 0                                       | 0         | 0         | 0          | 0          | 
| 2014-01-01T03:00:00 | 2                                       | 1         | 1         | 0          | 0          | 
| 2014-01-01T04:00:00 | 0                                       | 0         | 0         | 0          | 0          | 
| 2014-01-01T05:00:00 | 0                                       | 0         | 0         | 0          | 0          | 
| 2014-01-01T06:00:00 | 0                                       | 0         | 0         | 0          | 0          | 
| 2014-01-01T07:00:00 | 2                                       | 1         | 1         | 0          | 0          | 
| 2014-01-01T08:00:00 | 3                                       | 1         | 2         | 0          | 0          | 
| 2014-01-01T09:00:00 | 3                                       | 1         | 2         | 0          | 0          | 
```