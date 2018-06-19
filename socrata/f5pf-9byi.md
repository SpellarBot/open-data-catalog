# Vehicle Restrictions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/vehicle-restrictions) |
| Metadata | [Link](https://data.sfgov.org/api/views/f5pf-9byi) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/f5pf-9byi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/f5pf-9byi/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | f5pf-9byi |
| Name | Vehicle Restrictions |
| Category | Transportation |
| Tags | vehicle restrictions |
| Created | 2016-08-18T20:48:42Z |
| Publication Date | 2016-11-07T22:14:25Z |

## Description

Location and attributes of streets with weight and/or interurban bus restrictions. This dataset is created through manual updates to individual restriction shapefiles. Merging of all restriction shapefiles into this final dataset completed periodically. The data is updated infrequently, twice a year at most.

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type | Render Type |
| ======== | =========== | ================== | ================== | ========= | =========== |
| Yes      | series tag  | object_id          | Object ID          | text      | number      |
| Yes      | series tag  | cnn_id             | CNN ID             | text      | number      |
| Yes      | series tag  | street_name        | Street Name        | text      | text        |
| Yes      | series tag  | street_type        | Street Type        | text      | text        |
| Yes      | series tag  | from_street        | From Street        | text      | text        |
| Yes      | series tag  | to_street          | To Street          | text      | text        |
| Yes      | series tag  | restriction_weight | Restriction Weight | text      | text        |
| Yes      | series tag  | restriction_other  | Restriction Other  | text      | text        |
| Yes      | time        | last_edited_date   | Last Edited Date   | date      | date        |
| No       |             | geom               | Geom               | line      | line        |
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
series e:f5pf-9byi d:2017-04-15T16:40:53.000Z t:street_name="EXECUTIVE PARK" t:object_id=119 t:cnn_id=5373201 t:street_type=BLVD m:row_number.f5pf-9byi=1

series e:f5pf-9byi d:2017-04-15T16:40:53.000Z t:street_name="EXECUTIVE PARK" t:object_id=120 t:cnn_id=5373101 t:street_type=BLVD m:row_number.f5pf-9byi=2

series e:f5pf-9byi d:2017-04-15T16:40:53.000Z t:street_name="VAN NESS" t:object_id=148 t:cnn_id=13173101 t:street_type=AVE m:row_number.f5pf-9byi=3
```

## Meta Commands

```ls
metric m:row_number.f5pf-9byi p:long l:"Row Number"

entity e:f5pf-9byi l:"Vehicle Restrictions" t:url=https://data.sfgov.org/api/views/f5pf-9byi

property e:f5pf-9byi t:meta.view v:id=f5pf-9byi v:category=Transportation v:averageRating=0 v:name="Vehicle Restrictions"

property e:f5pf-9byi t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:f5pf-9byi t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:f5pf-9byi t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| object_id | cnn_id   | street_name     | street_type | from_street | to_street | restriction_weight | restriction_other | last_edited_date | geom                                                                                                                                                                                                                                                                                                                                                                       | 
| ========= | ======== | =============== | =========== | =========== | ========= | ================== | ================= | ================ | ========================================================================================================================================================================================================================================================================================================================================================================== | 
| 119       | 5373201  | EXECUTIVE PARK  | BLVD        |             |           |                    |                   |                  | LINESTRING (-122.39262223122195 37.711277082616775, -122.39244266943749 37.71131516187355, -122.39106494287047 37.71124494725019, -122.39084908368507 37.711174712346136)                                                                                                                                                                                                  | 
| 120       | 5373101  | EXECUTIVE PARK  | BLVD        |             |           |                    |                   |                  | LINESTRING (-122.39262223122195 37.711277082616775, -122.39245072120926 37.711220213746365, -122.39107299525892 37.71114999831586, -122.39084908368507 37.711174712346136)                                                                                                                                                                                                 | 
| 148       | 13173101 | VAN NESS        | AVE         |             |           |                    |                   |                  | LINESTRING (-122.42512273999225 37.80415079200958, -122.42524417420707 37.80423095288545, -122.42539537453413 37.80497643056817, -122.42531178392917 37.80508284898121)                                                                                                                                                                                                    | 
| 149       | 13173201 | VAN NESS        | AVE         |             |           |                    |                   |                  | LINESTRING (-122.42512273999225 37.80415079200958, -122.42503911478329 37.80425704175859, -122.42519033691153 37.805002628720814, -122.42531178392917 37.80508284898121)                                                                                                                                                                                                   | 
| 150       | 13172101 | VAN NESS        | AVE         |             |           |                    |                   |                  | LINESTRING (-122.42493202306599 37.80321045356828, -122.42505504259921 37.803298438868666, -122.42520385508544 37.80403216257228, -122.42512273999225 37.80415079200958)                                                                                                                                                                                                   | 
| 155       | 8454101  | LOMBARD         | ST          |             |           |                    |                   |                  | LINESTRING (-122.42619326312384 37.80110040169061, -122.42629855318118 37.80102327965799, -122.42770804715306 37.80084445423912, -122.42783825207336 37.8008917014021)                                                                                                                                                                                                     | 
| 171       | 8702201  | MARINA          | BLVD        |             |           |                    |                   |                  | LINESTRING (-122.43381116560516 37.80504823349718, -122.43390323059518 37.80514182631988, -122.43538402430316 37.806077875415234, -122.43565967747848 37.80619638192118)                                                                                                                                                                                                   | 
| 172       | 8702101  | MARINA          | BLVD        |             |           |                    |                   |                  | LINESTRING (-122.43381116560516 37.80504823349718, -122.43397876102482 37.8050532936443, -122.43547110318389 37.80599664275103, -122.43565967747848 37.80619638192118)                                                                                                                                                                                                     | 
| 214       | 7832201  | KING            | ST          |             |           |                    |                   |                  | LINESTRING (-122.38960390706593 37.779866232647294, -122.38978236487381 37.779869903490166, -122.39067380941064 37.779169915724076, -122.39115410804064 37.778823465601185, -122.39180716949586 37.778249434284504, -122.39185373637395 37.778130644446264)                                                                                                                | 
| 266       | 19940000 | BAYSIDE VILLAGE | PL          |             |           |                    |                   |                  | LINESTRING (-122.3902433270553 37.785677826151954, -122.3896876078311 37.78523563755048, -122.38965505553206 37.78515308609559, -122.38971326253335 37.78506114268964, -122.38978179808136 37.784999371247174, -122.3897802557218 37.78493872259643, -122.38970156896167 37.784805087672645, -122.38973614668456 37.78472930161481, -122.39050585675216 37.78412673325473) | 
```