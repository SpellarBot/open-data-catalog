# WiredNYC ? Certified Buildings

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/wirednyc-certified-buildings-6e70f) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/37it-gmcp) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/37it-gmcp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/37it-gmcp/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 37it-gmcp |
| Name | WiredNYC ? Certified Buildings |
| Attribution | NYC EDC |
| Category | NYC BigApps |
| Tags | wirednyc, broadband, buildings, access, connectivity, nycedc, nyc bigapps, bigapps |
| Created | 2014-06-13T14:49:28Z |
| Publication Date | 2014-06-13T14:52:52Z |

## Description

This dataset contains information for buildings that have completed the certification process. These buildings are all publicly viewable on the WiredNYC website (www.wiredscore.com)

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
series e:37it-gmcp d:2014-06-13T07:49:40.000Z t:building_name="666 Fifth Avenue" t:bbl=1-1268-1102 t:isps_1="5 or more" t:riser_space_for_current_providers=Yes t:designated_telecom_utility_space="Combination of open, shared, and dedicated  space" t:new_service_providers=Yes t:fiber_connection=Yes t:signed_poes="Yes - for installed connections" t:coax_cable_connections=Yes t:riser_space_for_additional_providers=Yes t:fiber_distribution="Partial Distribution (some floors)" t:diverse_riser_locations=Yes t:of_carriers="5 or more" t:multiple_points_of_entry=Yes t:borough=Manhattan t:satellite_fixed_wireless_connection=Yes t:agreements=No t:certification_class=Platinum t:street_address="666 5 AVENUE" t:isps_2="Zayo,Verizon FIOS,Verizon,Time Warner Cable,Rainbow Broadband,Lightpath,Lightower,Cogent" t:additional_telecom_space=Yes m:bble=1012681102

series e:37it-gmcp d:2014-06-13T07:49:40.000Z t:building_name="One New York Plaza" t:bbl=1-4-1010 t:isps_1="5 or more" t:riser_space_for_current_providers=Yes t:designated_telecom_utility_space="Combination of open, shared, and dedicated  space" t:new_service_providers=Yes t:fiber_connection=Yes t:signed_poes="Yes - for installed connections" t:coax_cable_connections=Yes t:riser_space_for_additional_providers=Yes t:fiber_distribution="Full Distribution (all floors)" t:diverse_riser_locations=Yes t:of_carriers="5 or more" t:multiple_points_of_entry=Yes t:borough=Manhattan t:satellite_fixed_wireless_connection=No t:agreements=Yes t:certification_class=Platinum t:street_address="1 WATER STREET" t:isps_2="Zayo,Verizon,Time Warner Cable,Lightpath,Lightower,Cogent,AT&T" t:additional_telecom_space=Yes m:bble=1000041010

series e:37it-gmcp d:2014-06-13T07:49:40.000Z t:building_name="250 Vesey Street" t:bbl=1-16-150 t:isps_1="5 or more" t:riser_space_for_current_providers=Yes t:designated_telecom_utility_space="Dedicated room" t:new_service_providers=Yes t:fiber_connection=Yes t:signed_poes="None available" t:coax_cable_connections=Yes t:riser_space_for_additional_providers=Yes t:fiber_distribution="Full Distribution (all floors)" t:diverse_riser_locations=Yes t:of_carriers="5 or more" t:multiple_points_of_entry=No t:borough=Manhattan t:satellite_fixed_wireless_connection=No t:agreements=Yes t:certification_class=Gold t:street_address="250 VESEY PLACE" t:isps_2="Zayo,Verizon,Time Warner Cable,Lightower,AT&T" t:additional_telecom_space=Yes m:bble=1000160150
```

## Meta Commands

```ls
metric m:bble p:integer l:BBLE t:dataTypeName=number

entity e:37it-gmcp l:"WiredNYC ? Certified Buildings" t:attribution="NYC EDC" t:url=https://data.cityofnewyork.us/api/views/37it-gmcp

property e:37it-gmcp t:meta.view v:id=37it-gmcp v:category="NYC BigApps" v:averageRating=0 v:name="WiredNYC ? Certified Buildings" v:attribution="NYC EDC"

