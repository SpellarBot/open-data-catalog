# Maryland Public School Enrollment Pre Kindergarten: 2009-2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-public-school-enrollment-pre-kindergarten-2009-2012-c2899) |
| Metadata | [Link](https://data.maryland.gov/api/views/9jgx-6epr) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/9jgx-6epr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/9jgx-6epr/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 9jgx-6epr |
| Name | Maryland Public School Enrollment Pre Kindergarten: 2009-2012 |
| Attribution | Maryland Department of Planning |
| Category | Education |
| Tags | public, school, education, enrollment, pre-k, planning, mdp |
| Created | 2012-12-21T17:27:55Z |
| Publication Date | 2013-11-20T15:18:37Z |

## Description

Public School Enrollmentin Maryland and Jurisdictions for Pre Kindergarten from 2009 to 2012. Source from the Maryland Department of Education.

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
series e:9jgx-6epr d:2013-07-01T00:00:00.000Z m:baltimore_city=4712 m:calvert_county=353 m:st_mary_s_county=743 m:wicomico_county=567 m:prince_george_s_county=6140 m:washington_county=488 m:carroll_county=286 m:montgomery_county=3426 m:garrett_county=122 m:talbot_county=221 m:kent_county=124 m:queen_anne_s_county=281 m:baltimore_county=3585 m:cecil_county=585 m:harford_county=902 m:caroline_county=327 m:frederick_county=995 m:charles_county=865 m:somerset_county=191 m:maryland=28627 m:anne_arundel_county=1699 m:howard_county=961 m:worcester_county=381 m:allegany_county=459 m:dorchester_county=214

series e:9jgx-6epr d:2013-07-01T00:00:00.000Z m:baltimore_city=4712 m:calvert_county=353 m:st_mary_s_county=743 m:wicomico_county=567 m:prince_george_s_county=6140 m:washington_county=488 m:carroll_county=286 m:montgomery_county=3426 m:garrett_county=122 m:talbot_county=221 m:kent_county=124 m:queen_anne_s_county=281 m:baltimore_county=3585 m:cecil_county=585 m:harford_county=902 m:caroline_county=327 m:frederick_county=995 m:charles_county=865 m:somerset_county=191 m:maryland=28627 m:anne_arundel_county=1699 m:howard_county=961 m:worcester_county=381 m:allegany_county=459 m:dorchester_county=214

series e:9jgx-6epr d:2013-07-01T00:00:00.000Z m:baltimore_city=4852 m:calvert_county=386 m:st_mary_s_county=701 m:wicomico_county=654 m:prince_george_s_county=5495 m:washington_county=485 m:carroll_county=296 m:montgomery_county=3627 m:garrett_county=131 m:talbot_county=268 m:kent_county=122 m:queen_anne_s_county=252 m:baltimore_county=3631 m:cecil_county=590 m:harford_county=779 m:caroline_county=324 m:frederick_county=1063 m:charles_county=891 m:somerset_county=201 m:maryland=28850 m:anne_arundel_county=1892 m:howard_county=1066 m:worcester_county=389 m:allegany_county=499 m:dorchester_county=256
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

entity e:9jgx-6epr l:"Maryland Public School Enrollment Pre Kindergarten: 2009-2012" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/9jgx-6epr

property e:9jgx-6epr t:meta.view v:id=9jgx-6epr v:category=Education v:attributionLink=http://planning.maryland.gov/msdc/md_statistical_handbook12.pdf v:averageRating=0 v:name="Maryland Public School Enrollment Pre Kindergarten: 2009-2012" v:attribution="Maryland Department of Planning"

property e:9jgx-6epr t:meta.view.license v:name="Public Domain"

property e:9jgx-6epr t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:9jgx-6epr t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| date_created | year | maryland | allegany_county | anne_arundel_county | baltimore_city | baltimore_county | calvert_county | caroline_county | carroll_county | cecil_county | charles_county | dorchester_county | frederick_county | garrett_county | harford_county | howard_county | kent_county | montgomery_county | prince_george_s_county | queen_anne_s_county | somerset_county | st_mary_s_county | talbot_county | washington_county | wicomico_county | worcester_county | 
| ============ | ==== | ======== | =============== | =================== | ============== | ================ | ============== | =============== | ============== | ============ | ============== | ================= | ================ | ============== | ============== | ============= | =========== | ================= | ====================== | =================== | =============== | ================ | ============= | ================= | =============== | ================ | 
| 7/1/2013     | 2009 | 28627    | 459             | 1699                | 4712           | 3585             | 353            | 327             | 286            | 585          | 865            | 214               | 995              | 122            | 902            | 961           | 124         | 3426              | 6140                   | 281                 | 191             | 743              | 221           | 488               | 567             | 381              | 
| 7/1/2013     | 2010 | 28627    | 459             | 1699                | 4712           | 3585             | 353            | 327             | 286            | 585          | 865            | 214               | 995              | 122            | 902            | 961           | 124         | 3426              | 6140                   | 281                 | 191             | 743              | 221           | 488               | 567             | 381              | 
| 7/1/2013     | 2011 | 28850    | 499             | 1892                | 4852           | 3631             | 386            | 324             | 296            | 590          | 891            | 256               | 1063             | 131            | 779            | 1066          | 122         | 3627              | 5495                   | 252                 | 201             | 701              | 268           | 485               | 654             | 389              | 
| 7/1/2013     | 2012 | 29671    | 520             | 2182                | 4890           | 3658             | 400            | 365             | 363            | 627          | 911            | 270               | 1067             | 86             | 760            | 1084          | 119         | 3779              | 5602                   | 249                 | 214             | 741              | 293           | 489               | 611             | 391              | 
```