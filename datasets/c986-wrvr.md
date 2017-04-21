# Hartford: Operating Budget

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hartford-operating-budget) |
| Metadata | [Link](https://data.hartford.gov/api/views/c986-wrvr) |
| Data: JSON | [100 Rows](https://data.hartford.gov/api/views/c986-wrvr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hartford.gov/api/views/c986-wrvr/rows.csv?max_rows=100) |
| Host | data.hartford.gov |
| Id | c986-wrvr |
| Name | Hartford: Operating Budget |
| Attribution | City of Hartford |
| Category | Financial |
| Created | 2015-01-09T15:23:17Z |
| Publication Date | 2015-03-12T22:34:28Z |

## Description

This data set is used to populate the operating budget on budget.hartford.gov

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
series e:c986-wrvr d:2015-01-01T00:00:00.000Z t:fund_type="Tax Supported" t:expense_type="Personnel Cost" t:description="REGULAR PAYROLL 1ST SHIFT" t:program=ADMINISTRATION t:department=MHIS t:service="General Government" t:expense_category=SALARIES/WAGES t:fund="Metro Hartford Information Services" m:approved_amount=340414 m:recommended_amount=340414

series e:c986-wrvr d:2015-01-01T00:00:00.000Z t:fund_type="Tax Supported" t:expense_type="Personnel Cost" t:description="PERMANENT PART TIME" t:program="APPLICATION ENGINEERING" t:department=MHIS t:service="General Government" t:expense_category=SALARIES/WAGES t:fund="Metro Hartford Information Services" m:approved_amount=35000 m:recommended_amount=35000

series e:c986-wrvr d:2015-01-01T00:00:00.000Z t:fund_type="Tax Supported" t:expense_type="Personnel Cost" t:description="PAYROLL REDUCTION TARGET" t:program="MHIS NETWORK OPERATIONS" t:department=MHIS t:service="General Government" t:expense_category=SALARIES/WAGES t:fund="Metro Hartford Information Services" m:approved_amount=-60000 m:recommended_amount=0
```

## Meta Commands

```ls
metric m:recommended_amount p:double l:"Recommended Amount" t:dataTypeName=money

metric m:approved_amount p:double l:"Approved Amount" t:dataTypeName=money

entity e:c986-wrvr l:"Hartford: Operating Budget" t:attribution="City of Hartford" t:url=https://data.hartford.gov/api/views/c986-wrvr

property e:c986-wrvr t:meta.view v:id=c986-wrvr v:category=Financial v:attributionLink=http://www.hartford.gov v:averageRating=0 v:name="Hartford: Operating Budget" v:attribution="City of Hartford"

property e:c986-wrvr t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:c986-wrvr t:meta.view.owner v:id=cdqe-xcn5 v:screenName=Brett v:displayName=Brett

property e:c986-wrvr t:meta.view.tableauthor v:id=cdqe-xcn5 v:screenName=Brett v:roleName=administrator v:displayName=Brett
```

## Top Records

```ls
| fiscal_year | service            | department | program                   | expense_category     | recommended_amount | approved_amount | fund                                | fund_type     | description               | expense_type      | 
| =========== | ================== | ========== | ========================= | ==================== | ================== | =============== | =================================== | ============= | ========================= | ================= | 
| 2015        | General Government | MHIS       | ADMINISTRATION            | SALARIES/WAGES       | 340414             | 340414          | Metro Hartford Information Services | Tax Supported | REGULAR PAYROLL 1ST SHIFT | Personnel Cost    | 
| 2015        | General Government | MHIS       | APPLICATION ENGINEERING   | SALARIES/WAGES       | 35000              | 35000           | Metro Hartford Information Services | Tax Supported | PERMANENT PART TIME       | Personnel Cost    | 
| 2015        | General Government | MHIS       | MHIS NETWORK OPERATIONS   | SALARIES/WAGES       | 0                  | -60000          | Metro Hartford Information Services | Tax Supported | PAYROLL REDUCTION TARGET  | Personnel Cost    | 
| 2015        | General Government | MHIS       | MHIS BOE SUPPORT SERVICES | DEBT SVC & MISC      | 500                | 500             | Metro Hartford Information Services | Tax Supported | ATTEND AT PROF CONV/CONF  | Operating Expense | 
| 2015        | General Government | MHIS       | MHIS BOE SUPPORT SERVICES | OTHER PURCH SVC      | 2500               | 2500            | Metro Hartford Information Services | Tax Supported | MILEAGE & TRAV ALLOW-CITY | Operating Expense | 
| 2015        | General Government | MHIS       | MHIS BOE SUPPORT SERVICES | SUPPLIES             | 1500               | 1500            | Metro Hartford Information Services | Tax Supported | GENERAL OFFICE SUPPLIES   | Operating Expense | 
| 2015        | General Government | MHIS       | MHIS BOE SUPPORT SERVICES | PURCH PROF & TECH SV | 5000               | 5000            | Metro Hartford Information Services | Tax Supported | STAFF TRAINING SERVICES   | Operating Expense | 
| 2015        | General Government | MHIS       | MHIS BOE SUPPORT SERVICES | PURCH PROF & TECH SV | 5000               | 5000            | Metro Hartford Information Services | Tax Supported | EQUIPMENT MAINT & REPAIRS | Operating Expense | 
| 2015        | General Government | MHIS       | MHIS BOE SUPPORT SERVICES | PURCH PROPERTY SVC   | 225678             | 225678          | Metro Hartford Information Services | Tax Supported | SOFTWARE MAINT SERV CONTR | Operating Expense | 
| 2015        | General Government | MHIS       | MHIS BOE SUPPORT SERVICES | SALARIES/WAGES       | 639875             | 639875          | Metro Hartford Information Services | Tax Supported | REGULAR PAYROLL           | Personnel Cost    | 
```