# Patient survey (ICH-CAHPS) - National

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/patient-survey-ich-cahps-national) |
| Metadata | [Link](https://data.medicare.gov/api/views/utgq-v46w) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/utgq-v46w/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/utgq-v46w/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | utgq-v46w |
| Name | Patient survey (ICH-CAHPS) - National |
| Category | Dialysis Facility Compare |
| Tags | dfc, dialysis, dialysis facilities, dialysis centers, cahps, patient survey, experience of care |
| Created | 2016-09-20T19:05:19Z |
| Publication Date | 2017-07-12T00:16:53Z |

## Description

The national average for ICH-CAHPS Survey measures. The ICH-CAHPS Survey is a national, standardized survey of in-center hemodialysis patients about their experiences with the facility, facility doctors and staff, and care received.

## Columns

```ls
| Included | Schema Type    | Field Name                                                                    | Name                                                                          | Data Type | Render Type |
| ======== | ============== | ============================================================================= | ============================================================================= | ========= | =========== |
| No       | time           | :updated_at                                                                   | updated_at                                                                    | meta_data | meta_data   |
| Yes      | series tag     | country                                                                       | Country                                                                       | text      | text        |
| Yes      | numeric metric | lower_box_percent_of_patients_nephrologists_communication_and_caring          | Lower box percent of patients nephrologists’ communication and caring         | number    | text        |
| Yes      | numeric metric | middle_box_percent_of_patients_nephrologists_communication_and_caring         | Middle box percent of patients nephrologists’ communication and caring        | number    | text        |
| Yes      | numeric metric | top_box_percent_of_patients_nephrologists_communication_and_caring            | Top box percent of patients nephrologists’ communication and caring           | number    | text        |
| Yes      | numeric metric | lower_box_percent_of_patients_quality_of_dialysis_center_care_and_operations  | Lower box percent of patients-quality of dialysis center care and operations  | number    | text        |
| Yes      | numeric metric | middle_box_percent_of_patients_quality_of_dialysis_center_care_and_operations | Middle box percent of patients-quality of dialysis center care and operations | number    | text        |
| Yes      | numeric metric | top_box_percent_of_patients_quality_of_dialysis_center_care_and_operations    | Top box percent of patients-quality of dialysis center care and operations    | number    | text        |
| Yes      | numeric metric | lower_box_percent_of_patients_providing_information_to_patients               | Lower box percent of patients-providing information to patients               | number    | text        |
| Yes      | numeric metric | top_box_percent_of_patients_providing_information_to_patients                 | Top box percent of patients providing information to patients                 | number    | text        |
| Yes      | numeric metric | lower_box_percent_of_patients_rating_of_the_nephrologist                      | Lower box percent of patients-rating of the nephrologist                      | number    | text        |
| Yes      | numeric metric | middle_box_percent_of_patients_rating_of_the_nephrologist                     | Middle box percent of patients- rating of the nephrologist                    | number    | text        |
| Yes      | numeric metric | top_box_percent_of_patients_rating_of_the_nephrologist                        | Top box percent of patients- rating of the nephrologist                       | number    | text        |
| Yes      | numeric metric | lower_box_percent_of_patients_rating_of_the_dialysis_center_staff             | Lower box percent of patients-rating of the dialysis center staff             | number    | text        |
| Yes      | numeric metric | middle_box_percent_of_patients_rating_of_the_dialysis_center_staff            | Middle box percent of patients-rating of the dialysis center staff            | number    | text        |
| Yes      | numeric metric | top_box_percent_of_patients_rating_of_the_dialysis_center_staff               | Top box percent of patients-rating of the dialysis center staff               | number    | text        |
| Yes      | numeric metric | lower_box_percent_of_patients_rating_of_the_dialysis_facility                 | Lower box percent of patients-rating of the dialysis facility                 | number    | text        |
| Yes      | numeric metric | middle_box_percent_of_patients_rating_of_the_dialysis_facility                | Middle box percent of patients-rating of the dialysis facility                | number    | text        |
| Yes      | numeric metric | top_box_percent_of_patients_rating_of_the_dialysis_facility                   | Top box percent of patients-rating of the dialysis facility                   | number    | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:utgq-v46w d:2017-06-09T17:34:53.000Z t:country=NATION m:middle_box_percent_of_patients_quality_of_dialysis_center_care_and_operations=21 m:top_box_percent_of_patients_nephrologists_communication_and_caring=66 m:middle_box_percent_of_patients_rating_of_the_dialysis_facility=22 m:lower_box_percent_of_patients_providing_information_to_patients=21 m:top_box_percent_of_patients_rating_of_the_nephrologist=61 m:top_box_percent_of_patients_rating_of_the_dialysis_center_staff=62 m:middle_box_percent_of_patients_rating_of_the_nephrologist=24 m:lower_box_percent_of_patients_rating_of_the_nephrologist=15 m:lower_box_percent_of_patients_nephrologists_communication_and_caring=18 m:lower_box_percent_of_patients_rating_of_the_dialysis_center_staff=12 m:lower_box_percent_of_patients_rating_of_the_dialysis_facility=12 m:top_box_percent_of_patients_quality_of_dialysis_center_care_and_operations=61 m:top_box_percent_of_patients_rating_of_the_dialysis_facility=66 m:top_box_percent_of_patients_providing_information_to_patients=79 m:middle_box_percent_of_patients_nephrologists_communication_and_caring=16 m:lower_box_percent_of_patients_quality_of_dialysis_center_care_and_operations=18 m:middle_box_percent_of_patients_rating_of_the_dialysis_center_staff=26
```

## Meta Commands

```ls
metric m:lower_box_percent_of_patients_nephrologists_communication_and_caring p:integer l:"Lower box percent of patients nephrologists’ communication and caring" t:dataTypeName=number

metric m:middle_box_percent_of_patients_nephrologists_communication_and_caring p:integer l:"Middle box percent of patients nephrologists’ communication and caring" t:dataTypeName=number

metric m:top_box_percent_of_patients_nephrologists_communication_and_caring p:integer l:"Top box percent of patients nephrologists’ communication and caring" t:dataTypeName=number

metric m:lower_box_percent_of_patients_quality_of_dialysis_center_care_and_operations p:integer l:"Lower box percent of patients-quality of dialysis center care and operations" t:dataTypeName=number

metric m:middle_box_percent_of_patients_quality_of_dialysis_center_care_and_operations p:integer l:"Middle box percent of patients-quality of dialysis center care and operations" t:dataTypeName=number

metric m:top_box_percent_of_patients_quality_of_dialysis_center_care_and_operations p:integer l:"Top box percent of patients-quality of dialysis center care and operations" t:dataTypeName=number

metric m:lower_box_percent_of_patients_providing_information_to_patients p:integer l:"Lower box percent of patients-providing information to patients" t:dataTypeName=number

metric m:top_box_percent_of_patients_providing_information_to_patients p:integer l:"Top box percent of patients providing information to patients" t:dataTypeName=number

metric m:lower_box_percent_of_patients_rating_of_the_nephrologist p:integer l:"Lower box percent of patients-rating of the nephrologist" t:dataTypeName=number

metric m:middle_box_percent_of_patients_rating_of_the_nephrologist p:integer l:"Middle box percent of patients- rating of the nephrologist" t:dataTypeName=number

metric m:top_box_percent_of_patients_rating_of_the_nephrologist p:integer l:"Top box percent of patients- rating of the nephrologist" t:dataTypeName=number

metric m:lower_box_percent_of_patients_rating_of_the_dialysis_center_staff p:integer l:"Lower box percent of patients-rating of the dialysis center staff" t:dataTypeName=number

metric m:middle_box_percent_of_patients_rating_of_the_dialysis_center_staff p:integer l:"Middle box percent of patients-rating of the dialysis center staff" t:dataTypeName=number

metric m:top_box_percent_of_patients_rating_of_the_dialysis_center_staff p:integer l:"Top box percent of patients-rating of the dialysis center staff" t:dataTypeName=number

metric m:lower_box_percent_of_patients_rating_of_the_dialysis_facility p:integer l:"Lower box percent of patients-rating of the dialysis facility" t:dataTypeName=number

metric m:middle_box_percent_of_patients_rating_of_the_dialysis_facility p:integer l:"Middle box percent of patients-rating of the dialysis facility" t:dataTypeName=number

metric m:top_box_percent_of_patients_rating_of_the_dialysis_facility p:integer l:"Top box percent of patients-rating of the dialysis facility" t:dataTypeName=number

entity e:utgq-v46w l:"Patient survey (ICH-CAHPS) - National" t:url=https://data.medicare.gov/api/views/utgq-v46w

property e:utgq-v46w t:meta.view d:2017-09-25T07:26:06.323Z v:averageRating=0 v:name="Patient survey (ICH-CAHPS) - National" v:id=utgq-v46w v:category="Dialysis Facility Compare"

property e:utgq-v46w t:meta.view.owner d:2017-09-25T07:26:06.323Z v:displayName=cms v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:id=drs7-75yr v:screenName=cms v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB

property e:utgq-v46w t:meta.view.tableauthor d:2017-09-25T07:26:06.323Z v:displayName=cms v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:roleName=administrator v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:id=drs7-75yr v:screenName=cms v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB

property e:utgq-v46w t:meta.view.metadata.custom_fields.common_core d:2017-09-25T07:26:06.323Z v:Contact_Email=DialysisData@umich.edu v:Contact_Name=CMS v:Program_Code=009:078 v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Bureau_Code=009:38
```

## Top Records

```ls
| :updated_at | country | lower_box_percent_of_patients_nephrologists_communication_and_caring | middle_box_percent_of_patients_nephrologists_communication_and_caring | top_box_percent_of_patients_nephrologists_communication_and_caring | lower_box_percent_of_patients_quality_of_dialysis_center_care_and_operations | middle_box_percent_of_patients_quality_of_dialysis_center_care_and_operations | top_box_percent_of_patients_quality_of_dialysis_center_care_and_operations | lower_box_percent_of_patients_providing_information_to_patients | top_box_percent_of_patients_providing_information_to_patients | lower_box_percent_of_patients_rating_of_the_nephrologist | middle_box_percent_of_patients_rating_of_the_nephrologist | top_box_percent_of_patients_rating_of_the_nephrologist | lower_box_percent_of_patients_rating_of_the_dialysis_center_staff | middle_box_percent_of_patients_rating_of_the_dialysis_center_staff | top_box_percent_of_patients_rating_of_the_dialysis_center_staff | lower_box_percent_of_patients_rating_of_the_dialysis_facility | middle_box_percent_of_patients_rating_of_the_dialysis_facility | top_box_percent_of_patients_rating_of_the_dialysis_facility | 
| =========== | ======= | ==================================================================== | ===================================================================== | ================================================================== | ============================================================================ | ============================================================================= | ========================================================================== | =============================================================== | ============================================================= | ======================================================== | ========================================================= | ====================================================== | ================================================================= | ================================================================== | =============================================================== | ============================================================= | ============================================================== | =========================================================== | 
| 1497029693  | NATION  | 18                                                                   | 16                                                                    | 66                                                                 | 18                                                                           | 21                                                                            | 61                                                                         | 21                                                              | 79                                                            | 15                                                       | 24                                                        | 61                                                     | 12                                                                | 26                                                                 | 62                                                              | 12                                                            | 22                                                             | 66                                                          | 
```