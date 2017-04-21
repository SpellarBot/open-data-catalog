# Salaries: ESD: LBL (Linn, Benton, Lincoln) Fiscal Year 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salaries-esd-lbl-linn-benton-lincoln-fiscal-year-2014-cad8f) |
| Metadata | [Link](https://data.oregon.gov/api/views/rvsz-c7z6) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/rvsz-c7z6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/rvsz-c7z6/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | rvsz-c7z6 |
| Name | Salaries: ESD: LBL (Linn, Benton, Lincoln) Fiscal Year 2014 |
| Category | Revenue & Expense |
| Tags | esd, esd salaries, lbl esd salaries, lbl esd, linn benton lincoln esd, 2014 |
| Created | 2014-12-16T21:01:27Z |
| Publication Date | 2014-12-29T06:11:53Z |

## Description

Summary of salaries for ESD: Linn, Benton, and Lincoln for Fiscal Year 2014

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| Yes      | series tag     | esd_id              | ESD ID              | text      | number      |
| Yes      | series tag     | esdname             | ESDName             | text      | text        |
| Yes      | numeric metric | pstncd              | PstnCd              | number    | number      |
| Yes      | series tag     | position            | Position            | text      | text        |
| Yes      | numeric metric | number_of_employees | Number of Employees | number    | number      |
| Yes      | series tag     | total_fte           | Total FTE           | text      | text        |
| Yes      | numeric metric | total_salary_wages  | Total Salary/Wages  | money     | money       |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:rvsz-c7z6 d:2014-01-01T00:00:00.000Z t:position=Superintendent t:esd_id=2098 t:esdname="Linn Benton Lincoln ESD" t:total_fte="* 1.0000" m:number_of_employees=1 m:pstncd=1 m:total_salary_wages=156676.89

series e:rvsz-c7z6 d:2014-01-01T00:00:00.000Z t:position="Deputy Superintendent" t:esd_id=2098 t:esdname="Linn Benton Lincoln ESD" t:total_fte="* 1.0000" m:number_of_employees=1 m:pstncd=2 m:total_salary_wages=132470

series e:rvsz-c7z6 d:2014-01-01T00:00:00.000Z t:position="Instructional Coordinator/Supervisor, Non-Special Ed" t:esd_id=2098 t:esdname="Linn Benton Lincoln ESD" t:total_fte="* 2.0000" m:number_of_employees=2 m:pstncd=6 m:total_salary_wages=200590
```

## Meta Commands

```ls
metric m:pstncd p:integer l:PstnCd t:dataTypeName=number

metric m:number_of_employees p:integer l:"Number of Employees" t:dataTypeName=number

metric m:total_salary_wages p:double l:"Total Salary/Wages" t:dataTypeName=money

entity e:rvsz-c7z6 l:"Salaries: ESD: LBL (Linn, Benton, Lincoln) Fiscal Year 2014" t:url=https://data.oregon.gov/api/views/rvsz-c7z6

property e:rvsz-c7z6 t:meta.view v:id=rvsz-c7z6 v:category="Revenue & Expense" v:averageRating=0 v:name="Salaries: ESD: LBL (Linn, Benton, Lincoln) Fiscal Year 2014"

property e:rvsz-c7z6 t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:rvsz-c7z6 t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd_id | esdname                 | pstncd | position                                                 | number_of_employees | total_fte | total_salary_wages | 
| ====== | ======================= | ====== | ======================================================== | =================== | ========= | ================== | 
| 2098   | Linn Benton Lincoln ESD | 1      | Superintendent                                           | 1                   | * 1.0000  | 156676.89          | 
| 2098   | Linn Benton Lincoln ESD | 2      | Deputy Superintendent                                    | 1                   | * 1.0000  | 132470.00          | 
| 2098   | Linn Benton Lincoln ESD | 6      | Instructional Coordinator/Supervisor, Non-Special Ed     | 2                   | * 2.0000  | 200590.00          | 
| 2098   | Linn Benton Lincoln ESD | 7      | Psychologist, Non-Special Ed                             | 13                  | * 12.1070 | 769194.08          | 
| 2098   | Linn Benton Lincoln ESD | 8      | Teacher, Non-Special Ed                                  | 1                   | * 1.0000  | 58386.58           | 
| 2098   | Linn Benton Lincoln ESD | 11     | Other Licensed Staff, Non-Special Ed                     | 12                  | * 11.3520 | 660081.43          | 
| 2098   | Linn Benton Lincoln ESD | 16     | Paraprofessional (Educational Assistant), Non-Special Ed | 9                   | * 7.1106  | 198242.75          | 
| 2098   | Linn Benton Lincoln ESD | 21     | Other Non-Licensed staff, Non-Special Ed                 | 75                  | * 71.5090 | 2690128.32         | 
| 2098   | Linn Benton Lincoln ESD | 22     | Special Education Teacher (Non-PE)                       | 22                  | * 12.0050 | 724436.57          | 
| 2098   | Linn Benton Lincoln ESD | 24     | Special Education Audiologist                            | 1                   | * 1.0000  | 63067.08           | 
```