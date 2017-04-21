# Alternative Fuel Locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/alternative-fuel-locations-e3fed) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/f7f2-ggz5) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/f7f2-ggz5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/f7f2-ggz5/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | f7f2-ggz5 |
| Name | Alternative Fuel Locations |
| Attribution | U.S. Department of Energy |
| Category | Environment & Sustainable Development |
| Tags | sustainability, transportation |
| Created | 2013-04-19T17:48:03Z |
| Publication Date | 2015-10-16T21:08:17Z |

## Description

List of locations in NE Illinois, NW Indiana, and SE Wisconsin where alternative vehicle fuels are available.  For a Chicago-only filtered view, see https://data.cityofchicago.org/d/fi3z-jc3f. For more detailed descriptions of fields, see http://developer.nrel.gov/docs/transportation/alt-fuel-stations-v1 or https://data.cityofchicago.org/developers/docs/alternative-fuel-locations.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type     | Render Type   |
| ======== | ============== | ======================= | ======================= | ============= | ============= |
| No       |                | id                      | ID                      | text          | number        |
| Yes      | series tag     | fuel_type_code          | Fuel Type Code          | text          | text          |
| Yes      | series tag     | station_name            | Station Name            | text          | text          |
| Yes      | series tag     | street_address          | Street Address          | text          | text          |
| Yes      | series tag     | intersection_directions | Intersection Directions | text          | text          |
| Yes      | series tag     | city                    | City                    | text          | text          |
| Yes      | series tag     | state                   | State                   | text          | text          |
| Yes      | series tag     | zip                     | ZIP                     | text          | text          |
| Yes      | series tag     | plus4                   | Plus4                   | text          | text          |
| Yes      | series tag     | station_phone           | Station Phone           | text          | text          |
| Yes      | series tag     | status_code             | Status Code             | text          | text          |
| No       |                | expected_date           | Expected Date           | calendar_date | calendar_date |
| Yes      | series tag     | groups_with_access_code | Groups With Access Code | text          | text          |
| No       |                | access_days_time        | Access Days Time        | text          | text          |
| Yes      | series tag     | cards_accepted          | Cards Accepted          | text          | text          |
| Yes      | series tag     | bd_blends               | BD Blends               | text          | text          |
| Yes      | series tag     | ng_fill_type_code       | NG Fill Type Code       | text          | text          |
| Yes      | series tag     | ng_psi                  | NG PSI                  | text          | text          |
| Yes      | series tag     | ev_level1_evse_num      | EV Level1 EVSE Num      | text          | number        |
| Yes      | series tag     | ev_level2_evse_num      | EV Level2 EVSE Num      | text          | number        |
| Yes      | numeric metric | ev_dc_fast_count        | EV DC Fast Count        | number        | number        |
| Yes      | series tag     | ev_other_info           | EV Other Info           | text          | text          |
| Yes      | series tag     | ev_network              | EV Network              | text          | text          |
| Yes      | series tag     | ev_network_web          | EV Network Web          | url           | url           |
| Yes      | series tag     | geocode_status          | Geocode Status          | text          | text          |
| No       |                | latitude                | Latitude                | number        | number        |
| No       |                | longitude               | Longitude               | number        | number        |
| Yes      | time           | date_last_confirmed     | Date Last Confirmed     | calendar_date | calendar_date |
| No       |                | updated_at              | Updated At              | date          | date          |
| Yes      | series tag     | owner_type_code         | Owner Type Code         | text          | text          |
| Yes      | series tag     | federal_agency_id       | Federal Agency ID       | text          | number        |
| Yes      | series tag     | federal_agency_name     | Federal Agency Name     | text          | text          |
| No       |                | open_date               | Open Date               | calendar_date | calendar_date |
| Yes      | series tag     | hydrogen_status_link    | Hydrogen Status Link    | text          | text          |
| Yes      | series tag     | ng_vehicle_class        | NG Vehicle Class        | text          | text          |
| Yes      | series tag     | lpg_primary             | LPG Primary             | text          | text          |
| Yes      | series tag     | e85_blender_pump        | E85 Blender Pump        | text          | text          |
```

## Time Field

```ls
Value = date_last_confirmed
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = id,access_days_time,latitude,longitude,expected_date,updated_at,open_date
```

## Data Commands

```ls
```

## Meta Commands

```ls
metric m:ev_dc_fast_count p:integer l:"EV DC Fast Count" t:dataTypeName=number

