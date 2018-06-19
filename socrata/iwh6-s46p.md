# Alternative Service Locations - Restroom Hours Unknown

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/alternative-service-locations-restroom-hours-unknown) |
| Metadata | [Link](https://data.iowa.gov/api/views/iwh6-s46p) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/iwh6-s46p/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/iwh6-s46p/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | iwh6-s46p |
| Name | Alternative Service Locations - Restroom Hours Unknown |
| Attribution | Iowa DOT, HDR Engineering |
| Category | Transportation & Utilities |
| Tags | asset, classification, rest, area, alternative, service, iowa dot, iowa department of transportation |
| Created | 2016-08-19T20:58:49Z |
| Publication Date | 2016-08-19T21:00:40Z |

## Description

Iowa Department of Transportation statewide rest area data. This layer displays alternative service locations that have restrooms with unknown operating hours.

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type | Render Type |
| ======== | ============== | ========================= | ========================= | ========= | =========== |
| No       | time           | :updated_at               | updated_at                | meta_data | meta_data   |
| Yes      | series tag     | objectid                  | OBJECTID                  | text      | number      |
| Yes      | series tag     | facility_id               | Facility_ID               | text      | text        |
| Yes      | series tag     | place                     | Place                     | text      | text        |
| Yes      | series tag     | category                  | Category                  | text      | text        |
| Yes      | series tag     | interstate_number         | Interstate_Number         | text      | text        |
| Yes      | series tag     | exit_number               | Exit_Number               | text      | text        |
| Yes      | series tag     | area_type                 | Area_Type                 | text      | text        |
| No       |                | address                   | Address                   | text      | text        |
| Yes      | series tag     | city                      | City                      | text      | text        |
| Yes      | series tag     | state                     | State                     | text      | text        |
| Yes      | series tag     | zip_code                  | Zip_Code                  | text      | number      |
| Yes      | series tag     | phone_number              | Phone_Number              | text      | text        |
| Yes      | series tag     | surveyed                  | Surveyed                  | text      | text        |
| Yes      | series tag     | hours_24                  | Hours_24                  | text      | text        |
| Yes      | series tag     | hours_operate             | Hours_Operate             | text      | text        |
| Yes      | series tag     | accessible                | Accessible                | text      | text        |
| Yes      | series tag     | cars_truck                | Cars_Truck                | text      | text        |
| Yes      | series tag     | truck_parking             | Truck_Parking             | text      | text        |
| Yes      | series tag     | free_prkng                | Free_Prkng                | text      | text        |
| Yes      | numeric metric | car_spaces                | Car_Spaces                | number    | text        |
| Yes      | numeric metric | truck_spaces              | Truck_Spaces              | number    | text        |
| Yes      | numeric metric | handi_spaces              | Handi_Spaces              | number    | text        |
| Yes      | series tag     | busy_day_truck            | Busy_Day_Truck            | text      | text        |
| Yes      | series tag     | busy_time_truck           | Busy_Time_Truck           | text      | text        |
| Yes      | series tag     | busy_season_truck         | Busy_Season_Truck         | text      | text        |
| Yes      | series tag     | busy_day_car              | Busy_Day_Car              | text      | text        |
| Yes      | series tag     | busy_time_car             | Busy_Time_Car             | text      | text        |
| Yes      | series tag     | busy_season_car           | Busy_Season_Car           | text      | text        |
| Yes      | series tag     | car_holiday_wknd          | Car_Holiday_Wknd          | text      | text        |
| Yes      | series tag     | hr_prkng_24               | Hr_Prkng_24               | text      | text        |
| Yes      | series tag     | parking_hours             | Parking_Hours             | text      | text        |
| Yes      | numeric metric | car_trk_pernight          | Car_Trk_PerNight          | number    | text        |
| Yes      | series tag     | trck_full                 | Trck_Full                 | text      | text        |
| Yes      | series tag     | restrooms                 | Restrooms                 | text      | text        |
| Yes      | series tag     | family_restroom           | Family_Restroom           | text      | text        |
| Yes      | series tag     | telephone                 | Telephone                 | text      | text        |
| Yes      | series tag     | tdd                       | TDD                       | text      | text        |
| Yes      | series tag     | wi_fi                     | Wi_Fi                     | text      | text        |
| Yes      | series tag     | wi_fi_free                | Wi_Fi_Free                | text      | text        |
| Yes      | series tag     | wi_fi_price               | Wi_Fi_Price               | text      | text        |
| Yes      | series tag     | travel_info               | Travel_Info               | text      | text        |
| Yes      | series tag     | rv_dump                   | RV_Dump                   | text      | text        |
| Yes      | series tag     | elect_veh_charge          | Elect_Veh_Charge          | text      | text        |
| Yes      | series tag     | elect_free                | Elect_Free                | text      | text        |
| Yes      | series tag     | picnic                    | Picnic                    | text      | text        |
| Yes      | series tag     | pet_exercise              | Pet_Exercise              | text      | text        |
| Yes      | series tag     | food_purchase             | Food_Purchase             | text      | text        |
| Yes      | series tag     | dot_tech_partner          | DOT_Tech_Partner          | text      | text        |
| Yes      | series tag     | other_services            | Other_Services            | text      | text        |
| Yes      | series tag     | name_request              | Name_Request              | text      | text        |
| Yes      | series tag     | email_request             | Email_Request             | text      | text        |
| Yes      | series tag     | future_question           | Future_Question           | text      | text        |
| Yes      | series tag     | location_facility_id      | Location_Facility_ID      | text      | text        |
| Yes      | numeric metric | approx_number_truck_space | Approx_Number_Truck_Space | number    | number      |
| Yes      | numeric metric | truck_percent_utili       | Truck_Percent_Utili       | number    | number      |
| Yes      | series tag     | truck_perc_group          | Truck_Perc_Group          | text      | text        |
| Yes      | series tag     | aslsummshort              | ASLSummShort              | text      | text        |
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
series e:iwh6-s46p d:2016-08-19T20:58:49.000Z t:truck_perc_group=75-99% t:surveyed=No t:state=Iowa t:interstate_number="35 & 80" t:facility_id="I-35 & 80 Exit-136, ID-4" t:food_purchase=Yes t:restrooms="Yes - Unknown" t:city="Des Moines" t:area_type="Urban Area" t:exit_number=136 t:truck_parking=Yes t:category="Gasoline Stations with Convenience Stores" t:location_facility_id="I-35 & 80 Exit-136, ID-4" t:accessible=Yes t:hours_24=Yes t:aslsummshort=RR_Not24hr t:travel_info=Unknown t:place="QUIKTRIP CORP" t:objectid=4 t:cars_truck=Yes m:approx_number_truck_space=40 m:truck_spaces=40 m:truck_percent_utili=75

series e:iwh6-s46p d:2016-08-19T20:58:49.000Z t:phone_number=5152888276 t:zip_code=50313 t:surveyed=No t:state=Iowa t:interstate_number="35 & 80" t:facility_id="I-35 & 80 Exit-135, ID-1" t:food_purchase=Yes t:restrooms="Yes - Unknown" t:city="Des Moines" t:area_type="Urban Area" t:exit_number=135 t:truck_parking=Unknown t:category="Gasoline Stations with Convenience Stores" t:accessible=No t:hours_24=Yes t:aslsummshort=RR_Not24hr t:travel_info=Unknown t:place="QUIKTRIP CORP" t:objectid=5 m:truck_spaces=0

series e:iwh6-s46p d:2016-08-19T20:58:49.000Z t:zip_code=50131 t:surveyed=No t:state=Iowa t:interstate_number="35 & 80" t:food_purchase=Yes t:facility_id="I-35 & 80 Exit-134, ID-1" t:restrooms="Yes - Unknown" t:city=Johnston t:area_type="Urban Area" t:exit_number=134 t:truck_parking=Unknown t:category="Gasoline Stations with Convenience Stores" t:accessible=No t:hours_24=Yes t:aslsummshort=RR_Not24hr t:travel_info=Unknown t:place="QUIKTRIP CORP" t:objectid=6 m:truck_spaces=0
```

## Meta Commands

```ls
metric m:car_spaces p:integer l:Car_Spaces d:"Car Parking Spaces" t:dataTypeName=number

metric m:truck_spaces p:integer l:Truck_Spaces d:"Truck Parking Spaces" t:dataTypeName=number

metric m:handi_spaces p:integer l:Handi_Spaces d:"Handicap Parking Spaces" t:dataTypeName=number

metric m:car_trk_pernight p:integer l:Car_Trk_PerNight d:"Car and Truck Parking at Night" t:dataTypeName=number

metric m:approx_number_truck_space p:integer l:Approx_Number_Truck_Space d:"Appoximate Number of Truck Spaces" t:dataTypeName=number

metric m:truck_percent_utili p:integer l:Truck_Percent_Utili d:"Truck Utilization Percent" t:dataTypeName=number

entity e:iwh6-s46p l:"Alternative Service Locations - Restroom Hours Unknown" t:attribution="Iowa DOT, HDR Engineering" t:url=https://data.iowa.gov/api/views/iwh6-s46p

property e:iwh6-s46p t:meta.view v:id=iwh6-s46p v:category="Transportation & Utilities" v:averageRating=0 v:name="Alternative Service Locations - Restroom Hours Unknown" v:attribution="Iowa DOT, HDR Engineering"

property e:iwh6-s46p t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:iwh6-s46p t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```

## Top Records

```ls
| :updated_at | objectid | facility_id              | place                     | category                                  | interstate_number | exit_number | area_type  | address                                         | city            | state | zip_code | phone_number | surveyed | hours_24 | hours_operate | accessible | cars_truck | truck_parking | free_prkng | car_spaces | truck_spaces | handi_spaces | busy_day_truck | busy_time_truck | busy_season_truck | busy_day_car | busy_time_car | busy_season_car | car_holiday_wknd | hr_prkng_24 | parking_hours | car_trk_pernight | trck_full | restrooms     | family_restroom | telephone | tdd | wi_fi | wi_fi_free | wi_fi_price | travel_info | rv_dump | elect_veh_charge | elect_free | picnic | pet_exercise | food_purchase | dot_tech_partner | other_services | name_request | email_request | future_question | location_facility_id     | approx_number_truck_space | truck_percent_utili | truck_perc_group | aslsummshort | 
| =========== | ======== | ======================== | ========================= | ========================================= | ================= | =========== | ========== | =============================================== | =============== | ===== | ======== | ============ | ======== | ======== | ============= | ========== | ========== | ============= | ========== | ========== | ============ | ============ | ============== | =============== | ================= | ============ | ============= | =============== | ================ | =========== | ============= | ================ | ========= | ============= | =============== | ========= | === | ===== | ========== | =========== | =========== | ======= | ================ | ========== | ====== | ============ | ============= | ================ | ============== | ============ | ============= | =============== | ======================== | ========================= | =================== | ================ | ============ | 
| 0           | 4        | I-35 & 80 Exit-136, ID-4 | QUIKTRIP CORP             | Gasoline Stations with Convenience Stores | 35 & 80           | 136         | Urban Area | 4801 N.E. 14TH ST, Des Moines, IA               | Des Moines      | Iowa  |          |              | No       | Yes      |               | Yes        | Yes        | Yes           |            |            | 40           |              |                |                 |                   |              |               |                 |                  |             |               |                  |           | Yes - Unknown |                 |           |     |       |            |             | Unknown     |         |                  |            |        |              | Yes           |                  |                |              |               |                 | I-35 & 80 Exit-136, ID-4 | 40                        | 75                  | 75-99%           | RR_Not24hr   | 
| 0           | 5        | I-35 & 80 Exit-135, ID-1 | QUIKTRIP CORP             | Gasoline Stations with Convenience Stores | 35 & 80           | 135         | Urban Area | 4575 NW 2ND ST, Des Moines, IA, 50313           | Des Moines      | Iowa  | 50313    | 5152888276   | No       | Yes      |               | No         |            | Unknown       |            |            | 0            |              |                |                 |                   |              |               |                 |                  |             |               |                  |           | Yes - Unknown |                 |           |     |       |            |             | Unknown     |         |                  |            |        |              | Yes           |                  |                |              |               |                 |                          |                           |                     |                  | RR_Not24hr   | 
| 0           | 6        | I-35 & 80 Exit-134, ID-1 | QUIKTRIP CORP             | Gasoline Stations with Convenience Stores | 35 & 80           | 134         | Urban Area | 5169 MERLE HAY RD, Johnston, IA, 50131          | Johnston        | Iowa  | 50131    |              | No       | Yes      |               | No         |            | Unknown       |            |            | 0            |              |                |                 |                   |              |               |                 |                  |             |               |                  |           | Yes - Unknown |                 |           |     |       |            |             | Unknown     |         |                  |            |        |              | Yes           |                  |                |              |               |                 |                          |                           |                     |                  | RR_Not24hr   | 
| 0           | 8        | I-35 & 80 Exit-134, ID-3 | QUIKTRIP CORP             | Gasoline Stations with Convenience Stores | 35 & 80           | 134         | Urban Area | 4600 MERLE HAY RD, Urbandale, IA, 50322         | Urbandale       | Iowa  | 50322    | 5152765010   | No       | Yes      |               | No         |            | Unknown       |            |            | 0            |              |                |                 |                   |              |               |                 |                  |             |               |                  |           | Yes - Unknown |                 |           |     |       |            |             | Unknown     |         |                  |            |        |              | Yes           |                  |                |              |               |                 |                          |                           |                     |                  | RR_Not24hr   | 
| 0           | 10       | I-35 & 80 Exit-129, ID-2 | KUM & GO                  | Gasoline Stations with Convenience Stores | 35 & 80           | 129         | Urban Area | 5225 N.W. 86Th St, Johnston, IA, 50131          | Johnston        | Iowa  | 50131    | 515-334-9410 | No       | Yes      |               | No         |            | Unknown       |            |            | 0            |              |                |                 |                   |              |               |                 |                  |             |               |                  |           | Yes - Unknown |                 |           |     |       |            |             | Unknown     |         |                  |            |        |              | Yes           |                  |                |              |               |                 |                          |                           |                     |                  | RR_Not24hr   | 
| 0           | 18       | I-35 & 80 Exit-124, ID-1 | KUM & GO                  | Gasoline Stations with Convenience Stores | 35 & 80           | 124         | Urban Area | 5308 University Ave, West Des Moines, IA, 50266 | West Des Moines | Iowa  | 50266    | 515-457-9028 | No       | Yes      |               | No         |            | Unknown       |            |            | 0            |              |                |                 |                   |              |               |                 |                  |             |               |                  |           | Yes - Unknown |                 |           |     |       |            |             | Unknown     |         |                  |            |        |              | Yes           |                  |                |              |               |                 |                          |                           |                     |                  | RR_Not24hr   | 
| 0           | 19       | I-35 & 80 Exit-124, ID-2 | QUIKTRIP CORP             | Gasoline Stations with Convenience Stores | 35 & 80           | 124         | Urban Area | 11925 UNIVERSITY AVE, Clive, IA                 | Clive           | Iowa  |          |              | No       | Yes      |               | No         |            | Unknown       |            |            | 0            |              |                |                 |                   |              |               |                 |                  |             |               |                  |           | Yes - Unknown |                 |           |     |       |            |             | Unknown     |         |                  |            |        |              | Yes           |                  |                |              |               |                 |                          |                           |                     |                  | RR_Not24hr   | 
| 0           | 20       | I-35 & 80 Exit-124, ID-3 | PETROPOINTE ON FOREST     | Gasoline Stations with Convenience Stores | 35 & 80           | 124         | Urban Area | 11408 Forest Ave, Clive, IA 50325               | Clive           | Iowa  | 50325    |              | No       |          |               | No         |            | Unknown       |            |            | 0            |              |                |                 |                   |              |               |                 |                  |             |               |                  |           | Yes - Unknown |                 |           |     |       |            |             | Unknown     |         |                  |            |        |              | Yes           |                  |                |              |               |                 |                          |                           |                     |                  | RR_Not24hr   | 
| 0           | 21       | I-29 & 80 Exit-3, ID-1   | TRAVEL CENTERS OF AMERICA | Other Gasoline Stations                   | 29 & 80           | 3           | Urban Area | 3210 S. 7th St                                  | Council Bluffs  | Iowa  | 51501    | 712-366-2217 | No       |          |               |            |            | Yes           |            |            |              |              |                |                 |                   |              |               |                 |                  |             |               |                  |           | Yes - Unknown |                 |           |     |       |            |             | Unknown     |         |                  |            |        |              | Yes           |                  |                |              |               |                 | I-29 & 80 Exit-3, ID-1   | 95                        | 80                  | 75-99%           | RR_Not24hr   | 
| 0           | 22       | I-29 & 80 Exit-3, ID-2   | U-STOP CONVENIENCE STOP   | Gasoline Stations with Convenience Stores | 29 & 80           | 3           | Urban Area | 701 S. 32nd Ave                                 | Council Bluffs  | Iowa  | 51501    | 712-366-5453 | No       |          |               |            |            | Unknown       |            |            |              |              |                |                 |                   |              |               |                 |                  |             |               |                  |           | Yes - Unknown |                 |           |     |       |            |             | Unknown     |         |                  |            |        |              | Yes           |                  |                |              |               |                 |                          |                           |                     |                  | RR_Not24hr   | 
```