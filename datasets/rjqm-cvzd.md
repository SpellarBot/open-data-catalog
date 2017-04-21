# 2013 Proposed Budget, General Fund Sources

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2013-proposed-budget-general-fund-sources-935dc) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/rjqm-cvzd) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/rjqm-cvzd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/rjqm-cvzd/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | rjqm-cvzd |
| Name | 2013 Proposed Budget, General Fund Sources |
| Attribution | King County Executive |
| Category | Budget |
| Tags | budget, 2013, budget2013 |
| Created | 2012-09-14T17:27:42Z |
| Publication Date | 2012-09-23T00:27:26Z |

## Description

King County budget proposed September 2012 by Executive for 2013, general fund, broken down by revenue source. See http://www.kingcounty.gov/budget for more.

## Columns

```ls
| Included | Schema Type | Field Name   | Name         | Data Type | Render Type |
| ======== | =========== | ============ | ============ | ========= | =========== |
| Yes      | series tag  | general_fund | General Fund | text      | text        |
| Yes      | series tag  | source       | Source       | text      | text        |
| No       |             | _            | 2013 Budget  | money     | money       |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = _
```

## Data Commands

```ls
series e:rjqm-cvzd d:2013-01-01T00:00:00.000Z t:general_fund=000000010 t:source=Taxes m:row_number.rjqm-cvzd=1

series e:rjqm-cvzd d:2013-01-01T00:00:00.000Z t:general_fund=000000010 t:source="Licenses And Permits" m:row_number.rjqm-cvzd=2

series e:rjqm-cvzd d:2013-01-01T00:00:00.000Z t:general_fund=000000010 t:source="Federal Grants Direct" m:row_number.rjqm-cvzd=3
```

## Meta Commands

```ls
metric m:row_number.rjqm-cvzd p:long l:"Row Number"

entity e:rjqm-cvzd l:"2013 Proposed Budget, General Fund Sources" t:attribution="King County Executive" t:url=https://data.kingcounty.gov/api/views/rjqm-cvzd

property e:rjqm-cvzd t:meta.view v:id=rjqm-cvzd v:category=Budget v:attributionLink=http://www.kingcounty.gov/budget v:averageRating=0 v:name="2013 Proposed Budget, General Fund Sources" v:attribution="King County Executive"

property e:rjqm-cvzd t:meta.view.license v:name="Public Domain"

property e:rjqm-cvzd t:meta.view.owner v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"

property e:rjqm-cvzd t:meta.view.tableauthor v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"
```

## Top Records

```ls
| general_fund | source                     | _         | 
| ============ | ========================== | ========= | 
| 000000010    | Taxes                      | 428366863 | 
| 000000010    | Licenses And Permits       | 3842408   | 
| 000000010    | Federal Grants Direct      | 505839    | 
| 000000010    | Federal Shared Revenues    | 120000    | 
| 000000010    | Federal Grants Indirect    | 7908472   | 
| 000000010    | State Grants               | 2857348   | 
| 000000010    | State Entitlements         | 8924002   | 
| 000000010    | Intergovernmental Payments | 78771757  | 
| 000000010    | Charge For Services        | 118033395 | 
| 000000010    | Fines And Forfeits         | 8577719   | 
```