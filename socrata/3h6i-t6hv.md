# Alternative Service Locations - RV Dump Station

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/alternative-service-locations-rv-dump-station) |
| Metadata | [Link](https://data.iowa.gov/api/views/3h6i-t6hv) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/3h6i-t6hv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/3h6i-t6hv/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | 3h6i-t6hv |
| Name | Alternative Service Locations - RV Dump Station |
| Attribution | Iowa DOT, HDR Engineering |
| Category | Transportation & Utilities |
| Tags | asset, classification, rest, area, alternative, service, rv, iowa dot, iowa department of transportation |
| Created | 2016-08-19T21:14:11Z |
| Publication Date | 2016-08-19T21:16:11Z |

## Description

Iowa Department of Transportation statewide rest area data. This layer displays alternative service locations that have an RV dump station.

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
| Yes      | series tag     | truck_spaces              | Truck_Spaces              | text      | text        |
| Yes      | numeric metric | handi_spaces              | Handi_Spaces              | number    | text        |
| Yes      | series tag     | busy_day_truck            | Busy_Day_Truck            | text      | text        |
| Yes      | series tag     | busy_time_truck           | Busy_Time_Truck           | text      | text        |
| Yes      | series tag     | busy_season_truck         | Busy_Season_Truck         | text      | text        |
| Yes      | series tag     | busy_day_car              | Busy_Day_Car              | text      | text        |
| Yes      | series tag     | busy_time_car             | Busy_Time_Car             | text      | text        |
| Yes      | series tag     | busy_season_car           | Busy_Season_Car           | text      | text        |
| Yes      | series tag     | car_holiday_wknd          | Car_Holiday_Wknd          | text      | text        |
| Yes      | series tag     | hr_prkng_24               | Hr_Prkng_24               | text      | text        |
| Yes      | numeric metric | parking_hours             | Parking_Hours             | number    | text        |
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
series e:3h6i-t6hv d:2016-08-19T21:14:11.000Z t:dot_tech_partner=N/A t:phone_number=5152761509 t:rv_dump=Yes t:hr_prkng_24=Yes t:parking_hours=N/A t:food_purchase=Yes t:car_trk_pernight=N/A t:city="Des Moines" t:exit_number=126 t:wi_fi=No t:car_holiday_wknd=No t:busy_season_car=Summer t:location_facility_id="I-35 & 80 Exit-126, ID-1" t:hours_operate=NA t:free_prkng=Yes t:pet_exercise=No t:place="PILOT TRAVEL CENTERS LLC" t:wi_fi_free="Not Free" t:busy_day_truck=Weekends t:elect_veh_charge=No t:wi_fi_price="$4.79 day" t:busy_season_truck=Winter t:category="Other Gasoline Stations" t:elect_free=N/A t:trck_full=Yes-Weekends t:hours_24=Yes t:travel_info=No t:objectid=14 t:cars_truck=Both t:picnic=No t:zip_code=50322 t:state=Iowa t:interstate_number="35 & 80" t:truck_spaces=75 t:facility_id="I-35 & 80 Exit-126, ID-1" t:restrooms="Yes - 24 Hours" t:area_type="Urban Area" t:busy_day_car=Wednesdays t:accessible=Yes t:aslsummshort=24hr_RR_TP t:other_services="Restaurant/Food Service" t:truck_perc_group=75-99% t:busy_time_truck="Fri nights" t:surveyed=Yes t:family_restroom=No t:email_request=No t:tdd=Yes t:truck_parking=Yes t:busy_time_car=Noon t:name_request="Charles Sang" t:telephone=Yes m:approx_number_truck_space=75 m:handi_spaces=12 m:truck_percent_utili=85 m:car_spaces=40

series e:3h6i-t6hv d:2016-08-19T21:14:11.000Z t:dot_tech_partner="No/Corporate question" t:phone_number=319-849-2700 t:zip_code=52213 t:hr_prkng_24="Yes [more below]" t:rv_dump=Yes t:state=Iowa t:interstate_number=380 t:truck_spaces=100 t:facility_id="I-380 Exit-35, ID-1" t:food_purchase=Yes t:restrooms="Yes - 24 Hours" t:city="Center Point" t:car_trk_pernight="120 trucks, 50 car" t:area_type="Urban Area" t:exit_number=35 t:wi_fi=Yes t:busy_season_car=Summer t:car_holiday_wknd=No t:busy_day_car=Friday-Saturday t:location_facility_id="I-380 Exit-35, ID-1" t:accessible=Yes t:pet_exercise=Yes t:free_prkng=Yes t:aslsummshort=24hr_RR_TP_TI t:place="CENTER POINT TRAVEL PLAZA" t:other_services="Scale, fax, showers and laundry, restaurants" t:wi_fi_free=Free t:truck_perc_group=0-74% t:busy_time_truck=9-11am t:busy_day_truck=Weekdays t:surveyed=Yes t:elect_veh_charge=No t:email_request=No t:family_restroom=No t:busy_season_truck=Summer t:tdd=No t:truck_parking=Yes t:elect_free=N/A t:category="Gasoline Stations with Convenience Stores" t:busy_time_car=5-6pm t:trck_full="Yes, often" t:hours_24=Yes t:travel_info=Yes t:name_request="Brian Maloney" t:cars_truck=Both t:objectid=42 t:telephone=Yes t:future_question=Yes m:approx_number_truck_space=100 m:handi_spaces=6 m:truck_percent_utili=70 m:car_spaces=90

series e:3h6i-t6hv d:2016-08-19T21:14:11.000Z t:dot_tech_partner="No/Corporate question" t:phone_number=563-386-7710 t:zip_code=52806 t:hr_prkng_24="Yes [more below]" t:rv_dump=Yes t:state=Iowa t:interstate_number=80 t:truck_spaces=200 t:facility_id="I-80 Exit-292, ID-2" t:food_purchase=Yes t:restrooms="Yes - 24 Hours" t:city=Davenport t:car_trk_pernight="160-170 semi, 35 cars" t:area_type="Urban Area" t:exit_number=292 t:wi_fi=Yes t:busy_season_car=Summer t:car_holiday_wknd=Yes t:busy_day_car=Sunday t:location_facility_id="I-80 Exit-292, ID-2" t:accessible=Yes t:pet_exercise=Yes t:free_prkng=Yes t:aslsummshort=24hr_RR_TP_TI t:place="FLYING J TRAVEL PLAZA" t:other_services="Showers (paid)" t:wi_fi_free="Not Free" t:truck_perc_group=75-99% t:busy_time_truck="11am - 7pm" t:busy_day_truck="Thursday & Friday" t:surveyed=Yes t:elect_veh_charge=No t:email_request=store636@pilottravelcenters.com t:family_restroom=No t:wi_fi_price="$4.99 daily, $19.99 monthly, $100 annual" t:busy_season_truck=Summer t:tdd=No t:truck_parking=Yes t:elect_free=N/A t:category="Gasoline Stations with Convenience Stores" t:busy_time_car=Morning t:trck_full="Yes, not often" t:hours_24=Yes t:travel_info=Yes t:name_request="Douglas Willet" t:cars_truck=Both t:objectid=71 t:telephone=Yes t:future_question=Yes m:approx_number_truck_space=200 m:handi_spaces=3 m:truck_percent_utili=95 m:car_spaces=50
```

## Meta Commands

```ls
metric m:handi_spaces p:integer l:Handi_Spaces d:"Handicap Parking Spaces" t:dataTypeName=number

metric m:approx_number_truck_space p:integer l:Approx_Number_Truck_Space d:"Appoximate Number of Truck Spaces" t:dataTypeName=number

metric m:truck_percent_utili p:integer l:Truck_Percent_Utili d:"Truck Utilization Percent" t:dataTypeName=number

entity e:3h6i-t6hv l:"Alternative Service Locations - RV Dump Station" t:attribution="Iowa DOT, HDR Engineering" t:url=https://data.iowa.gov/api/views/3h6i-t6hv

property e:3h6i-t6hv t:meta.view v:id=3h6i-t6hv v:category="Transportation & Utilities" v:averageRating=0 v:name="Alternative Service Locations - RV Dump Station" v:attribution="Iowa DOT, HDR Engineering"

property e:3h6i-t6hv t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:3h6i-t6hv t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```

## Top Records

```ls
| :updated_at | objectid | facility_id              | place                              | category                                  | interstate_number | exit_number | area_type  | address                                     | city         | state | zip_code | phone_number | surveyed | hours_24 | hours_operate | accessible | cars_truck | truck_parking | free_prkng | car_spaces | truck_spaces                                              | handi_spaces | busy_day_truck    | busy_time_truck     | busy_season_truck | busy_day_car    | busy_time_car | busy_season_car | car_holiday_wknd | hr_prkng_24      | parking_hours | car_trk_pernight                       | trck_full        | restrooms          | family_restroom | telephone | tdd | wi_fi | wi_fi_free | wi_fi_price                              | travel_info | rv_dump | elect_veh_charge | elect_free | picnic | pet_exercise | food_purchase | dot_tech_partner      | other_services                                                             | name_request       | email_request                   | future_question | location_facility_id     | approx_number_truck_space | truck_percent_utili | truck_perc_group | aslsummshort  | 
| =========== | ======== | ======================== | ================================== | ========================================= | ================= | =========== | ========== | =========================================== | ============ | ===== | ======== | ============ | ======== | ======== | ============= | ========== | ========== | ============= | ========== | ========== | ========================================================= | ============ | ================= | =================== | ================= | =============== | ============= | =============== | ================ | ================ | ============= | ====================================== | ================ | ================== | =============== | ========= | === | ===== | ========== | ======================================== | =========== | ======= | ================ | ========== | ====== | ============ | ============= | ===================== | ========================================================================== | ================== | =============================== | =============== | ======================== | ========================= | =================== | ================ | ============= | 
| 0           | 14       | I-35 & 80 Exit-126, ID-1 | PILOT TRAVEL CENTERS LLC           | Other Gasoline Stations                   | 35 & 80           | 126         | Urban Area | 11957 Douglas Avenue, Des Moines, IA, 50322 | Des Moines   | Iowa  | 50322    | 5152761509   | Yes      | Yes      | NA            | Yes        | Both       | Yes           | Yes        | 40         | 75                                                        | 12           | Weekends          | Fri nights          | Winter            | Wednesdays      | Noon          | Summer          | No               | Yes              | N/A           | N/A                                    | Yes-Weekends     | Yes - 24 Hours     | No              | Yes       | Yes | No    | Not Free   | $4.79 day                                | No          | Yes     | No               | N/A        | No     | No           | Yes           | N/A                   | Restaurant/Food Service                                                    | Charles Sang       | No                              |                 | I-35 & 80 Exit-126, ID-1 | 75                        | 85                  | 75-99%           | 24hr_RR_TP    | 
| 0           | 42       | I-380 Exit-35, ID-1      | CENTER POINT TRAVEL PLAZA          | Gasoline Stations with Convenience Stores | 380               | 35          | Urban Area | 696 Grain Lane                              | Center Point | Iowa  | 52213    | 319-849-2700 | Yes      | Yes      |               | Yes        | Both       | Yes           | Yes        | 90         | 100                                                       | 6            | Weekdays          | 9-11am              | Summer            | Friday-Saturday | 5-6pm         | Summer          | No               | Yes [more below] |               | 120 trucks, 50 car                     | Yes, often       | Yes - 24 Hours     | No              | Yes       | No  | Yes   | Free       |                                          | Yes         | Yes     | No               | N/A        |        | Yes          | Yes           | No/Corporate question | Scale, fax, showers and laundry, restaurants                               | Brian Maloney      | No                              | Yes             | I-380 Exit-35, ID-1      | 100                       | 70                  | 0-74%            | 24hr_RR_TP_TI | 
| 0           | 71       | I-80 Exit-292, ID-2      | FLYING J TRAVEL PLAZA              | Gasoline Stations with Convenience Stores | 80                | 292         | Urban Area | 8200 Northwest Blvd                         | Davenport    | Iowa  | 52806    | 563-386-7710 | Yes      | Yes      |               | Yes        | Both       | Yes           | Yes        | 50         | 200                                                       | 3            | Thursday & Friday | 11am - 7pm          | Summer            | Sunday          | Morning       | Summer          | Yes              | Yes [more below] |               | 160-170 semi, 35 cars                  | Yes, not often   | Yes - 24 Hours     | No              | Yes       | No  | Yes   | Not Free   | $4.99 daily, $19.99 monthly, $100 annual | Yes         | Yes     | No               | N/A        |        | Yes          | Yes           | No/Corporate question | Showers (paid)                                                             | Douglas Willet     | store636@pilottravelcenters.com | Yes             | I-80 Exit-292, ID-2      | 200                       | 95                  | 75-99%           | 24hr_RR_TP_TI | 
| 0           | 109      | I-80 Exit-173, ID-1      | SHORTSTOP TRAVEL PLAZA/PHILLIPS 66 | Gasoline Stations with Convenience Stores | 80                | 173         | Rural Area | 1570 Iowa 224                               | Kellogg      | Iowa  | 50135    | 641-526-8535 | Yes      | No       | 6am-10pm      | Yes        | Both       | Yes           | Yes        | 50         | 8                                                         | 2            | Varies            | Varies              | Summer            | ?               | ?             | Summer          | Yes              | Yes [more below] |               | 8 trucks                               | No               | Yes - Not 24 Hours | Yes             | Yes       | No  | Yes   | Free       |                                          | No          | Yes     | No               | N/A        |        | Yes          | Yes           | No/Manager question   |                                                                            | Diane Wenndt       | No                              | Yes             |                          |                           |                     |                  | RR_Not24hr    | 
| 0           | 110      | I-80 Exit-168, ID-1      | LOVES TRAVEL CENTER                | Gasoline Stations with Convenience Stores | 80                | 168         | Urban Area | 4400 S 22nd Ave E                           | Newton       | Iowa  | 50208    | 641-791-2410 | Yes      | Yes      |               | Yes        | Both       | Yes           | Yes        | 80         | 100                                                       | 8            | Thursday          | 09/19/2012          | Summer            | All the same    | 09/19/2012    | Summer          | Yes              | Yes [more below] |               | 10 cars (2hr limit), 85 trucks         | Yes, not often   | Yes - 24 Hours     | Yes             | Yes       | No  | Yes   | Not Free   | Unsure                                   | No          | Yes     | No               | N/A        |        | Yes          | Yes           | No/Corporate question |                                                                            | Jamie Black        | No                              | Yes             | I-80 Exit-168, ID-1      | 100                       | 90                  | 75-99%           | 24hr_RR_TP    | 
| 0           | 138      | I-80 Exit-40, ID-1       | WINGS AMERICA LIMITED PARTNERSHIP  | Other Gasoline Stations                   | 80                | 40          | Urban Area | 7005 N Chesnut St                           | Avoca        | Iowa  | 51521    | 712-343-4007 | Yes      | Yes      |               | Yes        | Both       | Yes           | Yes        | 100        | 250                                                       | 6            | Thursday-Friday   | after 5pm           | Summer            | Saturday        | Noon          | Summer          | No               | Yes [more below] |               | 250+ trucks, 20 cars                   | Often            | Yes - 24 Hours     | Yes             | Yes       | No  | Yes   | Free       |                                          | Yes         | Yes     | No               | N/A        |        | Yes          | Yes           | No/Corporate question | Cat scale, showers, restaurants, theater, drivers lounge, laundry, massage | Jeff Bradley       | No                              | Yes             | I-80 Exit-40, ID-1       | 250                       | 70                  | 0-74%            | 24hr_RR_TP_TI | 
| 0           | 158      | I-35 Exit-144, ID-1      | BOONDOCKS TRUCK HAVEN              | Other Gasoline Stations                   | 35                | 144         | Rural Area | 3073 220th St                               | Williams     | Iowa  | 50271    | 515-854-2763 | Yes      | Yes      |               | Yes        | Both       | Yes           | Yes        | ?          | ?                                                         | 3            | Monday-Thursday   | Overnight           | Summer            | Sunday          | Morning       | Summer          | Yes              | Yes [more below] |               | Unsure                                 | Yes              | Yes - 24 Hours     | No              | Yes       | No  | Yes   | Free       |                                          | Yes         | Yes     | Yes              | Yes        |        | No           | Yes           | Yes                   |                                                                            | Connie Richtsmeier | No                              | Yes             | I-35 Exit-144, ID-1      | 100                       | 80                  | 75-99%           | 24hr_RR_TP_TI | 
| 0           | 188      | I-35 Exit-34, ID-2       | Pilot Travel Center                | Gas Station/Convenience                   | 35                | 34          | Urban Area | 2010 West Clay Street, Osceola, IA, 50213   | Osceola      | Iowa  | 50213    | 641-342-8658 | Yes      | Yes      | NA            | Yes        | both       | Yes           | Yes        | 40         | 80                                                        | 4            | Thursday/Friday   | 4:00-6:00           | Spring, Summer    | Friday evening  | N/A           | Spring, Summer  | Yes              | No               | 12            | 60-80 trucks                           | Yes              | Yes - 24 Hours     | Yes             | Yes       | No  | No    | Not Free   | $4.79/day, $14.99/month, $149/year       | Yes         | Yes     | No               | N/A        | No     | Yes          | Yes           | Corporate             | Vaccuum center, air center                                                 | ? Hollinger        | store131@pilottravelcenters.com |                 | I-35 Exit-34, ID-2       | 80                        | 95                  | 75-99%           | 24hr_RR_TP_TI | 
| 0           | 226      | I-29 Exit-10, ID-1       | SAPP BROS TRUCK STOPS              | Other Gasoline Stations                   | 29                | 10          | Rural Area | 2496 210th Ave                              | Percival     | Iowa  | 51648    | 712-382-1101 | Yes      | Yes      |               | Yes        | Both       | Yes           | Yes        | 75         | 150 (two lots - 75 across street, 54 lot behind building) | 10           | Tues/Weds         | Dinner hour (6-8pm) | Fall              | Weekends        | All day       | Summer          | Yes              | Yes [more below] |               | Trucks fill up lot, cars steady amount | Yes, every night | Yes - 24 Hours     | Yes             | Yes       | Yes | Yes   | Free       |                                          | Yes         | Yes     | No               | N/A        |        | Yes          | Yes           | Yes                   | ATM, full store including bedding, clothing, gifts, etc.                   | Brad Buckingham    | bbuckingham@sappbros.net        | Yes             | I-29 Exit-10, ID-1       | 150                       | 85                  | 75-99%           | 24hr_RR_TP_TI | 
```