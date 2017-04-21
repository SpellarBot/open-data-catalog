# Airport Quarterly Passenger Survey

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/airport-quarterly-passenger-survey) |
| Metadata | [Link](https://data.austintexas.gov/api/views/dvu8-ztdx) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/dvu8-ztdx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/dvu8-ztdx/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | dvu8-ztdx |
| Name | Airport Quarterly Passenger Survey |
| Attribution | Austin Bergstrom International Airport |
| Tags | airport, customer, survey, passenger |
| Created | 2015-07-06T17:42:08Z |
| Publication Date | 2016-12-07T15:28:47Z |

## Description

Results from Austin-Bergstrom International Airport's customer surveys.  Surveys are tallied and reported quarterly to help ABIA improve general customer satisfaction as well as to target specific areas for improvement.

## Columns

```ls
| Included | Schema Type    | Field Name                                   | Name                                         | Data Type     | Render Type   |
| ======== | ============== | ============================================ | ============================================ | ============= | ============= |
| No       |                | quarter                                      | Quarter                                      | text          | text          |
| Yes      | time           | date_recorded                                | Date recorded                                | calendar_date | calendar_date |
| No       |                | departure_time                               | Departure time                               | text          | text          |
| Yes      | numeric metric | ground_transportation_to_from_airport        | Ground transportation to/from airport        | number        | number        |
| Yes      | numeric metric | parking_facilities                           | Parking facilities                           | number        | number        |
| Yes      | numeric metric | parking_facilities_value_for_money           | Parking facilities (value for money)         | number        | number        |
| Yes      | numeric metric | availability_of_baggage_carts                | Availability of baggage carts                | number        | number        |
| Yes      | numeric metric | efficiency_of_check_in_staff                 | Efficiency of check-in staff                 | number        | number        |
| No       |                | checkiin_wait_time                           | Check-in wait time                           | number        | number        |
| Yes      | numeric metric | courtesy_of_of_check_in_staff                | Courtesy of of check-in staff                | number        | number        |
| Yes      | numeric metric | wait_time_at_passport_inspection             | Wait time at passport inspection             | number        | number        |
| Yes      | numeric metric | courtesy_of_inspection_staff                 | Courtesy of inspection staff                 | number        | number        |
| Yes      | numeric metric | courtesy_of_security_staff                   | Courtesy of security staff                   | number        | number        |
| Yes      | numeric metric | thoroughness_of_security_inspection          | Thoroughness of security inspection          | number        | number        |
| Yes      | numeric metric | wait_time_of_security_inspection             | Wait time of security inspection             | number        | number        |
| Yes      | numeric metric | feeling_of_safety_and_security               | Feeling of safety and security               | number        | number        |
| Yes      | numeric metric | ease_of_finding_your_way_through_the_airport | Ease of finding your way through the airport | number        | number        |
| Yes      | numeric metric | flight_information_screens                   | Flight information screens                   | number        | number        |
| Yes      | numeric metric | walking_distance_inside_terminal             | Walking distance inside terminal             | number        | number        |
| Yes      | numeric metric | ease_of_making_connections                   | Ease of making connections                   | number        | number        |
| Yes      | numeric metric | courtesy_of_airport_staff                    | Courtesy of airport staff                    | number        | number        |
| Yes      | numeric metric | restaurants                                  | Restaurants                                  | number        | number        |
| Yes      | numeric metric | restaurants_value_for_money                  | Restaurants (value for money)                | number        | number        |
| Yes      | numeric metric | availability_of_banks_atm_money_changing     | Availability of banks/ATM/money changing     | number        | number        |
| Yes      | numeric metric | shopping_facilities                          | Shopping facilities                          | number        | number        |
| Yes      | numeric metric | shopping_facilities_value_for_money          | Shopping facilities (value for money)        | number        | number        |
| Yes      | numeric metric | internet_access                              | Internet access                              | number        | number        |
| Yes      | numeric metric | business_executive_lounges                   | Business/executive lounges                   | number        | number        |
| Yes      | numeric metric | availability_of_washrooms                    | Availability of washrooms                    | number        | number        |
| Yes      | numeric metric | cleanliness_of_washrooms                     | Cleanliness of washrooms                     | number        | number        |
| Yes      | numeric metric | comfort_of_waiting_gate_areas                | Comfort of waiting/gate areas                | number        | number        |
| Yes      | numeric metric | cleanliness_of_airport_terminal              | Cleanliness of airport terminal              | number        | number        |
| Yes      | numeric metric | ambience_of_airport                          | Ambience of airport                          | number        | number        |
| Yes      | numeric metric | arrivals_passport_and_visa_inspection        | Arrivals passport and visa inspection        | number        | number        |
| Yes      | numeric metric | speed_of_baggage_delivery                    | Speed of baggage delivery                    | number        | number        |
| Yes      | numeric metric | customs_inspection                           | Customs inspection                           | number        | number        |
| Yes      | numeric metric | overall_satisfaction                         | Overall satisfaction                         | number        | number        |
```

## Time Field

```ls
Value = date_recorded
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = departure_time,checkiin_wait_time,quarter
```

## Data Commands

```ls
series e:dvu8-ztdx d:2015-02-05T00:00:00.000Z m:availability_of_baggage_carts=5 m:availability_of_washrooms=5 m:ease_of_making_connections=0 m:parking_facilities=0 m:arrivals_passport_and_visa_inspection=0 m:feeling_of_safety_and_security=5 m:internet_access=0 m:walking_distance_inside_terminal=5 m:restaurants_value_for_money=0 m:ground_transportation_to_from_airport=5 m:wait_time_at_passport_inspection=5 m:flight_information_screens=5 m:parking_facilities_value_for_money=0 m:business_executive_lounges=0 m:ease_of_finding_your_way_through_the_airport=5 m:speed_of_baggage_delivery=1 m:wait_time_of_security_inspection=5 m:overall_satisfaction=5 m:shopping_facilities_value_for_money=0 m:shopping_facilities=0 m:availability_of_banks_atm_money_changing=0 m:efficiency_of_check_in_staff=3 m:restaurants=0 m:courtesy_of_airport_staff=0 m:cleanliness_of_airport_terminal=5 m:ambience_of_airport=5 m:comfort_of_waiting_gate_areas=5 m:courtesy_of_of_check_in_staff=5 m:thoroughness_of_security_inspection=5 m:cleanliness_of_washrooms=5 m:courtesy_of_security_staff=5 m:customs_inspection=0 m:courtesy_of_inspection_staff=5

series e:dvu8-ztdx d:2015-02-05T00:00:00.000Z m:availability_of_baggage_carts=0 m:availability_of_washrooms=5 m:ease_of_making_connections=5 m:parking_facilities=0 m:arrivals_passport_and_visa_inspection=0 m:feeling_of_safety_and_security=5 m:internet_access=5 m:walking_distance_inside_terminal=5 m:restaurants_value_for_money=5 m:ground_transportation_to_from_airport=4 m:wait_time_at_passport_inspection=5 m:flight_information_screens=5 m:parking_facilities_value_for_money=0 m:business_executive_lounges=0 m:ease_of_finding_your_way_through_the_airport=5 m:speed_of_baggage_delivery=0 m:wait_time_of_security_inspection=5 m:overall_satisfaction=5 m:shopping_facilities_value_for_money=0 m:shopping_facilities=0 m:availability_of_banks_atm_money_changing=0 m:efficiency_of_check_in_staff=0 m:restaurants=5 m:courtesy_of_airport_staff=5 m:cleanliness_of_airport_terminal=5 m:ambience_of_airport=5 m:comfort_of_waiting_gate_areas=4 m:courtesy_of_of_check_in_staff=0 m:thoroughness_of_security_inspection=5 m:cleanliness_of_washrooms=5 m:courtesy_of_security_staff=5 m:customs_inspection=0 m:courtesy_of_inspection_staff=5

series e:dvu8-ztdx d:2015-02-05T00:00:00.000Z m:availability_of_baggage_carts=0 m:availability_of_washrooms=4 m:ease_of_making_connections=5 m:parking_facilities=4 m:arrivals_passport_and_visa_inspection=0 m:feeling_of_safety_and_security=4 m:internet_access=0 m:walking_distance_inside_terminal=4 m:restaurants_value_for_money=3 m:ground_transportation_to_from_airport=4 m:wait_time_at_passport_inspection=5 m:flight_information_screens=5 m:parking_facilities_value_for_money=5 m:business_executive_lounges=0 m:ease_of_finding_your_way_through_the_airport=5 m:speed_of_baggage_delivery=4 m:wait_time_of_security_inspection=5 m:overall_satisfaction=5 m:shopping_facilities_value_for_money=0 m:shopping_facilities=0 m:availability_of_banks_atm_money_changing=0 m:efficiency_of_check_in_staff=5 m:restaurants=4 m:courtesy_of_airport_staff=4 m:cleanliness_of_airport_terminal=5 m:ambience_of_airport=4 m:comfort_of_waiting_gate_areas=4 m:courtesy_of_of_check_in_staff=0 m:thoroughness_of_security_inspection=4 m:cleanliness_of_washrooms=4 m:courtesy_of_security_staff=4 m:customs_inspection=0 m:courtesy_of_inspection_staff=4
```

## Meta Commands

```ls
metric m:ground_transportation_to_from_airport p:integer l:"Ground transportation to/from airport" t:dataTypeName=number

metric m:parking_facilities p:integer l:"Parking facilities" t:dataTypeName=number

metric m:parking_facilities_value_for_money p:integer l:"Parking facilities (value for money)" t:dataTypeName=number

metric m:availability_of_baggage_carts p:integer l:"Availability of baggage carts" t:dataTypeName=number

metric m:efficiency_of_check_in_staff p:integer l:"Efficiency of check-in staff" t:dataTypeName=number

metric m:courtesy_of_of_check_in_staff p:integer l:"Courtesy of of check-in staff" t:dataTypeName=number

metric m:wait_time_at_passport_inspection p:integer l:"Wait time at passport inspection" t:dataTypeName=number

metric m:courtesy_of_inspection_staff p:integer l:"Courtesy of inspection staff" t:dataTypeName=number

metric m:courtesy_of_security_staff p:integer l:"Courtesy of security staff" t:dataTypeName=number

metric m:thoroughness_of_security_inspection p:integer l:"Thoroughness of security inspection" t:dataTypeName=number

metric m:wait_time_of_security_inspection p:integer l:"Wait time of security inspection" t:dataTypeName=number

metric m:feeling_of_safety_and_security p:integer l:"Feeling of safety and security" t:dataTypeName=number

metric m:ease_of_finding_your_way_through_the_airport p:integer l:"Ease of finding your way through the airport" t:dataTypeName=number

metric m:flight_information_screens p:integer l:"Flight information screens" t:dataTypeName=number

metric m:walking_distance_inside_terminal p:integer l:"Walking distance inside terminal" t:dataTypeName=number

metric m:ease_of_making_connections p:integer l:"Ease of making connections" t:dataTypeName=number

metric m:courtesy_of_airport_staff p:integer l:"Courtesy of airport staff" t:dataTypeName=number

metric m:restaurants p:integer l:Restaurants t:dataTypeName=number

metric m:restaurants_value_for_money p:integer l:"Restaurants (value for money)" t:dataTypeName=number

metric m:availability_of_banks_atm_money_changing p:integer l:"Availability of banks/ATM/money changing" t:dataTypeName=number

metric m:shopping_facilities p:integer l:"Shopping facilities" t:dataTypeName=number

metric m:shopping_facilities_value_for_money p:integer l:"Shopping facilities (value for money)" t:dataTypeName=number

metric m:internet_access p:integer l:"Internet access" t:dataTypeName=number

metric m:business_executive_lounges p:integer l:"Business/executive lounges" t:dataTypeName=number

metric m:availability_of_washrooms p:integer l:"Availability of washrooms" t:dataTypeName=number

metric m:cleanliness_of_washrooms p:integer l:"Cleanliness of washrooms" t:dataTypeName=number

metric m:comfort_of_waiting_gate_areas p:integer l:"Comfort of waiting/gate areas" t:dataTypeName=number

metric m:cleanliness_of_airport_terminal p:integer l:"Cleanliness of airport terminal" t:dataTypeName=number

metric m:ambience_of_airport p:integer l:"Ambience of airport" t:dataTypeName=number

metric m:arrivals_passport_and_visa_inspection p:integer l:"Arrivals passport and visa inspection" t:dataTypeName=number

metric m:speed_of_baggage_delivery p:integer l:"Speed of baggage delivery" t:dataTypeName=number

metric m:customs_inspection p:integer l:"Customs inspection" t:dataTypeName=number

metric m:overall_satisfaction p:integer l:"Overall satisfaction" t:dataTypeName=number

entity e:dvu8-ztdx l:"Airport Quarterly Passenger Survey" t:attribution="Austin Bergstrom International Airport" t:url=https://data.austintexas.gov/api/views/dvu8-ztdx

property e:dvu8-ztdx t:meta.view v:id=dvu8-ztdx v:averageRating=0 v:name="Airport Quarterly Passenger Survey" v:attribution="Austin Bergstrom International Airport"

property e:dvu8-ztdx t:meta.view.license v:name="Public Domain"

property e:dvu8-ztdx t:meta.view.owner v:id=ra8t-tbn2 v:screenName=Holly v:displayName=Holly

property e:dvu8-ztdx t:meta.view.tableauthor v:id=ra8t-tbn2 v:screenName=Holly v:roleName=editor v:displayName=Holly
```

## Top Records

```ls
| quarter | date_recorded       | departure_time | ground_transportation_to_from_airport | parking_facilities | parking_facilities_value_for_money | availability_of_baggage_carts | efficiency_of_check_in_staff | checkiin_wait_time | courtesy_of_of_check_in_staff | wait_time_at_passport_inspection | courtesy_of_inspection_staff | courtesy_of_security_staff | thoroughness_of_security_inspection | wait_time_of_security_inspection | feeling_of_safety_and_security | ease_of_finding_your_way_through_the_airport | flight_information_screens | walking_distance_inside_terminal | ease_of_making_connections | courtesy_of_airport_staff | restaurants | restaurants_value_for_money | availability_of_banks_atm_money_changing | shopping_facilities | shopping_facilities_value_for_money | internet_access | business_executive_lounges | availability_of_washrooms | cleanliness_of_washrooms | comfort_of_waiting_gate_areas | cleanliness_of_airport_terminal | ambience_of_airport | arrivals_passport_and_visa_inspection | speed_of_baggage_delivery | customs_inspection | overall_satisfaction | 
| ======= | =================== | ============== | ===================================== | ================== | ================================== | ============================= | ============================ | ================== | ============================= | ================================ | ============================ | ========================== | =================================== | ================================ | ============================== | ============================================ | ========================== | ================================ | ========================== | ========================= | =========== | =========================== | ======================================== | =================== | =================================== | =============== | ========================== | ========================= | ======================== | ============================= | =============================== | =================== | ===================================== | ========================= | ================== | ==================== | 
| 1Q15    | 2015-02-05T00:00:00 | 14:26          | 5                                     | 0                  | 0                                  | 5                             | 3                            | 5                  | 5                             | 5                                | 5                            | 5                          | 5                                   | 5                                | 5                              | 5                                            | 5                          | 5                                | 0                          | 0                         | 0           | 0                           | 0                                        | 0                   | 0                                   | 0               | 0                          | 5                         | 5                        | 5                             | 5                               | 5                   | 0                                     | 1                         | 0                  | 5                    | 
| 1Q15    | 2015-02-05T00:00:00 | 14:26          | 4                                     | 0                  | 0                                  | 0                             | 0                            | 0                  | 0                             | 5                                | 5                            | 5                          | 5                                   | 5                                | 5                              | 5                                            | 5                          | 5                                | 5                          | 5                         | 5           | 5                           | 0                                        | 0                   | 0                                   | 5               | 0                          | 5                         | 5                        | 4                             | 5                               | 5                   | 0                                     | 0                         | 0                  | 5                    | 
| 1Q15    | 2015-02-05T00:00:00 | 14:26          | 4                                     | 4                  | 5                                  | 0                             | 5                            | 0                  | 0                             | 5                                | 4                            | 4                          | 4                                   | 5                                | 4                              | 5                                            | 5                          | 4                                | 5                          | 4                         | 4           | 3                           | 0                                        | 0                   | 0                                   | 0               | 0                          | 4                         | 4                        | 4                             | 5                               | 4                   | 0                                     | 4                         | 0                  | 5                    | 
| 1Q15    | 2015-02-05T00:00:00 | 14:26          | 0                                     | 0                  | 0                                  | 0                             | 4                            | 4                  | 4                             | 0                                | 0                            | 3                          | 4                                   | 4                                | 4                              | 5                                            | 5                          | 5                                | 5                          | 0                         | 4           | 4                           | 0                                        | 0                   | 0                                   | 4               | 0                          | 4                         |                          | 3                             | 3                               | 2                   | 0                                     | 5                         | 0                  | 4                    | 
| 1Q15    | 2015-02-05T00:00:00 | 14:26          | 4                                     | 4                  | 3                                  | 0                             | 4                            | 4                  | 4                             | 0                                | 0                            | 5                          | 4                                   | 4                                | 4                              | 5                                            | 5                          | 5                                | 5                          | 5                         | 5           | 5                           | 0                                        | 0                   | 0                                   | 0               | 0                          | 5                         | 5                        | 5                             | 5                               | 5                   | 0                                     | 4                         | 0                  | 5                    | 
| 1Q15    | 2015-02-05T00:00:00 | 14:26          | 4                                     | 4                  | 4                                  |                               | 4                            | 4                  | 4                             | 4                                | 4                            | 4                          | 4                                   | 4                                | 4                              | 5                                            | 5                          | 5                                | 0                          | 4                         | 0           | 0                           | 0                                        | 4                   | 3                                   | 0               | 0                          | 5                         | 5                        | 4                             | 5                               | 5                   | 0                                     | 5                         | 0                  | 5                    | 
| 1Q15    | 2015-02-05T00:00:00 | 14:26          | 5                                     | 0                  | 0                                  | 0                             | 5                            | 5                  | 5                             | 5                                | 5                            | 0                          | 5                                   | 5                                | 5                              | 5                                            | 5                          | 5                                | 0                          | 0                         | 0           | 5                           | 0                                        | 5                   | 5                                   | 0               | 0                          | 5                         | 5                        | 5                             | 5                               | 5                   | 0                                     | 5                         | 0                  | 5                    | 
| 1Q15    | 2015-02-05T00:00:00 | 14:26          | 4                                     | 3                  | 3                                  | 0                             | 4                            | 4                  | 4                             | 4                                | 4                            | 5                          | 2                                   | 5                                | 3                              | 0                                            | 0                          | 0                                | 0                          | 5                         | 0           | 0                           | 0                                        | 0                   | 0                                   | 0               | 0                          | 0                         | 5                        | 5                             | 0                               | 4                   | 0                                     | 0                         | 0                  | 4                    | 
| 1Q15    | 2015-02-05T00:00:00 | 14:26          | 0                                     | 0                  | 0                                  | 0                             | 3                            | 3                  | 4                             | 4                                | 5                            | 5                          | 5                                   | 5                                | 5                              | 5                                            | 0                          | 5                                | 0                          | 5                         | 5           | 5                           | 0                                        | 4                   | 3                                   | 5               | 0                          | 5                         | 5                        | 5                             | 5                               | 5                   |                                       |                           |                    | 5                    | 
| 1Q15    | 2015-02-05T00:00:00 | 14:26          | 0                                     | 0                  | 0                                  | 0                             | 5                            | 5                  | 5                             | 5                                | 5                            | 3                          | 3                                   | 3                                | 3                              | 5                                            | 5                          | 5                                | 0                          | 4                         | 4           | 4                           | 0                                        | 0                   | 0                                   | 0               |                            | 3                         | 3                        | 2                             | 3                               | 3                   | 0                                     | 2                         | 0                  | 3                    | 
```