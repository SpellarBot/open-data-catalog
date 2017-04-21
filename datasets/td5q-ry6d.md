# Medallion Drivers ? Passenger Assistance Trained

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/medallion-drivers-passenger-assistance-trained-0a5a8) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/td5q-ry6d) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/td5q-ry6d/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/td5q-ry6d/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | td5q-ry6d |
| Name | Medallion Drivers ? Passenger Assistance Trained |
| Attribution | Taxi and Limousine Commission (TLC) |
| Category | Transportation |
| Tags | taxi, taxicab, tlc, limousine, taxi driver, medallion, taxi license, driver |
| Created | 2013-03-01T19:21:48Z |
| Publication Date | 2017-04-21T01:54:50Z |

## Description

This list contains information on the status of current medallion drivers who had completed Passenger Assistance Training. This list is accurate to the date and time represented in the Last Date Updated and Last Time Updated fields.

## Columns

```ls
| Included | Schema Type | Field Name              | Name                    | Data Type     | Render Type   |
| ======== | =========== | ======================= | ======================= | ============= | ============= |
| Yes      | series tag  | license_number          | License Number          | text          | text          |
| Yes      | series tag  | name                    | Name                    | text          | text          |
| Yes      | series tag  | type                    | Type                    | text          | text          |
| Yes      | time        | expiration_date         | Expiration Date         | calendar_date | calendar_date |
| Yes      | series tag  | completed_both_training | Completed Both Training | text          | text          |
| No       |             | last_updated_date       | Last Date Updated       | calendar_date | calendar_date |
| No       |             | last_updated_time       | Last Time Updated       | text          | text          |
```

## Time Field

```ls
Value = expiration_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = last_updated_date,last_updated_time
```

## Data Commands

```ls
series e:td5q-ry6d d:2016-11-07T00:00:00.000Z t:completed_both_training=YES t:license_number=466364 t:name=GROSSMAN,VLADIMIR t:type="MEDALLION TAXI DRIVER" m:row_number.td5q-ry6d=1

series e:td5q-ry6d d:2017-11-07T00:00:00.000Z t:completed_both_training=YES t:license_number=466513 t:name=MIAH,MOHAMMAD,J t:type="MEDALLION TAXI DRIVER" m:row_number.td5q-ry6d=2

series e:td5q-ry6d d:2017-11-05T00:00:00.000Z t:completed_both_training=YES t:license_number=466717 t:name=UDDIN,NAZIR t:type="MEDALLION TAXI DRIVER" m:row_number.td5q-ry6d=3
```

## Meta Commands

```ls
metric m:row_number.td5q-ry6d p:long l:"Row Number"

entity e:td5q-ry6d l:"Medallion Drivers ? Passenger Assistance Trained" t:attribution="Taxi and Limousine Commission (TLC)" t:url=https://data.cityofnewyork.us/api/views/td5q-ry6d

property e:td5q-ry6d t:meta.view v:id=td5q-ry6d v:category=Transportation v:averageRating=0 v:name="Medallion Drivers ? Passenger Assistance Trained" v:attribution="Taxi and Limousine Commission (TLC)"

property e:td5q-ry6d t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:td5q-ry6d t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| license_number | name              | type                  | expiration_date     | completed_both_training | last_updated_date   | last_updated_time | 
| ============== | ================= | ===================== | =================== | ======================= | =================== | ================= | 
| 466364         | GROSSMAN,VLADIMIR | MEDALLION TAXI DRIVER | 2016-11-07T00:00:00 | YES                     | 2016-08-24T00:00:00 | 13:20             | 
| 466513         | MIAH,MOHAMMAD,J   | MEDALLION TAXI DRIVER | 2017-11-07T00:00:00 | YES                     | 2016-08-24T00:00:00 | 13:20             | 
| 466717         | UDDIN,NAZIR       | MEDALLION TAXI DRIVER | 2017-11-05T00:00:00 | YES                     | 2016-08-24T00:00:00 | 13:20             | 
| 466875         | TIRFE,MELAKE,K    | MEDALLION TAXI DRIVER | 2017-12-28T00:00:00 | YES                     | 2016-08-24T00:00:00 | 13:20             | 
| 466877         | CISSE,MAMADOU     | MEDALLION TAXI DRIVER | 2017-12-29T00:00:00 | YES                     | 2016-08-24T00:00:00 | 13:20             | 
| 466903         | KUMAR,TARUN       | MEDALLION TAXI DRIVER | 2017-12-30T00:00:00 | YES                     | 2016-08-24T00:00:00 | 13:20             | 
| 466914         | TURNER,DONELL,JR  | MEDALLION TAXI DRIVER | 2016-12-11T00:00:00 | YES                     | 2016-08-24T00:00:00 | 13:20             | 
| 466997         | SOTO,RAFAEL       | MEDALLION TAXI DRIVER | 2017-12-08T00:00:00 | YES                     | 2016-08-24T00:00:00 | 13:20             | 
| 472501         | MADAN,DARSHAN,0   | MEDALLION TAXI DRIVER | 2017-12-29T00:00:00 | YES                     | 2016-08-24T00:00:00 | 13:20             | 
| 854057         | LINDOR,MANASSE    | MEDALLION TAXI DRIVER | 2017-10-28T00:00:00 | YES                     | 2016-08-24T00:00:00 | 13:20             | 
```