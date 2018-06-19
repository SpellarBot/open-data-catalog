# Salaries: ESD: LBL: FY2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salaries-esd-lbl-fy2013-c0c5d) |
| Metadata | [Link](https://data.oregon.gov/api/views/ye35-yhsz) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/ye35-yhsz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/ye35-yhsz/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | ye35-yhsz |
| Name | Salaries: ESD: LBL: FY2013 |
| Category | Revenue & Expense |
| Tags | esd, esd salaries, lbl esd salaries, lbl esd, linn benton lincoln esd |
| Created | 2013-12-02T22:43:36Z |
| Publication Date | 2013-12-02T22:46:44Z |

## Description

Summary of salaries for Linn, Benton, Lincoln ESD for Fiscal Year 2013

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
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ye35-yhsz d:2013-01-01T00:00:00.000Z t:position=Superintendent t:esd_id=2098 t:esdname="Linn Benton Lincoln ESD" t:total_fte="* 1.0000" m:number_of_employees=1 m:pstncd=1 m:total_salary_wages=152113

series e:ye35-yhsz d:2013-01-01T00:00:00.000Z t:position="Deputy Superintendent" t:esd_id=2098 t:esdname="Linn Benton Lincoln ESD" t:total_fte="* 1.0000" m:number_of_employees=1 m:pstncd=2 m:total_salary_wages=127375

series e:ye35-yhsz d:2013-01-01T00:00:00.000Z t:position="Instructional Coordinator/Supervisor, Non-Special Ed" t:esd_id=2098 t:esdname="Linn Benton Lincoln ESD" t:total_fte="* 3.0000" m:number_of_employees=3 m:pstncd=6 m:total_salary_wages=288984
```

## Meta Commands

```ls
metric m:pstncd p:integer l:PstnCd t:dataTypeName=number

metric m:number_of_employees p:integer l:"Number of Employees" t:dataTypeName=number

metric m:total_salary_wages p:double l:"Total Salary/Wages" t:dataTypeName=money

entity e:ye35-yhsz l:"Salaries: ESD: LBL: FY2013" t:url=https://data.oregon.gov/api/views/ye35-yhsz

property e:ye35-yhsz t:meta.view v:id=ye35-yhsz v:category="Revenue & Expense" v:averageRating=0 v:name="Salaries: ESD: LBL: FY2013"

property e:ye35-yhsz t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:ye35-yhsz t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd_id | esdname                 | pstncd | position                                                 | number_of_employees | total_fte | total_salary_wages | 
| ====== | ======================= | ====== | ======================================================== | =================== | ========= | ================== | 
| 2098   | Linn Benton Lincoln ESD | 1      | Superintendent                                           | 1                   | * 1.0000  | 152113.00          | 
| 2098   | Linn Benton Lincoln ESD | 2      | Deputy Superintendent                                    | 1                   | * 1.0000  | 127375.00          | 
| 2098   | Linn Benton Lincoln ESD | 6      | Instructional Coordinator/Supervisor, Non-Special Ed     | 3                   | * 3.0000  | 288984.00          | 
| 2098   | Linn Benton Lincoln ESD | 7      | Psychologist, Non-Special Ed                             | 12                  | * 11.6014 | 687096.20          | 
| 2098   | Linn Benton Lincoln ESD | 8      | Teacher, Non-Special Ed                                  | 2                   | * 2.0000  | 97538.59           | 
| 2098   | Linn Benton Lincoln ESD | 9      | Library/Media Specialist                                 | 1                   | * 0.6379  | 42326.49           | 
| 2098   | Linn Benton Lincoln ESD | 11     | Other Licensed Staff, Non-Special Ed                     | 20                  | * 17.3493 | 830845.17          | 
| 2098   | Linn Benton Lincoln ESD | 16     | Paraprofessional (Educational Assistant), Non-Special Ed | 7                   | * 5.5722  | 161465.15          | 
| 2098   | Linn Benton Lincoln ESD | 17     | District Support (Non-Licensed, Non-Special Ed)          | 14                  | * 12.9425 | 467365.80          | 
| 2098   | Linn Benton Lincoln ESD | 21     | Other Non-Licensed staff, Non-Special Ed                 | 69                  | * 62.7919 | 2988193.80         | 
```