# Montgomery Cable Schedule

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/montgomery-cable-schedule) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/9why-cbxu) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/9why-cbxu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/9why-cbxu/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | 9why-cbxu |
| Name | Montgomery Cable Schedule |
| Attribution | Montgomery County, MD |
| Category | Community/Recreation |
| Tags | cable, programming, tv, shows, television, channels |
| Created | 2016-08-10T10:33:05Z |
| Publication Date | 2016-11-02T12:54:03Z |

## Description

Daily programming guide Update Frequency: Weekly

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| No       |             | id          | ID         | text      | number      |
| Yes      | series tag  | times       | Times      | text      | text        |
| Yes      | series tag  | sunday      | Sunday     | text      | text        |
| Yes      | series tag  | monday      | Monday     | text      | text        |
| Yes      | series tag  | tuesday     | Tuesday    | text      | text        |
| Yes      | series tag  | wednesday   | Wednesday  | text      | text        |
| Yes      | series tag  | thursday    | Thursday   | text      | text        |
| Yes      | series tag  | friday      | Friday     | text      | text        |
| Yes      | series tag  | saturday    | Saturday   | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = id
```

## Data Commands

```ls
series e:9why-cbxu d:2016-11-02T15:52:09.000Z t:wednesday="One on One" t:times="6:00 PM" t:thursday="Seniors Today" t:monday=Parks t:sunday="Seniors Today" t:saturday=Parks t:friday="The Decision Makers" t:tuesday="Seniors Today" m:row_number.9why-cbxu=1

series e:9why-cbxu d:2016-11-02T15:52:09.000Z t:times="3:45 AM" m:row_number.9why-cbxu=2

series e:9why-cbxu d:2016-11-02T15:52:09.000Z t:wednesday="En Sintonia" t:times="1:00 AM" t:thursday="Mont. Al Dia" t:monday="Somos Montgomery" t:sunday=MTA t:saturday=MTA t:friday=Parks t:tuesday="Seniors Today" m:row_number.9why-cbxu=3
```

## Meta Commands

```ls
metric m:row_number.9why-cbxu p:long l:"Row Number"

entity e:9why-cbxu l:"Montgomery Cable Schedule" t:attribution="Montgomery County, MD" t:url=https://data.montgomerycountymd.gov/api/views/9why-cbxu

property e:9why-cbxu t:meta.view v:id=9why-cbxu v:category=Community/Recreation v:averageRating=0 v:name="Montgomery Cable Schedule" v:attribution="Montgomery County, MD"

property e:9why-cbxu t:meta.view.license v:name="Public Domain"

property e:9why-cbxu t:meta.view.owner v:id=rykt-6e5x v:profileImageUrlMedium=/api/users/rykt-6e5x/profile_images/THUMB v:profileImageUrlLarge=/api/users/rykt-6e5x/profile_images/LARGE v:screenName=Brian v:profileImageUrlSmall=/api/users/rykt-6e5x/profile_images/TINY v:displayName=Brian

property e:9why-cbxu t:meta.view.tableauthor v:id=rykt-6e5x v:profileImageUrlMedium=/api/users/rykt-6e5x/profile_images/THUMB v:profileImageUrlLarge=/api/users/rykt-6e5x/profile_images/LARGE v:screenName=Brian v:profileImageUrlSmall=/api/users/rykt-6e5x/profile_images/TINY v:roleName=editor v:displayName=Brian
```

## Top Records

```ls
| :updated_at | id | times    | sunday               | monday               | tuesday              | wednesday            | thursday             | friday               | saturday                   | 
| =========== | == | ======== | ==================== | ==================== | ==================== | ==================== | ==================== | ==================== | ========================== | 
| 1478101929  | 75 | 6:00 PM  | Seniors Today        | Parks                | Seniors Today        | One on One           | Seniors Today        | The Decision Makers  | Parks                      | 
| 1478101929  | 17 | 3:45 AM  |                      |                      |                      |                      |                      |                      |                            | 
| 1478101929  | 6  | 1:00 AM  | MTA                  | Somos Montgomery     | Seniors Today        | En Sintonia          | Mont. Al Dia         | Parks                | MTA                        | 
| 1478101929  | 71 | 5:00 PM  | Bottom Line          | Traffic              | Traffic              | Traffic              | Traffic              | Traffic              | CE PRC                     | 
| 1478101929  | 86 | 8:45 PM  | The Decision Makers  |                      |                      |                      |                      |                      |                            | 
| 1478101929  | 7  | 1:15 AM  |                      | En Sintonia          |                      | Somos Montgomery     |                      | DID YOU KNOW         |                            | 
| 1478101929  | 18 | 4:00 AM  | Community Connection | Community Connection | Community Connection | Community Connection | Community Connection | Community Connection | Community Connection       | 
| 1478101929  | 5  | 12:45 AM |                      | CRTW - Spanish       | Made In Montgomery   | CRTW - Spanish       |                      |                      | The Decision Makers        | 
| 1478101929  | 73 | 5:30 PM  | Made In Montgomery   | Traffic              | Traffic              | Traffic              | Traffic              | Traffic              | Legget Commencement Speech | 
| 1478101929  | 34 | 7:45 AM  | Traffic              | Traffic              | Traffic              | Traffic              | Traffic              | Traffic              | Traffic                    | 
```