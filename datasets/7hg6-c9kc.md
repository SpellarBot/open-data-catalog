# Port of Los Angeles - Adopted Budget (Last 5 years)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/port-of-los-angeles-adopted-budget-last-5-years-5dc44) |
| Metadata | [Link](https://data.lacity.org/api/views/7hg6-c9kc) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/7hg6-c9kc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/7hg6-c9kc/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | 7hg6-c9kc |
| Name | Port of Los Angeles - Adopted Budget (Last 5 years) |
| Attribution | Port of Los Angeles |
| Category | A Well Run City |
| Tags | budget |
| Created | 2014-04-21T18:16:09Z |
| Publication Date | 2014-05-19T21:07:29Z |

## Description

Port of Los Angeles - Adopted Budget (Last 5 years)

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
series e:7hg6-c9kc d:2014-04-21T11:16:12.000Z t:fiscal_year=FY10 t:expense_categories=Salaries t:account_name="510 - Salaries - Regular" m:appropriation_amount=60782097

series e:7hg6-c9kc d:2014-04-21T11:16:12.000Z t:fiscal_year=FY10 t:expense_categories=Salaries t:account_name="511 - Salaries - Overtime" m:appropriation_amount=5015147

series e:7hg6-c9kc d:2014-04-21T11:16:12.000Z t:fiscal_year=FY10 t:expense_categories=Benefits t:account_name="516 - Employee Benefits" m:appropriation_amount=32911815
```

## Meta Commands

```ls
metric m:appropriation_amount p:integer l:"Appropriation Amount" t:dataTypeName=money

entity e:7hg6-c9kc l:"Port of Los Angeles - Adopted Budget (Last 5 years)" t:attribution="Port of Los Angeles" t:url=https://data.lacity.org/api/views/7hg6-c9kc

property e:7hg6-c9kc t:meta.view v:id=7hg6-c9kc v:category="A Well Run City" v:averageRating=0 v:name="Port of Los Angeles - Adopted Budget (Last 5 years)" v:attribution="Port of Los Angeles"

property e:7hg6-c9kc t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:7hg6-c9kc t:meta.view.owner v:id=2ib6-ssvz v:profileImageUrlMedium=/api/users/2ib6-ssvz/profile_images/THUMB v:profileImageUrlLarge=/api/users/2ib6-ssvz/profile_images/LARGE v:screenName="Port of Los Angeles" v:profileImageUrlSmall=/api/users/2ib6-ssvz/profile_images/TINY v:displayName="Port of Los Angeles"

property e:7hg6-c9kc t:meta.view.tableauthor v:id=2ib6-ssvz v:profileImageUrlMedium=/api/users/2ib6-ssvz/profile_images/THUMB v:profileImageUrlLarge=/api/users/2ib6-ssvz/profile_images/LARGE v:screenName="Port of Los Angeles" v:profileImageUrlSmall=/api/users/2ib6-ssvz/profile_images/TINY v:roleName=publisher v:displayName="Port of Los Angeles"
```

## Top Records

```ls
| :updated_at | fiscal_year | account_name                         | appropriation_amount | expense_categories | 
| =========== | =========== | ==================================== | ==================== | ================== | 
| 1398078972  | FY10        | 510 - Salaries - Regular             | 60782097             | Salaries           | 
| 1398078972  | FY10        | 511 - Salaries - Overtime            | 5015147              | Salaries           | 
| 1398078972  | FY10        | 516 - Employee Benefits              | 32911815             | Benefits           | 
| 1398078972  | FY10        | 517 - Paid Employee Benefits         | 1843854              | Benefits           | 
| 1398078972  | FY10        | 520 - Advertising & Public Relations | 3375458              | Expenditure        | 
| 1398078972  | FY10        | 521 - Domestic Trade Rep.            | 63000                | Expenditure        | 
| 1398078972  | FY10        | 522 - Foreign Trade Rep.             | 687163               | Expenditure        | 
| 1398078972  | FY10        | 530 - Domestic Travel                | 462833               | Expenditure        | 
| 1398078972  | FY10        | 531 - Foreign Travel                 | 362500               | Expenditure        | 
| 1398078972  | FY10        | 532 - Local Travel                   | 101200               | Expenditure        | 
```