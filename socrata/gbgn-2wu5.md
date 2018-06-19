# Maryland Total New Parcels Inside PFA For Residential Development: 2006-2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-total-new-parcels-inside-pfa-for-residential-development-2006-2010-023fe) |
| Metadata | [Link](https://data.maryland.gov/api/views/gbgn-2wu5) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/gbgn-2wu5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/gbgn-2wu5/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | gbgn-2wu5 |
| Name | Maryland Total New Parcels Inside PFA For Residential Development: 2006-2010 |
| Attribution | Maryland Department of Planning |
| Category | Housing |
| Tags | total, new, parcels, inside, pfa, residential, development, planning, mdp |
| Created | 2012-12-21T18:02:37Z |
| Publication Date | 2013-11-20T15:42:00Z |

## Description

Maryland Total New Parcels inside Priority Funding Areas (PFA) for residential development from 2006 to 2010. 
Priority Funding Areas are existing communities and places where local governments want State investment to support furture growth.

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
series e:gbgn-2wu5 d:2013-07-01T00:00:00.000Z m:baltimore_city=334 m:calvert_county=203 m:st_mary_s_county=522 m:wicomico_county=354 m:prince_george_s_county=2127 m:washington_county=729 m:carroll_county=413 m:montgomery_county=1193 m:garrett_county=62 m:talbot_county=176 m:kent_county=94 m:queen_anne_s_county=138 m:baltimore_county=1492 m:cecil_county=209 m:harford_county=1063 m:caroline_county=163 m:frederick_county=947 m:charles_county=509 m:somerset_county=87 m:maryland=13767 m:anne_arundel_county=1216 m:howard_county=914 m:worcester_county=545 m:allegany_county=102 m:dorchester_county=175

series e:gbgn-2wu5 d:2013-07-01T00:00:00.000Z m:baltimore_city=269 m:calvert_county=149 m:st_mary_s_county=377 m:wicomico_county=190 m:prince_george_s_county=1541 m:washington_county=302 m:carroll_county=200 m:montgomery_county=1133 m:garrett_county=51 m:talbot_county=140 m:kent_county=118 m:queen_anne_s_county=135 m:baltimore_county=1153 m:cecil_county=194 m:harford_county=656 m:caroline_county=55 m:frederick_county=638 m:charles_county=441 m:somerset_county=60 m:maryland=9907 m:anne_arundel_county=830 m:howard_county=728 m:worcester_county=297 m:allegany_county=98 m:dorchester_county=152

series e:gbgn-2wu5 d:2013-07-01T00:00:00.000Z m:baltimore_city=238 m:calvert_county=143 m:st_mary_s_county=319 m:wicomico_county=150 m:prince_george_s_county=874 m:washington_county=209 m:carroll_county=166 m:montgomery_county=837 m:garrett_county=39 m:talbot_county=118 m:kent_county=49 m:queen_anne_s_county=100 m:baltimore_county=559 m:cecil_county=155 m:harford_county=463 m:caroline_county=17 m:frederick_county=474 m:charles_county=236 m:somerset_county=47 m:maryland=6968 m:anne_arundel_county=809 m:howard_county=595 m:worcester_county=231 m:allegany_county=66 m:dorchester_county=74
```

## Meta Commands

```ls
metric m:maryland p:long l:MARYLAND t:dataTypeName=number

metric m:allegany_county p:integer l:"Allegany County" t:dataTypeName=number

metric m:anne_arundel_county p:long l:"Anne Arundel County" t:dataTypeName=number

metric m:baltimore_city p:integer l:"Baltimore City" t:dataTypeName=number

metric m:baltimore_county p:long l:"Baltimore County" t:dataTypeName=number

metric m:calvert_county p:integer l:"Calvert County" t:dataTypeName=number

metric m:caroline_county p:integer l:"Caroline County" t:dataTypeName=number

metric m:carroll_county p:integer l:"Carroll County" t:dataTypeName=number

metric m:cecil_county p:integer l:"Cecil County" t:dataTypeName=number

metric m:charles_county p:integer l:"Charles County" t:dataTypeName=number

metric m:dorchester_county p:integer l:"Dorchester County" t:dataTypeName=number

metric m:frederick_county p:integer l:"Frederick County" t:dataTypeName=number

metric m:garrett_county p:integer l:"Garrett County" t:dataTypeName=number

metric m:harford_county p:long l:"Harford County" t:dataTypeName=number

metric m:howard_county p:integer l:"Howard County" t:dataTypeName=number

metric m:kent_county p:integer l:"Kent County" t:dataTypeName=number

metric m:montgomery_county p:long l:"Montgomery County" t:dataTypeName=number

metric m:prince_george_s_county p:long l:"Prince George's County" t:dataTypeName=number

metric m:queen_anne_s_county p:integer l:"Queen Anne's County" t:dataTypeName=number

metric m:somerset_county p:integer l:"Somerset County" t:dataTypeName=number

metric m:st_mary_s_county p:integer l:"St. Mary's County" t:dataTypeName=number

metric m:talbot_county p:integer l:"Talbot County" t:dataTypeName=number

metric m:washington_county p:integer l:"Washington County" t:dataTypeName=number

metric m:wicomico_county p:integer l:"Wicomico County" t:dataTypeName=number

metric m:worcester_county p:integer l:"Worcester County" t:dataTypeName=number

entity e:gbgn-2wu5 l:"Maryland Total New Parcels Inside PFA For Residential Development: 2006-2010" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/gbgn-2wu5

property e:gbgn-2wu5 t:meta.view v:id=gbgn-2wu5 v:category=Housing v:attributionLink=http://planning.maryland.gov/msdc/md_statistical_handbook12.pdf v:averageRating=0 v:name="Maryland Total New Parcels Inside PFA For Residential Development: 2006-2010" v:attribution="Maryland Department of Planning"

property e:gbgn-2wu5 t:meta.view.license v:name="Public Domain"

property e:gbgn-2wu5 t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:gbgn-2wu5 t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| date_created | year | maryland | allegany_county | anne_arundel_county | baltimore_city | baltimore_county | calvert_county | caroline_county | carroll_county | cecil_county | charles_county | dorchester_county | frederick_county | garrett_county | harford_county | howard_county | kent_county | montgomery_county | prince_george_s_county | queen_anne_s_county | somerset_county | st_mary_s_county | talbot_county | washington_county | wicomico_county | worcester_county | 
| ============ | ==== | ======== | =============== | =================== | ============== | ================ | ============== | =============== | ============== | ============ | ============== | ================= | ================ | ============== | ============== | ============= | =========== | ================= | ====================== | =================== | =============== | ================ | ============= | ================= | =============== | ================ | 
| 7/1/2013     | 2006 | 13,767   | 102             | 1,216               | 334            | 1,492            | 203            | 163             | 413            | 209          | 509            | 175               | 947              | 62             | 1,063          | 914           | 94          | 1,193             | 2,127                  | 138                 | 87              | 522              | 176           | 729               | 354             | 545              | 
| 7/1/2013     | 2007 | 9,907    | 98              | 830                 | 269            | 1,153            | 149            | 55              | 200            | 194          | 441            | 152               | 638              | 51             | 656            | 728           | 118         | 1,133             | 1,541                  | 135                 | 60              | 377              | 140           | 302               | 190             | 297              | 
| 7/1/2013     | 2008 | 6,968    | 66              | 809                 | 238            | 559              | 143            | 17              | 166            | 155          | 236            | 74                | 474              | 39             | 463            | 595           | 49          | 837               | 874                    | 100                 | 47              | 319              | 118           | 209               | 150             | 231              | 
| 7/1/2013     | 2009 | 5,485    | 23              | 772                 | 90             | 390              | 147            | 21              | 102            | 83           | 262            | 19                | 498              | 8              | 338            | 558           | 54          | 620               | 855                    | 43                  | 18              | 243              | 83            | 82                | 111             | 65               | 
| 7/1/2013     | 2010 | 6,319    | 44              | 717                 | 98             | 429              | 105            | 13              | 128            | 117          | 410            | 31                | 715              | 12             | 452            | 755           | 30          | 822               | 683                    | 55                  | 9               | 323              | 89            | 120               | 98              | 64               | 
```