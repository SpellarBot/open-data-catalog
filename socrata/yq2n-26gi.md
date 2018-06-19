# Budget 2012- Total Budget

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/budget-2012-total-budget-ab83b) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/yq2n-26gi) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/yq2n-26gi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/yq2n-26gi/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | yq2n-26gi |
| Name | Budget 2012- Total Budget |
| Attribution | King County |
| Category | Budget |
| Tags | budget |
| Created | 2011-09-26T14:47:10Z |
| Publication Date | 2011-09-26T14:47:23Z |

## Description

General fund versus total budget. More at http://www.kingcounty.gov/budget

## Columns

```ls
| Included | Schema Type | Field Name   | Name   | Data Type | Render Type |
| ======== | =========== | ============ | ====== | ========= | =========== |
| Yes      | series tag  | general_fund | Fund   | text      | text        |
| No       |             | _            | Amount | money     | money       |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = _
```

## Data Commands

```ls
series e:yq2n-26gi d:2012-01-01T00:00:00.000Z t:general_fund="General fund" m:row_number.yq2n-26gi=1

series e:yq2n-26gi d:2012-01-01T00:00:00.000Z t:general_fund="All other funds" m:row_number.yq2n-26gi=2
```

## Meta Commands

```ls
metric m:row_number.yq2n-26gi p:long l:"Row Number"

entity e:yq2n-26gi l:"Budget 2012- Total Budget" t:attribution="King County" t:url=https://data.kingcounty.gov/api/views/yq2n-26gi

property e:yq2n-26gi t:meta.view v:id=yq2n-26gi v:category=Budget v:attributionLink=http://www.kingcounty.gov/budget v:averageRating=0 v:name="Budget 2012- Total Budget" v:attribution="King County"

property e:yq2n-26gi t:meta.view.license v:name="Public Domain"

property e:yq2n-26gi t:meta.view.owner v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:displayName="King County Webteam"

property e:yq2n-26gi t:meta.view.tableauthor v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:roleName=administrator v:displayName="King County Webteam"
```

## Top Records

```ls
| general_fund    | _          | 
| =============== | ========== | 
| General fund    | 652011441  | 
| All other funds | 4759455806 | 
```