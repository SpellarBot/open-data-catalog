# Thruway Commuter Park and Ride Lots

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/thruway-commuter-park-and-ride-lots) |
| Metadata | [Link](https://data.ny.gov/api/views/nvxe-b625) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/nvxe-b625/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/nvxe-b625/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | nvxe-b625 |
| Name | Thruway Commuter Park and Ride Lots |
| Attribution | New York State Thruway Authority |
| Category | Transportation |
| Tags | commuter lots, park and ride |
| Created | 2013-02-26T15:50:03Z |
| Publication Date | 2013-02-28T20:53:41Z |

## Description

The Commuter Park and Ride Lots Listing provides travelers along the Thruway System with a listing of available locations in which to park their vehicle and commute from. The csv file contains the latitude and longitude, title of lot, location, lot owner, available parking, lighting and pavement conditions.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | title       | Title      | text      | text        |
| Yes      | series tag     | exit        | Exit       | text      | text        |
| Yes      | series tag     | run_by      | Run By     | text      | text        |
| Yes      | numeric metric | spaces      | Spaces     | number    | number      |
| Yes      | series tag     | paved       | Paved      | text      | text        |
| Yes      | series tag     | lighted     | Lighted    | text      | text        |
| Yes      | series tag     | comments    | Comments   | text      | text        |
| No       |                | latitude    | Latitude   | number    | number      |
| No       |                | longitude   | Longitude  | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = latitude,longitude
```

## Data Commands

```ls
series e:nvxe-b625 d:2013-02-26T07:50:05.000Z t:title="West Nyack (Lot 1)" t:paved=Yes t:lighted=Yes t:comments="Located at the NE Corner of Rt. 59 and Rt. 303" t:exit=12 t:run_by=NYSDOT m:spaces=232

series e:nvxe-b625 d:2013-02-26T07:50:05.000Z t:title="West Nyack (Lot 2)" t:paved=Yes t:lighted=Yes t:comments="Located at the SE Corner of Rt.59 and Rt. 303" t:exit=12 t:run_by=NYSDOT m:spaces=200

series e:nvxe-b625 d:2013-02-26T07:50:05.000Z t:title="West Nyack (Lot J)" t:paved=Yes t:lighted=Yes t:comments="Located on Palisades Center Ring Road" t:exit=12 t:run_by=Palisades m:spaces=900
```

## Meta Commands

```ls
metric m:spaces p:integer l:Spaces d:"The number of parking spaces available." t:dataTypeName=number

entity e:nvxe-b625 l:"Thruway Commuter Park and Ride Lots" t:attribution="New York State Thruway Authority" t:url=https://data.ny.gov/api/views/nvxe-b625

property e:nvxe-b625 t:meta.view v:id=nvxe-b625 v:category=Transportation v:attributionLink=http://www.thruway.ny.gov/travelers/interchanges/commuter-lots.html v:averageRating=0 v:name="Thruway Commuter Park and Ride Lots" v:attribution="New York State Thruway Authority"

property e:nvxe-b625 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:nvxe-b625 t:meta.view.tableauthor v:id=mwxm-zess v:profileImageUrlMedium=/api/users/mwxm-zess/profile_images/THUMB v:profileImageUrlLarge=/api/users/mwxm-zess/profile_images/LARGE v:screenName="Lindsey Krough" v:profileImageUrlSmall=/api/users/mwxm-zess/profile_images/TINY v:roleName=administrator v:displayName="Lindsey Krough"

property e:nvxe-b625 t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | title                     | exit | run_by                        | spaces | paved | lighted | comments                                                                                              | latitude | longitude | 
| =========== | ========================= | ==== | ============================= | ====== | ===== | ======= | ===================================================================================================== | ======== | ========= | 
| 1361865005  | West Nyack (Lot 1)        | 12   | NYSDOT                        | 232    | Yes   | Yes     | Located at the NE Corner of Rt. 59 and Rt. 303                                                        | 41.09436 | -73.94979 | 
| 1361865005  | West Nyack (Lot 2)        | 12   | NYSDOT                        | 200    | Yes   | Yes     | Located at the SE Corner of Rt.59 and Rt. 303                                                         | 41.09316 | -73.9497  | 
| 1361865005  | West Nyack (Lot J)        | 12   | Palisades                     | 900    | Yes   | Yes     | Located on Palisades Center Ring Road                                                                 | 41.09968 | -73.96232 | 
| 1361865005  | Spring Valley (East Lot)  | 14   | NYSDOT and Town of Clarkstown | 188    | Yes   | Yes     | Located at the South Side of Rt. 59 at NYSTA Exit 14                                                  | 41.10289 | -74.02979 | 
| 1361865005  | Spring Valley (North Lot) | 14   | NYSDOT and Town of Clarkstown | 225    | Yes   | Yes     | Located at the North Side of Rt. 59 at NYSTA Exit 14                                                  | 41.10358 | -74.02896 | 
| 1361865005  | Spring Valley (West Lot)  | 14   | NYSDOT and Town of Clarkstown | 80     | Yes   | Yes     | Located at the South Side of Rt. 59 at NYSTA Exit 14                                                  | 41.10343 | -74.03072 | 
| 1361865005  | Newburgh                  | 17   | Short Line                    | 289    | Yes   | Yes     | Located on Rt. 17K at Union Avenue at the Short Line Bus Station. Privately maintained by Short Line. | 41.50568 | -74.06309 | 
| 1361865005  | New Paltz                 | 18   | Thruway                       | 150    | Yes   | Yes     | Located on the South Side of Rt. 299 at the New Paltz Toll Plaza (16-hour Parking Limit)              | 41.74027 | -74.06242 | 
| 1361865005  | Kingston                  | 19   | NYSDOT                        | 84     | Yes   | Yes     | Located off Route 587                                                                                 | 41.94275 | -74.02749 | 
| 1361865005  | Saugerties South          | 20   | NYSDOT                        | 12     | No    | No      | Located off Routes 32 and 212                                                                         | 42.08614 | -73.97564 | 
```