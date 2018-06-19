# Revenue: ESD: Revenue By Fund And Source-by ESD 2012-13

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/revenue-esd-revenue-by-fund-and-source-by-esd-2012-13-aa6e9) |
| Metadata | [Link](https://data.oregon.gov/api/views/wf6w-fnc5) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/wf6w-fnc5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/wf6w-fnc5/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | wf6w-fnc5 |
| Name | Revenue: ESD: Revenue By Fund And Source-by ESD 2012-13 |
| Category | Revenue & Expense |
| Tags | esd, esd revenue, esd revenue 2012, esd revenue 2013, esd revenue by source |
| Created | 2014-04-02T18:03:55Z |
| Publication Date | 2014-04-02T18:22:50Z |

## Description

ESD revenue by fund and source for FY 2012-2013

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
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:wf6w-fnc5 d:2012-01-01T00:00:00.000Z t:funddesc="General Fund" t:schoolyear=01-Jul-12 t:esdid=1902 t:esdname="Clackamas ESD" t:sourcedesc="Ad valorem taxes levied by district" m:sourcecd=1110 m:actualrevamt=12264379.26 m:fundcd=100

series e:wf6w-fnc5 d:2012-01-01T00:00:00.000Z t:funddesc="General Fund" t:schoolyear=01-Jul-12 t:esdid=1902 t:esdname="Clackamas ESD" t:sourcedesc="Penalties and interest on taxes" m:sourcecd=1190 m:actualrevamt=66700.39 m:fundcd=100

series e:wf6w-fnc5 d:2012-01-01T00:00:00.000Z t:funddesc="General Fund" t:schoolyear=01-Jul-12 t:esdid=1902 t:esdname="Clackamas ESD" t:sourcedesc="Tuition from Other Districts within the State" m:sourcecd=1312 m:actualrevamt=810574 m:fundcd=100
```

## Meta Commands

```ls
metric m:fundcd p:integer l:FundCd t:dataTypeName=number

metric m:sourcecd p:integer l:SourceCd t:dataTypeName=number

metric m:actualrevamt p:double l:ActualRevAmt t:dataTypeName=money

entity e:wf6w-fnc5 l:"Revenue: ESD: Revenue By Fund And Source-by ESD 2012-13" t:url=https://data.oregon.gov/api/views/wf6w-fnc5

property e:wf6w-fnc5 t:meta.view v:id=wf6w-fnc5 v:category="Revenue & Expense" v:averageRating=0 v:name="Revenue: ESD: Revenue By Fund And Source-by ESD 2012-13"

property e:wf6w-fnc5 t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:wf6w-fnc5 t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| schoolyear | esdid | esdname       | fundcd | funddesc              | sourcecd | sourcedesc                                     | actualrevamt | 
| ========== | ===== | ============= | ====== | ===================== | ======== | ============================================== | ============ | 
| 01-Jul-12  | 1902  | Clackamas ESD | 100    | General Fund          | 1110     | Ad valorem taxes levied by district            | 12264379.26  | 
| 01-Jul-12  | 1902  | Clackamas ESD | 100    | General Fund          | 1190     | Penalties and interest on taxes                | 66700.39     | 
| 01-Jul-12  | 1902  | Clackamas ESD | 100    | General Fund          | 1312     | Tuition from Other Districts within the State  | 810574.00    | 
| 01-Jul-12  | 1902  | Clackamas ESD | 100    | General Fund          | 1500     | Earnings on Investments                        | 57786.30     | 
| 01-Jul-12  | 1902  | Clackamas ESD | 100    | General Fund          | 1980     | Fees Charged to Grants                         | 351489.84    | 
| 01-Jul-12  | 1902  | Clackamas ESD | 100    | General Fund          | 1990     | Miscellaneous                                  | 7928.93      | 
| 01-Jul-12  | 1902  | Clackamas ESD | 100    | General Fund          | 3101     | State School Fund --General Support            | 7255830.66   | 
| 01-Jul-12  | 1902  | Clackamas ESD | 100    | General Fund          | 3104     | State Managed County Timber                    | 10782.86     | 
| 01-Jul-12  | 1902  | Clackamas ESD | 200    | Special Revenue Funds | 1312     | Tuition from Other Districts within the State  | 1405066.42   | 
| 01-Jul-12  | 1902  | Clackamas ESD | 200    | Special Revenue Funds | 1313     | Tuition from Other Districts outside the State | 19380.00     | 
```