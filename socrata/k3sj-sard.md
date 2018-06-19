# Salaries:ESD: Clackamas: Fiscal Year 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salaries-esd-clackamas-fiscal-year-2014-26e45) |
| Metadata | [Link](https://data.oregon.gov/api/views/k3sj-sard) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/k3sj-sard/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/k3sj-sard/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | k3sj-sard |
| Name | Salaries:ESD: Clackamas: Fiscal Year 2014 |
| Category | Revenue & Expense |
| Tags | esd salaries, esd, clackamas esd salaries, clackamas esd 2014 |
| Created | 2014-12-16T18:51:29Z |
| Publication Date | 2014-12-28T22:25:47Z |

## Description

Summary of salaries for Clackamas ESD for Fiscal Year 2014.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| Yes      | numeric metric | esd                 | ESD#                | number    | number      |
| Yes      | series tag     | esd_name            | ESD Name            | text      | text        |
| Yes      | numeric metric | classification      | Classification      | number    | number      |
| Yes      | series tag     | service_type        | Service Type        | text      | text        |
| Yes      | numeric metric | number_of_employees | Number of Employees | number    | number      |
| Yes      | numeric metric | total_fte           | Total FTE           | number    | number      |
| Yes      | numeric metric | total_salary        | Total Salary        | money     | money       |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:k3sj-sard d:2014-01-01T00:00:00.000Z t:esd_name="Clackamas ESD" t:service_type=Superintendent m:number_of_employees=1 m:total_salary=142051 m:classification=1 m:esd=1902 m:total_fte=1

series e:k3sj-sard d:2014-01-01T00:00:00.000Z t:esd_name="Clackamas ESD" t:service_type="Assistant Superintendent" m:number_of_employees=1 m:total_salary=10166.67 m:classification=2 m:esd=1902 m:total_fte=1

series e:k3sj-sard d:2014-01-01T00:00:00.000Z t:esd_name="Clackamas ESD" t:service_type="Assistant Superintendent" m:number_of_employees=1 m:total_salary=61000 m:classification=2 m:esd=1902 m:total_fte=1
```

## Meta Commands

```ls
metric m:esd p:integer l:ESD# t:dataTypeName=number

metric m:classification p:integer l:Classification t:dataTypeName=number

metric m:number_of_employees p:integer l:"Number of Employees" t:dataTypeName=number

metric m:total_fte p:double l:"Total FTE" t:dataTypeName=number

metric m:total_salary p:double l:"Total Salary" t:dataTypeName=money

entity e:k3sj-sard l:"Salaries:ESD: Clackamas: Fiscal Year 2014" t:url=https://data.oregon.gov/api/views/k3sj-sard

property e:k3sj-sard t:meta.view v:id=k3sj-sard v:category="Revenue & Expense" v:averageRating=0 v:name="Salaries:ESD: Clackamas: Fiscal Year 2014"

property e:k3sj-sard t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:k3sj-sard t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | esd_name      | classification | service_type                         | number_of_employees | total_fte | total_salary | 
| ==== | ============= | ============== | ==================================== | =================== | ========= | ============ | 
| 1902 | Clackamas ESD | 1              | Superintendent                       | 1                   | 1         | 142051.00    | 
| 1902 | Clackamas ESD | 2              | Assistant Superintendent             | 1                   | 1         | 10166.67     | 
| 1902 | Clackamas ESD | 2              | Assistant Superintendent             | 1                   | 1         | 61000.00     | 
| 1902 | Clackamas ESD | 8              | Teacher, Non-Special Ed              | 1                   | 1         | 49563.73     | 
| 1902 | Clackamas ESD | 11             | Other Licensed Staff, Non-Special Ed | 1                   | 1         | 63349.56     | 
| 1902 | Clackamas ESD | 11             | Other Licensed Staff, Non-Special Ed | 1                   | 0.6011    | 40668.64     | 
| 1902 | Clackamas ESD | 11             | Other Licensed Staff, Non-Special Ed | 1                   | 1         | 77131.35     | 
| 1902 | Clackamas ESD | 11             | Other Licensed Staff, Non-Special Ed | 1                   | 1         | 73255.41     | 
| 1902 | Clackamas ESD | 11             | Other Licensed Staff, Non-Special Ed | 1                   | 1         | 114315.00    | 
| 1902 | Clackamas ESD | 11             | Other Licensed Staff, Non-Special Ed | 1                   | 1         | 15769.33     | 
```