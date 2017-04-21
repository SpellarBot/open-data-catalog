# Connecticut Green Bank Checkbook Financial Data FY 15

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/connecticut-green-bank-checkbook-financial-data-fy-15) |
| Metadata | [Link](https://data.ct.gov/api/views/digc-7q28) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/digc-7q28/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/digc-7q28/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | digc-7q28 |
| Name | Connecticut Green Bank Checkbook Financial Data FY 15 |
| Attribution | Connecticut Green Bank |
| Category | Environment and Natural Resources |
| Tags | checkbook, spending, financial data, quasi-public, green bank |
| Created | 2016-04-28T17:06:45Z |
| Publication Date | 2016-04-28T17:24:42Z |

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type     | Render Type   |
| ======== | ============== | ===================== | ===================== | ============= | ============= |
| Yes      | time           | payment_dt            | Payment DT            | calendar_date | calendar_date |
| Yes      | series tag     | payment_number        | Payment Number        | text          | text          |
| Yes      | series tag     | vendor_recipient_name | Vendor/Recipient Name | text          | text          |
| Yes      | series tag     | category              | Category              | text          | text          |
| Yes      | numeric metric | amount                | Amount                | money         | money         |
```

## Time Field

```ls
Value = payment_dt
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:digc-7q28 d:2014-07-01T00:00:00.000Z t:category="Program Loan CPACE" t:vendor_recipient_name="Calvary Temple Christian Center Inc." t:payment_number=JE085-13 m:amount=12958.25

series e:digc-7q28 d:2014-07-03T00:00:00.000Z t:category="CI Shared Services Expenses" t:vendor_recipient_name="CT Innovations, Inc" t:payment_number=20529 m:amount=158862.29

series e:digc-7q28 d:2014-07-03T00:00:00.000Z t:category="Program Loan - Campus Efficiency" t:vendor_recipient_name="Campus Efficiency Now, LLC" t:payment_number=20528 m:amount=82386.07
```

## Meta Commands

```ls
metric m:amount p:double l:Amount t:dataTypeName=money

entity e:digc-7q28 l:"Connecticut Green Bank Checkbook Financial Data FY 15" t:attribution="Connecticut Green Bank" t:url=https://data.ct.gov/api/views/digc-7q28

property e:digc-7q28 t:meta.view v:id=digc-7q28 v:category="Environment and Natural Resources" v:attributionLink=http://www.ctcleanenergy.com/ v:averageRating=0 v:name="Connecticut Green Bank Checkbook Financial Data FY 15" v:attribution="Connecticut Green Bank"

property e:digc-7q28 t:meta.view.owner v:id=xhf5-s5a4 v:screenName="Office of the State Comptroller" v:displayName="Office of the State Comptroller"

property e:digc-7q28 t:meta.view.tableauthor v:id=xhf5-s5a4 v:screenName="Office of the State Comptroller" v:roleName=publisher v:displayName="Office of the State Comptroller"
```

## Top Records

```ls
| payment_dt          | payment_number | vendor_recipient_name                | category                                     | amount    | 
| =================== | ============== | ==================================== | ============================================ | ========= | 
| 2014-07-01T00:00:00 | JE085-13       | Calvary Temple Christian Center Inc. | Program Loan CPACE                           | 12958.25  | 
| 2014-07-03T00:00:00 | 20529          | CT Innovations, Inc                  | CI Shared Services Expenses                  | 158862.29 | 
| 2014-07-03T00:00:00 | 20528          | Campus Efficiency Now, LLC           | Program Loan - Campus Efficiency             | 82386.07  | 
| 2014-07-03T00:00:00 | 20526          | C-TEC Solar                          | Program Grant - Clean Energy Communities     | 9389      | 
| 2014-07-03T00:00:00 | 20537          | Schub, Jeffrey                       | Program Development Expense                  | 8624.35   | 
| 2014-07-03T00:00:00 | 20527          | Cadmus Group, Inc.                   | Program Evaluation Expense                   | 8554      | 
| 2014-07-03T00:00:00 | 20535          | RMI Associates, LLC                  | Insurance Consulting Expense                 | 3500      | 
| 2014-07-03T00:00:00 | 20530          | Eastland Title Services              | Program Administration Expense               | 1775      | 
| 2014-07-03T00:00:00 | 1033           | Macunas, Matt                        | Employee Travel&Business Exp. Reimbursements | 600       | 
| 2014-07-03T00:00:00 | 1034           | Santella, Thomas                     | Interest Rate Buydown Incentive              | 600       | 
```