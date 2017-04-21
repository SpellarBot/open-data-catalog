# IDOR February 2012 Disbursement Info

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idor-february-2012-disbursement-info-c250d) |
| Metadata | [Link](https://data.illinois.gov/api/views/hndt-sirc) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/hndt-sirc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/hndt-sirc/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | hndt-sirc |
| Name | IDOR February 2012 Disbursement Info |
| Category | Economics |
| Tags | disbursements |
| Created | 2012-03-28T21:11:50Z |
| Publication Date | 2012-03-28T21:14:44Z |

## Description

Contains disbursement information for the December 2011 collections of Sales and Related Taxes. Voucher Date: 02/07/2012

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
series e:hndt-sirc d:2012-01-01T00:00:00.000Z t:tax=MT t:vendor=390000010 t:local_governments=ABINGDON m:warrant=15104.2 m:interest_income_included_in_warrant=0

series e:hndt-sirc d:2012-01-01T00:00:00.000Z t:tax=CST t:vendor=290000001 t:local_governments="ADAMS COUNTY GOVERNMENT" m:warrant=174710.95 m:interest_income_included_in_warrant=0

series e:hndt-sirc d:2012-01-01T00:00:00.000Z t:tax=CT t:vendor=290000001 t:local_governments="ADAMS COUNTY GOVERNMENT" m:warrant=37121.97 m:interest_income_included_in_warrant=0
```

## Meta Commands

```ls
metric m:warrant p:double l:Warrant t:dataTypeName=number

metric m:interest_income_included_in_warrant p:float l:"Interest Income Included in Warrant" t:dataTypeName=number

entity e:hndt-sirc l:"IDOR February 2012 Disbursement Info" t:url=https://data.illinois.gov/api/views/hndt-sirc

property e:hndt-sirc t:meta.view v:id=hndt-sirc v:category=Economics v:averageRating=0 v:name="IDOR February 2012 Disbursement Info"

property e:hndt-sirc t:meta.view.owner v:id=krk3-r9n3 v:screenName="Bob Griffin" v:displayName="Bob Griffin"

property e:hndt-sirc t:meta.view.tableauthor v:id=krk3-r9n3 v:screenName="Bob Griffin" v:displayName="Bob Griffin"
```

## Top Records

```ls
| local_governments       | tax   | vendor    | warrant   | interest_income_included_in_warrant | 
| ======================= | ===== | ========= | ========= | =================================== | 
| ABINGDON                | MT    | 390000010 | 15104.20  | 0                                   | 
| ADAMS COUNTY GOVERNMENT | CST   | 290000001 | 174710.95 | 0                                   | 
| ADAMS COUNTY GOVERNMENT | CT    | 290000001 | 37121.97  | 0                                   | 
| ADDIEVILLE              | MT    | 390000018 | 4443.07   | 0                                   | 
| ADDISON                 | HMR   | 390000029 | 416942.71 | 235.25                              | 
| ADDISON                 | MT    | 390000029 | 671106.62 | 0                                   | 
| ADDISON                 | MTART | 390000029 | 273.62    | 0                                   | 
| ADELINE                 | MT    | 390000030 | 71.36     | 0                                   | 
| ALBANY                  | MT    | 390000020 | 3668.35   | 0                                   | 
| ALBERS                  | MT    | 390000045 | 6173.80   | 0                                   | 
```