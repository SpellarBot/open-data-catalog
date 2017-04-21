# 2013 CIP Encumbrances

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2013-cip-encumbrances-5d2bd) |
| Metadata | [Link](https://data.hawaii.gov/api/views/p6rw-tx3z) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/p6rw-tx3z/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/p6rw-tx3z/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | p6rw-tx3z |
| Name | 2013 CIP Encumbrances |
| Attribution | Department of Accounting and General Services |
| Category | Government-Wide Support |
| Created | 2013-01-24T02:12:21Z |
| Publication Date | 2013-04-10T21:00:57Z |

## Description

DAGS supplied data

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | series tag     | transaction_code        | Transaction Code        | text      | number      |
| Yes      | series tag     | fund                    | Fund                    | text      | text        |
| Yes      | time           | fiscal_year             | Fiscal Year             | number    | number      |
| Yes      | numeric metric | account                 | Account                 | number    | number      |
| Yes      | series tag     | department              | Department              | text      | text        |
| Yes      | numeric metric | division                | Division                | number    | number      |
| Yes      | series tag     | mode_of_funding         | Mode of Funding         | text      | text        |
| Yes      | series tag     | current_document_number | Current Document Number | text      | number      |
| Yes      | numeric metric | amount                  | Amount                  | number    | number      |
| Yes      | numeric metric | reverse_indicator       | Reverse Indicator       | number    | number      |
| Yes      | numeric metric | fiscal_month            | Fiscal Month            | number    | number      |
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
series e:p6rw-tx3z d:2012-01-01T00:00:00.000Z t:batch_id="B P121109876" t:department=B t:fund=B t:transaction_code=631 t:current_document_number=61561 t:mode_of_funding=C t:appropriation_type=4 m:fiscal_month=5 m:amount=1400000 m:division=2 m:account=415

series e:p6rw-tx3z d:2010-01-01T00:00:00.000Z t:batch_id="D P121105853" t:department=D t:fund=B t:transaction_code=631 t:current_document_number=61552 t:mode_of_funding=E t:appropriation_type=5 m:fiscal_month=5 m:amount=21810.58 m:division=4 m:account=531

series e:p6rw-tx3z d:2010-01-01T00:00:00.000Z t:batch_id="D P121105853" t:department=D t:fund=S t:transaction_code=631 t:current_document_number=61552 t:mode_of_funding=N t:appropriation_type=C m:fiscal_month=5 m:amount=87242.32 m:division=4 m:account=136
```

## Meta Commands

```ls
metric m:account p:integer l:Account t:dataTypeName=number

metric m:division p:integer l:Division t:dataTypeName=number

metric m:amount p:double l:Amount t:dataTypeName=number

metric m:reverse_indicator p:long l:"Reverse Indicator" t:dataTypeName=number

metric m:fiscal_month p:integer l:"Fiscal Month" t:dataTypeName=number

entity e:p6rw-tx3z l:"2013 CIP Encumbrances" t:attribution="Department of Accounting and General Services" t:url=https://data.hawaii.gov/api/views/p6rw-tx3z

property e:p6rw-tx3z t:meta.view v:id=p6rw-tx3z v:category="Government-Wide Support" v:attributionLink=http://hawaii.gov/dags v:averageRating=0 v:name="2013 CIP Encumbrances" v:attribution="Department of Accounting and General Services"

property e:p6rw-tx3z t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:p6rw-tx3z t:meta.view.owner v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:displayName="OIMT Open Data Coordinator"

property e:p6rw-tx3z t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```

## Top Records

```ls
| transaction_code | fund | fiscal_year | account | department | division | mode_of_funding | current_document_number | amount    | reverse_indicator | fiscal_month | appropriation_type | batch_id     | transaction_year | 
| ================ | ==== | =========== | ======= | ========== | ======== | =============== | ======================= | ========= | ================= | ============ | ================== | ============ | ================ | 
| 631              | B    | 2012        | 415     | B          | 2        | C               | 61561                   | 1400000   |                   | 5            | 4                  | B P121109876 | 2013             | 
| 631              | B    | 2010        | 531     | D          | 4        | E               | 61552                   | 21810.58  |                   | 5            | 5                  | D P121105853 | 2013             | 
| 631              | S    | 2010        | 136     | D          | 4        | N               | 61552                   | 87242.32  |                   | 5            | C                  | D P121105853 | 2013             | 
| 631              | B    | 2011        | 535     | D          | 4        | E               | 61552                   | 40709.42  |                   | 5            | 5                  | D P121105853 | 2013             | 
| 631              | B    | 2011        | 535     | D          | 4        | E               | 61552                   | 3120      |                   | 5            | 5                  | D P121105853 | 2013             | 
| 631              | S    | 2011        | 144     | D          | 4        | N               | 61552                   | 12480     |                   | 5            | C                  | D P121105853 | 2013             | 
| 631              | S    | 2011        | 144     | D          | 4        | N               | 61552                   | 162837.68 |                   | 5            | C                  | D P121105853 | 2013             | 
| 631              | B    | 2012        | 513     | D          | 4        | E               | 61563                   | 208087    |                   | 5            | 5                  | D P121109877 | 2013             | 
| 631              | B    | 2012        | 513     | D          | 4        | E               | 61563                   | 10404     |                   | 5            | 5                  | D P121109877 | 2013             | 
| 631              | B    | 2011        | 535     | D          | 4        | E               | 61564                   | 2200      |                   | 5            | 5                  | D P121109885 | 2013             | 
```