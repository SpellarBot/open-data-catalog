# Animal Control - Gender, by Breed - Fiscal Year 2011 Incomplete

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/animal-control-gender-by-breed-fiscal-year-2011-incomplete-bdd7a) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/yhg3-4awc) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/yhg3-4awc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/yhg3-4awc/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | yhg3-4awc |
| Name | Animal Control - Gender, by Breed - Fiscal Year 2011 Incomplete |
| Attribution | Cook County Department of Animal Control |
| Category | Finance & Administration |
| Created | 2011-09-23T17:40:50Z |
| Publication Date | 2014-10-09T21:52:20Z |

## Description

A breakdown of registered animals by gender and breed for part of Fiscal Year 2011. Data last updated September 23, 2011.

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
series e:yhg3-4awc d:2011-01-01T00:00:00.000Z t:breed=ABYSSINIAN m:male_unkn=0 m:female_unk=0 m:female=5 m:male_cast=34 m:male=2 m:female_lit=0 m:unknown=0 m:totals=63 m:female_spayed=22

series e:yhg3-4awc d:2011-01-01T00:00:00.000Z t:breed=AFFENPINSCHER m:male_unkn=0 m:female_unk=0 m:female=2 m:male_cast=12 m:male=4 m:female_lit=0 m:unknown=0 m:totals=30 m:female_spayed=12

series e:yhg3-4awc d:2011-01-01T00:00:00.000Z t:breed="AFGHAN HOUND (TAZI)" m:male_unkn=0 m:female_unk=0 m:female=3 m:male_cast=6 m:male=5 m:female_lit=0 m:unknown=0 m:totals=16 m:female_spayed=2
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

entity e:yhg3-4awc l:"Animal Control - Gender, by Breed - Fiscal Year 2011 Incomplete" t:attribution="Cook County Department of Animal Control" t:url=https://datacatalog.cookcountyil.gov/api/views/yhg3-4awc

property e:yhg3-4awc t:meta.view v:id=yhg3-4awc v:category="Finance & Administration" v:attributionLink=http://www.cookcountygov.com/portal/server.pt/community/animal___rabies_control/247 v:averageRating=0 v:name="Animal Control - Gender, by Breed - Fiscal Year 2011 Incomplete" v:attribution="Cook County Department of Animal Control"

property e:yhg3-4awc t:meta.view.license v:name="Public Domain"

property e:yhg3-4awc t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:yhg3-4awc t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| year | breed                                                  | female | female_lit | female_spayed | female_unk | male | male_cast | male_unkn | unknown | totals | 
| ==== | ====================================================== | ====== | ========== | ============= | ========== | ==== | ========= | ========= | ======= | ====== | 
| 2011 | ABYSSINIAN                                             | 5      | 0          | 22            | 0          | 2    | 34        | 0         | 0       | 63     | 
| 2011 | AFFENPINSCHER                                          | 2      | 0          | 12            | 0          | 4    | 12        | 0         | 0       | 30     | 
| 2011 | AFGHAN HOUND (TAZI)                                    | 3      | 0          | 2             | 0          | 5    | 6         | 0         | 0       | 16     | 
| 2011 | AIREDALE TERRIER                                       | 11     | 0          | 20            | 0          | 14   | 22        | 0         | 0       | 67     | 
| 2011 | AKITA (AKITA INU)                                      | 19     | 0          | 25            | 0          | 39   | 24        | 0         | 0       | 107    | 
| 2011 | AKITA MIXED                                            | 0      | 0          | 5             | 0          | 2    | 8         | 0         | 0       | 15     | 
| 2011 | ALASKAN MALAMUTE                                       | 10     | 0          | 11            | 0          | 8    | 16        | 0         | 0       | 45     | 
| 2011 | ALASKAN MALAMUTE MIXED                                 | 0      | 0          | 3             | 0          | 1    | 3         | 0         | 0       | 7      | 
| 2011 | AMER COCKER SPANIEL                                    | 150    | 0          | 200           | 0          | 197  | 187       | 0         | 3       | 737    | 
| 2011 | AMERICAN BLACK & TAN COONHOUND (BLACK & TAN COONHOUND) | 1      | 0          | 0             | 0          | 0    | 3         | 0         | 0       | 4      | 
```