# Avg Monthly Service Pension

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/avg-monthly-service-pension-e0deb) |
| Metadata | [Link](https://data.lacity.org/api/views/skve-7mzv) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/skve-7mzv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/skve-7mzv/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | skve-7mzv |
| Name | Avg Monthly Service Pension |
| Category | A Well Run City |
| Tags | service pension |
| Created | 2014-05-23T22:36:10Z |
| Publication Date | 2014-05-23T22:37:00Z |

## Description

Avg Monthly Service Pension

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type | Render Type |
| ======== | ============== | =========================== | =========================== | ========= | =========== |
| No       | time           | :updated_at                 | updated_at                  | meta_data | meta_data   |
| Yes      | series tag     | month                       | Month                       | text      | text        |
| Yes      | numeric metric | avg_monthly_service_pension | Avg Monthly Service Pension | money     | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:skve-7mzv d:2014-05-23T15:36:12.000Z t:month=4/30/2014 m:avg_monthly_service_pension=5708.4
```

## Meta Commands

```ls
metric m:avg_monthly_service_pension p:double l:"Avg Monthly Service Pension" t:dataTypeName=money

entity e:skve-7mzv l:"Avg Monthly Service Pension" t:url=https://data.lacity.org/api/views/skve-7mzv

property e:skve-7mzv t:meta.view v:id=skve-7mzv v:category="A Well Run City" v:averageRating=0 v:name="Avg Monthly Service Pension"

property e:skve-7mzv t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:skve-7mzv t:meta.view.owner v:id=sgjw-6a7f v:profileImageUrlMedium=/api/users/sgjw-6a7f/profile_images/THUMB v:profileImageUrlLarge=/api/users/sgjw-6a7f/profile_images/LARGE v:screenName="Fire & Police Pensions OpenData" v:profileImageUrlSmall=/api/users/sgjw-6a7f/profile_images/TINY v:displayName="Fire & Police Pensions OpenData"

property e:skve-7mzv t:meta.view.tableauthor v:id=sgjw-6a7f v:profileImageUrlMedium=/api/users/sgjw-6a7f/profile_images/THUMB v:profileImageUrlLarge=/api/users/sgjw-6a7f/profile_images/LARGE v:screenName="Fire & Police Pensions OpenData" v:profileImageUrlSmall=/api/users/sgjw-6a7f/profile_images/TINY v:roleName=publisher v:displayName="Fire & Police Pensions OpenData"
```

## Top Records

```ls
| :updated_at | month     | avg_monthly_service_pension | 
| =========== | ========= | =========================== | 
| 1400859372  | 4/30/2014 | $5,708.40                   | 
```