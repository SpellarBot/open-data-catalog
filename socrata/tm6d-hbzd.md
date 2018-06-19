# Incidents Responded to by Fire Companies

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fdny-incidents-responded-to-by-fire-companies) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/tm6d-hbzd) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/tm6d-hbzd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/tm6d-hbzd/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | tm6d-hbzd |
| Name | Incidents Responded to by Fire Companies |
| Attribution | Fire Department of New York City (FDNY) |
| Category | Public Safety |
| Tags | fdny, fire, emergency |
| Created | 2016-07-27T21:11:43Z |
| Publication Date | 2016-08-01T16:00:17Z |

## Description

This dataset contains detailed information on incidents handled by FDNY Fire (non-EMS) units and includes fire, medical and non-fire emergencies. The data is collected in the New York Fire Incident Reporting System (NYFIRS), which is structured by the FDNY to provide data to the National Fire Incident Reporting System (NFIRS).  NFIRS is a modular all-incident reporting system designed by the U.S. Fire Administration. After responding to an incident, FDNY officers complete one or more of the NFIRS modules, depending upon the type of incident. The information in these modules describes the kind of incident responded to, where it occurred, the resources used to mitigate it.  Although NFIRS was designed specifically to understand the nature and causes of fire, as well as civilian fire casualties and firefighter injuries, it has been expanded to collect basic information on all incidents to which fire units respond.

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                         | Data Type     | Render Type   |
| ======== | ============== | ============================ | ============================ | ============= | ============= |
| Yes      | series tag     | im_incident_key              | IM_INCIDENT_KEY              | text          | text          |
| Yes      | series tag     | fire_box                     | FIRE_BOX                     | text          | text          |
| Yes      | series tag     | incident_type_desc           | INCIDENT_TYPE_DESC           | text          | text          |
| Yes      | time           | incident_date_time           | INCIDENT_DATE_TIME           | calendar_date | calendar_date |
| No       |                | arrival_date_time            | ARRIVAL_DATE_TIME            | calendar_date | calendar_date |
| Yes      | numeric metric | units_onscene                | UNITS_ONSCENE                | number        | text          |
| No       |                | last_unit_cleared_date_time  | LAST_UNIT_CLEARED_DATE_TIME  | calendar_date | calendar_date |
| Yes      | series tag     | highest_level_desc           | HIGHEST_LEVEL_DESC           | text          | text          |
| Yes      | numeric metric | total_incident_duration      | TOTAL_INCIDENT_DURATION      | number        | text          |
| Yes      | series tag     | action_taken1_desc           | ACTION_TAKEN1_DESC           | text          | text          |
| Yes      | series tag     | action_taken2_desc           | ACTION_TAKEN2_DESC           | text          | text          |
| Yes      | series tag     | action_taken3_desc           | ACTION_TAKEN3_DESC           | text          | text          |
| Yes      | series tag     | property_use_desc            | PROPERTY_USE_DESC            | text          | text          |
| Yes      | series tag     | street_highway               | STREET_HIGHWAY               | text          | text          |
| Yes      | series tag     | zip_code                     | ZIP_CODE                     | text          | text          |
| Yes      | series tag     | borough_desc                 | BOROUGH_DESC                 | text          | text          |
| Yes      | series tag     | floor                        | FLOOR                        | text          | text          |
| Yes      | series tag     | co_detector_present_desc     | CO_DETECTOR_PRESENT_DESC     | text          | text          |
| Yes      | series tag     | fire_origin_below_grade_flag | FIRE_ORIGIN_BELOW_GRADE_FLAG | text          | text          |
| Yes      | numeric metric | story_fire_origin_count      | STORY_FIRE_ORIGIN_COUNT      | number        | text          |
| Yes      | series tag     | fire_spread_desc             | FIRE_SPREAD_DESC             | text          | text          |
| Yes      | series tag     | detector_presence_desc       | DETECTOR_PRESENCE_DESC       | text          | text          |
| Yes      | series tag     | aes_presence_desc            | AES_PRESENCE_DESC            | text          | text          |
| Yes      | series tag     | standpipe_sys_present_flag   | STANDPIPE_SYS_PRESENT_FLAG   | text          | text          |
```

## Time Field

```ls
Value = incident_date_time
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = arrival_date_time,last_unit_cleared_date_time
```

## Data Commands

```ls
series e:tm6d-hbzd d:2013-01-01T00:00:20.000Z t:im_incident_key=55672688 t:action_taken1_desc="00 - Action taken, other" t:zip_code=10454 t:property_use_desc="UUU - Undetermined" t:borough_desc="2 - Bronx" t:incident_type_desc="300 - Rescue, EMS incident, other" t:fire_box=2147 t:highest_level_desc="1 - More than initial alarm, less than Signal 7-5" t:street_highway="E 138 ST" m:units_onscene=1 m:total_incident_duration=1186

