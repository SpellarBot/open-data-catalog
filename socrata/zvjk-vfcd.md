# IDHS FY 00 CASELOADS

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idhs-fy-00-caseloads-ae58e) |
| Metadata | [Link](https://data.illinois.gov/api/views/zvjk-vfcd) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/zvjk-vfcd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/zvjk-vfcd/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | zvjk-vfcd |
| Name | IDHS FY 00 CASELOADS |
| Category | Social/Healthcare |
| Created | 2011-11-02T19:03:43Z |
| Publication Date | 2011-11-02T19:07:06Z |

## Description

FY 00 CASELOADS

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type | Render Type |
| ======== | ============== | =========================== | =========================== | ========= | =========== |
| No       | time           | :updated_at                 | updated_at                  | meta_data | meta_data   |
| Yes      | series tag     | fy_2000                     | FY 2000                     | text      | text        |
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
series e:zvjk-vfcd d:2011-11-02T12:03:46.000Z t:fy_2000=July m:total=774949 m:general_assist_family=612 m:tanf=106643 m:mang=550810 m:aabd=40496 m:general_assist_transitional=6462 m:refugee=420 m:total_food_stamps=345053 m:non_assist_food_stamps=69926

series e:zvjk-vfcd d:2011-11-02T12:03:46.000Z t:fy_2000=August m:total=778268 m:general_assist_family=612 m:tanf=107546 m:mang=554227 m:aabd=40382 m:general_assist_transitional=6358 m:refugee=483 m:total_food_stamps=344155 m:non_assist_food_stamps=69143

series e:zvjk-vfcd d:2011-11-02T12:03:46.000Z t:fy_2000=September m:total=783396 m:general_assist_family=605 m:tanf=106779 m:mang=560555 m:aabd=40409 m:general_assist_transitional=6290 m:refugee=486 m:total_food_stamps=342885 m:non_assist_food_stamps=68758
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

entity e:zvjk-vfcd l:"IDHS FY 00 CASELOADS" t:url=https://data.illinois.gov/api/views/zvjk-vfcd

property e:zvjk-vfcd t:meta.view v:id=zvjk-vfcd v:category=Social/Healthcare v:averageRating=0 v:name="IDHS FY 00 CASELOADS"

property e:zvjk-vfcd t:meta.view.owner v:id=e9y5-49nr v:screenName="Carl Awe" v:displayName="Carl Awe"

property e:zvjk-vfcd t:meta.view.tableauthor v:id=e9y5-49nr v:screenName="Carl Awe" v:displayName="Carl Awe"
```

## Top Records

```ls
| :updated_at | fy_2000   | mang   | general_assist_transitional | general_assist_family | tanf   | non_assist_food_stamps | aabd  | total  | refugee | total_food_stamps | 
| =========== | ========= | ====== | =========================== | ===================== | ====== | ====================== | ===== | ====== | ======= | ================= | 
| 1320235426  | July      | 550810 | 6462                        | 612                   | 106643 | 69926                  | 40496 | 774949 | 420     | 345053            | 
| 1320235426  | August    | 554227 | 6358                        | 612                   | 107546 | 69143                  | 40382 | 778268 | 483     | 344155            | 
| 1320235426  | September | 560555 | 6290                        | 605                   | 106779 | 68758                  | 40409 | 783396 | 486     | 342885            | 
| 1320235426  | October   | 568599 | 6194                        | 610                   | 98729  | 69721                  | 40268 | 784121 | 510     | 340124            | 
| 1320235426  | November  | 576110 | 6159                        | 628                   | 100266 | 70822                  | 40292 | 794277 | 513     | 343949            | 
| 1320235426  | December  | 585209 | 6146                        | 636                   | 100244 | 76205                  | 40389 | 808829 | 518     | 362074            | 
| 1320235426  | January   | 589629 | 6107                        | 648                   | 93074  | 50475                  | 40330 | 780263 | 469     | 147457            | 
| 1320235426  | February  | 593631 | 5977                        | 647                   | 94092  | 76510                  | 40318 | 811175 | 432     | 346359            | 
| 1320235426  | March     | 601177 | 5849                        | 625                   | 93712  | 80322                  | 40331 | 822016 | 451     | 357289            | 
| 1320235426  | April     | 606653 | 5847                        | 605                   | 88702  | 80498                  | 40304 | 822609 | 400     | 354639            | 
```