# 2014 Elections - Top 10 Receipts (includes Contributions Received, Other Receipts and Loans)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2014-elections-top-10-receipts-includes-contributions-received-other-receipts-and-loans-ca1a7) |
| Metadata | [Link](https://data.hawaii.gov/api/views/caat-4tnh) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/caat-4tnh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/caat-4tnh/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | caat-4tnh |
| Name | 2014 Elections - Top 10 Receipts (includes Contributions Received, Other Receipts and Loans) |
| Category | Community |
| Tags | campaign spending commission |
| Created | 2015-01-12T18:26:53Z |
| Publication Date | 2015-01-12T18:41:02Z |

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | series tag     | candidate_name | Candidate Name | text      | text        |
| Yes      | numeric metric | receipts       | Receipts       | money     | money       |
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
series e:caat-4tnh d:2014-01-01T00:00:00.000Z t:office=Governor t:status=Challenger t:candidate_name="Ige, David" t:won=Y m:receipts=2396974.27

series e:caat-4tnh d:2014-01-01T00:00:00.000Z t:office="Lt. Governor" t:status=Incumbent t:candidate_name="Tsutsui, Shan" t:won=Y m:receipts=1252792.56

series e:caat-4tnh d:2014-01-01T00:00:00.000Z t:office=Mayor t:status=Incumbent t:candidate_name="Arakawa, Alan" t:won=Y m:receipts=941137.28
```

## Meta Commands

```ls
metric m:receipts p:double l:Receipts t:dataTypeName=money

entity e:caat-4tnh l:"2014 Elections - Top 10 Receipts (includes Contributions Received, Other Receipts and Loans)" t:url=https://data.hawaii.gov/api/views/caat-4tnh

property e:caat-4tnh t:meta.view v:id=caat-4tnh v:category=Community v:averageRating=0 v:name="2014 Elections - Top 10 Receipts (includes Contributions Received, Other Receipts and Loans)"

property e:caat-4tnh t:meta.view.license v:name="Public Domain"

property e:caat-4tnh t:meta.view.owner v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:displayName="Hawaii Campaign Spending Commission"

property e:caat-4tnh t:meta.view.tableauthor v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:roleName=editor v:displayName="Hawaii Campaign Spending Commission"
```

## Top Records

```ls
| candidate_name      | receipts   | office           | status     | won | 
| =================== | ========== | ================ | ========== | === | 
| Ige, David          | 2396974.27 | Governor         | Challenger | Y   | 
| Tsutsui, Shan       | 1252792.56 | Lt. Governor     | Incumbent  | Y   | 
| Arakawa, Alan       | 941137.28  | Mayor            | Incumbent  | Y   | 
| Martin, Ernest      | 605828.34  | Honolulu Council | Incumbent  | Y   | 
| Clayton, Hee        | 380601.25  | Lt. Governor     | Challenger | N   | 
| Hannemann, Mufi     | 367149.56  | Governor         | Challenger | N   | 
| Ahu, Elwin          | 322956.74  | Lt. Governor     | Challenger | N   | 
| Abercrombie, Neil   | 4928328.15 | Governor         | Incumbent  | N   | 
| Carvalho, Bernard   | 296772.31  | Mayor            | Incumbent  | Y   | 
| Aiona, James (Duke) | 1532306.65 | Governor         | Challenger | N   | 
```