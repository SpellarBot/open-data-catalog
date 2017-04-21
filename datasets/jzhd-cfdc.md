# Salaries: ESD: Jefferson County: FY 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salaries-esd-jefferson-county-fy-2013-abf48) |
| Metadata | [Link](https://data.oregon.gov/api/views/jzhd-cfdc) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/jzhd-cfdc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/jzhd-cfdc/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | jzhd-cfdc |
| Name | Salaries: ESD: Jefferson County: FY 2013 |
| Category | Revenue & Expense |
| Tags | jefferson esd salaries, jefferson county esd salaries, jcesd salaries, esd salaries, jefferson co esd salaries |
| Created | 2013-11-12T18:47:35Z |
| Publication Date | 2013-11-12T18:50:29Z |

## Description

Summary of salaries for Jefferson County ESD for Fiscal Year 2013.

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
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:jzhd-cfdc d:2013-01-01T00:00:00.000Z t:esd_name="Jefferson Co. Ed. Svc. District" t:service_type=ADMINISTRATIVE t:classification=CFO t:full_part_time="Full Time" m:annual_salary=83000 m:esd=2049

series e:jzhd-cfdc d:2013-01-01T00:00:00.000Z t:esd_name="Jefferson Co. Ed. Svc. District" t:service_type=ADMINISTRATIVE t:classification="DIR. OF SPECIAL PROGRAMS" t:full_part_time="Part Time" m:annual_salary=18000 m:esd=2049

series e:jzhd-cfdc d:2013-01-01T00:00:00.000Z t:esd_name="Jefferson Co. Ed. Svc. District" t:service_type=ADMINISTRATIVE t:classification=SUPERINTENDENT t:full_part_time="Part Time" m:annual_salary=12000 m:esd=2049
```

## Meta Commands

```ls
metric m:esd p:integer l:ESD# t:dataTypeName=number

metric m:annual_salary p:double l:"Annual Salary" t:dataTypeName=money

entity e:jzhd-cfdc l:"Salaries: ESD: Jefferson County: FY 2013" t:url=https://data.oregon.gov/api/views/jzhd-cfdc

property e:jzhd-cfdc t:meta.view v:id=jzhd-cfdc v:category="Revenue & Expense" v:averageRating=0 v:name="Salaries: ESD: Jefferson County: FY 2013"

property e:jzhd-cfdc t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:jzhd-cfdc t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | esd_name                        | classification           | service_type   | full_part_time | annual_salary | 
| ==== | =============================== | ======================== | ============== | ============== | ============= | 
| 2049 | Jefferson Co. Ed. Svc. District | CFO                      | ADMINISTRATIVE | Full Time      | 83000.00      | 
| 2049 | Jefferson Co. Ed. Svc. District | DIR. OF SPECIAL PROGRAMS | ADMINISTRATIVE | Part Time      | 18000.00      | 
| 2049 | Jefferson Co. Ed. Svc. District | SUPERINTENDENT           | ADMINISTRATIVE | Part Time      | 12000.00      | 
| 2049 | Jefferson Co. Ed. Svc. District | INSPIRE TEACHER          | CERTIFIED      | Full Time      | 60976.73      | 
| 2049 | Jefferson Co. Ed. Svc. District | PSYCHOLOGIST             | CERTIFIED      | Full Time      | 48699.17      | 
| 2049 | Jefferson Co. Ed. Svc. District | PSYCHOLOGIST             | CERTIFIED      | Full Time      | 68230.55      | 
| 2049 | Jefferson Co. Ed. Svc. District | PSYCHOLOGIST             | CERTIFIED      | Full Time      | 46038.83      | 
| 2049 | Jefferson Co. Ed. Svc. District | SLP                      | CERTIFIED      | Full Time      | 50171.95      | 
| 2049 | Jefferson Co. Ed. Svc. District | SLP                      | CERTIFIED      | Full Time      | 62714.94      | 
| 2049 | Jefferson Co. Ed. Svc. District | SLP                      | CERTIFIED      | Full Time      | 41143.36      | 
```