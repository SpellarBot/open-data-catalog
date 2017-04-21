# 2012 Salary Reporting

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2012-salary-reporting-01ae3) |
| Metadata | [Link](https://data.illinois.gov/api/views/szp6-7w9h) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/szp6-7w9h/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/szp6-7w9h/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | szp6-7w9h |
| Name | 2012 Salary Reporting |
| Attribution | City of Rockford |
| Category | Municipality |
| Tags | rockford |
| Created | 2013-01-17T18:34:18Z |
| Publication Date | 2013-01-17T19:05:46Z |

## Description

2012 employee total compensation

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                        | Data Type | Render Type |
| ======== | ============== | ====================== | =========================== | ========= | =========== |
| Yes      | series tag     | last_name              | Last Name                   | text      | text        |
| Yes      | series tag     | first_name             | First Name                  | text      | text        |
| Yes      | series tag     | current_job_title      | Current Job Title           | text      | text        |
| Yes      | series tag     | department_location    | Department Location         | text      | text        |
| Yes      | numeric metric | base_earnings          | 2011 Base Earnings          | number    | number      |
| Yes      | numeric metric | overtime_earnings      | 2011 Overtime Earnings      | number    | number      |
| Yes      | numeric metric | total_earnings         | 2011 Total Earnings         | number    | number      |
| Yes      | numeric metric | salary_as_of_4_24_2012 | 2012 Salary as of 4/24/2012 | number    | number      |
| Yes      | numeric metric | health_ins             | Health Ins                  | number    | number      |
| Yes      | numeric metric | imrf                   | IMRF                        | number    | number      |
| Yes      | numeric metric | fica_med               | FICA/Med                    | number    | number      |
| Yes      | numeric metric | police_pension         | Police Pension              | number    | number      |
| Yes      | numeric metric | fire_pension           | Fire Pension                | number    | number      |
| Yes      | numeric metric | workers_comp           | Workers Comp                | number    | number      |
| Yes      | numeric metric | unemp                  | Unemp                       | number    | number      |
| Yes      | numeric metric | life_ins               | Life Ins                    | number    | number      |
| Yes      | numeric metric | parking                | Parking                     | number    | number      |
| Yes      | numeric metric | grand_total            | Grand Total                 | number    | number      |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:szp6-7w9h d:2012-01-01T00:00:00.000Z t:first_name=MICHAEL t:department_location=FIRE t:last_name=ADAMANY t:current_job_title="FIRE DRIVER ENGINEER" m:health_ins=24102 m:total_earnings=78763.6 m:unemp=180 m:fire_pension=18481 m:overtime_earnings=6515.37 m:fica_med=0 m:salary_as_of_4_24_2012=78008.84 m:police_pension=0 m:workers_comp=4540.11 m:imrf=0 m:life_ins=78 m:grand_total=125389.95 m:base_earnings=72248.23

series e:szp6-7w9h d:2012-01-01T00:00:00.000Z t:first_name=JEFFERY t:department_location="PUBLIC WORKS" t:last_name=ADAMI t:current_job_title="AUTOMOTIVE MECHANIC AFS1" m:health_ins=15548 m:total_earnings=62242.66 m:unemp=180 m:fire_pension=0 m:overtime_earnings=4004.02 m:fica_med=4736.94 m:salary_as_of_4_24_2012=61920.82 m:police_pension=0 m:workers_comp=2885.51 m:imrf=8161.16 m:life_ins=78 m:grand_total=93510.44 m:base_earnings=58238.64

series e:szp6-7w9h d:2012-01-01T00:00:00.000Z t:first_name="SARA EMILY" t:department_location=POLICE t:last_name=AHRENS t:current_job_title="POLICE SERGEANT" m:health_ins=24102 m:total_earnings=96409.87 m:unemp=180 m:fire_pension=0 m:parking=636 m:overtime_earnings=15658.08 m:fica_med=0 m:salary_as_of_4_24_2012=84938.36 m:police_pension=15828 m:workers_comp=3253.14 m:imrf=0 m:life_ins=78 m:grand_total=129015.5 m:base_earnings=80751.79
```

## Meta Commands

```ls
metric m:base_earnings p:float l:"2011 Base Earnings" t:dataTypeName=number

metric m:overtime_earnings p:float l:"2011 Overtime Earnings" t:dataTypeName=number

metric m:total_earnings p:float l:"2011 Total Earnings" t:dataTypeName=number

metric m:salary_as_of_4_24_2012 p:float l:"2012 Salary as of 4/24/2012" t:dataTypeName=number

metric m:health_ins p:float l:"Health Ins" t:dataTypeName=number

metric m:imrf p:float l:IMRF t:dataTypeName=number

metric m:fica_med p:float l:FICA/Med t:dataTypeName=number

metric m:police_pension p:float l:"Police Pension" t:dataTypeName=number

metric m:fire_pension p:float l:"Fire Pension" t:dataTypeName=number

metric m:workers_comp p:float l:"Workers Comp" t:dataTypeName=number

metric m:unemp p:float l:Unemp t:dataTypeName=number

metric m:life_ins p:float l:"Life Ins" t:dataTypeName=number

metric m:parking p:float l:Parking t:dataTypeName=number

metric m:grand_total p:double l:"Grand Total" t:dataTypeName=number

entity e:szp6-7w9h l:"2012 Salary Reporting" t:attribution="City of Rockford" t:url=https://data.illinois.gov/api/views/szp6-7w9h

property e:szp6-7w9h t:meta.view v:id=szp6-7w9h v:category=Municipality v:averageRating=0 v:name="2012 Salary Reporting" v:attribution="City of Rockford"

property e:szp6-7w9h t:meta.view.owner v:id=hdqp-matg v:profileImageUrlMedium=/api/users/hdqp-matg/profile_images/THUMB v:profileImageUrlLarge=/api/users/hdqp-matg/profile_images/LARGE v:screenName=Glenn v:profileImageUrlSmall=/api/users/hdqp-matg/profile_images/TINY v:displayName=Glenn

property e:szp6-7w9h t:meta.view.tableauthor v:id=hdqp-matg v:profileImageUrlMedium=/api/users/hdqp-matg/profile_images/THUMB v:profileImageUrlLarge=/api/users/hdqp-matg/profile_images/LARGE v:screenName=Glenn v:profileImageUrlSmall=/api/users/hdqp-matg/profile_images/TINY v:roleName=publisher v:displayName=Glenn
```

## Top Records

```ls
| last_name | first_name    | current_job_title        | department_location | base_earnings | overtime_earnings | total_earnings | salary_as_of_4_24_2012 | health_ins | imrf    | fica_med | police_pension | fire_pension | workers_comp | unemp  | life_ins | parking | grand_total | 
| ========= | ============= | ======================== | =================== | ============= | ================= | ============== | ====================== | ========== | ======= | ======== | ============== | ============ | ============ | ====== | ======== | ======= | =========== | 
| ADAMANY   | MICHAEL       | FIRE DRIVER ENGINEER     | FIRE                | 72248.23      | 6515.37           | 78763.60       | 78008.84               | 24102.00   | 0.00    | 0.00     | 0.00           | 18481.00     | 4540.11      | 180.00 | 78.00    |         | 125389.95   | 
| ADAMI     | JEFFERY       | AUTOMOTIVE MECHANIC AFS1 | PUBLIC WORKS        | 58238.64      | 4004.02           | 62242.66       | 61920.82               | 15548.00   | 8161.16 | 4736.94  | 0.00           | 0.00         | 2885.51      | 180.00 | 78.00    |         | 93510.44    | 
| AHRENS    | SARA EMILY    | POLICE SERGEANT          | POLICE              | 80751.79      | 15658.08          | 96409.87       | 84938.36               | 24102.00   | 0.00    | 0.00     | 15828.00       | 0.00         | 3253.14      | 180.00 | 78.00    | 636.00  | 129015.50   | 
| AHRENS    | MICHAEL       | POLICE SERGEANT          | POLICE              | 85170.36      | 13734.34          | 98904.70       | 84338.28               | 0.00       | 0.00    | 0.00     | 15828.00       | 0.00         | 3230.16      | 180.00 | 78.00    | 636.00  | 104290.44   | 
| ALBRIGHT  | SHEENA KAY    | FIREFIGHTER 51 HR        | FIRE                | 62690.18      | 8823.64           | 71513.82       | 72081.88               | 16068.00   | 0.00    | 0.00     | 0.00           | 18481.00     | 4195.17      | 180.00 | 78.00    |         | 111084.05   | 
| ALDRICH   | CHRISTOPHER   | POLICE INVESTIGATOR      | POLICE              | 74912.04      | 5696.87           | 80608.91       | 75832.64               | 24102.00   | 0.00    | 0.00     | 15828.00       | 0.00         | 2904.39      | 180.00 | 78.00    | 636.00  | 119561.03   | 
| ALEGRIA   | BRENDA        | LAND USE PLANNER AFSB    | BUILDING DEPARTMENT | 48542.00      | 104.18            | 48646.18       | 48152.00               | 15548.00   | 6346.43 | 3683.63  | 0.00           | 0.00         | 134.83       | 180.00 | 78.00    | 516.00  | 74638.89    | 
| ALEXANDER | ISHELIA       | ADMINISTRATIVE ASSISTANT | LEGAL DEPARTMENT    | 45134.38      | 1825.43           | 46959.81       | 46092.80               | 15548.00   | 6075.03 | 3526.10  | 0.00           | 0.00         | 129.06       | 180.00 | 78.00    | 1152.00 | 72780.99    | 
| ALLEN     | DOUGLAS       | FIRE CAPTAIN/COORD       | FIRE                | 75358.72      | 18498.06          | 93856.78       | 84052.80               | 24102.00   | 0.00    | 0.00     | 0.00           | 18481.00     | 4891.87      | 180.00 | 78.00    |         | 131785.67   | 
| ALLEN     | DANIEL JOSEPH | FIREFIGHTER 51 HR        | FIRE                | 25634.77      | 3217.21           | 28851.98       | 72081.88               | 24102.00   | 0.00    | 0.00     | 0.00           | 18481.00     | 4195.17      | 180.00 | 78.00    |         | 119118.05   | 
```