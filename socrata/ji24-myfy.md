# Salary: OUS: Chancellor's Office: Fiscal Year 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salary-ous-chancellors-office-fiscal-year-2012-d8639) |
| Metadata | [Link](https://data.oregon.gov/api/views/ji24-myfy) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/ji24-myfy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/ji24-myfy/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | ji24-myfy |
| Name | Salary: OUS: Chancellor's Office: Fiscal Year 2012 |
| Category | Revenue & Expense |
| Created | 2012-12-13T21:51:12Z |
| Publication Date | 2012-12-13T21:51:50Z |

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
series e:ji24-myfy d:2012-01-01T00:00:00.000Z t:service_type="Classified Staff" t:classification="Accountant 2" t:agency_title="OUS - Chancellor's Office" t:agency=58080 t:full_part_time=Full-Time m:annual_salary=57756

series e:ji24-myfy d:2012-01-01T00:00:00.000Z t:service_type="Classified Staff" t:classification="Fiscal Coordinator 2" t:agency_title="OUS - Chancellor's Office" t:agency=58080 t:full_part_time=Full-Time m:annual_salary=69828

series e:ji24-myfy d:2012-01-01T00:00:00.000Z t:service_type="Classified Staff" t:classification="Accountant 2" t:agency_title="OUS - Chancellor's Office" t:agency=58080 t:full_part_time=Full-Time m:annual_salary=57756
```

## Meta Commands

```ls
metric m:annual_salary p:integer l:"ANNUAL SALARY" t:dataTypeName=money

entity e:ji24-myfy l:"Salary: OUS: Chancellor's Office: Fiscal Year 2012" t:url=https://data.oregon.gov/api/views/ji24-myfy

property e:ji24-myfy t:meta.view v:id=ji24-myfy v:category="Revenue & Expense" v:averageRating=0 v:name="Salary: OUS: Chancellor's Office: Fiscal Year 2012"

property e:ji24-myfy t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:ji24-myfy t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| agency | agency_title              | classification            | service_type                   | full_part_time | annual_salary | 
| ====== | ========================= | ========================= | ============================== | ============== | ============= | 
| 58080  | OUS - Chancellor's Office | Accountant 2              | Classified Staff               | Full-Time      | 57756         | 
| 58080  | OUS - Chancellor's Office | Fiscal Coordinator 2      | Classified Staff               | Full-Time      | 69828         | 
| 58080  | OUS - Chancellor's Office | Accountant 2              | Classified Staff               | Full-Time      | 57756         | 
| 58080  | OUS - Chancellor's Office | Accountant 2              | Classified Staff               | Full-Time      | 57756         | 
| 58080  | OUS - Chancellor's Office | Fiscal Coordinator 2      | Classified Staff               | Full-Time      | 69828         | 
| 58080  | OUS - Chancellor's Office | Accountant 1              | Classified Staff               | Full-Time      | 39588         | 
| 58080  | OUS - Chancellor's Office | Program Representative 1  | Classified Staff               | Full-Time      | 39588         | 
| 58080  | OUS - Chancellor's Office | Audit Supervisor          | Executive/Admin and managerial | Full-Time      | 80604         | 
| 58080  | OUS - Chancellor's Office | Staff Auditor             | Other professionals            | Full-Time      | 47748         | 
| 58080  | OUS - Chancellor's Office | VC of Academic Strategies | Executive/Admin and managerial | Full-Time      | 207036        | 
```