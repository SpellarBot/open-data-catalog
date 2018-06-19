# Risk Management - Employee Enrollment and Pool - 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/risk-management-employee-enrollment-and-pool-2012-d0e45) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/ccqh-74ig) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/ccqh-74ig/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/ccqh-74ig/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | ccqh-74ig |
| Name | Risk Management - Employee Enrollment and Pool - 2012 |
| Attribution | Cook County Department of Risk Management |
| Category | Finance & Administration |
| Created | 2012-05-21T16:37:09Z |
| Publication Date | 2014-10-09T22:33:13Z |

## Description

2012 Employee insurance plan enrollment as of May 21, 2012

## Columns

```ls
| Included | Schema Type | Field Name               | Name                     | Data Type | Render Type |
| ======== | =========== | ======================== | ======================== | ========= | =========== |
| Yes      | series tag  | pool                     | Pool                     | text      | text        |
| Yes      | series tag  | hmo_il_a_blue_cross_hmo  | HMO IL, a Blue Cross HMO | text      | text        |
| Yes      | series tag  | classic_blue_hmo         | Classic Blue HMO         | text      | text        |
| Yes      | series tag  | blue_cross_ppo           | Blue Cross PPO           | text      | text        |
| Yes      | series tag  | tier_totals              | Tier totals              | text      | text        |
| Yes      | series tag  | percentage_by_subscriber | percentage by subscriber | text      | text        |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ccqh-74ig d:2012-01-01T00:00:00.000Z t:tier_totals="Tier totals" t:blue_cross_ppo="Blue Cross PPO" t:classic_blue_hmo="Classic Blue HMO" t:pool=Pool t:hmo_il_a_blue_cross_hmo="HMO IL, a Blue Cross HMO" t:percentage_by_subscriber="percentage by subscriber" m:row_number.ccqh-74ig=1

series e:ccqh-74ig d:2012-01-01T00:00:00.000Z t:tier_totals=7,303 t:blue_cross_ppo=1,937 t:classic_blue_hmo=1,030 t:pool=Single t:hmo_il_a_blue_cross_hmo=4,336 t:percentage_by_subscriber=33.47% m:row_number.ccqh-74ig=2

series e:ccqh-74ig d:2012-01-01T00:00:00.000Z t:tier_totals=5,284 t:blue_cross_ppo=1,400 t:classic_blue_hmo=739 t:pool="Employee and 1 dependent" t:hmo_il_a_blue_cross_hmo=3,145 t:percentage_by_subscriber=24.21% m:row_number.ccqh-74ig=3
```

## Meta Commands

```ls
metric m:row_number.ccqh-74ig p:long l:"Row Number"

entity e:ccqh-74ig l:"Risk Management - Employee Enrollment and Pool - 2012" t:attribution="Cook County Department of Risk Management" t:url=https://datacatalog.cookcountyil.gov/api/views/ccqh-74ig

property e:ccqh-74ig t:meta.view v:id=ccqh-74ig v:category="Finance & Administration" v:attributionLink=http://www.cookcountyrisk.com/ v:averageRating=0 v:name="Risk Management - Employee Enrollment and Pool - 2012" v:attribution="Cook County Department of Risk Management"

property e:ccqh-74ig t:meta.view.license v:name="Public Domain"

property e:ccqh-74ig t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:ccqh-74ig t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| pool                     | hmo_il_a_blue_cross_hmo  | classic_blue_hmo | blue_cross_ppo | tier_totals | percentage_by_subscriber | 
| ======================== | ======================== | ================ | ============== | =========== | ======================== | 
| Pool                     | HMO IL, a Blue Cross HMO | Classic Blue HMO | Blue Cross PPO | Tier totals | percentage by subscriber | 
| Single                   | 4,336                    | 1,030            | 1,937          | 7,303       | 33.47%                   | 
| Employee and 1 dependent | 3,145                    | 739              | 1,400          | 5,284       | 24.21%                   | 
| Family                   | 5,669                    | 1,173            | 2,393          | 9,235       | 42.32%                   | 
| Totals                   | 13,150                   | 2,942            | 5,730          | 21,822      | 100.00%                  | 
```