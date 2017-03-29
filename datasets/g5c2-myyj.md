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
| Yes      | series tag     | department_num       | DEPARTMENT NUM       | text          | html          |
| Yes      | series tag     | department_name      | DEPARTMENT NAME      | text          | text          |
| Yes      | series tag     | division_num         | DIVISION NUM         | html          | html          |
| Yes      | series tag     | division_name        | DIVISION NAME        | text          | text          |
| Yes      | series tag     | job_code             | JOB CODE             | text          | html          |
| Yes      | series tag     | job_code_description | JOB TITLE            | text          | text          |
| Yes      | time           | hire_date            | CURRENT HIRE DATE    | calendar_date | calendar_date |
| No       |                | end_date             | EMPLOYMENT END DATE  | calendar_date | calendar_date |
| Yes      | numeric metric | scheduled_hours      | SCHEDULED HOURS      | number        | number        |
| No       |                | longevity_percentage | LONGEVITY PERCENTAGE | number        | number        |
| Yes      | numeric metric | base_hourly_rate     | BASE HOURLY RATE     | number        | number        |
| Yes      | numeric metric | total_hourly_rate    | TOTAL HOURLY RATE    | number        | number        |
| Yes      | numeric metric | overtime_hourly_rate | OVERTIME HOURLY RATE | number        | number        |
| Yes      | series tag     | payroll_status       | EMPLOYMENT STATUS    | text          | number        |
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
Excluded Fields = end_date,longevity_percentage,year
```

## Data Commands

```ls
series e:g5c2-myyj d:1988-04-19T00:00:00.000Z t:first_name=ROBERT t:department_num=21 t:job_code=182119 t:job_code_description="DEPUTY CONSTABLE - CAPTAIN" t:employee_num=000094 t:last_name=ACHORD t:division_num=2110000 t:payroll_status=0 t:department_name="CITY CONSTABLE" t:division_name="CITY CONSTABLE-GENERAL FUND" t:middle_init=J m:total_hourly_rate=28.3957 m:base_hourly_rate=24.3313 m:overtime_hourly_rate=46.2713 m:total_overtime_pay=3177.3 m:total_overtime_hours=66 m:scheduled_hours=80 m:base_pay=58904.9 m:gross_pay=62082.2

series e:g5c2-myyj d:1988-04-19T00:00:00.000Z t:first_name=ROBERT t:department_num=21 t:job_code=182119 t:job_code_description="DEPUTY CONSTABLE - CAPTAIN" t:employee_num=000094 t:last_name=ACHORD t:division_num=2110000 t:payroll_status=5 t:department_name="CITY CONSTABLE" t:division_name="CITY CONSTABLE-GENERAL FUND" t:middle_init=J m:total_hourly_rate=28.2243 m:base_hourly_rate=24.3313 m:overtime_hourly_rate=42.3365 m:total_overtime_pay=374.25 m:total_overtime_hours=8 m:scheduled_hours=80 m:base_pay=54906.9 m:gross_pay=55281.15

series e:g5c2-myyj d:2006-01-09T00:00:00.000Z t:first_name=WILLIAM t:department_num=05 t:job_code=370201 t:job_code_description="SR SPEC ASST PARISH ATTY-JOB SHARE" t:employee_num=000302 t:last_name=AARON t:division_num=0512000 t:payroll_status=0 t:department_name="PARISH ATTORNEY" t:division_name="PARISH ATTORNEY-LITIGATION" t:middle_init=R m:total_hourly_rate=47.5599 m:base_hourly_rate=39.6332 m:overtime_hourly_rate=71.3399 m:total_overtime_pay=0 m:total_overtime_hours=0 m:scheduled_hours=40 m:base_pay=49462.4 m:gross_pay=49462.4
```

## Meta Commands

```ls
metric m:scheduled_hours p:integer l:"SCHEDULED HOURS" d:"Scheduled hours per pay period" t:dataTypeName=number

metric m:base_hourly_rate p:float l:"BASE HOURLY RATE" d:"Hourly rate based on pay grade and step" t:dataTypeName=number

