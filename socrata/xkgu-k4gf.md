# IDOR March 2012 Disbursement Info

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idor-march-2012-disbursement-info-4fc3a) |
| Metadata | [Link](https://data.illinois.gov/api/views/xkgu-k4gf) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/xkgu-k4gf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/xkgu-k4gf/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | xkgu-k4gf |
| Name | IDOR March 2012 Disbursement Info |
| Category | Economics |
| Tags | disbursements |
| Created | 2012-03-28T21:19:07Z |
| Publication Date | 2012-03-28T21:21:53Z |

## Description

Contains disbursement information for the January 2012 collections of Sales and Related Taxes. Voucher Date: 03/07/2012

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
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:xkgu-k4gf d:2012-01-01T00:00:00.000Z t:tax=MT t:vendor=390000010 t:local_governments=ABINGDON m:warrant=15805.41 m:interest_income_included_in_warrant=0

series e:xkgu-k4gf d:2012-01-01T00:00:00.000Z t:tax=CST t:vendor=290000001 t:local_governments="ADAMS COUNTY GOVERNMENT" m:warrant=222516.89 m:interest_income_included_in_warrant=0

series e:xkgu-k4gf d:2012-01-01T00:00:00.000Z t:tax=CT t:vendor=290000001 t:local_governments="ADAMS COUNTY GOVERNMENT" m:warrant=48334.55 m:interest_income_included_in_warrant=0
```

## Meta Commands

```ls
metric m:warrant p:double l:Warrant t:dataTypeName=number

metric m:interest_income_included_in_warrant p:float l:"Interest Income Included in Warrant" t:dataTypeName=number

entity e:xkgu-k4gf l:"IDOR March 2012 Disbursement Info" t:url=https://data.illinois.gov/api/views/xkgu-k4gf

property e:xkgu-k4gf t:meta.view v:id=xkgu-k4gf v:category=Economics v:averageRating=0 v:name="IDOR March 2012 Disbursement Info"

property e:xkgu-k4gf t:meta.view.owner v:id=krk3-r9n3 v:screenName="Bob Griffin" v:displayName="Bob Griffin"

property e:xkgu-k4gf t:meta.view.tableauthor v:id=krk3-r9n3 v:screenName="Bob Griffin" v:displayName="Bob Griffin"
```

## Top Records

```ls
| local_governments       | tax   | vendor    | warrant   | interest_income_included_in_warrant | 
| ======================= | ===== | ========= | ========= | =================================== | 
| ABINGDON                | MT    | 390000010 | 15805.41  | 0                                   | 
| ADAMS COUNTY GOVERNMENT | CST   | 290000001 | 222516.89 | 0                                   | 
| ADAMS COUNTY GOVERNMENT | CT    | 290000001 | 48334.55  | 0                                   | 
| ADDIEVILLE              | MT    | 390000018 | 3257.63   | 0                                   | 
| ADDISON                 | HMR   | 390000029 | 423578.26 | 244.64                              | 
| ADDISON                 | MT    | 390000029 | 693151.17 | 0                                   | 
| ADDISON                 | MTART | 390000029 | 271.42    | 0                                   | 
| ADELINE                 | MT    | 390000030 | 114.72    | 0                                   | 
| ALBANY                  | MT    | 390000020 | 3571.12   | 0                                   | 
| ALBERS                  | MT    | 390000045 | 8634.50   | 0                                   | 
```