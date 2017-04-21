# 2014 Elections - Ballot Issue Committees

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2014-elections-ballot-issue-committees) |
| Metadata | [Link](https://data.hawaii.gov/api/views/b7sp-ttng) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/b7sp-ttng/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/b7sp-ttng/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | b7sp-ttng |
| Name | 2014 Elections - Ballot Issue Committees |
| Attribution | Hawaii State Camapaing Spending Commission |
| Category | Community |
| Tags | campaign spending, candidates, campaign spending commission, elections |
| Created | 2015-02-18T21:53:55Z |
| Publication Date | 2015-02-20T00:43:22Z |

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| Yes      | series tag     | committee_name      | Committee Name      | text      | text        |
| Yes      | series tag     | ballot_issue        | Ballot Issue        | text      | text        |
| Yes      | numeric metric | total_recipts       | Total Receipts      | money     | money       |
| Yes      | numeric metric | total_disbursements | Total Disbursements | money     | money       |
| Yes      | numeric metric | closing_cash        | Closing Cash        | money     | money       |
| Yes      | numeric metric | unpaid_expenditures | Unpaid Expenditures | money     | money       |
| Yes      | numeric metric | surplus_deficit     | Surplus/Deficit     | money     | money       |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:b7sp-ttng d:2014-01-01T00:00:00.000Z t:ballot_issue="Engineered Organisms" t:committee_name="Support Agriculture Coalition Committee" m:unpaid_expenditures=0 m:closing_cash=0 m:total_recipts=35931.91 m:total_disbursements=35931.91 m:surplus_deficit=0

series e:b7sp-ttng d:2014-01-01T00:00:00.000Z t:ballot_issue="Engineered Organisms" t:committee_name="BASF Plant Science, L.P." m:unpaid_expenditures=0 m:closing_cash=0 m:total_recipts=59000 m:total_disbursements=59000 m:surplus_deficit=0

series e:b7sp-ttng d:2014-01-01T00:00:00.000Z t:ballot_issue="Engineered Organisms" t:committee_name="Citizens Against the Maui County Farming Band" m:unpaid_expenditures=0 m:closing_cash=865706.12 m:total_recipts=8082455.26 m:total_disbursements=7216749.14 m:surplus_deficit=865706.12
```

## Meta Commands

```ls
metric m:total_recipts p:double l:"Total Receipts" t:dataTypeName=money

metric m:total_disbursements p:double l:"Total Disbursements" t:dataTypeName=money

metric m:closing_cash p:double l:"Closing Cash" t:dataTypeName=money

metric m:unpaid_expenditures p:double l:"Unpaid Expenditures" t:dataTypeName=money

metric m:surplus_deficit p:double l:Surplus/Deficit t:dataTypeName=money

entity e:b7sp-ttng l:"2014 Elections - Ballot Issue Committees" t:attribution="Hawaii State Camapaing Spending Commission" t:url=https://data.hawaii.gov/api/views/b7sp-ttng

property e:b7sp-ttng t:meta.view v:id=b7sp-ttng v:category=Community v:averageRating=0 v:name="2014 Elections - Ballot Issue Committees" v:attribution="Hawaii State Camapaing Spending Commission"

property e:b7sp-ttng t:meta.view.license v:name="Public Domain"

property e:b7sp-ttng t:meta.view.owner v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:displayName="Hawaii Campaign Spending Commission"

property e:b7sp-ttng t:meta.view.tableauthor v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:roleName=editor v:displayName="Hawaii Campaign Spending Commission"
```

## Top Records

```ls
| committee_name                                                               | ballot_issue              | total_recipts | total_disbursements | closing_cash | unpaid_expenditures | surplus_deficit | 
| ============================================================================ | ========================= | ============= | =================== | ============ | =================== | =============== | 
| Support Agriculture Coalition Committee                                      | Engineered Organisms      | 35931.91      | 35931.91            | 0            | 0                   | 0               | 
| BASF Plant Science, L.P.                                                     | Engineered Organisms      | 59000         | 59000               | 0            | 0                   | 0               | 
| Citizens Against the Maui County Farming Band                                | Engineered Organisms      | 8082455.26    | 7216749.14          | 865706.12    | 0                   | 865706.12       | 
| Council for Biotechnology Information Noncandidate Committee                 | Engineered Organisms      | 1000000       | 1000000             | 0            | 0                   | 0               | 
| Dow AgroSciences, LLC                                                        | Engineered Organisms      | 1782906.8     | 1782906.8           | 0            | 0                   | 0               | 
| Good Beginnings Alliance - Children's Action Network                         | Early Childhood Education | 888987.45     | 871605.57           | 17381.88     | 0                   | 17381.88        | 
| Kamehameha Schools Early Education Support                                   | Early Childhood Education | 503154        | 503154              | 0            | 0                   | 0               | 
| Learning Matters                                                             | Early Childhood Education | 1050          | 1050                | 0            | 0                   | 0               | 
| Maui Citizen's Initiative for a Temporary Moratorium on GMO Crop Cultivation | Engineered Organisms      | 121128.14     | 126469.19           | -4784.05     | 0                   | -4784.05        | 
| Maui United                                                                  | Engineered Organisms      | 16088.6       | 16088.6             | 0            | 0                   | 0               | 
```