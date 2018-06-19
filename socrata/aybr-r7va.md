# CIP Encumberances June 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cip-encumberances-june-2012-c3032) |
| Metadata | [Link](https://data.hawaii.gov/api/views/aybr-r7va) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/aybr-r7va/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/aybr-r7va/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | aybr-r7va |
| Name | CIP Encumberances June 2012 |
| Attribution | Accounting Division of Department of Accounting and General Services |
| Category | Government-Wide Support |
| Tags | famis, dags |
| Created | 2012-08-20T21:20:08Z |
| Publication Date | 2012-11-07T19:46:57Z |

## Description

CIP Encumbrances. Created from a monthly extract of FAMIS - Financial Administration and Management System. Additional analysis may need to be done to interpret fields

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | series tag     | transaction_code        | Transaction Code        | text      | text        |
| Yes      | series tag     | fund                    | Fund                    | text      | text        |
| Yes      | time           | fiscal_year             | Fiscal Year             | number    | number      |
| Yes      | numeric metric | account                 | Account                 | number    | text        |
| Yes      | series tag     | department              | Department              | text      | text        |
| Yes      | series tag     | division                | Division                | text      | text        |
| Yes      | series tag     | mode_of_funding         | Mode of Funding         | text      | text        |
| Yes      | series tag     | current_document_number | Current Document Number | text      | text        |
| Yes      | numeric metric | amount                  | Amount                  | money     | money       |
| Yes      | series tag     | reverse_indicator       | Reverse Indicator       | text      | text        |
| Yes      | numeric metric | fiscal_month            | Fiscal Month            | number    | text        |
| Yes      | series tag     | appropriation_type      | Appropriation Type      | text      | text        |
| Yes      | series tag     | batch_id                | Batch ID                | text      | text        |
| No       |                | transaction_year        | Transaction Year        | number    | number      |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = transaction_year
```

## Data Commands

```ls
series e:aybr-r7va d:2011-01-01T00:00:00.000Z t:batch_id="C P120613016" t:department=C t:fund=B t:transaction_code=631 t:current_document_number=61040 t:mode_of_funding=C t:appropriation_type=4 m:fiscal_month=12 m:amount=948900 m:account=445

series e:aybr-r7va d:2011-01-01T00:00:00.000Z t:batch_id="C P120613017" t:department=C t:fund=B t:transaction_code=631 t:current_document_number=61045 t:mode_of_funding=C t:appropriation_type=4 m:fiscal_month=12 m:amount=33491.72 m:account=428

series e:aybr-r7va d:2011-01-01T00:00:00.000Z t:batch_id="C P120613016" t:department=C t:fund=B t:transaction_code=631 t:current_document_number=61040 t:mode_of_funding=C t:appropriation_type=4 m:fiscal_month=12 m:amount=47445 m:account=445
```

## Meta Commands

```ls
metric m:account p:integer l:Account t:dataTypeName=number

metric m:amount p:integer l:Amount t:dataTypeName=money

metric m:fiscal_month p:integer l:"Fiscal Month" t:dataTypeName=number

entity e:aybr-r7va l:"CIP Encumberances June 2012" t:attribution="Accounting Division of Department of Accounting and General Services" t:url=https://data.hawaii.gov/api/views/aybr-r7va

property e:aybr-r7va t:meta.view v:id=aybr-r7va v:category="Government-Wide Support" v:attributionLink=http://hawaii.gov/dags/ v:averageRating=0 v:name="CIP Encumberances June 2012" v:attribution="Accounting Division of Department of Accounting and General Services"

property e:aybr-r7va t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:aybr-r7va t:meta.view.owner v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:displayName="OIMT Open Data Coordinator"

property e:aybr-r7va t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```

## Top Records

```ls
| transaction_code | fund | fiscal_year | account | department | division | mode_of_funding | current_document_number | amount   | reverse_indicator | fiscal_month | appropriation_type | batch_id     | transaction_year | 
| ================ | ==== | =========== | ======= | ========== | ======== | =============== | ======================= | ======== | ================= | ============ | ================== | ============ | ================ | 
| 631              | B    | 2011        | 445     | C          |          | C               | 61040                   | 948900   |                   | 12           | 4                  | C P120613016 | 2012             | 
| 631              | B    | 2011        | 428     | C          |          | C               | 61045                   | 33491.72 |                   | 12           | 4                  | C P120613017 | 2012             | 
| 631              | B    | 2011        | 445     | C          |          | C               | 61040                   | 47445    |                   | 12           | 4                  | C P120613016 | 2012             | 
| 631              | B    | 2011        | 419     | C          |          | C               | 61063                   | 227834   |                   | 12           | 4                  | C P120614073 | 2012             | 
| 631              | B    | 2011        | 419     | C          |          | C               | 61063                   | 6100     |                   | 12           | 4                  | C P120614073 | 2012             | 
| 631              | B    | 2011        | 419     | C          |          | C               | 61063                   | 1200     |                   | 12           | 4                  | C P120614073 | 2012             | 
| 631              | B    | 2011        | 419     | C          |          | C               | 61063                   | 4454     |                   | 12           | 4                  | C P120614073 | 2012             | 
| 631              | B    | 2008        | 419     | C          |          | C               | 59897                   | 12060    |                   | 12           | 4                  | C P120615092 | 2012             | 
| 631              | B    | 2011        | 419     | C          |          | C               | 61110                   | 179421   |                   | 12           | 4                  | C P120620145 | 2012             | 
| 631              | B    | 2011        | 420     | C          |          | C               | 61110                   | 136536   |                   | 12           | 4                  | C P120620145 | 2012             | 
```