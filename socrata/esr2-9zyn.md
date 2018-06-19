# Veterans Health Administration Patient Safety Indicators Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/veterans-health-administration-patient-safety-indicators-data) |
| Metadata | [Link](https://data.medicare.gov/api/views/esr2-9zyn) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/esr2-9zyn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/esr2-9zyn/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | esr2-9zyn |
| Name | Veterans Health Administration Patient Safety Indicators Data |
| Category | Hospital Compare |
| Tags | veterans |
| Created | 2016-11-08T17:37:01Z |
| Publication Date | 2016-12-19T02:13:07Z |

## Description

A list of VHA hospitals with data on the Agency for Healthcare Research and Quality (AHRQ) Patient Safety Indicators (PSIs). These indicators provide information on potential in hospital complications and adverse events following surgeries and procedures*.*

## Columns

```ls
| Included | Schema Type    | Field Name                            | Name                                  | Data Type | Render Type |
| ======== | ============== | ===================================== | ===================================== | ========= | =========== |
| No       | time           | :updated_at                           | updated_at                            | meta_data | meta_data   |
| Yes      | series tag     | ccn                                   | CCN#                                  | text      | text        |
| Yes      | series tag     | vha_facility                          | VHA Facility                          | text      | text        |
| No       |                | address                               | Address                               | text      | text        |
| Yes      | series tag     | city                                  | City                                  | text      | text        |
| Yes      | series tag     | state                                 | State                                 | text      | text        |
| Yes      | series tag     | zip_code                              | Zip Code                              | text      | text        |
| Yes      | series tag     | measureid                             | MeasureID                             | text      | text        |
| Yes      | series tag     | technical_measure_title               | Technical Measure Title               | text      | text        |
| Yes      | series tag     | measure_as_posted_on_hospital_compare | Measure as Posted on Hospital Compare | text      | text        |
| Yes      | numeric metric | observed_rate                         | Observed Rate                         | number    | text        |
| Yes      | numeric metric | expected_rate                         | Expected Rate                         | number    | text        |
| Yes      | numeric metric | risk_adjusted_rate                    | Risk Adjusted Rate                    | number    | text        |
| Yes      | numeric metric | 95_confidence_lower_limit             | 95% Confidence Lower Limit            | number    | text        |
| Yes      | numeric metric | 95_confidence_lower_upper_limit       | 95% Confidence Lower Upper Limit      | number    | text        |
| No       |                | footnotes                             | Footnotes                             | text      | text        |
| No       |                | date_range                            | Date Range                            | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address,footnotes,date_range
```

## Data Commands

```ls
series e:esr2-9zyn d:2016-11-24T16:56:53.000Z t:zip_code=35233 t:ccn=01014F t:state=AL t:measureid=PSI-3 t:vha_facility="BIRMINGHAM VA MEDICAL CENTER" t:measure_as_posted_on_hospital_compare="Pressure Ulcer Rate (PSI03)" t:city=BIRMINGHAM t:technical_measure_title="Patient Safety Indicator 03 Pressure Ulcer Rate" m:expected_rate=0.59 m:95_confidence_lower_upper_limit=0.99 m:observed_rate=0.44 m:95_confidence_lower_limit=0 m:risk_adjusted_rate=0.38

series e:esr2-9zyn d:2016-11-24T16:56:53.000Z t:zip_code=35233 t:ccn=01014F t:state=AL t:measureid=PSI-4 t:vha_facility="BIRMINGHAM VA MEDICAL CENTER" t:measure_as_posted_on_hospital_compare="Inpatient Surgical Deaths (PSI04)" t:city=BIRMINGHAM t:technical_measure_title="Patient Safety Indicator 04 Death Rate among Surgical Inpatients with Serious Treatable Complications" m:expected_rate=122.97 m:95_confidence_lower_upper_limit=148.13 m:observed_rate=94.83 m:95_confidence_lower_limit=36.18 m:risk_adjusted_rate=92.16

series e:esr2-9zyn d:2016-11-24T16:56:53.000Z t:zip_code=35233 t:ccn=01014F t:state=AL t:measureid=PSI-6 t:vha_facility="BIRMINGHAM VA MEDICAL CENTER" t:measure_as_posted_on_hospital_compare="Collapsed lung due to medical treatment  (PSI06)" t:city=BIRMINGHAM t:technical_measure_title="Patient Safety Indicator 06 Iatrogenic Pneumothorax Rate" m:expected_rate=0.27 m:95_confidence_lower_upper_limit=0.73 m:observed_rate=0.32 m:95_confidence_lower_limit=0.08 m:risk_adjusted_rate=0.4
```

## Meta Commands

```ls
entity e:esr2-9zyn l:"Veterans Health Administration Patient Safety Indicators Data" t:url=https://data.medicare.gov/api/views/esr2-9zyn

property e:esr2-9zyn t:meta.view v:id=esr2-9zyn v:category="Hospital Compare" v:averageRating=0 v:name="Veterans Health Administration Patient Safety Indicators Data"

property e:esr2-9zyn t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:esr2-9zyn t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:esr2-9zyn t:meta.view.metadata.custom_fields.common_core v:Bureau_Code=009:38
```

## Top Records

```ls
| :updated_at | ccn    | vha_facility                 | address               | city       | state | zip_code | measureid | technical_measure_title                                                                               | measure_as_posted_on_hospital_compare                          | observed_rate | expected_rate | risk_adjusted_rate | 95_confidence_lower_limit | 95_confidence_lower_upper_limit | footnotes | date_range                    | 
| =========== | ====== | ============================ | ===================== | ========== | ===== | ======== | ========= | ===================================================================================================== | ============================================================== | ============= | ============= | ================== | ========================= | =============================== | ========= | ============================= | 
| 1480006613  | 01014F | BIRMINGHAM VA MEDICAL CENTER | 700 SOUTH 19TH STREET | BIRMINGHAM | AL    | 35233    | PSI-3     | Patient Safety Indicator 03 Pressure Ulcer Rate                                                       | Pressure Ulcer Rate (PSI03)                                    | 0.44          | 0.59          | 0.38               | 0                         | 0.99                            |           | October 2012 ? September 2015 | 
| 1480006613  | 01014F | BIRMINGHAM VA MEDICAL CENTER | 700 SOUTH 19TH STREET | BIRMINGHAM | AL    | 35233    | PSI-4     | Patient Safety Indicator 04 Death Rate among Surgical Inpatients with Serious Treatable Complications | Inpatient Surgical Deaths (PSI04)                              | 94.83         | 122.97        | 92.16              | 36.18                     | 148.13                          |           | October 2012 ? September 2015 | 
| 1480006613  | 01014F | BIRMINGHAM VA MEDICAL CENTER | 700 SOUTH 19TH STREET | BIRMINGHAM | AL    | 35233    | PSI-6     | Patient Safety Indicator 06 Iatrogenic Pneumothorax Rate                                              | Collapsed lung due to medical treatment (PSI06)                | 0.32          | 0.27          | 0.4                | 0.08                      | 0.73                            |           | October 2012 ? September 2015 | 
| 1480006613  | 01014F | BIRMINGHAM VA MEDICAL CENTER | 700 SOUTH 19TH STREET | BIRMINGHAM | AL    | 35233    | PSI-7     | Patient Safety Indicator 07 Central Venous Catheter-Related Blood Stream Infection Rate               | Central Venous Catheter-Related Blood Stream Infection (PSI07) | 0.33          | 0.26          | 0.26               | 0                         | 0.53                            |           | October 2012 ? September 2015 | 
| 1480006613  | 01014F | BIRMINGHAM VA MEDICAL CENTER | 700 SOUTH 19TH STREET | BIRMINGHAM | AL    | 35233    | PSI-8     | Patient Safety Indicator 08 In Hospital Fall with Hip Fracture                                        | Postoperative Hip Fracture (PSI08)                             | 0             | 0.04          | 0                  | 0                         | 0.25                            |           | October 2012 ? September 2015 | 
| 1480006613  | 01014F | BIRMINGHAM VA MEDICAL CENTER | 700 SOUTH 19TH STREET | BIRMINGHAM | AL    | 35233    | PSI-9     | Patient Safety Indicator 09 Perioperative Hemorrhage or Hematoma Rate                                 | Perioperative Bleeding/Bruise (PSI09)                          | 6.81          | 6.86          | 5.11               | 3.15                      | 7.07                            |           | October 2012 ? September 2015 | 
| 1480006613  | 01014F | BIRMINGHAM VA MEDICAL CENTER | 700 SOUTH 19TH STREET | BIRMINGHAM | AL    | 35233    | PSI-10    | Patient Safety Indicator 10 Postoperative Acute Kidney Injury Requiring Dialysis                      | Postoperative Kidney & Diabetic Complications (PSI10)          | 0.41          | 0.94          | 0.31               | 0                         | 1.23                            |           | October 2012 ? September 2015 | 
| 1480006613  | 01014F | BIRMINGHAM VA MEDICAL CENTER | 700 SOUTH 19TH STREET | BIRMINGHAM | AL    | 35233    | PSI-11    | Patient Safety Indicator 11 Postoperative Respiratory Failure Rate                                    | Postoperative Respiratory Failure (PSI11)                      | 10.91         | 11.06         | 9.95               | 5.74                      | 14.17                           |           | October 2012 ? September 2015 | 
| 1480006613  | 01014F | BIRMINGHAM VA MEDICAL CENTER | 700 SOUTH 19TH STREET | BIRMINGHAM | AL    | 35233    | PSI-12    | Patient Safety Indicator 12 Perioperative Pulmonary Embolism or Deep Vein Thrombosis Rate             | Perioperative Blood Clot/Embolism (PSI12                       | 2.96          | 4.47          | 3.34               | 1.03                      | 5.66                            |           | October 2012 ? September 2015 | 
| 1480006613  | 01014F | BIRMINGHAM VA MEDICAL CENTER | 700 SOUTH 19TH STREET | BIRMINGHAM | AL    | 35233    | PSI-13    | Patient Safety Indicator 13 Postoperative Sepsis Rate                                                 | Postoperative Sepsis (PSI13)                                   | 13.11         | 10.74         | 11.68              | 3.92                      | 19.44                           |           | October 2012 ? September 2015 | 
```