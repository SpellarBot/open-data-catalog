# Speed Camera Violations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/speed-camera-violations-997eb) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/hhkd-xvj4) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/hhkd-xvj4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/hhkd-xvj4/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | hhkd-xvj4 |
| Name | Speed Camera Violations |
| Attribution | City of Chicago |
| Category | Transportation |
| Tags | traffic, public safety, transportation |
| Created | 2014-08-08T00:33:28Z |
| Publication Date | 2016-11-29T23:16:44Z |

## Description

This dataset reflects the daily volume of violations that have occurred in Children's Safety Zones for each camera. The data reflects violations that occurred from July 1, 2014 until present, minus the most recent 14 days. This data may change due to occasional time lags between the capturing of a potential violation and the processing and determination of a violation. The most recent 14 days are not shown due to revised data being submitted to the City of Chicago. The reported violations are those that have been collected by the camera and radar system and reviewed by two separate City contractors. In some instances, due to the inability the registered owner of the offending vehicle, the violation may not be issued as a citation. However, this dataset contains all violations regardless of whether a citation was issued, which provides an accurate view into the Automated Speed Enforcement Program violations taking place in Children's Safety Zones. More information on the Safety Zone Program can be found here: http://www.cityofchicago.org/city/en/depts/cdot/supp_info/children_s_safetyzoneporgramautomaticspeedenforcement.html. The corresponding dataset for red light camera violations is https://data.cityofchicago.org/id/spqx-js37.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type     | Render Type   |
| ======== | ============== | ============== | ============== | ============= | ============= |
| No       |                | address        | ADDRESS        | text          | text          |
| Yes      | series tag     | camera_id      | CAMERA ID      | text          | text          |
| Yes      | time           | violation_date | VIOLATION DATE | calendar_date | calendar_date |
| Yes      | numeric metric | violations     | VIOLATIONS     | number        | number        |
| No       |                | x_coordinate   | X COORDINATE   | number        | number        |
| No       |                | y_coordinate   | Y COORDINATE   | number        | number        |
| No       |                | latitude       | LATITUDE       | number        | number        |
| No       |                | longitude      | LONGITUDE      | number        | number        |
```

## Time Field

```ls
Value = violation_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address,x_coordinate,y_coordinate,latitude,longitude
```

## Data Commands

```ls
series e:hhkd-xvj4 d:2014-07-08T00:00:00.000Z t:camera_id=CHI065 m:violations=65

series e:hhkd-xvj4 d:2014-07-16T00:00:00.000Z t:camera_id=CHI010 m:violations=56

series e:hhkd-xvj4 d:2014-07-08T00:00:00.000Z t:camera_id=CHI069 m:violations=10
```

## Meta Commands

```ls
metric m:violations p:integer l:VIOLATIONS d:"Number of violations for each camera on a particular day." t:dataTypeName=number

entity e:hhkd-xvj4 l:"Speed Camera Violations" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/hhkd-xvj4

property e:hhkd-xvj4 t:meta.view v:id=hhkd-xvj4 v:category=Transportation v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Speed Camera Violations" v:attribution="City of Chicago"

property e:hhkd-xvj4 t:meta.view.owner v:id=3qqc-w7ag v:profileImageUrlMedium=/api/users/3qqc-w7ag/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qqc-w7ag/profile_images/LARGE v:screenName="Tom Schenk Jr" v:profileImageUrlSmall=/api/users/3qqc-w7ag/profile_images/TINY v:lastNotificationSeenAt=1491330280 v:displayName="Tom Schenk Jr"

property e:hhkd-xvj4 t:meta.view.tableauthor v:id=3qqc-w7ag v:profileImageUrlMedium=/api/users/3qqc-w7ag/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qqc-w7ag/profile_images/LARGE v:screenName="Tom Schenk Jr" v:profileImageUrlSmall=/api/users/3qqc-w7ag/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491330280 v:displayName="Tom Schenk Jr"
```

## Top Records

```ls
| address         | camera_id | violation_date      | violations | x_coordinate | y_coordinate | latitude | longitude | 
| =============== | ========= | =================== | ========== | ============ | ============ | ======== | ========= | 
| 7738 S WESTERN  | CHI065    | 2014-07-08T00:00:00 | 65         |              |              |          |           | 
| 1111 N HUMBOLDT | CHI010    | 2014-07-16T00:00:00 | 56         |              |              |          |           | 
| 5520 S WESTERN  | CHI069    | 2014-07-08T00:00:00 | 10         |              |              |          |           | 
| 1111 N HUMBOLDT | CHI010    | 2014-07-26T00:00:00 | 101        |              |              |          |           | 
| 1111 N HUMBOLDT | CHI010    | 2014-07-27T00:00:00 | 92         |              |              |          |           | 
| 5529 S WESTERN  | CHI068    | 2014-08-03T00:00:00 | 20         |              |              |          |           | 
| 1111 N HUMBOLDT | CHI010    | 2014-07-30T00:00:00 | 66         |              |              |          |           | 
| 5520 S WESTERN  | CHI069    | 2014-07-28T00:00:00 | 18         |              |              |          |           | 
| 5520 S WESTERN  | CHI069    | 2014-07-16T00:00:00 | 17         |              |              |          |           | 
| 5520 S WESTERN  | CHI069    | 2014-07-24T00:00:00 | 11         |              |              |          |           | 
```