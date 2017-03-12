# Transit communities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/transit-communities-fa210) |
| Metadata | [Link](https://data.seattle.gov/api/views/ndi9-2pye) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/ndi9-2pye/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/ndi9-2pye/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | ndi9-2pye |
| Name | Transit communities |
| Category | Transportation |
| Created | 2011-02-14T19:50:08Z |
| Publication Date | 2011-04-17T00:03:09Z |
| Rows Updated | 2011-08-21T02:48:35Z |

## Columns

```ls
| Included | Schema Type | Field Name              | Name                      | Data Type | Render Type |
| ======== | =========== | ======================= | ========================= | ========= | =========== |
| No       | time        | :updated_at             | updated_at                | meta_data | meta_data   |
| Yes      | series tag  | name                    | Name                      | text      | text        |
| Yes      | series tag  | typology                | Typology                  | text      | text        |
| Yes      | series tag  | current_conditions      | Current Conditions        | text      | text        |
| Yes      | series tag  | future_needs_priorities | Future Needs & Priorities | text      | text        |
| Yes      | series tag  | district                | District                  | text      | text        |
| Yes      | series tag  | neighborhood_plan       | Neighborhood Plan         | url       | url         |
| Yes      | series tag  | status_check            | Status Check              | url       | url         |
| Yes      | series tag  | city_planning           | City Planning             | url       | url         |
| Yes      | series tag  | major_transit_project   | Major Transit project?    | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:ndi9-2pye l:"Transit communities" t:url=https://data.seattle.gov/api/views/ndi9-2pye

property e:ndi9-2pye t:meta.view v:id=ndi9-2pye v:category=Transportation v:averageRating=0 v:name="Transit communities"

property e:ndi9-2pye t:meta.view.owner v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"

property e:ndi9-2pye t:meta.view.tableauthor v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```