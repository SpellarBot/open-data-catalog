# Painted Safety Zones

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/painted-safety-zones) |
| Metadata | [Link](https://data.sfgov.org/api/views/gny2-eg9k) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/gny2-eg9k/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/gny2-eg9k/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | gny2-eg9k |
| Name | Painted Safety Zones |
| Attribution | City and County of San Francisco |
| Category | Transportation |
| Tags | painted safety zones |
| Created | 2016-08-18T20:43:07Z |
| Publication Date | 2016-10-12T00:48:30Z |

## Description

This dataset was created to show the locations of painted safety zones, many of which are implemented through the WalkFirst Investment Strategy.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | series tag     | object_id        | Object ID        | text      | number      |
| Yes      | series tag     | cnn_id           | CNN ID           | text      | number      |
| Yes      | series tag     | intersection     | Intersection     | text      | text        |
| Yes      | numeric metric | number_of_zones  | Number of Zones  | number    | number      |
| No       |                | install_date     | Install Date     | date      | date        |
| Yes      | time           | last_edited_date | Last Edited Date | date      | date        |
```

## Time Field

```ls
Value = last_edited_date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = install_date
```

## Data Commands

```ls
series e:gny2-eg9k d:2015-08-24T00:00:00.000Z t:intersection="2nd and South Park" t:object_id=1 t:cnn_id=24484000 m:number_of_zones=1

series e:gny2-eg9k d:2015-11-19T00:00:00.000Z t:intersection="McAllister and Webster" t:object_id=2 t:cnn_id=25967000 m:number_of_zones=0

series e:gny2-eg9k d:2015-08-24T00:00:00.000Z t:intersection="Geary and Polk" t:object_id=3 t:cnn_id=25182000 m:number_of_zones=1
```

## Meta Commands

```ls
metric m:number_of_zones p:integer l:"Number of Zones" t:dataTypeName=number

entity e:gny2-eg9k l:"Painted Safety Zones" t:attribution="City and County of San Francisco" t:url=https://data.sfgov.org/api/views/gny2-eg9k

property e:gny2-eg9k t:meta.view v:id=gny2-eg9k v:category=Transportation v:attributionLink=http://sfgov.org/ v:averageRating=0 v:name="Painted Safety Zones" v:attribution="City and County of San Francisco"

property e:gny2-eg9k t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:gny2-eg9k t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:gny2-eg9k t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| object_id | cnn_id   | intersection            | number_of_zones | install_date | last_edited_date | 
| ========= | ======== | ======================= | =============== | ============ | ================ | 
| 1         | 24484000 | 2nd and South Park      | 1               | 1435017600   | 1440374400       | 
| 2         | 25967000 | McAllister and Webster  | 0               |              | 1447891200       | 
| 3         | 25182000 | Geary and Polk          | 1               | 1427760000   | 1440374400       | 
| 4         | 26027000 | Scott and Oak           | 1               | 1448841600   | 1453161600       | 
| 5         | 24129000 | 19th and South Van Ness | 1               | 1436832000   | 1450828800       | 
| 6         | 24293000 | 6th St and Mission      | 3               | 1412035200   | 1440374400       | 
| 7         | 23871000 | 8th and Townsend        | 7               | 1428883200   | 1450828800       | 
| 8         | 30742000 | Market and 7th          | 1               | 1439164800   | 1440374400       | 
| 9         | 24083000 | 21st and South Van Ness | 2               | 1436832000   | 1450828800       | 
| 10        | 24305000 | 9th and Howard          | 1               | 1425081600   | 1440374400       | 
```