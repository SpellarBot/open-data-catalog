# Salaries: ESD: Jefferson County: Fiscal Year 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salaries-esd-jefferson-county-fiscal-year-2014-1fa43) |
| Metadata | [Link](https://data.oregon.gov/api/views/5v4e-jsc2) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/5v4e-jsc2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/5v4e-jsc2/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 5v4e-jsc2 |
| Name | Salaries: ESD: Jefferson County: Fiscal Year 2014 |
| Category | Revenue & Expense |
| Tags | jefferson esd salaries, jefferson county esd salaries, jcesd salaries, esd salaries, 2014 |
| Created | 2014-12-16T21:19:37Z |
| Publication Date | 2014-12-29T06:13:54Z |

## Description

Summary of salaries for Jefferson County ESD for Fiscal Year 2014.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | numeric metric | esd            | ESD#           | number    | number      |
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
series e:5v4e-jsc2 d:2014-01-01T00:00:00.000Z t:esd_name="Jefferson Co. Ed. Svc. District" t:service_type=ADMINISTRATIVE t:classification="EXECUTIVE ADMIN ASST" t:full_part_time="Part Time" m:annual_salary=6000 m:esd=2049

series e:5v4e-jsc2 d:2014-01-01T00:00:00.000Z t:esd_name="Jefferson Co. Ed. Svc. District" t:service_type=ADMINISTRATIVE t:classification=CFO t:full_part_time="Part Time" m:annual_salary=12250 m:esd=2049

series e:5v4e-jsc2 d:2014-01-01T00:00:00.000Z t:esd_name="Jefferson Co. Ed. Svc. District" t:service_type=ADMINISTRATIVE t:classification=SUPERINTENDENT t:full_part_time="Part Time" m:annual_salary=12250 m:esd=2049
```

## Meta Commands

```ls
metric m:esd p:integer l:ESD# t:dataTypeName=number

metric m:annual_salary p:double l:"Annual Salary" t:dataTypeName=money

entity e:5v4e-jsc2 l:"Salaries: ESD: Jefferson County: Fiscal Year 2014" t:url=https://data.oregon.gov/api/views/5v4e-jsc2

property e:5v4e-jsc2 t:meta.view v:id=5v4e-jsc2 v:category="Revenue & Expense" v:averageRating=0 v:name="Salaries: ESD: Jefferson County: Fiscal Year 2014"

property e:5v4e-jsc2 t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:5v4e-jsc2 t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | esd_name                        | classification           | service_type   | full_part_time | annual_salary | 
| ==== | =============================== | ======================== | ============== | ============== | ============= | 
| 2049 | Jefferson Co. Ed. Svc. District | EXECUTIVE ADMIN ASST     | ADMINISTRATIVE | Part Time      | 6000.00       | 
| 2049 | Jefferson Co. Ed. Svc. District | CFO                      | ADMINISTRATIVE | Part Time      | 12250.00      | 
| 2049 | Jefferson Co. Ed. Svc. District | SUPERINTENDENT           | ADMINISTRATIVE | Part Time      | 12250.00      | 
| 2049 | Jefferson Co. Ed. Svc. District | DIR. OF SPECIAL PROGRAMS | ADMINISTRATIVE | Part Time      | 18000.00      | 
| 2049 | Jefferson Co. Ed. Svc. District | SLP                      | CERTIFIED      | Part Time      | 20236.00      | 
| 2049 | Jefferson Co. Ed. Svc. District | SLP                      | CERTIFIED      | Full Time      | 42201.00      | 
| 2049 | Jefferson Co. Ed. Svc. District | SLP                      | CERTIFIED      | Full Time      | 42741.00      | 
| 2049 | Jefferson Co. Ed. Svc. District | SPED TEACHER             | CERTIFIED      | Full Time      | 43297.00      | 
| 2049 | Jefferson Co. Ed. Svc. District | PSYCHOLOGIST             | CERTIFIED      | Full Time      | 43959.00      | 
| 2049 | Jefferson Co. Ed. Svc. District | SLP                      | CERTIFIED      | Full Time      | 43959.00      | 
```