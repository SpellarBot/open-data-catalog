# Alternative Service Locations - Telephone

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/alternative-service-locations-telephone) |
| Metadata | [Link](https://data.iowa.gov/api/views/hdui-gwut) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/hdui-gwut/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/hdui-gwut/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | hdui-gwut |
| Name | Alternative Service Locations - Telephone |
| Attribution | Iowa DOT, HDR Engineering |
| Category | Transportation & Utilities |
| Tags | asset, classification, rest, area, alternative, service, iowa dot, iowa department of transportation |
| Created | 2016-08-19T21:05:37Z |
| Publication Date | 2016-08-19T21:07:32Z |

## Description

Iowa Department of Transportation statewide rest area data. This layer displays alternative service locations that have a telephone.

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
series e:hdui-gwut d:2016-08-19T21:05:37.000Z t:dot_tech_partner=N/A t:phone_number=5152761509 t:rv_dump=Yes t:hr_prkng_24=Yes t:parking_hours=N/A t:food_purchase=Yes t:car_trk_pernight=N/A t:city="Des Moines" t:exit_number=126 t:wi_fi=No t:car_holiday_wknd=No t:busy_season_car=Summer t:location_facility_id="I-35 & 80 Exit-126, ID-1" t:hours_operate=NA t:free_prkng=Yes t:pet_exercise=No t:place="PILOT TRAVEL CENTERS LLC" t:car_spaces=40 t:wi_fi_free="Not Free" t:handi_spaces=12 t:busy_day_truck=Weekends t:elect_veh_charge=No t:wi_fi_price="$4.79 day" t:busy_season_truck=Winter t:elect_free=N/A t:category="Other Gasoline Stations" t:trck_full=Yes-Weekends t:hours_24=Yes t:travel_info=No t:objectid=14 t:cars_truck=Both t:picnic=No t:zip_code=50322 t:state=Iowa t:interstate_number="35 & 80" t:truck_spaces=75 t:facility_id="I-35 & 80 Exit-126, ID-1" t:restrooms="Yes - 24 Hours" t:area_type="Urban Area" t:busy_day_car=Wednesdays t:accessible=Yes t:aslsummshort=24hr_RR_TP t:other_services="Restaurant/Food Service" t:truck_perc_group=75-99% t:busy_time_truck="Fri nights" t:surveyed=Yes t:family_restroom=No t:email_request=No t:tdd=Yes t:truck_parking=Yes t:busy_time_car=Noon t:name_request="Charles Sang" t:telephone=Yes m:approx_number_truck_space=75 m:truck_percent_utili=85

series e:hdui-gwut d:2016-08-19T21:05:37.000Z t:dot_tech_partner=No t:phone_number=5152767437 t:rv_dump=No t:hr_prkng_24=No t:parking_hours="Only trucks--any time" t:food_purchase=Yes t:car_trk_pernight=200 t:city=Clive t:exit_number=125 t:wi_fi=No t:car_holiday_wknd=No t:busy_season_car=Summer t:location_facility_id="I-35 & 80 Exit-125, ID-2" t:hours_operate=NA t:free_prkng=Yes t:pet_exercise=Yes t:place="Love's Travel Stop" t:car_spaces=130 t:wi_fi_free="Not Free" t:handi_spaces=6 t:busy_day_truck=Tuesday-Wednesday t:elect_veh_charge=No t:wi_fi_price="AT&T provides it--not sure" t:busy_season_truck=Summer t:elect_free=N/A t:category="Gas Station/Conveinece" t:trck_full="Yes--3 nights/week" t:hours_24=Yes t:travel_info=No t:objectid=17 t:cars_truck=Both t:picnic=No t:zip_code=50325 t:state=Iowa t:interstate_number="35 & 80" t:truck_spaces=250 t:facility_id="I-35 & 80 Exit-125, ID-2" t:restrooms="Yes - 24 Hours" t:area_type="Urban Area" t:busy_day_car=Varies t:accessible=Yes t:aslsummshort=24hr_RR_TP t:other_services=No t:truck_perc_group=75-99% t:busy_time_truck=Varies t:surveyed=Yes t:family_restroom=Yes t:email_request=store411@love.com t:tdd=Yes t:truck_parking=Yes t:busy_time_car=Day t:name_request="? Long" t:telephone=Yes m:approx_number_truck_space=250 m:truck_percent_utili=90

series e:hdui-gwut d:2016-08-19T21:05:37.000Z t:dot_tech_partner="No/Corporate question" t:phone_number=712-322-0088 t:rv_dump=No t:hr_prkng_24="Yes [more below]" t:food_purchase=Yes t:car_trk_pernight="70 trucks, 5 cars" t:city="Council Bluffs" t:exit_number=1B t:wi_fi=Yes t:car_holiday_wknd=Yes t:busy_season_car=Summer t:location_facility_id="I-29 & 80 Exit-1B, ID-3" t:free_prkng=Yes t:pet_exercise=No t:place="PILOT TRAVEL CENTERS LLC" t:car_spaces=40 t:wi_fi_free="Not Free" t:handi_spaces=10 t:busy_day_truck=Weds-Sun t:elect_veh_charge=No t:wi_fi_price=$2.99/day t:busy_season_truck=Summer t:category="Other Gasoline Stations" t:elect_free=N/A t:trck_full="Yes, often" t:hours_24=Yes t:travel_info=Yes t:objectid=29 t:cars_truck=Both t:future_question=Yes t:zip_code=51501 t:state=Iowa t:interstate_number="29 & 80" t:truck_spaces=70 t:facility_id="I-29 & 80 Exit-1B, ID-3" t:restrooms="Yes - 24 Hours" t:area_type="Urban Area" t:busy_day_car=Sunday t:accessible=Yes t:aslsummshort=24hr_RR_TP_TI t:truck_perc_group=75-99% t:busy_time_truck=9am-1pm t:surveyed=Yes t:family_restroom=Yes t:email_request=No t:tdd=No t:truck_parking=Yes t:busy_time_car=11/01/2012 t:name_request="Jason Brown" t:telephone=Yes m:approx_number_truck_space=70 m:truck_percent_utili=90
```

## Meta Commands

```ls
metric m:approx_number_truck_space p:integer l:Approx_Number_Truck_Space d:"Appoximate Number of Truck Spaces" t:dataTypeName=number

metric m:truck_percent_utili p:integer l:Truck_Percent_Utili d:"Truck Utilization Percent" t:dataTypeName=number

entity e:hdui-gwut l:"Alternative Service Locations - Telephone" t:attribution="Iowa DOT, HDR Engineering" t:url=https://data.iowa.gov/api/views/hdui-gwut

property e:hdui-gwut t:meta.view v:id=hdui-gwut v:category="Transportation & Utilities" v:averageRating=0 v:name="Alternative Service Locations - Telephone" v:attribution="Iowa DOT, HDR Engineering"

property e:hdui-gwut t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:hdui-gwut t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```

## Top Records

```ls
| :updated_at | objectid | facility_id              | place                     | category                                  | interstate_number | exit_number | area_type  | address                                     | city           | state | zip_code | phone_number | surveyed | hours_24 | hours_operate                  | accessible | cars_truck | truck_parking | free_prkng | car_spaces | truck_spaces | handi_spaces | busy_day_truck    | busy_time_truck | busy_season_truck | busy_day_car      | busy_time_car      | busy_season_car | car_holiday_wknd | hr_prkng_24      | parking_hours         | car_trk_pernight   | trck_full          | restrooms          | family_restroom | telephone | tdd                   | wi_fi | wi_fi_free | wi_fi_price                | travel_info | rv_dump | elect_veh_charge | elect_free | picnic | pet_exercise | food_purchase | dot_tech_partner                     | other_services                                            | name_request  | email_request     | future_question | location_facility_id     | approx_number_truck_space | truck_percent_utili | truck_perc_group | aslsummshort  | 
| =========== | ======== | ======================== | ========================= | ========================================= | ================= | =========== | ========== | =========================================== | ============== | ===== | ======== | ============ | ======== | ======== | ============================== | ========== | ========== | ============= | ========== | ========== | ============ | ============ | ================= | =============== | ================= | ================= | ================== | =============== | ================ | ================ | ===================== | ================== | ================== | ================== | =============== | ========= | ===================== | ===== | ========== | ========================== | =========== | ======= | ================ | ========== | ====== | ============ | ============= | ==================================== | ========================================================= | ============= | ================= | =============== | ======================== | ========================= | =================== | ================ | ============= | 
| 0           | 14       | I-35 & 80 Exit-126, ID-1 | PILOT TRAVEL CENTERS LLC  | Other Gasoline Stations                   | 35 & 80           | 126         | Urban Area | 11957 Douglas Avenue, Des Moines, IA, 50322 | Des Moines     | Iowa  | 50322    | 5152761509   | Yes      | Yes      | NA                             | Yes        | Both       | Yes           | Yes        | 40         | 75           | 12           | Weekends          | Fri nights      | Winter            | Wednesdays        | Noon               | Summer          | No               | Yes              | N/A                   | N/A                | Yes-Weekends       | Yes - 24 Hours     | No              | Yes       | Yes                   | No    | Not Free   | $4.79 day                  | No          | Yes     | No               | N/A        | No     | No           | Yes           | N/A                                  | Restaurant/Food Service                                   | Charles Sang  | No                |                 | I-35 & 80 Exit-126, ID-1 | 75                        | 85                  | 75-99%           | 24hr_RR_TP    | 
| 0           | 17       | I-35 & 80 Exit-125, ID-2 | Love's Travel Stop        | Gas Station/Conveinece                    | 35 & 80           | 125         | Urban Area | 11820 Hickman Road, Clive, IA 50325         | Clive          | Iowa  | 50325    | 5152767437   | Yes      | Yes      | NA                             | Yes        | Both       | Yes           | Yes        | 130        | 250          | 6            | Tuesday-Wednesday | Varies          | Summer            | Varies            | Day                | Summer          | No               | No               | Only trucks--any time | 200                | Yes--3 nights/week | Yes - 24 Hours     | Yes             | Yes       | Yes                   | No    | Not Free   | AT&T provides it--not sure | No          | No      | No               | N/A        | No     | Yes          | Yes           | No                                   | No                                                        | ? Long        | store411@love.com |                 | I-35 & 80 Exit-125, ID-2 | 250                       | 90                  | 75-99%           | 24hr_RR_TP    | 
| 0           | 25       | I-29 & 80 Exit-3, ID-5   | CASEYS GENERAL STORE      | Gasoline Stations with Convenience Stores | 29 & 80           | 3           | Urban Area | 510 23rd Ave                                | Council Bluffs | Iowa  | 51501    | 712-322-6235 | Yes      | Yes      |                                | Yes        | Only cars  | Unknown       | Yes        | 15         |              | 2            |                   |                 |                   | Friday            | Varies             | Summer          | Yes              | Yes [more below] |                       | Varies             |                    | Yes - 24 Hours     | No              | Yes       |                       | No    |            |                            | Yes         | No      | No               |            |        | No           | Yes           |                                      |                                                           | No            | No                | No              |                          |                           |                     |                  | 24hr_RR       | 
| 0           | 29       | I-29 & 80 Exit-1B, ID-3  | PILOT TRAVEL CENTERS LLC  | Other Gasoline Stations                   | 29 & 80           | 1B          | Urban Area | 2647 S. 24th St                             | Council Bluffs | Iowa  | 51501    | 712-322-0088 | Yes      | Yes      |                                | Yes        | Both       | Yes           | Yes        | 40         | 70           | 10           | Weds-Sun          | 9am-1pm         | Summer            | Sunday            | 11/01/2012         | Summer          | Yes              | Yes [more below] |                       | 70 trucks, 5 cars  | Yes, often         | Yes - 24 Hours     | Yes             | Yes       | No                    | Yes   | Not Free   | $2.99/day                  | Yes         | No      | No               | N/A        |        | No           | Yes           | No/Corporate question                |                                                           | Jason Brown   | No                | Yes             | I-29 & 80 Exit-1B, ID-3  | 70                        | 90                  | 75-99%           | 24hr_RR_TP_TI | 
| 0           | 30       | I-29 & 80 Exit-1B, ID-4  | SAPP BROS TRUCK STOPS     | Other Gasoline Stations                   | 29 & 80           | 1B          | Urban Area | 2608 S. 24th St                             | Council Bluffs | Iowa  | 51501    | 712-322-3000 | Yes      | Yes      |                                | Yes        | Both       | Yes           | Yes        | 55         | 110          | 8            | Friday            | Afternoon       | Winter            | Thursday          | 3pm-8pm            | Summer          | Yes              | Yes [more below] |                       | 75 trucks, 20 cars | No                 | Yes - 24 Hours     | No              | Yes       | No                    | Yes   | Free       |                            | Yes         | No      | No               | N/A        |        | Yes          | Yes           | No/Corporate question                | D.A.T load board, laundry, showers, fax, ATM, restaurants | Susan West    | No                | Yes             | I-29 & 80 Exit-1B, ID-4  | 110                       | 85                  | 75-99%           | 24hr_RR_TP_TI | 
| 0           | 36       | I-380 Exit-70, ID-2      | CASEYS GENERAL STORE      | Gasoline Stations with Convenience Stores | 380               | 70          | Urban Area | 1038 River Forest Rd                        | Evansdale      | Iowa  | 50707    | 319-232-6900 | Yes      | No       | 5am -11pm Mon-Sat 6am-11pm Sun | Yes        | Both       | Unknown       | Yes        | 25 - 30    |              | 2            | Monday            | Varies          | Summer            | Saturday          | 6am - 9am          | Summer          | No               | No [more below]  | During business hours |                    |                    | Yes - Not 24 Hours | Yes             | Yes       |                       |       |            |                            | Unknown     |         |                  |            |        |              | Yes           |                                      |                                                           | No            | No                | No              |                          |                           |                     |                  | RR_Not24hr    | 
| 0           | 42       | I-380 Exit-35, ID-1      | CENTER POINT TRAVEL PLAZA | Gasoline Stations with Convenience Stores | 380               | 35          | Urban Area | 696 Grain Lane                              | Center Point   | Iowa  | 52213    | 319-849-2700 | Yes      | Yes      |                                | Yes        | Both       | Yes           | Yes        | 90         | 100          | 6            | Weekdays          | 9-11am          | Summer            | Friday-Saturday   | 5-6pm              | Summer          | No               | Yes [more below] |                       | 120 trucks, 50 car | Yes, often         | Yes - 24 Hours     | No              | Yes       | No                    | Yes   | Free       |                            | Yes         | Yes     | No               | N/A        |        | Yes          | Yes           | No/Corporate question                | Scale, fax, showers and laundry, restaurants              | Brian Maloney | No                | Yes             | I-380 Exit-35, ID-1      | 100                       | 70                  | 0-74%            | 24hr_RR_TP_TI | 
| 0           | 46       | I-380 Exit-24B, ID-1     | LOWES HOME IMPROVEMENT    | All Other General Merchandise Stores      | 380               | 24B         | Urban Area | 5300 Blairs Ferry Rd                        | Hiawatha       | Iowa  | 52402    | 319-294-3780 | Yes      | No       | M-SAT 6:30AM-9PM; SUN 8AM-8PM  | Yes        | Both       | Unknown       | Yes        | 100        | 8            | 12           | VARIES            | VARIES          | Summer            | SATURDAY          | 10-4PM             | Summer          | Yes              | No [more below]  | BUSINESS HOURS ONLY   |                    | VENDORS ONLY       | Yes - Not 24 Hours | Yes             | Yes       | CUSTOMER SERVICE ONLY | Yes   | Free       |                            | No          | No      | No               |            |        | No           | Yes           | CORPORATE QUESTION; UNABLE TO ANSWER | No                                                        | JASON NORRIS  | No                | Yes             |                          |                           |                     |                  | RR_Not24hr    | 
| 0           | 52       | I-380 Exit-22, ID-1      | KWIK SHOP                 | Gasoline Stations with Convenience Stores | 380               | 22          | Urban Area | 2904 Center Point Rd NE                     | Cedar Rapids   | Iowa  | 52404    | 319-365-5587 | Yes      | Yes      |                                | Yes        | Only cars  | Unknown       | Yes        | 15         | 0            | 2            | N/A               | N/A             | Summer            | Friday Night      | 6pm - 12am         | Summer          | Yes              | Yes [more below] |                       |                    |                    | Yes - 24 Hours     | No              | Yes       |                       | No    |            |                            | No          | No      | No               | No         |        | No           | Yes           |                                      |                                                           | No            | No                | No              |                          |                           |                     |                  | 24hr_RR       | 
| 0           | 53       | I-380 Exit-22, ID-2      | CASEY'S GENERAL STORE     | Gasoline Stations with Convenience Stores | 380               | 22          | Urban Area | 1661 32nd St. NE                            | Cedar Rapids   | Iowa  | 52402    | 319-862-0397 | Yes      | Yes      |                                | Yes        | Only cars  | Unknown       | Yes        | 16         | 0            | 2            |                   |                 |                   | Monday & Thursday | Morning until Noon | Summer          | Yes              | Yes [more below] |                       |                    |                    | Yes - 24 Hours     | No              | Yes       |                       | No    |            |                            | No          | No      | No               | N/A        |        | No           | Yes           |                                      |                                                           | No            | No                | No              |                          |                           |                     |                  | 24hr_RR       | 
```