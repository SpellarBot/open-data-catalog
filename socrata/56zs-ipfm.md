# 2014 Elections - Top 10 Disbursements (includes Expenditures, Loans Repaid/Forgiven and Unpaid Ex. Paid/Forgiven)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2014-elections-top-10-disbursements-includes-expenditures-loans-repaid-forgiven-and-unpaid-634c2) |
| Metadata | [Link](https://data.hawaii.gov/api/views/56zs-ipfm) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/56zs-ipfm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/56zs-ipfm/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 56zs-ipfm |
| Name | 2014 Elections - Top 10 Disbursements (includes Expenditures, Loans Repaid/Forgiven and Unpaid Ex. Paid/Forgiven) |
| Category | Community |
| Tags | campaign spending commission |
| Created | 2015-01-13T00:31:35Z |
| Publication Date | 2015-01-13T17:48:34Z |

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | series tag     | candidate_name | Candidate Name | text      | text        |
| Yes      | numeric metric | disbursements  | Disbursements  | money     | money       |
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
series e:56zs-ipfm d:2014-01-01T00:00:00.000Z t:office=Governor t:status=Challenger t:candidate_name="Hannemann, Mufi" t:won=N m:disbursements=286276.97

series e:56zs-ipfm d:2014-01-01T00:00:00.000Z t:office=Governor t:status=Incumbent t:candidate_name="Abercrombie, Neil" t:won=N m:disbursements=5296582.64

series e:56zs-ipfm d:2014-01-01T00:00:00.000Z t:office=Governor t:status=Challenger t:candidate_name="Ige, David" t:won=Y m:disbursements=2029646.05
```

## Meta Commands

```ls
metric m:disbursements p:double l:Disbursements t:dataTypeName=money

entity e:56zs-ipfm l:"2014 Elections - Top 10 Disbursements (includes Expenditures, Loans Repaid/Forgiven and Unpaid Ex. Paid/Forgiven)" t:url=https://data.hawaii.gov/api/views/56zs-ipfm

property e:56zs-ipfm t:meta.view v:id=56zs-ipfm v:category=Community v:averageRating=0 v:name="2014 Elections - Top 10 Disbursements (includes Expenditures, Loans Repaid/Forgiven and Unpaid Ex. Paid/Forgiven)"

property e:56zs-ipfm t:meta.view.license v:name="Public Domain"

property e:56zs-ipfm t:meta.view.owner v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:displayName="Hawaii Campaign Spending Commission"

property e:56zs-ipfm t:meta.view.tableauthor v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:roleName=editor v:displayName="Hawaii Campaign Spending Commission"
```

## Top Records

```ls
| candidate_name      | disbursements | office           | status     | won | 
| =================== | ============= | ================ | ========== | === | 
| Hannemann, Mufi     | 286276.97     | Governor         | Challenger | N   | 
| Abercrombie, Neil   | 5296582.64    | Governor         | Incumbent  | N   | 
| Ige, David          | 2029646.05    | Governor         | Challenger | Y   | 
| Aiona, James (Duke) | 1554229.47    | Governor         | Challenger | N   | 
| Tsutsui, Shan       | 1184286.02    | Lt. Governor     | Incumbent  | Y   | 
| Arakawa, Alan       | 757865.1      | Mayor            | Incumbent  | Y   | 
| Hee, Clayton        | 707310.8      | Lt. Governor     | Challenger | N   | 
| Ahu, Elwin          | 309515.81     | Lt. Governor     | Challenger | N   | 
| Martin, Ernest      | 295877.57     | Honolulu Council | Incumbent  | Y   | 
| Carvalho, Bernard   | 283673.56     | Mayor            | Incumbent  | N   | 
```