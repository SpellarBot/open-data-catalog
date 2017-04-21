# IDHS FY 10 CASELOADS

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idhs-fy-10-caseloads-9a4a8) |
| Metadata | [Link](https://data.illinois.gov/api/views/kh6p-bipc) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/kh6p-bipc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/kh6p-bipc/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | kh6p-bipc |
| Name | IDHS FY 10 CASELOADS |
| Category | Social/Healthcare |
| Created | 2011-11-03T12:32:27Z |
| Publication Date | 2011-11-03T12:35:26Z |

## Description

FY 10 CASELOADS

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type | Render Type |
| ======== | ============== | =========================== | =========================== | ========= | =========== |
| No       | time           | :updated_at                 | updated_at                  | meta_data | meta_data   |
| Yes      | series tag     | fy_2010                     | FY 2010                     | text      | text        |
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
series e:kh6p-bipc d:2011-11-03T05:32:54.000Z t:fy_2010=July m:total=1371666 m:general_assist_family=856 m:tanf=28844 m:mang=1107724 m:aabd=29240 m:general_assist_transitional=8424 m:refugee=550 m:total_food_stamps=712041 m:non_assist_food_stamps=196578

series e:kh6p-bipc d:2011-11-03T05:32:54.000Z t:fy_2010=August m:total=1378355 m:general_assist_family=859 m:tanf=29007 m:mang=1113732 m:aabd=29232 m:general_assist_transitional=8439 m:refugee=519 m:total_food_stamps=713213 m:non_assist_food_stamps=197086

series e:kh6p-bipc d:2011-11-03T05:32:54.000Z t:fy_2010=September m:total=1390359 m:general_assist_family=859 m:tanf=29534 m:mang=1120500 m:aabd=29268 m:general_assist_transitional=8320 m:refugee=563 m:total_food_stamps=724500 m:non_assist_food_stamps=201878
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

entity e:kh6p-bipc l:"IDHS FY 10 CASELOADS" t:url=https://data.illinois.gov/api/views/kh6p-bipc

property e:kh6p-bipc t:meta.view v:id=kh6p-bipc v:category=Social/Healthcare v:averageRating=0 v:name="IDHS FY 10 CASELOADS"

property e:kh6p-bipc t:meta.view.owner v:id=e9y5-49nr v:screenName="Carl Awe" v:displayName="Carl Awe"

property e:kh6p-bipc t:meta.view.tableauthor v:id=e9y5-49nr v:screenName="Carl Awe" v:displayName="Carl Awe"
```

## Top Records

```ls
| :updated_at | fy_2010   | mang    | general_assist_transitional | general_assist_family | tanf  | non_assist_food_stamps | aabd  | total   | refugee | total_food_stamps | 
| =========== | ========= | ======= | =========================== | ===================== | ===== | ====================== | ===== | ======= | ======= | ================= | 
| 1320298374  | July      | 1107724 | 8424                        | 856                   | 28844 | 196578                 | 29240 | 1371666 | 550     | 712041            | 
| 1320298374  | August    | 1113732 | 8439                        | 859                   | 29007 | 197086                 | 29232 | 1378355 | 519     | 713213            | 
| 1320298374  | September | 1120500 | 8320                        | 859                   | 29534 | 201878                 | 29268 | 1390359 | 563     | 724500            | 
| 1320298374  | October   | 1127347 | 8408                        | 864                   | 30167 | 207523                 | 29314 | 1403623 | 607     | 739304            | 
| 1320298374  | November  | 1132965 | 8414                        | 866                   | 30763 | 209923                 | 29286 | 1412217 | 614     | 737443            | 
| 1320298374  | December  | 1138213 | 8488                        | 876                   | 32095 | 216497                 | 29328 | 1425497 | 625     | 760630            | 
| 1320298374  | January   | 1143674 | 8516                        | 876                   | 32217 | 215543                 | 29327 | 1430153 | 648     | 755937            | 
| 1320298374  | February  | 1147328 | 8538                        | 861                   | 31991 | 216428                 | 29336 | 1434482 | 624     | 756341            | 
| 1320298374  | March     | 1152020 | 8629                        | 874                   | 32289 | 222190                 | 29345 | 1445347 | 594     | 765758            | 
| 1320298374  | April     | 1183180 | 8821                        | 875                   | 32398 | 225261                 | 29303 | 1479838 | 584     | 769309            | 
```