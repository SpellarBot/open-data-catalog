# Bike Counters

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bike-counters) |
| Metadata | [Link](https://data.sfgov.org/api/views/gda9-vxx4) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/gda9-vxx4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/gda9-vxx4/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | gda9-vxx4 |
| Name | Bike Counters |
| Category | Transportation |
| Tags | bike counters |
| Created | 2016-04-14T23:36:06Z |
| Publication Date | 2016-04-15T18:25:21Z |

## Description

This dataset is created to show the locations of bicycle loop counters in San Francisco. Updated quarterly.

## Columns

```ls
| Included | Schema Type | Field Name               | Name                     | Data Type | Render Type |
| ======== | =========== | ======================== | ======================== | ========= | =========== |
| Yes      | series tag  | object_id                | Object ID                | text      | number      |
| Yes      | series tag  | location                 | Location                 | text      | text        |
| Yes      | series tag  | route_type               | Route Type               | text      | text        |
| Yes      | series tag  | lane_width               | Lane Width               | text      | text        |
| Yes      | series tag  | street_width             | Street Width             | text      | text        |
| Yes      | series tag  | loop_detector_type       | Loop Detector Type       | text      | number      |
| Yes      | series tag  | status                   | Status                   | text      | text        |
| Yes      | series tag  | approximate_cross_street | Approximate Cross Street | text      | text        |
| Yes      | series tag  | pavement                 | Pavement                 | text      | text        |
| Yes      | series tag  | bike_facility_on_street  | Bike Facility On Street  | text      | text        |
| Yes      | series tag  | street_repaving_start    | Street Repaving Start    | text      | text        |
| Yes      | series tag  | street_repaving_end      | Street Repaving End      | text      | text        |
| Yes      | series tag  | counter_id               | Counter ID               | text      | text        |
| Yes      | series tag  | supervisor_district      | Supervisor District      | text      | number      |
| Yes      | series tag  | hardware_type            | Hardware Type            | text      | text        |
| Yes      | time        | last_edited_date         | Last Edited Date         | date      | date        |
```

## Time Field

```ls
Value = last_edited_date
Format & Zone = seconds
```

## Data Commands

```ls
series e:gda9-vxx4 d:2017-01-17T00:00:00.000Z t:location="Holloway Ave West of Stratford WB" t:object_id=1 m:row_number.gda9-vxx4=1

series e:gda9-vxx4 d:2017-01-17T00:00:00.000Z t:location="Marina Bike Path East of Baker St" t:object_id=2 m:row_number.gda9-vxx4=2

series e:gda9-vxx4 d:2017-01-17T00:00:00.000Z t:location="2nd Street North of Townsend NB" t:object_id=3 m:row_number.gda9-vxx4=3
```

## Meta Commands

```ls
metric m:row_number.gda9-vxx4 p:long l:"Row Number"

entity e:gda9-vxx4 l:"Bike Counters" t:url=https://data.sfgov.org/api/views/gda9-vxx4

property e:gda9-vxx4 t:meta.view v:id=gda9-vxx4 v:category=Transportation v:averageRating=0 v:name="Bike Counters"

property e:gda9-vxx4 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:gda9-vxx4 t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:gda9-vxx4 t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| object_id | location                           | route_type | lane_width | street_width | loop_detector_type | status | approximate_cross_street | pavement | bike_facility_on_street | street_repaving_start | street_repaving_end | counter_id | supervisor_district | hardware_type | last_edited_date | 
| ========= | ================================== | ========== | ========== | ============ | ================== | ====== | ======================== | ======== | ======================= | ===================== | =================== | ========== | =================== | ============= | ================ | 
| 1         | Holloway Ave West of Stratford WB  |            |            |              |                    |        |                          |          |                         |                       |                     |            |                     |               | 1484611200       | 
| 2         | Marina Bike Path East of Baker St  |            |            |              |                    |        |                          |          |                         |                       |                     |            |                     |               | 1484611200       | 
| 3         | 2nd Street North of Townsend NB    |            |            |              |                    |        |                          |          |                         |                       |                     |            |                     |               | 1484611200       | 
| 4         | Duboce Bike Path East of Church    |            |            |              |                    |        |                          |          |                         |                       |                     |            |                     |               | 1484611200       | 
| 5         | 11th St North of Folsom            |            |            |              |                    |        |                          |          |                         |                       |                     |            |                     |               | 1484611200       | 
| 6         | Folsom between 8th and 9th Sts. EB |            |            |              |                    |        |                          |          |                         |                       |                     |            |                     |               | 1484611200       | 
| 7         | Market St East of Castro EB        |            |            |              |                    |        |                          |          |                         |                       |                     |            |                     |               | 1484611200       | 
| 8         | Fulton St East of Webster St       |            |            |              |                    |        |                          |          |                         |                       |                     |            |                     |               | 1484611200       | 
| 9         | Townsend East of 5th               |            |            |              |                    |        |                          |          |                         |                       |                     |            |                     |               | 1484611200       | 
| 10        | JFK West of Conservatory Dr. West  |            |            |              |                    |        |                          |          |                         |                       |                     |            |                     |               | 1484611200       | 
```