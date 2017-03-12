# Patient survey (ICH-CAHPS) - State

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/patient-survey-ich-cahps-state) |
| Metadata | [Link](https://data.medicare.gov/api/views/hanv-ru8h) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/hanv-ru8h/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/hanv-ru8h/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | hanv-ru8h |
| Name | Patient survey (ICH-CAHPS) - State |
| Category | Dialysis Facility Compare |
| Tags | dfc, dialysis, dialysis facilities, dialysis centers, cahps, patient survey, experience of care |
| Created | 2016-09-20T19:06:24Z |
| Publication Date | 2017-01-26T01:51:07Z |
| Rows Updated | 2017-01-10T17:44:43Z |

## Description

State averages for ICH-CAHPS Survey measures. The ICH-CAHPS Survey is a national, standardized survey of in-center hemodialysis patients about their experiences with the facility, facility doctors and staff, and care received.

## Columns

```ls
| Included | Schema Type    | Field Name                                                                    | Name                                                                          | Data Type | Render Type |
| ======== | ============== | ============================================================================= | ============================================================================= | ========= | =========== |
| No       | time           | :updated_at                                                                   | updated_at                                                                    | meta_data | meta_data   |
| Yes      | series tag     | state                                                                         | State                                                                         | text      | text        |
| Yes      | numeric metric | lower_box_percent_of_patients_nephrologists_communication_and_caring          | Lower box percent of patients nephrologists? communication and caring         | number    | number      |
| Yes      | numeric metric | middle_box_percent_of_patients_nephrologists_communication_and_caring         | Middle box percent of patients nephrologists? communication and caring        | number    | number      |
| Yes      | numeric metric | top_box_percent_of_patients_nephrologists_communication_and_caring            | Top box percent of patients nephrologists? communication and caring           | number    | number      |
| Yes      | numeric metric | lower_box_percent_of_patients_quality_of_dialysis_center_care_and_operations  | Lower box percent of patients-quality of dialysis center care and operations  | number    | number      |
| Yes      | numeric metric | middle_box_percent_of_patients_quality_of_dialysis_center_care_and_operations | Middle box percent of patients-quality of dialysis center care and operations | number    | number      |
| Yes      | numeric metric | top_box_percent_of_patients_quality_of_dialysis_center_care_and_operations    | Top box percent of patients-quality of dialysis center care and operations    | number    | number      |
| Yes      | numeric metric | lower_box_percent_of_patients_providing_information_to_patients               | Lower box percent of patients-providing information to patients               | number    | number      |
| Yes      | numeric metric | top_box_percent_of_patients_providing_information_to_patients                 | Top box percent of patients providing information to patients                 | number    | number      |
| Yes      | numeric metric | lower_box_percent_of_patients_rating_of_the_nephrologist                      | Lower box percent of patients-rating of the nephrologist                      | number    | number      |
| Yes      | numeric metric | middle_box_percent_of_patients_rating_of_the_nephrologist                     | Middle box percent of patients- rating of the nephrologist                    | number    | number      |
| Yes      | numeric metric | top_box_percent_of_patients_rating_of_the_nephrologist                        | Top box percent of patients- rating of the nephrologist                       | number    | number      |
| Yes      | numeric metric | lower_box_percent_of_patients_rating_of_the_dialysis_center_staff             | Lower box percent of patients-rating of the dialysis center staff             | number    | number      |
| Yes      | numeric metric | middle_box_percent_of_patients_rating_of_the_dialysis_center_staff            | Middle box percent of patients-rating of the dialysis center staff            | number    | number      |
| Yes      | numeric metric | top_box_percent_of_patients_rating_of_the_dialysis_center_staff               | Top box percent of patients-rating of the dialysis center staff               | number    | number      |
| Yes      | numeric metric | lower_box_percent_of_patients_rating_of_the_dialysis_facility                 | Lower box percent of patients-rating of the dialysis facility                 | number    | number      |
| Yes      | numeric metric | middle_box_percent_of_patients_rating_of_the_dialysis_facility                | Middle box percent of patients-rating of the dialysis facility                | number    | number      |
| Yes      | numeric metric | top_box_percent_of_patients_rating_of_the_dialysis_facility                   | Top box percent of patients-rating of the dialysis facility                   | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:hanv-ru8h d:2017-01-10T17:44:31.000Z t:state=AK m:lower_box_percent_of_patients_rating_of_the_dialysis_center_staff=9 m:lower_box_percent_of_patients_nephrologists_communication_and_caring=14 m:lower_box_percent_of_patients_rating_of_the_nephrologist=17 m:lower_box_percent_of_patients_providing_information_to_patients=18 m:middle_box_percent_of_patients_quality_of_dialysis_center_care_and_operations=24 m:top_box_percent_of_patients_rating_of_the_nephrologist=65 m:top_box_percent_of_patients_quality_of_dialysis_center_care_and_operations=63 m:middle_box_percent_of_patients_nephrologists_communication_and_caring=17 m:top_box_percent_of_patients_providing_information_to_patients=82 m:top_box_percent_of_patients_rating_of_the_dialysis_center_staff=68 m:lower_box_percent_of_patients_rating_of_the_dialysis_facility=9 m:middle_box_percent_of_patients_rating_of_the_dialysis_facility=17 m:top_box_percent_of_patients_nephrologists_communication_and_caring=69 m:middle_box_percent_of_patients_rating_of_the_dialysis_center_staff=23 m:top_box_percent_of_patients_rating_of_the_dialysis_facility=74 m:middle_box_percent_of_patients_rating_of_the_nephrologist=18 m:lower_box_percent_of_patients_quality_of_dialysis_center_care_and_operations=13

series e:hanv-ru8h d:2017-01-10T17:44:31.000Z t:state=AL m:lower_box_percent_of_patients_rating_of_the_dialysis_center_staff=15 m:lower_box_percent_of_patients_nephrologists_communication_and_caring=19 m:lower_box_percent_of_patients_rating_of_the_nephrologist=16 m:lower_box_percent_of_patients_providing_information_to_patients=22 m:middle_box_percent_of_patients_quality_of_dialysis_center_care_and_operations=20 m:top_box_percent_of_patients_rating_of_the_nephrologist=61 m:top_box_percent_of_patients_quality_of_dialysis_center_care_and_operations=60 m:middle_box_percent_of_patients_nephrologists_communication_and_caring=15 m:top_box_percent_of_patients_providing_information_to_patients=78 m:top_box_percent_of_patients_rating_of_the_dialysis_center_staff=60 m:lower_box_percent_of_patients_rating_of_the_dialysis_facility=14 m:middle_box_percent_of_patients_rating_of_the_dialysis_facility=23 m:top_box_percent_of_patients_nephrologists_communication_and_caring=66 m:middle_box_percent_of_patients_rating_of_the_dialysis_center_staff=25 m:top_box_percent_of_patients_rating_of_the_dialysis_facility=63 m:middle_box_percent_of_patients_rating_of_the_nephrologist=23 m:lower_box_percent_of_patients_quality_of_dialysis_center_care_and_operations=20

series e:hanv-ru8h d:2017-01-10T17:44:31.000Z t:state=AR m:lower_box_percent_of_patients_rating_of_the_dialysis_center_staff=15 m:lower_box_percent_of_patients_nephrologists_communication_and_caring=18 m:lower_box_percent_of_patients_rating_of_the_nephrologist=16 m:lower_box_percent_of_patients_providing_information_to_patients=20 m:middle_box_percent_of_patients_quality_of_dialysis_center_care_and_operations=21 m:top_box_percent_of_patients_rating_of_the_nephrologist=61 m:top_box_percent_of_patients_quality_of_dialysis_center_care_and_operations=60 m:middle_box_percent_of_patients_nephrologists_communication_and_caring=17 m:top_box_percent_of_patients_providing_information_to_patients=80 m:top_box_percent_of_patients_rating_of_the_dialysis_center_staff=59 m:lower_box_percent_of_patients_rating_of_the_dialysis_facility=13 m:middle_box_percent_of_patients_rating_of_the_dialysis_facility=24 m:top_box_percent_of_patients_nephrologists_communication_and_caring=65 m:middle_box_percent_of_patients_rating_of_the_dialysis_center_staff=26 m:top_box_percent_of_patients_rating_of_the_dialysis_facility=63 m:middle_box_percent_of_patients_rating_of_the_nephrologist=23 m:lower_box_percent_of_patients_quality_of_dialysis_center_care_and_operations=19
```

## Meta Commands

```ls
metric m:lower_box_percent_of_patients_nephrologists_communication_and_caring p:integer l:"Lower box percent of patients nephrologists? communication and caring" t:dataTypeName=number

metric m:middle_box_percent_of_patients_nephrologists_communication_and_caring p:integer l:"Middle box percent of patients nephrologists? communication and caring" t:dataTypeName=number

metric m:top_box_percent_of_patients_nephrologists_communication_and_caring p:integer l:"Top box percent of patients nephrologists? communication and caring" t:dataTypeName=number

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

entity e:hanv-ru8h l:"Patient survey (ICH-CAHPS) - State" t:url=https://data.medicare.gov/api/views/hanv-ru8h

property e:hanv-ru8h t:meta.view v:id=hanv-ru8h v:category="Dialysis Facility Compare" v:averageRating=0 v:name="Patient survey (ICH-CAHPS) - State"

property e:hanv-ru8h t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:hanv-ru8h t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:hanv-ru8h t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=DialysisData@umich.edu v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```