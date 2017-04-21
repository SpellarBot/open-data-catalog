# Salaries of Oregon Lottery Employees FY 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salaries-of-oregon-lottery-employees-fy-2016) |
| Metadata | [Link](https://data.oregon.gov/api/views/rjr2-3kwr) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/rjr2-3kwr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/rjr2-3kwr/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | rjr2-3kwr |
| Name | Salaries of Oregon Lottery Employees FY 2016 |
| Category | Revenue & Expense |
| Tags | salaries, lottery employees, salaries of lottery employees, wages; salaries 2016, 2016 |
| Created | 2016-11-24T08:01:36Z |
| Publication Date | 2016-11-24T08:13:41Z |

## Description

Salaries of Oregon Lottery work force - 2016. For more information go to: http://www.oregon.gov/transparency/Pages/state_workforce.aspx#State_Employee_Salary:_H

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
series e:rjr2-3kwr d:2016-01-01T00:00:00.000Z t:service_type=UNREPRESENTED t:classification="ADMINISTRATIVE ASSISTANT 2" t:agency_title="LOTTERY, OREGON STATE" t:agency=17700 t:full_part_time="Fulltime Regular" m:annual_salary=50076

series e:rjr2-3kwr d:2016-01-01T00:00:00.000Z t:service_type=UNREPRESENTED t:classification="ADMINISTRATIVE ASSISTANT 2" t:agency_title="LOTTERY, OREGON STATE" t:agency=17700 t:full_part_time="Fulltime Regular" m:annual_salary=57984

series e:rjr2-3kwr d:2016-01-01T00:00:00.000Z t:service_type=UNREPRESENTED t:classification="ADMINISTRATIVE ASSISTANT 2" t:agency_title="LOTTERY, OREGON STATE" t:agency=17700 t:full_part_time="Fulltime Regular" m:annual_salary=58524
```

## Meta Commands

```ls
metric m:annual_salary p:integer l:"ANNUAL SALARY" t:dataTypeName=money

entity e:rjr2-3kwr l:"Salaries of Oregon Lottery Employees FY 2016" t:url=https://data.oregon.gov/api/views/rjr2-3kwr

property e:rjr2-3kwr t:meta.view v:id=rjr2-3kwr v:category="Revenue & Expense" v:averageRating=0 v:name="Salaries of Oregon Lottery Employees FY 2016"

property e:rjr2-3kwr t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:rjr2-3kwr t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| fiscal_year | agency | agency_title          | classification             | service_type  | full_part_time   | annual_salary | 
| =========== | ====== | ===================== | ========================== | ============= | ================ | ============= | 
| 2016        | 17700  | LOTTERY, OREGON STATE | ADMINISTRATIVE ASSISTANT 2 | UNREPRESENTED | Fulltime Regular | 50076         | 
| 2016        | 17700  | LOTTERY, OREGON STATE | ADMINISTRATIVE ASSISTANT 2 | UNREPRESENTED | Fulltime Regular | 57984         | 
| 2016        | 17700  | LOTTERY, OREGON STATE | ADMINISTRATIVE ASSISTANT 2 | UNREPRESENTED | Fulltime Regular | 58524         | 
| 2016        | 17700  | LOTTERY, OREGON STATE | ADMINISTRATIVE ASSISTANT 2 | UNREPRESENTED | Fulltime Regular | 44112         | 
| 2016        | 17700  | LOTTERY, OREGON STATE | ADMINISTRATIVE ASSISTANT 2 | UNREPRESENTED | Fulltime Regular | 58524         | 
| 2016        | 17700  | LOTTERY, OREGON STATE | ADMINISTRATIVE ASSISTANT 2 | UNREPRESENTED | Fulltime Regular | 55860         | 
| 2016        | 17700  | LOTTERY, OREGON STATE | ADMINISTRATIVE ASSISTANT 2 | UNREPRESENTED | Fulltime Regular | 58524         | 
| 2016        | 17700  | LOTTERY, OREGON STATE | ADMINISTRATIVE ASSISTANT 2 | UNREPRESENTED | Fulltime Regular | 54984         | 
| 2016        | 17700  | LOTTERY, OREGON STATE | ADMINISTRATIVE ASSISTANT 2 | UNREPRESENTED | Fulltime Regular | 43368         | 
| 2016        | 17700  | LOTTERY, OREGON STATE | ADMINISTRATIVE ASSISTANT 2 | UNREPRESENTED | Fulltime Regular | 58524         | 
```