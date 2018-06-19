# Consumer Fraud Refunds

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/consumer-fraud-refunds) |
| Metadata | [Link](https://data.iowa.gov/api/views/b37c-2vmj) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/b37c-2vmj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/b37c-2vmj/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | b37c-2vmj |
| Name | Consumer Fraud Refunds |
| Attribution | Iowa Department of Administrative Services, State Accounting Enterprise |
| Category | Government |
| Tags | checkbook, expenditures, payments, consumer fraud, refunds |
| Created | 2015-01-06T15:02:52Z |
| Publication Date | 2015-01-06T19:49:39Z |

## Description

This dataset contains payment transactions recorded in the State?s central accounting system for the Consumer Fraud Refunds fund.

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                             | Data Type     | Render Type   |
| ======== | ============== | ========================= | ================================ | ============= | ============= |
| Yes      | series tag     | rec_no                    | Record Number                    | text          | text          |
| No       |                | fiscal_year               | Fiscal Year                      | number        | number        |
| Yes      | numeric metric | fiscal_year_period        | Fiscal Year Period               | number        | number        |
| Yes      | series tag     | accounting_period         | Accounting Period                | text          | text          |
| Yes      | series tag     | service                   | Service                          | text          | text          |
| Yes      | series tag     | department                | Department                       | text          | text          |
| Yes      | series tag     | fund_code                 | Fund Code                        | text          | text          |
| Yes      | series tag     | fund_name                 | Fund Name                        | text          | text          |
| Yes      | series tag     | appropriation_code        | Appropriation Code               | text          | text          |
| Yes      | series tag     | appropriation_name        | Appropriation Name               | text          | text          |
| Yes      | series tag     | program                   | Program                          | text          | text          |
| Yes      | series tag     | expense_category          | Expense Category                 | text          | text          |
| Yes      | series tag     | vendor                    | Vendor                           | text          | text          |
| Yes      | series tag     | vendor_id                 | Vendor Number                    | text          | text          |
| Yes      | series tag     | payment_id                | Payment Number                   | text          | text          |
| Yes      | time           | payment_date              | Payment Issue Date               | calendar_date | calendar_date |
| Yes      | series tag     | invoice_id                | Invoice Number                   | text          | text          |
| Yes      | series tag     | invoice_line              | Invoice Line Number              | text          | number        |
| Yes      | series tag     | invoice_distribution_line | Invoice Line Distribution Number | text          | number        |
| No       |                | invoice_date              | Invoice Date                     | calendar_date | calendar_date |
| Yes      | numeric metric | amount                    | Amount                           | number        | number        |
| Yes      | series tag     | description               | Description                      | text          | text          |
```

## Time Field

```ls
Value = payment_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = invoice_date,fiscal_year
```

## Data Commands

```ls
series e:b37c-2vmj d:2014-10-27T00:00:00.000Z t:fund_code=822 t:department="ATTORNEY GENERAL" t:vendor="DAVID BOWEN" t:expense_category=REFUNDS-OTHER t:rec_no=206447566 t:vendor_id=11200 t:invoice_distribution_line=1 t:fund_name="CONSUMER FRAUD REFUNDS" t:invoice_line=1 t:program="CONSUMER FRAUD REFUNDS" t:description=REFUND t:service="JUSTICE SYSTEM" t:invoice_id=GAX-112-300554-1-0 t:payment_id=GAX-112-300554-1-0 t:accounting_period=OCTOBER m:amount=106 m:fiscal_year_period=4

series e:b37c-2vmj d:2014-09-04T00:00:00.000Z t:fund_code=822 t:department="ATTORNEY GENERAL" t:vendor="MICHAEL SHIFLEPP" t:expense_category=REFUNDS-OTHER t:rec_no=201984968 t:vendor_id=11200 t:invoice_distribution_line=1 t:fund_name="CONSUMER FRAUD REFUNDS" t:invoice_line=1 t:program="CONSUMER FRAUD REFUNDS" t:description=REFUND t:service="JUSTICE SYSTEM" t:invoice_id=GAX-112-031814-1-0 t:payment_id=GAX-112-031814-1-0 t:accounting_period=SEPTEMBER m:amount=87 m:fiscal_year_period=3

series e:b37c-2vmj d:2014-10-16T00:00:00.000Z t:fund_code=822 t:department="ATTORNEY GENERAL" t:vendor="MOHAMMAD FAROOQ" t:expense_category=REFUNDS-OTHER t:rec_no=205565406 t:vendor_id=11200 t:invoice_distribution_line=1 t:fund_name="CONSUMER FRAUD REFUNDS" t:invoice_line=1 t:program="CONSUMER FRAUD REFUNDS" t:description=REFUND t:service="JUSTICE SYSTEM" t:invoice_id=GAX-112-213731-1-0 t:payment_id=GAX-112-213731-1-0 t:accounting_period=OCTOBER m:amount=138 m:fiscal_year_period=4
```

## Meta Commands

```ls
metric m:fiscal_year_period p:integer l:"Fiscal Year Period" d:"Reflects twelve periods with July being period 1 and June being period 12. Hold-over payments are reflected in period 12." t:dataTypeName=number

metric m:amount p:double l:Amount d:"Amount of payment to the vendor" t:dataTypeName=number

entity e:b37c-2vmj l:"Consumer Fraud Refunds" t:attribution="Iowa Department of Administrative Services, State Accounting Enterprise" t:url=https://data.iowa.gov/api/views/b37c-2vmj

property e:b37c-2vmj t:meta.view v:id=b37c-2vmj v:category=Government v:averageRating=0 v:name="Consumer Fraud Refunds" v:attribution="Iowa Department of Administrative Services, State Accounting Enterprise"

property e:b37c-2vmj t:meta.view.license v:name="Public Domain"

property e:b37c-2vmj t:meta.view.owner v:id=vxmx-2ngw v:profileImageUrlMedium=/api/users/vxmx-2ngw/profile_images/THUMB v:profileImageUrlLarge=/api/users/vxmx-2ngw/profile_images/LARGE v:screenName="DAS, State Accounting Enterprise" v:profileImageUrlSmall=/api/users/vxmx-2ngw/profile_images/TINY v:displayName="DAS, State Accounting Enterprise"

property e:b37c-2vmj t:meta.view.tableauthor v:id=vxmx-2ngw v:profileImageUrlMedium=/api/users/vxmx-2ngw/profile_images/THUMB v:profileImageUrlLarge=/api/users/vxmx-2ngw/profile_images/LARGE v:screenName="DAS, State Accounting Enterprise" v:profileImageUrlSmall=/api/users/vxmx-2ngw/profile_images/TINY v:roleName=editor v:displayName="DAS, State Accounting Enterprise"
```

## Top Records

```ls
| rec_no    | fiscal_year | fiscal_year_period | accounting_period | service        | department       | fund_code | fund_name              | appropriation_code | appropriation_name | program                | expense_category | vendor           | vendor_id | payment_id         | payment_date        | invoice_id         | invoice_line | invoice_distribution_line | invoice_date        | amount | description | 
| ========= | =========== | ================== | ================= | ============== | ================ | ========= | ====================== | ================== | ================== | ====================== | ================ | ================ | ========= | ================== | =================== | ================== | ============ | ========================= | =================== | ====== | =========== | 
| 206447566 | 2015        | 4                  | OCTOBER           | JUSTICE SYSTEM | ATTORNEY GENERAL | 822       | CONSUMER FRAUD REFUNDS |                    |                    | CONSUMER FRAUD REFUNDS | REFUNDS-OTHER    | DAVID BOWEN      | 11200     | GAX-112-300554-1-0 | 2014-10-27T00:00:00 | GAX-112-300554-1-0 | 1            | 1                         | 2014-10-27T00:00:00 | 106    | REFUND      | 
| 201984968 | 2015        | 3                  | SEPTEMBER         | JUSTICE SYSTEM | ATTORNEY GENERAL | 822       | CONSUMER FRAUD REFUNDS |                    |                    | CONSUMER FRAUD REFUNDS | REFUNDS-OTHER    | MICHAEL SHIFLEPP | 11200     | GAX-112-031814-1-0 | 2014-09-04T00:00:00 | GAX-112-031814-1-0 | 1            | 1                         | 2014-09-04T00:00:00 | 87     | REFUND      | 
| 205565406 | 2015        | 4                  | OCTOBER           | JUSTICE SYSTEM | ATTORNEY GENERAL | 822       | CONSUMER FRAUD REFUNDS |                    |                    | CONSUMER FRAUD REFUNDS | REFUNDS-OTHER    | MOHAMMAD FAROOQ  | 11200     | GAX-112-213731-1-0 | 2014-10-16T00:00:00 | GAX-112-213731-1-0 | 1            | 1                         | 2014-10-16T00:00:00 | 138    | REFUND      | 
| 205725710 | 2015        | 4                  | OCTOBER           | JUSTICE SYSTEM | ATTORNEY GENERAL | 822       | CONSUMER FRAUD REFUNDS |                    |                    | CONSUMER FRAUD REFUNDS | REFUNDS-OTHER    | DEBORAH KOZIOL   | 11200     | GAX-112-227158-1-0 | 2014-10-17T00:00:00 | GAX-112-227158-1-0 | 1            | 1                         | 2014-10-17T00:00:00 | 27     | REFUND      | 
| 202361828 | 2015        | 3                  | SEPTEMBER         | JUSTICE SYSTEM | ATTORNEY GENERAL | 822       | CONSUMER FRAUD REFUNDS |                    |                    | CONSUMER FRAUD REFUNDS | REFUNDS-OTHER    | REGINA M WHITE   | 11200     | GAX-112-075671-1-0 | 2014-09-08T00:00:00 | GAX-112-075671-1-0 | 1            | 1                         | 2014-09-08T00:00:00 | 17     | REFUND      | 
| 206286354 | 2015        | 4                  | OCTOBER           | JUSTICE SYSTEM | ATTORNEY GENERAL | 822       | CONSUMER FRAUD REFUNDS |                    |                    | CONSUMER FRAUD REFUNDS | REFUNDS-OTHER    | NANCY NEESSEN    | 11200     | GAX-112-285057-1-0 | 2014-10-24T00:00:00 | GAX-112-285057-1-0 | 1            | 1                         | 2014-10-24T00:00:00 | 125    | REFUND      | 
| 206415546 | 2015        | 4                  | OCTOBER           | JUSTICE SYSTEM | ATTORNEY GENERAL | 822       | CONSUMER FRAUD REFUNDS |                    |                    | CONSUMER FRAUD REFUNDS | REFUNDS-OTHER    | MARLA GERRITSEN  | 11200     | GAX-112-292549-1-0 | 2014-10-27T00:00:00 | GAX-112-292549-1-0 | 1            | 1                         | 2014-10-27T00:00:00 | 6      | REFUND      | 
| 202461192 | 2015        | 3                  | SEPTEMBER         | JUSTICE SYSTEM | ATTORNEY GENERAL | 822       | CONSUMER FRAUD REFUNDS |                    |                    | CONSUMER FRAUD REFUNDS | REFUNDS-OTHER    | IRENE DAVISON    | 11200     | GAX-112-099922-1-0 | 2014-09-08T00:00:00 | GAX-112-099922-1-0 | 1            | 1                         | 2014-09-08T00:00:00 | 135    | REFUND      | 
| 202648706 | 2015        | 3                  | SEPTEMBER         | JUSTICE SYSTEM | ATTORNEY GENERAL | 822       | CONSUMER FRAUD REFUNDS |                    |                    | CONSUMER FRAUD REFUNDS | REFUNDS-OTHER    | CYNTHIA NARVAEZ  | 11200     | GAX-112-120139-1-0 | 2014-09-09T00:00:00 | GAX-112-120139-1-0 | 1            | 1                         | 2014-09-09T00:00:00 | 141    | REFUND      | 
| 207199480 | 2015        | 4                  | OCTOBER           | JUSTICE SYSTEM | ATTORNEY GENERAL | 822       | CONSUMER FRAUD REFUNDS |                    |                    | CONSUMER FRAUD REFUNDS | REFUNDS-OTHER    | KENNETH DAHLMAN  | 11200     | GAX-112-364582-1-0 | 2014-10-31T00:00:00 | GAX-112-364582-1-0 | 1            | 1                         | 2014-10-31T00:00:00 | 8      | REFUND      | 
```