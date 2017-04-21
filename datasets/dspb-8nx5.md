# IDOR November 2011 Disbursement Info

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idor-november-2011-disbursement-info-3f422) |
| Metadata | [Link](https://data.illinois.gov/api/views/dspb-8nx5) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/dspb-8nx5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/dspb-8nx5/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | dspb-8nx5 |
| Name | IDOR November 2011 Disbursement Info |
| Category | Economics |
| Tags | disbursements |
| Created | 2012-03-28T20:29:08Z |
| Publication Date | 2012-03-28T20:32:28Z |

## Description

Contains disbursement information for the September 2011 collections of Sales and Related Taxes. Voucher Date: 11/03/2011

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
series e:dspb-8nx5 d:2011-01-01T00:00:00.000Z t:tax=MT t:vendor=390000010 t:local_governments=ABINGDON m:warrant=14415.94 m:interest_income_included_in_warrant=0

series e:dspb-8nx5 d:2011-01-01T00:00:00.000Z t:tax=CST t:vendor=290000001 t:local_governments="ADAMS COUNTY GOVERNMENT" m:warrant=165033.22 m:interest_income_included_in_warrant=0

series e:dspb-8nx5 d:2011-01-01T00:00:00.000Z t:tax=CT t:vendor=290000001 t:local_governments="ADAMS COUNTY GOVERNMENT" m:warrant=43940.09 m:interest_income_included_in_warrant=0
```

## Meta Commands

```ls
metric m:warrant p:double l:Warrant t:dataTypeName=number

metric m:interest_income_included_in_warrant p:float l:"Interest Income Included in Warrant" t:dataTypeName=number

entity e:dspb-8nx5 l:"IDOR November 2011 Disbursement Info" t:url=https://data.illinois.gov/api/views/dspb-8nx5

property e:dspb-8nx5 t:meta.view v:id=dspb-8nx5 v:category=Economics v:averageRating=0 v:name="IDOR November 2011 Disbursement Info"

property e:dspb-8nx5 t:meta.view.owner v:id=krk3-r9n3 v:screenName="Bob Griffin" v:displayName="Bob Griffin"

property e:dspb-8nx5 t:meta.view.tableauthor v:id=krk3-r9n3 v:screenName="Bob Griffin" v:displayName="Bob Griffin"
```

## Top Records

```ls
| local_governments       | tax   | vendor    | warrant   | interest_income_included_in_warrant | 
| ======================= | ===== | ========= | ========= | =================================== | 
| ABINGDON                | MT    | 390000010 | 14415.94  | 0                                   | 
| ADAMS COUNTY GOVERNMENT | CST   | 290000001 | 165033.22 | 0                                   | 
| ADAMS COUNTY GOVERNMENT | CT    | 290000001 | 43940.09  | 0                                   | 
| ADDIEVILLE              | MT    | 390000018 | 4881.77   | 0                                   | 
| ADDISON                 | HMR   | 390000029 | 450694.65 | 89.24                               | 
| ADDISON                 | MT    | 390000029 | 720914.37 | 0                                   | 
| ADDISON                 | MTART | 390000029 | 482.26    | 0                                   | 
| ADELINE                 | MT    | 390000030 | 11.52     | 0                                   | 
| ALBANY                  | MT    | 390000020 | 3321.17   | 0                                   | 
| ALBERS                  | MT    | 390000045 | 5500.61   | 0                                   | 
```