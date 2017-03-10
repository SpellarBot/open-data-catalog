# flu-clinic-test

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/flu-clinic-test) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/fqyg-zgdm) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/fqyg-zgdm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/fqyg-zgdm/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | fqyg-zgdm |
| Name | flu-clinic-test |
| Created | 2016-08-16T19:32:26Z |
| Publication Date | 2016-08-16T19:51:01Z |
| Rows Updated | 2016-08-16T19:50:12Z |

## Columns

```ls
| Included | Schema Type | Field Name   | Name         | Data Type     | Render Type   |
| ======== | =========== | ============ | ============ | ============= | ============= |
| Yes      | series tag  | site_name    | Site Name    | text          | text          |
| Yes      | time        | clinic_date  | Clinic Date  | calendar_date | calendar_date |
| Yes      | series tag  | clinic_hours | Clinic Hours | text          | text          |
| Yes      | series tag  | clinic_room  | Clinic Room  | text          | text          |
```

## Time Field

```ls
Value = clinic_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:fqyg-zgdm l:flu-clinic-test t:url=https://data.kingcounty.gov/api/views/fqyg-zgdm

property e:fqyg-zgdm t:meta.view v:id=fqyg-zgdm v:averageRating=0 v:name=flu-clinic-test

property e:fqyg-zgdm t:meta.view.owner v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:roleName=administrator v:displayName="King County Webteam"

property e:fqyg-zgdm t:meta.view.tableauthor v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:roleName=administrator v:displayName="King County Webteam"
```