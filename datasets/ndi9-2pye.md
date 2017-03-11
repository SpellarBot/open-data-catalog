# Transit communities

## Dataset

* [Dataset URL](https://data.seattle.gov/api/views/ndi9-2pye/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/transit-communities-fa210)
* Id = ndi9-2pye
* Name = Transit communities
* Category = Transportation
* Created = 2011-02-14T19:50:08Z
* Publication Date = 2011-04-17T00:03:09Z
* Rows Updated = 2011-08-21T02:48:35Z

## Description



## Columns

```ls
| Name                      | Field Name              | Data Type | Render Type | Schema Type | Included | 
| ========================= | ======================= | ========= | =========== | =========== | ======== | 
| updated_at                | :updated_at             | meta_data | meta_data   | time        | Yes      | 
| Name                      | name                    | text      | text        | series tag  | Yes      | 
| Typology                  | typology                | text      | text        | series tag  | Yes      | 
| Current Conditions        | current_conditions      | text      | text        | series tag  | Yes      | 
| Future Needs & Priorities | future_needs_priorities | text      | text        | series tag  | Yes      | 
| District                  | district                | text      | text        | series tag  | Yes      | 
| Neighborhood Plan         | neighborhood_plan       | url       | url         | series tag  | Yes      | 
| Status Check              | status_check            | url       | url         | series tag  | Yes      | 
| City Planning             | city_planning           | url       | url         | series tag  | Yes      | 
| Major Transit project?    | major_transit_project   | url       | url         | series tag  | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls





```

## Meta Commands

```ls
entity e:ndi9-2pye l:"Transit communities" t:url=https://data.seattle.gov/api/views/ndi9-2pye

property e:ndi9-2pye t:meta.view d:2017-03-03T14:23:04.758Z v:id=ndi9-2pye v:category=Transportation v:averageRating=0 v:name="Transit communities"

property e:ndi9-2pye t:meta.view.owner d:2017-03-03T14:23:04.758Z v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"

property e:ndi9-2pye t:meta.view.tableauthor d:2017-03-03T14:23:04.758Z v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```