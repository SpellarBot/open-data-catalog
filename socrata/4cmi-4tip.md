# EMS - Quarterly Clinical Measures - STEMI Alert

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ems-quarterly-clinical-measures-stemi-alert) |
| Metadata | [Link](https://data.austintexas.gov/api/views/4cmi-4tip) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/4cmi-4tip/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/4cmi-4tip/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 4cmi-4tip |
| Name | EMS - Quarterly Clinical Measures - STEMI Alert |
| Attribution | Austin-Travis County EMS |
| Category | Public Safety |
| Tags | ems, atcems, clinical data, clinical performance, clinical measures, patient care, stemi, alert |
| Created | 2017-01-17T22:16:33Z |
| Publication Date | 2017-01-18T16:10:13Z |

## Description

This table contains data describing ATCEMS management of STEMI Alert patients.

## Columns

```ls
| Included | Schema Type    | Field Name                           | Name                                            | Data Type     | Render Type   |
| ======== | ============== | ==================================== | =============================================== | ============= | ============= |
| Yes      | numeric metric | fiscal_quarter_key                   | Fiscal Quarter Key                              | number        | number        |
| No       |                | fiscal_quarter                       | Fiscal Quarter                                  | text          | text          |
| Yes      | time           | fiscal_quarter_start_date            | Fiscal Quarter Start Date                       | calendar_date | calendar_date |
| No       |                | fiscal_quarter_end_date              | Fiscal Quarter End Date                         | calendar_date | calendar_date |
| Yes      | numeric metric | count_stemi_alert                    | Count - STEMI Alerts                            | number        | number        |
| Yes      | numeric metric | count_scene_time_compliance          | Count - STEMI Alert Scene Interval Compliance   | number        | number        |
| Yes      | numeric metric | percent_scene_time_compliance        | Percent - STEMI Alert Scene Interval Compliance | percent       | percent       |
| Yes      | numeric metric | percent_scene_time_compliance_target | STEMI Alert Scene Interval Target               | percent       | percent       |
| Yes      | numeric metric | count_specialty_center               | Count - STEMI Center Transports                 | number        | number        |
| Yes      | numeric metric | percent_specialty_center             | Percent STEMI Center Transports                 | percent       | percent       |
| Yes      | numeric metric | percent_specialty_center_target      | STEMI Center Transports Target                  | percent       | percent       |
| Yes      | numeric metric | average_interval_call_to_door        | Average Call to Door Interval (Minutes)         | number        | number        |
| Yes      | numeric metric | average_interval_call_to_door_target | Call to Door Interval Target                    | number        | number        |
| Yes      | numeric metric | count_aspirin                        | Count ? STEMI Alert ASA Administration          | number        | number        |
| Yes      | numeric metric | percent_aspirin                      | Percent ? STEMI Alert ASA Administration        | percent       | percent       |
| Yes      | numeric metric | percent_aspirin_target               | STEMI Alert ASA Administration Target           | percent       | percent       |
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
series e:4cmi-4tip d:2013-10-01T00:00:00.000Z m:fiscal_quarter_key=201401 m:count_scene_time_compliance=58 m:percent_specialty_center_target=95 m:count_stemi_alert=67 m:average_interval_call_to_door=39.45 m:count_aspirin=63 m:percent_specialty_center=98.51 m:average_interval_call_to_door_target=45 m:percent_aspirin_target=95 m:percent_scene_time_compliance=86.57 m:percent_scene_time_compliance_target=90 m:count_specialty_center=66 m:percent_aspirin=94.03

series e:4cmi-4tip d:2014-01-01T00:00:00.000Z m:fiscal_quarter_key=201402 m:count_scene_time_compliance=56 m:percent_specialty_center_target=95 m:count_stemi_alert=81 m:average_interval_call_to_door=46.32 m:count_aspirin=76 m:percent_specialty_center=100 m:average_interval_call_to_door_target=45 m:percent_aspirin_target=95 m:percent_scene_time_compliance=69.14 m:percent_scene_time_compliance_target=90 m:count_specialty_center=81 m:percent_aspirin=93.83

series e:4cmi-4tip d:2014-04-01T00:00:00.000Z m:fiscal_quarter_key=201403 m:count_scene_time_compliance=71 m:percent_specialty_center_target=95 m:count_stemi_alert=92 m:average_interval_call_to_door=36.63 m:count_aspirin=84 m:percent_specialty_center=100 m:average_interval_call_to_door_target=45 m:percent_aspirin_target=95 m:percent_scene_time_compliance=77.17 m:percent_scene_time_compliance_target=90 m:count_specialty_center=92 m:percent_aspirin=91.3
```

## Meta Commands

```ls
metric m:fiscal_quarter_key p:integer l:"Fiscal Quarter Key" d:"Row identifier ? numeric representation of fiscal quarter in <yyyyqq> format." t:dataTypeName=number

metric m:count_stemi_alert p:integer l:"Count - STEMI Alerts" d:"Count of STEMI Alert patients." t:dataTypeName=number

metric m:count_scene_time_compliance p:integer l:"Count - STEMI Alert Scene Interval Compliance" d:"Count of STEMI Alert patients with a scene interval less than 15 minutes. Scene interval starts when the first ATCEMS unit arrives at the scene, and ends when ATCEMS personnel depart the scene." t:dataTypeName=number

metric m:percent_scene_time_compliance p:float l:"Percent - STEMI Alert Scene Interval Compliance" d:"Percent of STEMI Alert patients with a scene interval less than 15 minutes." t:dataTypeName=percent

metric m:percent_scene_time_compliance_target p:float l:"STEMI Alert Scene Interval Target" d:"Target performance level for compliance with scene time goal for STEMI Alert patients." t:dataTypeName=percent

metric m:count_specialty_center p:integer l:"Count - STEMI Center Transports" d:"Count of STEMI Alert patients who are transported to a system approved STEMI center." t:dataTypeName=number

metric m:percent_specialty_center p:float l:"Percent STEMI Center Transports" d:"Percent of STEMI Alert patients who are transported to a system approved STEMI center." t:dataTypeName=percent

metric m:percent_specialty_center_target p:float l:"STEMI Center Transports Target" d:"Target specialty center transport rate for STEMI Alert patients." t:dataTypeName=percent

metric m:average_interval_call_to_door p:float l:"Average Call to Door Interval (Minutes)" d:"Average interval between first 911 call and arrival at the receiving facility for STEMI Alert patients, measured in decimal minutes (e.g. 37.7 minutes)." t:dataTypeName=number

metric m:average_interval_call_to_door_target p:float l:"Call to Door Interval Target" d:"Target for Average Call to Door Interval, in decimal minutes." t:dataTypeName=number

metric m:count_aspirin p:integer l:"Count ? STEMI Alert ASA Administration" d:"Count of STEMI Alert patients who receive aspirin." t:dataTypeName=number

metric m:percent_aspirin p:float l:"Percent ? STEMI Alert ASA Administration" d:"Percent of STEMI Alert patients who receive aspirin." t:dataTypeName=percent

metric m:percent_aspirin_target p:float l:"STEMI Alert ASA Administration Target" d:"Target performance level for aspirin administration to STEMI Alert patients." t:dataTypeName=percent

entity e:4cmi-4tip l:"EMS - Quarterly Clinical Measures - STEMI Alert" t:attribution="Austin-Travis County EMS" t:url=https://data.austintexas.gov/api/views/4cmi-4tip

property e:4cmi-4tip t:meta.view v:id=4cmi-4tip v:category="Public Safety" v:averageRating=0 v:name="EMS - Quarterly Clinical Measures - STEMI Alert" v:attribution="Austin-Travis County EMS"

property e:4cmi-4tip t:meta.view.owner v:id=4zcf-8die v:profileImageUrlMedium=/api/users/4zcf-8die/profile_images/THUMB v:profileImageUrlLarge=/api/users/4zcf-8die/profile_images/LARGE v:screenName="Austin-Travis County EMS" v:profileImageUrlSmall=/api/users/4zcf-8die/profile_images/TINY v:displayName="Austin-Travis County EMS"

property e:4cmi-4tip t:meta.view.tableauthor v:id=4zcf-8die v:profileImageUrlMedium=/api/users/4zcf-8die/profile_images/THUMB v:profileImageUrlLarge=/api/users/4zcf-8die/profile_images/LARGE v:screenName="Austin-Travis County EMS" v:profileImageUrlSmall=/api/users/4zcf-8die/profile_images/TINY v:roleName=publisher_stories v:displayName="Austin-Travis County EMS"
```

## Top Records

```ls
| fiscal_quarter_key | fiscal_quarter | fiscal_quarter_start_date | fiscal_quarter_end_date | count_stemi_alert | count_scene_time_compliance | percent_scene_time_compliance | percent_scene_time_compliance_target | count_specialty_center | percent_specialty_center | percent_specialty_center_target | average_interval_call_to_door | average_interval_call_to_door_target | count_aspirin | percent_aspirin | percent_aspirin_target | 
| ================== | ============== | ========================= | ======================= | ================= | =========================== | ============================= | ==================================== | ====================== | ======================== | =============================== | ============================= | ==================================== | ============= | =============== | ====================== | 
| 201401             | 2014-Q1        | 2013-10-01T00:00:00       | 2013-12-31T23:59:50     | 67                | 58                          | 86.57                         | 90.00                                | 66                     | 98.51                    | 95.00                           | 39.45                         | 45.00                                | 63            | 94.03           | 95.00                  | 
| 201402             | 2014-Q2        | 2014-01-01T00:00:00       | 2014-03-31T23:59:59     | 81                | 56                          | 69.14                         | 90.00                                | 81                     | 100.00                   | 95.00                           | 46.32                         | 45.00                                | 76            | 93.83           | 95.00                  | 
| 201403             | 2014-Q3        | 2014-04-01T00:00:00       | 2014-06-30T23:59:59     | 92                | 71                          | 77.17                         | 90.00                                | 92                     | 100.00                   | 95.00                           | 36.63                         | 45.00                                | 84            | 91.30           | 95.00                  | 
| 201404             | 2014-Q4        | 2014-07-01T00:00:00       | 2014-09-30T23:59:59     | 70                | 42                          | 60.00                         | 90.00                                | 70                     | 100.00                   | 95.00                           | 41.31                         | 45.00                                | 59            | 84.29           | 95.00                  | 
| 201501             | 2015-Q1        | 2014-10-01T00:00:00       | 2014-12-31T23:59:50     | 52                | 35                          | 67.31                         | 90.00                                | 52                     | 100.00                   | 95.00                           | 39.53                         | 45.00                                | 47            | 90.38           | 95.00                  | 
| 201502             | 2015-Q2        | 2015-01-01T00:00:00       | 2015-03-31T23:59:59     | 82                | 56                          | 68.29                         | 90.00                                | 82                     | 100.00                   | 95.00                           | 40.45                         | 45.00                                | 69            | 84.15           | 95.00                  | 
| 201503             | 2015-Q3        | 2015-04-01T00:00:00       | 2015-06-30T23:59:59     | 76                | 58                          | 76.32                         | 90.00                                | 76                     | 100.00                   | 95.00                           | 40.85                         | 45.00                                | 68            | 89.47           | 95.00                  | 
| 201504             | 2015-Q4        | 2015-07-01T00:00:00       | 2015-09-30T23:59:59     | 80                | 57                          | 71.25                         | 90.00                                | 80                     | 100.00                   | 95.00                           | 37.66                         | 45.00                                | 74            | 92.50           | 95.00                  | 
| 201601             | 2016-Q1        | 2015-10-01T00:00:00       | 2015-12-31T23:59:50     | 63                | 46                          | 73.02                         | 90.00                                | 63                     | 100.00                   | 95.00                           | 40.85                         | 45.00                                | 54            | 85.71           | 95.00                  | 
| 201602             | 2016-Q2        | 2016-01-01T00:00:00       | 2016-03-31T23:59:59     | 63                | 44                          | 69.84                         | 90.00                                | 62                     | 98.41                    | 95.00                           | 37.14                         | 45.00                                | 54            | 85.71           | 95.00                  | 
```