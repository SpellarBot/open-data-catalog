# City-Parish Employee Annual Salaries

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-parish-employee-annual-salaries) |
| Metadata | [Link](https://data.brla.gov/api/views/g5c2-myyj) |
| Data: JSON | [100 Rows](https://data.brla.gov/api/views/g5c2-myyj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.brla.gov/api/views/g5c2-myyj/rows.csv?max_rows=100) |
| Host | data.brla.gov |
| Id | g5c2-myyj |
| Name | City-Parish Employee Annual Salaries |
| Attribution | City of Baton Rouge - Human Resources |
| Category | Government |
| Tags | salary, employee, department, longevity |
| Created | 2014-11-23T15:12:20Z |
| Publication Date | 2017-01-05T01:07:21Z |
| Rows Updated | 2017-01-05T00:58:24Z |

## Description

City-Parish employees' annual salaries and other payroll related information. Information is calculated after the last payroll is run for the year specified.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type     | Render Type   |
| ======== | ============== | ==================== | ==================== | ============= | ============= |
| No       |                | year                 | YEAR                 | number        | number        |
| Yes      | series tag     | employee_num         | EMPLOYEE NUM         | html          | html          |
| Yes      | series tag     | last_name            | LAST NAME            | text          | text          |
| Yes      | series tag     | first_name           | FIRST NAME           | text          | text          |
| Yes      | series tag     | middle_init          | MIDDLE INIT          | text          | text          |
| Yes      | series tag     | department_num       | DEPARTMENT NUM       | html          | html          |
| Yes      | series tag     | department_name      | DEPARTMENT NAME      | text          | text          |
| Yes      | series tag     | division_num         | DIVISION NUM         | html          | html          |
| Yes      | series tag     | division_name        | DIVISION NAME        | text          | text          |
| Yes      | series tag     | job_code             | JOB CODE             | html          | html          |
| Yes      | series tag     | job_code_description | JOB TITLE            | text          | text          |
| Yes      | time           | hire_date            | CURRENT HIRE DATE    | calendar_date | calendar_date |
| No       |                | end_date             | EMPLOYMENT END DATE  | calendar_date | calendar_date |
| Yes      | numeric metric | scheduled_hours      | SCHEDULED HOURS      | number        | number        |
| Yes      | numeric metric | longevity_percentage | LONGEVITY PERCENTAGE | number        | number        |
| Yes      | numeric metric | base_hourly_rate     | BASE HOURLY RATE     | number        | number        |
| Yes      | numeric metric | total_hourly_rate    | TOTAL HOURLY RATE    | number        | number        |
| Yes      | numeric metric | overtime_hourly_rate | OVERTIME HOURLY RATE | number        | number        |
| Yes      | numeric metric | payroll_status       | EMPLOYMENT STATUS    | number        | number        |
| Yes      | numeric metric | base_pay             | TOTAL BASE PAY       | money         | money         |
| Yes      | numeric metric | gross_pay            | GROSS PAY            | money         | money         |
| Yes      | numeric metric | total_overtime_hours | TOTAL OVERTIME HOURS | number        | number        |
| Yes      | numeric metric | total_overtime_pay   | TOTAL OVERTIME PAY   | money         | money         |
```

## Time Field

```ls
Value = hire_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = end_date,year
```

## Data Commands

```ls
series e:g5c2-myyj d:1988-04-19T00:00:00.000Z t:first_name=ROBERT t:department_num=21 t:job_code=182119 t:job_code_description="DEPUTY CONSTABLE - CAPTAIN" t:employee_num=000094 t:last_name=ACHORD t:division_num=2110000 t:department_name="CITY CONSTABLE" t:division_name="CITY CONSTABLE-GENERAL FUND" t:middle_init=J m:total_hourly_rate=28.3957 m:base_hourly_rate=24.3313 m:overtime_hourly_rate=46.2713 m:total_overtime_pay=3177.3 m:payroll_status=0 m:total_overtime_hours=66 m:longevity_percentage=0.15 m:scheduled_hours=80 m:base_pay=58904.9 m:gross_pay=62082.2

series e:g5c2-myyj d:1988-04-19T00:00:00.000Z t:first_name=ROBERT t:department_num=21 t:job_code=182119 t:job_code_description="DEPUTY CONSTABLE - CAPTAIN" t:employee_num=000094 t:last_name=ACHORD t:division_num=2110000 t:department_name="CITY CONSTABLE" t:division_name="CITY CONSTABLE-GENERAL FUND" t:middle_init=J m:total_hourly_rate=28.2243 m:base_hourly_rate=24.3313 m:overtime_hourly_rate=42.3365 m:total_overtime_pay=374.25 m:payroll_status=5 m:total_overtime_hours=8 m:longevity_percentage=0.16 m:scheduled_hours=80 m:base_pay=54906.9 m:gross_pay=55281.15

series e:g5c2-myyj d:2006-01-09T00:00:00.000Z t:first_name=WILLIAM t:department_num=05 t:job_code=370201 t:job_code_description="SR SPEC ASST PARISH ATTY-JOB SHARE" t:employee_num=000302 t:last_name=AARON t:division_num=0512000 t:department_name="PARISH ATTORNEY" t:division_name="PARISH ATTORNEY-LITIGATION" t:middle_init=R m:total_hourly_rate=47.5599 m:base_hourly_rate=39.6332 m:overtime_hourly_rate=71.3399 m:total_overtime_pay=0 m:payroll_status=0 m:total_overtime_hours=0 m:longevity_percentage=0.2 m:scheduled_hours=40 m:base_pay=49462.4 m:gross_pay=49462.4
```

## Meta Commands

```ls
metric m:scheduled_hours p:integer l:"SCHEDULED HOURS" d:"Scheduled hours per pay period" t:dataTypeName=number

metric m:longevity_percentage p:float l:"LONGEVITY PERCENTAGE" d:"Percentage of pay earned by employee for longevity with City-Parish" t:dataTypeName=number

metric m:base_hourly_rate p:float l:"BASE HOURLY RATE" d:"Hourly rate based on pay grade and step" t:dataTypeName=number

metric m:total_hourly_rate p:float l:"TOTAL HOURLY RATE" d:"Hourly rate plus longevity and other earning allowances (Educational, Hazardous Pay, etc)" t:dataTypeName=number

metric m:overtime_hourly_rate p:float l:"OVERTIME HOURLY RATE" d:"Hourly rate plus allowable overtime earning types multiplied by 1.5" t:dataTypeName=number

metric m:payroll_status p:integer l:"EMPLOYMENT STATUS" d:"Status in payroll system: 0 - Active, 1 - Temporary Leave (no arrears), 2 - Temporary Leave with Arrears, 3 - Inactive, 4 - Terminated Last Pay Period, 5 - No longer with City-Parish." t:dataTypeName=number

metric m:base_pay p:double l:"TOTAL BASE PAY" d:"Annual salary plus longevity and other earning allowances (Educational, Hazardous Pay, etc)" t:dataTypeName=money

metric m:gross_pay p:double l:"GROSS PAY" d:"Base pay plus overtime plus/minus any adjustments" t:dataTypeName=money

metric m:total_overtime_hours p:float l:"TOTAL OVERTIME HOURS" d:"Total number of overtime hours worked for the year" t:dataTypeName=number

metric m:total_overtime_pay p:double l:"TOTAL OVERTIME PAY" d:"Total overtime amount earned for the year" t:dataTypeName=money

entity e:g5c2-myyj l:"City-Parish Employee Annual Salaries" t:attribution="City of Baton Rouge - Human Resources" t:url=https://data.brla.gov/api/views/g5c2-myyj

property e:g5c2-myyj t:meta.view v:id=g5c2-myyj v:category=Government v:attributionLink=http://brgov.com/dept/hr v:averageRating=0 v:name="City-Parish Employee Annual Salaries" v:attribution="City of Baton Rouge - Human Resources"

property e:g5c2-myyj t:meta.view.license v:name="Public Domain"

property e:g5c2-myyj t:meta.view.owner v:id=mjn2-v86v v:profileImageUrlMedium=/api/users/mjn2-v86v/profile_images/THUMB v:profileImageUrlLarge=/api/users/mjn2-v86v/profile_images/LARGE v:screenName="Open Data BR" v:profileImageUrlSmall=/api/users/mjn2-v86v/profile_images/TINY v:roleName=viewer v:displayName="Open Data BR"

property e:g5c2-myyj t:meta.view.tableauthor v:id=mjn2-v86v v:profileImageUrlMedium=/api/users/mjn2-v86v/profile_images/THUMB v:profileImageUrlLarge=/api/users/mjn2-v86v/profile_images/LARGE v:screenName="Open Data BR" v:profileImageUrlSmall=/api/users/mjn2-v86v/profile_images/TINY v:roleName=viewer v:displayName="Open Data BR"
```