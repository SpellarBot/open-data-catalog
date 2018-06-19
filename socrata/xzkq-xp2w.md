# Current Employee Names, Salaries, and Position Titles

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/current-employee-names-salaries-and-position-titles-840f7) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/xzkq-xp2w) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/xzkq-xp2w/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/xzkq-xp2w/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | xzkq-xp2w |
| Name | Current Employee Names, Salaries, and Position Titles |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | personnel |
| Created | 2011-09-27T20:18:55Z |
| Publication Date | 2017-04-12T20:40:32Z |

## Description

This dataset is a listing of all current City of Chicago employees, complete with full names, departments, positions, and annual salaries. For hourly employees the annual salary is estimated. Data Owner: Human Resources. Frequency: Data is updated quarterly. For information on the positions and related salaries detailed in the annual budgets, see https://data.cityofchicago.org/browse?limitTo=datasets&q="Budget+Ordinance+-+Positions+and+Salaries"&sortBy=newest&tags=budget.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| No       | time           | :updated_at            | updated_at             | meta_data | meta_data   |
| Yes      | series tag     | name                   | Name                   | text      | text        |
| Yes      | series tag     | job_titles             | Position Title         | text      | text        |
| Yes      | series tag     | department             | Department             | text      | text        |
| Yes      | numeric metric | employee_annual_salary | Employee Annual Salary | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:xzkq-xp2w d:2017-04-12T20:39:09.000Z t:job_titles=SERGEANT t:department=POLICE t:name="AARON,  JEFFERY M" m:employee_annual_salary=101442

series e:xzkq-xp2w d:2017-04-12T20:39:09.000Z t:job_titles="POLICE OFFICER" t:department=POLICE t:name="AARON,  KARINA" m:employee_annual_salary=86142

series e:xzkq-xp2w d:2017-04-12T20:39:09.000Z t:job_titles="CHIEF CONTRACT EXPEDITER" t:department="GENERAL SERVICES" t:name="AARON,  KIMBERLEI R" m:employee_annual_salary=95148
```

## Meta Commands

```ls
metric m:employee_annual_salary p:double l:"Employee Annual Salary" t:dataTypeName=money

entity e:xzkq-xp2w l:"Current Employee Names, Salaries, and Position Titles" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/xzkq-xp2w

property e:xzkq-xp2w t:meta.view v:id=xzkq-xp2w v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Current Employee Names, Salaries, and Position Titles" v:attribution="City of Chicago"

property e:xzkq-xp2w t:meta.view.owner v:id=vi9p-p863 v:screenName="Eric Phillips" v:displayName="Eric Phillips"

property e:xzkq-xp2w t:meta.view.tableauthor v:id=vi9p-p863 v:screenName="Eric Phillips" v:displayName="Eric Phillips"
```

## Top Records

```ls
| :updated_at | name                 | job_titles                  | department       | employee_annual_salary | 
| =========== | ==================== | =========================== | ================ | ====================== | 
| 1492029549  | AARON, JEFFERY M     | SERGEANT                    | POLICE           | 101442.00              | 
| 1492029549  | AARON, KARINA        | POLICE OFFICER              | POLICE           | 86142.00               | 
| 1492029549  | AARON, KIMBERLEI R   | CHIEF CONTRACT EXPEDITER    | GENERAL SERVICES | 95148.00               | 
| 1492029549  | ABAD JR, VICENTE M   | CIVIL ENGINEER IV           | WATER MGMNT      | 107904.00              | 
| 1492029549  | ABARCA, ANABEL       | SENIOR POLICY ANALYST       | HEALTH           | 79284.00               | 
| 1492029549  | ABASCAL, REECE E     | TRAFFIC CONTROL AIDE-HOURLY | OEMC             | 20248.80               | 
| 1492029549  | ABBASI, CHRISTOPHER  | STAFF ASST TO THE ALDERMAN  | CITY COUNCIL     | 50436.00               | 
| 1492029549  | ABBATACOLA, ROBERT J | ELECTRICAL MECHANIC         | AVIATION         | 95888.00               | 
| 1492029549  | ABBATE, JOSEPH L     | POOL MOTOR TRUCK DRIVER     | STREETS & SAN    | 74048.00               | 
| 1492029549  | ABBATE, TERRY M      | POLICE OFFICER              | POLICE           | 92430.00               | 
```