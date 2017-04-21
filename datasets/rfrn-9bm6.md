# Salary: State Agencies: As of June 30, 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salary-state-agencies-as-of-june-30-2013-cafd5) |
| Metadata | [Link](https://data.oregon.gov/api/views/rfrn-9bm6) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/rfrn-9bm6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/rfrn-9bm6/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | rfrn-9bm6 |
| Name | Salary: State Agencies: As of June 30, 2013 |
| Category | Revenue & Expense |
| Created | 2013-07-30T15:36:19Z |
| Publication Date | 2013-07-30T16:13:42Z |

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
series e:rfrn-9bm6 d:2013-01-01T00:00:00.000Z t:service_type=REPRESENTED t:classification="ACCOUNTANT 1" t:agency_title="HUMAN SERVICES, DEPARTMENT OF" t:agency=10000 t:full_part_time=FULL-TIME m:annual_salary=34788

series e:rfrn-9bm6 d:2013-01-01T00:00:00.000Z t:service_type=REPRESENTED t:classification="ACCOUNTANT 1" t:agency_title="HUMAN SERVICES, DEPARTMENT OF" t:agency=10000 t:full_part_time=FULL-TIME m:annual_salary=36384

series e:rfrn-9bm6 d:2013-01-01T00:00:00.000Z t:service_type=REPRESENTED t:classification="ACCOUNTANT 1" t:agency_title="HUMAN SERVICES, DEPARTMENT OF" t:agency=10000 t:full_part_time=FULL-TIME m:annual_salary=36384
```

## Meta Commands

```ls
metric m:annual_salary p:double l:"ANNUAL SALARY" t:dataTypeName=money

entity e:rfrn-9bm6 l:"Salary: State Agencies: As of June 30, 2013" t:url=https://data.oregon.gov/api/views/rfrn-9bm6

property e:rfrn-9bm6 t:meta.view v:id=rfrn-9bm6 v:category="Revenue & Expense" v:averageRating=0 v:name="Salary: State Agencies: As of June 30, 2013"

property e:rfrn-9bm6 t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:rfrn-9bm6 t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| agency | agency_title                  | classification | service_type | full_part_time | annual_salary | fiscal_year | 
| ====== | ============================= | ============== | ============ | ============== | ============= | =========== | 
| 10000  | HUMAN SERVICES, DEPARTMENT OF | ACCOUNTANT 1   | REPRESENTED  | FULL-TIME      | 34788.00      | 2013        | 
| 10000  | HUMAN SERVICES, DEPARTMENT OF | ACCOUNTANT 1   | REPRESENTED  | FULL-TIME      | 36384.00      | 2013        | 
| 10000  | HUMAN SERVICES, DEPARTMENT OF | ACCOUNTANT 1   | REPRESENTED  | FULL-TIME      | 36384.00      | 2013        | 
| 10000  | HUMAN SERVICES, DEPARTMENT OF | ACCOUNTANT 1   | REPRESENTED  | FULL-TIME      | 37254.00      | 2013        | 
| 10000  | HUMAN SERVICES, DEPARTMENT OF | ACCOUNTANT 1   | REPRESENTED  | FULL-TIME      | 42816.00      | 2013        | 
| 10000  | HUMAN SERVICES, DEPARTMENT OF | ACCOUNTANT 1   | REPRESENTED  | FULL-TIME      | 48228.00      | 2013        | 
| 10000  | HUMAN SERVICES, DEPARTMENT OF | ACCOUNTANT 1   | REPRESENTED  | FULL-TIME      | 48228.00      | 2013        | 
| 10000  | HUMAN SERVICES, DEPARTMENT OF | ACCOUNTANT 1   | REPRESENTED  | FULL-TIME      | 48228.00      | 2013        | 
| 10000  | HUMAN SERVICES, DEPARTMENT OF | ACCOUNTANT 1   | REPRESENTED  | FULL-TIME      | 49374.00      | 2013        | 
| 10000  | HUMAN SERVICES, DEPARTMENT OF | ACCOUNTANT 1   | REPRESENTED  | FULL-TIME      | 49374.00      | 2013        | 
```