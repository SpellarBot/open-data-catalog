# Connecticut Student Loan Foundation Financial Data FY 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/connecticut-student-loan-foundation-financial-data-fy-2015) |
| Metadata | [Link](https://data.ct.gov/api/views/azij-cs9u) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/azij-cs9u/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/azij-cs9u/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | azij-cs9u |
| Name | Connecticut Student Loan Foundation Financial Data FY 2015 |
| Attribution | Connecticut Student Loan Foundation |
| Tags | transparency, checkbook, vendor payments, quasi |
| Created | 2016-07-05T17:23:50Z |
| Publication Date | 2016-07-05T17:27:07Z |

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type     | Render Type   |
| ======== | ============== | ================ | ================ | ============= | ============= |
| Yes      | series tag     | fund             | Fund             | text          | text          |
| Yes      | series tag     | vendor           | Vendor           | text          | text          |
| Yes      | series tag     | expense_category | Expense Category | text          | text          |
| Yes      | time           | payment_date     | Payment Date     | calendar_date | calendar_date |
| Yes      | numeric metric | amount           | Amount           | money         | money         |
```

## Time Field

```ls
Value = payment_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:azij-cs9u d:2015-03-06T00:00:00.000Z t:vendor=CHEFA t:expense_category="MEETINGS & WORKSHOPS" t:fund="General Fund" m:amount=373.92

series e:azij-cs9u d:2015-05-11T00:00:00.000Z t:vendor=CHEFA t:expense_category="MEETINGS & WORKSHOPS" t:fund="General Fund" m:amount=145.46

series e:azij-cs9u d:2014-12-16T00:00:00.000Z t:vendor="CohnReznick LLP" t:expense_category=ACCOUNTING t:fund="General Fund" m:amount=30000
```

## Meta Commands

```ls
metric m:amount p:double l:Amount t:dataTypeName=money

entity e:azij-cs9u l:"Connecticut Student Loan Foundation Financial Data FY 2015" t:attribution="Connecticut Student Loan Foundation" t:url=https://data.ct.gov/api/views/azij-cs9u

property e:azij-cs9u t:meta.view v:id=azij-cs9u v:attributionLink=http://www.cslf.com/ v:averageRating=0 v:name="Connecticut Student Loan Foundation Financial Data FY 2015" v:attribution="Connecticut Student Loan Foundation"

property e:azij-cs9u t:meta.view.owner v:id=xhf5-s5a4 v:screenName="Office of the State Comptroller" v:displayName="Office of the State Comptroller"

property e:azij-cs9u t:meta.view.tableauthor v:id=xhf5-s5a4 v:screenName="Office of the State Comptroller" v:roleName=publisher v:displayName="Office of the State Comptroller"
```

## Top Records

```ls
| fund         | vendor                           | expense_category     | payment_date        | amount   | 
| ============ | ================================ | ==================== | =================== | ======== | 
| General Fund | CHEFA                            | MEETINGS & WORKSHOPS | 2015-03-06T00:00:00 | 373.92   | 
| General Fund | CHEFA                            | MEETINGS & WORKSHOPS | 2015-05-11T00:00:00 | 145.46   | 
| General Fund | CohnReznick LLP                  | ACCOUNTING           | 2014-12-16T00:00:00 | 30000.00 | 
| General Fund | CohnReznick LLP                  | ACCOUNTING           | 2015-03-20T00:00:00 | 18550.00 | 
| General Fund | CohnReznick LLP                  | ACCOUNTING           | 2015-04-21T00:00:00 | 10400.00 | 
| General Fund | Education Solution Partners, LLC | CONTRACT SERVICES    | 2014-07-01T00:00:00 | 37000.00 | 
| General Fund | Education Solution Partners, LLC | TRAVEL               | 2014-07-01T00:00:00 | 1892.03  | 
| General Fund | Education Solution Partners, LLC | OFFICE               | 2014-08-05T00:00:00 | 454.05   | 
| General Fund | Education Solution Partners, LLC | TRAVEL               | 2014-08-05T00:00:00 | 1810.04  | 
| General Fund | Education Solution Partners, LLC | CONTRACT SERVICES    | 2014-08-05T00:00:00 | 37000.00 | 
```