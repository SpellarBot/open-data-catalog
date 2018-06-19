# 2015-Salaries-Lottery-063015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-salaries-lottery-063015) |
| Metadata | [Link](https://data.oregon.gov/api/views/a64g-gq3c) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/a64g-gq3c/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/a64g-gq3c/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | a64g-gq3c |
| Name | 2015-Salaries-Lottery-063015 |
| Category | Revenue & Expense |
| Tags | salaries, lottery employees, salaries of lottery employees, wages of lottery employees, salaries 2015, 2015 |
| Created | 2015-12-14T01:38:56Z |
| Publication Date | 2015-12-24T06:11:04Z |

## Description

Salaries of Oregon Lottery work force - 2015. For more information go to: http://www.oregon.gov/transparency/Pages/state_workforce.aspx#State_Employee_Salary:_Historical_Reports

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
series e:a64g-gq3c d:2015-01-01T00:00:00.000Z t:service_type=UNREPRESENTED t:classification="ADMINISTRATIVE ASSISTANT 1" t:agency_title="LOTTERY, OREGON STATE" t:agency=17700 t:full_part_time="Parttime Temporary" m:annual_salary=34632

series e:a64g-gq3c d:2015-01-01T00:00:00.000Z t:service_type=UNREPRESENTED t:classification="ADMINISTRATIVE ASSISTANT 1" t:agency_title="LOTTERY, OREGON STATE" t:agency=17700 t:full_part_time="Parttime Temporary" m:annual_salary=17317

series e:a64g-gq3c d:2015-01-01T00:00:00.000Z t:service_type=UNREPRESENTED t:classification="ADMINISTRATIVE ASSISTANT 2" t:agency_title="LOTTERY, OREGON STATE" t:agency=17700 t:full_part_time="Fulltime Regular" m:annual_salary=57240
```

## Meta Commands

```ls
metric m:annual_salary p:integer l:"ANNUAL SALARY" t:dataTypeName=money

entity e:a64g-gq3c l:2015-Salaries-Lottery-063015 t:url=https://data.oregon.gov/api/views/a64g-gq3c

property e:a64g-gq3c t:meta.view v:id=a64g-gq3c v:category="Revenue & Expense" v:averageRating=0 v:name=2015-Salaries-Lottery-063015

property e:a64g-gq3c t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:a64g-gq3c t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| fiscal_year | agency | agency_title          | classification             | service_type  | full_part_time     | annual_salary | 
| =========== | ====== | ===================== | ========================== | ============= | ================== | ============= | 
| 2015        | 17700  | LOTTERY, OREGON STATE | ADMINISTRATIVE ASSISTANT 1 | UNREPRESENTED | Parttime Temporary | 34632         | 
| 2015        | 17700  | LOTTERY, OREGON STATE | ADMINISTRATIVE ASSISTANT 1 | UNREPRESENTED | Parttime Temporary | 17317         | 
| 2015        | 17700  | LOTTERY, OREGON STATE | ADMINISTRATIVE ASSISTANT 2 | UNREPRESENTED | Fulltime Regular   | 57240         | 
| 2015        | 17700  | LOTTERY, OREGON STATE | ADMINISTRATIVE ASSISTANT 2 | UNREPRESENTED | Fulltime Regular   | 57240         | 
| 2015        | 17700  | LOTTERY, OREGON STATE | ADMINISTRATIVE ASSISTANT 2 | UNREPRESENTED | Fulltime Regular   | 51213         | 
| 2015        | 17700  | LOTTERY, OREGON STATE | ADMINISTRATIVE ASSISTANT 2 | UNREPRESENTED | Fulltime Regular   | 46635         | 
| 2015        | 17700  | LOTTERY, OREGON STATE | ADMINISTRATIVE ASSISTANT 2 | UNREPRESENTED | Fulltime Regular   | 57063         | 
| 2015        | 17700  | LOTTERY, OREGON STATE | ADMINISTRATIVE ASSISTANT 2 | UNREPRESENTED | Fulltime Regular   | 57240         | 
| 2015        | 17700  | LOTTERY, OREGON STATE | ADMINISTRATIVE ASSISTANT 2 | UNREPRESENTED | Fulltime Regular   | 52033         | 
| 2015        | 17700  | LOTTERY, OREGON STATE | ADMINISTRATIVE ASSISTANT 2 | UNREPRESENTED | Fulltime Regular   | 40392         | 
```