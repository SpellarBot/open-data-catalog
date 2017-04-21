# EMS - Quarterly OMD Clinical Performance Indicators

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ems-quarterly-omd-clinical-performance-indicators) |
| Metadata | [Link](https://data.austintexas.gov/api/views/2cxe-9vbj) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/2cxe-9vbj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/2cxe-9vbj/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 2cxe-9vbj |
| Name | EMS - Quarterly OMD Clinical Performance Indicators |
| Attribution | Austin-Travis County EMS |
| Category | Public Safety |
| Tags | ems, atcems, clinical data, clinical performance, clinical measures, patient care, stroke, stemi, trauma, alert, cpi, omd |
| Created | 2017-01-17T22:20:43Z |
| Publication Date | 2017-01-18T16:34:52Z |

## Description

This table contains data related to Clinical Performance Indicators (CPIs) used by the City of Austin/Travis County EMS System Office of the Medical Director (OMD).  More information on CPIs can be found at http://www.austintexas.gov/page/performance-improvement.

## Columns

```ls
| Included | Schema Type    | Field Name                                 | Name                                               | Data Type     | Render Type   |
| ======== | ============== | ========================================== | ================================================== | ============= | ============= |
| Yes      | numeric metric | fiscal_quarter_key                         | Fiscal Quarter Key                                 | number        | number        |
| No       |                | fiscal_quarter                             | Fiscal Quarter                                     | text          | text          |
| Yes      | time           | fiscal_quarter_start_date                  | Fiscal Quarter Start Date                          | calendar_date | calendar_date |
| No       |                | fiscal_quarter_end_date                    | Fiscal Quarter End Date                            | calendar_date | calendar_date |
| Yes      | numeric metric | cpi_01_count                               | Count - Trauma Alerts                              | number        | number        |
| Yes      | numeric metric | cpi_01_count_goal_met                      | Count - Trauma Alert Scene Interval Compliance     | number        | number        |
| Yes      | numeric metric | cpi_01_percent_goal_met                    | Percent - Trauma Alert Scene Interval Compliance   | percent       | percent       |
| Yes      | numeric metric | cpi_01_percent_goal_met_target             | Trauma Alert Scene Interval Compliance Target      | percent       | percent       |
| Yes      | numeric metric | cpi_01_percentile_90_interval_scene        | 90th Percentile Trauma Scene Time                  | number        | number        |
| Yes      | numeric metric | cpi_01_percentile_90_interval_scene_target | 90th Percentile Trauma Alert Scene Interval Target | number        | number        |
| Yes      | numeric metric | cpi_02_count                               | Count - Stroke Alerts                              | number        | number        |
| Yes      | numeric metric | cpi_02_count_goal_met                      | Count - Stroke Alert Scene Interval Compliance     | number        | number        |
| Yes      | numeric metric | cpi_02_percent_goal_met                    | Percent - Stroke Alert Scene Interval Compliance   | percent       | percent       |
| Yes      | numeric metric | cpi_02_percent_goal_met_target             | Stroke Alert Scene Interval Compliance Target      | percent       | percent       |
| Yes      | numeric metric | cpi_02_percentile_90_interval_scene        | 90th Percentile Stroke Alert Scene Interval        | number        | number        |
| Yes      | numeric metric | cpi_02_percentile_90_interval_scene_target | 90th Percentile Stroke Alert Scene Interval Target | number        | number        |
| Yes      | numeric metric | cpi_03_count                               | Count - STEMI Alerts                               | number        | number        |
| Yes      | numeric metric | cpi_03_count_goal_met                      | Count - STEMI Alert Scene Interval Compliance      | number        | number        |
| Yes      | numeric metric | cpi_03_percent_goal_met                    | Percent - STEMI Alert Scene Interval Compliance    | percent       | percent       |
| Yes      | numeric metric | cpi_03_percent_goal_met_target             | STEMI Alert Scene Interval Compliance Target       | percent       | percent       |
| Yes      | numeric metric | cpi_03_percentile_90_interval_scene        | 90th Percentile STEMI Alert Scene Interval         | number        | number        |
| Yes      | numeric metric | cpi_03_percentile_90_interval_scene_target | 90th Percentile STEMI Alert Scene Interval Target  | number        | number        |
| Yes      | numeric metric | cpi_04_count                               | Count ? ACS Patients                               | number        | number        |
| Yes      | numeric metric | cpi_04_count_goal_met                      | Count ? ACS Patient ASA Administration             | number        | number        |
| Yes      | numeric metric | cpi_04_percent_goal_met                    | Percent ? ACS Patient ASA Administration           | percent       | percent       |
| Yes      | numeric metric | cpi_04_percent_goal_met_target             | ACS Patient ASA Administration Target              | percent       | percent       |
| Yes      | numeric metric | cpi_05_count                               | Count - AMS Patients                               | number        | number        |
| Yes      | numeric metric | cpi_05_count_goal_met                      | Count - BGL Test for AMS Patients                  | number        | number        |
| Yes      | numeric metric | cpi_05_percent_goal_met                    | Percent - BGL Test for AMS Patients                | percent       | percent       |
| Yes      | numeric metric | cpi_05_percent_goal_met_target             | AMS Patient BGL Test Target                        | percent       | percent       |
| Yes      | numeric metric | cpi_06_count                               | Count - Seizure Patients                           | number        | number        |
| Yes      | numeric metric | cpi_06_count_goal_met                      | Count - BGL Test for Seizure Patients              | number        | number        |
| Yes      | numeric metric | cpi_06_percent_goal_met                    | Percent - BGL Test for Seizure Patients            | percent       | percent       |
| Yes      | numeric metric | cpi_06_percent_goal_met_target             | Seizure Patient BGL Test Target                    | percent       | percent       |
| Yes      | numeric metric | cpi_07_count                               | Count - Stroke Patients                            | number        | number        |
| Yes      | numeric metric | cpi_07_count_goal_met                      | Count - BGL Test for Stroke Patients               | number        | number        |
| Yes      | numeric metric | cpi_07_percent_goal_met                    | Percent - BGL Test for Stroke Patients             | percent       | percent       |
| Yes      | numeric metric | cpi_07_percent_goal_met_target             | Stroke Patient BGL Test Target                     | percent       | percent       |
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
series e:2cxe-9vbj d:2013-10-01T00:00:00.000Z m:cpi_06_count_goal_met=815 m:cpi_05_count_goal_met=1380 m:cpi_07_percent_goal_met=90.59 m:cpi_02_percent_goal_met=83.87 m:cpi_07_count=170 m:cpi_02_count=124 m:cpi_03_percent_goal_met_target=90 m:cpi_01_count=169 m:cpi_01_percent_goal_met_target=90 m:cpi_06_count=918 m:cpi_02_percent_goal_met_target=90 m:cpi_02_count_goal_met=104 m:cpi_02_percentile_90_interval_scene=17.19 m:cpi_01_count_goal_met=146 m:cpi_05_percent_goal_met=92.8 m:cpi_01_percent_goal_met=86.39 m:cpi_02_percentile_90_interval_scene_target=15 m:fiscal_quarter_key=201401 m:cpi_03_count=67 m:cpi_07_percent_goal_met_target=95 m:cpi_03_percentile_90_interval_scene_target=15 m:cpi_01_percentile_90_interval_scene=17.25 m:cpi_04_percent_goal_met_target=95 m:cpi_04_count_goal_met=607 m:cpi_05_percent_goal_met_target=95 m:cpi_03_percentile_90_interval_scene=22.88 m:cpi_03_count_goal_met=58 m:cpi_04_count=638 m:cpi_07_count_goal_met=154 m:cpi_06_percent_goal_met=88.78 m:cpi_05_count=1487 m:cpi_03_percent_goal_met=86.57 m:cpi_01_percentile_90_interval_scene_target=15 m:cpi_04_percent_goal_met=95.14 m:cpi_06_percent_goal_met_target=95

series e:2cxe-9vbj d:2014-01-01T00:00:00.000Z m:cpi_06_count_goal_met=816 m:cpi_05_count_goal_met=1317 m:cpi_07_percent_goal_met=94.68 m:cpi_02_percent_goal_met=79.14 m:cpi_07_count=188 m:cpi_02_count=139 m:cpi_03_percent_goal_met_target=90 m:cpi_01_count=144 m:cpi_01_percent_goal_met_target=90 m:cpi_06_count=896 m:cpi_02_percent_goal_met_target=90 m:cpi_02_count_goal_met=110 m:cpi_02_percentile_90_interval_scene=18.87 m:cpi_01_count_goal_met=128 m:cpi_05_percent_goal_met=91.52 m:cpi_01_percent_goal_met=88.89 m:cpi_02_percentile_90_interval_scene_target=15 m:fiscal_quarter_key=201402 m:cpi_03_count=81 m:cpi_07_percent_goal_met_target=95 m:cpi_03_percentile_90_interval_scene_target=15 m:cpi_01_percentile_90_interval_scene=17.45 m:cpi_04_percent_goal_met_target=95 m:cpi_04_count_goal_met=615 m:cpi_05_percent_goal_met_target=95 m:cpi_03_percentile_90_interval_scene=27.25 m:cpi_03_count_goal_met=56 m:cpi_04_count=629 m:cpi_07_count_goal_met=178 m:cpi_06_percent_goal_met=91.07 m:cpi_05_count=1439 m:cpi_03_percent_goal_met=69.14 m:cpi_01_percentile_90_interval_scene_target=15 m:cpi_04_percent_goal_met=97.77 m:cpi_06_percent_goal_met_target=95

series e:2cxe-9vbj d:2014-04-01T00:00:00.000Z m:cpi_06_count_goal_met=945 m:cpi_05_count_goal_met=1410 m:cpi_07_percent_goal_met=94.15 m:cpi_02_percent_goal_met=81.06 m:cpi_07_count=171 m:cpi_02_count=132 m:cpi_03_percent_goal_met_target=90 m:cpi_01_count=166 m:cpi_01_percent_goal_met_target=90 m:cpi_06_count=989 m:cpi_02_percent_goal_met_target=90 m:cpi_02_count_goal_met=107 m:cpi_02_percentile_90_interval_scene=18.57 m:cpi_01_count_goal_met=151 m:cpi_05_percent_goal_met=92.4 m:cpi_01_percent_goal_met=90.96 m:cpi_02_percentile_90_interval_scene_target=15 m:fiscal_quarter_key=201403 m:cpi_03_count=92 m:cpi_07_percent_goal_met_target=95 m:cpi_03_percentile_90_interval_scene_target=15 m:cpi_01_percentile_90_interval_scene=15.03 m:cpi_04_percent_goal_met_target=95 m:cpi_04_count_goal_met=649 m:cpi_05_percent_goal_met_target=95 m:cpi_03_percentile_90_interval_scene=21.51 m:cpi_03_count_goal_met=71 m:cpi_04_count=697 m:cpi_07_count_goal_met=161 m:cpi_06_percent_goal_met=95.55 m:cpi_05_count=1526 m:cpi_03_percent_goal_met=77.17 m:cpi_01_percentile_90_interval_scene_target=15 m:cpi_04_percent_goal_met=93.11 m:cpi_06_percent_goal_met_target=95
```

## Meta Commands

```ls
metric m:fiscal_quarter_key p:integer l:"Fiscal Quarter Key" d:"Row identifier ? numeric representation of fiscal quarter in <yyyyqq> format." t:dataTypeName=number

metric m:cpi_01_count p:integer l:"Count - Trauma Alerts" d:"Count of Trauma Alert patients. In this setting, ?Trauma Alert? refers to injured patients who meet Physiological or Anatomical criteria for transport to a Trauma Center per City of Austin/Travis County EMS System Clinical Operating Guidelines." t:dataTypeName=number

metric m:cpi_01_count_goal_met p:integer l:"Count - Trauma Alert Scene Interval Compliance" d:"Count of Trauma Alert patients with a scene interval less than 15 minutes. Scene interval starts when the first ATCEMS unit arrives on scene, and ends when ATCEMS personnel depart the scene." t:dataTypeName=number

metric m:cpi_01_percent_goal_met p:float l:"Percent - Trauma Alert Scene Interval Compliance" d:"Percent of Trauma Alert patients with a scene interval less than 15 minutes." t:dataTypeName=percent

metric m:cpi_01_percent_goal_met_target p:float l:"Trauma Alert Scene Interval Compliance Target" d:"Target performance level for compliance with scene interval goal for Trauma Alert patients." t:dataTypeName=percent

metric m:cpi_01_percentile_90_interval_scene p:float l:"90th Percentile Trauma Scene Time" d:"90th percentile scene interval for included Trauma Alert patients, measured in decimal minutes. Scene interval starts when the first ATCEMS unit arrives on scene, and ends when ATCEMS personnel depart the scene." t:dataTypeName=number

metric m:cpi_01_percentile_90_interval_scene_target p:float l:"90th Percentile Trauma Alert Scene Interval Target" d:"Target performance level for 90th percentile scene interval for Trauma Alert patients, measured in decimal minutes." t:dataTypeName=number

metric m:cpi_02_count p:integer l:"Count - Stroke Alerts" d:"Count of Stroke Alert patients. Not all stroke patients meet criteria for calling a Stroke Alert, so this group will be smaller than the group for CPI 7 ? Blood Glucose Test for Stroke Patients." t:dataTypeName=number

metric m:cpi_02_count_goal_met p:integer l:"Count - Stroke Alert Scene Interval Compliance" d:"Count of Stroke Alert patients with a scene interval less than 15 minutes. Scene interval starts when the first ATCEMS unit arrives on scene, and ends when ATCEMS personnel depart the scene." t:dataTypeName=number

metric m:cpi_02_percent_goal_met p:float l:"Percent - Stroke Alert Scene Interval Compliance" d:"Percent of Stroke Alert patients with a scene interval less than 15 minutes." t:dataTypeName=percent

metric m:cpi_02_percent_goal_met_target p:float l:"Stroke Alert Scene Interval Compliance Target" d:"Target performance level for compliance with scene interval goal for Stroke Alert patients." t:dataTypeName=percent

metric m:cpi_02_percentile_90_interval_scene p:float l:"90th Percentile Stroke Alert Scene Interval" d:"90th percentile scene interval for included Stroke Alert patients, measured in decimal minutes. Scene interval starts when the first ATCEMS unit arrives on scene, and ends when ATCEMS personnel depart the scene." t:dataTypeName=number

metric m:cpi_02_percentile_90_interval_scene_target p:float l:"90th Percentile Stroke Alert Scene Interval Target" d:"Target performance level for 90th percentile scene interval for Stroke Alert patients, measured in decimal minutes." t:dataTypeName=number

metric m:cpi_03_count p:integer l:"Count - STEMI Alerts" d:"Count of STEMI Alert patients. STEMI Alert patients are a subset of ACS patients; therefore, this count will be smaller than the count for CPI 4 ? Aspirin Administration to ACS Patients." t:dataTypeName=number

metric m:cpi_03_count_goal_met p:integer l:"Count - STEMI Alert Scene Interval Compliance" d:"Count of STEMI Alert patients with a scene interval less than 15 minutes. Scene interval starts when the first ATCEMS unit arrives on scene, and ends when ATCEMS personnel depart the scene." t:dataTypeName=number

metric m:cpi_03_percent_goal_met p:float l:"Percent - STEMI Alert Scene Interval Compliance" d:"Percent of STEMI Alert patients with a scene interval less than 15 minutes." t:dataTypeName=percent

metric m:cpi_03_percent_goal_met_target p:float l:"STEMI Alert Scene Interval Compliance Target" d:"Target performance level for compliance with scene interval goal for STEMI Alert patients." t:dataTypeName=percent

metric m:cpi_03_percentile_90_interval_scene p:float l:"90th Percentile STEMI Alert Scene Interval" d:"90th percentile scene interval for included STEMI Alert patients, measured in decimal minutes. Scene interval starts when the first ATCEMS unit arrives on scene, and ends when ATCEMS personnel depart the scene." t:dataTypeName=number

metric m:cpi_03_percentile_90_interval_scene_target p:float l:"90th Percentile STEMI Alert Scene Interval Target" d:"Target performance level for 90th percentile scene interval for STEMI Alert patients, measured in decimal minutes." t:dataTypeName=number

metric m:cpi_04_count p:integer l:"Count ? ACS Patients" d:"Count of Acute Coronary Syndrome (ACS) patients. This includes patients with a Primary Impression of ?Acute Coronary Syndrome? or ?STEMI,? and patients for whom a STEMI Alert is called. This group will be larger than the group for CPI 3 ? Scene interval for STEMI Alerts." t:dataTypeName=number

metric m:cpi_04_count_goal_met p:integer l:"Count ? ACS Patient ASA Administration" d:"Count of ACS patients who receive aspirin (ASA)." t:dataTypeName=number

metric m:cpi_04_percent_goal_met p:float l:"Percent ? ACS Patient ASA Administration" d:"Percent of ACS patients who receive aspirin." t:dataTypeName=percent

metric m:cpi_04_percent_goal_met_target p:float l:"ACS Patient ASA Administration Target" d:"Target performance level for aspirin administration to ACS patients." t:dataTypeName=percent

metric m:cpi_05_count p:integer l:"Count - AMS Patients" d:"Count of patients with a primary impression suggestive of Altered Mental Status (AMS)." t:dataTypeName=number

metric m:cpi_05_count_goal_met p:integer l:"Count - BGL Test for AMS Patients" d:"Count of AMS patients who receive a blood glucose level (BGL) assessment." t:dataTypeName=number

metric m:cpi_05_percent_goal_met p:float l:"Percent - BGL Test for AMS Patients" d:"Percent of AMS patients who receive a blood glucose level assessment." t:dataTypeName=percent

metric m:cpi_05_percent_goal_met_target p:float l:"AMS Patient BGL Test Target" d:"Target performance level for blood glucose assessment of AMS patients." t:dataTypeName=percent

metric m:cpi_06_count p:integer l:"Count - Seizure Patients" d:"Count of patients with a primary impression of ?Seizure ? Other Convulsions,? ?Seizure Febrile,? or ?Seizure Postictal State.?" t:dataTypeName=number

metric m:cpi_06_count_goal_met p:integer l:"Count - BGL Test for Seizure Patients" d:"Count of seizure patients who receive a blood glucose level assessment." t:dataTypeName=number

metric m:cpi_06_percent_goal_met p:float l:"Percent - BGL Test for Seizure Patients" t:dataTypeName=percent

metric m:cpi_06_percent_goal_met_target p:float l:"Seizure Patient BGL Test Target" d:"Target performance level for blood glucose assessment of seizure patients." t:dataTypeName=percent

metric m:cpi_07_count p:integer l:"Count - Stroke Patients" d:"Count of stroke patients. This definition includes all patients with Primary Impression of stroke, regardless of whether the patient qualified as a Stroke Alert, as well as those for whom a Stroke Alert is called. This group will be larger than the group for CPI 2?Scene interval for Stroke Alerts." t:dataTypeName=number

metric m:cpi_07_count_goal_met p:integer l:"Count - BGL Test for Stroke Patients" d:"Count of stroke patients who receive a blood glucose level assessment." t:dataTypeName=number

metric m:cpi_07_percent_goal_met p:float l:"Percent - BGL Test for Stroke Patients" d:"Percent of stroke patients who receive a blood glucose level assessment." t:dataTypeName=percent

metric m:cpi_07_percent_goal_met_target p:float l:"Stroke Patient BGL Test Target" d:"Target performance level for blood glucose assessment of stroke patients." t:dataTypeName=percent

entity e:2cxe-9vbj l:"EMS - Quarterly OMD Clinical Performance Indicators" t:attribution="Austin-Travis County EMS" t:url=https://data.austintexas.gov/api/views/2cxe-9vbj

property e:2cxe-9vbj t:meta.view v:id=2cxe-9vbj v:category="Public Safety" v:averageRating=0 v:name="EMS - Quarterly OMD Clinical Performance Indicators" v:attribution="Austin-Travis County EMS"

property e:2cxe-9vbj t:meta.view.owner v:id=4zcf-8die v:profileImageUrlMedium=/api/users/4zcf-8die/profile_images/THUMB v:profileImageUrlLarge=/api/users/4zcf-8die/profile_images/LARGE v:screenName="Austin-Travis County EMS" v:profileImageUrlSmall=/api/users/4zcf-8die/profile_images/TINY v:displayName="Austin-Travis County EMS"

property e:2cxe-9vbj t:meta.view.tableauthor v:id=4zcf-8die v:profileImageUrlMedium=/api/users/4zcf-8die/profile_images/THUMB v:profileImageUrlLarge=/api/users/4zcf-8die/profile_images/LARGE v:screenName="Austin-Travis County EMS" v:profileImageUrlSmall=/api/users/4zcf-8die/profile_images/TINY v:roleName=publisher_stories v:displayName="Austin-Travis County EMS"
```

## Top Records

```ls
| fiscal_quarter_key | fiscal_quarter | fiscal_quarter_start_date | fiscal_quarter_end_date | cpi_01_count | cpi_01_count_goal_met | cpi_01_percent_goal_met | cpi_01_percent_goal_met_target | cpi_01_percentile_90_interval_scene | cpi_01_percentile_90_interval_scene_target | cpi_02_count | cpi_02_count_goal_met | cpi_02_percent_goal_met | cpi_02_percent_goal_met_target | cpi_02_percentile_90_interval_scene | cpi_02_percentile_90_interval_scene_target | cpi_03_count | cpi_03_count_goal_met | cpi_03_percent_goal_met | cpi_03_percent_goal_met_target | cpi_03_percentile_90_interval_scene | cpi_03_percentile_90_interval_scene_target | cpi_04_count | cpi_04_count_goal_met | cpi_04_percent_goal_met | cpi_04_percent_goal_met_target | cpi_05_count | cpi_05_count_goal_met | cpi_05_percent_goal_met | cpi_05_percent_goal_met_target | cpi_06_count | cpi_06_count_goal_met | cpi_06_percent_goal_met | cpi_06_percent_goal_met_target | cpi_07_count | cpi_07_count_goal_met | cpi_07_percent_goal_met | cpi_07_percent_goal_met_target | 
| ================== | ============== | ========================= | ======================= | ============ | ===================== | ======================= | ============================== | =================================== | ========================================== | ============ | ===================== | ======================= | ============================== | =================================== | ========================================== | ============ | ===================== | ======================= | ============================== | =================================== | ========================================== | ============ | ===================== | ======================= | ============================== | ============ | ===================== | ======================= | ============================== | ============ | ===================== | ======================= | ============================== | ============ | ===================== | ======================= | ============================== | 
| 201401             | 2014-Q1        | 2013-10-01T00:00:00       | 2013-12-31T23:59:50     | 169          | 146                   | 86.39                   | 90.00                          | 17.25                               | 15.00                                      | 124          | 104                   | 83.87                   | 90.00                          | 17.19                               | 15.00                                      | 67           | 58                    | 86.57                   | 90.00                          | 22.88                               | 15.00                                      | 638          | 607                   | 95.14                   | 95.00                          | 1487         | 1380                  | 92.80                   | 95.00                          | 918          | 815                   | 88.78                   | 95.00                          | 170          | 154                   | 90.59                   | 95.00                          | 
| 201402             | 2014-Q2        | 2014-01-01T00:00:00       | 2014-03-31T23:59:59     | 144          | 128                   | 88.89                   | 90.00                          | 17.45                               | 15.00                                      | 139          | 110                   | 79.14                   | 90.00                          | 18.87                               | 15.00                                      | 81           | 56                    | 69.14                   | 90.00                          | 27.25                               | 15.00                                      | 629          | 615                   | 97.77                   | 95.00                          | 1439         | 1317                  | 91.52                   | 95.00                          | 896          | 816                   | 91.07                   | 95.00                          | 188          | 178                   | 94.68                   | 95.00                          | 
| 201403             | 2014-Q3        | 2014-04-01T00:00:00       | 2014-06-30T23:59:59     | 166          | 151                   | 90.96                   | 90.00                          | 15.03                               | 15.00                                      | 132          | 107                   | 81.06                   | 90.00                          | 18.57                               | 15.00                                      | 92           | 71                    | 77.17                   | 90.00                          | 21.51                               | 15.00                                      | 697          | 649                   | 93.11                   | 95.00                          | 1526         | 1410                  | 92.40                   | 95.00                          | 989          | 945                   | 95.55                   | 95.00                          | 171          | 161                   | 94.15                   | 95.00                          | 
| 201404             | 2014-Q4        | 2014-07-01T00:00:00       | 2014-09-30T23:59:59     | 171          | 149                   | 87.13                   | 90.00                          | 16.27                               | 15.00                                      | 145          | 128                   | 88.28                   | 90.00                          | 16.13                               | 15.00                                      | 70           | 42                    | 60.00                   | 90.00                          | 25.57                               | 15.00                                      | 597          | 564                   | 94.47                   | 95.00                          | 1548         | 1419                  | 91.67                   | 95.00                          | 944          | 912                   | 96.61                   | 95.00                          | 200          | 187                   | 93.50                   | 95.00                          | 
| 201501             | 2015-Q1        | 2014-10-01T00:00:00       | 2014-12-31T23:59:50     | 161          | 149                   | 92.55                   | 90.00                          | 14.91                               | 15.00                                      | 121          | 96                    | 79.34                   | 90.00                          | 19.55                               | 15.00                                      | 52           | 35                    | 67.31                   | 90.00                          | 31.21                               | 15.00                                      | 556          | 515                   | 92.63                   | 95.00                          | 1544         | 1425                  | 92.29                   | 95.00                          | 978          | 895                   | 91.51                   | 95.00                          | 183          | 176                   | 96.17                   | 95.00                          | 
| 201502             | 2015-Q2        | 2015-01-01T00:00:00       | 2015-03-31T23:59:59     | 156          | 138                   | 88.46                   | 90.00                          | 18.21                               | 15.00                                      | 160          | 136                   | 85.00                   | 90.00                          | 18.77                               | 15.00                                      | 82           | 56                    | 68.29                   | 90.00                          | 25.50                               | 15.00                                      | 589          | 527                   | 89.47                   | 95.00                          | 1686         | 1586                  | 94.07                   | 95.00                          | 1050         | 996                   | 94.86                   | 95.00                          | 216          | 207                   | 95.83                   | 95.00                          | 
| 201503             | 2015-Q3        | 2015-04-01T00:00:00       | 2015-06-30T23:59:59     | 152          | 128                   | 84.21                   | 90.00                          | 17.91                               | 15.00                                      | 155          | 122                   | 78.71                   | 90.00                          | 18.52                               | 15.00                                      | 76           | 58                    | 76.32                   | 90.00                          | 27.25                               | 15.00                                      | 604          | 576                   | 95.36                   | 95.00                          | 1907         | 1790                  | 93.86                   | 95.00                          | 1058         | 973                   | 91.97                   | 95.00                          | 226          | 210                   | 92.92                   | 95.00                          | 
| 201504             | 2015-Q4        | 2015-07-01T00:00:00       | 2015-09-30T23:59:59     | 175          | 158                   | 90.29                   | 90.00                          | 15.88                               | 15.00                                      | 145          | 121                   | 83.45                   | 90.00                          | 18.68                               | 15.00                                      | 80           | 57                    | 71.25                   | 90.00                          | 25.65                               | 15.00                                      | 627          | 595                   | 94.90                   | 95.00                          | 1850         | 1740                  | 94.05                   | 95.00                          | 1119         | 1089                  | 97.32                   | 95.00                          | 224          | 205                   | 91.52                   | 95.00                          | 
| 201601             | 2016-Q1        | 2015-10-01T00:00:00       | 2015-12-31T23:59:50     | 137          | 129                   | 94.16                   | 90.00                          | 14.62                               | 15.00                                      | 139          | 109                   | 78.42                   | 90.00                          | 20.28                               | 15.00                                      | 63           | 46                    | 73.02                   | 90.00                          | 24.49                               | 15.00                                      | 477          | 451                   | 94.55                   | 95.00                          | 1580         | 1474                  | 93.29                   | 95.00                          | 959          | 941                   | 98.12                   | 95.00                          | 225          | 208                   | 92.44                   | 95.00                          | 
| 201602             | 2016-Q2        | 2016-01-01T00:00:00       | 2016-03-31T23:59:59     | 155          | 139                   | 89.68                   | 90.00                          | 16.08                               | 15.00                                      | 162          | 130                   | 80.25                   | 90.00                          | 19.35                               | 15.00                                      | 63           | 44                    | 69.84                   | 90.00                          | 24.92                               | 15.00                                      | 517          | 489                   | 94.58                   | 95.00                          | 1425         | 1353                  | 94.95                   | 95.00                          | 926          | 899                   | 97.08                   | 95.00                          | 239          | 234                   | 97.91                   | 95.00                          | 
```