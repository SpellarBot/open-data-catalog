# WiredNYC ? Participating Buildings

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/wirednyc-participating-buildings-734ec) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/cfzn-4iza) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/cfzn-4iza/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/cfzn-4iza/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | cfzn-4iza |
| Name | WiredNYC ? Participating Buildings |
| Attribution | NYC EDC |
| Category | NYC BigApps |
| Tags | wirednyc, broadband, buildings, access, connectivity, nycedc, nyc bigapps, bigapps |
| Created | 2014-06-13T14:58:42Z |
| Publication Date | 2014-06-13T15:03:16Z |

## Description

This dataset contains information for certified and non-certified buildings that are participating in the WiredNYC program. These buildings are all publicly viewable on the WiredNYC website.

## Columns

```ls
| Included | Schema Type    | Field Name                           | Name                                 | Data Type | Render Type |
| ======== | ============== | ==================================== | ==================================== | ========= | =========== |
| No       | time           | :updated_at                          | updated_at                           | meta_data | meta_data   |
| Yes      | numeric metric | bble                                 | BBLE                                 | number    | number      |
| Yes      | series tag     | bbl                                  | BBL                                  | text      | text        |
| Yes      | series tag     | borough                              | Borough                              | text      | text        |
| Yes      | series tag     | building_name                        | Building Name                        | text      | text        |
| Yes      | series tag     | street_address                       | Street Address                       | text      | text        |
| Yes      | series tag     | certification_class                  | Certification Class                  | text      | text        |
| Yes      | series tag     | of_carriers                          | # of Carriers                        | text      | text        |
| Yes      | series tag     | coax_cable_connections               | Coax/Cable Connections               | text      | text        |
| Yes      | series tag     | fiber_connection                     | Fiber Connection                     | text      | text        |
| Yes      | series tag     | satellite_fixed_wireless_connection  | Satellite/Fixed Wireless Connection  | text      | text        |
| Yes      | series tag     | fiber_distribution                   | Fiber Distribution                   | text      | text        |
| Yes      | series tag     | isps_1                               | # ISPs                               | text      | text        |
| Yes      | series tag     | multiple_points_of_entry             | Multiple Points of Entry             | text      | text        |
| Yes      | series tag     | designated_telecom_utility_space     | Designated Telecom Utility Space     | text      | text        |
| Yes      | series tag     | additional_telecom_space             | Additional Telecom Space             | text      | text        |
| Yes      | series tag     | riser_space_for_current_providers    | Riser Space for Current Providers    | text      | text        |
| Yes      | series tag     | riser_space_for_additional_providers | Riser Space for Additional Providers | text      | text        |
| Yes      | series tag     | diverse_riser_locations              | Diverse Riser Locations              | text      | text        |
| Yes      | series tag     | signed_poes                          | Signed POEs                          | text      | text        |
| Yes      | series tag     | agreements                           | Agreements                           | text      | text        |
| Yes      | series tag     | new_service_providers                | New Service Providers                | text      | text        |
| Yes      | series tag     | isps_2                               | ISPs                                 | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:cfzn-4iza d:2014-06-13T07:58:46.000Z t:building_name="1370 Broadway" t:bbl=1-812-49 t:isps_1=4 t:riser_space_for_current_providers=No t:designated_telecom_utility_space="Combination of open, shared, and dedicated  space" t:new_service_providers=Yes t:fiber_connection=Yes t:signed_poes="Yes - for installed connections" t:coax_cable_connections=Yes t:riser_space_for_additional_providers=No t:fiber_distribution="Partial Distribution (some floors)" t:diverse_riser_locations="Does not have two or more diverse riser locations" t:of_carriers=4 t:multiple_points_of_entry=Yes t:borough=Manhattan t:satellite_fixed_wireless_connection=No t:agreements=Yes t:certification_class="Not certified" t:street_address="1370 BROADWAY" t:additional_telecom_space=No m:bble=1008120049

series e:cfzn-4iza d:2014-06-13T07:58:46.000Z t:building_name="149 Fifth Avenue" t:bbl=1-850-1 t:isps_1="5 or more" t:riser_space_for_current_providers=Yes t:designated_telecom_utility_space="Common (shared) room" t:new_service_providers=Yes t:fiber_connection=Yes t:signed_poes="Yes - for installed connections" t:coax_cable_connections=Yes t:riser_space_for_additional_providers=Yes t:fiber_distribution="Full Distribution (all floors)" t:diverse_riser_locations="Does not have two or more diverse riser locations" t:of_carriers="5 or more" t:multiple_points_of_entry=No t:borough=Manhattan t:satellite_fixed_wireless_connection=No t:agreements=No t:certification_class="Not certified" t:street_address="149 5 AVENUE" t:additional_telecom_space=Yes m:bble=1008500001

series e:cfzn-4iza d:2014-06-13T07:58:46.000Z t:building_name="162 Fifth Ave" t:bbl=1-823-37 t:isps_1=3 t:riser_space_for_current_providers=Yes t:designated_telecom_utility_space="Dedicated room" t:new_service_providers=Yes t:fiber_connection=Yes t:signed_poes="Yes - for installed connections" t:coax_cable_connections=Yes t:riser_space_for_additional_providers=Yes t:fiber_distribution="Full Distribution (all floors)" t:diverse_riser_locations="Does not have two or more diverse riser locations" t:of_carriers=4 t:multiple_points_of_entry=Yes t:borough=Manhattan t:satellite_fixed_wireless_connection=No t:agreements=Yes t:certification_class="Not certified" t:street_address="162 5 AVENUE" t:isps_2="Verizon,Time Warner Cable,OCG" t:additional_telecom_space=No m:bble=1008230037
```

## Meta Commands

