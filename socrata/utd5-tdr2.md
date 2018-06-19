# Building Inventory

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/building-inventory) |
| Metadata | [Link](https://data.illinois.gov/api/views/utd5-tdr2) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/utd5-tdr2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/utd5-tdr2/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | utd5-tdr2 |
| Name | Building Inventory |
| Attribution | Capital Development Board |
| Category | Housing |
| Tags | building, inventory, cdb |
| Created | 2014-06-17T18:32:48Z |
| Publication Date | 2017-02-27T15:02:56Z |

## Description

List of all in-use building in our Inventory database

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| No       | time           | :updated_at             | updated_at              | meta_data | meta_data   |
| Yes      | series tag     | agency_name             | Agency Name             | text      | text        |
| Yes      | series tag     | location_name           | Location Name           | text      | text        |
| No       |                | address                 | Address                 | text      | text        |
| Yes      | series tag     | city                    | City                    | text      | text        |
| Yes      | series tag     | zip_code                | Zip code                | text      | text        |
| Yes      | series tag     | county                  | County                  | text      | text        |
| Yes      | numeric metric | congress_dist           | Congress Dist           | number    | number      |
| Yes      | series tag     | congressional_full_name | Congressional Full Name | text      | text        |
| Yes      | numeric metric | rep_dist                | Rep Dist                | number    | number      |
| Yes      | series tag     | rep_full_name           | Rep Full Name           | text      | text        |
| Yes      | numeric metric | senate_dist             | Senate Dist             | number    | number      |
| Yes      | series tag     | senator_full_name       | Senator Full Name       | text      | text        |
| Yes      | series tag     | bldg_status             | Bldg Status             | text      | text        |
| Yes      | numeric metric | year_acquired           | Year Acquired           | number    | text        |
| Yes      | numeric metric | year_constructed        | Year Constructed        | number    | text        |
| Yes      | numeric metric | square_footage          | Square Footage          | number    | number      |
| Yes      | numeric metric | total_floors            | Total Floors            | number    | number      |
| Yes      | numeric metric | floors_above_grade      | Floors Above Grade      | number    | number      |
| Yes      | numeric metric | floors_below_grade      | Floors Below Grade      | number    | number      |
| Yes      | series tag     | usage_description       | Usage Description       | text      | text        |
| Yes      | series tag     | usage_description_2     | Usage Description 2     | text      | text        |
| Yes      | series tag     | usage_description_3     | Usage Description 3     | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:utd5-tdr2 d:2017-02-27T14:54:31.000Z t:bldg_status="In Use" t:senator_full_name="John M. Sullivan" t:location_name="Anderson Lake Conservation Area - Fulton County" t:usage_description_2=Unusual t:usage_description=Unusual t:zip_code=61501 t:county=Fulton t:usage_description_3="Not provided" t:rep_full_name="Hammond Norine" t:congressional_full_name="Cheri Bustos" t:agency_name="Department of Natural Resources" t:city=Astoria m:floors_below_grade=0 m:rep_dist=93 m:square_footage=144 m:congress_dist=17 m:total_floors=1 m:floors_above_grade=1 m:year_constructed=1975 m:year_acquired=1975 m:senate_dist=47

series e:utd5-tdr2 d:2017-02-27T14:54:31.000Z t:bldg_status="In Use" t:senator_full_name="John M. Sullivan" t:location_name="Anderson Lake Conservation Area - Fulton County" t:usage_description_2=Unusual t:usage_description=Unusual t:zip_code=61501 t:county=Fulton t:usage_description_3="Not provided" t:rep_full_name="Hammond Norine" t:congressional_full_name="Cheri Bustos" t:agency_name="Department of Natural Resources" t:city=Astoria m:floors_below_grade=0 m:rep_dist=93 m:square_footage=144 m:congress_dist=17 m:total_floors=1 m:floors_above_grade=1 m:year_constructed=2004 m:year_acquired=2004 m:senate_dist=47

series e:utd5-tdr2 d:2017-02-27T14:54:31.000Z t:bldg_status="In Use" t:senator_full_name="John M. Sullivan" t:location_name="Anderson Lake Conservation Area - Fulton County" t:usage_description_2=Unusual t:usage_description=Unusual t:zip_code=61501 t:county=Fulton t:usage_description_3="Not provided" t:rep_full_name="Hammond Norine" t:congressional_full_name="Cheri Bustos" t:agency_name="Department of Natural Resources" t:city=Astoria m:floors_below_grade=0 m:rep_dist=93 m:square_footage=144 m:congress_dist=17 m:total_floors=1 m:floors_above_grade=1 m:year_constructed=2004 m:year_acquired=2004 m:senate_dist=47
```

## Meta Commands

```ls
metric m:congress_dist p:integer l:"Congress Dist" t:dataTypeName=number

metric m:rep_dist p:integer l:"Rep Dist" t:dataTypeName=number

metric m:senate_dist p:integer l:"Senate Dist" t:dataTypeName=number

metric m:year_acquired p:integer l:"Year Acquired" t:dataTypeName=number

metric m:year_constructed p:integer l:"Year Constructed" t:dataTypeName=number

metric m:square_footage p:integer l:"Square Footage" t:dataTypeName=number

metric m:total_floors p:integer l:"Total Floors" t:dataTypeName=number

metric m:floors_above_grade p:integer l:"Floors Above Grade" t:dataTypeName=number

metric m:floors_below_grade p:integer l:"Floors Below Grade" t:dataTypeName=number

entity e:utd5-tdr2 l:"Building Inventory" t:attribution="Capital Development Board" t:url=https://data.illinois.gov/api/views/utd5-tdr2

property e:utd5-tdr2 t:meta.view v:id=utd5-tdr2 v:category=Housing v:averageRating=0 v:name="Building Inventory" v:attribution="Capital Development Board"

property e:utd5-tdr2 t:meta.view.license v:name="Public Domain"

property e:utd5-tdr2 t:meta.view.owner v:id=stwr-tj4y v:profileImageUrlMedium=/api/users/stwr-tj4y/profile_images/THUMB v:profileImageUrlLarge=/api/users/stwr-tj4y/profile_images/LARGE v:screenName=Scott v:profileImageUrlSmall=/api/users/stwr-tj4y/profile_images/TINY v:displayName=Scott

property e:utd5-tdr2 t:meta.view.tableauthor v:id=stwr-tj4y v:profileImageUrlMedium=/api/users/stwr-tj4y/profile_images/THUMB v:profileImageUrlLarge=/api/users/stwr-tj4y/profile_images/LARGE v:screenName=Scott v:profileImageUrlSmall=/api/users/stwr-tj4y/profile_images/TINY v:roleName=publisher v:displayName=Scott
```

## Top Records

```ls
| :updated_at | agency_name                     | location_name                                   | address            | city     | zip_code | county  | congress_dist | congressional_full_name | rep_dist | rep_full_name     | senate_dist | senator_full_name | bldg_status | year_acquired | year_constructed | square_footage | total_floors | floors_above_grade | floors_below_grade | usage_description | usage_description_2 | usage_description_3 | 
| =========== | =============================== | =============================================== | ================== | ======== | ======== | ======= | ============= | ======================= | ======== | ================= | =========== | ================= | =========== | ============= | ================ | ============== | ============ | ================== | ================== | ================= | =================== | =================== | 
| 1488207271  | Department of Natural Resources | Anderson Lake Conservation Area - Fulton County | Anderson Lake C.a. | Astoria  | 61501    | Fulton  | 17            | Cheri Bustos            | 93       | Hammond Norine    | 47          | John M. Sullivan  | In Use      | 1975          | 1975             | 144            | 1            | 1                  | 0                  | Unusual           | Unusual             | Not provided        | 
| 1488207271  | Department of Natural Resources | Anderson Lake Conservation Area - Fulton County | Anderson Lake C.a. | Astoria  | 61501    | Fulton  | 17            | Cheri Bustos            | 93       | Hammond Norine    | 47          | John M. Sullivan  | In Use      | 2004          | 2004             | 144            | 1            | 1                  | 0                  | Unusual           | Unusual             | Not provided        | 
| 1488207271  | Department of Natural Resources | Anderson Lake Conservation Area - Fulton County | Anderson Lake C.a. | Astoria  | 61501    | Fulton  | 17            | Cheri Bustos            | 93       | Hammond Norine    | 47          | John M. Sullivan  | In Use      | 2004          | 2004             | 144            | 1            | 1                  | 0                  | Unusual           | Unusual             | Not provided        | 
| 1488207271  | Department of Natural Resources | Anderson Lake Conservation Area - Fulton County | Anderson Lake C.a. | Astoria  | 61501    | Fulton  | 17            | Cheri Bustos            | 93       | Hammond Norine    | 47          | John M. Sullivan  | In Use      | 2004          | 2004             | 144            | 1            | 1                  | 0                  | Unusual           | Unusual             | Not provided        | 
| 1488207271  | Department of Natural Resources | Anderson Lake Conservation Area - Fulton County | Anderson Lake C.a. | Astoria  | 61501    | Fulton  | 17            | Cheri Bustos            | 93       | Hammond Norine    | 47          | John M. Sullivan  | In Use      | 2004          | 2004             | 144            | 1            | 1                  | 0                  | Unusual           | Unusual             | Not provided        | 
| 1488207271  | Department of Natural Resources | Anderson Lake Conservation Area - Fulton County | Anderson Lake C.a. | Astoria  | 61501    | Fulton  | 17            | Cheri Bustos            | 93       | Hammond Norine    | 47          | John M. Sullivan  | In Use      | 2004          | 2004             | 144            | 1            | 1                  | 0                  | Unusual           | Unusual             | Not provided        | 
| 1488207271  | Department of Natural Resources | Dixon Springs State Park - Pope County          | Rr #2              | Golconda | 62938    | Pope    | 15            | John Shimkus            | 118      | Phelps Brandon W. | 59          | Gary Forby        | In Use      | 2000          | 2000             | 120            | 1            | 1                  | 0                  | Unusual           | Unusual             | Not provided        | 
| 1488207271  | Department of Natural Resources | Dixon Springs State Park - Pope County          | Rr #2              | Golconda | 62938    | Pope    | 15            | John Shimkus            | 118      | Phelps Brandon W. | 59          | Gary Forby        | In Use      | 2000          | 2000             | 120            | 1            | 1                  | 0                  | Unusual           | Unusual             | Not provided        | 
| 1488207271  | Department of Natural Resources | Matthiessen State Park - LaSalle County         | R. R. 178, Box 509 | Utica    | 61373    | LaSalle | 16            | Adam Kinzinger          | 76       | Mautino Frank J.  | 38          | Sue Rezin         | In Use      | 2000          | 2000             | 144            | 1            | 1                  | 0                  | Unusual           | Unusual             | Not provided        | 
| 1488207271  | Department of Natural Resources | Matthiessen State Park - LaSalle County         | R. R. 178, Box 509 | Utica    | 61373    | LaSalle | 16            | Adam Kinzinger          | 76       | Mautino Frank J.  | 38          | Sue Rezin         | In Use      | 2000          | 2000             | 144            | 1            | 1                  | 0                  | Unusual           | Unusual             | Not provided        | 
```