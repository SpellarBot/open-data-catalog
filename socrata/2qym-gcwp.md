# IE for 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ie-for-2014-1dfd5) |
| Metadata | [Link](https://data.hawaii.gov/api/views/2qym-gcwp) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/2qym-gcwp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/2qym-gcwp/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 2qym-gcwp |
| Name | IE for 2014 |
| Created | 2014-11-14T23:26:46Z |
| Publication Date | 2015-01-06T18:30:09Z |

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | series tag     | support_oppose | Support/Oppose | text      | text        |
| Yes      | numeric metric | amount         | Amount         | money     | money       |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:2qym-gcwp d:2014-01-01T00:00:00.000Z t:support_oppose="IEs Supporting Candidates (Positive)" m:amount=2134776.92

series e:2qym-gcwp d:2014-01-01T00:00:00.000Z t:support_oppose="IEs Opposing Candidates (Negative)" m:amount=2596250.96
```

## Meta Commands

```ls
metric m:amount p:double l:Amount t:dataTypeName=money

entity e:2qym-gcwp l:"IE for 2014" t:url=https://data.hawaii.gov/api/views/2qym-gcwp

property e:2qym-gcwp t:meta.view v:id=2qym-gcwp v:averageRating=0 v:name="IE for 2014"

property e:2qym-gcwp t:meta.view.owner v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:displayName="Hawaii Campaign Spending Commission"

property e:2qym-gcwp t:meta.view.tableauthor v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:roleName=editor v:displayName="Hawaii Campaign Spending Commission"
```

## Top Records

```ls
| support_oppose                       | amount     | 
| ==================================== | ========== | 
| IEs Supporting Candidates (Positive) | 2134776.92 | 
| IEs Opposing Candidates (Negative)   | 2596250.96 | 
```