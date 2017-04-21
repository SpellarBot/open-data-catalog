# October 2012 Encumbrances

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/october-2012-encumbrances-3678c) |
| Metadata | [Link](https://data.hawaii.gov/api/views/avhv-dnmd) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/avhv-dnmd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/avhv-dnmd/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | avhv-dnmd |
| Name | October 2012 Encumbrances |
| Attribution | Department of Accounting and General Services |
| Category | Government-Wide Support |
| Created | 2013-01-24T01:55:40Z |
| Publication Date | 2013-01-24T01:58:28Z |

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
series e:avhv-dnmd d:2009-01-01T00:00:00.000Z t:batch_id="A P120815295" t:department=A t:fund=B t:transaction_code=631 t:current_document_number=61319 t:mode_of_funding=C t:appropriation_type=4 m:fiscal_month=2 m:amount=24500 m:account=407

series e:avhv-dnmd d:2011-01-01T00:00:00.000Z t:batch_id="B P120816299" t:department=B t:fund=B t:transaction_code=631 t:current_document_number=61321 t:mode_of_funding=C t:appropriation_type=4 m:fiscal_month=2 m:amount=26000000 m:division=1 m:account=406

series e:avhv-dnmd d:2011-01-01T00:00:00.000Z t:batch_id="B P120822334" t:department=B t:fund=B t:transaction_code=631 t:current_document_number=61321 t:mode_of_funding=C t:appropriation_type=4 m:fiscal_month=2 m:amount=26000000 m:division=1 m:account=406
```

## Meta Commands

```ls
metric m:account p:integer l:Account t:dataTypeName=number

metric m:division p:integer l:Division t:dataTypeName=number

metric m:amount p:double l:Amount t:dataTypeName=number

metric m:reverse_indicator p:long l:"Reverse Indicator" t:dataTypeName=number

metric m:fiscal_month p:integer l:"Fiscal Month" t:dataTypeName=number

entity e:avhv-dnmd l:"October 2012 Encumbrances" t:attribution="Department of Accounting and General Services" t:url=https://data.hawaii.gov/api/views/avhv-dnmd

property e:avhv-dnmd t:meta.view v:id=avhv-dnmd v:category="Government-Wide Support" v:attributionLink=http://hawaii.gov/dags v:averageRating=0 v:name="October 2012 Encumbrances" v:attribution="Department of Accounting and General Services"

property e:avhv-dnmd t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:avhv-dnmd t:meta.view.owner v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:displayName="OIMT Open Data Coordinator"

property e:avhv-dnmd t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```

## Top Records

```ls
| transaction_code | fund | fiscal_year | account | department | division | mode_of_funding | current_document_number | amount   | reverse_indicator | fiscal_month | appropriation_type | batch_id     | transaction_year | 
| ================ | ==== | =========== | ======= | ========== | ======== | =============== | ======================= | ======== | ================= | ============ | ================== | ============ | ================ | 
| 631              | B    | 2009        | 407     | A          |          | C               | 61319                   | 24500    |                   | 2            | 4                  | A P120815295 | 2013             | 
| 631              | B    | 2011        | 406     | B          | 1        | C               | 61321                   | 26000000 |                   | 2            | 4                  | B P120816299 | 2013             | 
| 631              | B    | 2011        | 406     | B          | 1        | C               | 61321                   | 26000000 |                   | 2            | 4                  | B P120822334 | 2013             | 
| 631              | B    | 2009        | 412     | C          |          | C               | 61356                   | 357000   |                   | 2            | 4                  | C P120830372 | 2013             | 
| 631              | B    | 2011        | 428     | C          |          | C               | 61369                   | 278075   |                   | 2            | 4                  | C P120831377 | 2013             | 
| 631              | B    | 2007        | 410     | C          |          | C               | 59591                   | 30000    |                   | 2            | 4                  | C P120906408 | 2013             | 
| 631              | S    | 2011        | 275     | C          |          | N               | 61391                   | 200000   |                   | 2            | C                  | C P120906412 | 2013             | 
| 631              | S    | 2011        | 276     | C          |          | N               | 61391                   | 168200   |                   | 2            | C                  | C P120906412 | 2013             | 
| 631              | B    | 2011        | 541     | D          | 4        | E               | 61301                   | 319200   |                   | 2            | 5                  | D P120807258 | 2013             | 
| 631              | B    | 2011        | 541     | D          | 4        | E               | 61301                   | 20800    |                   | 2            | 5                  | D P120807258 | 2013             | 
```