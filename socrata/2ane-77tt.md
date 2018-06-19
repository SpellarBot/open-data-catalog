# Salaries: ESD: Lane: FY 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salaries-esd-lane-fy-2013-681de) |
| Metadata | [Link](https://data.oregon.gov/api/views/2ane-77tt) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/2ane-77tt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/2ane-77tt/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 2ane-77tt |
| Name | Salaries: ESD: Lane: FY 2013 |
| Category | Revenue & Expense |
| Tags | lane esd salaries, lane esd, esd salaries |
| Created | 2013-11-12T18:53:57Z |
| Publication Date | 2013-11-12T18:57:09Z |

## Description

Summary of salaries for Lane ESD for Fiscal Year 2013.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| Yes      | numeric metric | esd                  | ESD #                | number    | number      |
| Yes      | series tag     | esd_name             | ESD Name             | text      | text        |
| Yes      | series tag     | position             | Position             | text      | text        |
| Yes      | numeric metric | number_of_employees  | NUMBER OF Employees  | number    | number      |
| Yes      | numeric metric | total_fte            | Total FTE            | number    | number      |
| Yes      | series tag     | total_salaries_wages | TOTAL Salaries/Wages | text      | text        |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:2ane-77tt d:2013-01-01T00:00:00.000Z t:position=SUPERINTENDENT t:esd_name="LANE EDUCATION SERVICE DISTRICT" t:total_salaries_wages="* 120,000.00" m:number_of_employees=1 m:esd=2064 m:total_fte=1

series e:2ane-77tt d:2013-01-01T00:00:00.000Z t:position="ASSISTANT SUPERINTENDENT" t:esd_name="LANE EDUCATION SERVICE DISTRICT" t:total_salaries_wages="* 105,836.00" m:number_of_employees=1 m:esd=2064 m:total_fte=1

series e:2ane-77tt d:2013-01-01T00:00:00.000Z t:position="LIBRARY/MEDIA SPECIALIST" t:esd_name="LANE EDUCATION SERVICE DISTRICT" t:total_salaries_wages="* 40,787.00" m:number_of_employees=1 m:esd=2064 m:total_fte=1
```

## Meta Commands

```ls
metric m:esd p:integer l:"ESD #" t:dataTypeName=number

metric m:number_of_employees p:integer l:"NUMBER OF Employees" t:dataTypeName=number

metric m:total_fte p:float l:"Total FTE" t:dataTypeName=number

entity e:2ane-77tt l:"Salaries: ESD: Lane: FY 2013" t:url=https://data.oregon.gov/api/views/2ane-77tt

property e:2ane-77tt t:meta.view v:id=2ane-77tt v:category="Revenue & Expense" v:averageRating=0 v:name="Salaries: ESD: Lane: FY 2013"

property e:2ane-77tt t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:2ane-77tt t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | esd_name                        | position                                        | number_of_employees | total_fte | total_salaries_wages | 
| ==== | =============================== | =============================================== | =================== | ========= | ==================== | 
| 2064 | LANE EDUCATION SERVICE DISTRICT | SUPERINTENDENT                                  | 1                   | 1.0       | * 120,000.00         | 
| 2064 | LANE EDUCATION SERVICE DISTRICT | ASSISTANT SUPERINTENDENT                        | 1                   | 1.0       | * 105,836.00         | 
| 2064 | LANE EDUCATION SERVICE DISTRICT | LIBRARY/MEDIA SPECIALIST                        | 1                   | 1.0       | * 40,787.00          | 
| 2064 | LANE EDUCATION SERVICE DISTRICT | OTHER LICENSED STAFF, NON-SPECIAL ED            | 5                   | 4.7       | * 280,826.08         | 
| 2064 | LANE EDUCATION SERVICE DISTRICT | DISTRICT SUPPORT (NON-LICENSED, NON-SPECIAL ED) | 2                   | 2.0       | * 100,567.72         | 
| 2064 | LANE EDUCATION SERVICE DISTRICT | SCHOOL SUPPORT (NON-LICENSED, NON-SPECIAL ED)   | 4                   | 3.9       | * 157,315.48         | 
| 2064 | LANE EDUCATION SERVICE DISTRICT | LIBRARY/MEDIA SUPPORT                           | 1                   | 1.0       | * 33,655.44          | 
| 2064 | LANE EDUCATION SERVICE DISTRICT | OTHER NON-LICENSED STAFF, NON-SPECIAL ED        | 27                  | 23.8      | * 1,199,297.69       | 
| 2064 | LANE EDUCATION SERVICE DISTRICT | SPECIAL EDUCATION TEACHER (NON-PE)              | 43                  | 42.4      | * 1,995,656.96       | 
| 2064 | LANE EDUCATION SERVICE DISTRICT | SPECIAL EDUCATION SPEECH PATHOLOGIST            | 9                   | 8.9       | * 514,616.94         | 
```