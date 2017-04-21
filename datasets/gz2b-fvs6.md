# Maryland Domestic Migration: 2000-2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-domestic-migration-2000-2012-88a60) |
| Metadata | [Link](https://data.maryland.gov/api/views/gz2b-fvs6) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/gz2b-fvs6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/gz2b-fvs6/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | gz2b-fvs6 |
| Name | Maryland Domestic Migration: 2000-2012 |
| Attribution | Maryland Department of Planning |
| Category | Demographic |
| Tags | domestic, migration, planning, mdp |
| Created | 2012-12-21T15:43:42Z |
| Publication Date | 2013-11-14T17:51:20Z |

## Description

Domestic Migration in Maryland and its Jurisdictions from 2000 to 2012. Domestic migration will also include the net  change in group quarters population, source: Population Division, U.S. Census bureau, release date April 2013.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | time           | date_created           | Date created           | text      | text        |
| No       |                | year                   | Year                   | number    | text        |
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
Format & Zone = MM/dd/yyyy
```

## Series Fields

```ls
Excluded Fields = year
```

## Data Commands

```ls
series e:gz2b-fvs6 d:2013-07-01T00:00:00.000Z m:baltimore_city=-12325 m:calvert_county=1688 m:st_mary_s_county=305 m:wicomico_county=11 m:prince_george_s_county=144 m:washington_county=617 m:carroll_county=2169 m:montgomery_county=-2525 m:garrett_county=-127 m:talbot_county=280 m:kent_county=176 m:queen_anne_s_county=387 m:baltimore_county=3377 m:cecil_county=1398 m:harford_county=1493 m:caroline_county=-21 m:frederick_county=3701 m:charles_county=2475 m:somerset_county=389 m:maryland=8641 m:anne_arundel_county=2118 m:howard_county=2334 m:worcester_county=821 m:allegany_county=-312 m:dorchester_county=68

series e:gz2b-fvs6 d:2013-07-01T00:00:00.000Z m:baltimore_city=-10750 m:calvert_county=2562 m:st_mary_s_county=1686 m:wicomico_county=274 m:prince_george_s_county=-2304 m:washington_county=1288 m:carroll_county=3524 m:montgomery_county=-5069 m:garrett_county=137 m:talbot_county=299 m:kent_county=204 m:queen_anne_s_county=1125 m:baltimore_county=3478 m:cecil_county=1401 m:harford_county=3173 m:caroline_county=151 m:frederick_county=4817 m:charles_county=2320 m:somerset_county=248 m:maryland=12107 m:anne_arundel_county=2070 m:howard_county=1090 m:worcester_county=681 m:allegany_county=-263 m:dorchester_county=-35

series e:gz2b-fvs6 d:2013-07-01T00:00:00.000Z m:baltimore_city=-8772 m:calvert_county=2592 m:st_mary_s_county=2109 m:wicomico_county=973 m:prince_george_s_county=-4179 m:washington_county=1608 m:carroll_county=3110 m:montgomery_county=-8759 m:garrett_county=126 m:talbot_county=296 m:kent_county=142 m:queen_anne_s_county=1066 m:baltimore_county=3605 m:cecil_county=1902 m:harford_county=2827 m:caroline_county=358 m:frederick_county=2662 m:charles_county=2724 m:somerset_county=44 m:maryland=5345 m:anne_arundel_county=-261 m:howard_county=646 m:worcester_county=538 m:allegany_county=-158 m:dorchester_county=146
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

entity e:gz2b-fvs6 l:"Maryland Domestic Migration: 2000-2012" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/gz2b-fvs6

property e:gz2b-fvs6 t:meta.view v:id=gz2b-fvs6 v:category=Demographic v:attributionLink=http://planning.maryland.gov/msdc/md_statistical_handbook12.pdf v:averageRating=0 v:name="Maryland Domestic Migration: 2000-2012" v:attribution="Maryland Department of Planning"

property e:gz2b-fvs6 t:meta.view.license v:name="Public Domain"

property e:gz2b-fvs6 t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:gz2b-fvs6 t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| date_created | year | maryland | allegany_county | anne_arundel_county | baltimore_city | baltimore_county | calvert_county | caroline_county | carroll_county | cecil_county | charles_county | dorchester_county | frederick_county | garrett_county | harford_county | howard_county | kent_county | montgomery_county | prince_george_s_county | queen_anne_s_county | somerset_county | st_mary_s_county | talbot_county | washington_county | wicomico_county | worcester_county | 
| ============ | ==== | ======== | =============== | =================== | ============== | ================ | ============== | =============== | ============== | ============ | ============== | ================= | ================ | ============== | ============== | ============= | =========== | ================= | ====================== | =================== | =============== | ================ | ============= | ================= | =============== | ================ | 
| 7/1/2013     | 2001 | 8641     | -312            | 2118                | -12325         | 3377             | 1688           | -21             | 2169           | 1398         | 2475           | 68                | 3701             | -127           | 1493           | 2334          | 176         | -2525             | 144                    | 387                 | 389             | 305              | 280           | 617               | 11              | 821              | 
| 7/1/2013     | 2002 | 12107    | -263            | 2070                | -10750         | 3478             | 2562           | 151             | 3524           | 1401         | 2320           | -35               | 4817             | 137            | 3173           | 1090          | 204         | -5069             | -2304                  | 1125                | 248             | 1686             | 299           | 1288              | 274             | 681              | 
| 7/1/2013     | 2003 | 5345     | -158            | -261                | -8772          | 3605             | 2592           | 358             | 3110           | 1902         | 2724           | 146               | 2662             | 126            | 2827           | 646           | 142         | -8759             | -4179                  | 1066                | 44              | 2109             | 296           | 1608              | 973             | 538              | 
| 7/1/2013     | 2004 | -10142   | 374             | -435                | -11620         | 2254             | 1541           | -9              | 2183           | 1876         | 2152           | 380               | 1780             | -129           | 1891           | -636          | 125         | -11774            | -6296                  | 595                 | 197             | 1513             | 624           | 2021              | 941             | 310              | 
| 7/1/2013     | 2005 | -13066   | -298            | -1834               | -7531          | 162              | 1014           | 581             | 1154           | 1511         | 1593           | 380               | 1358             | -130           | 2173           | -495          | 218         | -10673            | -7633                  | 348                 | -87             | 1180             | 529           | 2141              | 1348            | -75              | 
| 7/1/2013     | 2006 | -27530   | 4               | -3844               | -5837          | -457             | 403            | 584             | 1102           | 1386         | 1106           | 194               | 718              | -37            | 1160           | -60           | 140         | -12808            | -16577                 | 696                 | 231             | 974              | 454           | 1412              | 1240            | 286              | 
| 7/1/2013     | 2007 | -33169   | 428             | -2076               | -5584          | -2839            | 132            | 328             | 43             | 198          | 151            | 405               | 1098             | -13            | -1018          | 362           | 102         | -11461            | -17047                 | 668                 | 344             | 813              | 76            | 1081              | 448             | 192              | 
| 7/1/2013     | 2008 | -29200   | 138             | -508                | -6234          | -2965            | 38             | 71              | -244           | 68           | -385           | 171               | -264             | 34             | -288           | 81            | 410         | -5191             | -14612                 | 445                 | -131            | 363              | 58            | -103              | -82             | -70              | 
| 7/1/2013     | 2009 | -12404   | 221             | 2001                | -6052          | -2255            | 245            | -175            | -240           | 122          | -282           | -124              | -364             | -121           | -388           | 1766          | 14          | 1102              | -7794                  | 321                 | -166            | 439              | 44            | -441              | -141            | -136             | 
| 7/1/2013     | 2010 | 1932     | -121            | 1993                | -5214          | -724             | 466            | -126            | 122            | -36          | 1120           | 134               | 1346             | -129           | 245            | 2467          | 117         | 1961              | -3717                  | 264                 | 29              | 1569             | 240           | 114               | -144            | -44              | 
```