# Police Measurables

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/police-measurables) |
| Metadata | [Link](https://data.srcity.org/api/views/hjz8-wskg) |
| Data: JSON | [100 Rows](https://data.srcity.org/api/views/hjz8-wskg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.srcity.org/api/views/hjz8-wskg/rows.csv?max_rows=100) |
| Host | data.srcity.org |
| Id | hjz8-wskg |
| Name | Police Measurables |
| Category | Police |
| Created | 2017-02-01T20:38:30Z |
| Publication Date | 2017-03-14T20:27:45Z |

## Columns

```ls
| Included | Schema Type    | Field Name                                           | Name                                                       | Data Type     | Render Type   |
| ======== | ============== | ==================================================== | ========================================================== | ============= | ============= |
| Yes      | time           | year_month                                           | Year-Month                                                 | calendar_date | calendar_date |
| Yes      | numeric metric | ucr_part_i_crimes_violent_crime                      | UCR PART I CRIMES - VIOLENT CRIME                          | number        | number        |
| Yes      | numeric metric | criminal_homicide                                    | Criminal Homicide                                          | number        | number        |
| Yes      | numeric metric | forcible_rape                                        | Forcible Rape                                              | number        | number        |
| Yes      | numeric metric | robbery                                              | Robbery                                                    | number        | number        |
| Yes      | numeric metric | aggravated_assault                                   | Aggravated Assault                                         | number        | number        |
| Yes      | numeric metric | ucr_part_i_crimes_property_crime_monthly_total       | UCR PART I CRIMES - PROPERTY CRIME (MONTHLY TOTAL)         | number        | number        |
| Yes      | numeric metric | burglary                                             | Burglary                                                   | number        | number        |
| Yes      | numeric metric | larceny_theft                                        | Larceny Theft                                              | number        | number        |
| Yes      | numeric metric | motor_vehicle_theft                                  | Motor Vehicle Theft                                        | number        | number        |
| Yes      | numeric metric | arson                                                | Arson                                                      | number        | number        |
| Yes      | numeric metric | ucr_part_i_crimes_monthly_total                      | UCR PART I CRIMES - (MONTHLY TOTAL)                        | number        | number        |
| Yes      | numeric metric | traffic_collisions                                   | TRAFFIC COLLISIONS                                         | number        | number        |
| Yes      | numeric metric | involving_injuries                                   | involving Injuries                                         | number        | number        |
| Yes      | numeric metric | involving_fatal_injuries                             | involving Fatal Injuries                                   | number        | number        |
| Yes      | numeric metric | involving_hit_run                                    | involving Hit & Run                                        | number        | number        |
| Yes      | numeric metric | involving_dui_alcohol                                | involving DUI/Alcohol                                      | number        | number        |
| Yes      | numeric metric | involving_dui_drugs_includes_drugs_alcohol_combo     | involving DUI/Drugs (includes Drugs/Alcohol combo)         | number        | number        |
| Yes      | numeric metric | involving_property_damage                            | involving Property Damage                                  | number        | number        |
| Yes      | numeric metric | arrests_dui                                          | ARRESTS - DUI                                              | number        | number        |
| Yes      | numeric metric | citations_total                                      | CITATIONS - TOTAL                                          | number        | number        |
| Yes      | numeric metric | fix_it_citation                                      | FIX-IT CITATION                                            | number        | number        |
| Yes      | numeric metric | moving_violation                                     | MOVING VIOLATION                                           | number        | number        |
| Yes      | numeric metric | parking_violation                                    | PARKING VIOLATION                                          | number        | number        |
| Yes      | numeric metric | registration_violation                               | REGISTRATION VIOLATION                                     | number        | number        |
| Yes      | numeric metric | municode_violation                                   | MUNICODE VIOLATION                                         | number        | number        |
| Yes      | numeric metric | criminal_citation                                    | CRIMINAL CITATION                                          | number        | number        |
| Yes      | numeric metric | warning_citation                                     | WARNING CITATION                                           | number        | number        |
| Yes      | numeric metric | license_violation                                    | LICENSE VIOLATION                                          | number        | number        |
| Yes      | numeric metric | non_moving_violation                                 | NON-MOVING VIOLATION                                       | number        | number        |
| Yes      | numeric metric | calls_for_service_total                              | CALLS FOR SERVICE - TOTAL                                  | number        | number        |
| Yes      | numeric metric | calls_officer_initiated_1                            | CALLS - OFFICER INITIATED                                  | number        | number        |
| Yes      | numeric metric | calls_other                                          | CALLS - OTHER                                              | number        | number        |
| Yes      | numeric metric | calls_officer_initiated_2                            | CALLS - % OFFICER INITIATED                                | percent       | percent       |
| Yes      | numeric metric | calls_average_time_on_call_minutes_officer_initiated | CALLS - AVERAGE TIME ON CALL (MINUTES) - OFFICER INITIATED | number        | number        |
| Yes      | numeric metric | calls_average_time_on_call_minutes_all               | CALLS - AVERAGE TIME ON CALL (MINUTES) - ALL               | number        | number        |
| Yes      | numeric metric | 911_calls                                            | 911 CALLS                                                  | number        | number        |
| Yes      | numeric metric | other_incoming_calls                                 | OTHER INCOMING CALLS                                       | number        | number        |
| Yes      | numeric metric | outbound_calls                                       | OUTBOUND CALLS                                             | number        | number        |
| Yes      | numeric metric | call_center_calls_total                              | CALL CENTER CALLS - TOTAL                                  | number        | number        |
| Yes      | numeric metric | priority_1_calls                                     | PRIORITY 1 CALLS                                           | number        | number        |
| Yes      | numeric metric | priority_2_calls                                     | PRIORITY 2 CALLS                                           | number        | number        |
| Yes      | numeric metric | priority_3_calls                                     | PRIORITY 3 CALLS                                           | number        | number        |
| Yes      | numeric metric | response_priority_1                                  | RESPONSE PRIORITY 1                                        | number        | number        |
| Yes      | numeric metric | response_priority_2                                  | RESPONSE PRIORITY 2                                        | number        | number        |
| Yes      | numeric metric | response_priority_3                                  | RESPONSE PRIORITY 3                                        | number        | number        |
```

## Time Field

```ls
Value = year_month
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:hjz8-wskg d:2016-01-01T00:00:00.000Z m:calls_average_time_on_call_minutes_all=24 m:moving_violation=324 m:aggravated_assault=27 m:involving_property_damage=30 m:outbound_calls=2844 m:arrests_dui=48 m:involving_dui_drugs_includes_drugs_alcohol_combo=2 m:priority_1_calls=441 m:calls_other=6893 m:citations_total=1077 m:forcible_rape=4 m:robbery=12 m:ucr_part_i_crimes_property_crime_monthly_total=370 m:criminal_homicide=1 m:parking_violation=108 m:ucr_part_i_crimes_monthly_total=414 m:priority_3_calls=1713 m:911_calls=5098 m:call_center_calls_total=18603 m:response_priority_3=19.63 m:traffic_collisions=145 m:larceny_theft=232 m:response_priority_1=6.55 m:involving_injuries=63 m:response_priority_2=9.98 m:involving_dui_alcohol=8 m:other_incoming_calls=10661 m:license_violation=7 m:fix_it_citation=126 m:involving_fatal_injuries=3 m:warning_citation=206 m:non_moving_violation=144 m:calls_for_service_total=11121 m:municode_violation=82 m:calls_officer_initiated_2=38 m:criminal_citation=0 m:calls_officer_initiated_1=4228 m:calls_average_time_on_call_minutes_officer_initiated=16 m:registration_violation=80 m:arson=3 m:involving_hit_run=38 m:ucr_part_i_crimes_violent_crime=44 m:burglary=74 m:motor_vehicle_theft=61 m:priority_2_calls=2565

series e:hjz8-wskg d:2016-02-01T00:00:00.000Z m:calls_average_time_on_call_minutes_all=26 m:moving_violation=254 m:aggravated_assault=38 m:involving_property_damage=26 m:outbound_calls=2880 m:arrests_dui=62 m:involving_dui_drugs_includes_drugs_alcohol_combo=0 m:priority_1_calls=441 m:calls_other=6730 m:citations_total=1085 m:forcible_rape=10 m:robbery=11 m:ucr_part_i_crimes_property_crime_monthly_total=302 m:criminal_homicide=1 m:parking_violation=129 m:ucr_part_i_crimes_monthly_total=362 m:priority_3_calls=1627 m:911_calls=4895 m:call_center_calls_total=19849 m:response_priority_3=22.37 m:traffic_collisions=156 m:larceny_theft=211 m:response_priority_1=6.2 m:involving_injuries=68 m:response_priority_2=11.27 m:involving_dui_alcohol=10 m:other_incoming_calls=12074 m:license_violation=9 m:fix_it_citation=113 m:involving_fatal_injuries=1 m:warning_citation=262 m:non_moving_violation=168 m:calls_for_service_total=11096 m:municode_violation=85 m:calls_officer_initiated_2=39 m:criminal_citation=1 m:calls_officer_initiated_1=4366 m:calls_average_time_on_call_minutes_officer_initiated=18 m:registration_violation=64 m:arson=3 m:involving_hit_run=44 m:ucr_part_i_crimes_violent_crime=60 m:burglary=43 m:motor_vehicle_theft=45 m:priority_2_calls=2504

series e:hjz8-wskg d:2016-03-01T00:00:00.000Z m:calls_average_time_on_call_minutes_all=25 m:moving_violation=399 m:aggravated_assault=45 m:involving_property_damage=18 m:outbound_calls=2918 m:arrests_dui=64 m:involving_dui_drugs_includes_drugs_alcohol_combo=1 m:priority_1_calls=431 m:calls_other=6716 m:citations_total=1290 m:forcible_rape=9 m:robbery=13 m:ucr_part_i_crimes_property_crime_monthly_total=287 m:criminal_homicide=0 m:parking_violation=136 m:ucr_part_i_crimes_monthly_total=354 m:priority_3_calls=1673 m:911_calls=5187 m:call_center_calls_total=20440 m:response_priority_3=21.3 m:traffic_collisions=136 m:larceny_theft=188 m:response_priority_1=5.93 m:involving_injuries=50 m:response_priority_2=10.92 m:involving_dui_alcohol=4 m:other_incoming_calls=12335 m:license_violation=5 m:fix_it_citation=114 m:involving_fatal_injuries=1 m:warning_citation=303 m:non_moving_violation=176 m:calls_for_service_total=11265 m:municode_violation=103 m:calls_officer_initiated_2=40 m:criminal_citation=2 m:calls_officer_initiated_1=4549 m:calls_average_time_on_call_minutes_officer_initiated=19 m:registration_violation=52 m:arson=3 m:involving_hit_run=36 m:ucr_part_i_crimes_violent_crime=67 m:burglary=54 m:motor_vehicle_theft=42 m:priority_2_calls=2573
```

## Meta Commands

```ls
metric m:ucr_part_i_crimes_violent_crime p:integer l:"UCR PART I CRIMES - VIOLENT CRIME" t:dataTypeName=number

metric m:criminal_homicide p:integer l:"Criminal Homicide" t:dataTypeName=number

metric m:forcible_rape p:integer l:"Forcible Rape" t:dataTypeName=number

metric m:robbery p:integer l:Robbery t:dataTypeName=number

metric m:aggravated_assault p:integer l:"Aggravated Assault" t:dataTypeName=number

metric m:ucr_part_i_crimes_property_crime_monthly_total p:integer l:"UCR PART I CRIMES - PROPERTY CRIME (MONTHLY TOTAL)" t:dataTypeName=number

metric m:burglary p:integer l:Burglary t:dataTypeName=number

metric m:larceny_theft p:integer l:"Larceny Theft" t:dataTypeName=number

metric m:motor_vehicle_theft p:integer l:"Motor Vehicle Theft" t:dataTypeName=number

metric m:arson p:integer l:Arson t:dataTypeName=number

metric m:ucr_part_i_crimes_monthly_total p:integer l:"UCR PART I CRIMES - (MONTHLY TOTAL)" t:dataTypeName=number

metric m:traffic_collisions p:integer l:"TRAFFIC COLLISIONS" t:dataTypeName=number

metric m:involving_injuries p:integer l:"involving Injuries" t:dataTypeName=number

metric m:involving_fatal_injuries p:integer l:"involving Fatal Injuries" t:dataTypeName=number

metric m:involving_hit_run p:integer l:"involving Hit & Run" t:dataTypeName=number

metric m:involving_dui_alcohol p:integer l:"involving DUI/Alcohol" t:dataTypeName=number

metric m:involving_dui_drugs_includes_drugs_alcohol_combo p:integer l:"involving DUI/Drugs (includes Drugs/Alcohol combo)" t:dataTypeName=number

metric m:involving_property_damage p:integer l:"involving Property Damage" t:dataTypeName=number

metric m:arrests_dui p:integer l:"ARRESTS - DUI" t:dataTypeName=number

metric m:citations_total p:integer l:"CITATIONS - TOTAL" t:dataTypeName=number

metric m:fix_it_citation p:integer l:"FIX-IT CITATION" t:dataTypeName=number

metric m:moving_violation p:integer l:"MOVING VIOLATION" t:dataTypeName=number

metric m:parking_violation p:integer l:"PARKING VIOLATION" t:dataTypeName=number

metric m:registration_violation p:integer l:"REGISTRATION VIOLATION" t:dataTypeName=number

metric m:municode_violation p:integer l:"MUNICODE VIOLATION" t:dataTypeName=number

metric m:criminal_citation p:integer l:"CRIMINAL CITATION" t:dataTypeName=number

metric m:warning_citation p:integer l:"WARNING CITATION" t:dataTypeName=number

metric m:license_violation p:integer l:"LICENSE VIOLATION" t:dataTypeName=number

metric m:non_moving_violation p:integer l:"NON-MOVING VIOLATION" t:dataTypeName=number

metric m:calls_for_service_total p:integer l:"CALLS FOR SERVICE - TOTAL" t:dataTypeName=number

metric m:calls_officer_initiated_1 p:integer l:"CALLS - OFFICER INITIATED" t:dataTypeName=number

metric m:calls_other p:integer l:"CALLS - OTHER" t:dataTypeName=number

metric m:calls_officer_initiated_2 p:integer l:"CALLS - % OFFICER INITIATED" t:dataTypeName=percent

metric m:calls_average_time_on_call_minutes_officer_initiated p:integer l:"CALLS - AVERAGE TIME ON CALL (MINUTES) - OFFICER INITIATED" t:dataTypeName=number

metric m:calls_average_time_on_call_minutes_all p:integer l:"CALLS - AVERAGE TIME ON CALL (MINUTES) - ALL" t:dataTypeName=number

metric m:911_calls p:integer l:"911 CALLS" t:dataTypeName=number

metric m:other_incoming_calls p:integer l:"OTHER INCOMING CALLS" t:dataTypeName=number

metric m:outbound_calls p:integer l:"OUTBOUND CALLS" t:dataTypeName=number

metric m:call_center_calls_total p:integer l:"CALL CENTER CALLS - TOTAL" t:dataTypeName=number

metric m:priority_1_calls p:integer l:"PRIORITY 1 CALLS" t:dataTypeName=number

metric m:priority_2_calls p:integer l:"PRIORITY 2 CALLS" t:dataTypeName=number

metric m:priority_3_calls p:integer l:"PRIORITY 3 CALLS" t:dataTypeName=number

metric m:response_priority_1 p:float l:"RESPONSE PRIORITY 1" t:dataTypeName=number

metric m:response_priority_2 p:float l:"RESPONSE PRIORITY 2" t:dataTypeName=number

metric m:response_priority_3 p:float l:"RESPONSE PRIORITY 3" t:dataTypeName=number

entity e:hjz8-wskg l:"Police Measurables" t:url=https://data.srcity.org/api/views/hjz8-wskg

property e:hjz8-wskg t:meta.view v:id=hjz8-wskg v:category=Police v:averageRating=0 v:name="Police Measurables"

property e:hjz8-wskg t:meta.view.owner v:id=u2re-x7kp v:screenName="Petri, Jerry" v:displayName="Petri, Jerry"

property e:hjz8-wskg t:meta.view.tableauthor v:id=u2re-x7kp v:screenName="Petri, Jerry" v:roleName=administrator v:displayName="Petri, Jerry"
```

## Top Records

```ls
| year_month          | ucr_part_i_crimes_violent_crime | criminal_homicide | forcible_rape | robbery | aggravated_assault | ucr_part_i_crimes_property_crime_monthly_total | burglary | larceny_theft | motor_vehicle_theft | arson | ucr_part_i_crimes_monthly_total | traffic_collisions | involving_injuries | involving_fatal_injuries | involving_hit_run | involving_dui_alcohol | involving_dui_drugs_includes_drugs_alcohol_combo | involving_property_damage | arrests_dui | citations_total | fix_it_citation | moving_violation | parking_violation | registration_violation | municode_violation | criminal_citation | warning_citation | license_violation | non_moving_violation | calls_for_service_total | calls_officer_initiated_1 | calls_other | calls_officer_initiated_2 | calls_average_time_on_call_minutes_officer_initiated | calls_average_time_on_call_minutes_all | 911_calls | other_incoming_calls | outbound_calls | call_center_calls_total | priority_1_calls | priority_2_calls | priority_3_calls | response_priority_1 | response_priority_2 | response_priority_3 | 
| =================== | =============================== | ================= | ============= | ======= | ================== | ============================================== | ======== | ============= | =================== | ===== | =============================== | ================== | ================== | ======================== | ================= | ===================== | ================================================ | ========================= | =========== | =============== | =============== | ================ | ================= | ====================== | ================== | ================= | ================ | ================= | ==================== | ======================= | ========================= | =========== | ========================= | ==================================================== | ====================================== | ========= | ==================== | ============== | ======================= | ================ | ================ | ================ | =================== | =================== | =================== | 
| 2016-01-01T00:00:00 | 44                              | 1                 | 4             | 12      | 27                 | 370                                            | 74       | 232           | 61                  | 3     | 414                             | 145                | 63                 | 3                        | 38                | 8                     | 2                                                | 30                        | 48          | 1077            | 126             | 324              | 108               | 80                     | 82                 | 0                 | 206              | 7                 | 144                  | 11121                   | 4228                      | 6893        | 38                        | 16                                                   | 24                                     | 5098      | 10661                | 2844           | 18603                   | 441              | 2565             | 1713             | 6.55                | 9.98                | 19.63               | 
| 2016-02-01T00:00:00 | 60                              | 1                 | 10            | 11      | 38                 | 302                                            | 43       | 211           | 45                  | 3     | 362                             | 156                | 68                 | 1                        | 44                | 10                    | 0                                                | 26                        | 62          | 1085            | 113             | 254              | 129               | 64                     | 85                 | 1                 | 262              | 9                 | 168                  | 11096                   | 4366                      | 6730        | 39                        | 18                                                   | 26                                     | 4895      | 12074                | 2880           | 19849                   | 441              | 2504             | 1627             | 6.20                | 11.27               | 22.37               | 
| 2016-03-01T00:00:00 | 67                              | 0                 | 9             | 13      | 45                 | 287                                            | 54       | 188           | 42                  | 3     | 354                             | 136                | 50                 | 1                        | 36                | 4                     | 1                                                | 18                        | 64          | 1290            | 114             | 399              | 136               | 52                     | 103                | 2                 | 303              | 5                 | 176                  | 11265                   | 4549                      | 6716        | 40                        | 19                                                   | 25                                     | 5187      | 12335                | 2918           | 20440                   | 431              | 2573             | 1673             | 5.93                | 10.92               | 21.30               | 
| 2016-04-01T00:00:00 | 49                              | 0                 | 8             | 6       | 35                 | 246                                            | 38       | 181           | 26                  | 1     | 295                             | 166                | 65                 | 0                        | 50                | 12                    | 0                                                | 19                        | 70          | 1175            | 80              | 290              | 137               | 68                     | 103                | 1                 | 275              | 6                 | 215                  | 11114                   | 4198                      | 6916        | 38                        | 17                                                   | 24                                     | 5035      | 12369                | 3130           | 20534                   | 422              | 2554             | 1793             | 6.52                | 10.70               | 21.20               | 
| 2016-05-01T00:00:00 | 60                              | 1                 | 9             | 5       | 45                 | 265                                            | 47       | 198           | 20                  | 0     | 325                             | 168                | 64                 | 0                        | 48                | 11                    | 3                                                | 27                        | 53          | 1011            | 70              | 256              | 111               | 71                     | 55                 | 0                 | 262              | 4                 | 182                  | 11437                   | 4044                      | 7393        | 35                        | 17                                                   | 24                                     | 5414      | 13306                | 3151           | 21871                   | 473              | 2790             | 1870             | 6.35                | 10.20               | 21.08               | 
| 2016-06-01T00:00:00 | 53                              | 1                 | 8             | 11      | 33                 | 255                                            | 42       | 182           | 30                  | 1     | 308                             | 134                | 53                 | 0                        | 41                | 11                    | 2                                                | 20                        | 45          | 1111            | 51              | 386              | 141               | 54                     | 43                 | 0                 | 250              | 7                 | 179                  | 11599                   | 3994                      | 7605        | 34                        | 16                                                   | 24                                     | 5629      | 13216                | 3307           | 22152                   | 480              | 2843             | 1930             | 6.42                | 10.27               | 21.33               | 
| 2016-07-01T00:00:00 | 57                              | 1                 | 6             | 6       | 44                 | 200                                            | 44       | 130           | 24                  | 2     | 257                             | 133                | 44                 | 0                        | 43                | 14                    | 3                                                | 15                        | 66          | 778             | 37              | 204              | 139               | 66                     | 43                 | 0                 | 196              | 3                 | 90                   | 12027                   | 4093                      | 7934        | 34                        | 16                                                   | 23                                     | 5736      | 13327                | 3442           | 22505                   | 510              | 2960             | 1921             | 6.55                | 10.80               | 21.18               | 
| 2016-08-01T00:00:00 | 55                              | 0                 | 6             | 11      | 38                 | 234                                            | 37       | 167           | 29                  | 1     | 289                             | 162                | 65                 | 0                        | 39                | 16                    | 2                                                | 31                        | 62          | 909             | 51              | 250              | 137               | 59                     | 54                 | 1                 | 227              | 2                 | 128                  | 12442                   | 4618                      | 7824        | 37                        | 15                                                   | 23                                     | 5999      | 13473                | 3427           | 22899                   | 478              | 2901             | 1902             | 6.23                | 10.55               | 21.92               | 
| 2016-09-01T00:00:00 | 62                              | 0                 | 13            | 11      | 38                 | 214                                            | 24       | 158           | 30                  | 2     | 276                             | 164                | 70                 | 0                        | 48                | 19                    | 2                                                | 27                        | 67          | 870             | 56              | 247              | 111               | 61                     | 31                 | 0                 | 230              | 3                 | 131                  | 11822                   | 4334                      | 7488        | 37                        | 16                                                   | 24                                     | 5519      | 13017                | 3180           | 21716                   | 427              | 2767             | 1835             | 6.18                | 11.62               | 22.78               | 
| 2016-10-01T00:00:00 | 60                              | 0                 | 11            | 11      | 38                 | 203                                            | 33       | 139           | 29                  | 2     | 263                             | 186                | 70                 | 1                        | 49                | 16                    | 1                                                | 35                        | 55          | 994             | 71              | 316              | 79                | 71                     | 20                 | 0                 | 276              | 4                 | 157                  | 11989                   | 4691                      | 7298        | 39                        | 16                                                   | 23                                     | 5573      | 16061                | 3275           | 24909                   | 479              | 2665             | 1849             | 6.73                | 11.58               | 22.85               | 
```