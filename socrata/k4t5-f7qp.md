# Salaries: ESD: Harney; Fiscal Year 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salaries-esd-harney-fiscal-year-2014-70e25) |
| Metadata | [Link](https://data.oregon.gov/api/views/k4t5-f7qp) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/k4t5-f7qp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/k4t5-f7qp/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | k4t5-f7qp |
| Name | Salaries: ESD: Harney; Fiscal Year 2014 |
| Category | Revenue & Expense |
| Tags | salaries, esd, harney, fiscal year 2014 |
| Created | 2014-12-16T18:32:13Z |
| Publication Date | 2014-12-29T06:07:23Z |

## Description

Salries for Harney ESD for Fiscal Year 2014

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | series tag     | esd            | ESD #          | text      | text        |
| Yes      | series tag     | esd_name       | ESD NAME       | text      | text        |
| Yes      | series tag     | classification | CLASSIFICATION | text      | text        |
| Yes      | series tag     | service_type   | SERVICE TYPE   | text      | text        |
| Yes      | series tag     | full_part_time | FULL/PART TIME | text      | text        |
| Yes      | numeric metric | annual_salary  | ANNUAL SALARY  | money     | money       |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:k4t5-f7qp d:2014-01-01T00:00:00.000Z t:esd_name="Harney ESD" t:service_type=Unrepresented t:classification=Superintendent t:esd="ESD #17" t:full_part_time="Part time" m:annual_salary=50000

series e:k4t5-f7qp d:2014-01-01T00:00:00.000Z t:esd_name="Harney ESD" t:service_type=Unrepresented t:classification="Business Manager" t:esd="ESD #17" t:full_part_time="Full Time" m:annual_salary=61002

series e:k4t5-f7qp d:2014-01-01T00:00:00.000Z t:esd_name="Harney ESD" t:service_type=Unrepresented t:classification="Technology Director" t:esd="ESD #17" t:full_part_time="Full Time" m:annual_salary=84872
```

## Meta Commands

```ls
metric m:annual_salary p:double l:"ANNUAL SALARY" t:dataTypeName=money

entity e:k4t5-f7qp l:"Salaries: ESD: Harney; Fiscal Year 2014" t:url=https://data.oregon.gov/api/views/k4t5-f7qp

property e:k4t5-f7qp t:meta.view v:id=k4t5-f7qp v:category="Revenue & Expense" v:averageRating=0 v:name="Salaries: ESD: Harney; Fiscal Year 2014"

property e:k4t5-f7qp t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:k4t5-f7qp t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd     | esd_name   | classification      | service_type  | full_part_time | annual_salary | 
| ======= | ========== | =================== | ============= | ============== | ============= | 
| ESD #17 | Harney ESD | Superintendent      | Unrepresented | Part time      | 50000.00      | 
| ESD #17 | Harney ESD | Business Manager    | Unrepresented | Full Time      | 61002.00      | 
| ESD #17 | Harney ESD | Technology Director | Unrepresented | Full Time      | 84872.00      | 
| ESD #17 | Harney ESD | Curriculum          | Unrepresented | Full Time      | 65776.00      | 
| ESD #17 | Harney ESD | Speech Director     | Unrepresented | Part time      | 3313.88       | 
| ESD #17 | Harney ESD | Eary Childhood Dir  | Unrepresented | Full Time      | 68588.76      | 
| ESD #17 | Harney ESD | ECC Teacher         | Unrepresented | Full Time      | 32380.00      | 
| ESD #17 | Harney ESD | ECC Teacher         | Unrepresented | Full Time      | 26412.00      | 
| ESD #17 | Harney ESD | ECC Teacher         | Unrepresented | Full Time      | 21630.72      | 
| ESD #17 | Harney ESD | ECC Teacher         | Unrepresented | Full Time      | 29649.45      | 
```