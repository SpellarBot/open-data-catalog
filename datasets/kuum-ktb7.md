# Risk Management--2011 Employee Healthcare Provider, by Pool, by Vendor

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/risk-management-2011-employee-healthcare-provider-by-pool-by-vendor-3d22b) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/kuum-ktb7) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/kuum-ktb7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/kuum-ktb7/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | kuum-ktb7 |
| Name | Risk Management--2011 Employee Healthcare Provider, by Pool, by Vendor |
| Attribution | Cook County Department of Risk Management |
| Category | Healthcare |
| Created | 2011-09-08T14:14:59Z |
| Publication Date | 2014-10-09T21:53:31Z |

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                           | Data Type | Render Type |
| ======== | ============== | ============================= | ============================== | ========= | =========== |
| Yes      | series tag     | pool                          | Pool                           | text      | text        |
| Yes      | numeric metric | hmo_illinois_a_blue_cross_hmo | HMO Illinois, a Blue Cross HMO | number    | text        |
| Yes      | numeric metric | classic_blue_hmo              | Classic Blue HMO               | number    | text        |
| Yes      | numeric metric | blue_cross_ppo                | Blue Cross PPO                 | number    | text        |
| Yes      | numeric metric | tier_totals                   | Tier Totals                    | number    | text        |
| Yes      | numeric metric | percentage_by_subscriber      | Percentage by Subscriber       | number    | text        |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:kuum-ktb7 d:2011-01-01T00:00:00.000Z t:pool=Single m:classic_blue_hmo=1050 m:blue_cross_ppo=1971 m:tier_totals=7700 m:hmo_illinois_a_blue_cross_hmo=4679 m:percentage_by_subscriber=0.340858787

series e:kuum-ktb7 d:2011-01-01T00:00:00.000Z t:pool="Employee and 1 dependent" m:classic_blue_hmo=772 m:blue_cross_ppo=1455 m:tier_totals=5609 m:hmo_illinois_a_blue_cross_hmo=3382 m:percentage_by_subscriber=0.248295706

series e:kuum-ktb7 d:2011-01-01T00:00:00.000Z t:pool=Family m:classic_blue_hmo=1171 m:blue_cross_ppo=2309 m:tier_totals=9281 m:hmo_illinois_a_blue_cross_hmo=5801 m:percentage_by_subscriber=0.410845507
```

## Meta Commands

```ls
metric m:hmo_illinois_a_blue_cross_hmo p:integer l:"HMO Illinois, a Blue Cross HMO" t:dataTypeName=number

metric m:classic_blue_hmo p:integer l:"Classic Blue HMO" t:dataTypeName=number

metric m:blue_cross_ppo p:integer l:"Blue Cross PPO" t:dataTypeName=number

metric m:tier_totals p:integer l:"Tier Totals" t:dataTypeName=number

metric m:percentage_by_subscriber p:double l:"Percentage by Subscriber" t:dataTypeName=number

entity e:kuum-ktb7 l:"Risk Management--2011 Employee Healthcare Provider, by Pool, by Vendor" t:attribution="Cook County Department of Risk Management" t:url=https://datacatalog.cookcountyil.gov/api/views/kuum-ktb7

property e:kuum-ktb7 t:meta.view v:id=kuum-ktb7 v:category=Healthcare v:averageRating=0 v:name="Risk Management--2011 Employee Healthcare Provider, by Pool, by Vendor" v:attribution="Cook County Department of Risk Management"

property e:kuum-ktb7 t:meta.view.license v:name="Public Domain"

property e:kuum-ktb7 t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:kuum-ktb7 t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| pool                     | hmo_illinois_a_blue_cross_hmo | classic_blue_hmo | blue_cross_ppo | tier_totals | percentage_by_subscriber | 
| ======================== | ============================= | ================ | ============== | =========== | ======================== | 
| Single                   | 4679                          | 1050             | 1971           | 7700        | 0.340858787              | 
| Employee and 1 dependent | 3382                          | 772              | 1455           | 5609        | 0.248295706              | 
| Family                   | 5801                          | 1171             | 2309           | 9281        | 0.410845507              | 
| Totals                   | 13862                         | 2993             | 5735           | 22590       |                          | 
```