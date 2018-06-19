# Expenditures: ESD: Harney: Fiscal Year 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/expenditures-esd-harney-fiscal-year-2013-de6a8) |
| Metadata | [Link](https://data.oregon.gov/api/views/uuhq-2fns) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/uuhq-2fns/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/uuhq-2fns/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | uuhq-2fns |
| Name | Expenditures: ESD: Harney: Fiscal Year 2013 |
| Category | Revenue & Expense |
| Tags | expenditures, esd, harney, fiscal year 2013 |
| Created | 2013-11-04T19:58:46Z |
| Publication Date | 2013-11-04T20:03:14Z |

## Description

Expenditures for Hareny ESD for Fiscal Year 2013

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | numeric metric | esd          | ESD#         | number    | number      |
| Yes      | series tag     | esd_name     | ESD_Name     | text      | text        |
| Yes      | numeric metric | fund         | Fund         | number    | number      |
| Yes      | series tag     | fund_name    | Fund_Name    | text      | text        |
| Yes      | numeric metric | compt        | Compt        | number    | number      |
| Yes      | numeric metric | obj          | Obj          | number    | number      |
| Yes      | series tag     | vendor_state | Vendor_State | text      | text        |
| Yes      | series tag     | vendor_name  | Vendor_Name  | text      | text        |
| Yes      | numeric metric | total_cost   | Total_Cost   | money     | money       |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:uuhq-2fns d:2013-01-01T00:00:00.000Z t:fund_name=General t:vendor_state=CA t:esd_name=Harney t:vendor_name="GOOGLE INC" m:total_cost=162.25 m:compt=0 m:esd=2013 m:obj=9421 m:fund=100

series e:uuhq-2fns d:2013-01-01T00:00:00.000Z t:fund_name=General t:vendor_state=CO t:esd_name=Harney t:vendor_name="MSR WEST INC" m:total_cost=1236 m:compt=0 m:esd=2013 m:obj=9421 m:fund=100

series e:uuhq-2fns d:2013-01-01T00:00:00.000Z t:fund_name=General t:vendor_state=IL t:esd_name=Harney t:vendor_name="HM RECEIVABLES CO LLC" m:total_cost=2875 m:compt=0 m:esd=2013 m:obj=9421 m:fund=100
```

## Meta Commands

```ls
metric m:esd p:integer l:ESD# t:dataTypeName=number

metric m:fund p:integer l:Fund t:dataTypeName=number

metric m:compt p:integer l:Compt t:dataTypeName=number

metric m:obj p:integer l:Obj t:dataTypeName=number

metric m:total_cost p:double l:Total_Cost t:dataTypeName=money

entity e:uuhq-2fns l:"Expenditures: ESD: Harney: Fiscal Year 2013" t:url=https://data.oregon.gov/api/views/uuhq-2fns

property e:uuhq-2fns t:meta.view v:id=uuhq-2fns v:category="Revenue & Expense" v:averageRating=0 v:name="Expenditures: ESD: Harney: Fiscal Year 2013"

property e:uuhq-2fns t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:uuhq-2fns t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | esd_name | fund | fund_name | compt | obj  | vendor_state | vendor_name                             | total_cost | 
| ==== | ======== | ==== | ========= | ===== | ==== | ============ | ======================================= | ========== | 
| 2013 | Harney   | 100  | General   | 0     | 9421 | CA           | GOOGLE INC                              | 162.25     | 
| 2013 | Harney   | 100  | General   | 0     | 9421 | CO           | MSR WEST INC                            | 1236.00    | 
| 2013 | Harney   | 100  | General   | 0     | 9421 | IL           | HM RECEIVABLES CO LLC                   | 2875.00    | 
| 2013 | Harney   | 100  | General   | 0     | 9421 | IL           | JOHN DEERE FINANCIAL                    | 40.74      | 
| 2013 | Harney   | 100  | General   | 0     | 9421 | MO           | US BANCORP #1404                        | 430.33     | 
| 2013 | Harney   | 100  | General   | 0     | 9421 | NC           | CHEVRON & TEXACO BUSINESS CARD SERVICES | 9.18       | 
| 2013 | Harney   | 100  | General   | 0     | 9421 | OR           | DEPT OF ADMINISTRATIVE SERVICE          | 1000.00    | 
| 2013 | Harney   | 100  | General   | 0     | 9421 | OR           | HC SCHOOL DISTRICT #3                   | 869.75     | 
| 2013 | Harney   | 100  | General   | 0     | 9421 | OR           | HOOPER, TASSIE                          | 320.00     | 
| 2013 | Harney   | 100  | General   | 0     | 9421 | OR           | KEEP KLEEN CAR WASH                     | 50.00      | 
```