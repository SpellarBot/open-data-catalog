# Salaries: ESD: High Desert: Fiscal Year 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salaries-esd-high-desert-fiscal-year-2013-fa720) |
| Metadata | [Link](https://data.oregon.gov/api/views/tacf-dqwb) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/tacf-dqwb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/tacf-dqwb/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | tacf-dqwb |
| Name | Salaries: ESD: High Desert: Fiscal Year 2013 |
| Category | Revenue & Expense |
| Tags | salaries, esd, high desert, fiscal year 2013 |
| Created | 2013-10-31T18:06:36Z |
| Publication Date | 2013-10-31T18:11:49Z |

## Description

Salaries for High Desert ESD for Fiscal Year 2013

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | series tag     | state_code             | State Code             | text      | number      |
| Yes      | series tag     | state_code_description | State Code Description | text      | text        |
| Yes      | series tag     | countofname            | CountOfName            | text      | text        |
| Yes      | numeric metric | sumoffte               | SumOfFTE               | number    | number      |
| Yes      | numeric metric | sumofamount            | SumOfAmount            | number    | number      |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:tacf-dqwb d:2013-01-01T00:00:00.000Z t:state_code=1 t:countofname="* 1" t:state_code_description=Superintendent m:sumofamount=133840 m:sumoffte=1

series e:tacf-dqwb d:2013-01-01T00:00:00.000Z t:state_code=2 t:countofname="* 1" t:state_code_description="Assistant Superintendent" m:sumofamount=120460 m:sumoffte=1

series e:tacf-dqwb d:2013-01-01T00:00:00.000Z t:state_code=6 t:countofname="* 3" t:state_code_description="Instructional Coordinator/Supervisor, Non-Special" m:sumofamount=137582.08 m:sumoffte=2
```

## Meta Commands

```ls
metric m:sumoffte p:float l:SumOfFTE t:dataTypeName=number

metric m:sumofamount p:float l:SumOfAmount t:dataTypeName=number

entity e:tacf-dqwb l:"Salaries: ESD: High Desert: Fiscal Year 2013" t:url=https://data.oregon.gov/api/views/tacf-dqwb

property e:tacf-dqwb t:meta.view v:id=tacf-dqwb v:category="Revenue & Expense" v:averageRating=0 v:name="Salaries: ESD: High Desert: Fiscal Year 2013"

property e:tacf-dqwb t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:tacf-dqwb t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| state_code | state_code_description                            | countofname | sumoffte | sumofamount        | 
| ========== | ================================================= | =========== | ======== | ================== | 
| 1          | Superintendent                                    | * 1         | 1        | 133840             | 
| 2          | Assistant Superintendent                          | * 1         | 1        | 120460             | 
| 6          | Instructional Coordinator/Supervisor, Non-Special | * 3         | 2        | 137582.07999999999 | 
| 11         | Other Licensed Staff, Non-Special Ed              | * 9         | 7.675    | 583773.76          | 
| 17         | District Support (Non-Licensed, Non-Special Ed)   | * 35        | 28.619   | 1460971.33         | 
| 18         | School Support (Non-Licensed, Non-Special Ed)     | * 1         | 1        | 31721.759999999998 | 
| 21         | Other Non-Licensed Staff, Non-Special Ed          | * 25        | 19.1125  | 561471.16          | 
| 22         | Special Education Teacher (Non-PE)                | * 36        | 30.3875  | 1517987.8          | 
| 24         | Special Education Audiologist                     | * 1         | 0.75     | 44798.76           | 
| 25         | Special Education Speech Pathologist              | * 13        | 8.3      | 403052.43          | 
```