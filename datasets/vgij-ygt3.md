# Animal Control - Animal Species By City And Gender - Part of Fiscal Year 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/animal-control-animal-species-by-city-and-gender-part-of-fiscal-year-2011-836d1) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/vgij-ygt3) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/vgij-ygt3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/vgij-ygt3/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | vgij-ygt3 |
| Name | Animal Control - Animal Species By City And Gender - Part of Fiscal Year 2011 |
| Attribution | Cook County Department of Animal Control |
| Category | Finance & Administration |
| Created | 2011-09-26T20:29:23Z |
| Publication Date | 2014-10-09T21:48:17Z |

## Description

Animal Species by city and gender for part of Fiscal Year 2011. Data last updated September 26, 2011

## Columns

```ls
| Included | Schema Type    | Field Name | Name      | Data Type | Render Type |
| ======== | ============== | ========== | ========= | ========= | =========== |
| Yes      | time           | year       | Year      | number    | text        |
| Yes      | series tag     | sex        | Sex       | text      | text        |
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
series e:vgij-ygt3 d:2011-01-01T00:00:00.000Z t:sex=FEMALE m:rabbit=0 m:cat=1 m:cow=0 m:guard_dog=0 m:unknown=0 m:totals=13 m:dog=12 m:ferret=0

series e:vgij-ygt3 d:2011-01-01T00:00:00.000Z t:sex="FEMALE SPAYED" m:rabbit=0 m:cat=13 m:cow=0 m:guard_dog=0 m:unknown=0 m:totals=20 m:dog=7 m:ferret=0

series e:vgij-ygt3 d:2011-01-01T00:00:00.000Z t:sex=MALE m:rabbit=0 m:cat=0 m:cow=0 m:guard_dog=0 m:unknown=0 m:totals=13 m:dog=13 m:ferret=0
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

entity e:vgij-ygt3 l:"Animal Control - Animal Species By City And Gender - Part of Fiscal Year 2011" t:attribution="Cook County Department of Animal Control" t:url=https://datacatalog.cookcountyil.gov/api/views/vgij-ygt3

property e:vgij-ygt3 t:meta.view v:id=vgij-ygt3 v:category="Finance & Administration" v:attributionLink=http://www.cookcountygov.com/portal/server.pt/community/animal___rabies_control/247 v:averageRating=0 v:name="Animal Control - Animal Species By City And Gender - Part of Fiscal Year 2011" v:attribution="Cook County Department of Animal Control"

property e:vgij-ygt3 t:meta.view.license v:name="Public Domain"

property e:vgij-ygt3 t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:vgij-ygt3 t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| year | sex           | cat | cow | dog | ferret | guard_dog | rabbit | unknown | totals | 
| ==== | ============= | === | === | === | ====== | ========= | ====== | ======= | ====== | 
| 2011 | FEMALE        | 1   | 0   | 12  | 0      | 0         | 0      | 0       | 13     | 
| 2011 | FEMALE SPAYED | 13  | 0   | 7   | 0      | 0         | 0      | 0       | 20     | 
| 2011 | MALE          | 0   | 0   | 13  | 0      | 0         | 0      | 0       | 13     | 
| 2011 | MALE CAST     | 14  | 0   | 16  | 0      | 0         | 0      | 0       | 30     | 
| 2011 | UNKNOWN       | 1   | 0   | 0   | 0      | 0         | 0      | 0       | 1      | 
| 2011 | FEMALE        | 0   | 0   | 1   | 0      | 0         | 0      | 0       | 1      | 
| 2011 | FEMALE SPAYED | 0   | 0   | 6   | 0      | 0         | 0      | 0       | 6      | 
| 2011 | MALE          | 0   | 0   | 2   | 0      | 0         | 0      | 0       | 2      | 
| 2011 | MALE CAST     | 2   | 0   | 7   | 0      | 0         | 0      | 0       | 9      | 
| 2011 | FEMALE        | 16  | 0   | 109 | 0      | 5         | 0      | 5       | 135    | 
```