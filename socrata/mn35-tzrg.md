# 2013 Proposed Budget, General Fund, Services

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2013-proposed-budget-general-fund-services-250b8) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/mn35-tzrg) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/mn35-tzrg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/mn35-tzrg/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | mn35-tzrg |
| Name | 2013 Proposed Budget, General Fund, Services |
| Attribution | King County Executive |
| Category | Budget |
| Tags | budget, 2013, budget2013 |
| Created | 2012-09-14T17:24:09Z |
| Publication Date | 2012-09-23T21:12:34Z |

## Description

King County budget proposed September 2012 by Executive for 2013, general fund, broken down by service. See http://www.kingcounty.gov/budget for more.

## Columns

```ls
| Included | Schema Type    | Field Name | Name          | Data Type | Render Type |
| ======== | ============== | ========== | ============= | ========= | =========== |
| Yes      | series tag     | budget     | Budget        | text      | text        |
| Yes      | series tag     | agency     | Service       | text      | text        |
| Yes      | series tag     | service    | Appropriation | text      | text        |
| Yes      | numeric metric | amount     | Amount        | money     | money       |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:mn35-tzrg d:2013-01-01T00:00:00.000Z t:budget=000000010 t:service="County Council" t:agency=Council m:amount=1637197

series e:mn35-tzrg d:2013-01-01T00:00:00.000Z t:budget=000000010 t:service="Council Administration" t:agency=Council m:amount=12757311

series e:mn35-tzrg d:2013-01-01T00:00:00.000Z t:budget=000000010 t:service="Hearing Examiner" t:agency=Council m:amount=604330
```

## Meta Commands

```ls
metric m:amount p:double l:Amount t:dataTypeName=money

entity e:mn35-tzrg l:"2013 Proposed Budget, General Fund, Services" t:attribution="King County Executive" t:url=https://data.kingcounty.gov/api/views/mn35-tzrg

property e:mn35-tzrg t:meta.view v:id=mn35-tzrg v:category=Budget v:attributionLink=http://www.kingcounty.gov/budget/ v:averageRating=0 v:name="2013 Proposed Budget, General Fund, Services" v:attribution="King County Executive"

property e:mn35-tzrg t:meta.view.license v:name="Public Domain"

property e:mn35-tzrg t:meta.view.owner v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"

property e:mn35-tzrg t:meta.view.tableauthor v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"
```

## Top Records

```ls
| budget    | agency               | service                         | amount    | 
| ========= | ==================== | =============================== | ========= | 
| 000000010 | Council              | County Council                  | 1637197   | 
| 000000010 | Council              | Council Administration          | 12757311  | 
| 000000010 | Council              | Hearing Examiner                | 604330    | 
| 000000010 | Council              | County Auditor                  | 1735744   | 
| 000000010 | Council              | Ombudsman Tax Advisor           | 1197574   | 
| 000000010 | Council              | Kc Civic Television             | 587735    | 
| 000000010 | Council              | Board Of Appeals Equalization   | 713595    | 
| 000000010 | Independent Agencies | Office Of Independent Oversight | 562169    | 
| 000000010 | Independent Agencies | Office of E and F Analysis      | 351914.00 | 
| 000000010 | County Executive     | County Executive                | 252902.00 | 
```