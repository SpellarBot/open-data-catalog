# LASAN: Miles of Sewer Cleaned

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lasan-miles-of-sewer-cleaned) |
| Metadata | [Link](https://data.lacity.org/api/views/iyyp-p2fx) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/iyyp-p2fx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/iyyp-p2fx/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | iyyp-p2fx |
| Name | LASAN: Miles of Sewer Cleaned |
| Attribution | LA Sanitation |
| Category | A Livable and Sustainable City |
| Tags | lasan, bureau of sanitation, sanitation, sewers, cleaned sewers |
| Created | 2014-08-12T14:39:58Z |
| Publication Date | 2014-08-12T14:42:27Z |

## Description

Miles of Sewer cleaned is reported monthly by LA Sanitation.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| No       |                | month                  | Month                  | text      | text        |
| No       |                | fiscal_year            | Fiscal Year            | number    | text        |
| Yes      | series tag     | month_number           | Month Number           | text      | number      |
| Yes      | numeric metric | miles_of_sewer_cleaned | Miles of Sewer Cleaned | number    | number      |
```

## Time Field

```ls
Value = fiscal_year-month
Format & Zone = yyyy-MMM
```

## Series Fields

```ls
Excluded Fields = fiscal_year,month
```

## Data Commands

```ls
series e:iyyp-p2fx d:2014-07-01T00:00:00.000Z t:month_number=1 m:miles_of_sewer_cleaned=548

series e:iyyp-p2fx d:2014-08-01T00:00:00.000Z t:month_number=2 m:miles_of_sewer_cleaned=560

series e:iyyp-p2fx d:2014-09-01T00:00:00.000Z t:month_number=3 m:miles_of_sewer_cleaned=468
```

## Meta Commands

```ls
metric m:miles_of_sewer_cleaned p:integer l:"Miles of Sewer Cleaned" t:dataTypeName=number

entity e:iyyp-p2fx l:"LASAN: Miles of Sewer Cleaned" t:attribution="LA Sanitation" t:url=https://data.lacity.org/api/views/iyyp-p2fx

property e:iyyp-p2fx t:meta.view v:id=iyyp-p2fx v:category="A Livable and Sustainable City" v:averageRating=0 v:name="LASAN: Miles of Sewer Cleaned" v:attribution="LA Sanitation"

property e:iyyp-p2fx t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:iyyp-p2fx t:meta.view.owner v:id=jwvk-b9mh v:profileImageUrlMedium=/api/users/jwvk-b9mh/profile_images/THUMB v:profileImageUrlLarge=/api/users/jwvk-b9mh/profile_images/LARGE v:screenName="Public Works: Sanitation OpenData" v:profileImageUrlSmall=/api/users/jwvk-b9mh/profile_images/TINY v:displayName="Public Works: Sanitation OpenData"

property e:iyyp-p2fx t:meta.view.tableauthor v:id=jwvk-b9mh v:profileImageUrlMedium=/api/users/jwvk-b9mh/profile_images/THUMB v:profileImageUrlLarge=/api/users/jwvk-b9mh/profile_images/LARGE v:screenName="Public Works: Sanitation OpenData" v:profileImageUrlSmall=/api/users/jwvk-b9mh/profile_images/TINY v:roleName=publisher v:displayName="Public Works: Sanitation OpenData"
```

## Top Records

```ls
| month | fiscal_year | month_number | miles_of_sewer_cleaned | 
| ===== | =========== | ============ | ====================== | 
| JUL   | 2014        | 1            | 548                    | 
| AUG   | 2014        | 2            | 560                    | 
| SEP   | 2014        | 3            | 468                    | 
| OCT   | 2014        | 4            | 498                    | 
| NOV   | 2014        | 5            | 470                    | 
| DEC   | 2014        | 6            | 447                    | 
| JAN   | 2014        | 7            | 561                    | 
| FEB   | 2014        | 8            | 565                    | 
| MAR   | 2014        | 9            | 620                    | 
| APR   | 2014        | 10           | 634                    | 
```