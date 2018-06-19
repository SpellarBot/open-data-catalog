# Connecticut Higher Education Supplemental Loan Authority Financial Data FY 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/connecticut-higher-education-supplemental-loan-authority-financial-data-fy-2015) |
| Metadata | [Link](https://data.ct.gov/api/views/aawr-mzex) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/aawr-mzex/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/aawr-mzex/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | aawr-mzex |
| Name | Connecticut Higher Education Supplemental Loan Authority Financial Data FY 2015 |
| Attribution | Connecticut Higher Education Supplemental Loan Authority |
| Tags | transparency, checkbook, vendor payments, quasi |
| Created | 2016-07-05T17:43:06Z |
| Publication Date | 2016-07-05T17:45:02Z |

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type     | Render Type   |
| ======== | ============== | ================ | ================ | ============= | ============= |
| Yes      | series tag     | fund             | Fund             | text          | text          |
| Yes      | series tag     | vendor_id        | Vendor ID        | text          | number        |
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
series e:aawr-mzex d:2015-06-11T00:00:00.000Z t:vendor="21st Century Media - CT" t:expense_category="Bond Issue Receivable" t:fund="General Fund" t:vendor_id=3 m:amount=702

series e:aawr-mzex d:2014-07-31T00:00:00.000Z t:vendor="AA System" t:expense_category="Maint Svc Contracts" t:fund="General Fund" t:vendor_id=2 m:amount=59.55

series e:aawr-mzex d:2014-08-29T00:00:00.000Z t:vendor="AA System" t:expense_category="Maint Svc Contracts" t:fund="General Fund" t:vendor_id=2 m:amount=59.55
```

## Meta Commands

```ls
metric m:amount p:double l:Amount t:dataTypeName=money

entity e:aawr-mzex l:"Connecticut Higher Education Supplemental Loan Authority Financial Data FY 2015" t:attribution="Connecticut Higher Education Supplemental Loan Authority" t:url=https://data.ct.gov/api/views/aawr-mzex

property e:aawr-mzex t:meta.view v:id=aawr-mzex v:attributionLink=http://www.chesla.org/ v:averageRating=0 v:name="Connecticut Higher Education Supplemental Loan Authority Financial Data FY 2015" v:attribution="Connecticut Higher Education Supplemental Loan Authority"

property e:aawr-mzex t:meta.view.owner v:id=xhf5-s5a4 v:screenName="Office of the State Comptroller" v:displayName="Office of the State Comptroller"

property e:aawr-mzex t:meta.view.tableauthor v:id=xhf5-s5a4 v:screenName="Office of the State Comptroller" v:roleName=publisher v:displayName="Office of the State Comptroller"
```

## Top Records

```ls
| fund         | vendor_id | vendor                  | expense_category      | payment_date        | amount | 
| ============ | ========= | ======================= | ===================== | =================== | ====== | 
| General Fund | 3         | 21st Century Media - CT | Bond Issue Receivable | 2015-06-11T00:00:00 | 702    | 
| General Fund | 2         | AA System               | Maint Svc Contracts   | 2014-07-31T00:00:00 | 59.55  | 
| General Fund | 2         | AA System               | Maint Svc Contracts   | 2014-08-29T00:00:00 | 59.55  | 
| General Fund | 2         | AA System               | Maint Svc Contracts   | 2014-09-30T00:00:00 | 84.24  | 
| General Fund | 2         | AA System               | Maint Svc Contracts   | 2014-10-31T00:00:00 | 59.55  | 
| General Fund | 2         | AA System               | Maint Svc Contracts   | 2014-11-30T00:00:00 | 59.55  | 
| General Fund | 2         | AA System               | Maint Svc Contracts   | 2014-12-31T00:00:00 | 83.4   | 
| General Fund | 2         | AA System               | Maint Svc Contracts   | 2015-02-27T00:00:00 | 59.55  | 
| General Fund | 2         | AA System               | Maint Svc Contracts   | 2015-03-31T00:00:00 | 80.81  | 
| General Fund | 2         | AA System               | Maint Svc Contracts   | 2015-04-30T00:00:00 | 59.55  | 
```