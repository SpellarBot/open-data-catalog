# Connecticut Health and Educational Facilities Authority Financial Data FY 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/connecticut-health-and-educational-facilities-authority-financial-data-fy-2015) |
| Metadata | [Link](https://data.ct.gov/api/views/vbh5-6zqp) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/vbh5-6zqp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/vbh5-6zqp/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | vbh5-6zqp |
| Name | Connecticut Health and Educational Facilities Authority Financial Data FY 2015 |
| Attribution | Connecticut Health and Educational Facilities Authority |
| Tags | transparency, checkbook, vendor payments, quasi |
| Created | 2016-07-05T17:54:15Z |
| Publication Date | 2016-07-05T17:58:35Z |

## Description

Includes checkbook level vendor payment data for fiscal year 2015

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
series e:vbh5-6zqp d:2014-08-13T00:00:00.000Z t:vendor="21st Century Media-Connecticut" t:expense_category="Issuance Expense" t:fund="General Fund" t:vendor_id=691 m:amount=2340

series e:vbh5-6zqp d:2015-03-13T00:00:00.000Z t:vendor="21st Century Media-Connecticut" t:expense_category="Issuance Expense" t:fund="General Fund" t:vendor_id=691 m:amount=2808

series e:vbh5-6zqp d:2014-07-15T00:00:00.000Z t:vendor="A & A Office Systems Inc" t:expense_category="Maint Svc Contracts" t:fund="General Fund" t:vendor_id=2 m:amount=70.27
```

## Meta Commands

```ls
metric m:amount p:double l:Amount t:dataTypeName=money

entity e:vbh5-6zqp l:"Connecticut Health and Educational Facilities Authority Financial Data FY 2015" t:attribution="Connecticut Health and Educational Facilities Authority" t:url=https://data.ct.gov/api/views/vbh5-6zqp

property e:vbh5-6zqp t:meta.view v:id=vbh5-6zqp v:attributionLink=https://www.chefa.com/ v:averageRating=0 v:name="Connecticut Health and Educational Facilities Authority Financial Data FY 2015" v:attribution="Connecticut Health and Educational Facilities Authority"

property e:vbh5-6zqp t:meta.view.owner v:id=xhf5-s5a4 v:screenName="Office of the State Comptroller" v:displayName="Office of the State Comptroller"

property e:vbh5-6zqp t:meta.view.tableauthor v:id=xhf5-s5a4 v:screenName="Office of the State Comptroller" v:roleName=publisher v:displayName="Office of the State Comptroller"
```

## Top Records

```ls
| fund         | vendor_id | vendor                         | expense_category    | payment_date        | amount | 
| ============ | ========= | ============================== | =================== | =================== | ====== | 
| General Fund | 691       | 21st Century Media-Connecticut | Issuance Expense    | 2014-08-13T00:00:00 | 2340   | 
| General Fund | 691       | 21st Century Media-Connecticut | Issuance Expense    | 2015-03-13T00:00:00 | 2808   | 
| General Fund | 2         | A & A Office Systems Inc       | Maint Svc Contracts | 2014-07-15T00:00:00 | 70.27  | 
| General Fund | 2         | A & A Office Systems Inc       | Maint Svc Contracts | 2014-08-13T00:00:00 | 439.59 | 
| General Fund | 2         | A & A Office Systems Inc       | Maint Svc Contracts | 2014-08-28T00:00:00 | 318.66 | 
| General Fund | 2         | A & A Office Systems Inc       | Maint Svc Contracts | 2014-09-11T00:00:00 | 128.09 | 
| General Fund | 2         | A & A Office Systems Inc       | Maint Svc Contracts | 2014-10-09T00:00:00 | 407.33 | 
| General Fund | 2         | A & A Office Systems Inc       | Maint Svc Contracts | 2014-10-30T00:00:00 | 339.14 | 
| General Fund | 2         | A & A Office Systems Inc       | Maint Svc Contracts | 2014-11-13T00:00:00 | 32.94  | 
| General Fund | 2         | A & A Office Systems Inc       | Maint Svc Contracts | 2014-12-04T00:00:00 | 393.29 | 
```