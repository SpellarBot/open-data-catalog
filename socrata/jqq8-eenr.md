# Alternative Service Locations - Wi-Fi

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/alternative-service-locations-wi-fi) |
| Metadata | [Link](https://data.iowa.gov/api/views/jqq8-eenr) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/jqq8-eenr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/jqq8-eenr/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | jqq8-eenr |
| Name | Alternative Service Locations - Wi-Fi |
| Attribution | Iowa DOT, HDR Engineering |
| Category | Transportation & Utilities |
| Tags | asset, classification, rest, area, alternative, service, iowa dot, iowa department of transportation |
| Created | 2016-08-19T21:12:04Z |
| Publication Date | 2016-08-19T21:13:56Z |

## Description

Iowa Department of Transportation statewide rest area data. This layer displays alternative service locations that have Wi-Fi.

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
series e:jqq8-eenr d:2016-08-19T21:12:04.000Z t:dot_tech_partner="Call corporate" t:phone_number=515-251-5819 t:zip_code=50322 t:hr_prkng_24=No t:rv_dump=No t:state=Iowa t:interstate_number="35 & 80" t:parking_hours="Business hours" t:truck_spaces=0 t:facility_id="I-35 & 80 Exit-127, ID-3" t:food_purchase=Yes t:restrooms="Yes - Not 24 Hours" t:city=Urbandale t:car_trk_pernight=N/A t:area_type="Urban Area" t:exit_number=127 t:wi_fi=Yes t:busy_season_car=April-July t:car_holiday_wknd=Yes t:busy_day_car="Saturday, Sunday" t:hours_operate="Open times vary; close at 10:00" t:accessible=Yes t:pet_exercise=No t:free_prkng=Yes t:aslsummshort=RR_Not24hr t:place="Home Depot" t:other_services=No t:wi_fi_free=Free t:busy_time_truck=10:00-2:00 t:busy_day_truck="Wednesday, Friday" t:surveyed=Yes t:elect_veh_charge=No t:email_request=robert_douglas_gilbert@homedepot.com t:family_restroom=No t:wi_fi_price=N/A t:busy_season_truck=March-July t:tdd=No t:truck_parking=Unknown t:elect_free=N/A t:category="Convenience Store" t:busy_time_car="10:00-5:00 Saturday" t:hours_24=No t:trck_full=N/A t:travel_info=No t:name_request="Robert Gilbert" t:cars_truck=Both t:objectid=13 t:telephone=No t:picnic=No m:handi_spaces=9

series e:jqq8-eenr d:2016-08-19T21:12:04.000Z t:dot_tech_partner="No/Corporate question" t:phone_number=712-322-3000 t:zip_code=51501 t:hr_prkng_24="Yes [more below]" t:rv_dump=No t:state=Iowa t:interstate_number="29 & 80" t:truck_spaces=110 t:facility_id="I-29 & 80 Exit-1B, ID-4" t:food_purchase=Yes t:restrooms="Yes - 24 Hours" t:city="Council Bluffs" t:car_trk_pernight="75 trucks, 20 cars" t:area_type="Urban Area" t:exit_number=1B t:wi_fi=Yes t:busy_season_car=Summer t:car_holiday_wknd=Yes t:busy_day_car=Thursday t:location_facility_id="I-29 & 80 Exit-1B, ID-4" t:accessible=Yes t:pet_exercise=Yes t:free_prkng=Yes t:aslsummshort=24hr_RR_TP_TI t:place="SAPP BROS TRUCK STOPS" t:other_services="D.A.T load board, laundry, showers, fax, ATM, restaurants" t:car_spaces=55 t:wi_fi_free=Free t:truck_perc_group=75-99% t:busy_time_truck=Afternoon t:busy_day_truck=Friday t:surveyed=Yes t:elect_veh_charge=No t:email_request=No t:family_restroom=No t:busy_season_truck=Winter t:tdd=No t:truck_parking=Yes t:elect_free=N/A t:category="Other Gasoline Stations" t:busy_time_car=3pm-8pm t:trck_full=No t:hours_24=Yes t:travel_info=Yes t:name_request="Susan West" t:cars_truck=Both t:objectid=30 t:telephone=Yes t:future_question=Yes m:approx_number_truck_space=110 m:handi_spaces=8 m:truck_percent_utili=85

series e:jqq8-eenr d:2016-08-19T21:12:04.000Z t:dot_tech_partner="No/Corporate question" t:phone_number=319-849-2700 t:zip_code=52213 t:hr_prkng_24="Yes [more below]" t:rv_dump=Yes t:state=Iowa t:interstate_number=380 t:truck_spaces=100 t:facility_id="I-380 Exit-35, ID-1" t:food_purchase=Yes t:restrooms="Yes - 24 Hours" t:city="Center Point" t:car_trk_pernight="120 trucks, 50 car" t:area_type="Urban Area" t:exit_number=35 t:wi_fi=Yes t:busy_season_car=Summer t:car_holiday_wknd=No t:busy_day_car=Friday-Saturday t:location_facility_id="I-380 Exit-35, ID-1" t:accessible=Yes t:pet_exercise=Yes t:free_prkng=Yes t:aslsummshort=24hr_RR_TP_TI t:place="CENTER POINT TRAVEL PLAZA" t:other_services="Scale, fax, showers and laundry, restaurants" t:car_spaces=90 t:wi_fi_free=Free t:truck_perc_group=0-74% t:busy_time_truck=9-11am t:busy_day_truck=Weekdays t:surveyed=Yes t:elect_veh_charge=No t:email_request=No t:family_restroom=No t:busy_season_truck=Summer t:tdd=No t:truck_parking=Yes t:elect_free=N/A t:category="Gasoline Stations with Convenience Stores" t:busy_time_car=5-6pm t:trck_full="Yes, often" t:hours_24=Yes t:travel_info=Yes t:name_request="Brian Maloney" t:cars_truck=Both t:objectid=42 t:telephone=Yes t:future_question=Yes m:approx_number_truck_space=100 m:handi_spaces=6 m:truck_percent_utili=70
```

## Meta Commands

```ls
metric m:handi_spaces p:integer l:Handi_Spaces d:"Handicap Parking Spaces" t:dataTypeName=number

metric m:approx_number_truck_space p:integer l:Approx_Number_Truck_Space d:"Appoximate Number of Truck Spaces" t:dataTypeName=number

metric m:truck_percent_utili p:integer l:Truck_Percent_Utili d:"Truck Utilization Percent" t:dataTypeName=number

entity e:jqq8-eenr l:"Alternative Service Locations - Wi-Fi" t:attribution="Iowa DOT, HDR Engineering" t:url=https://data.iowa.gov/api/views/jqq8-eenr

property e:jqq8-eenr t:meta.view v:id=jqq8-eenr v:category="Transportation & Utilities" v:averageRating=0 v:name="Alternative Service Locations - Wi-Fi" v:attribution="Iowa DOT, HDR Engineering"

property e:jqq8-eenr t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:jqq8-eenr t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```

## Top Records

```ls
| :updated_at | objectid | facility_id              | place                               | category                                  | interstate_number | exit_number | area_type  | address                                | city           | state | zip_code | phone_number | surveyed | hours_24 | hours_operate                     | accessible | cars_truck                                                 | truck_parking | free_prkng | car_spaces | truck_spaces                                                    | handi_spaces | busy_day_truck    | busy_time_truck | busy_season_truck | busy_day_car     | busy_time_car       | busy_season_car | car_holiday_wknd | hr_prkng_24      | parking_hours       | car_trk_pernight   | trck_full             | restrooms          | family_restroom | telephone | tdd                   | wi_fi | wi_fi_free | wi_fi_price | travel_info | rv_dump | elect_veh_charge | elect_free | picnic | pet_exercise | food_purchase | dot_tech_partner                     | other_services                                                                                                        | name_request   | email_request                        | future_question | location_facility_id    | approx_number_truck_space | truck_percent_utili | truck_perc_group | aslsummshort  | 
| =========== | ======== | ======================== | =================================== | ========================================= | ================= | =========== | ========== | ====================================== | ============== | ===== | ======== | ============ | ======== | ======== | ================================= | ========== | ========================================================== | ============= | ========== | ========== | =============================================================== | ============ | ================= | =============== | ================= | ================ | =================== | =============== | ================ | ================ | =================== | ================== | ===================== | ================== | =============== | ========= | ===================== | ===== | ========== | =========== | =========== | ======= | ================ | ========== | ====== | ============ | ============= | ==================================== | ===================================================================================================================== | ============== | ==================================== | =============== | ======================= | ========================= | =================== | ================ | ============= | 
| 0           | 13       | I-35 & 80 Exit-127, ID-3 | Home Depot                          | Convenience Store                         | 35 & 80           | 127         | Urban Area | 10850 Plum Drive, Urbandale, IA, 50322 | Urbandale      | Iowa  | 50322    | 515-251-5819 | Yes      | No       | Open times vary; close at 10:00   | Yes        | Both                                                       | Unknown       | Yes        |            | 0                                                               | 9            | Wednesday, Friday | 10:00-2:00      | March-July        | Saturday, Sunday | 10:00-5:00 Saturday | April-July      | Yes              | No               | Business hours      | N/A                | N/A                   | Yes - Not 24 Hours | No              | No        | No                    | Yes   | Free       | N/A         | No          | No      | No               | N/A        | No     | No           | Yes           | Call corporate                       | No                                                                                                                    | Robert Gilbert | robert_douglas_gilbert@homedepot.com |                 |                         |                           |                     |                  | RR_Not24hr    | 
| 0           | 30       | I-29 & 80 Exit-1B, ID-4  | SAPP BROS TRUCK STOPS               | Other Gasoline Stations                   | 29 & 80           | 1B          | Urban Area | 2608 S. 24th St                        | Council Bluffs | Iowa  | 51501    | 712-322-3000 | Yes      | Yes      |                                   | Yes        | Both                                                       | Yes           | Yes        | 55         | 110                                                             | 8            | Friday            | Afternoon       | Winter            | Thursday         | 3pm-8pm             | Summer          | Yes              | Yes [more below] |                     | 75 trucks, 20 cars | No                    | Yes - 24 Hours     | No              | Yes       | No                    | Yes   | Free       |             | Yes         | No      | No               | N/A        |        | Yes          | Yes           | No/Corporate question                | D.A.T load board, laundry, showers, fax, ATM, restaurants                                                             | Susan West     | No                                   | Yes             | I-29 & 80 Exit-1B, ID-4 | 110                       | 85                  | 75-99%           | 24hr_RR_TP_TI | 
| 0           | 42       | I-380 Exit-35, ID-1      | CENTER POINT TRAVEL PLAZA           | Gasoline Stations with Convenience Stores | 380               | 35          | Urban Area | 696 Grain Lane                         | Center Point   | Iowa  | 52213    | 319-849-2700 | Yes      | Yes      |                                   | Yes        | Both                                                       | Yes           | Yes        | 90         | 100                                                             | 6            | Weekdays          | 9-11am          | Summer            | Friday-Saturday  | 5-6pm               | Summer          | No               | Yes [more below] |                     | 120 trucks, 50 car | Yes, often            | Yes - 24 Hours     | No              | Yes       | No                    | Yes   | Free       |             | Yes         | Yes     | No               | N/A        |        | Yes          | Yes           | No/Corporate question                | Scale, fax, showers and laundry, restaurants                                                                          | Brian Maloney  | No                                   | Yes             | I-380 Exit-35, ID-1     | 100                       | 70                  | 0-74%            | 24hr_RR_TP_TI | 
| 0           | 46       | I-380 Exit-24B, ID-1     | LOWES HOME IMPROVEMENT              | All Other General Merchandise Stores      | 380               | 24B         | Urban Area | 5300 Blairs Ferry Rd                   | Hiawatha       | Iowa  | 52402    | 319-294-3780 | Yes      | No       | M-SAT 6:30AM-9PM; SUN 8AM-8PM     | Yes        | Both                                                       | Unknown       | Yes        | 100        | 8                                                               | 12           | VARIES            | VARIES          | Summer            | SATURDAY         | 10-4PM              | Summer          | Yes              | No [more below]  | BUSINESS HOURS ONLY |                    | VENDORS ONLY          | Yes - Not 24 Hours | Yes             | Yes       | CUSTOMER SERVICE ONLY | Yes   | Free       |             | No          | No      | No               |            |        | No           | Yes           | CORPORATE QUESTION; UNABLE TO ANSWER | No                                                                                                                    | JASON NORRIS   | No                                   | Yes             |                         |                           |                     |                  | RR_Not24hr    | 
| 0           | 64       | I-380 Exit-13, ID-2      | JUST DIESEL/CASEYS GENERAL STORE    | Gasoline Stations with Convenience Stores | 380               | 13          | Urban Area | 9001 6th St SW                         | Cedar Rapids   | Iowa  | 52404    | 319-841-9244 | Yes      | Yes      |                                   | Yes        | Both                                                       | Yes           | Yes        | 30         | 55 (currently expanding to 95, which should be done in October) | 2            | Wednesday         | Noon            | Summer            | Friday           | Noon                | Summer          | Yes              | Yes [more below] |                     | 55 trucks, 5 cars  | Yes, not often        | Yes - 24 Hours     | No              | Yes       | No                    | Yes   | Free       |             | Yes         | No      | No               | N/A        |        | No           | Yes           | No/Corporate question                | Showers and laundry                                                                                                   | Kevin Temple   | No                                   | Yes             |                         |                           |                     |                  | 24hr_RR_TP_TI | 
| 0           | 68       | I-80 Exit-306, ID-1      | MISSISSIPPI MARKETPLACE/PHILLIPS 66 | Gasoline Stations with Convenience Stores | 80                | 306         | Urban Area | 1403 Eagle Ridge Rd                    | Le Claire      | Iowa  | 52753    | 563-289-4801 | Yes      | No       | 5am - 11pm Mon - Fri              | Yes        | Only cars                                                  | Unknown       | Yes        | 50         |                                                                 |              |                   |                 |                   | Fri - Sun        | Morning             | Summer          | Yes              | No [more below]  | Business Hours Only |                    |                       | Yes - Not 24 Hours | No              | No        |                       | No    | Free       |             | No          | No      | No               |            |        | No           | Yes           | No                                   |                                                                                                                       | No             | No                                   | No              |                         |                           |                     |                  | RR_Not24hr    | 
| 0           | 72       | I-80 Exit-284, ID-1      | IOWA 80 TRAVEL PLAZA                | Gasoline Stations with Convenience Stores | 80                | 284         | Rural Area | 755 Interstate 80 Road                 | Walcott        | Iowa  | 52773    | 563-284-6961 | Yes      | Yes      |                                   | Yes        | Both                                                       | Yes           | Yes        | 150        | 850 (soon to be 1,000)                                          |              | Saturday          | Nighttime       | Summer            | Weekends         | Noon                | Summer          | Yes              | Yes [more below] |                     | 600-800            | Yes, most of the time | Yes - 24 Hours     | Yes             | Yes       | No                    | Yes   | Free       |             | Yes         | No      | No               | N/A        |        | Yes          | Yes           | Yes                                  | 75-seat theatre, restaurants, dentist, chiropractor                                                                   | Jim Morris     | jim.morris@iowa80group.com           | Yes             | I-80 Exit-284, ID-1     | 850                       | 85                  | 75-99%           | 24hr_RR_TP_TI | 
| 0           | 90       | I-80 Exit-240, ID-2      | LOWES HOME IMPROVEMENT              | All Other General Merchandise Stores      | 80                | 240         | Urban Area | 2701 2nd St                            | Coralville     | Iowa  | 52241    | 319-545-8300 | Yes      | No       | M-SAT: 6:30AM TO 9PM; SUN:8AM-8PM | Yes        | Only cars/DOES PERMIT SEMI TRUCK PARKING (ONCE IN A WHILE) | Unknown       | Yes        | 60-75      | 0                                                               | 12           | VARIES            | VARIES          | Summer            | SAT/SUN          | 2-4PM               | Summer          | Yes              | No [more below]  | BUSINESS HOURS      |                    |                       | Yes - Not 24 Hours | Yes             | No        |                       | Yes   | Free       |             | No          | No      | No               |            |        | No           | Yes           | CORPORATE QUESTION                   | No                                                                                                                    | SHAMUS FREEMAN | No                                   | Yes             |                         |                           |                     |                  | RR_Not24hr    | 
| 0           | 91       | I-80 Exit-240, ID-3      | TARGET                              | All Other General Merchandise Stores      | 80                | 240         | Urban Area | 1441 Coral Ridge Ave                   | Coralville     | Iowa  | 52241    | 319-351-5150 | Yes      |          | MON:8AM 11PM; SUN: 8AM - 10PM     | Yes        | Only cars                                                  | Unknown       | Yes        |            |                                                                 |              |                   |                 |                   |                  |                     |                 |                  |                  |                     |                    |                       | Yes                | No              | Yes       | Yes                   | Yes   | Free       |             | Unknown     | No      |                  |            |        | No           | Yes           | No/THIS IS A CORPORATE               | THEY ARE LOCATED IN A MALL AND ARE NOT IN CHARGE OF THE PARKING SO MUCH, SO UNABLE TO ASK MAJORITY OF THE QUESTIONS.. | No             | No                                   | No              |                         |                           |                     |                  | RR_Not24hr    | 
| 0           | 104      | I-80 Exit-201, ID-1      | KWIK TRIP/KWIK STAR                 | Gasoline Stations with Convenience Stores | 80                | 201         | Rural Area | 4177 Highway 21                        | Brooklyn       | Iowa  | 52211    | 319-685-4411 | Yes      | Yes      |                                   | Yes        | Both                                                       | Yes           | Yes        | 30         | 200                                                             | 5            | Steady            | Depends on day  |                   | ?                | ?                   |                 | No               | Yes [more below] |                     | ?                  | No                    | Yes - 24 Hours     | No              | Yes       | No                    | Yes   | Free       |             | No          | No      | No               | N/A        |        | Yes          | Yes           | No/Corporate question                | Showers                                                                                                               | Megan Vajgrt   | No                                   | Yes             | I-80 Exit-201, ID-1     | 200                       | 80                  | 75-99%           | 24hr_RR_TP    | 
```