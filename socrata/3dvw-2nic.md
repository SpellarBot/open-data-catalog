# 2014 Elections - Lt. Governor - Receipts and Disbursements

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2014-elections-lt-governor-receipts-and-disbursements-2676e) |
| Metadata | [Link](https://data.hawaii.gov/api/views/3dvw-2nic) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/3dvw-2nic/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/3dvw-2nic/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 3dvw-2nic |
| Name | 2014 Elections - Lt. Governor - Receipts and Disbursements |
| Attribution | State of Hawaii Camapaign Spending Commission |
| Category | Community |
| Tags | campaign spending commission, campaign finance, candidate, hawaii candidates, contributions, political contributions, campaign contributions, campaign spending, elections |
| Created | 2015-01-15T20:53:47Z |
| Publication Date | 2015-01-15T21:12:41Z |

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
| Yes      | numeric metric | cost_per_vote       | Cost Per Vote       | money     | money       |
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
series e:3dvw-2nic d:2014-01-01T00:00:00.000Z t:primary_only=N t:status=Challenger t:candidate_name="Ahu, Elwin" t:won=N t:party=Republican m:cost_per_vote=2.28 m:votes=135775 m:total_disbursements=309515.81 m:total_receipts=322956.74

series e:3dvw-2nic d:2014-01-01T00:00:00.000Z t:primary_only=N t:status=Challenger t:candidate_name="Chang, Lester" t:won=N t:party=Independent m:cost_per_vote=0.24 m:votes=42934 m:total_disbursements=10198.78 m:total_receipts=11130.31

series e:3dvw-2nic d:2014-01-01T00:00:00.000Z t:primary_only=Y t:status=Challenger t:candidate_name="Hee, Clayton" t:won=N t:party=Democrat m:cost_per_vote=8.7 m:votes=81255 m:total_disbursements=707310.8 m:total_receipts=380601.25
```

## Meta Commands

```ls
metric m:total_receipts p:double l:"Total Receipts" t:dataTypeName=money

metric m:total_disbursements p:double l:"Total Disbursements" t:dataTypeName=money

metric m:cost_per_vote p:double l:"Cost Per Vote" t:dataTypeName=money

metric m:votes p:integer l:Votes t:dataTypeName=number

entity e:3dvw-2nic l:"2014 Elections - Lt. Governor - Receipts and Disbursements" t:attribution="State of Hawaii Camapaign Spending Commission" t:url=https://data.hawaii.gov/api/views/3dvw-2nic

property e:3dvw-2nic t:meta.view v:id=3dvw-2nic v:category=Community v:attributionLink=http://ags.hawaii.gov v:averageRating=0 v:name="2014 Elections - Lt. Governor - Receipts and Disbursements" v:attribution="State of Hawaii Camapaign Spending Commission"

property e:3dvw-2nic t:meta.view.license v:name="Public Domain"

property e:3dvw-2nic t:meta.view.owner v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:displayName="Hawaii Campaign Spending Commission"

property e:3dvw-2nic t:meta.view.tableauthor v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:roleName=editor v:displayName="Hawaii Campaign Spending Commission"
```

## Top Records

```ls
| candidate_name      | total_receipts | total_disbursements | status     | won | party       | cost_per_vote | votes  | primary_only | 
| =================== | ============== | =================== | ========== | === | =========== | ============= | ====== | ============ | 
| Ahu, Elwin          | 322956.74      | 309515.81           | Challenger | N   | Republican  | 2.28          | 135775 | N            | 
| Chang, Lester       | 11130.31       | 10198.78            | Challenger | N   | Independent | 0.24          | 42934  | N            | 
| Hee, Clayton        | 380601.25      | 707310.8            | Challenger | N   | Democrat    | 8.7           | 81255  | Y            | 
| Marlin, Cynthia     | 75             | 75                  | Challenger | N   | Libertarian | 0.01          | 6395   | N            | 
| Shiratori, Miles    | 8510.71        | 8510.71             | Challenger | N   | Democrat    | 3.28          | 2593   | Y            | 
| Sutton, Warner Kimo | 43935.44       | 40979.1             | Challenger | N   | Republican  | 3.56          | 11511  | Y            | 
| Tsutsui, Shan       | 1252792.56     | 1184286.02          | Incumbent  | Y   | Democrat    | 6.54          | 181106 | N            | 
| Puletasi, S. Palasi | 900.95         | 900.95              | Challenger | N   | Democrat    | 0.42          | 2126   | Y            | 
| Zanakis, Mary       | 0              | 0                   | Challenger | N   | Democrat    | 0             | 18174  | Y            | 
```