# 2014 Public Bonds Data As of JUne 30, 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2014-public-bonds-data-as-of-june-30-2014-5b02b) |
| Metadata | [Link](https://data.mo.gov/api/views/3hue-nw7e) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/3hue-nw7e/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/3hue-nw7e/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | 3hue-nw7e |
| Name | 2014 Public Bonds Data As of JUne 30, 2014 |
| Category | Government Administration |
| Created | 2014-07-02T18:44:04Z |
| Publication Date | 2014-07-02T18:45:22Z |

## Description

The data provided here details the State of Missouri's Public Bonds Data as of June 30, 2014.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| Yes      | time           | budget_fiscal_year | Budget Fiscal Year | number    | text        |
| Yes      | series tag     | agency_name        | Agency Name        | text      | text        |
| Yes      | series tag     | fund_name          | Fund Name          | text      | text        |
| Yes      | numeric metric | restricted_amount  | Restricted Amount  | money     | money       |
| Yes      | numeric metric | released_amount    | Released Amount    | money     | money       |
```

## Time Field

```ls
Value = budget_fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:3hue-nw7e d:2014-01-01T00:00:00.000Z t:fund_name="AGRICULTURE BUSINESS DEVELOPMENT" t:agency_name=AGRICULTURE m:released_amount=38 m:restricted_amount=0

series e:3hue-nw7e d:2014-01-01T00:00:00.000Z t:fund_name="AGRICULTURE DEVELOPMENT" t:agency_name=AGRICULTURE m:released_amount=400 m:restricted_amount=0

series e:3hue-nw7e d:2014-01-01T00:00:00.000Z t:fund_name="AGRICULTURE PROTECTION" t:agency_name=AGRICULTURE m:released_amount=29400 m:restricted_amount=0
```

## Meta Commands

```ls
metric m:restricted_amount p:double l:"Restricted Amount" t:dataTypeName=money

metric m:released_amount p:double l:"Released Amount" t:dataTypeName=money

entity e:3hue-nw7e l:"2014 Public Bonds Data As of JUne 30, 2014" t:url=https://data.mo.gov/api/views/3hue-nw7e

property e:3hue-nw7e t:meta.view v:id=3hue-nw7e v:category="Government Administration" v:averageRating=0 v:name="2014 Public Bonds Data As of JUne 30, 2014"

property e:3hue-nw7e t:meta.view.owner v:id=4cdh-4my4 v:screenName=Dwight v:displayName=Dwight

property e:3hue-nw7e t:meta.view.tableauthor v:id=4cdh-4my4 v:screenName=Dwight v:roleName=editor v:displayName=Dwight
```

## Top Records

```ls
| budget_fiscal_year | agency_name | fund_name                                     | restricted_amount | released_amount | 
| ================== | =========== | ============================================= | ================= | =============== | 
| 2014               | AGRICULTURE | AGRICULTURE BUSINESS DEVELOPMENT              | 0.00              | 38.00           | 
| 2014               | AGRICULTURE | AGRICULTURE DEVELOPMENT                       | 0.00              | 400.00          | 
| 2014               | AGRICULTURE | AGRICULTURE PROTECTION                        | 0.00              | 29400.00        | 
| 2014               | AGRICULTURE | ANIMAL CARE RESERVE                           | 0.00              | 2000.00         | 
| 2014               | AGRICULTURE | ANIMAL HEALTH LABORATORY FEE                  | 0.00              | 752.00          | 
| 2014               | AGRICULTURE | AQUACULTURE MARKETING DEVELOPMENT             | 0.00              | 63.00           | 
| 2014               | AGRICULTURE | BOLL WEEVIL SUPPRESSION AND ERADICATION       | 0.00              | 250.00          | 
| 2014               | AGRICULTURE | COMMODITY COUNCIL MERCHANDISING               | 0.00              | 563.00          | 
| 2014               | AGRICULTURE | DEPARTMENT OF AGRICULTURE - FEDERAL AND OTHER | 0.00              | 9344.00         | 
| 2014               | AGRICULTURE | GENERAL REVENUE                               | 0.00              | 286959.00       | 
```