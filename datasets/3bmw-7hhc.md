# Chronic Absenteeism by District: 2012-13

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/chronic-absenteeism-by-district-2012-13) |
| Metadata | [Link](https://data.ct.gov/api/views/3bmw-7hhc) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/3bmw-7hhc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/3bmw-7hhc/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 3bmw-7hhc |
| Name | Chronic Absenteeism by District: 2012-13 |
| Attribution | State Department of Education |
| Category | Education |
| Tags | education, absenteeism, school, ctkids |
| Created | 2014-03-19T18:22:47Z |
| Publication Date | 2014-03-19T18:25:43Z |

## Description

Chronic absenteeism is defined as missing 10 percent or more of the days enrolled in a school year for any reason. Commonly reported aggregate attendance measures such as average daily attendance in many instances do not adequately highlight the extent of student absenteeism. This dataset contains aggregate chronic absenteeism rates at the overall district level and by selected student subgroups. Percentages are presented where the cell statistic is representative of 20 students or more; where the cell statistic is representative of fewer than 20 total students the cell is suppressed and an asterisk is displayed. National research1 as well as Connecticut education data2 highlight the association of chronic absenteeism to student academic achievement and high school graduation. Chronic absenteeism is also a key metric in the Department of Education?s school turnaround initiatives (i.e., Alliance Districts and Commissioner?s Network schools).

1 Balfanz, R., & Byrnes, V. (2012). Chronic Absenteeism: Summarizing What We Know From Nationally Available Data. Baltimore: Johns Hopkins University Center for Social Organizations of Schools.

2 http://www.sde.ct.gov/sde/lib/sde/pdf/deps/chronicabsenteeism/learningfromthedata.statepresentation.pdf

## Columns

```ls
| Included | Schema Type | Field Name                                       | Name                                               | Data Type | Render Type |
| ======== | =========== | ================================================ | ================================================== | ========= | =========== |
| Yes      | series tag  | district_number                                  | District Number                                    | text      | number      |
| Yes      | series tag  | district                                         | District                                           | text      | text        |
| Yes      | series tag  | total_of_students_chronically_absent_in_district | Total % of Students Chronically Absent in District | text      | number      |
| Yes      | series tag  | elementary_level_grade_k_3                       | Elementary Level (Grade K-3)                       | text      | text        |
| Yes      | series tag  | middle_grades_grades_4_8                         | Middle Grades (Grades 4-8)                         | text      | text        |
| Yes      | series tag  | secondary_school_grades_9_12                     | Secondary School (Grades 9-12)                     | text      | text        |
| Yes      | series tag  | american_indian_or_alaska_native                 | American Indian or Alaska Native                   | text      | text        |
| Yes      | series tag  | asian                                            | Asian                                              | text      | text        |
| Yes      | series tag  | black_or_african_american                        | Black or African American                          | text      | text        |
| Yes      | series tag  | hispaniclatino_of_any_race                       | HispanicLatino of any race                         | text      | text        |
| Yes      | series tag  | native_hawaiian_or_other_pacific_islander        | Native Hawaiian or Other Pacific Islander          | text      | text        |
| Yes      | series tag  | two_or_more_races                                | Two or More Races                                  | text      | text        |
| Yes      | series tag  | white                                            | White                                              | text      | text        |
| Yes      | series tag  | students_with_disabilities                       | Students with Disabilities                         | text      | text        |
| Yes      | series tag  | english_language_learner                         | English Language Learner                           | text      | text        |
| Yes      | series tag  | free_lunch_eligible                              | Free Lunch Eligible                                | text      | text        |
| Yes      | series tag  | reduced_lunch_eligible                           | Reduced Lunch Eligible                             | text      | text        |
| Yes      | series tag  | not_eligible_for_lunch_subsidies                 | Not Eligible for Lunch Subsidies                   | text      | text        |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:3bmw-7hhc d:2012-01-01T00:00:00.000Z t:black_or_african_american=- t:hispaniclatino_of_any_race=* t:white=* t:free_lunch_eligible=* t:students_with_disabilities=- t:two_or_more_races=- t:american_indian_or_alaska_native=- t:district_number=1 t:asian=- t:secondary_school_grades_9_12=- t:middle_grades_grades_4_8=* t:english_language_learner=- t:native_hawaiian_or_other_pacific_islander=- t:total_of_students_chronically_absent_in_district=3.8 t:not_eligible_for_lunch_subsidies=* t:elementary_level_grade_k_3=5.0 t:reduced_lunch_eligible=- t:district="Andover School District" m:row_number.3bmw-7hhc=1

series e:3bmw-7hhc d:2012-01-01T00:00:00.000Z t:black_or_african_american=17.6 t:hispaniclatino_of_any_race=14.4 t:white=13.1 t:free_lunch_eligible=17.7 t:students_with_disabilities=20.9 t:two_or_more_races=* t:american_indian_or_alaska_native=* t:district_number=2 t:asian=* t:secondary_school_grades_9_12=19.2 t:middle_grades_grades_4_8=12.6 t:english_language_learner=* t:native_hawaiian_or_other_pacific_islander=* t:total_of_students_chronically_absent_in_district=14.2 t:not_eligible_for_lunch_subsidies=12.2 t:elementary_level_grade_k_3=12.1 t:reduced_lunch_eligible=* t:district="Ansonia School District" m:row_number.3bmw-7hhc=2

series e:3bmw-7hhc d:2012-01-01T00:00:00.000Z t:black_or_african_american=- t:hispaniclatino_of_any_race=* t:white=7.1 t:free_lunch_eligible=* t:students_with_disabilities=* t:two_or_more_races=* t:american_indian_or_alaska_native=- t:district_number=3 t:asian=* t:secondary_school_grades_9_12=- t:middle_grades_grades_4_8=* t:english_language_learner=* t:native_hawaiian_or_other_pacific_islander=- t:total_of_students_chronically_absent_in_district=7.0 t:not_eligible_for_lunch_subsidies=* t:elementary_level_grade_k_3=* t:reduced_lunch_eligible=- t:district="Ashford School District" m:row_number.3bmw-7hhc=3
```

## Meta Commands

```ls
metric m:row_number.3bmw-7hhc p:long l:"Row Number"

entity e:3bmw-7hhc l:"Chronic Absenteeism by District: 2012-13" t:attribution="State Department of Education" t:url=https://data.ct.gov/api/views/3bmw-7hhc

property e:3bmw-7hhc t:meta.view v:id=3bmw-7hhc v:category=Education v:averageRating=0 v:name="Chronic Absenteeism by District: 2012-13" v:attribution="State Department of Education"

property e:3bmw-7hhc t:meta.view.license v:name="Public Domain"

property e:3bmw-7hhc t:meta.view.owner v:id=nyku-jy9c v:screenName="Stephanie O'Day" v:displayName="Stephanie O'Day"

property e:3bmw-7hhc t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| district_number | district                    | total_of_students_chronically_absent_in_district | elementary_level_grade_k_3 | middle_grades_grades_4_8 | secondary_school_grades_9_12 | american_indian_or_alaska_native | asian | black_or_african_american | hispaniclatino_of_any_race | native_hawaiian_or_other_pacific_islander | two_or_more_races | white | students_with_disabilities | english_language_learner | free_lunch_eligible | reduced_lunch_eligible | not_eligible_for_lunch_subsidies | 
| =============== | =========================== | ================================================ | ========================== | ======================== | ============================ | ================================ | ===== | ========================= | ========================== | ========================================= | ================= | ===== | ========================== | ======================== | =================== | ====================== | ================================ | 
| 1               | Andover School District     | 3.8                                              | 5.0                        | *                        | -                            | -                                | -     | -                         | *                          | -                                         | -                 | *     | -                          | -                        | *                   | -                      | *                                | 
| 2               | Ansonia School District     | 14.2                                             | 12.1                       | 12.6                     | 19.2                         | *                                | *     | 17.6                      | 14.4                       | *                                         | *                 | 13.1  | 20.9                       | *                        | 17.7                | *                      | 12.2                             | 
| 3               | Ashford School District     | 7.0                                              | *                          | *                        | -                            | -                                | *     | -                         | *                          | -                                         | *                 | 7.1   | *                          | *                        | *                   | -                      | *                                | 
| 4               | Avon School District        | 5.0                                              | 5.9                        | 5.0                      | 4.2                          | *                                | *     | *                         | *                          | -                                         | *                 | 4.5   | 9.9                        | *                        | 16.2                | *                      | 4.4                              | 
| 5               | Barkhamsted School District | 4.0                                              | *                          | *                        | -                            | -                                | -     | *                         | -                          | -                                         | *                 | *     | *                          | *                        | -                   | -                      | *                                | 
| 7               | Berlin School District      | 5.6                                              | 3.0                        | 6.2                      | 7.0                          | -                                | *     | *                         | 15.2                       | -                                         | *                 | 4.4   | 12.2                       | *                        | 16.9                | *                      | 4.1                              | 
| 8               | Bethany School District     | 5.6                                              | *                          | *                        | -                            | -                                | *     | *                         | *                          | -                                         | -                 | 5.4   | *                          | -                        | *                   | *                      | 4.8                              | 
| 9               | Bethel School District      | 6.8                                              | 3.9                        | 7.2                      | 8.6                          | -                                | *     | *                         | 7.2                        | -                                         | *                 | 6.5   | 15.5                       | *                        | 15.1                | *                      | 5.5                              | 
| 11              | Bloomfield School District  | 7.8                                              | 7.4                        | 5.1                      | 11.0                         | -                                | -     | 7.0                       | 14.9                       | -                                         | *                 | *     | 14.2                       | *                        | 10.4                | *                      | 6.1                              | 
| 12              | Bolton School District      | 3.6                                              | *                          | *                        | *                            | -                                | *     | *                         | *                          | -                                         | *                 | 2.6   | *                          | -                        | *                   | -                      | 2.6                              | 
```