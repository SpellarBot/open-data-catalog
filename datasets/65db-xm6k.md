# Fremont Bridge Hourly Bicycle Counts by Month October 2012 to present

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fremont-bridge-hourly-bicycle-counts-by-month-october-2012-to-present-f2f91) |
| Metadata | [Link](https://data.seattle.gov/api/views/65db-xm6k) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/65db-xm6k/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/65db-xm6k/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | 65db-xm6k |
| Name | Fremont Bridge Hourly Bicycle Counts by Month October 2012 to present |
| Attribution | Seattle Department of Transportation |
| Category | Transportation |
| Tags | bicycle, traffic, fremont, seattle, counts, bike counts, bike |
| Created | 2013-03-14T19:37:34Z |
| Publication Date | 2017-04-03T21:54:55Z |

## Description

The Fremont Bridge Bicycle Counter records the number of bikes that cross the bridge using the pedestrian/bicycle pathways. Inductive loops on the east and west pathways count the passing of bicycles regardless of travel direction. The data consists of a date/time field: Date, east pathway count field: Fremont Bridge NB,  and west pathway count field: Fremont Bridge SB. The count fields represent the total bicycles detected during the specified one hour period. Direction of travel is not specified, but in general most traffic in the Fremont Bridge NB field is travelling northbound and most traffic in the Fremont Bridge SB field is travelling southbound.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name                         | Data Type     | Render Type   |
| ======== | ============== | ================= | ============================ | ============= | ============= |
| Yes      | time           | date              | Date                         | calendar_date | calendar_date |
| Yes      | numeric metric | fremont_bridge_nb | Fremont Bridge West Sidewalk | number        | number        |
| Yes      | numeric metric | fremont_bridge_sb | Fremont Bridge East Sidewalk | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:65db-xm6k d:2012-10-03T00:00:00.000Z m:fremont_bridge_nb=4 m:fremont_bridge_sb=9

series e:65db-xm6k d:2012-10-03T01:00:00.000Z m:fremont_bridge_nb=4 m:fremont_bridge_sb=6

series e:65db-xm6k d:2012-10-03T02:00:00.000Z m:fremont_bridge_nb=1 m:fremont_bridge_sb=1
```

## Meta Commands

```ls
metric m:fremont_bridge_nb p:integer l:"Fremont Bridge West Sidewalk" t:dataTypeName=number

metric m:fremont_bridge_sb p:integer l:"Fremont Bridge East Sidewalk" t:dataTypeName=number

entity e:65db-xm6k l:"Fremont Bridge Hourly Bicycle Counts by Month October 2012 to present" t:attribution="Seattle Department of Transportation" t:url=https://data.seattle.gov/api/views/65db-xm6k

property e:65db-xm6k t:meta.view v:id=65db-xm6k v:category=Transportation v:averageRating=0 v:name="Fremont Bridge Hourly Bicycle Counts by Month October 2012 to present" v:attribution="Seattle Department of Transportation"

property e:65db-xm6k t:meta.view.license v:name="Public Domain"

property e:65db-xm6k t:meta.view.owner v:id=psms-jbhq v:profileImageUrlMedium=/api/users/psms-jbhq/profile_images/THUMB v:profileImageUrlLarge=/api/users/psms-jbhq/profile_images/LARGE v:screenName="Zuniga, Rafael" v:profileImageUrlSmall=/api/users/psms-jbhq/profile_images/TINY v:displayName="Zuniga, Rafael"

property e:65db-xm6k t:meta.view.tableauthor v:id=psms-jbhq v:profileImageUrlMedium=/api/users/psms-jbhq/profile_images/THUMB v:profileImageUrlLarge=/api/users/psms-jbhq/profile_images/LARGE v:screenName="Zuniga, Rafael" v:profileImageUrlSmall=/api/users/psms-jbhq/profile_images/TINY v:roleName=publisher v:displayName="Zuniga, Rafael"
```

## Top Records

```ls
| date                | fremont_bridge_nb | fremont_bridge_sb | 
| =================== | ================= | ================= | 
| 2012-10-03T00:00:00 | 4                 | 9                 | 
| 2012-10-03T01:00:00 | 4                 | 6                 | 
| 2012-10-03T02:00:00 | 1                 | 1                 | 
| 2012-10-03T03:00:00 | 2                 | 3                 | 
| 2012-10-03T04:00:00 | 6                 | 1                 | 
| 2012-10-03T05:00:00 | 21                | 10                | 
| 2012-10-03T06:00:00 | 105               | 50                | 
| 2012-10-03T07:00:00 | 257               | 95                | 
| 2012-10-03T08:00:00 | 291               | 146               | 
| 2012-10-03T09:00:00 | 172               | 104               | 
```