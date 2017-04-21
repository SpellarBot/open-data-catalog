# Salaries: ESD: North Central: Fiscal Year 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salaries-esd-north-central-fiscal-year-2013-595a9) |
| Metadata | [Link](https://data.oregon.gov/api/views/czci-kz7t) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/czci-kz7t/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/czci-kz7t/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | czci-kz7t |
| Name | Salaries: ESD: North Central: Fiscal Year 2013 |
| Category | Revenue & Expense |
| Tags | salaries, esd, north central, fiscal year 2013 |
| Created | 2013-10-31T20:13:31Z |
| Publication Date | 2013-10-31T20:15:53Z |

## Description

Salaries for North Central ESD for Fiscal Year 2013

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
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:czci-kz7t d:2013-01-01T00:00:00.000Z t:position=Superintendent t:state_code=1 t:name_of_esd="North Central ESD" m:total_salary_wages=25173 m:esd=2004 m:employees=1 m:total_fte=0.21

series e:czci-kz7t d:2013-01-01T00:00:00.000Z t:position="Instructional Coordinator/Supervisor, Non-Special Ed" t:state_code=6 t:name_of_esd="North Central ESD" m:total_salary_wages=111520 m:esd=2004 m:employees=3 m:total_fte=1.59

series e:czci-kz7t d:2013-01-01T00:00:00.000Z t:position="Teacher, Non-Special Ed" t:state_code=8 t:name_of_esd="North Central ESD" m:total_salary_wages=18633 m:esd=2004 m:employees=1 m:total_fte=0.4
```

## Meta Commands

```ls
metric m:esd p:integer l:"ESD #" t:dataTypeName=number

metric m:employees p:integer l:"# Employees" t:dataTypeName=number

metric m:total_fte p:float l:"Total FTE" t:dataTypeName=number

metric m:total_salary_wages p:integer l:"Total Salary/Wages" t:dataTypeName=money

entity e:czci-kz7t l:"Salaries: ESD: North Central: Fiscal Year 2013" t:url=https://data.oregon.gov/api/views/czci-kz7t

property e:czci-kz7t t:meta.view v:id=czci-kz7t v:category="Revenue & Expense" v:averageRating=0 v:name="Salaries: ESD: North Central: Fiscal Year 2013"

property e:czci-kz7t t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:czci-kz7t t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | name_of_esd       | state_code | position                                             | employees | total_fte | total_salary_wages | 
| ==== | ================= | ========== | ==================================================== | ========= | ========= | ================== | 
| 2004 | North Central ESD | 1          | Superintendent                                       | 1         | 0.21      | 25173              | 
| 2004 | North Central ESD | 6          | Instructional Coordinator/Supervisor, Non-Special Ed | 3         | 1.59      | 111520             | 
| 2004 | North Central ESD | 8          | Teacher, Non-Special Ed                              | 1         | 0.40      | 18633              | 
| 2004 | North Central ESD | 17         | District Support (Non-Licensed, Non-Special Ed)      | 8         | 6.29      | 289927             | 
| 2004 | North Central ESD | 21         | Other Non-Licensed staff, Non-Special Ed             | 2         | 0.90      | 36636              | 
| 2004 | North Central ESD | 25         | Special Education Speech Pathologist                 | 3         | 2.20      | 86988              | 
| 2004 | North Central ESD | 35         | Special Education Paraprofessional                   | 3         | 3.00      | 76753              | 
| 2004 | North Central ESD | 37         | Special Education Administrator, Director            | 3         | 1.04      | 75452              | 
| 2004 | North Central ESD | 36         | Special Education, Other Services, Licensed          | 3         | 2.40      | 111995             | 
```