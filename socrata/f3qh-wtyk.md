# Maryland Total Acres Inside PFA For Residential Development: 2006-2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-total-acres-inside-pfa-for-residential-development-2006-2010-1cf5b) |
| Metadata | [Link](https://data.maryland.gov/api/views/f3qh-wtyk) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/f3qh-wtyk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/f3qh-wtyk/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | f3qh-wtyk |
| Name | Maryland Total Acres Inside PFA For Residential Development: 2006-2010 |
| Attribution | Maryland Department of Planning |
| Category | Housing |
| Tags | total, acres, inside, pfa, residential, development, planning, mdp |
| Created | 2012-12-21T17:42:34Z |
| Publication Date | 2013-11-20T16:05:35Z |

## Description

Maryland Total Acres inside  Priority Funding Areas (PFA) for residential development from 2006 to 2010. 
Priority Funding Areas are existing communities and places where local governments want State investment to support.

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
series e:f3qh-wtyk d:2013-07-01T00:00:00.000Z m:baltimore_city=20 m:calvert_county=75 m:st_mary_s_county=120 m:wicomico_county=107 m:prince_george_s_county=575 m:washington_county=159 m:carroll_county=119 m:montgomery_county=222 m:garrett_county=25 m:talbot_county=69 m:kent_county=40 m:queen_anne_s_county=44 m:baltimore_county=358 m:cecil_county=89 m:harford_county=197 m:caroline_county=48 m:frederick_county=213 m:charles_county=124 m:somerset_county=90 m:maryland=3402 m:anne_arundel_county=260 m:howard_county=162 m:worcester_county=128 m:allegany_county=98 m:dorchester_county=60

series e:f3qh-wtyk d:2013-07-01T00:00:00.000Z m:baltimore_city=16 m:calvert_county=56 m:st_mary_s_county=102 m:wicomico_county=63 m:prince_george_s_county=452 m:washington_county=93 m:carroll_county=75 m:montgomery_county=216 m:garrett_county=23 m:talbot_county=54 m:kent_county=53 m:queen_anne_s_county=44 m:baltimore_county=306 m:cecil_county=51 m:harford_county=134 m:caroline_county=12 m:frederick_county=128 m:charles_county=84 m:somerset_county=77 m:maryland=2537 m:anne_arundel_county=178 m:howard_county=145 m:worcester_county=60 m:allegany_county=73 m:dorchester_county=42

series e:f3qh-wtyk d:2013-07-01T00:00:00.000Z m:baltimore_city=16 m:calvert_county=25 m:st_mary_s_county=69 m:wicomico_county=43 m:prince_george_s_county=279 m:washington_county=48 m:carroll_county=45 m:montgomery_county=159 m:garrett_county=16 m:talbot_county=34 m:kent_county=18 m:queen_anne_s_county=34 m:baltimore_county=155 m:cecil_county=38 m:harford_county=78 m:caroline_county=9 m:frederick_county=87 m:charles_county=41 m:somerset_county=54 m:maryland=1681 m:anne_arundel_county=182 m:howard_county=147 m:worcester_county=39 m:allegany_county=34 m:dorchester_county=32
```

## Meta Commands

```ls
metric m:maryland p:long l:MARYLAND t:dataTypeName=number

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

entity e:f3qh-wtyk l:"Maryland Total Acres Inside PFA For Residential Development: 2006-2010" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/f3qh-wtyk

property e:f3qh-wtyk t:meta.view v:id=f3qh-wtyk v:category=Housing v:attributionLink=http://planning.maryland.gov/msdc/md_statistical_handbook12.pdf v:averageRating=0 v:name="Maryland Total Acres Inside PFA For Residential Development: 2006-2010" v:attribution="Maryland Department of Planning"

property e:f3qh-wtyk t:meta.view.license v:name="Public Domain"

property e:f3qh-wtyk t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:f3qh-wtyk t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| date_created | year | maryland | allegany_county | anne_arundel_county | baltimore_city | baltimore_county | calvert_county | caroline_county | carroll_county | cecil_county | charles_county | dorchester_county | frederick_county | garrett_county | harford_county | howard_county | kent_county | montgomery_county | prince_george_s_county | queen_anne_s_county | somerset_county | st_mary_s_county | talbot_county | washington_county | wicomico_county | worcester_county | 
| ============ | ==== | ======== | =============== | =================== | ============== | ================ | ============== | =============== | ============== | ============ | ============== | ================= | ================ | ============== | ============== | ============= | =========== | ================= | ====================== | =================== | =============== | ================ | ============= | ================= | =============== | ================ | 
| 7/1/2013     | 2006 | 3,402.0  | 98.0            | 260.0               | 20.0           | 358.0            | 75.0           | 48.0            | 119.0          | 89.0         | 124.0          | 60.0              | 213.0            | 25.0           | 197.0          | 162.0         | 40.0        | 222.0             | 575.0                  | 44.0                | 90.0            | 120.0            | 69.0          | 159.0             | 107.0           | 128.0            | 
| 7/1/2013     | 2007 | 2,537.0  | 73.0            | 178.0               | 16.0           | 306.0            | 56.0           | 12.0            | 75.0           | 51.0         | 84.0           | 42.0              | 128.0            | 23.0           | 134.0          | 145.0         | 53.0        | 216.0             | 452.0                  | 44.0                | 77.0            | 102.0            | 54.0          | 93.0              | 63.0            | 60.0             | 
| 7/1/2013     | 2008 | 1,681.0  | 34.0            | 182.0               | 16.0           | 155.0            | 25.0           | 9.0             | 45.0           | 38.0         | 41.0           | 32.0              | 87.0             | 16.0           | 78.0           | 147.0         | 18.0        | 159.0             | 279.0                  | 34.0                | 54.0            | 69.0             | 34.0          | 48.0              | 43.0            | 39.0             | 
| 7/1/2013     | 2009 | 1,361.0  | 17.0            | 158.0               | 11.0           | 109.0            | 25.0           | 11.0            | 40.0           | 29.0         | 46.0           | 13.0              | 78.0             | 11.0           | 59.0           | 152.0         | 30.0        | 105.0             | 228.0                  | 10.0                | 11.0            | 87.0             | 32.0          | 47.0              | 40.0            | 12.0             | 
| 7/1/2013     | 2010 | 1,216.1  | 41.1            | 113.8               | 8.6            | 110.7            | 24.4           | 4.5             | 47.9           | 28.5         | 68.0           | 7.9               | 109.5            | 3.4            | 77.1           | 119.8         | 9.3         | 92.5              | 165.7                  | 10.4                | 11.6            | 72.1             | 19.4          | 39.9              | 20.9            | 9.3              | 
```