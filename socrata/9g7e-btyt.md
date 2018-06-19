# Patient Survey (HCAHPS) ? National

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/patient-survey-hcahps-a-national) |
| Metadata | [Link](https://data.medicare.gov/api/views/9g7e-btyt) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/9g7e-btyt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/9g7e-btyt/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | 9g7e-btyt |
| Name | Patient Survey (HCAHPS) ? National |
| Category | Hospital Compare |
| Created | 2016-11-08T17:53:16Z |
| Publication Date | 2016-12-19T02:12:06Z |

## Description

A list of hospital ratings for the Hospital Consumer Assessment of Healthcare Providers and Systems (HCAHPS). HCAHPS is a national, standardized survey of hospital patients about their experiences during a recent inpatient hospital stay.

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type | Render Type |
| ======== | ============== | ========================= | ========================= | ========= | =========== |
| Yes      | series tag     | hcahps_measure_id         | HCAHPS Measure ID         | text      | text        |
| Yes      | series tag     | hcahps_question           | HCAHPS Question           | text      | text        |
| Yes      | series tag     | hcahps_answer_description | HCAHPS Answer Description | text      | text        |
| Yes      | numeric metric | hcahps_answer_percent     | HCAHPS Answer Percent     | number    | text        |
| Yes      | time           | measure_start_date        | Measure Start Date        | text      | text        |
| No       |                | measure_end_date          | Measure End Date          | text      | text        |
```

## Time Field

```ls
Value = measure_start_date
Format & Zone = MM/dd/yyyy
```

## Series Fields

```ls
Excluded Fields = measure_end_date
```

## Data Commands

```ls
series e:9g7e-btyt d:2015-04-01T00:00:00.000Z t:hcahps_measure_id=H_COMP_1_U_P t:hcahps_question="Patients who reported that their nurses Usually communicated well" t:hcahps_answer_description="Nurses usually communicated well" m:hcahps_answer_percent=16

series e:9g7e-btyt d:2015-04-01T00:00:00.000Z t:hcahps_measure_id=H_COMP_1_SN_P t:hcahps_question="Patients who reported that their nurses Sometimes or Never communicated well" t:hcahps_answer_description="Nurses sometimes or never communicated well" m:hcahps_answer_percent=4

series e:9g7e-btyt d:2015-04-01T00:00:00.000Z t:hcahps_measure_id=H_COMP_1_A_P t:hcahps_question="Patients who reported that their nurses Always communicated well" t:hcahps_answer_description="Nurses always communicated well" m:hcahps_answer_percent=80
```

## Meta Commands

```ls
metric m:hcahps_answer_percent p:integer l:"HCAHPS Answer Percent" t:dataTypeName=number

entity e:9g7e-btyt l:"Patient Survey (HCAHPS) ? National" t:url=https://data.medicare.gov/api/views/9g7e-btyt

property e:9g7e-btyt t:meta.view v:id=9g7e-btyt v:category="Hospital Compare" v:averageRating=0 v:name="Patient Survey (HCAHPS) ? National"

property e:9g7e-btyt t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:9g7e-btyt t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:9g7e-btyt t:meta.view.metadata.custom_fields.common_core v:Bureau_Code=009:38
```

## Top Records

```ls
| hcahps_measure_id | hcahps_question                                                                         | hcahps_answer_description                                        | hcahps_answer_percent | measure_start_date | measure_end_date | 
| ================= | ======================================================================================= | ================================================================ | ===================== | ================== | ================ | 
| H_COMP_1_U_P      | Patients who reported that their nurses Usually communicated well                       | Nurses usually communicated well                                 | 16                    | 04/01/2015         | 03/31/2016       | 
| H_COMP_1_SN_P     | Patients who reported that their nurses Sometimes or Never communicated well            | Nurses sometimes or never communicated well                      | 4                     | 04/01/2015         | 03/31/2016       | 
| H_COMP_1_A_P      | Patients who reported that their nurses Always communicated well                        | Nurses always communicated well                                  | 80                    | 04/01/2015         | 03/31/2016       | 
| H_COMP_2_SN_P     | Patients who reported that their doctors Sometimes or Never communicated well           | Doctors sometimes or never communicated well                     | 4                     | 04/01/2015         | 03/31/2016       | 
| H_COMP_2_U_P      | Patients who reported that their doctors Usually communicated well                      | Doctors usually communicated well                                | 14                    | 04/01/2015         | 03/31/2016       | 
| H_COMP_2_A_P      | Patients who reported that their doctors Always communicated well                       | Doctors always communicated well                                 | 82                    | 04/01/2015         | 03/31/2016       | 
| H_COMP_3_U_P      | Patients who reported that they Usually received help as soon as they wanted            | Patients usually received help as soon as they wanted            | 23                    | 04/01/2015         | 03/31/2016       | 
| H_COMP_3_SN_P     | Patients who reported that they Sometimes or Never received help as soon as they wanted | Patients sometimes or never received help as soon as they wanted | 8                     | 04/01/2015         | 03/31/2016       | 
| H_COMP_3_A_P      | Patients who reported that they Always received help as soon as they wanted             | Patients always received help as soon as they wanted             | 69                    | 04/01/2015         | 03/31/2016       | 
| H_COMP_4_U_P      | Patients who reported that their pain was Usually well controlled                       | Pain was usually well controlled                                 | 22                    | 04/01/2015         | 03/31/2016       | 
```