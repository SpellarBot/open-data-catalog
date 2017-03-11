# 2014 Elections - Contributions Received (more than $100) by Contibutor Type

## Dataset

* [Dataset URL](https://data.hawaii.gov/api/views/hty7-p2e9/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/2014-elections-contributions-received-more-than-100-by-contibutor-type-99b7e)
* Id = hty7-p2e9
* Name = 2014 Elections - Contributions Received (more than $100) by Contibutor Type
* Category = Community
* Tags = [cmapaign spending commission]
* Created = 2015-01-12T21:24:48Z
* Publication Date = 2015-01-12T21:45:56Z
* Rows Updated = 2015-01-12T21:45:00Z

## Description



## Columns

```ls
| Name                                       | Field Name                                 | Data Type | Render Type | Schema Type    | Included | 
| ========================================== | ========================================== | ========= | =========== | ============== | ======== | 
| updated_at                                 | :updated_at                                | meta_data | meta_data   | time           | Yes      | 
| Contributor Type                           | contributor_type                           | text      | text        | series tag     | Yes      | 
| Count                                      | count                                      | number    | number      | numeric metric | Yes      | 
| Percentage of Total Count                  | percentage_of_total_count                  | percent   | percent     | numeric metric | Yes      | 
| Total Contribution Received                | total_contribution_received                | money     | money       | numeric metric | Yes      | 
| Percentage of Total Contributions Received | percentage_of_total_contributions_received | percent   | percent     | numeric metric | Yes      | 
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
series e:hty7-p2e9 d:2015-01-12T13:35:55.000Z t:contributor_type="Candidate Committee" m:count=128 m:percentage_of_total_contributions_received=0.34 m:percentage_of_total_count=0.64 m:total_contribution_received=39575.16

series e:hty7-p2e9 d:2015-01-12T13:36:43.000Z t:contributor_type="Immediate Family" m:count=310 m:percentage_of_total_contributions_received=2.06 m:percentage_of_total_count=1.54 m:total_contribution_received=238752.53

series e:hty7-p2e9 d:2015-01-12T13:37:33.000Z t:contributor_type=Individual m:count=14966 m:percentage_of_total_contributions_received=68.21 m:percentage_of_total_count=74.57 m:total_contribution_received=7912040.29
```

## Meta Commands

```ls
metric m:count p:integer l:Count t:dataTypeName=number

entity e:hty7-p2e9 l:"2014 Elections - Contributions Received (more than $100) by Contibutor Type" t:url=https://data.hawaii.gov/api/views/hty7-p2e9

property e:hty7-p2e9 t:meta.view d:2017-03-03T14:33:26.710Z v:id=hty7-p2e9 v:category=Community v:averageRating=0 v:name="2014 Elections - Contributions Received (more than $100) by Contibutor Type"

property e:hty7-p2e9 t:meta.view.license d:2017-03-03T14:33:26.710Z v:name="Public Domain"

property e:hty7-p2e9 t:meta.view.owner d:2017-03-03T14:33:26.710Z v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:roleName=editor v:displayName="Hawaii Campaign Spending Commission"

property e:hty7-p2e9 t:meta.view.tableauthor d:2017-03-03T14:33:26.710Z v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:roleName=editor v:displayName="Hawaii Campaign Spending Commission"
```