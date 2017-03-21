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
| Publication Date | 2017-01-26T01:51:05Z |
| Rows Updated | 2017-01-10T17:44:42Z |

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
series e:utgq-v46w d:2017-01-10T17:44:29.000Z t:country=NATION m:lower_box_percent_of_patients_rating_of_the_dialysis_center_staff=13 m:lower_box_percent_of_patients_nephrologists_communication_and_caring=17 m:lower_box_percent_of_patients_rating_of_the_nephrologist=16 m:lower_box_percent_of_patients_providing_information_to_patients=22 m:middle_box_percent_of_patients_quality_of_dialysis_center_care_and_operations=22 m:top_box_percent_of_patients_rating_of_the_nephrologist=62 m:top_box_percent_of_patients_quality_of_dialysis_center_care_and_operations=61 m:middle_box_percent_of_patients_nephrologists_communication_and_caring=17 m:top_box_percent_of_patients_providing_information_to_patients=78 m:top_box_percent_of_patients_rating_of_the_dialysis_center_staff=62 m:lower_box_percent_of_patients_rating_of_the_dialysis_facility=12 m:middle_box_percent_of_patients_rating_of_the_dialysis_facility=23 m:top_box_percent_of_patients_nephrologists_communication_and_caring=66 m:middle_box_percent_of_patients_rating_of_the_dialysis_center_staff=25 m:top_box_percent_of_patients_rating_of_the_dialysis_facility=65 m:middle_box_percent_of_patients_rating_of_the_nephrologist=22 m:lower_box_percent_of_patients_quality_of_dialysis_center_care_and_operations=17
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

property e:utgq-v46w t:meta.view v:id=utgq-v46w v:category="Dialysis Facility Compare" v:averageRating=0 v:name="Patient survey (ICH-CAHPS) - National"

property e:utgq-v46w t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:utgq-v46w t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:utgq-v46w t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=DialysisData@umich.edu v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```