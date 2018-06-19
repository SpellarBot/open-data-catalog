# Salaries: ESD: Southern Oregon: FY 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salaries-esd-southern-oregon-fy-2014-e394e) |
| Metadata | [Link](https://data.oregon.gov/api/views/6s8d-tm4m) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/6s8d-tm4m/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/6s8d-tm4m/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 6s8d-tm4m |
| Name | Salaries: ESD: Southern Oregon: FY 2014 |
| Category | Revenue & Expense |
| Tags | soesd salaries, southern oregon esd salaries, southern oregon salaries |
| Created | 2014-12-15T03:05:39Z |
| Publication Date | 2014-12-29T05:56:07Z |

## Description

Summary of salaries for Southern Oregon ESD for Fiscal Year 2014.

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
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:6s8d-tm4m d:2014-01-01T00:00:00.000Z t:position="ADVANCED SIGN LANG INTERPRETER" t:esd_name="Southern Oregon ESD" t:esd_id=2025 t:service_type=Classified m:number_of_employees=1 m:fte=0.19 m:total_salary=6441

series e:6s8d-tm4m d:2014-01-01T00:00:00.000Z t:position="SIGN LANG FACILITATOR" t:esd_name="Southern Oregon ESD" t:esd_id=2025 t:service_type=Classified m:number_of_employees=1 m:fte=0.325 m:total_salary=7567.7

series e:6s8d-tm4m d:2014-01-01T00:00:00.000Z t:position="EI TEACHING ASSISTANT III" t:esd_name="Southern Oregon ESD" t:esd_id=2025 t:service_type=Classified m:number_of_employees=1 m:fte=0.45 m:total_salary=11667.95
```

## Meta Commands

```ls
metric m:number_of_employees p:integer l:"Number of Employees" t:dataTypeName=number

metric m:fte p:float l:FTE t:dataTypeName=number

metric m:total_salary p:double l:"Total Salary" t:dataTypeName=money

entity e:6s8d-tm4m l:"Salaries: ESD: Southern Oregon: FY 2014" t:url=https://data.oregon.gov/api/views/6s8d-tm4m

property e:6s8d-tm4m t:meta.view v:id=6s8d-tm4m v:category="Revenue & Expense" v:averageRating=0 v:name="Salaries: ESD: Southern Oregon: FY 2014"

property e:6s8d-tm4m t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:6s8d-tm4m t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd_id | esd_name            | service_type | position                       | number_of_employees | fte    | total_salary | 
| ====== | =================== | ============ | ============================== | =================== | ====== | ============ | 
| 2025   | Southern Oregon ESD | Classified   | ADVANCED SIGN LANG INTERPRETER | 1                   | 0.1900 | 6441.00      | 
| 2025   | Southern Oregon ESD | Classified   | SIGN LANG FACILITATOR          | 1                   | 0.3250 | 7567.70      | 
| 2025   | Southern Oregon ESD | Classified   | EI TEACHING ASSISTANT III      | 1                   | 0.4500 | 11667.95     | 
| 2025   | Southern Oregon ESD | Classified   | EI TEACHING ASSISTANT III      | 1                   | 0.4550 | 11797.45     | 
| 2025   | Southern Oregon ESD | Classified   | TEACHING ASSOCIATE             | 1                   | 0.4588 | 13015.47     | 
| 2025   | Southern Oregon ESD | Classified   | EI TEACHING ASSISTANT I        | 1                   | 0.4800 | 9945.60      | 
| 2025   | Southern Oregon ESD | Classified   | STEPS PLUS ED ASSISTANT        | 1                   | 0.5000 | 13946.79     | 
| 2025   | Southern Oregon ESD | Classified   | BRAILLIST IV                   | 1                   | 0.5000 | 17852.40     | 
| 2025   | Southern Oregon ESD | Classified   | BRAILLIST IV                   | 1                   | 0.5000 | 17852.40     | 
| 2025   | Southern Oregon ESD | Classified   | INDIAN ED FACILITATOR          | 1                   | 0.5000 | 14576.80     | 
```