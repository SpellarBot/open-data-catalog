# Salary: OUS: Oregon State University: Fiscal Year 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salary-ous-oregon-state-university-fiscal-year-2012-da8a4) |
| Metadata | [Link](https://data.oregon.gov/api/views/i8tj-ziur) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/i8tj-ziur/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/i8tj-ziur/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | i8tj-ziur |
| Name | Salary: OUS: Oregon State University: Fiscal Year 2012 |
| Category | Revenue & Expense |
| Created | 2012-12-15T00:59:43Z |
| Publication Date | 2012-12-15T01:02:26Z |

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | series tag     | agency         | AGENCY #       | text      | text        |
| Yes      | series tag     | agency_title   | AGENCY TITLE   | text      | text        |
| Yes      | series tag     | classification | CLASSIFICATION | text      | text        |
| Yes      | series tag     | service_type   | SERVICE TYPE   | text      | text        |
| Yes      | series tag     | full_part_time | FULL/PART-TIME | text      | text        |
| Yes      | numeric metric | annual_salary  | ANNUAL SALARY  | money     | money       |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:i8tj-ziur d:2012-01-01T00:00:00.000Z t:service_type="Other professionals" t:classification="Head Coach" t:agency_title="OUS - Oregon State University" t:agency=58030 t:full_part_time=Full-Time m:annual_salary=860004

series e:i8tj-ziur d:2012-01-01T00:00:00.000Z t:service_type="Executive/Admin and managerial" t:classification=Director t:agency_title="OUS - Oregon State University" t:agency=58030 t:full_part_time=Full-Time m:annual_salary=440364

series e:i8tj-ziur d:2012-01-01T00:00:00.000Z t:service_type="Other professionals" t:classification="Assistant Coach" t:agency_title="OUS - Oregon State University" t:agency=58030 t:full_part_time=Full-Time m:annual_salary=440004
```

## Meta Commands

```ls
metric m:annual_salary p:integer l:"ANNUAL SALARY" t:dataTypeName=money

entity e:i8tj-ziur l:"Salary: OUS: Oregon State University: Fiscal Year 2012" t:url=https://data.oregon.gov/api/views/i8tj-ziur

property e:i8tj-ziur t:meta.view v:id=i8tj-ziur v:category="Revenue & Expense" v:averageRating=0 v:name="Salary: OUS: Oregon State University: Fiscal Year 2012"

property e:i8tj-ziur t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:i8tj-ziur t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| agency | agency_title                  | classification       | service_type                   | full_part_time | annual_salary | 
| ====== | ============================= | ==================== | ============================== | ============== | ============= | 
| 58030  | OUS - Oregon State University | Head Coach           | Other professionals            | Full-Time      | 860004        | 
| 58030  | OUS - Oregon State University | Director             | Executive/Admin and managerial | Full-Time      | 440364        | 
| 58030  | OUS - Oregon State University | Assistant Coach      | Other professionals            | Full-Time      | 440004        | 
| 58030  | OUS - Oregon State University | President            | Executive/Admin and managerial | Full-Time      | 425700        | 
| 58030  | OUS - Oregon State University | Provost              | Executive/Admin and managerial | Full-Time      | 300000        | 
| 58030  | OUS - Oregon State University | Head Coach           | Other professionals            | Full-Time      | 293556        | 
| 58030  | OUS - Oregon State University | Assistant Coach      | Other professionals            | Full-Time      | 260004        | 
| 58030  | OUS - Oregon State University | Head Coach           | Other professionals            | Full-Time      | 260004        | 
| 58030  | OUS - Oregon State University | Vice President       | Executive/Admin and managerial | Full-Time      | 254880        | 
| 58030  | OUS - Oregon State University | Professional Faculty | Other professionals            | Full-Time      | 240420        | 
```