series e:tm6d-hbzd d:2013-01-01T00:00:37.000Z t:im_incident_key=55672692 t:action_taken1_desc="86 - Investigate" t:zip_code=10036 t:property_use_desc="UUU - Undetermined" t:borough_desc="1 - Manhattan" t:incident_type_desc="735A - Unwarranted alarm/defective condition of alarm system" t:fire_box=0818 t:highest_level_desc="1 - More than initial alarm, less than Signal 7-5" t:street_highway="W 46 ST" m:units_onscene=3 m:total_incident_duration=1769

series e:tm6d-hbzd d:2013-01-01T00:01:17.000Z t:im_incident_key=55672693 t:action_taken1_desc="00 - Action taken, other" t:zip_code=11418 t:property_use_desc="UUU - Undetermined" t:borough_desc="5 - Queens" t:incident_type_desc="300 - Rescue, EMS incident, other" t:fire_box=9656 t:highest_level_desc="1 - More than initial alarm, less than Signal 7-5" t:street_highway="116 ST" m:units_onscene=1 m:total_incident_duration=841
```

## Meta Commands

```ls
metric m:units_onscene p:integer l:UNITS_ONSCENE t:dataTypeName=number

metric m:total_incident_duration p:integer l:TOTAL_INCIDENT_DURATION t:dataTypeName=number

metric m:story_fire_origin_count p:integer l:STORY_FIRE_ORIGIN_COUNT t:dataTypeName=number

entity e:tm6d-hbzd l:"Incidents Responded to by Fire Companies" t:attribution="Fire Department of New York City (FDNY)" t:url=https://data.cityofnewyork.us/api/views/tm6d-hbzd

property e:tm6d-hbzd t:meta.view v:id=tm6d-hbzd v:category="Public Safety" v:averageRating=0 v:name="Incidents Responded to by Fire Companies" v:attribution="Fire Department of New York City (FDNY)"

