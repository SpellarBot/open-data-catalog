# Salaries: ESD: Grant: Fiscal Year 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salaries-esd-grant-fiscal-year-2013-2ca68) |
| Metadata | [Link](https://data.oregon.gov/api/views/4n7s-wgfb) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/4n7s-wgfb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/4n7s-wgfb/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 4n7s-wgfb |
| Name | Salaries: ESD: Grant: Fiscal Year 2013 |
| Category | Revenue & Expense |
| Tags | salaries, esd, grant, fiscal year 2013 |
| Created | 2013-11-04T19:44:15Z |
| Publication Date | 2013-11-04T19:46:34Z |

## Description

Salaries for Grant ESD for Fiscal Year 2013

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | numeric metric | esd            | ESD #          | number    | number      |
| Yes      | series tag     | esd_name       | ESD Name       | text      | text        |
| Yes      | series tag     | classification | Classification | text      | text        |
| Yes      | series tag     | service_type   | Service Type   | text      | text        |
| Yes      | series tag     | full_part_time | Full/Part Time | text      | text        |
| Yes      | numeric metric | annual_salary  | Annual Salary  | money     | money       |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:4n7s-wgfb d:2013-01-01T00:00:00.000Z t:esd_name="GRANT ESD" t:service_type=Classified t:classification="Technology Specialist 3" t:full_part_time="Full Time" m:annual_salary=51568 m:esd=2007

series e:4n7s-wgfb d:2013-01-01T00:00:00.000Z t:esd_name="GRANT ESD" t:service_type=Classified t:classification="Special Ed Aide - Substitute" t:full_part_time="Part Time" m:annual_salary=615.7 m:esd=2007

series e:4n7s-wgfb d:2013-01-01T00:00:00.000Z t:esd_name="GRANT ESD" t:service_type=Classified t:classification="Technology Specialist" t:full_part_time="Full Time" m:annual_salary=20250 m:esd=2007
```

## Meta Commands

```ls
metric m:esd p:integer l:"ESD #" t:dataTypeName=number

metric m:annual_salary p:double l:"Annual Salary" t:dataTypeName=money

entity e:4n7s-wgfb l:"Salaries: ESD: Grant: Fiscal Year 2013" t:url=https://data.oregon.gov/api/views/4n7s-wgfb

property e:4n7s-wgfb t:meta.view v:id=4n7s-wgfb v:category="Revenue & Expense" v:averageRating=0 v:name="Salaries: ESD: Grant: Fiscal Year 2013"

property e:4n7s-wgfb t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:4n7s-wgfb t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | esd_name  | classification                | service_type   | full_part_time | annual_salary | 
| ==== | ========= | ============================= | ============== | ============== | ============= | 
| 2007 | GRANT ESD | Technology Specialist 3       | Classified     | Full Time      | 51568.00      | 
| 2007 | GRANT ESD | Special Ed Aide - Substitute  | Classified     | Part Time      | 615.70        | 
| 2007 | GRANT ESD | Technology Specialist         | Classified     | Full Time      | 20250.00      | 
| 2007 | GRANT ESD | Special Ed. Aide              | Classified     | Part Time      | 12099.90      | 
| 2007 | GRANT ESD | Special Ed. Aide              | Classified     | Part Time      | 18461.86      | 
| 2007 | GRANT ESD | Regional CTE Coordinator      | Classified     | Part Time      | 42560.00      | 
| 2007 | GRANT ESD | Special Ed. Aide - Substitute | Classified     | Part Time      | 131.00        | 
| 2007 | GRANT ESD | Special Ed. Aide - Substitute | Classified     | Part Time      | 2089.45       | 
| 2007 | GRANT ESD | Special Ed. Aide              | Classified     | Part Time      | 19603.00      | 
| 2007 | GRANT ESD | Deputy Clerk                  | Administrative | Full Time      | 75682.57      | 
```