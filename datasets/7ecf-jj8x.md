# Member Health Subsidy

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/member-health-subsidy-e9b91) |
| Metadata | [Link](https://data.lacity.org/api/views/7ecf-jj8x) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/7ecf-jj8x/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/7ecf-jj8x/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | 7ecf-jj8x |
| Name | Member Health Subsidy |
| Category | A Well Run City |
| Tags | health subsidy |
| Created | 2014-05-23T22:56:55Z |
| Publication Date | 2014-05-23T22:57:31Z |

## Description

Member Health Subsidy

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type | Render Type |
| ======== | ============== | ========================= | ========================= | ========= | =========== |
| Yes      | time           | fiscal_year_ending        | Fiscal Year Ending        | number    | text        |
| Yes      | numeric metric | max_member_health_subsidy | Max Member Health Subsidy | money     | money       |
| Yes      | numeric metric | avg_member_health_subsidy | Avg Member Health Subsidy | money     | money       |
```

## Time Field

```ls
Value = fiscal_year_ending
Format & Zone = yyyy
```

## Data Commands

```ls
series e:7ecf-jj8x d:2010-01-01T00:00:00.000Z m:avg_member_health_subsidy=656.71 m:max_member_health_subsidy=958.52

series e:7ecf-jj8x d:2011-01-01T00:00:00.000Z m:avg_member_health_subsidy=709.51 m:max_member_health_subsidy=1025.62

series e:7ecf-jj8x d:2012-01-01T00:00:00.000Z m:avg_member_health_subsidy=717.4 m:max_member_health_subsidy=1097.41
```

## Meta Commands

```ls
metric m:max_member_health_subsidy p:double l:"Max Member Health Subsidy" t:dataTypeName=money

metric m:avg_member_health_subsidy p:double l:"Avg Member Health Subsidy" t:dataTypeName=money

entity e:7ecf-jj8x l:"Member Health Subsidy" t:url=https://data.lacity.org/api/views/7ecf-jj8x

property e:7ecf-jj8x t:meta.view v:id=7ecf-jj8x v:category="A Well Run City" v:averageRating=0 v:name="Member Health Subsidy"

property e:7ecf-jj8x t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:7ecf-jj8x t:meta.view.owner v:id=sgjw-6a7f v:profileImageUrlMedium=/api/users/sgjw-6a7f/profile_images/THUMB v:profileImageUrlLarge=/api/users/sgjw-6a7f/profile_images/LARGE v:screenName="Fire & Police Pensions OpenData" v:profileImageUrlSmall=/api/users/sgjw-6a7f/profile_images/TINY v:displayName="Fire & Police Pensions OpenData"

property e:7ecf-jj8x t:meta.view.tableauthor v:id=sgjw-6a7f v:profileImageUrlMedium=/api/users/sgjw-6a7f/profile_images/THUMB v:profileImageUrlLarge=/api/users/sgjw-6a7f/profile_images/LARGE v:screenName="Fire & Police Pensions OpenData" v:profileImageUrlSmall=/api/users/sgjw-6a7f/profile_images/TINY v:roleName=publisher v:displayName="Fire & Police Pensions OpenData"
```

## Top Records

```ls
| fiscal_year_ending | max_member_health_subsidy | avg_member_health_subsidy | 
| ================== | ========================= | ========================= | 
| 2010               | 958.52                    | 656.71                    | 
| 2011               | 1025.62                   | 709.51                    | 
| 2012               | 1097.41                   | 717.40                    | 
| 2013               | 1174.23                   | 763.43                    | 
| 2014               | 1256.43                   | 814.17                    | 
```