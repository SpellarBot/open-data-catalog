# Inmate Assault on Staff

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/inmate-assault-on-staff) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/erra-pzy8) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/erra-pzy8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/erra-pzy8/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | erra-pzy8 |
| Name | Inmate Assault on Staff |
| Attribution | Department of Correction (DOC) |
| Category | Public Safety |
| Created | 2016-03-23T18:29:41Z |
| Publication Date | 2016-03-23T18:44:05Z |

## Description

Inmate assaults on staff (uniform staff only; incidents resulting in UOF only).

## Columns

```ls
| Included | Schema Type | Field Name    | Name          | Data Type     | Render Type   |
| ======== | =========== | ============= | ============= | ============= | ============= |
| Yes      | series tag  | incident_id   | INCIDENT_ID   | text          | text          |
| Yes      | time        | reported_dt   | REPORTED_DT   | calendar_date | calendar_date |
| Yes      | series tag  | incident_type | INCIDENT_TYPE | text          | text          |
| Yes      | series tag  | reason        | REASON        | text          | text          |
```

## Time Field

```ls
Value = reported_dt
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:erra-pzy8 d:2016-01-06T18:55:00.000Z t:incident_type="Use of Force" t:reason="Assault on Staff" t:incident_id=75250 m:row_number.erra-pzy8=1

series e:erra-pzy8 d:2016-01-08T11:09:00.000Z t:incident_type="Use of Force" t:reason="Assault on Staff" t:incident_id=75326 m:row_number.erra-pzy8=2

series e:erra-pzy8 d:2016-01-14T08:45:00.000Z t:incident_type="Use of Force" t:reason="Assault on Staff" t:incident_id=75523 m:row_number.erra-pzy8=3
```

## Meta Commands

```ls
metric m:row_number.erra-pzy8 p:long l:"Row Number"

entity e:erra-pzy8 l:"Inmate Assault on Staff" t:attribution="Department of Correction (DOC)" t:url=https://data.cityofnewyork.us/api/views/erra-pzy8

property e:erra-pzy8 t:meta.view v:id=erra-pzy8 v:category="Public Safety" v:averageRating=0 v:name="Inmate Assault on Staff" v:attribution="Department of Correction (DOC)"

property e:erra-pzy8 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:erra-pzy8 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| incident_id | reported_dt         | incident_type | reason           | 
| =========== | =================== | ============= | ================ | 
| 75250       | 2016-01-06T18:55:00 | Use of Force  | Assault on Staff | 
| 75326       | 2016-01-08T11:09:00 | Use of Force  | Assault on Staff | 
| 75523       | 2016-01-14T08:45:00 | Use of Force  | Assault on Staff | 
| 75545       | 2016-01-15T13:08:00 | Use of Force  | Assault on Staff | 
| 75861       | 2016-01-25T13:53:00 | Use of Force  | Assault on Staff | 
| 75939       | 2016-01-27T14:06:00 | Use of Force  | Assault on Staff | 
| 76064       | 2016-01-31T14:10:00 | Use of Force  | Assault on Staff | 
| 76077       | 2016-01-31T21:17:00 | Use of Force  | Assault on Staff | 
| 76079       | 2016-01-31T19:14:00 | Use of Force  | Assault on Staff | 
| 76092       | 2016-02-01T09:03:00 | Use of Force  | Assault on Staff | 
```