metric m:total_hourly_rate p:float l:"TOTAL HOURLY RATE" d:"Hourly rate plus longevity and other earning allowances (Educational, Hazardous Pay, etc)" t:dataTypeName=number

metric m:overtime_hourly_rate p:float l:"OVERTIME HOURLY RATE" d:"Hourly rate plus allowable overtime earning types multiplied by 1.5" t:dataTypeName=number

metric m:base_pay p:double l:"TOTAL BASE PAY" d:"Annual salary plus longevity and other earning allowances (Educational, Hazardous Pay, etc)" t:dataTypeName=money

metric m:gross_pay p:double l:"GROSS PAY" d:"Base pay plus overtime plus/minus any adjustments" t:dataTypeName=money

metric m:total_overtime_hours p:float l:"TOTAL OVERTIME HOURS" d:"Total number of overtime hours worked for the year" t:dataTypeName=number

metric m:total_overtime_pay p:double l:"TOTAL OVERTIME PAY" d:"Total overtime amount earned for the year" t:dataTypeName=money

entity e:g5c2-myyj l:"City-Parish Employee Annual Salaries" t:attribution="City of Baton Rouge - Human Resources" t:url=https://data.brla.gov/api/views/g5c2-myyj

property e:g5c2-myyj t:meta.view v:id=g5c2-myyj v:category=Government v:attributionLink=http://brgov.com/dept/hr v:averageRating=0 v:name="City-Parish Employee Annual Salaries" v:attribution="City of Baton Rouge - Human Resources"

property e:g5c2-myyj t:meta.view.license v:name="Public Domain"

property e:g5c2-myyj t:meta.view.owner v:id=mjn2-v86v v:profileImageUrlMedium=/api/users/mjn2-v86v/profile_images/THUMB v:profileImageUrlLarge=/api/users/mjn2-v86v/profile_images/LARGE v:screenName="Open Data BR" v:profileImageUrlSmall=/api/users/mjn2-v86v/profile_images/TINY v:displayName="Open Data BR"

