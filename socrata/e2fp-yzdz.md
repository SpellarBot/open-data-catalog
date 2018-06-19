# Funded Status

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/funded-status) |
| Metadata | [Link](https://data.lacity.org/api/views/e2fp-yzdz) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/e2fp-yzdz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/e2fp-yzdz/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | e2fp-yzdz |
| Name | Funded Status |
| Category | A Well Run City |
| Tags | funded status |
| Created | 2014-05-23T22:44:27Z |
| Publication Date | 2015-12-07T20:44:55Z |

## Description

Funded Status

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                    | Data Type | Render Type |
| ======== | ============== | ===================== | ======================= | ========= | =========== |
| Yes      | time           | fiscal_year_ending    | Fiscal Year Ending      | number    | text        |
| Yes      | numeric metric | funded_status_pension | Funded Status (Pension) | percent   | percent     |
```

## Time Field

```ls
Value = fiscal_year_ending
Format & Zone = yyyy
```

## Data Commands

```ls
series e:e2fp-yzdz d:2010-01-01T00:00:00.000Z m:funded_status_pension=91.6

series e:e2fp-yzdz d:2011-01-01T00:00:00.000Z m:funded_status_pension=86.3

series e:e2fp-yzdz d:2012-01-01T00:00:00.000Z m:funded_status_pension=83.7
```

## Meta Commands

```ls
metric m:funded_status_pension p:float l:"Funded Status (Pension)" t:dataTypeName=percent

entity e:e2fp-yzdz l:"Funded Status" t:url=https://data.lacity.org/api/views/e2fp-yzdz

property e:e2fp-yzdz t:meta.view v:id=e2fp-yzdz v:category="A Well Run City" v:averageRating=0 v:name="Funded Status"

property e:e2fp-yzdz t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:e2fp-yzdz t:meta.view.owner v:id=sgjw-6a7f v:profileImageUrlMedium=/api/users/sgjw-6a7f/profile_images/THUMB v:profileImageUrlLarge=/api/users/sgjw-6a7f/profile_images/LARGE v:screenName="Fire & Police Pensions OpenData" v:profileImageUrlSmall=/api/users/sgjw-6a7f/profile_images/TINY v:displayName="Fire & Police Pensions OpenData"

property e:e2fp-yzdz t:meta.view.tableauthor v:id=sgjw-6a7f v:profileImageUrlMedium=/api/users/sgjw-6a7f/profile_images/THUMB v:profileImageUrlLarge=/api/users/sgjw-6a7f/profile_images/LARGE v:screenName="Fire & Police Pensions OpenData" v:profileImageUrlSmall=/api/users/sgjw-6a7f/profile_images/TINY v:roleName=publisher v:displayName="Fire & Police Pensions OpenData"
```

## Top Records

```ls
| fiscal_year_ending | funded_status_pension | 
| ================== | ===================== | 
| 2010               | 91.60                 | 
| 2011               | 86.30                 | 
| 2012               | 83.70                 | 
| 2013               | 83.10                 | 
```