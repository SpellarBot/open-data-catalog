# Patient survey (ICH-CAHPS) - State

## Dataset

* [Dataset URL](https://data.medicare.gov/api/views/hanv-ru8h/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/patient-survey-ich-cahps-state)
* [Metadata URL](https://data.medicare.gov/api/views/hanv-ru8h)
* Id = hanv-ru8h
* Name = Patient survey (ICH-CAHPS) - State
* Category = Dialysis Facility Compare
* Tags = [dfc, dialysis, dialysis facilities, dialysis centers, cahps, patient survey, experience of care]
* Created = 2016-09-20T19:06:24Z
* Publication Date = 2017-01-26T01:51:07Z
* Rows Updated = 2017-01-10T17:44:43Z

## Description

State averages for ICH-CAHPS Survey measures. The ICH-CAHPS Survey is a national, standardized survey of in-center hemodialysis patients about their experiences with the facility, facility doctors and staff, and care received.

## Columns

```ls
| Name                                                                          | Field Name                                                                    | Data Type | Render Type | Schema Type    | Included | 
| ============================================================================= | ============================================================================= | ========= | =========== | ============== | ======== | 
| updated_at                                                                    | :updated_at                                                                   | meta_data | meta_data   | time           | No       | 
| State                                                                         | state                                                                         | text      | text        | series tag     | Yes      | 
| Lower box percent of patients nephrologists? communication and caring         | lower_box_percent_of_patients_nephrologists_communication_and_caring          | number    | number      | numeric metric | Yes      | 
| Middle box percent of patients nephrologists? communication and caring        | middle_box_percent_of_patients_nephrologists_communication_and_caring         | number    | number      | numeric metric | Yes      | 
| Top box percent of patients nephrologists? communication and caring           | top_box_percent_of_patients_nephrologists_communication_and_caring            | number    | number      | numeric metric | Yes      | 
| Lower box percent of patients-quality of dialysis center care and operations  | lower_box_percent_of_patients_quality_of_dialysis_center_care_and_operations  | number    | number      | numeric metric | Yes      | 
| Middle box percent of patients-quality of dialysis center care and operations | middle_box_percent_of_patients_quality_of_dialysis_center_care_and_operations | number    | number      | numeric metric | Yes      | 
| Top box percent of patients-quality of dialysis center care and operations    | top_box_percent_of_patients_quality_of_dialysis_center_care_and_operations    | number    | number      | numeric metric | Yes      | 
| Lower box percent of patients-providing information to patients               | lower_box_percent_of_patients_providing_information_to_patients               | number    | number      | numeric metric | Yes      | 
| Top box percent of patients providing information to patients                 | top_box_percent_of_patients_providing_information_to_patients                 | number    | number      | numeric metric | Yes      | 
| Lower box percent of patients-rating of the nephrologist                      | lower_box_percent_of_patients_rating_of_the_nephrologist                      | number    | number      | numeric metric | Yes      | 
| Middle box percent of patients- rating of the nephrologist                    | middle_box_percent_of_patients_rating_of_the_nephrologist                     | number    | number      | numeric metric | Yes      | 
| Top box percent of patients- rating of the nephrologist                       | top_box_percent_of_patients_rating_of_the_nephrologist                        | number    | number      | numeric metric | Yes      | 
| Lower box percent of patients-rating of the dialysis center staff             | lower_box_percent_of_patients_rating_of_the_dialysis_center_staff             | number    | number      | numeric metric | Yes      | 
| Middle box percent of patients-rating of the dialysis center staff            | middle_box_percent_of_patients_rating_of_the_dialysis_center_staff            | number    | number      | numeric metric | Yes      | 
| Top box percent of patients-rating of the dialysis center staff               | top_box_percent_of_patients_rating_of_the_dialysis_center_staff               | number    | number      | numeric metric | Yes      | 
| Lower box percent of patients-rating of the dialysis facility                 | lower_box_percent_of_patients_rating_of_the_dialysis_facility                 | number    | number      | numeric metric | Yes      | 
| Middle box percent of patients-rating of the dialysis facility                | middle_box_percent_of_patients_rating_of_the_dialysis_facility                | number    | number      | numeric metric | Yes      | 
| Top box percent of patients-rating of the dialysis facility                   | top_box_percent_of_patients_rating_of_the_dialysis_facility                   | number    | number      | numeric metric | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
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

property e:hanv-ru8h t:meta.view d:2017-03-07T17:57:29.242Z v:id=hanv-ru8h v:category="Dialysis Facility Compare" v:averageRating=0 v:name="Patient survey (ICH-CAHPS) - State"

property e:hanv-ru8h t:meta.view.owner d:2017-03-07T17:57:29.242Z v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:hanv-ru8h t:meta.view.tableauthor d:2017-03-07T17:57:29.242Z v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:hanv-ru8h t:meta.view.metadata.custom_fields.common_core d:2017-03-07T17:57:29.242Z v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=DialysisData@umich.edu v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```