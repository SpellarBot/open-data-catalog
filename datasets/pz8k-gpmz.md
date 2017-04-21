# DGS Personnel Report

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dgs-personnel-report) |
| Metadata | [Link](https://data.maryland.gov/api/views/pz8k-gpmz) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/pz8k-gpmz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/pz8k-gpmz/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | pz8k-gpmz |
| Name | DGS Personnel Report |
| Attribution | Department of General Services (DGS) |
| Category | Budget |
| Tags | dgs, dgs template, personnel, department of general services, sick leave, accident leave, overtime, iwif |
| Created | 2015-01-29T16:49:00Z |
| Publication Date | 2015-08-28T17:50:42Z |

## Description

Data are provided by the Department of General Services (DGS). This report, updated monthly, shows DGS-wide overtime use, IWIF reports, and sick leave, and accident leave.

## Columns

```ls
| Included | Schema Type    | Field Name                                                | Name                                                       | Data Type     | Render Type   |
| ======== | ============== | ========================================================= | ========================================================== | ============= | ============= |
| Yes      | time           | pay_period_ending_date                                    | Pay Period Ending Date                                     | calendar_date | calendar_date |
| Yes      | numeric metric | overtime_total_hours                                      | OVERTIME TOTAL (HOURS)                                     | number        | number        |
| Yes      | numeric metric | overtime_hours_administration                             | Overtime Hours: Administration                             | number        | number        |
| Yes      | numeric metric | overtime_hours_facilities_operation_and_maintenance       | Overtime Hours: Facilities Operation and Maintenance       | number        | number        |
| Yes      | numeric metric | overtime_hours_facilities_design_planning                 | Overtime Hours: Facilities Design & Planning               | number        | number        |
| Yes      | numeric metric | overtime_hours_real_estate                                | Overtime Hours: Real Estate                                | number        | number        |
| Yes      | numeric metric | overtime_hours_procurement_logistics                      | Overtime Hours: Procurement & Logistics                    | number        | number        |
| Yes      | numeric metric | overtime_hours_security                                   | Overtime Hours: Security                                   | number        | number        |
| Yes      | numeric metric | sick_leave_total_days                                     | SICK LEAVE TOTAL DAYS                                      | number        | number        |
| Yes      | numeric metric | sick_leave_days_administration                            | Sick Leave Days: Administration                            | number        | number        |
| Yes      | numeric metric | sick_leave_days_facilities_operation_and_maintenance      | Sick Leave Days: Facilities Operation and Maintenance      | number        | number        |
| Yes      | numeric metric | sick_leave_days_facilities_design_planning                | Sick Leave Days: Facilities Design & Planning              | number        | number        |
| Yes      | numeric metric | sick_leave_days_real_estate                               | Sick Leave Days: Real Estate                               | number        | number        |
| Yes      | numeric metric | sick_leave_days_procurement_logistics                     | Sick Leave Days: Procurement & Logistics                   | number        | number        |
| Yes      | numeric metric | sick_leave_days_security                                  | Sick Leave Days: Security                                  | number        | number        |
| Yes      | numeric metric | accident_leave_hours_administration                       | Accident Leave Hours: Administration                       | number        | number        |
| Yes      | numeric metric | accident_leave_hours_facilities_operation_and_maintenance | Accident Leave Hours: Facilities Operation and Maintenance | number        | number        |
| Yes      | numeric metric | accident_leave_hours_facilities_design_planning           | Accident Leave Hours: Facilities Design & Planning         | number        | number        |
| Yes      | numeric metric | accident_leave_hours_real_estate                          | Accident Leave Hours: Real Estate                          | number        | number        |
| Yes      | numeric metric | accident_leave_hours_procurement_logistics                | Accident Leave Hours: Procurement & Logistics              | number        | number        |
| Yes      | numeric metric | accident_leave_hours_security                             | Accident Leave Hours: Security                             | number        | number        |
```

## Time Field

```ls
Value = pay_period_ending_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:pz8k-gpmz d:2007-05-22T00:00:00.000Z m:overtime_hours_procurement_logistics=24 m:sick_leave_days_real_estate=5.75 m:sick_leave_days_administration=20.41 m:overtime_hours_administration=0 m:overtime_hours_security=578 m:sick_leave_days_facilities_design_planning=21.35 m:accident_leave_hours_security=72 m:accident_leave_hours_real_estate=0 m:sick_leave_days_procurement_logistics=34.66 m:overtime_hours_real_estate=0 m:overtime_hours_facilities_design_planning=0 m:overtime_total_hours=1630 m:accident_leave_hours_facilities_operation_and_maintenance=48 m:accident_leave_hours_procurement_logistics=0 m:sick_leave_days_facilities_operation_and_maintenance=85.37 m:sick_leave_days_security=87.81 m:accident_leave_hours_administration=0 m:overtime_hours_facilities_operation_and_maintenance=1028 m:sick_leave_total_days=255.4 m:accident_leave_hours_facilities_design_planning=0

series e:pz8k-gpmz d:2007-06-05T00:00:00.000Z m:overtime_hours_procurement_logistics=11 m:sick_leave_days_real_estate=9.46 m:sick_leave_days_administration=14.35 m:overtime_hours_administration=0 m:overtime_hours_security=541 m:sick_leave_days_facilities_design_planning=22.75 m:accident_leave_hours_security=72 m:accident_leave_hours_real_estate=0 m:sick_leave_days_procurement_logistics=19.91 m:overtime_hours_real_estate=0 m:overtime_hours_facilities_design_planning=0 m:overtime_total_hours=2621 m:accident_leave_hours_facilities_operation_and_maintenance=48 m:accident_leave_hours_procurement_logistics=0 m:sick_leave_days_facilities_operation_and_maintenance=69.18 m:sick_leave_days_security=69.82 m:accident_leave_hours_administration=0 m:overtime_hours_facilities_operation_and_maintenance=1293.9 m:sick_leave_total_days=205.5 m:accident_leave_hours_facilities_design_planning=0

series e:pz8k-gpmz d:2007-06-19T00:00:00.000Z m:overtime_hours_procurement_logistics=0 m:sick_leave_days_real_estate=5.18 m:sick_leave_days_administration=21.75 m:overtime_hours_administration=0 m:overtime_hours_security=628 m:sick_leave_days_facilities_design_planning=23.92 m:accident_leave_hours_security=80 m:accident_leave_hours_real_estate=0 m:sick_leave_days_procurement_logistics=32.5 m:overtime_hours_real_estate=0 m:overtime_hours_facilities_design_planning=0 m:overtime_total_hours=1730 m:accident_leave_hours_facilities_operation_and_maintenance=80 m:accident_leave_hours_procurement_logistics=0 m:sick_leave_days_facilities_operation_and_maintenance=78.76 m:sick_leave_days_security=55.18 m:accident_leave_hours_administration=0 m:overtime_hours_facilities_operation_and_maintenance=1102 m:sick_leave_total_days=217.3 m:accident_leave_hours_facilities_design_planning=0
```

## Meta Commands

```ls
metric m:overtime_total_hours p:float l:"OVERTIME TOTAL (HOURS)" t:dataTypeName=number

metric m:overtime_hours_administration p:float l:"Overtime Hours: Administration" t:dataTypeName=number

metric m:overtime_hours_facilities_operation_and_maintenance p:float l:"Overtime Hours: Facilities Operation and Maintenance" t:dataTypeName=number

metric m:overtime_hours_facilities_design_planning p:float l:"Overtime Hours: Facilities Design & Planning" t:dataTypeName=number

metric m:overtime_hours_real_estate p:double l:"Overtime Hours: Real Estate" t:dataTypeName=number

metric m:overtime_hours_procurement_logistics p:float l:"Overtime Hours: Procurement & Logistics" t:dataTypeName=number

metric m:overtime_hours_security p:float l:"Overtime Hours: Security" t:dataTypeName=number

metric m:sick_leave_total_days p:float l:"SICK LEAVE TOTAL DAYS" t:dataTypeName=number

metric m:sick_leave_days_administration p:float l:"Sick Leave Days: Administration" t:dataTypeName=number

metric m:sick_leave_days_facilities_operation_and_maintenance p:double l:"Sick Leave Days: Facilities Operation and Maintenance" t:dataTypeName=number

metric m:sick_leave_days_facilities_design_planning p:float l:"Sick Leave Days: Facilities Design & Planning" t:dataTypeName=number

metric m:sick_leave_days_real_estate p:float l:"Sick Leave Days: Real Estate" t:dataTypeName=number

metric m:sick_leave_days_procurement_logistics p:float l:"Sick Leave Days: Procurement & Logistics" t:dataTypeName=number

metric m:sick_leave_days_security p:float l:"Sick Leave Days: Security" t:dataTypeName=number

metric m:accident_leave_hours_administration p:double l:"Accident Leave Hours: Administration" t:dataTypeName=number

metric m:accident_leave_hours_facilities_operation_and_maintenance p:double l:"Accident Leave Hours: Facilities Operation and Maintenance" t:dataTypeName=number

metric m:accident_leave_hours_facilities_design_planning p:double l:"Accident Leave Hours: Facilities Design & Planning" t:dataTypeName=number

metric m:accident_leave_hours_real_estate p:double l:"Accident Leave Hours: Real Estate" t:dataTypeName=number

metric m:accident_leave_hours_procurement_logistics p:double l:"Accident Leave Hours: Procurement & Logistics" t:dataTypeName=number

metric m:accident_leave_hours_security p:integer l:"Accident Leave Hours: Security" t:dataTypeName=number

entity e:pz8k-gpmz l:"DGS Personnel Report" t:attribution="Department of General Services (DGS)" t:url=https://data.maryland.gov/api/views/pz8k-gpmz

property e:pz8k-gpmz t:meta.view v:id=pz8k-gpmz v:category=Budget v:attributionLink=http://www.dgs.maryland.gov/ v:averageRating=0 v:name="DGS Personnel Report" v:attribution="Department of General Services (DGS)"

property e:pz8k-gpmz t:meta.view.license v:name="Public Domain"

property e:pz8k-gpmz t:meta.view.owner v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"

property e:pz8k-gpmz t:meta.view.tableauthor v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"
```

## Top Records

```ls
| pay_period_ending_date | overtime_total_hours | overtime_hours_administration | overtime_hours_facilities_operation_and_maintenance | overtime_hours_facilities_design_planning | overtime_hours_real_estate | overtime_hours_procurement_logistics | overtime_hours_security | sick_leave_total_days | sick_leave_days_administration | sick_leave_days_facilities_operation_and_maintenance | sick_leave_days_facilities_design_planning | sick_leave_days_real_estate | sick_leave_days_procurement_logistics | sick_leave_days_security | accident_leave_hours_administration | accident_leave_hours_facilities_operation_and_maintenance | accident_leave_hours_facilities_design_planning | accident_leave_hours_real_estate | accident_leave_hours_procurement_logistics | accident_leave_hours_security | 
| ====================== | ==================== | ============================= | =================================================== | ========================================= | ========================== | ==================================== | ======================= | ===================== | ============================== | ==================================================== | ========================================== | =========================== | ===================================== | ======================== | =================================== | ========================================================= | =============================================== | ================================ | ========================================== | ============================= | 
| 2007-05-22T00:00:00    | 1630                 | 0                             | 1028                                                | 0                                         | 0                          | 24                                   | 578                     | 255.4                 | 20.41                          | 85.37                                                | 21.35                                      | 5.75                        | 34.66                                 | 87.81                    | 0                                   | 48                                                        | 0                                               | 0                                | 0                                          | 72                            | 
| 2007-06-05T00:00:00    | 2621                 | 0                             | 1293.9                                              | 0                                         | 0                          | 11                                   | 541                     | 205.5                 | 14.35                          | 69.18                                                | 22.75                                      | 9.46                        | 19.91                                 | 69.82                    | 0                                   | 48                                                        | 0                                               | 0                                | 0                                          | 72                            | 
| 2007-06-19T00:00:00    | 1730                 | 0                             | 1102                                                | 0                                         | 0                          | 0                                    | 628                     | 217.3                 | 21.75                          | 78.76                                                | 23.92                                      | 5.18                        | 32.5                                  | 55.18                    | 0                                   | 80                                                        | 0                                               | 0                                | 0                                          | 80                            | 
| 2007-07-03T00:00:00    | 1331                 | 0                             | 830                                                 | 0                                         | 0                          | 0                                    | 501                     | 241.9                 | 9.41                           | 91.68                                                | 15.43                                      | 5.18                        | 33.75                                 | 86.46                    | 0                                   | 88                                                        | 0                                               | 0                                | 0                                          | 112                           | 
| 2007-07-17T00:00:00    | 1823.3               | 0                             | 1240.8                                              | 0                                         | 0                          | 0                                    | 582.5                   | 249.2                 | 20.98                          | 104.75                                               | 20.56                                      | 1.73                        | 37.86                                 | 63.15                    | 0                                   | 80                                                        | 0                                               | 0                                | 0                                          | 72                            | 
| 2007-07-31T00:00:00    | 2023.9               | 0                             | 1324.7                                              | 0                                         | 0                          | 0                                    | 699.2                   | 272.2                 | 11                             | 123.92                                               | 32.93                                      | 5.73                        | 34.79                                 | 63.86                    | 0                                   | 84                                                        | 0                                               | 0                                | 0                                          | 80                            | 
| 2007-08-14T00:00:00    | 1710.5               | 0                             | 1254.7                                              | 0                                         | 0                          | 0                                    | 455.8                   | 220.2                 | 5.62                           | 84.58                                                | 43.5                                       | 2.72                        | 24.26                                 | 59.5                     | 0                                   | 80                                                        | 0                                               | 0                                | 0                                          | 80                            | 
| 2007-08-28T00:00:00    | 1272                 | 0                             | 788.4                                               | 0                                         | 0                          | 0                                    | 483.6                   | 253.8                 | 14.43                          | 86.81                                                | 45.83                                      | 5.31                        | 36.83                                 | 64.68                    | 0                                   | 80                                                        | 0                                               | 0                                | 0                                          | 16                            | 
| 2007-09-11T00:00:00    | 1165.1               | 0                             | 798.5                                               | 0                                         | 0                          | 1                                    | 365.6                   | 290.7                 | 8.1                            | 103                                                  | 30.2                                       | 5.8                         | 43.4                                  | 100.2                    | 0                                   | 80                                                        | 0                                               | 0                                | 0                                          | 56                            | 
| 2007-09-25T00:00:00    | 1030.1               | 1                             | 738.2                                               | 3.5                                       | 0                          | 0                                    | 287.4                   | 339.1                 | 7.1                            | 136.1                                                | 41.3                                       | 6.6                         | 48.2                                  | 99.8                     | 0                                   | 104                                                       | 0                                               | 0                                | 0                                          | 0                             | 
```