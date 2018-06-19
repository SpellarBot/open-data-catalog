# Cook County Check Register

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cook-county-check-register-a5a44) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/gywr-fjeh) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/gywr-fjeh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/gywr-fjeh/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | gywr-fjeh |
| Name | Cook County Check Register |
| Attribution | Cook County Office of the Comptroller |
| Category | Finance & Administration |
| Tags | check register, check registry, payments |
| Created | 2014-06-24T18:15:50Z |
| Publication Date | 2016-10-25T21:46:12Z |

## Description

This check register provides a cumulative record of payments to County suppliers, vendors and other payees as approved by the Cook County Board of Commissioners. Data covers December 2009 through September 2016. [NOTE: We are in the process of restructuring this dataset with implementation of a new financial system. Updates will resume once the new structure has been established.]

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type     | Render Type   |
| ======== | ============== | ================== | ================== | ============= | ============= |
| Yes      | series tag     | check_number       | CHECK NUMBER       | text          | number        |
| Yes      | time           | check_date         | CHECK DATE         | calendar_date | calendar_date |
| Yes      | series tag     | payee_number       | PAYEE NUMBER       | text          | number        |
| Yes      | series tag     | payee_vendor_name  | PAYEE VENDOR NAME  | text          | text          |
| Yes      | numeric metric | payment_amount     | PAYMENT AMOUNT     | money         | money         |
| Yes      | series tag     | service_type_id    | SERVICE TYPE ID    | text          | number        |
| Yes      | series tag     | service_type_desc  | SERVICE TYPE DESC  | text          | text          |
| Yes      | numeric metric | purchase_order     | PURCHASE ORDER     | number        | number        |
| Yes      | numeric metric | pdmcu              | PDMCU              | number        | number        |
| Yes      | series tag     | department_nbr     | DEPARTMENT NBR     | text          | number        |
| Yes      | series tag     | department_name    | DEPARTMENT NAME    | text          | text          |
| Yes      | series tag     | business_unit_code | BUSINESS UNIT CODE | text          | number        |
| Yes      | series tag     | business_unit_name | BUSINESS UNIT NAME | text          | text          |
| Yes      | series tag     | vendor_name        | VENDOR NAME        | text          | text          |
| No       |                | vendor_address_1   | VENDOR ADDRESS_1   | text          | text          |
| No       |                | vendor_address_2   | VENDOR ADDRESS_2   | text          | text          |
| Yes      | series tag     | city               | CITY               | text          | text          |
| Yes      | series tag     | state_id           | STATE ID           | text          | text          |
| Yes      | series tag     | zip_code           | ZIP CODE           | text          | text          |
```

## Time Field

```ls
Value = check_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = vendor_address_1,vendor_address_2
```

## Data Commands

```ls
series e:gywr-fjeh d:2016-07-14T00:00:00.000Z t:payee_number=834152 t:business_unit_name="239 307 Business Office" t:service_type_desc="MISCELLANEOUS PRODUCTS" t:check_number=1708948 t:payee_vendor_name="3M Electronic Monitoring Inc" t:department_nbr=239 t:department_name="Department of Corrections" t:service_type_id=578 t:business_unit_code=2390954 m:pdmcu=2390954 m:payment_amount=3375.9 m:purchase_order=193917

series e:gywr-fjeh d:2016-07-14T00:00:00.000Z t:payee_number=834152 t:business_unit_name="239 307 Business Office" t:service_type_desc="MISCELLANEOUS PRODUCTS" t:check_number=1708948 t:payee_vendor_name="3M Electronic Monitoring Inc" t:department_nbr=239 t:department_name="Department of Corrections" t:service_type_id=578 t:business_unit_code=2390954 m:pdmcu=2390954 m:payment_amount=192063.3 m:purchase_order=194473

series e:gywr-fjeh d:2016-07-14T00:00:00.000Z t:payee_number=834152 t:business_unit_name="239 307 Business Office" t:service_type_desc="MISCELLANEOUS PRODUCTS" t:check_number=1708948 t:payee_vendor_name="3M Electronic Monitoring Inc" t:department_nbr=239 t:department_name="Department of Corrections" t:service_type_id=578 t:business_unit_code=2390954 m:pdmcu=2390954 m:payment_amount=30858.3 m:purchase_order=194473
```

## Meta Commands

```ls
metric m:payment_amount p:double l:"PAYMENT AMOUNT" t:dataTypeName=money

metric m:purchase_order p:integer l:"PURCHASE ORDER" t:dataTypeName=number

metric m:pdmcu p:long l:PDMCU t:dataTypeName=number

