# IDOR September 2011 Disbursement Info

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idor-september-2011-disbursement-info-15678) |
| Metadata | [Link](https://data.illinois.gov/api/views/rwfk-zcun) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/rwfk-zcun/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/rwfk-zcun/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | rwfk-zcun |
| Name | IDOR September 2011 Disbursement Info |
| Category | Economics |
| Created | 2012-03-28T20:08:23Z |
| Publication Date | 2012-03-28T20:12:48Z |

## Description

Contains disbursement information for the July 2011 collections of Sales and Related Taxes. Voucher Date: 09/06/2011

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
series e:rwfk-zcun d:2011-01-01T00:00:00.000Z t:tax=MT t:vendor=390000010 t:local_governments=ABINGDON m:warrant=16302.18 m:interest_income_included_in_warrant=0

series e:rwfk-zcun d:2011-01-01T00:00:00.000Z t:tax=CST t:vendor=290000001 t:local_governments="ADAMS COUNTY GOVERNMENT" m:warrant=172393.97 m:interest_income_included_in_warrant=0

series e:rwfk-zcun d:2011-01-01T00:00:00.000Z t:tax=CT t:vendor=290000001 t:local_governments="ADAMS COUNTY GOVERNMENT" m:warrant=42018.85 m:interest_income_included_in_warrant=0
```

## Meta Commands

```ls
metric m:warrant p:double l:Warrant t:dataTypeName=number

metric m:interest_income_included_in_warrant p:float l:"Interest Income Included in Warrant" t:dataTypeName=number

entity e:rwfk-zcun l:"IDOR September 2011 Disbursement Info" t:url=https://data.illinois.gov/api/views/rwfk-zcun

property e:rwfk-zcun t:meta.view v:id=rwfk-zcun v:category=Economics v:averageRating=0 v:name="IDOR September 2011 Disbursement Info"

property e:rwfk-zcun t:meta.view.owner v:id=krk3-r9n3 v:screenName="Bob Griffin" v:displayName="Bob Griffin"

property e:rwfk-zcun t:meta.view.tableauthor v:id=krk3-r9n3 v:screenName="Bob Griffin" v:displayName="Bob Griffin"
```

## Top Records

```ls
| local_governments       | tax   | vendor    | warrant   | interest_income_included_in_warrant | 
| ======================= | ===== | ========= | ========= | =================================== | 
| ABINGDON                | MT    | 390000010 | 16302.18  | 0                                   | 
| ADAMS COUNTY GOVERNMENT | CST   | 290000001 | 172393.97 | 0                                   | 
| ADAMS COUNTY GOVERNMENT | CT    | 290000001 | 42018.85  | 0                                   | 
| ADDIEVILLE              | MT    | 390000018 | 4619.99   | 0                                   | 
| ADDISON                 | HMR   | 390000029 | 423807.13 | 477.8                               | 
| ADDISON                 | MT    | 390000029 | 676885.29 | 0                                   | 
| ADDISON                 | MTART | 390000029 | 238.64    | 0                                   | 
| ADELINE                 | MT    | 390000030 | 13.78     | 0                                   | 
| ALBANY                  | MT    | 390000020 | 3648.01   | 0                                   | 
| ALBERS                  | MT    | 390000045 | 6194.04   | 0                                   | 
```