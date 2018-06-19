# Open Data - BZ - FY2005 - Building, Plumbing, And Electrical Permits Applied For-- Locator

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/open-data-bz-fy2005-building-plumbing-and-electrical-permits-applied-for-locator-8dd37) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/iiq4-y58u) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/iiq4-y58u/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/iiq4-y58u/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | iiq4-y58u |
| Name | Open Data - BZ - FY2005 - Building, Plumbing, And Electrical Permits Applied For-- Locator |
| Attribution | Cook County Bureau of Economic Development |
| Category | Property & Taxation |
| Created | 2011-10-14T21:33:00Z |
| Publication Date | 2014-10-27T16:41:48Z |

## Description

Updated 10/14/2011, use for mapping

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
series e:iiq4-y58u d:2005-01-01T00:00:00.000Z t:township_name=Barrington m:building=18 m:electrical=2 m:plumbing=7 m:totals=27

series e:iiq4-y58u d:2005-01-01T00:00:00.000Z t:township_name=Berwyn m:building=0 m:electrical=0 m:plumbing=0 m:totals=0

series e:iiq4-y58u d:2005-01-01T00:00:00.000Z t:township_name=Bloom m:building=20 m:electrical=6 m:plumbing=6 m:totals=32
```

## Meta Commands

```ls
metric m:building p:integer l:Building t:dataTypeName=number

metric m:electrical p:integer l:Electrical t:dataTypeName=number

metric m:plumbing p:integer l:Plumbing t:dataTypeName=number

metric m:totals p:integer l:Totals t:dataTypeName=number

entity e:iiq4-y58u l:"Open Data - BZ - FY2005 - Building, Plumbing, And Electrical Permits Applied For-- Locator" t:attribution="Cook County Bureau of Economic Development" t:url=https://datacatalog.cookcountyil.gov/api/views/iiq4-y58u

property e:iiq4-y58u t:meta.view v:id=iiq4-y58u v:category="Property & Taxation" v:averageRating=0 v:name="Open Data - BZ - FY2005 - Building, Plumbing, And Electrical Permits Applied For-- Locator" v:attribution="Cook County Bureau of Economic Development"

property e:iiq4-y58u t:meta.view.license v:name="Public Domain"

property e:iiq4-y58u t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:iiq4-y58u t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
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