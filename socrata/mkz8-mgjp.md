# Expenditures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/expenditures-2015-2014) |
| Metadata | [Link](https://data.hawaii.gov/api/views/mkz8-mgjp) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/mkz8-mgjp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/mkz8-mgjp/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | mkz8-mgjp |
| Name | Expenditures |
| Created | 2016-01-27T00:05:29Z |
| Publication Date | 2016-02-01T19:57:26Z |

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type     | Render Type   |
| ======== | ============== | ================== | ================== | ============= | ============= |
| No       |                | fiscal_year        | Fiscal_Year        | number        | text          |
| Yes      | numeric metric | fiscal_period      | Fiscal_Period      | number        | number        |
| Yes      | series tag     | department         | Department         | text          | text          |
| Yes      | series tag     | program            | Program            | text          | text          |
| Yes      | series tag     | expense_category   | Expense_Category   | text          | text          |
| Yes      | series tag     | fund               | Fund               | text          | text          |
| Yes      | series tag     | vendor_name        | Vendor_Name        | text          | text          |
| Yes      | series tag     | vendor_number      | Vendor_Number      | text          | text          |
| Yes      | series tag     | payment_number     | Payment_Number     | text          | text          |
| Yes      | series tag     | payment_method     | Payment_Method     | text          | text          |
| Yes      | time           | payment_issue_date | Payment_Issue_date | calendar_date | calendar_date |
| Yes      | series tag     | payment_status     | Payment_Status     | text          | text          |
| Yes      | numeric metric | amount             | Amount             | money         | money         |
```

## Time Field

```ls
Value = payment_issue_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = fiscal_year
```

## Data Commands

```ls
series e:mkz8-mgjp d:2014-07-31T00:00:00.000Z t:vendor_number=331736 t:program=LNR804 t:department="LAND AND NATURAL RESOURCES" t:payment_number=B0000428 t:expense_category="OPERATING SUPPLIES" t:payment_method=Check t:vendor_name="ALLIED PLASTIC LUMBER, LLC" t:payment_status=Paid m:amount=99793.17 m:fiscal_period=1

series e:mkz8-mgjp d:2014-11-19T00:00:00.000Z t:vendor_number=29765 t:program=LNR407 t:department="LAND AND NATURAL RESOURCES" t:payment_number=B0002180 t:expense_category="OPERATING SUPPLIES" t:payment_method=Check t:vendor_name="HAWAII MEGA-COR., INC." t:payment_status=Paid m:amount=71869.8 m:fiscal_period=5

series e:mkz8-mgjp d:2014-11-19T00:00:00.000Z t:vendor_number=29765 t:program=LNR407 t:department="LAND AND NATURAL RESOURCES" t:payment_number=B0002180 t:expense_category="OPERATING SUPPLIES" t:payment_method=Check t:vendor_name="HAWAII MEGA-COR., INC." t:payment_status=Paid m:amount=91359 m:fiscal_period=5
```

## Meta Commands

```ls
metric m:fiscal_period p:integer l:Fiscal_Period t:dataTypeName=number

metric m:amount p:double l:Amount t:dataTypeName=money

entity e:mkz8-mgjp l:Expenditures t:url=https://data.hawaii.gov/api/views/mkz8-mgjp

property e:mkz8-mgjp t:meta.view v:id=mkz8-mgjp v:averageRating=0 v:name=Expenditures

property e:mkz8-mgjp t:meta.view.owner v:id=wktp-67q4 v:screenName=karen v:displayName=karen

property e:mkz8-mgjp t:meta.view.tableauthor v:id=wktp-67q4 v:screenName=karen v:roleName=administrator v:displayName=karen
```

## Top Records

```ls
| fiscal_year | fiscal_period | department                 | program | expense_category   | fund | vendor_name                | vendor_number | payment_number | payment_method | payment_issue_date  | payment_status | amount    | 
| =========== | ============= | ========================== | ======= | ================== | ==== | ========================== | ============= | ============== | ============== | =================== | ============== | ========= | 
| 2015        | 1             | LAND AND NATURAL RESOURCES | LNR804  | OPERATING SUPPLIES |      | ALLIED PLASTIC LUMBER, LLC | 331736        | B0000428       | Check          | 2014-07-31T00:00:00 | Paid           | 99793.17  | 
| 2015        | 5             | LAND AND NATURAL RESOURCES | LNR407  | OPERATING SUPPLIES |      | HAWAII MEGA-COR., INC.     | 29765         | B0002180       | Check          | 2014-11-19T00:00:00 | Paid           | 71869.80  | 
| 2015        | 5             | LAND AND NATURAL RESOURCES | LNR407  | OPERATING SUPPLIES |      | HAWAII MEGA-COR., INC.     | 29765         | B0002180       | Check          | 2014-11-19T00:00:00 | Paid           | 91359.00  | 
| 2015        | 2             | LAND AND NATURAL RESOURCES | LNR172  | OPERATING SUPPLIES |      | HAWAII MEGA-COR., INC.     | 29765         | S0008656       | Check          | 2014-08-18T00:00:00 | Paid           | 33702.37  | 
| 2015        | 2             | LAND AND NATURAL RESOURCES | LNR407  | OPERATING SUPPLIES |      | HAWAII MEGA-COR., INC.     | 29765         | S0009527       | Check          | 2014-08-22T00:00:00 | Paid           | 87297.92  | 
| 2015        | 2             | LAND AND NATURAL RESOURCES | LNR407  | OPERATING SUPPLIES |      | HAWAII MEGA-COR., INC.     | 29765         | S0009527       | Check          | 2014-08-22T00:00:00 | Paid           | 250000.00 | 
| 2015        | 6             | LAND AND NATURAL RESOURCES | LNR407  | OPERATING SUPPLIES |      | HAWAII MEGA-COR., INC.     | 29765         | S0037439       | Check          | 2014-12-30T00:00:00 | Paid           | 101015.87 | 
| 2014        | 7             | LAND AND NATURAL RESOURCES | LNR407  | OPERATING SUPPLIES |      | HAWAII MEGA-COR., INC.     | 29765         | S0041784       | Check          | 2014-01-22T00:00:00 | Paid           | 189946.65 | 
| 2015        | 1             | PUBLIC SAFETY              | PSD420  | OPERATING SUPPLIES |      | TOUCH LEGAL, INC.          | 279573        | G0008765       | Check          | 2014-07-31T00:00:00 | Paid           | 31333.92  | 
| 2015        | 1             | PUBLIC SAFETY              | PSD420  | OPERATING SUPPLIES |      | TOUCH LEGAL, INC.          | 279573        | G0008765       | Check          | 2014-07-31T00:00:00 | Paid           | 44011.56  | 
```