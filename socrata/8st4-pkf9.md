# September 2012 Encumbrances

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/september-2012-encumbrances-cd83b) |
| Metadata | [Link](https://data.hawaii.gov/api/views/8st4-pkf9) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/8st4-pkf9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/8st4-pkf9/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 8st4-pkf9 |
| Name | September 2012 Encumbrances |
| Attribution | Department of Accounting and General Services |
| Category | Government-Wide Support |
| Tags | ebcumbrance |
| Created | 2013-01-24T01:51:27Z |
| Publication Date | 2013-01-24T01:54:50Z |

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
series e:8st4-pkf9 d:2011-01-01T00:00:00.000Z t:batch_id="A P120907429" t:department=A t:fund=B t:transaction_code=631 t:current_document_number=59954 t:mode_of_funding=C t:appropriation_type=4 m:fiscal_month=3 m:amount=1695955 m:account=409

series e:8st4-pkf9 d:2011-01-01T00:00:00.000Z t:batch_id="A P120917474" t:department=A t:fund=B t:transaction_code=631 t:current_document_number=58062 t:mode_of_funding=C t:appropriation_type=4 m:fiscal_month=3 m:amount=39320 m:account=408

series e:8st4-pkf9 d:2001-01-01T00:00:00.000Z t:batch_id="A P120927570" t:department=A t:fund=B t:transaction_code=631 t:current_document_number=61467 t:mode_of_funding=C t:appropriation_type=4 m:fiscal_month=3 m:amount=47600 m:account=802
```

## Meta Commands

```ls
metric m:account p:integer l:Account t:dataTypeName=number

metric m:division p:integer l:Division t:dataTypeName=number

metric m:amount p:integer l:Amount t:dataTypeName=number

metric m:reverse_indicator p:long l:"Reverse Indicator" t:dataTypeName=number

metric m:fiscal_month p:integer l:"Fiscal Month" t:dataTypeName=number

entity e:8st4-pkf9 l:"September 2012 Encumbrances" t:attribution="Department of Accounting and General Services" t:url=https://data.hawaii.gov/api/views/8st4-pkf9

property e:8st4-pkf9 t:meta.view v:id=8st4-pkf9 v:category="Government-Wide Support" v:attributionLink=http://hawaii.gov/dags v:averageRating=0 v:name="September 2012 Encumbrances" v:attribution="Department of Accounting and General Services"

property e:8st4-pkf9 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:8st4-pkf9 t:meta.view.owner v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:displayName="OIMT Open Data Coordinator"

property e:8st4-pkf9 t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```

## Top Records

```ls
| transaction_code | fund | fiscal_year | account | department | division | mode_of_funding | current_document_number | amount  | reverse_indicator | fiscal_month | appropriation_type | batch_id     | transaction_year | 
| ================ | ==== | =========== | ======= | ========== | ======== | =============== | ======================= | ======= | ================= | ============ | ================== | ============ | ================ | 
| 631              | B    | 2011        | 409     | A          |          | C               | 59954                   | 1695955 |                   | 3            | 4                  | A P120907429 | 2013             | 
| 631              | B    | 2011        | 408     | A          |          | C               | 58062                   | 39320   |                   | 3            | 4                  | A P120917474 | 2013             | 
| 631              | B    | 2001        | 802     | A          |          | C               | 61467                   | 47600   |                   | 3            | 4                  | A P120927570 | 2013             | 
| 631              | B    | 2009        | 405     | A          |          | C               | 61466                   | 129524  |                   | 3            | 4                  | A P120927571 | 2013             | 
| 631              | B    | 2011        | 419     | A          |          | C               | 61466                   | 29165   |                   | 3            | 4                  | A P120927571 | 2013             | 
| 631              | B    | 2011        | 430     | C          |          | C               | 61407                   | 195000  |                   | 3            | 4                  | C P120911442 | 2013             | 
| 631              | B    | 2011        | 432     | C          |          | C               | 61407                   | 585000  |                   | 3            | 4                  | C P120911442 | 2013             | 
| 631              | B    | 2011        | 433     | C          |          | C               | 61407                   | 478695  |                   | 3            | 4                  | C P120911442 | 2013             | 
| 631              | B    | 2011        | 445     | C          |          | C               | 61431                   | 835209  |                   | 3            | 4                  | C P120920499 | 2013             | 
| 631              | B    | 2011        | 445     | C          |          | C               | 61431                   | 41760   |                   | 3            | 4                  | C P120920499 | 2013             | 
```