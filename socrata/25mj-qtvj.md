# Salaries of State Agencies FY 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salaries-of-state-agencies-fy-2016) |
| Metadata | [Link](https://data.oregon.gov/api/views/25mj-qtvj) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/25mj-qtvj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/25mj-qtvj/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 25mj-qtvj |
| Name | Salaries of State Agencies FY 2016 |
| Category | Revenue & Expense |
| Tags | 2016, salaries, state employees, salaries of state employees, wages, salaries 2016 |
| Created | 2016-11-24T08:23:20Z |
| Publication Date | 2016-11-24T08:30:31Z |

## Description

Salaries of state work force sorted by agency - 2016. For more information go to http://www.oregon.gov/transparency/Pages/state_workforce.aspx

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | time           | fiscal_year    | FISCAL YEAR    | number    | number      |
| Yes      | series tag     | agency         | AGENCY #       | text      | text        |
| Yes      | series tag     | agency_title   | AGENCY TITLE   | text      | text        |
| Yes      | series tag     | classification | CLASSIFICATION | text      | text        |
| Yes      | series tag     | service_type   | SERVICE TYPE   | text      | text        |
| Yes      | series tag     | full_part_time | FULL/PART TIME | text      | text        |
| Yes      | numeric metric | annual_salary  | ANNUAL SALARY  | money     | money       |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:25mj-qtvj d:2016-01-01T00:00:00.000Z t:service_type="AGENCY HEAD" t:full_part_time=FULL-TIME t:agency=12000 t:agency_title="ACCOUNTANCY, OREGON BOARD OF" t:classification="PRINCIPAL EXECUTIVE/MANAGER D" m:annual_salary=96036

series e:25mj-qtvj d:2016-01-01T00:00:00.000Z t:service_type=UNREPRESENTED t:full_part_time=FULL-TIME t:agency=12000 t:agency_title="ACCOUNTANCY, OREGON BOARD OF" t:classification="OFFICE SPECIALIST 1" m:annual_salary=38712

series e:25mj-qtvj d:2016-01-01T00:00:00.000Z t:service_type=UNREPRESENTED t:full_part_time=FULL-TIME t:agency=12000 t:agency_title="ACCOUNTANCY, OREGON BOARD OF" t:classification="ADMINISTRATIVE SPECIALIST 1" m:annual_salary=35268
```

## Meta Commands

```ls
metric m:annual_salary p:double l:"ANNUAL SALARY" t:dataTypeName=money

entity e:25mj-qtvj l:"Salaries of State Agencies FY 2016" t:url=https://data.oregon.gov/api/views/25mj-qtvj

property e:25mj-qtvj t:meta.view d:2017-09-25T07:29:33.362Z v:averageRating=0 v:name="Salaries of State Agencies FY 2016" v:id=25mj-qtvj v:category="Revenue & Expense"

property e:25mj-qtvj t:meta.view.owner d:2017-09-25T07:29:33.362Z v:displayName="Paula N." v:lastNotificationSeenAt=1500509429 v:id=d6zz-js5q v:screenName="Paula N."

property e:25mj-qtvj t:meta.view.tableauthor d:2017-09-25T07:29:33.362Z v:displayName="Paula N." v:lastNotificationSeenAt=1500509429 v:roleName=administrator v:id=d6zz-js5q v:screenName="Paula N."
```

## Top Records

```ls
| fiscal_year | agency | agency_title                 | classification                | service_type  | full_part_time | annual_salary | 
| =========== | ====== | ============================ | ============================= | ============= | ============== | ============= | 
| 2016        | 12000  | ACCOUNTANCY, OREGON BOARD OF | PRINCIPAL EXECUTIVE/MANAGER D | AGENCY HEAD   | FULL-TIME      | 96036.00      | 
| 2016        | 12000  | ACCOUNTANCY, OREGON BOARD OF | OFFICE SPECIALIST 1           | UNREPRESENTED | FULL-TIME      | 38712.00      | 
| 2016        | 12000  | ACCOUNTANCY, OREGON BOARD OF | ADMINISTRATIVE SPECIALIST 1   | UNREPRESENTED | FULL-TIME      | 35268.00      | 
| 2016        | 12000  | ACCOUNTANCY, OREGON BOARD OF | ADMINISTRATIVE SPECIALIST 1   | UNREPRESENTED | FULL-TIME      | 35268.00      | 
| 2016        | 12000  | ACCOUNTANCY, OREGON BOARD OF | ADMINISTRATIVE SPECIALIST 1   | UNREPRESENTED | FULL-TIME      | 33816.00      | 
| 2016        | 12000  | ACCOUNTANCY, OREGON BOARD OF | ADMINISTRATIVE SPECIALIST 2   | UNREPRESENTED | FULL-TIME      | 51181.20      | 
| 2016        | 12000  | ACCOUNTANCY, OREGON BOARD OF | PROGRAM ANALYST 1             | UNREPRESENTED | FULL-TIME      | 61727.40      | 
| 2016        | 12000  | ACCOUNTANCY, OREGON BOARD OF | FINANCIAL INVESTIGATOR 1      | UNREPRESENTED | FULL-TIME      | 67848.00      | 
| 2016        | 12000  | ACCOUNTANCY, OREGON BOARD OF | FINANCIAL INVESTIGATOR 1      | UNREPRESENTED | PART-TIME      | 67848.00      | 
| 2016        | 12000  | ACCOUNTANCY, OREGON BOARD OF | FINANCIAL INVESTIGATOR 1      | UNREPRESENTED | FULL-TIME      | 67861.20      | 
```