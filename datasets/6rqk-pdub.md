# Employee Salaries - 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/employee-salaries-2015) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/6rqk-pdub) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/6rqk-pdub/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/6rqk-pdub/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | 6rqk-pdub |
| Name | Employee Salaries - 2015 |
| Category | Human Resources |
| Tags | 2015, annual, employee salaries, overtime, gross pay, salary and gender. |
| Created | 2016-02-09T19:52:28Z |
| Publication Date | 2016-02-10T18:51:56Z |

## Description

Annual salary information including gross pay and overtime pay for all active, permanent employees of Montgomery County, MD paid in calendar year 2015. This information will be published annually, by the end of January each year.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type     | Render Type   |
| ======== | ============== | ======================= | ======================= | ============= | ============= |
| Yes      | series tag     | full_name               | Full Name               | text          | text          |
| Yes      | series tag     | gender                  | Gender                  | text          | text          |
| Yes      | numeric metric | current_annual_salary   | Current Annual Salary   | money         | money         |
| Yes      | numeric metric | 2015_gross_pay_received | 2015 Gross Pay Received | money         | money         |
| Yes      | numeric metric | 2015_overtime_pay       | 2015 Overtime Pay       | money         | money         |
| Yes      | series tag     | department              | Department              | text          | text          |
| Yes      | series tag     | department_name         | Department Name         | text          | text          |
| Yes      | series tag     | division                | Division                | text          | text          |
| Yes      | series tag     | assignment_category     | Assignment Category     | text          | text          |
| Yes      | series tag     | position_title          | Position Title          | text          | text          |
| Yes      | series tag     | underfilled_job_title   | Underfilled Job Title   | text          | text          |
| Yes      | time           | date_first_hired        | Date First Hired        | calendar_date | calendar_date |
```

## Time Field

```ls
Value = date_first_hired
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:6rqk-pdub d:1986-09-22T00:00:00.000Z t:division="MSB Information Management and Technology Division Data Systems Section" t:department=POL t:gender=F t:position_title="Office Services Coordinator" t:assignment_category=Fulltime-Regular t:department_name="Department of Police" t:full_name="Aarhus, Pam J." m:current_annual_salary=68878.16 m:2015_gross_pay_received=72336.79

series e:6rqk-pdub d:1988-09-12T00:00:00.000Z t:division="ISB Major Crimes Division Fugitive Section" t:department=POL t:gender=M t:position_title="Master Police Officer" t:assignment_category=Fulltime-Regular t:department_name="Department of Police" t:full_name="Aaron, David J." m:current_annual_salary=96908.09 m:2015_gross_pay_received=101857 m:2015_overtime_pay=4640.99

series e:6rqk-pdub d:1989-11-19T00:00:00.000Z t:division="Adult Protective and Case Management Services" t:department=HHS t:gender=F t:position_title="Social Worker IV" t:assignment_category=Fulltime-Regular t:department_name="Department of Health and Human Services" t:full_name="Aaron, Marsha M." m:current_annual_salary=104196.06 m:2015_gross_pay_received=103019.73
```

## Meta Commands

```ls
metric m:current_annual_salary p:double l:"Current Annual Salary" d:"Annual salary for the employee at the end of calendar 2015. This includes base salary, longevity pay, pay differentials, etc. NOTE: This is the projected salary based on employee status and hours the employee is scheduled to work." t:dataTypeName=money

metric m:2015_gross_pay_received p:double l:"2015 Gross Pay Received" d:"All earnings/wages before pre-tax deductions the employee received during 2015. This includes base salary, longevity pay, pay differentials, performance pay, overtime pay, etc." t:dataTypeName=money

metric m:2015_overtime_pay p:double l:"2015 Overtime Pay" d:"2015 pay the employee received for hours worked beyond the employee?s normally scheduled workday or workweek. Encompasses all forms of overtime, including pay differential, lunch, and retroactive overtime. Also includes holiday premium and emergency pay." t:dataTypeName=money

