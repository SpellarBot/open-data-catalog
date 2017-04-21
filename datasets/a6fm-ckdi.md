# Animal Control - Species By Color - Fiscal Year 2011 Incomplete

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/animal-control-species-by-color-fiscal-year-2011-incomplete-cef74) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/a6fm-ckdi) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/a6fm-ckdi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/a6fm-ckdi/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | a6fm-ckdi |
| Name | Animal Control - Species By Color - Fiscal Year 2011 Incomplete |
| Attribution | Cook County Department of Animal Control |
| Category | Finance & Administration |
| Created | 2011-09-26T20:16:52Z |
| Publication Date | 2014-10-09T22:05:50Z |

## Description

Species by color data for part of fiscal year 2011. Data last updated September 2011

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
series e:a6fm-ckdi d:2011-01-01T00:00:00.000Z t:color=APRICOT m:rabbit=0 m:cat=14 m:cow=0 m:guard_dog=0 m:unknown=15 m:totals=919 m:dog=890 m:ferret=0

series e:a6fm-ckdi d:2011-01-01T00:00:00.000Z t:color=AUBURN m:rabbit=0 m:cat=0 m:cow=0 m:guard_dog=0 m:unknown=0 m:totals=32 m:dog=32 m:ferret=0

series e:a6fm-ckdi d:2011-01-01T00:00:00.000Z t:color=BEIGE m:rabbit=0 m:cat=148 m:cow=0 m:guard_dog=0 m:unknown=14 m:totals=946 m:dog=784 m:ferret=0
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

entity e:a6fm-ckdi l:"Animal Control - Species By Color - Fiscal Year 2011 Incomplete" t:attribution="Cook County Department of Animal Control" t:url=https://datacatalog.cookcountyil.gov/api/views/a6fm-ckdi

property e:a6fm-ckdi t:meta.view v:id=a6fm-ckdi v:category="Finance & Administration" v:averageRating=0 v:name="Animal Control - Species By Color - Fiscal Year 2011 Incomplete" v:attribution="Cook County Department of Animal Control"

property e:a6fm-ckdi t:meta.view.license v:name="Public Domain"

property e:a6fm-ckdi t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:a6fm-ckdi t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| year | color         | cat  | cow | dog   | ferret | guard_dog | rabbit | unknown | totals | 
| ==== | ============= | ==== | === | ===== | ====== | ========= | ====== | ======= | ====== | 
| 2011 | APRICOT       | 14   | 0   | 890   | 0      | 0         | 0      | 15      | 919    | 
| 2011 | AUBURN        | 0    | 0   | 32    | 0      | 0         | 0      | 0       | 32     | 
| 2011 | BEIGE         | 148  | 0   | 784   | 0      | 0         | 0      | 14      | 946    | 
| 2011 | BELTON        | 0    | 0   | 1     | 0      | 0         | 0      | 0       | 1      | 
| 2011 | BI-COLOR      | 7    | 0   | 39    | 0      | 0         | 0      | 5       | 51     | 
| 2011 | BLACK         | 5783 | 0   | 14410 | 0      | 97        | 0      | 495     | 20785  | 
| 2011 | BLACK & BEIGE | 1    | 0   | 4     | 0      | 0         | 0      | 0       | 5      | 
| 2011 | BLACK & BROWN | 408  | 0   | 4572  | 0      | 12        | 0      | 184     | 5176   | 
| 2011 | BLACK & FAWN  | 1    | 0   | 5     | 0      | 0         | 0      | 0       | 6      | 
| 2011 | BLACK & GREY  | 138  | 0   | 213   | 0      | 0         | 0      | 8       | 359    | 
```