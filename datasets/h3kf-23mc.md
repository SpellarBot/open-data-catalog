# IDHS FY 06 CASELOADS

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idhs-fy-06-caseloads-b731a) |
| Metadata | [Link](https://data.illinois.gov/api/views/h3kf-23mc) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/h3kf-23mc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/h3kf-23mc/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | h3kf-23mc |
| Name | IDHS FY 06 CASELOADS |
| Category | Social/Healthcare |
| Created | 2011-11-03T11:51:53Z |
| Publication Date | 2011-11-03T11:55:03Z |

## Description

FY 06 CASELOADS

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type | Render Type |
| ======== | ============== | =========================== | =========================== | ========= | =========== |
| No       | time           | :updated_at                 | updated_at                  | meta_data | meta_data   |
| Yes      | series tag     | fy_2006                     | FY 2006                     | text      | text        |
| Yes      | numeric metric | mang                        | MANG                        | number    | number      |
| Yes      | numeric metric | general_assist_transitional | GENERAL ASSIST TRANSITIONAL | number    | number      |
| Yes      | numeric metric | general_assist_family       | GENERAL ASSIST FAMILY       | number    | number      |
| Yes      | numeric metric | tanf                        | TANF                        | number    | number      |
| Yes      | numeric metric | non_assist_food_stamps      | NON-ASSIST FOOD STAMPS      | number    | number      |
| Yes      | numeric metric | aabd                        | AABD                        | number    | number      |
| Yes      | numeric metric | total                       | TOTAL                       | number    | number      |
| Yes      | numeric metric | refugee                     | REFUGEE                     | number    | number      |
| Yes      | numeric metric | total_food_stamps           | TOTAL FOOD STAMPS           | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:h3kf-23mc d:2011-11-03T04:51:55.000Z t:fy_2006=July m:total=1088272 m:general_assist_family=758 m:tanf=41487 m:mang=880720 m:aabd=32394 m:general_assist_transitional=6311 m:refugee=173 m:total_food_stamps=533165 m:non_assist_food_stamps=126602

series e:h3kf-23mc d:2011-11-03T04:51:55.000Z t:fy_2006=August m:total=1094446 m:general_assist_family=755 m:tanf=41621 m:mang=884611 m:aabd=32364 m:general_assist_transitional=6393 m:refugee=198 m:total_food_stamps=537183 m:non_assist_food_stamps=128702

series e:h3kf-23mc d:2011-11-03T04:51:55.000Z t:fy_2006=September m:total=1100481 m:general_assist_family=753 m:tanf=42204 m:mang=887724 m:aabd=32247 m:general_assist_transitional=6334 m:refugee=198 m:total_food_stamps=546754 m:non_assist_food_stamps=131219
```

## Meta Commands

```ls
metric m:mang p:double l:MANG t:dataTypeName=number

metric m:general_assist_transitional p:double l:"GENERAL ASSIST TRANSITIONAL" t:dataTypeName=number

metric m:general_assist_family p:double l:"GENERAL ASSIST FAMILY" t:dataTypeName=number

metric m:tanf p:double l:TANF t:dataTypeName=number

metric m:non_assist_food_stamps p:double l:"NON-ASSIST FOOD STAMPS" t:dataTypeName=number

metric m:aabd p:double l:AABD t:dataTypeName=number

metric m:total p:double l:TOTAL t:dataTypeName=number

metric m:refugee p:double l:REFUGEE t:dataTypeName=number

metric m:total_food_stamps p:double l:"TOTAL FOOD STAMPS" t:dataTypeName=number

entity e:h3kf-23mc l:"IDHS FY 06 CASELOADS" t:url=https://data.illinois.gov/api/views/h3kf-23mc

property e:h3kf-23mc t:meta.view v:id=h3kf-23mc v:category=Social/Healthcare v:averageRating=0 v:name="IDHS FY 06 CASELOADS"

property e:h3kf-23mc t:meta.view.owner v:id=e9y5-49nr v:screenName="Carl Awe" v:displayName="Carl Awe"

property e:h3kf-23mc t:meta.view.tableauthor v:id=e9y5-49nr v:screenName="Carl Awe" v:displayName="Carl Awe"
```

## Top Records

```ls
| :updated_at | fy_2006   | mang   | general_assist_transitional | general_assist_family | tanf  | non_assist_food_stamps | aabd  | total   | refugee | total_food_stamps | 
| =========== | ========= | ====== | =========================== | ===================== | ===== | ====================== | ===== | ======= | ======= | ================= | 
| 1320295915  | July      | 880720 | 6311                        | 758                   | 41487 | 126602                 | 32394 | 1088272 | 173     | 533165            | 
| 1320295915  | August    | 884611 | 6393                        | 755                   | 41621 | 128702                 | 32364 | 1094446 | 198     | 537183            | 
| 1320295915  | September | 887724 | 6334                        | 753                   | 42204 | 131219                 | 32247 | 1100481 | 198     | 546754            | 
| 1320295915  | October   | 891991 | 6565                        | 760                   | 42380 | 131858                 | 32205 | 1105759 | 248     | 547459            | 
| 1320295915  | November  | 895766 | 6569                        | 766                   | 41958 | 132431                 | 32175 | 1109665 | 259     | 551063            | 
| 1320295915  | December  | 901498 | 6473                        | 769                   | 42137 | 135170                 | 32108 | 1118155 | 289     | 560039            | 
| 1320295915  | January   | 904958 | 6412                        | 769                   | 41549 | 134529                 | 31946 | 1120163 | 290     | 552271            | 
| 1320295915  | February  | 906015 | 6421                        | 776                   | 40860 | 133596                 | 31755 | 1119423 | 302     | 553399            | 
| 1320295915  | March     | 905556 | 7169                        | 766                   | 40649 | 135833                 | 31679 | 1121652 | 292     | 561058            | 
| 1320295915  | April     | 902003 | 6631                        | 791                   | 39802 | 135097                 | 31491 | 1115815 | 287     | 555185            | 
```