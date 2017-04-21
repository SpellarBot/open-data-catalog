# IDOR December 2011 Disbursement Info

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idor-december-2011-disbursement-info-96740) |
| Metadata | [Link](https://data.illinois.gov/api/views/nz4r-xryt) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/nz4r-xryt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/nz4r-xryt/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | nz4r-xryt |
| Name | IDOR December 2011 Disbursement Info |
| Category | Economics |
| Tags | disbursements |
| Created | 2012-03-28T20:50:42Z |
| Publication Date | 2012-03-28T20:54:07Z |

## Description

Contains disbursement information for the October 2011 collections of Sales and Related Taxes. Voucher Date: 12/07/2011

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
series e:nz4r-xryt d:2011-01-01T00:00:00.000Z t:tax=MT t:vendor=390000010 t:local_governments=ABINGDON m:warrant=16779.37 m:interest_income_included_in_warrant=0

series e:nz4r-xryt d:2011-01-01T00:00:00.000Z t:tax=CST t:vendor=290000001 t:local_governments="ADAMS COUNTY GOVERNMENT" m:warrant=166623.31 m:interest_income_included_in_warrant=0

series e:nz4r-xryt d:2011-01-01T00:00:00.000Z t:tax=CT t:vendor=290000001 t:local_governments="ADAMS COUNTY GOVERNMENT" m:warrant=42690.17 m:interest_income_included_in_warrant=0
```

## Meta Commands

```ls
metric m:warrant p:double l:Warrant t:dataTypeName=number

metric m:interest_income_included_in_warrant p:float l:"Interest Income Included in Warrant" t:dataTypeName=number

entity e:nz4r-xryt l:"IDOR December 2011 Disbursement Info" t:url=https://data.illinois.gov/api/views/nz4r-xryt

property e:nz4r-xryt t:meta.view v:id=nz4r-xryt v:category=Economics v:averageRating=0 v:name="IDOR December 2011 Disbursement Info"

property e:nz4r-xryt t:meta.view.owner v:id=krk3-r9n3 v:screenName="Bob Griffin" v:displayName="Bob Griffin"

property e:nz4r-xryt t:meta.view.tableauthor v:id=krk3-r9n3 v:screenName="Bob Griffin" v:displayName="Bob Griffin"
```

## Top Records

```ls
| local_governments       | tax   | vendor    | warrant   | interest_income_included_in_warrant | 
| ======================= | ===== | ========= | ========= | =================================== | 
| ABINGDON                | MT    | 390000010 | 16779.37  | 0                                   | 
| ADAMS COUNTY GOVERNMENT | CST   | 290000001 | 166623.31 | 0                                   | 
| ADAMS COUNTY GOVERNMENT | CT    | 290000001 | 42690.17  | 0                                   | 
| ADDIEVILLE              | MT    | 390000018 | 4918.47   | 0                                   | 
| ADDISON                 | HMR   | 390000029 | 420528.85 | 72.67                               | 
| ADDISON                 | MT    | 390000029 | 672175.32 | 0                                   | 
| ADDISON                 | MTART | 390000029 | 277.03    | 0                                   | 
| ADELINE                 | MT    | 390000030 | 45.44     | 0                                   | 
| ALBANY                  | MT    | 390000020 | 4288.57   | 0                                   | 
| ALBERS                  | MT    | 390000045 | 5524.06   | 0                                   | 
```