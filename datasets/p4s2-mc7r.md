# Maryland Total Acres For Residential Development: 2006-2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-total-acres-for-residential-development-2006-2010-a0976) |
| Metadata | [Link](https://data.maryland.gov/api/views/p4s2-mc7r) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/p4s2-mc7r/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/p4s2-mc7r/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | p4s2-mc7r |
| Name | Maryland Total Acres For Residential Development: 2006-2010 |
| Attribution | Maryland Department of Planning |
| Category | Housing |
| Tags | total, acres, residential, development, planning, mdp |
| Created | 2012-12-21T17:40:29Z |
| Publication Date | 2013-11-20T15:57:10Z |
| Rows Updated | 2013-11-20T15:55:56Z |

## Description

Total Acres used for Residential Development in Maryland and its Counties from 2006 to 2010.

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
series e:p4s2-mc7r d:2013-07-01T00:00:00.000Z m:baltimore_city=20 m:calvert_county=410 m:st_mary_s_county=1051 m:wicomico_county=511 m:prince_george_s_county=1423 m:washington_county=858 m:carroll_county=696 m:montgomery_county=652 m:garrett_county=619 m:talbot_county=317 m:kent_county=124 m:queen_anne_s_county=276 m:baltimore_county=1031 m:cecil_county=403 m:harford_county=1097 m:caroline_county=264 m:frederick_county=909 m:charles_county=1051 m:somerset_county=337 m:maryland=14358 m:anne_arundel_county=737 m:howard_county=523 m:worcester_county=488 m:allegany_county=275 m:dorchester_county=288

series e:p4s2-mc7r d:2013-07-01T00:00:00.000Z m:baltimore_city=16 m:calvert_county=350 m:st_mary_s_county=775 m:wicomico_county=305 m:prince_george_s_county=1180 m:washington_county=415 m:carroll_county=470 m:montgomery_county=528 m:garrett_county=449 m:talbot_county=217 m:kent_county=148 m:queen_anne_s_county=265 m:baltimore_county=836 m:cecil_county=317 m:harford_county=713 m:caroline_county=227 m:frederick_county=612 m:charles_county=553 m:somerset_county=251 m:maryland=10558 m:anne_arundel_county=620 m:howard_county=355 m:worcester_county=329 m:allegany_county=336 m:dorchester_county=292

series e:p4s2-mc7r d:2013-07-01T00:00:00.000Z m:baltimore_city=16 m:calvert_county=203 m:st_mary_s_county=668 m:wicomico_county=226 m:prince_george_s_county=651 m:washington_county=305 m:carroll_county=266 m:montgomery_county=427 m:garrett_county=383 m:talbot_county=187 m:kent_county=61 m:queen_anne_s_county=210 m:baltimore_county=501 m:cecil_county=219 m:harford_county=424 m:caroline_county=152 m:frederick_county=423 m:charles_county=449 m:somerset_county=185 m:maryland=7522 m:anne_arundel_county=635 m:howard_county=374 m:worcester_county=178 m:allegany_county=192 m:dorchester_county=185
```

## Meta Commands

```ls
metric m:maryland p:long l:MARYLAND t:dataTypeName=number

metric m:allegany_county p:float l:"Allegany County" t:dataTypeName=number

metric m:anne_arundel_county p:float l:"Anne Arundel County" t:dataTypeName=number

metric m:baltimore_city p:float l:"Baltimore City" t:dataTypeName=number

metric m:baltimore_county p:long l:"Baltimore County" t:dataTypeName=number

metric m:calvert_county p:float l:"Calvert County" t:dataTypeName=number

metric m:caroline_county p:float l:"Caroline County" t:dataTypeName=number

metric m:carroll_county p:float l:"Carroll County" t:dataTypeName=number

metric m:cecil_county p:float l:"Cecil County" t:dataTypeName=number

metric m:charles_county p:long l:"Charles County" t:dataTypeName=number

metric m:dorchester_county p:float l:"Dorchester County" t:dataTypeName=number

metric m:frederick_county p:float l:"Frederick County" t:dataTypeName=number

metric m:garrett_county p:float l:"Garrett County" t:dataTypeName=number

metric m:harford_county p:long l:"Harford County" t:dataTypeName=number

metric m:howard_county p:float l:"Howard County" t:dataTypeName=number

metric m:kent_county p:float l:"Kent County" t:dataTypeName=number

metric m:montgomery_county p:float l:"Montgomery County" t:dataTypeName=number

metric m:prince_george_s_county p:long l:"Prince George's County" t:dataTypeName=number

metric m:queen_anne_s_county p:float l:"Queen Anne's County" t:dataTypeName=number

metric m:somerset_county p:float l:"Somerset County" t:dataTypeName=number

metric m:st_mary_s_county p:long l:"St. Mary's County" t:dataTypeName=number

metric m:talbot_county p:float l:"Talbot County" t:dataTypeName=number

metric m:washington_county p:float l:"Washington County" t:dataTypeName=number

metric m:wicomico_county p:float l:"Wicomico County" t:dataTypeName=number

metric m:worcester_county p:float l:"Worcester County" t:dataTypeName=number

entity e:p4s2-mc7r l:"Maryland Total Acres For Residential Development: 2006-2010" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/p4s2-mc7r

property e:p4s2-mc7r t:meta.view v:id=p4s2-mc7r v:category=Housing v:attributionLink=http://planning.maryland.gov/msdc/md_statistical_handbook12.pdf v:averageRating=0 v:name="Maryland Total Acres For Residential Development: 2006-2010" v:attribution="Maryland Department of Planning"

property e:p4s2-mc7r t:meta.view.license v:name="Public Domain"

property e:p4s2-mc7r t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP

property e:p4s2-mc7r t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```