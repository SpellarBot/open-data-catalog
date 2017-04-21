# 2014 Elections - Maui Mayor - Receipts and Disbursements

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2014-elections-maui-mayor-receipts-and-disbursements-b4b9f) |
| Metadata | [Link](https://data.hawaii.gov/api/views/gpft-tsy3) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/gpft-tsy3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/gpft-tsy3/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | gpft-tsy3 |
| Name | 2014 Elections - Maui Mayor - Receipts and Disbursements |
| Attribution | State of Hawaii Campaign Spending Commission |
| Category | Community |
| Tags | campaign spending commission, campaign finance, candidate, hawaii candidates, contributions, political contributions, campaign contributions, campaign spending, elections |
| Created | 2015-01-14T20:47:51Z |
| Publication Date | 2015-01-14T20:57:40Z |

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
series e:gpft-tsy3 d:2014-01-01T00:00:00.000Z t:primary_only=N t:status=Incumbent t:candidate_name="Arakawa, Alan" t:won=Y t:party=Non-Partisan m:cost_per_vote=29.8 m:votes=25435 m:total_disbursements=757865.1 m:total_receipts=941137.28

series e:gpft-tsy3 d:2014-01-01T00:00:00.000Z t:primary_only=Y t:status=Challenger t:candidate_name="Hawkes, Beau" t:won=N t:party=Non-Partisan m:cost_per_vote=0 m:votes=380 m:total_disbursements=0 m:total_receipts=0

series e:gpft-tsy3 d:2014-01-01T00:00:00.000Z t:primary_only=Y t:status=Challenger t:candidate_name="Kay, Alana" t:won=N t:party=Non-Partisan m:cost_per_vote=0.58 m:votes=1398 m:total_disbursements=816.31 m:total_receipts=920
```

## Meta Commands

```ls
metric m:total_receipts p:double l:"Total Receipts" t:dataTypeName=money

metric m:total_disbursements p:double l:"Total Disbursements" t:dataTypeName=money

metric m:cost_per_vote p:double l:"Cost Per Vote" t:dataTypeName=money

metric m:votes p:integer l:Votes t:dataTypeName=number

entity e:gpft-tsy3 l:"2014 Elections - Maui Mayor - Receipts and Disbursements" t:attribution="State of Hawaii Campaign Spending Commission" t:url=https://data.hawaii.gov/api/views/gpft-tsy3

property e:gpft-tsy3 t:meta.view v:id=gpft-tsy3 v:category=Community v:attributionLink=http://ags.hawaii.gov v:averageRating=0 v:name="2014 Elections - Maui Mayor - Receipts and Disbursements" v:attribution="State of Hawaii Campaign Spending Commission"

property e:gpft-tsy3 t:meta.view.license v:name="Public Domain"

property e:gpft-tsy3 t:meta.view.owner v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:displayName="Hawaii Campaign Spending Commission"

property e:gpft-tsy3 t:meta.view.tableauthor v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:roleName=editor v:displayName="Hawaii Campaign Spending Commission"
```

## Top Records

```ls
| candidate_name      | total_receipts | total_disbursements | status     | won | party        | cost_per_vote | votes | primary_only | 
| =================== | ============== | =================== | ========== | === | ============ | ============= | ===== | ============ | 
| Arakawa, Alan       | 941137.28      | 757865.1            | Incumbent  | Y   | Non-Partisan | 29.8          | 25435 | N            | 
| Hawkes, Beau        | 0              | 0                   | Challenger | N   | Non-Partisan | 0             | 380   | Y            | 
| Kay, Alana          | 920            | 816.31              | Challenger | N   | Non-Partisan | 0.58          | 1398  | Y            | 
| Kopelman, Orion     | 13425.01       | 13425               | Challenger | N   | Non-Partisan | 18.94         | 709   | Y            | 
| Paltin, Tamara      | 24246.71       | 18743.63            | Challenger | N   | Non-Partisan | 1.03          | 18162 | N            | 
| Waikiki, Nelson Jr. | 0              | 0                   | Challenger | N   | Non-Partisan | 0             | 818   | N            | 
```