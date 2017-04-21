# Alternative Service Locations - No Restroom

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/alternative-service-locations-no-restroom) |
| Metadata | [Link](https://data.iowa.gov/api/views/xhab-8eat) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/xhab-8eat/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/xhab-8eat/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | xhab-8eat |
| Name | Alternative Service Locations - No Restroom |
| Attribution | Iowa DOT, HDR Engineering |
| Category | Transportation & Utilities |
| Tags | asset, classification, rest, area, alternative, service, iowa dot, iowa department of transportation |
| Created | 2016-08-19T20:52:01Z |
| Publication Date | 2016-08-19T20:54:10Z |

## Description

Iowa Department of Transportation statewide rest area data. This layer displays alternative service locations that do not have restrooms.

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
| Yes      | series tag     | car_spaces                | Car_Spaces                | text      | text        |
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
series e:xhab-8eat d:2016-08-19T20:52:01.000Z t:zip_code=50010 t:surveyed=No t:state=Iowa t:interstate_number=35 t:facility_id="I-35 Exit-116, ID-2" t:restrooms=No t:city=Ames t:area_type="Rural Area" t:exit_number=116 t:truck_parking=Unknown t:category=Recreation t:accessible=No t:hours_24=No t:pet_exercise=Yes t:aslsummshort=No_RR t:travel_info=Unknown t:place="Peterson Pits Recreation Area" t:objectid=164 t:picnic=Yes m:truck_spaces=0

series e:xhab-8eat d:2016-08-19T20:52:01.000Z t:zip_code=50010 t:surveyed=No t:state=Iowa t:interstate_number=35 t:facility_id="I-35 Exit-116, ID-4" t:restrooms=No t:city=Ames t:area_type="Rural Area" t:exit_number=116 t:truck_parking=Unknown t:category=Recreation t:accessible=No t:hours_24=No t:pet_exercise=Yes t:aslsummshort=No_RR t:travel_info=Unknown t:place="Soper's Mill County Park" t:objectid=166 t:picnic=No m:truck_spaces=0

series e:xhab-8eat d:2016-08-19T20:52:01.000Z t:dot_tech_partner=Yes t:phone_number=712-622-8191 t:zip_code=51561 t:hr_prkng_24="Yes [more below]" t:rv_dump=No t:state=Iowa t:interstate_number=29 t:facility_id="I-29 Exit-35, ID-2" t:food_purchase=Yes t:restrooms=No t:city="Pacific Junction" t:car_trk_pernight="FOR THOSE THAT PAID FOR STAY" t:area_type="Rural Area" t:exit_number=35 t:wi_fi=Yes t:busy_season_car=Spring t:car_holiday_wknd=Yes t:busy_day_car=MONDAY-THURSDAY t:accessible=Yes t:pet_exercise=Yes t:free_prkng=Yes t:aslsummshort=No_RR t:place=BP t:other_services="THEY HAVE FAX MACHINES, COPY MACHINES, LAUNDRY FACILITY, VENDING & GAME AREA" t:car_spaces="ABOUT 40" t:wi_fi_free=Free t:busy_time_truck=09/19/2012 t:busy_day_truck=SUNDAY t:surveyed=Yes t:elect_veh_charge=Yes t:email_request=SASSYINIOWA@HOTMAIL.COM t:family_restroom=No t:busy_season_truck=Spring t:tdd="ONLY IN THE ROOMS" t:truck_parking=Yes t:elect_free="Yes/FREE FOR REGISTERED GUESTS; FEE FOR NON-GUESTS" t:category="Gasoline Stations with Convenience Stores" t:busy_time_car=6PM-7PM t:trck_full="FOR THOSE THAT PAID FOR STAY" t:hours_24=Yes t:travel_info=Yes t:name_request="LEEANN HILL" t:cars_truck=Both t:objectid=225 t:telephone=Yes t:future_question=Yes m:handi_spaces=1 m:truck_spaces=10
```

## Meta Commands

```ls
metric m:truck_spaces p:integer l:Truck_Spaces d:"Truck Parking Spaces" t:dataTypeName=number

metric m:handi_spaces p:integer l:Handi_Spaces d:"Handicap Parking Spaces" t:dataTypeName=number

metric m:approx_number_truck_space p:long l:Approx_Number_Truck_Space d:"Appoximate Number of Truck Spaces" t:dataTypeName=number

metric m:truck_percent_utili p:long l:Truck_Percent_Utili d:"Truck Utilization Percent" t:dataTypeName=number

entity e:xhab-8eat l:"Alternative Service Locations - No Restroom" t:attribution="Iowa DOT, HDR Engineering" t:url=https://data.iowa.gov/api/views/xhab-8eat

property e:xhab-8eat t:meta.view v:id=xhab-8eat v:category="Transportation & Utilities" v:averageRating=0 v:name="Alternative Service Locations - No Restroom" v:attribution="Iowa DOT, HDR Engineering"

property e:xhab-8eat t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:xhab-8eat t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```

## Top Records

```ls
| :updated_at | objectid | facility_id         | place                         | category                                  | interstate_number | exit_number | area_type  | address                            | city             | state | zip_code | phone_number | surveyed | hours_24 | hours_operate | accessible | cars_truck | truck_parking | free_prkng | car_spaces | truck_spaces | handi_spaces | busy_day_truck | busy_time_truck | busy_season_truck | busy_day_car    | busy_time_car | busy_season_car | car_holiday_wknd | hr_prkng_24      | parking_hours | car_trk_pernight             | trck_full                    | restrooms | family_restroom | telephone | tdd               | wi_fi | wi_fi_free | wi_fi_price | travel_info | rv_dump | elect_veh_charge | elect_free                                         | picnic | pet_exercise | food_purchase | dot_tech_partner | other_services                                                               | name_request | email_request           | future_question | location_facility_id | approx_number_truck_space | truck_percent_utili | truck_perc_group | aslsummshort | 
| =========== | ======== | =================== | ============================= | ========================================= | ================= | =========== | ========== | ================================== | ================ | ===== | ======== | ============ | ======== | ======== | ============= | ========== | ========== | ============= | ========== | ========== | ============ | ============ | ============== | =============== | ================= | =============== | ============= | =============== | ================ | ================ | ============= | ============================ | ============================ | ========= | =============== | ========= | ================= | ===== | ========== | =========== | =========== | ======= | ================ | ================================================== | ====== | ============ | ============= | ================ | ============================================================================ | ============ | ======================= | =============== | ==================== | ========================= | =================== | ================ | ============ | 
| 0           | 164      | I-35 Exit-116, ID-2 | Peterson Pits Recreation Area | Recreation                                | 35                | 116         | Rural Area | 55756 180th St., Ames, IA, 50010   | Ames             | Iowa  | 50010    |              | No       | No       |               | No         |            | Unknown       |            |            | 0            |              |                |                 |                   |                 |               |                 |                  |                  |               |                              |                              | No        |                 |           |                   |       |            |             | Unknown     |         |                  |                                                    | Yes    | Yes          |               |                  |                                                                              |              |                         |                 |                      |                           |                     |                  | No_RR        | 
| 0           | 166      | I-35 Exit-116, ID-4 | Soper's Mill County Park      | Recreation                                | 35                | 116         | Rural Area | 56500 170th Street, Ames, IA 50010 | Ames             | Iowa  | 50010    |              | No       | No       |               | No         |            | Unknown       |            |            | 0            |              |                |                 |                   |                 |               |                 |                  |                  |               |                              |                              | No        |                 |           |                   |       |            |             | Unknown     |         |                  |                                                    | No     | Yes          |               |                  |                                                                              |              |                         |                 |                      |                           |                     |                  | No_RR        | 
| 0           | 225      | I-29 Exit-35, ID-2  | BP                            | Gasoline Stations with Convenience Stores | 29                | 35          | Rural Area | 57902 190th St                     | Pacific Junction | Iowa  | 51561    | 712-622-8191 | Yes      | Yes      |               | Yes        | Both       | Yes           | Yes        | ABOUT 40   | 10           | 1            | SUNDAY         | 09/19/2012      | Spring            | MONDAY-THURSDAY | 6PM-7PM       | Spring          | Yes              | Yes [more below] |               | FOR THOSE THAT PAID FOR STAY | FOR THOSE THAT PAID FOR STAY | No        | No              | Yes       | ONLY IN THE ROOMS | Yes   | Free       |             | Yes         | No      | Yes              | Yes/FREE FOR REGISTERED GUESTS; FEE FOR NON-GUESTS |        | Yes          | Yes           | Yes              | THEY HAVE FAX MACHINES, COPY MACHINES, LAUNDRY FACILITY, VENDING & GAME AREA | LEEANN HILL  | SASSYINIOWA@HOTMAIL.COM | Yes             |                      |                           |                     |                  | No_RR        | 
```