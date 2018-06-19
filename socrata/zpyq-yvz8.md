# IDHS - FY 11 CASELOADS

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idhs-fy-11-caseloads-f0bd3) |
| Metadata | [Link](https://data.illinois.gov/api/views/zpyq-yvz8) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/zpyq-yvz8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/zpyq-yvz8/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | zpyq-yvz8 |
| Name | IDHS - FY 11 CASELOADS |
| Category | Social/Healthcare |
| Created | 2011-11-03T12:38:26Z |
| Publication Date | 2011-11-03T12:41:23Z |

## Description

FY 11 CASELOADS

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type | Render Type |
| ======== | ============== | =========================== | =========================== | ========= | =========== |
| No       | time           | :updated_at                 | updated_at                  | meta_data | meta_data   |
| Yes      | series tag     | fy_2011                     | FY 2011                     | text      | text        |
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
series e:zpyq-yvz8 d:2011-11-03T05:39:04.000Z t:fy_2011=July m:total=1572071 m:general_assist_family=884 m:tanf=34373 m:mang=1260220 m:aabd=29241 m:general_assist_transitional=9177 m:refugee=491 m:total_food_stamps=795746 m:non_assist_food_stamps=238176

series e:zpyq-yvz8 d:2011-11-03T05:39:04.000Z t:fy_2011=August m:total=1577449 m:general_assist_family=883 m:tanf=35912 m:mang=1262048 m:aabd=29291 m:general_assist_transitional=9068 m:refugee=452 m:total_food_stamps=803812 m:non_assist_food_stamps=240247

series e:zpyq-yvz8 d:2011-11-03T05:39:04.000Z t:fy_2011=September m:total=1618606 m:general_assist_family=891 m:tanf=36773 m:mang=1265576 m:aabd=29601 m:general_assist_transitional=9155 m:refugee=438 m:total_food_stamps=849263 m:non_assist_food_stamps=276610
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

entity e:zpyq-yvz8 l:"IDHS - FY 11 CASELOADS" t:url=https://data.illinois.gov/api/views/zpyq-yvz8

property e:zpyq-yvz8 t:meta.view v:id=zpyq-yvz8 v:category=Social/Healthcare v:averageRating=0 v:name="IDHS - FY 11 CASELOADS"

property e:zpyq-yvz8 t:meta.view.owner v:id=e9y5-49nr v:screenName="Carl Awe" v:displayName="Carl Awe"

property e:zpyq-yvz8 t:meta.view.tableauthor v:id=e9y5-49nr v:screenName="Carl Awe" v:displayName="Carl Awe"
```

## Top Records

```ls
| :updated_at | fy_2011   | mang    | general_assist_transitional | general_assist_family | tanf  | non_assist_food_stamps | aabd  | total   | refugee | total_food_stamps | 
| =========== | ========= | ======= | =========================== | ===================== | ===== | ====================== | ===== | ======= | ======= | ================= | 
| 1320298744  | July      | 1260220 | 9177                        | 884                   | 34373 | 238176                 | 29241 | 1572071 | 491     | 795746            | 
| 1320298744  | August    | 1262048 | 9068                        | 883                   | 35912 | 240247                 | 29291 | 1577449 | 452     | 803812            | 
| 1320298744  | September | 1265576 | 9155                        | 891                   | 36773 | 276610                 | 29601 | 1618606 | 438     | 849263            | 
| 1320298744  | October   | 1270163 | 9179                        | 882                   | 37939 | 244683                 | 29638 | 1592484 | 414     | 817687            | 
| 1320298744  | November  | 1273920 | 9183                        | 903                   | 38837 | 250206                 | 29644 | 1602693 | 408     | 825059            | 
| 1320298744  | December  | 1278003 | 9217                        | 903                   | 40627 | 262406                 | 29755 | 1620911 | 407     | 857282            | 
| 1320298744  | January   | 1282297 | 9265                        | 911                   | 41221 | 268970                 | 29728 | 1632392 | 402     | 861850            | 
| 1320298744  | February  | 1283009 | 9190                        | 895                   | 41374 | 268604                 | 29669 | 1632741 | 416     | 860797            | 
| 1320298744  | March     |         |                             |                       |       |                        |       |         |         |                   | 
| 1320298744  | April     |         |                             |                       |       |                        |       |         |         |                   | 
```