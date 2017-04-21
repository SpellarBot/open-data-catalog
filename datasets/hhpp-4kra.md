# Salaries: State Agencies: As of June 30, 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-salaries-das-063015) |
| Metadata | [Link](https://data.oregon.gov/api/views/hhpp-4kra) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/hhpp-4kra/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/hhpp-4kra/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | hhpp-4kra |
| Name | Salaries: State Agencies: As of June 30, 2015 |
| Category | Revenue & Expense |
| Tags | 2015, salaries, state employees, salaries of state employees, wages, salaries 2015, 2015-salaries-das-063015 |
| Created | 2015-12-14T01:47:03Z |
| Publication Date | 2015-12-24T06:09:08Z |

## Description

Salaries of state work force sorted by agency - 2015. For more information go to http://www.oregon.gov/transparency/Pages/state_workforce.aspx

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | time           | fiscal_year    | FISCAL YEAR    | number    | number      |
| Yes      | series tag     | agency         | AGENCY #       | text      | number      |
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
series e:hhpp-4kra d:2015-01-01T00:00:00.000Z t:service_type="AGENCY HEAD" t:classification="PRINCIPAL EXECUTIVE/MANAGER D" t:agency_title="ACCOUNTANCY, OREGON BOARD OF" t:agency=12000 t:full_part_time=FULL-TIME m:annual_salary=93924

series e:hhpp-4kra d:2015-01-01T00:00:00.000Z t:service_type=UNREPRESENTED t:classification="OFFICE SPECIALIST 1" t:agency_title="ACCOUNTANCY, OREGON BOARD OF" t:agency=12000 t:full_part_time=FULL-TIME m:annual_salary=38712

series e:hhpp-4kra d:2015-01-01T00:00:00.000Z t:service_type=UNREPRESENTED t:classification="ADMINISTRATIVE SPECIALIST 1" t:agency_title="ACCOUNTANCY, OREGON BOARD OF" t:agency=12000 t:full_part_time=FULL-TIME m:annual_salary=33072
```

## Meta Commands

```ls
metric m:annual_salary p:double l:"ANNUAL SALARY" t:dataTypeName=money

entity e:hhpp-4kra l:"Salaries: State Agencies: As of June 30, 2015" t:url=https://data.oregon.gov/api/views/hhpp-4kra

property e:hhpp-4kra t:meta.view v:id=hhpp-4kra v:category="Revenue & Expense" v:averageRating=80 v:name="Salaries: State Agencies: As of June 30, 2015"

property e:hhpp-4kra t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:hhpp-4kra t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| fiscal_year | agency | agency_title                  | classification                | service_type      | full_part_time | annual_salary | 
| =========== | ====== | ============================= | ============================= | ================= | ============== | ============= | 
| 2015        | 12000  | ACCOUNTANCY, OREGON BOARD OF  | PRINCIPAL EXECUTIVE/MANAGER D | AGENCY HEAD       | FULL-TIME      | 93924.00      | 
| 2015        | 12000  | ACCOUNTANCY, OREGON BOARD OF  | OFFICE SPECIALIST 1           | UNREPRESENTED     | FULL-TIME      | 38712.00      | 
| 2015        | 12000  | ACCOUNTANCY, OREGON BOARD OF  | ADMINISTRATIVE SPECIALIST 1   | UNREPRESENTED     | FULL-TIME      | 33072.00      | 
| 2015        | 12000  | ACCOUNTANCY, OREGON BOARD OF  | ADMINISTRATIVE SPECIALIST 1   | UNREPRESENTED     | FULL-TIME      | 30468.00      | 
| 2015        | 12000  | ACCOUNTANCY, OREGON BOARD OF  | ADMINISTRATIVE SPECIALIST 2   | UNREPRESENTED     | FULL-TIME      | 47676.00      | 
| 2015        | 12000  | ACCOUNTANCY, OREGON BOARD OF  | PROGRAM ANALYST 1             | UNREPRESENTED     | FULL-TIME      | 57594.60      | 
| 2015        | 12000  | ACCOUNTANCY, OREGON BOARD OF  | FINANCIAL INVESTIGATOR 1      | UNREPRESENTED     | FULL-TIME      | 66360.00      | 
| 2015        | 12000  | ACCOUNTANCY, OREGON BOARD OF  | FINANCIAL INVESTIGATOR 1      | UNREPRESENTED     | FULL-TIME      | 63324.00      | 
| 2015        | 10700  | ADMINISTRATIVE SRVCS, DEPT OF | EXECUTIVE ASSISTANT           | EXECUTIVE SERVICE | FULL-TIME      | 65904.00      | 
| 2015        | 10700  | ADMINISTRATIVE SRVCS, DEPT OF | PRINCIPAL EXECUTIVE/MANAGER F | EXECUTIVE SERVICE | FULL-TIME      | 107004.00     | 
```