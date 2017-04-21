# 2015 - OPIF & I OPIF Payments FY2014-2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-opif-i-opif-payments-fy2014-2015) |
| Metadata | [Link](https://data.oregon.gov/api/views/49mp-b2ic) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/49mp-b2ic/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/49mp-b2ic/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 49mp-b2ic |
| Name | 2015 - OPIF & I OPIF Payments FY2014-2015 |
| Category | Revenue & Expense |
| Tags | 2015; opif; iopif; i opif; opif and iopif; fy 2014-2015. |
| Created | 2016-01-09T04:11:22Z |
| Publication Date | 2016-01-09T04:14:03Z |

## Description

2015-New Reporting Topic: A new reporting topic to satisfy SB 515 by the 77th Legislature, Oregon Laws 2015, Chapter 456, requires reporting of the Filmmakers or companies receiving reimbursements and the amount of each reimbursement from the OPIF and iOPIF programs under ORS 284.368. For more information, go to:
http://www.oregon.gov/transparency/Pages/TaxExpenditures.aspx.

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                              | Data Type | Render Type |
| ======== | ============== | =============================== | ================================= | ========= | =========== |
| Yes      | series tag     | opif_iopif_production_companies | OPIF & iOPIF Production Companies | text      | text        |
| Yes      | numeric metric | payments_fy_2014_2015           | Payments (FY 2014-2015)           | money     | money       |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:49mp-b2ic d:2015-01-01T00:00:00.000Z t:opif_iopif_production_companies="Backbone Entertainment" m:payments_fy_2014_2015=99062.93

series e:49mp-b2ic d:2015-01-01T00:00:00.000Z t:opif_iopif_production_companies="Bent Image Labs" m:payments_fy_2014_2015=39177.83

series e:49mp-b2ic d:2015-01-01T00:00:00.000Z t:opif_iopif_production_companies="BIL Productions LLC" m:payments_fy_2014_2015=300000
```

## Meta Commands

```ls
metric m:payments_fy_2014_2015 p:double l:"Payments (FY 2014-2015)" t:dataTypeName=money

entity e:49mp-b2ic l:"2015 - OPIF & I OPIF Payments FY2014-2015" t:url=https://data.oregon.gov/api/views/49mp-b2ic

property e:49mp-b2ic t:meta.view v:id=49mp-b2ic v:category="Revenue & Expense" v:averageRating=0 v:name="2015 - OPIF & I OPIF Payments FY2014-2015"

property e:49mp-b2ic t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:49mp-b2ic t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| opif_iopif_production_companies | payments_fy_2014_2015 | 
| =============================== | ===================== | 
| Backbone Entertainment          | 99062.93              | 
| Bent Image Labs                 | 39177.83              | 
| BIL Productions LLC             | 300000.00             | 
| Cabin Fever Productions, LLC    | 160000.00             | 
| Combat Report, LLC              | 50000.00              | 
| Ex Libris Productions Inc       | 2204380.75            | 
| Green Room Productions LLC      | 425000.00             | 
| Iron Girl Productions Inc       | 1177785.78            | 
| LAIKA Inc                       | 1250000.00            | 
| Pipeworks Software              | 107373.55             | 
```