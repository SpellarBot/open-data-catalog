# Boat Launch Sites by Waterbody

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/boat-launch-sites-by-waterbody) |
| Metadata | [Link](https://data.ny.gov/api/views/icvg-v8xr) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/icvg-v8xr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/icvg-v8xr/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | icvg-v8xr |
| Name | Boat Launch Sites by Waterbody |
| Attribution | New York State Department of Environmental Conservation |
| Category | Recreation |
| Tags | boat, launching, public, access |
| Created | 2013-02-14T03:31:26Z |
| Publication Date | 2013-03-01T18:57:42Z |

## Description

This dataset contains boat launch sites owned or operated by the Department of Environmental Conservation, which offer public facilities for launching boats onto New York State waters.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | waterbody   | WATERBODY  | text      | text        |
| Yes      | series tag     | sanitary_f  | Restrooms  | text      | text        |
| Yes      | numeric metric | car         | Cars       | number    | number      |
| Yes      | numeric metric | trail       | Trailers   | number    | number      |
| Yes      | series tag     | access      | Access     | text      | text        |
| Yes      | series tag     | name_icon   | NAME_ICON  | text      | text        |
| No       |                | point_x     | POINT_X    | number    | number      |
| No       |                | point_y     | POINT_Y    | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = point_x,point_y
```

## Data Commands

```ls
series e:icvg-v8xr d:2013-02-20T18:30:35.000Z t:waterbody="Alder Lake" t:sanitary_f=No t:access="Hand Launch" t:name_icon="Alder Lake_Hand Launch" m:car=10 m:trail=0

series e:icvg-v8xr d:2013-02-20T18:30:35.000Z t:waterbody="Allegheny River" t:sanitary_f=No t:access="Hand Launch" t:name_icon="Allegheny River_Hand Launch" m:car=8 m:trail=0

series e:icvg-v8xr d:2013-02-20T18:30:35.000Z t:waterbody="Allen Lake" t:sanitary_f=Yes t:access="Trailer - Unimproved" t:name_icon="Allen Lake_Trailer - Unimproved" m:car=20 m:trail=5
```

## Meta Commands

```ls
metric m:car p:integer l:Cars d:"Number of cars that can be parked at facility" t:dataTypeName=number

metric m:trail p:integer l:Trailers d:"Number of Trailers that can be parked at facility" t:dataTypeName=number

entity e:icvg-v8xr l:"Boat Launch Sites by Waterbody" t:attribution="New York State Department of Environmental Conservation" t:url=https://data.ny.gov/api/views/icvg-v8xr

property e:icvg-v8xr t:meta.view v:id=icvg-v8xr v:category=Recreation v:attributionLink=http://www.dec.ny.gov/outdoor/7832.html v:averageRating=0 v:name="Boat Launch Sites by Waterbody" v:attribution="New York State Department of Environmental Conservation"

property e:icvg-v8xr t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:icvg-v8xr t:meta.view.tableauthor v:id=mwxm-zess v:profileImageUrlMedium=/api/users/mwxm-zess/profile_images/THUMB v:profileImageUrlLarge=/api/users/mwxm-zess/profile_images/LARGE v:screenName="Lindsey Krough" v:profileImageUrlSmall=/api/users/mwxm-zess/profile_images/TINY v:roleName=administrator v:displayName="Lindsey Krough"

property e:icvg-v8xr t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | waterbody                  | sanitary_f | car | trail | access               | name_icon                              | point_x        | point_y       | 
| =========== | ========================== | ========== | === | ===== | ==================== | ====================================== | ============== | ============= | 
| 1361385035  | Alder Lake                 | No         | 10  | 0     | Hand Launch          | Alder Lake_Hand Launch                 | -74.6804221073 | 42.049918124  | 
| 1361385035  | Allegheny River            | No         | 8   | 0     | Hand Launch          | Allegheny River_Hand Launch            | -78.5295620729 | 42.101689611  | 
| 1361385035  | Allen Lake                 | Yes        | 20  | 5     | Trailer - Unimproved | Allen Lake_Trailer - Unimproved        | -78.070131421  | 42.3827071658 | 
| 1361385035  | Alma Pond                  | No         | 10  | 0     | Hand Launch          | Alma Pond_Hand Launch                  | -77.995245063  | 42.0151912165 | 
| 1361385035  | Balsam Pond                | No         | 0   | 8     | Trailer - Unimproved | Balsam Pond_Trailer - Unimproved       | -75.7582987042 | 42.548958619  | 
| 1361385035  | Barge Canal / Mohawk River | No         | 5   | 0     | Hand Launch          | Barge Canal / Mohawk River_Hand Launch | -75.6461721387 | 43.2097386594 | 
| 1361385035  | Basha Kill Marsh 1         | No         | 2   | 0     | Hand Launch          | Basha Kill Marsh 1_Hand Launch         | -74.5102223967 | 41.5433255348 | 
| 1361385035  | Basha Kill Marsh 2         | No         | 2   | 0     | Hand Launch          | Basha Kill Marsh 2_Hand Launch         | -74.5168846894 | 41.5357785338 | 
| 1361385035  | Basha Kill Marsh 3         | No         | 2   | 0     | Hand Launch          | Basha Kill Marsh 3_Hand Launch         | -74.537999599  | 41.5166615733 | 
| 1361385035  | Basha Kill Marsh 4         | No         | 2   | 0     | Hand Launch          | Basha Kill Marsh 4_Hand Launch         | -74.5442511573 | 41.5087329835 | 
```