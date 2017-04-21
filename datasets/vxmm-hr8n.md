# Salaries: ESD: Wallowa: Fiscal Year 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salaries-esd-wallowa-fiscal-year-2013-447dc) |
| Metadata | [Link](https://data.oregon.gov/api/views/vxmm-hr8n) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/vxmm-hr8n/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/vxmm-hr8n/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | vxmm-hr8n |
| Name | Salaries: ESD: Wallowa: Fiscal Year 2013 |
| Category | Revenue & Expense |
| Tags | salaries, esd, wallows, fiscal year 2013 |
| Created | 2013-10-31T18:59:51Z |
| Publication Date | 2013-10-31T19:01:26Z |

## Description

Salaries for Wallowa ESD for Fiscal Year 2013

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | series tag     | esd            | ESD #          | text      | text        |
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
series e:vxmm-hr8n d:2013-01-01T00:00:00.000Z t:esd_name="Wallowa County ESD" t:service_type=Unrepresented t:classification="Spec Ed. Teacher" t:esd="ESD #18" t:full_part_time="Full Time" m:annual_salary=51875

series e:vxmm-hr8n d:2013-01-01T00:00:00.000Z t:esd_name="Wallowa County ESD" t:service_type=Unrepresented t:classification="Executive Secretary" t:esd="ESD #18" t:full_part_time="3/4 time" m:annual_salary=21115.08

series e:vxmm-hr8n d:2013-01-01T00:00:00.000Z t:esd_name="Wallowa County ESD" t:service_type=Unrepresented t:classification="Spec. Ed. Aide" t:esd="ESD #18" t:full_part_time="3/4 Time" m:annual_salary=15036.39
```

## Meta Commands

```ls
metric m:annual_salary p:double l:"ANNUAL SALARY" t:dataTypeName=money

entity e:vxmm-hr8n l:"Salaries: ESD: Wallowa: Fiscal Year 2013" t:url=https://data.oregon.gov/api/views/vxmm-hr8n

property e:vxmm-hr8n t:meta.view v:id=vxmm-hr8n v:category="Revenue & Expense" v:averageRating=0 v:name="Salaries: ESD: Wallowa: Fiscal Year 2013"

property e:vxmm-hr8n t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:vxmm-hr8n t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd     | esd_name           | classification      | service_type  | full_part_time | annual_salary | 
| ======= | ================== | =================== | ============= | ============== | ============= | 
| ESD #18 | Wallowa County ESD | Spec Ed. Teacher    | Unrepresented | Full Time      | 51875.00      | 
| ESD #18 | Wallowa County ESD | Executive Secretary | Unrepresented | 3/4 time       | 21115.08      | 
| ESD #18 | Wallowa County ESD | Spec. Ed. Aide      | Unrepresented | 3/4 Time       | 15036.39      | 
| ESD #18 | Wallowa County ESD | Spec. Ed. Aide      | Unrepresented | 3/4 Time       | 15718.23      | 
| ESD #18 | Wallowa County ESD | Spec. Ed. Aide      | Unrepresented | 3/4 Time       | 15036.39      | 
| ESD #18 | Wallowa County ESD | Spec Ed. Teacher    | Unrepresented | Full Time      | 61510.00      | 
| ESD #18 | Wallowa County ESD | Deputy Clerk        | Unrepresented | Full Time      | 38382.43      | 
| ESD #18 | Wallowa County ESD | Spec Ed. Teacher    | Unrepresented | Full Time      | 61510.00      | 
| ESD #18 | Wallowa County ESD | Speech Pathologist  | Unrepresented | Full Time      | 67691.00      | 
| ESD #18 | Wallowa County ESD | Superintendent      | Unrepresented | 1/2 Time       | 42500.00      | 
```