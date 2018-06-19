# Spokane St Bridge Counter

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/spokane-st-bridge-counter-356ae) |
| Metadata | [Link](https://data.seattle.gov/api/views/upms-nr8w) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/upms-nr8w/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/upms-nr8w/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | upms-nr8w |
| Name | Spokane St Bridge Counter |
| Attribution | SDOT |
| Category | Transportation |
| Created | 2014-02-04T16:57:57Z |
| Publication Date | 2017-04-03T21:42:23Z |

## Description

The Spokane Bridge Bicycle Counter records the number of bikes that cross the bridge using the pedestrian/bicycle pathway on the south side. Inductive loops on the pathway count the passing of bicycles with travel direction. The data consists of a date/time field, east pathway count field and west pathway count field. The count fields represent the total bicycles detected during the specified one hour period.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                     | Data Type     | Render Type   |
| ======== | ============== | ======================= | ======================== | ============= | ============= |
| Yes      | time           | date                    | Date                     | calendar_date | calendar_date |
| Yes      | numeric metric | spokane_st_bridge_total | Spokane St. Bridge Total | number        | number        |
| Yes      | numeric metric | west                    | West                     | number        | number        |
| Yes      | numeric metric | east                    | East                     | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:upms-nr8w d:2014-01-01T00:00:00.000Z m:spokane_st_bridge_total=0 m:east=0 m:west=0

series e:upms-nr8w d:2014-01-01T01:00:00.000Z m:spokane_st_bridge_total=3 m:east=0 m:west=3

series e:upms-nr8w d:2014-01-01T02:00:00.000Z m:spokane_st_bridge_total=6 m:east=1 m:west=5
```

## Meta Commands

```ls
metric m:spokane_st_bridge_total p:integer l:"Spokane St. Bridge Total" t:dataTypeName=number

metric m:west p:integer l:West t:dataTypeName=number

metric m:east p:integer l:East t:dataTypeName=number

entity e:upms-nr8w l:"Spokane St Bridge Counter" t:attribution=SDOT t:url=https://data.seattle.gov/api/views/upms-nr8w

property e:upms-nr8w t:meta.view v:id=upms-nr8w v:category=Transportation v:averageRating=0 v:name="Spokane St Bridge Counter" v:attribution=SDOT

property e:upms-nr8w t:meta.view.license v:name="Public Domain"

property e:upms-nr8w t:meta.view.owner v:id=psms-jbhq v:profileImageUrlMedium=/api/users/psms-jbhq/profile_images/THUMB v:profileImageUrlLarge=/api/users/psms-jbhq/profile_images/LARGE v:screenName="Zuniga, Rafael" v:profileImageUrlSmall=/api/users/psms-jbhq/profile_images/TINY v:displayName="Zuniga, Rafael"

property e:upms-nr8w t:meta.view.tableauthor v:id=psms-jbhq v:profileImageUrlMedium=/api/users/psms-jbhq/profile_images/THUMB v:profileImageUrlLarge=/api/users/psms-jbhq/profile_images/LARGE v:screenName="Zuniga, Rafael" v:profileImageUrlSmall=/api/users/psms-jbhq/profile_images/TINY v:roleName=publisher v:displayName="Zuniga, Rafael"
```

## Top Records

```ls
| date                | spokane_st_bridge_total | west | east | 
| =================== | ======================= | ==== | ==== | 
| 2014-01-01T00:00:00 | 0                       | 0    | 0    | 
| 2014-01-01T01:00:00 | 3                       | 3    | 0    | 
| 2014-01-01T02:00:00 | 6                       | 5    | 1    | 
| 2014-01-01T03:00:00 | 7                       | 6    | 1    | 
| 2014-01-01T04:00:00 | 0                       | 0    | 0    | 
| 2014-01-01T05:00:00 | 6                       | 5    | 1    | 
| 2014-01-01T06:00:00 | 1                       | 1    | 0    | 
| 2014-01-01T07:00:00 | 2                       | 0    | 2    | 
| 2014-01-01T08:00:00 | 7                       | 1    | 6    | 
| 2014-01-01T09:00:00 | 6                       | 2    | 4    | 
```