# ESD Salaries 2016 - Composite Dataset - V1

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/esd-salaries-2016-composite-dataset-v1) |
| Metadata | [Link](https://data.oregon.gov/api/views/m7fw-7rb2) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/m7fw-7rb2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/m7fw-7rb2/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | m7fw-7rb2 |
| Name | ESD Salaries 2016 - Composite Dataset - V1 |
| Category | Revenue & Expense |
| Tags | 2016, salaries, esd, fiscal year 2016, esd salaries, education service districts |
| Created | 2017-01-02T05:02:11Z |
| Publication Date | 2017-01-02T06:48:57Z |

## Description

This is a composite listing of salary data from all ESD's per SB250 for Fiscal Year 2016. For more information go to: http://www.oregon.gov/transparency/Pages/ESDTransparency.aspx.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| Yes      | time           | fiscal_year         | Fiscal Year         | number    | number      |
| Yes      | series tag     | esd_id              | ESD ID              | text      | number      |
| Yes      | series tag     | esd_name            | ESD Name            | text      | text        |
| Yes      | series tag     | classification      | Classification      | text      | text        |
| Yes      | series tag     | service_type        | Service Type        | text      | text        |
| Yes      | series tag     | full_part_time      | Full /Part time     | text      | text        |
| Yes      | numeric metric | number_of_employees | Number of Employees | number    | number      |
| Yes      | numeric metric | total_fte           | Total FTE           | number    | number      |
| Yes      | numeric metric | annual_salary_wages | Annual Salary/Wages | money     | money       |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:m7fw-7rb2 d:2016-01-01T00:00:00.000Z t:esd_name="Clackamas ESD" t:esd_id=1902 t:service_type=1 t:classification=Superintendent t:full_part_time="Full Time" m:number_of_employees=1 m:annual_salary_wages=146704 m:total_fte=1

series e:m7fw-7rb2 d:2016-01-01T00:00:00.000Z t:esd_name="Clackamas ESD" t:esd_id=1902 t:service_type=2 t:classification="Assistant Superintendent" t:full_part_time="Full Time" m:number_of_employees=1 m:annual_salary_wages=124440 m:total_fte=1

series e:m7fw-7rb2 d:2016-01-01T00:00:00.000Z t:esd_name="Clackamas ESD" t:esd_id=1902 t:service_type=11 t:classification="Other Licensed Staff, Non-Special Ed" t:full_part_time="Part Time" m:number_of_employees=1 m:annual_salary_wages=25859.1 m:total_fte=0.6214
```

## Meta Commands

```ls
metric m:number_of_employees p:integer l:"Number of Employees" t:dataTypeName=number

metric m:total_fte p:float l:"Total FTE" t:dataTypeName=number

metric m:annual_salary_wages p:double l:"Annual Salary/Wages" t:dataTypeName=money

entity e:m7fw-7rb2 l:"ESD Salaries 2016 - Composite Dataset - V1" t:url=https://data.oregon.gov/api/views/m7fw-7rb2

property e:m7fw-7rb2 t:meta.view v:id=m7fw-7rb2 v:category="Revenue & Expense" v:averageRating=0 v:name="ESD Salaries 2016 - Composite Dataset - V1"

property e:m7fw-7rb2 t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:m7fw-7rb2 t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| fiscal_year | esd_id | esd_name      | classification                                    | service_type | full_part_time | number_of_employees | total_fte | annual_salary_wages | 
| =========== | ====== | ============= | ================================================= | ============ | ============== | =================== | ========= | =================== | 
| 2016        | 1902   | Clackamas ESD | Superintendent                                    | 1            | Full Time      | 1                   | 1         | 146704.00           | 
| 2016        | 1902   | Clackamas ESD | Assistant Superintendent                          | 2            | Full Time      | 1                   | 1         | 124440.00           | 
| 2016        | 1902   | Clackamas ESD | Other Licensed Staff, Non-Special Ed              | 11           | Part Time      | 1                   | 0.6214    | 25859.10            | 
| 2016        | 1902   | Clackamas ESD | Other Licensed Staff, Non-Special Ed              | 11           | Full Time      | 1                   | 1         | 60254.74            | 
| 2016        | 1902   | Clackamas ESD | Other Licensed Staff, Non-Special Ed              | 11           | Full Time      | 1                   | 1         | 118059.00           | 
| 2016        | 1902   | Clackamas ESD | Other Licensed Staff, Non-Special Ed              | 11           | Full Time      | 1                   | 1         | 76055.00            | 
| 2016        | 1902   | Clackamas ESD | Paraprofessional (Inst Assistant), Non-Special Ed | 16           | Full Time      | 1                   | 1         | 18438.45            | 
| 2016        | 1902   | Clackamas ESD | Paraprofessional (Inst Assistant), Non-Special Ed | 16           | Full Time      | 1                   | 1         | 27057.90            | 
| 2016        | 1902   | Clackamas ESD | Paraprofessional (Inst Assistant), Non-Special Ed | 16           | Full Time      | 1                   | 1         | 27057.90            | 
| 2016        | 1902   | Clackamas ESD | Paraprofessional (Inst Assistant), Non-Special Ed | 16           | Full Time      | 1                   | 1         | 27057.90            | 
```