# Hartford Open Expenditures - Ledger

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hartford-open-expenditures-ledger) |
| Metadata | [Link](https://data.hartford.gov/api/views/y8at-88br) |
| Data: JSON | [100 Rows](https://data.hartford.gov/api/views/y8at-88br/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hartford.gov/api/views/y8at-88br/rows.csv?max_rows=100) |
| Host | data.hartford.gov |
| Id | y8at-88br |
| Name | Hartford Open Expenditures - Ledger |
| Attribution | City of Hartford |
| Category | Financial |
| Tags | hartford, financial, checkbook |
| Created | 2015-08-25T20:30:25Z |
| Publication Date | 2015-08-25T20:37:58Z |

## Description

This data set is being used to update checkbook.hartford.gov which is our open expenditures website. Updated weekly

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type     | Render Type   |
| ======== | ============== | ================== | ================== | ============= | ============= |
| No       |                | j_jrnl_entry_year  | j_jrnl_entry_year  | number        | number        |
| Yes      | numeric metric | j_jrnl_entry_per   | j_jrnl_entry_per   | number        | number        |
| Yes      | series tag     | service            | Service            | text          | text          |
| Yes      | series tag     | dept_name          | Dept Name          | text          | text          |
| Yes      | series tag     | program            | Program            | text          | text          |
| Yes      | series tag     | expense_category   | Expense Category   | text          | text          |
| Yes      | series tag     | fund_name          | Fund Name          | text          | text          |
| Yes      | series tag     | fund_type          | Fund Type          | text          | text          |
| Yes      | series tag     | vendor             | Vendor             | text          | text          |
| Yes      | series tag     | a_vendor_number    | a_vendor_number    | text          | text          |
| Yes      | series tag     | vendor_zip         | Vendor Zip         | text          | text          |
| Yes      | series tag     | a_check_number     | a_check_number     | text          | text          |
| Yes      | series tag     | payment_type       | Payment Type       | text          | text          |
| No       |                | a_check_date       | a_check_date       | calendar_date | calendar_date |
| Yes      | series tag     | payment_status     | Payment Status     | text          | text          |
| Yes      | series tag     | a_invoice_number   | a_invoice_number   | text          | text          |
| Yes      | series tag     | id_line_number     | id_line_number     | text          | number        |
| Yes      | numeric metric | line_na            | line_NA            | number        | number        |
| Yes      | time           | i_invoice_date     | i_invoice_date     | calendar_date | calendar_date |
| Yes      | numeric metric | a_line_item_amount | a_line_item_amount | number        | number        |
| Yes      | series tag     | a_line_item_desc   | a_line_item_desc   | text          | text          |
| Yes      | series tag     | a_purch_order_no   | a_purch_order_no   | text          | text          |
| Yes      | numeric metric | purch_order_line   | purch_order_line   | number        | number        |
```

## Time Field

```ls
Value = i_invoice_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = a_check_date,j_jrnl_entry_year
```

## Data Commands

```ls
series e:y8at-88br d:2015-07-14T00:00:00.000Z t:a_line_item_desc="HART PUB LIB- ELECTRIC @ NEW BRITAIN 6/11-7/14/15" t:fund_type=SUPPLIES t:vendor="Eversource Energy" t:id_line_number=1 t:expense_category=SUPPLIES t:dept_name="HARTFORD PUBLIC LIBRARY" t:a_invoice_number=578611 t:payment_status=Cleared t:fund_name="HARTFORD PUBLIC LIBRARY" t:vendor_zip=06141-0270 t:a_check_number=609581 t:program="GOODWIN BRANCH" t:service="Culture & Recreation" t:a_vendor_number=3 t:payment_type=Check m:a_line_item_amount=1176.98 m:j_jrnl_entry_per=1

series e:y8at-88br d:2016-07-26T00:00:00.000Z t:a_line_item_desc="Account#10H035 ID#V5984 6/29/16-7/29/16" t:a_purch_order_no=20171657 t:fund_type=SUPPLIES t:vendor=CBS t:id_line_number=1 t:expense_category=SUPPLIES t:dept_name="COMMUNICATIONS & NEW MEDIA" t:a_invoice_number=670349 t:payment_status=Cleared t:fund_name="GENERAL FUND" t:vendor_zip=06109 t:a_check_number=108408 t:program="GRAPHICS & MAIL SERVICES" t:service="General Government" t:a_vendor_number=19224 t:payment_type=Check m:a_line_item_amount=3054.57 m:j_jrnl_entry_per=4

series e:y8at-88br d:2016-08-31T00:00:00.000Z t:a_line_item_desc="RENZULLI METER 891289322" t:a_purch_order_no=20170401 t:fund_type=SUPPLIES t:vendor="Eversource Energy" t:id_line_number=3 t:expense_category=SUPPLIES t:dept_name="SCHOOL BASED OPERATIONAL SVS" t:a_invoice_number=660113 t:payment_status=Cleared t:fund_name="EDUCATIONAL GRANTS FUND" t:vendor_zip=06141-0270 t:a_check_number=105863 t:program="PLANT OPERATION & MAINTENANCE" t:service=EDUCATION t:a_vendor_number=3 t:payment_type=Check m:a_line_item_amount=57.31 m:j_jrnl_entry_per=3
```

## Meta Commands

```ls
metric m:j_jrnl_entry_per p:integer l:j_jrnl_entry_per t:dataTypeName=number

metric m:line_na p:long l:line_NA t:dataTypeName=number

metric m:a_line_item_amount p:double l:a_line_item_amount t:dataTypeName=number

metric m:purch_order_line p:long l:purch_order_line t:dataTypeName=number

entity e:y8at-88br l:"Hartford Open Expenditures - Ledger" t:attribution="City of Hartford" t:url=https://data.hartford.gov/api/views/y8at-88br

property e:y8at-88br t:meta.view v:id=y8at-88br v:category=Financial v:attributionLink=http://www.hartford.gov v:averageRating=0 v:name="Hartford Open Expenditures - Ledger" v:attribution="City of Hartford"

property e:y8at-88br t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:y8at-88br t:meta.view.owner v:id=cdqe-xcn5 v:screenName=Brett v:displayName=Brett

property e:y8at-88br t:meta.view.tableauthor v:id=cdqe-xcn5 v:screenName=Brett v:roleName=administrator v:displayName=Brett
```

## Top Records

```ls
| j_jrnl_entry_year | j_jrnl_entry_per | service              | dept_name                    | program                       | expense_category     | fund_name                      | fund_type            | vendor                            | a_vendor_number | vendor_zip | a_check_number | payment_type | a_check_date        | payment_status | a_invoice_number | id_line_number | line_na | i_invoice_date      | a_line_item_amount | a_line_item_desc                                  | a_purch_order_no | purch_order_line | 
| ================= | ================ | ==================== | ============================ | ============================= | ==================== | ============================== | ==================== | ================================= | =============== | ========== | ============== | ============ | =================== | ============== | ================ | ============== | ======= | =================== | ================== | ================================================= | ================ | ================ | 
| 2016              | 1                | Culture & Recreation | HARTFORD PUBLIC LIBRARY      | GOODWIN BRANCH                | SUPPLIES             | HARTFORD PUBLIC LIBRARY        | SUPPLIES             | Eversource Energy                 | 3               | 06141-0270 | 609581         | Check        | 2015-07-27T00:00:00 | Cleared        | 578611           | 1              |         | 2015-07-14T00:00:00 | 1176.98            | HART PUB LIB- ELECTRIC @ NEW BRITAIN 6/11-7/14/15 |                  |                  | 
| 2017              | 4                | General Government   | COMMUNICATIONS & NEW MEDIA   | GRAPHICS & MAIL SERVICES      | SUPPLIES             | GENERAL FUND                   | SUPPLIES             | CBS                               | 19224           | 06109      | 108408         | Check        | 2016-11-07T00:00:00 | Cleared        | 670349           | 1              |         | 2016-07-26T00:00:00 | 3054.57            | Account#10H035 ID#V5984 6/29/16-7/29/16           | 20171657         |                  | 
| 2017              | 3                | EDUCATION            | SCHOOL BASED OPERATIONAL SVS | PLANT OPERATION & MAINTENANCE | SUPPLIES             | EDUCATIONAL GRANTS FUND        | SUPPLIES             | Eversource Energy                 | 3               | 06141-0270 | 105863         | Check        | 2016-09-12T00:00:00 | Cleared        | 660113           | 3              |         | 2016-08-31T00:00:00 | 57.31              | RENZULLI METER 891289322                          | 20170401         |                  | 
| 2017              | 7                | EDUCATION            | BUILDING & GROUNDS           | PLANT OPERATION & MAINTENANCE | PURCH PROPERTY SVC   | GENERAL FUND - EDUCATION       | PURCH PROPERTY SVC   | Air Temp Mechanical Services Inc. | 39971           | 06489      | 111453         | Check        | 2017-01-17T00:00:00 | Not Cleared    | 683385           | 1              |         | 2016-12-29T00:00:00 | 1121.8             | ACCT # 108757 - JOURNALISM AND MEDIA              | 20170047         |                  | 
| 2017              | 6                | Public Safety        | FIRE                         | SUPPRESSION                   | SUPPLIES             | GENERAL FUND                   | SUPPLIES             | STAPLES                           | 52413           | 6111       |                | ACI          |                     | Not Cleared    | 683858           | 1              |         | 2016-12-30T00:00:00 | 113.81             | STAPLES 00112680 -STAPLES DESKTOP                 |                  |                  | 
| 2017              | 6                | EDUCATION            | BETANCES SCHOOL              | REGULAR INSTRUCTION           | SUPPLIES             | GENERAL FUND - EDUCATION       | SUPPLIES             | School Specialty Inc.             | 562             | 54942      | 5476           | ACI          | 2016-12-12T00:00:00 | Not Cleared    | 678205           | 1              |         | 2016-10-18T00:00:00 | 35.19              | CLASSROOM SUPPLIES                                | 20170473         |                  | 
| 2017              | 4                | Public Works         | PUBLIC WORKS                 | EQUIPMENT SERVICES            | SUPPLIES             | GENERAL FUND                   | SUPPLIES             | Nutmeg International Trucks Inc   | 16634           | 06114      | 5380           | ACI          | 2016-11-14T00:00:00 | Not Cleared    | 669229           | 1              |         | 2016-10-17T00:00:00 | 104.06             | INTERNATIONAL PARTS FY 2017 - PO# 20170198        | 20170198         |                  | 
| 2017              | 4                | Human Services       | DEVELOPMENT SERVICES         | ADMINISTRATION                | PURCH PROF & TECH SV | COMMUNITY DEVELOPMENT ACT FUND | PURCH PROF & TECH SV | Bliss Hospitality LLC             | 52251           | 06120      |                | ACI          |                     | Not Cleared    | 672882           | 1              |         | 2016-10-31T00:00:00 | 350                | SUPER 8 - Purchase MATTHEWS ST ALEMENS ALLEGRA    |                  |                  | 
| 2017              | 7                | EDUCATION            | HOOKER SCHOOL                | REGULAR INSTRUCTION           | SUPPLIES             | GENERAL FUND - EDUCATION       | SUPPLIES             | School Specialty Inc.             | 562             | 54942      | 5606           | ACI          | 2017-01-23T00:00:00 | Not Cleared    | 685103           | 1              |         | 2017-01-06T00:00:00 | 414.09             | SCHOOL EQUIPMENT, TEACHING AID                    | 20172338         |                  | 
| 2017              | 5                | Public Works         | PUBLIC WORKS                 | EQUIPMENT SERVICES            | SUPPLIES             | GENERAL FUND                   | SUPPLIES             | Genuine Parts Co.                 | 4907            | 06114      | 109117         | Check        | 2016-11-21T00:00:00 | Cleared        | 670875           | 1              |         | 2016-10-24T00:00:00 | 39.12              | NON OEM REPLACEMENT PARTS FY 17 - PO# 20170177    | 20170177         |                  | 
```