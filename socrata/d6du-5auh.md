# Department of Revenue - Revenue Collected by Tax Type - December 2011 to June 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/department-of-revenue-revenue-collected-by-tax-type-december-2011-to-june-2012-c34f5) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/d6du-5auh) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/d6du-5auh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/d6du-5auh/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | d6du-5auh |
| Name | Department of Revenue - Revenue Collected by Tax Type - December 2011 to June 2012 |
| Attribution | Cook County Department of Revenue |
| Category | Finance & Administration |
| Created | 2012-08-13T19:53:08Z |
| Publication Date | 2014-10-09T21:44:54Z |

## Description

Total revenue collected by tax type per month. Data covers December 2011 through June 2012.

## Columns

```ls
| Included | Schema Type | Field Name                | Name                      | Data Type | Render Type |
| ======== | =========== | ========================= | ========================= | ========= | =========== |
| Yes      | series tag  | cook_county_posting_month | Cook County Posting Month | text      | text        |
| No       |             | _1                        | 12/11                     | text      | text        |
| No       |             | _2                        | 1/12                      | text      | text        |
| No       |             | _3                        | 2/12                      | text      | text        |
| No       |             | _4                        | 3/12                      | text      | text        |
| No       |             | _5                        | 4/12                      | text      | text        |
| No       |             | _6                        | 5/12                      | text      | text        |
| No       |             | _7                        | 6/12                      | text      | text        |
| No       |             | _8                        | 7/12                      | text      | text        |
| No       |             | _9                        | 8/12                      | text      | text        |
| Yes      | series tag  | _10                       | 9/12                      | text      | text        |
| Yes      | series tag  | _11                       | 10/12                     | text      | text        |
| Yes      | series tag  | _12                       | 11/12                     | text      | text        |
| Yes      | series tag  | ytd_total                 | YTD Total                 | text      | text        |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = _1,_2,_3,_4,_5,_6,_7,_8,_9
```

## Data Commands

```ls
series e:d6du-5auh d:2011-01-01T00:00:00.000Z t:_11=$- t:_10=$- t:cook_county_posting_month=Use t:ytd_total=$25,717,000 t:_12=$- m:row_number.d6du-5auh=1

series e:d6du-5auh d:2011-01-01T00:00:00.000Z t:_11=$- t:_10=$- t:cook_county_posting_month="Alcoholic Beverage" t:ytd_total=$15,251,000 t:_12=$- m:row_number.d6du-5auh=2

series e:d6du-5auh d:2011-01-01T00:00:00.000Z t:_11=$- t:_10=$- t:cook_county_posting_month=Cigarette t:ytd_total=$59,493,000 t:_12=$- m:row_number.d6du-5auh=3
```

## Meta Commands

```ls
metric m:row_number.d6du-5auh p:long l:"Row Number"

entity e:d6du-5auh l:"Department of Revenue - Revenue Collected by Tax Type - December 2011 to June 2012" t:attribution="Cook County Department of Revenue" t:url=https://datacatalog.cookcountyil.gov/api/views/d6du-5auh

property e:d6du-5auh t:meta.view v:id=d6du-5auh v:category="Finance & Administration" v:attributionLink=http://cookcountyil.gov/revenue v:averageRating=0 v:name="Department of Revenue - Revenue Collected by Tax Type - December 2011 to June 2012" v:attribution="Cook County Department of Revenue"

property e:d6du-5auh t:meta.view.license v:name="Public Domain"

property e:d6du-5auh t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:d6du-5auh t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| cook_county_posting_month       | _1         | _2         | _3         | _4          | _5         | _6          | _7 | _8 | _9 | _10 | _11 | _12 | ytd_total   | 
| =============================== | ========== | ========== | ========== | =========== | ========== | =========== | == | == | == | === | === | === | =========== | 
| Use                             | $3,274,000 | $3,653,392 | $3,686,608 | $4,673,000  | $6,067,000 | $4,363,000  | $- | $- | $- | $-  | $-  | $-  | $25,717,000 | 
| Alcoholic Beverage              | $2,341,000 | $3,072,000 | $1,779,000 | $2,582,000  | $2,870,000 | $2,607,000  | $- | $- | $- | $-  | $-  | $-  | $15,251,000 | 
| Cigarette                       | $9,932,000 | $7,753,000 | $9,448,000 | $11,995,000 | $8,220,000 | $12,145,000 | $- | $- | $- | $-  | $-  | $-  | $59,493,000 | 
| Gasoline / Diesel Fuel          | $7,217,000 | $7,368,000 | $5,329,000 | $11,672,000 | $7,386,000 | $6,665,000  | $- | $- | $- | $-  | $-  | $-  | $45,637,000 | 
| Retail Sale of Motor Vehicles   | $173,000   | $227,000   | $141,000   | $226,000    | $249,000   | $218,000    | $- | $- | $- | $-  | $-  | $-  | $1,234,000  | 
| Wheel                           | $28,000    | $42,000    | $37,000    | $37,000     | $24,000    | $47,000     | $- | $- | $- | $-  | $-  | $-  | $215,000    | 
| Amusement                       | $1,427,000 | $1,495,000 | $1,061,000 | $9,111,000  | $7,018,000 | $3,003,000  | $- | $- | $- | $-  | $-  | $-  | $23,115,000 | 
| Parking Lot & Garage Operations | $2,931,000 | $2,903,000 | $2,855,000 | $3,394,000  | $3,587,000 | $3,214,000  | $- | $- | $- | $-  | $-  | $-  | $18,884,000 | 
| Other Tobacco Products          | $-         | $-         | $-         | $-          | $3,689,000 | $831,000    | $- | $- | $- | $-  | $-  | $-  | $4,520,000  | 
| Non Retailer Title Transfer Use | $-         | $-         | $-         | $-          | $-         | $-          | $- | $- | $- | $-  | $-  | $-  | $-          | 
```