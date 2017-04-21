# Maryland Resident Population Per Square Mile: 2010-2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-resident-population-per-square-mile-2010-2012-64660) |
| Metadata | [Link](https://data.maryland.gov/api/views/key9-38wi) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/key9-38wi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/key9-38wi/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | key9-38wi |
| Name | Maryland Resident Population Per Square Mile: 2010-2012 |
| Attribution | Maryland Department of Planning |
| Category | Demographic |
| Tags | resident, population, mile, per, square, planning, mdp |
| Created | 2012-12-21T17:34:11Z |
| Publication Date | 2013-11-19T19:50:49Z |

## Description

Resident population density for Maryland and Jurisdictions per square mile from 2010 to 2012. Source: U.S. Bureau of Census

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
series e:key9-38wi d:2013-07-01T00:00:00.000Z m:baltimore_city=7684.9 m:calvert_county=413.4 m:st_mary_s_county=292.8 m:wicomico_county=262.2 m:prince_george_s_county=1780.3 m:washington_county=322.6 m:carroll_county=372.4 m:montgomery_county=1973.9 m:garrett_county=46.4 m:talbot_county=140.7 m:kent_county=72.2 m:queen_anne_s_county=128.6 m:baltimore_county=1347 m:cecil_county=290.6 m:harford_county=556.9 m:caroline_county=103.3 m:frederick_county=353.3 m:charles_county=319.1 m:somerset_county=81 m:maryland=592.2 m:anne_arundel_county=1296.7 m:howard_county=1145.1 m:worcester_county=108.7 m:allegany_county=176.3 m:dorchester_county=58.6

series e:key9-38wi d:2013-07-01T00:00:00.000Z m:baltimore_city=7675.6 m:calvert_county=414.8 m:st_mary_s_county=298.1 m:wicomico_county=265 m:prince_george_s_county=1797.4 m:washington_county=324.8 m:carroll_county=372.5 m:montgomery_county=2005.6 m:garrett_county=46.4 m:talbot_county=141.1 m:kent_county=72.5 m:queen_anne_s_county=130 m:baltimore_county=1357.2 m:cecil_county=291.9 m:harford_county=560.1 m:caroline_county=102.9 m:frederick_county=358 m:charles_county=323.7 m:somerset_county=80.6 m:maryland=597.5 m:anne_arundel_county=1309.9 m:howard_county=1166 m:worcester_county=108.7 m:allegany_county=175.1 m:dorchester_county=58.7

series e:key9-38wi d:2013-07-01T00:00:00.000Z m:baltimore_city=7689.5 m:calvert_county=416.5 m:st_mary_s_county=301.7 m:wicomico_county=266.8 m:prince_george_s_county=1812 m:washington_county=325.6 m:carroll_county=372.3 m:montgomery_county=2032 m:garrett_county=46.1 m:talbot_county=141.6 m:kent_county=72.3 m:queen_anne_s_county=130.6 m:baltimore_county=1365.6 m:cecil_county=292.1 m:harford_county=564.6 m:caroline_county=102.2 m:frederick_county=361.4 m:charles_county=326.7 m:somerset_county=80.2 m:maryland=602.1 m:anne_arundel_county=1323.5 m:howard_county=1188 m:worcester_county=109 m:allegany_county=174 m:dorchester_county=58.4
```

## Meta Commands

```ls
metric m:maryland p:float l:MARYLAND t:dataTypeName=number

metric m:allegany_county p:float l:"Allegany County" t:dataTypeName=number

metric m:anne_arundel_county p:float l:"Anne Arundel County" t:dataTypeName=number

metric m:baltimore_city p:float l:"Baltimore City" t:dataTypeName=number

metric m:baltimore_county p:float l:"Baltimore County" t:dataTypeName=number

metric m:calvert_county p:float l:"Calvert County" t:dataTypeName=number

metric m:caroline_county p:float l:"Caroline County" t:dataTypeName=number

metric m:carroll_county p:float l:"Carroll County" t:dataTypeName=number

metric m:cecil_county p:float l:"Cecil County" t:dataTypeName=number

metric m:charles_county p:float l:"Charles County" t:dataTypeName=number

metric m:dorchester_county p:float l:"Dorchester County" t:dataTypeName=number

metric m:frederick_county p:float l:"Frederick County" t:dataTypeName=number

metric m:garrett_county p:float l:"Garrett County" t:dataTypeName=number

metric m:harford_county p:float l:"Harford County" t:dataTypeName=number

metric m:howard_county p:float l:"Howard County" t:dataTypeName=number

metric m:kent_county p:float l:"Kent County" t:dataTypeName=number

metric m:montgomery_county p:float l:"Montgomery County" t:dataTypeName=number

metric m:prince_george_s_county p:float l:"Prince George's County" t:dataTypeName=number

metric m:queen_anne_s_county p:float l:"Queen Anne's County" t:dataTypeName=number

metric m:somerset_county p:float l:"Somerset County" t:dataTypeName=number

metric m:st_mary_s_county p:float l:"St. Mary's County" t:dataTypeName=number

metric m:talbot_county p:float l:"Talbot County" t:dataTypeName=number

metric m:washington_county p:float l:"Washington County" t:dataTypeName=number

metric m:wicomico_county p:float l:"Wicomico County" t:dataTypeName=number

metric m:worcester_county p:float l:"Worcester County" t:dataTypeName=number

entity e:key9-38wi l:"Maryland Resident Population Per Square Mile: 2010-2012" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/key9-38wi

property e:key9-38wi t:meta.view v:id=key9-38wi v:category=Demographic v:attributionLink=http://planning.maryland.gov/msdc/md_statistical_handbook12.pdf v:averageRating=0 v:name="Maryland Resident Population Per Square Mile: 2010-2012" v:attribution="Maryland Department of Planning"

property e:key9-38wi t:meta.view.license v:name="Public Domain"

property e:key9-38wi t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:key9-38wi t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| date_created | year | maryland | allegany_county | anne_arundel_county | baltimore_city | baltimore_county | calvert_county | caroline_county | carroll_county | cecil_county | charles_county | dorchester_county | frederick_county | garrett_county | harford_county | howard_county | kent_county | montgomery_county | prince_george_s_county | queen_anne_s_county | somerset_county | st_mary_s_county | talbot_county | washington_county | wicomico_county | worcester_county | 
| ============ | ==== | ======== | =============== | =================== | ============== | ================ | ============== | =============== | ============== | ============ | ============== | ================= | ================ | ============== | ============== | ============= | =========== | ================= | ====================== | =================== | =============== | ================ | ============= | ================= | =============== | ================ | 
| 7/1/2013     | 2010 | 592.2    | 176.3           | 1296.7              | 7684.9         | 1347.0           | 413.4          | 103.3           | 372.4          | 290.6        | 319.1          | 58.6              | 353.3            | 46.4           | 556.9          | 1145.1        | 72.2        | 1973.9            | 1780.3                 | 128.6               | 81.0            | 292.8            | 140.7         | 322.6             | 262.2           | 108.7            | 
| 7/1/2013     | 2011 | 597.5    | 175.1           | 1309.9              | 7675.6         | 1357.2           | 414.8          | 102.9           | 372.5          | 291.9        | 323.7          | 58.7              | 358.0            | 46.4           | 560.1          | 1166.0        | 72.5        | 2005.6            | 1797.4                 | 130.0               | 80.6            | 298.1            | 141.1         | 324.8             | 265.0           | 108.7            | 
| 7/1/2013     | 2012 | 602.1    | 174.0           | 1323.5              | 7689.5         | 1365.6           | 416.5          | 102.2           | 372.3          | 292.1        | 326.7          | 58.4              | 361.4            | 46.1           | 564.6          | 1188.0        | 72.3        | 2032.0            | 1812.0                 | 130.6               | 80.2            | 301.7            | 141.6         | 325.6             | 266.8           | 109.0            | 
```