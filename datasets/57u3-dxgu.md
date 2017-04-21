# Animal Control - Gender by Species - Fiscal Year 2011 Incomplete

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/animal-control-gender-by-species-fiscal-year-2011-incomplete-e114c) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/57u3-dxgu) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/57u3-dxgu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/57u3-dxgu/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | 57u3-dxgu |
| Name | Animal Control - Gender by Species - Fiscal Year 2011 Incomplete |
| Attribution | Cook County Department of Animal Control |
| Category | Finance & Administration |
| Created | 2011-09-23T20:48:57Z |
| Publication Date | 2014-10-09T22:20:25Z |

## Description

Data last updated September 2011

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
series e:57u3-dxgu d:2011-01-01T00:00:00.000Z t:type=CAT m:male_unkn=0 m:female_unk=0 m:female=3138 m:male_cast=15982 m:male=3185 m:female_lit=0 m:unknown=906 m:totals=39134 m:female_spayed=15923

series e:57u3-dxgu d:2011-01-01T00:00:00.000Z t:type=DOG m:male_unkn=1 m:female_unk=0 m:female=15909 m:male_cast=35767 m:male=20768 m:female_lit=0 m:unknown=6608 m:totals=114911 m:female_spayed=35858

series e:57u3-dxgu d:2011-01-01T00:00:00.000Z t:type=FERRET m:male_unkn=0 m:female_unk=0 m:female=14 m:male_cast=19 m:male=19 m:female_lit=0 m:unknown=2 m:totals=72 m:female_spayed=18
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

entity e:57u3-dxgu l:"Animal Control - Gender by Species - Fiscal Year 2011 Incomplete" t:attribution="Cook County Department of Animal Control" t:url=https://datacatalog.cookcountyil.gov/api/views/57u3-dxgu

property e:57u3-dxgu t:meta.view v:id=57u3-dxgu v:category="Finance & Administration" v:averageRating=0 v:name="Animal Control - Gender by Species - Fiscal Year 2011 Incomplete" v:attribution="Cook County Department of Animal Control"

property e:57u3-dxgu t:meta.view.license v:name="Public Domain"

property e:57u3-dxgu t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:57u3-dxgu t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| year | type      | female | female_lit | female_spayed | female_unk | male  | male_cast | male_unkn | unknown | totals | 
| ==== | ========= | ====== | ========== | ============= | ========== | ===== | ========= | ========= | ======= | ====== | 
| 2011 | CAT       | 3138   | 0          | 15923         | 0          | 3185  | 15982     | 0         | 906     | 39134  | 
| 2011 | DOG       | 15909  | 0          | 35858         | 0          | 20768 | 35767     | 1         | 6608    | 114911 | 
| 2011 | FERRET    | 14     | 0          | 18            | 0          | 19    | 19        | 0         | 2       | 72     | 
| 2011 | GUARD DOG | 44     | 0          | 0             | 0          | 96    | 1         | 0         | 0       | 141    | 
| 2011 | UNKNOWN   | 315    | 6          | 1624          | 0          | 418   | 1556      | 0         | 283     | 4202   | 
```