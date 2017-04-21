# Artificial Reefs Managed by New York State Department of Environmental Conservation

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/artificial-reefs-managed-by-new-york-state-department-of-environmental-conservation) |
| Metadata | [Link](https://data.ny.gov/api/views/jsnj-ehv9) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/jsnj-ehv9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/jsnj-ehv9/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | jsnj-ehv9 |
| Name | Artificial Reefs Managed by New York State Department of Environmental Conservation |
| Attribution | New York State Department of Environmental Conservation |
| Category | Recreation |
| Tags | artificial reefs, diving, marine habitat, fishing |
| Created | 2014-06-30T15:12:49Z |
| Publication Date | 2016-01-27T19:22:30Z |

## Description

The dataset is composed of information from Marine Artificial Reef Map and includes GPS location coordinates as well as other information regarding the reef. New York State Department of Environmental Conservation's (NYSDEC) Bureau of Marine Resources created and manages these reef sites as well as other marine resources in the area and in New York State in general.

## Columns

```ls
| Included | Schema Type | Field Name              | Name                    | Data Type | Render Type |
| ======== | =========== | ======================= | ======================= | ========= | =========== |
| No       | time        | :updated_at             | updated_at              | meta_data | meta_data   |
| Yes      | series tag  | reef_name               | Reef Name               | text      | text        |
| No       |             | northwest_latitude      | Northwest Latitude      | number    | number      |
| No       |             | northwest_longitude     | Northwest Longitude     | number    | number      |
| No       |             | northeast_latitude      | Northeast Latitude      | number    | number      |
| No       |             | northeast_longitude     | Northeast Longitude     | number    | number      |
| No       |             | southeast_latitude      | Southeast Latitude      | number    | number      |
| No       |             | southeast_longitude     | Southeast Longitude     | number    | number      |
| No       |             | southwest_latitude      | Southwest Latitude      | number    | number      |
| No       |             | southwest_longitude     | Southwest Longitude     | number    | number      |
| Yes      | series tag  | body_of_water           | Body of Water           | text      | text        |
| Yes      | series tag  | description_of_location | Description of Location | text      | text        |
| Yes      | series tag  | size                    | Size                    | text      | text        |
| Yes      | series tag  | boundaries              | Boundaries              | text      | text        |
| Yes      | series tag  | minimum_depth           | Minimum Depth           | text      | text        |
| Yes      | series tag  | maximum_depth           | Maximum Depth           | text      | text        |
| Yes      | series tag  | comments                | Comments                | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = northwest_latitude,northwest_longitude,northeast_latitude,northeast_longitude,southeast_latitude,southeast_longitude,southwest_latitude,southwest_longitude
```

## Data Commands

```ls
series e:jsnj-ehv9 d:2016-01-22T15:00:28.000Z t:body_of_water="Atlantic Ocean" t:boundaries="2,000 by 1,000 yards" t:description_of_location="3.0 Nautical Miles South of Atlantic Beach." t:maximum_depth="64 feet" t:minimum_depth="55 feet" t:reef_name="Atlantic Beach Reef" t:size="413 acres" m:row_number.jsnj-ehv9=1

series e:jsnj-ehv9 d:2016-01-22T15:00:28.000Z t:body_of_water="Atlantic Ocean" t:boundaries="3,000 by 1,200 yards" t:description_of_location="2.0 Nautical Miles South of Fire Island Lighthouse." t:maximum_depth="73 feet" t:minimum_depth="62 feet" t:reef_name="Fire Island Reef" t:comments="Fish pots banned by state law" t:size="744 acres" m:row_number.jsnj-ehv9=2

series e:jsnj-ehv9 d:2016-01-22T15:00:28.000Z t:body_of_water="Atlantic Ocean" t:boundaries="3,000 by 1,200 yards" t:description_of_location="3.3 Nautical Miles South of Jones Beach State Park." t:maximum_depth="72 feet" t:minimum_depth="50 feet" t:reef_name="Hempstead Reef" t:size="744 acres" m:row_number.jsnj-ehv9=3
```

## Meta Commands

```ls
metric m:row_number.jsnj-ehv9 p:long l:"Row Number"

entity e:jsnj-ehv9 l:"Artificial Reefs Managed by New York State Department of Environmental Conservation" t:attribution="New York State Department of Environmental Conservation" t:url=https://data.ny.gov/api/views/jsnj-ehv9

property e:jsnj-ehv9 t:meta.view v:id=jsnj-ehv9 v:category=Recreation v:attributionLink=http://www.dec.ny.gov/outdoor/7896.html v:averageRating=0 v:name="Artificial Reefs Managed by New York State Department of Environmental Conservation" v:attribution="New York State Department of Environmental Conservation"

property e:jsnj-ehv9 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:jsnj-ehv9 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:jsnj-ehv9 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | reef_name           | northwest_latitude | northwest_longitude | northeast_latitude | northeast_longitude | southeast_latitude | southeast_longitude | southwest_latitude | southwest_longitude | body_of_water     | description_of_location                                                            | size      | boundaries           | minimum_depth | maximum_depth | comments                      | 
| =========== | =================== | ================== | =================== | ================== | =================== | ================== | =================== | ================== | =================== | ================= | ================================================================================== | ========= | ==================== | ============= | ============= | ============================= | 
| 1453474828  | Atlantic Beach Reef | 40.53366667        | -73.72833333        | 40.53366667        | -73.70666667        | 40.5255            | -73.70666667        | 40.5255            | -73.72833333        | Atlantic Ocean    | 3.0 Nautical Miles South of Atlantic Beach.                                        | 413 acres | 2,000 by 1,000 yards | 55 feet       | 64 feet       |                               | 
| 1453474828  | Fire Island Reef    | 40.60166667        | -73.225             | 40.5455            | -73.19166667        | 40.59333333        | -73.19166667        | 40.59333333        | -73.225             | Atlantic Ocean    | 2.0 Nautical Miles South of Fire Island Lighthouse.                                | 744 acres | 3,000 by 1,200 yards | 62 feet       | 73 feet       | Fish pots banned by state law | 
| 1453474828  | Hempstead Reef      | 40.52083333        | -73.55583333        | 40.525             | -73.52283333        | 40.51533333        | -73.52583333        | 40.51116667        | -73.55866667        | Atlantic Ocean    | 3.3 Nautical Miles South of Jones Beach State Park.                                | 744 acres | 3,000 by 1,200 yards | 50 feet       | 72 feet       |                               | 
| 1453474828  | Kismet Reef         | 40.63566667        | -73.21563333        | 40.6385            | -73.20548333        | 40.63808333        | -73.20528333        | 40.63525           | -73.21543333        | Great South Bay   | 120 yards North of the South Beach, between Kismet and the National Seashore dock. | 10 acres  | 1,000 by 50 yards    | 16 feet       | 25 feet       | Fish pots banned by state law | 
| 1453474828  | Matinecock Reef     | 40.90965           | -73.62901667        | 40.91148333        | -73.62083333        | 40.90968333        | -73.62016667        | 40.90798333        | -73.62835           | Long Island Sound | 0.5 Nautical Miles North of Peacock Point.                                         | 41 acres  | 800 by 250 yards     | 30 feet       | 40 feet       | Fish pots banned by state law | 
| 1453474828  | McAllister Grounds  | 40.53833333        | -73.66166667        | 40.53833333        | -73.65333333        | 40.535             | -73.65333333        | 40.535             | -73.66166667        | Atlantic Ocean    | 2.8 Nautical Miles South of Long Beach.                                            | 115 acres | 925 by 600 yards     | 50 feet       | 53 feet       | Fish pots banned by state law | 
| 1453474828  | Moriches Reef       | 40.7245            | -72.77733333        | 40.72566667        | -72.77266667        | 40.7245            | -72.77216667        | 40.72333333        | -72.77691667        | Atlantic Ocean    | 2.4 Nautical Miles South of Moriches Inlet                                         | 14 acres  | 450 by 150 yards     | 70 feet       | 75 feet       | Fish pots banned by state law | 
| 1453474828  | Rockaway Reef       | 40.5455            | -73.8535            | 40.5455            | -73.832             | 40.53666667        | -73.832             | 40.53666667        | -73.8535            | Atlantic Ocean    | 1.6 Nautical Miles South of Rockaway Beach.                                        | 413 acres | 2,000 by 1,000 yards | 32 Feet       | 40 feet       | Fish pots banned by state law | 
| 1453474828  | Shinnecock Reef     | 40.80278333        | -72.47778333        | 40.80361667        | -72.47166667        | 40.80138333        | -72.47221667        | 40.80055           | -72.47861667        | Atlantic Ocean    | 2.0 Nautical Miles South of Shinecock Inlet.                                       | 35 acres  | 680 by 250 yards     | 79 feet       | 84 feet       | Fish pots banned by state law | 
| 1453474828  | Smithtown Reef      | 40.93291667        | -73.18616667        | 40.93341667        | -73.1845            | 40.93258333        | -73.18391667        | 40.932             | -73.18566667        | Long Island Sound | 1.6 Nautical Miles Northwest of Stony Brook Harbor entrance.                       | 3 acres   | 150 by 100 yards     | 38 feet       | 40 feet       | Fish pots banned by state law | 
```