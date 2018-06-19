# Department of Revenue - Unincorporated Cook County Municipalities by Township and ZIP

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/department-of-revenue-unincorporated-cook-county-municipalities-by-township-and-zip-b55e5) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/nkuy-refp) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/nkuy-refp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/nkuy-refp/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | nkuy-refp |
| Name | Department of Revenue - Unincorporated Cook County Municipalities by Township and ZIP |
| Attribution | Cook County Department of Revenue |
| Category | Finance & Administration |
| Tags | department of revenue, unincoporated cook county municipalities, township, zip code |
| Created | 2011-09-08T19:21:10Z |
| Publication Date | 2011-09-08T19:21:10Z |

## Description

Data last updated September 8th, 2011

## Columns

```ls
| Included | Schema Type | Field Name   | Name         | Data Type | Render Type |
| ======== | =========== | ============ | ============ | ========= | =========== |
| No       | time        | :updated_at  | updated_at   | meta_data | meta_data   |
| Yes      | series tag  | township     | Township     | text      | text        |
| Yes      | series tag  | municipality | Municipality | text      | text        |
| Yes      | series tag  | zip_code     | ZIP Code     | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:nkuy-refp d:2011-09-08T12:21:11.000Z t:township="TOWN OF WORTH" t:zip_code=60406 m:row_number.nkuy-refp=1

series e:nkuy-refp d:2011-09-08T12:21:12.000Z t:township="TOWN OF RICH" t:zip_code=60443 m:row_number.nkuy-refp=2

series e:nkuy-refp d:2011-09-08T12:21:12.000Z t:township="TOWN OF BREMEN" t:zip_code=60445 m:row_number.nkuy-refp=3
```

## Meta Commands

```ls
metric m:row_number.nkuy-refp p:long l:"Row Number"

entity e:nkuy-refp l:"Department of Revenue - Unincorporated Cook County Municipalities by Township and ZIP" t:attribution="Cook County Department of Revenue" t:url=https://datacatalog.cookcountyil.gov/api/views/nkuy-refp

property e:nkuy-refp t:meta.view v:id=nkuy-refp v:category="Finance & Administration" v:attributionLink=http://cookcountyil.gov/revenue v:averageRating=0 v:name="Department of Revenue - Unincorporated Cook County Municipalities by Township and ZIP" v:attribution="Cook County Department of Revenue"

property e:nkuy-refp t:meta.view.license v:name="Public Domain"

property e:nkuy-refp t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:nkuy-refp t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| :updated_at | township          | municipality    | zip_code | 
| =========== | ================= | =============== | ======== | 
| 1315484471  | TOWN OF WORTH     |                 | 60406    | 
| 1315484472  | TOWN OF RICH      |                 | 60443    | 
| 1315484472  | TOWN OF BREMEN    |                 | 60445    | 
| 1315484472  | TOWN OF BREMEN    |                 | 60463    | 
| 1315484472  | TOWN OF BLOOM     |                 | 60475    | 
| 1315484472  | TOWN OF BLOOM     |                 | 60475    | 
| 1315484472  | TOWN OF BLOOM     |                 | 60475    | 
| 1315484472  | TOWN OF BLOOM     | Chicago Heights | 60475    | 
| 1315484472  | TOWN OF BLOOM     | Lynwood         | 60475    | 
| 1315484472  | TOWNSHIP OF PALOS | Willow Springs  | 60482    | 
```