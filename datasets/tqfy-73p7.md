# Capital Improvement 2014 Annual Budget

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/capital-improvement-2014-annual-budget-82345) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/tqfy-73p7) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/tqfy-73p7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/tqfy-73p7/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | tqfy-73p7 |
| Name | Capital Improvement 2014 Annual Budget |
| Attribution | King County |
| Category | Budget |
| Tags | budget, 2014, capital improvement |
| Created | 2013-09-23T17:50:35Z |
| Publication Date | 2013-09-23T17:53:59Z |

## Description

King County Executive's proposed budget, 2014, capital improvements

## Columns

```ls
| Included | Schema Type    | Field Name | Name   | Data Type | Render Type |
| ======== | ============== | ========== | ====== | ========= | =========== |
| Yes      | series tag     | fund       | Fund   | text      | text        |
| Yes      | numeric metric | amount     | Amount | money     | money       |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:tqfy-73p7 d:2014-01-01T00:00:00.000Z t:fund="FMD-Parks Rec Open Space" m:amount=10625240

series e:tqfy-73p7 d:2014-01-01T00:00:00.000Z t:fund="Long-Term Leases" m:amount=47728668

series e:tqfy-73p7 d:2014-01-01T00:00:00.000Z t:fund="Youth Srvs Facilts Const" m:amount=204964732
```

## Meta Commands

```ls
metric m:amount p:integer l:Amount t:dataTypeName=money

entity e:tqfy-73p7 l:"Capital Improvement 2014 Annual Budget" t:attribution="King County" t:url=https://data.kingcounty.gov/api/views/tqfy-73p7

property e:tqfy-73p7 t:meta.view v:id=tqfy-73p7 v:category=Budget v:attributionLink=http://www.kingcounty.gov/budget v:averageRating=0 v:name="Capital Improvement 2014 Annual Budget" v:attribution="King County"

property e:tqfy-73p7 t:meta.view.license v:name="Public Domain"

property e:tqfy-73p7 t:meta.view.owner v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"

property e:tqfy-73p7 t:meta.view.tableauthor v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"
```

## Top Records

```ls
| fund                      | amount    | 
| ========================= | ========= | 
| FMD-Parks Rec Open Space  | 10625240  | 
| Long-Term Leases          | 47728668  | 
| Youth Srvs Facilts Const  | 204964732 | 
| Mjr Mntnce Rsrv Sub-Fund  | 7621146   | 
| FMD-Parks Facility Rehab  | 1216229   | 
| Parks Capital Fund        | 26037575  | 
| Real Estate Excise Tx Cap | 8363654   | 
| Real Estate Excise Tx 2   | 7536732   | 
| OIRM Capital Projects     | 18591236  | 
| ITS Capital               | 550000    | 
```