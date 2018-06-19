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
series e:bbyy-e7gq d:2017-09-17T11:00:35.000Z t:station_name="Ridge Blvd & Howard St" t:status="In Service" m:docks_in_service=15 m:total_docks=15

series e:bbyy-e7gq d:2017-09-18T11:00:37.000Z t:station_name="Morgan St & 18th St" t:status="In Service" m:docks_in_service=15 m:total_docks=15

series e:bbyy-e7gq d:2017-09-18T11:00:37.000Z t:station_name="State St & 29th St" t:status="In Service" m:docks_in_service=15 m:total_docks=15
```

## Meta Commands

```ls
metric m:total_docks p:integer l:"Total Docks" d:"Total docks in the station. Each dock can accommodate one bicycle." t:dataTypeName=number

metric m:docks_in_service p:integer l:"Docks in Service" d:"Excludes docks taken out of service. Calculated as the number of docks reported as containing available bicycles or available to receive a returned bicycle, as of the time this dataset was refreshed." t:dataTypeName=number

entity e:bbyy-e7gq l:"Divvy Bicycle Stations" t:attribution="Alta Bicycle Share, Inc." t:url=https://data.cityofchicago.org/api/views/bbyy-e7gq

property e:bbyy-e7gq t:meta.view d:2017-09-25T07:25:33.869Z v:averageRating=0 v:name="Divvy Bicycle Stations" v:attribution="Alta Bicycle Share, Inc." v:attributionLink=http://divvybikes.com/stations/json v:id=bbyy-e7gq v:category=Transportation

property e:bbyy-e7gq t:meta.view.owner d:2017-09-25T07:25:33.869Z v:displayName="Jonathan Levy" v:lastNotificationSeenAt=1505253103 v:id=vewm-vupz v:screenName="Jonathan Levy"

property e:bbyy-e7gq t:meta.view.tableauthor d:2017-09-25T07:25:33.869Z v:displayName="Jonathan Levy" v:lastNotificationSeenAt=1505253103 v:roleName=administrator v:id=vewm-vupz v:screenName="Jonathan Levy"
```

## Top Records

```ls
| :updated_at | id  | station_name               | address                    | total_docks | docks_in_service | status     | latitude     | longitude     | 
| =========== | === | ========================== | ========================== | =========== | ================ | ========== | ============ | ============= | 
| 1505646035  | 514 | Ridge Blvd & Howard St     | Ridge Blvd & Howard St     | 15          | 15               | In Service | 42.019276    | -87.68452     | 
| 1505732437  | 14  | Morgan St & 18th St        | 962 W. 18th St             | 15          | 15               | In Service | 41.858086    | -87.651073    | 
| 1505732437  | 193 | State St & 29th St         | State St & 29th St         | 15          | 15               | In Service | 41.841707    | -87.626938    | 
| 1506078037  | 622 | California Ave & Cortez St | California Ave & Cortez St | 15          | 15               | In Service | 41.900363    | -87.696704    | 
| 1506078037  | 623 | Michigan Ave & 8th St      | Michigan Ave & 8th St      | 23          | 21               | In Service | 41.872773    | -87.623981    | 
| 1506078037  | 73  | Jefferson St & Monroe St   | 207 S. Jefferson St.       | 19          | 18               | In Service | 41.880422    | -87.642746    | 
| 1506164440  | 106 | State St & Pearson St      | State St & Pearson St      | 27          | 25               | In Service | 41.897448    | -87.628722    | 
| 1506164440  | 94  | Clark St & Armitage Ave    | Clark St & Armitage Ave    | 31          | 27               | In Service | 41.918306    | -87.636282    | 
| 1506250839  | 59  | Wabash Ave & Roosevelt Rd  | 1210 S. Wabash Ave.        | 23          | 22               | In Service | 41.867227    | -87.625961    | 
| 1506250839  | 6   | Dusable Harbor             | Dusable Harbor             | 39          | 35               | In Service | 41.885041992 | -87.612794539 | 
```