property e:tm6d-hbzd t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:tm6d-hbzd t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| im_incident_key | fire_box | incident_type_desc                                           | incident_date_time  | arrival_date_time   | units_onscene | last_unit_cleared_date_time | highest_level_desc                                | total_incident_duration | action_taken1_desc                                  | action_taken2_desc    | action_taken3_desc          | property_use_desc          | street_highway | zip_code | borough_desc  | floor | co_detector_present_desc | fire_origin_below_grade_flag | story_fire_origin_count | fire_spread_desc | detector_presence_desc | aes_presence_desc | standpipe_sys_present_flag | 
| =============== | ======== | ============================================================ | =================== | =================== | ============= | =========================== | ================================================= | ======================= | =================================================== | ===================== | =========================== | ========================== | ============== | ======== | ============= | ===== | ======================== | ============================ | ======================= | ================ | ====================== | ================= | ========================== | 
| 55672688        | 2147     | 300 - Rescue, EMS incident, other                            | 2013-01-01T00:00:20 | 2013-01-01T00:14:23 | 1             | 2013-01-01T00:20:06         | 1 - More than initial alarm, less than Signal 7-5 | 1186                    | 00 - Action taken, other                            |                       |                             | UUU - Undetermined         | E 138 ST       | 10454    | 2 - Bronx     |       |                          |                              |                         |                  |                        |                   |                            | 
| 55672692        | 0818     | 735A - Unwarranted alarm/defective condition of alarm system | 2013-01-01T00:00:37 | 2013-01-01T00:09:03 | 3             | 2013-01-01T00:30:06         | 1 - More than initial alarm, less than Signal 7-5 | 1769                    | 86 - Investigate                                    |                       |                             | UUU - Undetermined         | W 46 ST        | 10036    | 1 - Manhattan |       |                          |                              |                         |                  |                        |                   |                            | 
| 55672693        | 9656     | 300 - Rescue, EMS incident, other                            | 2013-01-01T00:01:17 | 2013-01-01T00:04:55 | 1             | 2013-01-01T00:15:18         | 1 - More than initial alarm, less than Signal 7-5 | 841                     | 00 - Action taken, other                            |                       |                             | UUU - Undetermined         | 116 ST         | 11418    | 5 - Queens    |       |                          |                              |                         |                  |                        |                   |                            | 
| 55672695        | 7412     | 412 - Gas leak (natural gas or LPG)                          | 2013-01-01T00:02:32 | 2013-01-01T00:07:48 | 4             | 2013-01-01T00:40:11         | 1 - More than initial alarm, less than Signal 7-5 | 2259                    | 44 - Hazardous materials leak control & containment | 64 - Shut down system | 82 - Notify other agencies. | 429 - Multifamily dwelling | 43 ST          | 11103    | 5 - Queens    | 1     |                          |                              |                         |                  |                        |                   |                            | 
| 55672697        | 4019     | 735A - Unwarranted alarm/defective condition of alarm system | 2013-01-01T00:01:49 | 2013-01-01T00:06:27 | 6             | 2013-01-01T00:24:56         | 1 - More than initial alarm, less than Signal 7-5 | 1387                    | 86 - Investigate                                    |                       |                             | UUU - Undetermined         | WYCKOFF AVE    | 11385    | 5 - Queens    |       |                          |                              |                         |                  |                        |                   |                            | 
| 55672698        | 1328     | 735A - Unwarranted alarm/defective condition of alarm system | 2013-01-01T00:02:45 | 2013-01-01T00:07:55 | 3             | 2013-01-01T00:18:20         | 1 - More than initial alarm, less than Signal 7-5 | 935                     | 86 - Investigate                                    |                       |                             | UUU - Undetermined         | HAMILTON AVE   | 11215    | 4 - Brooklyn  |       |                          |                              |                         |                  |                        |                   |                            | 
| 55672699        | 0688     | 353 - Removal of victim(s) from stalled elevator             | 2013-01-01T00:03:55 | 2013-01-01T00:13:10 | 1             | 2013-01-01T00:30:33         | 1 - More than initial alarm, less than Signal 7-5 | 1598                    | 64 - Shut down system                               |                       |                             | 429 - Multifamily dwelling | AVEOFAMERICAS  | 10001    | 1 - Manhattan | 18    |                          |                              |                         |                  |                        |                   |                            | 
| 55672700        | 9604     | 651 - Smoke scare, odor of smoke                             | 2013-01-01T00:04:03 | 2013-01-01T00:06:19 | 4             | 2013-01-01T00:11:21         | 1 - More than initial alarm, less than Signal 7-5 | 438                     | 86 - Investigate                                    |                       |                             | 960 - Street, other        | 102 ST         | 11418    | 5 - Queens    |       |                          |                              |                         |                  |                        |                   |                            | 
| 55672703        | 2897     | 331 - Lock-in (if lock out , use 511 )                       | 2013-01-01T00:04:37 | 2013-01-01T00:11:02 | 1             | 2013-01-01T00:23:29         | 1 - More than initial alarm, less than Signal 7-5 | 1132                    | 70 - Assistance, other                              |                       |                             | 429 - Multifamily dwelling | BOYNTON AVE    | 10472    | 2 - Bronx     |       |                          |                              |                         |                  |                        |                   |                            | 
| 55672705        | 2602     | 710 - Malicious, mischievous false call, other               | 2013-01-01T00:05:10 | 2013-01-01T00:08:20 | 6             | 2013-01-01T00:10:29         | 1 - More than initial alarm, less than Signal 7-5 | 319                     | 00 - Action taken, other                            |                       |                             | UUU - Undetermined         | 52 ST          | 11219    | 4 - Brooklyn  |       |                          |                              |                         |                  |                        |                   |                            | 
```