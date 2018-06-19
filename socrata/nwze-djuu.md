# Breakfast, Lunch, And At-Risk Afterschool Meals Programs Participation

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/breakfast-lunch-and-at-risk-afterschool-meals-programs-participation-35d96) |
| Metadata | [Link](https://data.maryland.gov/api/views/nwze-djuu) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/nwze-djuu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/nwze-djuu/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | nwze-djuu |
| Name | Breakfast, Lunch, And At-Risk Afterschool Meals Programs Participation |
| Attribution | Department of Human Resources (DHR) |
| Category | Health and Human Services |
| Tags | dhr, hunger, childhood hunger, breakfast, lunch, education, meal |
| Created | 2013-02-09T01:05:49Z |
| Publication Date | 2017-04-06T20:43:25Z |

## Description

This dataset tracks participation in the Free/Reduced Cost School Breakfast and Lunch Meals as well as the At-Risk Afterschool Meals programs.

## Columns

```ls
| Included | Schema Type    | Field Name                                                    | Name                                                       | Data Type | Render Type |
| ======== | ============== | ============================================================= | ========================================================== | ========= | =========== |
| No       | time           | :updated_at                                                   | updated_at                                                 | meta_data | meta_data   |
| Yes      | series tag     | school_year                                                   | School Year                                                | text      | text        |
| Yes      | numeric metric | students_eligible_for_free_and_reduced_meals                  | Students Eligible for Free and Reduced Meals               | number    | number      |
| Yes      | numeric metric | free_reduced_school_breakfast_participation                   | Free/Reduced School Breakfast: Average Daily Participation | number    | number      |
| Yes      | numeric metric | free_reduced_school_lunch_participation                       | Free/Reduced School Lunch: Average Daily Participation     | number    | number      |
| Yes      | numeric metric | of_f_r_lunch_participants_that_eat_breakfast                  | % F/R Lunch Participants that eat Breakfast                | percent   | percent     |
| Yes      | numeric metric | school_breakfast_program_2015_participation_goal              | School Breakfast Program 2015 Participation Goal           | number    | number      |
| Yes      | numeric metric | at_risk_afterschool_meals_program_average_daily_participation | At-Risk Afterschool Program Avg. Daily Participation       | number    | number      |
| Yes      | numeric metric | of_f_r_lunch_participants_that_eat_afterschool_meals          | % F/R Lunch Participants that eat Afterschool Meals        | percent   | percent     |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:nwze-djuu d:2013-02-13T13:29:34.000Z t:school_year="SY 07-08" m:students_eligible_for_free_and_reduced_meals=284448 m:free_reduced_school_lunch_participation=193133 m:of_f_r_lunch_participants_that_eat_breakfast=44.6 m:school_breakfast_program_2015_participation_goal=0.7 m:free_reduced_school_breakfast_participation=86082

series e:nwze-djuu d:2013-02-13T13:29:40.000Z t:school_year="SY 08-09" m:students_eligible_for_free_and_reduced_meals=294122 m:free_reduced_school_lunch_participation=211291 m:of_f_r_lunch_participants_that_eat_breakfast=45.3 m:school_breakfast_program_2015_participation_goal=0.7 m:free_reduced_school_breakfast_participation=95618

series e:nwze-djuu d:2013-02-13T13:29:48.000Z t:school_year="SY 09-10" m:students_eligible_for_free_and_reduced_meals=326871 m:free_reduced_school_lunch_participation=228269 m:of_f_r_lunch_participants_that_eat_breakfast=45.6 m:school_breakfast_program_2015_participation_goal=0.7 m:of_f_r_lunch_participants_that_eat_afterschool_meals=1.5 m:free_reduced_school_breakfast_participation=104150 m:at_risk_afterschool_meals_program_average_daily_participation=3322
```

## Meta Commands

```ls
metric m:students_eligible_for_free_and_reduced_meals p:integer l:"Students Eligible for Free and Reduced Meals" t:dataTypeName=number

metric m:free_reduced_school_breakfast_participation p:integer l:"Free/Reduced School Breakfast: Average Daily Participation" t:dataTypeName=number

metric m:free_reduced_school_lunch_participation p:integer l:"Free/Reduced School Lunch: Average Daily Participation" t:dataTypeName=number

metric m:of_f_r_lunch_participants_that_eat_breakfast p:float l:"% F/R Lunch Participants that eat Breakfast" t:dataTypeName=percent

metric m:school_breakfast_program_2015_participation_goal p:float l:"School Breakfast Program 2015 Participation Goal" t:dataTypeName=number

metric m:at_risk_afterschool_meals_program_average_daily_participation p:integer l:"At-Risk Afterschool Program Avg. Daily Participation" t:dataTypeName=number

metric m:of_f_r_lunch_participants_that_eat_afterschool_meals p:double l:"% F/R Lunch Participants that eat Afterschool Meals" t:dataTypeName=percent

entity e:nwze-djuu l:"Breakfast, Lunch, And At-Risk Afterschool Meals Programs Participation" t:attribution="Department of Human Resources (DHR)" t:url=https://data.maryland.gov/api/views/nwze-djuu

property e:nwze-djuu t:meta.view v:id=nwze-djuu v:category="Health and Human Services" v:attributionLink=http://dhr.state.md.us v:averageRating=0 v:name="Breakfast, Lunch, And At-Risk Afterschool Meals Programs Participation" v:attribution="Department of Human Resources (DHR)"

property e:nwze-djuu t:meta.view.license v:name="Public Domain"

property e:nwze-djuu t:meta.view.owner v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"

property e:nwze-djuu t:meta.view.tableauthor v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"
```

## Top Records

```ls
| :updated_at | school_year | students_eligible_for_free_and_reduced_meals | free_reduced_school_breakfast_participation | free_reduced_school_lunch_participation | of_f_r_lunch_participants_that_eat_breakfast | school_breakfast_program_2015_participation_goal | at_risk_afterschool_meals_program_average_daily_participation | of_f_r_lunch_participants_that_eat_afterschool_meals | 
| =========== | =========== | ============================================ | =========================================== | ======================================= | ============================================ | ================================================ | ============================================================= | ==================================================== | 
| 1360762174  | SY 07-08    | 284448                                       | 86082                                       | 193133                                  | 44.6                                         | 0.7                                              |                                                               |                                                      | 
| 1360762180  | SY 08-09    | 294122                                       | 95618                                       | 211291                                  | 45.3                                         | 0.7                                              |                                                               |                                                      | 
| 1360762188  | SY 09-10    | 326871                                       | 104150                                      | 228269                                  | 45.6                                         | 0.7                                              | 3322                                                          | 1.5                                                  | 
| 1360762200  | SY 10-11    | 343569                                       | 113437                                      | 240564                                  | 47.2                                         | 0.7                                              | 8936                                                          | 3.7                                                  | 
| 1360762209  | SY 11-12    | 358373                                       | 133298                                      | 256735                                  | 51.9                                         | 0.7                                              | 11448                                                         | 4.5                                                  | 
| 1441106604  | SY 12-13    | 369619                                       | 149713                                      | 264574                                  | 57.1                                         | 0.7                                              | 24008                                                         | 6                                                    | 
| 1441106606  | SY 13-14    | 389284                                       | 162927                                      | 270803                                  | 61.2                                         | 0.7                                              | 24370                                                         | 8                                                    | 
```