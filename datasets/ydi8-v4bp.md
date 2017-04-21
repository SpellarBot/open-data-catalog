# Bonded Boat Registration Agents

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bonded-boat-registration-agents-1ffaf) |
| Metadata | [Link](https://data.oregon.gov/api/views/ydi8-v4bp) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/ydi8-v4bp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/ydi8-v4bp/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | ydi8-v4bp |
| Name | Bonded Boat Registration Agents |
| Attribution | Oregon State Marine Board |
| Category | Recreation |
| Tags | register, boat, agents, bonded, dealers, renew |
| Created | 2011-09-21T22:06:29Z |
| Publication Date | 2016-09-20T15:28:07Z |

## Description

The Marine Board has a partnership with many boat dealers and sporting good stores who provide exceptional customer service to boaters by serving as registration agents.

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | agentname   | AgentName  | text      | text        |
| Yes      | series tag  | telephone   | Telephone  | phone     | phone       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ydi8-v4bp d:2011-09-21T15:06:31.000Z t:phone_number=503-643-5018 t:agentname="Active Water Sports" m:row_number.ydi8-v4bp=1

series e:ydi8-v4bp d:2011-09-21T15:06:31.000Z t:phone_number=503-650-5991 t:agentname="Active Water Sports" m:row_number.ydi8-v4bp=2

series e:ydi8-v4bp d:2011-09-21T15:06:31.000Z t:phone_number=541-382-5009 t:agentname="All Seasons RV Center" m:row_number.ydi8-v4bp=3
```

## Meta Commands

```ls
metric m:row_number.ydi8-v4bp p:long l:"Row Number"

entity e:ydi8-v4bp l:"Bonded Boat Registration Agents" t:attribution="Oregon State Marine Board" t:url=https://data.oregon.gov/api/views/ydi8-v4bp

property e:ydi8-v4bp t:meta.view v:id=ydi8-v4bp v:category=Recreation v:attributionLink=http://www.boatoregon.com v:averageRating=0 v:name="Bonded Boat Registration Agents" v:attribution="Oregon State Marine Board"

property e:ydi8-v4bp t:meta.view.owner v:id=a2bu-8256 v:profileImageUrlMedium=/api/users/a2bu-8256/profile_images/THUMB v:profileImageUrlLarge=/api/users/a2bu-8256/profile_images/LARGE v:screenName="Ashley Massey" v:profileImageUrlSmall=/api/users/a2bu-8256/profile_images/TINY v:displayName="Ashley Massey"

property e:ydi8-v4bp t:meta.view.tableauthor v:id=a2bu-8256 v:profileImageUrlMedium=/api/users/a2bu-8256/profile_images/THUMB v:profileImageUrlLarge=/api/users/a2bu-8256/profile_images/LARGE v:screenName="Ashley Massey" v:profileImageUrlSmall=/api/users/a2bu-8256/profile_images/TINY v:roleName=editor v:displayName="Ashley Massey"
```

## Top Records

```ls
| :updated_at | agentname                 | telephone            | 
| =========== | ========================= | ==================== | 
| 1316617591  | Active Water Sports       | [503-643-5018, null] | 
| 1316617591  | Active Water Sports       | [503-650-5991, null] | 
| 1316617591  | All Seasons RV Center     | [541-382-5009, null] | 
| 1316617591  | Baker County Sheriff      | [541-523-6415, null] | 
| 1316617591  | Beaverton Honda Yamaha    | [503-684-6600, null] | 
| 1316617591  | Blackbird Shopping Center | [541-779-5435, null] | 
| 1316617591  | B&L Marine & RV Center    | [541-938-6560, null] | 
| 1316617591  | Boat Yard                 | [541-938-6634, null] | 
| 1316617591  | Canyonville Ace Hardware  | [541-839-4391, null] | 
| 1316617591  | Central Lakes Marine      | [541-385-7791, null] | 
```