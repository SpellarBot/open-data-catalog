# Maryland Total Deaths By Year: 2000-2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-total-deaths-by-year-2000-2011-f14e1) |
| Metadata | [Link](https://data.maryland.gov/api/views/jadi-9c9a) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/jadi-9c9a/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/jadi-9c9a/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | jadi-9c9a |
| Name | Maryland Total Deaths By Year: 2000-2011 |
| Attribution | Maryland Department of Planning |
| Category | Demographic |
| Tags | total, deaths, year, planning, mdp |
| Created | 2012-12-21T17:51:08Z |
| Publication Date | 2013-11-14T19:53:30Z |

## Description

Maryland Total Deaths by Year by 2000 to 2011. Source from the Maryland Department of Health and Mental Hygiene, Vital Statistics Reports.

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
series e:jadi-9c9a d:2013-07-01T00:00:00.000Z m:baltimore_city=8390 m:calvert_county=494 m:st_mary_s_county=602 m:wicomico_county=820 m:prince_george_s_county=4978 m:washington_county=1279 m:carroll_county=1143 m:montgomery_county=5455 m:garrett_county=290 m:talbot_county=394 m:kent_county=208 m:queen_anne_s_county=338 m:baltimore_county=7657 m:cecil_county=687 m:harford_county=1490 m:caroline_county=336 m:frederick_county=1287 m:charles_county=753 m:somerset_county=271 m:maryland=43602 m:anne_arundel_county=3554 m:howard_county=1315 m:worcester_county=553 m:allegany_county=910 m:dorchester_county=398

series e:jadi-9c9a d:2013-07-01T00:00:00.000Z m:baltimore_city=8096 m:calvert_county=507 m:st_mary_s_county=550 m:wicomico_county=792 m:prince_george_s_county=5087 m:washington_county=1283 m:carroll_county=1209 m:montgomery_county=5462 m:garrett_county=314 m:talbot_county=420 m:kent_county=246 m:queen_anne_s_county=367 m:baltimore_county=7663 m:cecil_county=738 m:harford_county=1550 m:caroline_county=317 m:frederick_county=1347 m:charles_county=801 m:somerset_county=245 m:maryland=43673 m:anne_arundel_county=3551 m:howard_county=1274 m:worcester_county=581 m:allegany_county=869 m:dorchester_county=404

series e:jadi-9c9a d:2013-07-01T00:00:00.000Z m:baltimore_city=7907 m:calvert_county=556 m:st_mary_s_county=605 m:wicomico_county=785 m:prince_george_s_county=5240 m:washington_county=1299 m:carroll_county=1187 m:montgomery_county=5420 m:garrett_county=322 m:talbot_county=401 m:kent_county=234 m:queen_anne_s_county=363 m:baltimore_county=7647 m:cecil_county=720 m:harford_county=1603 m:caroline_county=320 m:frederick_county=1374 m:charles_county=834 m:somerset_county=271 m:maryland=43917 m:anne_arundel_county=3648 m:howard_county=1336 m:worcester_county=531 m:allegany_county=917 m:dorchester_county=397
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

entity e:jadi-9c9a l:"Maryland Total Deaths By Year: 2000-2011" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/jadi-9c9a

property e:jadi-9c9a t:meta.view v:id=jadi-9c9a v:category=Demographic v:attributionLink=http://planning.maryland.gov/msdc/md_statistical_handbook12.pdf v:averageRating=0 v:name="Maryland Total Deaths By Year: 2000-2011" v:attribution="Maryland Department of Planning"

property e:jadi-9c9a t:meta.view.license v:name="Public Domain"

property e:jadi-9c9a t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:jadi-9c9a t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| date_created | year | maryland | allegany_county | anne_arundel_county | baltimore_city | baltimore_county | calvert_county | caroline_county | carroll_county | cecil_county | charles_county | dorchester_county | frederick_county | garrett_county | harford_county | howard_county | kent_county | montgomery_county | prince_george_s_county | queen_anne_s_county | somerset_county | st_mary_s_county | talbot_county | washington_county | wicomico_county | worcester_county | 
| ============ | ==== | ======== | =============== | =================== | ============== | ================ | ============== | =============== | ============== | ============ | ============== | ================= | ================ | ============== | ============== | ============= | =========== | ================= | ====================== | =================== | =============== | ================ | ============= | ================= | =============== | ================ | 
| 7/1/2013     | 2000 | 43602    | 910             | 3554                | 8390           | 7657             | 494            | 336             | 1143           | 687          | 753            | 398               | 1287             | 290            | 1490           | 1315          | 208         | 5455              | 4978                   | 338                 | 271             | 602              | 394           | 1279              | 820             | 553              | 
| 7/1/2013     | 2001 | 43673    | 869             | 3551                | 8096           | 7663             | 507            | 317             | 1209           | 738          | 801            | 404               | 1347             | 314            | 1550           | 1274          | 246         | 5462              | 5087                   | 367                 | 245             | 550              | 420           | 1283              | 792             | 581              | 
| 7/1/2013     | 2002 | 43917    | 917             | 3648                | 7907           | 7647             | 556            | 320             | 1187           | 720          | 834            | 397               | 1374             | 322            | 1603           | 1336          | 234         | 5420              | 5240                   | 363                 | 271             | 605              | 401           | 1299              | 785             | 531              | 
| 7/1/2013     | 2003 | 44364    | 901             | 3567                | 7853           | 7717             | 538            | 311             | 1283           | 714          | 844            | 393               | 1438             | 296            | 1653           | 1327          | 247         | 5559              | 5278                   | 366                 | 291             | 631              | 394           | 1358              | 832             | 573              | 
| 7/1/2013     | 2004 | 43157    | 898             | 3494                | 7322           | 7379             | 577            | 302             | 1234           | 727          | 871            | 348               | 1388             | 319            | 1707           | 1231          | 264         | 5491              | 5270                   | 367                 | 258             | 597              | 407           | 1352              | 820             | 534              | 
| 7/1/2013     | 2005 | 43778    | 930             | 3665                | 7221           | 7784             | 606            | 296             | 1284           | 722          | 856            | 386               | 1450             | 307            | 1708           | 1328          | 204         | 5448              | 5119                   | 366                 | 232             | 679              | 440           | 1367              | 864             | 516              | 
| 7/1/2013     | 2006 | 43491    | 889             | 3763                | 7017           | 7710             | 615            | 320             | 1285           | 763          | 841            | 372               | 1392             | 271            | 1721           | 1314          | 257         | 5400              | 5190                   | 354                 | 254             | 653              | 443           | 1231              | 872             | 564              | 
| 7/1/2013     | 2007 | 43597    | 911             | 3653                | 6902           | 7568             | 611            | 304             | 1247           | 842          | 808            | 372               | 1421             | 310            | 1789           | 1368          | 251         | 5452              | 5090                   | 386                 | 243             | 670              | 447           | 1420              | 954             | 578              | 
| 7/1/2013     | 2008 | 43849    | 856             | 3830                | 6509           | 7692             | 609            | 315             | 1329           | 812          | 878            | 356               | 1477             | 321            | 1811           | 1474          | 254         | 5560              | 5268                   | 356                 | 225             | 653              | 455           | 1334              | 885             | 590              | 
| 7/1/2013     | 2009 | 43763    | 877             | 3695                | 6503           | 7829             | 586            | 328             | 1337           | 857          | 871            | 370               | 1472             | 325            | 1797           | 1404          | 265         | 5493              | 5133                   | 343                 | 271             | 703              | 440           | 1351              | 923             | 590              | 
```