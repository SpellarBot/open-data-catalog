# LAFPP Portfolio Summary

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lafpp-portfolio-summary-194ca) |
| Metadata | [Link](https://data.lacity.org/api/views/tnz4-ynvq) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/tnz4-ynvq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/tnz4-ynvq/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | tnz4-ynvq |
| Name | LAFPP Portfolio Summary |
| Category | A Well Run City |
| Tags | portfolio |
| Created | 2014-05-23T22:55:51Z |
| Publication Date | 2014-05-23T22:56:36Z |

## Description

LAFPP Portfolio Summary

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| No       | time           | :updated_at  | updated_at   | meta_data | meta_data   |
| Yes      | series tag     | month        | Month        | text      | text        |
| Yes      | series tag     | account      | Account      | text      | text        |
| Yes      | numeric metric | market_value | Market Value | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:tnz4-ynvq d:2014-05-23T15:55:54.000Z t:month=4/30/2014 t:account="Domestic Equity Large Cap" m:market_value=5161202427.71

series e:tnz4-ynvq d:2014-05-23T15:55:54.000Z t:month=4/30/2014 t:account="Domestic Equity Small Cap" m:market_value=1225574272.84

series e:tnz4-ynvq d:2014-05-23T15:55:54.000Z t:month=4/30/2014 t:account="International Equity Developed Markets" m:market_value=3054433163.45
```

## Meta Commands

```ls
metric m:market_value p:double l:"Market Value" t:dataTypeName=money

entity e:tnz4-ynvq l:"LAFPP Portfolio Summary" t:url=https://data.lacity.org/api/views/tnz4-ynvq

property e:tnz4-ynvq t:meta.view v:id=tnz4-ynvq v:category="A Well Run City" v:averageRating=0 v:name="LAFPP Portfolio Summary"

property e:tnz4-ynvq t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:tnz4-ynvq t:meta.view.owner v:id=sgjw-6a7f v:profileImageUrlMedium=/api/users/sgjw-6a7f/profile_images/THUMB v:profileImageUrlLarge=/api/users/sgjw-6a7f/profile_images/LARGE v:screenName="Fire & Police Pensions OpenData" v:profileImageUrlSmall=/api/users/sgjw-6a7f/profile_images/TINY v:displayName="Fire & Police Pensions OpenData"

property e:tnz4-ynvq t:meta.view.tableauthor v:id=sgjw-6a7f v:profileImageUrlMedium=/api/users/sgjw-6a7f/profile_images/THUMB v:profileImageUrlLarge=/api/users/sgjw-6a7f/profile_images/LARGE v:screenName="Fire & Police Pensions OpenData" v:profileImageUrlSmall=/api/users/sgjw-6a7f/profile_images/TINY v:roleName=publisher v:displayName="Fire & Police Pensions OpenData"
```

## Top Records

```ls
| :updated_at | month     | account                                | market_value  | 
| =========== | ========= | ====================================== | ============= | 
| 1400860554  | 4/30/2014 | Domestic Equity Large Cap              | 5161202427.71 | 
| 1400860554  | 4/30/2014 | Domestic Equity Small Cap              | 1225574272.84 | 
| 1400860554  | 4/30/2014 | International Equity Developed Markets | 3054433163.45 | 
| 1400860554  | 4/30/2014 | International Equity Emerging Markets  | 751947464.66  | 
| 1400860554  | 4/30/2014 | Core Fixed Income                      | 2315220204.51 | 
| 1400860554  | 4/30/2014 | TIPS                                   | 791526891.77  | 
| 1400860554  | 4/30/2014 | High Yield Bonds                       | 443385225.71  | 
| 1400860554  | 4/30/2014 | Real Estate                            | 1746464720.78 | 
| 1400860554  | 4/30/2014 | Commodity                              | 180381066.59  | 
| 1400860554  | 4/30/2014 | Private Equity                         | 1402802441.63 | 
```