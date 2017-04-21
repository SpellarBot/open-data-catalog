# Burke Gilman Trail north of NE 70th St Bike and Ped Counter

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/burke-gilman-trail-north-of-ne-70th-st-bike-and-ped-counter-aa37e) |
| Metadata | [Link](https://data.seattle.gov/api/views/2z5v-ecg8) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/2z5v-ecg8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/2z5v-ecg8/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | 2z5v-ecg8 |
| Name | Burke Gilman Trail north of NE 70th St Bike and Ped Counter |
| Attribution | SDOT |
| Category | Transportation |
| Tags | seattle, bike, counts, sdot, monthly data, bicycle, pedestrian |
| Created | 2014-02-04T16:15:56Z |
| Publication Date | 2017-04-03T21:53:00Z |

## Description

These sensors counts both people riding bikes and pedestrians. Separate volumes are tallied for each travel mode. Wires in a diamond formation in the concrete detect bikes and an infrared sensor mounted on a wooden post detects pedestrians. The counters also capture the direction of travel for both bikes and pedestrians.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type     | Render Type   |
| ======== | ============== | ========================== | ========================== | ============= | ============= |
| Yes      | time           | date                       | Date                       | calendar_date | calendar_date |
| Yes      | numeric metric | bgt_north_of_ne_70th_total | BGT North of NE 70th Total | number        | number        |
| Yes      | numeric metric | ped_south                  | Ped South                  | number        | number        |
| Yes      | numeric metric | ped_north                  | Ped North                  | number        | number        |
| Yes      | numeric metric | bike_north                 | Bike North                 | number        | number        |
| Yes      | numeric metric | bike_south                 | Bike South                 | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:2z5v-ecg8 d:2014-01-01T00:00:00.000Z m:bike_south=2 m:bgt_north_of_ne_70th_total=15 m:ped_south=0 m:ped_north=2 m:bike_north=11

series e:2z5v-ecg8 d:2014-01-01T01:00:00.000Z m:bike_south=1 m:bgt_north_of_ne_70th_total=9 m:ped_south=1 m:ped_north=0 m:bike_north=7

series e:2z5v-ecg8 d:2014-01-01T02:00:00.000Z m:bike_south=0 m:bgt_north_of_ne_70th_total=9 m:ped_south=0 m:ped_north=0 m:bike_north=9
```

## Meta Commands

```ls
metric m:bgt_north_of_ne_70th_total p:integer l:"BGT North of NE 70th Total" t:dataTypeName=number

metric m:ped_south p:integer l:"Ped South" t:dataTypeName=number

metric m:ped_north p:integer l:"Ped North" t:dataTypeName=number

metric m:bike_north p:integer l:"Bike North" t:dataTypeName=number

metric m:bike_south p:integer l:"Bike South" t:dataTypeName=number

entity e:2z5v-ecg8 l:"Burke Gilman Trail north of NE 70th St Bike and Ped Counter" t:attribution=SDOT t:url=https://data.seattle.gov/api/views/2z5v-ecg8

property e:2z5v-ecg8 t:meta.view v:id=2z5v-ecg8 v:category=Transportation v:averageRating=0 v:name="Burke Gilman Trail north of NE 70th St Bike and Ped Counter" v:attribution=SDOT

property e:2z5v-ecg8 t:meta.view.license v:name="Public Domain"

property e:2z5v-ecg8 t:meta.view.owner v:id=psms-jbhq v:profileImageUrlMedium=/api/users/psms-jbhq/profile_images/THUMB v:profileImageUrlLarge=/api/users/psms-jbhq/profile_images/LARGE v:screenName="Zuniga, Rafael" v:profileImageUrlSmall=/api/users/psms-jbhq/profile_images/TINY v:displayName="Zuniga, Rafael"

property e:2z5v-ecg8 t:meta.view.tableauthor v:id=psms-jbhq v:profileImageUrlMedium=/api/users/psms-jbhq/profile_images/THUMB v:profileImageUrlLarge=/api/users/psms-jbhq/profile_images/LARGE v:screenName="Zuniga, Rafael" v:profileImageUrlSmall=/api/users/psms-jbhq/profile_images/TINY v:roleName=publisher v:displayName="Zuniga, Rafael"
```

## Top Records

```ls
| date                | bgt_north_of_ne_70th_total | ped_south | ped_north | bike_north | bike_south | 
| =================== | ========================== | ========= | ========= | ========== | ========== | 
| 2014-01-01T00:00:00 | 15                         | 0         | 2         | 11         | 2          | 
| 2014-01-01T01:00:00 | 9                          | 1         | 0         | 7          | 1          | 
| 2014-01-01T02:00:00 | 9                          | 0         | 0         | 9          | 0          | 
| 2014-01-01T03:00:00 | 19                         | 0         | 0         | 19         | 0          | 
| 2014-01-01T04:00:00 | 19                         | 0         | 0         | 19         | 0          | 
| 2014-01-01T05:00:00 | 14                         | 0         | 0         | 14         | 0          | 
| 2014-01-01T06:00:00 | 10                         | 0         | 1         | 8          | 1          | 
| 2014-01-01T07:00:00 | 10                         | 2         | 3         | 1          | 4          | 
| 2014-01-01T08:00:00 | 27                         | 12        | 6         | 1          | 8          | 
| 2014-01-01T09:00:00 | 29                         | 5         | 14        | 2          | 8          | 
```