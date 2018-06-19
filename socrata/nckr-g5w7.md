# Reservoir Characteristics

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/reservoir-and-dam-statistics) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/nckr-g5w7) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/nckr-g5w7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/nckr-g5w7/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | nckr-g5w7 |
| Name | Reservoir Characteristics |
| Attribution | Department of Environmental Protection (DEP) |
| Category | Environment |
| Tags | department of environmental protection, dep, environment, water, reservoir, health, ecosystem, eco-system, agua, water system, water supply, nyc, tap, tap water, conservation, watershed, dam, cove... |
| Created | 2011-09-30T18:18:37Z |
| Publication Date | 2013-06-21T19:44:37Z |

## Description

The data tables provides current reservoir storage levels along with release, diversion, and spill rates

## Columns

```ls
| Included | Schema Type    | Field Name                                   | Name                                           | Data Type | Render Type |
| ======== | ============== | ============================================ | ============================================== | ========= | =========== |
| Yes      | series tag     | reservior_                                   | Reservior #                                    | text      | text        |
| Yes      | series tag     | name_of_reservior                            | Name of Reservior                              | text      | text        |
| Yes      | series tag     | location                                     | Location                                       | text      | text        |
| Yes      | numeric metric | drainage_area                                | Drainage Area                                  | number    | number      |
| Yes      | time           | date_put_in_service                          | Date Put in Service                            | number    | number      |
| Yes      | series tag     | kind_of_dam                                  | Kind of Dam                                    | text      | text        |
| Yes      | numeric metric | area_of_water_surface_at_spilway_elevation   | Area of Water Surface at Spilway Elevation     | number    | number      |
| Yes      | numeric metric | length_of_shoreline_miles_                   | Length of Shoreline (Miles)                    | number    | number      |
| Yes      | numeric metric | elevation_of_spillway_m_s_l_sandy_hook_feet_ | Elevation of Spillway M.S.L. Sandy Hook (Feet) | number    | number      |
```

## Time Field

```ls
Value = date_put_in_service
Format & Zone = yyyy
```

## Data Commands

```ls
series e:nckr-g5w7 d:1873-01-01T00:00:00.000Z t:location=Kent t:name_of_reservior="Boyds Corner" t:kind_of_dam="Masonry, Earth Wings" t:reservior_=1 m:area_of_water_surface_at_spilway_elevation=0.464 m:drainage_area=23.46 m:length_of_shoreline_miles_=6.2 m:elevation_of_spillway_m_s_l_sandy_hook_feet_=580.05

series e:nckr-g5w7 d:1870-01-01T00:00:00.000Z t:location=Kent t:name_of_reservior="Barretts Pond" t:kind_of_dam=Earth t:reservior_=2x m:area_of_water_surface_at_spilway_elevation=0.108 m:drainage_area=0.57 m:length_of_shoreline_miles_=1.4 m:elevation_of_spillway_m_s_l_sandy_hook_feet_=776.55

series e:nckr-g5w7 d:1870-01-01T00:00:00.000Z t:location=Carmel t:name_of_reservior="Lake Glenieda" t:kind_of_dam=Earth t:reservior_=3x m:area_of_water_surface_at_spilway_elevation=0.264 m:drainage_area=0.68 m:length_of_shoreline_miles_=2.2 m:elevation_of_spillway_m_s_l_sandy_hook_feet_=504.55
```

## Meta Commands

```ls
metric m:drainage_area p:double l:"Drainage Area" t:dataTypeName=number

metric m:area_of_water_surface_at_spilway_elevation p:float l:"Area of Water Surface at Spilway Elevation" t:dataTypeName=number

metric m:length_of_shoreline_miles_ p:float l:"Length of Shoreline (Miles)" t:dataTypeName=number

metric m:elevation_of_spillway_m_s_l_sandy_hook_feet_ p:double l:"Elevation of Spillway M.S.L. Sandy Hook (Feet)" t:dataTypeName=number

entity e:nckr-g5w7 l:"Reservoir Characteristics" t:attribution="Department of Environmental Protection (DEP)" t:url=https://data.cityofnewyork.us/api/views/nckr-g5w7

property e:nckr-g5w7 t:meta.view v:id=nckr-g5w7 v:category=Environment v:averageRating=0 v:name="Reservoir Characteristics" v:attribution="Department of Environmental Protection (DEP)"

property e:nckr-g5w7 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:nckr-g5w7 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| reservior_ | name_of_reservior  | location  | drainage_area | date_put_in_service | kind_of_dam                           | area_of_water_surface_at_spilway_elevation | length_of_shoreline_miles_ | elevation_of_spillway_m_s_l_sandy_hook_feet_ | 
| ========== | ================== | ========= | ============= | =================== | ===================================== | ========================================== | ========================== | ============================================ | 
|            |                    | Town      |               |                     |                                       |                                            |                            |                                              | 
|            |                    |           |               |                     |                                       |                                            |                            |                                              | 
|            |                    |           |               |                     |                                       |                                            |                            |                                              | 
| 1          | Boyds Corner       | Kent      | 23.46         | 1873                | Masonry, Earth Wings                  | 0.464                                      | 6.2                        | 580.05                                       | 
| 2x         | Barretts Pond      | Kent      | 0.57          | 1870                | Earth                                 | 0.108                                      | 1.4                        | 776.55                                       | 
| 3x         | Lake Glenieda      | Carmel    | 0.68          | 1870                | Earth                                 | 0.264                                      | 2.2                        | 504.55                                       | 
| 4          | West Branch (Main) | Carmel    | 42.82         | 1895                | Earth, Masonry Core & Spilway         | 1.692                                      | 15.6                       | 503.2                                        | 
| 5          | West Branch Aux    | Carmel    |               |                     |                                       |                                            |                            |                                              | 
|            |                    |           |               |                     | Earth, Masonry Core & (Auxillary Dam) | 0.17                                       | 11.2                       |                                              | 
| 6          | Middle Branch      | Southeast | 21.31         | 1878                | Earth, Masonry Core                   | 0.669                                      | 6.82                       | 371.55                                       | 
```