# Parking Regulations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/parking-regulations) |
| Metadata | [Link](https://data.sfgov.org/api/views/2ehv-6arf) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/2ehv-6arf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/2ehv-6arf/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | 2ehv-6arf |
| Name | Parking Regulations |
| Category | Transportation |
| Tags | parking regulations |
| Created | 2016-04-14T20:35:34Z |
| Publication Date | 2016-04-20T22:19:08Z |

## Description

Parking regulations by blockface for the City of San Francisco. Includes the following regulations: Residential Parking Permits, Time limits, Government Permit, Metered, No overnight, Oversized Vehicle. Created through a mix of manual updates and data compilation. Updated as MTA Board resolutions are passed that impact parking regulations. Other critical information: This dataset has not been comprehesively updated. Dataset does not include color curb regulations such as loading zones or blue zones. Does not include detailed information for metered parking such as cap color or operating hours.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | series tag     | object_id        | Object ID        | text      | number      |
| Yes      | series tag     | regulation       | Regulation       | text      | text        |
| Yes      | series tag     | days             | Days             | text      | text        |
| Yes      | series tag     | hours            | Hours            | text      | text        |
| Yes      | numeric metric | hours_begin      | Hours Begin      | number    | number      |
| Yes      | numeric metric | hours_end        | Hours End        | number    | number      |
| Yes      | series tag     | rpp_area_1       | RPP Area 1       | text      | text        |
| Yes      | series tag     | rpp_area_2       | RPP Area 2       | text      | text        |
| Yes      | series tag     | rpp_area_3       | RPP Area 3       | text      | text        |
| Yes      | numeric metric | hour_limit       | Hour Limit       | number    | number      |
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
series e:2ehv-6arf d:2016-10-21T00:00:00.000Z t:days=M-F t:hours=900-1800 t:rpp_area_1=N t:object_id=1 t:regulation=RPP m:hours_begin=900 m:hour_limit=2 m:hours_end=1800

series e:2ehv-6arf d:2016-10-21T00:00:00.000Z t:days=M-F t:hours=800-1800 t:rpp_area_1=E t:object_id=2 t:regulation=RPP m:hours_begin=800 m:hour_limit=1 m:hours_end=1800

series e:2ehv-6arf d:2016-10-21T00:00:00.000Z t:days=M-F t:hours=700-1800 t:rpp_area_1=D t:object_id=3 t:regulation=RPP m:hours_begin=700 m:hour_limit=2 m:hours_end=1800
```

## Meta Commands

```ls
metric m:hours_begin p:long l:"Hours Begin" t:dataTypeName=number

metric m:hours_end p:long l:"Hours End" t:dataTypeName=number

metric m:hour_limit p:long l:"Hour Limit" t:dataTypeName=number

entity e:2ehv-6arf l:"Parking Regulations" t:url=https://data.sfgov.org/api/views/2ehv-6arf

property e:2ehv-6arf t:meta.view v:id=2ehv-6arf v:category=Transportation v:averageRating=0 v:name="Parking Regulations"

property e:2ehv-6arf t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:2ehv-6arf t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:2ehv-6arf t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| object_id | regulation | days | hours    | hours_begin | hours_end | rpp_area_1 | rpp_area_2 | rpp_area_3 | hour_limit | last_edited_date | geom                                                                                                                                                                                                                                                 | 
| ========= | ========== | ==== | ======== | =========== | ========= | ========== | ========== | ========== | ========== | ================ | ==================================================================================================================================================================================================================================================== | 
| 1         | RPP        | M-F  | 900-1800 | 900         | 1800      | N          |            |            | 2          | 1477008000       | LINESTRING (-122.46135273132373 37.78675307823066, -122.46054784629841 37.786789477745)                                                                                                                                                              | 
| 2         | RPP        | M-F  | 800-1800 | 800         | 1800      | E          |            |            | 1          | 1477008000       | LINESTRING (-122.47678120578983 37.718031360733214, -122.47570155764237 37.7181446831003)                                                                                                                                                            | 
| 3         | RPP        | M-F  | 700-1800 | 700         | 1800      | D          |            |            | 2          | 1477008000       | LINESTRING (-122.43229408310665 37.73461764380936, -122.4318811558754 37.73466771698949)                                                                                                                                                             | 
| 4         | RPP        | M-Sa | 900-1800 | 900         | 1800      | I          | Z          |            | 2          | 1477008000       | LINESTRING (-122.42094963934966 37.75043799214984, -122.4206921382835 37.75045352403558)                                                                                                                                                             | 
| 5         | RPP        | M-F  | 800-1800 | 800         | 1800      | Z          |            |            | 2          | 1477008000       | LINESTRING (-122.42680570370699 37.74695999020145, -122.42492395529638 37.747075492860084)                                                                                                                                                           | 
| 6         | RPP        | M-F  | 800-1800 | 800         | 1800      | H          |            |            | 1          | 1477008000       | LINESTRING (-122.47335747092194 37.72459598719971, -122.47318128641355 37.72470450542054, -122.4730527399089 37.72476633505152, -122.4728875335491 37.724779380779296, -122.47273221190967 37.72477553487166, -122.47270987221148 37.72476904051233) | 
| 7         | RPP        | M-F  | 800-1800 | 800         | 1800      | M          |            |            | 2          | 1477008000       | LINESTRING (-122.43687867710125 37.80451323367086, -122.43547270164845 37.80469466746918)                                                                                                                                                            | 
| 8         | RPP        | M-F  | 800-1800 | 800         | 1800      | J          |            |            | 2          | 1477008000       | LINESTRING (-122.46401165103485 37.76050447743601, -122.46413023249255 37.76217866747121)                                                                                                                                                            | 
| 9         | RPP        | M-F  | 900-1800 | 900         | 1800      | N          |            |            | 2          | 1477008000       | LINESTRING (-122.47404511643145 37.782592052530525, -122.47418095279409 37.78426002042664)                                                                                                                                                           | 
| 10        | RPP        | M-F  | 800-1800 | 800         | 1800      | G          |            |            | 2          | 1477008000       | LINESTRING (-122.43282568629807 37.79260545791685, -122.43268663234582 37.79191724658408)                                                                                                                                                            | 
```