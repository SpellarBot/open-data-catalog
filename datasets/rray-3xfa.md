# Chronic Absenteeism by District: 2011-12

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/chronic-absenteeism-by-district-2011-12) |
| Metadata | [Link](https://data.ct.gov/api/views/rray-3xfa) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/rray-3xfa/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/rray-3xfa/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | rray-3xfa |
| Name | Chronic Absenteeism by District: 2011-12 |
| Attribution | State Department of Education |
| Category | Education |
| Tags | education, absenteeism, school |
| Created | 2014-03-21T15:35:35Z |
| Publication Date | 2014-03-21T15:37:37Z |

## Description

Chronic absenteeism is defined as missing 10 percent or more of the days enrolled in a school year for any reason. Commonly reported aggregate attendance measures such as average daily attendance in many instances do not adequately highlight the extent of student absenteeism. This dataset contains aggregate chronic absenteeism rates at the overall district level and by selected student subgroups. Percentages are presented where the cell statistic is representative of 20 students or more; where the cell statistic is representative of fewer than 20 total students the cell is suppressed and an asterisk is displayed. National research1 as well as Connecticut education data2 highlight the association of chronic absenteeism to student academic achievement and high school graduation. Chronic absenteeism is also a key metric in the Department of Education?s school turnaround initiatives (i.e., Alliance Districts and Commissioner?s Network schools).

1 Balfanz, R., & Byrnes, V. (2012). Chronic Absenteeism: Summarizing What We Know From Nationally Available Data. Baltimore: Johns Hopkins University Center for Social Organizations of Schools.

2 http://www.sde.ct.gov/sde/lib/sde/pdf/deps/chronicabsenteeism/learningfromthedata.statepresentation.pdf

## Columns

```ls
| Included | Schema Type    | Field Name                                       | Name                                               | Data Type | Render Type |
| ======== | ============== | ================================================ | ================================================== | ========= | =========== |
| Yes      | series tag     | district_number                                  | District Number                                    | text      | number      |
| Yes      | series tag     | district                                         | District                                           | text      | text        |
| Yes      | series tag     | total_of_students_chronically_absent_in_district | Total % of Students Chronically Absent in District | text      | number      |
| Yes      | numeric metric | elementary_level_grades_k_3                      | Elementary Level(Grades K-3)                       | number    | number      |
| Yes      | numeric metric | middle_grades_grades_4_8                         | Middle Grades (Grades 4-8)                         | number    | number      |
| Yes      | numeric metric | secondary_school_grades_9_12                     | Secondary School(Grades 9-12)                      | number    | number      |
| Yes      | numeric metric | american_indian_or_alaska_native                 | American Indian or Alaska Native                   | number    | number      |
| Yes      | numeric metric | asian                                            | Asian                                              | number    | number      |
| Yes      | numeric metric | black_or_african_american                        | Black or African American                          | number    | number      |
| Yes      | numeric metric | hispaniclatino_of_any_race                       | HispanicLatino of any race                         | number    | number      |
| Yes      | numeric metric | native_hawaiian_or_other_pacific_islander        | Native Hawaiian or Other Pacific Islander          | number    | number      |
| Yes      | numeric metric | two_or_more_races                                | Two or More Races                                  | number    | number      |
| Yes      | numeric metric | white                                            | White                                              | number    | number      |
| Yes      | numeric metric | students_with_disabilities                       | Students with Disabilities                         | number    | number      |
| Yes      | numeric metric | english_language_learner                         | English Language Learner                           | number    | number      |
| Yes      | numeric metric | free_lunch_eligible                              | Free Lunch Eligible                                | number    | number      |
| Yes      | numeric metric | reduced_lunch_eligible                           | Reduced Lunch Eligible                             | number    | number      |
| Yes      | numeric metric | not_eligible_for_lunch_subsidies                 | Not Eligible for Lunch Subsidies                   | number    | number      |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:rray-3xfa d:2011-01-01T00:00:00.000Z t:total_of_students_chronically_absent_in_district=12.3 t:district="Ansonia School District" t:district_number=2 m:black_or_african_american=16.5 m:hispaniclatino_of_any_race=14.4 m:middle_grades_grades_4_8=11.8 m:not_eligible_for_lunch_subsidies=7.1 m:white=9.6 m:free_lunch_eligible=16.2 m:reduced_lunch_eligible=9 m:students_with_disabilities=19.5 m:elementary_level_grades_k_3=13.4 m:secondary_school_grades_9_12=11.8

series e:rray-3xfa d:2011-01-01T00:00:00.000Z t:total_of_students_chronically_absent_in_district=9.1 t:district="Ashford School District" t:district_number=3 m:middle_grades_grades_4_8=9.3 m:not_eligible_for_lunch_subsidies=7.4 m:white=8.8

series e:rray-3xfa d:2011-01-01T00:00:00.000Z t:total_of_students_chronically_absent_in_district=4.3 t:district="Avon School District" t:district_number=4 m:middle_grades_grades_4_8=5.2 m:not_eligible_for_lunch_subsidies=3.8 m:white=4 m:free_lunch_eligible=14.9 m:students_with_disabilities=7 m:elementary_level_grades_k_3=4.7 m:secondary_school_grades_9_12=2.9
```

## Meta Commands

```ls
metric m:elementary_level_grades_k_3 p:float l:"Elementary Level(Grades K-3)" t:dataTypeName=number

metric m:middle_grades_grades_4_8 p:float l:"Middle Grades (Grades 4-8)" t:dataTypeName=number

metric m:secondary_school_grades_9_12 p:float l:"Secondary School(Grades 9-12)" t:dataTypeName=number

metric m:american_indian_or_alaska_native p:float l:"American Indian or Alaska Native" t:dataTypeName=number

metric m:asian p:float l:Asian t:dataTypeName=number

metric m:black_or_african_american p:float l:"Black or African American" t:dataTypeName=number

metric m:hispaniclatino_of_any_race p:float l:"HispanicLatino of any race" t:dataTypeName=number

metric m:native_hawaiian_or_other_pacific_islander p:float l:"Native Hawaiian or Other Pacific Islander" t:dataTypeName=number

metric m:two_or_more_races p:float l:"Two or More Races" t:dataTypeName=number

metric m:white p:float l:White t:dataTypeName=number

metric m:students_with_disabilities p:float l:"Students with Disabilities" t:dataTypeName=number

metric m:english_language_learner p:float l:"English Language Learner" t:dataTypeName=number

metric m:free_lunch_eligible p:float l:"Free Lunch Eligible" t:dataTypeName=number

metric m:reduced_lunch_eligible p:float l:"Reduced Lunch Eligible" t:dataTypeName=number

metric m:not_eligible_for_lunch_subsidies p:float l:"Not Eligible for Lunch Subsidies" t:dataTypeName=number

entity e:rray-3xfa l:"Chronic Absenteeism by District: 2011-12" t:attribution="State Department of Education" t:url=https://data.ct.gov/api/views/rray-3xfa

property e:rray-3xfa t:meta.view v:id=rray-3xfa v:category=Education v:averageRating=0 v:name="Chronic Absenteeism by District: 2011-12" v:attribution="State Department of Education"

property e:rray-3xfa t:meta.view.license v:name="Public Domain"

property e:rray-3xfa t:meta.view.owner v:id=nyku-jy9c v:screenName="Stephanie O'Day" v:displayName="Stephanie O'Day"

property e:rray-3xfa t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| district_number | district                    | total_of_students_chronically_absent_in_district | elementary_level_grades_k_3 | middle_grades_grades_4_8 | secondary_school_grades_9_12 | american_indian_or_alaska_native | asian | black_or_african_american | hispaniclatino_of_any_race | native_hawaiian_or_other_pacific_islander | two_or_more_races | white | students_with_disabilities | english_language_learner | free_lunch_eligible | reduced_lunch_eligible | not_eligible_for_lunch_subsidies | 
| =============== | =========================== | ================================================ | =========================== | ======================== | ============================ | ================================ | ===== | ========================= | ========================== | ========================================= | ================= | ===== | ========================== | ======================== | =================== | ====================== | ================================ | 
| 1               | Andover School District     | 0.7                                              |                             |                          |                              |                                  |       |                           |                            |                                           |                   |       |                            |                          |                     |                        |                                  | 
| 2               | Ansonia School District     | 12.3                                             | 13.4                        | 11.8                     | 11.8                         |                                  |       | 16.5                      | 14.4                       |                                           |                   | 9.6   | 19.5                       |                          | 16.2                | 9.0                    | 7.1                              | 
| 3               | Ashford School District     | 9.1                                              |                             | 9.3                      |                              |                                  |       |                           |                            |                                           |                   | 8.8   |                            |                          |                     |                        | 7.4                              | 
| 4               | Avon School District        | 4.3                                              | 4.7                         | 5.2                      | 2.9                          |                                  |       |                           |                            |                                           |                   | 4.0   | 7.0                        |                          | 14.9                |                        | 3.8                              | 
| 5               | Barkhamsted School District | 3.2                                              |                             |                          |                              |                                  |       |                           |                            |                                           |                   |       |                            |                          |                     |                        |                                  | 
| 7               | Berlin School District      | 5.8                                              | 2.5                         | 6.3                      | 7.8                          |                                  |       |                           | 10.4                       |                                           |                   | 5.0   | 14.7                       |                          | 21.2                |                        | 4.1                              | 
| 8               | Bethany School District     | 3.2                                              |                             |                          |                              |                                  |       |                           |                            |                                           |                   |       |                            |                          |                     |                        |                                  | 
| 9               | Bethel School District      | 6.1                                              | 4.2                         | 5.9                      | 7.7                          |                                  |       |                           | 7.0                        |                                           |                   | 5.6   | 15.6                       |                          | 15.5                |                        | 4.3                              | 
| 11              | Bloomfield School District  | 7.4                                              | 6.3                         | 5.9                      | 9.7                          |                                  |       | 6.8                       | 13.6                       |                                           |                   |       | 14.9                       |                          | 10.9                |                        | 4.4                              | 
| 12              | Bolton School District      | 2.6                                              |                             |                          |                              |                                  |       |                           |                            |                                           |                   |       |                            |                          |                     |                        |                                  | 
```