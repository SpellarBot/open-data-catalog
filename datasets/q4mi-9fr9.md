# Maryland Per Capita Personal Income (Constant 2005 Dollars): 2005-2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-per-capita-personal-income-constant-2005-dollars-2005-2010-d8255) |
| Metadata | [Link](https://data.maryland.gov/api/views/q4mi-9fr9) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/q4mi-9fr9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/q4mi-9fr9/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | q4mi-9fr9 |
| Name | Maryland Per Capita Personal Income (Constant 2005 Dollars): 2005-2010 |
| Attribution | Maryland Department of Planning |
| Category | Demographic |
| Tags | per, capita, personal, income, constant, planning, mdp |
| Created | 2012-12-21T17:01:35Z |
| Publication Date | 2012-12-21T17:04:08Z |

## Description

Maryland Per Capita Personal Income (Constant 2005 Dollars) from 2005 to 2010. Source U.S. Bureau of Economic Analysis

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
series e:q4mi-9fr9 d:2012-12-17T00:00:00.000Z m:baltimore_city=32270 m:calvert_county=38081 m:st_mary_s_county=34949 m:wicomico_county=30230 m:prince_george_s_county=34496 m:washington_county=30615 m:carroll_county=38431 m:montgomery_county=60602 m:garrett_county=30015 m:talbot_county=50129 m:kent_county=40065 m:queen_anne_s_county=41401 m:baltimore_county=43580 m:cecil_county=32984 m:harford_county=39308 m:caroline_county=28680 m:frederick_county=39147 m:charles_county=37078 m:somerset_county=23386 m:maryland=42405 m:anne_arundel_county=47823 m:howard_county=54844 m:worcester_county=34882 m:allegany_county=25633 m:dorchester_county=29727

series e:q4mi-9fr9 d:2012-12-17T00:00:00.000Z m:baltimore_city=32799 m:calvert_county=39057 m:st_mary_s_county=35656 m:wicomico_county=30164 m:prince_george_s_county=34624 m:washington_county=31390 m:carroll_county=39484 m:montgomery_county=63435 m:garrett_county=30616 m:talbot_county=51595 m:kent_county=42990 m:queen_anne_s_county=42283 m:baltimore_county=45423 m:cecil_county=33422 m:harford_county=40526 m:caroline_county=27968 m:frederick_county=40287 m:charles_county=37549 m:somerset_county=23383 m:maryland=43669 m:anne_arundel_county=49383 m:howard_county=56628 m:worcester_county=35517 m:allegany_county=26011 m:dorchester_county=29077

series e:q4mi-9fr9 d:2012-12-17T00:00:00.000Z m:baltimore_city=33729 m:calvert_county=40263 m:st_mary_s_county=36669 m:wicomico_county=30805 m:prince_george_s_county=35414 m:washington_county=31909 m:carroll_county=39858 m:montgomery_county=63731 m:garrett_county=31080 m:talbot_county=52073 m:kent_county=42793 m:queen_anne_s_county=42825 m:baltimore_county=46111 m:cecil_county=34312 m:harford_county=41689 m:caroline_county=28476 m:frederick_county=41151 m:charles_county=38216 m:somerset_county=24003 m:maryland=44398 m:anne_arundel_county=50216 m:howard_county=57668 m:worcester_county=36371 m:allegany_county=26468 m:dorchester_county=29824
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

entity e:q4mi-9fr9 l:"Maryland Per Capita Personal Income (Constant 2005 Dollars): 2005-2010" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/q4mi-9fr9

property e:q4mi-9fr9 t:meta.view v:id=q4mi-9fr9 v:category=Demographic v:attributionLink=http://planning.maryland.gov/msdc/md_statistical_handbook11.pdf v:averageRating=0 v:name="Maryland Per Capita Personal Income (Constant 2005 Dollars): 2005-2010" v:attribution="Maryland Department of Planning"

property e:q4mi-9fr9 t:meta.view.license v:name="Public Domain"

property e:q4mi-9fr9 t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:q4mi-9fr9 t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| date_created | year | maryland | allegany_county | anne_arundel_county | baltimore_city | baltimore_county | calvert_county | caroline_county | carroll_county | cecil_county | charles_county | dorchester_county | frederick_county | garrett_county | harford_county | howard_county | kent_county | montgomery_county | prince_george_s_county | queen_anne_s_county | somerset_county | st_mary_s_county | talbot_county | washington_county | wicomico_county | worcester_county | 
| ============ | ==== | ======== | =============== | =================== | ============== | ================ | ============== | =============== | ============== | ============ | ============== | ================= | ================ | ============== | ============== | ============= | =========== | ================= | ====================== | =================== | =============== | ================ | ============= | ================= | =============== | ================ | 
| 12/17/2012   | 2005 | 42405    | 25633           | 47823               | 32270          | 43580            | 38081          | 28680           | 38431          | 32984        | 37078          | 29727             | 39147            | 30015          | 39308          | 54844         | 40065       | 60602             | 34496                  | 41401               | 23386           | 34949            | 50129         | 30615             | 30230           | 34882            | 
| 12/17/2012   | 2006 | 43669    | 26011           | 49383               | 32799          | 45423            | 39057          | 27968           | 39484          | 33422        | 37549          | 29077             | 40287            | 30616          | 40526          | 56628         | 42990       | 63435             | 34624                  | 42283               | 23383           | 35656            | 51595         | 31390             | 30164           | 35517            | 
| 12/17/2012   | 2007 | 44398    | 26468           | 50216               | 33729          | 46111            | 40263          | 28476           | 39858          | 34312        | 38216          | 29824             | 41151            | 31080          | 41689          | 57668         | 42793       | 63731             | 35414                  | 42825               | 24003           | 36669            | 52073         | 31909             | 30805           | 36371            | 
| 12/17/2012   | 2008 | 44853    | 27614           | 50334               | 34487          | 45983            | 41246          | 28459           | 40465          | 34644        | 38939          | 30891             | 41925            | 32039          | 42309          | 58224         | 41850       | 64111             | 35658                  | 43753               | 24637           | 37370            | 53397         | 32463             | 31559           | 38397            | 
| 12/17/2012   | 2009 | 43612    | 28038           | 48826               | 34713          | 43944            | 41056          | 27825           | 39658          | 34088        | 38799          | 30615             | 40967            | 32047          | 41730          | 56602         | 39584       | 60484             | 35550                  | 41883               | 24629           | 37941            | 48929         | 31909             | 30529           | 36862            | 
| 12/17/2012   | 2010 | 44120    | 28566           | 49055               | 36027          | 44352            | 41541          | 28154           | 39822          | 34657        | 39187          | 30839             | 41451            | 33052          | 42184          | 57037         | 40192       | 60875             | 35682                  | 42058               | 24725           | 39103            | 49231         | 32526             | 30730           | 37671            | 
```