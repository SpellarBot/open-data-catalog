# IDHS FY 96 CASELOADS

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idhs-fy-96-caseloads-ac6f6) |
| Metadata | [Link](https://data.illinois.gov/api/views/xdud-s82f) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/xdud-s82f/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/xdud-s82f/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | xdud-s82f |
| Name | IDHS FY 96 CASELOADS |
| Category | Social/Healthcare |
| Created | 2011-11-02T18:46:21Z |
| Publication Date | 2011-11-02T18:49:55Z |

## Description

FY 96 CASELOADS

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                            | Data Type | Render Type |
| ======== | ============== | =============================== | =============================== | ========= | =========== |
| No       | time           | :updated_at                     | updated_at                      | meta_data | meta_data   |
| Yes      | series tag     | fy_1996                         | FY 1996                         | text      | text        |
| Yes      | numeric metric | mang                            | MANG                            | number    | number      |
| Yes      | numeric metric | general_assistance_transitional | GENERAL ASSISTANCE TRANSITIONAL | number    | number      |
| Yes      | numeric metric | general_assistance_family       | GENERAL ASSISTANCE FAMILY       | number    | number      |
| Yes      | numeric metric | tanf                            | TANF                            | number    | number      |
| Yes      | numeric metric | non_asst_food_stamps            | NON-ASST FOOD STAMPS            | number    | number      |
| Yes      | numeric metric | aabd                            | AABD                            | number    | number      |
| Yes      | numeric metric | total                           | TOTAL                           | number    | number      |
| Yes      | numeric metric | refugee                         | REFUGEE                         | number    | number      |
| Yes      | numeric metric | total_food_stamps               | TOTAL FOOD STAMPS               | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:xdud-s82f d:2011-11-02T11:46:24.000Z t:fy_1996=July m:total=836406 m:general_assistance_family=1179 m:tanf=238112 m:mang=446538 m:non_asst_food_stamps=70377 m:aabd=73060 m:refugee=856 m:general_assistance_transitional=7140 m:total_food_stamps=478837

series e:xdud-s82f d:2011-11-02T11:46:24.000Z t:fy_1996=August m:total=834176 m:general_assistance_family=1166 m:tanf=237565 m:mang=446327 m:non_asst_food_stamps=70104 m:aabd=71945 m:refugee=857 m:general_assistance_transitional=7069 m:total_food_stamps=478220

series e:xdud-s82f d:2011-11-02T11:46:24.000Z t:fy_1996=September m:total=814113 m:general_assistance_family=1167 m:tanf=236539 m:mang=446704 m:non_asst_food_stamps=70728 m:aabd=51211 m:refugee=884 m:general_assistance_transitional=7764 m:total_food_stamps=477479
```

## Meta Commands

```ls
metric m:mang p:double l:MANG t:dataTypeName=number

metric m:general_assistance_transitional p:double l:"GENERAL ASSISTANCE TRANSITIONAL" t:dataTypeName=number

metric m:general_assistance_family p:double l:"GENERAL ASSISTANCE FAMILY" t:dataTypeName=number

metric m:tanf p:double l:TANF t:dataTypeName=number

metric m:non_asst_food_stamps p:double l:"NON-ASST FOOD STAMPS" t:dataTypeName=number

metric m:aabd p:double l:AABD t:dataTypeName=number

metric m:total p:double l:TOTAL t:dataTypeName=number

metric m:refugee p:double l:REFUGEE t:dataTypeName=number

metric m:total_food_stamps p:double l:"TOTAL FOOD STAMPS" t:dataTypeName=number

entity e:xdud-s82f l:"IDHS FY 96 CASELOADS" t:url=https://data.illinois.gov/api/views/xdud-s82f

property e:xdud-s82f t:meta.view v:id=xdud-s82f v:category=Social/Healthcare v:averageRating=0 v:name="IDHS FY 96 CASELOADS"

property e:xdud-s82f t:meta.view.owner v:id=e9y5-49nr v:screenName="Carl Awe" v:displayName="Carl Awe"

property e:xdud-s82f t:meta.view.tableauthor v:id=e9y5-49nr v:screenName="Carl Awe" v:displayName="Carl Awe"
```

## Top Records

```ls
| :updated_at | fy_1996   | mang   | general_assistance_transitional | general_assistance_family | tanf   | non_asst_food_stamps | aabd  | total  | refugee | total_food_stamps | 
| =========== | ========= | ====== | =============================== | ========================= | ====== | ==================== | ===== | ====== | ======= | ================= | 
| 1320234384  | July      | 446538 | 7140                            | 1179                      | 238112 | 70377                | 73060 | 836406 | 856     | 478837            | 
| 1320234384  | August    | 446327 | 7069                            | 1166                      | 237565 | 70104                | 71945 | 834176 | 857     | 478220            | 
| 1320234384  | September | 446704 | 7764                            | 1167                      | 236539 | 70728                | 51211 | 814113 | 884     | 477479            | 
| 1320234384  | October   | 428529 | 8189                            | 1163                      | 235052 | 72077                | 51212 | 796222 | 932     | 472323            | 
| 1320234384  | November  | 426815 | 8339                            | 1197                      | 234861 | 73691                | 51352 | 796255 | 1018    | 470581            | 
| 1320234384  | December  | 425014 | 8390                            | 1194                      | 234572 | 76570                | 51327 | 797067 | 1028    | 473127            | 
| 1320234384  | January   | 425650 | 8354                            | 1181                      | 233664 | 78693                | 51337 | 798879 | 1032    | 473732            | 
| 1320234384  | February  | 426536 | 8217                            | 1158                      | 233721 | 79678                | 51159 | 800469 | 987     | 470570            | 
| 1320234384  | March     | 427999 | 8181                            | 1173                      | 234353 | 81564                | 50933 | 804203 | 1000    | 473239            | 
| 1320234384  | April     | 429611 | 8253                            | 1162                      | 233224 | 82474                | 50860 | 805584 | 940     | 472343            | 
```