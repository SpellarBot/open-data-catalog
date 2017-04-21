# Thruway Travel Plazas and Parking/Rest Areas

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/thruway-travel-plazas-and-parking-rest-areas) |
| Metadata | [Link](https://data.ny.gov/api/views/mj5h-8ei4) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/mj5h-8ei4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/mj5h-8ei4/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | mj5h-8ei4 |
| Name | Thruway Travel Plazas and Parking/Rest Areas |
| Attribution | New York State Thruway Authority |
| Category | Transportation |
| Tags | travel plazas, rest areas, parking areas, rest stops |
| Created | 2013-02-26T16:07:51Z |
| Publication Date | 2013-02-28T21:10:20Z |

## Description

The Travel Plazas and Parking/Rest Areas is an informational aid for travelers along the Thruway System that provides patrons with a listing of travel plazas and parking/rest areas and their locations. The csv file contains the latitude and longitude, milepost, direction of the location of the travel plaza and parking/rest area and the route name along which they are located.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| No       | time           | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | series tag     | title          | Title          | text      | text        |
| Yes      | series tag     | milepost       | Milepost       | text      | number      |
| Yes      | series tag     | route_location | Route Location | text      | text        |
| Yes      | series tag     | direction      | Direction      | text      | text        |
| Yes      | series tag     | route          | Route          | text      | text        |
| Yes      | numeric metric | icon_anchor    | Icon Anchor    | number    | number      |
| Yes      | series tag     | tp_id          | TP ID          | text      | text        |
| No       |                | latitude       | Latitude       | number    | number      |
| No       |                | longitude      | Longitude      | number    | number      |
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
series e:mj5h-8ei4 d:2013-02-26T08:07:52.000Z t:title=Angola t:milepost=447 t:route="I-90 - NYS Thruway" t:direction="Eastbound & Westbound" t:route_location="Exit 57A (Eden-Angola) & Exit 58 (Silver Creek)" t:tp_id=an m:icon_anchor=0

series e:mj5h-8ei4 d:2013-02-26T08:07:52.000Z t:title=Ardsley t:milepost=6 t:route="I-87 - NYS Thruway" t:direction=Northbound t:route_location="Exit 6A (Yonkers Toll Barrier) & Exit 7 (Ardsley)" t:tp_id=ar m:icon_anchor=1

series e:mj5h-8ei4 d:2013-02-26T08:07:52.000Z t:title=Chittenango t:milepost=266 t:route="I-90 - NYS Thruway" t:direction=Westbound t:route_location="Exit 34 (Canastota) & Exit 34A (Syracuse I-481)" t:tp_id=ch m:icon_anchor=4
```

## Meta Commands

```ls
metric m:icon_anchor p:integer l:"Icon Anchor" d:"Used for placement on an interactive google map." t:dataTypeName=number

entity e:mj5h-8ei4 l:"Thruway Travel Plazas and Parking/Rest Areas" t:attribution="New York State Thruway Authority" t:url=https://data.ny.gov/api/views/mj5h-8ei4

property e:mj5h-8ei4 t:meta.view v:id=mj5h-8ei4 v:category=Transportation v:attributionLink=http://www.thruway.ny.gov/travelers/travelplazas/ v:averageRating=0 v:name="Thruway Travel Plazas and Parking/Rest Areas" v:attribution="New York State Thruway Authority"

property e:mj5h-8ei4 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:mj5h-8ei4 t:meta.view.tableauthor v:id=mwxm-zess v:profileImageUrlMedium=/api/users/mwxm-zess/profile_images/THUMB v:profileImageUrlLarge=/api/users/mwxm-zess/profile_images/LARGE v:screenName="Lindsey Krough" v:profileImageUrlSmall=/api/users/mwxm-zess/profile_images/TINY v:roleName=administrator v:displayName="Lindsey Krough"

property e:mj5h-8ei4 t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | title           | milepost | route_location                                         | direction             | route              | icon_anchor | tp_id | latitude | longitude | 
| =========== | =============== | ======== | ====================================================== | ===================== | ================== | =========== | ===== | ======== | ========= | 
| 1361866072  | Angola          | 447      | Exit 57A (Eden-Angola) & Exit 58 (Silver Creek)        | Eastbound & Westbound | I-90 - NYS Thruway | 0           | an    | 42.63576 | -78.98909 | 
| 1361866072  | Ardsley         | 6        | Exit 6A (Yonkers Toll Barrier) & Exit 7 (Ardsley)      | Northbound            | I-87 - NYS Thruway | 1           | ar    | 40.984   | -73.85287 | 
| 1361866072  | Chittenango     | 266      | Exit 34 (Canastota) & Exit 34A (Syracuse I-481)        | Westbound             | I-90 - NYS Thruway | 4           | ch    | 43.09607 | -75.8416  | 
| 1361866072  | Clarence        | 412      | Exit 48A (Pembroke) & Exit 49 (Depew)                  | Westbound             | I-90 - NYS Thruway | 4           | cl    | 42.95248 | -78.60289 | 
| 1361866072  | Clifton Springs | 337      | Exit 43 (Manchester) & Exit 42 (Geneva)                | Eastbound             | I-90 - NYS Thruway | 3           | cs    | 42.9729  | -77.17367 | 
| 1361866072  | Dewitt          | 280      | Exit 36 (Syracuse I-81) & Exit 35 (Syracuse East)      | Eastbound             | I-90 - NYS Thruway | 3           | de    | 43.09103 | -76.10088 | 
| 1361866072  | Guilderland     | 153      | Exit 25 (Schenectady East) & Exit 24 (Albany Northway) | Eastbound             | I-90 - NYS Thruway | 3           | gu    | 42.74384 | -73.91855 | 
| 1361866072  | Indian Castle   | 210      | Exit 29A (Little Falls) & Exit 29 (Canajoharie)        | Eastbound             | I-90 - NYS Thruway | 3           | ic    | 43.01549 | -74.80299 | 
| 1361866072  | Iroquois        | 210      | Exit 29 (Canajoharie) & Exit 29A (Little Falls)        | Westbound             | I-90 - NYS Thruway | 4           | ir    | 43.01711 | -74.80219 | 
| 1361866072  | Junius Ponds    | 324      | Exit 41 (Waterloo) & Exit 42 (Geneva)                  | Westbound             | I-90 - NYS Thruway | 4           | jp    | 42.95897 | -76.91816 | 
```