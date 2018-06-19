# Risk Management - Payments to Healthcare Providers for Inmate Care, by Payment Year, by Vendor

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/risk-management-payments-to-healthcare-providers-for-inmate-care-by-payment-year-by-vendor-37ec3) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/a5kn-k8qb) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/a5kn-k8qb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/a5kn-k8qb/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | a5kn-k8qb |
| Name | Risk Management - Payments to Healthcare Providers for Inmate Care, by Payment Year, by Vendor |
| Attribution | Cook County Department of Risk Management |
| Category | Healthcare |
| Created | 2011-09-08T13:47:41Z |
| Publication Date | 2014-10-09T21:18:55Z |

## Description

A list of payments to healthcare providers for services rendered to Sheriff detainees that were paid beginning in December 2010 through July 2012.

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| Yes      | series tag     | hospital                 | HOSPITAL                 | text      | text        |
| Yes      | numeric metric | original_billed_amount   | ORIGINAL BILLED AMOUNT   | money     | money       |
| Yes      | numeric metric | idhfs_discount           | IDHFS DISCOUNT           | money     | money       |
| Yes      | numeric metric | unrelated                | UNRELATED                | money     | money       |
| Yes      | numeric metric | provider_discount        | PROVIDER DISCOUNT        | money     | money       |
| Yes      | numeric metric | amount_payable           | AMOUNT PAYABLE           | money     | money       |
| Yes      | time           | board_meeting_date       | BOARD MEETING DATE       | date      | date        |
| No       |                | fiscal_year_of_payment   | FISCAL YEAR OF PAYMENT   | number    | text        |
| No       |                | fiscal_year_of_treatment | FISCAL YEAR OF TREATMENT | number    | text        |
```

## Time Field

```ls
Value = board_meeting_date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = fiscal_year_of_treatment,fiscal_year_of_payment
```

## Data Commands

```ls
series e:a5kn-k8qb d:2011-05-04T07:00:00.000Z t:hospital="SINAI COMMUNITY FOUNDATION" m:amount_payable=69.55 m:idhfs_discount=209 m:unrelated=0 m:provider_discount=0 m:original_billed_amount=279

series e:a5kn-k8qb d:2011-05-04T07:00:00.000Z t:hospital="SINAI PATHOLOGY ASSOCIATES" m:amount_payable=13.61 m:idhfs_discount=70 m:unrelated=0 m:provider_discount=0 m:original_billed_amount=84

series e:a5kn-k8qb d:2011-05-04T07:00:00.000Z t:hospital="SINAI COMMUNITY FOUNDATION" m:amount_payable=16.4 m:idhfs_discount=54 m:unrelated=0 m:provider_discount=0 m:original_billed_amount=70
```

## Meta Commands

```ls
metric m:original_billed_amount p:double l:"ORIGINAL BILLED AMOUNT" t:dataTypeName=money

metric m:idhfs_discount p:double l:"IDHFS DISCOUNT" t:dataTypeName=money

metric m:unrelated p:integer l:UNRELATED t:dataTypeName=money

metric m:provider_discount p:integer l:"PROVIDER DISCOUNT" t:dataTypeName=money

metric m:amount_payable p:double l:"AMOUNT PAYABLE" t:dataTypeName=money

entity e:a5kn-k8qb l:"Risk Management - Payments to Healthcare Providers for Inmate Care, by Payment Year, by Vendor" t:attribution="Cook County Department of Risk Management" t:url=https://datacatalog.cookcountyil.gov/api/views/a5kn-k8qb

property e:a5kn-k8qb t:meta.view v:id=a5kn-k8qb v:category=Healthcare v:attributionLink=http://www.cookcountyrisk.com/ v:averageRating=0 v:name="Risk Management - Payments to Healthcare Providers for Inmate Care, by Payment Year, by Vendor" v:attribution="Cook County Department of Risk Management"

property e:a5kn-k8qb t:meta.view.license v:name="Public Domain"

property e:a5kn-k8qb t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:a5kn-k8qb t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| hospital                      | original_billed_amount | idhfs_discount | unrelated | provider_discount | amount_payable | board_meeting_date | fiscal_year_of_payment | fiscal_year_of_treatment | 
| ============================= | ====================== | ============== | ========= | ================= | ============== | ================== | ====================== | ======================== | 
| SINAI COMMUNITY FOUNDATION    | 279                    | 209            | 0         | 0                 | 69.55          | 1304492400         | 2011                   | 2011                     | 
| SINAI PATHOLOGY ASSOCIATES    | 84                     | 70             | 0         | 0                 | 13.61          | 1304492400         | 2011                   | 2011                     | 
| SINAI COMMUNITY FOUNDATION    | 70                     | 54             | 0         | 0                 | 16.40          | 1304492400         | 2011                   | 2011                     | 
| PALOS COMMUNITY HOSPITAL      | 560                    | 466            | 0         | 0                 | 94.20          | 1304492400         | 2011                   | 2011                     | 
| SINAI PATHOLOGY ASSOCIATES    | 1446                   | 1215           | 0         | 0                 | 230.78         | 1304492400         | 2011                   | 2011                     | 
| SOUTH SUBURBAN HOSPITAL       | 534                    | 353            | 0         | 0                 | 181.00         | 1304492400         | 2011                   | 2011                     | 
| SUBURBAN EMERGENCY PHYSICIANS | 60                     | 46             | 0         | 0                 | 14.35          | 1304492400         | 2011                   | 2011                     | 
| CHICAGO IMAGING ASSOC LLC     | 43                     | 32             | 0         | 0                 | 10.75          | 1304492400         | 2011                   | 2011                     | 
| ST. ANTHONY HOSPITAL          | 9696                   | 6872           | 0         | 0                 | 2823.61        | 1304492400         | 2011                   | 2011                     | 
| RUSH-ST. LUKE MED. CNTR       | 19949                  | 18900          | 0         | 0                 | 1049.00        | 1304492400         | 2011                   | 2011                     | 
```