entity e:gywr-fjeh l:"Cook County Check Register" t:attribution="Cook County Office of the Comptroller" t:url=https://datacatalog.cookcountyil.gov/api/views/gywr-fjeh

property e:gywr-fjeh t:meta.view v:id=gywr-fjeh v:category="Finance & Administration" v:averageRating=0 v:name="Cook County Check Register" v:attribution="Cook County Office of the Comptroller"

property e:gywr-fjeh t:meta.view.license v:name="Public Domain"

property e:gywr-fjeh t:meta.view.owner v:id=u38g-hbsa v:screenName="Cook County Open Data" v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"

property e:gywr-fjeh t:meta.view.tableauthor v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"
```

## Top Records

```ls
| check_number | check_date          | payee_number | payee_vendor_name            | payment_amount | service_type_id | service_type_desc                   | purchase_order | pdmcu   | department_nbr | department_name                            | business_unit_code | business_unit_name             | vendor_name      | vendor_address_1 | vendor_address_2 | city    | state_id | zip_code | 
| ============ | =================== | ============ | ============================ | ============== | =============== | =================================== | ============== | ======= | ============== | ========================================== | ================== | ============================== | ================ | ================ | ================ | ======= | ======== | ======== | 
| 1708948      | 2016-07-14T00:00:00 | 834152       | 3M Electronic Monitoring Inc | 3375.9         | 578             | MISCELLANEOUS PRODUCTS              | 193917         | 2390954 | 239            | Department of Corrections                  | 2390954            | 239 307 Business Office        |                  |                  |                  |         |          |          | 
| 1708948      | 2016-07-14T00:00:00 | 834152       | 3M Electronic Monitoring Inc | 192063.3       | 578             | MISCELLANEOUS PRODUCTS              | 194473         | 2390954 | 239            | Department of Corrections                  | 2390954            | 239 307 Business Office        |                  |                  |                  |         |          |          | 
| 1708948      | 2016-07-14T00:00:00 | 834152       | 3M Electronic Monitoring Inc | 30858.3        | 578             | MISCELLANEOUS PRODUCTS              | 194473         | 2390954 | 239            | Department of Corrections                  | 2390954            | 239 307 Business Office        |                  |                  |                  |         |          |          | 
| 1708144      | 2016-07-12T00:00:00 | 834152       | 3M Electronic Monitoring Inc | 67537.8        | 961             | MISCELLANEOUS PROFESSIONAL SERVICES | 194474         | 2800847 | 280            | Adult Probation Department                 | 2800847            | 280 101 Supervisory And Cleric |                  |                  |                  |         |          |          | 
| 1707503      | 2016-07-07T00:00:00 | 850909       | A & A IMPERIAL SERVICES      | 455            | 962             | MISCELLANEOUS SERVICES              | 194410         | 91375   | 9              | Enterprise Technology                      | 91375              | 009 103 Media and Communicatio |                  |                  |                  |         |          |          | 
| 1708989      | 2016-07-19T00:00:00 | 81620        | A Safe Haven LLC             | 2967.02        | 961             | MISCELLANEOUS PROFESSIONAL SERVICES | 194591         | 5321453 | 532            | Adult Probation/Probation Service Fee Fund | 5321453            | 532 101 Administration         | A Safe Haven LLC | P O BOX 39083    |                  | Chicago |          | 60639    | 
| 1708989      | 2016-07-19T00:00:00 | 81620        | A Safe Haven LLC             | 4750.66        | 961             | MISCELLANEOUS PROFESSIONAL SERVICES | 194591         | 5321453 | 532            | Adult Probation/Probation Service Fee Fund | 5321453            | 532 101 Administration         | A Safe Haven LLC | P O BOX 39083    |                  | Chicago |          | 60639    | 
| 1711566      | 2016-07-29T00:00:00 | 737281       | A.M.C. Mechanical, Inc       | 346.5          | 578             | MISCELLANEOUS PRODUCTS              | 192567         | 2390954 | 239            | Department of Corrections                  | 2390954            | 239 307 Business Office        |                  |                  |                  |         |          |          | 
| 1711566      | 2016-07-29T00:00:00 | 737281       | A.M.C. Mechanical, Inc       | 396            | 578             | MISCELLANEOUS PRODUCTS              | 192567         | 2390954 | 239            | Department of Corrections                  | 2390954            | 239 307 Business Office        |                  |                  |                  |         |          |          | 
| 1711566      | 2016-07-29T00:00:00 | 737281       | A.M.C. Mechanical, Inc       | 643.5          | 578             | MISCELLANEOUS PRODUCTS              | 192567         | 2390954 | 239            | Department of Corrections                  | 2390954            | 239 307 Business Office        |                  |                  |                  |         |          |          | 
```