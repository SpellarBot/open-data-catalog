# IDHS FY 03 CASELOADS

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idhs-fy-03-caseloads-fc607) |
| Metadata | [Link](https://data.illinois.gov/api/views/q25t-cxmv) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/q25t-cxmv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/q25t-cxmv/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | q25t-cxmv |
| Name | IDHS FY 03 CASELOADS |
| Category | Social/Healthcare |
| Created | 2011-11-03T11:34:16Z |
| Publication Date | 2011-11-03T11:37:01Z |

## Description

FY 03 CASELOADS

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type | Render Type |
| ======== | ============== | =========================== | =========================== | ========= | =========== |
| No       | time           | :updated_at                 | updated_at                  | meta_data | meta_data   |
| Yes      | series tag     | fy_2003                     | FY 2003                     | text      | text        |
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
series e:q25t-cxmv d:2011-11-03T04:34:18.000Z t:fy_2003=July m:total=878666 m:general_assist_family=737 m:tanf=46801 m:mang=706579 m:aabd=36976 m:general_assist_transitional=6162 m:refugee=78 m:total_food_stamps=387445 m:non_assist_food_stamps=81411

series e:q25t-cxmv d:2011-11-03T04:34:18.000Z t:fy_2003=August m:total=880431 m:general_assist_family=735 m:tanf=46836 m:mang=705492 m:aabd=36884 m:general_assist_transitional=6132 m:refugee=70 m:total_food_stamps=405145 m:non_assist_food_stamps=84352

series e:q25t-cxmv d:2011-11-03T04:34:18.000Z t:fy_2003=September m:total=888882 m:general_assist_family=729 m:tanf=46180 m:mang=714925 m:aabd=36715 m:general_assist_transitional=6261 m:refugee=178 m:total_food_stamps=406289 m:non_assist_food_stamps=84072
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

entity e:q25t-cxmv l:"IDHS FY 03 CASELOADS" t:url=https://data.illinois.gov/api/views/q25t-cxmv

property e:q25t-cxmv t:meta.view v:id=q25t-cxmv v:category=Social/Healthcare v:averageRating=0 v:name="IDHS FY 03 CASELOADS"

property e:q25t-cxmv t:meta.view.owner v:id=e9y5-49nr v:screenName="Carl Awe" v:displayName="Carl Awe"

property e:q25t-cxmv t:meta.view.tableauthor v:id=e9y5-49nr v:screenName="Carl Awe" v:displayName="Carl Awe"
```

## Top Records

```ls
| :updated_at | fy_2003   | mang   | general_assist_transitional | general_assist_family | tanf  | non_assist_food_stamps | aabd  | total  | refugee | total_food_stamps | 
| =========== | ========= | ====== | =========================== | ===================== | ===== | ====================== | ===== | ====== | ======= | ================= | 
| 1320294858  | July      | 706579 | 6162                        | 737                   | 46801 | 81411                  | 36976 | 878666 | 78      | 387445            | 
| 1320294858  | August    | 705492 | 6132                        | 735                   | 46836 | 84352                  | 36884 | 880431 | 70      | 405145            | 
| 1320294858  | September | 714925 | 6261                        | 729                   | 46180 | 84072                  | 36715 | 888882 | 178     | 406289            | 
| 1320294858  | October   | 722616 | 6115                        | 725                   | 44510 | 83006                  | 36610 | 893582 | 185     | 400370            | 
| 1320294858  | November  | 732940 | 6029                        | 726                   | 44589 | 85130                  | 36377 | 905791 | 181     | 408584            | 
| 1320294858  | December  | 739290 | 6080                        | 720                   | 44740 | 87931                  | 36345 | 915106 | 184     | 417483            | 
| 1320294858  | January   | 744594 | 5603                        | 717                   | 42918 | 87028                  | 36186 | 917046 | 181     | 407994            | 
| 1320294858  | February  | 747448 | 5594                        | 724                   | 42525 | 88994                  | 35953 | 921238 | 156     | 414232            | 
| 1320294858  | March     | 752642 | 5585                        | 717                   | 41745 | 92042                  | 35761 | 928492 | 161     | 423955            | 
| 1320294858  | April     | 756792 | 5652                        | 720                   | 40002 | 90492                  | 35672 | 929330 | 154     | 417293            | 
```