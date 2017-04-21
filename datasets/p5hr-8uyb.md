# Maryland Per Capita Personal Income Projections (in Constant 2009 Dollars):1970-2040

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-per-capita-personal-income-projections-in-constant-2009-dollars-1970-2040-d3d84) |
| Metadata | [Link](https://data.maryland.gov/api/views/p5hr-8uyb) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/p5hr-8uyb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/p5hr-8uyb/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | p5hr-8uyb |
| Name | Maryland Per Capita Personal Income Projections (in Constant 2009 Dollars):1970-2040 |
| Attribution | Maryland Department of Planning |
| Category | Demographic |
| Tags | personal, income, projections, planning, mdp |
| Created | 2012-11-30T15:32:11Z |
| Publication Date | 2015-02-12T19:47:31Z |

## Description

Historical and Projected Per Capita Personal Income for Maryland and its Jurisdictions (in constant 2009 Dollars): 1970 - 2040. Historical data, 1970 - 2010, from the U.S. Bureau of Economic Analysis. Projections by the the Maryland Department of Planning.

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
series e:p5hr-8uyb d:2015-02-12T00:00:00.000Z m:baltimore_city=18245 m:calvert_county=18047 m:st_mary_s_county=19218 m:wicomico_county=17627 m:prince_george_s_county=23307 m:washington_county=17067 m:carroll_county=18713 m:montgomery_county=32293 m:garrett_county=11632 m:talbot_county=20044 m:kent_county=16956 m:queen_anne_s_county=18933 m:baltimore_county=22537 m:cecil_county=17682 m:harford_county=19667 m:caroline_county=15951 m:frederick_county=18816 m:charles_county=19706 m:somerset_county=12502 m:maryland=21850 m:anne_arundel_county=20728 m:howard_county=25386 m:worcester_county=16853 m:allegany_county=15513 m:dorchester_county=16276

series e:p5hr-8uyb d:2015-02-12T00:00:00.000Z m:baltimore_city=21417 m:calvert_county=23876 m:st_mary_s_county=19925 m:wicomico_county=17986 m:prince_george_s_county=25278 m:washington_county=21024 m:carroll_county=24972 m:montgomery_county=36926 m:garrett_county=16203 m:talbot_county=26144 m:kent_county=19161 m:queen_anne_s_county=22886 m:baltimore_county=27712 m:cecil_county=20586 m:harford_county=25334 m:caroline_county=16288 m:frederick_county=23881 m:charles_county=24567 m:somerset_county=13734 m:maryland=26102 m:anne_arundel_county=27115 m:howard_county=34377 m:worcester_county=18013 m:allegany_county=18529 m:dorchester_county=18488

series e:p5hr-8uyb d:2015-02-12T00:00:00.000Z m:baltimore_city=26781 m:calvert_county=32819 m:st_mary_s_county=27057 m:wicomico_county=25616 m:prince_george_s_county=33236 m:washington_county=24626 m:carroll_county=32262 m:montgomery_county=48196 m:garrett_county=20303 m:talbot_county=36793 m:kent_county=28783 m:queen_anne_s_county=32484 m:baltimore_county=35740 m:cecil_county=27575 m:harford_county=30647 m:caroline_county=22364 m:frederick_county=30593 m:charles_county=31504 m:somerset_county=18947 m:maryland=34197 m:anne_arundel_county=34338 m:howard_county=41845 m:worcester_county=29925 m:allegany_county=22753 m:dorchester_county=24347
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

entity e:p5hr-8uyb l:"Maryland Per Capita Personal Income Projections (in Constant 2009 Dollars):1970-2040" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/p5hr-8uyb

property e:p5hr-8uyb t:meta.view v:id=p5hr-8uyb v:category=Demographic v:attributionLink=http://planning.maryland.gov/msdc/S3_Projection.shtml v:averageRating=0 v:name="Maryland Per Capita Personal Income Projections (in Constant 2009 Dollars):1970-2040" v:attribution="Maryland Department of Planning"

property e:p5hr-8uyb t:meta.view.license v:name="Public Domain"

property e:p5hr-8uyb t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:p5hr-8uyb t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| date_created | year | maryland | allegany_county | anne_arundel_county | baltimore_city | baltimore_county | calvert_county | caroline_county | carroll_county | cecil_county | charles_county | dorchester_county | frederick_county | garrett_county | harford_county | howard_county | kent_county | montgomery_county | prince_george_s_county | queen_anne_s_county | somerset_county | st_mary_s_county | talbot_county | washington_county | wicomico_county | worcester_county | 
| ============ | ==== | ======== | =============== | =================== | ============== | ================ | ============== | =============== | ============== | ============ | ============== | ================= | ================ | ============== | ============== | ============= | =========== | ================= | ====================== | =================== | =============== | ================ | ============= | ================= | =============== | ================ | 
| 2/12/15      | 1970 | 21850    | 15513           | 20728               | 18245          | 22537            | 18047          | 15951           | 18713          | 17682        | 19706          | 16276             | 18816            | 11632          | 19667          | 25386         | 16956       | 32293             | 23307                  | 18933               | 12502           | 19218            | 20044         | 17067             | 17627           | 16853            | 
| 2/12/15      | 1980 | 26102    | 18529           | 27115               | 21417          | 27712            | 23876          | 16288           | 24972          | 20586        | 24567          | 18488             | 23881            | 16203          | 25334          | 34377         | 19161       | 36926             | 25278                  | 22886               | 13734           | 19925            | 26144         | 21024             | 17986           | 18013            | 
| 2/12/15      | 1990 | 34197    | 22753           | 34338               | 26781          | 35740            | 32819          | 22364           | 32262          | 27575        | 31504          | 24347             | 30593            | 20303          | 30647          | 41845         | 28783       | 48196             | 33236                  | 32484               | 18947           | 27057            | 36793         | 24626             | 25616           | 29925            | 
| 2/12/15      | 2000 | 42501    | 25562           | 45899               | 30136          | 44327            | 38483          | 27648           | 40186          | 34750        | 38083          | 29601             | 39889            | 28008          | 38782          | 54405         | 38400       | 61446             | 36129                  | 42983               | 23767           | 36696            | 48058         | 30523             | 30315           | 35557            | 
| 2/12/15      | 2005 | 47467    | 28630           | 52693               | 35410          | 48621            | 42948          | 32671           | 42609          | 36608        | 41997          | 33537             | 43727            | 34173          | 43633          | 60998         | 46108       | 68022             | 39570                  | 46871               | 26895           | 39618            | 56635         | 33973             | 34310           | 40152            | 
| 2/12/15      | 2010 | 49221    | 31456           | 53936               | 39245          | 48915            | 46606          | 31979           | 44211          | 37883        | 44401          | 33732             | 45294            | 36697          | 47327          | 63825         | 43609       | 68454             | 41010                  | 48460               | 28294           | 43924            | 53420         | 35474             | 34883           | 43034            | 
| 2/12/15      | 2015 | 52000    | 32805           | 57983               | 43183          | 51910            | 48265          | 35015           | 47439          | 41350        | 46033          | 36254             | 47823            | 39935          | 50031          | 67759         | 49483       | 70996             | 41352                  | 52229               | 29526           | 46126            | 58998         | 37559             | 35744           | 47078            | 
| 2/12/15      | 2020 | 56854    | 36135           | 63934               | 49076          | 56094            | 52566          | 38525           | 51674          | 45498        | 50350          | 39658             | 52262            | 44078          | 55363          | 74633         | 55114       | 77059             | 44002                  | 57493               | 32281           | 51220            | 65581         | 41584             | 38710           | 51903            | 
| 2/12/15      | 2025 | 60112    | 38496           | 68365               | 52681          | 58603            | 55490          | 40996           | 54504          | 48053        | 53197          | 42064             | 55243            | 47135          | 59245          | 79384         | 59415       | 80945             | 45980                  | 61273               | 34138           | 54973            | 69764         | 44166             | 40370           | 55404            | 
| 2/12/15      | 2030 | 62541    | 40392           | 71950               | 54854          | 60377            | 57685          | 42967           | 56616          | 49954        | 55342          | 43566             | 57516            | 49599          | 62433          | 82990         | 63051       | 83769             | 47360                  | 64291               | 35559           | 58091            | 73376         | 46028             | 42052           | 58231            | 
```