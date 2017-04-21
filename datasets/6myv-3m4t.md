# Building and Zoning - Building, Plumbing, And Electrical Permits Applied For - Fiscal Year 2005 through part of Fiscal Year 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/building-and-zoning-building-plumbing-and-electrical-permits-applied-for-fiscal-year-200-2-e7586) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/6myv-3m4t) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/6myv-3m4t/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/6myv-3m4t/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | 6myv-3m4t |
| Name | Building and Zoning - Building, Plumbing, And Electrical Permits Applied For - Fiscal Year 2005 through part of Fiscal Year 2011 |
| Attribution | Cook County Department of Building and Zoning |
| Category | Economic Development |
| Created | 2011-09-27T14:53:15Z |
| Publication Date | 2014-10-09T21:37:20Z |

## Description

Building, Plumbing, And Electrical Permits Applied For by Township covering Fiscal Year 2005 through part of Fiscal Year 2011. Data last updated September 27, 2011

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| Yes      | time           | fiscal_year   | Fiscal Year   | number    | text        |
| Yes      | series tag     | township_name | Township Name | text      | text        |
| Yes      | numeric metric | building      | Building      | number    | number      |
| Yes      | numeric metric | electrical    | Electrical    | number    | number      |
| Yes      | numeric metric | plumbing      | Plumbing      | number    | number      |
| Yes      | numeric metric | totals        | Totals        | number    | number      |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:6myv-3m4t d:2005-01-01T00:00:00.000Z t:township_name=Barrington m:building=18 m:electrical=2 m:plumbing=7 m:totals=27

series e:6myv-3m4t d:2005-01-01T00:00:00.000Z t:township_name=Berwyn m:building=0 m:electrical=0 m:plumbing=0 m:totals=0

series e:6myv-3m4t d:2005-01-01T00:00:00.000Z t:township_name=Bloom m:building=20 m:electrical=6 m:plumbing=6 m:totals=32
```

## Meta Commands

```ls
metric m:building p:integer l:Building t:dataTypeName=number

metric m:electrical p:integer l:Electrical t:dataTypeName=number

metric m:plumbing p:integer l:Plumbing t:dataTypeName=number

metric m:totals p:integer l:Totals t:dataTypeName=number

entity e:6myv-3m4t l:"Building and Zoning - Building, Plumbing, And Electrical Permits Applied For - Fiscal Year 2005 through part of Fiscal Year 2011" t:attribution="Cook County Department of Building and Zoning" t:url=https://datacatalog.cookcountyil.gov/api/views/6myv-3m4t

property e:6myv-3m4t t:meta.view v:id=6myv-3m4t v:category="Economic Development" v:attributionLink=http://www.cookcountyil.gov/BuildingZoning v:averageRating=0 v:name="Building and Zoning - Building, Plumbing, And Electrical Permits Applied For - Fiscal Year 2005 through part of Fiscal Year 2011" v:attribution="Cook County Department of Building and Zoning"

property e:6myv-3m4t t:meta.view.license v:name="Public Domain"

property e:6myv-3m4t t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:6myv-3m4t t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| fiscal_year | township_name | building | electrical | plumbing | totals | 
| =========== | ============= | ======== | ========== | ======== | ====== | 
| 2005        | Barrington    | 18       | 2          | 7        | 27     | 
| 2005        | Berwyn        | 0        | 0          | 0        | 0      | 
| 2005        | Bloom         | 20       | 6          | 6        | 32     | 
| 2005        | Bremen        | 24       | 2          | 1        | 27     | 
| 2005        | Calumet       | 0        | 0          | 0        | 0      | 
| 2005        | Cicero        | 0        | 0          | 0        | 0      | 
| 2005        | Elk Grove     | 29       | 55         | 16       | 100    | 
| 2005        | Evanston      | 0        | 0          | 0        | 0      | 
| 2005        | Hanover       | 21       | 10         | 5        | 36     | 
| 2005        | Lemont        | 81       | 26         | 15       | 122    | 
```