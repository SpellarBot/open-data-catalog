# Maryland Total Jobs By Place of Work Projections:1970-2040

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-total-jobs-by-place-of-work-projections-1970-2040-7dca9) |
| Metadata | [Link](https://data.maryland.gov/api/views/u5my-pdap) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/u5my-pdap/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/u5my-pdap/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | u5my-pdap |
| Name | Maryland Total Jobs By Place of Work Projections:1970-2040 |
| Attribution | Maryland Department of Planning |
| Category | Demographic |
| Tags | jobs, employment, projections, planning, mdp |
| Created | 2012-11-30T16:39:58Z |
| Publication Date | 2015-02-12T20:11:51Z |

## Description

Historical and Projected Total Jobs by Place of Work for Maryland's Jurisdictions: 1970 - 2040. Historical data from the U.S. Bureau of Economic Analysis, Tables CA25 and CA25N
Projections from 2015 to 2040 prepared by the Maryland Department of Planning, June 2012.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | time           | date_created           | Date created           | text      | text        |
| No       |                | year                   | Year                   | number    | number      |
| Yes      | numeric metric | maryland               | MARYLAND               | number    | number      |
| Yes      | numeric metric | allegany_county        | Allegany County        | number    | number      |
| Yes      | numeric metric | anne_arundel_county    | Anne Arundel County    | number    | number      |
| Yes      | numeric metric | baltimore_city         | Baltimore City         | number    | number      |
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
Value = date_created
Format & Zone = MM/dd/yy
```

## Series Fields

```ls
Excluded Fields = year
```

## Data Commands

```ls
series e:u5my-pdap d:2015-02-12T00:00:00.000Z m:baltimore_city=533697 m:calvert_county=6249 m:st_mary_s_county=19164 m:wicomico_county=29972 m:prince_george_s_county=198903 m:washington_county=44839 m:carroll_county=27223 m:montgomery_county=235394 m:garrett_county=6723 m:talbot_county=12583 m:kent_county=7303 m:queen_anne_s_county=6710 m:baltimore_county=227055 m:cecil_county=20979 m:harford_county=44726 m:caroline_county=8125 m:frederick_county=33439 m:charles_county=15777 m:somerset_county=6748 m:maryland=1702298 m:anne_arundel_county=130013 m:howard_county=22397 m:worcester_county=14205 m:allegany_county=36133 m:dorchester_county=13941

series e:u5my-pdap d:2015-02-12T00:00:00.000Z m:baltimore_city=503343 m:calvert_county=7782 m:st_mary_s_county=21211 m:wicomico_county=33516 m:prince_george_s_county=264059 m:washington_county=52159 m:carroll_county=36133 m:montgomery_county=349504 m:garrett_county=10169 m:talbot_county=15949 m:kent_county=8066 m:queen_anne_s_county=8398 m:baltimore_county=308319 m:cecil_county=19096 m:harford_county=50932 m:caroline_county=8466 m:frederick_county=44042 m:charles_county=21877 m:somerset_county=7183 m:maryland=2070441 m:anne_arundel_county=175706 m:howard_county=56654 m:worcester_county=19124 m:allegany_county=34418 m:dorchester_county=14335

series e:u5my-pdap d:2015-02-12T00:00:00.000Z m:baltimore_city=508534 m:calvert_county=18146 m:st_mary_s_county=35990 m:wicomico_county=44899 m:prince_george_s_county=372367 m:washington_county=66698 m:carroll_county=52388 m:montgomery_county=512644 m:garrett_county=14229 m:talbot_county=21607 m:kent_county=10269 m:queen_anne_s_county=12829 m:baltimore_county=399498 m:cecil_county=25922 m:harford_county=75058 m:caroline_county=11158 m:frederick_county=72323 m:charles_county=38209 m:somerset_county=9031 m:maryland=2737249 m:anne_arundel_county=250070 m:howard_county=105751 m:worcester_county=27130 m:allegany_county=35894 m:dorchester_county=16605
```

## Meta Commands

```ls
metric m:maryland p:integer l:MARYLAND t:dataTypeName=number

metric m:allegany_county p:integer l:"Allegany County" t:dataTypeName=number

metric m:anne_arundel_county p:integer l:"Anne Arundel County" t:dataTypeName=number

metric m:baltimore_city p:integer l:"Baltimore City" t:dataTypeName=number

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

entity e:u5my-pdap l:"Maryland Total Jobs By Place of Work Projections:1970-2040" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/u5my-pdap

property e:u5my-pdap t:meta.view v:id=u5my-pdap v:category=Demographic v:attributionLink=http://planning.maryland.gov/msdc/S3_Projection.shtml v:averageRating=0 v:name="Maryland Total Jobs By Place of Work Projections:1970-2040" v:attribution="Maryland Department of Planning"

property e:u5my-pdap t:meta.view.license v:name="Public Domain"

property e:u5my-pdap t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:u5my-pdap t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| date_created | year | maryland | allegany_county | anne_arundel_county | baltimore_city | baltimore_county | calvert_county | caroline_county | carroll_county | cecil_county | charles_county | dorchester_county | frederick_county | garrett_county | harford_county | howard_county | kent_county | montgomery_county | prince_george_s_county | queen_anne_s_county | somerset_county | st_mary_s_county | talbot_county | washington_county | wicomico_county | worcester_county | 
| ============ | ==== | ======== | =============== | =================== | ============== | ================ | ============== | =============== | ============== | ============ | ============== | ================= | ================ | ============== | ============== | ============= | =========== | ================= | ====================== | =================== | =============== | ================ | ============= | ================= | =============== | ================ | 
| 2/12/15      | 1970 | 1702298  | 36133           | 130013              | 533697         | 227055           | 6249           | 8125            | 27223          | 20979        | 15777          | 13941             | 33439            | 6723           | 44726          | 22397         | 7303        | 235394            | 198903                 | 6710                | 6748            | 19164            | 12583         | 44839             | 29972           | 14205            | 
| 2/12/15      | 1980 | 2070441  | 34418           | 175706              | 503343         | 308319           | 7782           | 8466            | 36133          | 19096        | 21877          | 14335             | 44042            | 10169          | 50932          | 56654         | 8066        | 349504            | 264059                 | 8398                | 7183            | 21211            | 15949         | 52159             | 33516           | 19124            | 
| 2/12/15      | 1990 | 2737249  | 35894           | 250070              | 508534         | 399498           | 18146          | 11158           | 52388          | 25922        | 38209          | 16605             | 72323            | 14229          | 75058          | 105751        | 10269       | 512644            | 372367                 | 12829               | 9031            | 35990            | 21607         | 66698             | 44899           | 27130            | 
| 2/12/15      | 2000 | 3065202  | 37848           | 295194              | 446406         | 448498           | 25816          | 12811           | 68111          | 32043        | 49370          | 16185             | 103859           | 17470          | 97094          | 159188        | 11603       | 592976            | 391158                 | 17113               | 10913           | 48952            | 25133         | 74880             | 51431           | 31150            | 
| 2/12/15      | 2005 | 3308776  | 38714           | 345711              | 397852         | 495195           | 32028          | 13851           | 80271          | 38499        | 58160          | 17188             | 124476           | 20255          | 111603         | 178019        | 12669       | 636627            | 421503                 | 21001               | 11017           | 56786            | 27853         | 78384             | 57558           | 33556            | 
| 2/12/15      | 2010 | 3344652  | 38191           | 354218              | 381313         | 505130           | 32649          | 13307           | 81611          | 40136        | 60281          | 16033             | 128113           | 20414          | 114779         | 189573        | 12705       | 644992            | 423654                 | 21964               | 10497           | 62710            | 27223         | 77353             | 55799           | 32007            | 
| 2/12/15      | 2015 | 3552000  | 38000           | 404700              | 400600         | 519900           | 34000          | 14800           | 85800          | 44000        | 62300          | 16100             | 135700           | 21400          | 126600         | 216100        | 12900       | 676500            | 439900                 | 23100               | 10700           | 66000            | 28600         | 83200             | 56900           | 34200            | 
| 2/12/15      | 2020 | 3751600  | 38800           | 428800              | 412300         | 541700           | 36800          | 16100           | 91300          | 49100        | 66700          | 17100             | 147000           | 22000          | 137100         | 235200        | 13100       | 715200            | 461700                 | 25000               | 11500           | 70400            | 29700         | 88100             | 60400           | 36500            | 
| 2/12/15      | 2025 | 3880900  | 40400           | 441500              | 419000         | 553600           | 39500          | 17100           | 95900          | 52200        | 70400          | 17700             | 154900           | 22900          | 143200         | 247000        | 13300       | 742700            | 473900                 | 27000               | 11800           | 74300            | 30400         | 92200             | 62200           | 37800            | 
| 2/12/15      | 2030 | 3975200  | 40800           | 452000              | 424500         | 562300           | 40900          | 17400           | 98600          | 54300        | 73300          | 18000             | 160000           | 23800          | 147500         | 258200        | 13800       | 759000            | 486200                 | 27600               | 12400           | 76500            | 31500         | 94200             | 63800           | 38600            | 
```