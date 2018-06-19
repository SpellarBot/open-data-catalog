# Alternative Service Locations - 24-Hour Restroom & Truck Parking

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/alternative-service-locations-24-hour-restroom-truck-parking) |
| Metadata | [Link](https://data.iowa.gov/api/views/hp75-ap4n) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/hp75-ap4n/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/hp75-ap4n/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | hp75-ap4n |
| Name | Alternative Service Locations - 24-Hour Restroom & Truck Parking |
| Attribution | Iowa DOT, HDR Engineering |
| Category | Transportation & Utilities |
| Tags | asset, classification, rest, area, alternative, service, iowa dot, iowa department of transportation |
| Created | 2016-08-19T20:47:27Z |
| Publication Date | 2016-08-19T20:49:33Z |

## Description

Iowa Department of Transportation statewide rest area data. This layer displays alternative service locations that have 24-hour restrooms and truck parking.

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
series e:hp75-ap4n d:2016-08-19T20:47:27.000Z t:dot_tech_partner=N/A t:phone_number=5152761509 t:rv_dump=Yes t:hr_prkng_24=Yes t:parking_hours=N/A t:food_purchase=Yes t:car_trk_pernight=N/A t:city="Des Moines" t:exit_number=126 t:wi_fi=No t:car_holiday_wknd=No t:busy_season_car=Summer t:location_facility_id="I-35 & 80 Exit-126, ID-1" t:hours_operate=NA t:free_prkng=Yes t:pet_exercise=No t:place="PILOT TRAVEL CENTERS LLC" t:wi_fi_free="Not Free" t:busy_day_truck=Weekends t:elect_veh_charge=No t:wi_fi_price="$4.79 day" t:busy_season_truck=Winter t:category="Other Gasoline Stations" t:elect_free=N/A t:trck_full=Yes-Weekends t:hours_24=Yes t:travel_info=No t:objectid=14 t:cars_truck=Both t:picnic=No t:zip_code=50322 t:state=Iowa t:interstate_number="35 & 80" t:facility_id="I-35 & 80 Exit-126, ID-1" t:restrooms="Yes - 24 Hours" t:area_type="Urban Area" t:busy_day_car=Wednesdays t:accessible=Yes t:aslsummshort=24hr_RR_TP t:other_services="Restaurant/Food Service" t:truck_perc_group=75-99% t:busy_time_truck="Fri nights" t:surveyed=Yes t:family_restroom=No t:email_request=No t:tdd=Yes t:truck_parking=Yes t:busy_time_car=Noon t:name_request="Charles Sang" t:telephone=Yes m:approx_number_truck_space=75 m:handi_spaces=12 m:truck_spaces=75 m:truck_percent_utili=85 m:car_spaces=40

series e:hp75-ap4n d:2016-08-19T20:47:27.000Z t:dot_tech_partner=No t:phone_number=5152767437 t:rv_dump=No t:hr_prkng_24=No t:parking_hours="Only trucks--any time" t:food_purchase=Yes t:car_trk_pernight=200 t:city=Clive t:exit_number=125 t:wi_fi=No t:car_holiday_wknd=No t:busy_season_car=Summer t:location_facility_id="I-35 & 80 Exit-125, ID-2" t:hours_operate=NA t:free_prkng=Yes t:pet_exercise=Yes t:place="Love's Travel Stop" t:wi_fi_free="Not Free" t:busy_day_truck=Tuesday-Wednesday t:elect_veh_charge=No t:wi_fi_price="AT&T provides it--not sure" t:busy_season_truck=Summer t:category="Gas Station/Conveinece" t:elect_free=N/A t:trck_full="Yes--3 nights/week" t:hours_24=Yes t:travel_info=No t:objectid=17 t:cars_truck=Both t:picnic=No t:zip_code=50325 t:state=Iowa t:interstate_number="35 & 80" t:facility_id="I-35 & 80 Exit-125, ID-2" t:restrooms="Yes - 24 Hours" t:area_type="Urban Area" t:busy_day_car=Varies t:accessible=Yes t:aslsummshort=24hr_RR_TP t:other_services=No t:truck_perc_group=75-99% t:busy_time_truck=Varies t:surveyed=Yes t:family_restroom=Yes t:email_request=store411@love.com t:tdd=Yes t:truck_parking=Yes t:busy_time_car=Day t:name_request="? Long" t:telephone=Yes m:approx_number_truck_space=250 m:handi_spaces=6 m:truck_spaces=250 m:truck_percent_utili=90 m:car_spaces=130

series e:hp75-ap4n d:2016-08-19T20:47:27.000Z t:dot_tech_partner="No/Corporate question" t:phone_number=815-315-0271 t:zip_code=50707 t:hr_prkng_24="Yes [more below]" t:rv_dump=No t:state=Iowa t:interstate_number=380 t:facility_id="I-380 Exit-68, ID-2" t:food_purchase=Yes t:restrooms="Yes - 24 Hours" t:city="Elk Run Heights" t:car_trk_pernight="10 cars, 100 trucks" t:area_type="Urban Area" t:exit_number=68 t:wi_fi=Yes t:busy_season_car=Summer t:car_holiday_wknd=Yes t:busy_day_car=Friday t:location_facility_id="I-380 Exit-68, ID-2" t:accessible=Yes t:pet_exercise=No t:free_prkng=Yes t:aslsummshort=24hr_RR_TP t:place="ROAD RANGER" t:other_services=Restaurants t:wi_fi_free="Not Free" t:truck_perc_group=75-99% t:busy_time_truck="after 5pm" t:busy_day_truck=Tues-Thurs t:surveyed=Yes t:elect_veh_charge=No t:email_request=No t:family_restroom=Yes t:wi_fi_price=$4.99/day t:busy_season_truck=Summer t:truck_parking=Yes t:elect_free=N/A t:category="Gasoline Stations with Convenience Stores" t:busy_time_car="after 2pm" t:trck_full="Yes, often" t:hours_24=Yes t:travel_info=No t:name_request="Brenda Hanson" t:cars_truck=Both t:objectid=38 t:telephone=No t:future_question=Yes m:approx_number_truck_space=200 m:handi_spaces=4 m:truck_spaces=200 m:truck_percent_utili=85 m:car_spaces=20
```

## Meta Commands

```ls
metric m:handi_spaces p:integer l:Handi_Spaces d:"Handicap Parking Spaces" t:dataTypeName=number

metric m:approx_number_truck_space p:integer l:Approx_Number_Truck_Space d:"Appoximate Number of Truck Spaces" t:dataTypeName=number

metric m:truck_percent_utili p:integer l:Truck_Percent_Utili d:"Truck Utilization Percent" t:dataTypeName=number

entity e:hp75-ap4n l:"Alternative Service Locations - 24-Hour Restroom & Truck Parking" t:attribution="Iowa DOT, HDR Engineering" t:url=https://data.iowa.gov/api/views/hp75-ap4n

property e:hp75-ap4n t:meta.view v:id=hp75-ap4n v:category="Transportation & Utilities" v:averageRating=0 v:name="Alternative Service Locations - 24-Hour Restroom & Truck Parking" v:attribution="Iowa DOT, HDR Engineering"

property e:hp75-ap4n t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:hp75-ap4n t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```

## Top Records

```ls
| :updated_at | objectid | facility_id              | place                       | category                                  | interstate_number | exit_number | area_type  | address                                     | city            | state | zip_code | phone_number | surveyed | hours_24 | hours_operate | accessible | cars_truck | truck_parking | free_prkng | car_spaces | truck_spaces | handi_spaces | busy_day_truck    | busy_time_truck      | busy_season_truck | busy_day_car | busy_time_car      | busy_season_car | car_holiday_wknd | hr_prkng_24      | parking_hours         | car_trk_pernight               | trck_full            | restrooms      | family_restroom | telephone | tdd | wi_fi | wi_fi_free | wi_fi_price                | travel_info | rv_dump | elect_veh_charge | elect_free | picnic | pet_exercise | food_purchase | dot_tech_partner                                 | other_services                                        | name_request  | email_request     | future_question | location_facility_id     | approx_number_truck_space | truck_percent_utili | truck_perc_group | aslsummshort | 
| =========== | ======== | ======================== | =========================== | ========================================= | ================= | =========== | ========== | =========================================== | =============== | ===== | ======== | ============ | ======== | ======== | ============= | ========== | ========== | ============= | ========== | ========== | ============ | ============ | ================= | ==================== | ================= | ============ | ================== | =============== | ================ | ================ | ===================== | ============================== | ==================== | ============== | =============== | ========= | === | ===== | ========== | ========================== | =========== | ======= | ================ | ========== | ====== | ============ | ============= | ================================================ | ===================================================== | ============= | ================= | =============== | ======================== | ========================= | =================== | ================ | ============ | 
| 0           | 14       | I-35 & 80 Exit-126, ID-1 | PILOT TRAVEL CENTERS LLC    | Other Gasoline Stations                   | 35 & 80           | 126         | Urban Area | 11957 Douglas Avenue, Des Moines, IA, 50322 | Des Moines      | Iowa  | 50322    | 5152761509   | Yes      | Yes      | NA            | Yes        | Both       | Yes           | Yes        | 40         | 75           | 12           | Weekends          | Fri nights           | Winter            | Wednesdays   | Noon               | Summer          | No               | Yes              | N/A                   | N/A                            | Yes-Weekends         | Yes - 24 Hours | No              | Yes       | Yes | No    | Not Free   | $4.79 day                  | No          | Yes     | No               | N/A        | No     | No           | Yes           | N/A                                              | Restaurant/Food Service                               | Charles Sang  | No                |                 | I-35 & 80 Exit-126, ID-1 | 75                        | 85                  | 75-99%           | 24hr_RR_TP   | 
| 0           | 17       | I-35 & 80 Exit-125, ID-2 | Love's Travel Stop          | Gas Station/Conveinece                    | 35 & 80           | 125         | Urban Area | 11820 Hickman Road, Clive, IA 50325         | Clive           | Iowa  | 50325    | 5152767437   | Yes      | Yes      | NA            | Yes        | Both       | Yes           | Yes        | 130        | 250          | 6            | Tuesday-Wednesday | Varies               | Summer            | Varies       | Day                | Summer          | No               | No               | Only trucks--any time | 200                            | Yes--3 nights/week   | Yes - 24 Hours | Yes             | Yes       | Yes | No    | Not Free   | AT&T provides it--not sure | No          | No      | No               | N/A        | No     | Yes          | Yes           | No                                               | No                                                    | ? Long        | store411@love.com |                 | I-35 & 80 Exit-125, ID-2 | 250                       | 90                  | 75-99%           | 24hr_RR_TP   | 
| 0           | 38       | I-380 Exit-68, ID-2      | ROAD RANGER                 | Gasoline Stations with Convenience Stores | 380               | 68          | Urban Area | 100 Plaza Dr                                | Elk Run Heights | Iowa  | 50707    | 815-315-0271 | Yes      | Yes      |               | Yes        | Both       | Yes           | Yes        | 20         | 200          | 4            | Tues-Thurs        | after 5pm            | Summer            | Friday       | after 2pm          | Summer          | Yes              | Yes [more below] |                       | 10 cars, 100 trucks            | Yes, often           | Yes - 24 Hours | Yes             | No        |     | Yes   | Not Free   | $4.99/day                  | No          | No      | No               | N/A        |        | No           | Yes           | No/Corporate question                            | Restaurants                                           | Brenda Hanson | No                | Yes             | I-380 Exit-68, ID-2      | 200                       | 85                  | 75-99%           | 24hr_RR_TP   | 
| 0           | 70       | I-80 Exit-292, ID-1      | MOTHER HUBBARDS CUPBOARD/BP | Gasoline Stations with Convenience Stores | 80                | 292         | Urban Area | 7522 Northwest Blvd                         | Davenport       | Iowa  | 52806    | 563-386-8086 | Yes      | Yes      |               | Yes        | Both       | Yes           | Yes        | 15         | 5            | 2            | VARIES            | EVENING              | Summer            | VARIES       | ALL DAY            | Summer          | Yes              | Yes [more below] |                       |                                | No                   | Yes - 24 Hours | No              | No        |     | No    |            |                            | No          | No      | No               |            |        | No           | Yes           | CANT ANSWER THIS QUESTION; HAVE TO ASK CORPORATE | MCDONALD'S INSIDE THE GAS STATION; THEY PROVIDE WI-FI | No            | No                | No              |                          |                           |                     |                  | 24hr_RR_TP   | 
| 0           | 83       | I-80 Exit-254, ID-2      | KUM & GO                    | Gasoline Stations with Convenience Stores | 80                | 254         | Urban Area | 620 S Downey St                             | West Branch     | Iowa  | 52358    | 319-643-5050 | Yes      | Yes      |               | Yes        | Both       | Yes           | Yes        | 10         | 10           | 1            | Thursday-Saturday | All day              | Summer            | Weekend      | Morning            | Summer          | Yes              | No [more below]  | 1 hour maximum        |                                |                      | Yes - 24 Hours | No              | No        |     | No    |            |                            | No          | No      | No               | N/A        |        | No           | Yes           | No/Corporate question                            |                                                       | Matt Keith    | No                | Yes             |                          |                           |                     |                  | 24hr_RR_TP   | 
| 0           | 104      | I-80 Exit-201, ID-1      | KWIK TRIP/KWIK STAR         | Gasoline Stations with Convenience Stores | 80                | 201         | Rural Area | 4177 Highway 21                             | Brooklyn        | Iowa  | 52211    | 319-685-4411 | Yes      | Yes      |               | Yes        | Both       | Yes           | Yes        | 30         | 200          | 5            | Steady            | Depends on day       |                   | ?            | ?                  |                 | No               | Yes [more below] |                       | ?                              | No                   | Yes - 24 Hours | No              | Yes       | No  | Yes   | Free       |                            | No          | No      | No               | N/A        |        | Yes          | Yes           | No/Corporate question                            | Showers                                               | Megan Vajgrt  | No                | Yes             | I-80 Exit-201, ID-1      | 200                       | 80                  | 75-99%           | 24hr_RR_TP   | 
| 0           | 110      | I-80 Exit-168, ID-1      | LOVES TRAVEL CENTER         | Gasoline Stations with Convenience Stores | 80                | 168         | Urban Area | 4400 S 22nd Ave E                           | Newton          | Iowa  | 50208    | 641-791-2410 | Yes      | Yes      |               | Yes        | Both       | Yes           | Yes        | 80         | 100          | 8            | Thursday          | 09/19/2012           | Summer            | All the same | 09/19/2012         | Summer          | Yes              | Yes [more below] |                       | 10 cars (2hr limit), 85 trucks | Yes, not often       | Yes - 24 Hours | Yes             | Yes       | No  | Yes   | Not Free   | Unsure                     | No          | Yes     | No               | N/A        |        | Yes          | Yes           | No/Corporate question                            |                                                       | Jamie Black   | No                | Yes             | I-80 Exit-168, ID-1      | 100                       | 90                  | 75-99%           | 24hr_RR_TP   | 
| 0           | 124      | I-80 Exit-110, ID-1      | KUM & GO                    | Gasoline Stations with Convenience Stores | 80                | 110         | Urban Area | 1203 Guthrie St, De Soto, IA, 50069         | De Soto         | Iowa  | 50069    | 515-834-2500 | Yes      | Yes      | NA            | Yes        | Both       | Yes           | Yes        | 23         | 3            | 2            | N/A               | N/A                  | Winter            | N/A          | N/A                | N/A             | Yes              | Yes              | N/A                   | N/A                            | Yes-few times a week | Yes - 24 Hours | No              | No        | No  | No    | N/A        | N/A                        | No          | No      | N/A              | N/A        | No     | No           | Yes           | N/A                                              | N/A                                                   | N/A           | N/A               |                 |                          |                           |                     |                  | 24hr_RR_TP   | 
| 0           | 137      | I-80 Exit-46, ID-2       | ANTIQUE CITY BP             | Gasoline Stations with Convenience Stores | 80                | 46          | Urban Area | 2101 Antique City Dr                        | Walnut          | Iowa  | 51577    | 712-784-3993 | Yes      | Yes      |               | Yes        | Both       | Yes           | Yes        | 20         | 20           | 2            | FRIDAY            | EVENING              | Summer            | WEEKENDS     | OVER LUNCH/EVENING | Summer          | Yes              | Yes [more below] |                       |                                | YES, OFTEN           | Yes - 24 Hours | No              | No        |     | Yes   | Free       |                            | No          | No      | No               |            |        | Yes          | Yes           | Yes                                              | No                                                    | PETRA SANDERS | No                | Yes             |                          |                           |                     |                  | 24hr_RR_TP   | 
| 0           | 176      | I-35 Exit-90, ID-5       | Walmart                     | Convenience Store                         | 35                | 90          | Urban Area | 10002 SE National Drive, Ankeny, IA, 50021  | Ankeny          | Iowa  | 50021    | 5159631111   | Yes      | Yes      | NA            | Yes        | Both       | Yes           | Yes        |            |              | 25           | Varies--Friday    | overnight 11:00-8:00 | N/A               | Saturday     | 11:00-6:00         | Any Holiday     | Yes              | Yes              | No                    | N/A                            | N/A                  | Yes - 24 Hours | No              | Yes       | Yes | No    | N/A        | N/A                        | No          | No      | No               | N/A        | No     | No           | Yes           | Home Office                                      | N/A                                                   | Kat Sayehuren | No                |                 |                          |                           |                     |                  | 24hr_RR_TP   | 
```