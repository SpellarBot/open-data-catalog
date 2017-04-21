# Sidewalk Weekly Construction Schedule

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sidewalk-weekly-construction-schedule-4ebc6) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/r528-jcks) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/r528-jcks/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/r528-jcks/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | r528-jcks |
| Name | Sidewalk Weekly Construction Schedule |
| Attribution | Department of Transportation (DOT) |
| Category | Transportation |
| Tags | dot, sidewalk, weekly construction schedule |
| Created | 2014-10-22T19:42:15Z |
| Publication Date | 2014-10-22T20:25:39Z |

## Description

Sidewalk schedule to install, maintain and repair sidewalks, curbs and pedestrian ramps.

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type | Render Type |
| ======== | =========== | =========== | =========== | ========= | =========== |
| No       | time        | :updated_at | updated_at  | meta_data | meta_data   |
| Yes      | series tag  | borough     | Borough     | text      | text        |
| No       |             | cb          | CB          | text      | text        |
| Yes      | series tag  | contract_no | Contract No | text      | text        |
| Yes      | series tag  | location    | Location    | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = cb
```

## Data Commands

```ls
series e:r528-jcks d:2014-10-22T12:42:19.000Z t:location="1-3 Family & 4+ Claim Locations" t:contract_no=HWS2014M t:borough=Manhattan m:row_number.r528-jcks=1

series e:r528-jcks d:2014-10-22T12:42:19.000Z t:location="1-3 Family & 4+ Claim Locations" t:contract_no=HWS2013X t:borough=Bronx m:row_number.r528-jcks=2

series e:r528-jcks d:2014-10-22T12:42:19.000Z t:location="1-3 Family & 4+ Claim Locations" t:contract_no=HWS2014K t:borough=Brooklyn m:row_number.r528-jcks=3
```

## Meta Commands

```ls
metric m:row_number.r528-jcks p:long l:"Row Number"

entity e:r528-jcks l:"Sidewalk Weekly Construction Schedule" t:attribution="Department of Transportation (DOT)" t:url=https://data.cityofnewyork.us/api/views/r528-jcks

property e:r528-jcks t:meta.view v:id=r528-jcks v:category=Transportation v:attributionLink=http://www.nyc.gov/html/dot/downloads/pdf/sidewalksch.pdf v:averageRating=0 v:name="Sidewalk Weekly Construction Schedule" v:attribution="Department of Transportation (DOT)"

property e:r528-jcks t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:r528-jcks t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | borough         | cb   | contract_no | location                                            | 
| =========== | =============== | ==== | =========== | =================================================== | 
| 1413981739  | Manhattan       | 2, 6 | HWS2014M    | 1-3 Family & 4+ Claim Locations                     | 
| 1413981739  | Bronx           | 9    | HWS2013X    | 1-3 Family & 4+ Claim Locations                     | 
| 1413981739  | Brooklyn        | 17   | HWS2014K    | 1-3 Family & 4+ Claim Locations                     | 
| 1413981739  | Queens          | 7    | HWS2013Q    | 1-3 Family & 4+ Claim Locations                     | 
| 1413981739  | Staten Island   | 2    | HWS2013R    | 1-3 Family properties                               | 
| 1413981739  | Citywide        | Q11  | HWS2013CW   | Expedited locations                                 | 
| 1413981739  | Citywide        | M3   | HWS2013CW   | NYCHA project - Seward Park Extension - 62 Essex St | 
| 1413981739  | Bus Pad         |      |             | No Contract                                         | 
| 1413981739  | Curb - Citywide |      |             | No Construction activity scheduled at this time     | 
```