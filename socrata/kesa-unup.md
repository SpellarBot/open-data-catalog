# Salaries: ESD: Northwest Regional: Fiscal Year 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salaries-esd-northwest-regional-fiscal-year-2014-83bec) |
| Metadata | [Link](https://data.oregon.gov/api/views/kesa-unup) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/kesa-unup/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/kesa-unup/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | kesa-unup |
| Name | Salaries: ESD: Northwest Regional: Fiscal Year 2014 |
| Category | Revenue & Expense |
| Tags | salaries, esd, northwest regional, nw regional, fiscal year 2014 |
| Created | 2014-12-16T21:51:08Z |
| Publication Date | 2014-12-29T06:15:30Z |

## Description

Salaries for Northwest Regional ESD for Fiscal Year 2014

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | series tag     | esd_id         | ESD ID         | text      | number      |
| Yes      | series tag     | esdname        | ESDName        | text      | text        |
| Yes      | series tag     | classification | Classification | text      | text        |
| Yes      | series tag     | service_type   | Service Type   | text      | text        |
| Yes      | numeric metric | full_part_time | Full/Part Time | number    | number      |
| Yes      | numeric metric | annual_salary  | Annual Salary  | money     | money       |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:kesa-unup d:2014-01-01T00:00:00.000Z t:esd_id=2230 t:service_type="Certified Non-Admin" t:classification="ASD Specialist" t:esdname="NW Regional ESD" m:annual_salary=39618 m:full_part_time=1

series e:kesa-unup d:2014-01-01T00:00:00.000Z t:esd_id=2230 t:service_type="Certified Non-Admin" t:classification="Speech Pathologist" t:esdname="NW Regional ESD" m:annual_salary=74105 m:full_part_time=1

series e:kesa-unup d:2014-01-01T00:00:00.000Z t:esd_id=2230 t:service_type="Certified Non-Admin" t:classification="Speech Pathologist" t:esdname="NW Regional ESD" m:annual_salary=74105 m:full_part_time=1
```

## Meta Commands

```ls
metric m:full_part_time p:double l:"Full/Part Time" t:dataTypeName=number

metric m:annual_salary p:double l:"Annual Salary" t:dataTypeName=money

entity e:kesa-unup l:"Salaries: ESD: Northwest Regional: Fiscal Year 2014" t:url=https://data.oregon.gov/api/views/kesa-unup

property e:kesa-unup t:meta.view v:id=kesa-unup v:category="Revenue & Expense" v:averageRating=0 v:name="Salaries: ESD: Northwest Regional: Fiscal Year 2014"

property e:kesa-unup t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:kesa-unup t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd_id | esdname         | classification            | service_type        | full_part_time | annual_salary | 
| ====== | =============== | ========================= | =================== | ============== | ============= | 
| 2230   | NW Regional ESD | ASD Specialist            | Certified Non-Admin | 1              | 39618.00      | 
| 2230   | NW Regional ESD | Speech Pathologist        | Certified Non-Admin | 1              | 74105.00      | 
| 2230   | NW Regional ESD | Speech Pathologist        | Certified Non-Admin | 1              | 74105.00      | 
| 2230   | NW Regional ESD | Administrative Asst l     | Classified          | 1              | 31700.00      | 
| 2230   | NW Regional ESD | School Psychologist       | Certified Non-Admin | 0.1            | 7410.50       | 
| 2230   | NW Regional ESD | School Improve Specialist | Certified Admin     | 0.5            | 41527.50      | 
| 2230   | NW Regional ESD | Teacher                   | Certified Non-Admin | 1              | 72298.00      | 
| 2230   | NW Regional ESD | Accounting Manager        | Certified Admin     | 1              | 80936.00      | 
| 2230   | NW Regional ESD | Chief Financial Officer   | Certified Admin     | 1              | 131954.06     | 
| 2230   | NW Regional ESD | Teacher, Vision Impaired  | Certified Non-Admin | 1              | 71227.00      | 
```