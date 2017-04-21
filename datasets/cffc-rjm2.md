# Salaries: ESD: Douglas: Fiscal Year 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salaries-esd-douglas-fiscal-year-2013-91cff) |
| Metadata | [Link](https://data.oregon.gov/api/views/cffc-rjm2) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/cffc-rjm2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/cffc-rjm2/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | cffc-rjm2 |
| Name | Salaries: ESD: Douglas: Fiscal Year 2013 |
| Category | Revenue & Expense |
| Tags | salaries, esd, douglas, fiscal year 2013 |
| Created | 2013-10-31T20:47:38Z |
| Publication Date | 2013-10-31T20:54:29Z |

## Description

Salaries for Douglas ESD for Fiscal Year 2013

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| Yes      | series tag     | esd_id              | ESD ID              | text      | number      |
| Yes      | series tag     | esdname             | ESDName             | text      | text        |
| Yes      | series tag     | pstncd              | PstnCd              | text      | text        |
| Yes      | series tag     | position            | Position            | text      | text        |
| Yes      | series tag     | number_of_employees | Number of Employees | text      | text        |
| Yes      | series tag     | total_fte           | Total FTE           | text      | text        |
| Yes      | numeric metric | total_salary_wages  | Total Salary/Wages  | number    | number      |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:cffc-rjm2 d:2013-01-01T00:00:00.000Z t:position="Assessment Support Specialist" t:number_of_employees="* 1" t:esd_id=1980 t:esdname="Douglas Education Service District" t:total_fte="* 1.0000" m:total_salary_wages=33046

series e:cffc-rjm2 d:2013-01-01T00:00:00.000Z t:position="Assistant Director of Special Education/EI-ECSE" t:number_of_employees="* 1" t:esd_id=1980 t:esdname="Douglas Education Service District" t:total_fte="* 1.0000" m:total_salary_wages=87788.62

series e:cffc-rjm2 d:2013-01-01T00:00:00.000Z t:position="Behavior Consultant" t:number_of_employees="* 1" t:esd_id=1980 t:esdname="Douglas Education Service District" t:total_fte="* 0.3000" m:total_salary_wages=20204.7
```

## Meta Commands

```ls
metric m:total_salary_wages p:decimal l:"Total Salary/Wages" t:dataTypeName=number

entity e:cffc-rjm2 l:"Salaries: ESD: Douglas: Fiscal Year 2013" t:url=https://data.oregon.gov/api/views/cffc-rjm2

property e:cffc-rjm2 t:meta.view v:id=cffc-rjm2 v:category="Revenue & Expense" v:averageRating=0 v:name="Salaries: ESD: Douglas: Fiscal Year 2013"

property e:cffc-rjm2 t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:cffc-rjm2 t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd_id | esdname                            | pstncd | position                                        | number_of_employees | total_fte | total_salary_wages | 
| ====== | ================================== | ====== | =============================================== | =================== | ========= | ================== | 
| 1980   | Douglas Education Service District |        | Assessment Support Specialist                   | * 1                 | * 1.0000  | 33046              | 
| 1980   | Douglas Education Service District |        | Assistant Director of Special Education/EI-ECSE | * 1                 | * 1.0000  | 87788.62           | 
| 1980   | Douglas Education Service District |        | Behavior Consultant                             | * 1                 | * 0.3000  | 20204.7            | 
| 1980   | Douglas Education Service District |        | Chief Financial Officer                         | * 1                 | * 1.0000  | 95442              | 
| 1980   | Douglas Education Service District |        | Computer Technician                             | * 3                 | * 1.9500  | 54986.770000000004 | 
| 1980   | Douglas Education Service District |        | Coordinator-Human Resources                     | * 1                 | * 1.0000  | 40000              | 
| 1980   | Douglas Education Service District |        | Coordinator-Program                             | * 2                 | * 2.0000  | 156090             | 
| 1980   | Douglas Education Service District |        | Courier                                         | * 1                 | * 0.1570  | 4593.53            | 
| 1980   | Douglas Education Service District |        | Custodian                                       | * 2                 | * 1.3750  | 39795.81           | 
| 1980   | Douglas Education Service District |        | Director of Business Services                   | * 3                 | * 1.5320  | 72500.009999999995 | 
```