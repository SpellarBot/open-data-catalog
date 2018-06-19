# Animal Control - Summary of Animal Gender by Species - 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/animal-control-summary-of-animal-gender-by-species-2010-a1f58) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/d5ez-mkjy) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/d5ez-mkjy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/d5ez-mkjy/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | d5ez-mkjy |
| Name | Animal Control - Summary of Animal Gender by Species - 2010 |
| Attribution | Cook County Department of Animal Control |
| Category | Finance & Administration |
| Created | 2011-09-23T20:42:04Z |
| Publication Date | 2014-10-09T21:46:51Z |

## Description

This data set contains a summary of cats, cows, dogs, ferrets, rabbits, and unknown animals in Cook County

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| Yes      | time           | year          | Year          | number    | text        |
| Yes      | series tag     | type          | Type          | text      | text        |
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
series e:d5ez-mkjy d:2010-01-01T00:00:00.000Z t:type=CAT m:male_unkn=0 m:female_unk=0 m:female=8596 m:male_cast=34080 m:male=8350 m:female_lit=0 m:unknown=2241 m:totals=86723 m:female_spayed=33456

series e:d5ez-mkjy d:2010-01-01T00:00:00.000Z t:type=COW m:male_unkn=0 m:female_unk=0 m:female=0 m:male_cast=1 m:male=0 m:female_lit=0 m:unknown=0 m:totals=1 m:female_spayed=0

series e:d5ez-mkjy d:2010-01-01T00:00:00.000Z t:type=DOG m:male_unkn=0 m:female_unk=0 m:female=39802 m:male_cast=73788 m:male=50788 m:female_lit=1 m:unknown=11245 m:totals=248707 m:female_spayed=73083
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

entity e:d5ez-mkjy l:"Animal Control - Summary of Animal Gender by Species - 2010" t:attribution="Cook County Department of Animal Control" t:url=https://datacatalog.cookcountyil.gov/api/views/d5ez-mkjy

property e:d5ez-mkjy t:meta.view v:id=d5ez-mkjy v:category="Finance & Administration" v:attributionLink=http://www.cookcountygov.com/portal/server.pt/community/animal___rabies_control/247 v:averageRating=0 v:name="Animal Control - Summary of Animal Gender by Species - 2010" v:attribution="Cook County Department of Animal Control"

property e:d5ez-mkjy t:meta.view.license v:name="Public Domain"

property e:d5ez-mkjy t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:d5ez-mkjy t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| year | type      | female | female_lit | female_spayed | female_unk | male  | male_cast | male_unkn | unknown | totals | 
| ==== | ========= | ====== | ========== | ============= | ========== | ===== | ========= | ========= | ======= | ====== | 
| 2010 | CAT       | 8596   | 0          | 33456         | 0          | 8350  | 34080     | 0         | 2241    | 86723  | 
| 2010 | COW       | 0      | 0          | 0             | 0          | 0     | 1         | 0         | 0       | 1      | 
| 2010 | DOG       | 39802  | 1          | 73083         | 0          | 50788 | 73788     | 0         | 11245   | 248707 | 
| 2010 | FERRET    | 49     | 0          | 62            | 0          | 59    | 68        | 0         | 3       | 241    | 
| 2010 | GUARD DOG | 61     | 0          | 1             | 0          | 168   | 11        | 0         | 0       | 241    | 
| 2010 | RABBIT    | 0      | 0          | 0             | 0          | 1     | 0         | 0         | 0       | 1      | 
| 2010 | UNKNOWN   | 282    | 41         | 2830          | 1          | 418   | 2753      | 1         | 1733    | 8059   | 
```