# NW 58th St Greenway at 22nd Ave NW Bike Counter

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nw-58th-st-greenway-at-22nd-ave-nw-bike-counter-ed9da) |
| Metadata | [Link](https://data.seattle.gov/api/views/47yq-6ugv) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/47yq-6ugv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/47yq-6ugv/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | 47yq-6ugv |
| Name | NW 58th St Greenway at 22nd Ave NW Bike Counter |
| Attribution | SDOT |
| Category | Transportation |
| Tags | seattle, bike, counts, sdot, monthly data, bicycle, pedestrian |
| Created | 2014-02-04T15:50:25Z |
| Publication Date | 2017-04-03T22:00:06Z |

## Description

The counters consist of two small tube sensors stretching across the street, which are attached to a small metal counting box made by Eco-Counter. The tubes only count people riding bikes. They are very accurate and designed to be used on greenways.

## Columns

```ls
| Included | Schema Type    | Field Name                               | Name                                     | Data Type     | Render Type   |
| ======== | ============== | ======================================== | ======================================== | ============= | ============= |
| Yes      | time           | date                                     | Date                                     | calendar_date | calendar_date |
| Yes      | numeric metric | nw_58th_st_greenway_st_22nd_ave_nw_total | NW 58th St Greenway st 22nd Ave NW Total | number        | number        |
| Yes      | numeric metric | east                                     | East                                     | number        | number        |
| Yes      | numeric metric | west                                     | West                                     | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:47yq-6ugv d:2014-01-01T00:00:00.000Z m:nw_58th_st_greenway_st_22nd_ave_nw_total=18 m:east=6 m:west=12

series e:47yq-6ugv d:2014-01-01T01:00:00.000Z m:nw_58th_st_greenway_st_22nd_ave_nw_total=6 m:east=3 m:west=3

series e:47yq-6ugv d:2014-01-01T02:00:00.000Z m:nw_58th_st_greenway_st_22nd_ave_nw_total=3 m:east=0 m:west=3
```

## Meta Commands

```ls
metric m:nw_58th_st_greenway_st_22nd_ave_nw_total p:integer l:"NW 58th St Greenway st 22nd Ave NW Total" t:dataTypeName=number

metric m:east p:integer l:East t:dataTypeName=number

metric m:west p:integer l:West t:dataTypeName=number

entity e:47yq-6ugv l:"NW 58th St Greenway at 22nd Ave NW Bike Counter" t:attribution=SDOT t:url=https://data.seattle.gov/api/views/47yq-6ugv

property e:47yq-6ugv t:meta.view v:id=47yq-6ugv v:category=Transportation v:averageRating=0 v:name="NW 58th St Greenway at 22nd Ave NW Bike Counter" v:attribution=SDOT

property e:47yq-6ugv t:meta.view.license v:name="Public Domain"

property e:47yq-6ugv t:meta.view.owner v:id=psms-jbhq v:profileImageUrlMedium=/api/users/psms-jbhq/profile_images/THUMB v:profileImageUrlLarge=/api/users/psms-jbhq/profile_images/LARGE v:screenName="Zuniga, Rafael" v:profileImageUrlSmall=/api/users/psms-jbhq/profile_images/TINY v:displayName="Zuniga, Rafael"

property e:47yq-6ugv t:meta.view.tableauthor v:id=psms-jbhq v:profileImageUrlMedium=/api/users/psms-jbhq/profile_images/THUMB v:profileImageUrlLarge=/api/users/psms-jbhq/profile_images/LARGE v:screenName="Zuniga, Rafael" v:profileImageUrlSmall=/api/users/psms-jbhq/profile_images/TINY v:roleName=publisher v:displayName="Zuniga, Rafael"
```

## Top Records

```ls
| date                | nw_58th_st_greenway_st_22nd_ave_nw_total | east | west | 
| =================== | ======================================== | ==== | ==== | 
| 2014-01-01T00:00:00 | 18                                       | 6    | 12   | 
| 2014-01-01T01:00:00 | 6                                        | 3    | 3    | 
| 2014-01-01T02:00:00 | 3                                        | 0    | 3    | 
| 2014-01-01T03:00:00 | 4                                        | 2    | 2    | 
| 2014-01-01T04:00:00 | 5                                        | 3    | 2    | 
| 2014-01-01T05:00:00 | 0                                        | 0    | 0    | 
| 2014-01-01T06:00:00 | 2                                        | 2    | 0    | 
| 2014-01-01T07:00:00 | 6                                        | 2    | 4    | 
| 2014-01-01T08:00:00 | 2                                        | 0    | 2    | 
| 2014-01-01T09:00:00 | 5                                        | 3    | 2    | 
```