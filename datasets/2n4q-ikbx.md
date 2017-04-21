# Household Population Projections for Non-Hispanic White and All Other by Age, Sex and Race

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/household-population-projections-for-non-hispanic-white-and-all-other-by-age-sex-and-race-fd0be) |
| Metadata | [Link](https://data.maryland.gov/api/views/2n4q-ikbx) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/2n4q-ikbx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/2n4q-ikbx/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 2n4q-ikbx |
| Name | Household Population Projections for Non-Hispanic White and All Other by Age, Sex and Race |
| Attribution | Maryland Department of Planning |
| Tags | population, household age, sex, race, projections, planning, mdp |
| Created | 2014-04-01T20:22:39Z |
| Publication Date | 2014-08-26T15:45:39Z |

## Description

Household Population Projections for Maryland and the jurisdictions - by age, sex and race projections out to 2040. Projections prepared by the Maryland Department of Planning, July 2014

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | series tag     | jurisdiction | Jurisdiction | text      | text        |
| Yes      | time           | year         | Year         | number    | text        |
| Yes      | series tag     | category     | Category     | text      | text        |
| Yes      | numeric metric | 0_4          | 0-4          | number    | number      |
| Yes      | numeric metric | 5_9          | 5-9          | number    | number      |
| Yes      | numeric metric | 10_14        | 10-14        | number    | number      |
| Yes      | numeric metric | 15_19        | 15-19        | number    | number      |
| Yes      | numeric metric | 20_24        | 20-24        | number    | number      |
| Yes      | numeric metric | 25_29        | 25-29        | number    | number      |
| Yes      | numeric metric | 30_34        | 30-34        | number    | number      |
| Yes      | numeric metric | 35_39        | 35-39        | number    | number      |
| Yes      | numeric metric | 40_44        | 40-44        | number    | number      |
| Yes      | numeric metric | 45_49        | 45-49        | number    | number      |
| Yes      | numeric metric | 50_54        | 50-54        | number    | number      |
| Yes      | numeric metric | 55_59        | 55-59        | number    | number      |
| Yes      | numeric metric | 60_64        | 60-64        | number    | number      |
| Yes      | numeric metric | 65_69        | 65-69        | number    | number      |
| Yes      | numeric metric | 70_74        | 70-74        | number    | number      |
| Yes      | numeric metric | 75_79        | 75-79        | number    | number      |
| Yes      | numeric metric | 80_84        | 80-84        | number    | number      |
| Yes      | numeric metric | _85          | 85+          | number    | number      |
| Yes      | numeric metric | total        | Total        | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:2n4q-ikbx d:2010-01-01T00:00:00.000Z t:category=Total t:jurisdiction="State of Maryland" m:45_49=455453 m:total=5635177 m:60_64=314837 m:25_29=384475 m:80_84=93340 m:20_24=361721 m:_85=85283 m:30_34=361859 m:50_54=435419 m:35_39=371760 m:5_9=366390 m:0_4=363828 m:40_44=412045 m:65_69=224108 m:55_59=374190 m:10_14=378312 m:70_74=157054 m:15_19=374039 m:75_79=121064

series e:2n4q-ikbx d:2010-01-01T00:00:00.000Z t:category="Total Male" t:jurisdiction="State of Maryland" m:45_49=216949 m:total=2709943 m:60_64=148079 m:25_29=186461 m:80_84=36759 m:20_24=180595 m:_85=28343 m:30_34=173469 m:50_54=207093 m:35_39=176722 m:5_9=186627 m:0_4=185585 m:40_44=195781 m:65_69=103573 m:55_59=176329 m:10_14=192617 m:70_74=70905 m:15_19=192223 m:75_79=51833

series e:2n4q-ikbx d:2010-01-01T00:00:00.000Z t:category="Total Female" t:jurisdiction="State of Maryland" m:45_49=238504 m:total=2925234 m:60_64=166758 m:25_29=198014 m:80_84=56581 m:20_24=181126 m:_85=56940 m:30_34=188390 m:50_54=228326 m:35_39=195038 m:5_9=179763 m:0_4=178243 m:40_44=216264 m:65_69=120535 m:55_59=197861 m:10_14=185695 m:70_74=86149 m:15_19=181816 m:75_79=69231
```

## Meta Commands

```ls
metric m:0_4 p:integer l:0-4 t:dataTypeName=number

metric m:5_9 p:integer l:5-9 t:dataTypeName=number

metric m:10_14 p:integer l:10-14 t:dataTypeName=number

metric m:15_19 p:integer l:15-19 t:dataTypeName=number

metric m:20_24 p:integer l:20-24 t:dataTypeName=number

metric m:25_29 p:integer l:25-29 t:dataTypeName=number

metric m:30_34 p:integer l:30-34 t:dataTypeName=number

metric m:35_39 p:integer l:35-39 t:dataTypeName=number

metric m:40_44 p:integer l:40-44 t:dataTypeName=number

metric m:45_49 p:integer l:45-49 t:dataTypeName=number

metric m:50_54 p:integer l:50-54 t:dataTypeName=number

metric m:55_59 p:integer l:55-59 t:dataTypeName=number

metric m:60_64 p:integer l:60-64 t:dataTypeName=number

metric m:65_69 p:integer l:65-69 t:dataTypeName=number

metric m:70_74 p:integer l:70-74 t:dataTypeName=number

metric m:75_79 p:integer l:75-79 t:dataTypeName=number

metric m:80_84 p:integer l:80-84 t:dataTypeName=number

metric m:_85 p:integer l:85+ t:dataTypeName=number

metric m:total p:integer l:Total t:dataTypeName=number

entity e:2n4q-ikbx l:"Household Population Projections for Non-Hispanic White and All Other by Age, Sex and Race" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/2n4q-ikbx

property e:2n4q-ikbx t:meta.view v:id=2n4q-ikbx v:attributionLink=http://planning.maryland.gov/msdc/S3_Projection.shtml v:averageRating=0 v:name="Household Population Projections for Non-Hispanic White and All Other by Age, Sex and Race" v:attribution="Maryland Department of Planning"

property e:2n4q-ikbx t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:2n4q-ikbx t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| jurisdiction      | year | category              | 0_4    | 5_9    | 10_14  | 15_19  | 20_24  | 25_29  | 30_34  | 35_39  | 40_44  | 45_49  | 50_54  | 55_59  | 60_64  | 65_69  | 70_74  | 75_79  | 80_84 | _85   | total   | 
| ================= | ==== | ===================== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ===== | ===== | ======= | 
| State of Maryland | 2010 | Total                 | 363828 | 366390 | 378312 | 374039 | 361721 | 384475 | 361859 | 371760 | 412045 | 455453 | 435419 | 374190 | 314837 | 224108 | 157054 | 121064 | 93340 | 85283 | 5635177 | 
| State of Maryland | 2010 | Total Male            | 185585 | 186627 | 192617 | 192223 | 180595 | 186461 | 173469 | 176722 | 195781 | 216949 | 207093 | 176329 | 148079 | 103573 | 70905  | 51833  | 36759 | 28343 | 2709943 | 
| State of Maryland | 2010 | Total Female          | 178243 | 179763 | 185695 | 181816 | 181126 | 198014 | 188390 | 195038 | 216264 | 238504 | 228326 | 197861 | 166758 | 120535 | 86149  | 69231  | 56581 | 56940 | 2925234 | 
| State of Maryland | 2010 | Total White Alone     | 155977 | 169758 | 183401 | 180409 | 177270 | 189122 | 170501 | 181942 | 219744 | 263525 | 265364 | 238331 | 207452 | 151959 | 106897 | 86467  | 71595 | 68071 | 3087785 | 
| State of Maryland | 2010 | Non-Hisp White Male   | 79991  | 86692  | 94308  | 93271  | 89308  | 93898  | 84130  | 88429  | 107017 | 129476 | 130321 | 116696 | 101266 | 72418  | 49641  | 38006  | 28848 | 23197 | 1506913 | 
| State of Maryland | 2010 | Non-Hisp White Female | 75986  | 83066  | 89093  | 87138  | 87962  | 95224  | 86371  | 93513  | 112727 | 134049 | 135043 | 121635 | 106186 | 79541  | 57256  | 48461  | 42747 | 44874 | 1580872 | 
| State of Maryland | 2010 | Total All Other       | 207851 | 196632 | 194911 | 193630 | 184451 | 195353 | 191358 | 189818 | 192301 | 191928 | 170055 | 135859 | 107385 | 72149  | 50157  | 34597  | 21745 | 17212 | 2547392 | 
| State of Maryland | 2010 | All Other Male        | 105594 | 99935  | 98309  | 98952  | 91287  | 92563  | 89339  | 88293  | 88764  | 87473  | 76772  | 59633  | 46813  | 31155  | 21264  | 13827  | 7911  | 5146  | 1203030 | 
| State of Maryland | 2010 | All Other Female      | 102257 | 96697  | 96602  | 94678  | 93164  | 102790 | 102019 | 101525 | 103537 | 104455 | 93283  | 76226  | 60572  | 40994  | 28893  | 20770  | 13834 | 12066 | 1344362 | 
| State of Maryland | 2015 | Total                 | 355210 | 366274 | 383155 | 362691 | 383881 | 419807 | 402832 | 372280 | 373534 | 409118 | 449713 | 422541 | 354363 | 288650 | 198618 | 132111 | 91320 | 98031 | 5864129 | 
```