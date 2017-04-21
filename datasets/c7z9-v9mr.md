# Maryland Total New Housing Units Authorized For Construction: 2000-2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-total-new-housing-units-authorized-for-construction-2000-2011-30d9a) |
| Metadata | [Link](https://data.maryland.gov/api/views/c7z9-v9mr) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/c7z9-v9mr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/c7z9-v9mr/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | c7z9-v9mr |
| Name | Maryland Total New Housing Units Authorized For Construction: 2000-2011 |
| Attribution | Maryland Department of Planning |
| Category | Housing |
| Tags | total, new, housing, units, construction, planning, mdp |
| Created | 2012-12-21T17:57:27Z |
| Publication Date | 2012-12-21T17:59:31Z |

## Description

Maryland Total New Housing Units Authorized for Construction from 2000 to 2011. Source from the U.S. Department of Commerce, Bureau of the Census.

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
series e:c7z9-v9mr d:2012-12-17T00:00:00.000Z m:baltimore_city=257 m:calvert_county=931 m:st_mary_s_county=1163 m:wicomico_county=480 m:prince_george_s_county=3456 m:washington_county=721 m:carroll_county=1459 m:montgomery_county=4950 m:garrett_county=253 m:talbot_county=339 m:kent_county=334 m:queen_anne_s_county=419 m:baltimore_county=2707 m:cecil_county=768 m:harford_county=1702 m:caroline_county=154 m:frederick_county=2747 m:charles_county=1233 m:somerset_county=27 m:maryland=30358 m:anne_arundel_county=3078 m:howard_county=2182 m:worcester_county=810 m:allegany_county=79 m:dorchester_county=109

series e:c7z9-v9mr d:2012-12-17T00:00:00.000Z m:baltimore_city=195 m:calvert_county=886 m:st_mary_s_county=549 m:wicomico_county=871 m:prince_george_s_county=3049 m:washington_county=986 m:carroll_county=1390 m:montgomery_county=5249 m:garrett_county=286 m:talbot_county=365 m:kent_county=347 m:queen_anne_s_county=507 m:baltimore_county=3153 m:cecil_county=940 m:harford_county=1844 m:caroline_county=176 m:frederick_county=1983 m:charles_county=1368 m:somerset_county=45 m:maryland=29059 m:anne_arundel_county=2492 m:howard_county=1327 m:worcester_county=854 m:allegany_county=80 m:dorchester_county=117

series e:c7z9-v9mr d:2012-12-17T00:00:00.000Z m:baltimore_city=293 m:calvert_county=928 m:st_mary_s_county=914 m:wicomico_county=841 m:prince_george_s_county=2563 m:washington_county=1235 m:carroll_county=1654 m:montgomery_county=5013 m:garrett_county=333 m:talbot_county=387 m:kent_county=394 m:queen_anne_s_county=549 m:baltimore_county=2706 m:cecil_county=968 m:harford_county=1883 m:caroline_county=174 m:frederick_county=1578 m:charles_county=1470 m:somerset_county=74 m:maryland=29293 m:anne_arundel_county=2359 m:howard_county=1547 m:worcester_county=1148 m:allegany_county=103 m:dorchester_county=179
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

entity e:c7z9-v9mr l:"Maryland Total New Housing Units Authorized For Construction: 2000-2011" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/c7z9-v9mr

property e:c7z9-v9mr t:meta.view v:id=c7z9-v9mr v:category=Housing v:attributionLink=http://planning.maryland.gov/msdc/md_statistical_handbook11.pdf v:averageRating=0 v:name="Maryland Total New Housing Units Authorized For Construction: 2000-2011" v:attribution="Maryland Department of Planning"

property e:c7z9-v9mr t:meta.view.license v:name="Public Domain"

property e:c7z9-v9mr t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:c7z9-v9mr t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| date_created | year | maryland | allegany_county | anne_arundel_county | baltimore_city | baltimore_county | calvert_county | caroline_county | carroll_county | cecil_county | charles_county | dorchester_county | frederick_county | garrett_county | harford_county | howard_county | kent_county | montgomery_county | prince_george_s_county | queen_anne_s_county | somerset_county | st_mary_s_county | talbot_county | washington_county | wicomico_county | worcester_county | 
| ============ | ==== | ======== | =============== | =================== | ============== | ================ | ============== | =============== | ============== | ============ | ============== | ================= | ================ | ============== | ============== | ============= | =========== | ================= | ====================== | =================== | =============== | ================ | ============= | ================= | =============== | ================ | 
| 12/17/2012   | 2000 | 30358    | 79              | 3078                | 257            | 2707             | 931            | 154             | 1459           | 768          | 1233           | 109               | 2747             | 253            | 1702           | 2182          | 334         | 4950              | 3456                   | 419                 | 27              | 1163             | 339           | 721               | 480             | 810              | 
| 12/17/2012   | 2001 | 29059    | 80              | 2492                | 195            | 3153             | 886            | 176             | 1390           | 940          | 1368           | 117               | 1983             | 286            | 1844           | 1327          | 347         | 5249              | 3049                   | 507                 | 45              | 549              | 365           | 986               | 871             | 854              | 
| 12/17/2012   | 2002 | 29293    | 103             | 2359                | 293            | 2706             | 928            | 174             | 1654           | 968          | 1470           | 179               | 1578             | 333            | 1883           | 1547          | 394         | 5013              | 2563                   | 549                 | 74              | 914              | 387           | 1235              | 841             | 1148             | 
| 12/17/2012   | 2003 | 29914    | 107             | 3001                | 695            | 2599             | 791            | 260             | 1065           | 1089         | 1244           | 287               | 1837             | 334            | 1976           | 1479          | 429         | 4428              | 2938                   | 318                 | 230             | 1094             | 522           | 1105              | 1068            | 1018             | 
| 12/17/2012   | 2004 | 27382    | 120             | 2364                | 740            | 2103             | 525            | 316             | 1040           | 811          | 1000           | 423               | 1773             | 355            | 1836           | 1837          | 221         | 3821              | 1948                   | 362                 | 185             | 1384             | 625           | 1368              | 1000            | 1225             | 
| 12/17/2012   | 2005 | 30180    | 114             | 2495                | 1256           | 1936             | 488            | 362             | 809            | 743          | 1309           | 490               | 1872             | 334            | 2659           | 1778          | 206         | 3591              | 3425                   | 394                 | 209             | 993              | 648           | 1945              | 1003            | 1121             | 
| 12/17/2012   | 2006 | 23262    | 120             | 1414                | 649            | 2217             | 305            | 194             | 511            | 405          | 1327           | 400               | 1300             | 287            | 1344           | 1567          | 194         | 3031              | 3033                   | 431                 | 135             | 759              | 578           | 908               | 1082            | 1071             | 
| 12/17/2012   | 2007 | 18582    | 135             | 1831                | 319            | 1143             | 333            | 91              | 312            | 422          | 908            | 125               | 1288             | 256            | 993            | 1388          | 233         | 3459              | 2183                   | 221                 | 164             | 939              | 480           | 427               | 513             | 419              | 
| 12/17/2012   | 2008 | 13018    | 81              | 974                 | 1080           | 1528             | 252            | 91              | 196            | 596          | 706            | 249               | 619              | 184            | 636            | 947           | 105         | 1476              | 1306                   | 183                 | 44              | 555              | 315           | 317               | 348             | 230              | 
| 12/17/2012   | 2009 | 11123    | 138             | 1175                | 341            | 1021             | 260            | 44              | 180            | 236          | 714            | 93                | 839              | 159            | 773            | 1473          | 117         | 862               | 1259                   | 152                 | 125             | 469              | 205           | 165               | 200             | 123              | 
```