# Red Light Camera Violations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/red-light-camera-violations-0cd67) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/spqx-js37) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/spqx-js37/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/spqx-js37/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | spqx-js37 |
| Name | Red Light Camera Violations |
| Attribution | City of Chicago |
| Category | Transportation |
| Tags | citations, violations, transportation, public safety |
| Created | 2014-08-08T00:09:40Z |
| Publication Date | 2016-11-29T23:16:25Z |

## Description

This dataset reflects the daily volume of violations created by the City of Chicago Red Light Program for each camera. The data reflects violations that occurred from July 1, 2014 until present, minus the most recent 14 days. This data may change due to occasional time lags between the capturing of a potential violation and the processing and determination of a violation. The most recent 14 days are not shown due to revised data being submitted to the City of Chicago during this period. The reported violations are those that have been collected by the camera system and reviewed by two separate City contractors. In some instances, due to the inability the registered owner of the offending vehicle, the violation may not be issued as a citation. However, this dataset contains all violations regardless of whether a citation was actually issued, which provides an accurate view into the Red Light Program.  Because of occasional time lags between the capturing of a potential violation and the processing and determination of a violation, as well as the occasional revision of the determination of a violation, this data may change. More information on the Red Light Program can be found here: http://www.cityofchicago.org/city/en/depts/cdot/supp_info/red-light_cameraenforcement.html.  The corresponding dataset for speed camera violations is https://data.cityofchicago.org/id/hhkd-xvj4.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type     | Render Type   |
| ======== | ============== | ============== | ============== | ============= | ============= |
| Yes      | series tag     | intersection   | INTERSECTION   | text          | text          |
| Yes      | series tag     | camera_id      | CAMERA ID      | text          | text          |
| No       |                | address        | ADDRESS        | text          | text          |
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
series e:spqx-js37 d:2014-08-02T00:00:00.000Z t:intersection="31ST ST AND MARTIN LUTHER KING DRIVE" t:camera_id=2121 m:violations=16

series e:spqx-js37 d:2014-07-15T00:00:00.000Z t:intersection="MADISON AND CENTRAL" t:camera_id=1751 m:violations=5

series e:spqx-js37 d:2014-07-27T00:00:00.000Z t:intersection="HOMAN/KIMBALL AND NORTH" t:camera_id=1771 m:violations=1
```

## Meta Commands

```ls
metric m:violations p:integer l:VIOLATIONS d:"Number of violations for each camera on a particular day." t:dataTypeName=number

entity e:spqx-js37 l:"Red Light Camera Violations" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/spqx-js37

property e:spqx-js37 t:meta.view v:id=spqx-js37 v:category=Transportation v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Red Light Camera Violations" v:attribution="City of Chicago"

property e:spqx-js37 t:meta.view.owner v:id=3qqc-w7ag v:profileImageUrlMedium=/api/users/3qqc-w7ag/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qqc-w7ag/profile_images/LARGE v:screenName="Tom Schenk Jr" v:profileImageUrlSmall=/api/users/3qqc-w7ag/profile_images/TINY v:lastNotificationSeenAt=1491330280 v:displayName="Tom Schenk Jr"

property e:spqx-js37 t:meta.view.tableauthor v:id=3qqc-w7ag v:profileImageUrlMedium=/api/users/3qqc-w7ag/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qqc-w7ag/profile_images/LARGE v:screenName="Tom Schenk Jr" v:profileImageUrlSmall=/api/users/3qqc-w7ag/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491330280 v:displayName="Tom Schenk Jr"
```

## Top Records

```ls
| intersection                         | camera_id | address                 | violation_date      | violations | x_coordinate | y_coordinate | latitude | longitude | 
| ==================================== | ========= | ======================= | =================== | ========== | ============ | ============ | ======== | ========= | 
| 31ST ST AND MARTIN LUTHER KING DRIVE | 2121      | 3100 S DR MARTIN L KING | 2014-08-02T00:00:00 | 16         |              |              |          |           | 
| MADISON AND CENTRAL                  | 1751      | 0 S CENTRAL AVENUE      | 2014-07-15T00:00:00 | 5          |              |              |          |           | 
| HOMAN/KIMBALL AND NORTH              | 1771      | 1600 N HOMAN AVENUE     | 2014-07-27T00:00:00 | 1          |              |              |          |           | 
| IRVING PARK AND LARAMIE              | 1533      | 5200 W IRVING PARK ROA  | 2014-08-07T00:00:00 | 6          |              |              |          |           | 
| ASHLAND AND MADISON                  | 1911      | 0 N ASHLAND AVE         | 2014-07-23T00:00:00 | 1          |              |              |          |           | 
| IRVING PARK AND KILPATRICK           | 2763      | 4700 W IRVING PARK ROA  | 2014-07-11T00:00:00 | 8          |              |              |          |           | 
| ASHLAND AND DIVERSEY                 | 1623      | 1600 W DIVERSEY PARKWA  | 2014-07-04T00:00:00 | 3          |              |              |          |           | 
| ELSTON AND IRVING PARK               | 1503      | 3700 W IRVING PARK ROA  | 2014-07-26T00:00:00 | 5          |              |              |          |           | 
| IRVING PARK AND LARAMIE              | 1533      | 5200 W IRVING PARK ROA  | 2014-08-01T00:00:00 | 2          |              |              |          |           | 
| 31ST AND CALIFORNIA                  | 2064      | 2800 W 31ST             | 2014-07-13T00:00:00 | 1          |              |              |          |           | 
```