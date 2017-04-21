# Maryland Total Personal Income (Thousands of Current Dollars): 2006-2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-total-personal-income-thousands-of-current-dollars-2006-2011-21e6e) |
| Metadata | [Link](https://data.maryland.gov/api/views/m4dq-89ja) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/m4dq-89ja/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/m4dq-89ja/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | m4dq-89ja |
| Name | Maryland Total Personal Income (Thousands of Current Dollars): 2006-2011 |
| Attribution | Maryland Department of Planning |
| Category | Demographic |
| Tags | total, personal, income, current, planning, mdp |
| Created | 2012-12-21T18:10:06Z |
| Publication Date | 2013-11-19T20:04:30Z |

## Description

Maryland Total Personal Income (thousands of current dollars) from 2006 to 2011. Based on Data from U.S. Bureau of Economic Analysis

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
series e:m4dq-89ja d:2013-07-01T00:00:00.000Z m:baltimore_city=20926218 m:calvert_county=3492251 m:st_mary_s_county=3620520 m:wicomico_county=2931795 m:prince_george_s_county=30306871 m:washington_county=4652482 m:carroll_county=6771311 m:montgomery_county=60372289 m:garrett_county=948125 m:talbot_county=1961009 m:kent_county=873776 m:queen_anne_s_county=1985612 m:baltimore_county=37035713 m:cecil_county=3392763 m:harford_county=10039699 m:caroline_county=925494 m:frederick_county=9278747 m:charles_county=5444783 m:somerset_county=627861 m:maryland=252431010 m:anne_arundel_county=26261768 m:howard_county=15810097 m:worcester_county=1848960 m:allegany_county=1976708 m:dorchester_county=946158

series e:m4dq-89ja d:2013-07-01T00:00:00.000Z m:baltimore_city=22072895 m:calvert_county=3714419 m:st_mary_s_county=3891673 m:wicomico_county=3123522 m:prince_george_s_county=31753583 m:washington_county=4920738 m:carroll_county=7038812 m:montgomery_county=62643745 m:garrett_county=988529 m:talbot_county=2041855 m:kent_county=893938 m:queen_anne_s_county=2101631 m:baltimore_county=38726771 m:cecil_county=3606396 m:harford_county=10627546 m:caroline_county=982984 m:frederick_county=9875134 m:charles_county=5754094 m:somerset_county=671919 m:maryland=264797709 m:anne_arundel_county=27574822 m:howard_county=16742719 m:worcester_county=1958822 m:allegany_county=2078912 m:dorchester_county=1012250

series e:m4dq-89ja d:2013-07-01T00:00:00.000Z m:baltimore_city=23300745 m:calvert_county=3944776 m:st_mary_s_county=4149392 m:wicomico_county=3338815 m:prince_george_s_county=33026742 m:washington_county=5187266 m:carroll_county=7381180 m:montgomery_county=65845731 m:garrett_county=1054877 m:talbot_county=2170219 m:kent_county=918703 m:queen_anne_s_county=2243315 m:baltimore_county=40008568 m:cecil_county=3782960 m:harford_county=11190498 m:caroline_county=1022603 m:frederick_county=10472478 m:charles_county=6099457 m:somerset_county=710560 m:maryland=277792794 m:anne_arundel_county=28804951 m:howard_county=17659377 m:worcester_county=2141583 m:allegany_county=2245396 m:dorchester_county=1092602
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

entity e:m4dq-89ja l:"Maryland Total Personal Income (Thousands of Current Dollars): 2006-2011" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/m4dq-89ja

property e:m4dq-89ja t:meta.view v:id=m4dq-89ja v:category=Demographic v:attributionLink=http://planning.maryland.gov/msdc/md_statistical_handbook12.pdf v:averageRating=0 v:name="Maryland Total Personal Income (Thousands of Current Dollars): 2006-2011" v:attribution="Maryland Department of Planning"

property e:m4dq-89ja t:meta.view.license v:name="Public Domain"

property e:m4dq-89ja t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:m4dq-89ja t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| date_created | year | maryland  | allegany_county | anne_arundel_county | baltimore_city | baltimore_county | calvert_county | caroline_county | carroll_county | cecil_county | charles_county | dorchester_county | frederick_county | garrett_county | harford_county | howard_county | kent_county | montgomery_county | prince_george_s_county | queen_anne_s_county | somerset_county | st_mary_s_county | talbot_county | washington_county | wicomico_county | worcester_county | 
| ============ | ==== | ========= | =============== | =================== | ============== | ================ | ============== | =============== | ============== | ============ | ============== | ================= | ================ | ============== | ============== | ============= | =========== | ================= | ====================== | =================== | =============== | ================ | ============= | ================= | =============== | ================ | 
| 7/1/2013     | 2006 | 252431010 | 1976708         | 26261768            | 20926218       | 37035713         | 3492251        | 925494          | 6771311        | 3392763      | 5444783        | 946158            | 9278747          | 948125         | 10039699       | 15810097      | 873776      | 60372289          | 30306871               | 1985612             | 627861          | 3620520          | 1961009       | 4652482           | 2931795         | 1848960          | 
| 7/1/2013     | 2007 | 264797709 | 2078912         | 27574822            | 22072895       | 38726771         | 3714419        | 982984          | 7038812        | 3606396      | 5754094        | 1012250           | 9875134          | 988529         | 10627546       | 16742719      | 893938      | 62643745          | 31753583               | 2101631             | 671919          | 3891673          | 2041855       | 4920738           | 3123522         | 1958822          | 
| 7/1/2013     | 2008 | 277792794 | 2245396         | 28804951            | 23300745       | 40008568         | 3944776        | 1022603         | 7381180        | 3782960      | 6099457        | 1092602           | 10472478         | 1054877        | 11190498       | 17659377      | 918703      | 65845731          | 33026742               | 2243315             | 710560          | 4149392          | 2170219       | 5187266           | 3338815         | 2141583          | 
| 7/1/2013     | 2009 | 271728830 | 2292903         | 28303880            | 23398934       | 38239406         | 3944473        | 1005086         | 7212930        | 3738490      | 6125410        | 1083995           | 10285902         | 1050487        | 11074625       | 17436676      | 861001      | 62962957          | 33156357               | 2171411             | 713034          | 4271985          | 1976296       | 5100100           | 3269987         | 2052505          | 
| 7/1/2013     | 2010 | 281304904 | 2352416         | 29129254            | 24502772       | 39309645         | 4060283        | 1032906         | 7313246        | 3837653      | 6350111        | 1090242           | 10542394         | 1094117        | 11516179       | 18257099      | 860025      | 65904393          | 33888631               | 2258242             | 727133          | 4537815          | 2009480       | 5230135           | 3353801         | 2146932          | 
| 7/1/2013     | 2011 | 295235516 | 2453991         | 30633776            | 26040916       | 41247408         | 4238187        | 1082546         | 7612765        | 4036174      | 6677709        | 1134936           | 11034674         | 1155860        | 12159148       | 19435303      | 898852      | 69050166          | 35036640               | 2398624             | 747680          | 4820539          | 2118791       | 5484690           | 3470201         | 2265940          | 
```