# Salaries: ESD: Lake County: Fiscal Year 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salaries-esd-lake-county-fiscal-year-2014-a2b04) |
| Metadata | [Link](https://data.oregon.gov/api/views/isbn-7w3f) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/isbn-7w3f/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/isbn-7w3f/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | isbn-7w3f |
| Name | Salaries: ESD: Lake County: Fiscal Year 2014 |
| Category | Revenue & Expense |
| Tags | salaries, esd, lake county, fiscal year 2014 |
| Created | 2014-12-05T00:21:28Z |
| Publication Date | 2014-12-29T05:44:22Z |

## Description

Salaries of Lake County ESD employees for Fiscal Year 2014

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| Yes      | series tag     | esd_id              | ESD ID              | text      | number      |
| Yes      | series tag     | esdname             | ESDName             | text      | text        |
| Yes      | numeric metric | pstncd              | PstnCd              | number    | number      |
| Yes      | series tag     | position            | Position            | text      | text        |
| Yes      | numeric metric | number_of_employees | Number of Employees | number    | number      |
| Yes      | numeric metric | total_fte           | Total FTE           | number    | number      |
| Yes      | numeric metric | total_salary_wages  | Total Salary/Wages  | money     | money       |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:isbn-7w3f d:2014-01-01T00:00:00.000Z t:position=Superintendent t:esd_id=2058 t:esdname="Lake ESD" m:number_of_employees=1 m:pstncd=1 m:total_salary_wages=40000 m:total_fte=0.4

series e:isbn-7w3f d:2014-01-01T00:00:00.000Z t:position=Principal t:esd_id=2058 t:esdname="Lake ESD" m:number_of_employees=1 m:pstncd=3 m:total_salary_wages=5000 m:total_fte=0.1

series e:isbn-7w3f d:2014-01-01T00:00:00.000Z t:position="Instructional Coordinator/Supervisor, Non-Special Ed" t:esd_id=2058 t:esdname="Lake ESD" m:number_of_employees=1 m:pstncd=6 m:total_salary_wages=20000 m:total_fte=0.2
```

## Meta Commands

```ls
metric m:pstncd p:integer l:PstnCd t:dataTypeName=number

metric m:number_of_employees p:integer l:"Number of Employees" t:dataTypeName=number

metric m:total_fte p:double l:"Total FTE" t:dataTypeName=number

metric m:total_salary_wages p:integer l:"Total Salary/Wages" t:dataTypeName=money

entity e:isbn-7w3f l:"Salaries: ESD: Lake County: Fiscal Year 2014" t:url=https://data.oregon.gov/api/views/isbn-7w3f

property e:isbn-7w3f t:meta.view v:id=isbn-7w3f v:category="Revenue & Expense" v:averageRating=0 v:name="Salaries: ESD: Lake County: Fiscal Year 2014"

property e:isbn-7w3f t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:isbn-7w3f t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd_id | esdname  | pstncd | position                                             | number_of_employees | total_fte | total_salary_wages | 
| ====== | ======== | ====== | ==================================================== | =================== | ========= | ================== | 
| 2058   | Lake ESD | 1      | Superintendent                                       | 1                   | 0.4       | 40000              | 
| 2058   | Lake ESD | 3      | Principal                                            | 1                   | 0.1       | 5000               | 
| 2058   | Lake ESD | 6      | Instructional Coordinator/Supervisor, Non-Special Ed | 1                   | 0.2       | 20000              | 
| 2058   | Lake ESD | 6      | Instructional Coordinator/Supervisor, Non-Special Ed | 1                   | 0.5       | 25660              | 
| 2058   | Lake ESD | 10     | Guidance Counselor, Non-Special Ed                   | 1                   | 1         | 51285              | 
| 2058   | Lake ESD | 17     | District Support (Non-Licensed, Non-Special Ed)      | 1                   | 0.5       | 11272              | 
| 2058   | Lake ESD | 17     | District Support (Non-Licensed, Non-Special Ed)      | 1                   | 0.5       | 20124              | 
| 2058   | Lake ESD | 17     | District Support (Non-Licensed, Non-Special Ed)      | 1                   | 0.5       | 13990              | 
| 2058   | Lake ESD | 17     | District Support (Non-Licensed, Non-Special Ed)      | 1                   | 0.5       | 16304              | 
| 2058   | Lake ESD | 17     | District Support (Non-Licensed, Non-Special Ed)      | 1                   | 0.5       | 15704              | 
```