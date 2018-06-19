# Bike Racks

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bike-racks-53162) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/cbyb-69xx) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/cbyb-69xx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/cbyb-69xx/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | cbyb-69xx |
| Name | Bike Racks |
| Attribution | City of Chicago |
| Category | Transportation |
| Tags | bicycling, gis, sustainability |
| Created | 2010-12-22T18:58:04Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Description

Bike racks in Chicago. To view or use the attachment files, compression software and special GIS software, such as ESRI ArcGIS, is required.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| No       | time           | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | series tag     | rackid         | RackID         | text      | number      |
| No       |                | address        | Address        | text      | text        |
| Yes      | series tag     | ward           | Ward           | text      | number      |
| Yes      | series tag     | community_area | Community Area | text      | number      |
| Yes      | series tag     | community_name | Community Name | text      | text        |
| Yes      | numeric metric | totinstall     | TotInstall     | number    | number      |
| No       |                | latitude       | Latitude       | number    | number      |
| No       |                | longitude      | Longitude      | number    | number      |
| Yes      | numeric metric | historical     | Historical     | number    | number      |
| Yes      | numeric metric | f12            | F12            | number    | number      |
| Yes      | numeric metric | f13            | F13            | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address,latitude,longitude
```

## Data Commands

```ls
series e:cbyb-69xx d:2010-12-22T10:58:05.000Z t:community_name=Loop t:ward=2 t:community_area=32 t:rackid=651 m:f12=41.8781 m:totinstall=1 m:historical=0 m:f13=-87.627495

series e:cbyb-69xx d:2010-12-22T10:58:05.000Z t:community_name="Washington Park" t:ward=3 t:community_area=40 t:rackid=1409 m:f12=41.8019 m:totinstall=1 m:historical=1 m:f13=-87.625808

series e:cbyb-69xx d:2010-12-22T10:58:05.000Z t:community_name=Loop t:ward=42 t:community_area=32 t:rackid=1989 m:f12=41.879382 m:totinstall=3 m:historical=1 m:f13=-87.627517
```

## Meta Commands

```ls
metric m:totinstall p:float l:TotInstall t:dataTypeName=number

metric m:historical p:float l:Historical t:dataTypeName=number

metric m:f12 p:double l:F12 t:dataTypeName=number

metric m:f13 p:float l:F13 t:dataTypeName=number

entity e:cbyb-69xx l:"Bike Racks" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/cbyb-69xx

property e:cbyb-69xx t:meta.view v:id=cbyb-69xx v:category=Transportation v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Bike Racks" v:attribution="City of Chicago"

property e:cbyb-69xx t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:cbyb-69xx t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| :updated_at | rackid | address          | ward | community_area | community_name  | totinstall | latitude  | longitude  | historical | f12       | f13        | 
| =========== | ====== | ================ | ==== | ============== | =============== | ========== | ========= | ========== | ========== | ========= | ========== | 
| 1293015485  | 651    | 1 E Jackson Blvd | 2    | 32             | Loop            | 1.000000   | 41.878100 | -87.627495 | 0.000000   | 41.878100 | -87.627495 | 
| 1293015485  | 1409   | 1 E 51st St      | 3    | 40             | Washington Park | 1.000000   | 41.801900 | -87.625808 | 1.000000   | 41.801900 | -87.625808 | 
| 1293015485  | 1989   | 1 E Adams St     | 42   | 32             | Loop            | 3.000000   | 41.879382 | -87.627517 | 1.000000   | 41.879382 | -87.627517 | 
| 1293015485  | 6379   | 1 E Erie St      | 42   | 8              | Near North Side | 1.000000   | 41.893974 | -87.627945 | 1.000000   | 41.893974 | -87.627945 | 
| 1293015485  | 3058   | 1 E Jackson Blvd | 2    | 32             | Loop            | 2.000000   | 41.878100 | -87.627495 | 1.000000   | 41.878100 | -87.627495 | 
| 1293015485  | 5019   | 1 E Jackson Blvd | 2    | 32             | Loop            | 2.000000   | 41.878100 | -87.627495 | 1.000000   | 41.878100 | -87.627495 | 
| 1293015485  | 4004   | 1 E Wacker Dr    | 42   | 32             | Loop            | 3.000000   | 41.886752 | -87.627907 | 1.000000   | 41.886752 | -87.627907 | 
| 1293015485  | 6162   | 1 E Wacker Dr    | 42   | 32             | Loop            | 1.000000   | 41.886752 | -87.627907 | 1.000000   | 41.886752 | -87.627907 | 
| 1293015485  | 2429   | 1 N Clark St     | 42   | 32             | Loop            | 2.000000   | 41.882059 | -87.630800 | 1.000000   | 41.882059 | -87.630800 | 
| 1293015485  | 957    | 1 N Franklin St  | 42   | 32             | Loop            | 1.000000   | 41.882014 | -87.635242 | 0.000000   | 41.882014 | -87.635242 | 
```