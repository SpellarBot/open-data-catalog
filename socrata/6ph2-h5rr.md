# Salaries:Oregon Lottery Payroll Report: As of June 30, 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salaries-oregon-lottery-payroll-report-as-of-june-30-2014-8018f) |
| Metadata | [Link](https://data.oregon.gov/api/views/6ph2-h5rr) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/6ph2-h5rr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/6ph2-h5rr/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 6ph2-h5rr |
| Name | Salaries:Oregon Lottery Payroll Report: As of June 30, 2014 |
| Category | Revenue & Expense |
| Tags | salaries, lottery employees, salaries of lottery employees, wages of lottery employees, salaries 2014, 2014 |
| Created | 2014-12-30T02:48:27Z |
| Publication Date | 2014-12-30T02:54:40Z |

## Description

Salaries of Oregon Lottery work force

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | series tag     | agency            | AGENCY #          | text      | number      |
| Yes      | series tag     | agency_title      | AGENCY TITLE      | text      | text        |
| Yes      | series tag     | classification    | CLASSIFICATION    | text      | text        |
| Yes      | series tag     | service_type      | SERVICE TYPE      | text      | text        |
| Yes      | series tag     | fulltime_parttime | FULLTIME/PARTTIME | text      | text        |
| Yes      | numeric metric | annual_salary     | ANNUAL SALARY     | money     | money       |
| Yes      | time           | fiscal_year       | FISCAL YEAR       | number    | number      |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:6ph2-h5rr d:2014-01-01T00:00:00.000Z t:service_type="NON MANAGEMENT" t:classification="ADMINISTRATIVE ASSISTANT 1" t:agency_title="LOTTERY, OREGON STATE" t:agency=17700 t:fulltime_parttime="REGULAR PARTTIME" m:annual_salary=18716.4

series e:6ph2-h5rr d:2014-01-01T00:00:00.000Z t:service_type="NON MANAGEMENT" t:classification="ADMINISTRATIVE ASSISTANT 1" t:agency_title="LOTTERY, OREGON STATE" t:agency=17700 t:fulltime_parttime="REGULAR FULLTIME" m:annual_salary=36000

series e:6ph2-h5rr d:2014-01-01T00:00:00.000Z t:service_type="NON MANAGEMENT" t:classification="ADMINISTRATIVE ASSISTANT 1" t:agency_title="LOTTERY, OREGON STATE" t:agency=17700 t:fulltime_parttime="REGULAR FULLTIME" m:annual_salary=36540
```

## Meta Commands

```ls
metric m:annual_salary p:double l:"ANNUAL SALARY" t:dataTypeName=money

entity e:6ph2-h5rr l:"Salaries:Oregon Lottery Payroll Report: As of June 30, 2014" t:url=https://data.oregon.gov/api/views/6ph2-h5rr

property e:6ph2-h5rr t:meta.view v:id=6ph2-h5rr v:category="Revenue & Expense" v:averageRating=0 v:name="Salaries:Oregon Lottery Payroll Report: As of June 30, 2014"

property e:6ph2-h5rr t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:6ph2-h5rr t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| agency | agency_title          | classification             | service_type              | fulltime_parttime | annual_salary | fiscal_year | 
| ====== | ===================== | ========================== | ========================= | ================= | ============= | =========== | 
| 17700  | LOTTERY, OREGON STATE | ADMINISTRATIVE ASSISTANT 1 | NON MANAGEMENT            | REGULAR PARTTIME  | 18716.40      | 2014        | 
| 17700  | LOTTERY, OREGON STATE | ADMINISTRATIVE ASSISTANT 1 | NON MANAGEMENT            | REGULAR FULLTIME  | 36000.00      | 2014        | 
| 17700  | LOTTERY, OREGON STATE | ADMINISTRATIVE ASSISTANT 1 | NON MANAGEMENT            | REGULAR FULLTIME  | 36540.00      | 2014        | 
| 17700  | LOTTERY, OREGON STATE | ADMINISTRATIVE ASSISTANT 1 | NON MANAGEMENT            | REGULAR FULLTIME  | 48036.00      | 2014        | 
| 17700  | LOTTERY, OREGON STATE | ADMINISTRATIVE ASSISTANT 1 | NON MANAGEMENT            | REGULAR FULLTIME  | 48588.00      | 2014        | 
| 17700  | LOTTERY, OREGON STATE | ADMINISTRATIVE ASSISTANT 1 | NON MANAGEMENT            | REGULAR FULLTIME  | 49224.00      | 2014        | 
| 17700  | LOTTERY, OREGON STATE | ADMINISTRATIVE ASSISTANT 2 | NON MANAGEMENT            | REGULAR FULLTIME  | 37716.00      | 2014        | 
| 17700  | LOTTERY, OREGON STATE | ADMINISTRATIVE ASSISTANT 2 | MANAGEMENT REPRESENTATIVE | REGULAR FULLTIME  | 42840.00      | 2014        | 
| 17700  | LOTTERY, OREGON STATE | ADMINISTRATIVE ASSISTANT 2 | NON MANAGEMENT            | REGULAR FULLTIME  | 43548.00      | 2014        | 
| 17700  | LOTTERY, OREGON STATE | ADMINISTRATIVE ASSISTANT 2 | NON MANAGEMENT            | REGULAR FULLTIME  | 47820.00      | 2014        | 
```