# Salaries: ESD: Lake County: Fiscal Year 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salaries-esd-lake-county-fiscal-year-2013-79ffc) |
| Metadata | [Link](https://data.oregon.gov/api/views/e5ku-bt49) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/e5ku-bt49/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/e5ku-bt49/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | e5ku-bt49 |
| Name | Salaries: ESD: Lake County: Fiscal Year 2013 |
| Category | Revenue & Expense |
| Tags | salaries, esd, lake county, fiscal year 2013 |
| Created | 2013-10-23T23:04:30Z |
| Publication Date | 2013-10-23T23:15:29Z |

## Description

Salaries of Lake County ESD employees for Fiscal Year 2013

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
| Yes      | series tag     | total_salary_wages  | Total Salary/Wages  | text      | text        |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:e5ku-bt49 d:2013-01-01T00:00:00.000Z t:position=Superintendent t:esd_id=2058 t:esdname="Lake ESD" t:total_salary_wages="* 50,000" m:number_of_employees=1 m:pstncd=1 m:total_fte=0.5

series e:e5ku-bt49 d:2013-01-01T00:00:00.000Z t:position=Principal t:esd_id=2058 t:esdname="Lake ESD" t:total_salary_wages="* 5,000" m:number_of_employees=1 m:pstncd=3 m:total_fte=0.1

series e:e5ku-bt49 d:2013-01-01T00:00:00.000Z t:position="Instructional Coordinator/Supervisor, Non-Special Ed" t:esd_id=2058 t:esdname="Lake ESD" t:total_salary_wages="* 20,000" m:number_of_employees=1 m:pstncd=6 m:total_fte=0.2
```

## Meta Commands

```ls
metric m:pstncd p:integer l:PstnCd t:dataTypeName=number

metric m:number_of_employees p:integer l:"Number of Employees" t:dataTypeName=number

metric m:total_fte p:double l:"Total FTE" t:dataTypeName=number

entity e:e5ku-bt49 l:"Salaries: ESD: Lake County: Fiscal Year 2013" t:url=https://data.oregon.gov/api/views/e5ku-bt49

property e:e5ku-bt49 t:meta.view v:id=e5ku-bt49 v:category="Revenue & Expense" v:averageRating=0 v:name="Salaries: ESD: Lake County: Fiscal Year 2013"

property e:e5ku-bt49 t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:e5ku-bt49 t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd_id | esdname  | pstncd | position                                             | number_of_employees | total_fte | total_salary_wages | 
| ====== | ======== | ====== | ==================================================== | =================== | ========= | ================== | 
| 2058   | Lake ESD | 1      | Superintendent                                       | 1                   | 0.5       | * 50,000           | 
| 2058   | Lake ESD | 3      | Principal                                            | 1                   | 0.1       | * 5,000            | 
| 2058   | Lake ESD | 6      | Instructional Coordinator/Supervisor, Non-Special Ed | 1                   | 0.2       | * 20,000           | 
| 2058   | Lake ESD | 6      | Instructional Coordinator/Supervisor, Non-Special Ed | 1                   | 0.5       | * 25,157           | 
| 2058   | Lake ESD | 10     | Guidance Counselor, Non-Special Ed                   | 1                   | 1         | * 48,894           | 
| 2058   | Lake ESD | 17     | District Support (Non-Licensed, Non-Special Ed)      | 1                   | 0.8       | * 16,070           | 
| 2058   | Lake ESD | 17     | District Support (Non-Licensed, Non-Special Ed)      | 1                   | 0.7       | * 7,202            | 
| 2058   | Lake ESD | 17     | District Support (Non-Licensed, Non-Special Ed)      | 1                   | 0.5       | * 14,585           | 
| 2058   | Lake ESD | 17     | District Support (Non-Licensed, Non-Special Ed)      | 1                   | 0.5       | * 11,000           | 
| 2058   | Lake ESD | 17     | District Support (Non-Licensed, Non-Special Ed)      | 1                   | 1         | * 39,040           | 
```