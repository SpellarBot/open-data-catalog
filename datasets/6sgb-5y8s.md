# Animal Control - Gender, by Breed - Fiscal Year 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/animal-control-gender-by-breed-fiscal-year-2010-6c933) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/6sgb-5y8s) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/6sgb-5y8s/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/6sgb-5y8s/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | 6sgb-5y8s |
| Name | Animal Control - Gender, by Breed - Fiscal Year 2010 |
| Attribution | Cook County Department of Animal Control |
| Category | Finance & Administration |
| Created | 2011-09-23T17:37:42Z |
| Publication Date | 2014-10-09T22:03:06Z |

## Description

For Fiscal Year 2010 a breakdown of registered animals by gender and breed

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| Yes      | time           | year          | Year          | number    | text        |
| Yes      | series tag     | breed         | Breed         | text      | text        |
| Yes      | numeric metric | female        | FEMALE        | number    | number      |
| Yes      | numeric metric | female_lit    | FEMALE LIT    | number    | number      |
| Yes      | numeric metric | female_spayed | FEMALE SPAYED | number    | number      |
| Yes      | numeric metric | female_unk    | FEMALE UNK    | number    | number      |
| Yes      | numeric metric | male          | MALE          | number    | number      |
| Yes      | numeric metric | male_cast     | MALE CAST     | number    | number      |
| Yes      | numeric metric | male_unkn     | MALE UNKN     | number    | number      |
| Yes      | numeric metric | unknown       | UNKNOWN       | number    | number      |
| Yes      | numeric metric | totals        | Totals        | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:6sgb-5y8s d:2010-01-01T00:00:00.000Z t:breed=ABYSSINIAN m:male_unkn=0 m:female_unk=0 m:female=4 m:male_cast=56 m:male=5 m:female_lit=0 m:unknown=3 m:totals=124 m:female_spayed=56

series e:6sgb-5y8s d:2010-01-01T00:00:00.000Z t:breed=AFFENPINSCHER m:male_unkn=0 m:female_unk=0 m:female=2 m:male_cast=52 m:male=11 m:female_lit=0 m:unknown=0 m:totals=101 m:female_spayed=36

series e:6sgb-5y8s d:2010-01-01T00:00:00.000Z t:breed="AFGHAN HOUND (TAZI)" m:male_unkn=0 m:female_unk=0 m:female=9 m:male_cast=13 m:male=10 m:female_lit=0 m:unknown=0 m:totals=35 m:female_spayed=3
```

## Meta Commands

```ls
metric m:female p:integer l:FEMALE t:dataTypeName=number

metric m:female_lit p:integer l:"FEMALE LIT" t:dataTypeName=number

metric m:female_spayed p:integer l:"FEMALE SPAYED" t:dataTypeName=number

metric m:female_unk p:integer l:"FEMALE UNK" t:dataTypeName=number

metric m:male p:integer l:MALE t:dataTypeName=number

metric m:male_cast p:integer l:"MALE CAST" t:dataTypeName=number

metric m:male_unkn p:integer l:"MALE UNKN" t:dataTypeName=number

metric m:unknown p:integer l:UNKNOWN t:dataTypeName=number

metric m:totals p:integer l:Totals t:dataTypeName=number

entity e:6sgb-5y8s l:"Animal Control - Gender, by Breed - Fiscal Year 2010" t:attribution="Cook County Department of Animal Control" t:url=https://datacatalog.cookcountyil.gov/api/views/6sgb-5y8s

property e:6sgb-5y8s t:meta.view v:id=6sgb-5y8s v:category="Finance & Administration" v:attributionLink=http://www.cookcountygov.com/portal/server.pt/community/animal___rabies_control/247 v:averageRating=0 v:name="Animal Control - Gender, by Breed - Fiscal Year 2010" v:attribution="Cook County Department of Animal Control"

property e:6sgb-5y8s t:meta.view.license v:name="Public Domain"

property e:6sgb-5y8s t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:6sgb-5y8s t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| year | breed                             | female | female_lit | female_spayed | female_unk | male | male_cast | male_unkn | unknown | totals | 
| ==== | ================================= | ====== | ========== | ============= | ========== | ==== | ========= | ========= | ======= | ====== | 
| 2010 | ABYSSINIAN                        | 4      | 0          | 56            | 0          | 5    | 56        | 0         | 3       | 124    | 
| 2010 | AFFENPINSCHER                     | 2      | 0          | 36            | 0          | 11   | 52        | 0         | 0       | 101    | 
| 2010 | AFGHAN HOUND (TAZI)               | 9      | 0          | 3             | 0          | 10   | 13        | 0         | 0       | 35     | 
| 2010 | AINU DOG (HOHKAIDO DOG, AINU KEN) | 0      | 0          | 2             | 0          | 0    | 2         | 0         | 0       | 4      | 
| 2010 | AIREDALE TERRIER                  | 35     | 0          | 55            | 0          | 37   | 59        | 0         | 0       | 186    | 
| 2010 | AKBASH DOG                        | 1      | 0          | 0             | 0          | 0    | 0         | 0         | 0       | 1      | 
| 2010 | AKITA (AKITA INU)                 | 79     | 0          | 93            | 0          | 120  | 78        | 0         | 2       | 372    | 
| 2010 | AKITA MIXED                       | 3      | 0          | 8             | 0          | 3    | 18        | 0         | 0       | 32     | 
| 2010 | ALASKAN MALAMUTE                  | 12     | 0          | 37            | 0          | 21   | 49        | 0         | 0       | 119    | 
| 2010 | ALASKAN MALAMUTE MIXED            | 3      | 0          | 5             | 0          | 4    | 9         | 0         | 0       | 21     | 
```