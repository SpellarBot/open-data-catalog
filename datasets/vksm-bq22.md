# Speed Limits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/speed-limits) |
| Metadata | [Link](https://data.sfgov.org/api/views/vksm-bq22) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/vksm-bq22/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/vksm-bq22/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | vksm-bq22 |
| Name | Speed Limits |
| Category | Transportation |
| Tags | speed limits |
| Created | 2016-04-28T15:30:37Z |
| Publication Date | 2016-09-26T22:57:55Z |

## Description

Speed limits are indicated primarily for streets that have speeds higher than 25 MPH. 25 MPH is the de facto speed limit for residential and most commercial streets. Alleys narrower than 25 feet can have de facto speed limits of 15 MPH. Data is updated manually from separate files to produce this master. It is updated as changes are legislated, a few times a year.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | series tag     | object_id        | Object ID        | text      | number      |
| Yes      | series tag     | cnn_segment_id   | CNN Segment ID   | text      | number      |
| Yes      | series tag     | street_name      | Street Name      | text      | text        |
| Yes      | series tag     | street_type      | Street Type      | text      | text        |
| Yes      | series tag     | from_street      | From Street      | text      | text        |
| Yes      | series tag     | to_street        | To Street        | text      | text        |
| Yes      | numeric metric | speed_limit      | Speed Limit      | number    | number      |
| Yes      | time           | last_edited_date | Last Edited Date | date      | date        |
| No       |                | geom             | Geom             | line      | line        |
```

## Time Field

```ls
Value = last_edited_date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = geom
```

## Data Commands

```ls
series e:vksm-bq22 d:2017-02-04T17:55:04.000Z t:cnn_segment_id=3837000 t:street_name=CAYUGA t:object_id=1 t:street_type=AVE m:speed_limit=15

series e:vksm-bq22 d:2017-02-04T17:55:04.000Z t:cnn_segment_id=3835000 t:street_name=CAYUGA t:object_id=2 t:street_type=AVE m:speed_limit=15

series e:vksm-bq22 d:2017-02-04T17:55:04.000Z t:cnn_segment_id=3834000 t:street_name=CAYUGA t:object_id=3 t:street_type=AVE m:speed_limit=15
```

## Meta Commands

```ls
metric m:speed_limit p:long l:"Speed Limit" t:dataTypeName=number

entity e:vksm-bq22 l:"Speed Limits" t:url=https://data.sfgov.org/api/views/vksm-bq22

property e:vksm-bq22 t:meta.view v:id=vksm-bq22 v:category=Transportation v:averageRating=0 v:name="Speed Limits"

property e:vksm-bq22 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:vksm-bq22 t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:vksm-bq22 t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| object_id | cnn_segment_id | street_name | street_type | from_street | to_street | speed_limit | last_edited_date | geom                                                                                                                                                                                                                                                                                         | 
| ========= | ============== | =========== | =========== | =========== | ========= | =========== | ================ | ============================================================================================================================================================================================================================================================================================ | 
| 1         | 3837000        | CAYUGA      | AVE         |             |           | 15          |                  | LINESTRING (-122.44096027285825 37.72018929105033, -122.44141420138112 37.71987030057758)                                                                                                                                                                                                    | 
| 2         | 3835000        | CAYUGA      | AVE         |             |           | 15          |                  | LINESTRING (-122.44012245471575 37.72152164062292, -122.44048613103382 37.720938754346285)                                                                                                                                                                                                   | 
| 3         | 3834000        | CAYUGA      | AVE         |             |           | 15          |                  | LINESTRING (-122.43977785474799 37.72207394101123, -122.44012245471575 37.72152164062292)                                                                                                                                                                                                    | 
| 4         | 3833000        | CAYUGA      | AVE         |             |           | 15          |                  | LINESTRING (-122.43936328559869 37.722738371359476, -122.43977785474799 37.72207394101123)                                                                                                                                                                                                   | 
| 5         | 3838000        | CAYUGA      | AVE         |             |           | 15          |                  | LINESTRING (-122.44141420138112 37.71987030057758, -122.4425647461102 37.71962578642073)                                                                                                                                                                                                     | 
| 6         | 7695000        | JULES       | AVE         |             |           | 15          |                  | LINESTRING (-122.46126374212065 37.72364724987909, -122.46126918992091 37.72483946315335, -122.46122376317322 37.72495463821853)                                                                                                                                                             | 
| 7         | 8407000        | LISBON      | ST          |             |           | 15          |                  | LINESTRING (-122.43126661156322 37.72511151503524, -122.43244527232524 37.72355466328143)                                                                                                                                                                                                    | 
| 8         | 5394000        | FAIRFIELD   | WAY         |             |           | 15          |                  | LINESTRING (-122.46385710949683 37.72586742841704, -122.46340204778487 37.72658151038042, -122.46329419277338 37.72688898284537, -122.46326361165762 37.72713624210014, -122.4633193849344 37.727315771116295, -122.46346491582717 37.72755641288219, -122.46359101343037 37.72774038708121) | 
| 9         | 13010000       | UPLAND      | DR          |             |           | 15          |                  | LINESTRING (-122.46464578660016 37.7299775340121, -122.46496863780479 37.73007984169703, -122.46543328344403 37.73017319237489)                                                                                                                                                              | 
| 10        | 13011000       | UPLAND      | DR          |             |           | 15          |                  | LINESTRING (-122.46543328344403 37.73017319237489, -122.46627050175869 37.73033395899628)                                                                                                                                                                                                    | 
```