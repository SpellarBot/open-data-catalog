# For Hire Vehicles (FHV) - Active Drivers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/for-hire-vehicles-fhv-active-drivers) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/xjfq-wh2d) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/xjfq-wh2d/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/xjfq-wh2d/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | xjfq-wh2d |
| Name | For Hire Vehicles (FHV) - Active Drivers |
| Attribution | Taxi and Limousine Commission (TLC) |
| Category | Transportation |
| Tags | fhv, for hire, for-hire, for-hire-vehicles, drivers, taxi, active |
| Created | 2015-07-16T17:24:02Z |
| Publication Date | 2017-04-20T18:56:20Z |

## Description

NYC TLC Licensed FHV drivers that are currently active and in good standing. This list is accurate to the date and time represented in the Last Date Updated and Last Time Updated fields. For inquiries about the contents of this dataset, please email licensinginquiries@tlc.nyc.gov.

## Columns

```ls
| Included | Schema Type | Field Name                    | Name                          | Data Type     | Render Type   |
| ======== | =========== | ============================= | ============================= | ============= | ============= |
| Yes      | series tag  | license_number                | License Number                | text          | number        |
| Yes      | series tag  | name                          | Name                          | text          | text          |
| Yes      | series tag  | type                          | Type                          | text          | text          |
| Yes      | time        | expiration_date               | Expiration Date               | calendar_date | calendar_date |
| Yes      | series tag  | wheelchair_accessible_trained | Wheelchair Accessible Trained | text          | text          |
| No       |             | last_date_updated             | Last Date Updated             | calendar_date | calendar_date |
| Yes      | series tag  | last_time_updated             | Last Time Updated             | text          | text          |
```

## Time Field

```ls
Value = expiration_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = last_date_updated
```

## Data Commands

```ls
series e:xjfq-wh2d d:2019-04-29T00:00:00.000Z t:last_time_updated=13:25 t:license_number=871831 t:name=RAMCHAL,HARRICHAN t:type="FOR HIRE VEHICLE DRIVER" t:wheelchair_accessible_trained=WAV m:row_number.xjfq-wh2d=1

series e:xjfq-wh2d d:2017-05-12T00:00:00.000Z t:last_time_updated=13:25 t:license_number=898432 t:name=COLON,BENITO t:type="FOR HIRE VEHICLE DRIVER" t:wheelchair_accessible_trained=WAV m:row_number.xjfq-wh2d=2

series e:xjfq-wh2d d:2017-05-12T00:00:00.000Z t:last_time_updated=13:25 t:license_number=5363807 t:name=AHMED,SARFRAZ t:type="FOR HIRE VEHICLE DRIVER" t:wheelchair_accessible_trained=WAV m:row_number.xjfq-wh2d=3
```

## Meta Commands

```ls
metric m:row_number.xjfq-wh2d p:long l:"Row Number"

entity e:xjfq-wh2d l:"For Hire Vehicles (FHV) - Active Drivers" t:attribution="Taxi and Limousine Commission (TLC)" t:url=https://data.cityofnewyork.us/api/views/xjfq-wh2d

property e:xjfq-wh2d t:meta.view v:id=xjfq-wh2d v:category=Transportation v:averageRating=0 v:name="For Hire Vehicles (FHV) - Active Drivers" v:attribution="Taxi and Limousine Commission (TLC)"

property e:xjfq-wh2d t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:xjfq-wh2d t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| license_number | name                  | type                    | expiration_date     | wheelchair_accessible_trained | last_date_updated   | last_time_updated | 
| ============== | ===================== | ======================= | =================== | ============================= | =================== | ================= | 
| 871831         | RAMCHAL,HARRICHAN     | FOR HIRE VEHICLE DRIVER | 2019-04-29T00:00:00 | WAV                           | 2017-04-19T00:00:00 | 13:25             | 
| 898432         | COLON,BENITO          | FOR HIRE VEHICLE DRIVER | 2017-05-12T00:00:00 | WAV                           | 2017-04-19T00:00:00 | 13:25             | 
| 5363807        | AHMED,SARFRAZ         | FOR HIRE VEHICLE DRIVER | 2017-05-12T00:00:00 | WAV                           | 2017-04-19T00:00:00 | 13:25             | 
| 5606934        | MEDELLIN,ORTEGA,P     | FOR HIRE VEHICLE DRIVER | 2017-06-06T00:00:00 | WAV                           | 2017-04-19T00:00:00 | 13:25             | 
| 5607423        | KUMAR,SANDEEP         | FOR HIRE VEHICLE DRIVER | 2017-06-06T00:00:00 | WAV                           | 2017-04-19T00:00:00 | 13:25             | 
| 5608540        | APARICIO-MENDEZ,JORGE | FOR HIRE VEHICLE DRIVER | 2017-06-11T00:00:00 | WAV                           | 2017-04-19T00:00:00 | 13:25             | 
| 5609078        | CORALES,JIMMY         | FOR HIRE VEHICLE DRIVER | 2017-06-06T00:00:00 | WAV                           | 2017-04-19T00:00:00 | 13:25             | 
| 5609495        | BRINEZ-MENDZ,MARIA,A  | FOR HIRE VEHICLE DRIVER | 2017-06-09T00:00:00 | WAV                           | 2017-04-19T00:00:00 | 13:25             | 
| 5611016        | MANIFOLD,DARRYL,E     | FOR HIRE VEHICLE DRIVER | 2017-05-28T00:00:00 | WAV                           | 2017-04-19T00:00:00 | 13:25             | 
| 5612805        | ROBLESAPARICIO,M      | FOR HIRE VEHICLE DRIVER | 2017-06-03T00:00:00 | WAV                           | 2017-04-19T00:00:00 | 13:25             | 
```