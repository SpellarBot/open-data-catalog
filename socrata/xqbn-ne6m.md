# Salary: OUS: Eastern Oregon University: Fiscal Year 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salary-ous-eastern-oregon-university-fiscal-year-2012-d7994) |
| Metadata | [Link](https://data.oregon.gov/api/views/xqbn-ne6m) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/xqbn-ne6m/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/xqbn-ne6m/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | xqbn-ne6m |
| Name | Salary: OUS: Eastern Oregon University: Fiscal Year 2012 |
| Category | Revenue & Expense |
| Created | 2012-12-13T21:52:31Z |
| Publication Date | 2012-12-13T21:54:48Z |

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
series e:xqbn-ne6m d:2012-01-01T00:00:00.000Z t:service_type="Classified Staff" t:classification=Carpenter t:agency_title="OUS - Eastern Oregon University" t:agency=58010 t:full_part_time=Full-Time m:annual_salary=37800

series e:xqbn-ne6m d:2012-01-01T00:00:00.000Z t:service_type="Classified Staff" t:classification="Budget Analyst" t:agency_title="OUS - Eastern Oregon University" t:agency=58010 t:full_part_time=Full-Time m:annual_salary=60612

series e:xqbn-ne6m d:2012-01-01T00:00:00.000Z t:service_type="Classified Staff" t:classification="Accountant 1" t:agency_title="OUS - Eastern Oregon University" t:agency=58010 t:full_part_time=Full-Time m:annual_salary=37800
```

## Meta Commands

```ls
metric m:annual_salary p:integer l:"ANNUAL SALARY" t:dataTypeName=money

entity e:xqbn-ne6m l:"Salary: OUS: Eastern Oregon University: Fiscal Year 2012" t:url=https://data.oregon.gov/api/views/xqbn-ne6m

property e:xqbn-ne6m t:meta.view v:id=xqbn-ne6m v:category="Revenue & Expense" v:averageRating=0 v:name="Salary: OUS: Eastern Oregon University: Fiscal Year 2012"

property e:xqbn-ne6m t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:xqbn-ne6m t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| agency | agency_title                    | classification               | service_type     | full_part_time | annual_salary | 
| ====== | =============================== | ============================ | ================ | ============== | ============= | 
| 58010  | OUS - Eastern Oregon University | Carpenter                    | Classified Staff | Full-Time      | 37800         | 
| 58010  | OUS - Eastern Oregon University | Budget Analyst               | Classified Staff | Full-Time      | 60612         | 
| 58010  | OUS - Eastern Oregon University | Accountant 1                 | Classified Staff | Full-Time      | 37800         | 
| 58010  | OUS - Eastern Oregon University | Environ Health Safety Pro 1  | Classified Staff | Full-Time      | 30252         | 
| 58010  | OUS - Eastern Oregon University | Info Technology Consultant   | Classified Staff | Full-Time      | 26940         | 
| 58010  | OUS - Eastern Oregon University | Hvac Control Technician      | Classified Staff | Full-Time      | 43428         | 
| 58010  | OUS - Eastern Oregon University | Office Specialist 1          | Classified Staff | Full-Time      | 23076         | 
| 58010  | OUS - Eastern Oregon University | Grounds Maintenance Worker 1 | Classified Staff | Full-Time      | 27072         | 
| 58010  | OUS - Eastern Oregon University | Equipment Systems Specialist | Classified Staff | Full-Time      | 28620         | 
| 58010  | OUS - Eastern Oregon University | Office Specialist 2          | Classified Staff | Full-Time      | 30252         | 
```