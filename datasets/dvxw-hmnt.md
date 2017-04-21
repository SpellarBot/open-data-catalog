# Total budget expenditures 2015-2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/total-budget-expenditures-2015-2016-8a428) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/dvxw-hmnt) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/dvxw-hmnt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/dvxw-hmnt/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | dvxw-hmnt |
| Name | Total budget expenditures 2015-2016 |
| Attribution | King County Performance, Strategy and Budget |
| Category | Budget |
| Tags | budget |
| Created | 2014-09-20T00:04:45Z |
| Publication Date | 2014-09-20T02:35:55Z |

## Description

King County biennial budget, by appropriations, 2015-2016

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
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
series e:dvxw-hmnt d:2015-01-01T00:00:00.000Z t:appropriation="County Council" m:fy15_16_budget=3581430

series e:dvxw-hmnt d:2015-01-01T00:00:00.000Z t:appropriation="County GIS" m:fy15_16_budget=15860252

series e:dvxw-hmnt d:2015-01-01T00:00:00.000Z t:appropriation="Council Administration" m:fy15_16_budget=30165121
```

## Meta Commands

```ls
metric m:fy15_16_budget p:integer l:"FY15-16 Budget" t:dataTypeName=money

entity e:dvxw-hmnt l:"Total budget expenditures 2015-2016" t:attribution="King County Performance, Strategy and Budget" t:url=https://data.kingcounty.gov/api/views/dvxw-hmnt

property e:dvxw-hmnt t:meta.view v:id=dvxw-hmnt v:category=Budget v:attributionLink=http://www.kingcounty.gov/budget v:averageRating=0 v:name="Total budget expenditures 2015-2016" v:attribution="King County Performance, Strategy and Budget"

property e:dvxw-hmnt t:meta.view.license v:name="Public Domain"

property e:dvxw-hmnt t:meta.view.owner v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"

property e:dvxw-hmnt t:meta.view.tableauthor v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"
```

## Top Records

```ls
| appropriation              | fy15_16_budget | 
| ========================== | ============== | 
| County Council             | 3581430        | 
| County GIS                 | 15860252       | 
| Council Administration     | 30165121       | 
| Hearing Examiner           | 1122613        | 
| County Auditor             | 3979434        | 
| Ombudsman Tax Advisor      | 2635184        | 
| KC Civic Television        | 1222043        | 
| Brd Of Appeals Equaliztn   | 1526995        | 
| Office Of Indep Oversight  | 1600241        | 
| Office Of E and F Analysis | 982051         | 
```