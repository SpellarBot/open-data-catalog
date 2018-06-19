# IDHS FY 08 CASELOADS

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idhs-fy-08-caseloads-b23a5) |
| Metadata | [Link](https://data.illinois.gov/api/views/bir6-3vcv) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/bir6-3vcv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/bir6-3vcv/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | bir6-3vcv |
| Name | IDHS FY 08 CASELOADS |
| Category | Social/Healthcare |
| Created | 2011-11-03T12:14:22Z |
| Publication Date | 2011-11-03T12:17:27Z |

## Description

FY 08 CASELOADS

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type | Render Type |
| ======== | ============== | =========================== | =========================== | ========= | =========== |
| No       | time           | :updated_at                 | updated_at                  | meta_data | meta_data   |
| Yes      | series tag     | fy_2008                     | FY 2008                     | text      | text        |
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
series e:bir6-3vcv d:2011-11-03T05:14:24.000Z t:fy_2008=July m:total=1193142 m:general_assist_family=818 m:tanf=31139 m:mang=981643 m:aabd=30440 m:general_assist_transitional=7864 m:refugee=223 m:total_food_stamps=568935 m:non_assist_food_stamps=141238

series e:bir6-3vcv d:2011-11-03T05:14:24.000Z t:fy_2008=August m:total=1201145 m:general_assist_family=818 m:tanf=30449 m:mang=987585 m:aabd=30436 m:general_assist_transitional=7958 m:refugee=227 m:total_food_stamps=581762 m:non_assist_food_stamps=143899

series e:bir6-3vcv d:2011-11-03T05:14:24.000Z t:fy_2008=September m:total=1205246 m:general_assist_family=814 m:tanf=29439 m:mang=993772 m:aabd=30336 m:general_assist_transitional=7789 m:refugee=260 m:total_food_stamps=580165 m:non_assist_food_stamps=143096
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

entity e:bir6-3vcv l:"IDHS FY 08 CASELOADS" t:url=https://data.illinois.gov/api/views/bir6-3vcv

property e:bir6-3vcv t:meta.view v:id=bir6-3vcv v:category=Social/Healthcare v:averageRating=0 v:name="IDHS FY 08 CASELOADS"

property e:bir6-3vcv t:meta.view.owner v:id=e9y5-49nr v:screenName="Carl Awe" v:displayName="Carl Awe"

property e:bir6-3vcv t:meta.view.tableauthor v:id=e9y5-49nr v:screenName="Carl Awe" v:displayName="Carl Awe"
```

## Top Records

```ls
| :updated_at | fy_2008   | mang    | general_assist_transitional | general_assist_family | tanf  | non_assist_food_stamps | aabd  | total   | refugee | total_food_stamps | 
| =========== | ========= | ======= | =========================== | ===================== | ===== | ====================== | ===== | ======= | ======= | ================= | 
| 1320297264  | July      | 981643  | 7864                        | 818                   | 31139 | 141238                 | 30440 | 1193142 | 223     | 568935            | 
| 1320297264  | August    | 987585  | 7958                        | 818                   | 30449 | 143899                 | 30436 | 1201145 | 227     | 581762            | 
| 1320297264  | September | 993772  | 7789                        | 814                   | 29439 | 143096                 | 30336 | 1205246 | 260     | 580165            | 
| 1320297264  | October   | 1000861 | 7689                        | 801                   | 29037 | 144846                 | 30296 | 1213530 | 355     | 581844            | 
| 1320297264  | November  | 1005801 | 7814                        | 831                   | 28426 | 145529                 | 30235 | 1218636 | 338     | 585751            | 
| 1320297264  | December  | 1012705 | 7625                        | 828                   | 28436 | 146529                 | 30205 | 1226328 | 308     | 589819            | 
| 1320297264  | January   | 1015862 | 7743                        | 840                   | 28220 | 148308                 | 30146 | 1231119 | 284     | 591004            | 
| 1320297264  | February  | 1018699 | 7699                        | 840                   | 27656 | 147496                 | 30028 | 1232418 | 277     | 589899            | 
| 1320297264  | March     | 1022255 | 7683                        | 838                   | 27292 | 148734                 | 29875 | 1236677 | 265     | 592390            | 
| 1320297264  | April     | 1024698 | 7831                        | 843                   | 27043 | 148628                 | 29792 | 1238835 | 284     | 594590            | 
```