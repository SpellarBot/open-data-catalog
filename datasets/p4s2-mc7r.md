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
| Yes      | series tag     | allegany_county        | Allegany County        | text      | text        |
| Yes      | series tag     | anne_arundel_county    | Anne Arundel County    | text      | text        |
| Yes      | numeric metric | baltimore_city         | Baltimore City         | number    | text        |
| Yes      | series tag     | baltimore_county       | Baltimore County       | text      | text        |
| Yes      | series tag     | calvert_county         | Calvert County         | text      | text        |
| Yes      | series tag     | caroline_county        | Caroline County        | text      | text        |
| Yes      | series tag     | carroll_county         | Carroll County         | text      | text        |
| Yes      | series tag     | cecil_county           | Cecil County           | text      | text        |
| Yes      | series tag     | charles_county         | Charles County         | text      | text        |
| Yes      | series tag     | dorchester_county      | Dorchester County      | text      | text        |
| Yes      | series tag     | frederick_county       | Frederick County       | text      | text        |
| Yes      | series tag     | garrett_county         | Garrett County         | text      | text        |
| Yes      | series tag     | harford_county         | Harford County         | text      | text        |
| Yes      | series tag     | howard_county          | Howard County          | text      | text        |
| Yes      | series tag     | kent_county            | Kent County            | text      | text        |
| Yes      | series tag     | montgomery_county      | Montgomery County      | text      | text        |
| Yes      | series tag     | prince_george_s_county | Prince George's County | text      | text        |
| Yes      | series tag     | queen_anne_s_county    | Queen Anne's County    | text      | text        |
| Yes      | series tag     | somerset_county        | Somerset County        | text      | text        |
| Yes      | series tag     | st_mary_s_county       | St. Mary's County      | text      | text        |
| Yes      | series tag     | talbot_county          | Talbot County          | text      | text        |
| Yes      | series tag     | washington_county      | Washington County      | text      | text        |
| Yes      | series tag     | wicomico_county        | Wicomico County        | text      | text        |
| Yes      | series tag     | worcester_county       | Worcester County       | text      | text        |
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
series e:p4s2-mc7r d:2013-07-01T00:00:00.000Z t:calvert_county=410.0 t:st_mary_s_county=1,051.0 t:wicomico_county=511.0 t:prince_george_s_county=1,423.0 t:washington_county=858.0 t:carroll_county=696.0 t:montgomery_county=652.0 t:garrett_county=619.0 t:talbot_county=317.0 t:kent_county=124.0 t:queen_anne_s_county=276.0 t:baltimore_county=1,031.0 t:cecil_county=403.0 t:caroline_county=264.0 t:harford_county=1,097.0 t:frederick_county=909.0 t:charles_county=1,051.0 t:somerset_county=337.0 t:howard_county=523.0 t:anne_arundel_county=737.0 t:worcester_county=488.0 t:allegany_county=275.0 t:dorchester_county=288.0 m:baltimore_city=20 m:maryland=14358

series e:p4s2-mc7r d:2013-07-01T00:00:00.000Z t:calvert_county=350.0 t:st_mary_s_county=775.0 t:wicomico_county=305.0 t:prince_george_s_county=1,180.0 t:washington_county=415.0 t:carroll_county=470.0 t:montgomery_county=528.0 t:garrett_county=449.0 t:talbot_county=217.0 t:kent_county=148.0 t:queen_anne_s_county=265.0 t:baltimore_county=836.0 t:cecil_county=317.0 t:caroline_county=227.0 t:harford_county=713.0 t:frederick_county=612.0 t:charles_county=553.0 t:somerset_county=251.0 t:howard_county=355.0 t:anne_arundel_county=620.0 t:worcester_county=329.0 t:allegany_county=336.0 t:dorchester_county=292.0 m:baltimore_city=16 m:maryland=10558

series e:p4s2-mc7r d:2013-07-01T00:00:00.000Z t:calvert_county=203.0 t:st_mary_s_county=668.0 t:wicomico_county=226.0 t:prince_george_s_county=651.0 t:washington_county=305.0 t:carroll_county=266.0 t:montgomery_county=427.0 t:garrett_county=383.0 t:talbot_county=187.0 t:kent_county=61.0 t:queen_anne_s_county=210.0 t:baltimore_county=501.0 t:cecil_county=219.0 t:caroline_county=152.0 t:harford_county=424.0 t:frederick_county=423.0 t:charles_county=449.0 t:somerset_county=185.0 t:howard_county=374.0 t:anne_arundel_county=635.0 t:worcester_county=178.0 t:allegany_county=192.0 t:dorchester_county=185.0 m:baltimore_city=16 m:maryland=7522
```

## Meta Commands

```ls
metric m:maryland p:long l:MARYLAND t:dataTypeName=number

metric m:baltimore_city p:float l:"Baltimore City" t:dataTypeName=number

entity e:p4s2-mc7r l:"Maryland Total Acres For Residential Development: 2006-2010" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/p4s2-mc7r

property e:p4s2-mc7r t:meta.view v:id=p4s2-mc7r v:category=Housing v:attributionLink=http://planning.maryland.gov/msdc/md_statistical_handbook12.pdf v:averageRating=0 v:name="Maryland Total Acres For Residential Development: 2006-2010" v:attribution="Maryland Department of Planning"

property e:p4s2-mc7r t:meta.view.license v:name="Public Domain"

property e:p4s2-mc7r t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:p4s2-mc7r t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```