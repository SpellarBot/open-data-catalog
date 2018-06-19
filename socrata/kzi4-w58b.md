# Revenue ESD By Fund and Source--by ESD 2014-15

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/revenue-esd-by-fund-and-source-by-esd-2014-15) |
| Metadata | [Link](https://data.oregon.gov/api/views/kzi4-w58b) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/kzi4-w58b/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/kzi4-w58b/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | kzi4-w58b |
| Name | Revenue ESD By Fund and Source--by ESD 2014-15 |
| Category | Revenue & Expense |
| Tags | esd, esd revenue, esd revenue 2014, esd revenue 2015, esd revenue by source |
| Created | 2016-04-01T16:32:03Z |
| Publication Date | 2016-04-01T16:37:29Z |

## Description

ESD revenue by fund and source for FY 2014-2015

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | series tag     | schoolyear   | SchoolYear   | text      | text        |
| Yes      | series tag     | esdid        | ESDID        | text      | number      |
| Yes      | series tag     | esdname      | ESDName      | text      | text        |
| Yes      | numeric metric | fundcd       | FundCd       | number    | number      |
| Yes      | series tag     | funddesc     | FundDesc     | text      | text        |
| Yes      | numeric metric | sourcecd     | SourceCd     | number    | number      |
| Yes      | series tag     | sourcedesc   | SourceDesc   | text      | text        |
| Yes      | numeric metric | actualrevamt | ActualRevAmt | money     | money       |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:kzi4-w58b d:2014-01-01T00:00:00.000Z t:funddesc="General Fund" t:schoolyear=01-Jul-14 t:esdid=1902 t:esdname="Clackamas ESD" t:sourcedesc="Ad valorem taxes levied by district" m:sourcecd=1110 m:actualrevamt=13755564.49 m:fundcd=100

series e:kzi4-w58b d:2014-01-01T00:00:00.000Z t:funddesc="General Fund" t:schoolyear=01-Jul-14 t:esdid=1902 t:esdname="Clackamas ESD" t:sourcedesc="Penalties and interest on taxes" m:sourcecd=1190 m:actualrevamt=64840.87 m:fundcd=100

series e:kzi4-w58b d:2014-01-01T00:00:00.000Z t:funddesc="General Fund" t:schoolyear=01-Jul-14 t:esdid=1902 t:esdname="Clackamas ESD" t:sourcedesc="Tuition from Other Districts within the State" m:sourcecd=1312 m:actualrevamt=941438.76 m:fundcd=100
```

## Meta Commands

```ls
metric m:fundcd p:integer l:FundCd t:dataTypeName=number

metric m:sourcecd p:integer l:SourceCd t:dataTypeName=number

metric m:actualrevamt p:double l:ActualRevAmt t:dataTypeName=money

entity e:kzi4-w58b l:"Revenue ESD By Fund and Source--by ESD 2014-15" t:url=https://data.oregon.gov/api/views/kzi4-w58b

property e:kzi4-w58b t:meta.view v:id=kzi4-w58b v:category="Revenue & Expense" v:averageRating=0 v:name="Revenue ESD By Fund and Source--by ESD 2014-15"

property e:kzi4-w58b t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:kzi4-w58b t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| schoolyear | esdid | esdname       | fundcd | funddesc              | sourcecd | sourcedesc                                       | actualrevamt | 
| ========== | ===== | ============= | ====== | ===================== | ======== | ================================================ | ============ | 
| 01-Jul-14  | 1902  | Clackamas ESD | 100    | General Fund          | 1110     | Ad valorem taxes levied by district              | 13755564.49  | 
| 01-Jul-14  | 1902  | Clackamas ESD | 100    | General Fund          | 1190     | Penalties and interest on taxes                  | 64840.87     | 
| 01-Jul-14  | 1902  | Clackamas ESD | 100    | General Fund          | 1312     | Tuition from Other Districts within the State    | 941438.76    | 
| 01-Jul-14  | 1902  | Clackamas ESD | 100    | General Fund          | 1500     | Earnings on Investments                          | 72717.80     | 
| 01-Jul-14  | 1902  | Clackamas ESD | 100    | General Fund          | 1940     | Services Provided Other Local Education Agencies | 4118.36      | 
| 01-Jul-14  | 1902  | Clackamas ESD | 100    | General Fund          | 1980     | Fees Charged to Grants                           | 377364.32    | 
| 01-Jul-14  | 1902  | Clackamas ESD | 100    | General Fund          | 1990     | Miscellaneous                                    | 41342.42     | 
| 01-Jul-14  | 1902  | Clackamas ESD | 100    | General Fund          | 3101     | State School Fund --General Support              | 7487974.26   | 
| 01-Jul-14  | 1902  | Clackamas ESD | 100    | General Fund          | 3104     | State Managed County Timber                      | 5122.58      | 
| 01-Jul-14  | 1902  | Clackamas ESD | 200    | Special Revenue Funds | 1312     | Tuition from Other Districts within the State    | 1696052.98   | 
```