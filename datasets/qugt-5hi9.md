# Motorized Access Trails

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/motorized-access-trails) |
| Metadata | [Link](https://data.ny.gov/api/views/qugt-5hi9) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/qugt-5hi9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/qugt-5hi9/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | qugt-5hi9 |
| Name | Motorized Access Trails |
| Attribution | New York State Department of Environmental Conservation |
| Category | Recreation |
| Tags | motor, vehicle, access, disability |
| Created | 2013-02-15T18:12:41Z |
| Publication Date | 2013-03-01T22:43:35Z |

## Description

This data shows the location of transportation corridors on state lands that are open to motor vehicle use by people with certain mobility impairment disabilities who possess a valid Department of Environmental Conservation -issued "Motorized Access Program for People with Disabilities" permit.

## Columns

```ls
| Included | Schema Type | Field Name  | Name                                   | Data Type | Render Type |
| ======== | =========== | =========== | ====================================== | ========= | =========== |
| No       | time        | :updated_at | updated_at                             | meta_data | meta_data   |
| Yes      | series tag  | facility    | Facility                               | text      | text        |
| Yes      | series tag  | name        | Name                                   | text      | text        |
| Yes      | series tag  | foot        | Foot Travel                            | text      | text        |
| Yes      | series tag  | horse       | Horse Travel                           | text      | text        |
| Yes      | series tag  | bike        | Mountain Bike                          | text      | text        |
| Yes      | series tag  | snowmb      | Snowmobile                             | text      | text        |
| Yes      | series tag  | accessible  | Accessible                             | text      | text        |
| Yes      | series tag  | mappwd      | Disability Permit Motor Vehicle Travel | text      | text        |
| Yes      | series tag  | fac_url     | Facility URL                           | url       | url         |
| No       |             | x           | Longitude                              | number    | number      |
| No       |             | y           | Latitude                               | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = x,y
```

## Data Commands

```ls
series e:qugt-5hi9 d:2013-02-20T18:44:25.000Z t:mappwd=Y t:bike=Y t:facility="SUGAR HILL STATE FOREST" t:fac_url=http://www.dec.ny.gov/lands/37446.html t:foot=Y t:name=ONONDAGA t:snowmb=Y t:horse=Y t:accessible=N m:row_number.qugt-5hi9=1

series e:qugt-5hi9 d:2013-02-20T18:44:25.000Z t:mappwd=Y t:bike=Y t:facility="SUGAR HILL STATE FOREST" t:fac_url=http://www.dec.ny.gov/lands/37446.html t:foot=Y t:name=SENECA t:snowmb=Y t:horse=Y t:accessible=N m:row_number.qugt-5hi9=2

series e:qugt-5hi9 d:2013-02-20T18:44:25.000Z t:mappwd=Y t:bike=Y t:facility="COYLE HILL STATE FOREST" t:fac_url=http://www.dec.ny.gov/lands/49443.html t:foot=Y t:name="BLUE TRAIL" t:snowmb=Y t:horse=Y t:accessible=N m:row_number.qugt-5hi9=3
```

## Meta Commands

```ls
metric m:row_number.qugt-5hi9 p:long l:"Row Number"

entity e:qugt-5hi9 l:"Motorized Access Trails" t:attribution="New York State Department of Environmental Conservation" t:url=https://data.ny.gov/api/views/qugt-5hi9

property e:qugt-5hi9 t:meta.view v:id=qugt-5hi9 v:category=Recreation v:attributionLink=http://www.dec.ny.gov/outdoor/2574.html v:averageRating=0 v:name="Motorized Access Trails" v:attribution="New York State Department of Environmental Conservation"

property e:qugt-5hi9 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:qugt-5hi9 t:meta.view.tableauthor v:id=jtha-fqbi v:screenName="OPEN DATA NY Admin" v:roleName=publisher v:displayName="OPEN DATA NY Admin"

property e:qugt-5hi9 t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | facility                | name                         | foot | horse | bike | snowmb | accessible | mappwd | fac_url                                        | x              | y             | 
| =========== | ======================= | ============================ | ==== | ===== | ==== | ====== | ========== | ====== | ============================================== | ============== | ============= | 
| 1361385865  | SUGAR HILL STATE FOREST | ONONDAGA                     | Y    | Y     | Y    | Y      | N          | Y      | [http://www.dec.ny.gov/lands/37446.html, null] | -77.0048741235 | 42.3860072027 | 
| 1361385865  | SUGAR HILL STATE FOREST | SENECA                       | Y    | Y     | Y    | Y      | N          | Y      | [http://www.dec.ny.gov/lands/37446.html, null] | -77.0051062622 | 42.3851371422 | 
| 1361385865  | COYLE HILL STATE FOREST | BLUE TRAIL                   | Y    | Y     | Y    | Y      | N          | Y      | [http://www.dec.ny.gov/lands/49443.html, null] | -78.1076761589 | 42.2699150753 | 
| 1361385865  | COYLE HILL STATE FOREST | BLUE TRAIL                   | Y    | Y     | Y    | Y      | N          | Y      | [http://www.dec.ny.gov/lands/49443.html, null] | -78.101814354  | 42.2592493766 | 
| 1361385865  | COYLE HILL STATE FOREST | YELLOW TRAIL                 | Y    | Y     | Y    | Y      | N          | Y      | [http://www.dec.ny.gov/lands/49443.html, null] | -78.1167048987 | 42.2574134745 | 
| 1361385865  | COYLE HILL STATE FOREST | RED TRAIL                    | Y    | Y     | N    | Y      | N          | Y      | [http://www.dec.ny.gov/lands/49443.html, null] | -78.1015006647 | 42.2436863057 | 
| 1361385865  | COYLE HILL STATE FOREST | YELLOW TRAIL                 | Y    | Y     | Y    | Y      | N          | Y      | [http://www.dec.ny.gov/lands/49443.html, null] | -78.1104744413 | 42.2612612352 | 
| 1361385865  | COYLE HILL STATE FOREST | YELLOW TRAIL                 | Y    | Y     | Y    | Y      | N          | Y      | [http://www.dec.ny.gov/lands/49443.html, null] | -78.11196073   | 42.2603132502 | 
| 1361385865  | PANAMA STATE FOREST     | WILTSIE ACCESS ROAD - 4-9/10 | N    | N     | N    | N      | N          | Y      | [http://www.dec.ny.gov/lands/42259.html, null] | -79.5030886527 | 42.0529532993 | 
| 1361385865  | COYLE HILL STATE FOREST | YELLOW TRAIL                 | Y    | Y     | Y    | Y      | N          | Y      | [http://www.dec.ny.gov/lands/49443.html, null] | -78.1142476482 | 42.2584701644 | 
```