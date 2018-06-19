# Veterans Health Administration Survey of Healthcare Experiences of Patients (SHEP)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/veterans-health-administration-survey-of-healthcare-experiences-of-patients-shep) |
| Metadata | [Link](https://data.medicare.gov/api/views/gesg-pgbr) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/gesg-pgbr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/gesg-pgbr/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | gesg-pgbr |
| Name | Veterans Health Administration Survey of Healthcare Experiences of Patients (SHEP) |
| Category | Hospital Compare |
| Tags | veterans |
| Created | 2016-11-08T17:33:30Z |
| Publication Date | 2016-12-19T02:13:12Z |

## Description

A list of VHA hospitals with inpatient experience of care survey data. The VA SHEP uses the same questions as the Hospital Consumer Assessment of Health Providers and Systems (HCAHPS) Survey shown on Hospital Compare, however, the results do not represent official HCAHPS results.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type | Render Type |
| ======== | ============== | ===================== | ===================== | ========= | =========== |
| Yes      | series tag     | provider_id           | Provider ID           | text      | text        |
| Yes      | series tag     | hospital_name         | Hospital Name         | text      | text        |
| No       |                | address               | Address               | text      | text        |
| Yes      | series tag     | city                  | City                  | text      | text        |
| Yes      | series tag     | state                 | State                 | text      | text        |
| Yes      | series tag     | zip                   | Zip                   | text      | text        |
| Yes      | series tag     | county_name           | County Name           | text      | text        |
| Yes      | series tag     | phone_number          | Phone Number          | text      | text        |
| Yes      | series tag     | measure_id            | Measure ID            | text      | text        |
| Yes      | series tag     | measure_name          | Measure Name          | text      | text        |
| Yes      | series tag     | survey_question       | Survey Question       | text      | text        |
| Yes      | series tag     | answer_description    | Answer Description    | text      | text        |
| Yes      | numeric metric | answer_percent        | Answer Percent        | number    | text        |
| Yes      | numeric metric | number_item_responses | Number Item Responses | number    | text        |
| No       |                | footnote              | Footnote              | text      | text        |
| Yes      | time           | measure_start_date    | Measure Start Date    | text      | text        |
| No       |                | measure_end_date      | Measure End Date      | text      | text        |
```

## Time Field

```ls
Value = measure_start_date
Format & Zone = MM/dd/yyyy
```

## Series Fields

```ls
Excluded Fields = address,footnote,measure_end_date
```

## Data Commands

```ls
series e:gesg-pgbr d:2015-04-01T00:00:00.000Z t:hospital_name="TOGUS VA MEDICAL CENTER" t:zip=04330 t:phone_number=2076238411 t:measure_id=VA-H_CLEAN_HSP_A_P t:provider_id=20003F t:state=ME t:county_name=KENNEBEC t:survey_question="Patients who reported that their room and bathroom were ""Always"" clean" t:answer_description="Room was ""always"" clean" t:measure_name="VA-Cleanliness of the Hospital Environment" t:city=AUGUSTA m:answer_percent=77 m:number_item_responses=383

series e:gesg-pgbr d:2015-04-01T00:00:00.000Z t:hospital_name="TOGUS VA MEDICAL CENTER" t:zip=04330 t:phone_number=2076238411 t:measure_id=VA-H_COMP_1_A_P t:provider_id=20003F t:state=ME t:county_name=KENNEBEC t:survey_question="Patients who reported that their nurses ""Always"" communicated well" t:answer_description="Nurses ""always"" communicated well" t:measure_name="VA-Communication with Nurses" t:city=AUGUSTA m:answer_percent=77 m:number_item_responses=383

series e:gesg-pgbr d:2015-04-01T00:00:00.000Z t:hospital_name="TOGUS VA MEDICAL CENTER" t:zip=04330 t:phone_number=2076238411 t:measure_id=VA-H_COMP_2_A_P t:provider_id=20003F t:state=ME t:county_name=KENNEBEC t:survey_question="Patients who reported that their doctors ""Always"" communicated well" t:answer_description="Doctors ""always"" communicated well" t:measure_name="VA-Communication with Doctors" t:city=AUGUSTA m:answer_percent=82 m:number_item_responses=380
```

## Meta Commands

```ls
metric m:answer_percent p:integer l:"Answer Percent" t:dataTypeName=number

metric m:number_item_responses p:integer l:"Number Item Responses" t:dataTypeName=number

entity e:gesg-pgbr l:"Veterans Health Administration Survey of Healthcare Experiences of Patients (SHEP)" t:url=https://data.medicare.gov/api/views/gesg-pgbr

property e:gesg-pgbr t:meta.view v:id=gesg-pgbr v:category="Hospital Compare" v:averageRating=0 v:name="Veterans Health Administration Survey of Healthcare Experiences of Patients (SHEP)"

property e:gesg-pgbr t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:gesg-pgbr t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:gesg-pgbr t:meta.view.metadata.custom_fields.common_core v:Bureau_Code=009:38
```

## Top Records

```ls
| provider_id | hospital_name           | address     | city    | state | zip   | county_name | phone_number | measure_id           | measure_name                               | survey_question                                                                                           | answer_description                                                                   | answer_percent | number_item_responses | footnote | measure_start_date | measure_end_date | 
| =========== | ======================= | =========== | ======= | ===== | ===== | =========== | ============ | ==================== | ========================================== | ========================================================================================================= | ==================================================================================== | ============== | ===================== | ======== | ================== | ================ | 
| 20003F      | TOGUS VA MEDICAL CENTER | 1 VA CENTER | AUGUSTA | ME    | 04330 | KENNEBEC    | 2076238411   | VA-H_CLEAN_HSP_A_P   | VA-Cleanliness of the Hospital Environment | Patients who reported that their room and bathroom were "Always" clean                                    | Room was "always" clean                                                              | 77             | 383                   |          | 04/01/2015         | 03/31/2016       | 
| 20003F      | TOGUS VA MEDICAL CENTER | 1 VA CENTER | AUGUSTA | ME    | 04330 | KENNEBEC    | 2076238411   | VA-H_COMP_1_A_P      | VA-Communication with Nurses               | Patients who reported that their nurses "Always" communicated well                                        | Nurses "always" communicated well                                                    | 77             | 383                   |          | 04/01/2015         | 03/31/2016       | 
| 20003F      | TOGUS VA MEDICAL CENTER | 1 VA CENTER | AUGUSTA | ME    | 04330 | KENNEBEC    | 2076238411   | VA-H_COMP_2_A_P      | VA-Communication with Doctors              | Patients who reported that their doctors "Always" communicated well                                       | Doctors "always" communicated well                                                   | 82             | 380                   |          | 04/01/2015         | 03/31/2016       | 
| 20003F      | TOGUS VA MEDICAL CENTER | 1 VA CENTER | AUGUSTA | ME    | 04330 | KENNEBEC    | 2076238411   | VA-H_COMP_3_A_P      | VA-Responsiveness of Hospital Staff        | Patients who reported that they "Always" received help as soon as they wanted                             | Patients "always" received help as soon as they wanted                               | 70             | 223                   |          | 04/01/2015         | 03/31/2016       | 
| 20003F      | TOGUS VA MEDICAL CENTER | 1 VA CENTER | AUGUSTA | ME    | 04330 | KENNEBEC    | 2076238411   | VA-H_COMP_4_A_P      | VA-Pain Management                         | Patients who reported that their pain was "Always" well controlled                                        | Pain was "always" well controlled                                                    | 70             | 255                   |          | 04/01/2015         | 03/31/2016       | 
| 20003F      | TOGUS VA MEDICAL CENTER | 1 VA CENTER | AUGUSTA | ME    | 04330 | KENNEBEC    | 2076238411   | VA-H_COMP_5_A_P      | VA-Communication about Medication          | Patients who reported that staff "Always" explained about medicines before giving it to them              | Staff "always" explained                                                             | 73             | 197                   |          | 04/01/2015         | 03/31/2016       | 
| 20003F      | TOGUS VA MEDICAL CENTER | 1 VA CENTER | AUGUSTA | ME    | 04330 | KENNEBEC    | 2076238411   | VA-H_COMP_6_Y_P      | VA-Discharge Information                   | Patients who reported that YES they were given information about what to do during their recovery at home | Yes staff "did" give patients this information                                       | 85             | 347                   |          | 04/01/2015         | 03/31/2016       | 
| 20003F      | TOGUS VA MEDICAL CENTER | 1 VA CENTER | AUGUSTA | ME    | 04330 | KENNEBEC    | 2076238411   | VA-H_COMP_7_SA       | VA-Care Transition                         | Patients who "Strongly Agree" they understood their care when they left the hospital                      | Patients who ?Strongly Agree? they understood their care when they left the hospital | 56             | 372                   |          | 04/01/2015         | 03/31/2016       | 
| 20003F      | TOGUS VA MEDICAL CENTER | 1 VA CENTER | AUGUSTA | ME    | 04330 | KENNEBEC    | 2076238411   | VA-H_HSP_RATING_9_10 | VA-Overall Rating of Hospital              | Patients who gave their hospital a rating of 9 or 10 on a scale from 0 (lowest) to 10 (highest)           | Patients who gave a rating of "9" or "10" (high)                                     | 68             | 377                   |          | 04/01/2015         | 03/31/2016       | 
| 20003F      | TOGUS VA MEDICAL CENTER | 1 VA CENTER | AUGUSTA | ME    | 04330 | KENNEBEC    | 2076238411   | VA-H_QUIET_HSP_A_P   | VA-Quietness of the Hospital Environment   | Patients who reported that the area around their room was "Always" quiet at night                         | "Always" quiet at night                                                              | 57             | 382                   |          | 04/01/2015         | 03/31/2016       | 
```