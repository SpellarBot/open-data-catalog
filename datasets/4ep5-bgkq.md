# IDHS FY 01 CASELOADS

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idhs-fy-01-caseloads-88316) |
| Metadata | [Link](https://data.illinois.gov/api/views/4ep5-bgkq) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/4ep5-bgkq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/4ep5-bgkq/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 4ep5-bgkq |
| Name | IDHS FY 01 CASELOADS |
| Category | Social/Healthcare |
| Created | 2011-11-02T19:12:43Z |
| Publication Date | 2011-11-02T19:15:52Z |

## Description

FY 01 CASELOADS

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type | Render Type |
| ======== | ============== | =========================== | =========================== | ========= | =========== |
| No       | time           | :updated_at                 | updated_at                  | meta_data | meta_data   |
| Yes      | series tag     | fy_2001                     | FY 2001                     | text      | text        |
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
series e:4ep5-bgkq d:2011-11-02T12:12:45.000Z t:fy_2001=July m:total=825656 m:general_assist_family=659 m:tanf=79424 m:mang=620439 m:aabd=40157 m:general_assist_transitional=6067 m:refugee=331 m:total_food_stamps=365991 m:non_assist_food_stamps=78910

series e:4ep5-bgkq d:2011-11-02T12:12:45.000Z t:fy_2001=August m:total=836022 m:general_assist_family=684 m:tanf=80957 m:mang=625027 m:aabd=40137 m:general_assist_transitional=6100 m:refugee=344 m:total_food_stamps=364010 m:non_assist_food_stamps=83117

series e:4ep5-bgkq d:2011-11-02T12:12:45.000Z t:fy_2001=September m:total=839844 m:general_assist_family=686 m:tanf=79707 m:mang=629637 m:aabd=39934 m:general_assist_transitional=6074 m:refugee=382 m:total_food_stamps=364864 m:non_assist_food_stamps=83806
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

entity e:4ep5-bgkq l:"IDHS FY 01 CASELOADS" t:url=https://data.illinois.gov/api/views/4ep5-bgkq

property e:4ep5-bgkq t:meta.view v:id=4ep5-bgkq v:category=Social/Healthcare v:averageRating=0 v:name="IDHS FY 01 CASELOADS"

property e:4ep5-bgkq t:meta.view.owner v:id=e9y5-49nr v:screenName="Carl Awe" v:displayName="Carl Awe"

property e:4ep5-bgkq t:meta.view.tableauthor v:id=e9y5-49nr v:screenName="Carl Awe" v:displayName="Carl Awe"
```

## Top Records

```ls
| :updated_at | fy_2001   | mang   | general_assist_transitional | general_assist_family | tanf  | non_assist_food_stamps | aabd  | total  | refugee | total_food_stamps | 
| =========== | ========= | ====== | =========================== | ===================== | ===== | ====================== | ===== | ====== | ======= | ================= | 
| 1320235965  | July      | 620439 | 6067                        | 659                   | 79424 | 78910                  | 40157 | 825656 | 331     | 365991            | 
| 1320235965  | August    | 625027 | 6100                        | 684                   | 80957 | 83117                  | 40137 | 836022 | 344     | 364010            | 
| 1320235965  | September | 629637 | 6074                        | 686                   | 79707 | 83806                  | 39934 | 839844 | 382     | 364864            | 
| 1320235965  | October   | 635154 | 6121                        | 710                   | 74411 | 79080                  | 39833 | 835309 | 424     | 350362            | 
| 1320235965  | November  | 642303 | 6083                        | 708                   | 75035 | 81891                  | 39767 | 845787 | 433     | 360463            | 
| 1320235965  | December  | 643017 | 6162                        | 719                   | 74871 | 83809                  | 39633 | 848211 | 394     | 367550            | 
| 1320235965  | January   | 653330 | 6143                        | 710                   | 70209 | 80817                  | 39542 | 850751 | 418     | 354907            | 
| 1320235965  | February  | 657393 | 5841                        | 703                   | 68581 | 83211                  | 39015 | 854744 | 375     | 359149            | 
| 1320235965  | March     | 665452 | 6194                        | 739                   | 69634 | 86769                  | 39321 | 868109 | 406     | 371795            | 
| 1320235965  | April     | 670026 | 6122                        | 743                   | 64833 | 81675                  | 39258 | 862657 | 418     | 352603            | 
```