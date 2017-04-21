# 2014 Elections - Total Receipts

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2014-elections-total-receipts-54d1e) |
| Metadata | [Link](https://data.hawaii.gov/api/views/9v3n-fxb7) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/9v3n-fxb7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/9v3n-fxb7/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 9v3n-fxb7 |
| Name | 2014 Elections - Total Receipts |
| Category | Community |
| Created | 2015-01-12T19:49:45Z |
| Publication Date | 2015-01-12T20:00:30Z |

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | series tag     | type_of_receipt | Type of Receipt | text      | text        |
| Yes      | numeric metric | total_amount    | Total Amount    | money     | money       |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:9v3n-fxb7 d:2014-01-01T00:00:00.000Z t:type_of_receipt="Other Receipts" m:total_amount=523496.72

series e:9v3n-fxb7 d:2014-01-01T00:00:00.000Z t:type_of_receipt=Loans m:total_amount=617661.5

series e:9v3n-fxb7 d:2014-01-01T00:00:00.000Z t:type_of_receipt="Contributions Received" m:total_amount=19893989.11
```

## Meta Commands

```ls
metric m:total_amount p:double l:"Total Amount" t:dataTypeName=money

entity e:9v3n-fxb7 l:"2014 Elections - Total Receipts" t:url=https://data.hawaii.gov/api/views/9v3n-fxb7

property e:9v3n-fxb7 t:meta.view v:id=9v3n-fxb7 v:category=Community v:averageRating=0 v:name="2014 Elections - Total Receipts"

property e:9v3n-fxb7 t:meta.view.license v:name="Public Domain"

property e:9v3n-fxb7 t:meta.view.owner v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:displayName="Hawaii Campaign Spending Commission"

property e:9v3n-fxb7 t:meta.view.tableauthor v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:roleName=editor v:displayName="Hawaii Campaign Spending Commission"
```

## Top Records

```ls
| type_of_receipt        | total_amount | 
| ====================== | ============ | 
| Other Receipts         | 523496.72    | 
| Loans                  | 617661.5     | 
| Contributions Received | 19893989.11  | 
```