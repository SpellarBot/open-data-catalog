# 2014 Elections - Kauai Mayor - Receipts and Disbursements

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2014-elections-kauai-mayor-receipts-and-disbursements-d5c85) |
| Metadata | [Link](https://data.hawaii.gov/api/views/aima-jkwt) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/aima-jkwt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/aima-jkwt/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | aima-jkwt |
| Name | 2014 Elections - Kauai Mayor - Receipts and Disbursements |
| Attribution | State of Hawaii Campaign Spending Commission |
| Category | Community |
| Tags | campaign spending commission, campaign finance, candidate, hawaii candidates, contributions, political contributions, campaign contributions, campaign spending, elections |
| Created | 2015-01-15T19:45:35Z |
| Publication Date | 2015-01-15T19:53:20Z |

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| Yes      | series tag     | candidate_name      | Candidate Name      | text      | text        |
| Yes      | numeric metric | total_receipts      | Total Receipts      | money     | money       |
| Yes      | numeric metric | total_disbursements | Total Disbursements | money     | money       |
| Yes      | series tag     | status              | Status              | text      | text        |
| Yes      | series tag     | won                 | Won                 | text      | text        |
| Yes      | series tag     | party               | Party               | text      | text        |
| Yes      | numeric metric | cost_per_vote       | Cost per Vote       | money     | money       |
| Yes      | numeric metric | votes               | Votes               | number    | number      |
| Yes      | series tag     | primary_only        | Primary Only        | text      | text        |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:aima-jkwt d:2014-01-01T00:00:00.000Z t:primary_only=N t:status=Challenger t:candidate_name="Barca, Dustin" t:won=N t:party=Non-Partisan m:cost_per_vote=9.03 m:votes=8195 m:total_disbursements=73988.31 m:total_receipts=74203.15

series e:aima-jkwt d:2014-01-01T00:00:00.000Z t:primary_only=N t:status=Incumbent t:candidate_name="Carvalho, Bernard" t:won=Y t:party=Non-Partisan m:cost_per_vote=19.31 m:votes=14688 m:total_disbursements=283673.56 m:total_receipts=296772.31

series e:aima-jkwt d:2014-01-01T00:00:00.000Z t:primary_only=Y t:status=Challenger t:candidate_name="DeSilva Carveiro, Debralynn" t:won=N t:party=Non-Partisan m:cost_per_vote=1.48 m:votes=570 m:total_disbursements=841.92 m:total_receipts=900
```

## Meta Commands

```ls
metric m:total_receipts p:double l:"Total Receipts" t:dataTypeName=money

metric m:total_disbursements p:double l:"Total Disbursements" t:dataTypeName=money

metric m:cost_per_vote p:double l:"Cost per Vote" t:dataTypeName=money

metric m:votes p:integer l:Votes t:dataTypeName=number

entity e:aima-jkwt l:"2014 Elections - Kauai Mayor - Receipts and Disbursements" t:attribution="State of Hawaii Campaign Spending Commission" t:url=https://data.hawaii.gov/api/views/aima-jkwt

property e:aima-jkwt t:meta.view v:id=aima-jkwt v:category=Community v:attributionLink=http://ags.hawaii.gov v:averageRating=0 v:name="2014 Elections - Kauai Mayor - Receipts and Disbursements" v:attribution="State of Hawaii Campaign Spending Commission"

property e:aima-jkwt t:meta.view.license v:name="Public Domain"

property e:aima-jkwt t:meta.view.owner v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:displayName="Hawaii Campaign Spending Commission"

property e:aima-jkwt t:meta.view.tableauthor v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:roleName=editor v:displayName="Hawaii Campaign Spending Commission"
```

## Top Records

```ls
| candidate_name              | total_receipts | total_disbursements | status     | won | party        | cost_per_vote | votes | primary_only | 
| =========================== | ============== | =================== | ========== | === | ============ | ============= | ===== | ============ | 
| Barca, Dustin               | 74203.15       | 73988.31            | Challenger | N   | Non-Partisan | 9.03          | 8195  | N            | 
| Carvalho, Bernard           | 296772.31      | 283673.56           | Incumbent  | Y   | Non-Partisan | 19.31         | 14688 | N            | 
| DeSilva Carveiro, Debralynn | 900            | 841.92              | Challenger | N   | Non-Partisan | 1.48          | 570   | Y            | 
| Lake Curtis Hendrix         | 0              | 0                   | Challenger | N   | Non-Partisan | 0             | 208   | Y            | 
```