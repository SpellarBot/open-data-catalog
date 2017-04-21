# IDHS FY 99 CASELOADS

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idhs-fy-99-caseloads-1fe22) |
| Metadata | [Link](https://data.illinois.gov/api/views/j3ki-3isk) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/j3ki-3isk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/j3ki-3isk/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | j3ki-3isk |
| Name | IDHS FY 99 CASELOADS |
| Category | Social/Healthcare |
| Created | 2011-11-02T18:59:29Z |
| Publication Date | 2011-11-02T19:02:59Z |

## Description

FY 99 CASELOADS

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type | Render Type |
| ======== | ============== | =========================== | =========================== | ========= | =========== |
| No       | time           | :updated_at                 | updated_at                  | meta_data | meta_data   |
| Yes      | series tag     | fy_1999                     | FY 1999                     | text      | text        |
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
series e:j3ki-3isk d:2011-11-02T11:59:32.000Z t:fy_1999=July m:total=763234 m:general_assist_family=639 m:tanf=154272 m:mang=487001 m:aabd=42070 m:general_assist_transitional=7883 m:refugee=598 m:total_food_stamps=373045 m:non_assist_food_stamps=71369

series e:j3ki-3isk d:2011-11-02T11:59:32.000Z t:fy_1999=August m:total=765780 m:general_assist_family=630 m:tanf=154925 m:mang=490163 m:aabd=41917 m:general_assist_transitional=7704 m:refugee=520 m:total_food_stamps=372406 m:non_assist_food_stamps=70441

series e:j3ki-3isk d:2011-11-02T11:59:32.000Z t:fy_1999=September m:total=764592 m:general_assist_family=616 m:tanf=152165 m:mang=493763 m:aabd=41788 m:general_assist_transitional=7526 m:refugee=474 m:total_food_stamps=366333 m:non_assist_food_stamps=68734
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

entity e:j3ki-3isk l:"IDHS FY 99 CASELOADS" t:url=https://data.illinois.gov/api/views/j3ki-3isk

property e:j3ki-3isk t:meta.view v:id=j3ki-3isk v:category=Social/Healthcare v:averageRating=0 v:name="IDHS FY 99 CASELOADS"

property e:j3ki-3isk t:meta.view.owner v:id=e9y5-49nr v:screenName="Carl Awe" v:displayName="Carl Awe"

property e:j3ki-3isk t:meta.view.tableauthor v:id=e9y5-49nr v:screenName="Carl Awe" v:displayName="Carl Awe"
```

## Top Records

```ls
| :updated_at | fy_1999   | mang   | general_assist_transitional | general_assist_family | tanf   | non_assist_food_stamps | aabd  | total  | refugee | total_food_stamps | 
| =========== | ========= | ====== | =========================== | ===================== | ====== | ====================== | ===== | ====== | ======= | ================= | 
| 1320235172  | July      | 487001 | 7883                        | 639                   | 154272 | 71369                  | 42070 | 763234 | 598     | 373045            | 
| 1320235172  | August    | 490163 | 7704                        | 630                   | 154925 | 70441                  | 41917 | 765780 | 520     | 372406            | 
| 1320235172  | September | 493763 | 7526                        | 616                   | 152165 | 68734                  | 41788 | 764592 | 474     | 366333            | 
| 1320235172  | October   | 498814 | 7398                        | 629                   | 143259 | 68233                  | 41677 | 760010 | 506     | 359731            | 
| 1320235172  | November  | 505572 | 7145                        | 609                   | 141842 | 65977                  | 41426 | 762571 | 499     | 357249            | 
| 1320235172  | December  | 509014 | 7008                        | 618                   | 139806 | 67195                  | 41497 | 765138 | 509     | 359910            | 
| 1320235172  | January   | 516135 | 6836                        | 606                   | 131737 | 66970                  | 41370 | 763654 | 537     | 351761            | 
| 1320235172  | February  | 519240 | 6702                        | 603                   | 130641 | 66833                  | 41075 | 765094 | 507     | 348033            | 
| 1320235172  | March     | 522932 | 6732                        | 618                   | 128700 | 70133                  | 41050 | 770165 | 484     | 357158            | 
| 1320235172  | April     | 531430 | 6655                        | 614                   | 118051 | 71152                  | 40587 | 768489 | 417     | 353825            | 
```