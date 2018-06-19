# Salaries: ESD: Willamette: Fiscal Year 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salaries-esd-willamette-fiscal-year-2014-7fc58) |
| Metadata | [Link](https://data.oregon.gov/api/views/vh2c-wmpt) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/vh2c-wmpt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/vh2c-wmpt/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | vh2c-wmpt |
| Name | Salaries: ESD: Willamette: Fiscal Year 2014 |
| Category | Revenue & Expense |
| Tags | salaries, esd, willamette, fiscal year 2014 |
| Created | 2014-12-16T17:40:26Z |
| Publication Date | 2014-12-29T06:01:24Z |

## Description

Salaries for Willamette ESD for Fiscal Year 2014

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | numeric metric | esd            | ESD #          | number    | number      |
| Yes      | series tag     | esd_name       | ESD Name       | text      | text        |
| Yes      | series tag     | classification | Classification | text      | text        |
| Yes      | series tag     | service_type   | Service Type   | text      | text        |
| Yes      | series tag     | full_part_time | Full/Part Time | text      | text        |
| Yes      | numeric metric | annual_salary  | Annual Salary  | money     | money       |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:vh2c-wmpt d:2014-01-01T00:00:00.000Z t:esd_name="Willamette ESD" t:service_type=Administrative t:classification="ADDITIONAL SALARY" t:full_part_time=0 m:annual_salary=2500 m:esd=2117

series e:vh2c-wmpt d:2014-01-01T00:00:00.000Z t:esd_name="Willamette ESD" t:service_type="Classified Represented" t:classification="ADMINISTRATIVE ASSIST 240" t:full_part_time=FT m:annual_salary=12005.76 m:esd=2117

series e:vh2c-wmpt d:2014-01-01T00:00:00.000Z t:esd_name="Willamette ESD" t:service_type="Classified Represented" t:classification="ADMINISTRATIVE ASSIST 240" t:full_part_time=FT m:annual_salary=33198.96 m:esd=2117
```

## Meta Commands

```ls
metric m:esd p:integer l:"ESD #" t:dataTypeName=number

metric m:annual_salary p:double l:"Annual Salary" t:dataTypeName=money

entity e:vh2c-wmpt l:"Salaries: ESD: Willamette: Fiscal Year 2014" t:url=https://data.oregon.gov/api/views/vh2c-wmpt

property e:vh2c-wmpt t:meta.view v:id=vh2c-wmpt v:category="Revenue & Expense" v:averageRating=0 v:name="Salaries: ESD: Willamette: Fiscal Year 2014"

property e:vh2c-wmpt t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:vh2c-wmpt t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | esd_name       | classification            | service_type           | full_part_time | annual_salary | 
| ==== | ============== | ========================= | ====================== | ============== | ============= | 
| 2117 | Willamette ESD | ADDITIONAL SALARY         | Administrative         | 0              | 2500.00       | 
| 2117 | Willamette ESD | ADMINISTRATIVE ASSIST 240 | Classified Represented | FT             | 12005.76      | 
| 2117 | Willamette ESD | ADMINISTRATIVE ASSIST 240 | Classified Represented | FT             | 33198.96      | 
| 2117 | Willamette ESD | ADMINISTRATIVE ASSISTANT  | Classified Represented | PT             | 20847.84      | 
| 2117 | Willamette ESD | APPLICATION DEVELOPER 2   | Classified Represented | FT             | 50721.52      | 
| 2117 | Willamette ESD | APPLICATION DEVELOPER 3   | Classified Represented | FT             | 61700.56      | 
| 2117 | Willamette ESD | APPLICATION DEVELOPER 3   | Classified Represented | FT             | 67991.92      | 
| 2117 | Willamette ESD | APPLICATION DEVELOPER 3   | Classified Represented | FT             | 71384.32      | 
| 2117 | Willamette ESD | APPLICATION DEVELOPER 4   | Classified Represented | FT             | 67991.92      | 
| 2117 | Willamette ESD | APPLICATION DEVELOPER 4   | Classified Represented | FT             | 78888.72      | 
```