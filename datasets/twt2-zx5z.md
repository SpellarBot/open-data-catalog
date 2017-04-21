# Successful Employment for Blind Iowans by Federal Fiscal Year

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/successful-employment-for-blind-iowans-by-federal-fiscal-year) |
| Metadata | [Link](https://data.iowa.gov/api/views/twt2-zx5z) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/twt2-zx5z/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/twt2-zx5z/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | twt2-zx5z |
| Name | Successful Employment for Blind Iowans by Federal Fiscal Year |
| Attribution | Iowa Department for the Blind |
| Category | Economy |
| Tags | blind, visually impaired, employment, wages, gender, veteran, minority |
| Created | 2014-12-12T14:10:52Z |
| Publication Date | 2016-07-18T20:18:29Z |

## Description

The Iowa Department for the Blind helps educate, train, and empower blind and visually impaired individuals to pursue lifelong goals.  This dataset summarizes the successful employment outcomes of blind Iowans by Federal Fiscal Year (October 1 - September 30), starting on October 1, 2012.

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                          | Data Type | Render Type |
| ======== | ============== | ============================= | ============================= | ========= | =========== |
| Yes      | time           | federal_fiscal_year           | Federal Fiscal Year           | number    | number      |
| Yes      | series tag     | case_id                       | Case ID                       | text      | text        |
| Yes      | series tag     | gender                        | Gender                        | text      | text        |
| Yes      | series tag     | minority                      | Minority                      | text      | text        |
| Yes      | series tag     | hispanic                      | Hispanic                      | text      | text        |
| Yes      | series tag     | age_group                     | Age Group                     | text      | text        |
| Yes      | numeric metric | age_at_application            | Age at Application            | number    | number      |
| Yes      | series tag     | referral_source               | Referral Source               | text      | text        |
| Yes      | series tag     | veteran                       | Veteran                       | text      | text        |
| Yes      | series tag     | closure_reason_description    | Closure Reason Description    | text      | text        |
| Yes      | series tag     | employment_status_description | Employment Status Description | text      | text        |
| Yes      | series tag     | soc_code                      | SOC Code                      | text      | text        |
| Yes      | series tag     | occupational_title            | Occupational Title            | text      | text        |
| Yes      | numeric metric | closure_hours_worked_per_week | Closure Hours Worked Per Week | number    | number      |
| Yes      | numeric metric | closure_weekly_earnings       | Closure Weekly Earnings       | money     | money       |
| Yes      | numeric metric | hourly_wage                   | Hourly Wage                   | money     | money       |
| Yes      | numeric metric | monthly_earnings              | Monthly Earnings              | money     | money       |
| Yes      | numeric metric | annual_earnings               | Annual Earnings               | money     | money       |
```

## Time Field

```ls
Value = federal_fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:twt2-zx5z d:2013-01-01T00:00:00.000Z t:veteran=No t:minority=Non-Minority t:employment_status_description="Not employed: Secondary Ed. Student" t:closure_reason_description="Achieved employment outcome." t:referral_source="Education Elementary/Secondary" t:age_group=Transition t:case_id=46 t:gender=Male t:occupational_title=Psychiatrist t:hispanic=Hispanic-No t:soc_code=29-1066.00 m:closure_hours_worked_per_week=40 m:annual_earnings=184600 m:monthly_earnings=14200 m:age_at_application=17 m:hourly_wage=88.75 m:closure_weekly_earnings=3550

series e:twt2-zx5z d:2013-01-01T00:00:00.000Z t:veteran=No t:minority=Non-Minority t:employment_status_description="Not employed: Secondary Ed. Student" t:closure_reason_description="Achieved employment outcome." t:referral_source="Education Elementary/Secondary" t:age_group=Transition t:case_id=630 t:gender=Female t:occupational_title="Home Health Aide" t:hispanic=Hispanic-No t:soc_code=31-1011.00 m:closure_hours_worked_per_week=40 m:annual_earnings=18720 m:monthly_earnings=1440 m:age_at_application=17 m:hourly_wage=9 m:closure_weekly_earnings=360

series e:twt2-zx5z d:2013-01-01T00:00:00.000Z t:veteran=No t:minority=Non-Minority t:employment_status_description="Employment without Supports" t:closure_reason_description="Achieved employment outcome." t:referral_source=Self-referral t:age_group=Transition t:case_id=1172 t:gender=Female t:occupational_title="Disabilities Consultant" t:hispanic=Hispanic-No t:soc_code=21-1019.00 m:closure_hours_worked_per_week=40 m:annual_earnings=40508 m:monthly_earnings=3116 m:age_at_application=15 m:hourly_wage=19.48 m:closure_weekly_earnings=779
```

## Meta Commands

```ls
metric m:age_at_application p:integer l:"Age at Application" d:"Age of the participant at time of application" t:dataTypeName=number

metric m:closure_hours_worked_per_week p:integer l:"Closure Hours Worked Per Week" d:"Number of hours worked per week at case closure" t:dataTypeName=number

metric m:closure_weekly_earnings p:double l:"Closure Weekly Earnings" d:"Weekly wages when case was closed" t:dataTypeName=money

metric m:hourly_wage p:double l:"Hourly Wage" d:"Hourly wage when case was closed" t:dataTypeName=money

metric m:monthly_earnings p:double l:"Monthly Earnings" d:"Monthly earnings when case was closed" t:dataTypeName=money

metric m:annual_earnings p:double l:"Annual Earnings" d:"Annualized earnings when case was closed" t:dataTypeName=money

entity e:twt2-zx5z l:"Successful Employment for Blind Iowans by Federal Fiscal Year" t:attribution="Iowa Department for the Blind" t:url=https://data.iowa.gov/api/views/twt2-zx5z

property e:twt2-zx5z t:meta.view v:id=twt2-zx5z v:category=Economy v:averageRating=0 v:name="Successful Employment for Blind Iowans by Federal Fiscal Year" v:attribution="Iowa Department for the Blind"

property e:twt2-zx5z t:meta.view.license v:name="Public Domain"

property e:twt2-zx5z t:meta.view.owner v:id=e8te-6wiw v:profileImageUrlMedium=/api/users/e8te-6wiw/profile_images/THUMB v:profileImageUrlLarge=/api/users/e8te-6wiw/profile_images/LARGE v:screenName="Iowa Department for the Blind" v:profileImageUrlSmall=/api/users/e8te-6wiw/profile_images/TINY v:displayName="Iowa Department for the Blind"

property e:twt2-zx5z t:meta.view.tableauthor v:id=e8te-6wiw v:profileImageUrlMedium=/api/users/e8te-6wiw/profile_images/THUMB v:profileImageUrlLarge=/api/users/e8te-6wiw/profile_images/LARGE v:screenName="Iowa Department for the Blind" v:profileImageUrlSmall=/api/users/e8te-6wiw/profile_images/TINY v:roleName=editor v:displayName="Iowa Department for the Blind"
```

## Top Records

```ls
| federal_fiscal_year | case_id | gender | minority     | hispanic    | age_group      | age_at_application | referral_source                  | veteran | closure_reason_description   | employment_status_description       | soc_code   | occupational_title                         | closure_hours_worked_per_week | closure_weekly_earnings | hourly_wage | monthly_earnings | annual_earnings | 
| =================== | ======= | ====== | ============ | =========== | ============== | ================== | ================================ | ======= | ============================ | =================================== | ========== | ========================================== | ============================= | ======================= | =========== | ================ | =============== | 
| 2013                | 46      | Male   | Non-Minority | Hispanic-No | Transition     | 17                 | Education Elementary/Secondary   | No      | Achieved employment outcome. | Not employed: Secondary Ed. Student | 29-1066.00 | Psychiatrist                               | 40                            | 3550                    | 88.75       | 14200            | 184600          | 
| 2013                | 630     | Female | Non-Minority | Hispanic-No | Transition     | 17                 | Education Elementary/Secondary   | No      | Achieved employment outcome. | Not employed: Secondary Ed. Student | 31-1011.00 | Home Health Aide                           | 40                            | 360                     | 9.00        | 1440             | 18720           | 
| 2013                | 1172    | Female | Non-Minority | Hispanic-No | Transition     | 15                 | Self-referral                    | No      | Achieved employment outcome. | Employment without Supports         | 21-1019.00 | Disabilities Consultant                    | 40                            | 779                     | 19.48       | 3116             | 40508           | 
| 2013                | 1664    | Female | Non-Minority | Hispanic-No | Transition     | 15                 | Other sources                    | No      | Achieved employment outcome. | Not employed: Secondary Ed. Student | 13-1121.00 | Meeting And Event Planner                  | 40                            | 600                     | 15.00       | 2400             | 31200           | 
| 2013                | 1695    | Female | Non-Minority | Hispanic-No | Non-Transition | 46                 | Community Rehabilitation Program | No      | Achieved employment outcome. | Not employed: Other                 | 21-1011.00 | Substance Abuse Counselor                  | 40                            | 474                     | 11.85       | 1896             | 24648           | 
| 2013                | 2182    | Male   | Non-Minority | Hispanic-No | Transition     | 14                 | Education Elementary/Secondary   | No      | Achieved employment outcome. | Not employed: All other Students    | 15-1071.00 | Network And Computer Systems Administrator | 40                            | 450                     | 11.25       | 1800             | 23400           | 
| 2013                | 2195    | Male   | Non-Minority | Hispanic-No | Non-Transition | 62                 | Self-referral                    | No      | Achieved employment outcome. | Employment without Supports         | 43-5081.01 | Retention: Shelf Facer                     | 6                             | 50                      | 8.33        | 200              | 2600            | 
| 2013                | 2276    | Female | Non-Minority | Hispanic-No | Transition     | 17                 | Community Rehabilitation Program | No      | Achieved employment outcome. | Not employed: Secondary Ed. Student | 11-2021.00 | Marketing Coordinator                      | 40                            | 360                     | 9.00        | 1440             | 18720           | 
| 2013                | 2372    | Male   | Non-Minority | Hispanic-No | Transition     | 20                 | Transition                       | No      | Achieved employment outcome. | Not employed: All other Students    | 25-2031.00 | Secondary Education Teacher                | 38                            | 355                     | 9.34        | 1420             | 18460           | 
| 2013                | 2379    | Male   | Non-Minority | Hispanic-No | Transition     | 14                 | Statewide Referral System        | No      | Achieved employment outcome. | Not employed: Secondary Ed. Student | 43-4161.00 | Human Resource Assistant (Loa Examiner)    | 40                            | 520                     | 13.00       | 2080             | 27040           | 
```