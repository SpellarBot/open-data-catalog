# Salaries: ESD: InterMountain: Fiscal Year 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salaries-esd-intermountain-fiscal-year-2013-ca849) |
| Metadata | [Link](https://data.oregon.gov/api/views/ctku-jg66) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/ctku-jg66/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/ctku-jg66/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | ctku-jg66 |
| Name | Salaries: ESD: InterMountain: Fiscal Year 2013 |
| Category | Revenue & Expense |
| Tags | salaries, esd, intermountain, fiscal year 2013 |
| Created | 2013-10-31T18:33:40Z |
| Publication Date | 2013-10-31T18:35:52Z |

## Description

Salaries for InterMountain ESD for Fiscal Year 2013

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | numeric metric | esd            | ESD #          | number    | number      |
| Yes      | series tag     | esd_name       | ESD NAME       | text      | text        |
| Yes      | series tag     | classification | CLASSIFICATION | text      | text        |
| Yes      | series tag     | service_type   | SERVICE TYPE   | text      | text        |
| Yes      | series tag     | full_part_time | FULL/PART TIME | text      | text        |
| Yes      | numeric metric | annual_salary  | ANNUAL SALARY  | money     | money       |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ctku-jg66 d:2013-01-01T00:00:00.000Z t:esd_name="INTERMOUNTAIN EDUCATION SERVICE DISTRICT" t:service_type=ADMINISTRATION t:classification=SUPERINTENDENT t:full_part_time="FULL TIME" m:annual_salary=148357.35 m:esd=2200

series e:ctku-jg66 d:2013-01-01T00:00:00.000Z t:esd_name="INTERMOUNTAIN EDUCATION SERVICE DISTRICT" t:service_type=ADMINISTRATION t:classification="ASSISTANT SUPERINTENDENT" t:full_part_time="FULL TIME" m:annual_salary=110022 m:esd=2200

series e:ctku-jg66 d:2013-01-01T00:00:00.000Z t:esd_name="INTERMOUNTAIN EDUCATION SERVICE DISTRICT" t:service_type=ADMINISTRATION t:classification="DEPUTY SUPERINTENDENT/OPERATIONS" t:full_part_time="FULL TIME" m:annual_salary=110022 m:esd=2200
```

## Meta Commands

```ls
metric m:esd p:integer l:"ESD #" t:dataTypeName=number

metric m:annual_salary p:double l:"ANNUAL SALARY" t:dataTypeName=money

entity e:ctku-jg66 l:"Salaries: ESD: InterMountain: Fiscal Year 2013" t:url=https://data.oregon.gov/api/views/ctku-jg66

property e:ctku-jg66 t:meta.view v:id=ctku-jg66 v:category="Revenue & Expense" v:averageRating=0 v:name="Salaries: ESD: InterMountain: Fiscal Year 2013"

property e:ctku-jg66 t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:ctku-jg66 t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | esd_name                                 | classification                         | service_type   | full_part_time | annual_salary | 
| ==== | ======================================== | ====================================== | ============== | ============== | ============= | 
| 2200 | INTERMOUNTAIN EDUCATION SERVICE DISTRICT | SUPERINTENDENT                         | ADMINISTRATION | FULL TIME      | 148357.35     | 
| 2200 | INTERMOUNTAIN EDUCATION SERVICE DISTRICT | ASSISTANT SUPERINTENDENT               | ADMINISTRATION | FULL TIME      | 110022.00     | 
| 2200 | INTERMOUNTAIN EDUCATION SERVICE DISTRICT | DEPUTY SUPERINTENDENT/OPERATIONS       | ADMINISTRATION | FULL TIME      | 110022.00     | 
| 2200 | INTERMOUNTAIN EDUCATION SERVICE DISTRICT | CHIEF FINANCIAL OFFICER                | ADMINISTRATION | FULL TIME      | 106475.00     | 
| 2200 | INTERMOUNTAIN EDUCATION SERVICE DISTRICT | INSTRUCTIONAL SERVICES DIRECTOR        | ADMINISTRATION | FULL TIME      | 99559.00      | 
| 2200 | INTERMOUNTAIN EDUCATION SERVICE DISTRICT | SCHOOL PSYCHOLOGIST                    | LICENSED       | FULL TIME      | 92678.00      | 
| 2200 | INTERMOUNTAIN EDUCATION SERVICE DISTRICT | INFORMATION TECHNOLOGY DIRECTOR        | ADMINISTRATION | FULL TIME      | 90094.00      | 
| 2200 | INTERMOUNTAIN EDUCATION SERVICE DISTRICT | SPECIAL ED DIRECTOR/REGIONAL PROGRAMS  | ADMINISTRATION | FULL TIME      | 85947.00      | 
| 2200 | INTERMOUNTAIN EDUCATION SERVICE DISTRICT | FACILITIES & SUPPORT SERVICES DIRECTOR | ADMINISTRATION | FULL TIME      | 84957.00      | 
| 2200 | INTERMOUNTAIN EDUCATION SERVICE DISTRICT | PHYSICAL THERAPIST                     | LICENSED       | FULL TIME      | 84957.00      | 
```