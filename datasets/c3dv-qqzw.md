# Texting Zone Locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/texting-zone-locations) |
| Metadata | [Link](https://data.ny.gov/api/views/c3dv-qqzw) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/c3dv-qqzw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/c3dv-qqzw/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | c3dv-qqzw |
| Name | Texting Zone Locations |
| Attribution | New York State Department of Transportation and New York State Thruway Authority |
| Category | Transportation |
| Tags | safety, texting zone, thruway, state highways |
| Created | 2013-10-10T18:13:37Z |
| Publication Date | 2013-11-06T14:38:26Z |

## Description

Special "Texting Zones" locations along the New York State Thruway and State Highways that give motorists a pull-off area to park and use their mobile devices. Existing Park-n-Ride facilities, rest stops, parking areas and travel plazas along the Thruway and State Highways will have a dual-function as a texting zone.  A total of 90 Texting Zones are located along major highways across the state. New York State Department of Transportation (NYSDOT) in coordination with the Thruway Authority, have collaborated to provide Texting Zones location information and signage to inform drivers.

## Columns

```ls
| Included | Schema Type | Field Name    | Name          | Data Type | Render Type |
| ======== | =========== | ============= | ============= | ========= | =========== |
| No       | time        | :updated_at   | updated_at    | meta_data | meta_data   |
| Yes      | series tag  | facility_name | Facility Name | text      | text        |
| Yes      | series tag  | facility_type | Facility Type | text      | text        |
| Yes      | series tag  | county        | County        | text      | text        |
| Yes      | series tag  | highway_name  | Highway Name  | text      | text        |
| Yes      | series tag  | rm_milepost   | RM Milepost   | text      | text        |
| Yes      | series tag  | maintained_by | Maintained By | text      | text        |
| No       |             | latitude      | Latitude      | number    | number      |
| No       |             | longitude     | Longitude     | number    | number      |
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
series e:c3dv-qqzw d:2013-11-06T06:37:23.000Z t:highway_name=I-87 t:facility_name="Glens Falls North" t:maintained_by=NYSDOT t:county=Warren t:facility_type="Rest Area" t:rm_milepost=87I17101007 m:row_number.c3dv-qqzw=1

series e:c3dv-qqzw d:2013-11-06T06:37:23.000Z t:highway_name=I-87 t:facility_name="Clifton Park" t:maintained_by=NYSDOT t:county=Saratoga t:facility_type="Rest Area" t:rm_milepost=87I15091060 m:row_number.c3dv-qqzw=2

series e:c3dv-qqzw d:2013-11-06T06:37:23.000Z t:highway_name=I-81 t:facility_name=Preble t:maintained_by=NYSDOT t:county=Cortland t:facility_type="Rest Area" t:rm_milepost=81I32023075 m:row_number.c3dv-qqzw=3
```

## Meta Commands

```ls
metric m:row_number.c3dv-qqzw p:long l:"Row Number"

entity e:c3dv-qqzw l:"Texting Zone Locations" t:attribution="New York State Department of Transportation and New York State Thruway Authority" t:url=https://data.ny.gov/api/views/c3dv-qqzw

property e:c3dv-qqzw t:meta.view v:id=c3dv-qqzw v:category=Transportation v:averageRating=0 v:name="Texting Zone Locations" v:attribution="New York State Department of Transportation and New York State Thruway Authority"

property e:c3dv-qqzw t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:c3dv-qqzw t:meta.view.tableauthor v:id=g8ff-96uh v:screenName="Rae Bascue" v:roleName=viewer v:displayName="Rae Bascue"

property e:c3dv-qqzw t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | facility_name     | facility_type | county      | highway_name | rm_milepost  | maintained_by | latitude    | longitude    | 
| =========== | ================= | ============= | =========== | ============ | ============ | ============= | =========== | ============ | 
| 1383719843  | Glens Falls North | Rest Area     | Warren      | I-87         | 87I17101007  | NYSDOT        | 43.27268681 | -73.67399684 | 
| 1383719843  | Clifton Park      | Rest Area     | Saratoga    | I-87         | 87I15091060  | NYSDOT        | 42.87749433 | -73.776839   | 
| 1383719843  | Preble            | Rest Area     | Cortland    | I-81         | 81I32023075  | NYSDOT        | 42.71227413 | -76.14709492 | 
| 1383719843  | Mount Morris      | Rest Area     | Livingston  | I-390        | 390I42021168 | NYSDOT        | 42.72724303 | -77.83167098 | 
| 1383719843  | Friendship        | Rest Area     | Allegany    | I-86         | 17 61032116  | NYSDOT        | 42.22402505 | -78.1006145  | 
| 1383719843  | Owego             | Rest Area     | Tioga       | NY17         | 17 65063162  | NYSDOT        | 42.08626857 | -76.28095135 | 
| 1383719843  | Point Au Roche    | Rest Area     | Clinton     | I-87         | 87I71051236  | NYSDOT        | 44.80457673 | -73.44290009 | 
| 1383719843  | Orleans           | Rest Area     | Jefferson   | I-81         | 81I73051438  | NYSDOT        | 44.24291147 | -75.9436667  | 
| 1383719843  | East Fishkill     | Rest Area     | Dutchess    | I-84         | 84I82021150  | NYSDOT        | 41.5465862  | -73.72215766 | 
| 1383719843  | Bedford           | Rest Area     | Westchester | I-684        | 684I87011153 | NYSDOT        | 41.23109623 | -73.68159217 | 
```