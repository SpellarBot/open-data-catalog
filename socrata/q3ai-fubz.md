# Salaries: State Agencies: As of June 30, 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salaries-state-agencies-as-of-june-30-2014-b848d) |
| Metadata | [Link](https://data.oregon.gov/api/views/q3ai-fubz) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/q3ai-fubz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/q3ai-fubz/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | q3ai-fubz |
| Name | Salaries: State Agencies: As of June 30, 2014 |
| Category | Revenue & Expense |
| Tags | salaries, state employees, salaries of state employees, wages of state employees, salaries 2014, 2014 |
| Created | 2014-12-29T19:12:04Z |
| Publication Date | 2014-12-29T19:26:06Z |

## Description

Salaries of state work force sorted by agency.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | series tag     | agency         | AGENCY #       | text      | number      |
| Yes      | series tag     | agency_title   | AGENCY TITLE   | text      | text        |
| Yes      | series tag     | classification | CLASSIFICATION | text      | text        |
| Yes      | series tag     | service_type   | SERVICE TYPE   | text      | text        |
| Yes      | series tag     | full_part_time | FULL/PART TIME | text      | text        |
| Yes      | numeric metric | annual_salary  | ANNUAL SALARY  | money     | money       |
| Yes      | time           | fiscal_year    | FISCAL YEAR    | number    | number      |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:q3ai-fubz d:2014-01-01T00:00:00.000Z t:service_type=REPRESENTED t:classification="ACCOUNTANT 1" t:agency_title="HUMAN SERVICES, DEPARTMENT OF" t:agency=10000 t:full_part_time=FULL-TIME m:annual_salary=51276

series e:q3ai-fubz d:2014-01-01T00:00:00.000Z t:service_type=REPRESENTED t:classification="ACCOUNTANT 1" t:agency_title="HUMAN SERVICES, DEPARTMENT OF" t:agency=10000 t:full_part_time=FULL-TIME m:annual_salary=51276

series e:q3ai-fubz d:2014-01-01T00:00:00.000Z t:service_type=REPRESENTED t:classification="ACCOUNTANT 1" t:agency_title="HUMAN SERVICES, DEPARTMENT OF" t:agency=10000 t:full_part_time=FULL-TIME m:annual_salary=42432
```

## Meta Commands

```ls
metric m:annual_salary p:double l:"ANNUAL SALARY" t:dataTypeName=money

entity e:q3ai-fubz l:"Salaries: State Agencies: As of June 30, 2014" t:url=https://data.oregon.gov/api/views/q3ai-fubz

property e:q3ai-fubz t:meta.view v:id=q3ai-fubz v:category="Revenue & Expense" v:averageRating=0 v:name="Salaries: State Agencies: As of June 30, 2014"

property e:q3ai-fubz t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:q3ai-fubz t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| agency | agency_title                  | classification | service_type | full_part_time | annual_salary | fiscal_year | 
| ====== | ============================= | ============== | ============ | ============== | ============= | =========== | 
| 10000  | HUMAN SERVICES, DEPARTMENT OF | ACCOUNTANT 1   | REPRESENTED  | FULL-TIME      | 51276.00      | 2014        | 
| 10000  | HUMAN SERVICES, DEPARTMENT OF | ACCOUNTANT 1   | REPRESENTED  | FULL-TIME      | 51276.00      | 2014        | 
| 10000  | HUMAN SERVICES, DEPARTMENT OF | ACCOUNTANT 1   | REPRESENTED  | FULL-TIME      | 42432.00      | 2014        | 
| 10000  | HUMAN SERVICES, DEPARTMENT OF | ACCOUNTANT 1   | REPRESENTED  | FULL-TIME      | 36924.00      | 2014        | 
| 10000  | HUMAN SERVICES, DEPARTMENT OF | ACCOUNTANT 1   | REPRESENTED  | FULL-TIME      | 38700.00      | 2014        | 
| 10000  | HUMAN SERVICES, DEPARTMENT OF | ACCOUNTANT 1   | REPRESENTED  | FULL-TIME      | 51276.00      | 2014        | 
| 10000  | HUMAN SERVICES, DEPARTMENT OF | ACCOUNTANT 1   | REPRESENTED  | FULL-TIME      | 51276.00      | 2014        | 
| 10000  | HUMAN SERVICES, DEPARTMENT OF | ACCOUNTANT 1   | REPRESENTED  | FULL-TIME      | 51276.00      | 2014        | 
| 10000  | HUMAN SERVICES, DEPARTMENT OF | ACCOUNTANT 1   | REPRESENTED  | FULL-TIME      | 40584.00      | 2014        | 
| 10000  | HUMAN SERVICES, DEPARTMENT OF | ACCOUNTANT 1   | REPRESENTED  | FULL-TIME      | 38700.00      | 2014        | 
```