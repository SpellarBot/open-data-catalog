# EWDD - Business Source Center Program Performance Objectives

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ewdd-business-source-center-program-performance-objectives-9e133) |
| Metadata | [Link](https://data.lacity.org/api/views/qqur-fdui) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/qqur-fdui/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/qqur-fdui/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | qqur-fdui |
| Name | EWDD - Business Source Center Program Performance Objectives |
| Attribution | May Smith |
| Category | A Prosperous City |
| Tags | ewdd, businesssource, business source, program performance, outcomes |
| Created | 2014-05-29T21:12:44Z |
| Publication Date | 2014-05-29T21:16:25Z |

## Description

The BSC Program, funded through the CDBG, provides entrepreneurial training, technical assistance and access to capital for micro-enterprise and start-up businesses.  The program promotes job creation for Angelenos by providing entrepreneurs and small businesses the support they need to start and/or expand their businesses.  Goals are established through HUD guidelines and local measures.

## Columns

```ls
| Included | Schema Type    | Field Name                               | Name                                       | Data Type | Render Type |
| ======== | ============== | ======================================== | ========================================== | ========= | =========== |
| No       | time           | :updated_at                              | updated_at                                 | meta_data | meta_data   |
| Yes      | numeric metric | metric_nbr                               | Metric Nbr                                 | number    | number      |
| Yes      | series tag     | metric                                   | Metric                                     | text      | text        |
| Yes      | numeric metric | annual_goal                              | Annual Goal                                | number    | number      |
| Yes      | numeric metric | 3_quarter_cumulative_goal_apr_1_dec_31   | 3 Quarter Cumulative Goal: Apr 1 - Dec 31  | number    | number      |
| Yes      | numeric metric | 3_quarter_cumulative_actual_apr_1_dec_31 | 3 Quarter Cumulative Actual:Apr 1 - Dec 31 | number    | number      |
| Yes      | numeric metric | percentage_of_3_quarter_goal             | Percentage of 3 Quarter Goal               | percent   | percent     |
| Yes      | numeric metric | of_annual_goal_completed                 | % of Annual Goal Completed                 | percent   | percent     |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:qqur-fdui d:2014-05-29T14:12:47.000Z t:metric="Total Capital Outlay" m:percentage_of_3_quarter_goal=153 m:metric_nbr=1.1 m:of_annual_goal_completed=115

series e:qqur-fdui d:2014-05-29T14:12:47.000Z t:metric="Number of Entrepreneurs Receiving Technical Assistance / Training" m:percentage_of_3_quarter_goal=176 m:3_quarter_cumulative_goal_apr_1_dec_31=600 m:metric_nbr=1.2 m:3_quarter_cumulative_actual_apr_1_dec_31=1057 m:annual_goal=800 m:of_annual_goal_completed=132

series e:qqur-fdui d:2014-05-29T14:12:47.000Z t:metric="Number of  Businesses Launched" m:percentage_of_3_quarter_goal=89 m:3_quarter_cumulative_goal_apr_1_dec_31=108 m:metric_nbr=1.3 m:3_quarter_cumulative_actual_apr_1_dec_31=96 m:annual_goal=144 m:of_annual_goal_completed=67
```

## Meta Commands

```ls
metric m:metric_nbr p:float l:"Metric Nbr" t:dataTypeName=number

metric m:annual_goal p:integer l:"Annual Goal" t:dataTypeName=number

metric m:3_quarter_cumulative_goal_apr_1_dec_31 p:integer l:"3 Quarter Cumulative Goal: Apr 1 - Dec 31" t:dataTypeName=number

metric m:3_quarter_cumulative_actual_apr_1_dec_31 p:integer l:"3 Quarter Cumulative Actual:Apr 1 - Dec 31" t:dataTypeName=number

metric m:percentage_of_3_quarter_goal p:integer l:"Percentage of 3 Quarter Goal" t:dataTypeName=percent

metric m:of_annual_goal_completed p:integer l:"% of Annual Goal Completed" t:dataTypeName=percent

entity e:qqur-fdui l:"EWDD - Business Source Center Program Performance Objectives" t:attribution="May Smith" t:url=https://data.lacity.org/api/views/qqur-fdui

property e:qqur-fdui t:meta.view v:id=qqur-fdui v:category="A Prosperous City" v:averageRating=0 v:name="EWDD - Business Source Center Program Performance Objectives" v:attribution="May Smith"

property e:qqur-fdui t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:qqur-fdui t:meta.view.owner v:id=utpt-bj92 v:profileImageUrlMedium=/api/users/utpt-bj92/profile_images/THUMB v:profileImageUrlLarge=/api/users/utpt-bj92/profile_images/LARGE v:screenName="Economic and Workforce Dev OpenData" v:profileImageUrlSmall=/api/users/utpt-bj92/profile_images/TINY v:displayName="Economic and Workforce Dev OpenData"

property e:qqur-fdui t:meta.view.tableauthor v:id=utpt-bj92 v:profileImageUrlMedium=/api/users/utpt-bj92/profile_images/THUMB v:profileImageUrlLarge=/api/users/utpt-bj92/profile_images/LARGE v:screenName="Economic and Workforce Dev OpenData" v:profileImageUrlSmall=/api/users/utpt-bj92/profile_images/TINY v:roleName=publisher v:displayName="Economic and Workforce Dev OpenData"
```

## Top Records

```ls
| :updated_at | metric_nbr | metric                                                            | annual_goal | 3_quarter_cumulative_goal_apr_1_dec_31 | 3_quarter_cumulative_actual_apr_1_dec_31 | percentage_of_3_quarter_goal | of_annual_goal_completed | 
| =========== | ========== | ================================================================= | =========== | ====================================== | ======================================== | ============================ | ======================== | 
| 1401372767  | 1.1        | Total Capital Outlay                                              |             |                                        |                                          | 153                          | 115                      | 
| 1401372767  | 1.2        | Number of Entrepreneurs Receiving Technical Assistance / Training | 800         | 600                                    | 1057                                     | 176                          | 132                      | 
| 1401372767  | 1.3        | Number of Businesses Launched                                     | 144         | 108                                    | 96                                       | 89                           | 67                       | 
| 1401372767  | 1.4        | Number of Loans Approved (Pre-startups)                           | 40          | 30                                     | 17                                       | 57                           | 43                       | 
| 1401372767  | 1.5        | Number of Loans Approved (Startups/Existing Business)             | 152         | 114                                    | 108                                      | 95                           | 71                       | 
| 1401372767  | 1.6        | Number of FTE Jobs Created                                        | 880         | 660                                    | 779                                      | 118                          | 89                       | 
| 1401372767  | 1.7        | Number of FTE Jobs Retained                                       | 336         | 252                                    | 196                                      | 78                           | 58                       | 
```