# Red Light Camera Locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/red-light-camera-locations-abc8b) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/thvf-6diy) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/thvf-6diy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/thvf-6diy/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | thvf-6diy |
| Name | Red Light Camera Locations |
| Attribution | City of Chicago |
| Category | Transportation |
| Tags | transportation, red light cameras, traffic |
| Created | 2014-08-11T18:48:44Z |
| Publication Date | 2016-11-29T23:13:34Z |

## Description

This dataset shows the location, first operational date, and approaches of the red light cameras in the City of Chicago. The approach describes the originating direction of travel which is monitored by a red light camera.

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type     | Render Type   |
| ======== | =========== | =============== | =============== | ============= | ============= |
| Yes      | series tag  | intersection    | INTERSECTION    | text          | text          |
| Yes      | series tag  | first_approach  | FIRST APPROACH  | text          | text          |
| Yes      | series tag  | second_approach | SECOND APPROACH | text          | text          |
| Yes      | series tag  | third_approach  | THIRD APPROACH  | text          | text          |
| Yes      | time        | go_live_date    | GO LIVE DATE    | calendar_date | calendar_date |
| No       |             | latitude        | LATITUDE        | number        | number        |
| No       |             | longitude       | LONGITUDE       | number        | number        |
```

## Time Field

```ls
Value = go_live_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = latitude,longitude
```

## Data Commands

```ls
series e:thvf-6diy d:2009-05-15T00:00:00.000Z t:intersection=Pulaski-Diversey t:first_approach=SB t:second_approach=NB m:row_number.thvf-6diy=1

series e:thvf-6diy d:2007-10-18T00:00:00.000Z t:intersection=Pulaski-Foster t:first_approach=SB t:second_approach=WB m:row_number.thvf-6diy=2

series e:thvf-6diy d:2006-02-25T00:00:00.000Z t:intersection=Cicero-Fullerton t:first_approach=SB t:second_approach=WB m:row_number.thvf-6diy=3
```

## Meta Commands

```ls
metric m:row_number.thvf-6diy p:long l:"Row Number"

entity e:thvf-6diy l:"Red Light Camera Locations" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/thvf-6diy

property e:thvf-6diy t:meta.view v:id=thvf-6diy v:category=Transportation v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Red Light Camera Locations" v:attribution="City of Chicago"

property e:thvf-6diy t:meta.view.owner v:id=3qqc-w7ag v:profileImageUrlMedium=/api/users/3qqc-w7ag/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qqc-w7ag/profile_images/LARGE v:screenName="Tom Schenk Jr" v:profileImageUrlSmall=/api/users/3qqc-w7ag/profile_images/TINY v:lastNotificationSeenAt=1491330280 v:displayName="Tom Schenk Jr"

property e:thvf-6diy t:meta.view.tableauthor v:id=3qqc-w7ag v:profileImageUrlMedium=/api/users/3qqc-w7ag/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qqc-w7ag/profile_images/LARGE v:screenName="Tom Schenk Jr" v:profileImageUrlSmall=/api/users/3qqc-w7ag/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491330280 v:displayName="Tom Schenk Jr"
```

## Top Records

```ls
| intersection           | first_approach | second_approach | third_approach | go_live_date        | latitude  | longitude  | 
| ====================== | ============== | =============== | ============== | =================== | ========= | ========== | 
| Pulaski-Diversey       | SB             | NB              |                | 2009-05-15T00:00:00 | 41.931791 | -87.726979 | 
| Pulaski-Foster         | SB             | WB              |                | 2007-10-18T00:00:00 | 41.975532 | -87.728234 | 
| Cicero-Fullerton       | SB             | WB              |                | 2006-02-25T00:00:00 | 41.924237 | -87.746302 | 
| Pulaski-Peterson       | SB             | EB              |                | 2008-10-30T00:00:00 | 41.990136 | -87.72864  | 
| Harlem-Belmont         | NB             | WB              |                | 2007-06-18T00:00:00 | 41.937997 | -87.806746 | 
| Narragansett-Fullerton | EB             | WB              |                | 2008-11-14T00:00:00 | 41.923676 | -87.785441 | 
| Western-Montrose       | NB             | WB              |                | 2008-08-26T00:00:00 | 41.961313 | -87.688681 | 
| Halsted-Madison        | NB             | SB              |                | 2008-06-14T00:00:00 | 41.881776 | -87.647361 | 
| State-75th             | NB             | WB              |                | 2009-08-28T00:00:00 | 41.75818  | -87.624757 | 
| Western-79th           | NB             | WB              |                | 2007-05-07T00:00:00 | 41.750101 | -87.682847 | 
```