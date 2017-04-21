# School Assessment Outcomes and Higher Education Degrees

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/school-assessment-outcomes-and-higher-education-degrees-a172a) |
| Metadata | [Link](https://data.maryland.gov/api/views/xnv4-iwf6) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/xnv4-iwf6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/xnv4-iwf6/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | xnv4-iwf6 |
| Name | School Assessment Outcomes and Higher Education Degrees |
| Attribution | MSDE |
| Category | Education |
| Tags | maryland state department of education, msde, education, higher education, college, university, school, ap, advanced placement, student achievement, gopi, performance improvement |
| Created | 2012-08-21T00:48:20Z |
| Publication Date | 2015-10-09T19:51:56Z |

## Description

This dataset shows broad performance metrics for education for Maryland as a whole, from School Years 2005/2006 to 2013/2014. Data are provided by the Maryland State Department of Education (MSDE) and were originally submitted to the Governor's Office.

## Columns

```ls
| Included | Schema Type    | Field Name                                           | Name                                                 | Data Type | Render Type |
| ======== | ============== | ==================================================== | ==================================================== | ========= | =========== |
| No       | time           | :updated_at                                          | updated_at                                           | meta_data | meta_data   |
| Yes      | series tag     | year                                                 | Year                                                 | text      | text        |
| Yes      | numeric metric | number_of_ap_exams_taken                             | Number of AP Exams Taken                             | number    | number      |
| Yes      | numeric metric | students_taking_ap_exams                             | Students Taking AP Exams                             | number    | number      |
| Yes      | numeric metric | children_entering_kindergarden_fully_ready           | Children Entering Kindergarden Fully Ready           | percent   | percent     |
| Yes      | numeric metric | number_of_ap_exams_taken_with_a_score_of_3_or_higher | Number of AP Exams Taken with a Score of 3 or Higher | number    | number      |
| Yes      | numeric metric | number_of_associate_s_degrees_awarded_in_maryland    | Number of Associates Degrees Awarded in Maryland     | number    | number      |
| Yes      | numeric metric | middle_school_math_msa_proficiency                   | Middle School Math MSA Proficiency                   | percent   | percent     |
| Yes      | numeric metric | stem_college_graduates                               | STEM College Graduates                               | number    | number      |
| Yes      | numeric metric | middle_school_reading_msa_proficiency                | Middle School Reading MSA Proficiency                | percent   | percent     |
| Yes      | numeric metric | number_of_bachelor_s_degrees_awarded_in_maryland     | Number of Bachelors Degrees Awarded in Maryland      | number    | number      |
| Yes      | numeric metric | elementary_school_math_msa_proficiency               | Elementary School Math MSA Proficiency               | percent   | percent     |
| Yes      | numeric metric | elementary_school_reading_msa_proficiency            | Elementary School Reading MSA Proficiency            | percent   | percent     |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:xnv4-iwf6 d:2014-03-12T10:25:31.000Z t:year=2007-2008 m:number_of_bachelor_s_degrees_awarded_in_maryland=26069 m:middle_school_math_msa_proficiency=68.5 m:students_taking_ap_exams=42349 m:number_of_associate_s_degrees_awarded_in_maryland=11051 m:children_entering_kindergarden_fully_ready=68 m:number_of_ap_exams_taken_with_a_score_of_3_or_higher=47103 m:number_of_ap_exams_taken=78094 m:elementary_school_reading_msa_proficiency=86.1 m:middle_school_reading_msa_proficiency=78.5 m:elementary_school_math_msa_proficiency=83.9 m:stem_college_graduates=9613

series e:xnv4-iwf6 d:2014-03-12T10:25:43.000Z t:year=2008-2009 m:number_of_bachelor_s_degrees_awarded_in_maryland=26684 m:middle_school_math_msa_proficiency=71.2 m:students_taking_ap_exams=45942 m:number_of_associate_s_degrees_awarded_in_maryland=11287 m:children_entering_kindergarden_fully_ready=73 m:number_of_ap_exams_taken_with_a_score_of_3_or_higher=52154 m:number_of_ap_exams_taken=85235 m:elementary_school_reading_msa_proficiency=87 m:middle_school_reading_msa_proficiency=81.8 m:elementary_school_math_msa_proficiency=84.9 m:stem_college_graduates=9777

series e:xnv4-iwf6 d:2014-03-12T10:26:03.000Z t:year=2010-2011 m:number_of_bachelor_s_degrees_awarded_in_maryland=28701 m:middle_school_math_msa_proficiency=73.7 m:students_taking_ap_exams=52518 m:number_of_associate_s_degrees_awarded_in_maryland=13539 m:children_entering_kindergarden_fully_ready=81 m:number_of_ap_exams_taken_with_a_score_of_3_or_higher=57573 m:number_of_ap_exams_taken=97756 m:elementary_school_reading_msa_proficiency=88 m:middle_school_reading_msa_proficiency=83.5 m:elementary_school_math_msa_proficiency=86.3 m:stem_college_graduates=11243
```

## Meta Commands

```ls
metric m:number_of_ap_exams_taken p:integer l:"Number of AP Exams Taken" t:dataTypeName=number

metric m:students_taking_ap_exams p:integer l:"Students Taking AP Exams" t:dataTypeName=number

metric m:children_entering_kindergarden_fully_ready p:integer l:"Children Entering Kindergarden Fully Ready" t:dataTypeName=percent

metric m:number_of_ap_exams_taken_with_a_score_of_3_or_higher p:integer l:"Number of AP Exams Taken with a Score of 3 or Higher" t:dataTypeName=number

metric m:number_of_associate_s_degrees_awarded_in_maryland p:integer l:"Number of Associates Degrees Awarded in Maryland" t:dataTypeName=number

metric m:middle_school_math_msa_proficiency p:float l:"Middle School Math MSA Proficiency" t:dataTypeName=percent

metric m:stem_college_graduates p:integer l:"STEM College Graduates" t:dataTypeName=number

metric m:middle_school_reading_msa_proficiency p:float l:"Middle School Reading MSA Proficiency" t:dataTypeName=percent

metric m:number_of_bachelor_s_degrees_awarded_in_maryland p:integer l:"Number of Bachelors Degrees Awarded in Maryland" t:dataTypeName=number

metric m:elementary_school_math_msa_proficiency p:float l:"Elementary School Math MSA Proficiency" t:dataTypeName=percent

metric m:elementary_school_reading_msa_proficiency p:float l:"Elementary School Reading MSA Proficiency" t:dataTypeName=percent

entity e:xnv4-iwf6 l:"School Assessment Outcomes and Higher Education Degrees" t:attribution=MSDE t:url=https://data.maryland.gov/api/views/xnv4-iwf6

property e:xnv4-iwf6 t:meta.view v:id=xnv4-iwf6 v:category=Education v:attributionLink=http://www.marylandpublicschools.org/msde v:averageRating=0 v:name="School Assessment Outcomes and Higher Education Degrees" v:attribution=MSDE

property e:xnv4-iwf6 t:meta.view.license v:name="Public Domain"

property e:xnv4-iwf6 t:meta.view.owner v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"

property e:xnv4-iwf6 t:meta.view.tableauthor v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"
```

## Top Records

```ls
| :updated_at | year      | number_of_ap_exams_taken | students_taking_ap_exams | children_entering_kindergarden_fully_ready | number_of_ap_exams_taken_with_a_score_of_3_or_higher | number_of_associate_s_degrees_awarded_in_maryland | middle_school_math_msa_proficiency | stem_college_graduates | middle_school_reading_msa_proficiency | number_of_bachelor_s_degrees_awarded_in_maryland | elementary_school_math_msa_proficiency | elementary_school_reading_msa_proficiency | 
| =========== | ========= | ======================== | ======================== | ========================================== | ==================================================== | ================================================= | ================================== | ====================== | ===================================== | ================================================ | ====================================== | ========================================= | 
| 1394619931  | 2007-2008 | 78094                    | 42349                    | 68                                         | 47103                                                | 11051                                             | 68.5                               | 9613                   | 78.5                                  | 26069                                            | 83.9                                   | 86.1                                      | 
| 1394619943  | 2008-2009 | 85235                    | 45942                    | 73                                         | 52154                                                | 11287                                             | 71.2                               | 9777                   | 81.8                                  | 26684                                            | 84.9                                   | 87                                        | 
| 1394619963  | 2010-2011 | 97756                    | 52518                    | 81                                         | 57573                                                | 13539                                             | 73.7                               | 11243                  | 83.5                                  | 28701                                            | 86.3                                   | 88                                        | 
| 1398863715  | 2006-2007 | 71278                    | 38456                    | 67                                         | 45029                                                | 10415                                             | 63.3                               | 9440                   | 71.7                                  | 25586                                            | 81                                     | 81.1                                      | 
| 1398863727  | 2009-2010 | 91471                    | 49506                    | 78                                         | 54370                                                | 12075                                             | 72.6                               | 10530                  | 82.8                                  | 27312                                            | 86.4                                   | 86.9                                      | 
| 1441017964  | 2005-2006 | 65700                    | 35583                    | 60                                         | 41918                                                | 10141                                             | 60.2                               | 9544                   | 69.9                                  | 25484                                            | 78.1                                   | 78.9                                      | 
| 1441018988  | 2011-2012 | 102774                   | 55065                    | 83                                         | 62952                                                | 14268                                             | 76.2                               | 11850                  | 82.1                                  | 30312                                            | 87.7                                   | 88.2                                      | 
| 1441019008  | 2012-2013 | 108471                   | 57236                    | 82                                         | 65460                                                | 14759                                             | 72.2                               | 13082                  | 83.4                                  | 31088                                            | 83.9                                   | 86.4                                      | 
| 1444394572  | 2013-2014 | 109279                   | 58039                    | 83                                         | 66538                                                | 15081                                             | 63.1                               |                        | 79.6                                  | 31461                                            | 75.8                                   | 84.3                                      | 
```