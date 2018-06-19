# Animal Control - Species, by Year

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/animal-control-species-by-year-4f3c5) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/nax4-xa7j) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/nax4-xa7j/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/nax4-xa7j/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | nax4-xa7j |
| Name | Animal Control - Species, by Year |
| Attribution | Cook County Department of Animal Control |
| Category | Finance & Administration |
| Created | 2011-09-23T20:39:26Z |
| Publication Date | 2014-10-09T22:25:29Z |

## Description

Data covers 2010 and part of 2011. Data last updated in September 2011

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
series e:nax4-xa7j d:2010-01-01T00:00:00.000Z m:rabbit=1 m:cat=86723 m:cow=1 m:guard_dog=241 m:unknown=8059 m:totals=343973 m:dog=248707 m:ferret=241

series e:nax4-xa7j d:2011-01-01T00:00:00.000Z m:rabbit=0 m:cat=39134 m:cow=0 m:guard_dog=141 m:unknown=4202 m:totals=158460 m:dog=114911 m:ferret=72
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

entity e:nax4-xa7j l:"Animal Control - Species, by Year" t:attribution="Cook County Department of Animal Control" t:url=https://datacatalog.cookcountyil.gov/api/views/nax4-xa7j

property e:nax4-xa7j t:meta.view v:id=nax4-xa7j v:category="Finance & Administration" v:attributionLink=http://www.cookcountygov.com/portal/server.pt/community/animal___rabies_control/247 v:averageRating=0 v:name="Animal Control - Species, by Year" v:attribution="Cook County Department of Animal Control"

property e:nax4-xa7j t:meta.view.license v:name="Public Domain"

property e:nax4-xa7j t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:nax4-xa7j t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| year | cat   | cow | dog    | ferret | guard_dog | rabbit | unknown | totals | 
| ==== | ===== | === | ====== | ====== | ========= | ====== | ======= | ====== | 
| 2010 | 86723 | 1   | 248707 | 241    | 241       | 1      | 8059    | 343973 | 
| 2011 | 39134 | 0   | 114911 | 72     | 141       | 0      | 4202    | 158460 | 
```