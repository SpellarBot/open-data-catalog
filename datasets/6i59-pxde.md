# Salaries: ESD: Grant: Fiscal Year 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salaries-esd-grant-fiscal-year-2014-2d617) |
| Metadata | [Link](https://data.oregon.gov/api/views/6i59-pxde) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/6i59-pxde/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/6i59-pxde/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 6i59-pxde |
| Name | Salaries: ESD: Grant: Fiscal Year 2014 |
| Category | Revenue & Expense |
| Tags | salaries, esd, grant, fiscal year 2014 |
| Created | 2014-12-16T19:36:55Z |
| Publication Date | 2014-12-29T06:10:15Z |

## Description

Salaries for Grant ESD for Fiscal Year 2014

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
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:6i59-pxde d:2014-01-01T00:00:00.000Z t:esd_name="GRANT ESD" t:service_type=Classified t:classification="Clerical Assistant" t:full_part_time="Part Time" m:annual_salary=110 m:esd=2007

series e:6i59-pxde d:2014-01-01T00:00:00.000Z t:esd_name="GRANT ESD" t:service_type=Classified t:classification="Clerical Assistant" t:full_part_time="Part Time" m:annual_salary=175 m:esd=2007

series e:6i59-pxde d:2014-01-01T00:00:00.000Z t:esd_name="GRANT ESD" t:service_type=Classified t:classification="Special Ed. Aide - Substitute" t:full_part_time="Part Time" m:annual_salary=65.5 m:esd=2007
```

## Meta Commands

```ls
metric m:esd p:integer l:"ESD #" t:dataTypeName=number

metric m:annual_salary p:double l:"Annual Salary" t:dataTypeName=money

entity e:6i59-pxde l:"Salaries: ESD: Grant: Fiscal Year 2014" t:url=https://data.oregon.gov/api/views/6i59-pxde

property e:6i59-pxde t:meta.view v:id=6i59-pxde v:category="Revenue & Expense" v:averageRating=0 v:name="Salaries: ESD: Grant: Fiscal Year 2014"

property e:6i59-pxde t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:6i59-pxde t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | esd_name  | classification                | service_type | full_part_time | annual_salary | 
| ==== | ========= | ============================= | ============ | ============== | ============= | 
| 2007 | GRANT ESD | Clerical Assistant            | Classified   | Part Time      | 110.00        | 
| 2007 | GRANT ESD | Clerical Assistant            | Classified   | Part Time      | 175.00        | 
| 2007 | GRANT ESD | Special Ed. Aide - Substitute | Classified   | Part Time      | 65.50         | 
| 2007 | GRANT ESD | Special Ed. Aide - Substitute | Classified   | Part Time      | 65.50         | 
| 2007 | GRANT ESD | Special Ed. Aide - Substitute | Classified   | Part Time      | 78.60         | 
| 2007 | GRANT ESD | Special Ed. Aide              | Classified   | Part Time      | 3307.76       | 
| 2007 | GRANT ESD | Special Ed. Aide              | Classified   | Part Time      | 11772.61      | 
| 2007 | GRANT ESD | Hearing Specialist            | Classified   | Part Time      | 677.29        | 
| 2007 | GRANT ESD | Special Ed. Aide - Substitute | Classified   | Part Time      | 196.50        | 
| 2007 | GRANT ESD | Technology Specialist         | Classified   | Part Time      | 1505.00       | 
```