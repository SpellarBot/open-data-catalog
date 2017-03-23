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
| Included | Schema Type | Field Name   | Name         | Data Type | Render Type   |
| ======== | =========== | ============ | ============ | ========= | ============= |
| No       | time        | :updated_at  | updated_at   | meta_data | meta_data     |
| Yes      | series tag  | site_name    | Site Name    | text      | text          |
| No       |             | clinic_date  | Clinic Date  | text      | calendar_date |
| Yes      | series tag  | clinic_hours | Clinic Hours | text      | text          |
| Yes      | series tag  | clinic_room  | Clinic Room  | text      | text          |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = clinic_date
```

## Data Commands

```ls
series e:fqyg-zgdm d:2016-08-16T12:32:30.000Z t:clinic_hours="7-8  a.m." t:site_name=Brightwater t:clinic_room="""Q"" room" m:row_number.fqyg-zgdm=1

series e:fqyg-zgdm d:2016-08-16T12:32:30.000Z t:clinic_hours="11 am - noon" t:site_name=Elections t:clinic_room="Large Conf Room" m:row_number.fqyg-zgdm=2

series e:fqyg-zgdm d:2016-08-16T12:32:43.000Z t:clinic_hours="2 - 4:30 p.m." t:site_name="North Transit Base" t:clinic_room=Classrooms m:row_number.fqyg-zgdm=3
```

## Meta Commands

```ls
metric m:row_number.fqyg-zgdm p:long l:"Row Number"

entity e:fqyg-zgdm l:flu-clinic-test t:url=https://data.kingcounty.gov/api/views/fqyg-zgdm

property e:fqyg-zgdm t:meta.view v:id=fqyg-zgdm v:averageRating=0 v:name=flu-clinic-test

property e:fqyg-zgdm t:meta.view.owner v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:displayName="King County Webteam"

property e:fqyg-zgdm t:meta.view.tableauthor v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:roleName=administrator v:displayName="King County Webteam"
```