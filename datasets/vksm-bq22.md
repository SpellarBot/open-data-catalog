# Speed Limits

## Dataset

* [Dataset URL](https://data.sfgov.org/api/views/vksm-bq22/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/speed-limits)
* [Metadata URL](https://data.sfgov.org/api/views/vksm-bq22)
* Id = vksm-bq22
* Name = Speed Limits
* Category = Transportation
* Tags = [speed limits]
* Created = 2016-04-28T15:30:37Z
* Publication Date = 2016-09-26T22:57:55Z
* Rows Updated = 2017-02-04T17:56:59Z

## Description

Speed limits are indicated primarily for streets that have speeds higher than 25 MPH. 25 MPH is the de facto speed limit for residential and most commercial streets. Alleys narrower than 25 feet can have de facto speed limits of 15 MPH. Data is updated manually from separate files to produce this master. It is updated as changes are legislated, a few times a year.

## Columns

```ls
| Name             | Field Name       | Data Type | Render Type | Schema Type    | Included | 
| ================ | ================ | ========= | =========== | ============== | ======== | 
| Object ID        | object_id        | text      | number      | series tag     | Yes      | 
| CNN Segment ID   | cnn_segment_id   | text      | number      | series tag     | Yes      | 
| Street Name      | street_name      | text      | text        | series tag     | Yes      | 
| Street Type      | street_type      | text      | text        | series tag     | Yes      | 
| From Street      | from_street      | text      | text        | series tag     | Yes      | 
| To Street        | to_street        | text      | text        | series tag     | Yes      | 
| Speed Limit      | speed_limit      | number    | number      | numeric metric | Yes      | 
| Last Edited Date | last_edited_date | date      | date        | time           | Yes      | 
| Geom             | geom             | line      | line        | series tag     | Yes      | 
```

## Time Field

```ls
Value = last_edited_date
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls
series e:vksm-bq22 d:2017-03-08T01:11:54.250Z t:cnn_segment_id=3837000 t:street_name=CAYUGA t:object_id=1 t:geom="LINESTRING (-122.44096027285825 37.72018929105033, -122.44141420138112 37.71987030057758)" t:street_type=AVE m:speed_limit=15

series e:vksm-bq22 d:2017-03-08T01:11:54.250Z t:cnn_segment_id=3835000 t:street_name=CAYUGA t:object_id=2 t:geom="LINESTRING (-122.44012245471575 37.72152164062292, -122.44048613103382 37.720938754346285)" t:street_type=AVE m:speed_limit=15

series e:vksm-bq22 d:2017-03-08T01:11:54.250Z t:cnn_segment_id=3834000 t:street_name=CAYUGA t:object_id=3 t:geom="LINESTRING (-122.43977785474799 37.72207394101123, -122.44012245471575 37.72152164062292)" t:street_type=AVE m:speed_limit=15
```

## Meta Commands

```ls
metric m:speed_limit l:"Speed Limit" t:dataTypeName=number

entity e:vksm-bq22 l:"Speed Limits" t:url=https://data.sfgov.org/api/views/vksm-bq22

property e:vksm-bq22 t:meta.view d:2017-03-08T01:11:54.250Z v:id=vksm-bq22 v:category=Transportation v:averageRating=0 v:name="Speed Limits"

property e:vksm-bq22 t:meta.view.license d:2017-03-08T01:11:54.250Z v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:vksm-bq22 t:meta.view.owner d:2017-03-08T01:11:54.250Z v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData

property e:vksm-bq22 t:meta.view.tableauthor d:2017-03-08T01:11:54.250Z v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```