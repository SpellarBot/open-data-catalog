# Animal Control - Species By City - Fiscal Year 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/animal-control-species-by-city-fiscal-year-2010-d3578) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/w3ph-28pq) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/w3ph-28pq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/w3ph-28pq/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | w3ph-28pq |
| Name | Animal Control - Species By City - Fiscal Year 2010 |
| Attribution | Cook County Department of Animal Control |
| Category | Finance & Administration |
| Created | 2011-09-26T20:25:16Z |
| Publication Date | 2014-10-09T21:55:40Z |

## Description

Species by city for fiscal year 2010

## Columns

```ls
| Included | Schema Type    | Field Name | Name      | Data Type | Render Type |
| ======== | ============== | ========== | ========= | ========= | =========== |
| Yes      | time           | year       | Year      | number    | text        |
| Yes      | numeric metric | cat        | CAT       | number    | number      |
| Yes      | numeric metric | cow        | COW       | number    | number      |
| Yes      | numeric metric | dog        | DOG       | number    | number      |
| Yes      | numeric metric | ferret     | FERRET    | number    | number      |
| Yes      | numeric metric | guard_dog  | GUARD DOG | number    | number      |
| Yes      | numeric metric | rabbit     | RABBIT    | number    | number      |
| Yes      | numeric metric | unknown    | UNKNOWN   | number    | number      |
| Yes      | numeric metric | totals     | Totals    | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:w3ph-28pq d:2010-01-01T00:00:00.000Z m:rabbit=0 m:cat=30 m:cow=0 m:guard_dog=0 m:unknown=0 m:totals=133 m:dog=103 m:ferret=0

series e:w3ph-28pq d:2010-01-01T00:00:00.000Z m:rabbit=0 m:cat=6 m:cow=0 m:guard_dog=0 m:unknown=1 m:totals=53 m:dog=46 m:ferret=0

series e:w3ph-28pq d:2010-01-01T00:00:00.000Z m:rabbit=0 m:cat=328 m:cow=0 m:guard_dog=0 m:unknown=52 m:totals=1758 m:dog=1378 m:ferret=0
```

## Meta Commands

```ls
metric m:cat p:integer l:CAT t:dataTypeName=number

metric m:cow p:integer l:COW t:dataTypeName=number

metric m:dog p:integer l:DOG t:dataTypeName=number

metric m:ferret p:integer l:FERRET t:dataTypeName=number

metric m:guard_dog p:integer l:"GUARD DOG" t:dataTypeName=number

metric m:rabbit p:integer l:RABBIT t:dataTypeName=number

metric m:unknown p:integer l:UNKNOWN t:dataTypeName=number

metric m:totals p:integer l:Totals t:dataTypeName=number

entity e:w3ph-28pq l:"Animal Control - Species By City - Fiscal Year 2010" t:attribution="Cook County Department of Animal Control" t:url=https://datacatalog.cookcountyil.gov/api/views/w3ph-28pq

property e:w3ph-28pq t:meta.view v:id=w3ph-28pq v:category="Finance & Administration" v:averageRating=0 v:name="Animal Control - Species By City - Fiscal Year 2010" v:attribution="Cook County Department of Animal Control"

property e:w3ph-28pq t:meta.view.license v:name="Public Domain"

property e:w3ph-28pq t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:w3ph-28pq t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| year | cat  | cow | dog  | ferret | guard_dog | rabbit | unknown | totals | 
| ==== | ==== | === | ==== | ====== | ========= | ====== | ======= | ====== | 
| 2010 | 30   | 0   | 103  | 0      | 0         | 0      | 0       | 133    | 
| 2010 | 6    | 0   | 46   | 0      | 0         | 0      | 1       | 53     | 
| 2010 | 328  | 0   | 1378 | 0      | 0         | 0      | 52      | 1758   | 
| 2010 | 0    | 0   | 1    | 0      | 0         | 0      | 0       | 1      | 
| 2010 | 5    | 0   | 17   | 0      | 0         | 0      | 0       | 22     | 
| 2010 | 0    | 0   | 2    | 0      | 0         | 0      | 0       | 2      | 
| 2010 | 1    | 0   | 0    | 0      | 0         | 0      | 0       | 1      | 
| 2010 | 2283 | 0   | 5994 | 9      | 1         | 0      | 33      | 8320   | 
| 2010 | 0    | 0   | 3    | 0      | 0         | 0      | 0       | 3      | 
| 2010 | 44   | 0   | 94   | 0      | 0         | 0      | 4       | 142    | 
```