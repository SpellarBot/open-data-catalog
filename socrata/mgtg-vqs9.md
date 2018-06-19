# 2010 Census Populations by Council District

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2010-census-populations-by-council-district) |
| Metadata | [Link](https://data.lacity.org/api/views/mgtg-vqs9) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/mgtg-vqs9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/mgtg-vqs9/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | mgtg-vqs9 |
| Name | 2010 Census Populations by Council District |
| Attribution | U.S. Census |
| Tags | census, population, council district |
| Created | 2016-03-07T02:01:15Z |
| Publication Date | 2016-03-07T02:21:19Z |

## Description

See source link for more information. This dataset will be updated when new census data comes out (next one scheduled for 2020).

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | series tag     | council_district       | Council_District       | text      | number      |
| Yes      | numeric metric | population_total       | Population_Total       | number    | number      |
| Yes      | numeric metric | latino                 | Latino                 | number    | number      |
| Yes      | numeric metric | white                  | White                  | number    | number      |
| Yes      | numeric metric | black                  | Black                  | number    | text        |
| Yes      | numeric metric | american_indian        | American_Indian        | number    | number      |
| Yes      | numeric metric | asian                  | Asian                  | number    | text        |
| Yes      | numeric metric | hawaii_pacific         | Hawaii_Pacific         | number    | number      |
| Yes      | numeric metric | other                  | Other                  | number    | number      |
| Yes      | numeric metric | mixed                  | Mixed                  | number    | number      |
| Yes      | numeric metric | adult_total            | Adult_Total            | number    | number      |
| Yes      | numeric metric | adult_latino           | Adult_Latino           | number    | number      |
| Yes      | numeric metric | adult_white            | Adult_White            | number    | number      |
| Yes      | numeric metric | adult_american_indian  | Adult_American_Indian  | number    | number      |
| Yes      | numeric metric | adult_black            | Adult_Black            | number    | number      |
| Yes      | numeric metric | adult_asian            | Adult_Asian            | number    | text        |
| Yes      | numeric metric | adult_hawaii_pacific   | Adult_Hawaii_Pacific   | number    | number      |
| Yes      | numeric metric | adult_other            | Adult_Other            | number    | number      |
| Yes      | numeric metric | adult_mixed            | Adult_Mixed            | number    | number      |
| Yes      | numeric metric | total_housing_units    | Total_Housing_Units    | number    | number      |
| Yes      | numeric metric | occupied_housing_units | Occupied_Housing_Units | number    | number      |
| Yes      | numeric metric | vacant_housing_units   | Vacant_Housing_Units   | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:mgtg-vqs9 d:2010-01-01T00:00:00.000Z t:council_district=1 m:occupied_housing_units=113776 m:other=980 m:adult_other=614 m:adult_total=272742 m:white=33348 m:adult_black=11394 m:american_indian=840 m:asian=68513 m:adult_mixed=964 m:total_housing_units=123096 m:adult_white=30402 m:latino=237279 m:population_total=355942 m:adult_asian=59587 m:adult_american_indian=710 m:vacant_housing_units=9320 m:adult_latino=168804 m:mixed=1263 m:adult_hawaii_pacific=267 m:hawaii_pacific=315 m:black=13404

series e:mgtg-vqs9 d:2010-01-01T00:00:00.000Z t:council_district=2 m:occupied_housing_units=124419 m:other=1497 m:adult_other=980 m:adult_total=266153 m:white=142594 m:adult_black=11853 m:american_indian=1161 m:asian=28609 m:adult_mixed=1125 m:total_housing_units=132750 m:adult_white=122148 m:latino=149319 m:population_total=339878 m:adult_asian=23724 m:adult_american_indian=990 m:vacant_housing_units=8331 m:adult_latino=104791 m:mixed=1528 m:adult_hawaii_pacific=542 m:hawaii_pacific=665 m:black=14505

series e:mgtg-vqs9 d:2010-01-01T00:00:00.000Z t:council_district=3 m:occupied_housing_units=101236 m:other=1059 m:adult_other=649 m:adult_total=224879 m:white=130823 m:adult_black=9707 m:american_indian=1013 m:asian=39279 m:adult_mixed=1072 m:total_housing_units=107919 m:adult_white=109807 m:latino=103468 m:population_total=290947 m:adult_asian=31044 m:adult_american_indian=820 m:vacant_housing_units=6683 m:adult_latino=71314 m:mixed=1573 m:adult_hawaii_pacific=466 m:hawaii_pacific=577 m:black=13155
```

## Meta Commands

```ls
metric m:population_total p:integer l:Population_Total t:dataTypeName=number

metric m:latino p:integer l:Latino t:dataTypeName=number

metric m:white p:integer l:White t:dataTypeName=number

metric m:black p:integer l:Black t:dataTypeName=number

metric m:american_indian p:integer l:American_Indian t:dataTypeName=number

metric m:asian p:integer l:Asian t:dataTypeName=number

metric m:hawaii_pacific p:integer l:Hawaii_Pacific t:dataTypeName=number

metric m:other p:integer l:Other t:dataTypeName=number

metric m:mixed p:integer l:Mixed t:dataTypeName=number

metric m:adult_total p:integer l:Adult_Total t:dataTypeName=number

metric m:adult_latino p:integer l:Adult_Latino t:dataTypeName=number

metric m:adult_white p:integer l:Adult_White t:dataTypeName=number

metric m:adult_american_indian p:integer l:Adult_American_Indian t:dataTypeName=number

metric m:adult_black p:integer l:Adult_Black t:dataTypeName=number

metric m:adult_asian p:integer l:Adult_Asian t:dataTypeName=number

metric m:adult_hawaii_pacific p:integer l:Adult_Hawaii_Pacific t:dataTypeName=number

metric m:adult_other p:integer l:Adult_Other t:dataTypeName=number

metric m:adult_mixed p:integer l:Adult_Mixed t:dataTypeName=number

metric m:total_housing_units p:integer l:Total_Housing_Units t:dataTypeName=number

metric m:occupied_housing_units p:integer l:Occupied_Housing_Units t:dataTypeName=number

metric m:vacant_housing_units p:integer l:Vacant_Housing_Units t:dataTypeName=number

entity e:mgtg-vqs9 l:"2010 Census Populations by Council District" t:attribution="U.S. Census" t:url=https://data.lacity.org/api/views/mgtg-vqs9

property e:mgtg-vqs9 t:meta.view v:id=mgtg-vqs9 v:attributionLink=https://www.census.gov/2010census/data/ v:averageRating=0 v:name="2010 Census Populations by Council District" v:attribution="U.S. Census"

property e:mgtg-vqs9 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:mgtg-vqs9 t:meta.view.owner v:id=95pg-i79k v:profileImageUrlMedium=/api/users/95pg-i79k/profile_images/THUMB v:profileImageUrlLarge=/api/users/95pg-i79k/profile_images/LARGE v:screenName=ChelseaU v:profileImageUrlSmall=/api/users/95pg-i79k/profile_images/TINY v:displayName=ChelseaU

property e:mgtg-vqs9 t:meta.view.tableauthor v:id=95pg-i79k v:profileImageUrlMedium=/api/users/95pg-i79k/profile_images/THUMB v:profileImageUrlLarge=/api/users/95pg-i79k/profile_images/LARGE v:screenName=ChelseaU v:profileImageUrlSmall=/api/users/95pg-i79k/profile_images/TINY v:roleName=administrator v:displayName=ChelseaU
```

## Top Records

```ls
| council_district | population_total | latino | white  | black  | american_indian | asian | hawaii_pacific | other | mixed | adult_total | adult_latino | adult_white | adult_american_indian | adult_black | adult_asian | adult_hawaii_pacific | adult_other | adult_mixed | total_housing_units | occupied_housing_units | vacant_housing_units | 
| ================ | ================ | ====== | ====== | ====== | =============== | ===== | ============== | ===== | ===== | =========== | ============ | =========== | ===================== | =========== | =========== | ==================== | =========== | =========== | =================== | ====================== | ==================== | 
| 1                | 355942           | 237279 | 33348  | 13404  | 840             | 68513 | 315            | 980   | 1263  | 272742      | 168804       | 30402       | 710                   | 11394       | 59587       | 267                  | 614         | 964         | 123096              | 113776                 | 9320                 | 
| 2                | 339878           | 149319 | 142594 | 14505  | 1161            | 28609 | 665            | 1497  | 1528  | 266153      | 104791       | 122148      | 990                   | 11853       | 23724       | 542                  | 980         | 1125        | 132750              | 124419                 | 8331                 | 
| 3                | 290947           | 103468 | 130823 | 13155  | 1013            | 39279 | 577            | 1059  | 1573  | 224879      | 71314        | 109807      | 820                   | 9707        | 31044       | 466                  | 649         | 1072        | 107919              | 101236                 | 6683                 | 
| 4                | 395665           | 69691  | 241635 | 21425  | 1515            | 56650 | 649            | 1762  | 2338  | 336855      | 54321        | 211470      | 1343                  | 18361       | 47636       | 554                  | 1366        | 1804        | 206502              | 191089                 | 15413                | 
| 5                | 339543           | 46057  | 216920 | 16621  | 1017            | 54535 | 756            | 1572  | 2065  | 285335      | 35837        | 183821      | 867                   | 13835       | 47510       | 664                  | 1208        | 1593        | 159896              | 148607                 | 11289                | 
| 6                | 320808           | 213439 | 59830  | 11527  | 859             | 32190 | 488            | 1183  | 1292  | 233818      | 144891       | 50980       | 713                   | 8876        | 26392       | 392                  | 660         | 914         | 96777               | 91414                  | 5363                 | 
| 7                | 301497           | 204275 | 61210  | 10879  | 1060            | 21961 | 378            | 778   | 956   | 219170      | 138225       | 52538       | 864                   | 8236        | 17865       | 299                  | 497         | 646         | 84670               | 80118                  | 4552                 | 
| 8                | 355382           | 187425 | 11981  | 140256 | 650             | 9768  | 284            | 1864  | 3154  | 256334      | 124584       | 10834       | 491                   | 107280      | 9295        | 224                  | 1305        | 2321        | 115494              | 107172                 | 8322                 | 
| 9                | 308897           | 233410 | 11568  | 51347  | 416             | 9760  | 106            | 1018  | 1272  | 212246      | 151894       | 10755       | 314                   | 38156       | 9406        | 91                   | 689         | 941         | 82595               | 75970                  | 6625                 | 
| 10               | 355658           | 166909 | 36449  | 76356  | 810             | 69883 | 346            | 1752  | 3153  | 277254      | 117761       | 32172       | 677                   | 61990       | 60760       | 297                  | 1228        | 2369        | 144534              | 133768                 | 10766                | 
```