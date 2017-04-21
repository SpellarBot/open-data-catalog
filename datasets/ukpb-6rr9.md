# Maryland Public School Enrollment Kindergarden To Grade 5: 2009-2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-public-school-enrollment-kindergarden-to-grade-5-2009-2012-33d78) |
| Metadata | [Link](https://data.maryland.gov/api/views/ukpb-6rr9) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/ukpb-6rr9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/ukpb-6rr9/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | ukpb-6rr9 |
| Name | Maryland Public School Enrollment Kindergarden To Grade 5: 2009-2012 |
| Attribution | Maryland Department of Planning |
| Category | Education |
| Tags | public, school, enrollment, kindergarden, fifth, grade, planning, mdp |
| Created | 2012-12-21T17:18:35Z |
| Publication Date | 2013-11-20T15:12:56Z |

## Description

Maryland Public School Enrollment from Kindergarden To Grade 5 from 2009 to 2012. Source from the Maryland State Department of Education.

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
series e:ukpb-6rr9 d:2013-07-01T00:00:00.000Z m:baltimore_city=37458 m:calvert_county=6973 m:st_mary_s_county=7391 m:wicomico_county=6973 m:prince_george_s_county=53270 m:washington_county=9894 m:carroll_county=11680 m:montgomery_county=62136 m:garrett_county=1817 m:talbot_county=1876 m:kent_county=933 m:queen_anne_s_county=3312 m:baltimore_county=45423 m:cecil_county=6919 m:harford_county=16738 m:caroline_county=2409 m:frederick_county=17240 m:charles_county=10462 m:somerset_county=1320 m:maryland=367621 m:anne_arundel_county=33493 m:howard_county=21316 m:worcester_county=2674 m:allegany_county=3878 m:dorchester_county=2036

series e:ukpb-6rr9 d:2013-07-01T00:00:00.000Z m:baltimore_city=37956 m:calvert_county=6891 m:st_mary_s_county=7527 m:wicomico_county=6810 m:prince_george_s_county=54333 m:washington_county=10018 m:carroll_county=11700 m:montgomery_county=64353 m:garrett_county=1797 m:talbot_county=1936 m:kent_county=930 m:queen_anne_s_county=3366 m:baltimore_county=46364 m:cecil_county=6860 m:harford_county=16776 m:caroline_county=2458 m:frederick_county=17584 m:charles_county=10686 m:somerset_county=1336 m:maryland=374471 m:anne_arundel_county=34305 m:howard_county=21851 m:worcester_county=2740 m:allegany_county=3854 m:dorchester_county=2040

series e:ukpb-6rr9 d:2013-07-01T00:00:00.000Z m:baltimore_city=38668 m:calvert_county=6846 m:st_mary_s_county=7831 m:wicomico_county=6806 m:prince_george_s_county=54948 m:washington_county=10048 m:carroll_county=11574 m:montgomery_county=66324 m:garrett_county=1757 m:talbot_county=1986 m:kent_county=947 m:queen_anne_s_county=3405 m:baltimore_county=47757 m:cecil_county=6878 m:harford_county=16766 m:caroline_county=2499 m:frederick_county=17727 m:charles_county=10729 m:somerset_county=1371 m:maryland=380653 m:anne_arundel_county=34867 m:howard_county=22281 m:worcester_county=2748 m:allegany_county=3809 m:dorchester_county=2081
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

entity e:ukpb-6rr9 l:"Maryland Public School Enrollment Kindergarden To Grade 5: 2009-2012" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/ukpb-6rr9

property e:ukpb-6rr9 t:meta.view v:id=ukpb-6rr9 v:category=Education v:attributionLink=http://planning.maryland.gov/msdc/md_statistical_handbook12.pdf v:averageRating=0 v:name="Maryland Public School Enrollment Kindergarden To Grade 5: 2009-2012" v:attribution="Maryland Department of Planning"

property e:ukpb-6rr9 t:meta.view.license v:name="Public Domain"

property e:ukpb-6rr9 t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:ukpb-6rr9 t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| date_created | year | maryland | allegany_county | anne_arundel_county | baltimore_city | baltimore_county | calvert_county | caroline_county | carroll_county | cecil_county | charles_county | dorchester_county | frederick_county | garrett_county | harford_county | howard_county | kent_county | montgomery_county | prince_george_s_county | queen_anne_s_county | somerset_county | st_mary_s_county | talbot_county | washington_county | wicomico_county | worcester_county | 
| ============ | ==== | ======== | =============== | =================== | ============== | ================ | ============== | =============== | ============== | ============ | ============== | ================= | ================ | ============== | ============== | ============= | =========== | ================= | ====================== | =================== | =============== | ================ | ============= | ================= | =============== | ================ | 
| 7/1/2013     | 2009 | 367621   | 3878            | 33493               | 37458          | 45423            | 6973           | 2409            | 11680          | 6919         | 10462          | 2036              | 17240            | 1817           | 16738          | 21316         | 933         | 62136             | 53270                  | 3312                | 1320            | 7391             | 1876          | 9894              | 6973            | 2674             | 
| 7/1/2013     | 2010 | 374471   | 3854            | 34305               | 37956          | 46364            | 6891           | 2458            | 11700          | 6860         | 10686          | 2040              | 17584            | 1797           | 16776          | 21851         | 930         | 64353             | 54333                  | 3366                | 1336            | 7527             | 1936          | 10018             | 6810            | 2740             | 
| 7/1/2013     | 2011 | 380653   | 3809            | 34867               | 38668          | 47757            | 6846           | 2499            | 11574          | 6878         | 10729          | 2081              | 17727            | 1757           | 16766          | 22281         | 947         | 66324             | 54948                  | 3405                | 1371            | 7831             | 1986          | 10048             | 6806            | 2748             | 
| 7/1/2013     | 2012 | 388944   | 3822            | 36027               | 39490          | 49464            | 6733           | 2516            | 11370          | 6850         | 10938          | 2155              | 17867            | 1787           | 16834          | 22768         | 946         | 68322             | 56375                  | 3461                | 1384            | 7955             | 1993          | 10185             | 6911            | 2791             | 
```