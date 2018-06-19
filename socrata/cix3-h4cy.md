# Census Demographics 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/census-demographics-2010-f7e6b) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/cix3-h4cy) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/cix3-h4cy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/cix3-h4cy/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | cix3-h4cy |
| Name | Census Demographics 2010 |
| Attribution | Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore |
| Category | Neighborhoods |
| Tags | census, demographics |
| Created | 2013-02-26T14:12:41Z |
| Publication Date | 2014-04-03T23:48:11Z |

## Description

BNIA-JFI analyzed data from the Census to provide greater understandingof the socioeconomic and demographic characteristics of the residents of the City and its neighborhoods . BNIA-JFI also used this data as denominators for many of the Vital Signs indicators allowing for data to be normalized and rates to be computed. Census data analyzed by BNIA-JFI is grouped into the following categories: population, race and ethnicity; households and families; and income.

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| Yes      | series tag     | csa2010    | CSA2010    | text      | text        |
| Yes      | numeric metric | totalpop10 | totalpop10 | number    | number      |
| Yes      | numeric metric | male10     | male10     | number    | number      |
| Yes      | numeric metric | female10   | female10   | number    | number      |
| Yes      | numeric metric | peraa10    | peraa10    | number    | number      |
| Yes      | numeric metric | perwhite10 | perwhite10 | number    | number      |
| Yes      | numeric metric | perna10    | perna10    | number    | number      |
| Yes      | numeric metric | perasi10   | perasi10   | number    | number      |
| Yes      | numeric metric | perpac10   | perpac10   | number    | number      |
| Yes      | numeric metric | per2m10    | per2m10    | number    | number      |
| Yes      | numeric metric | perother10 | perother10 | number    | number      |
| Yes      | numeric metric | perhisp10  | perhisp10  | number    | number      |
| Yes      | numeric metric | age1810    | age1810    | number    | number      |
| Yes      | numeric metric | age2410    | age2410    | number    | number      |
| Yes      | numeric metric | age4410    | age4410    | number    | number      |
| Yes      | numeric metric | age6410    | age6410    | number    | number      |
| Yes      | numeric metric | age6510    | age6510    | number    | number      |
| Yes      | numeric metric | hhs10      | hhs10      | number    | number      |
| Yes      | numeric metric | fam10      | fam10      | number    | number      |
| Yes      | numeric metric | hhsize10   | hhsize10   | number    | number      |
| Yes      | numeric metric | hh25inc10  | hh25inc10  | number    | number      |
| Yes      | numeric metric | hh40inc10  | hh40inc10  | number    | number      |
| Yes      | numeric metric | hh60inc10  | hh60inc10  | number    | number      |
| Yes      | numeric metric | hh75inc10  | hh75inc10  | number    | number      |
| Yes      | numeric metric | hhmore7510 | hhmore7510 | number    | number      |
| Yes      | numeric metric | mhhi10     | mhhi10     | number    | number      |
| Yes      | numeric metric | racdiv10   | racdiv10   | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:cix3-h4cy d:2010-01-01T00:00:00.000Z t:csa2010="Allendale/Irvington/S. Hilton" m:racdiv10=22.857310776595064 m:mhhi10=33563.12 m:age1810=25.01 m:perasi10=0.46 m:male10=7246 m:hhsize10=2.64 m:female10=8971 m:fam10=35.47 m:hh25inc10=39.27 m:hhs10=6098 m:peraa10=88.54 m:age6510=12.82 m:hh60inc10=18.42 m:hh40inc10=17.14 m:perpac10=0.02 m:age6410=27.75 m:perna10=0.35 m:totalpop10=16217 m:hh75inc10=6.2 m:perwhite10=8.69 m:age4410=24.16 m:hhmore7510=18.96 m:perother10=0.43 m:perhisp10=1.29 m:age2410=10.25 m:per2m10=1.5

series e:cix3-h4cy d:2010-01-01T00:00:00.000Z t:csa2010="Beechfield/Ten Hills/West Hills" m:racdiv10=36.23230490451774 m:mhhi10=50780.92 m:age1810=23.19 m:perasi10=0.85 m:male10=5566 m:hhsize10=2.4 m:female10=6698 m:fam10=33.16 m:hh25inc10=21.6 m:hhs10=5076 m:peraa10=79.28 m:age6510=10.46 m:hh60inc10=21.82 m:hh40inc10=18.2 m:perpac10=0.07 m:age6410=28.74 m:perna10=0.19 m:totalpop10=12264 m:hh75inc10=10.4 m:perwhite10=17.22 m:age4410=27.45 m:hhmore7510=27.97 m:perother10=0.47 m:perhisp10=1.59 m:age2410=10.16 m:per2m10=1.92

