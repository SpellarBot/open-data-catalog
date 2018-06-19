# Iowa Veterans Home - Room Conversion Project

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/iowa-veterans-home-room-conversion-project) |
| Metadata | [Link](https://data.iowa.gov/api/views/tspp-t8gv) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/tspp-t8gv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/tspp-t8gv/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | tspp-t8gv |
| Name | Iowa Veterans Home - Room Conversion Project |
| Attribution | Iowa Vaterans Home |
| Category | Government |
| Tags | room, conversion, private |
| Created | 2015-07-17T11:58:26Z |
| Publication Date | 2015-07-17T12:08:09Z |

## Description

Shows the percentage increases of Private rooms at IVH over time.

## Columns

```ls
| Included | Schema Type    | Field Name                                             | Name                                                     | Data Type | Render Type |
| ======== | ============== | ====================================================== | ======================================================== | ========= | =========== |
| No       | time           | :updated_at                                            | updated_at                                               | meta_data | meta_data   |
| Yes      | series tag     | iowa_veterans_home_conversion_to_private_rooms_project | Iowa Veterans Home - Conversion to Private Rooms Project | text      | text        |
| Yes      | numeric metric | of_private_rooms_added                                 | % of Private Rooms Added                                 | percent   | percent     |
| Yes      | numeric metric | cummulative_of_private_rooms                           | Cummulative % of Private Rooms                           | percent   | percent     |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:tspp-t8gv d:2015-07-17T04:58:35.000Z t:iowa_veterans_home_conversion_to_private_rooms_project=Initial m:cummulative_of_private_rooms=9.9 m:of_private_rooms_added=0

series e:tspp-t8gv d:2015-07-17T04:58:35.000Z t:iowa_veterans_home_conversion_to_private_rooms_project=Mar-2012 m:cummulative_of_private_rooms=29.11 m:of_private_rooms_added=19.2

series e:tspp-t8gv d:2015-07-17T04:58:35.000Z t:iowa_veterans_home_conversion_to_private_rooms_project=May-2012 m:cummulative_of_private_rooms=42.57 m:of_private_rooms_added=13.5
```

## Meta Commands

```ls
metric m:of_private_rooms_added p:float l:"% of Private Rooms Added" t:dataTypeName=percent

metric m:cummulative_of_private_rooms p:float l:"Cummulative % of Private Rooms" t:dataTypeName=percent

entity e:tspp-t8gv l:"Iowa Veterans Home - Room Conversion Project" t:attribution="Iowa Vaterans Home" t:url=https://data.iowa.gov/api/views/tspp-t8gv

property e:tspp-t8gv t:meta.view v:id=tspp-t8gv v:category=Government v:averageRating=0 v:name="Iowa Veterans Home - Room Conversion Project" v:attribution="Iowa Vaterans Home"

property e:tspp-t8gv t:meta.view.license v:name="Public Domain"

property e:tspp-t8gv t:meta.view.owner v:id=ew8u-gyn7 v:screenName=LComstock v:displayName=LComstock

property e:tspp-t8gv t:meta.view.tableauthor v:id=wji9-p6ra v:profileImageUrlMedium=/api/users/wji9-p6ra/profile_images/THUMB v:profileImageUrlLarge=/api/users/wji9-p6ra/profile_images/LARGE v:screenName="Iowa Veterans Home" v:profileImageUrlSmall=/api/users/wji9-p6ra/profile_images/TINY v:displayName="Iowa Veterans Home"
```

## Top Records

```ls
| :updated_at | iowa_veterans_home_conversion_to_private_rooms_project | of_private_rooms_added | cummulative_of_private_rooms | 
| =========== | ====================================================== | ====================== | ============================ | 
| 1437109115  | Initial                                                | 0.00                   | 9.90                         | 
| 1437109115  | Mar-2012                                               | 19.20                  | 29.11                        | 
| 1437109115  | May-2012                                               | 13.50                  | 42.57                        | 
| 1437109115  | May-2014                                               | 14.40                  | 58.64                        | 
| 1437109115  | Jun-2015                                               | 15.50                  | 76.17                        | 
| 1437109115  | Current                                                | 0.00                   | 76.17                        | 
```