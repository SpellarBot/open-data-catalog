# Salaries: ESD: Columbia Gorge; Fiscal Year 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salaries-esd-columbia-gorge-fiscal-year-2013-35d98) |
| Metadata | [Link](https://data.oregon.gov/api/views/hszj-wj88) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/hszj-wj88/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/hszj-wj88/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | hszj-wj88 |
| Name | Salaries: ESD: Columbia Gorge; Fiscal Year 2013 |
| Category | Revenue & Expense |
| Tags | salaries, esd, columbia gorge, fiscal year 2013 |
| Created | 2013-10-22T15:45:52Z |
| Publication Date | 2013-10-23T23:20:00Z |

## Description

Salaries for Columbia Gorge ESD for Fiscal Year 2013

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| Yes      | numeric metric | esd                 | ESD #               | number    | number      |
| Yes      | series tag     | esd_name            | ESD NAME            | text      | text        |
| Yes      | series tag     | classification      | CLASSIFICATION      | text      | text        |
| Yes      | numeric metric | number_of_employees | NUMBER OF EMPLOYEES | number    | number      |
| Yes      | numeric metric | total_fte           | TOTAL FTE           | number    | number      |
| Yes      | numeric metric | total_salary        | TOTAL SALARY        | money     | money       |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:hszj-wj88 d:2013-01-01T00:00:00.000Z t:esd_name="Columbia Gorge Education Service District" t:classification=Superintendent m:number_of_employees=1 m:total_salary=67357 m:esd=2223 m:total_fte=0.65

series e:hszj-wj88 d:2013-01-01T00:00:00.000Z t:esd_name="Columbia Gorge Education Service District" t:classification="Instructional Coordinators and Supervisors" m:number_of_employees=1 m:total_salary=79638 m:esd=2223 m:total_fte=1

series e:hszj-wj88 d:2013-01-01T00:00:00.000Z t:esd_name="Columbia Gorge Education Service District" t:classification="Other Licensed Staff" m:number_of_employees=2 m:total_salary=62307 m:esd=2223 m:total_fte=0.94
```

## Meta Commands

```ls
metric m:esd p:integer l:"ESD #" t:dataTypeName=number

metric m:number_of_employees p:integer l:"NUMBER OF EMPLOYEES" t:dataTypeName=number

metric m:total_fte p:float l:"TOTAL FTE" t:dataTypeName=number

metric m:total_salary p:integer l:"TOTAL SALARY" t:dataTypeName=money

entity e:hszj-wj88 l:"Salaries: ESD: Columbia Gorge; Fiscal Year 2013" t:url=https://data.oregon.gov/api/views/hszj-wj88

property e:hszj-wj88 t:meta.view v:id=hszj-wj88 v:category="Revenue & Expense" v:averageRating=0 v:name="Salaries: ESD: Columbia Gorge; Fiscal Year 2013"

property e:hszj-wj88 t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:hszj-wj88 t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | esd_name                                  | classification                                                       | number_of_employees | total_fte | total_salary | 
| ==== | ========================================= | ==================================================================== | =================== | ========= | ============ | 
| 2223 | Columbia Gorge Education Service District | Superintendent                                                       | 1                   | 0.65      | 67357        | 
| 2223 | Columbia Gorge Education Service District | Instructional Coordinators and Supervisors                           | 1                   | 1         | 79638        | 
| 2223 | Columbia Gorge Education Service District | Other Licensed Staff                                                 | 2                   | 0.94      | 62307        | 
| 2223 | Columbia Gorge Education Service District | District Support (District Level Clerical Support to Administrators) | 4                   | 3.14      | 173025       | 
| 2223 | Columbia Gorge Education Service District | Student Support (Supervisors of Student Support Staff)               | 5                   | 3.15      | 76207        | 
| 2223 | Columbia Gorge Education Service District | Other Non-Licensed Staff                                             | 7                   | 4.76      | 265791       | 
| 2223 | Columbia Gorge Education Service District | Special Education Teacher                                            | 1                   | 0.95      | 34836        | 
| 2223 | Columbia Gorge Education Service District | Special Education Speech Pathologist                                 | 2                   | 1.45      | 79705        | 
| 2223 | Columbia Gorge Education Service District | Special Education Occupational Therapist                             | 1                   | 0.74      | 44150        | 
| 2223 | Columbia Gorge Education Service District | Special EducationMedical and Nursing Staff                           | 1                   | 0.7       | 45604        | 
```