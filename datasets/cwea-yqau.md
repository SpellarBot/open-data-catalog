# Capital Improvement Projects

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/capital-improvement-projects) |
| Metadata | [Link](https://data.hawaii.gov/api/views/cwea-yqau) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/cwea-yqau/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/cwea-yqau/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | cwea-yqau |
| Name | Capital Improvement Projects |
| Created | 2015-02-20T01:09:46Z |
| Publication Date | 2016-02-02T16:54:40Z |

## Columns

```ls
| Included | Schema Type    | Field Name                       | Name                             | Data Type     | Render Type   |
| ======== | ============== | ================================ | ================================ | ============= | ============= |
| No       |                | fiscal_year                      | Fiscal_Year                      | number        | text          |
| Yes      | numeric metric | fiscal_period                    | Fiscal_Period                    | number        | number        |
| Yes      | series tag     | service                          | Service                          | text          | text          |
| Yes      | series tag     | department                       | Department                       | text          | text          |
| Yes      | series tag     | program                          | Program                          | text          | text          |
| Yes      | series tag     | expense_category                 | Expense_Category                 | text          | text          |
| Yes      | series tag     | fund                             | Fund                             | text          | text          |
| Yes      | series tag     | fund_type                        | Fund_Type                        | text          | text          |
| Yes      | series tag     | vendor_name                      | Vendor_Name                      | text          | text          |
| Yes      | series tag     | vendor_number                    | Vendor_Number                    | text          | number        |
| Yes      | series tag     | vendor_zip                       | Vendor_Zip                       | text          | text          |
| Yes      | series tag     | payment_number                   | Payment_Number                   | text          | text          |
| Yes      | series tag     | payment_method                   | Payment_Method                   | text          | text          |
| Yes      | time           | payment_issue_date               | Payment_Issue_date               | calendar_date | calendar_date |
| Yes      | series tag     | payment_status                   | Payment_Status                   | text          | text          |
| Yes      | series tag     | invoice_number                   | Invoice_Number                   | text          | text          |
| Yes      | series tag     | invoice_line_number              | Invoice_Line_Number              | text          | text          |
| Yes      | series tag     | invoice_line_distribution_number | Invoice_Line_Distribution_Number | text          | text          |
| No       |                | invoice_date                     | Invoice_Date                     | text          | text          |
| Yes      | numeric metric | amount                           | Amount                           | money         | money         |
```

## Time Field

```ls
Value = payment_issue_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = invoice_date,fiscal_year
```

## Data Commands

```ls
series e:cwea-yqau d:2014-07-31T00:00:00.000Z t:vendor_number=331736 t:invoice_line_distribution_number=N/A t:program=LNR804 t:department="LAND AND NATURAL RESOURCES" t:invoice_line_number=N/A t:payment_number=B0000428 t:service="LAND AND NATURAL RESOURCES" t:expense_category="OPERATING SUPPLIES" t:invoice_number=N/A t:payment_method=Check t:vendor_name="ALLIED PLASTIC LUMBER, LLC" t:payment_status=Paid m:amount=99793.17 m:fiscal_period=1

series e:cwea-yqau d:2014-11-19T00:00:00.000Z t:vendor_number=29765 t:invoice_line_distribution_number=N/A t:program=LNR407 t:department="LAND AND NATURAL RESOURCES" t:invoice_line_number=N/A t:payment_number=B0002180 t:service="LAND AND NATURAL RESOURCES" t:expense_category="OPERATING SUPPLIES" t:invoice_number=N/A t:payment_method=Check t:vendor_name="HAWAII MEGA-COR., INC." t:payment_status=Paid m:amount=71869.8 m:fiscal_period=5

series e:cwea-yqau d:2014-11-19T00:00:00.000Z t:vendor_number=29765 t:invoice_line_distribution_number=N/A t:program=LNR407 t:department="LAND AND NATURAL RESOURCES" t:invoice_line_number=N/A t:payment_number=B0002180 t:service="LAND AND NATURAL RESOURCES" t:expense_category="OPERATING SUPPLIES" t:invoice_number=N/A t:payment_method=Check t:vendor_name="HAWAII MEGA-COR., INC." t:payment_status=Paid m:amount=91359 m:fiscal_period=5
```

## Meta Commands

```ls
metric m:fiscal_period p:integer l:Fiscal_Period t:dataTypeName=number

metric m:amount p:double l:Amount t:dataTypeName=money

entity e:cwea-yqau l:"Capital Improvement Projects" t:url=https://data.hawaii.gov/api/views/cwea-yqau

property e:cwea-yqau t:meta.view v:id=cwea-yqau v:averageRating=0 v:name="Capital Improvement Projects"

property e:cwea-yqau t:meta.view.owner v:id=wktp-67q4 v:screenName=karen v:displayName=karen

property e:cwea-yqau t:meta.view.tableauthor v:id=wktp-67q4 v:screenName=karen v:roleName=administrator v:displayName=karen
```

## Top Records

```ls
| fiscal_year | fiscal_period | service                    | department                 | program | expense_category                         | fund | fund_type | vendor_name                | vendor_number | vendor_zip | payment_number | payment_method | payment_issue_date  | payment_status | invoice_number | invoice_line_number | invoice_line_distribution_number | invoice_date | amount    | 
| =========== | ============= | ========================== | ========================== | ======= | ======================================== | ==== | ========= | ========================== | ============= | ========== | ============== | ============== | =================== | ============== | ============== | =================== | ================================ | ============ | ========= | 
| 2015        | 1             | LAND AND NATURAL RESOURCES | LAND AND NATURAL RESOURCES | LNR804  | OPERATING SUPPLIES                       |      |           | ALLIED PLASTIC LUMBER, LLC | 331736        |            | B0000428       | Check          | 2014-07-31T00:00:00 | Paid           | N/A            | N/A                 | N/A                              | N/A          | 99793.17  | 
| 2015        | 5             | LAND AND NATURAL RESOURCES | LAND AND NATURAL RESOURCES | LNR407  | OPERATING SUPPLIES                       |      |           | HAWAII MEGA-COR., INC.     | 29765         |            | B0002180       | Check          | 2014-11-19T00:00:00 | Paid           | N/A            | N/A                 | N/A                              | N/A          | 71869.80  | 
| 2015        | 5             | LAND AND NATURAL RESOURCES | LAND AND NATURAL RESOURCES | LNR407  | OPERATING SUPPLIES                       |      |           | HAWAII MEGA-COR., INC.     | 29765         |            | B0002180       | Check          | 2014-11-19T00:00:00 | Paid           | N/A            | N/A                 | N/A                              | N/A          | 91359.00  | 
| 2015        | 4             | LAND AND NATURAL RESOURCES | LAND AND NATURAL RESOURCES | LNR804  | R&M MAT & SUP - BLDG & CONS              |      |           | LAND PREP LLC              | 301061        |            | B0001797       | Check          | 2014-10-24T00:00:00 | Paid           | N/A            | N/A                 | N/A                              | N/A          | 48000.00  | 
| 2015        | 6             | AGRICULTURE                | AGRICULTURE                | AGR161  | OTHR MATERIALS & SUPPLIES- CALLING CARDS |      |           | PACIFIC BIODIESEL          | 333667        |            | B0002597       | Check          | 2014-12-18T00:00:00 | Paid           | N/A            | N/A                 | N/A                              | N/A          | 36458.10  | 
| 2015        | 6             | AGRICULTURE                | AGRICULTURE                | AGR161  | OTHR MATERIALS & SUPPLIES- CALLING CARDS |      |           | PACIFIC BIODIESEL          | 333667        |            | B0002597       | Check          | 2014-12-18T00:00:00 | Paid           | N/A            | N/A                 | N/A                              | N/A          | 41666.40  | 
| 2015        | 6             | AGRICULTURE                | AGRICULTURE                | AGR161  | OTHR MATERIALS & SUPPLIES- CALLING CARDS |      |           | PACIFIC BIODIESEL          | 333667        |            | B0002597       | Check          | 2014-12-18T00:00:00 | Paid           | N/A            | N/A                 | N/A                              | N/A          | 55416.00  | 
| 2015        | 6             | AGRICULTURE                | AGRICULTURE                | AGR161  | OTHR MATERIALS & SUPPLIES- CALLING CARDS |      |           | PACIFIC BIODIESEL          | 333667        |            | B0002597       | Check          | 2014-12-18T00:00:00 | Paid           | N/A            | N/A                 | N/A                              | N/A          | 116005.51 | 
| 2015        | 6             | AGRICULTURE                | AGRICULTURE                | AGR161  | OTHR MATERIALS & SUPPLIES- CALLING CARDS |      |           | PACIFIC BIODIESEL          | 333667        |            | B0002597       | Check          | 2014-12-18T00:00:00 | Paid           | N/A            | N/A                 | N/A                              | N/A          | 187498.80 | 
| 2015        | 6             | AGRICULTURE                | AGRICULTURE                | AGR161  | OTHR MATERIALS & SUPPLIES- CALLING CARDS |      |           | PACIFIC BIODIESEL          | 333667        |            | B0002597       | Check          | 2014-12-18T00:00:00 | Paid           | N/A            | N/A                 | N/A                              | N/A          | 248320.00 | 
```