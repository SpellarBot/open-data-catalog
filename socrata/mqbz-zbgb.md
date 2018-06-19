# 2014 Elections - Total Receipts and Disbursements by Office

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2014-elections-total-receipts-and-disbursements-by-office-608db) |
| Metadata | [Link](https://data.hawaii.gov/api/views/mqbz-zbgb) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/mqbz-zbgb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/mqbz-zbgb/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | mqbz-zbgb |
| Name | 2014 Elections - Total Receipts and Disbursements by Office |
| Category | Community |
| Created | 2015-01-12T19:19:50Z |
| Publication Date | 2015-01-12T19:40:34Z |

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | series tag     | office                     | Office                     | text      | text        |
| Yes      | numeric metric | total_number_of_candidates | Total Number of Candidates | number    | number      |
| Yes      | numeric metric | total_receipts             | Total Receipts             | money     | money       |
| Yes      | numeric metric | total_disbursements        | Total Disbursements        | money     | money       |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:mqbz-zbgb d:2014-01-01T00:00:00.000Z t:office=House m:total_number_of_candidates=127 m:total_disbursements=3293892.62 m:total_receipts=3631967.43

series e:mqbz-zbgb d:2014-01-01T00:00:00.000Z t:office="Office of Hawaiian Affairs" m:total_number_of_candidates=22 m:total_disbursements=429145.57 m:total_receipts=431354.51

series e:mqbz-zbgb d:2014-01-01T00:00:00.000Z t:office="Kauai Mayor" m:total_number_of_candidates=4 m:total_disbursements=358503.79 m:total_receipts=371875.46
```

## Meta Commands

```ls
metric m:total_number_of_candidates p:integer l:"Total Number of Candidates" t:dataTypeName=number

metric m:total_receipts p:double l:"Total Receipts" t:dataTypeName=money

metric m:total_disbursements p:double l:"Total Disbursements" t:dataTypeName=money

entity e:mqbz-zbgb l:"2014 Elections - Total Receipts and Disbursements by Office" t:url=https://data.hawaii.gov/api/views/mqbz-zbgb

property e:mqbz-zbgb t:meta.view v:id=mqbz-zbgb v:category=Community v:averageRating=0 v:name="2014 Elections - Total Receipts and Disbursements by Office"

property e:mqbz-zbgb t:meta.view.license v:name="Public Domain"

property e:mqbz-zbgb t:meta.view.owner v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:displayName="Hawaii Campaign Spending Commission"

property e:mqbz-zbgb t:meta.view.tableauthor v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:roleName=editor v:displayName="Hawaii Campaign Spending Commission"
```

## Top Records

```ls
| office                     | total_number_of_candidates | total_receipts | total_disbursements | 
| ========================== | ========================== | ============== | =================== | 
| House                      | 127                        | 3631967.43     | 3293892.62          | 
| Office of Hawaiian Affairs | 22                         | 431354.51      | 429145.57           | 
| Kauai Mayor                | 4                          | 371875.46      | 358503.79           | 
| Maui County Council        | 22                         | 727136.85      | 645122.23           | 
| Hawaii County Council      | 28                         | 323770.35      | 290702.91           | 
| Governor                   | 8                          | 9231335.57     | 9173312.07          | 
| Lt. Governor               | 9                          | 2020902.96     | 2261777.17          | 
| Honolulu City Council      | 15                         | 1301467.14     | 924671.81           | 
| Senate                     | 37                         | 1557249.95     | 1274681.2           | 
| Kauai County Council       | 20                         | 458358.11      | 390857.76           | 
```