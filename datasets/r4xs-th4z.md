# Salaries: ESD: Southern Oregon: FY 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salaries-esd-southern-oregon-fy-2013-15242) |
| Metadata | [Link](https://data.oregon.gov/api/views/r4xs-th4z) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/r4xs-th4z/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/r4xs-th4z/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | r4xs-th4z |
| Name | Salaries: ESD: Southern Oregon: FY 2013 |
| Category | Revenue & Expense |
| Tags | soesd salaries, souther oregon esd salaries, southern oregon salaries |
| Created | 2013-11-12T19:18:50Z |
| Publication Date | 2013-11-12T19:22:05Z |

## Description

Summary of salaries for Southern Oregon ESD for Fiscal Year 2013.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| Yes      | series tag     | esd_id              | ESD ID              | text      | number      |
| Yes      | series tag     | esd_name            | ESD Name            | text      | text        |
| Yes      | series tag     | service_type        | Service Type        | text      | text        |
| Yes      | series tag     | position            | Position            | text      | text        |
| Yes      | numeric metric | number_of_employees | Number of Employees | number    | number      |
| Yes      | numeric metric | fte                 | FTE                 | number    | number      |
| Yes      | numeric metric | total_salary        | Total Salary        | money     | money       |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:r4xs-th4z d:2013-01-01T00:00:00.000Z t:position=ACCOUNTANT t:esd_name="Southern Oregon ESD" t:esd_id=2025 t:service_type=Classified m:number_of_employees=1 m:fte=1 m:total_salary=35051.2

series e:r4xs-th4z d:2013-01-01T00:00:00.000Z t:position=ACCOUNTANT t:esd_name="Southern Oregon ESD" t:esd_id=2025 t:service_type=Classified m:number_of_employees=1 m:fte=1 m:total_salary=25000.16

series e:r4xs-th4z d:2013-01-01T00:00:00.000Z t:position=ACCOUNTANT t:esd_name="Southern Oregon ESD" t:esd_id=2025 t:service_type=Classified m:number_of_employees=1 m:fte=1 m:total_salary=25728.32
```

## Meta Commands

```ls
metric m:number_of_employees p:integer l:"Number of Employees" t:dataTypeName=number

metric m:fte p:float l:FTE t:dataTypeName=number

metric m:total_salary p:double l:"Total Salary" t:dataTypeName=money

entity e:r4xs-th4z l:"Salaries: ESD: Southern Oregon: FY 2013" t:url=https://data.oregon.gov/api/views/r4xs-th4z

property e:r4xs-th4z t:meta.view v:id=r4xs-th4z v:category="Revenue & Expense" v:averageRating=0 v:name="Salaries: ESD: Southern Oregon: FY 2013"

property e:r4xs-th4z t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:r4xs-th4z t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd_id | esd_name            | service_type | position                     | number_of_employees | fte    | total_salary | 
| ====== | =================== | ============ | ============================ | =================== | ====== | ============ | 
| 2025   | Southern Oregon ESD | Classified   | ACCOUNTANT                   | 1                   | 1.0000 | 35051.20     | 
| 2025   | Southern Oregon ESD | Classified   | ACCOUNTANT                   | 1                   | 1.0000 | 25000.16     | 
| 2025   | Southern Oregon ESD | Classified   | ACCOUNTANT                   | 1                   | 1.0000 | 25728.32     | 
| 2025   | Southern Oregon ESD | Classified   | ADMIN ASSIST TO DIRECTOR     | 1                   | 1.0000 | 32735.04     | 
| 2025   | Southern Oregon ESD | Classified   | ADMIN ASSIST TO THE DIRECTOR | 1                   | 1.0000 | 39346.56     | 
| 2025   | Southern Oregon ESD | Classified   | ADMINISTRATIVE ASSIST III    | 1                   | 1.0000 | 33725.76     | 
| 2025   | Southern Oregon ESD | Classified   | ADMINISTRATIVE ASSISTANT     | 1                   | 0.5000 | 16357.20     | 
| 2025   | Southern Oregon ESD | Classified   | ADMINISTRATIVE ASSISTANT II  | 1                   | 0.8000 | 20416.00     | 
| 2025   | Southern Oregon ESD | Classified   | ADMINISTRATIVE ASSISTANT II  | 1                   | 1.0000 | 29384.40     | 
| 2025   | Southern Oregon ESD | Classified   | ADMINISTRATIVE ASSISTANT III | 1                   | 1.0000 | 33351.04     | 
```