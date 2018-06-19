# 2014 Elections - Top 10 Contributions Received

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2014-elections-top-10-contributions-received-2c02b) |
| Metadata | [Link](https://data.hawaii.gov/api/views/aen2-hwav) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/aen2-hwav/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/aen2-hwav/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | aen2-hwav |
| Name | 2014 Elections - Top 10 Contributions Received |
| Category | Community |
| Tags | campaign spending commission |
| Created | 2015-01-12T20:57:57Z |
| Publication Date | 2015-01-12T21:09:08Z |

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | series tag     | candidate_name | Candidate Name | text      | text        |
| Yes      | numeric metric | contributions  | Contributions  | money     | money       |
| Yes      | series tag     | office         | Office         | text      | text        |
| Yes      | series tag     | status         | Status         | text      | text        |
| Yes      | series tag     | won            | Won            | text      | text        |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:aen2-hwav d:2014-01-01T00:00:00.000Z t:office=Governor t:status=Incumbent t:candidate_name="Abercrombie, Neil" t:won=N m:contributions=4860264.6

series e:aen2-hwav d:2014-01-01T00:00:00.000Z t:office=Governor t:status=Challenger t:candidate_name="Ige, David" t:won=Y m:contributions=2207375.63

series e:aen2-hwav d:2014-01-01T00:00:00.000Z t:office=Governor t:status=Challenger t:candidate_name="Aiona, James (Duke)" t:won=N m:contributions=1523560.76
```

## Meta Commands

```ls
metric m:contributions p:double l:Contributions t:dataTypeName=money

entity e:aen2-hwav l:"2014 Elections - Top 10 Contributions Received" t:url=https://data.hawaii.gov/api/views/aen2-hwav

property e:aen2-hwav t:meta.view v:id=aen2-hwav v:category=Community v:averageRating=0 v:name="2014 Elections - Top 10 Contributions Received"

property e:aen2-hwav t:meta.view.license v:name="Public Domain"

property e:aen2-hwav t:meta.view.owner v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:displayName="Hawaii Campaign Spending Commission"

property e:aen2-hwav t:meta.view.tableauthor v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:roleName=editor v:displayName="Hawaii Campaign Spending Commission"
```

## Top Records

```ls
| candidate_name      | contributions | office           | status     | won | 
| =================== | ============= | ================ | ========== | === | 
| Abercrombie, Neil   | 4860264.6     | Governor         | Incumbent  | N   | 
| Ige, David          | 2207375.63    | Governor         | Challenger | Y   | 
| Aiona, James (Duke) | 1523560.76    | Governor         | Challenger | N   | 
| Tsutsui, Shan       | 1252792.56    | Lt. Governor     | Incumbent  | Y   | 
| Arakawa, Alan       | 939176.65     | Mayor            | Incumbent  | Y   | 
| Martin, Ernest      | 601628.34     | Honolulu Council | Incumbent  | Y   | 
| Hee, Clayton        | 359911.92     | Lt. Governor     | Challenger | N   | 
| Ahu, Elwin          | 322861.74     | Lt. Governor     | Challenger | N   | 
| Hanneman, Mufi      | 320422.19     | Governor         | Challenger | N   | 
| Carvalho, Bernard   | 294645.35     | Mayor            | Incumbent  | Y   | 
```