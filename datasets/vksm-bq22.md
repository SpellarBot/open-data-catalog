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
| Rows Updated | 2017-02-04T17:56:59Z |

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

property e:vksm-bq22 t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData

property e:vksm-bq22 t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```