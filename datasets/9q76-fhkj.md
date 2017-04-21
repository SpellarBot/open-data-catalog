# Salaries: ESD: Wallowa: Fiscal Year 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salaries-esd-wallowa-fiscal-year-2014-2947f) |
| Metadata | [Link](https://data.oregon.gov/api/views/9q76-fhkj) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/9q76-fhkj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/9q76-fhkj/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 9q76-fhkj |
| Name | Salaries: ESD: Wallowa: Fiscal Year 2014 |
| Category | Revenue & Expense |
| Tags | salaries, esd, wallows, fiscal year 2014 |
| Created | 2014-12-15T02:47:47Z |
| Publication Date | 2014-12-29T05:54:37Z |

## Description

Salaries for Wallowa ESD for Fiscal Year 2014

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
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:9q76-fhkj d:2014-01-01T00:00:00.000Z t:esd_name="Wallowa County ESD" t:service_type=Unrepresented t:classification="Spec Ed. Teacher" t:esd="ESD #18" t:full_part_time="Full Time" m:annual_salary=54478

series e:9q76-fhkj d:2014-01-01T00:00:00.000Z t:esd_name="Wallowa County ESD" t:service_type=Unrepresented t:classification="Executive Secretary" t:esd="ESD #18" t:full_part_time="3/4 time" m:annual_salary=22114.86

series e:9q76-fhkj d:2014-01-01T00:00:00.000Z t:esd_name="Wallowa County ESD" t:service_type=Unrepresented t:classification="Spec. Ed. Aide" t:esd="ESD #18" t:full_part_time="3/4 Time" m:annual_salary=15346.78
```

## Meta Commands

```ls
metric m:annual_salary p:double l:"ANNUAL SALARY" t:dataTypeName=money

entity e:9q76-fhkj l:"Salaries: ESD: Wallowa: Fiscal Year 2014" t:url=https://data.oregon.gov/api/views/9q76-fhkj

property e:9q76-fhkj t:meta.view v:id=9q76-fhkj v:category="Revenue & Expense" v:averageRating=0 v:name="Salaries: ESD: Wallowa: Fiscal Year 2014"

property e:9q76-fhkj t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:9q76-fhkj t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd     | esd_name           | classification      | service_type  | full_part_time | annual_salary | 
| ======= | ================== | =================== | ============= | ============== | ============= | 
| ESD #18 | Wallowa County ESD | Spec Ed. Teacher    | Unrepresented | Full Time      | 54478.00      | 
| ESD #18 | Wallowa County ESD | Executive Secretary | Unrepresented | 3/4 time       | 22114.86      | 
| ESD #18 | Wallowa County ESD | Spec. Ed. Aide      | Unrepresented | 3/4 Time       | 15346.78      | 
| ESD #18 | Wallowa County ESD | Spec. Ed. Aide      | Unrepresented | 3/4 Time       | 16047.06      | 
| ESD #18 | Wallowa County ESD | Spec. Ed. Aide      | Unrepresented | 3/4 Time       | 15346.78      | 
| ESD #18 | Wallowa County ESD | Spec Ed. Teacher    | Unrepresented | Full Time      | 62802.00      | 
| ESD #18 | Wallowa County ESD | Deputy Clerk        | Unrepresented | Full Time      | 34687.10      | 
| ESD #18 | Wallowa County ESD | Spec Ed. Teacher    | Unrepresented | Full Time      | 62802.00      | 
| ESD #18 | Wallowa County ESD | Speech Pathologist  | Unrepresented | Full Time      | 69113.00      | 
| ESD #18 | Wallowa County ESD | Superintendent      | Unrepresented | 1/2 Time       | 43392.50      | 
```