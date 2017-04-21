# 2014 Salary Reporting

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2014-salary-reporting) |
| Metadata | [Link](https://data.illinois.gov/api/views/h8gb-xkm2) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/h8gb-xkm2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/h8gb-xkm2/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | h8gb-xkm2 |
| Name | 2014 Salary Reporting |
| Category | Municipality |
| Tags | 2014 salary reporting, rockford |
| Created | 2015-06-25T13:41:21Z |
| Publication Date | 2015-06-25T15:24:09Z |

## Description

2014 employee total compensation

## Columns

```ls
| Included | Schema Type    | Field Name                         | Name                                 | Data Type | Render Type |
| ======== | ============== | ================================== | ==================================== | ========= | =========== |
| Yes      | series tag     | last_name                          | Last Name                            | text      | text        |
| Yes      | series tag     | first_name                         | First Name                           | text      | text        |
| Yes      | series tag     | current_job_title                  | Current Job Title                    | text      | text        |
| Yes      | series tag     | department_location                | Department Location                  | text      | text        |
| Yes      | numeric metric | 2014_pay                           | 2014 Pay                             | number    | number      |
| Yes      | numeric metric | 2014_overtime_pay                  | 2014 Overtime Pay                    | number    | number      |
| Yes      | numeric metric | 2014_total_pay                     | 2014 Total Pay                       | number    | number      |
| Yes      | numeric metric | 2015_budgeted_salary               | 2015 Budgeted Salary                 | number    | number      |
| Yes      | numeric metric | health_ins                         | Health Ins                           | number    | number      |
| Yes      | numeric metric | imrf                               | IMRF                                 | number    | number      |
| Yes      | numeric metric | fica_med                           | FICA/Med                             | number    | number      |
| Yes      | numeric metric | police_pension                     | Police Pension                       | number    | number      |
| Yes      | numeric metric | fire_pension                       | Fire Pension                         | number    | number      |
| Yes      | numeric metric | workers_comp                       | Workers Comp                         | number    | number      |
| Yes      | numeric metric | unemp                              | Unemp                                | number    | number      |
| Yes      | numeric metric | life_ins                           | Life Ins                             | number    | number      |
| Yes      | numeric metric | parking                            | Parking                              | number    | number      |
| Yes      | numeric metric | 2015_grand_total_salaries_benefits | 2015 Grand Total Salaries & Benefits | number    | number      |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:h8gb-xkm2 d:2014-01-01T00:00:00.000Z t:first_name=PATRICK t:department_location="LEGAL DEPARTMENT" t:last_name=HAYES t:current_job_title="LEGAL DIRECTOR" m:health_ins=19890 m:unemp=180 m:fire_pension=0 m:parking=1248 m:2014_overtime_pay=0 m:fica_med=10995.9876 m:2015_grand_total_salaries_benefits=194557.65047999998 m:2015_budgeted_salary=143738.4 m:2014_pay=140845.57 m:police_pension=0 m:workers_comp=402.46752000000004 m:imrf=18024.795359999996 m:life_ins=78 m:2014_total_pay=140845.57

series e:h8gb-xkm2 d:2014-01-01T00:00:00.000Z t:first_name=CHESTER t:department_location=POLICE t:last_name=EPPERSON t:current_job_title="POLICE CHIEF" m:health_ins=20592 m:unemp=180 m:fire_pension=0 m:parking=684 m:2014_overtime_pay=0 m:fica_med=0 m:2015_grand_total_salaries_benefits=188235.776016 m:2015_budgeted_salary=140131.68 m:2014_pay=137985.7 m:police_pension=21147 m:workers_comp=5423.0960159999995 m:imrf=0 m:life_ins=78 m:2014_total_pay=137985.7

series e:h8gb-xkm2 d:2014-01-01T00:00:00.000Z t:first_name=DEREK t:department_location=FIRE t:last_name=BERGSTEN t:current_job_title="FIRE CHIEF" m:health_ins=20592 m:unemp=180 m:fire_pension=28687 m:2014_overtime_pay=0 m:fica_med=0 m:2015_grand_total_salaries_benefits=184982.233214 m:2015_budgeted_salary=127911.26 m:2014_pay=126013.12 m:police_pension=0 m:workers_comp=7533.973213999999 m:imrf=0 m:life_ins=78 m:2014_total_pay=126013.12
```

## Meta Commands

```ls
metric m:2014_pay p:float l:"2014 Pay" t:dataTypeName=number

metric m:2014_overtime_pay p:float l:"2014 Overtime Pay" t:dataTypeName=number

metric m:2014_total_pay p:float l:"2014 Total Pay" t:dataTypeName=number

metric m:2015_budgeted_salary p:float l:"2015 Budgeted Salary" t:dataTypeName=number

metric m:health_ins p:float l:"Health Ins" t:dataTypeName=number

metric m:imrf p:double l:IMRF t:dataTypeName=number

metric m:fica_med p:double l:FICA/Med t:dataTypeName=number

metric m:police_pension p:integer l:"Police Pension" t:dataTypeName=number

metric m:fire_pension p:integer l:"Fire Pension" t:dataTypeName=number

metric m:workers_comp p:decimal l:"Workers Comp" t:dataTypeName=number

metric m:unemp p:integer l:Unemp t:dataTypeName=number

metric m:life_ins p:integer l:"Life Ins" t:dataTypeName=number

metric m:parking p:integer l:Parking t:dataTypeName=number

metric m:2015_grand_total_salaries_benefits p:double l:"2015 Grand Total Salaries & Benefits" t:dataTypeName=number

entity e:h8gb-xkm2 l:"2014 Salary Reporting" t:url=https://data.illinois.gov/api/views/h8gb-xkm2

property e:h8gb-xkm2 t:meta.view v:id=h8gb-xkm2 v:category=Municipality v:averageRating=0 v:name="2014 Salary Reporting"

property e:h8gb-xkm2 t:meta.view.owner v:id=hdqp-matg v:profileImageUrlMedium=/api/users/hdqp-matg/profile_images/THUMB v:profileImageUrlLarge=/api/users/hdqp-matg/profile_images/LARGE v:screenName=Glenn v:profileImageUrlSmall=/api/users/hdqp-matg/profile_images/TINY v:displayName=Glenn

property e:h8gb-xkm2 t:meta.view.tableauthor v:id=hdqp-matg v:profileImageUrlMedium=/api/users/hdqp-matg/profile_images/THUMB v:profileImageUrlLarge=/api/users/hdqp-matg/profile_images/LARGE v:screenName=Glenn v:profileImageUrlSmall=/api/users/hdqp-matg/profile_images/TINY v:roleName=publisher v:displayName=Glenn
```

## Top Records

```ls
| last_name    | first_name  | current_job_title        | department_location | 2014_pay           | 2014_overtime_pay | 2014_total_pay     | 2015_budgeted_salary | health_ins | imrf               | fica_med           | police_pension | fire_pension | workers_comp       | unemp | life_ins | parking | 2015_grand_total_salaries_benefits | 
| ============ | =========== | ======================== | =================== | ================== | ================= | ================== | ==================== | ========== | ================== | ================== | ============== | ============ | ================== | ===== | ======== | ======= | ================================== | 
| HAYES        | PATRICK     | LEGAL DIRECTOR           | LEGAL DEPARTMENT    | 140845.57          | 0                 | 140845.57          | 143738.4             | 19890      | 18024.795359999996 | 10995.9876         | 0              | 0            | 402.46752000000004 | 180   | 78       | 1248    | 194557.65047999998                 | 
| EPPERSON     | CHESTER     | POLICE CHIEF             | POLICE              | 137985.70000000001 | 0                 | 137985.70000000001 | 140131.68            | 20592      | 0                  | 0                  | 21147          | 0            | 5423.0960159999995 | 180   | 78       | 684     | 188235.77601599999                 | 
| BERGSTEN     | DEREK       | FIRE CHIEF               | FIRE                | 126013.12          | 0                 | 126013.12          | 127911.26            | 20592      | 0                  | 0                  | 0              | 28687        | 7533.9732139999987 | 180   | 78       |         | 184982.23321400001                 | 
| RYAN         | JAMES       | CITY ADMINISTRATOR       | MAYORS OFFICE       | 131608.79999999999 | 0                 | 131608.79999999999 | 134360.93            | 20592      | 16848.860621999997 | 10278.611144999999 | 0              | 0            | 376.21060400000005 | 180   | 78       | 564     | 183278.612371                      | 
| HANSON       | TIMOTHY     | PUBLIC WORKS DIRECTOR    | PUBLIC WORKS        | 129598.88          | 0                 | 129598.88          | 132260.54            | 20592      | 16585.471716       | 10117.93131        | 0              | 0            | 370.32951200000008 | 180   | 78       | 564     | 180748.27253799999                 | 
| CORL         | JOSEPH      | DIV CHIEF EMERGENCY OPPS | FIRE                | 120046.24          | 0                 | 120046.24          | 121949.57            | 20592      | 0                  | 0                  | 0              | 28687        | 7182.8296729999993 | 180   | 78       |         | 178669.39967300001                 | 
| BLACK        | CHRISTOPHER | FINANCE DIRECTOR         | FINANCE DEPT        | 126376.56          | 0                 | 126376.56          | 128972.06            | 20397      | 16173.096323999998 | 9866.3625900000006 | 0              | 0            | 361.12176800000003 | 180   | 78       | 564     | 176591.640682                      | 
| SCOTT-VALDEZ | JULIA       | HUMAN RESOURCES DIRECTOR | HUMAN RESOURCES     | 122094             | 0                 | 122094             | 124601.57            | 20592      | 15625.036877999999 | 9532.0201049999996 | 0              | 0            | 348.88439600000009 | 180   | 78       | 1248    | 172205.51137900003                 | 
| KNOTT        | MATTHEW     | DIV CHIEF FIRE TRAINING  | FIRE                | 120046.24          | 0                 | 120046.24          | 121949.57            | 20592      | 0                  | 0                  | 0              | 28687        | 341.45879600000006 | 180   | 78       |         | 171828.028796                      | 
| MORRISSEY    | LAWRENCE    | MAYOR                    | MAYORS OFFICE       | 130889.87          | 0                 | 130889.87          | 124696               | 20592      | 15636.878399999998 | 9539.2440000000006 | 0              | 0            | 0                  | 180   | 78       | 564     | 171286.12239999999                 | 
```