# IDOR August 2011 Disbursement Info

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idor-august-2011-disbursement-info-45701) |
| Metadata | [Link](https://data.illinois.gov/api/views/k2uu-sczi) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/k2uu-sczi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/k2uu-sczi/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | k2uu-sczi |
| Name | IDOR August 2011 Disbursement Info |
| Category | Economics |
| Tags | disbursements |
| Created | 2012-03-28T19:53:34Z |
| Publication Date | 2012-03-28T19:58:59Z |

## Description

Contains disbursement information for the June 2011 collections of Sales and Related Taxes. Voucher Date: 08/04//2011

## Columns

```ls
| Included | Schema Type    | Field Name                          | Name                                | Data Type | Render Type |
| ======== | ============== | =================================== | =================================== | ========= | =========== |
| Yes      | series tag     | local_governments                   | Local Governments                   | text      | text        |
| Yes      | series tag     | tax                                 | Tax                                 | text      | text        |
| Yes      | series tag     | vendor                              | Vendor#                             | text      | text        |
| Yes      | numeric metric | warrant                             | Warrant                             | number    | number      |
| Yes      | numeric metric | interest_income_included_in_warrant | Interest Income Included in Warrant | number    | number      |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:k2uu-sczi d:2011-01-01T00:00:00.000Z t:tax=MT t:vendor=390000010 t:local_governments=ABINGDON m:warrant=16151.88 m:interest_income_included_in_warrant=0

series e:k2uu-sczi d:2011-01-01T00:00:00.000Z t:tax=CST t:vendor=290000001 t:local_governments="ADAMS COUNTY GOVERNMENT" m:warrant=157701.52 m:interest_income_included_in_warrant=0

series e:k2uu-sczi d:2011-01-01T00:00:00.000Z t:tax=CT t:vendor=290000001 t:local_governments="ADAMS COUNTY GOVERNMENT" m:warrant=39683.95 m:interest_income_included_in_warrant=0
```

## Meta Commands

```ls
metric m:warrant p:double l:Warrant t:dataTypeName=number

metric m:interest_income_included_in_warrant p:float l:"Interest Income Included in Warrant" t:dataTypeName=number

entity e:k2uu-sczi l:"IDOR August 2011 Disbursement Info" t:url=https://data.illinois.gov/api/views/k2uu-sczi

property e:k2uu-sczi t:meta.view v:id=k2uu-sczi v:category=Economics v:averageRating=0 v:name="IDOR August 2011 Disbursement Info"

property e:k2uu-sczi t:meta.view.owner v:id=krk3-r9n3 v:screenName="Bob Griffin" v:displayName="Bob Griffin"

property e:k2uu-sczi t:meta.view.tableauthor v:id=krk3-r9n3 v:screenName="Bob Griffin" v:displayName="Bob Griffin"
```

## Top Records

```ls
| local_governments       | tax   | vendor    | warrant   | interest_income_included_in_warrant | 
| ======================= | ===== | ========= | ========= | =================================== | 
| ABINGDON                | MT    | 390000010 | 16151.88  | 0                                   | 
| ADAMS COUNTY GOVERNMENT | CST   | 290000001 | 157701.52 | 0                                   | 
| ADAMS COUNTY GOVERNMENT | CT    | 290000001 | 39683.95  | 0                                   | 
| ADDIEVILLE              | MT    | 390000018 | 3698.05   | 0                                   | 
| ADDISON                 | HMR   | 390000029 | 413182.34 | 0.01                                | 
| ADDISON                 | MT    | 390000029 | 661797.15 | 0                                   | 
| ADDISON                 | MTART | 390000029 | 205.98    | 2.23                                | 
| ADELINE                 | MT    | 390000030 | 28.32     | 0                                   | 
| ALBANY                  | MT    | 390000020 | 3151.32   | 0                                   | 
| ALBERS                  | MT    | 390000045 | 6318.91   | 0                                   | 
```