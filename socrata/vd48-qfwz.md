# Salaries: ESD: High Desert: Fiscal Year 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salaries-esd-high-desert-fiscal-year-2014-7ee77) |
| Metadata | [Link](https://data.oregon.gov/api/views/vd48-qfwz) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/vd48-qfwz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/vd48-qfwz/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | vd48-qfwz |
| Name | Salaries: ESD: High Desert: Fiscal Year 2014 |
| Category | Revenue & Expense |
| Tags | salaries, esd, high desert, fiscal year 2014 |
| Created | 2014-12-16T22:19:45Z |
| Publication Date | 2014-12-29T06:17:11Z |

## Description

Salaries for High Desert ESD for Fiscal Year 2014

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| Yes      | series tag     | esd_id      | ESD ID      | text      | number      |
| Yes      | series tag     | esdname     | ESDName     | text      | text        |
| Yes      | series tag     | state_code  | State Code  | text      | number      |
| Yes      | series tag     | description | Description | text      | text        |
| Yes      | numeric metric | fte         | FTE         | number    | number      |
| Yes      | numeric metric | employees   | # Employees | number    | number      |
| Yes      | numeric metric | salary      | Salary      | money     | money       |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:vd48-qfwz d:2014-01-01T00:00:00.000Z t:state_code=1 t:esd_id=1975 t:description=Superintendent t:esdname="High Desert ESD" m:fte=1 m:salary=133840 m:employees=1

series e:vd48-qfwz d:2014-01-01T00:00:00.000Z t:state_code=2 t:esd_id=1975 t:description="Assistant Superintendent" t:esdname="High Desert ESD" m:fte=1 m:salary=120460 m:employees=1

series e:vd48-qfwz d:2014-01-01T00:00:00.000Z t:state_code=6 t:esd_id=1975 t:description="Instructional Coordinator/Supervisor, Non-Special" t:esdname="High Desert ESD" m:fte=2 m:salary=139078.4 m:employees=3
```

## Meta Commands

```ls
metric m:fte p:float l:FTE t:dataTypeName=number

metric m:employees p:integer l:"# Employees" t:dataTypeName=number

metric m:salary p:double l:Salary t:dataTypeName=money

entity e:vd48-qfwz l:"Salaries: ESD: High Desert: Fiscal Year 2014" t:url=https://data.oregon.gov/api/views/vd48-qfwz

property e:vd48-qfwz t:meta.view v:id=vd48-qfwz v:category="Revenue & Expense" v:averageRating=0 v:name="Salaries: ESD: High Desert: Fiscal Year 2014"

property e:vd48-qfwz t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:vd48-qfwz t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd_id | esdname         | state_code | description                                       | fte    | employees | salary     | 
| ====== | =============== | ========== | ================================================= | ====== | ========= | ========== | 
| 1975   | High Desert ESD | 1          | Superintendent                                    | 1      | 1         | 133840.00  | 
| 1975   | High Desert ESD | 2          | Assistant Superintendent                          | 1      | 1         | 120460.00  | 
| 1975   | High Desert ESD | 6          | Instructional Coordinator/Supervisor, Non-Special | 2      | 3         | 139078.40  | 
| 1975   | High Desert ESD | 11         | Other Licensed Staff, Non-Special Ed              | 7.29   | 10        | 479685.29  | 
| 1975   | High Desert ESD | 17         | District Support (Non-Licensed, Non-Special Ed)   | 37.239 | 48        | 1821881.38 | 
| 1975   | High Desert ESD | 18         | School Support (Non-Licensed, Non-Special Ed)     | 1      | 1         | 29242.08   | 
| 1975   | High Desert ESD | 21         | Other Non-Licensed Staff, Non-Special Ed          | 19.7   | 25        | 600003.45  | 
| 1975   | High Desert ESD | 22         | Special Education Teacher (Non-PE)                | 28.225 | 35        | 1506222.42 | 
| 1975   | High Desert ESD | 25         | Special Education Speech Pathologist              | 9.8    | 15        | 429896.26  | 
| 1975   | High Desert ESD | 26         | Special Education Interpreter                     | 4.375  | 5         | 152103.63  | 
```