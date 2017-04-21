# Elliott Bay Trail in Myrtle Edwards Park

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/elliott-bay-trail-in-myrtle-edwards-park-4b186) |
| Metadata | [Link](https://data.seattle.gov/api/views/4qej-qvrz) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/4qej-qvrz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/4qej-qvrz/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | 4qej-qvrz |
| Name | Elliott Bay Trail in Myrtle Edwards Park |
| Attribution | SDOT |
| Category | Transportation |
| Tags | seattle, bike, counts, sdot, monthly data, bicycle, pedestrian |
| Created | 2014-02-04T16:34:12Z |
| Publication Date | 2017-04-03T21:48:58Z |

## Description

These sensors counts both people riding bikes and pedestrians. Separate volumes are tallied for each travel mode. Wires in a diamond formation in the concrete detect bikes and an infrared sensor mounted on a wooden post detects pedestrians. The counters also capture the direction of travel for both bikes and pedestrians.

## Columns

```ls
| Included | Schema Type    | Field Name                                      | Name                                           | Data Type     | Render Type   |
| ======== | ============== | =============================================== | ============================================== | ============= | ============= |
| Yes      | time           | date                                            | Date                                           | calendar_date | calendar_date |
| Yes      | numeric metric | eilliott_bay_trail_in_myrtle_edwards_park_total | Elliott Bay Trail in Myrtle Edwards Park Total | number        | number        |
| Yes      | numeric metric | ped_north                                       | Ped North                                      | number        | number        |
| Yes      | numeric metric | ped_south                                       | Ped South                                      | number        | number        |
| Yes      | numeric metric | bike_north                                      | Bike North                                     | number        | number        |
| Yes      | numeric metric | bike_south                                      | Bike South                                     | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:4qej-qvrz d:2014-01-01T00:00:00.000Z m:eilliott_bay_trail_in_myrtle_edwards_park_total=20 m:bike_south=3 m:ped_south=11 m:ped_north=5 m:bike_north=1

series e:4qej-qvrz d:2014-01-01T01:00:00.000Z m:eilliott_bay_trail_in_myrtle_edwards_park_total=7 m:bike_south=1 m:ped_south=3 m:ped_north=2 m:bike_north=1

series e:4qej-qvrz d:2014-01-01T02:00:00.000Z m:eilliott_bay_trail_in_myrtle_edwards_park_total=5 m:bike_south=1 m:ped_south=0 m:ped_north=1 m:bike_north=3
```

## Meta Commands

```ls
metric m:eilliott_bay_trail_in_myrtle_edwards_park_total p:integer l:"Elliott Bay Trail in Myrtle Edwards Park Total" t:dataTypeName=number

metric m:ped_north p:integer l:"Ped North" t:dataTypeName=number

metric m:ped_south p:integer l:"Ped South" t:dataTypeName=number

metric m:bike_north p:integer l:"Bike North" t:dataTypeName=number

metric m:bike_south p:integer l:"Bike South" t:dataTypeName=number

entity e:4qej-qvrz l:"Elliott Bay Trail in Myrtle Edwards Park" t:attribution=SDOT t:url=https://data.seattle.gov/api/views/4qej-qvrz

property e:4qej-qvrz t:meta.view v:id=4qej-qvrz v:category=Transportation v:averageRating=0 v:name="Elliott Bay Trail in Myrtle Edwards Park" v:attribution=SDOT

property e:4qej-qvrz t:meta.view.license v:name="Public Domain"

property e:4qej-qvrz t:meta.view.owner v:id=psms-jbhq v:profileImageUrlMedium=/api/users/psms-jbhq/profile_images/THUMB v:profileImageUrlLarge=/api/users/psms-jbhq/profile_images/LARGE v:screenName="Zuniga, Rafael" v:profileImageUrlSmall=/api/users/psms-jbhq/profile_images/TINY v:displayName="Zuniga, Rafael"

property e:4qej-qvrz t:meta.view.tableauthor v:id=psms-jbhq v:profileImageUrlMedium=/api/users/psms-jbhq/profile_images/THUMB v:profileImageUrlLarge=/api/users/psms-jbhq/profile_images/LARGE v:screenName="Zuniga, Rafael" v:profileImageUrlSmall=/api/users/psms-jbhq/profile_images/TINY v:roleName=publisher v:displayName="Zuniga, Rafael"
```

## Top Records

```ls
| date                | eilliott_bay_trail_in_myrtle_edwards_park_total | ped_north | ped_south | bike_north | bike_south | 
| =================== | =============================================== | ========= | ========= | ========== | ========== | 
| 2014-01-01T00:00:00 | 20                                              | 5         | 11        | 1          | 3          | 
| 2014-01-01T01:00:00 | 7                                               | 2         | 3         | 1          | 1          | 
| 2014-01-01T02:00:00 | 5                                               | 1         | 0         | 3          | 1          | 
| 2014-01-01T03:00:00 | 4                                               | 2         | 0         | 1          | 1          | 
| 2014-01-01T04:00:00 | 2                                               | 1         | 1         | 0          | 0          | 
| 2014-01-01T05:00:00 | 4                                               | 2         | 0         | 1          | 1          | 
| 2014-01-01T06:00:00 | 1                                               | 0         | 1         | 0          | 0          | 
| 2014-01-01T07:00:00 | 26                                              | 7         | 10        | 4          | 5          | 
| 2014-01-01T08:00:00 | 43                                              | 21        | 16        | 2          | 4          | 
| 2014-01-01T09:00:00 | 83                                              | 44        | 29        | 3          | 7          | 
```