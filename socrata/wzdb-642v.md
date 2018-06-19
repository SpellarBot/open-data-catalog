# CY14 AFD Standard Of Coverage By RAP

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cy14-afd-standard-of-coverage-by-rap) |
| Metadata | [Link](https://data.austintexas.gov/api/views/wzdb-642v) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/wzdb-642v/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/wzdb-642v/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | wzdb-642v |
| Name | CY14 AFD Standard Of Coverage By RAP |
| Attribution | Christine Thies |
| Category | Public Safety |
| Tags | afd, fire, response times, soc, standard of coverage |
| Created | 2015-07-28T14:54:50Z |
| Publication Date | 2015-07-28T15:48:20Z |

## Description

Standard of Coverage for Calendar Year 2014 (January 2014 - December 2014).  AFD's goal is to reach the resident/incident within 8 mins (from phone pickup to first arriving unit), 90% of the time. Info is grouped by Response Area Polygon (RAP) --- this is a geographical boundary which often reflects the area the station/unit would be the first responding unit.  This data can be joined to the AFD RAP layer, which is in GIS format.

## Columns

```ls
| Included | Schema Type    | Field Name                                                     | Name                                                             | Data Type | Render Type |
| ======== | ============== | ============================================================== | ================================================================ | ========= | =========== |
| No       | time           | :updated_at                                                    | updated_at                                                       | meta_data | meta_data   |
| Yes      | series tag     | response_area                                                  | Response Area                                                    | text      | text        |
| Yes      | numeric metric | number_of_emergency_incidents_with_valid_data                  | Number of Emergency Incidents with Valid Data                    | number    | number      |
| Yes      | numeric metric | number_of_arrivals_within_8_minutes                            | Number of Arrivals within 8 minutes                              | number    | number      |
| Yes      | numeric metric | percent_of_arrivals_within_8_minutes                           | Percent of Arrivals within 8 Minutes                             | percent   | percent     |
| Yes      | series tag     | first_in_department_afd                                        | First-In Department AFD                                          | text      | number      |
| Yes      | series tag     | first_in_department_esd                                        | First-In Department ESD                                          | text      | number      |
| Yes      | series tag     | 90th_percentile_total_response_time_call_receipt_to_1st_arrive | 90th Percentile Total Response Time (Call Receipt-to-1st Arrive) | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:wzdb-642v d:2015-07-28T07:54:54.000Z t:first_in_department_esd=1 t:90th_percentile_total_response_time_call_receipt_to_1st_arrive=0:09:14 t:response_area=00-0010 t:first_in_department_afd=0 m:number_of_emergency_incidents_with_valid_data=1 m:number_of_arrivals_within_8_minutes=0 m:percent_of_arrivals_within_8_minutes=0

series e:wzdb-642v d:2015-07-28T07:54:54.000Z t:first_in_department_esd=1 t:90th_percentile_total_response_time_call_receipt_to_1st_arrive=0:27:51 t:response_area=00-0020 t:first_in_department_afd=0 m:number_of_emergency_incidents_with_valid_data=1 m:number_of_arrivals_within_8_minutes=0 m:percent_of_arrivals_within_8_minutes=0

series e:wzdb-642v d:2015-07-28T07:54:54.000Z t:first_in_department_esd=0 t:90th_percentile_total_response_time_call_receipt_to_1st_arrive=0:12:50 t:response_area=00-0040 t:first_in_department_afd=10 m:number_of_emergency_incidents_with_valid_data=10 m:number_of_arrivals_within_8_minutes=7 m:percent_of_arrivals_within_8_minutes=70
```

## Meta Commands

```ls
metric m:number_of_emergency_incidents_with_valid_data p:integer l:"Number of Emergency Incidents with Valid Data" t:dataTypeName=number

metric m:number_of_arrivals_within_8_minutes p:integer l:"Number of Arrivals within 8 minutes" t:dataTypeName=number

metric m:percent_of_arrivals_within_8_minutes p:float l:"Percent of Arrivals within 8 Minutes" t:dataTypeName=percent

entity e:wzdb-642v l:"CY14 AFD Standard Of Coverage By RAP" t:attribution="Christine Thies" t:url=https://data.austintexas.gov/api/views/wzdb-642v

property e:wzdb-642v t:meta.view v:id=wzdb-642v v:category="Public Safety" v:averageRating=0 v:name="CY14 AFD Standard Of Coverage By RAP" v:attribution="Christine Thies"

property e:wzdb-642v t:meta.view.license v:name="Public Domain"

property e:wzdb-642v t:meta.view.owner v:id=uy54-8dp2 v:profileImageUrlMedium=/api/users/uy54-8dp2/profile_images/THUMB v:profileImageUrlLarge=/api/users/uy54-8dp2/profile_images/LARGE v:screenName="Christine Thies" v:profileImageUrlSmall=/api/users/uy54-8dp2/profile_images/TINY v:displayName="Christine Thies"

property e:wzdb-642v t:meta.view.tableauthor v:id=uy54-8dp2 v:profileImageUrlMedium=/api/users/uy54-8dp2/profile_images/THUMB v:profileImageUrlLarge=/api/users/uy54-8dp2/profile_images/LARGE v:screenName="Christine Thies" v:profileImageUrlSmall=/api/users/uy54-8dp2/profile_images/TINY v:roleName=editor_stories v:displayName="Christine Thies"
```

## Top Records

```ls
| :updated_at | response_area | number_of_emergency_incidents_with_valid_data | number_of_arrivals_within_8_minutes | percent_of_arrivals_within_8_minutes | first_in_department_afd | first_in_department_esd | 90th_percentile_total_response_time_call_receipt_to_1st_arrive | 
| =========== | ============= | ============================================= | =================================== | ==================================== | ======================= | ======================= | ============================================================== | 
| 1438070094  | 00-0010       | 1                                             | 0                                   | 0.0                                  | 0                       | 1                       | 0:09:14                                                        | 
| 1438070094  | 00-0020       | 1                                             | 0                                   | 0.0                                  | 0                       | 1                       | 0:27:51                                                        | 
| 1438070094  | 00-0040       | 10                                            | 7                                   | 70.0                                 | 10                      | 0                       | 0:12:50                                                        | 
| 1438070094  | 00-0060       | 16                                            | 13                                  | 81.3                                 | 7                       | 9                       | 0:09:19                                                        | 
| 1438070094  | 00-0070       | 11                                            | 7                                   | 63.6                                 | 11                      | 0                       | 0:09:19                                                        | 
| 1438070094  | 00-0080       | 4                                             | 4                                   | 100.0                                | 4                       | 0                       | 0:05:56                                                        | 
| 1438070094  | 00-0101       | 1960                                          | 1853                                | 94.5                                 | 1960                    | 0                       | 0:06:55                                                        | 
| 1438070094  | 00-0102       | 1388                                          | 1316                                | 94.8                                 | 1388                    | 0                       | 0:07:10                                                        | 
| 1438070094  | 00-0201       | 593                                           | 541                                 | 91.2                                 | 593                     | 0                       | 0:07:35                                                        | 
| 1438070094  | 00-0202       | 476                                           | 439                                 | 92.2                                 | 476                     | 0                       | 0:07:29                                                        | 
```