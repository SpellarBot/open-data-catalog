# Maryland Public School Enrollment Trends Kindergarten To Grade 12: 2002-2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-public-school-enrollment-trends-kindergarten-to-grade-12-2002-2012-914b6) |
| Metadata | [Link](https://data.maryland.gov/api/views/wwk3-j4pg) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/wwk3-j4pg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/wwk3-j4pg/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | wwk3-j4pg |
| Name | Maryland Public School Enrollment Trends Kindergarten To Grade 12: 2002-2012 |
| Attribution | Maryland Department of Planning |
| Tags | public, school, enrollment, k-12, planning, mdp |
| Created | 2012-12-21T17:31:24Z |
| Publication Date | 2013-11-19T21:28:11Z |

## Description

Public School Enrollment Trends in Maryland and Jurisdictions for Kindergarten To Grade 12 from 2002 to 2012. Source from the Maryland State Department of Education.

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
series e:wwk3-j4pg d:2013-07-01T00:00:00.000Z m:baltimore_city=92858 m:calvert_county=16812 m:st_mary_s_county=15433 m:wicomico_county=13863 m:prince_george_s_county=132392 m:washington_county=19705 m:carroll_county=28217 m:montgomery_county=136568 m:garrett_county=4687 m:talbot_county=4338 m:kent_county=2502 m:queen_anne_s_county=7261 m:baltimore_county=104956 m:cecil_county=15714 m:harford_county=39325 m:caroline_county=5321 m:frederick_county=37938 m:charles_county=24084 m:somerset_county=2840 m:maryland=846174 m:anne_arundel_county=73725 m:howard_county=46538 m:worcester_county=6625 m:allegany_county=9860 m:dorchester_county=4612

series e:wwk3-j4pg d:2013-07-01T00:00:00.000Z m:baltimore_city=90702 m:calvert_county=17076 m:st_mary_s_county=15586 m:wicomico_county=13922 m:prince_george_s_county=133713 m:washington_county=19966 m:carroll_county=28613 m:montgomery_county=136493 m:garrett_county=4657 m:talbot_county=4301 m:kent_county=2441 m:queen_anne_s_county=7231 m:baltimore_county=105334 m:cecil_county=15993 m:harford_county=39297 m:caroline_county=5183 m:frederick_county=38307 m:charles_county=24867 m:somerset_county=2795 m:maryland=847722 m:anne_arundel_county=73369 m:howard_county=47124 m:worcester_county=6539 m:allegany_county=9606 m:dorchester_county=4607

series e:wwk3-j4pg d:2013-07-01T00:00:00.000Z m:baltimore_city=87195 m:calvert_county=17101 m:st_mary_s_county=15880 m:wicomico_county=13894 m:prince_george_s_county=131965 m:washington_county=20367 m:carroll_county=28576 m:montgomery_county=136465 m:garrett_county=4574 m:talbot_county=4333 m:kent_county=2392 m:queen_anne_s_county=7365 m:baltimore_county=104072 m:cecil_county=16042 m:harford_county=39355 m:caroline_county=5171 m:frederick_county=38798 m:charles_county=25292 m:somerset_county=2794 m:maryland=842181 m:anne_arundel_county=72641 m:howard_county=47463 m:worcester_county=6442 m:allegany_county=9445 m:dorchester_county=4559
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

entity e:wwk3-j4pg l:"Maryland Public School Enrollment Trends Kindergarten To Grade 12: 2002-2012" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/wwk3-j4pg

property e:wwk3-j4pg t:meta.view v:id=wwk3-j4pg v:attributionLink=http://planning.maryland.gov/msdc/md_statistical_handbook12.pdf v:averageRating=0 v:name="Maryland Public School Enrollment Trends Kindergarten To Grade 12: 2002-2012" v:attribution="Maryland Department of Planning"

property e:wwk3-j4pg t:meta.view.license v:name="Public Domain"

property e:wwk3-j4pg t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:wwk3-j4pg t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| date_created | year | maryland | allegany_county | anne_arundel_county | baltimore_city | baltimore_county | calvert_county | caroline_county | carroll_county | cecil_county | charles_county | dorchester_county | frederick_county | garrett_county | harford_county | howard_county | kent_county | montgomery_county | prince_george_s_county | queen_anne_s_county | somerset_county | st_mary_s_county | talbot_county | washington_county | wicomico_county | worcester_county | 
| ============ | ==== | ======== | =============== | =================== | ============== | ================ | ============== | =============== | ============== | ============ | ============== | ================= | ================ | ============== | ============== | ============= | =========== | ================= | ====================== | =================== | =============== | ================ | ============= | ================= | =============== | ================ | 
| 7/1/2013     | 2002 | 846174   | 9860            | 73725               | 92858          | 104956           | 16812          | 5321            | 28217          | 15714        | 24084          | 4612              | 37938            | 4687           | 39325          | 46538         | 2502        | 136568            | 132392                 | 7261                | 2840            | 15433            | 4338          | 19705             | 13863           | 6625             | 
| 7/1/2013     | 2003 | 847722   | 9606            | 73369               | 90702          | 105334           | 17076          | 5183            | 28613          | 15993        | 24867          | 4607              | 38307            | 4657           | 39297          | 47124         | 2441        | 136493            | 133713                 | 7231                | 2795            | 15586            | 4301          | 19966             | 13922           | 6539             | 
| 7/1/2013     | 2004 | 842181   | 9445            | 72641               | 87195          | 104072           | 17101          | 5171            | 28576          | 16042        | 25292          | 4559              | 38798            | 4574           | 39355          | 47463         | 2392        | 136465            | 131965                 | 7365                | 2794            | 15880            | 4333          | 20367             | 13894           | 6442             | 
| 7/1/2013     | 2005 | 835811   | 9313            | 72278               | 84307          | 103386           | 17107          | 5320            | 28707          | 16036        | 25624          | 4450              | 38945            | 4574           | 39317          | 47785         | 2310        | 136388            | 128391                 | 7437                | 2760            | 15908            | 4294          | 20709             | 14013           | 6452             | 
| 7/1/2013     | 2006 | 825966   | 9087            | 71800               | 81012          | 101915           | 17112          | 5309            | 28346          | 15924        | 25822          | 4472              | 39493            | 4530           | 38666          | 48148         | 2226        | 134787            | 125396                 | 7460                | 2772            | 15911            | 4224          | 21080             | 13988           | 6486             | 
| 7/1/2013     | 2007 | 818534   | 8996            | 71804               | 77642          | 100681           | 17029          | 5360            | 28009          | 15769        | 25878          | 4438              | 39614            | 4400           | 38298          | 48586         | 2155        | 134671            | 123112                 | 7480                | 2734            | 16126            | 4233          | 21195             | 13941           | 6383             | 
| 7/1/2013     | 2008 | 816963   | 8761            | 71969               | 78267          | 99678            | 16727          | 5255            | 27648          | 15631        | 25887          | 4331              | 39152            | 4303           | 37731          | 48886         | 2081        | 136115            | 122207                 | 7567                | 2716            | 16075            | 4260          | 21265             | 14133           | 6318             | 
| 7/1/2013     | 2009 | 819636   | 8693            | 73077               | 78154          | 99741            | 16653          | 5224            | 27435          | 15620        | 25914          | 4414              | 39164            | 4189           | 37734          | 49680         | 2060        | 138296            | 120908                 | 7512                | 2707            | 16443            | 4274          | 21414             | 14052           | 6278             | 
| 7/1/2013     | 2010 | 822594   | 8516            | 73811               | 78926          | 100547           | 16410          | 5174            | 27063          | 15347        | 25992          | 4379              | 39204            | 4090           | 37612          | 49991         | 2035        | 140520            | 120247                 | 7493                | 2706            | 16464            | 4258          | 21668             | 13810           | 6331             | 
| 7/1/2013     | 2011 | 824928   | 8414            | 74411               | 79360          | 101522           | 16167          | 5221            | 26786          | 15237        | 25887          | 4391              | 39350            | 3946           | 37445          | 50489         | 2040        | 142832            | 118338                 | 7509                | 2681            | 16748            | 4279          | 21755             | 13866           | 6254             | 
```