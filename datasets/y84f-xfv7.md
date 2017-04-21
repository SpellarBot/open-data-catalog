# 2015 State Budget Restrictions As of June 30, 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-state-budget-restrictions-as-of-june-30-2015) |
| Metadata | [Link](https://data.mo.gov/api/views/y84f-xfv7) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/y84f-xfv7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/y84f-xfv7/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | y84f-xfv7 |
| Name | 2015 State Budget Restrictions As of June 30, 2015 |
| Category | Government Administration |
| Created | 2015-07-02T15:19:33Z |
| Publication Date | 2015-07-02T15:21:38Z |

## Description

The data provided here details the State of Missouri's Budget Restrictions as of June 30, 2015.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| Yes      | time           | budget_fiscal_year | Budget Fiscal Year | number    | text        |
| Yes      | series tag     | agency_name        | Agency Name        | text      | text        |
| Yes      | series tag     | fund_name          | Fund Name          | text      | text        |
| Yes      | numeric metric | restricted_amount  | Restricted Amount  | number    | number      |
| Yes      | numeric metric | released_amount    | Released Amount    | number    | number      |
```

## Time Field

```ls
Value = budget_fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:y84f-xfv7 d:2015-01-01T00:00:00.000Z t:fund_name="AGRICULTURE BUSINESS DEVELOPMENT" t:agency_name=AGRICULTURE m:released_amount=39 m:restricted_amount=39

series e:y84f-xfv7 d:2015-01-01T00:00:00.000Z t:fund_name="AGRICULTURE DEVELOPMENT" t:agency_name=AGRICULTURE m:released_amount=343 m:restricted_amount=343

series e:y84f-xfv7 d:2015-01-01T00:00:00.000Z t:fund_name="AGRICULTURE PROTECTION" t:agency_name=AGRICULTURE m:released_amount=2364 m:restricted_amount=46330
```

## Meta Commands

```ls
metric m:restricted_amount p:integer l:"Restricted Amount" t:dataTypeName=number

metric m:released_amount p:integer l:"Released Amount" t:dataTypeName=number

entity e:y84f-xfv7 l:"2015 State Budget Restrictions As of June 30, 2015" t:url=https://data.mo.gov/api/views/y84f-xfv7

property e:y84f-xfv7 t:meta.view v:id=y84f-xfv7 v:category="Government Administration" v:averageRating=0 v:name="2015 State Budget Restrictions As of June 30, 2015"

property e:y84f-xfv7 t:meta.view.license v:name="Public Domain"

property e:y84f-xfv7 t:meta.view.owner v:id=4cdh-4my4 v:screenName=Dwight v:displayName=Dwight

property e:y84f-xfv7 t:meta.view.tableauthor v:id=4cdh-4my4 v:screenName=Dwight v:roleName=editor v:displayName=Dwight
```

## Top Records

```ls
| budget_fiscal_year | agency_name | fund_name                                     | restricted_amount | released_amount | 
| ================== | =========== | ============================================= | ================= | =============== | 
| 2015               | AGRICULTURE | AGRICULTURE BUSINESS DEVELOPMENT              | 39                | 39              | 
| 2015               | AGRICULTURE | AGRICULTURE DEVELOPMENT                       | 343               | 343             | 
| 2015               | AGRICULTURE | AGRICULTURE PROTECTION                        | 46330             | 2364            | 
| 2015               | AGRICULTURE | ANIMAL CARE RESERVE                           | 2352              | 2249            | 
| 2015               | AGRICULTURE | ANIMAL HEALTH LABORATORY FEE                  | 764               | 104             | 
| 2015               | AGRICULTURE | AQUACULTURE MARKETING DEVELOPMENT             | 42                | 42              | 
| 2015               | AGRICULTURE | BOLL WEEVIL SUPPRESSION AND ERADICATION       | 181               | 181             | 
| 2015               | AGRICULTURE | COMMODITY COUNCIL MERCHANDISING               | 357               | 357             | 
| 2015               | AGRICULTURE | DEPARTMENT OF AGRICULTURE - FEDERAL AND OTHER | 6541              | 3140            | 
| 2015               | AGRICULTURE | FEDERAL STIMULUS - AGRICULTURE                | 170               | 170             | 
```