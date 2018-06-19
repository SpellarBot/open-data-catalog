# State Taxes and Fees Collected: Beginning Fiscal Year Ending March 31, 1995

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-taxes-and-fees-collected-beginning-fiscal-year-ending-march-31-2003) |
| Metadata | [Link](https://data.ny.gov/api/views/cpjr-ezcj) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/cpjr-ezcj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/cpjr-ezcj/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | cpjr-ezcj |
| Name | State Taxes and Fees Collected: Beginning Fiscal Year Ending March 31, 1995 |
| Attribution | New York State Department of Taxation and Finance |
| Category | Government & Finance |
| Tags | taxes, fees, tax collections, tax revenues |
| Created | 2013-02-14T22:00:19Z |
| Publication Date | 2016-09-26T17:53:12Z |

## Description

The Department of Taxation and Finance annually produces a compilation of the taxes and fees collected by the department. The taxes and fees information provided in this data set are primarily taxes imposed by the Tax Law, but also includes fees that are imposed by other state laws but are administered and collected by the Department. Collections are net of refunds and other processing and accounting adjustments.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type | Render Type |
| ======== | ============== | ===================== | ===================== | ========= | =========== |
| Yes      | time           | fiscal_year           | Fiscal Year Ended     | number    | number      |
| Yes      | series tag     | tax_category          | Tax Category          | text      | text        |
| Yes      | series tag     | tax_or_fee            | Tax or Fee            | text      | text        |
| Yes      | numeric metric | amount_collected      | Amount Collected      | money     | money       |
| Yes      | numeric metric | tax_or_fee_sort_order | Tax or Fee Sort Order | number    | number      |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:cpjr-ezcj d:2015-01-01T00:00:00.000Z t:tax_or_fee="Personal Income Tax" t:tax_category="Personal Income" m:tax_or_fee_sort_order=1 m:amount_collected=43709833323

series e:cpjr-ezcj d:2015-01-01T00:00:00.000Z t:tax_or_fee="Business Corporations Article 9-A" t:tax_category="Corporation and Business" m:tax_or_fee_sort_order=2 m:amount_collected=2969705402

series e:cpjr-ezcj d:2015-01-01T00:00:00.000Z t:tax_or_fee="Foreign Corporation Licenses, Article 9, Section 181" t:tax_category="Corporation and Business" m:tax_or_fee_sort_order=3 m:amount_collected=26511684
```

## Meta Commands

```ls
metric m:amount_collected p:long l:"Amount Collected" d:"Net amount of collections for each Tax or Fee identified, in US dollars, during the fiscal year identified. A $0 value may indicate the tax was not in effect during that period. Refer to the Effective Dates attachment." t:dataTypeName=money

metric m:tax_or_fee_sort_order p:integer l:"Tax or Fee Sort Order" d:"Sort order on the Tax or Fee" t:dataTypeName=number

entity e:cpjr-ezcj l:"State Taxes and Fees Collected: Beginning Fiscal Year Ending March 31, 1995" t:attribution="New York State Department of Taxation and Finance" t:url=https://data.ny.gov/api/views/cpjr-ezcj

property e:cpjr-ezcj t:meta.view v:id=cpjr-ezcj v:category="Government & Finance" v:attributionLink=http://www.tax.ny.gov/research/stats/statistics/stat_fy_collections.htm v:averageRating=0 v:name="State Taxes and Fees Collected: Beginning Fiscal Year Ending March 31, 1995" v:attribution="New York State Department of Taxation and Finance"

property e:cpjr-ezcj t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:cpjr-ezcj t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:cpjr-ezcj t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| fiscal_year | tax_category             | tax_or_fee                                                       | amount_collected | tax_or_fee_sort_order | 
| =========== | ======================== | ================================================================ | ================ | ===================== | 
| 2015        | Personal Income          | Personal Income Tax                                              | 43709833323      | 1                     | 
| 2015        | Corporation and Business | Business Corporations Article 9-A                                | 2969705402       | 2                     | 
| 2015        | Corporation and Business | Foreign Corporation Licenses, Article 9, Section 181             | 26511684         | 3                     | 
| 2015        | Corporation and Business | Transportation, Transmission, Article 9, Section 183             | 11037395         | 4                     | 
| 2015        | Corporation and Business | Transportation, Transmission, Article 9, Section 184             | 36521507         | 5                     | 
| 2015        | Corporation and Business | Agricultural Co-operatives, Article 9, Section 185               | -308811          | 6                     | 
| 2015        | Corporation and Business | Light, Water, Power, Article 9, Section 186                      | 6346854          | 7                     | 
| 2015        | Corporation and Business | Utilities, Article 9, Section 186-a                              | 161632428        | 8                     | 
| 2015        | Corporation and Business | Telecommunications, Article 9, Section 186-e                     | 381985062        | 9                     | 
| 2015        | Corporation and Business | Public Safety Communications Surcharge, Article 9, Section 186-f | 185262082        | 10                    | 
```