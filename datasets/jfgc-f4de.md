# King County budget, 2015-2016, General Fund Services

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/king-county-budget-2015-2016-general-fund-services-49190) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/jfgc-f4de) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/jfgc-f4de/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/jfgc-f4de/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | jfgc-f4de |
| Name | King County budget, 2015-2016, General Fund Services |
| Attribution | King County Performance, Strategy and Budget |
| Category | Budget |
| Tags | budget, general fund |
| Created | 2014-09-20T00:41:57Z |
| Publication Date | 2014-09-20T02:33:33Z |

## Description

King County biennial budget, 2015-2016, general fund by service

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | series tag     | service        | Service        | text      | text        |
| Yes      | series tag     | appropriation  | Appropriation  | text      | text        |
| Yes      | numeric metric | fy15_16_budget | FY15-16 Budget | money     | money       |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:jfgc-f4de d:2015-01-01T00:00:00.000Z t:appropriation="COUNTY COUNCIL" t:service="County Council" m:fy15_16_budget=3581430

series e:jfgc-f4de d:2015-01-01T00:00:00.000Z t:appropriation="COUNCIL ADMINISTRATION" t:service="County Council" m:fy15_16_budget=30165121

series e:jfgc-f4de d:2015-01-01T00:00:00.000Z t:appropriation="HEARING EXAMINER" t:service="County Council" m:fy15_16_budget=1122613
```

## Meta Commands

```ls
metric m:fy15_16_budget p:integer l:"FY15-16 Budget" t:dataTypeName=money

entity e:jfgc-f4de l:"King County budget, 2015-2016, General Fund Services" t:attribution="King County Performance, Strategy and Budget" t:url=https://data.kingcounty.gov/api/views/jfgc-f4de

property e:jfgc-f4de t:meta.view v:id=jfgc-f4de v:category=Budget v:attributionLink=http://www.kingcounty.gov/budget v:averageRating=0 v:name="King County budget, 2015-2016, General Fund Services" v:attribution="King County Performance, Strategy and Budget"

property e:jfgc-f4de t:meta.view.license v:name="Public Domain"

property e:jfgc-f4de t:meta.view.owner v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"

property e:jfgc-f4de t:meta.view.tableauthor v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"
```

## Top Records

```ls
| service                         | appropriation                             | fy15_16_budget | 
| =============================== | ========================================= | ============== | 
| County Council                  | COUNTY COUNCIL                            | 3581430        | 
| County Council                  | COUNCIL ADMINISTRATION                    | 30165121       | 
| County Council                  | HEARING EXAMINER                          | 1122613        | 
| County Council                  | COUNTY AUDITOR                            | 3979434        | 
| County Council                  | OMBUDSMAN TAX ADVISOR                     | 2635184        | 
| County Council                  | KC CIVIC TELEVISION                       | 1222043        | 
| County Council                  | BRD OF APPEALS EQUALIZTN                  | 1526995        | 
| County Executive                | COUNTY EXECUTIVE                          | 555537         | 
| County Executive                | OFFICE OF THE EXECUTIVE                   | 10201447       | 
| Performance Strategy and Budget | OFFICE OF PERFORMANCE STRATEGY AND BUDGET | 20453043       | 
```