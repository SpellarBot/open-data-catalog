# DBEDT Cost Of Electricity For State Agencies by Fiscal Year

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dbedt-cost-of-electricity-for-state-agencies-by-fiscal-year-d2430) |
| Metadata | [Link](https://data.hawaii.gov/api/views/x7ms-76ef) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/x7ms-76ef/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/x7ms-76ef/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | x7ms-76ef |
| Name | DBEDT Cost Of Electricity For State Agencies by Fiscal Year |
| Attribution | DBEDT Energy |
| Category | Economic Development |
| Tags | electricity cost |
| Created | 2012-09-18T14:54:37Z |
| Publication Date | 2012-09-18T14:57:54Z |

## Description

Cost Of Electricity For State Agencies

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | time           | year         | Year         | number    | number      |
| No       |                | uh           | UH           | number    | number      |
| Yes      | numeric metric | doe          | DOE          | number    | number      |
| Yes      | numeric metric | dot_airports | DOT Airports | number    | number      |
| Yes      | numeric metric | dags         | DAGS         | number    | number      |
| Yes      | numeric metric | dot_highways | DOT Highways | number    | number      |
| Yes      | numeric metric | doh          | DOH          | number    | number      |
| Yes      | numeric metric | hpha         | HPHA         | number    | number      |
| Yes      | numeric metric | hhsc         | HHSC         | number    | number      |
| Yes      | numeric metric | psd          | PSD          | number    | number      |
| Yes      | numeric metric | dot_harbors  | DOT Harbors  | number    | number      |
| Yes      | numeric metric | hspls        | HSPLS        | number    | number      |
| Yes      | numeric metric | dod          | DOD          | number    | number      |
| Yes      | numeric metric | hta_cc       | HTA-CC       | number    | number      |
| Yes      | numeric metric | hhfdc        | HHFDC        | number    | number      |
| Yes      | numeric metric | nelha        | NELHA        | number    | number      |
| Yes      | numeric metric | dhs          | DHS          | number    | number      |
| Yes      | numeric metric | dhhl         | DHHL         | number    | number      |
| Yes      | numeric metric | dlnr         | DLNR         | number    | number      |
| Yes      | numeric metric | doa          | DOA          | number    | number      |
| Yes      | numeric metric | dcca         | DCCA         | number    | number      |
| Yes      | numeric metric | ftz          | FTZ          | number    | number      |
| Yes      | numeric metric | dbedt        | DBEDT        | number    | number      |
| Yes      | numeric metric | hcda         | HCDA         | number    | number      |
| Yes      | numeric metric | dlir         | DLIR         | number    | number      |
| No       |                | ag           | AG           | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = uh,ag
```

## Data Commands

```ls
series e:x7ms-76ef d:2005-01-01T00:00:00.000Z m:dcca=219025 m:dlnr=705898 m:dbedt=115698 m:hspls=1533815 m:hcda=149278 m:dot_highways=5010087 m:dhhl=489457 m:dot_airports=17761072 m:hhsc=3982094 m:hpha=2726530 m:hta_cc=1104124 m:dot_harbors=1648777 m:dags=7482710 m:psd=3264187 m:nelha=871574 m:hhfdc=449366 m:doa=545360 m:dhs=682243 m:ftz=134290 m:dod=1163226 m:doe=25567384 m:dlir=80885 m:doh=3934069

series e:x7ms-76ef d:2006-01-01T00:00:00.000Z m:dcca=268360 m:dlnr=841123 m:dbedt=89907 m:hspls=1808919 m:hcda=53436 m:dot_highways=5905006 m:dhhl=628181 m:dot_airports=22259323 m:hhsc=4415497 m:hpha=3308536 m:hta_cc=1520889 m:dot_harbors=2044297 m:dags=9092737 m:psd=3951300 m:nelha=1015139 m:hhfdc=568198 m:doa=647465 m:dhs=847648 m:ftz=180726 m:dod=1422139 m:doe=30610076 m:dlir=116710 m:doh=4728875

series e:x7ms-76ef d:2007-01-01T00:00:00.000Z m:dcca=273982 m:dlnr=889243 m:dbedt=124219 m:hspls=1893315 m:hcda=61014 m:dot_highways=5782916 m:dhhl=811352 m:dot_airports=22920171 m:hhsc=4801818 m:hpha=3427260 m:hta_cc=1411445 m:dot_harbors=2136409 m:dags=9310630 m:psd=3848077 m:nelha=1071918 m:hhfdc=910554 m:doa=789592 m:dhs=869025 m:ftz=174446 m:dod=1492829 m:doe=31805744 m:dlir=116422 m:doh=4759470
```

## Meta Commands

```ls
metric m:doe p:integer l:DOE t:dataTypeName=number

metric m:dot_airports p:integer l:"DOT Airports" t:dataTypeName=number

metric m:dags p:integer l:DAGS t:dataTypeName=number

metric m:dot_highways p:integer l:"DOT Highways" t:dataTypeName=number

metric m:doh p:integer l:DOH t:dataTypeName=number

metric m:hpha p:integer l:HPHA t:dataTypeName=number

metric m:hhsc p:integer l:HHSC t:dataTypeName=number

metric m:psd p:integer l:PSD t:dataTypeName=number

metric m:dot_harbors p:integer l:"DOT Harbors" t:dataTypeName=number

metric m:hspls p:integer l:HSPLS t:dataTypeName=number

metric m:dod p:integer l:DOD t:dataTypeName=number

metric m:hta_cc p:integer l:HTA-CC t:dataTypeName=number

metric m:hhfdc p:integer l:HHFDC t:dataTypeName=number

metric m:nelha p:integer l:NELHA t:dataTypeName=number

metric m:dhs p:integer l:DHS t:dataTypeName=number

metric m:dhhl p:integer l:DHHL t:dataTypeName=number

metric m:dlnr p:integer l:DLNR t:dataTypeName=number

metric m:doa p:integer l:DOA t:dataTypeName=number

metric m:dcca p:integer l:DCCA t:dataTypeName=number

metric m:ftz p:integer l:FTZ t:dataTypeName=number

metric m:dbedt p:integer l:DBEDT t:dataTypeName=number

metric m:hcda p:integer l:HCDA t:dataTypeName=number

metric m:dlir p:integer l:DLIR t:dataTypeName=number

entity e:x7ms-76ef l:"DBEDT Cost Of Electricity For State Agencies by Fiscal Year" t:attribution="DBEDT Energy" t:url=https://data.hawaii.gov/api/views/x7ms-76ef

property e:x7ms-76ef t:meta.view v:id=x7ms-76ef v:category="Economic Development" v:averageRating=0 v:name="DBEDT Cost Of Electricity For State Agencies by Fiscal Year" v:attribution="DBEDT Energy"

property e:x7ms-76ef t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:x7ms-76ef t:meta.view.owner v:id=tz3q-nbms v:profileImageUrlMedium=/api/users/tz3q-nbms/profile_images/THUMB v:profileImageUrlLarge=/api/users/tz3q-nbms/profile_images/LARGE v:screenName="Russell Castagnaro" v:profileImageUrlSmall=/api/users/tz3q-nbms/profile_images/TINY v:displayName="Russell Castagnaro"

property e:x7ms-76ef t:meta.view.tableauthor v:id=tz3q-nbms v:profileImageUrlMedium=/api/users/tz3q-nbms/profile_images/THUMB v:profileImageUrlLarge=/api/users/tz3q-nbms/profile_images/LARGE v:screenName="Russell Castagnaro" v:profileImageUrlSmall=/api/users/tz3q-nbms/profile_images/TINY v:roleName=publisher v:displayName="Russell Castagnaro"
```

## Top Records

```ls
| year | uh       | doe      | dot_airports | dags     | dot_highways | doh     | hpha    | hhsc    | psd     | dot_harbors | hspls   | dod     | hta_cc  | hhfdc   | nelha   | dhs     | dhhl    | dlnr    | doa    | dcca   | ftz    | dbedt  | hcda   | dlir   | ag    | 
| ==== | ======== | ======== | ============ | ======== | ============ | ======= | ======= | ======= | ======= | =========== | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ====== | ====== | ====== | ====== | ====== | ====== | ===== | 
| 2005 | 25206974 | 25567384 | 17761072     | 7482710  | 5010087      | 3934069 | 2726530 | 3982094 | 3264187 | 1648777     | 1533815 | 1163226 | 1104124 | 449366  | 871574  | 682243  | 489457  | 705898  | 545360 | 219025 | 134290 | 115698 | 149278 | 80885  | 10741 | 
| 2006 | 33613946 | 30610076 | 22259323     | 9092737  | 5905006      | 4728875 | 3308536 | 4415497 | 3951300 | 2044297     | 1808919 | 1422139 | 1520889 | 568198  | 1015139 | 847648  | 628181  | 841123  | 647465 | 268360 | 180726 | 89907  | 53436  | 116710 | 11632 | 
| 2007 | 34221881 | 31805744 | 22920171     | 9310630  | 5782916      | 4759470 | 3427260 | 4801818 | 3848077 | 2136409     | 1893315 | 1492829 | 1411445 | 910554  | 1071918 | 869025  | 811352  | 889243  | 789592 | 273982 | 174446 | 124219 | 61014  | 116422 | 12204 | 
| 2008 | 41121936 | 38173389 | 28641831     | 11667310 | 6979978      | 6022990 | 4229350 | 5866179 | 4689674 | 2663999     | 2244370 | 1741314 | 1717207 | 1243518 | 1313291 | 1011941 | 1031764 | 1057708 | 793773 | 347577 | 221373 | 139262 | 74315  | 130371 | 14626 | 
| 2009 | 41486486 | 38407151 | 30078400     | 11226894 | 6883710      | 6682947 | 4314939 | 6007542 | 4634448 | 2422545     | 2249731 | 1703990 | 1582841 | 1256511 | 1425614 | 1004178 | 1128121 | 1044212 | 650222 | 362075 | 206781 | 158482 | 78566  | 115599 | 12843 | 
| 2010 | 36468378 | 33966349 | 26676871     | 9499992  | 6318805      | 5771076 | 4023549 | 5181870 | 3897747 | 1939602     | 1946842 | 1487429 | 1356185 | 1101118 | 1301215 | 896555  | 946675  | 860711  | 559057 | 309522 | 200512 | 186947 | 166956 | 99715  | 11996 | 
```