# Veterans & Human Services Levy Calendar

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/veterans-human-services-levy-calendar) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/n9da-svsr) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/n9da-svsr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/n9da-svsr/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | n9da-svsr |
| Name | Veterans & Human Services Levy Calendar |
| Category | Government |
| Tags | vhsl, veterans, human services, dchs |
| Created | 2016-06-21T15:50:54Z |
| Publication Date | 2017-04-11T16:55:47Z |

## Description

Events calendar for the Veterans and Human Services Levy.

## Columns

```ls
| Included | Schema Type | Field Name        | Name              | Data Type | Render Type |
| ======== | =========== | ================= | ================= | ========= | =========== |
| Yes      | time        | start_time        | Start time        | date      | date        |
| No       |             | end_time          | End time          | date      | date        |
| Yes      | series tag  | event_name        | Event name        | text      | text        |
| Yes      | series tag  | event_description | Event description | text      | text        |
| Yes      | series tag  | location_name     | Location name     | text      | text        |
| Yes      | series tag  | url               | URL               | url       | url         |
```

## Time Field

```ls
Value = start_time
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = end_time
```

## Data Commands

```ls
series e:n9da-svsr d:2017-09-21T17:15:00.000Z t:location_name="King County Chinook Building, Room 124" t:event_description="Regular board meeting. Join by phone: 206-263-8114, Conference ID: 2689139." t:event_name="Veterans Citizen Oversight Board" m:row_number.n9da-svsr=1

series e:n9da-svsr d:2017-06-22T17:15:00.000Z t:location_name="King County Chinook Building, Room 428" t:event_description="Regular board meeting. Join by phone: 206-263-8114, Conference ID: 2689139." t:event_name="Joint Regional Human Services Citizen Oversight Board and Veterans Citizen Oversight Board" m:row_number.n9da-svsr=2

series e:n9da-svsr d:2017-07-27T17:15:00.000Z t:location_name="King County Chinook Building, Room 428" t:event_description="Regular board meeting. Join by phone: 206-263-8114, Conference ID: 2689139." t:event_name="Joint Regional Human Services Citizen Oversight Board and Veterans Citizen Oversight Board" m:row_number.n9da-svsr=3
```

## Meta Commands

```ls
metric m:row_number.n9da-svsr p:long l:"Row Number"

entity e:n9da-svsr l:"Veterans & Human Services Levy Calendar" t:url=https://data.kingcounty.gov/api/views/n9da-svsr

property e:n9da-svsr t:meta.view v:id=n9da-svsr v:category=Government v:averageRating=0 v:name="Veterans & Human Services Levy Calendar"

property e:n9da-svsr t:meta.view.owner v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:displayName="King County Webteam"

property e:n9da-svsr t:meta.view.tableauthor v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:roleName=administrator v:displayName="King County Webteam"
```

## Top Records

```ls
| start_time | end_time   | event_name                                                                                 | event_description                                                           | location_name                          | url          | 
| ========== | ========== | ========================================================================================== | =========================================================================== | ====================================== | ============ | 
| 1506014100 | 1506021300 | Veterans Citizen Oversight Board                                                           | Regular board meeting. Join by phone: 206-263-8114, Conference ID: 2689139. | King County Chinook Building, Room 124 | [null, null] | 
| 1498151700 | 1498158900 | Joint Regional Human Services Citizen Oversight Board and Veterans Citizen Oversight Board | Regular board meeting. Join by phone: 206-263-8114, Conference ID: 2689139. | King County Chinook Building, Room 428 | [null, null] | 
| 1501175700 | 1501182900 | Joint Regional Human Services Citizen Oversight Board and Veterans Citizen Oversight Board | Regular board meeting. Join by phone: 206-263-8114, Conference ID: 2689139. | King County Chinook Building, Room 428 | [null, null] | 
| 1502990100 | 1502997300 | Veterans Citizen Oversight Board                                                           | Regular board meeting. Join by phone: 206-263-8114, Conference ID: 2689139. | King County Chinook Building, Room 124 | [null, null] | 
| 1503508500 | 1503515700 | Regional Human Services Citizen Oversight Board                                            | Regular board meeting. Join by phone: 206-263-8114, Conference ID: 2689139. | King County Chinook Building, Room 124 | [null, null] | 
| 1506532500 | 1506539700 | Regional Human Services Citizen Oversight Board                                            | Regular board meeting. Join by phone: 206-263-8114, Conference ID: 2689139. | King County Chinook Building, Room 124 | [null, null] | 
| 1509038100 | 1509045300 | Joint Regional Human Services Citizen Oversight Board and Veterans Citizen Oversight Board | Regular board meeting. Join by phone: 206-263-8114, Conference ID: 2689139. | King County Chinook Building, Room 428 | [null, null] | 
| 1510856100 | 1510863300 | Joint Regional Human Services Citizen Oversight Board and Veterans Citizen Oversight Board | Regular board meeting. Join by phone: 206-263-8114, Conference ID: 2689139. | King County Chinook Building, Room 428 | [null, null] | 
| 1512670500 | 1481141700 | Joint Regional Human Services Citizen Oversight Board and Veterans Citizen Oversight Board | Regular board meeting. Join by phone: 206-263-8114, Conference ID: 2689139. | King County Chinook Building, Room 428 | [null, null] | 
| 1493313300 | 1493320500 | Joint Regional Human Services Citizen Oversight Board and Veterans Citizen Oversight Board | Regular board meeting. Join by phone: 206-263-8114, Conference ID: 2689139. | King County Chinook Building, Room 428 | [null, null] | 
```