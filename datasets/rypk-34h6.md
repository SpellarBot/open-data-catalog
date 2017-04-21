# Salaries: ESD: Lane: Fiscal Year 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salaries-esd-lane-fiscal-year-2014-0a464) |
| Metadata | [Link](https://data.oregon.gov/api/views/rypk-34h6) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/rypk-34h6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/rypk-34h6/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | rypk-34h6 |
| Name | Salaries: ESD: Lane: Fiscal Year 2014 |
| Category | Revenue & Expense |
| Tags | lane esd salaries, lane esd, esd salaries 2014 |
| Created | 2014-12-16T17:12:13Z |
| Publication Date | 2014-12-29T05:59:47Z |

## Description

Summary of salaries for Lane ESD for Fiscal Year 2014.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| Yes      | numeric metric | esd                  | ESD#                 | number    | number      |
| Yes      | series tag     | esd_name             | ESD NAME             | text      | text        |
| Yes      | series tag     | position             | POSITION             | text      | text        |
| Yes      | numeric metric | number_of_employees  | NUMBER OF EMPLOYEES  | number    | number      |
| Yes      | numeric metric | total_fte            | TOTAL FTE            | number    | number      |
| Yes      | numeric metric | total_salaries_wages | TOTAL SALARIES/WAGES | money     | money       |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:rypk-34h6 d:2014-01-01T00:00:00.000Z t:position=SUPERINTENDENT t:esd_name="LANE EDUCATION SERVICE DISTRICT" m:number_of_employees=1 m:esd=2064 m:total_salaries_wages=120000 m:total_fte=1

series e:rypk-34h6 d:2014-01-01T00:00:00.000Z t:position="ASSISTANT SUPERINTENDENT" t:esd_name="LANE EDUCATION SERVICE DISTRICT" m:number_of_employees=1 m:esd=2064 m:total_salaries_wages=105836 m:total_fte=1

series e:rypk-34h6 d:2014-01-01T00:00:00.000Z t:position="INSTRUCTIONAL COORDINATOR/SUPERVISOR" t:esd_name="LANE EDUCATION SERVICE DISTRICT" m:number_of_employees=1 m:esd=2064 m:total_salaries_wages=83915 m:total_fte=0.6
```

## Meta Commands

```ls
metric m:esd p:integer l:ESD# t:dataTypeName=number

metric m:number_of_employees p:integer l:"NUMBER OF EMPLOYEES" t:dataTypeName=number

metric m:total_fte p:float l:"TOTAL FTE" t:dataTypeName=number

metric m:total_salaries_wages p:double l:"TOTAL SALARIES/WAGES" t:dataTypeName=money

entity e:rypk-34h6 l:"Salaries: ESD: Lane: Fiscal Year 2014" t:url=https://data.oregon.gov/api/views/rypk-34h6

property e:rypk-34h6 t:meta.view v:id=rypk-34h6 v:category="Revenue & Expense" v:averageRating=0 v:name="Salaries: ESD: Lane: Fiscal Year 2014"

property e:rypk-34h6 t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:rypk-34h6 t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | esd_name                        | position                                        | number_of_employees | total_fte | total_salaries_wages | 
| ==== | =============================== | =============================================== | =================== | ========= | ==================== | 
| 2064 | LANE EDUCATION SERVICE DISTRICT | SUPERINTENDENT                                  | 1                   | 1.0       | 120000               | 
| 2064 | LANE EDUCATION SERVICE DISTRICT | ASSISTANT SUPERINTENDENT                        | 1                   | 1.0       | 105836               | 
| 2064 | LANE EDUCATION SERVICE DISTRICT | INSTRUCTIONAL COORDINATOR/SUPERVISOR            | 1                   | 0.6       | 83915                | 
| 2064 | LANE EDUCATION SERVICE DISTRICT | LIBRARY/MEDIA SPECIALIST                        | 1                   | 1.0       | 42529                | 
| 2064 | LANE EDUCATION SERVICE DISTRICT | OTHER LICENSED STAFF, NON-SPECIAL ED            | 3                   | 3.0       | 197321               | 
| 2064 | LANE EDUCATION SERVICE DISTRICT | DISTRICT SUPPORT (NON-LICENSED, NON-SPECIAL ED) | 1                   | 1.0       | 57078                | 
| 2064 | LANE EDUCATION SERVICE DISTRICT | SCHOOL SUPPORT (NON-LICENSED, NON-SPECIAL ED)   | 7                   | 6.6       | 236996.576           | 
| 2064 | LANE EDUCATION SERVICE DISTRICT | OTHER NON-LICENSED STAFF, NON-SPECIAL ED        | 23                  | 19.4      | 979802.26320000004   | 
| 2064 | LANE EDUCATION SERVICE DISTRICT | SPECIAL EDUCATION TEACHER (NON-PE)              | 25                  | 24.5      | 1244218              | 
| 2064 | LANE EDUCATION SERVICE DISTRICT | SPECIAL EDUCATION SPEECH PATHOLOGIST            | 7                   | 5.7       | 400893               | 
```