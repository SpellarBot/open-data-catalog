# State of Iowa Checkbook

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-of-iowa-checkbook) |
| Metadata | [Link](https://data.iowa.gov/api/views/cyqb-8ina) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/cyqb-8ina/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/cyqb-8ina/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | cyqb-8ina |
| Name | State of Iowa Checkbook |
| Attribution | Iowa Department of Administrative Services, State Accounting Enterprise |
| Category | Government |
| Tags | checkbook, expenditures, payments, vendors |
| Created | 2014-12-10T15:54:52Z |
| Publication Date | 2015-01-05T21:33:03Z |

## Description

This dataset contains payment transactions recorded in the State?s central accounting system for the Executive Branch.  Please visit Iowa's Open Checkbook at http://checkbook.iowa.gov to explore this dataset more extensively.

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
series e:cyqb-8ina d:2013-11-18T00:00:00.000Z t:fund_code=0001 t:department="STATE PUBLIC DEFENDER/DIA" t:vendor="ANN M TROGE" t:expense_category="PROF & SCIENTIFIC SERVICES" t:rec_no=184484346 t:vendor_id=00003062217 t:invoice_distribution_line=1 t:appropriation_code=Q44 t:fund_name="GENERAL FUND" t:invoice_line=1 t:program="ATTORNEY FEES INDIGENT DEFENSE" t:description="JUVENILE CTY BAS ATTY FEES" t:service="ADMINISTRATION AND REGULATION" t:appropriation_name="INDIGENT DEFENSE APPROPRIATION" t:invoice_id=GAX-428-428R318140543-1-0 t:payment_id=GAX-428-428R318140543-1-0 t:accounting_period=NOVEMBER m:amount=237.42 m:fiscal_year_period=5

series e:cyqb-8ina d:2013-11-18T00:00:00.000Z t:fund_code=0001 t:department="STATE PUBLIC DEFENDER/DIA" t:vendor="DANI L EISENTRAGER" t:expense_category="PROF & SCIENTIFIC SERVICES" t:rec_no=184484348 t:vendor_id=EISENTRAGXX t:invoice_distribution_line=1 t:appropriation_code=Q44 t:fund_name="GENERAL FUND" t:invoice_line=2 t:program="ATTORNEY FEES INDIGENT DEFENSE" t:description="JUVENILE CTY BAS ATTY FEES" t:service="ADMINISTRATION AND REGULATION" t:appropriation_name="INDIGENT DEFENSE APPROPRIATION" t:invoice_id=TP-428-428R318140545-1-0 t:payment_id=TP-428-428R318140545-1-0 t:accounting_period=NOVEMBER m:amount=223.35 m:fiscal_year_period=5

series e:cyqb-8ina d:2013-11-18T00:00:00.000Z t:fund_code=0001 t:department="STATE PUBLIC DEFENDER/DIA" t:vendor="DANI L EISENTRAGER" t:expense_category="PROF & SCIENTIFIC SERVICES" t:rec_no=184484352 t:vendor_id=EISENTRAGXX t:invoice_distribution_line=1 t:appropriation_code=Q44 t:fund_name="GENERAL FUND" t:invoice_line=1 t:program="ATTORNEY FEES INDIGENT DEFENSE" t:description="JUVENILE CTY BAS ATTY FEES" t:service="ADMINISTRATION AND REGULATION" t:appropriation_name="INDIGENT DEFENSE APPROPRIATION" t:invoice_id=TP-428-428R318140545-1-0 t:payment_id=TP-428-428R318140545-1-0 t:accounting_period=NOVEMBER m:amount=108.09 m:fiscal_year_period=5
```

## Meta Commands

```ls
metric m:fiscal_year_period p:integer l:"Fiscal Year Period" d:"Reflects twelve periods with July being period 1 and June being period 12. Hold-over payments are reflected in period 12." t:dataTypeName=number

metric m:amount p:double l:Amount d:"Amount of payment to the vendor" t:dataTypeName=number

entity e:cyqb-8ina l:"State of Iowa Checkbook" t:attribution="Iowa Department of Administrative Services, State Accounting Enterprise" t:url=https://data.iowa.gov/api/views/cyqb-8ina

property e:cyqb-8ina t:meta.view v:id=cyqb-8ina v:category=Government v:averageRating=0 v:name="State of Iowa Checkbook" v:attribution="Iowa Department of Administrative Services, State Accounting Enterprise"

property e:cyqb-8ina t:meta.view.license v:name="Public Domain"

property e:cyqb-8ina t:meta.view.owner v:id=vxmx-2ngw v:profileImageUrlMedium=/api/users/vxmx-2ngw/profile_images/THUMB v:profileImageUrlLarge=/api/users/vxmx-2ngw/profile_images/LARGE v:screenName="DAS, State Accounting Enterprise" v:profileImageUrlSmall=/api/users/vxmx-2ngw/profile_images/TINY v:displayName="DAS, State Accounting Enterprise"

property e:cyqb-8ina t:meta.view.tableauthor v:id=vxmx-2ngw v:profileImageUrlMedium=/api/users/vxmx-2ngw/profile_images/THUMB v:profileImageUrlLarge=/api/users/vxmx-2ngw/profile_images/LARGE v:screenName="DAS, State Accounting Enterprise" v:profileImageUrlSmall=/api/users/vxmx-2ngw/profile_images/TINY v:roleName=editor v:displayName="DAS, State Accounting Enterprise"
```

## Top Records

```ls
| rec_no    | fiscal_year | fiscal_year_period | accounting_period | service                       | department                | fund_code | fund_name    | appropriation_code | appropriation_name             | program                        | expense_category           | vendor                    | vendor_id   | payment_id                | payment_date        | invoice_id                | invoice_line | invoice_distribution_line | invoice_date        | amount | description                | 
| ========= | =========== | ================== | ================= | ============================= | ========================= | ========= | ============ | ================== | ============================== | ============================== | ========================== | ========================= | =========== | ========================= | =================== | ========================= | ============ | ========================= | =================== | ====== | ========================== | 
| 184484346 | 2014        | 5                  | NOVEMBER          | ADMINISTRATION AND REGULATION | STATE PUBLIC DEFENDER/DIA | 0001      | GENERAL FUND | Q44                | INDIGENT DEFENSE APPROPRIATION | ATTORNEY FEES INDIGENT DEFENSE | PROF & SCIENTIFIC SERVICES | ANN M TROGE               | 00003062217 | GAX-428-428R318140543-1-0 | 2013-11-18T00:00:00 | GAX-428-428R318140543-1-0 | 1            | 1                         | 2013-11-18T00:00:00 | 237.42 | JUVENILE CTY BAS ATTY FEES | 
| 184484348 | 2014        | 5                  | NOVEMBER          | ADMINISTRATION AND REGULATION | STATE PUBLIC DEFENDER/DIA | 0001      | GENERAL FUND | Q44                | INDIGENT DEFENSE APPROPRIATION | ATTORNEY FEES INDIGENT DEFENSE | PROF & SCIENTIFIC SERVICES | DANI L EISENTRAGER        | EISENTRAGXX | TP-428-428R318140545-1-0  | 2013-11-18T00:00:00 | TP-428-428R318140545-1-0  | 2            | 1                         | 2013-11-18T00:00:00 | 223.35 | JUVENILE CTY BAS ATTY FEES | 
| 184484352 | 2014        | 5                  | NOVEMBER          | ADMINISTRATION AND REGULATION | STATE PUBLIC DEFENDER/DIA | 0001      | GENERAL FUND | Q44                | INDIGENT DEFENSE APPROPRIATION | ATTORNEY FEES INDIGENT DEFENSE | PROF & SCIENTIFIC SERVICES | DANI L EISENTRAGER        | EISENTRAGXX | TP-428-428R318140545-1-0  | 2013-11-18T00:00:00 | TP-428-428R318140545-1-0  | 1            | 1                         | 2013-11-18T00:00:00 | 108.09 | JUVENILE CTY BAS ATTY FEES | 
| 184484356 | 2014        | 5                  | NOVEMBER          | ADMINISTRATION AND REGULATION | STATE PUBLIC DEFENDER/DIA | 0001      | GENERAL FUND | Q44                | INDIGENT DEFENSE APPROPRIATION | ATTORNEY FEES INDIGENT DEFENSE | PROF & SCIENTIFIC SERVICES | ADAM D HANSON             | HANSONADAXX | TP-428-428R319140614-1-0  | 2013-11-18T00:00:00 | TP-428-428R319140614-1-0  | 3            | 1                         | 2013-11-18T00:00:00 | 150    | JUVENILE CTY BAS ATTY FEES | 
| 184484360 | 2014        | 5                  | NOVEMBER          | ADMINISTRATION AND REGULATION | STATE PUBLIC DEFENDER/DIA | 0001      | GENERAL FUND | Q44                | INDIGENT DEFENSE APPROPRIATION | ATTORNEY FEES INDIGENT DEFENSE | PROF & SCIENTIFIC SERVICES | ADAM D HANSON             | HANSONADAXX | TP-428-428R319140614-1-0  | 2013-11-18T00:00:00 | TP-428-428R319140614-1-0  | 2            | 1                         | 2013-11-18T00:00:00 | 326.6  | JUVENILE CTY BAS ATTY FEES | 
| 184484364 | 2014        | 5                  | NOVEMBER          | ADMINISTRATION AND REGULATION | STATE PUBLIC DEFENDER/DIA | 0001      | GENERAL FUND | Q44                | INDIGENT DEFENSE APPROPRIATION | ATTORNEY FEES INDIGENT DEFENSE | PROF & SCIENTIFIC SERVICES | ADAM D HANSON             | HANSONADAXX | TP-428-428R319140614-1-0  | 2013-11-18T00:00:00 | TP-428-428R319140614-1-0  | 1            | 1                         | 2013-11-18T00:00:00 | 612    | JUVENILE CTY BAS ATTY FEES | 
| 184484370 | 2014        | 5                  | NOVEMBER          | ADMINISTRATION AND REGULATION | STATE PUBLIC DEFENDER/DIA | 0001      | GENERAL FUND | Q44                | INDIGENT DEFENSE APPROPRIATION | ATTORNEY FEES INDIGENT DEFENSE | PROF & SCIENTIFIC SERVICES | KATHERINE KAMINSKY MURPHY | KAMINSKYMXX | TP-428-428R319140615-1-0  | 2013-11-18T00:00:00 | TP-428-428R319140615-1-0  | 2            | 1                         | 2013-11-18T00:00:00 | 454.45 | JUVENILE CTY BAS ATTY FEES | 
| 184484374 | 2014        | 5                  | NOVEMBER          | ADMINISTRATION AND REGULATION | STATE PUBLIC DEFENDER/DIA | 0001      | GENERAL FUND | Q44                | INDIGENT DEFENSE APPROPRIATION | ATTORNEY FEES INDIGENT DEFENSE | PROF & SCIENTIFIC SERVICES | KATHERINE KAMINSKY MURPHY | KAMINSKYMXX | TP-428-428R319140615-1-0  | 2013-11-18T00:00:00 | TP-428-428R319140615-1-0  | 1            | 1                         | 2013-11-18T00:00:00 | 713.1  | JUVENILE CTY BAS ATTY FEES | 
| 184484378 | 2014        | 5                  | NOVEMBER          | ADMINISTRATION AND REGULATION | STATE PUBLIC DEFENDER/DIA | 0001      | GENERAL FUND | Q44                | INDIGENT DEFENSE APPROPRIATION | ATTORNEY FEES INDIGENT DEFENSE | PROF & SCIENTIFIC SERVICES | KATHERINE KAMINSKY MURPHY | KAMINSKYMXX | TP-428-428R319140615-1-0  | 2013-11-18T00:00:00 | TP-428-428R319140615-1-0  | 3            | 1                         | 2013-11-18T00:00:00 | 266.8  | JUVENILE CTY BAS ATTY FEES | 
| 184484380 | 2014        | 5                  | NOVEMBER          | ADMINISTRATION AND REGULATION | STATE PUBLIC DEFENDER/DIA | 0001      | GENERAL FUND | Q44                | INDIGENT DEFENSE APPROPRIATION | ATTORNEY FEES INDIGENT DEFENSE | PROF & SCIENTIFIC SERVICES | DANI L EISENTRAGER        | EISENTRAGXX | TP-428-428R319140616-1-0  | 2013-11-18T00:00:00 | TP-428-428R319140616-1-0  | 1            | 1                         | 2013-11-18T00:00:00 | 273.21 | JUVENILE CTY BAS ATTY FEES | 
```