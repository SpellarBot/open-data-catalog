# Bike Share Stations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bike-share-stations) |
| Metadata | [Link](https://data.sfgov.org/api/views/gtyg-jpkj) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/gtyg-jpkj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/gtyg-jpkj/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | gtyg-jpkj |
| Name | Bike Share Stations |
| Attribution | SFTMA |
| Category | Transportation |
| Tags | bikes, sfmta |
| Created | 2016-04-28T16:46:11Z |
| Publication Date | 2016-05-21T00:02:28Z |

## Description

This dataset was created to show the locations of Bay Area Bike Share stations.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | series tag     | uid              | UID              | text      | number      |
| Yes      | series tag     | site_id          | Site ID          | text      | text        |
| Yes      | series tag     | station_location | Station Location | text      | text        |
| Yes      | series tag     | location_name    | Location Name    | text      | text        |
| Yes      | numeric metric | phase            | Phase            | number    | number      |
| Yes      | series tag     | station_id       | Station ID       | text      | number      |
| Yes      | time           | last_edited_date | Last Edited Date | date      | date        |
```

## Time Field

```ls
Value = last_edited_date
Format & Zone = seconds
```

## Data Commands

```ls
series e:gtyg-jpkj d:2016-05-23T00:00:00.000Z t:uid=1 t:location_name="Parking (metered)" t:station_location=On-Street t:site_id="SF-T24 S1" t:station_id=97 m:phase=1

series e:gtyg-jpkj d:2016-05-23T00:00:00.000Z t:uid=2 t:location_name="Parking (metered)" t:station_location=On-Street t:site_id="SF-G33 S1" t:station_id=36 m:phase=1

series e:gtyg-jpkj d:2016-05-23T00:00:00.000Z t:uid=3 t:location_name="Public -Temporary Transbay Terminal" t:station_location=Plaza t:site_id=SOMA-06A t:station_id=24 m:phase=0
```

## Meta Commands

```ls
metric m:phase p:integer l:Phase t:dataTypeName=number

entity e:gtyg-jpkj l:"Bike Share Stations" t:attribution=SFTMA t:url=https://data.sfgov.org/api/views/gtyg-jpkj

property e:gtyg-jpkj t:meta.view v:id=gtyg-jpkj v:category=Transportation v:averageRating=0 v:name="Bike Share Stations" v:attribution=SFTMA

property e:gtyg-jpkj t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:gtyg-jpkj t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:gtyg-jpkj t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| uid | site_id    | station_location | location_name                       | phase | station_id | last_edited_date | 
| === | ========== | ================ | =================================== | ===== | ========== | ================ | 
| 1   | SF-T24 S1  | On-Street        | Parking (metered)                   | 1     | 97         | 1463961600       | 
| 2   | SF-G33 S1  | On-Street        | Parking (metered)                   | 1     | 36         | 1463961600       | 
| 3   | SOMA-06A   | Plaza            | Public -Temporary Transbay Terminal | 0     | 24         | 1463961600       | 
| 4   | SF-T22 S5  | On-Street        | Parking (unmetered)                 | 1     | 95         | 1463961600       | 
| 5   | SF-R25 S4  | On-Street        | Parking (metered)                   | 1     | 87         | 1463961600       | 
| 6   | NOMA-2E    | On-Street        | Gray Meters                         | 0     | 35         | 1463961600       | 
| 7   | SF-L33 S4  | On-Street        | Parking (metered)                   | 1     | 53         | 1463961600       | 
| 8   | SF-O24 S4  | On-Street        | Parking (unmetered)                 | 1     | 66         | 1463961600       | 
| 9   | Market-03B | Sidewalk         | Public - Department of Public Works | 0     | 9          | 1463961600       | 
| 10  | SF-O28 S2  | On-Street        | Parking (unmetered)                 | 1     | 70         | 1463961600       | 
```