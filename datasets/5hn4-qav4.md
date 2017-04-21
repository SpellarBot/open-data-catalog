# 2014 Elections - Top 10 Loans

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2014-elections-top-10-loans-67b6b) |
| Metadata | [Link](https://data.hawaii.gov/api/views/5hn4-qav4) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/5hn4-qav4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/5hn4-qav4/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 5hn4-qav4 |
| Name | 2014 Elections - Top 10 Loans |
| Category | Community |
| Tags | campaign spending commission |
| Created | 2015-01-12T23:32:00Z |
| Publication Date | 2015-01-13T00:05:29Z |

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | series tag     | candidate_name | Candidate Name | text      | text        |
| Yes      | numeric metric | amount         | Amount         | money     | money       |
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
series e:5hn4-qav4 d:2014-01-01T00:00:00.000Z t:office=Governor t:status=Challenger t:candidate_name="Ige, David" t:won=Y m:amount=70000

series e:5hn4-qav4 d:2014-01-01T00:00:00.000Z t:office=Senate t:status=Challenger t:candidate_name="Inouye, Lorraine" t:won=Y m:amount=30000

series e:5hn4-qav4 d:2014-01-01T00:00:00.000Z t:office=OHA t:status=Challenger t:candidate_name="Shin, Lorraine" t:won=N m:amount=30000
```

## Meta Commands

```ls
metric m:amount p:double l:Amount t:dataTypeName=money

entity e:5hn4-qav4 l:"2014 Elections - Top 10 Loans" t:url=https://data.hawaii.gov/api/views/5hn4-qav4

property e:5hn4-qav4 t:meta.view v:id=5hn4-qav4 v:category=Community v:averageRating=0 v:name="2014 Elections - Top 10 Loans"

property e:5hn4-qav4 t:meta.view.license v:name="Public Domain"

property e:5hn4-qav4 t:meta.view.owner v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:displayName="Hawaii Campaign Spending Commission"

property e:5hn4-qav4 t:meta.view.tableauthor v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:roleName=editor v:displayName="Hawaii Campaign Spending Commission"
```

## Top Records

```ls
| candidate_name      | amount   | office           | status      | won | 
| =================== | ======== | ================ | =========== | === | 
| Ige, David          | 70000    | Governor         | Challenger  | Y   | 
| Inouye, Lorraine    | 30000    | Senate           | Challenger  | Y   | 
| Shin, Lorraine      | 30000    | OHA              | Challenger  | N   | 
| Sutton, Warner Kimo | 25013.24 | Lt. Governor     | Challenger  | N   | 
| Hanneman, Mufi      | 25000    | Governor         | Challenger  | N   | 
| Kinney, Nathaniel   | 22000    | House            | Challenger  | N   | 
| Fukunaga, CArol     | 21879.36 | Honolulu Council | Incumbent   | Y   | 
| Poulton, Brysen     | 26000    | Honolulu Council | Open        | N   | 
| Cowden, Felicia     | 21945.14 | Kauai Council    | Challenger  | N   | 
| Hee, Clayton        | 20500    | Lt. Governor     | Chanllenger | N   | 
```