series e:cix3-h4cy d:2010-01-01T00:00:00.000Z t:csa2010=Belair-Edison m:racdiv10=24.608122063964622 m:mhhi10=42920.83 m:age1810=27.12 m:perasi10=0.53 m:male10=7891 m:hhsize10=2.9 m:female10=9525 m:fam10=39.86 m:hh25inc10=25.14 m:hhs10=6174 m:peraa10=87.3 m:age6510=7.95 m:hh60inc10=21.52 m:hh40inc10=22.66 m:perpac10=0 m:age6410=27.73 m:perna10=0.21 m:totalpop10=17416 m:hh75inc10=9.81 m:perwhite10=10.17 m:age4410=26.29 m:hhmore7510=20.87 m:perother10=0.46 m:perhisp10=1.22 m:age2410=10.92 m:per2m10=1.33
```

## Meta Commands

```ls
metric m:totalpop10 p:integer l:totalpop10 t:dataTypeName=number

metric m:male10 p:integer l:male10 t:dataTypeName=number

metric m:female10 p:integer l:female10 t:dataTypeName=number

metric m:peraa10 p:float l:peraa10 t:dataTypeName=number

metric m:perwhite10 p:float l:perwhite10 t:dataTypeName=number

metric m:perna10 p:float l:perna10 t:dataTypeName=number

metric m:perasi10 p:float l:perasi10 t:dataTypeName=number

metric m:perpac10 p:float l:perpac10 t:dataTypeName=number

metric m:per2m10 p:float l:per2m10 t:dataTypeName=number

metric m:perother10 p:float l:perother10 t:dataTypeName=number

metric m:perhisp10 p:float l:perhisp10 t:dataTypeName=number

metric m:age1810 p:float l:age1810 t:dataTypeName=number

metric m:age2410 p:float l:age2410 t:dataTypeName=number

metric m:age4410 p:double l:age4410 t:dataTypeName=number

metric m:age6410 p:float l:age6410 t:dataTypeName=number

metric m:age6510 p:float l:age6510 t:dataTypeName=number

metric m:hhs10 p:integer l:hhs10 t:dataTypeName=number

metric m:fam10 p:float l:fam10 t:dataTypeName=number

metric m:hhsize10 p:float l:hhsize10 t:dataTypeName=number

metric m:hh25inc10 p:float l:hh25inc10 t:dataTypeName=number

metric m:hh40inc10 p:float l:hh40inc10 t:dataTypeName=number

metric m:hh60inc10 p:float l:hh60inc10 t:dataTypeName=number

metric m:hh75inc10 p:float l:hh75inc10 t:dataTypeName=number

metric m:hhmore7510 p:float l:hhmore7510 t:dataTypeName=number

metric m:mhhi10 p:float l:mhhi10 t:dataTypeName=number

metric m:racdiv10 p:decimal l:racdiv10 t:dataTypeName=number

entity e:cix3-h4cy l:"Census Demographics 2010" t:attribution="Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore" t:url=https://data.baltimorecity.gov/api/views/cix3-h4cy

property e:cix3-h4cy t:meta.view v:id=cix3-h4cy v:category=Neighborhoods v:attributionLink=http://www.bniajfi.org v:averageRating=0 v:name="Census Demographics 2010" v:attribution="Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore"

