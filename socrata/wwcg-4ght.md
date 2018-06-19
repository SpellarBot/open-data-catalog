# FundSpending

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fundspending) |
| Metadata | [Link](https://data.wa.gov/api/views/wwcg-4ght) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/wwcg-4ght/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/wwcg-4ght/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | wwcg-4ght |
| Name | FundSpending |
| Created | 2015-08-11T17:04:01Z |
| Publication Date | 2015-08-11T17:26:37Z |

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | time           | year            | Year            | number    | text        |
| Yes      | numeric metric | tax_revenues    | Tax Revenues    | money     | money       |
| Yes      | numeric metric | loan_repayments | Loan Repayments | money     | money       |
| Yes      | numeric metric | expenditurres   | Expenditurres   | money     | money       |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
```

## Meta Commands

```ls
metric m:tax_revenues p:double l:"Tax Revenues" t:dataTypeName=money

metric m:loan_repayments p:double l:"Loan Repayments" t:dataTypeName=money

metric m:expenditurres p:double l:Expenditurres t:dataTypeName=money

entity e:wwcg-4ght l:FundSpending t:url=https://data.wa.gov/api/views/wwcg-4ght

property e:wwcg-4ght t:meta.view v:id=wwcg-4ght v:averageRating=0 v:name=FundSpending

property e:wwcg-4ght t:meta.view.owner v:id=7b3t-6m6i v:screenName=Rodney v:displayName=Rodney

property e:wwcg-4ght t:meta.view.tableauthor v:id=7b3t-6m6i v:screenName=Rodney v:roleName=designer v:displayName=Rodney
```

## Top Records

```ls
| year | tax_revenues | loan_repayments | expenditurres | 
| ==== | ============ | =============== | ============= | 
| 2015 |              |                 |               | 
| 2014 |              |                 |               | 
| 2013 |              |                 |               | 
| 2012 |              |                 |               | 
| 2011 |              |                 |               | 
| 2010 |              |                 |               | 
| 2009 |              |                 |               | 
| 2008 |              |                 |               | 
| 2007 |              |                 |               | 
| 2006 |              |                 |               | 
```