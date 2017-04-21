# Salary: State Agencies: As of June 30, 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salary-state-agencies-as-of-june-30-2012-c3694) |
| Metadata | [Link](https://data.oregon.gov/api/views/axr9-cfm7) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/axr9-cfm7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/axr9-cfm7/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | axr9-cfm7 |
| Name | Salary: State Agencies: As of June 30, 2012 |
| Category | Revenue & Expense |
| Created | 2012-12-03T20:58:41Z |
| Publication Date | 2012-12-18T20:48:35Z |

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | series tag     | agency         | AGENCY #       | text      | text        |
| Yes      | series tag     | agency_title   | AGENCY TITLE   | text      | text        |
| Yes      | series tag     | classification | CLASSIFICATION | text      | text        |
| Yes      | series tag     | service_type   | SERVICE TYPE   | text      | text        |
| Yes      | series tag     | full_part_time | FULL/PART TIME | text      | text        |
| Yes      | numeric metric | annual_salary  | ANNUAL SALARY  | money     | money       |
| Yes      | time           | fiscal_year    | FISCAL YEAR    | number    | text        |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:axr9-cfm7 d:2012-01-01T00:00:00.000Z t:service_type="MANAGEMENT SERVICE" t:classification="PHYSICIAN SPECIALIST" t:agency_title="HUMAN SERVICES, DEPARTMENT OF" t:agency=10000 t:full_part_time=FULL-TIME m:annual_salary=169544.76

series e:axr9-cfm7 d:2012-01-01T00:00:00.000Z t:service_type="AGENCY HEAD" t:classification="PRINCIPAL EXECUTIVE/MANAGER J" t:agency_title="HUMAN SERVICES, DEPARTMENT OF" t:agency=10000 t:full_part_time=FULL-TIME m:annual_salary=152508

series e:axr9-cfm7 d:2012-01-01T00:00:00.000Z t:service_type="MANAGEMENT SERVICE" t:classification="SR MEDICAL CONSULTANT" t:agency_title="HUMAN SERVICES, DEPARTMENT OF" t:agency=10000 t:full_part_time=FULL-TIME m:annual_salary=149859.6
```

## Meta Commands

```ls
metric m:annual_salary p:double l:"ANNUAL SALARY" t:dataTypeName=money

entity e:axr9-cfm7 l:"Salary: State Agencies: As of June 30, 2012" t:url=https://data.oregon.gov/api/views/axr9-cfm7

property e:axr9-cfm7 t:meta.view v:id=axr9-cfm7 v:category="Revenue & Expense" v:averageRating=0 v:name="Salary: State Agencies: As of June 30, 2012"

property e:axr9-cfm7 t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:axr9-cfm7 t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| agency | agency_title                  | classification                | service_type       | full_part_time | annual_salary | fiscal_year | 
| ====== | ============================= | ============================= | ================== | ============== | ============= | =========== | 
| 10000  | HUMAN SERVICES, DEPARTMENT OF | PHYSICIAN SPECIALIST          | MANAGEMENT SERVICE | FULL-TIME      | 169544.76     | 2012        | 
| 10000  | HUMAN SERVICES, DEPARTMENT OF | PRINCIPAL EXECUTIVE/MANAGER J | AGENCY HEAD        | FULL-TIME      | 152508.00     | 2012        | 
| 10000  | HUMAN SERVICES, DEPARTMENT OF | SR MEDICAL CONSULTANT         | MANAGEMENT SERVICE | FULL-TIME      | 149859.60     | 2012        | 
| 10000  | HUMAN SERVICES, DEPARTMENT OF | PRINCIPAL EXECUTIVE/MANAGER I | EXECUTIVE SERVICE  | FULL-TIME      | 143076.00     | 2012        | 
| 10000  | HUMAN SERVICES, DEPARTMENT OF | PRINCIPAL EXECUTIVE/MANAGER H | EXECUTIVE SERVICE  | FULL-TIME      | 129804.00     | 2012        | 
| 10000  | HUMAN SERVICES, DEPARTMENT OF | PRINCIPAL EXECUTIVE/MANAGER I | EXECUTIVE SERVICE  | FULL-TIME      | 129804.00     | 2012        | 
| 10000  | HUMAN SERVICES, DEPARTMENT OF | PRINCIPAL EXECUTIVE/MANAGER H | MANAGEMENT SERVICE | FULL-TIME      | 129804.00     | 2012        | 
| 10000  | HUMAN SERVICES, DEPARTMENT OF | MEDICAL CONSULTANT            | REPRESENTED        | FULL-TIME      | 129571.20     | 2012        | 
| 10000  | HUMAN SERVICES, DEPARTMENT OF | MEDICAL CONSULTANT            | REPRESENTED        | FULL-TIME      | 129571.20     | 2012        | 
| 10000  | HUMAN SERVICES, DEPARTMENT OF | MEDICAL CONSULTANT            | REPRESENTED        | FULL-TIME      | 129571.20     | 2012        | 
```