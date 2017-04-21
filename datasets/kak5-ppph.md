# Salaries: ESD: Douglas: Fiscal Year 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salaries-esd-douglas-fiscal-year-2014-45b6f) |
| Metadata | [Link](https://data.oregon.gov/api/views/kak5-ppph) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/kak5-ppph/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/kak5-ppph/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | kak5-ppph |
| Name | Salaries: ESD: Douglas: Fiscal Year 2014 |
| Category | Revenue & Expense |
| Tags | salaries, esd, douglas, fiscal year 2014 |
| Created | 2014-12-11T22:21:40Z |
| Publication Date | 2014-12-29T05:49:39Z |

## Description

Salaries for Douglas ESD for Fiscal Year 2014

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| Yes      | series tag     | esd_id              | ESD ID              | text      | number      |
| Yes      | series tag     | esdname             | ESDName             | text      | text        |
| Yes      | series tag     | pstncd              | PstnCd              | text      | text        |
| Yes      | series tag     | position            | Position            | text      | text        |
| Yes      | numeric metric | number_of_employees | Number of Employees | number    | number      |
| Yes      | series tag     | fte                 | FTE                 | text      | text        |
| Yes      | numeric metric | amount_ftd          | Amount FTD          | money     | money       |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:kak5-ppph d:2014-01-01T00:00:00.000Z t:position="Administrative Assistant" t:fte="* 10.8750" t:esd_id=1980 t:esdname="Douglas Education Service District" m:number_of_employees=11 m:amount_ftd=371888.01

series e:kak5-ppph d:2014-01-01T00:00:00.000Z t:position="Assessment Support Specialist" t:fte="* 0.7500" t:esd_id=1980 t:esdname="Douglas Education Service District" m:number_of_employees=1 m:amount_ftd=25340.28

series e:kak5-ppph d:2014-01-01T00:00:00.000Z t:position="Assistant Director of Special Education/EI-ECSE" t:fte="* 1.0000" t:esd_id=1980 t:esdname="Douglas Education Service District" m:number_of_employees=1 m:amount_ftd=90522
```

## Meta Commands

```ls
metric m:number_of_employees p:integer l:"Number of Employees" t:dataTypeName=number

metric m:amount_ftd p:double l:"Amount FTD" t:dataTypeName=money

entity e:kak5-ppph l:"Salaries: ESD: Douglas: Fiscal Year 2014" t:url=https://data.oregon.gov/api/views/kak5-ppph

property e:kak5-ppph t:meta.view v:id=kak5-ppph v:category="Revenue & Expense" v:averageRating=0 v:name="Salaries: ESD: Douglas: Fiscal Year 2014"

property e:kak5-ppph t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:kak5-ppph t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd_id | esdname                            | pstncd | position                                        | number_of_employees | fte       | amount_ftd | 
| ====== | ================================== | ====== | =============================================== | =================== | ========= | ========== | 
| 1980   | Douglas Education Service District |        | Administrative Assistant                        | 11                  | * 10.8750 | 371888.01  | 
| 1980   | Douglas Education Service District |        | Assessment Support Specialist                   | 1                   | * 0.7500  | 25340.28   | 
| 1980   | Douglas Education Service District |        | Assistant Director of Special Education/EI-ECSE | 1                   | * 1.0000  | 90522.00   | 
| 1980   | Douglas Education Service District |        | Chief Financial Officer                         | 1                   | * 1.0000  | 96396.00   | 
| 1980   | Douglas Education Service District |        | Classified Substitute                           | 34                  | * 3.4728  | 86761.96   | 
| 1980   | Douglas Education Service District |        | Communications Specialist                       | 1                   | * 1.0000  | 4333.10    | 
| 1980   | Douglas Education Service District |        | Computer Technician                             | 3                   | * 2.2774  | 75979.71   | 
| 1980   | Douglas Education Service District |        | Coordinator-Human Resources                     | 1                   | * 1.0000  | 40400.00   | 
| 1980   | Douglas Education Service District |        | Coordinator-Program                             | 2                   | * 2.0000  | 157650.00  | 
| 1980   | Douglas Education Service District |        | Courier                                         | 1                   | * 0.3000  | 8682.20    | 
```