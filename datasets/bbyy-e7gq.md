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
series e:bbyy-e7gq d:2017-05-23T11:00:36.000Z t:station_name="Ridge Blvd & Howard St" t:status="In Service" m:total_docks=15 m:docks_in_service=15

series e:bbyy-e7gq d:2017-05-26T11:00:44.000Z t:station_name="Loomis St & Archer Ave" t:status="In Service" m:total_docks=15 m:docks_in_service=15

series e:bbyy-e7gq d:2017-06-05T11:00:37.000Z t:station_name="Jeffery Blvd & 71st St" t:status="In Service" m:total_docks=11 m:docks_in_service=11
```

## Meta Commands

```ls
metric m:total_docks p:integer l:"Total Docks" d:"Total docks in the station. Each dock can accommodate one bicycle." t:dataTypeName=number

metric m:docks_in_service p:integer l:"Docks in Service" d:"Excludes docks taken out of service. Calculated as the number of docks reported as containing available bicycles or available to receive a returned bicycle, as of the time this dataset was refreshed." t:dataTypeName=number

entity e:bbyy-e7gq l:"Divvy Bicycle Stations" t:attribution="Alta Bicycle Share, Inc." t:url=https://data.cityofchicago.org/api/views/bbyy-e7gq

property e:bbyy-e7gq t:meta.view d:2017-06-09T13:54:12.070Z v:id=bbyy-e7gq v:category=Transportation v:attributionLink=http://divvybikes.com/stations/json v:averageRating=0 v:name="Divvy Bicycle Stations" v:attribution="Alta Bicycle Share, Inc."

property e:bbyy-e7gq t:meta.view.owner d:2017-06-09T13:54:12.070Z v:id=vewm-vupz v:screenName="Jonathan Levy" v:lastNotificationSeenAt=1496780786 v:displayName="Jonathan Levy"

property e:bbyy-e7gq t:meta.view.tableauthor d:2017-06-09T13:54:12.070Z v:id=vewm-vupz v:screenName="Jonathan Levy" v:roleName=administrator v:lastNotificationSeenAt=1496780786 v:displayName="Jonathan Levy"
```

## Top Records

```ls
| :updated_at | id  | station_name                  | address                       | total_docks | docks_in_service | status     | latitude     | longitude     | 
| =========== | === | ============================= | ============================= | =========== | ================ | ========== | ============ | ============= | 
| 1495537236  | 514 | Ridge Blvd & Howard St        | Ridge Blvd & Howard St        | 15          | 15               | In Service | 42.019276    | -87.68452     | 
| 1495796444  | 366 | Loomis St & Archer Ave        | Loomis St & Archer Ave        | 15          | 15               | In Service | 41.84163254  | -87.657434953 | 
| 1496660437  | 11  | Jeffery Blvd & 71st St        | Jeffery Blvd & 71st St        | 11          | 11               | In Service | 41.766638237 | -87.576450114 | 
| 1496833237  | 14  | Morgan St & 18th St           | 962 W. 18th St                | 15          | 14               | In Service | 41.858086    | -87.651073    | 
| 1497006043  | 106 | State St & Pearson St         | State St & Pearson St         | 27          | 26               | In Service | 41.897448    | -87.628722    | 
| 1497006043  | 532 | Austin Blvd & Lake St         | Austin Blvd & Lake St         | 15          | 14               | In Service | 41.887919    | -87.774446    | 
| 1495018833  | 429 | Cottage Grove Ave & 67th St   | Cottage Grove Ave & 67th St   | 11          | 11               | In Service | 41.773720952 | -87.60563486  | 
| 1495710033  | 435 | Kedzie Ave & Roosevelt Rd     | Kedzie Ave & Roosevelt Rd     | 15          | 14               | In Service | 41.866492782 | -87.706496176 | 
| 1496833237  | 214 | Damen Ave & Grand Ave         | Damen Ave & Grand Ave         | 23          | 23               | In Service | 41.89122     | -87.67686     | 
| 1496833237  | 319 | Greenview Ave & Diversey Pkwy | Greenview Ave & Diversey Pkwy | 15          | 15               | In Service | 41.932595    | -87.665939    | 
```