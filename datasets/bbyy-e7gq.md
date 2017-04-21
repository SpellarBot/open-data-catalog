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
series e:bbyy-e7gq d:2017-04-16T11:00:38.000Z t:station_name="Jeffery Blvd & 71st St" t:status="In Service" m:total_docks=11 m:docks_in_service=10

series e:bbyy-e7gq d:2017-04-18T11:00:35.000Z t:station_name="Wilton Ave & Diversey Pkwy" t:status="In Service" m:total_docks=27 m:docks_in_service=27

series e:bbyy-e7gq d:2017-04-18T11:00:35.000Z t:station_name="Morgan St & 18th St" t:status="In Service" m:total_docks=15 m:docks_in_service=15
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
| :updated_at | id  | station_name               | address                    | total_docks | docks_in_service | status     | latitude     | longitude     | 
| =========== | === | ========================== | ========================== | =========== | ================ | ========== | ============ | ============= | 
| 1492340438  | 11  | Jeffery Blvd & 71st St     | Jeffery Blvd & 71st St     | 11          | 10               | In Service | 41.766638237 | -87.576450114 | 
| 1492513235  | 13  | Wilton Ave & Diversey Pkwy | 2790 N.Wilton Ave          | 27          | 27               | In Service | 41.932418    | -87.652705    | 
| 1492513235  | 14  | Morgan St & 18th St        | 962 W. 18th St             | 15          | 15               | In Service | 41.858086    | -87.651073    | 
| 1492513235  | 532 | Austin Blvd & Lake St      | Austin Blvd & Lake St      | 15          | 15               | In Service | 41.887919    | -87.774446    | 
| 1492599640  | 163 | Damen Ave & Clybourn Ave   | Damen Ave & Clybourn Ave   | 15          | 14               | In Service | 41.931931    | -87.677856    | 
| 1483444838  | 12  | South Shore Dr & 71st St   | MLSW                       | 15          | 15               | In Service | 41.766409457 | -87.565687572 | 
| 1479988838  | 514 | Ridge Blvd & Howard St     | Ridge Blvd & Howard St     | 15          | 15               | In Service | 42.019276    | -87.68452     | 
| 1490526047  | 22  | May St & Taylor St         | 1134 W. Taylor St          | 15          | 15               | In Service | 41.8694821   | -87.6554864   | 
| 1491822040  | 74  | Kingsbury St & Erie St     | 511 W Erie                 | 23          | 23               | In Service | 41.893882    | -87.641711    | 
| 1491994837  | 253 | Clifton Ave & Lawrence Ave | Clifton Ave & Lawrence Ave | 15          | 15               | In Service | 41.968873    | -87.658857    | 
```