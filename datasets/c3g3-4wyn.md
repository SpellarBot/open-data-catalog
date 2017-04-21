# Risk Management - Provider Payments - April 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/risk-management-provider-payments-april-2012-a43c1) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/c3g3-4wyn) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/c3g3-4wyn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/c3g3-4wyn/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | c3g3-4wyn |
| Name | Risk Management - Provider Payments - April 2012 |
| Attribution | Cook County Department of Risk Management |
| Category | Finance & Administration |
| Created | 2012-05-21T17:04:59Z |
| Publication Date | 2014-10-09T22:27:27Z |

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type     | Render Type   |
| ======== | ============== | ======================== | ======================== | ============= | ============= |
| Yes      | series tag     | hospital_billing         | HOSPITAL (BILLING)       | text          | text          |
| Yes      | numeric metric | total_billed             | TOTAL BILLED             | money         | money         |
| Yes      | numeric metric | idhfs_discount           | IDHFS DISCOUNT           | money         | money         |
| Yes      | numeric metric | unrelated                | UNRELATED                | money         | money         |
| Yes      | numeric metric | provider_discount        | PROVIDER DISCOUNT        | money         | money         |
| Yes      | numeric metric | amount_payable           | AMOUNT PAYABLE           | money         | money         |
| Yes      | time           | board_meeting            | BOARD MEETING            | calendar_date | calendar_date |
| No       |                | fiscal_year_of_payment   | FISCAL YEAR OF PAYMENT   | number        | text          |
| No       |                | fiscal_year_of_treatment | FISCAL YEAR OF TREATMENT | number        | text          |
```

## Time Field

```ls
Value = board_meeting
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = fiscal_year_of_treatment,fiscal_year_of_payment
```

## Data Commands

```ls
series e:c3g3-4wyn d:2012-04-03T00:00:00.000Z t:hospital_billing="SINAI MEDICAL GROUP" m:amount_payable=69 m:idhfs_discount=252 m:unrelated=0 m:provider_discount=0 m:total_billed=321

series e:c3g3-4wyn d:2012-04-03T00:00:00.000Z t:hospital_billing="ST. ANTHONY HOSPITAL" m:amount_payable=2236.92 m:idhfs_discount=0 m:unrelated=0 m:provider_discount=3089.08 m:total_billed=5326

series e:c3g3-4wyn d:2012-04-03T00:00:00.000Z t:hospital_billing="CITY OF CHICAGO DEPT OF REVENUE" m:amount_payable=678 m:idhfs_discount=0 m:unrelated=0 m:provider_discount=0 m:total_billed=678
```

## Meta Commands

```ls
metric m:total_billed p:double l:"TOTAL BILLED" t:dataTypeName=money

metric m:idhfs_discount p:double l:"IDHFS DISCOUNT" t:dataTypeName=money

metric m:unrelated p:double l:UNRELATED t:dataTypeName=money

metric m:provider_discount p:double l:"PROVIDER DISCOUNT" t:dataTypeName=money

metric m:amount_payable p:double l:"AMOUNT PAYABLE" t:dataTypeName=money

entity e:c3g3-4wyn l:"Risk Management - Provider Payments - April 2012" t:attribution="Cook County Department of Risk Management" t:url=https://datacatalog.cookcountyil.gov/api/views/c3g3-4wyn

property e:c3g3-4wyn t:meta.view v:id=c3g3-4wyn v:category="Finance & Administration" v:attributionLink=http://www.cookcountyrisk.com/ v:averageRating=0 v:name="Risk Management - Provider Payments - April 2012" v:attribution="Cook County Department of Risk Management"

property e:c3g3-4wyn t:meta.view.license v:name="Public Domain"

property e:c3g3-4wyn t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:c3g3-4wyn t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| hospital_billing                | total_billed | idhfs_discount | unrelated | provider_discount | amount_payable | board_meeting       | fiscal_year_of_payment | fiscal_year_of_treatment | 
| =============================== | ============ | ============== | ========= | ================= | ============== | =================== | ====================== | ======================== | 
| SINAI MEDICAL GROUP             | 321.00       | 252.00         | 0.00      | 0.00              | 69.00          | 2012-04-03T00:00:00 | 2012                   | 2011                     | 
| ST. ANTHONY HOSPITAL            | 5326.00      | 0.00           | 0.00      | 3089.08           | 2236.92        | 2012-04-03T00:00:00 | 2012                   | 2010                     | 
| CITY OF CHICAGO DEPT OF REVENUE | 678.00       | 0.00           | 0.00      | 0.00              | 678.00         | 2012-04-03T00:00:00 | 2012                   | 2010                     | 
| LOYOLA UNIVERSITY MED. CNTR.    | 16273.60     | 14533.47       | 0.00      | 0.00              | 1740.13        | 2012-04-03T00:00:00 | 2012                   | 2011                     | 
| OAKLAWN RADIOLOGY IMAGING       | 43.00        | 32.25          | 0.00      | 0.00              | 10.75          | 2012-04-03T00:00:00 | 2012                   | 2011                     | 
| SINAI MEDICAL GROUP             | 210.00       | 160.80         | 0.00      | 0.00              | 49.20          | 2012-04-03T00:00:00 | 2012                   | 2011                     | 
| RESURRECTION MED GRP - ST. MARY | 699.00       | 629.75         | 0.00      | 0.00              | 69.25          | 2012-04-03T00:00:00 | 2012                   | 2011                     | 
| LOYOLA UNIVERSITY MEDICAL GROUP | 5184.98      | 0.00           | 4776.98   | 40.80             | 367.20         | 2012-04-03T00:00:00 | 2012                   | 2010                     | 
| LOYOLA UNIVERSITY MEDICAL GROUP | 509.00       | 0.00           | 0.00      | 50.90             | 458.10         | 2012-04-03T00:00:00 | 2012                   | 2010                     | 
| LOYOLA UNIVERSITY MEDICAL GROUP | 144.00       | 0.00           | 96.00     | 4.80              | 43.20          | 2012-04-03T00:00:00 | 2012                   | 2010                     | 
```