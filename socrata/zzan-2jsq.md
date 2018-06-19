# Animal Control - Species By City - Fiscal Year 2011 Incomplete

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/animal-control-species-by-city-fiscal-year-2011-incomplete-3d5a7) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/zzan-2jsq) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/zzan-2jsq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/zzan-2jsq/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | zzan-2jsq |
| Name | Animal Control - Species By City - Fiscal Year 2011 Incomplete |
| Attribution | Cook County Department of Animal Control |
| Category | Finance & Administration |
| Created | 2011-09-23T21:35:58Z |
| Publication Date | 2014-10-09T22:34:16Z |

## Description

Species by city for part of Fiscal Year 2011. Data last updated September 2011.

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
series e:zzan-2jsq d:2011-01-01T00:00:00.000Z m:rabbit=0 m:cat=29 m:cow=0 m:guard_dog=0 m:unknown=0 m:totals=77 m:dog=48 m:ferret=0

series e:zzan-2jsq d:2011-01-01T00:00:00.000Z m:rabbit=0 m:cat=2 m:cow=0 m:guard_dog=0 m:unknown=0 m:totals=18 m:dog=16 m:ferret=0

series e:zzan-2jsq d:2011-01-01T00:00:00.000Z m:rabbit=0 m:cat=123 m:cow=0 m:guard_dog=11 m:unknown=45 m:totals=812 m:dog=633 m:ferret=0
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

entity e:zzan-2jsq l:"Animal Control - Species By City - Fiscal Year 2011 Incomplete" t:attribution="Cook County Department of Animal Control" t:url=https://datacatalog.cookcountyil.gov/api/views/zzan-2jsq

property e:zzan-2jsq t:meta.view v:id=zzan-2jsq v:category="Finance & Administration" v:attributionLink=http://www.cookcountygov.com/portal/server.pt/community/animal___rabies_control/247 v:averageRating=0 v:name="Animal Control - Species By City - Fiscal Year 2011 Incomplete" v:attribution="Cook County Department of Animal Control"

property e:zzan-2jsq t:meta.view.license v:name="Public Domain"

property e:zzan-2jsq t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:zzan-2jsq t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| year | cat | cow | dog  | ferret | guard_dog | rabbit | unknown | totals | 
| ==== | === | === | ==== | ====== | ========= | ====== | ======= | ====== | 
| 2011 | 29  | 0   | 48   | 0      | 0         | 0      | 0       | 77     | 
| 2011 | 2   | 0   | 16   | 0      | 0         | 0      | 0       | 18     | 
| 2011 | 123 | 0   | 633  | 0      | 11        | 0      | 45      | 812    | 
| 2011 | 0   | 0   | 1    | 0      | 0         | 0      | 0       | 1      | 
| 2011 | 2   | 0   | 10   | 0      | 0         | 0      | 0       | 12     | 
| 2011 | 0   | 0   | 1    | 0      | 0         | 0      | 0       | 1      | 
| 2011 | 1   | 0   | 0    | 0      | 0         | 0      | 0       | 1      | 
| 2011 | 936 | 0   | 2738 | 1      | 0         | 0      | 25      | 3700   | 
| 2011 | 0   | 0   | 1    | 0      | 0         | 0      | 0       | 1      | 
| 2011 | 10  | 0   | 34   | 0      | 0         | 0      | 0       | 44     | 
```