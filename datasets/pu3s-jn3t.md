# Salaries: ESD: Columbia Gorge; Fiscal Year 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salaries-esd-columbia-gorge-fiscal-year-2014-96c23) |
| Metadata | [Link](https://data.oregon.gov/api/views/pu3s-jn3t) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/pu3s-jn3t/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/pu3s-jn3t/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | pu3s-jn3t |
| Name | Salaries: ESD: Columbia Gorge; Fiscal Year 2014 |
| Category | Revenue & Expense |
| Tags | salaries, esd, columbia gorge, fiscal year 2014 |
| Created | 2014-12-16T19:22:05Z |
| Publication Date | 2014-12-29T06:08:45Z |

## Description

Salaries for Columbia Gorge ESD for Fiscal Year 2014

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| Yes      | series tag     | esd_id              | ESD ID              | text      | number      |
| Yes      | series tag     | esdname             | ESDName             | text      | text        |
| Yes      | numeric metric | pstncd              | PstnCd              | number    | number      |
| Yes      | series tag     | position            | Position            | text      | text        |
| Yes      | numeric metric | number_of_employees | Number of Employees | number    | number      |
| Yes      | numeric metric | total_fte           | Total FTE           | number    | number      |
| Yes      | numeric metric | total_salary_wages  | Total Salary/ Wages | money     | money       |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:pu3s-jn3t d:2014-01-01T00:00:00.000Z t:position=Superintenent t:esd_id=2223 t:esdname="Columbia Gorge ESD" m:number_of_employees=1 m:pstncd=1 m:total_salary_wages=51813 m:total_fte=0.49

series e:pu3s-jn3t d:2014-01-01T00:00:00.000Z t:position="Assistant Superintendent" t:esd_id=2223 t:esdname="Columbia Gorge ESD" m:number_of_employees=1 m:pstncd=2 m:total_salary_wages=105000 m:total_fte=0.98

series e:pu3s-jn3t d:2014-01-01T00:00:00.000Z t:position="Head Teacher" t:esd_id=2223 t:esdname="Columbia Gorge ESD" m:number_of_employees=1 m:pstncd=5 m:total_salary_wages=34765 m:total_fte=0.88
```

## Meta Commands

```ls
metric m:pstncd p:integer l:PstnCd t:dataTypeName=number

metric m:number_of_employees p:integer l:"Number of Employees" t:dataTypeName=number

metric m:total_fte p:float l:"Total FTE" t:dataTypeName=number

metric m:total_salary_wages p:integer l:"Total Salary/ Wages" t:dataTypeName=money

entity e:pu3s-jn3t l:"Salaries: ESD: Columbia Gorge; Fiscal Year 2014" t:url=https://data.oregon.gov/api/views/pu3s-jn3t

property e:pu3s-jn3t t:meta.view v:id=pu3s-jn3t v:category="Revenue & Expense" v:averageRating=0 v:name="Salaries: ESD: Columbia Gorge; Fiscal Year 2014"

property e:pu3s-jn3t t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:pu3s-jn3t t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd_id | esdname            | pstncd | position                                                             | number_of_employees | total_fte | total_salary_wages | 
| ====== | ================== | ====== | ==================================================================== | =================== | ========= | ================== | 
| 2223   | Columbia Gorge ESD | 1      | Superintenent                                                        | 1                   | 0.49      | 51813              | 
| 2223   | Columbia Gorge ESD | 2      | Assistant Superintendent                                             | 1                   | 0.98      | 105000             | 
| 2223   | Columbia Gorge ESD | 5      | Head Teacher                                                         | 1                   | 0.88      | 34765              | 
| 2223   | Columbia Gorge ESD | 16     | Paraprofessional (Educational Assistants)                            | 3                   | 0.53      | 14246              | 
| 2223   | Columbia Gorge ESD | 17     | District Support (District Level Clerical Support to Administrators) | 3                   | 1.93      | 81267              | 
| 2223   | Columbia Gorge ESD | 19     | Student Support (Supervisors of Student Support Functions)           | 5                   | 2.60      | 64219              | 
| 2223   | Columbia Gorge ESD | 21     | Other Non-Licensed Staff                                             | 8                   | 6.25      | 399066             | 
| 2223   | Columbia Gorge ESD | 22     | Special Education Teacher                                            | 1                   | 1.00      | 34036              | 
| 2223   | Columbia Gorge ESD | 25     | Special Education Speech Pathologist                                 | 3                   | 2.40      | 120107             | 
| 2223   | Columbia Gorge ESD | 28     | Special Educational Occupational Therapist                           | 1                   | 0.75      | 47147              | 
```