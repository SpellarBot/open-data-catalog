# Home Health Care - Patient survey (HHCAHPS) State Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/home-health-care-patient-survey-hhcahps-state-data) |
| Metadata | [Link](https://data.medicare.gov/api/views/m5jg-jg7i) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/m5jg-jg7i/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/m5jg-jg7i/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | m5jg-jg7i |
| Name | Home Health Care - Patient survey (HHCAHPS) State Data |
| Category | Home Health Compare |
| Tags | hhc, facilities, quality, ratings, comparison, home health agencies, state average, hhcahps, patient survey results |
| Created | 2012-04-16T17:12:11Z |
| Publication Date | 2017-04-11T23:18:43Z |

## Columns

```ls
| Included | Schema Type    | Field Name                                                                                                        | Name                                                                                                                 | Data Type | Render Type |
| ======== | ============== | ================================================================================================================= | ==================================================================================================================== | ========= | =========== |
| No       | time           | :updated_at                                                                                                       | updated_at                                                                                                           | meta_data | meta_data   |
| Yes      | series tag     | state                                                                                                             | State                                                                                                                | text      | text        |
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
series e:m5jg-jg7i d:2017-03-27T17:01:14.000Z t:state=AK m:percent_of_patients_who_gave_their_home_health_agency_a_rating_of_9_or_10_on_a_scale_from_0_lowest_to_10_highest=84 m:percent_of_patients_who_reported_that_their_home_health_team_communicated_well_with_them=85 m:percent_of_patients_who_reported_that_their_home_health_team_gave_care_in_a_professional_way=88 m:percent_of_patients_who_reported_that_their_home_health_team_discussed_medicines_pain_and_home_safety_with_them=82 m:percent_of_patients_who_reported_yes_they_would_definitely_recommend_the_home_health_agency_to_friends_and_family=81

series e:m5jg-jg7i d:2017-03-27T17:01:14.000Z t:state=AL m:percent_of_patients_who_gave_their_home_health_agency_a_rating_of_9_or_10_on_a_scale_from_0_lowest_to_10_highest=88 m:percent_of_patients_who_reported_that_their_home_health_team_communicated_well_with_them=89 m:percent_of_patients_who_reported_that_their_home_health_team_gave_care_in_a_professional_way=91 m:percent_of_patients_who_reported_that_their_home_health_team_discussed_medicines_pain_and_home_safety_with_them=87 m:percent_of_patients_who_reported_yes_they_would_definitely_recommend_the_home_health_agency_to_friends_and_family=84

series e:m5jg-jg7i d:2017-03-27T17:01:14.000Z t:state=AR m:percent_of_patients_who_gave_their_home_health_agency_a_rating_of_9_or_10_on_a_scale_from_0_lowest_to_10_highest=88 m:percent_of_patients_who_reported_that_their_home_health_team_communicated_well_with_them=88 m:percent_of_patients_who_reported_that_their_home_health_team_gave_care_in_a_professional_way=91 m:percent_of_patients_who_reported_that_their_home_health_team_discussed_medicines_pain_and_home_safety_with_them=86 m:percent_of_patients_who_reported_yes_they_would_definitely_recommend_the_home_health_agency_to_friends_and_family=83
```

## Meta Commands

```ls
metric m:percent_of_patients_who_reported_that_their_home_health_team_gave_care_in_a_professional_way p:integer l:"Percent of patients who reported that their home health team gave care in a professional way" t:dataTypeName=percent

metric m:percent_of_patients_who_reported_that_their_home_health_team_communicated_well_with_them p:integer l:"Percent of patients who reported that their home health team communicated well with them" t:dataTypeName=percent

metric m:percent_of_patients_who_reported_that_their_home_health_team_discussed_medicines_pain_and_home_safety_with_them p:integer l:"Percent of patients who reported that their home health team discussed medicines, pain, and home safety with them" t:dataTypeName=percent

metric m:percent_of_patients_who_gave_their_home_health_agency_a_rating_of_9_or_10_on_a_scale_from_0_lowest_to_10_highest p:integer l:"Percent of patients who gave their home health agency a rating of 9 or 10 on a scale from 0 (lowest) to 10 (highest)" t:dataTypeName=percent

metric m:percent_of_patients_who_reported_yes_they_would_definitely_recommend_the_home_health_agency_to_friends_and_family p:integer l:"Percent of patients who reported YES, they would definitely recommend the home health agency to friends and family" t:dataTypeName=percent

entity e:m5jg-jg7i l:"Home Health Care - Patient survey (HHCAHPS) State Data" t:url=https://data.medicare.gov/api/views/m5jg-jg7i

property e:m5jg-jg7i t:meta.view v:id=m5jg-jg7i v:category="Home Health Compare" v:averageRating=0 v:name="Home Health Care - Patient survey (HHCAHPS) State Data"

property e:m5jg-jg7i t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:m5jg-jg7i t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:m5jg-jg7i t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=HomeHealthQualityQuestions@cms.hhs.gov v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```

## Top Records

```ls
| :updated_at | state | percent_of_patients_who_reported_that_their_home_health_team_gave_care_in_a_professional_way | percent_of_patients_who_reported_that_their_home_health_team_communicated_well_with_them | percent_of_patients_who_reported_that_their_home_health_team_discussed_medicines_pain_and_home_safety_with_them | percent_of_patients_who_gave_their_home_health_agency_a_rating_of_9_or_10_on_a_scale_from_0_lowest_to_10_highest | percent_of_patients_who_reported_yes_they_would_definitely_recommend_the_home_health_agency_to_friends_and_family | number_of_completed_surveys | response_rate | 
| =========== | ===== | ============================================================================================ | ======================================================================================== | =============================================================================================================== | ================================================================================================================ | ================================================================================================================= | =========================== | ============= | 
| 1490634074  | AK    | 88                                                                                           | 85                                                                                       | 82                                                                                                              | 84                                                                                                               | 81                                                                                                                |                             |               | 
| 1490634074  | AL    | 91                                                                                           | 89                                                                                       | 87                                                                                                              | 88                                                                                                               | 84                                                                                                                |                             |               | 
| 1490634074  | AR    | 91                                                                                           | 88                                                                                       | 86                                                                                                              | 88                                                                                                               | 83                                                                                                                |                             |               | 
| 1490634074  | AZ    | 87                                                                                           | 83                                                                                       | 79                                                                                                              | 81                                                                                                               | 75                                                                                                                |                             |               | 
| 1490634074  | CA    | 86                                                                                           | 83                                                                                       | 82                                                                                                              | 80                                                                                                               | 74                                                                                                                |                             |               | 
| 1490634074  | CO    | 88                                                                                           | 85                                                                                       | 82                                                                                                              | 83                                                                                                               | 78                                                                                                                |                             |               | 
| 1490634074  | CT    | 86                                                                                           | 84                                                                                       | 83                                                                                                              | 82                                                                                                               | 77                                                                                                                |                             |               | 
| 1490634074  | DC    | 80                                                                                           | 75                                                                                       | 72                                                                                                              | 71                                                                                                               | 60                                                                                                                |                             |               | 
| 1490634074  | DE    | 87                                                                                           | 84                                                                                       | 82                                                                                                              | 80                                                                                                               | 77                                                                                                                |                             |               | 
| 1490634074  | FL    | 89                                                                                           | 85                                                                                       | 81                                                                                                              | 85                                                                                                               | 79                                                                                                                |                             |               | 
```