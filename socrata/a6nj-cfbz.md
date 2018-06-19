# WiredNYC ? All Buildings Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/wirednyc-all-buildings-data-5db2c) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/a6nj-cfbz) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/a6nj-cfbz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/a6nj-cfbz/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | a6nj-cfbz |
| Name | WiredNYC ? All Buildings Data |
| Attribution | NYC EDC |
| Category | NYC BigApps |
| Tags | wirednyc, broadband, buildings, access, connectivity, nycedc, nyc bigapps, bigapps |
| Created | 2014-06-13T15:05:42Z |
| Publication Date | 2014-06-16T14:20:40Z |

## Description

This dataset contains building information for all buildings that have completed a WiredNYC survey.  This includes buildings that have opted-out from displaying their profiles publicly.  Therefore, the building-specific data (e.g. building address) provided is anonymous and only linked to the borough the building is located in.

## Columns

```ls
| Included | Schema Type | Field Name                           | Name                                 | Data Type | Render Type |
| ======== | =========== | ==================================== | ==================================== | ========= | =========== |
| No       | time        | :updated_at                          | updated_at                           | meta_data | meta_data   |
| Yes      | series tag  | building_id                          | Building_id                          | text      | text        |
| Yes      | series tag  | borough                              | Borough                              | text      | text        |
| Yes      | series tag  | certification_class                  | Certification Class                  | text      | text        |
| Yes      | series tag  | of_carriers                          | # of Carriers                        | text      | text        |
| Yes      | series tag  | coax_cable_connections               | Coax/Cable Connections               | text      | text        |
| Yes      | series tag  | fiber_connection                     | Fiber Connection                     | text      | text        |
| Yes      | series tag  | satellite_fixed_wireless_connection  | Satellite/Fixed Wireless Connection  | text      | text        |
| Yes      | series tag  | fiber_distribution                   | Fiber Distribution                   | text      | text        |
| Yes      | series tag  | isps_1                               | # ISPs                               | text      | text        |
| Yes      | series tag  | multiple_points_of_entry             | Multiple Points of Entry             | text      | text        |
| Yes      | series tag  | designated_telecom_utility_space     | Designated Telecom Utility Space     | text      | text        |
| Yes      | series tag  | additional_telecom_space             | Additional Telecom Space             | text      | text        |
| Yes      | series tag  | riser_space_for_current_providers    | Riser Space for Current Providers    | text      | text        |
| Yes      | series tag  | riser_space_for_additional_providers | Riser Space for Additional Providers | text      | text        |
| Yes      | series tag  | diverse_riser_locations              | Diverse Riser Locations              | text      | text        |
| Yes      | series tag  | signed_poes                          | Signed POEs                          | text      | text        |
| Yes      | series tag  | agreements                           | Agreements                           | text      | text        |
| Yes      | series tag  | new_service_providers                | New Service Providers                | text      | text        |
| Yes      | series tag  | isps_2                               | ISPs                                 | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:a6nj-cfbz d:2014-06-13T08:05:46.000Z t:isps_1=4 t:riser_space_for_current_providers=No t:designated_telecom_utility_space="Combination of open, shared, and dedicated  space" t:new_service_providers=Yes t:fiber_connection=Yes t:signed_poes="Yes - for installed connections" t:coax_cable_connections=Yes t:building_id=building_1 t:riser_space_for_additional_providers=No t:fiber_distribution="Partial Distribution (some floors)" t:diverse_riser_locations="Does not have two or more diverse riser locations" t:of_carriers=4 t:borough=Manhattan t:multiple_points_of_entry=Yes t:satellite_fixed_wireless_connection=No t:agreements=Yes t:certification_class="Not certified" t:additional_telecom_space=No m:row_number.a6nj-cfbz=1

series e:a6nj-cfbz d:2014-06-13T08:05:46.000Z t:isps_1="5 or more" t:riser_space_for_current_providers=Yes t:designated_telecom_utility_space="Common (shared) room" t:new_service_providers=Yes t:fiber_connection=Yes t:signed_poes="Yes - for installed connections" t:coax_cable_connections=Yes t:building_id=building_2 t:riser_space_for_additional_providers=Yes t:fiber_distribution="Full Distribution (all floors)" t:diverse_riser_locations="Does not have two or more diverse riser locations" t:of_carriers="5 or more" t:borough=Manhattan t:multiple_points_of_entry=No t:satellite_fixed_wireless_connection=No t:agreements=No t:certification_class="Not certified" t:additional_telecom_space=Yes m:row_number.a6nj-cfbz=2

series e:a6nj-cfbz d:2014-06-13T08:05:46.000Z t:isps_1=3 t:riser_space_for_current_providers=Yes t:designated_telecom_utility_space="Dedicated room" t:new_service_providers=Yes t:fiber_connection=Yes t:signed_poes="Yes - for installed connections" t:coax_cable_connections=Yes t:building_id=building_3 t:riser_space_for_additional_providers=Yes t:fiber_distribution="Full Distribution (all floors)" t:diverse_riser_locations="Does not have two or more diverse riser locations" t:of_carriers=4 t:borough=Manhattan t:multiple_points_of_entry=Yes t:satellite_fixed_wireless_connection=No t:agreements=Yes t:certification_class="Not certified" t:isps_2="Verizon,Time Warner Cable,OCG" t:additional_telecom_space=No m:row_number.a6nj-cfbz=3
```

