# Salaries: ESD: North Central: Fiscal Year 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salaries-esd-north-central-fiscal-year-2014-5a5b8) |
| Metadata | [Link](https://data.oregon.gov/api/views/ts3e-9b3t) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/ts3e-9b3t/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/ts3e-9b3t/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | ts3e-9b3t |
| Name | Salaries: ESD: North Central: Fiscal Year 2014 |
| Category | Revenue & Expense |
| Tags | salaries, esd, north central, fiscal year 2014 |
| Created | 2014-12-11T23:30:10Z |
| Publication Date | 2014-12-29T05:52:28Z |

## Description

Salaries for North Central ESD for Fiscal Year 2014

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| Yes      | numeric metric | esd                | ESD #              | number    | number      |
| Yes      | series tag     | name_of_esd        | NAME OF ESD        | text      | text        |
| Yes      | series tag     | state_code         | State Code         | text      | number      |
| Yes      | series tag     | position           | POSITION           | text      | text        |
| Yes      | numeric metric | employees          | # Employees        | number    | number      |
| Yes      | numeric metric | total_fte          | Total FTE          | number    | number      |
| Yes      | numeric metric | total_salary_wages | Total Salary/Wages | money     | money       |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ts3e-9b3t d:2014-01-01T00:00:00.000Z t:position=Superintendent t:state_code=1 t:name_of_esd="North Central ESD" m:total_salary_wages=23975 m:esd=2004 m:employees=1 m:total_fte=0.2

series e:ts3e-9b3t d:2014-01-01T00:00:00.000Z t:position="Instructional Coordinator/Supervisor, Non-Special Ed" t:state_code=6 t:name_of_esd="North Central ESD" m:total_salary_wages=104865 m:esd=2004 m:employees=3 m:total_fte=1.68

series e:ts3e-9b3t d:2014-01-01T00:00:00.000Z t:position="Teacher, Non-Special Ed" t:state_code=8 t:name_of_esd="North Central ESD" m:total_salary_wages=57055 m:esd=2004 m:employees=2 m:total_fte=1.39
```

## Meta Commands

```ls
metric m:esd p:integer l:"ESD #" t:dataTypeName=number

metric m:employees p:integer l:"# Employees" t:dataTypeName=number

metric m:total_fte p:float l:"Total FTE" t:dataTypeName=number

metric m:total_salary_wages p:integer l:"Total Salary/Wages" t:dataTypeName=money

entity e:ts3e-9b3t l:"Salaries: ESD: North Central: Fiscal Year 2014" t:url=https://data.oregon.gov/api/views/ts3e-9b3t

property e:ts3e-9b3t t:meta.view v:id=ts3e-9b3t v:category="Revenue & Expense" v:averageRating=0 v:name="Salaries: ESD: North Central: Fiscal Year 2014"

property e:ts3e-9b3t t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:ts3e-9b3t t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | name_of_esd       | state_code | position                                             | employees | total_fte | total_salary_wages | 
| ==== | ================= | ========== | ==================================================== | ========= | ========= | ================== | 
| 2004 | North Central ESD | 1          | Superintendent                                       | 1         | 0.20      | 23975              | 
| 2004 | North Central ESD | 6          | Instructional Coordinator/Supervisor, Non-Special Ed | 3         | 1.68      | 104865             | 
| 2004 | North Central ESD | 8          | Teacher, Non-Special Ed                              | 2         | 1.39      | 57055              | 
| 2004 | North Central ESD | 17         | District Support (Non-Licensed, Non-Special Ed)      | 7         | 4.65      | 220967             | 
| 2004 | North Central ESD | 21         | Other Non-Licensed staff, Non-Special Ed             | 2         | 0.97      | 35954              | 
| 2004 | North Central ESD | 22         | Special Education Teacher                            | 2         | 2.00      | 103258             | 
| 2004 | North Central ESD | 25         | Special Education Speech Pathologist                 | 2         | 1.00      | 60840              | 
| 2004 | North Central ESD | 35         | Special Education Paraprofessional                   | 4         | 3.39      | 92327              | 
| 2004 | North Central ESD | 37         | Special Education Administrator, Director            | 2         | 1.06      | 75119              | 
```