# "Electric Motor Only" Waterways in Oregon

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/electric-motor-only-waterways-in-oregon-28ba9) |
| Metadata | [Link](https://data.oregon.gov/api/views/vkd9-qi8f) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/vkd9-qi8f/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/vkd9-qi8f/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | vkd9-qi8f |
| Name | "Electric Motor Only" Waterways in Oregon |
| Attribution | Oregon State Marine Board |
| Category | Recreation |
| Tags | electric motor only waterways, motor boat restrictions, watercraft, kicker motors, under 10 horse power, small electric motors, open boats, boats under 16 feet, puddle jumpers |
| Created | 2011-11-08T15:52:00Z |
| Publication Date | 2013-05-07T21:26:32Z |

## Description

Some waterbodies in Oregon have been designated "electric motor only" by Oregon Administrative Rule or statute.  These waterbodies have been designated based on their topography, size and traditional boating uses.

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type | Render Type |
| ======== | =========== | ================== | ================== | ========= | =========== |
| No       | time        | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag  | waterbody          | Waterbody          | text      | text        |
| Yes      | series tag  | county             | County             | text      | text        |
| Yes      | series tag  | waterway_segment   | Restrictions       | flag      | flag        |
| Yes      | series tag  | restricted_segment | Restricted Segment | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:vkd9-qi8f d:2011-11-08T08:04:37.000Z t:county=Deschutes t:waterbody="Meadow Lake" m:row_number.vkd9-qi8f=1

series e:vkd9-qi8f d:2011-11-08T08:05:15.000Z t:county=Coos t:waterbody="New River" m:row_number.vkd9-qi8f=2

series e:vkd9-qi8f d:2011-11-08T08:04:53.000Z t:county=Marion t:waterbody="Mission Lake" m:row_number.vkd9-qi8f=3
```

## Meta Commands

```ls
metric m:row_number.vkd9-qi8f p:long l:"Row Number"

entity e:vkd9-qi8f l:"""Electric Motor Only"" Waterways in Oregon" t:attribution="Oregon State Marine Board" t:url=https://data.oregon.gov/api/views/vkd9-qi8f

property e:vkd9-qi8f t:meta.view v:id=vkd9-qi8f v:category=Recreation v:attributionLink=http://www.boatoregon.com v:averageRating=0 v:name="""Electric Motor Only"" Waterways in Oregon" v:attribution="Oregon State Marine Board"

property e:vkd9-qi8f t:meta.view.owner v:id=a2bu-8256 v:profileImageUrlMedium=/api/users/a2bu-8256/profile_images/THUMB v:profileImageUrlLarge=/api/users/a2bu-8256/profile_images/LARGE v:screenName="Ashley Massey" v:profileImageUrlSmall=/api/users/a2bu-8256/profile_images/TINY v:displayName="Ashley Massey"

property e:vkd9-qi8f t:meta.view.tableauthor v:id=a2bu-8256 v:profileImageUrlMedium=/api/users/a2bu-8256/profile_images/THUMB v:profileImageUrlLarge=/api/users/a2bu-8256/profile_images/LARGE v:screenName="Ashley Massey" v:profileImageUrlSmall=/api/users/a2bu-8256/profile_images/TINY v:roleName=editor v:displayName="Ashley Massey"
```

## Top Records

```ls
| :updated_at | waterbody                  | county    | waterway_segment | restricted_segment | 
| =========== | ========================== | ========= | ================ | ================== | 
| 1320739477  | Meadow Lake                | Deschutes |                  |                    | 
| 1320739515  | New River                  | Coos      |                  |                    | 
| 1320739493  | Mission Lake               | Marion    |                  |                    | 
| 1320739501  | Mud Lake                   | Lake      |                  |                    | 
| 1320739577  | Smith Lake                 | Multnomah |                  |                    | 
| 1320739624  | Walton Lake                | Crook     |                  |                    | 
| 1320739524  | Old Long Tom River Channel | Lane      |                  |                    | 
| 1320739533  | Ollala Lake                | Lincoln   |                  |                    | 
| 1320739614  | Walter Wirth Lake          | Marion    |                  |                    | 
| 1320739549  | Rock Creek Reservoir       | Wasco     |                  |                    | 
```