# IDHS FY 09 CASELOADS

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idhs-fy-09-caseloads-ac264) |
| Metadata | [Link](https://data.illinois.gov/api/views/63k2-pmuf) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/63k2-pmuf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/63k2-pmuf/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 63k2-pmuf |
| Name | IDHS FY 09 CASELOADS |
| Category | Social/Healthcare |
| Created | 2011-11-03T12:20:30Z |
| Publication Date | 2011-11-03T12:26:00Z |

## Description

FY 09 CASELOADS

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type | Render Type |
| ======== | ============== | =========================== | =========================== | ========= | =========== |
| No       | time           | :updated_at                 | updated_at                  | meta_data | meta_data   |
| Yes      | series tag     | fy_2009                     | FY 2009                     | text      | text        |
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
series e:63k2-pmuf d:2011-11-03T05:20:31.000Z t:fy_2009=July m:total=1257022 m:general_assist_family=841 m:tanf=26953 m:mang=1042254 m:aabd=29549 m:general_assist_transitional=7859 m:refugee=370 m:total_food_stamps=605662 m:non_assist_food_stamps=149566

series e:63k2-pmuf d:2011-11-03T05:20:31.000Z t:fy_2009=August m:total=1262493 m:general_assist_family=841 m:tanf=26814 m:mang=1047074 m:aabd=29467 m:general_assist_transitional=7929 m:refugee=433 m:total_food_stamps=611531 m:non_assist_food_stamps=150368

series e:63k2-pmuf d:2011-11-03T05:20:31.000Z t:fy_2009=September m:total=1266451 m:general_assist_family=834 m:tanf=26675 m:mang=1050769 m:aabd=29439 m:general_assist_transitional=7783 m:refugee=462 m:total_food_stamps=607215 m:non_assist_food_stamps=150951
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

entity e:63k2-pmuf l:"IDHS FY 09 CASELOADS" t:url=https://data.illinois.gov/api/views/63k2-pmuf

property e:63k2-pmuf t:meta.view v:id=63k2-pmuf v:category=Social/Healthcare v:averageRating=0 v:name="IDHS FY 09 CASELOADS"

property e:63k2-pmuf t:meta.view.owner v:id=e9y5-49nr v:screenName="Carl Awe" v:displayName="Carl Awe"

property e:63k2-pmuf t:meta.view.tableauthor v:id=e9y5-49nr v:screenName="Carl Awe" v:displayName="Carl Awe"
```

## Top Records

```ls
| :updated_at | fy_2009   | mang    | general_assist_transitional | general_assist_family | tanf  | non_assist_food_stamps | aabd  | total   | refugee | total_food_stamps | 
| =========== | ========= | ======= | =========================== | ===================== | ===== | ====================== | ===== | ======= | ======= | ================= | 
| 1320297631  | July      | 1042254 | 7859                        | 841                   | 26953 | 149566                 | 29549 | 1257022 | 370     | 605662            | 
| 1320297631  | August    | 1047074 | 7929                        | 841                   | 26814 | 150368                 | 29467 | 1262493 | 433     | 611531            | 
| 1320297631  | September | 1050769 | 7783                        | 834                   | 26675 | 150951                 | 29439 | 1266451 | 462     | 607215            | 
| 1320297631  | October   | 1056721 | 7833                        | 848                   | 26824 | 172141                 | 29438 | 1293805 | 505     | 640037            | 
| 1320297631  | November  | 1061361 | 7664                        | 835                   | 26921 | 158581                 | 29406 | 1284768 | 509     | 628723            | 
| 1320297631  | December  | 1066359 | 7801                        | 846                   | 27699 | 161315                 | 29526 | 1293546 | 547     | 633923            | 
| 1320297631  | January   | 1073405 | 7819                        | 839                   | 27596 | 169648                 | 29412 | 1308719 | 542     | 655751            | 
| 1320297631  | February  | 1076473 | 7986                        | 845                   | 27563 | 175398                 | 29384 | 1317649 | 531     | 663016            | 
| 1320297631  | March     | 1082215 | 8135                        | 843                   | 27527 | 180723                 | 29650 | 1329093 | 519     | 672138            | 
| 1320297631  | April     | 1087774 | 8217                        | 845                   | 27648 | 185977                 | 29291 | 1339752 | 509     | 687775            | 
```