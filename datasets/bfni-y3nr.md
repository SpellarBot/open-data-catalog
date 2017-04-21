# Cook County Check Register - Fiscal Years 2006 through 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cook-county-check-register-fiscal-years-2006-through-2013-47763) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/bfni-y3nr) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/bfni-y3nr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/bfni-y3nr/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | bfni-y3nr |
| Name | Cook County Check Register - Fiscal Years 2006 through 2013 |
| Attribution | Cook County Office of the Comptroller |
| Category | Finance & Administration |
| Tags | comptroller, check register, finance |
| Created | 2012-08-02T15:48:33Z |
| Publication Date | 2014-01-09T17:21:44Z |

## Description

New check register data can be found at https://datacatalog.cookcountyil.gov/id/gywr-fjeh. This register contains checks from December 2006 through November 2013. This dataset will not be updated.

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                          | Data Type     | Render Type   |
| ======== | ============== | ============================= | ============================= | ============= | ============= |
| Yes      | series tag     | check_number                  | Check Number                  | text          | text          |
| Yes      | series tag     | payee_number                  | Payee Number                  | text          | text          |
| Yes      | series tag     | company_name                  | Company Name                  | text          | text          |
| Yes      | series tag     | purchase_order_number         | Purchase Order Number         | text          | text          |
| Yes      | series tag     | product_descritpion_nigp_code | Product Descritpion NIGP Code | text          | number        |
| Yes      | series tag     | description                   | Description                   | text          | text          |
| Yes      | series tag     | business_unit                 | Business Unit                 | text          | text          |
| Yes      | numeric metric | payment_amount                | Payment Amount                | money         | money         |
| Yes      | time           | check_date                    | Check Date                    | calendar_date | calendar_date |
```

## Time Field

```ls
Value = check_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:bfni-y3nr d:2006-12-07T08:00:00.000Z t:business_unit=72821030 t:payee_number=772613 t:purchase_order_number=146601 t:company_name="Champion Environmental Services" t:description="CONSTRUCTION SERVICES, GENERAL" t:product_descritpion_nigp_code=912 t:check_number=943393 m:payment_amount=190000

series e:bfni-y3nr d:2006-12-07T08:00:00.000Z t:business_unit=72020520 t:payee_number=76703 t:purchase_order_number=141602 t:company_name="Lombard Co" t:description="CONSTRUCTION SERVICES, GENERAL" t:product_descritpion_nigp_code=912 t:check_number=943395 m:payment_amount=98685

series e:bfni-y3nr d:2006-12-07T08:00:00.000Z t:business_unit=72020520 t:payee_number=76703 t:purchase_order_number=141602 t:company_name="Lombard Co" t:description="CONSTRUCTION SERVICES, GENERAL" t:product_descritpion_nigp_code=912 t:check_number=943395 m:payment_amount=40905
```

## Meta Commands

```ls
metric m:payment_amount p:double l:"Payment Amount" t:dataTypeName=money

entity e:bfni-y3nr l:"Cook County Check Register - Fiscal Years 2006 through 2013" t:attribution="Cook County Office of the Comptroller" t:url=https://datacatalog.cookcountyil.gov/api/views/bfni-y3nr

property e:bfni-y3nr t:meta.view v:id=bfni-y3nr v:category="Finance & Administration" v:attributionLink=http://www.cookcountygov.com/portal/server.pt/community/comptroller%2C_office_of_the/266/comptroller%2C_office_of_the v:averageRating=0 v:name="Cook County Check Register - Fiscal Years 2006 through 2013" v:attribution="Cook County Office of the Comptroller"

property e:bfni-y3nr t:meta.view.license v:name="Public Domain"

property e:bfni-y3nr t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:bfni-y3nr t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| check_number | payee_number | company_name                         | purchase_order_number | product_descritpion_nigp_code | description                                                | business_unit | payment_amount | check_date          | 
| ============ | ============ | ==================================== | ===================== | ============================= | ========================================================== | ============= | ============== | =================== | 
| 943393       | 772613       | Champion Environmental Services      | 146601                | 912                           | CONSTRUCTION SERVICES, GENERAL                             | 72821030      | 190000.00      | 2006-12-07T08:00:00 | 
| 943395       | 76703        | Lombard Co                           | 141602                | 912                           | CONSTRUCTION SERVICES, GENERAL                             | 72020520      | 98685.00       | 2006-12-07T08:00:00 | 
| 943395       | 76703        | Lombard Co                           | 141602                | 912                           | CONSTRUCTION SERVICES, GENERAL                             | 72020520      | 40905.00       | 2006-12-07T08:00:00 | 
| 943397       | 546685       | Northwestern University Acct Service | 150679                | 962                           | MISCELLANEOUS SERVICES                                     | 3260801       | 150186.97      | 2006-12-07T08:00:00 | 
| 943397       | 546685       | Northwestern University Acct Service | 150679                | 962                           | MISCELLANEOUS SERVICES                                     | 3260801       | 7226.26        | 2006-12-07T08:00:00 | 
| 943397       | 546685       | Northwestern University Acct Service | 150679                | 962                           | MISCELLANEOUS SERVICES                                     | 3260801       | 8916.05        | 2006-12-07T08:00:00 | 
| 943400       | 76969        | Tasc Inc                             | 152525                | 961                           | MISCELLANEOUS PROFESSIONAL SERVICES                        | 2500900       | 58502.83       | 2006-12-07T08:00:00 | 
| 943400       | 76969        | Tasc Inc                             | 152525                | 961                           | MISCELLANEOUS PROFESSIONAL SERVICES                        | 2500900       | 58502.83       | 2006-12-07T08:00:00 | 
| 944167       | 83018        | Abbott Labs Diagnostics Division     | 143343                | 465                           | HOSPITAL AND SURGICAL EQUIPMENT, INSTRUMENTS, AND SUPPLIES | 8912036       | 4177.42        | 2006-12-07T08:00:00 | 
| 944178       | 779370       | Advanced Concepts Chicago Inc        | 154367                | 918                           | CONSULTING SERVICES                                        | 5270582       | 8541.50        | 2006-12-07T08:00:00 | 
```