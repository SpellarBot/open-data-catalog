# 2014 Elections - Total Disbursements

## Dataset

* [Dataset URL](https://data.hawaii.gov/api/views/wwxb-ba4w/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/2014-elections-total-disbursements-17c27)
* [Metadata URL](https://data.hawaii.gov/api/views/wwxb-ba4w)
* Id = wwxb-ba4w
* Name = 2014 Elections - Total Disbursements
* Category = Community
* Created = 2015-01-12T20:09:48Z
* Publication Date = 2015-01-12T20:31:55Z
* Rows Updated = 2015-01-12T20:31:36Z

## Description



## Columns

```ls
| Name                 | Field Name           | Data Type | Render Type | Schema Type    | Included | 
| ==================== | ==================== | ========= | =========== | ============== | ======== | 
| updated_at           | :updated_at          | meta_data | meta_data   | time           | No       | 
| Type of Disbursement | type_of_disbursement | text      | text        | series tag     | Yes      | 
| Total Amount         | total_amount         | money     | money       | numeric metric | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
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

property e:wwxb-ba4w t:meta.view d:2017-03-08T02:16:36.558Z v:id=wwxb-ba4w v:category=Community v:averageRating=0 v:name="2014 Elections - Total Disbursements"

property e:wwxb-ba4w t:meta.view.license d:2017-03-08T02:16:36.558Z v:name="Public Domain"

property e:wwxb-ba4w t:meta.view.owner d:2017-03-08T02:16:36.558Z v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:roleName=editor v:displayName="Hawaii Campaign Spending Commission"

property e:wwxb-ba4w t:meta.view.tableauthor d:2017-03-08T02:16:36.558Z v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:roleName=editor v:displayName="Hawaii Campaign Spending Commission"
```