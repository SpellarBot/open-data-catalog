# 2014 Elections - Total Disbursements

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2014-elections-total-disbursements-17c27) |
| Metadata | [Link](https://data.hawaii.gov/api/views/wwxb-ba4w) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/wwxb-ba4w/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/wwxb-ba4w/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | wwxb-ba4w |
| Name | 2014 Elections - Total Disbursements |
| Category | Community |
| Created | 2015-01-12T20:09:48Z |
| Publication Date | 2015-01-12T20:31:55Z |
| Rows Updated | 2015-01-12T20:31:36Z |

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| No       | time           | :updated_at          | updated_at           | meta_data | meta_data   |
| Yes      | series tag     | type_of_disbursement | Type of Disbursement | text      | text        |
| Yes      | numeric metric | total_amount         | Total Amount         | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:wwxb-ba4w d:2015-01-12T12:23:58.000Z t:type_of_disbursement=Expenditures m:total_amount=19133482

series e:wwxb-ba4w d:2015-01-12T12:31:32.000Z t:type_of_disbursement="Loans Repaid/Forgiven" m:total_amount=309582.43

series e:wwxb-ba4w d:2015-01-12T12:31:35.000Z t:type_of_disbursement="Unpaid Expenditures Paid/Forgiven" m:total_amount=390452.4
```

## Meta Commands

```ls
entity e:wwxb-ba4w l:"2014 Elections - Total Disbursements" t:url=https://data.hawaii.gov/api/views/wwxb-ba4w

property e:wwxb-ba4w t:meta.view v:id=wwxb-ba4w v:category=Community v:averageRating=0 v:name="2014 Elections - Total Disbursements"

property e:wwxb-ba4w t:meta.view.license v:name="Public Domain"

property e:wwxb-ba4w t:meta.view.owner v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:roleName=editor v:displayName="Hawaii Campaign Spending Commission"

property e:wwxb-ba4w t:meta.view.tableauthor v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:roleName=editor v:displayName="Hawaii Campaign Spending Commission"
```