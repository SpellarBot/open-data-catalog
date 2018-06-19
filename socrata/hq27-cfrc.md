# Maryland International Migration: 2000-2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-international-migration-2000-2012-5e7b4) |
| Metadata | [Link](https://data.maryland.gov/api/views/hq27-cfrc) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/hq27-cfrc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/hq27-cfrc/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | hq27-cfrc |
| Name | Maryland International Migration: 2000-2012 |
| Attribution | Maryland Department of Planning |
| Category | Demographic |
| Tags | international, migration, planning, mdp |
| Created | 2012-12-21T16:07:35Z |
| Publication Date | 2013-11-14T17:45:07Z |

## Description

Maryland International Migration from 2000 to 2012, which 
includes net foreign-born international migration, net movement to/ from Puerto Rico, net Armed Forces movement and native emigration. Source from the Population Division, U.S. Census Bureau

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | time           | date_created           | Date created           | text      | text        |
| No       |                | year                   | Year                   | number    | text        |
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
series e:hq27-cfrc d:2013-07-01T00:00:00.000Z m:baltimore_city=1185 m:calvert_county=58 m:st_mary_s_county=56 m:wicomico_county=192 m:prince_george_s_county=5058 m:washington_county=102 m:carroll_county=66 m:montgomery_county=10246 m:garrett_county=6 m:talbot_county=38 m:kent_county=12 m:queen_anne_s_county=54 m:baltimore_county=1987 m:cecil_county=59 m:harford_county=144 m:caroline_county=70 m:frederick_county=257 m:charles_county=72 m:somerset_county=34 m:maryland=21486 m:anne_arundel_county=629 m:howard_county=1066 m:worcester_county=71 m:allegany_county=16 m:dorchester_county=8

series e:hq27-cfrc d:2013-07-01T00:00:00.000Z m:baltimore_city=1164 m:calvert_county=32 m:st_mary_s_county=-75 m:wicomico_county=179 m:prince_george_s_county=4846 m:washington_county=90 m:carroll_county=61 m:montgomery_county=10143 m:garrett_county=5 m:talbot_county=40 m:kent_county=11 m:queen_anne_s_county=53 m:baltimore_county=1926 m:cecil_county=53 m:harford_county=53 m:caroline_county=71 m:frederick_county=210 m:charles_county=-29 m:somerset_county=34 m:maryland=20010 m:anne_arundel_county=53 m:howard_county=999 m:worcester_county=69 m:allegany_county=15 m:dorchester_county=7

series e:hq27-cfrc d:2013-07-01T00:00:00.000Z m:baltimore_city=1011 m:calvert_county=-26 m:st_mary_s_county=-325 m:wicomico_county=155 m:prince_george_s_county=3948 m:washington_county=63 m:carroll_county=47 m:montgomery_county=9130 m:garrett_county=5 m:talbot_county=38 m:kent_county=8 m:queen_anne_s_county=42 m:baltimore_county=1658 m:cecil_county=42 m:harford_county=-130 m:caroline_county=70 m:frederick_county=97 m:charles_county=-231 m:somerset_county=31 m:maryland=15408 m:anne_arundel_county=-1104 m:howard_county=811 m:worcester_county=59 m:allegany_county=7 m:dorchester_county=2
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

entity e:hq27-cfrc l:"Maryland International Migration: 2000-2012" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/hq27-cfrc

property e:hq27-cfrc t:meta.view v:id=hq27-cfrc v:category=Demographic v:attributionLink=http://planning.maryland.gov/msdc/md_statistical_handbook12.pdf v:averageRating=0 v:name="Maryland International Migration: 2000-2012" v:attribution="Maryland Department of Planning"

property e:hq27-cfrc t:meta.view.license v:name="Public Domain"

property e:hq27-cfrc t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:hq27-cfrc t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| date_created | year | maryland | allegany_county | anne_arundel_county | baltimore_city | baltimore_county | calvert_county | caroline_county | carroll_county | cecil_county | charles_county | dorchester_county | frederick_county | garrett_county | harford_county | howard_county | kent_county | montgomery_county | prince_george_s_county | queen_anne_s_county | somerset_county | st_mary_s_county | talbot_county | washington_county | wicomico_county | worcester_county | 
| ============ | ==== | ======== | =============== | =================== | ============== | ================ | ============== | =============== | ============== | ============ | ============== | ================= | ================ | ============== | ============== | ============= | =========== | ================= | ====================== | =================== | =============== | ================ | ============= | ================= | =============== | ================ | 
| 7/1/2013     | 2001 | 21486    | 16              | 629                 | 1185           | 1987             | 58             | 70              | 66             | 59           | 72             | 8                 | 257              | 6              | 144            | 1066          | 12          | 10246             | 5058                   | 54                  | 34              | 56               | 38            | 102               | 192             | 71               | 
| 7/1/2013     | 2002 | 20010    | 15              | 53                  | 1164           | 1926             | 32             | 71              | 61             | 53           | -29            | 7                 | 210              | 5              | 53             | 999           | 11          | 10143             | 4846                   | 53                  | 34              | -75              | 40            | 90                | 179             | 69               | 
| 7/1/2013     | 2003 | 15408    | 7               | -1104               | 1011           | 1658             | -26            | 70              | 47             | 42           | -231           | 2                 | 97               | 5              | -130           | 811           | 8           | 9130              | 3948                   | 42                  | 31              | -325             | 38            | 63                | 155             | 59               | 
| 7/1/2013     | 2004 | 21393    | 15              | 1350                | 1043           | 1668             | 91             | 77              | 78             | 61           | 213            | 11                | 297              | 6              | 221            | 976           | 10          | 9340              | 5231                   | 49                  | 34              | 244              | 44            | 96                | 172             | 66               | 
| 7/1/2013     | 2005 | 21141    | 13              | 508                 | 1132           | 1805             | 50             | 81              | 74             | 59           | 53             | 8                 | 247              | 7              | 102            | 993           | 10          | 10154             | 5351                   | 47                  | 38              | 40               | 44            | 91                | 169             | 65               | 
| 7/1/2013     | 2006 | 22574    | 15              | 1032                | 1150           | 1834             | 74             | 88              | 82             | 64           | 147            | 11                | 296              | 7              | 182            | 1041          | 11          | 10265             | 5634                   | 49                  | 39              | 152              | 45            | 99                | 189             | 68               | 
| 7/1/2013     | 2007 | 19328    | 12              | 491                 | 1023           | 1618             | 46             | 77              | 65             | 59           | 56             | 9                 | 228              | 7              | 93             | 912           | 8           | 9267              | 4883                   | 44                  | 33              | 42               | 40            | 83                | 171             | 61               | 
| 7/1/2013     | 2008 | 18849    | 11              | 632                 | 979            | 1539             | 53             | 80              | 65             | 57           | 84             | 10                | 235              | 5              | 113            | 876           | 7           | 8854              | 4740                   | 43                  | 31              | 80               | 39            | 83                | 172             | 61               | 
| 7/1/2013     | 2009 | 16608    | 10              | 434                 | 865            | 1357             | 42             | 74              | 57             | 46           | 56             | 10                | 197              | 6              | 80             | 753           | 8           | 7967              | 4207                   | 39                  | 28              | 46               | 37            | 72                | 161             | 56               | 
| 7/1/2013     | 2010 | 17133    | 12              | 714                 | 852            | 1337             | 57             | 76              | 61             | 48           | 108            | 11                | 220              | 6              | 121            | 766           | 8           | 7911              | 4305                   | 41                  | 29              | 114              | 38            | 77                | 164             | 57               | 
```