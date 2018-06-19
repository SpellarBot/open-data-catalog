# Home Health Care - Patient survey (HHCAHPS) National Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/home-health-care-patient-survey-hhcahps-national-data) |
| Metadata | [Link](https://data.medicare.gov/api/views/vxub-6swi) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/vxub-6swi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/vxub-6swi/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | vxub-6swi |
| Name | Home Health Care - Patient survey (HHCAHPS) National Data |
| Category | Home Health Compare |
| Tags | hhc, facilities, quality, ratings, comparison, home health agencies, hhcahps, patient survey results |
| Created | 2012-04-16T16:45:27Z |
| Publication Date | 2017-04-11T23:17:15Z |

## Columns

```ls
| Included | Schema Type    | Field Name                                                                                                        | Name                                                                                                                 | Data Type | Render Type |
| ======== | ============== | ================================================================================================================= | ==================================================================================================================== | ========= | =========== |
| No       | time           | :updated_at                                                                                                       | updated_at                                                                                                           | meta_data | meta_data   |
| Yes      | series tag     | country                                                                                                           | Country                                                                                                              | text      | text        |
| Yes      | numeric metric | percent_of_patients_who_reported_that_their_home_health_team_gave_care_in_a_professional_way                      | Percent of patients who reported that their home health team gave care in a professional way                         | percent   | percent     |
| Yes      | numeric metric | percent_of_patients_who_reported_that_their_home_health_team_communicated_well_with_them                          | Percent of patients who reported that their home health team communicated well with them                             | percent   | percent     |
| Yes      | numeric metric | percent_of_patients_who_reported_that_their_home_health_team_discussed_medicines_pain_and_home_safety_with_them   | Percent of patients who reported that their home health team discussed medicines, pain, and home safety with them    | percent   | percent     |
| Yes      | numeric metric | percent_of_patients_who_gave_their_home_health_agency_a_rating_of_9_or_10_on_a_scale_from_0_lowest_to_10_highest  | Percent of patients who gave their home health agency a rating of 9 or 10 on a scale from 0 (lowest) to 10 (highest) | percent   | percent     |
| Yes      | numeric metric | percent_of_patients_who_reported_yes_they_would_definitely_recommend_the_home_health_agency_to_friends_and_family | Percent of patients who reported YES, they would definitely recommend the home health agency to friends and family   | percent   | percent     |
| Yes      | series tag     | number_of_completed_surveys                                                                                       | Number of completed Surveys                                                                                          | text      | text        |
| Yes      | series tag     | response_rate                                                                                                     | Response rate                                                                                                        | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:vxub-6swi d:2017-03-27T16:54:30.000Z t:country=Nation m:percent_of_patients_who_gave_their_home_health_agency_a_rating_of_9_or_10_on_a_scale_from_0_lowest_to_10_highest=84 m:percent_of_patients_who_reported_that_their_home_health_team_communicated_well_with_them=85 m:percent_of_patients_who_reported_that_their_home_health_team_gave_care_in_a_professional_way=88 m:percent_of_patients_who_reported_that_their_home_health_team_discussed_medicines_pain_and_home_safety_with_them=83 m:percent_of_patients_who_reported_yes_they_would_definitely_recommend_the_home_health_agency_to_friends_and_family=78
```

## Meta Commands

```ls
metric m:percent_of_patients_who_reported_that_their_home_health_team_gave_care_in_a_professional_way p:integer l:"Percent of patients who reported that their home health team gave care in a professional way" t:dataTypeName=percent

metric m:percent_of_patients_who_reported_that_their_home_health_team_communicated_well_with_them p:integer l:"Percent of patients who reported that their home health team communicated well with them" t:dataTypeName=percent

metric m:percent_of_patients_who_reported_that_their_home_health_team_discussed_medicines_pain_and_home_safety_with_them p:integer l:"Percent of patients who reported that their home health team discussed medicines, pain, and home safety with them" t:dataTypeName=percent

metric m:percent_of_patients_who_gave_their_home_health_agency_a_rating_of_9_or_10_on_a_scale_from_0_lowest_to_10_highest p:integer l:"Percent of patients who gave their home health agency a rating of 9 or 10 on a scale from 0 (lowest) to 10 (highest)" t:dataTypeName=percent

metric m:percent_of_patients_who_reported_yes_they_would_definitely_recommend_the_home_health_agency_to_friends_and_family p:integer l:"Percent of patients who reported YES, they would definitely recommend the home health agency to friends and family" t:dataTypeName=percent

entity e:vxub-6swi l:"Home Health Care - Patient survey (HHCAHPS) National Data" t:url=https://data.medicare.gov/api/views/vxub-6swi

property e:vxub-6swi t:meta.view v:id=vxub-6swi v:category="Home Health Compare" v:averageRating=0 v:name="Home Health Care - Patient survey (HHCAHPS) National Data"

property e:vxub-6swi t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:vxub-6swi t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:vxub-6swi t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=HomeHealthQualityQuestions@cms.hhs.gov v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```

## Top Records

```ls
| :updated_at | country | percent_of_patients_who_reported_that_their_home_health_team_gave_care_in_a_professional_way | percent_of_patients_who_reported_that_their_home_health_team_communicated_well_with_them | percent_of_patients_who_reported_that_their_home_health_team_discussed_medicines_pain_and_home_safety_with_them | percent_of_patients_who_gave_their_home_health_agency_a_rating_of_9_or_10_on_a_scale_from_0_lowest_to_10_highest | percent_of_patients_who_reported_yes_they_would_definitely_recommend_the_home_health_agency_to_friends_and_family | number_of_completed_surveys | response_rate | 
| =========== | ======= | ============================================================================================ | ======================================================================================== | =============================================================================================================== | ================================================================================================================ | ================================================================================================================= | =========================== | ============= | 
| 1490633670  | Nation  | 88                                                                                           | 85                                                                                       | 83                                                                                                              | 84                                                                                                               | 78                                                                                                                |                             |               | 
```