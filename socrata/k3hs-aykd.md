# City of Seattle Wages: Comparison by Gender - Discretionary Pay Titles by Department

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-of-seattle-wages-comparison-by-gender-discretionary-pay-titles-by-department-eafb4) |
| Metadata | [Link](https://data.seattle.gov/api/views/k3hs-aykd) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/k3hs-aykd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/k3hs-aykd/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | k3hs-aykd |
| Name | City of Seattle Wages: Comparison by Gender - Discretionary Pay Titles by Department |
| Category | City Business |
| Tags | wages, salary, salaries, job, classifications, government, gender, comparison by gender, gender wage study |
| Created | 2013-07-16T20:42:14Z |
| Publication Date | 2013-07-16T20:48:20Z |

## Columns

```ls
| Included | Schema Type    | Field Name                                 | Name                                       | Data Type | Render Type |
| ======== | ============== | ========================================== | ========================================== | ========= | =========== |
| No       | time           | :updated_at                                | updated_at                                 | meta_data | meta_data   |
| Yes      | series tag     | department                                 | DEPARTMENT                                 | text      | text        |
| Yes      | series tag     | descr                                      | DESCR                                      | text      | text        |
| Yes      | series tag     | gender_descr                               | GENDER DESCR                               | text      | text        |
| Yes      | numeric metric | admin_support_ee                           | Admin Support # EE                         | number    | number      |
| Yes      | numeric metric | admin_support_gender                       | Admin Support % Gender                     | percent   | percent     |
| Yes      | numeric metric | admin_support_avg_hrly                     | Admin Support Avg Hrly                     | number    | number      |
| Yes      | numeric metric | admin_support_avg_yrs_in_current_job       | Admin Support Avg Yrs in Current Job       | number    | number      |
| Yes      | numeric metric | officials_admin_ee                         | Officials/Admin # EE                       | number    | number      |
| Yes      | numeric metric | officials_admin_gender                     | Officials/Admin % Gender                   | percent   | percent     |
| Yes      | numeric metric | officials_admin_avg_hrly                   | Officials/Admin Avg Hrly                   | number    | number      |
| Yes      | numeric metric | officials_admin_avg_yrs_in_current_job     | Officials/Admin Avg Yrs in Current Job     | number    | number      |
| Yes      | numeric metric | para_professionals_ee                      | Para-Professionals # EE                    | number    | number      |
| Yes      | numeric metric | para_professionals_gender                  | Para-Professionals % Gender                | percent   | percent     |
| Yes      | numeric metric | para_professionals_avg_hrly                | Para-Professionals Avg Hrly                | number    | number      |
| Yes      | numeric metric | para_professionals_avg_yrs_in_current_job  | Para-Professionals Avg Yrs in Current Job  | number    | number      |
| Yes      | numeric metric | professionals_ee                           | Professionals # EE                         | number    | number      |
| Yes      | numeric metric | professionals_gender                       | Professionals % Gender                     | percent   | percent     |
| Yes      | numeric metric | professionals_avg_hrly                     | Professionals Avg Hrly                     | number    | number      |
| Yes      | numeric metric | professionals_avg_yrs_in_current_job       | Professionals Avg Yrs in Current Job       | number    | number      |
| Yes      | numeric metric | protected_services_ee                      | Protected Services # EE                    | number    | number      |
| Yes      | numeric metric | protected_services_gender                  | Protected Services % Gender                | percent   | percent     |
| Yes      | numeric metric | protected_services_avg_hrly                | Protected Services Avg Hrly                | number    | number      |
| Yes      | numeric metric | protected_services_avg_yrs_in_current_job  | Protected Services Avg Yrs in Current Job  | number    | number      |
| Yes      | numeric metric | service_maintenance_ee                     | Service/Maintenance # EE                   | number    | number      |
| Yes      | numeric metric | service_maintenance_gender                 | Service/Maintenance % Gender               | percent   | percent     |
| Yes      | numeric metric | service_maintenance_avg_hrly               | Service/Maintenance Avg Hrly               | number    | number      |
| Yes      | numeric metric | service_maintenance_avg_yrs_in_current_job | Service/Maintenance Avg Yrs in Current Job | number    | number      |
| Yes      | numeric metric | skilled_craft_ee                           | Skilled Craft # EE                         | number    | number      |
| Yes      | numeric metric | skilled_craft_gender                       | Skilled Craft % Gender                     | percent   | percent     |
| Yes      | numeric metric | skilled_craft_avg_hrly                     | Skilled Craft Avg Hrly                     | number    | number      |
| Yes      | numeric metric | skilled_craft_avg_yrs_in_current_job       | Skilled Craft Avg Yrs in Current Job       | number    | number      |
| Yes      | numeric metric | technicians_ee                             | Technicians # EE                           | number    | number      |
| Yes      | numeric metric | technicians_gender                         | Technicians % Gender                       | percent   | percent     |
| Yes      | numeric metric | technicians_avg_hrly                       | Technicians Avg Hrly                       | number    | number      |
| Yes      | numeric metric | technicians_avg_yrs_in_current_job         | Technicians Avg Yrs in Current Job         | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:k3hs-aykd d:2013-07-16T13:42:18.000Z t:gender_descr=Female t:department="Arts and Cultural Affairs" m:professionals_gender=79 m:para_professionals_ee=0 m:professionals_avg_hrly=35 m:admin_support_ee=2 m:officials_admin_gender=67 m:admin_support_avg_hrly=26.53 m:officials_admin_avg_hrly=49.97 m:technicians_ee=0 m:service_maintenance_ee=1 m:service_maintenance_gender=33 m:service_maintenance_avg_hrly=27.78 m:professionals_ee=15 m:protected_services_ee=0 m:admin_support_gender=100 m:officials_admin_ee=2 m:skilled_craft_ee=0 m:technicians_gender=0

series e:k3hs-aykd d:2013-07-16T13:42:18.000Z t:gender_descr=Male t:department="Arts and Cultural Affairs" m:professionals_gender=21 m:para_professionals_ee=0 m:professionals_avg_hrly=32.64 m:admin_support_ee=0 m:officials_admin_gender=33 m:officials_admin_avg_hrly=51.95 m:technicians_ee=1 m:service_maintenance_ee=2 m:service_maintenance_gender=67 m:technicians_avg_hrly=29.04 m:service_maintenance_avg_hrly=20.73 m:professionals_ee=4 m:protected_services_ee=0 m:admin_support_gender=0 m:officials_admin_ee=1 m:skilled_craft_ee=0 m:technicians_gender=100

series e:k3hs-aykd d:2013-07-16T13:42:18.000Z t:descr="Total Employees" t:department="Arts and Cultural Affairs" m:admin_support_ee=2 m:professionals_ee=19 m:technicians_ee=1 m:service_maintenance_ee=3 m:officials_admin_ee=3
```

## Meta Commands

```ls
metric m:admin_support_ee p:integer l:"Admin Support # EE" t:dataTypeName=number

metric m:admin_support_gender p:integer l:"Admin Support % Gender" t:dataTypeName=percent

metric m:admin_support_avg_hrly p:float l:"Admin Support Avg Hrly" t:dataTypeName=number

metric m:admin_support_avg_yrs_in_current_job p:double l:"Admin Support Avg Yrs in Current Job" t:dataTypeName=number

metric m:officials_admin_ee p:integer l:"Officials/Admin # EE" t:dataTypeName=number

metric m:officials_admin_gender p:integer l:"Officials/Admin % Gender" t:dataTypeName=percent

metric m:officials_admin_avg_hrly p:float l:"Officials/Admin Avg Hrly" t:dataTypeName=number

metric m:officials_admin_avg_yrs_in_current_job p:float l:"Officials/Admin Avg Yrs in Current Job" t:dataTypeName=number

metric m:para_professionals_ee p:integer l:"Para-Professionals # EE" t:dataTypeName=number

metric m:para_professionals_gender p:integer l:"Para-Professionals % Gender" t:dataTypeName=percent

metric m:para_professionals_avg_hrly p:float l:"Para-Professionals Avg Hrly" t:dataTypeName=number

metric m:para_professionals_avg_yrs_in_current_job p:float l:"Para-Professionals Avg Yrs in Current Job" t:dataTypeName=number

metric m:professionals_ee p:integer l:"Professionals # EE" t:dataTypeName=number

metric m:professionals_gender p:integer l:"Professionals % Gender" t:dataTypeName=percent

metric m:professionals_avg_hrly p:float l:"Professionals Avg Hrly" t:dataTypeName=number

metric m:professionals_avg_yrs_in_current_job p:float l:"Professionals Avg Yrs in Current Job" t:dataTypeName=number

metric m:protected_services_ee p:integer l:"Protected Services # EE" t:dataTypeName=number

metric m:protected_services_gender p:integer l:"Protected Services % Gender" t:dataTypeName=percent

metric m:protected_services_avg_hrly p:float l:"Protected Services Avg Hrly" t:dataTypeName=number

metric m:protected_services_avg_yrs_in_current_job p:float l:"Protected Services Avg Yrs in Current Job" t:dataTypeName=number

metric m:service_maintenance_ee p:integer l:"Service/Maintenance # EE" t:dataTypeName=number

metric m:service_maintenance_gender p:integer l:"Service/Maintenance % Gender" t:dataTypeName=percent

metric m:service_maintenance_avg_hrly p:float l:"Service/Maintenance Avg Hrly" t:dataTypeName=number

metric m:service_maintenance_avg_yrs_in_current_job p:float l:"Service/Maintenance Avg Yrs in Current Job" t:dataTypeName=number

metric m:skilled_craft_ee p:integer l:"Skilled Craft # EE" t:dataTypeName=number

metric m:skilled_craft_gender p:integer l:"Skilled Craft % Gender" t:dataTypeName=percent

metric m:skilled_craft_avg_hrly p:float l:"Skilled Craft Avg Hrly" t:dataTypeName=number

metric m:skilled_craft_avg_yrs_in_current_job p:float l:"Skilled Craft Avg Yrs in Current Job" t:dataTypeName=number

metric m:technicians_ee p:integer l:"Technicians # EE" t:dataTypeName=number

metric m:technicians_gender p:integer l:"Technicians % Gender" t:dataTypeName=percent

metric m:technicians_avg_hrly p:float l:"Technicians Avg Hrly" t:dataTypeName=number

metric m:technicians_avg_yrs_in_current_job p:float l:"Technicians Avg Yrs in Current Job" t:dataTypeName=number

entity e:k3hs-aykd l:"City of Seattle Wages: Comparison by Gender - Discretionary Pay Titles by Department" t:url=https://data.seattle.gov/api/views/k3hs-aykd

property e:k3hs-aykd t:meta.view d:2017-09-25T07:26:38.778Z v:averageRating=0 v:name="City of Seattle Wages: Comparison by Gender - Discretionary Pay Titles by Department" v:attributionLink=http://mayormcginn.wpengine.netdna-cdn.com/wp-content/uploads/2013/07/Appendix-4-EEO-Final.pdf v:id=k3hs-aykd v:category="City Business"

property e:k3hs-aykd t:meta.view.license d:2017-09-25T07:26:38.778Z v:name="Public Domain"

property e:k3hs-aykd t:meta.view.owner d:2017-09-25T07:26:38.778Z v:displayName="Seattle IT" v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:id=pfbu-yuv5 v:screenName="Seattle IT" v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB

property e:k3hs-aykd t:meta.view.tableauthor d:2017-09-25T07:26:38.778Z v:displayName="Seattle IT" v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:roleName=administrator v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:id=pfbu-yuv5 v:screenName="Seattle IT" v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB
```

## Top Records

```ls
| :updated_at | department                | descr                  | gender_descr | admin_support_ee | admin_support_gender | admin_support_avg_hrly | admin_support_avg_yrs_in_current_job | officials_admin_ee | officials_admin_gender | officials_admin_avg_hrly | officials_admin_avg_yrs_in_current_job | para_professionals_ee | para_professionals_gender | para_professionals_avg_hrly | para_professionals_avg_yrs_in_current_job | professionals_ee | professionals_gender | professionals_avg_hrly | professionals_avg_yrs_in_current_job | protected_services_ee | protected_services_gender | protected_services_avg_hrly | protected_services_avg_yrs_in_current_job | service_maintenance_ee | service_maintenance_gender | service_maintenance_avg_hrly | service_maintenance_avg_yrs_in_current_job | skilled_craft_ee | skilled_craft_gender | skilled_craft_avg_hrly | skilled_craft_avg_yrs_in_current_job | technicians_ee | technicians_gender | technicians_avg_hrly | technicians_avg_yrs_in_current_job | 
| =========== | ========================= | ====================== | ============ | ================ | ==================== | ====================== | ==================================== | ================== | ====================== | ======================== | ====================================== | ===================== | ========================= | =========================== | ========================================= | ================ | ==================== | ====================== | ==================================== | ===================== | ========================= | =========================== | ========================================= | ====================== | ========================== | ============================ | ========================================== | ================ | ==================== | ====================== | ==================================== | ============== | ================== | ==================== | ================================== | 
| 1373982138  | Arts and Cultural Affairs |                        | Female       | 2                | 100                  | 26.53                  |                                      | 2                  | 67                     | 49.97                    |                                        | 0                     |                           |                             |                                           | 15               | 79                   | 35.00                  |                                      | 0                     |                           |                             |                                           | 1                      | 33                         | 27.78                        |                                            | 0                |                      |                        |                                      | 0              | 0                  |                      |                                    | 
| 1373982138  | Arts and Cultural Affairs |                        | Male         | 0                | 0                    |                        |                                      | 1                  | 33                     | 51.95                    |                                        | 0                     |                           |                             |                                           | 4                | 21                   | 32.64                  |                                      | 0                     |                           |                             |                                           | 2                      | 67                         | 20.73                        |                                            | 0                |                      |                        |                                      | 1              | 100                | 29.04                |                                    | 
| 1373982138  | Arts and Cultural Affairs | Total Employees        |              | 2                |                      |                        |                                      | 3                  |                        |                          |                                        |                       |                           |                             |                                           | 19               |                      |                        |                                      |                       |                           |                             |                                           | 3                      |                            |                              |                                            |                  |                      |                        |                                      | 1              |                    |                      |                                    | 
| 1373982138  | Arts and Cultural Affairs | Ave Yrs in Current Job |              |                  |                      |                        | 3.9                                  |                    |                        |                          | 9.4                                    |                       |                           |                             |                                           |                  |                      |                        | 5.2                                  |                       |                           |                             |                                           |                        |                            |                              | 4                                          |                  |                      |                        |                                      |                |                    |                      | 0.1                                | 
| 1373982138  | City Auditor              |                        | Female       | 0                |                      |                        |                                      | 0                  | 0                      |                          |                                        | 0                     |                           |                             |                                           | 8                | 89                   | 49.67                  |                                      | 0                     |                           |                             |                                           | 0                      |                            |                              |                                            | 0                |                      |                        |                                      | 0              |                    |                      |                                    | 
| 1373982138  | City Auditor              |                        | Male         | 0                |                      |                        |                                      | 1                  | 100                    | 65.26                    |                                        | 0                     |                           |                             |                                           | 1                | 11                   | 47.52                  |                                      | 0                     |                           |                             |                                           | 0                      |                            |                              |                                            | 0                |                      |                        |                                      | 0              |                    |                      |                                    | 
| 1373982138  | City Auditor              | Total Employees        |              |                  |                      |                        |                                      | 1                  |                        |                          |                                        |                       |                           |                             |                                           | 9                |                      |                        |                                      |                       |                           |                             |                                           |                        |                            |                              |                                            |                  |                      |                        |                                      |                |                    |                      |                                    | 
| 1373982138  | City Auditor              | Ave Yrs in Current Job |              |                  |                      |                        |                                      |                    |                        |                          | 3.4                                    |                       |                           |                             |                                           |                  |                      |                        | 6.5                                  |                       |                           |                             |                                           |                        |                            |                              |                                            |                  |                      |                        |                                      |                |                    |                      |                                    | 
| 1373982138  | City Budget Office        |                        | Female       | 1                | 100                  | 26.26                  |                                      | 1                  | 50                     | 73.03                    |                                        | 0                     |                           |                             |                                           | 15               | 63                   | 45.60                  |                                      | 0                     |                           |                             |                                           | 0                      |                            |                              |                                            | 0                |                      |                        |                                      | 0              |                    |                      |                                    | 
| 1373982138  | City Budget Office        |                        | Male         | 0                | 0                    |                        |                                      | 1                  | 50                     | 68.27                    |                                        | 0                     |                           |                             |                                           | 9                | 38                   | 45.70                  |                                      | 0                     |                           |                             |                                           | 0                      |                            |                              |                                            | 0                |                      |                        |                                      | 0              |                    |                      |                                    | 
```