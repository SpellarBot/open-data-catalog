# Maryland Historical and Projected Total Personal Income (in thousands of Constant 2009 Dollars):1970-2040

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-historical-and-projected-total-personal-income-in-thousands-of-constant-2009-1970) |
| Metadata | [Link](https://data.maryland.gov/api/views/yu6n-fkf7) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/yu6n-fkf7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/yu6n-fkf7/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | yu6n-fkf7 |
| Name | Maryland Historical and Projected Total Personal Income (in thousands of Constant 2009 Dollars):1970-2040 |
| Attribution | Maryland Department of Planning |
| Category | Demographic |
| Tags | income, projections, planning, mdp |
| Created | 2012-11-30T20:03:10Z |
| Publication Date | 2015-02-18T16:18:07Z |

## Description

Historical and Projected Total Personal Income for Maryland and its Jurisdictions (in thousands of constant 2009 Dollars). Historical data, 1970 - 2010, from the U.S. Bureau of Economic Analysis

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | time           | date_created           | Date created           | text      | text        |
| No       |                | year                   | Year                   | number    | number      |
| Yes      | numeric metric | maryland               | MARYLAND               | money     | money       |
| Yes      | numeric metric | allegany_county        | Allegany County        | money     | money       |
| Yes      | numeric metric | anne_arundel_county    | Anne Arundel County    | money     | money       |
| Yes      | numeric metric | baltimore_city         | Baltimore City         | money     | money       |
| Yes      | numeric metric | baltimore_county       | Baltimore County       | money     | money       |
| Yes      | numeric metric | calvert_county         | Calvert County         | money     | money       |
| Yes      | numeric metric | caroline_county        | Caroline County        | money     | money       |
| Yes      | numeric metric | carroll_county         | Carroll County         | money     | money       |
| Yes      | numeric metric | cecil_county           | Cecil County           | money     | money       |
| Yes      | numeric metric | charles_county         | Charles County         | money     | money       |
| Yes      | numeric metric | dorchester_county      | Dorchester County      | money     | money       |
| Yes      | numeric metric | frederick_county       | Frederick County       | money     | money       |
| Yes      | numeric metric | garrett_county         | Garrett County         | money     | money       |
| Yes      | numeric metric | harford_county         | Harford County         | money     | money       |
| Yes      | numeric metric | howard_county          | Howard County          | money     | money       |
| Yes      | numeric metric | kent_county            | Kent County            | money     | money       |
| Yes      | numeric metric | montgomery_county      | Montgomery County      | money     | money       |
| Yes      | numeric metric | prince_george_s_county | Prince George's County | money     | money       |
| Yes      | numeric metric | queen_anne_s_county    | Queen Anne's County    | money     | money       |
| Yes      | numeric metric | somerset_county        | Somerset County        | money     | money       |
| Yes      | numeric metric | st_mary_s_county       | St. Mary's County      | money     | money       |
| Yes      | numeric metric | talbot_county          | Talbot County          | money     | money       |
| Yes      | numeric metric | washington_county      | Washington County      | money     | money       |
| Yes      | numeric metric | wicomico_county        | Wicomico County        | money     | money       |
| Yes      | numeric metric | worcester_county       | Worcester County       | money     | money       |
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
series e:yu6n-fkf7 d:2015-02-12T00:00:00.000Z m:baltimore_city=16504130 m:calvert_county=377760 m:st_mary_s_county=919395 m:wicomico_county=961281 m:prince_george_s_county=15525868 m:washington_county=1773599 m:carroll_county=1299440 m:montgomery_county=16934195 m:garrett_county=251337 m:talbot_county=475239 m:kent_county=275485 m:queen_anne_s_county=350370 m:baltimore_county=14027682 m:cecil_county=946316 m:harford_county=2288193 m:caroline_county=317321 m:frederick_county=1605138 m:charles_county=950473 m:somerset_county=236641 m:maryland=86048219 m:anne_arundel_county=6214656 m:howard_county=1617465 m:worcester_county=413191 m:allegany_county=1302804 m:dorchester_county=480242

series e:yu6n-fkf7 d:2015-02-12T00:00:00.000Z m:baltimore_city=16839965 m:calvert_county=832901 m:st_mary_s_county=1198979 m:wicomico_county=1162718 m:prince_george_s_county=16844484 m:washington_county=2375781 m:carroll_county=2418577 m:montgomery_county=21493135 m:garrett_county=430283 m:talbot_county=672741 m:kent_county=320128 m:queen_anne_s_county=587746 m:baltimore_county=18176004 m:cecil_county=1247301 m:harford_county=3708779 m:caroline_county=377969 m:frederick_county=2763125 m:charles_county=1804837 m:somerset_county=262740 m:maryland=110351069 m:anne_arundel_county=10098133 m:howard_county=4120210 m:worcester_county=556467 m:allegany_county=1493119 m:dorchester_county=564946

series e:yu6n-fkf7 d:2015-02-12T00:00:00.000Z m:baltimore_city=19701243 m:calvert_county=1705055 m:st_mary_s_county=2066094 m:wicomico_county=1914644 m:prince_george_s_county=24297829 m:washington_county=3003225 m:carroll_county=4003276 m:montgomery_county=36643086 m:garrett_county=573274 m:talbot_county=1128099 m:kent_county=514331 m:queen_anne_s_county=1107126 m:baltimore_county=24831294 m:cecil_county=1981710 m:harford_county=5630331 m:caroline_county=606612 m:frederick_county=4630077 m:charles_county=3205574 m:somerset_county=444660 m:maryland=164137117 m:anne_arundel_county=14726846 m:howard_county=7924054 m:worcester_county=1055986 m:allegany_county=1705421 m:dorchester_county=737270
```

## Meta Commands

```ls
metric m:maryland p:integer l:MARYLAND t:dataTypeName=money

metric m:allegany_county p:integer l:"Allegany County" t:dataTypeName=money

metric m:anne_arundel_county p:integer l:"Anne Arundel County" t:dataTypeName=money

metric m:baltimore_city p:integer l:"Baltimore City" t:dataTypeName=money

metric m:baltimore_county p:integer l:"Baltimore County" t:dataTypeName=money

metric m:calvert_county p:integer l:"Calvert County" t:dataTypeName=money

metric m:caroline_county p:integer l:"Caroline County" t:dataTypeName=money

metric m:carroll_county p:integer l:"Carroll County" t:dataTypeName=money

metric m:cecil_county p:integer l:"Cecil County" t:dataTypeName=money

metric m:charles_county p:integer l:"Charles County" t:dataTypeName=money

metric m:dorchester_county p:integer l:"Dorchester County" t:dataTypeName=money

metric m:frederick_county p:integer l:"Frederick County" t:dataTypeName=money

metric m:garrett_county p:integer l:"Garrett County" t:dataTypeName=money

metric m:harford_county p:integer l:"Harford County" t:dataTypeName=money

metric m:howard_county p:integer l:"Howard County" t:dataTypeName=money

metric m:kent_county p:integer l:"Kent County" t:dataTypeName=money

metric m:montgomery_county p:integer l:"Montgomery County" t:dataTypeName=money

metric m:prince_george_s_county p:integer l:"Prince George's County" t:dataTypeName=money

metric m:queen_anne_s_county p:integer l:"Queen Anne's County" t:dataTypeName=money

metric m:somerset_county p:integer l:"Somerset County" t:dataTypeName=money

metric m:st_mary_s_county p:integer l:"St. Mary's County" t:dataTypeName=money

metric m:talbot_county p:integer l:"Talbot County" t:dataTypeName=money

metric m:washington_county p:integer l:"Washington County" t:dataTypeName=money

metric m:wicomico_county p:integer l:"Wicomico County" t:dataTypeName=money

metric m:worcester_county p:integer l:"Worcester County" t:dataTypeName=money

entity e:yu6n-fkf7 l:"Maryland Historical and Projected Total Personal Income (in thousands of Constant 2009 Dollars):1970-2040" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/yu6n-fkf7

property e:yu6n-fkf7 t:meta.view v:id=yu6n-fkf7 v:category=Demographic v:attributionLink=http://planning.maryland.gov/msdc/S3_Projection.shtml v:averageRating=0 v:name="Maryland Historical and Projected Total Personal Income (in thousands of Constant 2009 Dollars):1970-2040" v:attribution="Maryland Department of Planning"

property e:yu6n-fkf7 t:meta.view.license v:name="Public Domain"

property e:yu6n-fkf7 t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:yu6n-fkf7 t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| date_created | year | maryland  | allegany_county | anne_arundel_county | baltimore_city | baltimore_county | calvert_county | caroline_county | carroll_county | cecil_county | charles_county | dorchester_county | frederick_county | garrett_county | harford_county | howard_county | kent_county | montgomery_county | prince_george_s_county | queen_anne_s_county | somerset_county | st_mary_s_county | talbot_county | washington_county | wicomico_county | worcester_county | 
| ============ | ==== | ========= | =============== | =================== | ============== | ================ | ============== | =============== | ============== | ============ | ============== | ================= | ================ | ============== | ============== | ============= | =========== | ================= | ====================== | =================== | =============== | ================ | ============= | ================= | =============== | ================ | 
| 2/12/15      | 1970 | 86048219  | 1302804         | 6214656             | 16504130       | 14027682         | 377760         | 317321          | 1299440        | 946316       | 950473         | 480242            | 1605138          | 251337         | 2288193        | 1617465       | 275485      | 16934195          | 15525868               | 350370              | 236641          | 919395           | 475239        | 1773599           | 961281          | 413191           | 
| 2/12/15      | 1980 | 110351069 | 1493119         | 10098133            | 16839965       | 18176004         | 832901         | 377969          | 2418577        | 1247301      | 1804837        | 564946            | 2763125          | 430283         | 3708779        | 4120210       | 320128      | 21493135          | 16844484               | 587746              | 262740          | 1198979          | 672741        | 2375781           | 1162718         | 556467           | 
| 2/12/15      | 1990 | 164137117 | 1705421         | 14726846            | 19701243       | 24831294         | 1705055        | 606612          | 4003276        | 1981710      | 3205574        | 737270            | 4630077          | 573274         | 5630331        | 7924054       | 514331      | 36643086          | 24297829               | 1107126             | 444660          | 2066094          | 1128099       | 3003225           | 1914644         | 1055986          | 
| 2/12/15      | 2000 | 225723207 | 1912121         | 22566987            | 19560557       | 33493253         | 2890756        | 823163          | 6086384        | 3004025      | 4616731        | 905225            | 7840621          | 835712         | 8524095        | 13578913      | 739281      | 53917780          | 29015722               | 1752107             | 587274          | 3174161          | 1628936       | 4030605           | 2573733         | 1665062          | 
| 2/12/15      | 2005 | 265452388 | 2117985         | 27198360            | 22009299       | 38367033         | 3706176        | 1026403         | 7052569        | 3544981      | 5819038        | 1053808           | 9672351          | 1028022        | 10402265       | 16383452      | 908091      | 62684692          | 33764215               | 2103530             | 693705          | 3837832          | 2062809       | 4826971           | 3173958         | 2014843          | 
| 2/12/15      | 2010 | 284851328 | 2358763         | 29081995            | 24379314       | 39432009         | 4145209        | 1057505         | 7393495        | 3832240      | 6531978        | 1102441           | 10606717         | 1104033        | 11604496       | 18412235      | 881558      | 66786183          | 35498503               | 2319936             | 749458          | 4644559          | 2022657       | 5241001           | 3450058         | 2214984          | 
| 2/12/15      | 2015 | 312526581 | 2448893         | 32447287            | 26989375       | 43191716         | 4423487        | 1187009         | 7995843        | 4283860      | 7231784        | 1205446           | 11745329         | 1202044        | 12607812       | 20940919      | 1019350     | 73551856          | 37231273               | 2619284             | 794249          | 5253751          | 2306822       | 5678921           | 3679845         | 2490426          | 
| 2/12/15      | 2020 | 353892529 | 2715545         | 37081720            | 31119092       | 47511618         | 5025310        | 1388826         | 9089457        | 4941083      | 8778523        | 1380098           | 13883400         | 1348787        | 14319640       | 24796814      | 1179440     | 82221953          | 40239829               | 3081625             | 895798          | 6410183          | 2678984       | 6665915           | 4227132         | 2911758          | 
| 2/12/15      | 2025 | 386504209 | 2921846         | 40581464            | 33926564       | 50222771         | 5457442        | 1568097         | 9780743        | 5636617      | 10142008       | 1537439           | 15796736         | 1470612        | 15705850       | 27506556      | 1313072     | 89848950          | 42745307               | 3514007             | 972933          | 7542296          | 2933576       | 7506012           | 4618328         | 3254985          | 
| 2/12/15      | 2030 | 413533746 | 3096047         | 43652065            | 35715439       | 52057049         | 5780037        | 1738015         | 10374882       | 6256739      | 11187385       | 1648973           | 17487740         | 1564848        | 17053574       | 29635729      | 1424953     | 96661049          | 44733888               | 3879962             | 1029433         | 8641036          | 3147830       | 8234409           | 5012598         | 3520064          | 
```