# Alternative Service Locations - Picnic Area

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/alternative-service-locations-picnic-area) |
| Metadata | [Link](https://data.iowa.gov/api/views/7dgi-gzrf) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/7dgi-gzrf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/7dgi-gzrf/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | 7dgi-gzrf |
| Name | Alternative Service Locations - Picnic Area |
| Attribution | Iowa DOT, HDR Engineering |
| Category | Transportation & Utilities |
| Tags | asset, classification, rest, area, alternative, service, iowa dot, iowa department of transportation |
| Created | 2016-08-19T21:16:44Z |
| Publication Date | 2016-08-19T21:18:59Z |

## Description

Iowa Department of Transportation statewide rest area data. This layer displays alternative service locations that have a picnic area.

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
| Yes      | series tag     | handi_spaces              | Handi_Spaces              | text      | text        |
| Yes      | series tag     | busy_day_truck            | Busy_Day_Truck            | text      | text        |
| Yes      | series tag     | busy_time_truck           | Busy_Time_Truck           | text      | text        |
| Yes      | series tag     | busy_season_truck         | Busy_Season_Truck         | text      | text        |
| Yes      | series tag     | busy_day_car              | Busy_Day_Car              | text      | text        |
| Yes      | series tag     | busy_time_car             | Busy_Time_Car             | text      | text        |
| Yes      | series tag     | busy_season_car           | Busy_Season_Car           | text      | text        |
| Yes      | series tag     | car_holiday_wknd          | Car_Holiday_Wknd          | text      | text        |
| Yes      | series tag     | hr_prkng_24               | Hr_Prkng_24               | text      | text        |
| Yes      | series tag     | parking_hours             | Parking_Hours             | text      | text        |
| Yes      | series tag     | car_trk_pernight          | Car_Trk_PerNight          | text      | text        |
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
series e:7dgi-gzrf d:2016-08-19T21:16:44.000Z t:phone_number=5152223444 t:surveyed=No t:state=Iowa t:interstate_number=80 t:facility_id="I-80 Exit-122, ID-2" t:restrooms="Yes - Not 24 Hours" t:city="West Des Moines" t:area_type="Urban Area" t:exit_number=122 t:truck_parking=Unknown t:category=Recreation t:accessible=No t:hours_24=No t:pet_exercise=Yes t:aslsummshort=RR_Not24hr t:travel_info=Unknown t:place="Peony Park" t:objectid=120 t:picnic=Yes m:truck_spaces=0

series e:7dgi-gzrf d:2016-08-19T21:16:44.000Z t:phone_number=641742-3751 t:surveyed=No t:state=Iowa t:interstate_number=80 t:facility_id="I-80 Exit-76, ID-2" t:restrooms="Yes - Not 24 Hours" t:city=Stuart t:area_type="Urban Area" t:exit_number=76 t:truck_parking=Unknown t:category=Recreation t:accessible=No t:hours_24=No t:pet_exercise=Yes t:aslsummshort=RR_Not24hr t:travel_info=Unknown t:place="Adair City Park" t:objectid=133 t:picnic=Yes m:truck_spaces=0

series e:7dgi-gzrf d:2016-08-19T21:16:44.000Z t:zip_code=50010 t:surveyed=No t:state=Iowa t:interstate_number=35 t:facility_id="I-35 Exit-116, ID-2" t:restrooms=No t:city=Ames t:area_type="Rural Area" t:exit_number=116 t:truck_parking=Unknown t:category=Recreation t:accessible=No t:hours_24=No t:pet_exercise=Yes t:aslsummshort=No_RR t:travel_info=Unknown t:place="Peterson Pits Recreation Area" t:objectid=164 t:picnic=Yes m:truck_spaces=0
```

## Meta Commands

```ls
metric m:car_spaces p:integer l:Car_Spaces d:"Car Parking Spaces" t:dataTypeName=number

metric m:truck_spaces p:integer l:Truck_Spaces d:"Truck Parking Spaces" t:dataTypeName=number

metric m:approx_number_truck_space p:long l:Approx_Number_Truck_Space d:"Appoximate Number of Truck Spaces" t:dataTypeName=number

metric m:truck_percent_utili p:long l:Truck_Percent_Utili d:"Truck Utilization Percent" t:dataTypeName=number

entity e:7dgi-gzrf l:"Alternative Service Locations - Picnic Area" t:attribution="Iowa DOT, HDR Engineering" t:url=https://data.iowa.gov/api/views/7dgi-gzrf

property e:7dgi-gzrf t:meta.view v:id=7dgi-gzrf v:category="Transportation & Utilities" v:averageRating=0 v:name="Alternative Service Locations - Picnic Area" v:attribution="Iowa DOT, HDR Engineering"

property e:7dgi-gzrf t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:7dgi-gzrf t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```

## Top Records

```ls
| :updated_at | objectid | facility_id          | place                  | category    | interstate_number | exit_number | area_type  | address                                   | city            | state | zip_code | phone_number | surveyed | hours_24 | hours_operate | accessible | cars_truck | truck_parking | free_prkng | car_spaces | truck_spaces | handi_spaces | busy_day_truck | busy_time_truck | busy_season_truck | busy_day_car | busy_time_car | busy_season_car | car_holiday_wknd | hr_prkng_24 | parking_hours | car_trk_pernight | trck_full | restrooms          | family_restroom | telephone | tdd | wi_fi | wi_fi_free | wi_fi_price | travel_info | rv_dump | elect_veh_charge | elect_free | picnic | pet_exercise | food_purchase | dot_tech_partner | other_services | name_request | email_request | future_question | location_facility_id | approx_number_truck_space | truck_percent_utili | truck_perc_group | aslsummshort | 
| =========== | ======== | ==================== | ====================== | =========== | ================= | =========== | ========== | ========================================= | =============== | ===== | ======== | ============ | ======== | ======== | ============= | ========== | ========== | ============= | ========== | ========== | ============ | ============ | ============== | =============== | ================= | ============ | ============= | =============== | ================ | =========== | ============= | ================ | ========= | ================== | =============== | ========= | === | ===== | ========== | =========== | =========== | ======= | ================ | ========== | ====== | ============ | ============= | ================ | ============== | ============ | ============= | =============== | ==================== | ========================= | =================== | ================ | ============ | 
| 0           | 35       | I-380 Exit-70, ID-1  | DEERWOOD PARK          | City Park   | 380               | 70          | Urban Area | Deerwood Park Rd                          | Evansdale       | Iowa  | 50707    | N/A          | No       |          |               |            |            | Unknown       |            |            |              |              |                |                 |                   |              |               |                 |                  |             |               |                  |           | Unknown            |                 |           |     |       |            |             | Unknown     |         |                  |            | Yes    |              |               |                  |                |              |               |                 |                      |                           |                     |                  |              | 
| 0           | 39       | I-380 Exit-62, ID-1  | BLACK HAWK COUNTY PARK | County Park | 380               | 62          | Rural Area |                                           |                 | Iowa  |          | N/A          | No       |          |               |            |            | Unknown       |            |            |              |              |                |                 |                   |              |               |                 |                  |             |               |                  |           | Unknown            |                 |           |     |       |            |             | Unknown     |         |                  |            | Yes    |              |               |                  |                |              |               |                 |                      |                           |                     |                  |              | 
| 0           | 50       | I-380 Exit-24B, ID-5 | HIAWATHA PARK          | City Park   | 380               | 24B         | Urban Area | N. 10th Ave                               | Hiawatha        | Iowa  | 52402    | N/A          | No       |          |               |            |            | Unknown       |            |            |              |              |                |                 |                   |              |               |                 |                  |             |               |                  |           | Unknown            |                 |           |     |       |            |             | Unknown     |         |                  |            | Yes    |              | Yes           |                  |                |              |               |                 |                      |                           |                     |                  |              | 
| 0           | 54       | I-380 Exit-21, ID-1  | DANIELS PARK           | City Park   | 380               | 21          | Urban Area |                                           | Cedar Rapids    | Iowa  | 52404    | N/A          | No       |          |               |            |            | Unknown       |            |            |              |              |                |                 |                   |              |               |                 |                  |             |               |                  |           | Unknown            |                 |           |     |       |            |             | Unknown     |         |                  |            | Yes    |              |               |                  |                |              |               |                 |                      |                           |                     |                  |              | 
| 0           | 77       | I-80 Exit-277, ID-3  | DUTTON PARK            | County Park | 80                | 277         | Rural Area |                                           | Durant          | Iowa  | 52747    | N/A          | No       |          |               |            |            | Unknown       |            |            |              |              |                |                 |                   |              |               |                 |                  |             |               |                  |           | Unknown            |                 |           |     |       |            |             | Unknown     |         |                  |            | Yes    |              |               |                  |                |              |               |                 |                      |                           |                     |                  |              | 
| 0           | 79       | I-80 Exit-265, ID-1  | ROCHESTER PARK         | County Park | 80                | 265         | Rural Area |                                           | Tipton          | Iowa  | 52772    | N/A          | No       |          |               |            |            | Unknown       |            |            |              |              |                |                 |                   |              |               |                 |                  |             |               |                  |           | Unknown            |                 |           |     |       |            |             | Unknown     |         |                  |            | Yes    |              |               |                  |                |              |               |                 |                      |                           |                     |                  |              | 
| 0           | 94       | I-80 Exit-240, ID-6  | NORTH RIDGE PARK       | City Park   | 80                | 240         | Urban Area | Holiday Road                              | Coralville      | Iowa  | 52241    | N/A          | No       |          |               |            |            | Unknown       |            |            |              |              |                |                 |                   |              |               |                 |                  |             |               |                  |           | Unknown            |                 |           |     |       |            |             | Unknown     |         |                  |            | Yes    |              | Yes           |                  |                |              |               |                 |                      |                           |                     |                  |              | 
| 0           | 106      | I-80 Exit-197, ID-1  | BROOKLYN CITY PARK     | City Park   | 80                | 197         | Rural Area |                                           | Brooklyn        | Iowa  | 52211    | N/A          | No       |          |               |            |            | Unknown       |            |            |              |              |                |                 |                   |              |               |                 |                  |             |               |                  |           | Unknown            |                 |           |     |       |            |             | Unknown     |         |                  |            | Yes    |              |               |                  |                |              |               |                 |                      |                           |                     |                  |              | 
| 0           | 120      | I-80 Exit-122, ID-2  | Peony Park             | Recreation  | 80                | 122         | Urban Area | 63rd & Pleasant St, Des Moines, IA, 50266 | West Des Moines | Iowa  |          | 5152223444   | No       | No       |               | No         |            | Unknown       |            |            | 0            |              |                |                 |                   |              |               |                 |                  |             |               |                  |           | Yes - Not 24 Hours |                 |           |     |       |            |             | Unknown     |         |                  |            | Yes    | Yes          |               |                  |                |              |               |                 |                      |                           |                     |                  | RR_Not24hr   | 
| 0           | 133      | I-80 Exit-76, ID-2   | Adair City Park        | Recreation  | 80                | 76          | Urban Area | 4th St, Stuart, IA                        | Stuart          | Iowa  |          | 641742-3751  | No       | No       |               | No         |            | Unknown       |            |            | 0            |              |                |                 |                   |              |               |                 |                  |             |               |                  |           | Yes - Not 24 Hours |                 |           |     |       |            |             | Unknown     |         |                  |            | Yes    | Yes          |               |                  |                |              |               |                 |                      |                           |                     |                  | RR_Not24hr   | 
```