# Salaries: ESD: Inter Mountain: Fiscal Year 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salaries-esd-inter-mountain-fiscal-year-2014-5f634) |
| Metadata | [Link](https://data.oregon.gov/api/views/tth8-fxzt) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/tth8-fxzt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/tth8-fxzt/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | tth8-fxzt |
| Name | Salaries: ESD: Inter Mountain: Fiscal Year 2014 |
| Category | Revenue & Expense |
| Tags | salaries, esd, intermountain, fiscal year 2014 |
| Created | 2014-12-16T18:11:41Z |
| Publication Date | 2014-12-29T06:04:58Z |

## Description

Salaries for Inter Mountain ESD for Fiscal Year 2014

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
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:tth8-fxzt d:2014-01-01T00:00:00.000Z t:esd_name="INTERMOUNTAIN EDUCATION SERVICE DISTRICT" t:service_type=ADMINISTRATION t:classification=SUPERINTENDENT t:full_part_time="FULL TIME" m:annual_salary=150903.58 m:esd=2200

series e:tth8-fxzt d:2014-01-01T00:00:00.000Z t:esd_name="INTERMOUNTAIN EDUCATION SERVICE DISTRICT" t:service_type=ADMINISTRATION t:classification="ASSISTANT SUPERINTENDENT" t:full_part_time="FULL TIME" m:annual_salary=113682 m:esd=2200

series e:tth8-fxzt d:2014-01-01T00:00:00.000Z t:esd_name="INTERMOUNTAIN EDUCATION SERVICE DISTRICT" t:service_type=ADMINISTRATION t:classification="CHIEF FINANCIAL OFFICER" t:full_part_time="FULL TIME" m:annual_salary=109928 m:esd=2200
```

## Meta Commands

```ls
metric m:esd p:integer l:"ESD #" t:dataTypeName=number

metric m:annual_salary p:double l:"ANNUAL SALARY" t:dataTypeName=money

entity e:tth8-fxzt l:"Salaries: ESD: Inter Mountain: Fiscal Year 2014" t:url=https://data.oregon.gov/api/views/tth8-fxzt

property e:tth8-fxzt t:meta.view v:id=tth8-fxzt v:category="Revenue & Expense" v:averageRating=0 v:name="Salaries: ESD: Inter Mountain: Fiscal Year 2014"

property e:tth8-fxzt t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:tth8-fxzt t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | esd_name                                 | classification                         | service_type   | full_part_time | annual_salary | 
| ==== | ======================================== | ====================================== | ============== | ============== | ============= | 
| 2200 | INTERMOUNTAIN EDUCATION SERVICE DISTRICT | SUPERINTENDENT                         | ADMINISTRATION | FULL TIME      | 150903.58     | 
| 2200 | INTERMOUNTAIN EDUCATION SERVICE DISTRICT | ASSISTANT SUPERINTENDENT               | ADMINISTRATION | FULL TIME      | 113682.00     | 
| 2200 | INTERMOUNTAIN EDUCATION SERVICE DISTRICT | CHIEF FINANCIAL OFFICER                | ADMINISTRATION | FULL TIME      | 109928.00     | 
| 2200 | INTERMOUNTAIN EDUCATION SERVICE DISTRICT | INSTRUCTIONAL SERVICES DIRECTOR        | ADMINISTRATION | FULL TIME      | 99559.00      | 
| 2200 | INTERMOUNTAIN EDUCATION SERVICE DISTRICT | INFORMATION TECHNOLOGY DIRECTOR        | ADMINISTRATION | FULL TIME      | 91716.00      | 
| 2200 | INTERMOUNTAIN EDUCATION SERVICE DISTRICT | SPECIAL ED DIRECTOR/REGIONAL PROGRAMS  | ADMINISTRATION | FULL TIME      | 88903.00      | 
| 2200 | INTERMOUNTAIN EDUCATION SERVICE DISTRICT | PRINCIPAL-PLEASANT VIEW HIGH SCHOOL    | ADMINISTRATION | FULL TIME      | 84950.00      | 
| 2200 | INTERMOUNTAIN EDUCATION SERVICE DISTRICT | SPECIAL ED DIRECTOR/SPEECH & LANGUAGE  | ADMINISTRATION | FULL TIME      | 80931.80      | 
| 2200 | INTERMOUNTAIN EDUCATION SERVICE DISTRICT | FACILITIES & SUPPORT SERVICES DIRECTOR | ADMINISTRATION | FULL TIME      | 79951.37      | 
| 2200 | INTERMOUNTAIN EDUCATION SERVICE DISTRICT | BUSINESS SERVICES DIRECTOR             | ADMINISTRATION | FULL TIME      | 78441.00      | 
```