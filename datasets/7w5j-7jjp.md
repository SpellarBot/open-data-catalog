# EWDD - Worksource Center Program Performance Outcomes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ewdd-worksource-center-program-performance-outcomes-22b8d) |
| Metadata | [Link](https://data.lacity.org/api/views/7w5j-7jjp) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/7w5j-7jjp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/7w5j-7jjp/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | 7w5j-7jjp |
| Name | EWDD - Worksource Center Program Performance Outcomes |
| Attribution | May Smith |
| Category | A Prosperous City |
| Tags | ewdd, worksource, program performance, outcomes |
| Created | 2014-05-29T22:16:44Z |
| Publication Date | 2014-05-29T22:20:58Z |

## Description

The WSC program, funded through the Workforce Investment Act (WIA); National Emergency Grant (NEG) and other competitive grants, provides employment training and placement services for adults and dislocated workers, with a special emphasis on vulnerable populations, including persons with disabilities, veterans, homeless, English-language learners and older workers.  Annual goals are established by California Employment Development Department and the US Department of Labor.

## Columns

```ls
| Included | Schema Type    | Field Name                                | Name                                        | Data Type | Render Type |
| ======== | ============== | ========================================= | =========================================== | ========= | =========== |
| No       | time           | :updated_at                               | updated_at                                  | meta_data | meta_data   |
| Yes      | numeric metric | metric_nbr                                | Metric Nbr                                  | number    | number      |
| Yes      | series tag     | metric                                    | Metric                                      | text      | text        |
| Yes      | series tag     | annual_goal                               | Annual Goal                                 | text      | text        |
| Yes      | numeric metric | 2_quarter_cumulative_goal_july_1_dec_31   | 2 Quarter Cumulative Goal: July 1 - Dec 31  | number    | number      |
| Yes      | numeric metric | 2_quarter_cumulative_actual_july_1_dec_31 | 2 Quarter Cumulative Actual:July 1 - Dec 31 | money     | money       |
| Yes      | numeric metric | percentage_of_2_quarter_goal              | Percentage of 2 Quarter Goal                | percent   | percent     |
| Yes      | numeric metric | of_annual_goal_completed                  | % of Annual Goal Completed                  | percent   | percent     |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:7w5j-7jjp d:2014-05-29T15:16:46.000Z t:metric="Universal Access Customers Served" t:annual_goal=150,000 m:2_quarter_cumulative_actual_july_1_dec_31=85200 m:metric_nbr=1.1 m:2_quarter_cumulative_goal_july_1_dec_31=75000 m:percentage_of_2_quarter_goal=114 m:of_annual_goal_completed=57

series e:7w5j-7jjp d:2014-05-29T15:16:46.000Z t:metric="WorkSource Adult Placements" t:annual_goal=1,586 m:2_quarter_cumulative_actual_july_1_dec_31=767 m:metric_nbr=1.2 m:2_quarter_cumulative_goal_july_1_dec_31=793 m:percentage_of_2_quarter_goal=97 m:of_annual_goal_completed=48

series e:7w5j-7jjp d:2014-05-29T15:16:46.000Z t:metric="WorkSource Average Wage at Placement" t:annual_goal=$11.78 m:2_quarter_cumulative_actual_july_1_dec_31=14.17 m:metric_nbr=1.3
```

## Meta Commands

```ls
metric m:metric_nbr p:float l:"Metric Nbr" t:dataTypeName=number

metric m:2_quarter_cumulative_goal_july_1_dec_31 p:integer l:"2 Quarter Cumulative Goal: July 1 - Dec 31" t:dataTypeName=number

metric m:2_quarter_cumulative_actual_july_1_dec_31 p:double l:"2 Quarter Cumulative Actual:July 1 - Dec 31" t:dataTypeName=money

metric m:percentage_of_2_quarter_goal p:integer l:"Percentage of 2 Quarter Goal" t:dataTypeName=percent

metric m:of_annual_goal_completed p:integer l:"% of Annual Goal Completed" t:dataTypeName=percent

entity e:7w5j-7jjp l:"EWDD - Worksource Center Program Performance Outcomes" t:attribution="May Smith" t:url=https://data.lacity.org/api/views/7w5j-7jjp

property e:7w5j-7jjp t:meta.view v:id=7w5j-7jjp v:category="A Prosperous City" v:averageRating=0 v:name="EWDD - Worksource Center Program Performance Outcomes" v:attribution="May Smith"

property e:7w5j-7jjp t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:7w5j-7jjp t:meta.view.owner v:id=utpt-bj92 v:profileImageUrlMedium=/api/users/utpt-bj92/profile_images/THUMB v:profileImageUrlLarge=/api/users/utpt-bj92/profile_images/LARGE v:screenName="Economic and Workforce Dev OpenData" v:profileImageUrlSmall=/api/users/utpt-bj92/profile_images/TINY v:displayName="Economic and Workforce Dev OpenData"

property e:7w5j-7jjp t:meta.view.tableauthor v:id=utpt-bj92 v:profileImageUrlMedium=/api/users/utpt-bj92/profile_images/THUMB v:profileImageUrlLarge=/api/users/utpt-bj92/profile_images/LARGE v:screenName="Economic and Workforce Dev OpenData" v:profileImageUrlSmall=/api/users/utpt-bj92/profile_images/TINY v:roleName=publisher v:displayName="Economic and Workforce Dev OpenData"
```

## Top Records

```ls
| :updated_at | metric_nbr | metric                                                                           | annual_goal | 2_quarter_cumulative_goal_july_1_dec_31 | 2_quarter_cumulative_actual_july_1_dec_31 | percentage_of_2_quarter_goal | of_annual_goal_completed | 
| =========== | ========== | ================================================================================ | =========== | ======================================= | ========================================= | ============================ | ======================== | 
| 1401376606  | 1.1        | Universal Access Customers Served                                                | 150,000     | 75000                                   | 85200                                     | 114                          | 57                       | 
| 1401376606  | 1.2        | WorkSource Adult Placements                                                      | 1,586       | 793                                     | 767                                       | 97                           | 48                       | 
| 1401376606  | 1.3        | WorkSource Average Wage at Placement                                             | $11.78      |                                         | 14.17                                     |                              |                          | 
| 1401376606  | 1.4        | WorkSource Dislocated Worker Placements                                          | 1,013       | 507                                     | 358                                       | 71                           | 35                       | 
| 1401376606  | 1.5        | WorkSource Dislocated Worker Average Wage at Placement                           | $13.33      |                                         | 17.67                                     |                              |                          | 
| 1401376606  | 1.6        | 3Rapid Response Served                                                           | 5,000       |                                         | 793                                       |                              |                          | 
| 1401376606  | 1.7        | National Emergency Grant (NEG): Back2Work Placements (Phase II)                  | 2,000       | 200                                     | 49                                        | 25                           | 2                        | 
| 1401376606  | 1.8        | CA Disability Initiative Employment Placements                                   | 158         | 79                                      | 229                                       | 290                          | 145                      | 
| 1401376606  | 1.9        | Veterans Employment Initiative                                                   | 10%         |                                         |                                           |                              |                          | 
| 1401376606  | 2.0        | CDBG/Living Independently Through Employment (LITE) Program: Homeless Placements | 120         | 90                                      | 103                                       | 114                          | 86                       | 
```