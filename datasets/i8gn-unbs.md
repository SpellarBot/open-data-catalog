# Free/Reduced Breakfast and Lunch Programs Participation by Month

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/free-reduced-breakfast-and-lunch-programs-participation-by-month-25102) |
| Metadata | [Link](https://data.maryland.gov/api/views/i8gn-unbs) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/i8gn-unbs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/i8gn-unbs/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | i8gn-unbs |
| Name | Free/Reduced Breakfast and Lunch Programs Participation by Month |
| Attribution | Department of Human Resources (DHR) |
| Category | Health and Human Services |
| Tags | dhr, hunger, childhood hunger, gdu |
| Created | 2013-02-14T00:17:46Z |
| Publication Date | 2015-09-02T14:47:14Z |

## Description

This dataset tracks monthly participation in the Free/Reduced Cost School Breakfast and Lunch Meals programs.

## Columns

```ls
| Included | Schema Type    | Field Name                                        | Name                                               | Data Type | Render Type |
| ======== | ============== | ================================================= | ================================================== | ========= | =========== |
| No       | time           | :updated_at                                       | updated_at                                         | meta_data | meta_data   |
| Yes      | series tag     | month                                             | Month                                              | text      | text        |
| Yes      | numeric metric | f_r_breakfast_program_average_daily_participation | F/R Breakfast Program: Average Daily Participation | number    | number      |
| Yes      | numeric metric | f_r_lunch_program_average_daily_participation     | F/R Lunch Program: Average Daily Participation     | number    | number      |
| Yes      | numeric metric | f_r_lunch_participants_that_eat_breakfast         | % F/R Lunch Participants that Eat Breakfast        | percent   | percent     |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:i8gn-unbs d:2015-09-01T12:05:28.000Z t:month=12-Jan m:f_r_lunch_participants_that_eat_breakfast=51.65 m:f_r_lunch_program_average_daily_participation=266298 m:f_r_breakfast_program_average_daily_participation=137533

series e:i8gn-unbs d:2015-09-01T12:05:28.000Z t:month=12-Feb m:f_r_lunch_participants_that_eat_breakfast=51.52 m:f_r_lunch_program_average_daily_participation=270534 m:f_r_breakfast_program_average_daily_participation=139382

series e:i8gn-unbs d:2015-09-01T12:05:28.000Z t:month=12-Mar m:f_r_lunch_participants_that_eat_breakfast=52.41 m:f_r_lunch_program_average_daily_participation=271593 m:f_r_breakfast_program_average_daily_participation=142335
```

## Meta Commands

```ls
metric m:f_r_breakfast_program_average_daily_participation p:integer l:"F/R Breakfast Program: Average Daily Participation" t:dataTypeName=number

metric m:f_r_lunch_program_average_daily_participation p:integer l:"F/R Lunch Program: Average Daily Participation" t:dataTypeName=number

metric m:f_r_lunch_participants_that_eat_breakfast p:float l:"% F/R Lunch Participants that Eat Breakfast" t:dataTypeName=percent

entity e:i8gn-unbs l:"Free/Reduced Breakfast and Lunch Programs Participation by Month" t:attribution="Department of Human Resources (DHR)" t:url=https://data.maryland.gov/api/views/i8gn-unbs

property e:i8gn-unbs t:meta.view v:id=i8gn-unbs v:category="Health and Human Services" v:attributionLink=http://dhr.state.md.us v:averageRating=0 v:name="Free/Reduced Breakfast and Lunch Programs Participation by Month" v:attribution="Department of Human Resources (DHR)"

property e:i8gn-unbs t:meta.view.owner v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"

property e:i8gn-unbs t:meta.view.tableauthor v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"
```

## Top Records

```ls
| :updated_at | month  | f_r_breakfast_program_average_daily_participation | f_r_lunch_program_average_daily_participation | f_r_lunch_participants_that_eat_breakfast | 
| =========== | ====== | ================================================= | ============================================= | ========================================= | 
| 1441109128  | 12-Jan | 137533                                            | 266298                                        | 51.65                                     | 
| 1441109128  | 12-Feb | 139382                                            | 270534                                        | 51.52                                     | 
| 1441109128  | 12-Mar | 142335                                            | 271593                                        | 52.41                                     | 
| 1441109128  | 12-Apr | 141452                                            | 268843                                        | 52.62                                     | 
| 1441109128  | 12-May | 141179                                            | 261331                                        | 54.02                                     | 
| 1441109128  | 12-Jun | 105238                                            | 192374                                        | 54.70                                     | 
| 1441109128  | 12-Jul | 1769                                              | 1812                                          | 97.63                                     | 
| 1441109128  | 12-Aug | 114036                                            | 229135                                        | 49.77                                     | 
| 1441109128  | 12-Sep | 148698                                            | 264167                                        | 56.29                                     | 
| 1441109128  | 12-Oct | 152198                                            | 266731                                        | 57.06                                     | 
```