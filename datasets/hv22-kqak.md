# Federal Loan Amount - Unemployment Trust Fund

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/federal-loan-amount-unemployment-trust-fund-01b3c) |
| Metadata | [Link](https://data.mo.gov/api/views/hv22-kqak) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/hv22-kqak/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/hv22-kqak/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | hv22-kqak |
| Name | Federal Loan Amount - Unemployment Trust Fund |
| Created | 2013-02-25T14:52:30Z |
| Publication Date | 2013-03-11T14:41:51Z |

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| Yes      | time           | date        | Date        | date      | date        |
| Yes      | numeric metric | loan_amount | Loan Amount | money     | money       |
```

## Time Field

```ls
Value = date
Format & Zone = seconds
```

## Data Commands

```ls
series e:hv22-kqak d:2012-03-01T08:00:00.000Z m:loan_amount=807432015.77

series e:hv22-kqak d:2011-09-01T07:00:00.000Z m:loan_amount=725446730.74

series e:hv22-kqak d:2012-09-01T07:00:00.000Z m:loan_amount=569252812.84
```

## Meta Commands

```ls
metric m:loan_amount p:double l:"Loan Amount" t:dataTypeName=money

entity e:hv22-kqak l:"Federal Loan Amount - Unemployment Trust Fund" t:url=https://data.mo.gov/api/views/hv22-kqak

property e:hv22-kqak t:meta.view v:id=hv22-kqak v:averageRating=0 v:name="Federal Loan Amount - Unemployment Trust Fund"

property e:hv22-kqak t:meta.view.owner v:id=eb88-upz2 v:screenName=DOLIR v:displayName=DOLIR

property e:hv22-kqak t:meta.view.tableauthor v:id=9z8w-z2yk v:screenName=Amy_Susan v:roleName=editor v:displayName=Amy_Susan
```

## Top Records

```ls
| date       | loan_amount  | 
| ========== | ============ | 
| 1330588800 | 807432015.77 | 
| 1314860400 | 725446730.74 | 
| 1346482800 | 569252812.84 | 
| 1298966400 | 878144121.09 | 
| 1349074800 | 569252812.84 | 
| 1317452400 | 725446730.74 | 
| 1304233200 | 672406218.09 | 
| 1335855600 | 563547139.03 | 
| 1293868800 | 789012013.67 | 
| 1325404800 | 772395878.49 | 
```