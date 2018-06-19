# Port Of Los Angeles - Adopted Budget Last 5 Years

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/port-of-los-angeles-adopted-budget-last-5-years) |
| Metadata | [Link](https://data.lacity.org/api/views/du8q-hww5) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/du8q-hww5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/du8q-hww5/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | du8q-hww5 |
| Name | Port Of Los Angeles - Adopted Budget Last 5 Years |
| Category | A Well Run City |
| Tags | pola, port, budget, adopted |
| Created | 2014-04-22T16:30:05Z |
| Publication Date | 2015-12-07T20:29:27Z |

## Description

POLA adopted budget for last 5 years.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| No       | time           | :updated_at          | updated_at           | meta_data | meta_data   |
| Yes      | series tag     | fiscal_year          | Fiscal Year          | text      | text        |
| Yes      | series tag     | account_name         | Account Name         | text      | text        |
| Yes      | numeric metric | appropriation_amount | Appropriation Amount | money     | money       |
| Yes      | series tag     | expense_categories   | Expense Categories   | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:du8q-hww5 d:2014-04-22T09:30:08.000Z t:fiscal_year=FY10 t:expense_categories=Salaries t:account_name="510 - Salaries - Regular" m:appropriation_amount=60782097

series e:du8q-hww5 d:2014-04-22T09:30:08.000Z t:fiscal_year=FY10 t:expense_categories=Salaries t:account_name="511 - Salaries - Overtime" m:appropriation_amount=5015147

series e:du8q-hww5 d:2014-04-22T09:30:08.000Z t:fiscal_year=FY10 t:expense_categories=Benefits t:account_name="516 - Employee Benefits" m:appropriation_amount=32911815
```

## Meta Commands

```ls
metric m:appropriation_amount p:double l:"Appropriation Amount" t:dataTypeName=money

entity e:du8q-hww5 l:"Port Of Los Angeles - Adopted Budget Last 5 Years" t:url=https://data.lacity.org/api/views/du8q-hww5

property e:du8q-hww5 t:meta.view v:id=du8q-hww5 v:category="A Well Run City" v:averageRating=0 v:name="Port Of Los Angeles - Adopted Budget Last 5 Years"

property e:du8q-hww5 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:du8q-hww5 t:meta.view.owner v:id=xy7d-fki2 v:screenName="Jessica Carsten" v:displayName="Jessica Carsten"

property e:du8q-hww5 t:meta.view.tableauthor v:id=xy7d-fki2 v:screenName="Jessica Carsten" v:displayName="Jessica Carsten"
```

## Top Records

```ls
| :updated_at | fiscal_year | account_name                         | appropriation_amount | expense_categories | 
| =========== | =========== | ==================================== | ==================== | ================== | 
| 1398159008  | FY10        | 510 - Salaries - Regular             | 60782097.00          | Salaries           | 
| 1398159008  | FY10        | 511 - Salaries - Overtime            | 5015147.00           | Salaries           | 
| 1398159008  | FY10        | 516 - Employee Benefits              | 32911815.00          | Benefits           | 
| 1398159008  | FY10        | 517 - Paid Employee Benefits         | 1843854.00           | Benefits           | 
| 1398159008  | FY10        | 520 - Advertising & Public Relations | 3375458.00           | Expenditure        | 
| 1398159008  | FY10        | 521 - Domestic Trade Rep.            | 63000.00             | Expenditure        | 
| 1398159008  | FY10        | 522 - Foreign Trade Rep.             | 687163.00            | Expenditure        | 
| 1398159008  | FY10        | 530 - Domestic Travel                | 462833.00            | Expenditure        | 
| 1398159008  | FY10        | 531 - Foreign Travel                 | 362500.00            | Expenditure        | 
| 1398159008  | FY10        | 532 - Local Travel                   | 101200.00            | Expenditure        | 
```