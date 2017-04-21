# Jobs for Jacksonians

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/jobs-for-jacksonians) |
| Metadata | [Link](https://data.jacksonms.gov/api/views/fj2t-2ps5) |
| Data: JSON | [100 Rows](https://data.jacksonms.gov/api/views/fj2t-2ps5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.jacksonms.gov/api/views/fj2t-2ps5/rows.csv?max_rows=100) |
| Host | data.jacksonms.gov |
| Id | fj2t-2ps5 |
| Name | Jobs for Jacksonians |
| Attribution | City of Jackson |
| Category | Economic Development |
| Tags | jobs, job readiness, jobs for jacksonians, city of jackson, economic development, unemployment |
| Created | 2016-03-07T20:53:51Z |
| Publication Date | 2016-09-07T15:57:11Z |

## Description

This data set details the monthly progress of the Jobs for Jacksonians program which is housed in the City's Economic Development division of the Planning Department. It shows the City's passion to ensure that Jacksonians are afforded work opportunities throughout the City. This information is updated monthly.

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type     | Render Type   |
| ======== | ============== | ======================== | ======================== | ============= | ============= |
| Yes      | time           | dates                    | Dates                    | calendar_date | calendar_date |
| Yes      | numeric metric | career_plan_hires        | Career Plan Hires        | number        | number        |
| Yes      | numeric metric | recruiting_session_hires | Recruiting Session Hires | number        | number        |
| Yes      | numeric metric | participating_companies  | Participating Companies  | number        | number        |
| Yes      | numeric metric | job_readiness_workshop   | Job Readiness Workshop   | number        | number        |
```

## Time Field

```ls
Value = dates
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:fj2t-2ps5 d:2015-01-01T00:00:00.000Z m:participating_companies=4 m:recruiting_session_hires=16 m:career_plan_hires=2 m:job_readiness_workshop=1

series e:fj2t-2ps5 d:2015-02-01T00:00:00.000Z m:participating_companies=4 m:recruiting_session_hires=10 m:career_plan_hires=4 m:job_readiness_workshop=1

series e:fj2t-2ps5 d:2015-03-01T00:00:00.000Z m:participating_companies=4 m:recruiting_session_hires=15 m:career_plan_hires=3 m:job_readiness_workshop=1
```

## Meta Commands

```ls
metric m:career_plan_hires p:integer l:"Career Plan Hires" t:dataTypeName=number

metric m:recruiting_session_hires p:integer l:"Recruiting Session Hires" t:dataTypeName=number

metric m:participating_companies p:integer l:"Participating Companies" t:dataTypeName=number

metric m:job_readiness_workshop p:integer l:"Job Readiness Workshop" t:dataTypeName=number

entity e:fj2t-2ps5 l:"Jobs for Jacksonians" t:attribution="City of Jackson" t:url=https://data.jacksonms.gov/api/views/fj2t-2ps5

property e:fj2t-2ps5 t:meta.view v:id=fj2t-2ps5 v:category="Economic Development" v:attributionLink=http://www.jacksonms.gov v:averageRating=0 v:name="Jobs for Jacksonians" v:attribution="City of Jackson"

property e:fj2t-2ps5 t:meta.view.owner v:id=6ngd-c2u2 v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:screenName="Justin Bruce" v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:lastNotificationSeenAt=1492180672 v:displayName="Justin Bruce"

property e:fj2t-2ps5 t:meta.view.tableauthor v:id=6ngd-c2u2 v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:screenName="Justin Bruce" v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492180672 v:displayName="Justin Bruce"
```

## Top Records

```ls
| dates               | career_plan_hires | recruiting_session_hires | participating_companies | job_readiness_workshop | 
| =================== | ================= | ======================== | ======================= | ====================== | 
| 2015-01-01T00:00:00 | 2                 | 16                       | 4                       | 1                      | 
| 2015-02-01T00:00:00 | 4                 | 10                       | 4                       | 1                      | 
| 2015-03-01T00:00:00 | 3                 | 15                       | 4                       | 1                      | 
| 2015-04-01T00:00:00 | 2                 | 16                       | 4                       | 1                      | 
| 2015-05-01T00:00:00 | 5                 | 19                       | 4                       | 1                      | 
| 2015-06-01T00:00:00 | 4                 | 13                       | 4                       | 1                      | 
| 2015-07-01T00:00:00 | 4                 | 11                       | 4                       | 1                      | 
| 2015-08-01T00:00:00 | 6                 | 22                       | 4                       | 1                      | 
| 2015-09-01T00:00:00 | 3                 | 486                      | 96                      | 1                      | 
| 2015-10-01T00:00:00 | 2                 | 8                        | 3                       | 1                      | 
```