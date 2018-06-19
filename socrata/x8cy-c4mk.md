# Salaries; ESD: Clackamas: FY 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salaries-esd-clackamas-fy-2013-46dd7) |
| Metadata | [Link](https://data.oregon.gov/api/views/x8cy-c4mk) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/x8cy-c4mk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/x8cy-c4mk/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | x8cy-c4mk |
| Name | Salaries; ESD: Clackamas: FY 2013 |
| Category | Revenue & Expense |
| Tags | esd salaries, esd, clackamas esd salaries, clackamas esd, education service district salaries |
| Created | 2013-11-26T16:06:54Z |
| Publication Date | 2013-11-26T16:10:29Z |

## Description

Summary of salaries for Clackamas ESD for Fiscal Year 2013.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | numeric metric | esd             | ESD#            | number    | number      |
| Yes      | series tag     | esdname         | ESDName         | text      | text        |
| Yes      | numeric metric | classification  | Classification  | number    | number      |
| Yes      | series tag     | servicetype     | ServiceType     | text      | text        |
| Yes      | numeric metric | numberemployees | NumberEmployees | number    | number      |
| Yes      | numeric metric | totalfte        | TotalFTE        | number    | number      |
| Yes      | numeric metric | totalsalary     | TotalSalary     | money     | money       |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:x8cy-c4mk d:2013-01-01T00:00:00.000Z t:servicetype=Superintendent t:esdname="Clackamas ESD" m:classification=1 m:totalsalary=140297 m:numberemployees=1 m:esd=1902 m:totalfte=1

series e:x8cy-c4mk d:2013-01-01T00:00:00.000Z t:servicetype="Teacher, Non-Special Ed" t:esdname="Clackamas ESD" m:classification=8 m:totalsalary=47188 m:numberemployees=1 m:esd=1902 m:totalfte=1

series e:x8cy-c4mk d:2013-01-01T00:00:00.000Z t:servicetype="Other Licensed Staff, Non-Special Ed" t:esdname="Clackamas ESD" m:classification=11 m:totalsalary=75046.17 m:numberemployees=1 m:esd=1902 m:totalfte=1
```

## Meta Commands

```ls
metric m:esd p:integer l:ESD# t:dataTypeName=number

metric m:classification p:integer l:Classification t:dataTypeName=number

metric m:numberemployees p:integer l:NumberEmployees t:dataTypeName=number

metric m:totalfte p:float l:TotalFTE t:dataTypeName=number

metric m:totalsalary p:double l:TotalSalary t:dataTypeName=money

entity e:x8cy-c4mk l:"Salaries; ESD: Clackamas: FY 2013" t:url=https://data.oregon.gov/api/views/x8cy-c4mk

property e:x8cy-c4mk t:meta.view v:id=x8cy-c4mk v:category="Revenue & Expense" v:averageRating=0 v:name="Salaries; ESD: Clackamas: FY 2013"

property e:x8cy-c4mk t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:x8cy-c4mk t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | esdname       | classification | servicetype                                       | numberemployees | totalfte | totalsalary | 
| ==== | ============= | ============== | ================================================= | =============== | ======== | =========== | 
| 1902 | Clackamas ESD | 1              | Superintendent                                    | 1               | 1        | 140297.00   | 
| 1902 | Clackamas ESD | 8              | Teacher, Non-Special Ed                           | 1               | 1        | 47188.00    | 
| 1902 | Clackamas ESD | 11             | Other Licensed Staff, Non-Special Ed              | 1               | 1        | 75046.17    | 
| 1902 | Clackamas ESD | 11             | Other Licensed Staff, Non-Special Ed              | 1               | 1        | 71113.26    | 
| 1902 | Clackamas ESD | 11             | Other Licensed Staff, Non-Special Ed              | 1               | 1        | 103495.33   | 
| 1902 | Clackamas ESD | 11             | Other Licensed Staff, Non-Special Ed              | 1               | 1        | 112904.00   | 
| 1902 | Clackamas ESD | 11             | Other Licensed Staff, Non-Special Ed              | 1               | 0.6      | 39880.74    | 
| 1902 | Clackamas ESD | 11             | Other Licensed Staff, Non-Special Ed              | 1               | 1        | 71255.96    | 
| 1902 | Clackamas ESD | 16             | Paraprofessional (Inst Assistant), Non-Special Ed | 1               | 1        | 24907.50    | 
| 1902 | Clackamas ESD | 16             | Paraprofessional (Inst Assistant), Non-Special Ed | 1               | 1        | 24907.50    | 
```