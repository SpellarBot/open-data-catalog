# ISTHA Illinois Tollway Traffic Volumes for 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/istha-illinois-tollway-traffic-volumes-for-2010-97c19) |
| Metadata | [Link](https://data.illinois.gov/api/views/ii2d-g8y2) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/ii2d-g8y2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/ii2d-g8y2/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | ii2d-g8y2 |
| Name | ISTHA Illinois Tollway Traffic Volumes for 2010 |
| Attribution | Individual or Organization |
| Category | Transportation |
| Tags | tollway, istha, traffic, aadt, adt, count, volume, 2010 |
| Created | 2011-07-21T19:30:46Z |
| Publication Date | 2012-01-26T15:53:24Z |

## Description

2010 Annual Average Daily Traffic (AADT) volumes as well as the AM and PM peak volumes for the Illinois Tollway. The beginning and ending milepost for each segment are provided as well as the coordinates for the center of each segment.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| Yes      | series tag     | route         | Route         | text      | number      |
| Yes      | series tag     | direction     | Direction     | text      | text        |
| Yes      | numeric metric | from_milepost | From Milepost | number    | number      |
| Yes      | numeric metric | to_milepost   | To Milepost   | number    | number      |
| Yes      | time           | year          | Year          | number    | text        |
| Yes      | series tag     | type          | Type          | text      | text        |
| Yes      | numeric metric | volume        | Volume        | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ii2d-g8y2 d:2010-01-01T00:00:00.000Z t:direction=E t:route=88 t:type=AADT m:from_milepost=44 m:to_milepost=44.54 m:volume=6450

series e:ii2d-g8y2 d:2010-01-01T00:00:00.000Z t:direction=E t:route=88 t:type=AADT m:from_milepost=44.54 m:to_milepost=53.974 m:volume=7030

series e:ii2d-g8y2 d:2010-01-01T00:00:00.000Z t:direction=E t:route=88 t:type=AADT m:from_milepost=53.974 m:to_milepost=54.409 m:volume=5710
```

## Meta Commands

```ls
metric m:from_milepost p:float l:"From Milepost" d:"Milepost for the beginning of the segment" t:dataTypeName=number

metric m:to_milepost p:float l:"To Milepost" d:"Milepost for the end of the segment" t:dataTypeName=number

metric m:volume p:integer l:Volume t:dataTypeName=number

entity e:ii2d-g8y2 l:"ISTHA Illinois Tollway Traffic Volumes for 2010" t:attribution="Individual or Organization" t:url=https://data.illinois.gov/api/views/ii2d-g8y2

property e:ii2d-g8y2 t:meta.view v:id=ii2d-g8y2 v:category=Transportation v:attributionLink=http://www.illinoistollway.com v:averageRating=0 v:name="ISTHA Illinois Tollway Traffic Volumes for 2010" v:attribution="Individual or Organization"

property e:ii2d-g8y2 t:meta.view.license v:name="Public Domain"

property e:ii2d-g8y2 t:meta.view.owner v:id=vtpi-ktes v:profileImageUrlMedium=/api/users/vtpi-ktes/profile_images/THUMB v:profileImageUrlLarge=/api/users/vtpi-ktes/profile_images/LARGE v:screenName=Brad v:profileImageUrlSmall=/api/users/vtpi-ktes/profile_images/TINY v:displayName=Brad

property e:ii2d-g8y2 t:meta.view.tableauthor v:id=vtpi-ktes v:profileImageUrlMedium=/api/users/vtpi-ktes/profile_images/THUMB v:profileImageUrlLarge=/api/users/vtpi-ktes/profile_images/LARGE v:screenName=Brad v:profileImageUrlSmall=/api/users/vtpi-ktes/profile_images/TINY v:roleName=publisher v:displayName=Brad
```

## Top Records

```ls
| route | direction | from_milepost      | to_milepost        | year | type | volume | 
| ===== | ========= | ================== | ================== | ==== | ==== | ====== | 
| 88    | E         | 44                 | 44.54              | 2010 | AADT | 6450   | 
| 88    | E         | 44.54              | 53.973999999999997 | 2010 | AADT | 7030   | 
| 88    | E         | 53.973999999999997 | 54.408999999999999 | 2010 | AADT | 5710   | 
| 88    | E         | 54.408999999999999 | 56.183             | 2010 | AADT | 7200   | 
| 88    | E         | 56.183             | 56.68              | 2010 | AADT | 5320   | 
| 88    | E         | 56.68              | 75.679000000000002 | 2010 | AADT | 7200   | 
| 88    | E         | 75.679000000000002 | 76.453000000000003 | 2010 | AADT | 6800   | 
| 88    | E         | 76.453000000000003 | 78.144999999999996 | 2010 | AADT | 8560   | 
| 88    | E         | 78.144999999999996 | 78.566999999999993 | 2010 | AADT | 8250   | 
| 88    | E         | 78.566999999999993 | 78.724999999999994 | 2010 | AADT | 10960  | 
```