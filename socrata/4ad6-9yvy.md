# Maryland Number Of Retail Establishments: 1997, 2002, 2007

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-number-of-retail-establishments-1997-2002-2007-ba820) |
| Metadata | [Link](https://data.maryland.gov/api/views/4ad6-9yvy) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/4ad6-9yvy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/4ad6-9yvy/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 4ad6-9yvy |
| Name | Maryland Number Of Retail Establishments: 1997, 2002, 2007 |
| Attribution | Maryland Department of Planning |
| Category | Business and Economy |
| Tags | total, number, retail, establishments, planning, mdp |
| Created | 2012-12-21T16:58:11Z |
| Publication Date | 2012-12-21T17:04:31Z |

## Description

Maryland total number of retail establishments from 1997, 2002 and 2007. Source from the U.S. Bureau of the Census, 1997, 2002, 2007 Economic Censuses.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | time           | date_created           | Date created           | text      | text        |
| No       |                | year                   | Year                   | number    | text        |
| Yes      | numeric metric | maryland               | MARYLAND               | number    | text        |
| Yes      | numeric metric | allegany_county        | Allegany County        | number    | text        |
| Yes      | numeric metric | anne_arundel_county    | Anne Arundel County    | number    | text        |
| Yes      | numeric metric | baltimore_city         | Baltimore City         | number    | text        |
| Yes      | numeric metric | baltimore_county       | Baltimore County       | number    | text        |
| Yes      | numeric metric | calvert_county         | Calvert County         | number    | text        |
| Yes      | numeric metric | caroline_county        | Caroline County        | number    | text        |
| Yes      | numeric metric | carroll_county         | Carroll County         | number    | text        |
| Yes      | numeric metric | cecil_county           | Cecil County           | number    | text        |
| Yes      | numeric metric | charles_county         | Charles County         | number    | text        |
| Yes      | numeric metric | dorchester_county      | Dorchester County      | number    | text        |
| Yes      | numeric metric | frederick_county       | Frederick County       | number    | text        |
| Yes      | numeric metric | garrett_county         | Garrett County         | number    | text        |
| Yes      | numeric metric | harford_county         | Harford County         | number    | text        |
| Yes      | numeric metric | howard_county          | Howard County          | number    | text        |
| Yes      | numeric metric | kent_county            | Kent County            | number    | text        |
| Yes      | numeric metric | montgomery_county      | Montgomery County      | number    | text        |
| Yes      | numeric metric | prince_george_s_county | Prince George's County | number    | text        |
| Yes      | numeric metric | queen_anne_s_county    | Queen Anne's County    | number    | text        |
| Yes      | numeric metric | somerset_county        | Somerset County        | number    | text        |
| Yes      | numeric metric | st_mary_s_county       | St. Mary's County      | number    | text        |
| Yes      | numeric metric | talbot_county          | Talbot County          | number    | text        |
| Yes      | numeric metric | washington_county      | Washington County      | number    | text        |
| Yes      | numeric metric | wicomico_county        | Wicomico County        | number    | text        |
| Yes      | numeric metric | worcester_county       | Worcester County       | number    | text        |
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
series e:4ad6-9yvy d:2012-12-17T00:00:00.000Z m:baltimore_city=2256 m:calvert_county=190 m:st_mary_s_county=278 m:wicomico_county=464 m:prince_george_s_county=2425 m:washington_county=598 m:carroll_county=604 m:montgomery_county=3000 m:garrett_county=157 m:talbot_county=262 m:kent_county=125 m:queen_anne_s_county=217 m:baltimore_county=3138 m:cecil_county=284 m:harford_county=741 m:caroline_county=104 m:frederick_county=741 m:charles_county=490 m:somerset_county=73 m:maryland=19798 m:anne_arundel_county=1863 m:howard_county=766 m:worcester_county=505 m:allegany_county=385 m:dorchester_county=132

series e:4ad6-9yvy d:2012-12-17T00:00:00.000Z m:baltimore_city=1999 m:calvert_county=202 m:st_mary_s_county=271 m:wicomico_county=457 m:prince_george_s_county=2295 m:washington_county=659 m:carroll_county=568 m:montgomery_county=2963 m:garrett_county=152 m:talbot_county=270 m:kent_county=123 m:queen_anne_s_county=218 m:baltimore_county=2963 m:cecil_county=310 m:harford_county=739 m:caroline_county=93 m:frederick_county=769 m:charles_county=518 m:somerset_county=67 m:maryland=19394 m:anne_arundel_county=2007 m:howard_county=812 m:worcester_county=467 m:allegany_county=353 m:dorchester_county=119

series e:4ad6-9yvy d:2012-12-17T00:00:00.000Z m:baltimore_city=1950 m:calvert_county=230 m:st_mary_s_county=314 m:wicomico_county=445 m:prince_george_s_county=2265 m:washington_county=673 m:carroll_county=580 m:montgomery_county=2952 m:garrett_county=160 m:talbot_county=262 m:kent_county=106 m:queen_anne_s_county=249 m:baltimore_county=2991 m:cecil_county=286 m:harford_county=774 m:caroline_county=100 m:frederick_county=790 m:charles_county=540 m:somerset_county=61 m:maryland=19601 m:anne_arundel_county=2126 m:howard_county=866 m:worcester_county=458 m:allegany_county=304 m:dorchester_county=119
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

entity e:4ad6-9yvy l:"Maryland Number Of Retail Establishments: 1997, 2002, 2007" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/4ad6-9yvy

property e:4ad6-9yvy t:meta.view v:id=4ad6-9yvy v:category="Business and Economy" v:attributionLink=http://planning.maryland.gov/msdc/md_statistical_handbook11.pdf v:averageRating=0 v:name="Maryland Number Of Retail Establishments: 1997, 2002, 2007" v:attribution="Maryland Department of Planning"

property e:4ad6-9yvy t:meta.view.license v:name="Public Domain"

property e:4ad6-9yvy t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:4ad6-9yvy t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| date_created | year | maryland | allegany_county | anne_arundel_county | baltimore_city | baltimore_county | calvert_county | caroline_county | carroll_county | cecil_county | charles_county | dorchester_county | frederick_county | garrett_county | harford_county | howard_county | kent_county | montgomery_county | prince_george_s_county | queen_anne_s_county | somerset_county | st_mary_s_county | talbot_county | washington_county | wicomico_county | worcester_county | 
| ============ | ==== | ======== | =============== | =================== | ============== | ================ | ============== | =============== | ============== | ============ | ============== | ================= | ================ | ============== | ============== | ============= | =========== | ================= | ====================== | =================== | =============== | ================ | ============= | ================= | =============== | ================ | 
| 12/17/2012   | 1997 | 19798    | 385             | 1863                | 2256           | 3138             | 190            | 104             | 604            | 284          | 490            | 132               | 741              | 157            | 741            | 766           | 125         | 3000              | 2425                   | 217                 | 73              | 278              | 262           | 598               | 464             | 505              | 
| 12/17/2012   | 2002 | 19394    | 353             | 2007                | 1999           | 2963             | 202            | 93              | 568            | 310          | 518            | 119               | 769              | 152            | 739            | 812           | 123         | 2963              | 2295                   | 218                 | 67              | 271              | 270           | 659               | 457             | 467              | 
| 12/17/2012   | 2007 | 19601    | 304             | 2126                | 1950           | 2991             | 230            | 100             | 580            | 286          | 540            | 119               | 790              | 160            | 774            | 866           | 106         | 2952              | 2265                   | 249                 | 61              | 314              | 262           | 673               | 445             | 458              | 
```