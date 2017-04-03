# Divvy Bicycle Stations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/divvy-bicycle-stations-3353a) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/bbyy-e7gq) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/bbyy-e7gq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/bbyy-e7gq/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | bbyy-e7gq |
| Name | Divvy Bicycle Stations |
| Attribution | Alta Bicycle Share, Inc. |
| Category | Transportation |
| Tags | bicycling, sustainability, transportation |
| Created | 2013-07-18T21:57:41Z |
| Publication Date | 2015-12-21T21:33:36Z |

## Description

A list of the stations where one can pick up and return bicycles from the Divvy bicycle sharing system (http://divvybikes.com/).   This dataset contains all stations.  For a list of only those stations currently in service, see https://data.cityofchicago.org/d/67g3-8ig8. For real-time status of stations in machine-readable format, see http://divvybikes.com/stations/json.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| No       | time           | :updated_at      | updated_at       | meta_data | meta_data   |
| No       |                | id               | ID               | text      | number      |
| Yes      | series tag     | station_name     | Station Name     | text      | text        |
| No       |                | address          | Address          | text      | text        |
| Yes      | numeric metric | total_docks      | Total Docks      | number    | number      |
| Yes      | numeric metric | docks_in_service | Docks in Service | number    | number      |
| Yes      | series tag     | status           | Status           | text      | text        |
| No       |                | latitude         | Latitude         | number    | number      |
| No       |                | longitude        | Longitude        | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = id,address,latitude,longitude
```

## Data Commands

```ls
series e:bbyy-e7gq d:2017-02-20T12:00:36.000Z t:station_name="Wentworth Ave & 35th St" t:status="In Service" m:total_docks=15 m:docks_in_service=15

series e:bbyy-e7gq d:2017-03-01T12:00:34.000Z t:station_name="Jeffery Blvd & 71st St" t:status="In Service" m:total_docks=11 m:docks_in_service=11

series e:bbyy-e7gq d:2016-11-03T11:00:35.000Z t:station_name="Cicero Ave & Flournoy St" t:status="In Service" m:total_docks=15 m:docks_in_service=15
```

## Meta Commands

```ls
metric m:total_docks p:integer l:"Total Docks" d:"Total docks in the station. Each dock can accommodate one bicycle." t:dataTypeName=number

metric m:docks_in_service p:integer l:"Docks in Service" d:"Excludes docks taken out of service. Calculated as the number of docks reported as containing available bicycles or available to receive a returned bicycle, as of the time this dataset was refreshed." t:dataTypeName=number

entity e:bbyy-e7gq l:"Divvy Bicycle Stations" t:attribution="Alta Bicycle Share, Inc." t:url=https://data.cityofchicago.org/api/views/bbyy-e7gq

property e:bbyy-e7gq t:meta.view v:id=bbyy-e7gq v:category=Transportation v:attributionLink=http://divvybikes.com/stations/json v:averageRating=0 v:name="Divvy Bicycle Stations" v:attribution="Alta Bicycle Share, Inc."

property e:bbyy-e7gq t:meta.view.owner v:id=vewm-vupz v:screenName="Jonathan Levy" v:displayName="Jonathan Levy"

property e:bbyy-e7gq t:meta.view.tableauthor v:id=vewm-vupz v:screenName="Jonathan Levy" v:roleName=administrator v:displayName="Jonathan Levy"
```

## Top Records

```ls
| :updated_at | id  | station_name             | address                  | total_docks | docks_in_service | status     | latitude     | longitude     | 
| =========== | === | ======================== | ======================== | =========== | ================ | ========== | ============ | ============= | 
| 1487592036  | 405 | Wentworth Ave & 35th St  | Wentworth Ave & 35th St  | 15          | 15               | In Service | 41.830777    | -87.632504    | 
| 1488369634  | 11  | Jeffery Blvd & 71st St   | Jeffery Blvd & 71st St   | 11          | 11               | In Service | 41.766638237 | -87.576450114 | 
| 1478170835  | 538 | Cicero Ave & Flournoy St | Cicero Ave & Flournoy St | 15          | 15               | In Service | 41.872131    | -87.746619    | 
| 1483444838  | 12  | South Shore Dr & 71st St | MLSW                     | 15          | 15               | In Service | 41.766409457 | -87.565687572 | 
| 1488974435  | 15  | Racine Ave & 18th St     | 1726 S Racine Ave        | 15          | 15               | In Service | 41.858166    | -87.656495    | 
| 1489662040  | 532 | Austin Blvd & Lake St    | Austin Blvd & Lake St    | 15          | 15               | In Service | 41.887919    | -87.774446    | 
| 1479988838  | 514 | Ridge Blvd & Howard St   | Ridge Blvd & Howard St   | 15          | 15               | In Service | 42.019276    | -87.68452     | 
| 1490353233  | 163 | Damen Ave & Clybourn Ave | Damen Ave & Clybourn Ave | 15          | 15               | In Service | 41.931931    | -87.677856    | 
| 1490439637  | 16  | Paulina Ave & North Ave  | 1575 N Paulina Ave       | 15          | 14               | In Service | 41.910337    | -87.670072    | 
| 1490439637  | 180 | Ritchie Ct & Banks St    | Ritchie Ct & Banks St    | 15          | 15               | In Service | 41.906782    | -87.626402    | 
```