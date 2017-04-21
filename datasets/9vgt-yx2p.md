# Hydrostats

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hydrostats-91549) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/9vgt-yx2p) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/9vgt-yx2p/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/9vgt-yx2p/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 9vgt-yx2p |
| Name | Hydrostats |
| Attribution | Department of Environmental Protection (DEP) |
| Category | Environment |
| Tags | department of environmental protection, dep, environment, water, reservoir, health, ecosystem, eco-system, agua, water system, water supply, nyc, tap, tap water, conservation, watershed, dam, cove... |
| Created | 2011-08-30T22:19:19Z |
| Publication Date | 2013-06-21T19:44:03Z |

## Description

Reservoir areas and stream lengths

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                             | Data Type | Render Type |
| ======== | ============== | ============================ | ================================ | ========= | =========== |
| No       | time           | :updated_at                  | updated_at                       | meta_data | meta_data   |
| Yes      | series tag     | basin                        | Basin                            | text      | text        |
| Yes      | numeric metric | reservoir_acres              | Reservoir Acres                  | number    | number      |
| Yes      | numeric metric | basin_acres_land_only        | Basin Acres (land only)          | number    | number      |
| Yes      | numeric metric | total_acres                  | Total Acres                      | number    | number      |
| Yes      | numeric metric | reservoir_shoreline_miles    | Reservoir Shoreline Miles        | number    | number      |
| Yes      | numeric metric | stream_miles                 | Stream Miles                     | number    | number      |
| Yes      | numeric metric | 100_ft_riparian_buffer_acres | 100 ft. Riparian Buffer*** Acres | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:9vgt-yx2p d:2011-08-30T15:19:19.000Z t:basin=Ashokan m:basin_acres_land_only=155299 m:100_ft_riparian_buffer_acres=11384.2 m:total_acres=163405.5 m:reservoir_shoreline_miles=53.2 m:stream_miles=485.4 m:reservoir_acres=8106.5

series e:9vgt-yx2p d:2011-08-30T15:19:19.000Z t:basin=Cannonsville m:basin_acres_land_only=286364.6 m:100_ft_riparian_buffer_acres=18782.6 m:total_acres=291077.3 m:reservoir_shoreline_miles=56.2 m:stream_miles=802.6 m:reservoir_acres=4712.7

series e:9vgt-yx2p d:2011-08-30T15:19:19.000Z t:basin=Neversink m:basin_acres_land_only=57409.4 m:100_ft_riparian_buffer_acres=5389.6 m:total_acres=58902.2 m:reservoir_shoreline_miles=18.6 m:stream_miles=229.9 m:reservoir_acres=1492.8
```

## Meta Commands

```ls
metric m:reservoir_acres p:float l:"Reservoir Acres" t:dataTypeName=number

metric m:basin_acres_land_only p:float l:"Basin Acres (land only)" t:dataTypeName=number

metric m:total_acres p:float l:"Total Acres" t:dataTypeName=number

metric m:reservoir_shoreline_miles p:float l:"Reservoir Shoreline Miles" t:dataTypeName=number

metric m:stream_miles p:float l:"Stream Miles" t:dataTypeName=number

metric m:100_ft_riparian_buffer_acres p:float l:"100 ft. Riparian Buffer*** Acres" t:dataTypeName=number

entity e:9vgt-yx2p l:Hydrostats t:attribution="Department of Environmental Protection (DEP)" t:url=https://data.cityofnewyork.us/api/views/9vgt-yx2p

property e:9vgt-yx2p t:meta.view v:id=9vgt-yx2p v:category=Environment v:averageRating=0 v:name=Hydrostats v:attribution="Department of Environmental Protection (DEP)"

property e:9vgt-yx2p t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:9vgt-yx2p t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | basin        | reservoir_acres | basin_acres_land_only | total_acres | reservoir_shoreline_miles | stream_miles | 100_ft_riparian_buffer_acres | 
| =========== | ============ | =============== | ===================== | =========== | ========================= | ============ | ============================ | 
| 1314717559  | Basin        |                 |                       |             |                           |              |                              | 
| 1314717559  | Ashokan      | 8106.5          | 155299.0              | 163405.5    | 53.2                      | 485.4        | 11384.2                      | 
| 1314717559  | Cannonsville | 4712.7          | 286364.6              | 291077.3    | 56.2                      | 802.6        | 18782.6                      | 
| 1314717559  | Neversink    | 1492.8          | 57409.4               | 58902.2     | 18.6                      | 229.9        | 5389.6                       | 
| 1314717559  | Pepacton     | 5193.7          | 232278.5              | 237472.2    | 53.2                      | 664.6        | 15711.4                      | 
| 1314717559  | Rondout      | 2037.9          | 59001.1               | 61039.0     | 20.3                      | 203.4        | 4797.7                       | 
| 1314717559  | Schoharie    | 1144.8          | 200895.0              | 202039.9    | 14.9                      | 742.7        | 17371.9                      | 
| 1314717559  | WOH Total    | 22688.4         | 991247.5              | 1013936.0   | 216.4                     | 3128.6       | 73437.4                      | 
| 1314717559  | Boyds Corner | 222.3           | 14095.6               | 14317.8     | 5.5                       | 51.3         | 1187.7                       | 
| 1314717559  | Kensico      | 2069.2          | 6406.3                | 8475.5      | 32.4                      | 20.7         | 448.3                        | 
```