entity e:6rqk-pdub l:"Employee Salaries - 2015" t:url=https://data.montgomerycountymd.gov/api/views/6rqk-pdub

property e:6rqk-pdub t:meta.view v:id=6rqk-pdub v:category="Human Resources" v:averageRating=0 v:name="Employee Salaries - 2015"

property e:6rqk-pdub t:meta.view.owner v:id=qzhb-tftn v:screenName="Kathy Luh" v:displayName="Kathy Luh"

property e:6rqk-pdub t:meta.view.tableauthor v:id=qzhb-tftn v:screenName="Kathy Luh" v:roleName=administrator v:displayName="Kathy Luh"
```

## Top Records

```ls
| full_name                | gender | current_annual_salary | 2015_gross_pay_received | 2015_overtime_pay | department | department_name                             | division                                                                | assignment_category | position_title               | underfilled_job_title | date_first_hired    | 
| ======================== | ====== | ===================== | ======================= | ================= | ========== | =========================================== | ======================================================================= | =================== | ============================ | ===================== | =================== | 
| Aarhus, Pam J.           | F      | 68878.16              | 72336.79                |                   | POL        | Department of Police                        | MSB Information Management and Technology Division Data Systems Section | Fulltime-Regular    | Office Services Coordinator  |                       | 1986-09-22T00:00:00 | 
| Aaron, David J.          | M      | 96908.09              | 101857.00               | 4640.99           | POL        | Department of Police                        | ISB Major Crimes Division Fugitive Section                              | Fulltime-Regular    | Master Police Officer        |                       | 1988-09-12T00:00:00 | 
| Aaron, Marsha M.         | F      | 104196.06             | 103019.73               |                   | HHS        | Department of Health and Human Services     | Adult Protective and Case Management Services                           | Fulltime-Regular    | Social Worker IV             |                       | 1989-11-19T00:00:00 | 
| Ababio, Godfred A.       | M      | 50697.79              | 54181.46                | 4445.15           | COR        | Correction and Rehabilitation               | PRRS Facility and Security                                              | Fulltime-Regular    | Resident Supervisor II       |                       | 2014-05-05T00:00:00 | 
| Ababu, Essayas           | M      | 92931.00              | 93468.35                |                   | HCA        | Department of Housing and Community Affairs | Single Family Housing Program                                           | Fulltime-Regular    | Planning Specialist III      |                       | 2007-03-05T00:00:00 | 
| Abbamonte, Drew B.       | M      | 67715.00              | 81392.40                | 10027.11          | POL        | Department of Police                        | PSB 6th District Special Assignment Team                                | Fulltime-Regular    | Police Officer III           |                       | 2007-07-16T00:00:00 | 
| Abdelmoniem, Marwan M.   | M      | 62286.30              | 59663.27                |                   | HHS        | Department of Health and Human Services     | Head Start                                                              | Fulltime-Regular    | Administrative Specialist II |                       | 2014-11-17T00:00:00 | 
| Abdul-Ghani, Hasinah J.  | F      | 45828.92              | 46783.23                | 6.38              | POL        | Department of Police                        | FSB Traffic Division Automated Traffic Enforcement Section              | Fulltime-Regular    | Police Aide                  |                       | 2007-02-05T00:00:00 | 
| Abduljabar, Saeed        | M      | 61040.57              | 66861.98                | 6569.81           | DGS        | Department of General Services              | Facilities Maintenance                                                  | Fulltime-Regular    | Electrician I                |                       | 2014-01-13T00:00:00 | 
| Abdur-Raheem, Mikaeel A. | M      | 56404.96              | 71943.08                | 15342.84          | DOT        | Department of Transportation                | Transit Silver Spring Ride On                                           | Fulltime-Regular    | Bus Operator                 |                       | 2002-04-28T00:00:00 | 
```