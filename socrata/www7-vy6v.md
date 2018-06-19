# Animal Control - Species By Color - Fiscal Year 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/animal-control-species-by-color-fiscal-year-2010-8bc94) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/www7-vy6v) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/www7-vy6v/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/www7-vy6v/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | www7-vy6v |
| Name | Animal Control - Species By Color - Fiscal Year 2010 |
| Attribution | Cook County Department of Animal Control |
| Category | Finance & Administration |
| Created | 2011-09-26T20:19:05Z |
| Publication Date | 2014-10-09T21:48:50Z |

## Description

Species by color for fiscal year 2010,

## Columns

```ls
| Included | Schema Type    | Field Name | Name      | Data Type | Render Type |
| ======== | ============== | ========== | ========= | ========= | =========== |
| Yes      | time           | year       | Year      | number    | text        |
| Yes      | series tag     | color      | Color     | text      | text        |
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
series e:www7-vy6v d:2010-01-01T00:00:00.000Z t:color=APRICOT m:rabbit=0 m:cat=39 m:cow=0 m:guard_dog=0 m:unknown=22 m:totals=1874 m:dog=1813 m:ferret=0

series e:www7-vy6v d:2010-01-01T00:00:00.000Z t:color=AUBURN m:rabbit=0 m:cat=2 m:cow=0 m:guard_dog=0 m:unknown=0 m:totals=50 m:dog=48 m:ferret=0

series e:www7-vy6v d:2010-01-01T00:00:00.000Z t:color=BEIGE m:rabbit=0 m:cat=346 m:cow=0 m:guard_dog=0 m:unknown=23 m:totals=2161 m:dog=1792 m:ferret=0
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

entity e:www7-vy6v l:"Animal Control - Species By Color - Fiscal Year 2010" t:attribution="Cook County Department of Animal Control" t:url=https://datacatalog.cookcountyil.gov/api/views/www7-vy6v

property e:www7-vy6v t:meta.view v:id=www7-vy6v v:category="Finance & Administration" v:averageRating=0 v:name="Animal Control - Species By Color - Fiscal Year 2010" v:attribution="Cook County Department of Animal Control"

property e:www7-vy6v t:meta.view.license v:name="Public Domain"

property e:www7-vy6v t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:www7-vy6v t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| year | color         | cat   | cow | dog   | ferret | guard_dog | rabbit | unknown | totals | 
| ==== | ============= | ===== | === | ===== | ====== | ========= | ====== | ======= | ====== | 
| 2010 | APRICOT       | 39    | 0   | 1813  | 0      | 0         | 0      | 22      | 1874   | 
| 2010 | AUBURN        | 2     | 0   | 48    | 0      | 0         | 0      | 0       | 50     | 
| 2010 | BEIGE         | 346   | 0   | 1792  | 0      | 0         | 0      | 23      | 2161   | 
| 2010 | BELTON        | 0     | 0   | 5     | 0      | 0         | 0      | 0       | 5      | 
| 2010 | BI-COLOR      | 40    | 0   | 171   | 0      | 0         | 0      | 0       | 211    | 
| 2010 | BLACK         | 13713 | 0   | 36823 | 17     | 169       | 0      | 685     | 51407  | 
| 2010 | BLACK & BEIGE | 1     | 0   | 15    | 0      | 0         | 0      | 0       | 16     | 
| 2010 | BLACK & BROWN | 1002  | 0   | 10943 | 47     | 11        | 0      | 108     | 12111  | 
| 2010 | BLACK & FAWN  | 1     | 0   | 8     | 1      | 0         | 0      | 0       | 10     | 
| 2010 | BLACK & GREY  | 278   | 0   | 371   | 0      | 0         | 0      | 8       | 657    | 
```