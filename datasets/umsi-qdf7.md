# SDOT Bike Share Locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sdot-bike-share-locations) |
| Metadata | [Link](https://data.seattle.gov/api/views/umsi-qdf7) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/umsi-qdf7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/umsi-qdf7/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | umsi-qdf7 |
| Name | SDOT Bike Share Locations |
| Category | Transportation |
| Tags | sdot, bicycle, bike |
| Created | 2016-04-21T15:42:37Z |
| Publication Date | 2016-04-21T16:39:03Z |

## Description

Displays the location and attribute information for bike share facilities in the City of Seattle.

## Columns

```ls
| Included | Schema Type | Field Name            | Name                  | Data Type | Render Type |
| ======== | =========== | ===================== | ===================== | ========= | =========== |
| No       | time        | :updated_at           | updated_at            | meta_data | meta_data   |
| Yes      | series tag  | objectid              | OBJECTID              | text      | number      |
| Yes      | series tag  | site_id               | SITE_ID               | text      | text        |
| Yes      | series tag  | alta_site_number      | ALTA_SITE_NUMBER      | text      | text        |
| Yes      | series tag  | proposed_station_name | PROPOSED_STATION_NAME | text      | text        |
| Yes      | series tag  | sdot_permit_number    | SDOT_PERMIT_NUMBER    | text      | number      |
| Yes      | series tag  | dpd_permit_number     | DPD_PERMIT_NUMBER     | text      | text        |
| Yes      | series tag  | district              | DISTRICT              | text      | text        |
| Yes      | series tag  | planned               | PLANNED               | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:umsi-qdf7 d:2016-04-21T15:42:37.000Z t:sdot_permit_number=236449 t:site_id=1755-01 t:district="Central Business District" t:proposed_station_name="7th Ave & Union St" t:alta_site_number=CBD-03 t:objectid=1 t:planned=N m:row_number.umsi-qdf7=1

series e:umsi-qdf7 d:2016-04-21T15:42:37.000Z t:sdot_permit_number=236398 t:site_id=1691-02 t:district="Capital Hill" t:proposed_station_name="Summit Ave & E Denny Way" t:alta_site_number=CH-01 t:objectid=2 t:planned=N m:row_number.umsi-qdf7=2

series e:umsi-qdf7 d:2016-04-21T15:42:37.000Z t:sdot_permit_number=236432 t:site_id=1733-01 t:district="South Lake Union" t:proposed_station_name="McGraw Square / Westlake Ave & 6th Ave" t:alta_site_number=SLU-15 t:objectid=3 t:planned=N m:row_number.umsi-qdf7=3
```

## Meta Commands

```ls
metric m:row_number.umsi-qdf7 p:long l:"Row Number"

entity e:umsi-qdf7 l:"SDOT Bike Share Locations" t:url=https://data.seattle.gov/api/views/umsi-qdf7

property e:umsi-qdf7 t:meta.view v:id=umsi-qdf7 v:category=Transportation v:averageRating=0 v:name="SDOT Bike Share Locations"

property e:umsi-qdf7 t:meta.view.license v:name="Public Domain"

property e:umsi-qdf7 t:meta.view.owner v:id=geh9-fb2x v:screenName="SDOT GIS" v:displayName="SDOT GIS"

property e:umsi-qdf7 t:meta.view.tableauthor v:id=geh9-fb2x v:screenName="SDOT GIS" v:roleName=publisher v:displayName="SDOT GIS"
```

## Top Records

```ls
| :updated_at | objectid | site_id | alta_site_number | proposed_station_name                                | sdot_permit_number | dpd_permit_number | district                  | planned | 
| =========== | ======== | ======= | ================ | ==================================================== | ================== | ================= | ========================= | ======= | 
| 0           | 1        | 1755-01 | CBD-03           | 7th Ave & Union St                                   | 236449             |                   | Central Business District | N       | 
| 0           | 2        | 1691-02 | CH-01            | Summit Ave & E Denny Way                             | 236398             |                   | Capital Hill              | N       | 
| 0           | 3        | 1733-01 | SLU-15           | McGraw Square / Westlake Ave & 6th Ave               | 236432             |                   | South Lake Union          | N       | 
| 0           | 4        | 1729-02 | WF-01            | Pier 69 / Alaskan Way & Clay St                      | 236434             |                   | Waterfront                | N       | 
| 0           | 5        | 1688-03 | SLU-07           | 9th Ave & Westlake Ave                               | 236425             |                   | South Lake Union          | N       | 
| 0           | 6        | 1731-04 | BT-05            | 2nd Ave & Blanchard St                               | 236444             |                   | Belltown                  | N       | 
| 0           | 7        | 1311-01 | EL-05            | Eastlake Ave E & E Allison St                        | 236412             |                   | Eastlake                  | N       | 
| 0           | 8        | 1854-02 | PS-05            | King Street Station Plaza / 2nd Ave S & S Jackson St |                    | 6428105           | Pioneer Square            | N       | 
| 0           | 9        | 1642-04 | CH-03            | Summit Ave E & E Republican St                       | 236400             |                   | Capital Hill              | N       | 
| 0           | 10       | 1669-01 | CH-02            | E Harrison St & Broadway Ave E                       | 236399             |                   | Capital Hill              | N       | 
```