# 2013 Salary Reporting

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2013-salary-reporting-d282d) |
| Metadata | [Link](https://data.illinois.gov/api/views/kfq4-b2hu) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/kfq4-b2hu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/kfq4-b2hu/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | kfq4-b2hu |
| Name | 2013 Salary Reporting |
| Category | Municipality |
| Tags | rockford |
| Created | 2013-03-21T16:02:55Z |
| Publication Date | 2013-03-21T16:05:50Z |

## Description

2013 employee total compensation

## Columns

```ls
| Included | Schema Type    | Field Name                             | Name                                   | Data Type | Render Type |
| ======== | ============== | ====================================== | ====================================== | ========= | =========== |
| Yes      | series tag     | last_name                              | Last Name                              | text      | text        |
| Yes      | series tag     | first_name                             | First Name                             | text      | text        |
| Yes      | series tag     | current_job_title                      | Current Job Title                      | text      | text        |
| Yes      | series tag     | department_location                    | Department Location                    | text      | text        |
| Yes      | numeric metric | 2012_pay                               | 2012 Pay                               | number    | number      |
| Yes      | numeric metric | 2012_overtime_pay                      | 2012 Overtime Pay                      | number    | number      |
| Yes      | numeric metric | 2012_total_pay                         | 2012 Total Pay                         | number    | number      |
| Yes      | numeric metric | 2013_budgeted_salary                   | 2013 Budgeted Salary                   | number    | number      |
| Yes      | numeric metric | health_ins                             | Health Ins                             | number    | number      |
| Yes      | numeric metric | imrf                                   | IMRF                                   | number    | number      |
| Yes      | numeric metric | fica_med                               | FICA/Med                               | number    | number      |
| Yes      | numeric metric | police_pension                         | Police Pension                         | number    | number      |
| Yes      | numeric metric | fire_pension                           | Fire Pension                           | number    | number      |
| Yes      | numeric metric | workers_comp                           | Workers Comp                           | number    | number      |
| Yes      | numeric metric | unemp                                  | Unemp                                  | number    | number      |
| Yes      | numeric metric | life_ins                               | Life Ins                               | number    | number      |
| Yes      | numeric metric | parking                                | Parking                                | number    | number      |
| Yes      | numeric metric | 2013_grand_total_salaries_and_benefits | 2013 Grand Total Salaries and Benefits | number    | number      |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:kfq4-b2hu d:2013-01-01T00:00:00.000Z t:first_name=MICHAEL t:department_location=FIRE t:last_name=ADAMANY t:current_job_title="FIRE DRIVER ENGINEER" m:unemp=180 m:health_ins=24102 m:fire_pension=21158 m:fica_med=0 m:2012_total_pay=104070.21 m:2013_grand_total_salaries_and_benefits=128293.18 m:2013_budgeted_salary=78008.84 m:2012_pay=76074.48 m:2012_overtime_pay=27995.73 m:workers_comp=4766.34 m:police_pension=0 m:imrf=0 m:life_ins=78

series e:kfq4-b2hu d:2013-01-01T00:00:00.000Z t:first_name=JEFFERY t:department_location="PUBLIC WORKS" t:last_name=ADAMI t:current_job_title="RETIRED OR SEPARATED IN 2012" m:2012_total_pay=28969.06 m:2012_overtime_pay=2631.05 m:2012_pay=26338.01

series e:kfq4-b2hu d:2013-01-01T00:00:00.000Z t:first_name=AUDREY t:department_location="HUMAN SERVICES" t:last_name=ADAMS t:current_job_title="HOMEVISIT TEACHER AFHE 37 WK" m:unemp=180 m:health_ins=7774 m:fire_pension=0 m:fica_med=3099.66 m:2012_total_pay=12311.36 m:2013_grand_total_salaries_and_benefits=57306.43 m:2013_budgeted_salary=40518.4 m:2012_pay=12311.36 m:2012_overtime_pay=0 m:workers_comp=117.5 m:police_pension=0 m:imrf=5538.87 m:life_ins=78
```

## Meta Commands

```ls
metric m:2012_pay p:float l:"2012 Pay" t:dataTypeName=number

metric m:2012_overtime_pay p:float l:"2012 Overtime Pay" t:dataTypeName=number

metric m:2012_total_pay p:double l:"2012 Total Pay" t:dataTypeName=number

metric m:2013_budgeted_salary p:float l:"2013 Budgeted Salary" t:dataTypeName=number

metric m:health_ins p:float l:"Health Ins" t:dataTypeName=number

metric m:imrf p:float l:IMRF t:dataTypeName=number

metric m:fica_med p:float l:FICA/Med t:dataTypeName=number

metric m:police_pension p:float l:"Police Pension" t:dataTypeName=number

metric m:fire_pension p:float l:"Fire Pension" t:dataTypeName=number

metric m:workers_comp p:float l:"Workers Comp" t:dataTypeName=number

metric m:unemp p:float l:Unemp t:dataTypeName=number

metric m:life_ins p:float l:"Life Ins" t:dataTypeName=number

metric m:parking p:float l:Parking t:dataTypeName=number

metric m:2013_grand_total_salaries_and_benefits p:double l:"2013 Grand Total Salaries and Benefits" t:dataTypeName=number

entity e:kfq4-b2hu l:"2013 Salary Reporting" t:url=https://data.illinois.gov/api/views/kfq4-b2hu

property e:kfq4-b2hu t:meta.view v:id=kfq4-b2hu v:category=Municipality v:averageRating=0 v:name="2013 Salary Reporting"

property e:kfq4-b2hu t:meta.view.owner v:id=hdqp-matg v:profileImageUrlMedium=/api/users/hdqp-matg/profile_images/THUMB v:profileImageUrlLarge=/api/users/hdqp-matg/profile_images/LARGE v:screenName=Glenn v:profileImageUrlSmall=/api/users/hdqp-matg/profile_images/TINY v:displayName=Glenn

property e:kfq4-b2hu t:meta.view.tableauthor v:id=hdqp-matg v:profileImageUrlMedium=/api/users/hdqp-matg/profile_images/THUMB v:profileImageUrlLarge=/api/users/hdqp-matg/profile_images/LARGE v:screenName=Glenn v:profileImageUrlSmall=/api/users/hdqp-matg/profile_images/TINY v:roleName=publisher v:displayName=Glenn
```

## Top Records

```ls
| last_name | first_name  | current_job_title             | department_location | 2012_pay | 2012_overtime_pay | 2012_total_pay | 2013_budgeted_salary | health_ins | imrf    | fica_med | police_pension | fire_pension | workers_comp | unemp  | life_ins | parking | 2013_grand_total_salaries_and_benefits | 
| ========= | =========== | ============================= | =================== | ======== | ================= | ============== | ==================== | ========== | ======= | ======== | ============== | ============ | ============ | ====== | ======== | ======= | ====================================== | 
| ADAMANY   | MICHAEL     | FIRE DRIVER ENGINEER          | FIRE                | 76074.48 | 27995.73          | 104070.21      | 78008.84             | 24102.00   | 0.00    | 0.00     | 0.00           | 21158.00     | 4766.34      | 180.00 | 78.00    |         | 128293.18                              | 
| ADAMI     | JEFFERY     | RETIRED OR SEPARATED IN 2012  | PUBLIC WORKS        | 26338.01 | 2631.05           | 28969.06       |                      |            |         |          |                |              |              |        |          |         |                                        | 
| ADAMS     | AUDREY      | HOMEVISIT TEACHER AFHE 37 WK  | HUMAN SERVICES      | 12311.36 | 0.00              | 12311.36       | 40518.40             | 7774.00    | 5538.87 | 3099.66  | 0.00           | 0.00         | 117.50       | 180.00 | 78.00    |         | 57306.43                               | 
| AHRENS    | SARA        | POLICE SERGEANT               | POLICE              | 87545.36 | 30354.07          | 117899.43      | 84938.36             | 24102.00   | 0.00    | 0.00     | 16915.00       | 0.00         | 3414.52      | 180.00 | 78.00    | 684.00  | 130311.88                              | 
| AHRENS    | MICHAEL     | POLICE SERGEANT               | POLICE              | 89676.46 | 22619.87          | 112296.33      | 84338.28             | 0.00       | 0.00    | 0.00     | 16915.00       | 0.00         | 3390.40      | 180.00 | 78.00    | 684.00  | 105585.68                              | 
| AKERS     | NICHOLAS    | WTR OPERATIONS SUPR - DISTRIB | PUBLIC WORKS        | 25253.52 | 0.00              | 25253.52       | 47236.80             | 7202.00    | 6457.27 | 3613.62  | 0.00           | 0.00         | 136.99       | 180.00 | 78.00    |         | 64904.67                               | 
| ALAMILLO  | SANDRA      | BUS DRIVER AFHN 37 WEEK       | HUMAN SERVICES      | 1620.24  | 0.00              | 1620.24        | 17634.24             | 0.00       | 2410.60 | 1349.02  | 0.00           | 0.00         | 1243.21      | 180.00 | 78.00    |         | 22895.07                               | 
| ALDRICH   | CHRISTOPHER | POLICE INVESTIGATOR           | POLICE              | 78138.36 | 4639.53           | 82777.89       | 75832.64             | 24102.00   | 0.00    | 0.00     | 16915.00       | 0.00         | 3048.47      | 180.00 | 78.00    | 684.00  | 120840.11                              | 
| ALEGRIA   | BRENDA      | LAND USE PLANNER AFSB         | BUILDING DEPARTMENT | 48542.03 | 0.00              | 48542.03       | 48152.00             | 23322.00   | 6582.38 | 3683.63  | 0.00           | 0.00         | 139.64       | 180.00 | 78.00    | 564.00  | 82701.65                               | 
| ALEXANDER | ISHELIA     | ADMINISTRATIVE ASSISTANT      | LEGAL DEPARTMENT    | 46071.14 | 2223.40           | 48294.54       | 47465.60             | 15548.00   | 6488.55 | 3631.12  | 0.00           | 0.00         | 137.65       | 180.00 | 78.00    | 564.00  | 74092.92                               | 
```