# Maryland Total Number Of Farms: 1987, 1992, 1997, 2002 and 2007

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-total-number-of-farms-1987-1992-1997-2002-and-2007-6b5ba) |
| Metadata | [Link](https://data.maryland.gov/api/views/xekf-g3h9) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/xekf-g3h9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/xekf-g3h9/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | xekf-g3h9 |
| Name | Maryland Total Number Of Farms: 1987, 1992, 1997, 2002 and 2007 |
| Attribution | Maryland Department of Planning |
| Category | Agriculture |
| Tags | farms, planning, mdp |
| Created | 2012-12-21T16:54:53Z |
| Publication Date | 2013-05-14T18:40:43Z |

## Description

Total number of farms in Maryland and its jurisdictions from 1987,1992,1997,2002 and 2007. Source from the Census of Agriculture.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | time           | year                   | Year                   | number    | number      |
| Yes      | numeric metric | maryland               | MARYLAND               | number    | number      |
| Yes      | numeric metric | allegany_county        | Allegany County        | number    | number      |
| Yes      | numeric metric | anne_arundel_county    | Anne Arundel County    | number    | number      |
| Yes      | series tag     | baltimore_city         | Baltimore City         | text      | text        |
| Yes      | numeric metric | baltimore_county       | Baltimore County       | number    | number      |
| Yes      | numeric metric | calvert_county         | Calvert County         | number    | number      |
| Yes      | numeric metric | caroline_county        | Caroline County        | number    | number      |
| Yes      | numeric metric | carroll_county         | Carroll County         | number    | number      |
| Yes      | numeric metric | cecil_county           | Cecil County           | number    | number      |
| Yes      | numeric metric | charles_county         | Charles County         | number    | number      |
| Yes      | numeric metric | dorchester_county      | Dorchester County      | number    | number      |
| Yes      | numeric metric | frederick_county       | Frederick County       | number    | number      |
| Yes      | numeric metric | garrett_county         | Garrett County         | number    | number      |
| Yes      | numeric metric | harford_county         | Harford County         | number    | number      |
| Yes      | numeric metric | howard_county          | Howard County          | number    | number      |
| Yes      | numeric metric | kent_county            | Kent County            | number    | number      |
| Yes      | numeric metric | montgomery_county      | Montgomery County      | number    | number      |
| Yes      | numeric metric | prince_george_s_county | Prince George's County | number    | number      |
| Yes      | numeric metric | queen_anne_s_county    | Queen Anne's County    | number    | number      |
| Yes      | numeric metric | somerset_county        | Somerset County        | number    | number      |
| Yes      | numeric metric | st_mary_s_county       | St. Mary's County      | number    | number      |
| Yes      | numeric metric | talbot_county          | Talbot County          | number    | number      |
| Yes      | numeric metric | washington_county      | Washington County      | number    | number      |
| Yes      | numeric metric | wicomico_county        | Wicomico County        | number    | number      |
| Yes      | numeric metric | worcester_county       | Worcester County       | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:xekf-g3h9 d:1987-01-01T00:00:00.000Z t:baltimore_city=------ m:calvert_county=464 m:st_mary_s_county=754 m:wicomico_county=774 m:prince_george_s_county=683 m:washington_county=906 m:carroll_county=1238 m:montgomery_county=669 m:garrett_county=670 m:talbot_county=280 m:kent_county=361 m:queen_anne_s_county=457 m:baltimore_county=917 m:cecil_county=501 m:harford_county=758 m:caroline_county=636 m:frederick_county=1439 m:charles_county=601 m:somerset_county=406 m:maryland=14776 m:anne_arundel_county=567 m:howard_county=432 m:worcester_county=631 m:allegany_county=240 m:dorchester_county=392

series e:xekf-g3h9 d:1992-01-01T00:00:00.000Z t:baltimore_city=------ m:calvert_county=400 m:st_mary_s_county=673 m:wicomico_county=684 m:prince_george_s_county=551 m:washington_county=809 m:carroll_county=1080 m:montgomery_county=561 m:garrett_county=634 m:talbot_county=250 m:kent_county=318 m:queen_anne_s_county=413 m:baltimore_county=840 m:cecil_county=455 m:harford_county=695 m:caroline_county=588 m:frederick_county=1346 m:charles_county=496 m:somerset_county=345 m:maryland=13037 m:anne_arundel_county=477 m:howard_county=382 m:worcester_county=474 m:allegany_county=219 m:dorchester_county=347

series e:xekf-g3h9 d:1997-01-01T00:00:00.000Z t:baltimore_city=------ m:calvert_county=383 m:st_mary_s_county=658 m:wicomico_county=624 m:prince_george_s_county=526 m:washington_county=823 m:carroll_county=1159 m:montgomery_county=596 m:garrett_county=718 m:talbot_county=254 m:kent_county=325 m:queen_anne_s_county=440 m:baltimore_county=889 m:cecil_county=510 m:harford_county=733 m:caroline_county=556 m:frederick_county=1429 m:charles_county=451 m:somerset_county=314 m:maryland=13254 m:anne_arundel_county=465 m:howard_county=369 m:worcester_county=450 m:allegany_county=274 m:dorchester_county=308
```

## Meta Commands

```ls
metric m:maryland p:integer l:MARYLAND t:dataTypeName=number

metric m:allegany_county p:integer l:"Allegany County" t:dataTypeName=number

metric m:anne_arundel_county p:integer l:"Anne Arundel County" t:dataTypeName=number

metric m:baltimore_county p:integer l:"Baltimore County" t:dataTypeName=number

metric m:calvert_county p:integer l:"Calvert County" t:dataTypeName=number

metric m:caroline_county p:integer l:"Caroline County" t:dataTypeName=number

metric m:carroll_county p:integer l:"Carroll County" t:dataTypeName=number

metric m:cecil_county p:integer l:"Cecil County" t:dataTypeName=number

metric m:charles_county p:integer l:"Charles County" t:dataTypeName=number

metric m:dorchester_county p:integer l:"Dorchester County" t:dataTypeName=number

metric m:frederick_county p:integer l:"Frederick County" t:dataTypeName=number

metric m:garrett_county p:integer l:"Garrett County" t:dataTypeName=number

metric m:harford_county p:integer l:"Harford County" t:dataTypeName=number

metric m:howard_county p:integer l:"Howard County" t:dataTypeName=number

metric m:kent_county p:integer l:"Kent County" t:dataTypeName=number

metric m:montgomery_county p:integer l:"Montgomery County" t:dataTypeName=number

metric m:prince_george_s_county p:integer l:"Prince George's County" t:dataTypeName=number

metric m:queen_anne_s_county p:integer l:"Queen Anne's County" t:dataTypeName=number

metric m:somerset_county p:integer l:"Somerset County" t:dataTypeName=number

metric m:st_mary_s_county p:integer l:"St. Mary's County" t:dataTypeName=number

metric m:talbot_county p:integer l:"Talbot County" t:dataTypeName=number

metric m:washington_county p:integer l:"Washington County" t:dataTypeName=number

metric m:wicomico_county p:integer l:"Wicomico County" t:dataTypeName=number

metric m:worcester_county p:integer l:"Worcester County" t:dataTypeName=number

entity e:xekf-g3h9 l:"Maryland Total Number Of Farms: 1987, 1992, 1997, 2002 and 2007" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/xekf-g3h9

property e:xekf-g3h9 t:meta.view v:id=xekf-g3h9 v:category=Agriculture v:attributionLink=http://planning.maryland.gov/msdc/md_statistical_handbook11.pdf v:averageRating=0 v:name="Maryland Total Number Of Farms: 1987, 1992, 1997, 2002 and 2007" v:attribution="Maryland Department of Planning"

property e:xekf-g3h9 t:meta.view.license v:name="Public Domain"

property e:xekf-g3h9 t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:xekf-g3h9 t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| year | maryland | allegany_county | anne_arundel_county | baltimore_city | baltimore_county | calvert_county | caroline_county | carroll_county | cecil_county | charles_county | dorchester_county | frederick_county | garrett_county | harford_county | howard_county | kent_county | montgomery_county | prince_george_s_county | queen_anne_s_county | somerset_county | st_mary_s_county | talbot_county | washington_county | wicomico_county | worcester_county | 
| ==== | ======== | =============== | =================== | ============== | ================ | ============== | =============== | ============== | ============ | ============== | ================= | ================ | ============== | ============== | ============= | =========== | ================= | ====================== | =================== | =============== | ================ | ============= | ================= | =============== | ================ | 
| 1987 | 14776    | 240             | 567                 | ------         | 917              | 464            | 636             | 1238           | 501          | 601            | 392               | 1439             | 670            | 758            | 432           | 361         | 669               | 683                    | 457                 | 406             | 754              | 280           | 906               | 774             | 631              | 
| 1992 | 13037    | 219             | 477                 | ------         | 840              | 400            | 588             | 1080           | 455          | 496            | 347               | 1346             | 634            | 695            | 382           | 318         | 561               | 551                    | 413                 | 345             | 673              | 250           | 809               | 684             | 474              | 
| 1997 | 13254    | 274             | 465                 | ------         | 889              | 383            | 556             | 1159           | 510          | 451            | 308               | 1429             | 718            | 733            | 369           | 325         | 596               | 526                    | 440                 | 314             | 658              | 254           | 823               | 624             | 450              | 
| 2002 | 12198    | 278             | 432                 | ------         | 784              | 321            | 506             | 1058           | 468          | 418            | 351               | 1273             | 634            | 683            | 346           | 318         | 577               | 452                    | 443                 | 301             | 577              | 288           | 775               | 512             | 403              | 
| 2007 | 12834    | 302             | 377                 | ------         | 751              | 274            | 574             | 1148           | 583          | 418            | 424               | 1442             | 677            | 704            | 335           | 377         | 561               | 375                    | 521                 | 329             | 621              | 305           | 844               | 508             | 384              | 
```