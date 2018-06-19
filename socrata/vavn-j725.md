# Maryland Total Births By Year: 2000-2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-total-births-by-year-2000-2011-990af) |
| Metadata | [Link](https://data.maryland.gov/api/views/vavn-j725) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/vavn-j725/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/vavn-j725/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | vavn-j725 |
| Name | Maryland Total Births By Year: 2000-2011 |
| Attribution | Maryland Department of Planning |
| Category | Demographic |
| Tags | total, births, year, planning, mdp |
| Created | 2012-12-21T17:47:43Z |
| Publication Date | 2013-11-14T19:49:43Z |

## Description

Maryland Total Births from 2000 to 2011. Source from the Maryland Department of Health and Mental Hygiene, Vital Statistics Reports.

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
series e:vavn-j725 d:2013-07-01T00:00:00.000Z m:baltimore_city=9641 m:calvert_county=1024 m:st_mary_s_county=1215 m:wicomico_county=1174 m:prince_george_s_county=12423 m:washington_county=1601 m:carroll_county=1897 m:montgomery_county=13055 m:garrett_county=333 m:talbot_county=369 m:kent_county=203 m:queen_anne_s_county=500 m:baltimore_county=9396 m:cecil_county=1138 m:harford_county=2954 m:caroline_county=407 m:frederick_county=2906 m:charles_county=1746 m:somerset_county=273 m:maryland=74226 m:anne_arundel_county=6790 m:howard_county=3563 m:worcester_county=496 m:allegany_county=794 m:dorchester_county=328

series e:vavn-j725 d:2013-07-01T00:00:00.000Z m:baltimore_city=9100 m:calvert_county=955 m:st_mary_s_county=1266 m:wicomico_county=1136 m:prince_george_s_county=12269 m:washington_county=1622 m:carroll_county=1884 m:montgomery_county=13146 m:garrett_county=328 m:talbot_county=355 m:kent_county=155 m:queen_anne_s_county=470 m:baltimore_county=9056 m:cecil_county=1178 m:harford_county=2895 m:caroline_county=389 m:frederick_county=2897 m:charles_county=1747 m:somerset_county=244 m:maryland=73152 m:anne_arundel_county=6893 m:howard_county=3602 m:worcester_county=521 m:allegany_county=708 m:dorchester_county=336

series e:vavn-j725 d:2013-07-01T00:00:00.000Z m:baltimore_city=9046 m:calvert_county=1012 m:st_mary_s_county=1337 m:wicomico_county=1156 m:prince_george_s_county=12403 m:washington_county=1691 m:carroll_county=1898 m:montgomery_county=13154 m:garrett_county=300 m:talbot_county=334 m:kent_county=157 m:queen_anne_s_county=532 m:baltimore_county=8997 m:cecil_county=1158 m:harford_county=2901 m:caroline_county=385 m:frederick_county=3008 m:charles_county=1753 m:somerset_county=259 m:maryland=73250 m:anne_arundel_county=6785 m:howard_county=3509 m:worcester_county=455 m:allegany_county=712 m:dorchester_county=308
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

entity e:vavn-j725 l:"Maryland Total Births By Year: 2000-2011" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/vavn-j725

property e:vavn-j725 t:meta.view v:id=vavn-j725 v:category=Demographic v:attributionLink=http://planning.maryland.gov/msdc/md_statistical_handbook11.pdf v:averageRating=0 v:name="Maryland Total Births By Year: 2000-2011" v:attribution="Maryland Department of Planning"

property e:vavn-j725 t:meta.view.license v:name="Public Domain"

property e:vavn-j725 t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:vavn-j725 t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| date_created | year | maryland | allegany_county | anne_arundel_county | baltimore_city | baltimore_county | calvert_county | caroline_county | carroll_county | cecil_county | charles_county | dorchester_county | frederick_county | garrett_county | harford_county | howard_county | kent_county | montgomery_county | prince_george_s_county | queen_anne_s_county | somerset_county | st_mary_s_county | talbot_county | washington_county | wicomico_county | worcester_county | 
| ============ | ==== | ======== | =============== | =================== | ============== | ================ | ============== | =============== | ============== | ============ | ============== | ================= | ================ | ============== | ============== | ============= | =========== | ================= | ====================== | =================== | =============== | ================ | ============= | ================= | =============== | ================ | 
| 7/1/2013     | 2000 | 74226    | 794             | 6790                | 9641           | 9396             | 1024           | 407             | 1897           | 1138         | 1746           | 328               | 2906             | 333            | 2954           | 3563          | 203         | 13055             | 12423                  | 500                 | 273             | 1215             | 369           | 1601              | 1174            | 496              | 
| 7/1/2013     | 2001 | 73152    | 708             | 6893                | 9100           | 9056             | 955            | 389             | 1884           | 1178         | 1747           | 336               | 2897             | 328            | 2895           | 3602          | 155         | 13146             | 12269                  | 470                 | 244             | 1266             | 355           | 1622              | 1136            | 521              | 
| 7/1/2013     | 2002 | 73250    | 712             | 6785                | 9046           | 8997             | 1012           | 385             | 1898           | 1158         | 1753           | 308               | 3008             | 300            | 2901           | 3509          | 157         | 13154             | 12403                  | 532                 | 259             | 1337             | 334           | 1691              | 1156            | 455              | 
| 7/1/2013     | 2003 | 74865    | 675             | 6913                | 9057           | 9344             | 1057           | 419             | 1955           | 1219         | 1889           | 348               | 3093             | 342            | 2905           | 3569          | 167         | 13529             | 12591                  | 501                 | 259             | 1352             | 341           | 1689              | 1182            | 469              | 
| 7/1/2013     | 2004 | 74500    | 641             | 6767                | 9183           | 9448             | 997            | 465             | 1990           | 1211         | 1820           | 365               | 2954             | 316            | 2988           | 3470          | 202         | 13546             | 12205                  | 509                 | 266             | 1449             | 388           | 1705              | 1166            | 449              | 
| 7/1/2013     | 2005 | 74880    | 648             | 6751                | 9179           | 9712             | 1001           | 428             | 1926           | 1217         | 1864           | 325               | 3030             | 314            | 2938           | 3314          | 181         | 13507             | 12545                  | 520                 | 265             | 1389             | 363           | 1756              | 1212            | 495              | 
| 7/1/2013     | 2006 | 77430    | 710             | 7102                | 9757           | 9947             | 1008           | 477             | 1881           | 1356         | 1953           | 406               | 3100             | 297            | 3028           | 3377          | 189         | 13807             | 12685                  | 516                 | 279             | 1492             | 357           | 1907              | 1333            | 466              | 
| 7/1/2013     | 2007 | 78057    | 684             | 7115                | 9875           | 10151            | 978            | 467             | 1861           | 1323         | 1980           | 412               | 3089             | 315            | 3025           | 3496          | 178         | 13843             | 12802                  | 557                 | 250             | 1473             | 368           | 1976              | 1339            | 500              | 
| 7/1/2013     | 2008 | 77268    | 712             | 7156                | 9911           | 10208            | 954            | 499             | 1749           | 1278         | 1919           | 451               | 2971             | 277            | 2983           | 3417          | 219         | 13681             | 12569                  | 532                 | 277             | 1450             | 387           | 1825              | 1364            | 479              | 
| 7/1/2013     | 2009 | 74999    | 740             | 7103                | 9504           | 9910             | 924            | 445             | 1572           | 1185         | 1808           | 411               | 2891             | 306            | 2849           | 3314          | 188         | 13493             | 12252                  | 501                 | 247             | 1479             | 351           | 1754              | 1312            | 460              | 
```