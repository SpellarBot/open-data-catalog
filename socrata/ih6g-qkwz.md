# Open Budget - Revenue 2010-2017

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/open-budget-revenue-2010-2017) |
| Metadata | [Link](https://data.lacity.org/api/views/ih6g-qkwz) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/ih6g-qkwz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/ih6g-qkwz/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | ih6g-qkwz |
| Name | Open Budget - Revenue 2010-2017 |
| Category | A Prosperous City |
| Tags | budget, revenue |
| Created | 2016-03-08T23:29:58Z |
| Publication Date | 2016-07-11T16:51:27Z |

## Description

Revenue amounts by high level source for use in the LA city open budget portal, http://lacity.budget.socrata.com/

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | series tag     | revenue_source | Revenue Source | text      | text        |
| Yes      | numeric metric | amount         | Amount         | number    | number      |
| Yes      | series tag     | fund_type      | Fund_Type      | text      | text        |
| Yes      | time           | fiscal_year    | Fiscal_Year    | number    | number      |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ih6g-qkwz d:2010-01-01T00:00:00.000Z t:fund_type=General t:revenue_source="Residential Development Tax" m:amount=1700000

series e:ih6g-qkwz d:2010-01-01T00:00:00.000Z t:fund_type=General t:revenue_source="Transfer from Telecommunications Dev. Account" m:amount=6223000

series e:ih6g-qkwz d:2010-01-01T00:00:00.000Z t:fund_type=General t:revenue_source="State Motor Vehicle License Fees" m:amount=12000000
```

## Meta Commands

```ls
metric m:amount p:integer l:Amount t:dataTypeName=number

entity e:ih6g-qkwz l:"Open Budget - Revenue 2010-2017" t:url=https://data.lacity.org/api/views/ih6g-qkwz

property e:ih6g-qkwz t:meta.view v:id=ih6g-qkwz v:category="A Prosperous City" v:averageRating=0 v:name="Open Budget - Revenue 2010-2017"

property e:ih6g-qkwz t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:ih6g-qkwz t:meta.view.owner v:id=95pg-i79k v:profileImageUrlMedium=/api/users/95pg-i79k/profile_images/THUMB v:profileImageUrlLarge=/api/users/95pg-i79k/profile_images/LARGE v:screenName=ChelseaU v:profileImageUrlSmall=/api/users/95pg-i79k/profile_images/TINY v:displayName=ChelseaU

property e:ih6g-qkwz t:meta.view.tableauthor v:id=95pg-i79k v:profileImageUrlMedium=/api/users/95pg-i79k/profile_images/THUMB v:profileImageUrlLarge=/api/users/95pg-i79k/profile_images/LARGE v:screenName=ChelseaU v:profileImageUrlSmall=/api/users/95pg-i79k/profile_images/TINY v:roleName=administrator v:displayName=ChelseaU
```

## Top Records

```ls
| revenue_source                                | amount    | fund_type | fiscal_year | 
| ============================================= | ========= | ========= | =========== | 
| Residential Development Tax                   | 1700000   | General   | 2010        | 
| Transfer from Telecommunications Dev. Account | 6223000   | General   | 2010        | 
| State Motor Vehicle License Fees              | 12000000  | General   | 2010        | 
| Tobacco Settlement                            | 12166000  | General   | 2010        | 
| Grants Receipts                               | 16000000  | General   | 2010        | 
| Interest                                      | 22080000  | General   | 2010        | 
| Franchise Income                              | 49479000  | General   | 2010        | 
| Special Parking Revenue Transfer              | 61371000  | General   | 2010        | 
| Parking Users' Tax                            | 82300000  | General   | 2010        | 
| Documentary Transfer Tax                      | 100000000 | General   | 2010        | 
```