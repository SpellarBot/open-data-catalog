# Libraries Collections Statistics 2005-2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/libraries-collections-statistics-2005-2011-0dd90) |
| Metadata | [Link](https://data.hawaii.gov/api/views/g4rv-58tp) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/g4rv-58tp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/g4rv-58tp/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | g4rv-58tp |
| Name | Libraries Collections Statistics 2005-2011 |
| Attribution | Hawaii State Public Library System |
| Category | Formal Education |
| Tags | library |
| Created | 2012-07-26T19:51:38Z |
| Publication Date | 2012-08-10T18:47:50Z |

## Description

Quantities of various media contained in Libraries

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | time           | year              | Year              | number    | number      |
| Yes      | series tag     | island            | Island            | text      | text        |
| Yes      | series tag     | library           | LIBRARY           | text      | text        |
| Yes      | numeric metric | reference         | REFERENCE         | number    | number      |
| Yes      | numeric metric | book              | BOOK              | number    | number      |
| No       |                | cd                | CD                | number    | number      |
| Yes      | numeric metric | dvd               | DVD               | number    | number      |
| Yes      | numeric metric | video             | VIDEO             | number    | number      |
| Yes      | numeric metric | phonotape         | PHONOTAPE         | number    | number      |
| Yes      | numeric metric | phonodisc         | PHONODISC         | number    | number      |
| Yes      | numeric metric | microform         | MICROFORM         | number    | number      |
| Yes      | numeric metric | cd_rom            | CD-ROM            | number    | number      |
| Yes      | numeric metric | software          | SOFTWARE          | number    | number      |
| Yes      | numeric metric | av_misc           | AV (MISC)         | number    | number      |
| Yes      | numeric metric | language_learning | LANGUAGE LEARNING | number    | number      |
| Yes      | numeric metric | uncataloged       | UNCATALOGED       | number    | number      |
| Yes      | numeric metric | total             | TOTAL             | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = cd
```

## Data Commands

```ls
series e:g4rv-58tp d:2011-01-01T00:00:00.000Z t:library=Aiea t:island=Oahu m:total=78348 m:phonotape=679 m:cd_rom=0 m:dvd=4145 m:av_misc=1 m:reference=1381 m:microform=0 m:language_learning=55 m:software=0 m:uncataloged=18 m:book=68590 m:phonodisc=0 m:video=71

series e:g4rv-58tp d:2011-01-01T00:00:00.000Z t:library="Aina Haina" t:island=Oahu m:total=66435 m:phonotape=532 m:cd_rom=2 m:dvd=1967 m:av_misc=8 m:reference=1322 m:microform=0 m:language_learning=48 m:software=0 m:uncataloged=39 m:book=59650 m:phonodisc=0 m:video=24

series e:g4rv-58tp d:2011-01-01T00:00:00.000Z t:library="Ewa Beach" t:island=Oahu m:total=80374 m:phonotape=470 m:cd_rom=3 m:dvd=1399 m:av_misc=5 m:reference=2987 m:microform=0 m:language_learning=22 m:software=0 m:uncataloged=14 m:book=74316 m:phonodisc=0 m:video=5
```

## Meta Commands

```ls
metric m:reference p:integer l:REFERENCE t:dataTypeName=number

metric m:book p:integer l:BOOK t:dataTypeName=number

metric m:dvd p:integer l:DVD t:dataTypeName=number

metric m:video p:integer l:VIDEO t:dataTypeName=number

metric m:phonotape p:integer l:PHONOTAPE t:dataTypeName=number

metric m:phonodisc p:integer l:PHONODISC t:dataTypeName=number

metric m:microform p:integer l:MICROFORM t:dataTypeName=number

metric m:cd_rom p:integer l:CD-ROM t:dataTypeName=number

metric m:software p:integer l:SOFTWARE t:dataTypeName=number

metric m:av_misc p:integer l:"AV (MISC)" t:dataTypeName=number

metric m:language_learning p:integer l:"LANGUAGE LEARNING" t:dataTypeName=number

metric m:uncataloged p:integer l:UNCATALOGED t:dataTypeName=number

metric m:total p:integer l:TOTAL t:dataTypeName=number

entity e:g4rv-58tp l:"Libraries Collections Statistics 2005-2011" t:attribution="Hawaii State Public Library System" t:url=https://data.hawaii.gov/api/views/g4rv-58tp

property e:g4rv-58tp t:meta.view v:id=g4rv-58tp v:category="Formal Education" v:attributionLink=http://www.librarieshawaii.org/ v:averageRating=0 v:name="Libraries Collections Statistics 2005-2011" v:attribution="Hawaii State Public Library System"

property e:g4rv-58tp t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:g4rv-58tp t:meta.view.owner v:id=4hgi-fxu8 v:screenName="Paola Saibene" v:displayName="Paola Saibene"

property e:g4rv-58tp t:meta.view.tableauthor v:id=4hgi-fxu8 v:screenName="Paola Saibene" v:displayName="Paola Saibene"
```

## Top Records

```ls
| year | island | library       | reference | book   | cd    | dvd  | video | phonotape | phonodisc | microform | cd_rom | software | av_misc | language_learning | uncataloged | total  | 
| ==== | ====== | ============= | ========= | ====== | ===== | ==== | ===== | ========= | ========= | ========= | ====== | ======== | ======= | ================= | =========== | ====== | 
| 2011 | Oahu   | Aiea          | 1381      | 68590  | 3408  | 4145 | 71    | 679       | 0         | 0         | 0      | 0        | 1       | 55                | 18          | 78348  | 
| 2011 | Oahu   | Aina Haina    | 1322      | 59650  | 2843  | 1967 | 24    | 532       | 0         | 0         | 2      | 0        | 8       | 48                | 39          | 66435  | 
| 2011 | Oahu   | Ewa Beach     | 2987      | 74316  | 1153  | 1399 | 5     | 470       | 0         | 0         | 3      | 0        | 5       | 22                | 14          | 80374  | 
| 2011 | Oahu   | Hawaii Kai    | 3464      | 70517  | 1715  | 1989 | 198   | 1007      | 0         | 0         | 6      | 0        | 1       | 15                | 13          | 78925  | 
| 2011 | Oahu   | Hawaii State  | 121403    | 426129 | 11325 | 6056 | 1674  | 3151      | 338       | 290       | 223    | 0        | 0       | 648               | 18          | 571255 | 
| 2011 | Oahu   | Kahuku        | 2950      | 43377  | 1102  | 1135 | 272   | 671       | 0         | 0         | 1      | 0        | 0       | 12                | 2           | 49522  | 
| 2011 | Oahu   | Kailua        | 3860      | 77374  | 3104  | 1874 | 71    | 1139      | 0         | 0         | 5      | 0        | 1       | 102               | 10          | 87540  | 
| 2011 | Oahu   | Kaimuki       | 11963     | 92208  | 3788  | 3739 | 247   | 1575      | 481       | 0         | 60     | 1        | 8       | 23                | 35          | 114128 | 
| 2011 | Oahu   | Kalihi-Palama | 2912      | 55194  | 3019  | 3170 | 34    | 104       | 0         | 0         | 8      | 0        | 1       | 49                | 9           | 64500  | 
| 2011 | Oahu   | Kaneohe       | 6906      | 109880 | 2814  | 2264 | 2     | 454       | 0         | 313       | 0      | 0        | 6       | 38                | 69          | 122746 | 
```