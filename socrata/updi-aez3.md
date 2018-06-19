# 2014 Elections - Governor - Receipts and Disbursements

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2014-elections-governor-receipts-and-disbursements-dd7fd) |
| Metadata | [Link](https://data.hawaii.gov/api/views/updi-aez3) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/updi-aez3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/updi-aez3/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | updi-aez3 |
| Name | 2014 Elections - Governor - Receipts and Disbursements |
| Attribution | State of Hawaii Campaign Spending Commission |
| Category | Community |
| Tags | campaign spending commission, campaign finance, candidate, hawaii candidates, contributions, political contributions, campaign contributions, campaign spending, elections |
| Created | 2015-01-14T18:56:19Z |
| Publication Date | 2015-01-14T19:10:01Z |

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
| Yes      | numeric metric | votes               | Votes               | number    | number      |
| Yes      | numeric metric | cost_per_vote       | Cost Per Vote       | money     | money       |
| Yes      | series tag     | primary_only        | Primary Only        | text      | text        |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:updi-aez3 d:2014-01-01T00:00:00.000Z t:primary_only=Y t:status=Incumbent t:candidate_name="Abercrombie, Neil" t:won=N t:party=Democrat m:cost_per_vote=72.06 m:votes=73507 m:total_disbursements=5296582.64 m:total_receipts=4928328.15

series e:updi-aez3 d:2014-01-01T00:00:00.000Z t:primary_only=N t:status=Challenger t:candidate_name="Aiona, James (Duke)" t:won=N t:party=Republican m:cost_per_vote=111.45 m:votes=135775 m:total_disbursements=1554229.47 m:total_receipts=1532306.65

series e:updi-aez3 d:2014-01-01T00:00:00.000Z t:primary_only=Y t:status=Challenger t:candidate_name="Collins, Charles" t:won=N t:party=Republican m:cost_per_vote=0 m:votes=580 m:total_disbursements=0 m:total_receipts=0
```

## Meta Commands

```ls
metric m:total_receipts p:double l:"Total Receipts" t:dataTypeName=money

metric m:total_disbursements p:double l:"Total Disbursements" t:dataTypeName=money

metric m:votes p:integer l:Votes t:dataTypeName=number

metric m:cost_per_vote p:double l:"Cost Per Vote" t:dataTypeName=money

entity e:updi-aez3 l:"2014 Elections - Governor - Receipts and Disbursements" t:attribution="State of Hawaii Campaign Spending Commission" t:url=https://data.hawaii.gov/api/views/updi-aez3

property e:updi-aez3 t:meta.view v:id=updi-aez3 v:category=Community v:attributionLink=http://ags.hawaii.gov v:averageRating=0 v:name="2014 Elections - Governor - Receipts and Disbursements" v:attribution="State of Hawaii Campaign Spending Commission"

property e:updi-aez3 t:meta.view.license v:name="Public Domain"

property e:updi-aez3 t:meta.view.owner v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:displayName="Hawaii Campaign Spending Commission"

property e:updi-aez3 t:meta.view.tableauthor v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:roleName=editor v:displayName="Hawaii Campaign Spending Commission"
```

## Top Records

```ls
| candidate_name      | total_receipts | total_disbursements | status     | won | party       | votes  | cost_per_vote | primary_only | 
| =================== | ============== | =================== | ========== | === | =========== | ====== | ============= | ============ | 
| Abercrombie, Neil   | 4928328.15     | 5296582.64          | Incumbent  | N   | Democrat    | 73507  | 72.06         | Y            | 
| Aiona, James (Duke) | 1532306.65     | 1554229.47          | Challenger | N   | Republican  | 135775 | 111.45        | N            | 
| Collins, Charles    | 0              | 0                   | Challenger | N   | Republican  | 580    | 0             | Y            | 
| Davis, Jeffrey      | 6463           | 6463                | Challenger | N   | Libertarian | 6395   | 1.01          | N            | 
| Gregory, Stuart     | 113.94         | 113.94              | Challenger | N   | Republican  | 640    | 0.18          | Y            | 
| Hannemann, Mufi     | 367149.56      | 286276.97           | Challenger | N   | Independent | 42934  | 6.67          | N            | 
| Ige, David          | 2396974.27     | 2029646.05          | Challenger | Y   | Democrat    | 181106 | 11.21         | N            | 
| Tanabe, Van         | 0              | 0                   | Challenger | N   | Democrat    | 2622   | 0             | Y            | 
```