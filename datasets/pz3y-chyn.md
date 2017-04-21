# Maryland New Multi Family Housing Units Authorized For Construction: 2000-2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-new-multi-family-housing-units-authorized-for-construction-2000-2011-7deca) |
| Metadata | [Link](https://data.maryland.gov/api/views/pz3y-chyn) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/pz3y-chyn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/pz3y-chyn/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | pz3y-chyn |
| Name | Maryland New Multi Family Housing Units Authorized For Construction: 2000-2011 |
| Attribution | Maryland Department of Planning |
| Category | Housing |
| Tags | multi, family, units, construction, planning, mdp |
| Created | 2012-12-21T16:51:23Z |
| Publication Date | 2012-12-21T16:53:36Z |

## Description

New Multi Family Housing Units Authorized For Construction in Maryland and its jurisdictions from 2000 to 2011. Source from the U.S. Department of Commerce, Bureau of the Census.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | time           | date_created           | Date created           | text      | text        |
| No       |                | year                   | Year                   | number    | number      |
| Yes      | numeric metric | maryland               | MARYLAND               | number    | number      |
| Yes      | numeric metric | allegany_county        | Allegany County        | number    | text        |
| Yes      | numeric metric | anne_arundel_county    | Anne Arundel County    | number    | number      |
| Yes      | numeric metric | baltimore_city         | Baltimore City         | number    | number      |
| Yes      | numeric metric | baltimore_county       | Baltimore County       | number    | number      |
| Yes      | numeric metric | calvert_county         | Calvert County         | number    | text        |
| Yes      | numeric metric | caroline_county        | Caroline County        | number    | text        |
| Yes      | numeric metric | carroll_county         | Carroll County         | number    | text        |
| Yes      | numeric metric | cecil_county           | Cecil County           | number    | number      |
| Yes      | numeric metric | charles_county         | Charles County         | number    | text        |
| Yes      | numeric metric | dorchester_county      | Dorchester County      | number    | text        |
| Yes      | numeric metric | frederick_county       | Frederick County       | number    | number      |
| Yes      | numeric metric | garrett_county         | Garrett County         | number    | text        |
| Yes      | numeric metric | harford_county         | Harford County         | number    | number      |
| Yes      | numeric metric | howard_county          | Howard County          | number    | number      |
| Yes      | numeric metric | kent_county            | Kent County            | number    | text        |
| Yes      | numeric metric | montgomery_county      | Montgomery County      | number    | number      |
| Yes      | numeric metric | prince_george_s_county | Prince George's County | number    | number      |
| Yes      | numeric metric | queen_anne_s_county    | Queen Anne's County    | number    | text        |
| Yes      | numeric metric | somerset_county        | Somerset County        | number    | text        |
| Yes      | numeric metric | st_mary_s_county       | St. Mary's County      | number    | number      |
| Yes      | series tag     | talbot_county          | Talbot County          | text      | text        |
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
series e:pz3y-chyn d:2012-12-17T00:00:00.000Z t:kent_county=- t:queen_anne_s_county=- t:caroline_county=- t:somerset_county=- t:garrett_county=- t:talbot_county=- t:allegany_county=- t:dorchester_county=- m:baltimore_city=38 m:calvert_county=25 m:st_mary_s_county=120 m:wicomico_county=109 m:prince_george_s_county=277 m:washington_county=162 m:carroll_county=112 m:montgomery_county=2019 m:baltimore_county=639 m:cecil_county=85 m:harford_county=156 m:frederick_county=52 m:charles_county=90 m:maryland=5226 m:anne_arundel_county=608 m:howard_county=551 m:worcester_county=183

series e:pz3y-chyn d:2012-12-17T00:00:00.000Z t:queen_anne_s_county=- t:calvert_county=- t:caroline_county=- t:charles_county=- t:talbot_county=- t:dorchester_county=- m:baltimore_city=80 m:st_mary_s_county=4 m:wicomico_county=386 m:washington_county=152 m:carroll_county=40 m:montgomery_county=2058 m:garrett_county=43 m:kent_county=2 m:baltimore_county=1295 m:cecil_county=238 m:harford_county=79 m:frederick_county=262 m:somerset_county=2 m:maryland=5351 m:anne_arundel_county=479 m:worcester_county=224 m:allegany_county=7

series e:pz3y-chyn d:2012-12-17T00:00:00.000Z t:queen_anne_s_county=- t:garrett_county=- t:talbot_county=- t:dorchester_county=- m:baltimore_city=112 m:calvert_county=73 m:st_mary_s_county=100 m:wicomico_county=259 m:prince_george_s_county=78 m:washington_county=257 m:carroll_county=155 m:montgomery_county=2104 m:kent_county=36 m:baltimore_county=765 m:cecil_county=76 m:harford_county=69 m:caroline_county=4 m:frederick_county=226 m:charles_county=66 m:somerset_county=10 m:maryland=5289 m:anne_arundel_county=333 m:howard_county=206 m:worcester_county=348 m:allegany_county=12
```

## Meta Commands

```ls
metric m:maryland p:integer l:MARYLAND t:dataTypeName=number

metric m:anne_arundel_county p:integer l:"Anne Arundel County" t:dataTypeName=number

metric m:baltimore_city p:integer l:"Baltimore City" t:dataTypeName=number

metric m:baltimore_county p:integer l:"Baltimore County" t:dataTypeName=number

metric m:cecil_county p:integer l:"Cecil County" t:dataTypeName=number

metric m:frederick_county p:integer l:"Frederick County" t:dataTypeName=number

metric m:harford_county p:integer l:"Harford County" t:dataTypeName=number

metric m:howard_county p:integer l:"Howard County" t:dataTypeName=number

metric m:montgomery_county p:integer l:"Montgomery County" t:dataTypeName=number

metric m:prince_george_s_county p:integer l:"Prince George's County" t:dataTypeName=number

metric m:st_mary_s_county p:integer l:"St. Mary's County" t:dataTypeName=number

metric m:washington_county p:integer l:"Washington County" t:dataTypeName=number

metric m:wicomico_county p:integer l:"Wicomico County" t:dataTypeName=number

metric m:worcester_county p:integer l:"Worcester County" t:dataTypeName=number

entity e:pz3y-chyn l:"Maryland New Multi Family Housing Units Authorized For Construction: 2000-2011" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/pz3y-chyn

property e:pz3y-chyn t:meta.view v:id=pz3y-chyn v:category=Housing v:attributionLink=http://planning.maryland.gov/msdc/md_statistical_handbook11.pdf v:averageRating=0 v:name="Maryland New Multi Family Housing Units Authorized For Construction: 2000-2011" v:attribution="Maryland Department of Planning"

property e:pz3y-chyn t:meta.view.license v:name="Public Domain"

property e:pz3y-chyn t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:pz3y-chyn t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| date_created | year | maryland | allegany_county | anne_arundel_county | baltimore_city | baltimore_county | calvert_county | caroline_county | carroll_county | cecil_county | charles_county | dorchester_county | frederick_county | garrett_county | harford_county | howard_county | kent_county | montgomery_county | prince_george_s_county | queen_anne_s_county | somerset_county | st_mary_s_county | talbot_county | washington_county | wicomico_county | worcester_county | 
| ============ | ==== | ======== | =============== | =================== | ============== | ================ | ============== | =============== | ============== | ============ | ============== | ================= | ================ | ============== | ============== | ============= | =========== | ================= | ====================== | =================== | =============== | ================ | ============= | ================= | =============== | ================ | 
| 12/17/2012   | 2000 | 5226     | -               | 608                 | 38             | 639              | 25             | -               | 112            | 85           | 90             | -                 | 52               | -              | 156            | 551           | -           | 2019              | 277                    | -                   | -               | 120              | -             | 162               | 109             | 183              | 
| 12/17/2012   | 2001 | 5351     | 7               | 479                 | 80             | 1295             | -              | -               | 40             | 238          | -              | -                 | 262              | 43             | 79             |               | 2           | 2058              |                        | -                   | 2               | 4                | -             | 152               | 386             | 224              | 
| 12/17/2012   | 2002 | 5289     | 12              | 333                 | 112            | 765              | 73             | 4               | 155            | 76           | 66             | -                 | 226              | -              | 69             | 206           | 36          | 2104              | 78                     | -                   | 10              | 100              | -             | 257               | 259             | 348              | 
| 12/17/2012   | 2003 | 6516     | -               | 837                 | 489            | 838              | -              | 54              | 60             | 154          | 92             | 2                 | 232              | 3              | 124            | 469           | -           | 2089              | 130                    | 2                   | 115             | 244              | -             | 104               | 202             | 276              | 
| 12/17/2012   | 2004 | 5829     | 20              | 595                 | 307            | 606              | -              | -               | 308            | 133          | -              | 60                | 55               | 6              | 406            | 553           | -           | 1445              | 73                     | 6                   | 77              | 288              | -             | 157               | 249             | 485              | 
| 12/17/2012   | 2005 | 7271     | 10              | 930                 | 613            | 422              | -              | 25              | 86             | 124          | 378            | 152               | 458              | -              | 443            | 438           | -           | 1891              | 170                    | 9                   | 10              | 30               | -             | 498               | 175             | 409              | 
| 12/17/2012   | 2006 | 5404     | -               | 306                 | 317            | 431              | -              | 4               | 4              | 2            | 181            | 126               | 202              | -              | 209            | 527           | -           | 1794              | 115                    | -                   | -               | 74               | -             | 247               | 381             | 484              | 
| 12/17/2012   | 2007 | 5350     | 2               | 790                 | 115            | 83               | -              | 8               | -              | 95           | 237            | 30                | 285              | 30             | 169            | 275           | 11          | 2051              | 721                    | -                   | 59              | 85               | -             | 20                | 244             | 40               | 
| 12/17/2012   | 2008 | 4091     | 9               | 150                 | 927            | 957              | -              | 2               | 8              | 342          | 271            | 96                | 84               | -              | 105            | 266           | -           | 479               | 42                     | -                   | -               | 74               | -             | 92                | 140             | 47               | 
| 12/17/2012   | 2009 | 2990     | 75              | 353                 | 204            | 583              | -              | -               | 38             |              | 156            | 41                | 90               | -              | 235            | 583           | -           |                   | 448                    | 20                  | 86              | 4                | -             | 2                 | 55              | 17               | 
```