property e:g5c2-myyj t:meta.view.tableauthor v:id=mjn2-v86v v:profileImageUrlMedium=/api/users/mjn2-v86v/profile_images/THUMB v:profileImageUrlLarge=/api/users/mjn2-v86v/profile_images/LARGE v:screenName="Open Data BR" v:profileImageUrlSmall=/api/users/mjn2-v86v/profile_images/TINY v:roleName=viewer v:displayName="Open Data BR"
```

## Top Records

```ls
| year | employee_num | last_name | first_name | middle_init | department_num | department_name   | division_num | division_name                           | job_code | job_code_description               | hire_date           | end_date            | scheduled_hours | longevity_percentage | base_hourly_rate | total_hourly_rate | overtime_hourly_rate | payroll_status | base_pay | gross_pay | total_overtime_hours | total_overtime_pay | 
| ==== | ============ | ========= | ========== | =========== | ============== | ================= | ============ | ======================================= | ======== | ================================== | =================== | =================== | =============== | ==================== | ================ | ================= | ==================== | ============== | ======== | ========= | ==================== | ================== | 
| 2008 | 000094       | ACHORD    | ROBERT     | J           | 21             | CITY CONSTABLE    | 2110000      | CITY CONSTABLE-GENERAL FUND             | 182119   | DEPUTY CONSTABLE - CAPTAIN         | 1988-04-19T00:00:00 | 2009-11-18T00:00:00 | 80              | 0.15                 | 24.3313          | 28.3957           | 46.2713              | 0              | 58904.9  | 62082.2   | 66                   | 3177.3             | 
| 2009 | 000094       | ACHORD    | ROBERT     | J           | 21             | CITY CONSTABLE    | 2110000      | CITY CONSTABLE-GENERAL FUND             | 182119   | DEPUTY CONSTABLE - CAPTAIN         | 1988-04-19T00:00:00 | 2009-11-18T00:00:00 | 80              | 0.16                 | 24.3313          | 28.2243           | 42.3365              | 5              | 54906.9  | 55281.15  | 8                    | 374.25             | 
| 2008 | 000302       | AARON     | WILLIAM    | R           | 05             | PARISH ATTORNEY   | 0512000      | PARISH ATTORNEY-LITIGATION              | 370201   | SR SPEC ASST PARISH ATTY-JOB SHARE | 2006-01-09T00:00:00 | 2011-07-28T00:00:00 | 40              | 0.2                  | 39.6332          | 47.5599           | 71.3399              | 0              | 49462.4  | 49462.4   | 0                    | 0                  | 
| 2009 | 000302       | AARON     | WILLIAM    | R           | 05             | PARISH ATTORNEY   | 0512000      | PARISH ATTORNEY-LITIGATION              | 370201   | SR SPEC ASST PARISH ATTY-JOB SHARE | 2006-01-09T00:00:00 | 2011-07-28T00:00:00 | 40              | 0.2                  | 39.6332          | 47.5599           | 71.3399              | 0              | 49462.4  | 49462.4   | 0                    | 0                  | 
| 2010 | 000302       | AARON     | WILLIAM    | R           | 05             | PARISH ATTORNEY   | 0512000      | PARISH ATTORNEY-LITIGATION              | 370201   | SR SPEC ASST PARISH ATTY-JOB SHARE | 2006-01-09T00:00:00 | 2011-07-28T00:00:00 | 40              | 0.2                  | 39.6332          | 47.5599           | 71.3399              | 0              | 48511.19 | 48511.19  | 0                    | 0                  | 
| 2011 | 000302       | AARON     | WILLIAM    | R           | 05             | PARISH ATTORNEY   | 0512000      | PARISH ATTORNEY-LITIGATION              | 370201   | SR SPEC ASST PARISH ATTY-JOB SHARE | 2006-01-09T00:00:00 | 2011-07-28T00:00:00 | 40              | 0.2                  | 39.6332          | 47.5599           | 71.3399              | 5              | 30438.4  | 30438.4   | 0                    | 0                  | 
| 2008 | 000337       | ADAMS     | RODNEY     | P           | 50             | POLICE DEPARTMENT | 5020001      | POLICE DEPARTMENT-UNIFORM PATROL BUREAU | 5020     | POLICE CAPTAIN                     | 1980-12-22T00:00:00 | 2010-11-17T00:00:00 | 80              | 0.2                  | 27.6491          | 33.179            | 53.4462              | 0              | 68986.93 | 86637.85  | 329.75               | 17650.92           | 
| 2009 | 000337       | ADAMS     | RODNEY     | P           | 50             | POLICE DEPARTMENT | 5020001      | POLICE DEPARTMENT-UNIFORM PATROL BUREAU | 5020     | POLICE CAPTAIN                     | 1980-12-22T00:00:00 | 2010-11-17T00:00:00 | 80              | 0.2                  | 27.6491          | 33.179            | 54.0954              | 0              | 71359.82 | 81537.06  | 189                  | 10177.24           | 
| 2010 | 000337       | ADAMS     | RODNEY     | P           | 50             | POLICE DEPARTMENT | 5020001      | POLICE DEPARTMENT-UNIFORM PATROL BUREAU | 5020     | POLICE CAPTAIN                     | 1980-12-22T00:00:00 | 2010-11-17T00:00:00 | 80              | 0.2                  | 27.6491          | 33.179            | 54.0954              | 5              | 64591.96 | 66863.96  | 42                   | 2272               | 
| 2008 | 000558       | ADOMITIS  | JOSEPH     | M           | 51             | FIRE DEPARTMENT   | 5120001      | FIRE DEPT-FIRE SUPPRESSION & PREVENTION | 170120   | DISTRICT FIRE CHIEF                | 1979-04-16T00:00:00 | 2010-12-09T00:00:00 | 112             | 0.2                  | 20.6354          | 25.7251           | 41.2146              | 0              | 73329.62 | 80584.73  | 173.24               | 7255.11            | 
```