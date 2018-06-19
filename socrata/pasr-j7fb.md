# Emergency Response Incidents

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/emergency-response-incidents-9cf52) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/pasr-j7fb) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/pasr-j7fb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/pasr-j7fb/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | pasr-j7fb |
| Name | Emergency Response Incidents |
| Attribution | Office of Emergency Management (OEM) |
| Category | Public Safety |
| Tags | emergency response incidents, oem |
| Created | 2014-03-05T21:56:00Z |
| Publication Date | 2016-06-24T22:07:33Z |

## Description

Type and address of emergency incident to which OEM responded

## Columns

```ls
| Included | Schema Type | Field Name    | Name          | Data Type     | Render Type   |
| ======== | =========== | ============= | ============= | ============= | ============= |
| Yes      | series tag  | incident_type | Incident Type | text          | text          |
| Yes      | series tag  | location      | Location      | text          | text          |
| Yes      | series tag  | borough       | Borough       | text          | text          |
| Yes      | time        | creation_date | Creation Date | calendar_date | calendar_date |
| No       |             | closed_date   | Closed Date   | calendar_date | calendar_date |
| No       |             | latitude      | Latitude      | number        | number        |
| No       |             | longitude     | Longitude     | number        | number        |
```

## Time Field

```ls
Value = creation_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = closed_date,latitude,longitude
```

## Data Commands

```ls
series e:pasr-j7fb d:2017-01-16T13:13:38.000Z t:incident_type="Utility-Water Main" t:location="136-17 72 Avenue" t:borough=Queens m:row_number.pasr-j7fb=1

series e:pasr-j7fb d:2016-10-29T12:13:31.000Z t:incident_type="Structural-Sidewalk Collapse" t:location="927 Broadway" t:borough=Manhattan m:row_number.pasr-j7fb=2

series e:pasr-j7fb d:2016-11-22T08:53:17.000Z t:incident_type=Utility-Other t:borough=Manhattan m:row_number.pasr-j7fb=3
```

## Meta Commands

```ls
metric m:row_number.pasr-j7fb p:long l:"Row Number"

entity e:pasr-j7fb l:"Emergency Response Incidents" t:attribution="Office of Emergency Management (OEM)" t:url=https://data.cityofnewyork.us/api/views/pasr-j7fb

property e:pasr-j7fb t:meta.view v:id=pasr-j7fb v:category="Public Safety" v:averageRating=0 v:name="Emergency Response Incidents" v:attribution="Office of Emergency Management (OEM)"

property e:pasr-j7fb t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:pasr-j7fb t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| incident_type                          | location                      | borough   | creation_date       | closed_date | latitude          | longitude          | 
| ====================================== | ============================= | ========= | =================== | =========== | ================= | ================== | 
| Utility-Water Main                     | 136-17 72 Avenue              | Queens    | 2017-01-16T13:13:38 |             | 40.71400364095638 | -73.82998933154158 | 
| Structural-Sidewalk Collapse           | 927 Broadway                  | Manhattan | 2016-10-29T12:13:31 |             | 40.71442154062271 | -74.00607638041981 | 
| Utility-Other                          |                               | Manhattan | 2016-11-22T08:53:17 |             |                   |                    | 
| Administration-Other                   | Seagirt Blvd & Beach 9 Street | Queens    | 2016-11-14T15:53:54 |             | 40.71400364095638 | -73.82998933154158 | 
| Law Enforcement-Other                  |                               | Brooklyn  | 2016-10-29T17:35:28 |             |                   |                    | 
| Utility-Water Main                     | 2-17 54 Avenue                | Queens    | 2016-12-02T16:40:13 |             | 40.71400364095638 | -73.82998933154158 | 
| Fire-2nd Alarm                         | 238 East 24 Street            | Manhattan | 2016-11-25T04:06:09 |             | 40.71442154062271 | -74.00607638041981 | 
| Utility-Water Main                     | 7th Avenue & West 27 Street   | Manhattan | 2016-12-03T04:17:30 |             | 40.71442154062271 | -74.00607638041981 | 
| Fire-10-76 (Commercial High Rise Fire) | 130 East 57 Street            | Manhattan | 2016-11-26T05:45:43 |             |                   |                    | 
| Structural-Crane                       |                               | Brooklyn  | 2016-11-18T13:12:51 |             |                   |                    | 
```