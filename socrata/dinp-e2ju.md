# IDOR October 2011 Disbursement Info

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idor-october-2011-disbursement-info-a2dea) |
| Metadata | [Link](https://data.illinois.gov/api/views/dinp-e2ju) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/dinp-e2ju/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/dinp-e2ju/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | dinp-e2ju |
| Name | IDOR October 2011 Disbursement Info |
| Category | Economics |
| Tags | disbursements |
| Created | 2012-03-28T20:20:21Z |
| Publication Date | 2012-03-28T20:25:20Z |

## Description

Contains disbursement information for the August 2011 collections of Sales and Related Taxes. Voucher Date: 10/11/2011

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
series e:dinp-e2ju d:2011-01-01T00:00:00.000Z t:tax=MT t:vendor=390000010 t:local_governments=ABINGDON m:warrant=15022.45 m:interest_income_included_in_warrant=0

series e:dinp-e2ju d:2011-01-01T00:00:00.000Z t:tax=CST t:vendor=290000001 t:local_governments="ADAMS COUNTY GOVERNMENT" m:warrant=163556.69 m:interest_income_included_in_warrant=0

series e:dinp-e2ju d:2011-01-01T00:00:00.000Z t:tax=CT t:vendor=290000001 t:local_governments="ADAMS COUNTY GOVERNMENT" m:warrant=36532.69 m:interest_income_included_in_warrant=0
```

## Meta Commands

```ls
metric m:warrant p:double l:Warrant t:dataTypeName=number

metric m:interest_income_included_in_warrant p:float l:"Interest Income Included in Warrant" t:dataTypeName=number

entity e:dinp-e2ju l:"IDOR October 2011 Disbursement Info" t:url=https://data.illinois.gov/api/views/dinp-e2ju

property e:dinp-e2ju t:meta.view v:id=dinp-e2ju v:category=Economics v:averageRating=0 v:name="IDOR October 2011 Disbursement Info"

property e:dinp-e2ju t:meta.view.owner v:id=krk3-r9n3 v:screenName="Bob Griffin" v:displayName="Bob Griffin"

property e:dinp-e2ju t:meta.view.tableauthor v:id=krk3-r9n3 v:screenName="Bob Griffin" v:displayName="Bob Griffin"
```

## Top Records

```ls
| local_governments       | tax   | vendor    | warrant   | interest_income_included_in_warrant | 
| ======================= | ===== | ========= | ========= | =================================== | 
| ABINGDON                | MT    | 390000010 | 15022.45  | 0                                   | 
| ADAMS COUNTY GOVERNMENT | CST   | 290000001 | 163556.69 | 0                                   | 
| ADAMS COUNTY GOVERNMENT | CT    | 290000001 | 36532.69  | 0                                   | 
| ADDIEVILLE              | MT    | 390000018 | 3891.68   | 0                                   | 
| ADDISON                 | HMR   | 390000029 | 427718.96 | 351.57                              | 
| ADDISON                 | MT    | 390000029 | 682336.39 | 0                                   | 
| ADDISON                 | MTART | 390000029 | 391.61    | 0                                   | 
| ADELINE                 | MT    | 390000030 | 52        | 0                                   | 
| ALBANY                  | MT    | 390000020 | 4098.39   | 0                                   | 
| ALBERS                  | MT    | 390000045 | 6634.57   | 0                                   | 
```