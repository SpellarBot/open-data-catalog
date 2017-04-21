# Maryland Total Migration: 2000-2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-total-migration-2000-2012-7cbc9) |
| Metadata | [Link](https://data.maryland.gov/api/views/3hb2-c6rg) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/3hb2-c6rg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/3hb2-c6rg/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 3hb2-c6rg |
| Name | Maryland Total Migration: 2000-2012 |
| Attribution | Maryland Department of Planning |
| Category | Demographic |
| Tags | total, migration, planning, mdp |
| Created | 2012-12-21T17:54:32Z |
| Publication Date | 2013-11-14T18:00:44Z |

## Description

Maryland Total (International and Domestic) Migration from 2000 to 2012. Source from the Population Division, U.S. Census Bureau.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | time           | year                   | Year                   | number    | text        |
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
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:3hb2-c6rg d:2001-01-01T00:00:00.000Z m:baltimore_city=-11140 m:calvert_county=1746 m:st_mary_s_county=361 m:wicomico_county=203 m:prince_george_s_county=5202 m:washington_county=719 m:carroll_county=2235 m:montgomery_county=7721 m:garrett_county=-121 m:talbot_county=318 m:kent_county=188 m:queen_anne_s_county=441 m:baltimore_county=5364 m:cecil_county=1457 m:harford_county=1637 m:caroline_county=49 m:frederick_county=3958 m:charles_county=2547 m:somerset_county=423 m:maryland=30127 m:anne_arundel_county=2747 m:howard_county=3400 m:worcester_county=892 m:allegany_county=-296 m:dorchester_county=76

series e:3hb2-c6rg d:2002-01-01T00:00:00.000Z m:baltimore_city=-9586 m:calvert_county=2594 m:st_mary_s_county=1611 m:wicomico_county=453 m:prince_george_s_county=2542 m:washington_county=1378 m:carroll_county=3585 m:montgomery_county=5074 m:garrett_county=142 m:talbot_county=339 m:kent_county=215 m:queen_anne_s_county=1178 m:baltimore_county=5404 m:cecil_county=1454 m:harford_county=3226 m:caroline_county=222 m:frederick_county=5027 m:charles_county=2291 m:somerset_county=282 m:maryland=32117 m:anne_arundel_county=2123 m:howard_county=2089 m:worcester_county=750 m:allegany_county=-248 m:dorchester_county=-28

series e:3hb2-c6rg d:2003-01-01T00:00:00.000Z m:baltimore_city=-7761 m:calvert_county=2566 m:st_mary_s_county=1784 m:wicomico_county=1128 m:prince_george_s_county=-231 m:washington_county=1671 m:carroll_county=3157 m:montgomery_county=371 m:garrett_county=131 m:talbot_county=334 m:kent_county=150 m:queen_anne_s_county=1108 m:baltimore_county=5263 m:cecil_county=1944 m:harford_county=2697 m:caroline_county=428 m:frederick_county=2759 m:charles_county=2493 m:somerset_county=75 m:maryland=20753 m:anne_arundel_county=-1365 m:howard_county=1457 m:worcester_county=597 m:allegany_county=-151 m:dorchester_county=148
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

entity e:3hb2-c6rg l:"Maryland Total Migration: 2000-2012" t:attribution="Maryland Department of  Planning" t:url=https://data.maryland.gov/api/views/3hb2-c6rg

property e:3hb2-c6rg t:meta.view v:id=3hb2-c6rg v:category=Demographic v:attributionLink=http://planning.maryland.gov/msdc/md_statistical_handbook12.pdf v:averageRating=0 v:name="Maryland Total Migration: 2000-2012" v:attribution="Maryland Department of  Planning"

property e:3hb2-c6rg t:meta.view.license v:name="Public Domain"

property e:3hb2-c6rg t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:3hb2-c6rg t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| year | maryland | allegany_county | anne_arundel_county | baltimore_city | baltimore_county | calvert_county | caroline_county | carroll_county | cecil_county | charles_county | dorchester_county | frederick_county | garrett_county | harford_county | howard_county | kent_county | montgomery_county | prince_george_s_county | queen_anne_s_county | somerset_county | st_mary_s_county | talbot_county | washington_county | wicomico_county | worcester_county | 
| ==== | ======== | =============== | =================== | ============== | ================ | ============== | =============== | ============== | ============ | ============== | ================= | ================ | ============== | ============== | ============= | =========== | ================= | ====================== | =================== | =============== | ================ | ============= | ================= | =============== | ================ | 
| 2001 | 30127    | -296            | 2747                | -11140         | 5364             | 1746           | 49              | 2235           | 1457         | 2547           | 76                | 3958             | -121           | 1637           | 3400          | 188         | 7721              | 5202                   | 441                 | 423             | 361              | 318           | 719               | 203             | 892              | 
| 2002 | 32117    | -248            | 2123                | -9586          | 5404             | 2594           | 222             | 3585           | 1454         | 2291           | -28               | 5027             | 142            | 3226           | 2089          | 215         | 5074              | 2542                   | 1178                | 282             | 1611             | 339           | 1378              | 453             | 750              | 
| 2003 | 20753    | -151            | -1365               | -7761          | 5263             | 2566           | 428             | 3157           | 1944         | 2493           | 148               | 2759             | 131            | 2697           | 1457          | 150         | 371               | -231                   | 1108                | 75              | 1784             | 334           | 1671              | 1128            | 597              | 
| 2004 | 11251    | 389             | 915                 | -10577         | 3922             | 1632           | 68              | 2261           | 1937         | 2365           | 391               | 2077             | -123           | 2112           | 340           | 135         | -2434             | -1065                  | 644                 | 231             | 1757             | 668           | 2117              | 1113            | 376              | 
| 2005 | 8075     | -285            | -1326               | -6399          | 1967             | 1064           | 662             | 1228           | 1570         | 1646           | 388               | 1605             | -123           | 2275           | 498           | 228         | -519              | -2282                  | 395                 | -49             | 1220             | 573           | 2232              | 1517            | -10              | 
| 2006 | -4956    | 19              | -2812               | -4687          | 1377             | 477            | 672             | 1184           | 1450         | 1253           | 205               | 1014             | -30            | 1342           | 981           | 151         | -2543             | -10943                 | 745                 | 270             | 1126             | 499           | 1511              | 1429            | 354              | 
| 2007 | -13841   | 440             | -1585               | -4561          | -1221            | 178            | 405             | 108            | 257          | 207            | 414               | 1326             | -6             | -925           | 1274          | 110         | -2194             | -12164                 | 712                 | 377             | 855              | 116           | 1164              | 619             | 253              | 
| 2008 | -10351   | 149             | 124                 | -5255          | -1426            | 91             | 151             | -179           | 125          | -301           | 181               | -29              | 39             | -175           | 957           | 417         | 3663              | -9872                  | 488                 | -100            | 443              | 97            | -20               | 90              | -9               | 
| 2009 | 4204     | 231             | 2435                | -5187          | -898             | 287            | -101            | -183           | 168          | -226           | -114              | -167             | -115           | -308           | 2519          | 22          | 9069              | -3587                  | 360                 | -138            | 485              | 81            | -369              | 20              | -80              | 
| 2010 | 19065    | -109            | 2707                | -4362          | 613              | 523            | -50             | 183            | 12           | 1228           | 145               | 1566             | -123           | 366            | 3233          | 125         | 9872              | 588                    | 305                 | 58              | 1683             | 278           | 191               | 20              | 13               | 
```