entity e:f7f2-ggz5 l:"Alternative Fuel Locations" t:attribution="U.S. Department of Energy" t:url=https://data.cityofchicago.org/api/views/f7f2-ggz5

property e:f7f2-ggz5 t:meta.view v:id=f7f2-ggz5 v:category="Environment & Sustainable Development" v:attributionLink=http://www.afdc.energy.gov/ v:averageRating=0 v:name="Alternative Fuel Locations" v:attribution="U.S. Department of Energy"

property e:f7f2-ggz5 t:meta.view.owner v:id=3qqc-w7ag v:profileImageUrlMedium=/api/users/3qqc-w7ag/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qqc-w7ag/profile_images/LARGE v:screenName="Tom Schenk Jr" v:profileImageUrlSmall=/api/users/3qqc-w7ag/profile_images/TINY v:lastNotificationSeenAt=1491330280 v:displayName="Tom Schenk Jr"

property e:f7f2-ggz5 t:meta.view.tableauthor v:id=3qqc-w7ag v:profileImageUrlMedium=/api/users/3qqc-w7ag/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qqc-w7ag/profile_images/LARGE v:screenName="Tom Schenk Jr" v:profileImageUrlSmall=/api/users/3qqc-w7ag/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491330280 v:displayName="Tom Schenk Jr"
```

## Top Records

```ls
| id    | fuel_type_code | station_name             | street_address           | intersection_directions                                       | city         | state | zip   | plus4 | station_phone | status_code | expected_date | groups_with_access_code           | access_days_time                             | cards_accepted                         | bd_blends | ng_fill_type_code | ng_psi | ev_level1_evse_num | ev_level2_evse_num | ev_dc_fast_count | ev_other_info | ev_network | ev_network_web | geocode_status | latitude   | longitude   | date_last_confirmed | updated_at | owner_type_code | federal_agency_id | federal_agency_name | open_date           | hydrogen_status_link | ng_vehicle_class | lpg_primary | e85_blender_pump | 
| ===== | ============== | ======================== | ======================== | ============================================================= | ============ | ===== | ===== | ===== | ============= | =========== | ============= | ================================= | ============================================ | ====================================== | ========= | ================= | ====== | ================== | ================== | ================ | ============= | ========== | ============== | ============== | ========== | =========== | =================== | ========== | =============== | ================= | =================== | =================== | ==================== | ================ | =========== | ================ | 
| 13050 | LPG            | AmeriGas                 | 700 County Highway H     | Route 12 exit                                                 | Elkhorn      | WI    | 53121 |       | 262-723-7410  | E           |               | Public                            | 8am-3pm M-F                                  | Cash M V                               |           |                   |        |                    |                    |                  |               |            | [null, null]   | 200-8          | 42.660919  | -88.522923  | 2016-11-02T00:00:00 | 1484682691 | P               |                   |                     |                     |                      |                  | false       |                  | 
| 14121 | LPG            | AmeriGas                 | 1901 Pleasant St         | Near Highway 38                                               | DeKalb       | IL    | 60115 |       | 815-758-5416  | E           |               | Public - Call ahead               | 7am-3:30pm M-F                               | Cash A D M V                           |           |                   |        |                    |                    |                  |               |            | [null, null]   | 200-8          | 41.9328155 | -88.7269657 | 2016-11-02T00:00:00 | 1484682656 | P               |                   |                     |                     |                      |                  | false       |                  | 
| 14122 | LPG            | AmeriGas                 | 4158 Division St         | Roosevelt Rd, west to Oak Ridge, north to Division            | Hillside     | IL    | 60162 |       | 708-544-1131  | E           |               | Public                            | 7am-4:30pm M-F                               | Cash A M V                             |           |                   |        |                    |                    |                  |               |            | [null, null]   | 200-8          | 41.8662363 | -87.8871535 | 2017-04-06T00:00:00 | 1491470114 | P               |                   |                     |                     |                      |                  | true        |                  | 
| 15014 | LPG            | AmeriGas                 | 310 N Sangamon St        | 4 blocks west of Interstate 90/94                             | Chicago      | IL    | 60607 |       | 312-997-2300  | E           |               | Public                            | 6am-4pm M-F                                  | Cash A D M V                           |           |                   |        |                    |                    |                  |               |            | [null, null]   | 200-8          | 41.8872821 | -87.6511547 | 2016-11-02T00:00:00 | 1484686087 | P               |                   |                     |                     |                      |                  | true        |                  | 
| 19143 | CNG            | Gas Technology Institute | 1700 S Mount Prospect Rd | 0.5 mile north of Touhy Avenue, just north of O'Hare Airport. | Des Plaines  | IL    | 60018 |       | 847-768-0500  | E           |               | Public - Credit card at all times | 24 hours daily                               | A D M V CleanEnergy FuelMan Wright_Exp |           | Q                 | 3600   |                    |                    |                  |               |            | [null, null]   | 200-8          | 42.019954  | -87.922412  | 2017-01-11T00:00:00 | 1484682999 | P               |                   |                     | 1995-01-15T00:00:00 |                      | HD               |             |                  | 
| 19794 | LPG            | U-Haul                   | 1861 US Route 41         | South of Route 30                                             | Schererville | IN    | 46375 |       | 219-322-2043  | E           |               | Public                            | 7am-7pm M-Th and Sat, 7am-8pm F, 9am-5pm Sun | Cash Checks A D M V                    |           |                   |        |                    |                    |                  |               |            | [null, null]   | 200-9          | 41.4886027 | -87.4695468 | 2016-06-30T00:00:00 | 1484678160 | P               |                   |                     |                     |                      |                  | false       |                  | 
| 19916 | LPG            | U-Haul                   | 1560 Mount Prospect Rd   | Corner of Oakton and Mt. Prospect, between 83 and Manheim     | Des Plaines  | IL    | 60018 |       | 847-298-1170  | E           |               | Public                            | 7am-7pm M-Th and Sat, 7am-8pm F, 9am-5pm Sun | Cash A D M V                           |           |                   |        |                    |                    |                  |               |            | [null, null]   | 200-8          | 42.023601  | -87.921322  | 2016-11-02T00:00:00 | 1484686075 | P               |                   |                     |                     |                      |                  | true        |                  | 
| 19918 | LPG            | U-Haul                   | 2125 Dempster St         | Between Dodge and McCormick                                   | Evanston     | IL    | 60201 |       | 847-864-8877  | E           |               | Public                            | 7am-7pm M-Th and Sat, 7am-8pm F, 9am-5pm Sun | Cash A D M V                           |           |                   |        |                    |                    |                  |               |            | [null, null]   | 200-8          | 42.041488  | -87.703333  | 2016-11-02T00:00:00 | 1484682678 | P               |                   |                     |                     |                      |                  | false       |                  | 
| 19919 | LPG            | U-Haul                   | 2915 W 159th St          |                                                               | Markham      | IL    | 60428 |       | 708-333-7840  | E           |               | Public                            | 7am-7pm M-Th and Sat, 7am-8pm F, 9am-5pm Sun | Cash A D M V                           |           |                   |        |                    |                    |                  |               |            | [null, null]   | 200-8          | 41.6002472 | -87.6881635 | 2016-11-02T00:00:00 | 1484682661 | P               |                   |                     |                     |                      |                  | false       |                  | 
| 19924 | LPG            | U-Haul                   | 1700 N Cicero Ave        | Between North and Grand                                       | Chicago      | IL    | 60639 |       | 773-889-8194  | E           |               | Public                            | 7am-7pm M-Th and Sat, 7am-8pm F, 9am-5pm Sun | Cash A D M V                           |           |                   |        |                    |                    |                  |               |            | [null, null]   | 200-8          | 41.9119446 | -87.7463825 | 2016-11-02T00:00:00 | 1484680966 | P               |                   |                     |                     |                      |                  | false       |                  | 
```