# Test Calendar

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/test-calendar) |
| Metadata | [Link](https://data.oregon.gov/api/views/ckyn-bwp9) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/ckyn-bwp9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/ckyn-bwp9/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | ckyn-bwp9 |
| Name | Test Calendar |
| Category | Administrative |
| Created | 2016-10-24T20:30:01Z |
| Publication Date | 2016-10-24T20:59:57Z |

## Description

Dataset for testing with calendar view

## Columns

```ls
| Included | Schema Type | Field Name    | Name            | Data Type     | Render Type   |
| ======== | =========== | ============= | =============== | ============= | ============= |
| Yes      | series tag  | event         | Event           | text          | text          |
| Yes      | time        | date_time     | Start Date/time | calendar_date | calendar_date |
| No       |             | end_date_time | End Date/Time   | calendar_date | calendar_date |
```

## Time Field

```ls
Value = date_time
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = end_date_time
```

## Data Commands

```ls
series e:ckyn-bwp9 d:2016-11-02T14:00:00.000Z t:event="Event 1" m:row_number.ckyn-bwp9=1

series e:ckyn-bwp9 d:2016-11-10T13:00:00.000Z t:event="Event 2" m:row_number.ckyn-bwp9=2

series e:ckyn-bwp9 d:2016-11-12T11:00:00.000Z t:event="Event 3" m:row_number.ckyn-bwp9=3
```

## Meta Commands

```ls
metric m:row_number.ckyn-bwp9 p:long l:"Row Number"

entity e:ckyn-bwp9 l:"Test Calendar" t:url=https://data.oregon.gov/api/views/ckyn-bwp9

property e:ckyn-bwp9 t:meta.view v:id=ckyn-bwp9 v:category=Administrative v:averageRating=0 v:name="Test Calendar"

property e:ckyn-bwp9 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:ckyn-bwp9 t:meta.view.owner v:id=vp2b-ad29 v:profileImageUrlMedium=/api/users/vp2b-ad29/profile_images/THUMB v:profileImageUrlLarge=/api/users/vp2b-ad29/profile_images/LARGE v:screenName="Shawn Amsberry" v:profileImageUrlSmall=/api/users/vp2b-ad29/profile_images/TINY v:lastNotificationSeenAt=1492723089 v:displayName="Shawn Amsberry"

property e:ckyn-bwp9 t:meta.view.tableauthor v:id=vp2b-ad29 v:profileImageUrlMedium=/api/users/vp2b-ad29/profile_images/THUMB v:profileImageUrlLarge=/api/users/vp2b-ad29/profile_images/LARGE v:screenName="Shawn Amsberry" v:profileImageUrlSmall=/api/users/vp2b-ad29/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492723089 v:displayName="Shawn Amsberry"
```

## Top Records

```ls
| event   | date_time           | end_date_time       | 
| ======= | =================== | =================== | 
| Event 1 | 2016-11-02T14:00:00 | 2016-11-02T15:00:00 | 
| Event 2 | 2016-11-10T13:00:00 | 2016-11-10T14:00:00 | 
| Event 3 | 2016-11-12T11:00:00 | 2016-11-12T12:00:00 | 
| Event 4 | 2016-11-18T13:00:00 | 2016-11-18T14:00:00 | 
```