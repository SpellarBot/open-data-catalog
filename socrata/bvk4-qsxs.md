# Maryland Median Household Income By Year With Margin Of Error: 2005-2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-median-household-income-by-year-with-margin-of-error-2005-2011-29001) |
| Metadata | [Link](https://data.maryland.gov/api/views/bvk4-qsxs) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/bvk4-qsxs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/bvk4-qsxs/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | bvk4-qsxs |
| Name | Maryland Median Household Income By Year With Margin Of Error: 2005-2011 |
| Attribution | Maryland Department of Planning |
| Category | Demographic |
| Tags | median, income, year, margin, error, planning, mdp |
| Created | 2012-12-21T16:21:35Z |
| Publication Date | 2013-02-13T20:00:45Z |

## Description

The data consist of the median household income by the year in Maryland and the margin of error of the median income from 2005 to 2011. MOE= Margin of Error for the 90% confidence interval. Source from the U.S. Census Bureau, Small Area Income and Poverty Estimates, May 2012.

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
series e:bvk4-qsxs d:2012-12-17T00:00:00.000Z m:baltimore_city=32453 m:calvert_county=81927 m:st_mary_s_county=62739 m:wicomico_county=43797 m:prince_george_s_county=63005 m:washington_county=47008 m:carroll_county=74206 m:montgomery_county=81874 m:garrett_county=39061 m:talbot_county=51637 m:kent_county=43724 m:queen_anne_s_county=65980 m:baltimore_county=56256 m:cecil_county=58300 m:harford_county=65381 m:caroline_county=45260 m:frederick_county=72205 m:charles_county=69820 m:somerset_county=32753 m:maryland=61546 m:anne_arundel_county=71609 m:howard_county=90311 m:worcester_county=46768 m:allegany_county=33643 m:dorchester_county=38347

series e:bvk4-qsxs d:2012-12-17T00:00:00.000Z m:baltimore_city=1575 m:calvert_county=4165 m:st_mary_s_county=4618 m:wicomico_county=3105 m:prince_george_s_county=1659 m:washington_county=2906 m:carroll_county=3466 m:montgomery_county=2024 m:garrett_county=2224 m:talbot_county=4415 m:kent_county=3389 m:queen_anne_s_county=4763 m:baltimore_county=1563 m:cecil_county=3213 m:harford_county=2987 m:caroline_county=2769 m:frederick_county=3668 m:charles_county=3591 m:somerset_county=2774 m:maryland=565 m:anne_arundel_county=2241 m:howard_county=3115 m:worcester_county=2955 m:allegany_county=1848 m:dorchester_county=2484

series e:bvk4-qsxs d:2012-12-17T00:00:00.000Z m:baltimore_city=35834 m:calvert_county=83219 m:st_mary_s_county=70163 m:wicomico_county=46102 m:prince_george_s_county=65611 m:washington_county=51109 m:carroll_county=73761 m:montgomery_county=87019 m:garrett_county=39616 m:talbot_county=54471 m:kent_county=46525 m:queen_anne_s_county=69970 m:baltimore_county=59864 m:cecil_county=56983 m:harford_county=69253 m:caroline_county=45743 m:frederick_county=73765 m:charles_county=78347 m:somerset_county=34822 m:maryland=65041 m:anne_arundel_county=78389 m:howard_county=93349 m:worcester_county=47856 m:allegany_county=34483 m:dorchester_county=39106
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

entity e:bvk4-qsxs l:"Maryland Median Household Income By Year With Margin Of Error: 2005-2011" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/bvk4-qsxs

property e:bvk4-qsxs t:meta.view v:id=bvk4-qsxs v:category=Demographic v:attributionLink=http://planning.maryland.gov/msdc/md_statistical_handbook11.pdf v:averageRating=0 v:name="Maryland Median Household Income By Year With Margin Of Error: 2005-2011" v:attribution="Maryland Department of Planning"

property e:bvk4-qsxs t:meta.view.license v:name="Public Domain"

property e:bvk4-qsxs t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:bvk4-qsxs t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| date_created | year | maryland | allegany_county | anne_arundel_county | baltimore_city | baltimore_county | calvert_county | caroline_county | carroll_county | cecil_county | charles_county | dorchester_county | frederick_county | garrett_county | harford_county | howard_county | kent_county | montgomery_county | prince_george_s_county | queen_anne_s_county | somerset_county | st_mary_s_county | talbot_county | washington_county | wicomico_county | worcester_county | 
| ============ | ==== | ======== | =============== | =================== | ============== | ================ | ============== | =============== | ============== | ============ | ============== | ================= | ================ | ============== | ============== | ============= | =========== | ================= | ====================== | =================== | =============== | ================ | ============= | ================= | =============== | ================ | 
| 12/17/2012   | 2005 | 61546    | 33643           | 71609               | 32453          | 56256            | 81927          | 45260           | 74206          | 58300        | 69820          | 38347             | 72205            | 39061          | 65381          | 90311         | 43724       | 81874             | 63005                  | 65980               | 32753           | 62739            | 51637         | 47008             | 43797           | 46768            | 
| 12/17/2012   | 2005 | 565      | 1848            | 2241                | 1575           | 1563             | 4165           | 2769            | 3466           | 3213         | 3591           | 2484              | 3668             | 2224           | 2987           | 3115          | 3389        | 2024              | 1659                   | 4763                | 2774            | 4618             | 4415          | 2906              | 3105            | 2955             | 
| 12/17/2012   | 2006 | 65041    | 34483           | 78389               | 35834          | 59864            | 83219          | 45743           | 73761          | 56983        | 78347          | 39106             | 73765            | 39616          | 69253          | 93349         | 46525       | 87019             | 65611                  | 69970               | 34822           | 70163            | 54471         | 51109             | 46102           | 47856            | 
| 12/17/2012   | 2006 | 620      | 2371            | 2380                | 1061           | 1345             | 4130           | 3431            | 2666           | 2600         | 3653           | 2990              | 2665             | 2263           | 2833           | 3535          | 3510        | 2336              | 1273                   | 4408                | 2879            | 2534             | 3577          | 2587              | 2873            | 3498             | 
| 12/17/2012   | 2007 | 67989    | 37171           | 80158               | 36894          | 60828            | 89159          | 48387           | 79803          | 62489        | 81545          | 42077             | 76802            | 42041          | 72092          | 100744        | 46693       | 91440             | 67706                  | 75902               | 35553           | 72534            | 56512         | 50257             | 49981           | 49067            | 
| 12/17/2012   | 2007 | 695      | 2604            | 1651                | 871            | 1042             | 5845           | 4311            | 4540           | 3286         | 3943           | 2949              | 2682             | 3148           | 2923           | 3373          | 3934        | 2066              | 2240                   | 3760                | 3244            | 4573             | 3963          | 3313              | 2961            | 4322             | 
| 12/17/2012   | 2008 | 70482    | 39055           | 82616               | 40087          | 63078            | 82033          | 54934           | 78348          | 66131        | 85173          | 43288             | 78437            | 43496          | 76620          | 101867        | 52934       | 93895             | 71696                  | 77686               | 39426           | 77703            | 62206         | 51587             | 48614           | 50347            | 
| 12/17/2012   | 2008 | 608      | 2694            | 2639                | 1393           | 1966             | 3791           | 3861            | 2939           | 4191         | 3805           | 2949              | 3451             | 3391           | 2544           | 3006          | 4882        | 2029              | 1744                   | 5622                | 3542            | 4257             | 3909          | 2546              | 2946            | 3422             | 
| 12/17/2012   | 2009 | 69193    | 37151           | 79843               | 38458          | 64629            | 86281          | 49050           | 78418          | 60543        | 85899          | 43751             | 82598            | 42320          | 75364          | 101417        | 50585       | 93774             | 69545                  | 75146               | 35621           | 71316            | 59633         | 48883             | 46404           | 47829            | 
| 12/17/2012   | 2009 | 660      | 3061            | 2510                | 1309           | 1628             | 6124           | 4290            | 3467           | 3733         | 4545           | 3680              | 2546             | 3668           | 3410           | 2926          | 4982        | 2268              | 1556                   | 6221                | 3100            | 5018             | 3926          | 2355              | 3257            | 3678             | 
```