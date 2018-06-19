# Alternative Service Locations - Food Purchase

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/alternative-service-locations-food-purchase) |
| Metadata | [Link](https://data.iowa.gov/api/views/qwe5-jnrf) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/qwe5-jnrf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/qwe5-jnrf/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | qwe5-jnrf |
| Name | Alternative Service Locations - Food Purchase |
| Attribution | Iowa DOT, HDR Engineering |
| Category | Transportation & Utilities |
| Tags | asset, classification, rest, area, alternative, service, iowa dot, iowa department of transportation |
| Created | 2016-08-19T21:09:54Z |
| Publication Date | 2016-08-19T21:11:52Z |

## Description

Iowa Department of Transportation statewide rest area data. This layer displays alternative service locations that have food available for purchase.

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
| Yes      | series tag     | truck_spaces              | Truck_Spaces              | text      | text        |
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
series e:qwe5-jnrf d:2016-08-19T21:09:54.000Z t:truck_perc_group=75-99% t:surveyed=No t:state=Iowa t:interstate_number="35 & 80" t:truck_spaces=40 t:facility_id="I-35 & 80 Exit-136, ID-4" t:food_purchase=Yes t:restrooms="Yes - Unknown" t:city="Des Moines" t:area_type="Urban Area" t:exit_number=136 t:truck_parking=Yes t:category="Gasoline Stations with Convenience Stores" t:location_facility_id="I-35 & 80 Exit-136, ID-4" t:accessible=Yes t:hours_24=Yes t:aslsummshort=RR_Not24hr t:travel_info=Unknown t:place="QUIKTRIP CORP" t:objectid=4 t:cars_truck=Yes m:approx_number_truck_space=40 m:truck_percent_utili=75

series e:qwe5-jnrf d:2016-08-19T21:09:54.000Z t:dot_tech_partner=N/A t:phone_number=5152761509 t:rv_dump=Yes t:hr_prkng_24=Yes t:parking_hours=N/A t:food_purchase=Yes t:car_trk_pernight=N/A t:city="Des Moines" t:exit_number=126 t:wi_fi=No t:car_holiday_wknd=No t:busy_season_car=Summer t:location_facility_id="I-35 & 80 Exit-126, ID-1" t:hours_operate=NA t:free_prkng=Yes t:pet_exercise=No t:place="PILOT TRAVEL CENTERS LLC" t:car_spaces=40 t:wi_fi_free="Not Free" t:handi_spaces=12 t:busy_day_truck=Weekends t:elect_veh_charge=No t:wi_fi_price="$4.79 day" t:busy_season_truck=Winter t:elect_free=N/A t:category="Other Gasoline Stations" t:trck_full=Yes-Weekends t:hours_24=Yes t:travel_info=No t:objectid=14 t:cars_truck=Both t:picnic=No t:zip_code=50322 t:state=Iowa t:interstate_number="35 & 80" t:truck_spaces=75 t:facility_id="I-35 & 80 Exit-126, ID-1" t:restrooms="Yes - 24 Hours" t:area_type="Urban Area" t:busy_day_car=Wednesdays t:accessible=Yes t:aslsummshort=24hr_RR_TP t:other_services="Restaurant/Food Service" t:truck_perc_group=75-99% t:busy_time_truck="Fri nights" t:surveyed=Yes t:family_restroom=No t:email_request=No t:tdd=Yes t:truck_parking=Yes t:busy_time_car=Noon t:name_request="Charles Sang" t:telephone=Yes m:approx_number_truck_space=75 m:truck_percent_utili=85

series e:qwe5-jnrf d:2016-08-19T21:09:54.000Z t:dot_tech_partner=No t:phone_number=5152767437 t:rv_dump=No t:hr_prkng_24=No t:parking_hours="Only trucks--any time" t:food_purchase=Yes t:car_trk_pernight=200 t:city=Clive t:exit_number=125 t:wi_fi=No t:car_holiday_wknd=No t:busy_season_car=Summer t:location_facility_id="I-35 & 80 Exit-125, ID-2" t:hours_operate=NA t:free_prkng=Yes t:pet_exercise=Yes t:place="Love's Travel Stop" t:car_spaces=130 t:wi_fi_free="Not Free" t:handi_spaces=6 t:busy_day_truck=Tuesday-Wednesday t:elect_veh_charge=No t:wi_fi_price="AT&T provides it--not sure" t:busy_season_truck=Summer t:elect_free=N/A t:category="Gas Station/Conveinece" t:trck_full="Yes--3 nights/week" t:hours_24=Yes t:travel_info=No t:objectid=17 t:cars_truck=Both t:picnic=No t:zip_code=50325 t:state=Iowa t:interstate_number="35 & 80" t:truck_spaces=250 t:facility_id="I-35 & 80 Exit-125, ID-2" t:restrooms="Yes - 24 Hours" t:area_type="Urban Area" t:busy_day_car=Varies t:accessible=Yes t:aslsummshort=24hr_RR_TP t:other_services=No t:truck_perc_group=75-99% t:busy_time_truck=Varies t:surveyed=Yes t:family_restroom=Yes t:email_request=store411@love.com t:tdd=Yes t:truck_parking=Yes t:busy_time_car=Day t:name_request="? Long" t:telephone=Yes m:approx_number_truck_space=250 m:truck_percent_utili=90
```

## Meta Commands

```ls
metric m:approx_number_truck_space p:integer l:Approx_Number_Truck_Space d:"Appoximate Number of Truck Spaces" t:dataTypeName=number

metric m:truck_percent_utili p:integer l:Truck_Percent_Utili d:"Truck Utilization Percent" t:dataTypeName=number

entity e:qwe5-jnrf l:"Alternative Service Locations - Food Purchase" t:attribution="Iowa DOT, HDR Engineering" t:url=https://data.iowa.gov/api/views/qwe5-jnrf

property e:qwe5-jnrf t:meta.view v:id=qwe5-jnrf v:category="Transportation & Utilities" v:averageRating=0 v:name="Alternative Service Locations - Food Purchase" v:attribution="Iowa DOT, HDR Engineering"

property e:qwe5-jnrf t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:qwe5-jnrf t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```

## Top Records

```ls
| :updated_at | objectid | facility_id              | place                 | category                                  | interstate_number | exit_number | area_type  | address                                    | city       | state | zip_code | phone_number | surveyed | hours_24 | hours_operate | accessible | cars_truck | truck_parking | free_prkng | car_spaces | truck_spaces | handi_spaces | busy_day_truck | busy_time_truck | busy_season_truck | busy_day_car | busy_time_car | busy_season_car | car_holiday_wknd | hr_prkng_24 | parking_hours | car_trk_pernight | trck_full | restrooms          | family_restroom | telephone | tdd | wi_fi | wi_fi_free | wi_fi_price | travel_info | rv_dump | elect_veh_charge | elect_free | picnic | pet_exercise | food_purchase | dot_tech_partner | other_services | name_request | email_request | future_question | location_facility_id     | approx_number_truck_space | truck_percent_utili | truck_perc_group | aslsummshort | 
| =========== | ======== | ======================== | ===================== | ========================================= | ================= | =========== | ========== | ========================================== | ========== | ===== | ======== | ============ | ======== | ======== | ============= | ========== | ========== | ============= | ========== | ========== | ============ | ============ | ============== | =============== | ================= | ============ | ============= | =============== | ================ | =========== | ============= | ================ | ========= | ================== | =============== | ========= | === | ===== | ========== | =========== | =========== | ======= | ================ | ========== | ====== | ============ | ============= | ================ | ============== | ============ | ============= | =============== | ======================== | ========================= | =================== | ================ | ============ | 
| 0           | 1        | I-35 & 80 Exit-136, ID-1 | CASEYS GENERAL STORE  | Gasoline Stations with Convenience Stores | 35 & 80           | 136         | Urban Area | 4560 E 14TH ST, Des Moines, IA             | Des Moines | Iowa  |          | 515-266-4427 | No       | No       |               | No         |            | Unknown       |            |            | 0            |              |                |                 |                   |              |               |                 |                  |             |               |                  |           | Yes - Not 24 Hours |                 |           |     |       |            |             | Unknown     |         |                  |            |        |              | Yes           |                  |                |              |               |                 |                          |                           |                     |                  | RR_Not24hr   | 
| 0           | 2        | I-35 & 80 Exit-136, ID-2 | KRUEGER'S BP          | Gasoline Stations with Convenience Stores | 35 & 80           | 136         | Urban Area | 5120 NE 14th Street, Des Moines, IA, 50313 | Des Moines | Iowa  | 50313    | 5152650558   | No       |          |               | No         |            | Unknown       |            |            |              |              |                |                 |                   |              |               |                 |                  |             |               |                  |           | Unknown            |                 |           |     |       |            |             | Unknown     |         |                  |            |        |              | Yes           |                  |                |              |               |                 |                          |                           |                     |                  |              | 
| 0           | 3        | I-35 & 80 Exit-136, ID-3 | Casey's General Store | Gas Station/Convenience                   | 35 & 80           | 136         | Urban Area | 5150 NE 14th Street, Des Moines, IA, 50313 | Des Moines | Iowa  | 50313    | 5155640708   | Yes      | Yes      | NA            | No         | Only cars  | Unknown       | Yes        | 15         | 0            | 2            | N/A            | N/A             | N/A               | Friday       | 2:00pm-7:00pm | Summer          | No               | No          | N/A           | N/A              | N/A       | Yes - 24 Hours     | No              | No        | No  | No    | N/A        | N/A         | Yes         | No      | No               | N/A        | No     | Yes          | Yes           | Call coporate    | No             | Jackie Peel  | No            |                 |                          |                           |                     |                  | 24hr_RR      | 
| 0           | 4        | I-35 & 80 Exit-136, ID-4 | QUIKTRIP CORP         | Gasoline Stations with Convenience Stores | 35 & 80           | 136         | Urban Area | 4801 N.E. 14TH ST, Des Moines, IA          | Des Moines | Iowa  |          |              | No       | Yes      |               | Yes        | Yes        | Yes           |            |            | 40           |              |                |                 |                   |              |               |                 |                  |             |               |                  |           | Yes - Unknown      |                 |           |     |       |            |             | Unknown     |         |                  |            |        |              | Yes           |                  |                |              |               |                 | I-35 & 80 Exit-136, ID-4 | 40                        | 75                  | 75-99%           | RR_Not24hr   | 
| 0           | 5        | I-35 & 80 Exit-135, ID-1 | QUIKTRIP CORP         | Gasoline Stations with Convenience Stores | 35 & 80           | 135         | Urban Area | 4575 NW 2ND ST, Des Moines, IA, 50313      | Des Moines | Iowa  | 50313    | 5152888276   | No       | Yes      |               | No         |            | Unknown       |            |            | 0            |              |                |                 |                   |              |               |                 |                  |             |               |                  |           | Yes - Unknown      |                 |           |     |       |            |             | Unknown     |         |                  |            |        |              | Yes           |                  |                |              |               |                 |                          |                           |                     |                  | RR_Not24hr   | 
| 0           | 6        | I-35 & 80 Exit-134, ID-1 | QUIKTRIP CORP         | Gasoline Stations with Convenience Stores | 35 & 80           | 134         | Urban Area | 5169 MERLE HAY RD, Johnston, IA, 50131     | Johnston   | Iowa  | 50131    |              | No       | Yes      |               | No         |            | Unknown       |            |            | 0            |              |                |                 |                   |              |               |                 |                  |             |               |                  |           | Yes - Unknown      |                 |           |     |       |            |             | Unknown     |         |                  |            |        |              | Yes           |                  |                |              |               |                 |                          |                           |                     |                  | RR_Not24hr   | 
| 0           | 7        | I-35 & 80 Exit-134, ID-2 | ULTIMATE ENTERPRISES  | Gasoline Stations with Convenience Stores | 35 & 80           | 134         | Urban Area | 4923 Merle Hay Road, Des Moines, IA, 50322 | Des Moines | Iowa  | 50322    | 5152769062   | No       | Yes      |               | Yes        |            | Unknown       |            |            | 0            |              |                |                 |                   |              |               |                 |                  |             |               |                  |           | Unknown            |                 |           |     |       |            |             | Unknown     |         |                  |            |        |              | Yes           |                  |                |              |               |                 |                          |                           |                     |                  |              | 
| 0           | 8        | I-35 & 80 Exit-134, ID-3 | QUIKTRIP CORP         | Gasoline Stations with Convenience Stores | 35 & 80           | 134         | Urban Area | 4600 MERLE HAY RD, Urbandale, IA, 50322    | Urbandale  | Iowa  | 50322    | 5152765010   | No       | Yes      |               | No         |            | Unknown       |            |            | 0            |              |                |                 |                   |              |               |                 |                  |             |               |                  |           | Yes - Unknown      |                 |           |     |       |            |             | Unknown     |         |                  |            |        |              | Yes           |                  |                |              |               |                 |                          |                           |                     |                  | RR_Not24hr   | 
| 0           | 9        | I-35 & 80 Exit-129, ID-1 | Casey's General Store | Gas Station/Convenience                   | 35 & 80           | 129         | Urban Area | 4901 86th St, Urbandale, IA                | Urbandale  | Iowa  |          | 5157271332   | No       | No       |               | No         |            | Unknown       |            |            | 0            |              |                |                 |                   |              |               |                 |                  |             |               |                  |           | Yes - Not 24 Hours |                 |           |     |       |            |             | Unknown     |         |                  |            |        |              | Yes           |                  |                |              |               |                 |                          |                           |                     |                  | RR_Not24hr   | 
| 0           | 10       | I-35 & 80 Exit-129, ID-2 | KUM & GO              | Gasoline Stations with Convenience Stores | 35 & 80           | 129         | Urban Area | 5225 N.W. 86Th St, Johnston, IA, 50131     | Johnston   | Iowa  | 50131    | 515-334-9410 | No       | Yes      |               | No         |            | Unknown       |            |            | 0            |              |                |                 |                   |              |               |                 |                  |             |               |                  |           | Yes - Unknown      |                 |           |     |       |            |             | Unknown     |         |                  |            |        |              | Yes           |                  |                |              |               |                 |                          |                           |                     |                  | RR_Not24hr   | 
```