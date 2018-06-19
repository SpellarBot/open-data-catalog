# EMS - Quarterly Clinical Measures - Stroke Alert

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ems-quarterly-clinical-measures-stroke-alert) |
| Metadata | [Link](https://data.austintexas.gov/api/views/6mtx-ivnd) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/6mtx-ivnd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/6mtx-ivnd/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 6mtx-ivnd |
| Name | EMS - Quarterly Clinical Measures - Stroke Alert |
| Attribution | Austin-Travis County EMS |
| Category | Public Safety |
| Tags | ems, atcems, clinical data, clinical performance, clinical measures, patient care, stroke, alert |
| Created | 2017-01-17T22:12:02Z |
| Publication Date | 2017-01-18T16:04:02Z |

## Description

This table contains data describing ATCEMS management of stroke alert patients.

## Columns

```ls
| Included | Schema Type    | Field Name                           | Name                                                 | Data Type     | Render Type   |
| ======== | ============== | ==================================== | ==================================================== | ============= | ============= |
| Yes      | numeric metric | fiscal_quarter_key                   | Fiscal Quarter Key                                   | number        | number        |
| No       |                | fiscal_quarter                       | Fiscal Quarter                                       | text          | text          |
| Yes      | time           | fiscal_quarter_start_date            | Fiscal Quarter Start Date                            | calendar_date | calendar_date |
| No       |                | fiscal_quarter_end_date              | Fiscal Quarter End Date                              | calendar_date | calendar_date |
| Yes      | numeric metric | count_stroke_alert                   | Count - Stroke Alerts                                | number        | number        |
| Yes      | numeric metric | count_scene_time_compliance          | Count - Stroke Alert Scene Interval Compliance       | number        | number        |
| Yes      | numeric metric | percent_scene_time_compliance        | Percent - Stroke Alert Scene Interval Compliance     | percent       | percent       |
| Yes      | numeric metric | percent_scene_time_compliance_target | Stroke Alert Scene Interval Compliance Target        | percent       | percent       |
| Yes      | numeric metric | count_specialty_center               | Count - Stroke Center Transports                     | number        | number        |
| Yes      | numeric metric | percent_specialty_center             | Percent Stroke Center Transports                     | percent       | percent       |
| Yes      | numeric metric | percent_specialty_center_target      | Stroke Center Transports Target                      | percent       | percent       |
| Yes      | numeric metric | average_interval_call_to_door        | Average Stroke Alert Call to Door Interval (Minutes) | number        | number        |
| Yes      | numeric metric | average_interval_call_to_door_target | Stroke Alert Call to Door Interval Target            | number        | number        |
| Yes      | numeric metric | count_bgl                            | Count - BGL Test for Stroke Alerts                   | number        | number        |
| Yes      | numeric metric | percent_bgl                          | Percent - BGL Test for Stroke Alerts                 | percent       | percent       |
| Yes      | numeric metric | percent_bgl_target                   | Stroke Alert BGL Test Target                         | percent       | percent       |
| Yes      | numeric metric | count_cpss                           | Count - CPSS Score Documented                        | number        | number        |
| Yes      | numeric metric | percent_cpss                         | Percent - CPSS Score Documented                      | percent       | percent       |
| Yes      | numeric metric | percent_cpss_target                  | Percent CPSS Target                                  | percent       | percent       |
| Yes      | numeric metric | count_bundle_complete                | Count ? Stroke Alert Bundle Completed                | number        | number        |
| Yes      | numeric metric | percent_bundle_complete              | Percent ? Stroke Alert Bundle Completed              | percent       | percent       |
| Yes      | numeric metric | percent_bundle_complete_target       | Percent - Stroke Alert Bundle Complete Target        | percent       | percent       |
```

## Time Field

```ls
Value = fiscal_quarter_start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = fiscal_quarter_end_date,fiscal_quarter
```

## Data Commands

```ls
series e:6mtx-ivnd d:2013-10-01T00:00:00.000Z m:percent_bundle_complete=75 m:fiscal_quarter_key=201401 m:percent_cpss_target=95 m:count_scene_time_compliance=104 m:count_cpss=119 m:percent_bundle_complete_target=90 m:count_stroke_alert=124 m:percent_specialty_center_target=95 m:average_interval_call_to_door=36.41 m:count_bgl=116 m:percent_bgl=93.55 m:percent_specialty_center=100 m:average_interval_call_to_door_target=45 m:percent_bgl_target=95 m:percent_scene_time_compliance=83.87 m:percent_scene_time_compliance_target=90 m:percent_cpss=95.97 m:count_bundle_complete=93 m:count_specialty_center=124

series e:6mtx-ivnd d:2014-01-01T00:00:00.000Z m:percent_bundle_complete=77.7 m:fiscal_quarter_key=201402 m:percent_cpss_target=95 m:count_scene_time_compliance=110 m:count_cpss=137 m:percent_bundle_complete_target=90 m:count_stroke_alert=139 m:percent_specialty_center_target=95 m:average_interval_call_to_door=37.53 m:count_bgl=134 m:percent_bgl=96.4 m:percent_specialty_center=100 m:average_interval_call_to_door_target=45 m:percent_bgl_target=95 m:percent_scene_time_compliance=79.14 m:percent_scene_time_compliance_target=90 m:percent_cpss=98.56 m:count_bundle_complete=108 m:count_specialty_center=139

series e:6mtx-ivnd d:2014-04-01T00:00:00.000Z m:percent_bundle_complete=76.52 m:fiscal_quarter_key=201403 m:percent_cpss_target=95 m:count_scene_time_compliance=107 m:count_cpss=127 m:percent_bundle_complete_target=90 m:count_stroke_alert=132 m:percent_specialty_center_target=95 m:average_interval_call_to_door=36.19 m:count_bgl=127 m:percent_bgl=96.21 m:percent_specialty_center=99.24 m:average_interval_call_to_door_target=45 m:percent_bgl_target=95 m:percent_scene_time_compliance=81.06 m:percent_scene_time_compliance_target=90 m:percent_cpss=96.21 m:count_bundle_complete=101 m:count_specialty_center=131
```

## Meta Commands

```ls
metric m:fiscal_quarter_key p:integer l:"Fiscal Quarter Key" d:"Numeric representation of fiscal quarter in <yyyyqq> format." t:dataTypeName=number

metric m:count_stroke_alert p:integer l:"Count - Stroke Alerts" d:"Count of Stroke Alert patients" t:dataTypeName=number

metric m:count_scene_time_compliance p:integer l:"Count - Stroke Alert Scene Interval Compliance" d:"Count of stroke alert patients with a scene interval less than 15 minutes. Scene interval starts when the first ATCEMS personnel arrive on scene, and ends when ATCEMS personnel depart the scene." t:dataTypeName=number

metric m:percent_scene_time_compliance p:float l:"Percent - Stroke Alert Scene Interval Compliance" d:"Percent of stroke alert patients with a scene interval less than 15 minutes." t:dataTypeName=percent

metric m:percent_scene_time_compliance_target p:float l:"Stroke Alert Scene Interval Compliance Target" d:"Target performance level for compliance with scene time goal for stroke alert patients." t:dataTypeName=percent

metric m:count_specialty_center p:integer l:"Count - Stroke Center Transports" d:"Count of stroke alert patients who are transported to a system approved stroke center." t:dataTypeName=number

metric m:percent_specialty_center p:float l:"Percent Stroke Center Transports" d:"Percent of stroke alert patients who are transported to a system approved stroke center." t:dataTypeName=percent

metric m:percent_specialty_center_target p:float l:"Stroke Center Transports Target" d:"Target specialty center transport rate for stroke alert patients." t:dataTypeName=percent

metric m:average_interval_call_to_door p:float l:"Average Stroke Alert Call to Door Interval (Minutes)" d:"Average interval between first 911 call and arrival at the receiving facility for stroke alert patients, measured in decimal minutes (e.g. 37.7 minutes)." t:dataTypeName=number

metric m:average_interval_call_to_door_target p:float l:"Stroke Alert Call to Door Interval Target" d:"Target for Average Call to Door Interval." t:dataTypeName=number

metric m:count_bgl p:integer l:"Count - BGL Test for Stroke Alerts" d:"Count of stroke alert patients who have a correctly documented blood glucose level (BGL) assessment." t:dataTypeName=number

metric m:percent_bgl p:float l:"Percent - BGL Test for Stroke Alerts" d:"Percent of stroke alert patients who receive a blood glucose level assessment." t:dataTypeName=percent

metric m:percent_bgl_target p:float l:"Stroke Alert BGL Test Target" d:"Target performance level for blood glucose level assessment of stroke alert patients." t:dataTypeName=percent

metric m:count_cpss p:integer l:"Count - CPSS Score Documented" d:"Count of stroke alert patients with correctly documented Cincinnati Prehospital Stroke Scale (CPSS) score." t:dataTypeName=number

metric m:percent_cpss p:float l:"Percent - CPSS Score Documented" d:"Percent of stroke alert patients with correctly documented Cincinnati Prehospital Stroke Scale score." t:dataTypeName=percent

metric m:percent_cpss_target p:float l:"Percent CPSS Target" d:"Target performance level for compliance with CPSS documentation for stroke alert patients." t:dataTypeName=percent

metric m:count_bundle_complete p:integer l:"Count ? Stroke Alert Bundle Completed" d:"Count of patients receiving complete Stroke Alert Bundle. Bundle consists of: ? BGL Assessment ? CPSS Score ? Scene Time Compliance ? Stroke Center Transport Destination A patient contact must meet standard on all four components in order to be counted as complete." t:dataTypeName=number

metric m:percent_bundle_complete p:float l:"Percent ? Stroke Alert Bundle Completed" d:"Percent of stroke alert patients receiving complete Stroke Alert Bundle." t:dataTypeName=percent

metric m:percent_bundle_complete_target p:float l:"Percent - Stroke Alert Bundle Complete Target" d:"Target performance level for compliance with Stroke Alert Bundle completion for stroke alert patients." t:dataTypeName=percent

entity e:6mtx-ivnd l:"EMS - Quarterly Clinical Measures - Stroke Alert" t:attribution="Austin-Travis County EMS" t:url=https://data.austintexas.gov/api/views/6mtx-ivnd

property e:6mtx-ivnd t:meta.view v:id=6mtx-ivnd v:category="Public Safety" v:averageRating=0 v:name="EMS - Quarterly Clinical Measures - Stroke Alert" v:attribution="Austin-Travis County EMS"

property e:6mtx-ivnd t:meta.view.owner v:id=4zcf-8die v:profileImageUrlMedium=/api/users/4zcf-8die/profile_images/THUMB v:profileImageUrlLarge=/api/users/4zcf-8die/profile_images/LARGE v:screenName="Austin-Travis County EMS" v:profileImageUrlSmall=/api/users/4zcf-8die/profile_images/TINY v:displayName="Austin-Travis County EMS"

property e:6mtx-ivnd t:meta.view.tableauthor v:id=4zcf-8die v:profileImageUrlMedium=/api/users/4zcf-8die/profile_images/THUMB v:profileImageUrlLarge=/api/users/4zcf-8die/profile_images/LARGE v:screenName="Austin-Travis County EMS" v:profileImageUrlSmall=/api/users/4zcf-8die/profile_images/TINY v:roleName=publisher_stories v:displayName="Austin-Travis County EMS"
```

## Top Records

```ls
| fiscal_quarter_key | fiscal_quarter | fiscal_quarter_start_date | fiscal_quarter_end_date | count_stroke_alert | count_scene_time_compliance | percent_scene_time_compliance | percent_scene_time_compliance_target | count_specialty_center | percent_specialty_center | percent_specialty_center_target | average_interval_call_to_door | average_interval_call_to_door_target | count_bgl | percent_bgl | percent_bgl_target | count_cpss | percent_cpss | percent_cpss_target | count_bundle_complete | percent_bundle_complete | percent_bundle_complete_target | 
| ================== | ============== | ========================= | ======================= | ================== | =========================== | ============================= | ==================================== | ====================== | ======================== | =============================== | ============================= | ==================================== | ========= | =========== | ================== | ========== | ============ | =================== | ===================== | ======================= | ============================== | 
| 201401             | 2014-Q1        | 2013-10-01T00:00:00       | 2013-12-31T23:59:50     | 124                | 104                         | 83.87                         | 90.00                                | 124                    | 100.00                   | 95.00                           | 36.41                         | 45.00                                | 116       | 93.55       | 95.00              | 119        | 95.97        | 95.00               | 93                    | 75.00                   | 90.00                          | 
| 201402             | 2014-Q2        | 2014-01-01T00:00:00       | 2014-03-31T23:59:59     | 139                | 110                         | 79.14                         | 90.00                                | 139                    | 100.00                   | 95.00                           | 37.53                         | 45.00                                | 134       | 96.40       | 95.00              | 137        | 98.56        | 95.00               | 108                   | 77.70                   | 90.00                          | 
| 201403             | 2014-Q3        | 2014-04-01T00:00:00       | 2014-06-30T23:59:59     | 132                | 107                         | 81.06                         | 90.00                                | 131                    | 99.24                    | 95.00                           | 36.19                         | 45.00                                | 127       | 96.21       | 95.00              | 127        | 96.21        | 95.00               | 101                   | 76.52                   | 90.00                          | 
| 201404             | 2014-Q4        | 2014-07-01T00:00:00       | 2014-09-30T23:59:59     | 145                | 128                         | 88.28                         | 90.00                                | 145                    | 100.00                   | 95.00                           | 37.28                         | 45.00                                | 139       | 95.86       | 95.00              | 139        | 95.86        | 95.00               | 118                   | 81.38                   | 90.00                          | 
| 201501             | 2015-Q1        | 2014-10-01T00:00:00       | 2014-12-31T23:59:50     | 121                | 96                          | 79.34                         | 90.00                                | 121                    | 100.00                   | 95.00                           | 36.49                         | 45.00                                | 118       | 97.52       | 95.00              | 115        | 95.04        | 95.00               | 88                    | 72.73                   | 90.00                          | 
| 201502             | 2015-Q2        | 2015-01-01T00:00:00       | 2015-03-31T23:59:59     | 160                | 136                         | 85.00                         | 90.00                                | 160                    | 100.00                   | 95.00                           | 37.06                         | 45.00                                | 154       | 96.25       | 95.00              | 152        | 95.00        | 95.00               | 130                   | 81.25                   | 90.00                          | 
| 201503             | 2015-Q3        | 2015-04-01T00:00:00       | 2015-06-30T23:59:59     | 155                | 122                         | 78.71                         | 90.00                                | 155                    | 100.00                   | 95.00                           | 36.07                         | 45.00                                | 146       | 94.19       | 95.00              | 146        | 94.19        | 95.00               | 107                   | 69.03                   | 90.00                          | 
| 201504             | 2015-Q4        | 2015-07-01T00:00:00       | 2015-09-30T23:59:59     | 145                | 121                         | 83.45                         | 90.00                                | 145                    | 100.00                   | 95.00                           | 37.72                         | 45.00                                | 137       | 94.48       | 95.00              | 137        | 94.48        | 95.00               | 112                   | 77.24                   | 90.00                          | 
| 201601             | 2016-Q1        | 2015-10-01T00:00:00       | 2015-12-31T23:59:50     | 139                | 109                         | 78.42                         | 90.00                                | 138                    | 99.28                    | 95.00                           | 37.32                         | 45.00                                | 134       | 96.40       | 95.00              | 136        | 97.84        | 95.00               | 103                   | 74.10                   | 90.00                          | 
| 201602             | 2016-Q2        | 2016-01-01T00:00:00       | 2016-03-31T23:59:59     | 162                | 130                         | 80.25                         | 90.00                                | 161                    | 99.38                    | 95.00                           | 37.12                         | 45.00                                | 159       | 98.15       | 95.00              | 157        | 96.91        | 95.00               | 124                   | 76.54                   | 90.00                          | 
```