# IDHS FY 07 CASELOADS

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idhs-fy-07-caseloads-a8a16) |
| Metadata | [Link](https://data.illinois.gov/api/views/py87-uhf3) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/py87-uhf3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/py87-uhf3/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | py87-uhf3 |
| Name | IDHS FY 07 CASELOADS |
| Category | Social/Healthcare |
| Created | 2011-11-03T12:07:47Z |
| Publication Date | 2011-11-03T12:11:08Z |

## Description

FY 07 CASELOADS

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type | Render Type |
| ======== | ============== | =========================== | =========================== | ========= | =========== |
| No       | time           | :updated_at                 | updated_at                  | meta_data | meta_data   |
| Yes      | series tag     | fy_2007                     | FY 2007                     | text      | text        |
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
series e:py87-uhf3 d:2011-11-03T05:07:49.000Z t:fy_2007=July m:total=1323564 m:general_assist_family=807 m:tanf=38493 m:mang=905788 m:aabd=31167 m:general_assist_transitional=6747 m:refugee=262 m:total_food_stamps=556648 m:non_assist_food_stamps=134413

series e:py87-uhf3 d:2011-11-03T05:07:49.000Z t:fy_2007=August m:total=1334812 m:general_assist_family=822 m:tanf=38096 m:mang=909977 m:aabd=31161 m:general_assist_transitional=6895 m:refugee=234 m:total_food_stamps=563723 m:non_assist_food_stamps=136795

series e:py87-uhf3 d:2011-11-03T05:07:49.000Z t:fy_2007=September m:total=1335368 m:general_assist_family=819 m:tanf=37593 m:mang=915850 m:aabd=31104 m:general_assist_transitional=6800 m:refugee=232 m:total_food_stamps=564241 m:non_assist_food_stamps=136622
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

entity e:py87-uhf3 l:"IDHS FY 07 CASELOADS" t:url=https://data.illinois.gov/api/views/py87-uhf3

property e:py87-uhf3 t:meta.view v:id=py87-uhf3 v:category=Social/Healthcare v:averageRating=0 v:name="IDHS FY 07 CASELOADS"

property e:py87-uhf3 t:meta.view.owner v:id=e9y5-49nr v:screenName="Carl Awe" v:displayName="Carl Awe"

property e:py87-uhf3 t:meta.view.tableauthor v:id=e9y5-49nr v:screenName="Carl Awe" v:displayName="Carl Awe"
```

## Top Records

```ls
| :updated_at | fy_2007   | mang   | general_assist_transitional | general_assist_family | tanf  | non_assist_food_stamps | aabd  | total   | refugee | total_food_stamps | 
| =========== | ========= | ====== | =========================== | ===================== | ===== | ====================== | ===== | ======= | ======= | ================= | 
| 1320296869  | July      | 905788 | 6747                        | 807                   | 38493 | 134413                 | 31167 | 1323564 | 262     | 556648            | 
| 1320296869  | August    | 909977 | 6895                        | 822                   | 38096 | 136795                 | 31161 | 1334812 | 234     | 563723            | 
| 1320296869  | September | 915850 | 6800                        | 819                   | 37593 | 136622                 | 31104 | 1335368 | 232     | 564241            | 
| 1320296869  | October   | 923325 | 6873                        | 815                   | 37490 | 137117                 | 31039 | 1136659 | 241     | 560925            | 
| 1320296869  | November  | 930218 | 7039                        | 826                   | 37168 | 138375                 | 30974 | 1144600 | 205     | 566902            | 
| 1320296869  | December  | 936714 | 7066                        | 821                   | 36997 | 139883                 | 30901 | 1152382 | 186     | 573310            | 
| 1320296869  | January   | 941425 | 7222                        | 816                   | 36704 | 139989                 | 30826 | 1156982 | 182     | 566589            | 
| 1320296869  | February  | 944246 | 7267                        | 801                   | 35714 | 137645                 | 30655 | 1156328 | 205     | 562543            | 
| 1320296869  | March     | 951064 | 7449                        | 813                   | 35118 | 140358                 | 30633 | 1165435 | 204     | 571148            | 
| 1320296869  | April     | 954740 | 7601                        | 821                   | 33905 | 139070                 | 30583 | 1166720 | 215     | 561799            | 
```