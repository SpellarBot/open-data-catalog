# Revenue: ESD: Revenue By Fund And Source-by ESD 2010-11

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/revenue-esd-revenue-by-fund-and-source-by-esd-2010-11-76533) |
| Metadata | [Link](https://data.oregon.gov/api/views/jew3-69sj) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/jew3-69sj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/jew3-69sj/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | jew3-69sj |
| Name | Revenue: ESD: Revenue By Fund And Source-by ESD 2010-11 |
| Created | 2012-12-06T00:31:13Z |
| Publication Date | 2012-12-21T05:18:43Z |

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | series tag     | schoolyear     | SchoolYear     | text      | text        |
| Yes      | series tag     | esdid          | ESDID          | text      | text        |
| Yes      | series tag     | esd            | ESD            | text      | text        |
| Yes      | numeric metric | fundcd         | FundCd         | number    | text        |
| Yes      | series tag     | fund           | Fund           | text      | text        |
| Yes      | series tag     | revenue_type   | Revenue Type   | text      | text        |
| Yes      | numeric metric | sourcecd       | SourceCd       | number    | text        |
| Yes      | series tag     | revenue_source | Revenue Source | text      | text        |
| Yes      | numeric metric | actualrevamt   | ActualRevAmt   | money     | money       |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:jew3-69sj d:2010-01-01T00:00:00.000Z t:schoolyear=2010-11 t:esdid=1902 t:revenue_type=Local t:esd="Clackamas ESD" t:fund="General Fund" t:revenue_source="Ad valorem taxes levied by district" m:sourcecd=1110 m:actualrevamt=12002393.9 m:fundcd=100

series e:jew3-69sj d:2010-01-01T00:00:00.000Z t:schoolyear=2010-11 t:esdid=1902 t:revenue_type=Local t:esd="Clackamas ESD" t:fund="General Fund" t:revenue_source="Penalties and interest on taxes" m:sourcecd=1190 m:actualrevamt=66158.91 m:fundcd=100

series e:jew3-69sj d:2010-01-01T00:00:00.000Z t:schoolyear=2010-11 t:esdid=1902 t:revenue_type=Local t:esd="Clackamas ESD" t:fund="General Fund" t:revenue_source="Tuition from Other Districts within the State" m:sourcecd=1312 m:actualrevamt=907588.67 m:fundcd=100
```

## Meta Commands

```ls
metric m:fundcd p:integer l:FundCd t:dataTypeName=number

metric m:sourcecd p:integer l:SourceCd t:dataTypeName=number

metric m:actualrevamt p:double l:ActualRevAmt t:dataTypeName=money

entity e:jew3-69sj l:"Revenue: ESD: Revenue By Fund And Source-by ESD 2010-11" t:url=https://data.oregon.gov/api/views/jew3-69sj

property e:jew3-69sj t:meta.view v:id=jew3-69sj v:averageRating=0 v:name="Revenue: ESD: Revenue By Fund And Source-by ESD 2010-11"

property e:jew3-69sj t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:jew3-69sj t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| schoolyear | esdid | esd           | fundcd | fund         | revenue_type | sourcecd | revenue_source                                               | actualrevamt | 
| ========== | ===== | ============= | ====== | ============ | ============ | ======== | ============================================================ | ============ | 
| 2010-11    | 1902  | Clackamas ESD | 100    | General Fund | Local        | 1110     | Ad valorem taxes levied by district                          | 12002393.90  | 
| 2010-11    | 1902  | Clackamas ESD | 100    | General Fund | Local        | 1190     | Penalties and interest on taxes                              | 66158.91     | 
| 2010-11    | 1902  | Clackamas ESD | 100    | General Fund | Local        | 1312     | Tuition from Other Districts within the State                | 907588.67    | 
| 2010-11    | 1902  | Clackamas ESD | 100    | General Fund | Local        | 1500     | Earnings on Investments                                      | 65353.86     | 
| 2010-11    | 1902  | Clackamas ESD | 100    | General Fund | Local        | 1940     | Services Provided Other Local Education Agencies             | 54847.33     | 
| 2010-11    | 1902  | Clackamas ESD | 100    | General Fund | Local        | 1980     | Fees Charged to Grants                                       | 331562.60    | 
| 2010-11    | 1902  | Clackamas ESD | 100    | General Fund | Local        | 1990     | Miscellaneous                                                | 50400.10     | 
| 2010-11    | 1902  | Clackamas ESD | 100    | General Fund | State        | 3101     | State School Fund --General Support                          | 6297009.68   | 
| 2010-11    | 1902  | Clackamas ESD | 100    | General Fund | State        | 3104     | State Managed County Timber                                  | 2850.79      | 
| 2010-11    | 1902  | Clackamas ESD | 100    | General Fund | Federal      | 4500     | Restricted Revenue From the Federal Government Through the S | 1033716.92   | 
```