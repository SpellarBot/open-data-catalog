# Salaries: ESD: Northwest Regional: Fiscal Year 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salaries-esd-northwest-regional-fiscal-year-2013-7b5dc) |
| Metadata | [Link](https://data.oregon.gov/api/views/qdwk-qyz8) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/qdwk-qyz8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/qdwk-qyz8/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | qdwk-qyz8 |
| Name | Salaries: ESD: Northwest Regional: Fiscal Year 2013 |
| Category | Revenue & Expense |
| Tags | salaries, esd, northwest regional, nw regional, fiscal year 2013 |
| Created | 2013-11-04T20:16:07Z |
| Publication Date | 2013-11-04T20:18:58Z |

## Description

Salaries for Northwest Regional ESD for Fiscal Year 2013

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type | Render Type |
| ======== | =========== | ============== | ============== | ========= | =========== |
| Yes      | series tag  | esd_id         | ESD ID         | text      | number      |
| Yes      | series tag  | esdname        | ESDName        | text      | text        |
| Yes      | series tag  | classification | Classification | text      | text        |
| Yes      | series tag  | service_type   | Service Type   | text      | text        |
| Yes      | series tag  | full_part_time | Full/Part Time | text      | text        |
| Yes      | series tag  | annual_salary  | Annual Salary  | text      | text        |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:qdwk-qyz8 d:2013-01-01T00:00:00.000Z t:annual_salary="* 44,844.00" t:esd_id=2230 t:service_type=Classified t:classification=Accountant t:esdname="NW Regional ESD" t:full_part_time="Full Time" m:row_number.qdwk-qyz8=1

series e:qdwk-qyz8 d:2013-01-01T00:00:00.000Z t:annual_salary="* 80,134.00" t:esd_id=2230 t:service_type=Administrators t:classification="Accounting Manager" t:esdname="NW Regional ESD" t:full_part_time="Full Time" m:row_number.qdwk-qyz8=2

series e:qdwk-qyz8 d:2013-01-01T00:00:00.000Z t:annual_salary="* 78,951.00" t:esd_id=2230 t:service_type=Administrators t:classification="Accounting Manager" t:esdname="NW Regional ESD" t:full_part_time="Full Time" m:row_number.qdwk-qyz8=3
```

## Meta Commands

```ls
metric m:row_number.qdwk-qyz8 p:long l:"Row Number"

entity e:qdwk-qyz8 l:"Salaries: ESD: Northwest Regional: Fiscal Year 2013" t:url=https://data.oregon.gov/api/views/qdwk-qyz8

property e:qdwk-qyz8 t:meta.view v:id=qdwk-qyz8 v:category="Revenue & Expense" v:averageRating=0 v:name="Salaries: ESD: Northwest Regional: Fiscal Year 2013"

property e:qdwk-qyz8 t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:qdwk-qyz8 t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd_id | esdname         | classification        | service_type   | full_part_time | annual_salary | 
| ====== | =============== | ===================== | ============== | ============== | ============= | 
| 2230   | NW Regional ESD | Accountant            | Classified     | Full Time      | * 44,844.00   | 
| 2230   | NW Regional ESD | Accounting Manager    | Administrators | Full Time      | * 80,134.00   | 
| 2230   | NW Regional ESD | Accounting Manager    | Administrators | Full Time      | * 78,951.00   | 
| 2230   | NW Regional ESD | Accounting Manager    | Administrators | Full Time      | * 76,634.00   | 
| 2230   | NW Regional ESD | Accounts Payable      | Classified     | Full Time      | * 34,925.80   | 
| 2230   | NW Regional ESD | Accounts Receivable   | Classified     | Full Time      | * 36,299.40   | 
| 2230   | NW Regional ESD | Admin Asst 1          | Classified     | Full Time      | * 21,396.09   | 
| 2230   | NW Regional ESD | Admin Asst 2          | Classified     | Full Time      | * 34,925.80   | 
| 2230   | NW Regional ESD | Administrative Asst 1 | Classified     | Part Time      | * 8,734.28    | 
| 2230   | NW Regional ESD | Administrative Asst 1 | Classified     | Part Time      | * 17,881.24   | 
```