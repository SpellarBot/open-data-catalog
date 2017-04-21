# Maryland Building Permits 2000-2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-building-permits-2000-2012-021f4) |
| Metadata | [Link](https://data.maryland.gov/api/views/sfr7-abnt) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/sfr7-abnt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/sfr7-abnt/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | sfr7-abnt |
| Name | Maryland Building Permits 2000-2012 |
| Attribution | Maryland Department of Planning |
| Category | Demographic |
| Tags | building permits, census, housing, planning, mdp |
| Created | 2012-11-09T18:45:27Z |
| Publication Date | 2013-11-20T15:26:55Z |

## Description

New housing units authorized for construction in Maryland and its Jurisdictions from 2000 to 2011 and cumulative 2000-2012.
Prepared by MD Department of Planning. State Data Center. 2013
SOURCE: U.S. Department of Commerce. Bureau of the Census. Reported and Imputed Data.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | time           | year             | Year             | number    | text        |
| Yes      | numeric metric | maryland         | MARYLAND         | number    | number      |
| Yes      | numeric metric | allegany         | ALLEGANY         | number    | number      |
| Yes      | numeric metric | anne_arundel     | ANNE ARUNDEL     | number    | number      |
| Yes      | numeric metric | baltimore_city   | BALTIMORE CITY   | number    | number      |
| Yes      | numeric metric | baltimore_county | BALTIMORE COUNTY | number    | number      |
| Yes      | numeric metric | calvert          | CALVERT          | number    | number      |
| Yes      | numeric metric | caroline         | CAROLINE         | number    | number      |
| Yes      | numeric metric | carroll          | CARROLL          | number    | number      |
| Yes      | numeric metric | cecil            | CECIL            | number    | number      |
| Yes      | numeric metric | charles          | CHARLES          | number    | number      |
| Yes      | numeric metric | dorchester       | DORCHESTER       | number    | number      |
| Yes      | numeric metric | frederick        | FREDERICK        | number    | number      |
| Yes      | numeric metric | garrett          | GARRETT          | number    | number      |
| Yes      | numeric metric | harford          | HARFORD          | number    | number      |
| Yes      | numeric metric | howard           | HOWARD           | number    | number      |
| Yes      | numeric metric | kent             | KENT             | number    | number      |
| Yes      | numeric metric | montgomery       | MONTGOMERY       | number    | number      |
| Yes      | numeric metric | prince_george_s  | PRINCE GEORGE'S  | number    | number      |
| Yes      | numeric metric | queen_anne_s     | QUEEN ANNE'S     | number    | number      |
| Yes      | numeric metric | st_mary_s        | ST. MARY'S       | number    | number      |
| Yes      | numeric metric | somerset         | SOMERSET         | number    | number      |
| Yes      | numeric metric | talbot           | TALBOT           | number    | number      |
| Yes      | numeric metric | washington       | WASHINGTON       | number    | number      |
| Yes      | numeric metric | wicomico         | WICOMICO         | number    | number      |
| Yes      | numeric metric | worcester        | WORCESTER        | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:sfr7-abnt d:2000-01-01T00:00:00.000Z m:anne_arundel=3078 m:baltimore_city=257 m:wicomico=480 m:montgomery=4950 m:kent=334 m:harford=1702 m:frederick=2747 m:prince_george_s=3456 m:carroll=1459 m:calvert=931 m:charles=1233 m:allegany=79 m:washington=721 m:queen_anne_s=419 m:caroline=154 m:somerset=1163 m:baltimore_county=2707 m:talbot=339 m:cecil=768 m:garrett=253 m:worcester=810 m:howard=2182 m:dorchester=109 m:maryland=30358 m:st_mary_s=27

series e:sfr7-abnt d:2001-01-01T00:00:00.000Z m:anne_arundel=2492 m:baltimore_city=195 m:wicomico=871 m:montgomery=5249 m:kent=347 m:harford=1844 m:frederick=1983 m:prince_george_s=3049 m:carroll=1390 m:calvert=886 m:charles=1368 m:allegany=80 m:washington=986 m:queen_anne_s=507 m:caroline=176 m:somerset=549 m:baltimore_county=3153 m:talbot=365 m:cecil=940 m:garrett=286 m:worcester=854 m:howard=1327 m:dorchester=117 m:maryland=29059 m:st_mary_s=45

series e:sfr7-abnt d:2002-01-01T00:00:00.000Z m:anne_arundel=2359 m:baltimore_city=293 m:wicomico=841 m:montgomery=5013 m:kent=394 m:harford=1883 m:frederick=1578 m:prince_george_s=2563 m:carroll=1654 m:calvert=928 m:charles=1470 m:allegany=103 m:washington=1235 m:queen_anne_s=549 m:caroline=174 m:somerset=914 m:baltimore_county=2706 m:talbot=387 m:cecil=968 m:garrett=333 m:worcester=1148 m:howard=1547 m:dorchester=179 m:maryland=29293 m:st_mary_s=74
```

## Meta Commands

```ls
metric m:maryland p:integer l:MARYLAND t:dataTypeName=number

metric m:allegany p:integer l:ALLEGANY t:dataTypeName=number

metric m:anne_arundel p:integer l:"ANNE ARUNDEL" t:dataTypeName=number

metric m:baltimore_city p:integer l:"BALTIMORE CITY" t:dataTypeName=number

metric m:baltimore_county p:integer l:"BALTIMORE COUNTY" t:dataTypeName=number

metric m:calvert p:integer l:CALVERT t:dataTypeName=number

metric m:caroline p:integer l:CAROLINE t:dataTypeName=number

metric m:carroll p:integer l:CARROLL t:dataTypeName=number

metric m:cecil p:integer l:CECIL t:dataTypeName=number

metric m:charles p:integer l:CHARLES t:dataTypeName=number

metric m:dorchester p:integer l:DORCHESTER t:dataTypeName=number

metric m:frederick p:integer l:FREDERICK t:dataTypeName=number

metric m:garrett p:integer l:GARRETT t:dataTypeName=number

metric m:harford p:integer l:HARFORD t:dataTypeName=number

metric m:howard p:integer l:HOWARD t:dataTypeName=number

metric m:kent p:integer l:KENT t:dataTypeName=number

metric m:montgomery p:integer l:MONTGOMERY t:dataTypeName=number

metric m:prince_george_s p:integer l:"PRINCE GEORGE'S" t:dataTypeName=number

metric m:queen_anne_s p:integer l:"QUEEN ANNE'S" t:dataTypeName=number

metric m:st_mary_s p:integer l:"ST. MARY'S" t:dataTypeName=number

metric m:somerset p:integer l:SOMERSET t:dataTypeName=number

metric m:talbot p:integer l:TALBOT t:dataTypeName=number

metric m:washington p:integer l:WASHINGTON t:dataTypeName=number

metric m:wicomico p:integer l:WICOMICO t:dataTypeName=number

metric m:worcester p:integer l:WORCESTER t:dataTypeName=number

entity e:sfr7-abnt l:"Maryland Building Permits 2000-2012" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/sfr7-abnt

property e:sfr7-abnt t:meta.view v:id=sfr7-abnt v:category=Demographic v:attributionLink=http://planning.maryland.gov/msdc/NewHH/newhh.shtml v:averageRating=0 v:name="Maryland Building Permits 2000-2012" v:attribution="Maryland Department of Planning"

property e:sfr7-abnt t:meta.view.license v:name="Public Domain"

property e:sfr7-abnt t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:sfr7-abnt t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| year | maryland | allegany | anne_arundel | baltimore_city | baltimore_county | calvert | caroline | carroll | cecil | charles | dorchester | frederick | garrett | harford | howard | kent | montgomery | prince_george_s | queen_anne_s | st_mary_s | somerset | talbot | washington | wicomico | worcester | 
| ==== | ======== | ======== | ============ | ============== | ================ | ======= | ======== | ======= | ===== | ======= | ========== | ========= | ======= | ======= | ====== | ==== | ========== | =============== | ============ | ========= | ======== | ====== | ========== | ======== | ========= | 
| 2000 | 30358    | 79       | 3078         | 257            | 2707             | 931     | 154      | 1459    | 768   | 1233    | 109        | 2747      | 253     | 1702    | 2182   | 334  | 4950       | 3456            | 419          | 27        | 1163     | 339    | 721        | 480      | 810       | 
| 2001 | 29059    | 80       | 2492         | 195            | 3153             | 886     | 176      | 1390    | 940   | 1368    | 117        | 1983      | 286     | 1844    | 1327   | 347  | 5249       | 3049            | 507          | 45        | 549      | 365    | 986        | 871      | 854       | 
| 2002 | 29293    | 103      | 2359         | 293            | 2706             | 928     | 174      | 1654    | 968   | 1470    | 179        | 1578      | 333     | 1883    | 1547   | 394  | 5013       | 2563            | 549          | 74        | 914      | 387    | 1235       | 841      | 1148      | 
| 2003 | 29914    | 107      | 3001         | 695            | 2599             | 791     | 260      | 1065    | 1089  | 1244    | 287        | 1837      | 334     | 1976    | 1479   | 429  | 4428       | 2938            | 318          | 230       | 1094     | 522    | 1105       | 1068     | 1018      | 
| 2004 | 27382    | 120      | 2364         | 740            | 2103             | 525     | 316      | 1040    | 811   | 1000    | 423        | 1773      | 355     | 1836    | 1837   | 221  | 3821       | 1948            | 362          | 185       | 1384     | 625    | 1368       | 1000     | 1225      | 
| 2005 | 30180    | 114      | 2495         | 1256           | 1936             | 488     | 362      | 809     | 743   | 1309    | 490        | 1872      | 334     | 2659    | 1778   | 206  | 3591       | 3425            | 394          | 209       | 993      | 648    | 1945       | 1003     | 1121      | 
| 2006 | 23262    | 120      | 1414         | 649            | 2217             | 305     | 194      | 511     | 405   | 1327    | 400        | 1300      | 287     | 1344    | 1567   | 194  | 3031       | 3033            | 431          | 135       | 759      | 578    | 908        | 1082     | 1071      | 
| 2007 | 18582    | 135      | 1831         | 319            | 1143             | 333     | 91       | 312     | 422   | 908     | 125        | 1288      | 256     | 993     | 1388   | 233  | 3459       | 2183            | 221          | 164       | 939      | 480    | 427        | 513      | 419       | 
| 2008 | 13018    | 81       | 974          | 1080           | 1528             | 252     | 91       | 196     | 596   | 706     | 249        | 619       | 184     | 636     | 947    | 105  | 1476       | 1306            | 183          | 44        | 555      | 315    | 317        | 348      | 230       | 
| 2009 | 11123    | 138      | 1175         | 341            | 1021             | 260     | 44       | 180     | 236   | 714     | 93         | 839       | 159     | 773     | 1473   | 117  | 862        | 1259            | 152          | 125       | 469      | 205    | 165        | 200      | 123       | 
```