property e:37it-gmcp t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:37it-gmcp t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | bble       | bbl         | borough   | building_name      | street_address            | certification_class | of_carriers | coax_cable_connections | fiber_connection | satellite_fixed_wireless_connection | fiber_distribution                 | isps_1    | multiple_points_of_entry | designated_telecom_utility_space                 | additional_telecom_space | riser_space_for_current_providers | riser_space_for_additional_providers | diverse_riser_locations | signed_poes                     | agreements | new_service_providers | isps_2                                                                                   | 
| =========== | ========== | =========== | ========= | ================== | ========================= | =================== | =========== | ====================== | ================ | =================================== | ================================== | ========= | ======================== | ================================================ | ======================== | ================================= | ==================================== | ======================= | =============================== | ========== | ===================== | ======================================================================================== | 
| 1402645780  | 1012681102 | 1-1268-1102 | Manhattan | 666 Fifth Avenue   | 666 5 AVENUE              | Platinum            | 5 or more   | Yes                    | Yes              | Yes                                 | Partial Distribution (some floors) | 5 or more | Yes                      | Combination of open, shared, and dedicated space | Yes                      | Yes                               | Yes                                  | Yes                     | Yes - for installed connections | No         | Yes                   | Zayo,Verizon FIOS,Verizon,Time Warner Cable,Rainbow Broadband,Lightpath,Lightower,Cogent | 
| 1402645780  | 1000041010 | 1-4-1010    | Manhattan | One New York Plaza | 1 WATER STREET            | Platinum            | 5 or more   | Yes                    | Yes              | No                                  | Full Distribution (all floors)     | 5 or more | Yes                      | Combination of open, shared, and dedicated space | Yes                      | Yes                               | Yes                                  | Yes                     | Yes - for installed connections | Yes        | Yes                   | Zayo,Verizon,Time Warner Cable,Lightpath,Lightower,Cogent,AT&T                           | 
| 1402645780  | 1000160150 | 1-16-150    | Manhattan | 250 Vesey Street   | 250 VESEY PLACE           | Gold                | 5 or more   | Yes                    | Yes              | No                                  | Full Distribution (all floors)     | 5 or more | No                       | Dedicated room                                   | Yes                      | Yes                               | Yes                                  | Yes                     | None available                  | Yes        | Yes                   | Zayo,Verizon,Time Warner Cable,Lightower,AT&T                                            | 
| 1402645780  | 1000160125 | 1-16-125    | Manhattan | 225 Liberty Street | 225 LIBERTY STREET        | Gold                | 5 or more   | Yes                    | Yes              | No                                  | Full Distribution (all floors)     | 5 or more | Yes                      | Combination of open, shared, and dedicated space | Yes                      | Yes                               | Yes                                  | Yes                     | None available                  | Yes        | Yes                   | Verizon,Time Warner Cable,Lightpath,Lightower,Cogent,AT&T,Abovenet                       | 
| 1402645780  | 1000160120 | 1-16-120    | Manhattan | 200 Liberty Street | 200 LIBERTY STREET        | Platinum            | 5 or more   | Yes                    | Yes              | No                                  | Full Distribution (all floors)     | 5 or more | Yes                      | Dedicated room                                   | Yes                      | Yes                               | Yes                                  | Yes                     | Yes - for installed connections | Yes        | Yes                   | Zayo,Verizon,Time Warner Cable,Sidera,Level(3),Cogent,AT&T                               | 
| 1402645780  | 1000627501 | 1-62-7501   | Manhattan | One Liberty Plaza  | 1 LIBERTY PLAZA           | Platinum            | 5 or more   | Yes                    | Yes              | No                                  | Full Distribution (all floors)     | 5 or more | Yes                      | Combination of open, shared, and dedicated space | Yes                      | Yes                               | Yes                                  | Yes                     | Yes - for installed connections | Yes        | Yes                   | Zayo,Verizon,Time Warner Cable,Lightower,Cogent,AT&T                                     | 
| 1402645780  |            | 1-1276-58   | Manhattan | 300 Madison Avenue | 300 MADISON AVENUE        | Gold                | 5 or more   | Yes                    | Yes              | No                                  | Full Distribution (all floors)     | 5 or more | Yes                      | Dedicated room                                   | Yes                      | Yes                               | Yes                                  | Yes                     | Yes - for installed connections | Yes        | Yes                   | Verizon,Time Warner Cable,Sprint,Lightpath,Lightower,AT&T                                | 
| 1402645780  |            | 1-1258-9    | Manhattan | Grace Building     | 1114 AVENUE OF THE AMERIC | Platinum            | 5 or more   | Yes                    | Yes              | No                                  | Full Distribution (all floors)     | 5 or more | Yes                      | Combination of open, shared, and dedicated space | Yes                      | Yes                               | Yes                                  | Yes                     | Yes - for installed connections | Yes        | Yes                   | Verizon,Time Warner Cable,Lightpath,Lightower,Cogent,AT&T,Abovenet                       | 
| 1402645780  |            | 1-1301-1    | Manhattan | 245 Park Avenue    | 245 PARK AVENUE           | Platinum            | 5 or more   | Yes                    | Yes              | No                                  | Full Distribution (all floors)     | 5 or more | Yes                      | Dedicated room                                   | Yes                      | Yes                               | Yes                                  | Yes                     | Yes - for installed connections | Yes        | Yes                   | Verizon,Time Warner Cable,Lightpath,Level(3),Cogent,Abovenet                             | 
| 1402645780  | 1010350017 | 1-1035-17   | Manhattan | The Plant          | 321 WEST 44 STREET        | Platinum            | 3           | Yes                    | Yes              | Yes                                 | Full Distribution (all floors)     | 5 or more | Yes                      | Combination of open, shared, and dedicated space | Yes                      | Yes                               | Yes                                  | Yes                     | None available                  | Yes        | Yes                   | Verizon FIOS,Verizon,Time Warner Cable,Broadview,AT&T                                    | 
```