property e:cix3-h4cy t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:cix3-h4cy t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:cix3-h4cy t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| csa2010                           | totalpop10 | male10 | female10 | peraa10            | perwhite10 | perna10             | perasi10            | perpac10             | per2m10            | perother10         | perhisp10          | age1810            | age2410 | age4410 | age6410 | age6510            | hhs10 | fam10              | hhsize10           | hh25inc10          | hh40inc10          | hh60inc10          | hh75inc10 | hhmore7510 | mhhi10   | racdiv10           | 
| ================================= | ========== | ====== | ======== | ================== | ========== | =================== | =================== | ==================== | ================== | ================== | ================== | ================== | ======= | ======= | ======= | ================== | ===== | ================== | ================== | ================== | ================== | ================== | ========= | ========== | ======== | ================== | 
| Allendale/Irvington/S. Hilton     | 16217      | 7246   | 8971     | 88.54              | 8.69       | 0.35                | 0.46                | 0.02                 | 1.5                | 0.43               | 1.29               | 25.01              | 10.25   | 24.16   | 27.75   | 12.82              | 6098  | 35.47              | 2.64               | 39.270000000000003 | 17.14              | 18.420000000000002 | 6.2       | 18.96      | 33563.12 | 22.857310776595064 | 
| Beechfield/Ten Hills/West Hills   | 12264      | 5566   | 6698     | 79.28              | 17.22      | 0.19                | 0.85                | 0.070000000000000007 | 1.92               | 0.47               | 1.59               | 23.19              | 10.16   | 27.45   | 28.74   | 10.46              | 5076  | 33.159999999999997 | 2.4                | 21.6               | 18.2               | 21.82              | 10.4      | 27.97      | 50780.92 | 36.23230490451774  | 
| Belair-Edison                     | 17416      | 7891   | 9525     | 87.3               | 10.17      | 0.21                | 0.53                | 0                    | 1.33               | 0.46               | 1.22               | 27.12              | 10.92   | 26.29   | 27.73   | 7.95               | 6174  | 39.86              | 2.9                | 25.14              | 22.66              | 21.52              | 9.81      | 20.87      | 42920.83 | 24.608122063964622 | 
| Brooklyn/Curtis Bay/Hawkins Point | 14243      | 6981   | 7262     | 36.46              | 52.07      | 0.57999999999999996 | 1.78                | 0.01                 | 4.91               | 4.1900000000000004 | 9.7899999999999991 | 28.39              | 11.06   | 29.99   | 23.49   | 7.08               | 5204  | 38.47              | 2.61               | 52.52              | 17.649999999999999 | 11.71              | 7.85      | 10.28      | 32888.50 | 66.706878048786635 | 
| Canton                            | 8100       | 4011   | 4089     | 4.1500000000000004 | 88.85      | 0.17                | 3.4                 | 0.070000000000000007 | 1.67               | 1.69               | 4.99               | 7.09               | 10.49   | 53      | 18.48   | 10.94              | 4310  | 8.56               | 1.86               | 13.69              | 8.1199999999999992 | 15.17              | 13.1      | 49.92      | 74685.14 | 28.275434321299798 | 
| Cedonia/Frankford                 | 23557      | 10788  | 12769    | 79.09              | 15.6       | 0.31                | 2.27                | 0.01                 | 2.12               | 0.59               | 1.97               | 24.49              | 11.56   | 27.53   | 27.76   | 8.66               | 9348  | 33.9               | 2.54               | 27.28              | 23.96              | 20.81              | 10.83     | 17.13      | 38969.08 | 37.478770163096307 | 
| Cherry Hill                       | 8202       | 3343   | 4859     | 95.74              | 1.74       | 0.2                 | 0.24                | 0.01                 | 1.33               | 0.73               | 1.6                | 35.700000000000003 | 12.14   | 23.79   | 20      | 8.3800000000000008 | 3145  | 44.96              | 2.57               | 59.29              | 18.239999999999998 | 10.09              | 6.74      | 5.64       | 18602.22 | 11.18019084328099  | 
| Chinquapin Park/Belvedere         | 7756       | 3527   | 4229     | 69.62              | 24.17      | 0.37                | 1.73                | 0.13                 | 2.09               | 1.88               | 3.71               | 21.33              | 11.06   | 28.24   | 27.93   | 11.45              | 3359  | 28.91              | 2.2599999999999998 | 26.31              | 17.47              | 19.29              | 8.65      | 28.28      | 44659.56 | 49.5364472574364   | 
| Claremont/Armistead               | 8231       | 3717   | 4514     | 53.66              | 35.9       | 0.97                | 0.55000000000000004 | 0.12                 | 3.2                | 5.6                | 11.38              | 26.83              | 10.42   | 28.78   | 24.47   | 9.5                | 3419  | 34.83              | 2.41               | 39.67              | 18.88              | 17.510000000000002 | 10.6      | 13.34      | 33236.03 | 66.714527253778499 | 
| Clifton-Berea                     | 9874       | 4473   | 5401     | 96.93              | 1.17       | 0.25                | 0.26                | 0                    | 1.1599999999999999 | 0.21               | 1.03               | 25.5               | 10.46   | 22.45   | 26.08   | 15.51              | 3529  | 34.29              | 2.83               | 47.61              | 23.17              | 15.77              | 5.13      | 8.32       | 26147.87 | 7.9494623952919952 | 
```