```ls
metric m:bble p:long l:BBLE t:dataTypeName=number

entity e:cfzn-4iza l:"WiredNYC ? Participating Buildings" t:attribution="NYC EDC" t:url=https://data.cityofnewyork.us/api/views/cfzn-4iza

property e:cfzn-4iza t:meta.view v:id=cfzn-4iza v:category="NYC BigApps" v:averageRating=0 v:name="WiredNYC ? Participating Buildings" v:attribution="NYC EDC"

property e:cfzn-4iza t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:cfzn-4iza t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | bble       | bbl          | borough   | building_name         | street_address           | certification_class | of_carriers | coax_cable_connections | fiber_connection | satellite_fixed_wireless_connection | fiber_distribution                 | isps_1    | multiple_points_of_entry | designated_telecom_utility_space                 | additional_telecom_space | riser_space_for_current_providers | riser_space_for_additional_providers | diverse_riser_locations                           | signed_poes                     | agreements | new_service_providers | isps_2                                       | 
| =========== | ========== | ============ | ========= | ===================== | ======================== | =================== | =========== | ====================== | ================ | =================================== | ================================== | ========= | ======================== | ================================================ | ======================== | ================================= | ==================================== | ================================================= | =============================== | ========== | ===================== | ============================================ | 
| 1402646326  | 1008120049 | 1-812-49     | Manhattan | 1370 Broadway         | 1370 BROADWAY            | Not certified       | 4           | Yes                    | Yes              | No                                  | Partial Distribution (some floors) | 4         | Yes                      | Combination of open, shared, and dedicated space | No                       | No                                | No                                   | Does not have two or more diverse riser locations | Yes - for installed connections | Yes        | Yes                   |                                              | 
| 1402646326  | 1008500001 | 1-850-1      | Manhattan | 149 Fifth Avenue      | 149 5 AVENUE             | Not certified       | 5 or more   | Yes                    | Yes              | No                                  | Full Distribution (all floors)     | 5 or more | No                       | Common (shared) room                             | Yes                      | Yes                               | Yes                                  | Does not have two or more diverse riser locations | Yes - for installed connections | No         | Yes                   |                                              | 
| 1402646326  | 1008230037 | 1-823-37     | Manhattan | 162 Fifth Ave         | 162 5 AVENUE             | Not certified       | 4           | Yes                    | Yes              | No                                  | Full Distribution (all floors)     | 3         | Yes                      | Dedicated room                                   | No                       | Yes                               | Yes                                  | Does not have two or more diverse riser locations | Yes - for installed connections | Yes        | Yes                   | Verizon,Time Warner Cable,OCG                | 
| 1402646326  | 1008070039 | 1-807-39     | Manhattan |                       | 875 AVENUE OF THE AMERIC | Not certified       | 2           | Yes                    | Yes              | No                                  | Full Distribution (all floors)     | 2         | Yes                      | Combination of open, shared, and dedicated space | Yes                      | Yes                               | Yes                                  | Yes                                               | Yes - for installed connections | Yes        | Yes                   |                                              | 
| 1402646326  | 1012620001 | 1-1262-1     | Manhattan |                       | 1180 AVENUE OF THE AMER  | Not certified       | 3           | Yes                    | Yes              | No                                  | Full Distribution (all floors)     | 4         | Yes                      | Common (shared) room                             | No                       | Yes                               | No                                   | Does not have two or more diverse riser locations | None available                  | No         | Yes                   | Verizon,Time Warner Cable,Lightower,Cogent   | 
| 1402646326  | 1008690061 | 1-869-61     | Manhattan | 280 Madison           | 280 MADISON AVENUE       | Not certified       | 3           | Yes                    | Yes              | No                                  | Full Distribution (all floors)     | 3         | Yes                      | Hallway/Open Space                               | Yes                      | Yes                               | Yes                                  | Does not have two or more diverse riser locations | Yes - for installed connections | No         | Yes                   | Other,Verizon FIOS,Verizon,Time Warner Cable | 
| 1402646326  |            | 1-99999-9999 | Manhattan | Testing This Building | 771 10 AVENUE            | Not certified       | 1           | Yes                    | Yes              | Yes                                 | Full Distribution (all floors)     | 3         | Yes                      | Dedicated room                                   | Yes                      | Yes                               | No                                   | Yes                                               | Yes - for installed connections | Yes        | Yes                   | Century Link                                 | 
| 1402646326  | 1013100063 | 1-1310-63    | Manhattan | 126 East 56th Street  | 126 EAST 56 STREET       | Not certified       | 3           | Yes                    | Yes              | No                                  | Full Distribution (all floors)     | 3         | Yes                      | Dedicated room                                   | Yes                      | Yes                               | Yes                                  | Yes                                               | Yes - for installed connections | Yes        | Yes                   | Verizon,Time Warner Cable,Cogent             | 
| 1402646326  | 1000290001 | 1/29/2001    | Manhattan | 85 Broad St.          | 85 BROAD STREET          | Not certified       | 3           | Yes                    | Yes              | No                                  | Partial Distribution (some floors) | 4         | Yes                      | Dedicated room                                   | Yes                      | Yes                               | Yes                                  | Yes                                               | Yes - for installed connections | Yes        | Yes                   | Verizon,TW Telecom,Time Warner Cable,AT&T    | 
| 1402646326  | 1012670041 | 1-1267-41    | Manhattan | 650 Fifth Ave         | 650 5 AVENUE             | Not certified       | 3           | Yes                    | Yes              | No                                  | Full Distribution (all floors)     | 5 or more | No                       | Dedicated room                                   | Yes                      | Yes                               | Yes                                  | Does not have two or more diverse riser locations | Yes - for installed connections | No         | Yes                   | Other,Verizon,Time Warner Cable,AT&T         | 
```