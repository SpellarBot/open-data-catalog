# Bad Debt Expense

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bad-debt-expense) |
| Metadata | [Link](https://data.austintexas.gov/api/views/6zan-sbz2) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/6zan-sbz2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/6zan-sbz2/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 6zan-sbz2 |
| Name | Bad Debt Expense |
| Attribution | Austin Energy |
| Category | Utility |
| Tags | "bad debt", debt, "money owed" |
| Created | 2015-08-18T15:19:37Z |
| Publication Date | 2016-09-12T19:22:47Z |

## Description

Bad Debt Expense

Bad debt expense is an estimate of the amount of revenue billed in any fiscal year that is not collected. The FY 2013 bad debt expense represents a final, audited number based on an analysis of collectability. Austin Energy has experienced growth in receivable balances for active accounts due to a postponement of utility cut-offs for delinquent payment during Austin Energy?s transition to the new customer billing system.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| No       | time           | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag     | fiscal_year      | Fiscal Year      | text      | text        |
| Yes      | numeric metric | revenue          | Revenue          | money     | money       |
| Yes      | numeric metric | bad_debt_expense | Bad Debt Expense | money     | money       |
| Yes      | numeric metric | percentage       | Percentage       | percent   | percent     |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:6zan-sbz2 d:2015-08-18T08:19:45.000Z t:fiscal_year="FY 2013" m:bad_debt_expense=17300000 m:percentage=1.32 m:revenue=1305500000

series e:6zan-sbz2 d:2015-08-18T08:19:45.000Z t:fiscal_year="FY 2012" m:bad_debt_expense=3500000 m:percentage=0.3 m:revenue=1183400000

series e:6zan-sbz2 d:2015-08-18T08:19:45.000Z t:fiscal_year="FY 2011" m:bad_debt_expense=3500000 m:percentage=0.27 m:revenue=1252700000
```

## Meta Commands

```ls
metric m:revenue p:integer l:Revenue t:dataTypeName=money

metric m:bad_debt_expense p:integer l:"Bad Debt Expense" t:dataTypeName=money

metric m:percentage p:float l:Percentage t:dataTypeName=percent

entity e:6zan-sbz2 l:"Bad Debt Expense" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/6zan-sbz2

property e:6zan-sbz2 t:meta.view v:id=6zan-sbz2 v:category=Utility v:averageRating=0 v:name="Bad Debt Expense" v:attribution="Austin Energy"

property e:6zan-sbz2 t:meta.view.license v:name="Public Domain"

property e:6zan-sbz2 t:meta.view.owner v:id=fxfz-wsmq v:profileImageUrlMedium=/api/users/fxfz-wsmq/profile_images/THUMB v:profileImageUrlLarge=/api/users/fxfz-wsmq/profile_images/LARGE v:screenName="Shannon Wisner" v:profileImageUrlSmall=/api/users/fxfz-wsmq/profile_images/TINY v:displayName="Shannon Wisner"

property e:6zan-sbz2 t:meta.view.tableauthor v:id=fxfz-wsmq v:profileImageUrlMedium=/api/users/fxfz-wsmq/profile_images/THUMB v:profileImageUrlLarge=/api/users/fxfz-wsmq/profile_images/LARGE v:screenName="Shannon Wisner" v:profileImageUrlSmall=/api/users/fxfz-wsmq/profile_images/TINY v:roleName=publisher v:displayName="Shannon Wisner"
```

## Top Records

```ls
| :updated_at | fiscal_year | revenue    | bad_debt_expense | percentage | 
| =========== | =========== | ========== | ================ | ========== | 
| 1439885985  | FY 2013     | 1305500000 | 17300000         | 1.32       | 
| 1439885985  | FY 2012     | 1183400000 | 3500000          | 0.30       | 
| 1439885985  | FY 2011     | 1252700000 | 3500000          | 0.27       | 
| 1439885985  | FY 2010     | 1151800000 | 4200000          | 0.37       | 
| 1439885985  | FY 2009     | 1165900000 | 3600000          | 0.31       | 
| 1439885985  | FY 2008     | 1219800000 | 2100000          | 0.17       | 
| 1439885985  | FY 2007     | 1060000000 | 3500000          | 0.33       | 
| 1439885985  | FY 2006     | 1075900000 | 5300000          | 0.49       | 
| 1473708096  | FY 2014     | 1388000000 | 20900000         | 1.5        | 
| 1473708128  | FY 2015     | 1359900000 | 8500000          | 0.63       | 
```