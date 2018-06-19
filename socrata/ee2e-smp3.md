# 2015 Composite All - ESD Salaries SB250

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-composite-all-esd-salaries-sb250) |
| Metadata | [Link](https://data.oregon.gov/api/views/ee2e-smp3) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/ee2e-smp3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/ee2e-smp3/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | ee2e-smp3 |
| Name | 2015 Composite All - ESD Salaries SB250 |
| Category | Revenue & Expense |
| Tags | 2015; salaries; esd, fiscal year 2015: esd salaries |
| Created | 2015-12-27T02:03:24Z |
| Publication Date | 2016-01-04T07:30:40Z |

## Description

This is a composite listing of salary data from all ESD's per SB250 for Fiscal Year 2015. For more information go to: http://www.oregon.gov/transparency/Pages/ESDTransparency.aspx.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                   | Data Type | Render Type |
| ======== | ============== | ===================== | ====================== | ========= | =========== |
| Yes      | time           | fiscal_year           | Fiscal Year            | number    | number      |
| Yes      | series tag     | esd_id                | ESD ID                 | text      | number      |
| Yes      | series tag     | esdname               | ESDName                | text      | text        |
| Yes      | series tag     | classification        | Classification         | text      | text        |
| Yes      | series tag     | service_type_pstncode | Service Type /PstnCode | text      | text        |
| Yes      | series tag     | full_part_time        | Full /Part time        | text      | text        |
| Yes      | numeric metric | number_of_employees   | Number of Employees    | number    | number      |
| Yes      | numeric metric | total_fte             | Total FTE              | number    | number      |
| Yes      | numeric metric | annual_salary_wages   | Annual Salary/Wages    | money     | money       |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ee2e-smp3 d:2015-01-01T00:00:00.000Z t:esd_id=1902 t:classification=Superintendent t:esdname="Clackamas ESD" t:service_type_pstncode=1 m:number_of_employees=1 m:annual_salary_wages=143827 m:total_fte=1

series e:ee2e-smp3 d:2015-01-01T00:00:00.000Z t:esd_id=1902 t:classification="Assistant Superintendent" t:esdname="Clackamas ESD" t:service_type_pstncode=2 m:number_of_employees=1 m:annual_salary_wages=122000 m:total_fte=1

series e:ee2e-smp3 d:2015-01-01T00:00:00.000Z t:esd_id=1902 t:classification="Instructional Coordinator/Supervisor, Non-Spec Ed" t:esdname="Clackamas ESD" t:service_type_pstncode=6 m:number_of_employees=1 m:annual_salary_wages=93655 m:total_fte=1
```

## Meta Commands

```ls
metric m:number_of_employees p:integer l:"Number of Employees" t:dataTypeName=number

metric m:total_fte p:float l:"Total FTE" t:dataTypeName=number

metric m:annual_salary_wages p:double l:"Annual Salary/Wages" t:dataTypeName=money

entity e:ee2e-smp3 l:"2015 Composite All - ESD Salaries  SB250" t:url=https://data.oregon.gov/api/views/ee2e-smp3

property e:ee2e-smp3 t:meta.view v:id=ee2e-smp3 v:category="Revenue & Expense" v:averageRating=0 v:name="2015 Composite All - ESD Salaries  SB250"

property e:ee2e-smp3 t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:ee2e-smp3 t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| fiscal_year | esd_id | esdname       | classification                                    | service_type_pstncode | full_part_time | number_of_employees | total_fte | annual_salary_wages | 
| =========== | ====== | ============= | ================================================= | ===================== | ============== | =================== | ========= | =================== | 
| 2015        | 1902   | Clackamas ESD | Superintendent                                    | 1                     |                | 1                   | 1         | 143827.00           | 
| 2015        | 1902   | Clackamas ESD | Assistant Superintendent                          | 2                     |                | 1                   | 1         | 122000.00           | 
| 2015        | 1902   | Clackamas ESD | Instructional Coordinator/Supervisor, Non-Spec Ed | 6                     |                | 1                   | 1         | 93655.00            | 
| 2015        | 1902   | Clackamas ESD | Teacher, Non-Special Ed                           | 8                     |                | 1                   | 1         | 52504.00            | 
| 2015        | 1902   | Clackamas ESD | Other Licensed Staff, Non-Special Ed              | 11                    |                | 1                   | 1         | 78488.42            | 
| 2015        | 1902   | Clackamas ESD | Other Licensed Staff, Non-Special Ed              | 11                    |                | 1                   | 1         | 115744.00           | 
| 2015        | 1902   | Clackamas ESD | Other Licensed Staff, Non-Special Ed              | 11                    |                | 1                   | 0.5978    | 41167.50            | 
| 2015        | 1902   | Clackamas ESD | Other Licensed Staff, Non-Special Ed              | 11                    |                | 1                   | 1         | 74564.00            | 
| 2015        | 1902   | Clackamas ESD | Paraprofessional (Inst Assistant), Non-Special Ed | 16                    |                | 1                   | 0.45      | 8617.21             | 
| 2015        | 1902   | Clackamas ESD | Paraprofessional (Inst Assistant), Non-Special Ed | 16                    |                | 1                   | 1         | 26379.45            | 
```