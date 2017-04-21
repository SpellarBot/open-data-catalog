# Maryland New Single Family Housing Units Authorized For Construction: 2000-2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-new-single-family-housing-units-authorized-for-construction-2000-2011-16ac2) |
| Metadata | [Link](https://data.maryland.gov/api/views/4br4-qbf4) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/4br4-qbf4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/4br4-qbf4/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 4br4-qbf4 |
| Name | Maryland New Single Family Housing Units Authorized For Construction: 2000-2011 |
| Attribution | Maryland Department of Planning |
| Category | Housing |
| Tags | single, family, units, construction, planning, mdp |
| Created | 2012-12-21T16:48:39Z |
| Publication Date | 2012-12-21T16:50:20Z |

## Description

New Single Family Housing Units Authorized For Construction in Maryland and its jurisdictions from 2000 to 2011. Source from the U.S. Department of Commerce. Bureau of the Census.

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
Format & Zone = MM/dd/yyyy
```

## Series Fields

```ls
Excluded Fields = year
```

## Data Commands

```ls
series e:4br4-qbf4 d:2012-12-17T00:00:00.000Z m:baltimore_city=219 m:calvert_county=906 m:st_mary_s_county=1043 m:wicomico_county=371 m:prince_george_s_county=3179 m:washington_county=559 m:carroll_county=1347 m:montgomery_county=2931 m:garrett_county=253 m:talbot_county=339 m:kent_county=334 m:queen_anne_s_county=419 m:baltimore_county=2068 m:cecil_county=683 m:harford_county=1546 m:caroline_county=154 m:frederick_county=2695 m:charles_county=1143 m:somerset_county=27 m:maryland=25132 m:anne_arundel_county=2470 m:howard_county=1631 m:worcester_county=627 m:allegany_county=79 m:dorchester_county=109

series e:4br4-qbf4 d:2012-12-17T00:00:00.000Z m:baltimore_city=115 m:calvert_county=886 m:st_mary_s_county=545 m:wicomico_county=485 m:prince_george_s_county=3049 m:washington_county=834 m:carroll_county=1350 m:montgomery_county=3191 m:garrett_county=243 m:talbot_county=365 m:kent_county=345 m:queen_anne_s_county=507 m:baltimore_county=1858 m:cecil_county=702 m:harford_county=1765 m:caroline_county=176 m:frederick_county=1721 m:charles_county=1368 m:somerset_county=43 m:maryland=23708 m:anne_arundel_county=2013 m:howard_county=1327 m:worcester_county=630 m:allegany_county=73 m:dorchester_county=117

series e:4br4-qbf4 d:2012-12-17T00:00:00.000Z m:baltimore_city=181 m:calvert_county=855 m:st_mary_s_county=814 m:wicomico_county=582 m:prince_george_s_county=2485 m:washington_county=978 m:carroll_county=1499 m:montgomery_county=2909 m:garrett_county=333 m:talbot_county=387 m:kent_county=358 m:queen_anne_s_county=549 m:baltimore_county=1941 m:cecil_county=892 m:harford_county=1814 m:caroline_county=170 m:frederick_county=1352 m:charles_county=1404 m:somerset_county=64 m:maryland=24004 m:anne_arundel_county=2026 m:howard_county=1341 m:worcester_county=800 m:allegany_county=91 m:dorchester_county=179
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

entity e:4br4-qbf4 l:"Maryland New Single Family Housing Units Authorized For Construction: 2000-2011" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/4br4-qbf4

property e:4br4-qbf4 t:meta.view v:id=4br4-qbf4 v:category=Housing v:attributionLink=http://planning.maryland.gov/msdc/md_statistical_handbook11.pdf v:averageRating=0 v:name="Maryland New Single Family Housing Units Authorized For Construction: 2000-2011" v:attribution="Maryland Department of Planning"

property e:4br4-qbf4 t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:4br4-qbf4 t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| date_created | year | maryland | allegany_county | anne_arundel_county | baltimore_city | baltimore_county | calvert_county | caroline_county | carroll_county | cecil_county | charles_county | dorchester_county | frederick_county | garrett_county | harford_county | howard_county | kent_county | montgomery_county | prince_george_s_county | queen_anne_s_county | somerset_county | st_mary_s_county | talbot_county | washington_county | wicomico_county | worcester_county | 
| ============ | ==== | ======== | =============== | =================== | ============== | ================ | ============== | =============== | ============== | ============ | ============== | ================= | ================ | ============== | ============== | ============= | =========== | ================= | ====================== | =================== | =============== | ================ | ============= | ================= | =============== | ================ | 
| 12/17/2012   | 2000 | 25132    | 79              | 2470                | 219            | 2068             | 906            | 154             | 1347           | 683          | 1143           | 109               | 2695             | 253            | 1546           | 1631          | 334         | 2931              | 3179                   | 419                 | 27              | 1043             | 339           | 559               | 371             | 627              | 
| 12/17/2012   | 2001 | 23708    | 73              | 2013                | 115            | 1858             | 886            | 176             | 1350           | 702          | 1368           | 117               | 1721             | 243            | 1765           | 1327          | 345         | 3191              | 3049                   | 507                 | 43              | 545              | 365           | 834               | 485             | 630              | 
| 12/17/2012   | 2002 | 24004    | 91              | 2026                | 181            | 1941             | 855            | 170             | 1499           | 892          | 1404           | 179               | 1352             | 333            | 1814           | 1341          | 358         | 2909              | 2485                   | 549                 | 64              | 814              | 387           | 978               | 582             | 800              | 
| 12/17/2012   | 2003 | 23398    | 107             | 2164                | 206            | 1761             | 791            | 206             | 1005           | 935          | 1152           | 285               | 1605             | 331            | 1852           | 1010          | 429         | 2339              | 2808                   | 316                 | 115             | 850              | 522           | 1001              | 866             | 742              | 
| 12/17/2012   | 2004 | 21553    | 100             | 1769                | 433            | 1497             | 525            | 316             | 732            | 678          | 1000           | 363               | 1718             | 349            | 1430           | 1284          | 221         | 2376              | 1875                   | 356                 | 108             | 1096             | 625           | 1211              | 751             | 740              | 
| 12/17/2012   | 2005 | 22909    | 104             | 1565                | 643            | 1514             | 488            | 337             | 723            | 619          | 931            | 338               | 1414             | 334            | 2216           | 1340          | 206         | 1700              | 3255                   | 385                 | 199             | 963              | 648           | 1447              | 828             | 712              | 
| 12/17/2012   | 2006 | 17858    | 120             | 1108                | 332            | 1786             | 305            | 190             | 507            | 403          | 1146           | 274               | 1098             | 287            | 1135           | 1040          | 194         | 1237              | 2918                   | 431                 | 135             | 685              | 578           | 661               | 701             | 587              | 
| 12/17/2012   | 2007 | 13232    | 133             | 1041                | 204            | 1060             | 333            | 83              | 312            | 327          | 671            | 95                | 1003             | 226            | 824            | 1113          | 222         | 1408              | 1462                   | 221                 | 105             | 854              | 480           | 407               | 269             | 379              | 
| 12/17/2012   | 2008 | 8927     | 72              | 824                 | 153            | 571              | 252            | 89              | 188            | 254          | 435            | 153               | 535              | 184            | 531            | 681           | 105         | 997               | 1264                   | 183                 | 44              | 481              | 315           | 225               | 208             | 183              | 
| 12/17/2012   | 2009 | 8133     | 63              | 822                 | 137            | 438              | 260            | 44              | 142            | 236          | 558            | 52                | 749              | 159            | 538            | 890           | 117         | 862               | 811                    | 132                 | 39              | 465              | 205           | 163               | 145             | 106              | 
```