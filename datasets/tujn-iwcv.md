# Expenditures: ESD: Harney: Fiscal Year 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/expenditures-esd-harney-fiscal-year-2014-11a4e) |
| Metadata | [Link](https://data.oregon.gov/api/views/tujn-iwcv) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/tujn-iwcv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/tujn-iwcv/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | tujn-iwcv |
| Name | Expenditures: ESD: Harney: Fiscal Year 2014 |
| Category | Revenue & Expense |
| Tags | expenditures, esd, harney, fiscal year 2014 |
| Created | 2014-12-16T18:25:32Z |
| Publication Date | 2014-12-29T06:06:42Z |

## Description

Expenditures for Harney ESD for Fiscal Year 2014

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | numeric metric | esd          | ESD #        | number    | number      |
| Yes      | series tag     | esd_name     | ESD Name     | text      | text        |
| Yes      | numeric metric | fund         | Fund         | number    | number      |
| Yes      | series tag     | fund_name    | Fund Name    | text      | text        |
| Yes      | numeric metric | compt        | Compt        | number    | number      |
| Yes      | numeric metric | obj          | Obj          | number    | number      |
| Yes      | series tag     | vendor_state | Vendor State | text      | text        |
| Yes      | series tag     | remit_name   | Remit Name   | text      | text        |
| Yes      | numeric metric | totalcost    | TotalCost    | money     | money       |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:tujn-iwcv d:2014-01-01T00:00:00.000Z t:fund_name=General t:vendor_state=OR t:esd_name=Harney t:remit_name="A PARTS STORE" m:totalcost=20.58 m:compt=2540 m:esd=2013 m:obj=329 m:fund=100

series e:tujn-iwcv d:2014-01-01T00:00:00.000Z t:fund_name=General t:vendor_state=OR t:esd_name=Harney t:remit_name="A PARTS STORE" m:totalcost=15.18 m:compt=2540 m:esd=2013 m:obj=329 m:fund=100

series e:tujn-iwcv d:2014-01-01T00:00:00.000Z t:fund_name=General t:vendor_state=OR t:esd_name=Harney t:remit_name="A PARTS STORE" m:totalcost=38.98 m:compt=2540 m:esd=2013 m:obj=329 m:fund=100
```

## Meta Commands

```ls
metric m:esd p:integer l:"ESD #" t:dataTypeName=number

metric m:fund p:integer l:Fund t:dataTypeName=number

metric m:compt p:integer l:Compt t:dataTypeName=number

metric m:obj p:integer l:Obj t:dataTypeName=number

metric m:totalcost p:double l:TotalCost t:dataTypeName=money

entity e:tujn-iwcv l:"Expenditures: ESD: Harney: Fiscal Year 2014" t:url=https://data.oregon.gov/api/views/tujn-iwcv

property e:tujn-iwcv t:meta.view v:id=tujn-iwcv v:category="Revenue & Expense" v:averageRating=0 v:name="Expenditures: ESD: Harney: Fiscal Year 2014"

property e:tujn-iwcv t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:tujn-iwcv t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | esd_name | fund | fund_name | compt | obj | vendor_state | remit_name                 | totalcost | 
| ==== | ======== | ==== | ========= | ===== | === | ============ | ========================== | ========= | 
| 2013 | Harney   | 100  | General   | 2540  | 329 | OR           | A PARTS STORE              | 20.58     | 
| 2013 | Harney   | 100  | General   | 2540  | 329 | OR           | A PARTS STORE              | 15.18     | 
| 2013 | Harney   | 100  | General   | 2540  | 329 | OR           | A PARTS STORE              | 38.98     | 
| 2013 | Harney   | 501  | EOT       | 2660  | 410 | OR           | A PARTS STORE              | 84.16     | 
| 2013 | Harney   | 501  | EOT       | 2660  | 310 | OR           | ACTIONABLE INFORMATION LLC | 3050.00   | 
| 2013 | Harney   | 501  | EOT       | 2660  | 310 | OR           | ACW RENTAL                 | 140.00    | 
| 2013 | Harney   | 501  | EOT       | 2660  | 310 | OR           | ACW RENTAL                 | 165.00    | 
| 2013 | Harney   | 501  | EOT       | 2660  | 410 | OR           | ACW ROCK & READY - MIX     | 561.75    | 
| 2013 | Harney   | 501  | EOT       | 2660  | 415 | OR           | ACW ROCK & READY - MIX     | 735.50    | 
| 2013 | Harney   | 501  | EOT       | 2660  | 415 | OR           | ACW ROCK & READY - MIX     | 700.00    | 
```