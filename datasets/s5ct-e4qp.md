# Maryland Average Wage Per Job (Constant 2009 Dollars): 2006-2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-average-wage-per-job-constant-2009-dollars-2006-2011-192e1) |
| Metadata | [Link](https://data.maryland.gov/api/views/s5ct-e4qp) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/s5ct-e4qp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/s5ct-e4qp/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | s5ct-e4qp |
| Name | Maryland Average Wage Per Job (Constant 2009 Dollars): 2006-2011 |
| Attribution | Maryland Department of Planning |
| Category | Demographic |
| Tags | average, job, wage, constant, planning, mdp |
| Created | 2012-12-21T15:22:36Z |
| Publication Date | 2013-11-19T20:52:12Z |

## Description

Average Wage Per Job in Maryland and its Jurisdictions(Constant 2009 Dollars) from 2006 to 2011. Data source from U.S. Bureau of Economic Analysis (Table CA34), May 2013.

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
series e:s5ct-e4qp d:2013-07-01T00:00:00.000Z m:baltimore_city=52694 m:calvert_county=41125 m:st_mary_s_county=52364 m:wicomico_county=36786 m:prince_george_s_county=49715 m:washington_county=38555 m:carroll_county=36588 m:montgomery_county=60316 m:garrett_county=29119 m:talbot_county=36017 m:kent_county=34860 m:queen_anne_s_county=34853 m:baltimore_county=48297 m:cecil_county=41943 m:harford_county=43169 m:caroline_county=33515 m:frederick_county=44605 m:charles_county=39273 m:somerset_county=35452 m:maryland=49996 m:anne_arundel_county=52461 m:howard_county=53684 m:worcester_county=29330 m:allegany_county=33701 m:dorchester_county=34649

series e:s5ct-e4qp d:2013-07-01T00:00:00.000Z m:baltimore_city=53512 m:calvert_county=41288 m:st_mary_s_county=53438 m:wicomico_county=37240 m:prince_george_s_county=50015 m:washington_county=38133 m:carroll_county=36432 m:montgomery_county=62194 m:garrett_county=29520 m:talbot_county=36316 m:kent_county=35740 m:queen_anne_s_county=34961 m:baltimore_county=48899 m:cecil_county=42984 m:harford_county=43744 m:caroline_county=33622 m:frederick_county=45219 m:charles_county=39666 m:somerset_county=37168 m:maryland=50797 m:anne_arundel_county=53445 m:howard_county=54738 m:worcester_county=29916 m:allegany_county=34078 m:dorchester_county=34990

series e:s5ct-e4qp d:2013-07-01T00:00:00.000Z m:baltimore_city=54288 m:calvert_county=40913 m:st_mary_s_county=53218 m:wicomico_county=37211 m:prince_george_s_county=50129 m:washington_county=37586 m:carroll_county=36027 m:montgomery_county=61589 m:garrett_county=29940 m:talbot_county=35954 m:kent_county=35759 m:queen_anne_s_county=34085 m:baltimore_county=47926 m:cecil_county=41609 m:harford_county=43452 m:caroline_county=33491 m:frederick_county=45498 m:charles_county=39666 m:somerset_county=36858 m:maryland=50597 m:anne_arundel_county=53324 m:howard_county=54649 m:worcester_county=29339 m:allegany_county=34336 m:dorchester_county=35177
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

entity e:s5ct-e4qp l:"Maryland Average Wage Per Job (Constant 2009 Dollars): 2006-2011" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/s5ct-e4qp

property e:s5ct-e4qp t:meta.view v:id=s5ct-e4qp v:category=Demographic v:attributionLink=http://planning.maryland.gov/msdc/md_statistical_handbook11.pdf v:averageRating=0 v:name="Maryland Average Wage Per Job (Constant 2009 Dollars): 2006-2011" v:attribution="Maryland Department of Planning"

property e:s5ct-e4qp t:meta.view.license v:name="Public Domain"

property e:s5ct-e4qp t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:s5ct-e4qp t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| date_created | year | maryland | allegany_county | anne_arundel_county | baltimore_city | baltimore_county | calvert_county | caroline_county | carroll_county | cecil_county | charles_county | dorchester_county | frederick_county | garrett_county | harford_county | howard_county | kent_county | montgomery_county | prince_george_s_county | queen_anne_s_county | somerset_county | st_mary_s_county | talbot_county | washington_county | wicomico_county | worcester_county | 
| ============ | ==== | ======== | =============== | =================== | ============== | ================ | ============== | =============== | ============== | ============ | ============== | ================= | ================ | ============== | ============== | ============= | =========== | ================= | ====================== | =================== | =============== | ================ | ============= | ================= | =============== | ================ | 
| 7/1/2013     | 2006 | 49996    | 33701           | 52461               | 52694          | 48297            | 41125          | 33515           | 36588          | 41943        | 39273          | 34649             | 44605            | 29119          | 43169          | 53684         | 34860       | 60316             | 49715                  | 34853               | 35452           | 52364            | 36017         | 38555             | 36786           | 29330            | 
| 7/1/2013     | 2007 | 50797    | 34078           | 53445               | 53512          | 48899            | 41288          | 33622           | 36432          | 42984        | 39666          | 34990             | 45219            | 29520          | 43744          | 54738         | 35740       | 62194             | 50015                  | 34961               | 37168           | 53438            | 36316         | 38133             | 37240           | 29916            | 
| 7/1/2013     | 2008 | 50597    | 34336           | 53324               | 54288          | 47926            | 40913          | 33491           | 36027          | 41609        | 39666          | 35177             | 45498            | 29940          | 43452          | 54649         | 35759       | 61589             | 50129                  | 34085               | 36858           | 53218            | 35954         | 37586             | 37211           | 29339            | 
| 7/1/2013     | 2009 | 51705    | 35166           | 55135               | 54243          | 48690            | 41963          | 33868           | 36923          | 41504        | 41289          | 35460             | 47034            | 30830          | 45025          | 56641         | 35462       | 63122             | 51102                  | 34936               | 37558           | 56697            | 37021         | 37296             | 37742           | 29835            | 
| 7/1/2013     | 2010 | 52084    | 35120           | 55569               | 54435          | 49010            | 41928          | 34223           | 37281          | 41282        | 40520          | 34830             | 47138            | 30890          | 45832          | 57096         | 35501       | 64049             | 50830                  | 35120               | 37431           | 58958            | 37126         | 37459             | 37743           | 30106            | 
| 7/1/2013     | 2011 | 52150    | 35176           | 55432               | 54408          | 48643            | 41544          | 34735           | 37310          | 40544        | 40171          | 34246             | 46830            | 30961          | 47269          | 57887         | 35500       | 64422             | 50502                  | 34672               | 37832           | 59616            | 36777         | 37638             | 37223           | 29991            | 
```