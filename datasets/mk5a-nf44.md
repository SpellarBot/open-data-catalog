# Maryland Average Wage Per Job (Current Dollars): 2006-2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-average-wage-per-job-current-dollars-2006-2011-7d7f2) |
| Metadata | [Link](https://data.maryland.gov/api/views/mk5a-nf44) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/mk5a-nf44/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/mk5a-nf44/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | mk5a-nf44 |
| Name | Maryland Average Wage Per Job (Current Dollars): 2006-2011 |
| Attribution | Maryland Department of Planning |
| Category | Demographic |
| Tags | average, job, wage, current, dollars, planning, mdp |
| Created | 2012-12-21T15:33:25Z |
| Publication Date | 2013-11-19T20:45:04Z |

## Description

Average Wage Per Job in Maryland and its Jurisdictions in Current Dollars from 2006 to 2011. Source data from U.S. Bureau of Economic Analysis (Table CA34), May 2013.

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
series e:mk5a-nf44 d:2013-07-01T00:00:00.000Z m:baltimore_city=49916 m:calvert_county=38957 m:st_mary_s_county=49603 m:wicomico_county=34847 m:prince_george_s_county=47094 m:washington_county=36522 m:carroll_county=34659 m:montgomery_county=57136 m:garrett_county=27584 m:talbot_county=34118 m:kent_county=33022 m:queen_anne_s_county=33016 m:baltimore_county=45751 m:cecil_county=39732 m:harford_county=40893 m:caroline_county=31748 m:frederick_county=42253 m:charles_county=37203 m:somerset_county=33583 m:maryland=47360 m:anne_arundel_county=49695 m:howard_county=50854 m:worcester_county=27784 m:allegany_county=31924 m:dorchester_county=32822

series e:mk5a-nf44 d:2013-07-01T00:00:00.000Z m:baltimore_city=51960 m:calvert_county=40090 m:st_mary_s_county=51888 m:wicomico_county=36160 m:prince_george_s_county=48564 m:washington_county=37027 m:carroll_county=35375 m:montgomery_county=60390 m:garrett_county=28664 m:talbot_county=35262 m:kent_county=34703 m:queen_anne_s_county=33947 m:baltimore_county=47480 m:cecil_county=41737 m:harford_county=42475 m:caroline_county=32647 m:frederick_county=43907 m:charles_county=38515 m:somerset_county=36090 m:maryland=49323 m:anne_arundel_county=51895 m:howard_county=53150 m:worcester_county=29048 m:allegany_county=33089 m:dorchester_county=33975

series e:mk5a-nf44 d:2013-07-01T00:00:00.000Z m:baltimore_city=54322 m:calvert_county=40939 m:st_mary_s_county=53252 m:wicomico_county=37234 m:prince_george_s_county=50161 m:washington_county=37610 m:carroll_county=36050 m:montgomery_county=61628 m:garrett_county=29959 m:talbot_county=35977 m:kent_county=35782 m:queen_anne_s_county=34106 m:baltimore_county=47956 m:cecil_county=41635 m:harford_county=43479 m:caroline_county=33512 m:frederick_county=45527 m:charles_county=39691 m:somerset_county=36881 m:maryland=50629 m:anne_arundel_county=53358 m:howard_county=54683 m:worcester_county=29357 m:allegany_county=34358 m:dorchester_county=35199
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

entity e:mk5a-nf44 l:"Maryland Average Wage Per Job (Current Dollars): 2006-2011" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/mk5a-nf44

property e:mk5a-nf44 t:meta.view v:id=mk5a-nf44 v:category=Demographic v:attributionLink=http://planning.maryland.gov/msdc/md_statistical_handbook12.pdf v:averageRating=0 v:name="Maryland Average Wage Per Job (Current Dollars): 2006-2011" v:attribution="Maryland Department of Planning"

property e:mk5a-nf44 t:meta.view.license v:name="Public Domain"

property e:mk5a-nf44 t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:mk5a-nf44 t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| date_created | year | maryland | allegany_county | anne_arundel_county | baltimore_city | baltimore_county | calvert_county | caroline_county | carroll_county | cecil_county | charles_county | dorchester_county | frederick_county | garrett_county | harford_county | howard_county | kent_county | montgomery_county | prince_george_s_county | queen_anne_s_county | somerset_county | st_mary_s_county | talbot_county | washington_county | wicomico_county | worcester_county | 
| ============ | ==== | ======== | =============== | =================== | ============== | ================ | ============== | =============== | ============== | ============ | ============== | ================= | ================ | ============== | ============== | ============= | =========== | ================= | ====================== | =================== | =============== | ================ | ============= | ================= | =============== | ================ | 
| 7/1/2013     | 2006 | 47360    | 31924           | 49695               | 49916          | 45751            | 38957          | 31748           | 34659          | 39732        | 37203          | 32822             | 42253            | 27584          | 40893          | 50854         | 33022       | 57136             | 47094                  | 33016               | 33583           | 49603            | 34118         | 36522             | 34847           | 27784            | 
| 7/1/2013     | 2007 | 49323    | 33089           | 51895               | 51960          | 47480            | 40090          | 32647           | 35375          | 41737        | 38515          | 33975             | 43907            | 28664          | 42475          | 53150         | 34703       | 60390             | 48564                  | 33947               | 36090           | 51888            | 35262         | 37027             | 36160           | 29048            | 
| 7/1/2013     | 2008 | 50629    | 34358           | 53358               | 54322          | 47956            | 40939          | 33512           | 36050          | 41635        | 39691          | 35199             | 45527            | 29959          | 43479          | 54683         | 35782       | 61628             | 50161                  | 34106               | 36881           | 53252            | 35977         | 37610             | 37234           | 29357            | 
| 7/1/2013     | 2009 | 51705    | 35166           | 55135               | 54243          | 48690            | 41963          | 33868           | 36923          | 41504        | 41289          | 35460             | 47034            | 30830          | 45025          | 56641         | 35462       | 63122             | 51102                  | 34936               | 37558           | 56697            | 37021         | 37296             | 37742           | 29835            | 
| 7/1/2013     | 2010 | 52945    | 35701           | 56488               | 55335          | 49821            | 42621          | 34789           | 37898          | 41965        | 41190          | 35406             | 47918            | 31401          | 46590          | 58040         | 36088       | 65108             | 51671                  | 35701               | 38050           | 59933            | 37740         | 38079             | 38367           | 30604            | 
| 7/1/2013     | 2011 | 54281    | 36613           | 57697               | 56631          | 50631            | 43241          | 36154           | 38835          | 42201        | 41812          | 35645             | 48743            | 32226          | 49200          | 60252         | 36951       | 67054             | 52566                  | 36089               | 39378           | 62052            | 38280         | 39176             | 38744           | 31216            | 
```