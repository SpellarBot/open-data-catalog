# Revenue ESD By Fund and Source-by ESD 2013-14

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/revenue-esd-revenue-by-fund-and-source-by-esd-2013-14) |
| Metadata | [Link](https://data.oregon.gov/api/views/svmq-xb8w) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/svmq-xb8w/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/svmq-xb8w/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | svmq-xb8w |
| Name | Revenue ESD By Fund and Source-by ESD 2013-14 |
| Category | Revenue & Expense |
| Tags | esd, esd revenue, esd revenue 2013, esd revenue 2014, esd revenue by source |
| Created | 2015-04-20T15:36:29Z |
| Publication Date | 2015-04-20T15:42:35Z |

## Description

ESD revenue by fund and source for FY 2013-2014

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
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:svmq-xb8w d:2013-01-01T00:00:00.000Z t:funddesc="General Fund" t:schoolyear=01-Jul-13 t:esdid=1902 t:esdname="Clackamas ESD" t:sourcedesc="Ad valorem taxes levied by district" m:sourcecd=1110 m:actualrevamt=12911261.19 m:fundcd=100

series e:svmq-xb8w d:2013-01-01T00:00:00.000Z t:funddesc="General Fund" t:schoolyear=01-Jul-13 t:esdid=1902 t:esdname="Clackamas ESD" t:sourcedesc="Penalties and interest on taxes" m:sourcecd=1190 m:actualrevamt=81158.17 m:fundcd=100

series e:svmq-xb8w d:2013-01-01T00:00:00.000Z t:funddesc="General Fund" t:schoolyear=01-Jul-13 t:esdid=1902 t:esdname="Clackamas ESD" t:sourcedesc="Tuition from Other Districts within the State" m:sourcecd=1312 m:actualrevamt=846897.23 m:fundcd=100
```

## Meta Commands

```ls
metric m:fundcd p:integer l:FundCd t:dataTypeName=number

metric m:sourcecd p:integer l:SourceCd t:dataTypeName=number

metric m:actualrevamt p:double l:ActualRevAmt t:dataTypeName=money

entity e:svmq-xb8w l:"Revenue ESD By Fund and Source-by ESD 2013-14" t:url=https://data.oregon.gov/api/views/svmq-xb8w

property e:svmq-xb8w t:meta.view v:id=svmq-xb8w v:category="Revenue & Expense" v:averageRating=0 v:name="Revenue ESD By Fund and Source-by ESD 2013-14"

property e:svmq-xb8w t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:svmq-xb8w t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| schoolyear | esdid | esdname       | fundcd | funddesc              | sourcecd | sourcedesc                                     | actualrevamt | 
| ========== | ===== | ============= | ====== | ===================== | ======== | ============================================== | ============ | 
| 01-Jul-13  | 1902  | Clackamas ESD | 100    | General Fund          | 1110     | Ad valorem taxes levied by district            | 12911261.19  | 
| 01-Jul-13  | 1902  | Clackamas ESD | 100    | General Fund          | 1190     | Penalties and interest on taxes                | 81158.17     | 
| 01-Jul-13  | 1902  | Clackamas ESD | 100    | General Fund          | 1312     | Tuition from Other Districts within the State  | 846897.23    | 
| 01-Jul-13  | 1902  | Clackamas ESD | 100    | General Fund          | 1500     | Earnings on Investments                        | 51813.32     | 
| 01-Jul-13  | 1902  | Clackamas ESD | 100    | General Fund          | 1980     | Fees Charged to Grants                         | 344091.54    | 
| 01-Jul-13  | 1902  | Clackamas ESD | 100    | General Fund          | 1990     | Miscellaneous                                  | 14146.34     | 
| 01-Jul-13  | 1902  | Clackamas ESD | 100    | General Fund          | 3101     | State School Fund --General Support            | 8062662.06   | 
| 01-Jul-13  | 1902  | Clackamas ESD | 100    | General Fund          | 3299     | Other Restricted Grants-In-Aid                 | 52.82        | 
| 01-Jul-13  | 1902  | Clackamas ESD | 200    | Special Revenue Funds | 1312     | Tuition from Other Districts within the State  | 1439343.15   | 
| 01-Jul-13  | 1902  | Clackamas ESD | 200    | Special Revenue Funds | 1313     | Tuition from Other Districts outside the State | 21216.00     | 
```