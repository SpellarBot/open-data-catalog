# Maryland Total New Parcels Outside PFA For Residential Development: 2006-2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-total-new-parcels-outside-pfa-for-residential-development-2006-2010-1f32a) |
| Metadata | [Link](https://data.maryland.gov/api/views/afh5-ag7t) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/afh5-ag7t/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/afh5-ag7t/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | afh5-ag7t |
| Name | Maryland Total New Parcels Outside PFA For Residential Development: 2006-2010 |
| Attribution | Maryland Department of Planning |
| Category | Housing |
| Tags | total, new, parcels, outside, pfa, residential, development, planning, mdp |
| Created | 2012-12-21T18:04:38Z |
| Publication Date | 2013-11-20T15:45:13Z |

## Description

Maryland Total New Parcels Outside Priority Funding Area (PFA) - New Parcel Development  for Residential Development from 2006 to 2010. 
Priority Funding Areas are existing communities and places where local governments want State investment to support future growth.

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
series e:afh5-ag7t d:2013-07-01T00:00:00.000Z m:baltimore_city=0 m:calvert_county=191 m:st_mary_s_county=346 m:wicomico_county=365 m:prince_george_s_county=794 m:washington_county=347 m:carroll_county=241 m:montgomery_county=234 m:garrett_county=283 m:talbot_county=111 m:kent_county=55 m:queen_anne_s_county=237 m:baltimore_county=317 m:cecil_county=233 m:harford_county=290 m:caroline_county=158 m:frederick_county=239 m:charles_county=460 m:somerset_county=81 m:maryland=6041 m:anne_arundel_county=389 m:howard_county=217 m:worcester_county=276 m:allegany_county=35 m:dorchester_county=142

series e:afh5-ag7t d:2013-07-01T00:00:00.000Z m:baltimore_city=0 m:calvert_county=135 m:st_mary_s_county=292 m:wicomico_county=172 m:prince_george_s_county=818 m:washington_county=212 m:carroll_county=149 m:montgomery_county=152 m:garrett_county=187 m:talbot_county=64 m:kent_county=40 m:queen_anne_s_county=156 m:baltimore_county=233 m:cecil_county=155 m:harford_county=178 m:caroline_county=127 m:frederick_county=153 m:charles_county=331 m:somerset_county=52 m:maryland=4379 m:anne_arundel_county=342 m:howard_county=137 m:worcester_county=161 m:allegany_county=43 m:dorchester_county=90

series e:afh5-ag7t d:2013-07-01T00:00:00.000Z m:baltimore_city=0 m:calvert_county=88 m:st_mary_s_county=245 m:wicomico_county=131 m:prince_george_s_county=522 m:washington_county=141 m:carroll_county=84 m:montgomery_county=116 m:garrett_county=174 m:talbot_county=54 m:kent_county=20 m:queen_anne_s_county=104 m:baltimore_county=169 m:cecil_county=92 m:harford_county=114 m:caroline_county=59 m:frederick_county=91 m:charles_county=216 m:somerset_county=44 m:maryland=3159 m:anne_arundel_county=337 m:howard_county=150 m:worcester_county=95 m:allegany_county=43 m:dorchester_county=70
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

entity e:afh5-ag7t l:"Maryland Total New Parcels Outside PFA For Residential Development: 2006-2010" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/afh5-ag7t

property e:afh5-ag7t t:meta.view v:id=afh5-ag7t v:category=Housing v:attributionLink=http://planning.maryland.gov/msdc/md_statistical_handbook12.pdf v:averageRating=0 v:name="Maryland Total New Parcels Outside PFA For Residential Development: 2006-2010" v:attribution="Maryland Department of Planning"

property e:afh5-ag7t t:meta.view.license v:name="Public Domain"

property e:afh5-ag7t t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:afh5-ag7t t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| date_created | year | maryland | allegany_county | anne_arundel_county | baltimore_city | baltimore_county | calvert_county | caroline_county | carroll_county | cecil_county | charles_county | dorchester_county | frederick_county | garrett_county | harford_county | howard_county | kent_county | montgomery_county | prince_george_s_county | queen_anne_s_county | somerset_county | st_mary_s_county | talbot_county | washington_county | wicomico_county | worcester_county | 
| ============ | ==== | ======== | =============== | =================== | ============== | ================ | ============== | =============== | ============== | ============ | ============== | ================= | ================ | ============== | ============== | ============= | =========== | ================= | ====================== | =================== | =============== | ================ | ============= | ================= | =============== | ================ | 
| 7/1/2013     | 2006 | 6041     | 35              | 389                 | 0              | 317              | 191            | 158             | 241            | 233          | 460            | 142               | 239              | 283            | 290            | 217           | 55          | 234               | 794                    | 237                 | 81              | 346              | 111           | 347               | 365             | 276              | 
| 7/1/2013     | 2007 | 4379     | 43              | 342                 | 0              | 233              | 135            | 127             | 149            | 155          | 331            | 90                | 153              | 187            | 178            | 137           | 40          | 152               | 818                    | 156                 | 52              | 292              | 64            | 212               | 172             | 161              | 
| 7/1/2013     | 2008 | 3159     | 43              | 337                 | 0              | 169              | 88             | 59              | 84             | 92           | 216            | 70                | 91               | 174            | 114            | 150           | 20          | 116               | 522                    | 104                 | 44              | 245              | 54            | 141               | 131             | 95               | 
| 7/1/2013     | 2009 | 2234     | 21              | 223                 | 0              | 93               | 98             | 44              | 62             | 52           | 199            | 25                | 51               | 58             | 84             | 103           | 20          | 108               | 528                    | 24                  | 22              | 210              | 22            | 61                | 75              | 51               | 
| 7/1/2013     | 2010 | 2296     | 18              | 180                 | 0              | 80               | 102            | 34              | 51             | 91           | 221            | 47                | 38               | 85             | 98             | 152           | 8           | 122               | 491                    | 27                  | 12              | 191              | 23            | 113               | 66              | 46               | 
```