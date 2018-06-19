# Illinois Guardianship and Advocacy Commission Number Of Wards by Region

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/illinois-guardianship-and-advocacy-commission-number-of-wards-by-region-dd5f2) |
| Metadata | [Link](https://data.illinois.gov/api/views/8kur-y9ks) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/8kur-y9ks/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/8kur-y9ks/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 8kur-y9ks |
| Name | Illinois Guardianship and Advocacy Commission Number Of Wards by Region |
| Category | Social/Healthcare |
| Tags | igac, disabilities, wards, caseload, guardian, guardianship |
| Created | 2013-02-08T16:28:28Z |
| Publication Date | 2013-02-14T18:56:26Z |

## Description

Break down of the number of wards served by Illinois Guardianship and Advocacy Commission by regional offices.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | region      | REGION     | text      | text        |
| Yes      | numeric metric | fy_08       | FY 08      | number    | number      |
| Yes      | numeric metric | fy_09       | FY 09      | number    | number      |
| Yes      | numeric metric | fy_10       | FY 10      | number    | number      |
| Yes      | numeric metric | fy_11       | FY 11      | number    | number      |
| Yes      | numeric metric | fy_12       | FY 12      | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:8kur-y9ks d:2013-02-08T08:28:29.000Z t:region="CHICAGO & WESTSUBURBAN" m:fy_09=1440 m:fy_08=1465 m:fy_10=1453 m:fy_12=1577 m:fy_11=1534

series e:8kur-y9ks d:2013-02-08T08:28:29.000Z t:region="EAST CENTRAL - CHAMPAIN" m:fy_09=657 m:fy_08=680 m:fy_10=667 m:fy_12=639 m:fy_11=660

series e:8kur-y9ks d:2013-02-08T08:28:29.000Z t:region="EGYPTIAN - ANNA" m:fy_09=515 m:fy_08=540 m:fy_10=508 m:fy_12=461 m:fy_11=464
```

## Meta Commands

```ls
metric m:fy_08 p:integer l:"FY 08" t:dataTypeName=number

metric m:fy_09 p:integer l:"FY 09" t:dataTypeName=number

metric m:fy_10 p:integer l:"FY 10" t:dataTypeName=number

metric m:fy_11 p:integer l:"FY 11" t:dataTypeName=number

metric m:fy_12 p:integer l:"FY 12" t:dataTypeName=number

entity e:8kur-y9ks l:"Illinois Guardianship and Advocacy Commission Number Of Wards by Region" t:url=https://data.illinois.gov/api/views/8kur-y9ks

property e:8kur-y9ks t:meta.view v:id=8kur-y9ks v:category=Social/Healthcare v:averageRating=0 v:name="Illinois Guardianship and Advocacy Commission Number Of Wards by Region"

property e:8kur-y9ks t:meta.view.owner v:id=vtpq-vdyg v:screenName=rdixo4 v:displayName=rdixo4

property e:8kur-y9ks t:meta.view.tableauthor v:id=vtpq-vdyg v:screenName=rdixo4 v:roleName=publisher v:displayName=rdixo4
```

## Top Records

```ls
| :updated_at | region                  | fy_08 | fy_09 | fy_10 | fy_11 | fy_12 | 
| =========== | ======================= | ===== | ===== | ===== | ===== | ===== | 
| 1360312109  | CHICAGO & WESTSUBURBAN  | 1465  | 1440  | 1453  | 1534  | 1577  | 
| 1360312109  | EAST CENTRAL - CHAMPAIN | 680   | 657   | 667   | 660   | 639   | 
| 1360312109  | EGYPTIAN - ANNA         | 540   | 515   | 508   | 464   | 461   | 
| 1360312109  | METRO EAST - ALTON      | 461   | 458   | 431   | 452   | 439   | 
| 1360312109  | NORTH SUBURBAN          | 831   | 821   | 817   | 826   | 840   | 
| 1360312109  | PEORIA                  | 482   | 468   | 467   | 467   | 467   | 
| 1360312109  | ROCKFORD                | 505   | 502   | 520   | 524   | 537   | 
| 1360312109  | YEARLY TOTALS           | 4964  | 4861  | 4863  | 4927  | 4960  | 
```