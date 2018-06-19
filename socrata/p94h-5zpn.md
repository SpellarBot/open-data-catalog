# IDHS FY 02 CASELOADS

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idhs-fy-02-caseloads-4389e) |
| Metadata | [Link](https://data.illinois.gov/api/views/p94h-5zpn) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/p94h-5zpn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/p94h-5zpn/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | p94h-5zpn |
| Name | IDHS FY 02 CASELOADS |
| Category | Social/Healthcare |
| Created | 2011-11-02T19:19:48Z |
| Publication Date | 2011-11-02T19:23:18Z |

## Description

FY 02 CASELOADS

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type | Render Type |
| ======== | ============== | =========================== | =========================== | ========= | =========== |
| No       | time           | :updated_at                 | updated_at                  | meta_data | meta_data   |
| Yes      | series tag     | fy_2002                     | FY 2002                     | text      | text        |
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
series e:p94h-5zpn d:2011-11-02T12:19:51.000Z t:fy_2002=July m:total=859268 m:general_assist_family=754 m:tanf=60800 m:mang=672686 m:aabd=38937 m:general_assist_transitional=6042 m:refugee=418 m:total_food_stamps=355969 m:non_assist_food_stamps=80049

series e:p94h-5zpn d:2011-11-02T12:19:51.000Z t:fy_2002=August m:total=898087 m:general_assist_family=751 m:tanf=61812 m:mang=707740 m:aabd=38987 m:general_assist_transitional=6041 m:refugee=455 m:total_food_stamps=373987 m:non_assist_food_stamps=82756

series e:p94h-5zpn d:2011-11-02T12:19:51.000Z t:fy_2002=September m:total=902578 m:general_assist_family=761 m:tanf=60727 m:mang=714571 m:aabd=38773 m:general_assist_transitional=6103 m:refugee=443 m:total_food_stamps=376495 m:non_assist_food_stamps=81643
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

entity e:p94h-5zpn l:"IDHS FY 02 CASELOADS" t:url=https://data.illinois.gov/api/views/p94h-5zpn

property e:p94h-5zpn t:meta.view v:id=p94h-5zpn v:category=Social/Healthcare v:averageRating=0 v:name="IDHS FY 02 CASELOADS"

property e:p94h-5zpn t:meta.view.owner v:id=e9y5-49nr v:screenName="Carl Awe" v:displayName="Carl Awe"

property e:p94h-5zpn t:meta.view.tableauthor v:id=e9y5-49nr v:screenName="Carl Awe" v:displayName="Carl Awe"
```

## Top Records

```ls
| :updated_at | fy_2002   | mang   | general_assist_transitional | general_assist_family | tanf  | non_assist_food_stamps | aabd  | total  | refugee | total_food_stamps | 
| =========== | ========= | ====== | =========================== | ===================== | ===== | ====================== | ===== | ====== | ======= | ================= | 
| 1320236391  | July      | 672686 | 6042                        | 754                   | 60800 | 80049                  | 38937 | 859268 | 418     | 355969            | 
| 1320236391  | August    | 707740 | 6041                        | 751                   | 61812 | 82756                  | 38987 | 898087 | 455     | 373987            | 
| 1320236391  | September | 714571 | 6103                        | 761                   | 60727 | 81643                  | 38773 | 902578 | 443     | 376495            | 
| 1320236391  | October   | 721572 | 6128                        | 766                   | 58077 | 79131                  | 38737 | 904411 | 504     | 367826            | 
| 1320236391  | November  | 727072 | 6137                        | 759                   | 58393 | 81946                  | 38574 | 912881 | 431     | 382225            | 
| 1320236391  | December  | 729077 | 6234                        | 766                   | 58309 | 84353                  | 38388 | 917127 | 394     | 392131            | 
| 1320236391  | January   | 729314 | 6367                        | 774                   | 55615 | 83025                  | 38266 | 913361 | 350     | 384143            | 
| 1320236391  | February  | 726496 | 6302                        | 771                   | 54985 | 84016                  | 38011 | 910581 | 288     | 388792            | 
| 1320236391  | March     | 719728 | 6374                        | 773                   | 54366 | 86964                  | 37808 | 906013 | 281     | 400963            | 
| 1320236391  | April     | 711408 | 6385                        | 768                   | 51312 | 83307                  | 37760 | 890940 | 252     | 386974            | 
```