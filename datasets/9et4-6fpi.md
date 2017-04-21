# EWDD - Day Labor Program

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ewdd-day-labor-program-321bf) |
| Metadata | [Link](https://data.lacity.org/api/views/9et4-6fpi) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/9et4-6fpi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/9et4-6fpi/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | 9et4-6fpi |
| Name | EWDD - Day Labor Program |
| Attribution | May Smith |
| Category | A Prosperous City |
| Tags | ewdd, day labor, program performance, outcomes |
| Created | 2014-05-29T22:36:13Z |
| Publication Date | 2014-05-29T22:38:05Z |

## Description

The Day Labor program, funded through CDBG, provides short-term employment and support services to unemployed Angelenos.  Goals for the program are established by federal regulations and local measures.

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
series e:9et4-6fpi d:2014-05-29T15:36:17.000Z t:metric="Number of Single-Day (short-term) Jobs Obtained" m:percentage_of_3_quarter_goal=162 m:3_quarter_cumulative_goal_apr_1_dec_31=12750 m:metric_nbr=1.1 m:3_quarter_cumulative_actual_apr_1_dec_31=20653 m:annual_goal=17000 m:of_annual_goal_completed=121

series e:9et4-6fpi d:2014-05-29T15:36:17.000Z t:metric="Number of Day Labor Center client visits for job placement" m:percentage_of_3_quarter_goal=109 m:3_quarter_cumulative_goal_apr_1_dec_31=65100 m:metric_nbr=1.2 m:3_quarter_cumulative_actual_apr_1_dec_31=71127 m:annual_goal=86800 m:of_annual_goal_completed=82

series e:9et4-6fpi d:2014-05-29T15:36:17.000Z t:metric="Number of Additional Services Provided" m:percentage_of_3_quarter_goal=325 m:3_quarter_cumulative_goal_apr_1_dec_31=8190 m:metric_nbr=1.3 m:3_quarter_cumulative_actual_apr_1_dec_31=26594 m:annual_goal=10920 m:of_annual_goal_completed=244
```

## Meta Commands

```ls
metric m:metric_nbr p:float l:"Metric Nbr" t:dataTypeName=number

metric m:annual_goal p:integer l:"Annual Goal" t:dataTypeName=number

metric m:3_quarter_cumulative_goal_apr_1_dec_31 p:integer l:"3 Quarter Cumulative Goal: Apr 1 - Dec 31" t:dataTypeName=number

metric m:3_quarter_cumulative_actual_apr_1_dec_31 p:integer l:"3 Quarter Cumulative Actual:Apr 1 - Dec 31" t:dataTypeName=number

metric m:percentage_of_3_quarter_goal p:integer l:"Percentage of 3 Quarter Goal" t:dataTypeName=percent

metric m:of_annual_goal_completed p:integer l:"% of Annual Goal Completed" t:dataTypeName=percent

entity e:9et4-6fpi l:"EWDD - Day Labor Program" t:attribution="May Smith" t:url=https://data.lacity.org/api/views/9et4-6fpi

property e:9et4-6fpi t:meta.view v:id=9et4-6fpi v:category="A Prosperous City" v:averageRating=0 v:name="EWDD - Day Labor Program" v:attribution="May Smith"

property e:9et4-6fpi t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:9et4-6fpi t:meta.view.owner v:id=utpt-bj92 v:profileImageUrlMedium=/api/users/utpt-bj92/profile_images/THUMB v:profileImageUrlLarge=/api/users/utpt-bj92/profile_images/LARGE v:screenName="Economic and Workforce Dev OpenData" v:profileImageUrlSmall=/api/users/utpt-bj92/profile_images/TINY v:displayName="Economic and Workforce Dev OpenData"

property e:9et4-6fpi t:meta.view.tableauthor v:id=utpt-bj92 v:profileImageUrlMedium=/api/users/utpt-bj92/profile_images/THUMB v:profileImageUrlLarge=/api/users/utpt-bj92/profile_images/LARGE v:screenName="Economic and Workforce Dev OpenData" v:profileImageUrlSmall=/api/users/utpt-bj92/profile_images/TINY v:roleName=publisher v:displayName="Economic and Workforce Dev OpenData"
```

## Top Records

```ls
| :updated_at | metric_nbr | metric                                                     | annual_goal | 3_quarter_cumulative_goal_apr_1_dec_31 | 3_quarter_cumulative_actual_apr_1_dec_31 | percentage_of_3_quarter_goal | of_annual_goal_completed | 
| =========== | ========== | ========================================================== | =========== | ====================================== | ======================================== | ============================ | ======================== | 
| 1401377777  | 1.1        | Number of Single-Day (short-term) Jobs Obtained            | 17000       | 12750                                  | 20653                                    | 162                          | 121                      | 
| 1401377777  | 1.2        | Number of Day Labor Center client visits for job placement | 86800       | 65100                                  | 71127                                    | 109                          | 82                       | 
| 1401377777  | 1.3        | Number of Additional Services Provided                     | 10920       | 8190                                   | 26594                                    | 325                          | 244                      | 
| 1401377777  | 1.4        | Increase Day Labor Income through Short-term Jobs          |             | 1125000                                |                                          | 139                          | 105                      | 
```