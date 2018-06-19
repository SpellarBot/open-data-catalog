# Racial Profiling Prohibition Project Traffic Stop Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/racial-profiling-prohibition-project-traffic-stop-data) |
| Metadata | [Link](https://data.ct.gov/api/views/g7s9-f7az) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/g7s9-f7az/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/g7s9-f7az/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | g7s9-f7az |
| Name | Racial Profiling Prohibition Project Traffic Stop Data |
| Attribution | Institute for Municipal and Regional Policy |
| Category | Public Safety |
| Tags | traffic, stop, racial profiling, ctrp3 |
| Created | 2014-09-05T14:24:39Z |
| Publication Date | 2015-09-22T20:32:52Z |

## Description

This dataset was created in accordance with The Alvin W. Penn Racial Profiling Prohibition Act (Connecticut General Statutes Sections 54-1l and 54-1m) which prohibits any law enforcement agency from stopping, detaining, or searching any motorist when the stop is motivated solely by considerations of the race, color, ethnicity, age, gender or sexual orientation.

## Columns

```ls
| Included | Schema Type    | Field Name                               | Name                                     | Data Type     | Render Type   |
| ======== | ============== | ======================================== | ======================================== | ============= | ============= |
| Yes      | series tag     | organization_identification_id           | Organization Identification ID           | text          | text          |
| Yes      | series tag     | department_name                          | Department Name                          | text          | text          |
| Yes      | series tag     | organization_activity_text               | Organization Activity Text               | text          | text          |
| Yes      | series tag     | reporting_office_ridentification_id      | Reporting Officer Identification ID      | text          | text          |
| Yes      | series tag     | intervention_identification_id           | Intervention Identification ID           | text          | text          |
| Yes      | series tag     | identification_category_description_text | Identification Category Description Text | text          | text          |
| Yes      | time           | intervention_date                        | Intervention Date                        | calendar_date | calendar_date |
| No       |                | day_of_week                              | Day of Week                              | text          | text          |
| Yes      | series tag     | subjec_trace_code                        | Subject Race Code                        | text          | text          |
| Yes      | series tag     | subjec_tethnicit_ycode                   | Subject Ethnicity Code                   | text          | text          |
| Yes      | series tag     | subject_sex_code                         | Subject Sex Code                         | text          | text          |
| Yes      | numeric metric | subject_age                              | Subject Age                              | number        | number        |
| Yes      | series tag     | resident_indicator                       | Resident Indicator                       | text          | text          |
| Yes      | series tag     | town_resident_indicator                  | Town Resident Indicator                  | text          | text          |
| Yes      | series tag     | intervention_location_name               | Intervention Location Name               | text          | text          |
| Yes      | series tag     | intervention_location_description_text   | Intervention Location Description Text   | text          | text          |
| Yes      | series tag     | intervention_reason_code                 | Intervention Reason Code                 | text          | text          |
| Yes      | series tag     | intervention_technique_code              | Intervention Technique Code              | text          | text          |
| Yes      | series tag     | intervention_duration_code               | Intervention Duration Code               | text          | number        |
| Yes      | series tag     | towed_indicator                          | Towed Indicator                          | text          | text          |
| Yes      | series tag     | statute_code_identification_id           | Statute Code Identification ID           | text          | text          |
| Yes      | series tag     | column2                                  | Statute Code Description                 | text          | text          |
| Yes      | series tag     | statutatory_citation                     | Statutatory Citation                     | text          | text          |
| Yes      | series tag     | vehicle_searched_indicator               | Vehicle Searched Indicator               | text          | text          |
| Yes      | series tag     | search_authorization_code                | Search Authorization Code                | text          | text          |
| Yes      | series tag     | contraband_indicator                     | Contraband Indicator                     | text          | text          |
| Yes      | series tag     | custodial_arrest_indicator               | Custodial Arrest Indicator               | text          | text          |
| Yes      | series tag     | intervention_disposition_code            | Intervention Disposition Code            | text          | text          |
| No       |                | intervention_time                        | Intervention Time                        | text          | text          |
```

## Time Field

```ls
Value = intervention_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = day_of_week,intervention_time
```

## Data Commands

```ls
series e:g7s9-f7az d:2013-10-01T00:00:00.000Z t:subject_sex_code=F t:resident_indicator=TRUE t:town_resident_indicator=FALSE t:intervention_reason_code=V t:statutatory_citation=14-100a(c)(1) t:intervention_identification_id=1300024756 t:intervention_disposition_code=V t:subjec_tethnicit_ycode=N t:column2=Seatbelt t:intervention_duration_code=1 t:intervention_location_name=BRANFORD t:organization_identification_id=CT0001400 t:reporting_office_ridentification_id=378 t:intervention_technique_code=G t:contraband_indicator=FALSE t:department_name=Branford t:organization_activity_text="Racial Profile" t:search_authorization_code=N t:statute_code_identification_id=14-100a(c)(1) t:subjec_trace_code=W t:vehicle_searched_indicator=FALSE t:intervention_location_description_text="west main/short beach rd" t:towed_indicator=FALSE t:custodial_arrest_indicator=FALSE t:identification_category_description_text="Incident ID" m:subject_age=36

series e:g7s9-f7az d:2013-10-01T00:00:00.000Z t:subject_sex_code=M t:resident_indicator=TRUE t:town_resident_indicator=TRUE t:intervention_reason_code=V t:statutatory_citation=14-298 t:intervention_identification_id=1300616313 t:intervention_disposition_code=V t:subjec_tethnicit_ycode=M t:column2=Other t:intervention_duration_code=1 t:intervention_location_name="NEW HAVEN" t:organization_identification_id=CTCSP1000 t:reporting_office_ridentification_id=1000001940 t:intervention_technique_code=G t:contraband_indicator=FALSE t:department_name="State Police" t:organization_activity_text="Racial Profile" t:search_authorization_code=N t:statute_code_identification_id=14-298 t:subjec_trace_code=W t:vehicle_searched_indicator=FALSE t:intervention_location_description_text="i-91 NORTHBOUND BY EXIT 7 ENTRANCE" t:towed_indicator=FALSE t:custodial_arrest_indicator=FALSE t:identification_category_description_text="Incident ID" m:subject_age=46

series e:g7s9-f7az d:2013-10-01T00:00:00.000Z t:subject_sex_code=F t:resident_indicator=TRUE t:town_resident_indicator=FALSE t:intervention_reason_code=V t:statutatory_citation=NA t:intervention_identification_id=1300616887 t:intervention_disposition_code=I t:subjec_tethnicit_ycode=H t:column2=Seatbelt t:intervention_duration_code=1 t:intervention_location_name=NORWICH t:organization_identification_id=CTCSP0600 t:reporting_office_ridentification_id=1000002349 t:intervention_technique_code=G t:contraband_indicator=FALSE t:department_name="State Police" t:organization_activity_text="Racial Profile" t:search_authorization_code=N t:statute_code_identification_id=14-100a(d) t:subjec_trace_code=W t:vehicle_searched_indicator=FALSE t:intervention_location_description_text="00000 N I 395 (NORWICH, T104)" t:towed_indicator=TRUE t:custodial_arrest_indicator=FALSE t:identification_category_description_text="Incident ID" m:subject_age=33
```

## Meta Commands

```ls
metric m:subject_age p:integer l:"Subject Age" t:dataTypeName=number

entity e:g7s9-f7az l:"Racial Profiling Prohibition Project Traffic Stop Data" t:attribution="Institute for Municipal and Regional Policy" t:url=https://data.ct.gov/api/views/g7s9-f7az

property e:g7s9-f7az t:meta.view v:id=g7s9-f7az v:category="Public Safety" v:attributionLink=http://s429795233.onlinehome.us/september-2014-report/ v:averageRating=0 v:name="Racial Profiling Prohibition Project Traffic Stop Data" v:attribution="Institute for Municipal and Regional Policy"

property e:g7s9-f7az t:meta.view.license v:name="Public Domain"

property e:g7s9-f7az t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:g7s9-f7az t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| organization_identification_id | department_name | organization_activity_text | reporting_office_ridentification_id | intervention_identification_id | identification_category_description_text | intervention_date   | day_of_week | subjec_trace_code | subjec_tethnicit_ycode | subject_sex_code | subject_age | resident_indicator | town_resident_indicator | intervention_location_name | intervention_location_description_text | intervention_reason_code | intervention_technique_code | intervention_duration_code | towed_indicator | statute_code_identification_id | column2           | statutatory_citation | vehicle_searched_indicator | search_authorization_code | contraband_indicator | custodial_arrest_indicator | intervention_disposition_code | intervention_time | 
| ============================== | =============== | ========================== | =================================== | ============================== | ======================================== | =================== | =========== | ================= | ====================== | ================ | =========== | ================== | ======================= | ========================== | ====================================== | ======================== | =========================== | ========================== | =============== | ============================== | ================= | ==================== | ========================== | ========================= | ==================== | ========================== | ============================= | ================= | 
| CT0001400                      | Branford        | Racial Profile             | 378                                 | 1300024756                     | Incident ID                              | 2013-10-01T00:00:00 | Tuesday     | W                 | N                      | F                | 36          | TRUE               | FALSE                   | BRANFORD                   | west main/short beach rd               | V                        | G                           | 1                          | FALSE           | 14-100a(c)(1)                  | Seatbelt          | 14-100a(c)(1)        | FALSE                      | N                         | FALSE                | FALSE                      | V                             | 12:52             | 
| CTCSP1000                      | State Police    | Racial Profile             | 1000001940                          | 1300616313                     | Incident ID                              | 2013-10-01T00:00:00 | Tuesday     | W                 | M                      | M                | 46          | TRUE               | TRUE                    | NEW HAVEN                  | i-91 NORTHBOUND BY EXIT 7 ENTRANCE     | V                        | G                           | 1                          | FALSE           | 14-298                         | Other             | 14-298               | FALSE                      | N                         | FALSE                | FALSE                      | V                             | 14:38             | 
| CTCSP0600                      | State Police    | Racial Profile             | 1000002349                          | 1300616887                     | Incident ID                              | 2013-10-01T00:00:00 | Tuesday     | W                 | H                      | F                | 33          | TRUE               | FALSE                   | NORWICH                    | 00000 N I 395 (NORWICH, T104)          | V                        | G                           | 1                          | TRUE            | 14-100a(d)                     | Seatbelt          | NA                   | FALSE                      | N                         | FALSE                | FALSE                      | I                             | 20:25             | 
| CTCSP0700                      | State Police    | Racial Profile             | 987312802                           | 1300615169                     | Incident ID                              | 2013-10-01T00:00:00 | Tuesday     | B                 | N                      | M                | 64          | TRUE               | FALSE                   | OLD SAYBROOK               | X67 SB                                 | V                        | G                           | 1                          | FALSE           | 14-298                         | Other             | 14-298               | FALSE                      | N                         | FALSE                | FALSE                      | I                             | 2:11              | 
| CT0001400                      | Branford        | Racial Profile             | 1051                                | 1300024738                     | Incident ID                              | 2013-10-01T00:00:00 | Tuesday     | W                 | N                      | M                | 49          | TRUE               | TRUE                    | Branford                   | cedar street                           | I                        | G                           | 1                          | FALSE           | 14-18(A)                       | Display of Plates | NA                   | FALSE                      | N                         | FALSE                | FALSE                      | N                             | 9:35              | 
| CT0011800                      | Ridgefield      | Racial Profile             | 1000142                             | 1300016337                     | Incident ID                              | 2013-10-01T00:00:00 | Tuesday     | B                 | N                      | M                | 18          | TRUE               | FALSE                   | RIDGEFIELD                 | Danbury Rd/Laurel Lane                 | V                        | G                           | 1                          | FALSE           | 14-219b                        | Speed Related     | 14-36(b)(1)          | FALSE                      | N                         | FALSE                | FALSE                      | I                             | 9:49              | 
| CT0014300                      | Torrington      | Racial Profile             | WQUAR040                            | 13-45354                       | Incident ID                              | 2013-10-01T00:00:00 | Tuesday     | W                 | N                      | M                | 49          | TRUE               | FALSE                   | Torrington                 | MIGEON AVE NEAR A TO Z                 | V                        | G                           | 1                          | FALSE           | 14-296aa(b)                    | Cell Phone        | NA                   | FALSE                      | N                         | FALSE                | FALSE                      | I                             | 14:23             | 
| CTCSP0800                      | State Police    | Racial Profile             | 961269420                           | 1300615108                     | Incident ID                              | 2013-10-01T00:00:00 | Tuesday     | W                 | N                      | M                | 26          | FALSE              | FALSE                   | EAST HAVEN                 | I-95 SB EXIT 51                        | V                        | B                           | 1                          | FALSE           | 14-219(c)(1)                   | Speed Related     | 14-219(C)(1)         | FALSE                      | N                         | FALSE                | FALSE                      | I                             | 1:31              | 
| CT0007700                      | Manchester      | Racial Profile             | GCB3491                             | 33732                          | Incident ID                              | 2013-10-01T00:00:00 | Tuesday     | W                 | N                      | F                | 31          | TRUE               | FALSE                   | Manchester                 | 1404 TOLLAND TPK                       | V                        | G                           | 1                          | FALSE           | 14-296aa(b)                    | Cell Phone        | NA                   | FALSE                      | N                         | FALSE                | FALSE                      | I                             | 15:41             | 
| CT0011800                      | Ridgefield      | Racial Profile             | 1000064                             | 1300016361                     | Incident ID                              | 2013-10-01T00:00:00 | Tuesday     | W                 | N                      | F                | 20          | TRUE               | FALSE                   | Ridgefield                 | danbury rd                             | V                        | G                           | 1                          | FALSE           | 14-218a                        | Speed Related     | NA                   | FALSE                      | N                         | FALSE                | FALSE                      | W                             | 20:35             | 
```