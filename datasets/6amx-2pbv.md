# Annual Average Daily Traffic (AADT): Beginning 1977

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/annual-average-daily-traffic-aadt-beginning-1977) |
| Metadata | [Link](https://data.ny.gov/api/views/6amx-2pbv) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/6amx-2pbv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/6amx-2pbv/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 6amx-2pbv |
| Name | Annual Average Daily Traffic (AADT): Beginning 1977 |
| Attribution | New York State Department of Transportation |
| Category | Transportation |
| Tags | aadt, adt, annual average daily traffic, traffic volume |
| Created | 2013-02-28T19:04:11Z |
| Publication Date | 2015-10-29T22:11:43Z |

## Description

Annual Average Daily Traffic (AADT) is an estimate of the average daily traffic along a defined segment of roadway. This value is calculated from short term counts taken along the same section which are then factored to produce the estimate of AADT. Because of this process, the most recent AADT for any given roadway will always be for the previous year. Data is available for all New York State Routes and roads that are part of the Federal Aid System.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name                      | Data Type | Render Type |
| ======== | ============== | =============== | ========================= | ========= | =========== |
| Yes      | series tag     | region          | Region                    | text      | number      |
| Yes      | series tag     | rc_id           | RC_ID                     | text      | text        |
| Yes      | series tag     | gis_code        | GIS Code                  | text      | text        |
| Yes      | series tag     | ramp            | Ramp                      | text      | text        |
| Yes      | numeric metric | begin_milepoint | Begin Milepoint           | number    | number      |
| Yes      | numeric metric | end_milepoint   | End Milepoint             | number    | number      |
| Yes      | series tag     | begin_desc      | Roadway Begin Description | text      | text        |
| Yes      | series tag     | end_desc        | Roadway End Description   | text      | text        |
| Yes      | series tag     | municipality    | Municipality              | text      | text        |
| Yes      | series tag     | signing         | Signing                   | text      | text        |
| Yes      | series tag     | route_number    | Route Number              | text      | text        |
| Yes      | series tag     | road_name       | Road Name                 | text      | text        |
| Yes      | time           | aadt_year       | Year                      | number    | text        |
| Yes      | numeric metric | aadt            | AADT                      | number    | number      |
| Yes      | series tag     | count_type      | Count Type                | text      | text        |
```

## Time Field

```ls
Value = aadt_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:6amx-2pbv d:1979-01-01T00:00:00.000Z t:begin_desc="WEST/PUTNAM CO LINE" t:route_number=9 t:region=8 t:rc_id=84_0059 t:count_type=ACTUAL t:end_desc="RT 403" t:signing=US t:municipality=PHILIPSTOWN t:gis_code=10051404 t:ramp=N m:end_milepoint=1.67 m:begin_milepoint=0 m:aadt=8410

series e:6amx-2pbv d:1995-01-01T00:00:00.000Z t:begin_desc="RT 9H" t:route_number=9 t:region=8 t:rc_id=81_0162 t:count_type=ACTUAL t:end_desc="COL/RENS CO LINE" t:signing=US t:municipality=KINDERHOOK t:gis_code=10051406 t:ramp=N m:end_milepoint=34.11 m:begin_milepoint=30.62 m:aadt=9930

series e:6amx-2pbv d:1979-01-01T00:00:00.000Z t:begin_desc="RT 303" t:route_number=9W t:region=8 t:rc_id=85_0004 t:count_type=ACTUAL t:end_desc="RT 304 HAVERSTRAW" t:signing=US t:municipality=CLARKSTOWN t:gis_code=10051301 t:ramp=N m:end_milepoint=13.38 m:begin_milepoint=12.78 m:aadt=9050
```

## Meta Commands

```ls
metric m:begin_milepoint p:float l:"Begin Milepoint" d:"The starting milepoint of the segment of roadway for which the AADT applies" t:dataTypeName=number

metric m:end_milepoint p:float l:"End Milepoint" d:"The ending milepoint of the segment of roadway for which the AADT applies" t:dataTypeName=number

metric m:aadt p:integer l:AADT d:"Annual Average Daily Traffic volume value: on any given day the average numbers of vehicles that pass the segment of roadway as described by the Begin/End Descriptions. These figures are based on an actual count taken for that year or statistically validated estimated and forecasted values" t:dataTypeName=number

entity e:6amx-2pbv l:"Annual Average Daily Traffic (AADT): Beginning 1977" t:attribution="New York State Department of Transportation" t:url=https://data.ny.gov/api/views/6amx-2pbv

property e:6amx-2pbv t:meta.view v:id=6amx-2pbv v:category=Transportation v:attributionLink=https://www.dot.ny.gov/highway-data-services v:averageRating=0 v:name="Annual Average Daily Traffic (AADT): Beginning 1977" v:attribution="New York State Department of Transportation"

property e:6amx-2pbv t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:6amx-2pbv t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:6amx-2pbv t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| region | rc_id   | gis_code | ramp | begin_milepoint | end_milepoint | begin_desc          | end_desc          | municipality | signing | route_number | road_name      | aadt_year | aadt  | count_type | 
| ====== | ======= | ======== | ==== | =============== | ============= | =================== | ================= | ============ | ======= | ============ | ============== | ========= | ===== | ========== | 
| 8      | 84_0059 | 10051404 | N    | 0               | 1.67          | WEST/PUTNAM CO LINE | RT 403            | PHILIPSTOWN  | US      | 9            |                | 1979      | 8410  | ACTUAL     | 
| 8      | 81_0162 | 10051406 | N    | 30.62           | 34.11         | RT 9H               | COL/RENS CO LINE  | KINDERHOOK   | US      | 9            |                | 1995      | 9930  | ACTUAL     | 
| 8      | 85_0004 | 10051301 | N    | 12.78           | 13.38         | RT 303              | RT 304 HAVERSTRAW | CLARKSTOWN   | US      | 9W           |                | 1979      | 9050  | ACTUAL     | 
| 10     | 07_8020 | 23626201 | N    | 6.75            | 6.84          | SR 110              | WLT WHITMAN RD    | HUNTINGTON   | COUNTY  |              | CR 3           | 2000      | 6800  | ACTUAL     | 
| 10     | 07_8270 | 23633801 | N    | 0               | 1.39          | SR 27               | SR 454            | ISLIP        | COUNTY  |              | CR 112         | 2004      | 13100 | ACTUAL     | 
| 10     | 03_1495 | 23225501 | N    | 0.38            | 0.86          | SUFFOLK ST          | FRONT ST          | FREEPORT     |         |              | WOODCLEFT AVE  | 2009      | 3375  | ACTUAL     | 
| 10     | 07_4141 | 24692101 | N    | 0               | 0.78          | ORINOCO DR          | SENECA DR         | ISLIP        |         |              | ASHAROKEN BLVD | 2013      | 444   | ACTUAL     | 
| 10     | 07_2687 | 24726501 | N    | 0               | 0.23          | TERRY RD            | DEAD END          | ISLIP        |         |              | CARRIE AVE     | 2014      | 86    | ACTUAL     | 
| 10     | 07_2904 | 25117301 | N    | 0               | 0.09          | LAKE AV             | END               | SMITHTOWN    |         |              | JAYNE CT       | 2014      | 104   | ACTUAL     | 
| 10     | 07_3201 | 27234101 | Y    | 0               | 0.19          | 908 M E/B (OFF)     | SYLVAN RD         | BABYLON      |         |              | NY231 AT 908M  | 2014      | 3385  | FORECAST   | 
```