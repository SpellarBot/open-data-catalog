# L.A. Zoo Budget Appropriation

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/l-a-zoo-budget-appropriation-2de09) |
| Metadata | [Link](https://data.lacity.org/api/views/jpdu-8y8k) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/jpdu-8y8k/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/jpdu-8y8k/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | jpdu-8y8k |
| Name | L.A. Zoo Budget Appropriation |
| Tags | zoo, attendance, recreation, attraction, park, animals, visitor, school, camp, membership, ticket, budget, money, appropriation |
| Created | 2014-05-30T17:01:37Z |
| Publication Date | 2014-05-30T21:46:43Z |

## Description

L.A. Zoo budget appropriation for the last 5 years.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| Yes      | time           | fiscal_year          | Fiscal Year          | text      | text        |
| Yes      | numeric metric | budget_appropriation | Budget Appropriation | money     | money       |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy-MM
```

## Data Commands

```ls
series e:jpdu-8y8k d:2013-01-01T00:00:00.000Z m:budget_appropriation=17561531

series e:jpdu-8y8k d:2011-12-01T00:00:00.000Z m:budget_appropriation=17986055

series e:jpdu-8y8k d:2010-11-01T00:00:00.000Z m:budget_appropriation=17483062
```

## Meta Commands

```ls
metric m:budget_appropriation p:integer l:"Budget Appropriation" t:dataTypeName=money

entity e:jpdu-8y8k l:"L.A. Zoo Budget Appropriation" t:url=https://data.lacity.org/api/views/jpdu-8y8k

property e:jpdu-8y8k t:meta.view v:id=jpdu-8y8k v:averageRating=0 v:name="L.A. Zoo Budget Appropriation"

property e:jpdu-8y8k t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:jpdu-8y8k t:meta.view.owner v:id=uypn-9feh v:profileImageUrlMedium=/api/users/uypn-9feh/profile_images/THUMB v:profileImageUrlLarge=/api/users/uypn-9feh/profile_images/LARGE v:screenName="LA Zoo OpenData" v:profileImageUrlSmall=/api/users/uypn-9feh/profile_images/TINY v:displayName="LA Zoo OpenData"

property e:jpdu-8y8k t:meta.view.tableauthor v:id=uypn-9feh v:profileImageUrlMedium=/api/users/uypn-9feh/profile_images/THUMB v:profileImageUrlLarge=/api/users/uypn-9feh/profile_images/LARGE v:screenName="LA Zoo OpenData" v:profileImageUrlSmall=/api/users/uypn-9feh/profile_images/TINY v:roleName=editor v:displayName="LA Zoo OpenData"
```

## Top Records

```ls
| fiscal_year | budget_appropriation | 
| =========== | ==================== | 
| 2012-13     | 17561531             | 
| 2011-12     | 17986055             | 
| 2010-11     | 17483062             | 
| 2009-10     | 18261512             | 
| 2008-09     | 19329046             | 
```