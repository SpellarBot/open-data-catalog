# Salaries: ESD: Multnomah County: Fiscal Year 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salaries-esd-multnomah-county-fiscal-year-2014-bf1ee) |
| Metadata | [Link](https://data.oregon.gov/api/views/d3qr-4azh) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/d3qr-4azh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/d3qr-4azh/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | d3qr-4azh |
| Name | Salaries: ESD: Multnomah County: Fiscal Year 2014 |
| Category | Revenue & Expense |
| Tags | esd, esd salaries, multnomah esd, mesd, mesd salaries, multnomah esd salaries, 2014 |
| Created | 2014-12-05T01:26:05Z |
| Publication Date | 2014-12-29T05:47:09Z |

## Description

Salaries of Multnomah County ESD employees for Fiscal Year 2014

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | numeric metric | esd            | ESD #          | number    | number      |
| Yes      | series tag     | esd_name       | ESD Name       | text      | text        |
| Yes      | series tag     | classification | Classification | text      | text        |
| Yes      | series tag     | full_part_time | Full/Part Time | text      | text        |
| Yes      | series tag     | service_type   | Service Type   | text      | text        |
| Yes      | numeric metric | annual_salary  | Annual Salary  | money     | money       |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:d3qr-4azh d:2014-01-01T00:00:00.000Z t:esd_name="Multnomah ESD" t:service_type=Classified t:classification="ACCOUNTING ASSISTANT II" t:full_part_time="Full Time" m:annual_salary=41509.44 m:esd=2148

series e:d3qr-4azh d:2014-01-01T00:00:00.000Z t:esd_name="Multnomah ESD" t:service_type=Classified t:classification="ACCOUNTING ASSISTANT III" t:full_part_time="Full Time" m:annual_salary=45789.84 m:esd=2148

series e:d3qr-4azh d:2014-01-01T00:00:00.000Z t:esd_name="Multnomah ESD" t:service_type=Classified t:classification="ALT PATHWAYS COLLEGE TRAN ADV" t:full_part_time="Part Time" m:annual_salary=7355.59 m:esd=2148
```

## Meta Commands

```ls
metric m:esd p:integer l:"ESD #" t:dataTypeName=number

metric m:annual_salary p:double l:"Annual Salary" t:dataTypeName=money

entity e:d3qr-4azh l:"Salaries: ESD: Multnomah County: Fiscal Year 2014" t:url=https://data.oregon.gov/api/views/d3qr-4azh

property e:d3qr-4azh t:meta.view v:id=d3qr-4azh v:category="Revenue & Expense" v:averageRating=0 v:name="Salaries: ESD: Multnomah County: Fiscal Year 2014"

property e:d3qr-4azh t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:d3qr-4azh t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | esd_name      | classification                | full_part_time | service_type  | annual_salary | 
| ==== | ============= | ============================= | ============== | ============= | ============= | 
| 2148 | Multnomah ESD | ACCOUNTING ASSISTANT II       | Full Time      | Classified    | 41509.44      | 
| 2148 | Multnomah ESD | ACCOUNTING ASSISTANT III      | Full Time      | Classified    | 45789.84      | 
| 2148 | Multnomah ESD | ALT PATHWAYS COLLEGE TRAN ADV | Part Time      | Classified    | 7355.59       | 
| 2148 | Multnomah ESD | ALT PATHWAYS COLLEGE TRAN ADV | Part Time      | Unrepresented | 17776.45      | 
| 2148 | Multnomah ESD | ALT PATHWAYS COLLEGE TRAN ADV | Part Time      | Classified    | 34698.45      | 
| 2148 | Multnomah ESD | ALT PATHWAYS PROJ MGR         | Full Time      | Supervisor    | 63734.14      | 
| 2148 | Multnomah ESD | APP DEV STUDENT DATA COORD    | Full Time      | Classified    | 74520.72      | 
| 2148 | Multnomah ESD | APPLICATION DEVELOPER         | Full Time      | Classified    | 55645.20      | 
| 2148 | Multnomah ESD | APPLICATION DEVELOPER         | Full Time      | Classified    | 58317.84      | 
| 2148 | Multnomah ESD | APPLICATION DEVELOPER         | Full Time      | Classified    | 64352.16      | 
```