# ESD REVENUE BY FUND AND SOURCE: 2009, 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/esd-revenue-by-fund-and-source-2009-2010-92b70) |
| Metadata | [Link](https://data.oregon.gov/api/views/wspt-s43w) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/wspt-s43w/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/wspt-s43w/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | wspt-s43w |
| Name | ESD REVENUE BY FUND AND SOURCE: 2009, 2010 |
| Category | Revenue & Expense |
| Created | 2011-12-06T21:55:52Z |
| Publication Date | 2011-12-27T19:36:04Z |

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | series tag     | schoolyear     | SchoolYear     | text      | text        |
| Yes      | series tag     | esdid          | ESDID          | text      | number      |
| Yes      | series tag     | esd            | ESD            | text      | text        |
| Yes      | series tag     | fund_code      | Fund Code      | text      | number      |
| Yes      | series tag     | fund           | Fund           | text      | text        |
| Yes      | series tag     | revenue_type   | Revenue Type   | text      | text        |
| Yes      | series tag     | source_code    | Source Code    | text      | number      |
| Yes      | series tag     | revenue_source | Revenue Source | text      | text        |
| Yes      | numeric metric | actualrevamt   | ActualRevAmt   | money     | money       |
```

## Time Field

```ls
Value = 2009
Format & Zone = yyyy
```

## Data Commands

```ls
series e:wspt-s43w d:2009-01-01T00:00:00.000Z t:source_code=1110 t:fund_code=100 t:schoolyear=2009-10 t:esdid=1902 t:revenue_type=Local t:esd="Clackamas ESD" t:fund="General Fund" t:revenue_source="Ad valorem taxes levied by district" m:actualrevamt=11733205

series e:wspt-s43w d:2009-01-01T00:00:00.000Z t:source_code=1190 t:fund_code=100 t:schoolyear=2009-10 t:esdid=1902 t:revenue_type=Local t:esd="Clackamas ESD" t:fund="General Fund" t:revenue_source="Penalties and interest on taxes" m:actualrevamt=55373

series e:wspt-s43w d:2009-01-01T00:00:00.000Z t:source_code=1312 t:fund_code=100 t:schoolyear=2009-10 t:esdid=1902 t:revenue_type=Local t:esd="Clackamas ESD" t:fund="General Fund" t:revenue_source="Tuition from Other Districts within the State" m:actualrevamt=974319
```

## Meta Commands

```ls
metric m:actualrevamt p:integer l:ActualRevAmt t:dataTypeName=money

entity e:wspt-s43w l:"ESD REVENUE BY FUND AND SOURCE: 2009, 2010" t:url=https://data.oregon.gov/api/views/wspt-s43w

property e:wspt-s43w t:meta.view v:id=wspt-s43w v:category="Revenue & Expense" v:averageRating=0 v:name="ESD REVENUE BY FUND AND SOURCE: 2009, 2010"

property e:wspt-s43w t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:wspt-s43w t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| schoolyear | esdid | esd           | fund_code | fund                  | revenue_type | source_code | revenue_source                                               | actualrevamt | 
| ========== | ===== | ============= | ========= | ===================== | ============ | =========== | ============================================================ | ============ | 
| 2009-10    | 1902  | Clackamas ESD | 100       | General Fund          | Local        | 1110        | Ad valorem taxes levied by district                          | 11733205     | 
| 2009-10    | 1902  | Clackamas ESD | 100       | General Fund          | Local        | 1190        | Penalties and interest on taxes                              | 55373        | 
| 2009-10    | 1902  | Clackamas ESD | 100       | General Fund          | Local        | 1312        | Tuition from Other Districts within the State                | 974319       | 
| 2009-10    | 1902  | Clackamas ESD | 100       | General Fund          | Local        | 1500        | Earnings on Investments                                      | 78919        | 
| 2009-10    | 1902  | Clackamas ESD | 100       | General Fund          | Local        | 1980        | Fees Charged to Grants                                       | 294923       | 
| 2009-10    | 1902  | Clackamas ESD | 100       | General Fund          | Local        | 1990        | Miscellaneous                                                | 29782        | 
| 2009-10    | 1902  | Clackamas ESD | 100       | General Fund          | State        | 3101        | State School Fund --General Support                          | 8351050      | 
| 2009-10    | 1902  | Clackamas ESD | 100       | General Fund          | State        | 3104        | State Managed County Timber                                  | 5455         | 
| 2009-10    | 1902  | Clackamas ESD | 100       | General Fund          | Federal      | 4500        | Restricted Revenue From the Federal Government Through the S | 484315       | 
| 2009-10    | 1902  | Clackamas ESD | 200       | Special Revenue Funds | Local        | 1312        | Tuition from Other Districts within the State                | 1565964      | 
```