## Meta Commands

```ls
metric m:row_number.a6nj-cfbz p:long l:"Row Number"

entity e:a6nj-cfbz l:"WiredNYC ? All Buildings Data" t:attribution="NYC EDC" t:url=https://data.cityofnewyork.us/api/views/a6nj-cfbz

property e:a6nj-cfbz t:meta.view v:id=a6nj-cfbz v:category="NYC BigApps" v:averageRating=0 v:name="WiredNYC ? All Buildings Data" v:attribution="NYC EDC"

property e:a6nj-cfbz t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:a6nj-cfbz t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | building_id | borough   | certification_class | of_carriers | coax_cable_connections | fiber_connection | satellite_fixed_wireless_connection | fiber_distribution                 | isps_1    | multiple_points_of_entry | designated_telecom_utility_space                 | additional_telecom_space | riser_space_for_current_providers | riser_space_for_additional_providers | diverse_riser_locations                           | signed_poes                     | agreements | new_service_providers | isps_2                                             | 
| =========== | =========== | ========= | =================== | =========== | ====================== | ================ | =================================== | ================================== | ========= | ======================== | ================================================ | ======================== | ================================= | ==================================== | ================================================= | =============================== | ========== | ===================== | ================================================== | 
| 1402646746  | building_1  | Manhattan | Not certified       | 4           | Yes                    | Yes              | No                                  | Partial Distribution (some floors) | 4         | Yes                      | Combination of open, shared, and dedicated space | No                       | No                                | No                                   | Does not have two or more diverse riser locations | Yes - for installed connections | Yes        | Yes                   |                                                    | 
| 1402646746  | building_2  | Manhattan | Not certified       | 5 or more   | Yes                    | Yes              | No                                  | Full Distribution (all floors)     | 5 or more | No                       | Common (shared) room                             | Yes                      | Yes                               | Yes                                  | Does not have two or more diverse riser locations | Yes - for installed connections | No         | Yes                   |                                                    | 
| 1402646746  | building_3  | Manhattan | Not certified       | 4           | Yes                    | Yes              | No                                  | Full Distribution (all floors)     | 3         | Yes                      | Dedicated room                                   | No                       | Yes                               | Yes                                  | Does not have two or more diverse riser locations | Yes - for installed connections | Yes        | Yes                   | Verizon,Time Warner Cable,OCG                      | 
| 1402646746  | building_4  | Manhattan | Not certified       | 2           | Yes                    | Yes              | No                                  | Full Distribution (all floors)     | 2         | Yes                      | Combination of open, shared, and dedicated space | Yes                      | Yes                               | Yes                                  | Yes                                               | Yes - for installed connections | Yes        | Yes                   |                                                    | 
| 1402646746  | building_5  | Manhattan | Not certified       | 3           | Yes                    | Yes              | No                                  | Full Distribution (all floors)     | 4         | Yes                      | Common (shared) room                             | No                       | Yes                               | No                                   | Does not have two or more diverse riser locations | None available                  | No         | Yes                   | Verizon,Time Warner Cable,Lightower,Cogent         | 
| 1402646746  | building_6  | Manhattan | Not certified       |             | No                     | No               | No                                  |                                    |           |                          |                                                  |                          | No                                | No                                   |                                                   |                                 |            |                       |                                                    | 
| 1402646746  | building_7  | Manhattan | Not certified       | 3           | Yes                    | Yes              | No                                  | Full Distribution (all floors)     | 3         | Yes                      | Hallway/Open Space                               | Yes                      | Yes                               | Yes                                  | Does not have two or more diverse riser locations | Yes - for installed connections | No         | Yes                   | Other,Verizon FIOS,Verizon,Time Warner Cable       | 
| 1402646746  | building_8  | Manhattan | Not certified       | 1           | Yes                    | Yes              | Yes                                 | Full Distribution (all floors)     | 3         | Yes                      | Dedicated room                                   | Yes                      | Yes                               | No                                   | Yes                                               | Yes - for installed connections | Yes        | Yes                   | Century Link                                       | 
| 1402646746  | building_9  | Manhattan | Platinum            | 5 or more   | Yes                    | Yes              | No                                  | Full Distribution (all floors)     | 5 or more | Yes                      | Common (shared) room                             | Yes                      | Yes                               | Yes                                  | Yes                                               | Yes - for installed connections | Yes        | Yes                   | Zayo,Verizon,TW Telecom,Lightpath,Cogent,Broadview | 
| 1402646746  | building_10 | Manhattan | Not certified       | 3           | Yes                    | Yes              | No                                  | Full Distribution (all floors)     | 3         | Yes                      | Dedicated room                                   | Yes                      | Yes                               | Yes                                  | Yes                                               | Yes - for installed connections | Yes        | Yes                   | Verizon,Time Warner Cable,Cogent                   | 
```