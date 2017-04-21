# IDHS FY 97 Caseloads

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idhs-fy-97-caseloads-02a7f) |
| Metadata | [Link](https://data.illinois.gov/api/views/xavn-jzvd) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/xavn-jzvd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/xavn-jzvd/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | xavn-jzvd |
| Name | IDHS FY 97 Caseloads |
| Category | Social/Healthcare |
| Created | 2011-11-02T18:50:28Z |
| Publication Date | 2011-11-02T18:55:04Z |

## Description

FY 97 Caseloads

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type | Render Type |
| ======== | ============== | =========================== | =========================== | ========= | =========== |
| No       | time           | :updated_at                 | updated_at                  | meta_data | meta_data   |
| Yes      | series tag     | fy_1997                     | FY 1997                     | text      | text        |
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
series e:xavn-jzvd d:2011-11-02T11:50:30.000Z t:fy_1997=July m:total=809568 m:general_assist_family=1120 m:tanf=227943 m:mang=439602 m:aabd=50199 m:general_assist_transitional=8067 m:refugee=722 m:total_food_stamps=464137 m:non_assist_food_stamps=82637

series e:xavn-jzvd d:2011-11-02T11:50:30.000Z t:fy_1997=August m:total=809837 m:general_assist_family=1110 m:tanf=227515 m:mang=440304 m:aabd=50021 m:general_assist_transitional=7985 m:refugee=606 m:total_food_stamps=464124 m:non_assist_food_stamps=82902

series e:xavn-jzvd d:2011-11-02T11:50:30.000Z t:fy_1997=September m:total=808563 m:general_assist_family=1138 m:tanf=225387 m:mang=441964 m:aabd=49882 m:general_assist_transitional=7869 m:refugee=581 m:total_food_stamps=461211 m:non_assist_food_stamps=82323
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

entity e:xavn-jzvd l:"IDHS FY 97 Caseloads" t:url=https://data.illinois.gov/api/views/xavn-jzvd

property e:xavn-jzvd t:meta.view v:id=xavn-jzvd v:category=Social/Healthcare v:averageRating=0 v:name="IDHS FY 97 Caseloads"

property e:xavn-jzvd t:meta.view.owner v:id=e9y5-49nr v:screenName="Carl Awe" v:displayName="Carl Awe"

property e:xavn-jzvd t:meta.view.tableauthor v:id=e9y5-49nr v:screenName="Carl Awe" v:displayName="Carl Awe"
```

## Top Records

```ls
| :updated_at | fy_1997   | mang   | general_assist_transitional | general_assist_family | tanf   | non_assist_food_stamps | aabd  | total  | refugee | total_food_stamps | 
| =========== | ========= | ====== | =========================== | ===================== | ====== | ====================== | ===== | ====== | ======= | ================= | 
| 1320234630  | July      | 439602 | 8067                        | 1120                  | 227943 | 82637                  | 50199 | 809568 | 722     | 464137            | 
| 1320234630  | August    | 440304 | 7985                        | 1110                  | 227515 | 82902                  | 50021 | 809837 | 606     | 464124            | 
| 1320234630  | September | 441964 | 7869                        | 1138                  | 225387 | 82323                  | 49882 | 808563 | 581     | 461211            | 
| 1320234630  | October   | 444529 | 7784                        | 1150                  | 221755 | 81978                  | 49658 | 806854 | 649     | 455267            | 
| 1320234630  | November  | 447426 | 7609                        | 1095                  | 216845 | 82385                  | 49308 | 804668 | 622     | 453150            | 
| 1320234630  | December  | 449084 | 7590                        | 1096                  | 217561 | 83134                  | 49250 | 807715 | 649     | 451788            | 
| 1320234630  | January   | 452031 | 7468                        | 1037                  | 213054 | 83160                  | 48818 | 805568 | 692     | 447875            | 
| 1320234630  | February  | 443847 | 7440                        | 1041                  | 206690 | 84919                  | 45881 | 789818 | 695     | 438263            | 
| 1320234630  | March     | 445098 | 7463                        | 1048                  | 208490 | 84073                  | 46016 | 792188 | 680     | 436294            | 
| 1320234630  | April     | 467245 | 7666                        | 1022                  | 201942 | 84251                  | 47477 | 809603 | 629     | 430426            | 
```