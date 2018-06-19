# Maryland Total Change in Resident Population: 2000-2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-total-change-in-resident-population-2000-2013-77f22) |
| Metadata | [Link](https://data.maryland.gov/api/views/5ueh-pqc8) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/5ueh-pqc8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/5ueh-pqc8/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 5ueh-pqc8 |
| Name | Maryland Total Change in Resident Population: 2000-2013 |
| Attribution | Maryland Department of Planning |
| Category | Demographic |
| Tags | population, change, total, resident |
| Created | 2012-12-21T16:15:39Z |
| Publication Date | 2014-08-26T14:59:24Z |

## Description

Total Change in Resident Population in Maryland and its Jurisdictions by year from 2000 to 2013

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | time           | date_created           | Date created           | text      | text        |
| Yes      | series tag     | year                   | Year                   | text      | text        |
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

## Data Commands

```ls
series e:5ueh-pqc8 d:2014-08-26T00:00:00.000Z t:year=2000-2001 m:baltimore_city=-8353 m:calvert_county=2100 m:st_mary_s_county=957 m:wicomico_county=738 m:prince_george_s_county=14249 m:washington_county=1042 m:carroll_county=2583 m:montgomery_county=14286 m:garrett_county=-26 m:talbot_county=336 m:kent_county=78 m:queen_anne_s_county=490 m:baltimore_county=7327 m:cecil_county=1780 m:harford_county=2956 m:caroline_county=41 m:frederick_county=5752 m:charles_county=3516 m:somerset_county=447 m:maryland=63657 m:anne_arundel_county=6889 m:howard_county=5621 m:worcester_county=1061 m:allegany_county=-279 m:dorchester_county=66

series e:5ueh-pqc8 d:2014-08-26T00:00:00.000Z t:year=2001-2002 m:baltimore_city=-6618 m:calvert_county=2935 m:st_mary_s_county=2364 m:wicomico_county=1042 m:prince_george_s_county=11533 m:washington_county=1738 m:carroll_county=3893 m:montgomery_county=11376 m:garrett_county=175 m:talbot_county=397 m:kent_county=113 m:queen_anne_s_county=1271 m:baltimore_county=7222 m:cecil_county=1833 m:harford_county=4616 m:caroline_county=240 m:frederick_county=6879 m:charles_county=3334 m:somerset_county=288 m:maryland=65698 m:anne_arundel_county=6325 m:howard_county=4321 m:worcester_county=863 m:allegany_county=-321 m:dorchester_county=-121

series e:5ueh-pqc8 d:2014-08-26T00:00:00.000Z t:year=2002-2003 m:baltimore_city=-5082 m:calvert_county=2854 m:st_mary_s_county=2514 m:wicomico_county=1784 m:prince_george_s_county=8755 m:washington_county=2041 m:carroll_county=3459 m:montgomery_county=7358 m:garrett_county=195 m:talbot_county=366 m:kent_county=62 m:queen_anne_s_county=1164 m:baltimore_county=7609 m:cecil_county=2383 m:harford_county=4042 m:caroline_county=499 m:frederick_county=4633 m:charles_county=3863 m:somerset_county=96 m:maryland=55880 m:anne_arundel_county=2885 m:howard_county=3654 m:worcester_county=772 m:allegany_county=-128 m:dorchester_county=102
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

entity e:5ueh-pqc8 l:"Maryland Total Change in Resident Population: 2000-2013" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/5ueh-pqc8

property e:5ueh-pqc8 t:meta.view v:id=5ueh-pqc8 v:category=Demographic v:attributionLink=http://planning.maryland.gov/msdc/md_statistical_handbook13.pdf v:averageRating=0 v:name="Maryland Total Change in Resident Population: 2000-2013" v:attribution="Maryland Department of Planning"

property e:5ueh-pqc8 t:meta.view.license v:name="Public Domain"

property e:5ueh-pqc8 t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:5ueh-pqc8 t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| date_created | year      | maryland | allegany_county | anne_arundel_county | baltimore_city | baltimore_county | calvert_county | caroline_county | carroll_county | cecil_county | charles_county | dorchester_county | frederick_county | garrett_county | harford_county | howard_county | kent_county | montgomery_county | prince_george_s_county | queen_anne_s_county | somerset_county | st_mary_s_county | talbot_county | washington_county | wicomico_county | worcester_county | 
| ============ | ========= | ======== | =============== | =================== | ============== | ================ | ============== | =============== | ============== | ============ | ============== | ================= | ================ | ============== | ============== | ============= | =========== | ================= | ====================== | =================== | =============== | ================ | ============= | ================= | =============== | ================ | 
| 8/26/14      | 2000-2001 | 63657    | -279            | 6889                | -8353          | 7327             | 2100           | 41              | 2583           | 1780         | 3516           | 66                | 5752             | -26            | 2956           | 5621          | 78          | 14286             | 14249                  | 490                 | 447             | 957              | 336           | 1042              | 738             | 1061             | 
| 8/26/14      | 2001-2002 | 65698    | -321            | 6325                | -6618          | 7222             | 2935           | 240             | 3893           | 1833         | 3334           | -121              | 6879             | 175            | 4616           | 4321          | 113         | 11376             | 11533                  | 1271                | 288             | 2364             | 397           | 1738              | 1042            | 863              | 
| 8/26/14      | 2002-2003 | 55880    | -128            | 2885                | -5082          | 7609             | 2854           | 499             | 3459           | 2383         | 3863           | 102               | 4633             | 195            | 4042           | 3654          | 62          | 7358              | 8755                   | 1164                | 96              | 2514             | 366           | 2041              | 1784            | 772              | 
| 8/26/14      | 2003-2004 | 50666    | 332             | 5490                | -4811          | 6615             | 1921           | 100             | 2526           | 2365         | 3659           | 458               | 3949             | -35            | 3438           | 2733          | 8           | 4493              | 8302                   | 723                 | 266             | 2567             | 799           | 2551              | 1747            | 470              | 
| 8/26/14      | 2004-2005 | 45444    | -429            | 2912                | -2662          | 4739             | 1366           | 763             | 1604           | 2027         | 2959           | 336               | 3425             | -64            | 3553           | 2671          | 182         | 6540              | 7321                   | 468                 | -14             | 1971             | 630           | 2661              | 2298            | 187              | 
| 8/26/14      | 2005-2006 | 34988    | 1               | 1527                | -451           | 4623             | 749            | 798             | 1431           | 1985         | 2604           | 255               | 3010             | 64             | 2761           | 3203          | 91          | 4961              | -1174                  | 837                 | 346             | 1978             | 577           | 2202              | 2113            | 497              | 
| 8/26/14      | 2006-2007 | 26041    | 469             | 2805                | -803           | 2340             | 402            | 506             | 440            | 807          | 1557           | 495               | 3252             | 1              | 471            | 3403          | 15          | 5202              | -2181                  | 801                 | 395             | 1750             | 167           | 1887              | 1489            | 371              | 
| 8/26/14      | 2007-2008 | 31557    | 189             | 4801                | -122           | 2578             | 343            | 263             | 43             | 604          | 1062           | 294               | 1823             | 74             | 1145           | 3209          | 349         | 11054             | 251                    | 546                 | -60             | 1322             | 140           | 501               | 1001            | 147              | 
| 8/26/14      | 2008-2009 | 45423    | 463             | 7091                | 325            | 3157             | 456            | 30              | -405           | 584          | 1021           | 4                 | 1656             | -77            | 906            | 4656          | -18         | 16265             | 5994                   | 469                 | -49             | 1352             | 189           | 279               | 958             | 117              | 
| 8/26/14      | 2009-2010 | 56805    | -116            | 6796                | 701            | 4318             | 698            | 56              | 205            | 344          | 2310           | 212               | 3232             | -60            | 1515           | 5418          | 83          | 16617             | 9454                   | 341                 | 63              | 2468             | 367           | 790               | 836             | 157              | 
```