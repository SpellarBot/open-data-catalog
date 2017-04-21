# Hawaii Operating Budget

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hawaii-operating-budget) |
| Metadata | [Link](https://data.hawaii.gov/api/views/p8xe-w4xh) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/p8xe-w4xh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/p8xe-w4xh/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | p8xe-w4xh |
| Name | Hawaii Operating Budget |
| Created | 2015-02-02T16:55:27Z |
| Publication Date | 2016-02-03T21:50:02Z |

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| Yes      | time           | fiscal_year        | Fiscal Year        | number    | number      |
| Yes      | series tag     | service            | Service            | text      | text        |
| Yes      | series tag     | department         | Department         | text      | text        |
| Yes      | series tag     | program            | Program            | text      | text        |
| Yes      | series tag     | expense_category   | Expense Category   | text      | text        |
| Yes      | numeric metric | recommended_amount | Recommended Amount | money     | money       |
| Yes      | numeric metric | approved_amount    | Approved Amount    | money     | money       |
| Yes      | series tag     | fund               | Fund               | text      | text        |
| Yes      | series tag     | fund_type          | Fund Type          | text      | text        |
| Yes      | series tag     | description        | Description        | text      | text        |
| Yes      | series tag     | expense_type       | Expense Type       | text      | text        |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:p8xe-w4xh d:2015-01-01T00:00:00.000Z t:fund_type="Tax Supported" t:expense_type="PERSONNEL COST" t:description="INVESTIGATOR V 117553" t:program=ATG100AJ t:department="LEGAL SERVICES" t:service="DEPARTMENT OF ATTORNEY GENERAL" t:expense_category="Personal Services" t:fund="General Fund" m:approved_amount=0 m:recommended_amount=0

series e:p8xe-w4xh d:2015-01-01T00:00:00.000Z t:fund_type="Tax Supported" t:expense_type="PERSONNEL COST" t:description="INVESTIGATOR V 118775" t:program=ATG100AJ t:department="LEGAL SERVICES" t:service="DEPARTMENT OF ATTORNEY GENERAL" t:expense_category="Personal Services" t:fund="General Fund" m:approved_amount=0 m:recommended_amount=0

series e:p8xe-w4xh d:2015-01-01T00:00:00.000Z t:fund_type="Tax Supported" t:expense_type="PERSONNEL COST" t:description="ACCOUNT CLERK III 40288" t:program=ATG100AJ t:department="LEGAL SERVICES" t:service="DEPARTMENT OF ATTORNEY GENERAL" t:expense_category="Personal Services" t:fund="Other Federal Funds" m:approved_amount=25059 m:recommended_amount=0
```

## Meta Commands

```ls
metric m:recommended_amount p:integer l:"Recommended Amount" t:dataTypeName=money

metric m:approved_amount p:integer l:"Approved Amount" t:dataTypeName=money

entity e:p8xe-w4xh l:"Hawaii Operating Budget" t:url=https://data.hawaii.gov/api/views/p8xe-w4xh

property e:p8xe-w4xh t:meta.view v:id=p8xe-w4xh v:averageRating=0 v:name="Hawaii Operating Budget"

property e:p8xe-w4xh t:meta.view.owner v:id=n97x-2qif v:screenName="Tim Wang" v:displayName="Tim Wang"

property e:p8xe-w4xh t:meta.view.tableauthor v:id=n97x-2qif v:screenName="Tim Wang" v:displayName="Tim Wang"
```

## Top Records

```ls
| fiscal_year | service                        | department                                   | program  | expense_category  | recommended_amount | approved_amount | fund                         | fund_type     | description                      | expense_type   | 
| =========== | ============================== | ============================================ | ======== | ================= | ================== | =============== | ============================ | ============= | ================================ | ============== | 
| 2015        | DEPARTMENT OF ATTORNEY GENERAL | LEGAL SERVICES                               | ATG100AJ | Personal Services | 0                  | 0               | General Fund                 | Tax Supported | INVESTIGATOR V 117553            | PERSONNEL COST | 
| 2015        | DEPARTMENT OF ATTORNEY GENERAL | LEGAL SERVICES                               | ATG100AJ | Personal Services | 0                  | 0               | General Fund                 | Tax Supported | INVESTIGATOR V 118775            | PERSONNEL COST | 
| 2015        | DEPARTMENT OF ATTORNEY GENERAL | LEGAL SERVICES                               | ATG100AJ | Personal Services | 0                  | 25059           | Other Federal Funds          | Tax Supported | ACCOUNT CLERK III 40288          | PERSONNEL COST | 
| 2015        | DEPARTMENT OF ATTORNEY GENERAL | LEGAL SERVICES                               | ATG100AJ | Personal Services | 0                  | 10525           | Other Federal Funds          | Tax Supported | FRINGE BENEFIT - PRIORITY 6C 958 | PERSONNEL COST | 
| 2015        | DEPARTMENT OF ATTORNEY GENERAL | LEGAL SERVICES                               | ATG100AJ | Personal Services | 0                  | 0               | Other Federal Funds          | Tax Supported | DEPUTY SALARY INCREASE 998       | PERSONNEL COST | 
| 2015        | DEPARTMENT OF ATTORNEY GENERAL | LEGAL SERVICES                               | ATG100AJ | Personal Services | 0                  | 0               | Special Funds                | Tax Supported | INVESTIGATOR V 117553            | PERSONNEL COST | 
| 2015        | DEPARTMENT OF ATTORNEY GENERAL | LEGAL SERVICES                               | ATG100AJ | Personal Services | 0                  | 10779           | Special Funds                | Tax Supported | FRINGE BENEFIT-PRIORITY 10 968   | PERSONNEL COST | 
| 2015        | DEPARTMENT OF ATTORNEY GENERAL | LEGAL SERVICES                               | ATG100AJ | Personal Services | 0                  | 0               | Special Funds                | Tax Supported | INVESTIGATOR V 118101            | PERSONNEL COST | 
| 2015        | DEPARTMENT OF ATTORNEY GENERAL | LEGAL SERVICES                               | ATG100AJ | Personal Services | 0                  | 25657           | Special Funds                | Tax Supported | INVESTIGATOR V 118775            | PERSONNEL COST | 
| 2015        | DEPARTMENT OF ATTORNEY GENERAL | STATE CRIMINAL JUSTICE INFO & IDENTIFICATION | ATG231BD | Personal Services | 0                  | 28000           | Inter-departmental Transfers | Tax Supported | RAP BACK PROGRAM CLERK 992001    | PERSONNEL COST | 
```