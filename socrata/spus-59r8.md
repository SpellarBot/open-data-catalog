# CTA - Performance - Unscheduled Days Off

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cta-performance-unscheduled-days-off-fb992) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/spus-59r8) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/spus-59r8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/spus-59r8/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | spus-59r8 |
| Name | CTA - Performance - Unscheduled Days Off |
| Category | Transportation |
| Tags | cta, chicago transit authority |
| Created | 2011-10-03T20:16:32Z |
| Publication Date | 2012-02-15T17:04:20Z |

## Description

This report shows unscheduled absences for bargained for employees in the CTA?s Rail and Bus divisions.  Unscheduled absences reflected in this report include Sick, FMLA, IOD, and AWOLs only.  It no longer includes Suspensions, which were included in earlier reports.

## Columns

```ls
| Included | Schema Type    | Field Name                        | Name                      | Data Type | Render Type |
| ======== | ============== | ================================= | ========================= | ========= | =========== |
| No       | time           | :updated_at                       | updated_at                | meta_data | meta_data   |
| Yes      | series tag     | mode                              | Mode                      | text      | text        |
| Yes      | numeric metric | days_lost_in_2010                 | Days Lost in 2010         | number    | number      |
| Yes      | numeric metric | days_lost_2011_projected_         | Days Lost 2011            | number    | number      |
| Yes      | numeric metric | days_lost_per_capita_2010         | Days Lost Per Capita 2010 | number    | number      |
| Yes      | numeric metric | days_lost_per_capita_jan_jun_2011 | Days Lost Per Capita 2011 | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:spus-59r8 d:2012-02-15T09:00:47.000Z t:mode="Bus Maintenance" m:days_lost_2011_projected_=9614 m:days_lost_per_capita_2010=8.5 m:days_lost_per_capita_jan_jun_2011=10.5 m:days_lost_in_2010=8159

series e:spus-59r8 d:2012-02-15T09:00:48.000Z t:mode="Bus Operations" m:days_lost_2011_projected_=79825 m:days_lost_per_capita_2010=20.3 m:days_lost_per_capita_jan_jun_2011=19 m:days_lost_in_2010=84528

series e:spus-59r8 d:2012-02-15T09:00:50.000Z t:mode="Rail Maintenance" m:days_lost_2011_projected_=5543 m:days_lost_per_capita_2010=10.6 m:days_lost_per_capita_jan_jun_2011=9.4 m:days_lost_in_2010=6906
```

## Meta Commands

```ls
metric m:days_lost_in_2010 p:integer l:"Days Lost in 2010" t:dataTypeName=number

metric m:days_lost_2011_projected_ p:integer l:"Days Lost 2011" t:dataTypeName=number

metric m:days_lost_per_capita_2010 p:float l:"Days Lost Per Capita 2010" t:dataTypeName=number

metric m:days_lost_per_capita_jan_jun_2011 p:float l:"Days Lost Per Capita 2011" t:dataTypeName=number

entity e:spus-59r8 l:"CTA - Performance - Unscheduled Days Off" t:url=https://data.cityofchicago.org/api/views/spus-59r8

property e:spus-59r8 t:meta.view v:id=spus-59r8 v:category=Transportation v:averageRating=0 v:name="CTA - Performance - Unscheduled Days Off"

property e:spus-59r8 t:meta.view.owner v:id=6bsn-5494 v:profileImageUrlMedium=/api/users/6bsn-5494/profile_images/THUMB v:profileImageUrlLarge=/api/users/6bsn-5494/profile_images/LARGE v:screenName="cta web" v:profileImageUrlSmall=/api/users/6bsn-5494/profile_images/TINY v:displayName="cta web"

property e:spus-59r8 t:meta.view.tableauthor v:id=6bsn-5494 v:profileImageUrlMedium=/api/users/6bsn-5494/profile_images/THUMB v:profileImageUrlLarge=/api/users/6bsn-5494/profile_images/LARGE v:screenName="cta web" v:profileImageUrlSmall=/api/users/6bsn-5494/profile_images/TINY v:roleName=designer v:displayName="cta web"
```

## Top Records

```ls
| :updated_at | mode             | days_lost_in_2010 | days_lost_2011_projected_ | days_lost_per_capita_2010 | days_lost_per_capita_jan_jun_2011 | 
| =========== | ================ | ================= | ========================= | ========================= | ================================= | 
| 1329296447  | Bus Maintenance  | 8159              | 9614                      | 8.5                       | 10.5                              | 
| 1329296448  | Bus Operations   | 84528             | 79825                     | 20.3                      | 19                                | 
| 1329296450  | Rail Maintenance | 6906              | 5543                      | 10.6                      | 9.4                               | 
| 1329296464  | Rail Operations  | 31018             | 40598                     | 24.4                      | 28.8                              | 
```