# CTOSC - 2013 and 2014 Revenue

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ctosc-2013-and-2014-revenue) |
| Metadata | [Link](https://data.ct.gov/api/views/x768-ejfj) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/x768-ejfj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/x768-ejfj/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | x768-ejfj |
| Name | CTOSC - 2013 and 2014 Revenue |
| Created | 2015-05-13T19:51:26Z |
| Publication Date | 2015-06-15T17:41:51Z |

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | series tag     | ledger_type      | LEDGER_TYPE      | text      | text        |
| Yes      | time           | fiscal_year      | FISCAL_YEAR      | number    | number      |
| Yes      | series tag     | description      | DESCRIPTION      | text      | text        |
| Yes      | series tag     | account_descr    | ACCOUNT_DESCR    | text      | text        |
| Yes      | series tag     | revenue_category | REVENUE CATEGORY | text      | text        |
| Yes      | numeric metric | actual_amount    | ACTUAL_AMOUNT    | number    | number      |
| Yes      | series tag     | program_descr    | Program DESCR    | text      | text        |
| Yes      | series tag     | fund_type        | FUND_TYPE        | text      | text        |
| Yes      | series tag     | fund_descr       | FUND_DESCR       | text      | text        |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:x768-ejfj d:2015-01-01T00:00:00.000Z t:fund_type="Special Revenue" t:description="Other Revenue" t:program_descr="Federal Highway Safety Grants" t:ledger_type=Revenue t:revenue_category="Non General Fund Revenue" t:account_descr="Federal Aid  Restricted" t:fund_descr="Special Revenue" m:actual_amount=1589313.47

series e:x768-ejfj d:2016-01-01T00:00:00.000Z t:fund_type="Special Revenue" t:description="Other Revenue" t:program_descr="Soil Remed Sikorsky-EPA funds" t:ledger_type=Revenue t:revenue_category="Non General Fund Revenue" t:account_descr="Grant Transfer Fed Grant-Restr" t:fund_descr="Special Revenue" m:actual_amount=86102.16

series e:x768-ejfj d:2015-01-01T00:00:00.000Z t:fund_type="Special Revenue" t:description="Other Revenue" t:program_descr="CT SBIRT Program" t:ledger_type=Revenue t:revenue_category="Non General Fund Revenue" t:account_descr="Federal Aid  Restricted" t:fund_descr="Special Revenue" m:actual_amount=1300719.92
```

## Meta Commands

```ls
metric m:actual_amount p:double l:ACTUAL_AMOUNT t:dataTypeName=number

entity e:x768-ejfj l:"CTOSC - 2013 and 2014 Revenue" t:url=https://data.ct.gov/api/views/x768-ejfj

property e:x768-ejfj t:meta.view v:id=x768-ejfj v:averageRating=0 v:name="CTOSC - 2013 and 2014 Revenue"

property e:x768-ejfj t:meta.view.owner v:id=dx23-uz2k v:screenName=PSAdmin v:displayName=PSAdmin

property e:x768-ejfj t:meta.view.tableauthor v:id=dx23-uz2k v:screenName=PSAdmin v:roleName=editor v:displayName=PSAdmin
```

## Top Records

```ls
| ledger_type | fiscal_year | description   | account_descr                  | revenue_category         | actual_amount | program_descr                  | fund_type       | fund_descr      | 
| =========== | =========== | ============= | ============================== | ======================== | ============= | ============================== | =============== | =============== | 
| Revenue     | 2015        | Other Revenue | Federal Aid Restricted         | Non General Fund Revenue | 1589313.47    | Federal Highway Safety Grants  | Special Revenue | Special Revenue | 
| Revenue     | 2016        | Other Revenue | Grant Transfer Fed Grant-Restr | Non General Fund Revenue | 86102.16      | Soil Remed Sikorsky-EPA funds  | Special Revenue | Special Revenue | 
| Revenue     | 2015        | Other Revenue | Federal Aid Restricted         | Non General Fund Revenue | 1300719.92    | CT SBIRT Program               | Special Revenue | Special Revenue | 
| Revenue     | 2017        | Other Revenue | Federal Aid Restricted         | Non General Fund Revenue | 28693.07      | FOMA - ANG Environmental - 478 | Special Revenue | Special Revenue | 
| Revenue     | 2017        | Other Revenue | Private Donations              | Miscellaneous            | 400           | Revenue Deposits               | Other Budgeted  | Special Revenue | 
| Revenue     | 2015        | Other Revenue | Non-Federal Aid Restricted     | Non General Fund Revenue | 10000000      | SIF Stipulation & Reimbursmt   | Special Revenue | Special Revenue | 
| Revenue     | 2015        | Other Revenue | Grant Transfer Fed Grant-Restr | Non General Fund Revenue | 7500          | DV Training - 4 Fed Share      | Special Revenue | Special Revenue | 
| Revenue     | 2015        | Other Revenue | Federal Aid - Miscellaneous    | Federal Grants           | 12300         | Institutional Gen Welfare Fund | Special Revenue | Special Revenue | 
| Revenue     | 2015        | Other Revenue | Grant Transfer Fed Grant-Restr | Non General Fund Revenue | 417677.39     | Hist Prserv- Sandy Relief Admi | Special Revenue | Special Revenue | 
| Revenue     | 2015        | Other Revenue | Non-Federal Aid Restricted     | Non General Fund Revenue | 491350        | New Automobile Warranties Acct | Special Revenue | Special Revenue | 
```