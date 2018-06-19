# Maryland Total Personal Income (Thousands of Constant 2009 Dollars): 2006-2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-total-personal-income-thousands-of-constant-2009-dollars-2006-2011-9214e) |
| Metadata | [Link](https://data.maryland.gov/api/views/4dhw-3gak) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/4dhw-3gak/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/4dhw-3gak/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 4dhw-3gak |
| Name | Maryland Total Personal Income (Thousands of Constant 2009 Dollars): 2006-2011 |
| Attribution | Maryland Department of Planning |
| Category | Demographic |
| Tags | total, personal, income, constant, planning, mdp |
| Created | 2012-12-21T18:07:31Z |
| Publication Date | 2013-11-19T19:59:00Z |

## Description

Maryland Total Personal Income in thousands of Constant 2009 Dollars from 2006 to 2011. Source Data from U.S Bureau of Economic Analysis (Table CA5N)

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
series e:4dhw-3gak d:2013-07-01T00:00:00.000Z m:baltimore_city=22090847 m:calvert_county=3686609 m:st_mary_s_county=3822017 m:wicomico_county=3094961 m:prince_george_s_county=31993572 m:washington_county=4911412 m:carroll_county=7148162 m:montgomery_county=63732253 m:garrett_county=1000892 m:talbot_county=2070147 m:kent_county=922405 m:queen_anne_s_county=2096119 m:baltimore_county=39096902 m:cecil_county=3581584 m:harford_county=10598449 m:caroline_county=977002 m:frederick_county=9795147 m:charles_county=5747807 m:somerset_county=662804 m:maryland=266479826 m:anne_arundel_county=27723343 m:howard_county=16689993 m:worcester_county=1951862 m:allegany_county=2086720 m:dorchester_county=998816

series e:4dhw-3gak d:2013-07-01T00:00:00.000Z m:baltimore_city=22732361 m:calvert_county=3825394 m:st_mary_s_county=4007943 m:wicomico_county=3216843 m:prince_george_s_county=32702276 m:washington_county=5067754 m:carroll_county=7249109 m:montgomery_county=64515335 m:garrett_county=1018063 m:talbot_county=2102859 m:kent_county=920646 m:queen_anne_s_county=2164421 m:baltimore_county=39883800 m:cecil_county=3714143 m:harford_county=10945062 m:caroline_county=1012352 m:frederick_county=10170171 m:charles_county=5926007 m:somerset_county=691994 m:maryland=272708997 m:anne_arundel_county=28398667 m:howard_county=17242937 m:worcester_county=2017345 m:allegany_county=2141023 m:dorchester_county=1042493

series e:4dhw-3gak d:2013-07-01T00:00:00.000Z m:baltimore_city=23286075 m:calvert_county=3942292 m:st_mary_s_county=4146780 m:wicomico_county=3336713 m:prince_george_s_county=33005948 m:washington_county=5184000 m:carroll_county=7376533 m:montgomery_county=65804274 m:garrett_county=1054213 m:talbot_county=2168853 m:kent_county=918125 m:queen_anne_s_county=2241903 m:baltimore_county=39983378 m:cecil_county=3780578 m:harford_county=11183452 m:caroline_county=1021959 m:frederick_county=10465884 m:charles_county=6095617 m:somerset_county=710113 m:maryland=277617895 m:anne_arundel_county=28786815 m:howard_county=17648259 m:worcester_county=2140235 m:allegany_county=2243982 m:dorchester_county=1091914
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

entity e:4dhw-3gak l:"Maryland Total Personal Income (Thousands of Constant 2009 Dollars): 2006-2011" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/4dhw-3gak

property e:4dhw-3gak t:meta.view v:id=4dhw-3gak v:category=Demographic v:attributionLink=http://planning.maryland.gov/msdc/md_statistical_handbook11.pdf v:averageRating=0 v:name="Maryland Total Personal Income (Thousands of Constant 2009 Dollars): 2006-2011" v:attribution="Maryland Department of Planning"

property e:4dhw-3gak t:meta.view.license v:name="Public Domain"

property e:4dhw-3gak t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:4dhw-3gak t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| date_created | year | maryland  | allegany_county | anne_arundel_county | baltimore_city | baltimore_county | calvert_county | caroline_county | carroll_county | cecil_county | charles_county | dorchester_county | frederick_county | garrett_county | harford_county | howard_county | kent_county | montgomery_county | prince_george_s_county | queen_anne_s_county | somerset_county | st_mary_s_county | talbot_county | washington_county | wicomico_county | worcester_county | 
| ============ | ==== | ========= | =============== | =================== | ============== | ================ | ============== | =============== | ============== | ============ | ============== | ================= | ================ | ============== | ============== | ============= | =========== | ================= | ====================== | =================== | =============== | ================ | ============= | ================= | =============== | ================ | 
| 7/1/2013     | 2006 | 266479826 | 2086720         | 27723343            | 22090847       | 39096902         | 3686609        | 977002          | 7148162        | 3581584      | 5747807        | 998816            | 9795147          | 1000892        | 10598449       | 16689993      | 922405      | 63732253          | 31993572               | 2096119             | 662804          | 3822017          | 2070147       | 4911412           | 3094961         | 1951862          | 
| 7/1/2013     | 2007 | 272708997 | 2141023         | 28398667            | 22732361       | 39883800         | 3825394        | 1012352         | 7249109        | 3714143      | 5926007        | 1042493           | 10170171         | 1018063        | 10945062       | 17242937      | 920646      | 64515335          | 32702276               | 2164421             | 691994          | 4007943          | 2102859       | 5067754           | 3216843         | 2017345          | 
| 7/1/2013     | 2008 | 277617895 | 2243982         | 28786815            | 23286075       | 39983378         | 3942292        | 1021959         | 7376533        | 3780578      | 6095617        | 1091914           | 10465884         | 1054213        | 11183452       | 17648259      | 918125      | 65804274          | 33005948               | 2241903             | 710113          | 4146780          | 2168853       | 5184000           | 3336713         | 2140235          | 
| 7/1/2013     | 2009 | 271728830 | 2292903         | 28303880            | 23398934       | 38239406         | 3944473        | 1005086         | 7212930        | 3738490      | 6125410        | 1083995           | 10285902         | 1050487        | 11074625       | 17436676      | 861001      | 62962957          | 33156357               | 2171411             | 713034          | 4271985          | 1976296       | 5100100           | 3269987         | 2052505          | 
| 7/1/2013     | 2010 | 276727826 | 2314140         | 28655295            | 24104090       | 38670042         | 3994219        | 1016100         | 7194253        | 3775211      | 6246789        | 1072503           | 10370860         | 1076315        | 11328801       | 17960040      | 846032      | 64832071          | 33337233               | 2221498             | 715302          | 4463981          | 1976784       | 5145036           | 3299232         | 2112000          | 
| 7/1/2013     | 2011 | 283645751 | 2357657         | 29431216            | 25018654       | 39628200         | 4071813        | 1040050         | 7313918        | 3877730      | 6415569        | 1090383           | 10601497         | 1110486        | 11681828       | 18672351      | 863567      | 66339533          | 33661242               | 2304464             | 718329          | 4631304          | 2035616       | 5269383           | 3333975         | 2176988          | 
```