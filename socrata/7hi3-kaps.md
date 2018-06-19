# Staff Injuries - Class A Injuries

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/staff-injuries-class-a-injuries) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/7hi3-kaps) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/7hi3-kaps/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/7hi3-kaps/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 7hi3-kaps |
| Name | Staff Injuries - Class A Injuries |
| Attribution | Department of Correction (DOC) |
| Category | Public Safety |
| Created | 2016-03-23T18:29:32Z |
| Publication Date | 2016-03-23T18:45:29Z |

## Description

Serious injury to staff as a result of inmate assault on staff (uniform staff only).

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
series e:7hi3-kaps d:2016-01-06T18:55:00.000Z t:incident_type="Use of Force" t:reason="Assault on Staff" t:incident_id=75250 m:row_number.7hi3-kaps=1

series e:7hi3-kaps d:2016-01-31T14:10:00.000Z t:incident_type="Use of Force" t:reason="Assault on Staff" t:incident_id=76064 m:row_number.7hi3-kaps=2

series e:7hi3-kaps d:2016-02-01T09:03:00.000Z t:incident_type="Use of Force" t:reason="Assault on Staff" t:incident_id=76092 m:row_number.7hi3-kaps=3
```

## Meta Commands

```ls
metric m:row_number.7hi3-kaps p:long l:"Row Number"

entity e:7hi3-kaps l:"Staff Injuries - Class A Injuries" t:attribution="Department of Correction (DOC)" t:url=https://data.cityofnewyork.us/api/views/7hi3-kaps

property e:7hi3-kaps t:meta.view v:id=7hi3-kaps v:category="Public Safety" v:averageRating=0 v:name="Staff Injuries - Class A Injuries" v:attribution="Department of Correction (DOC)"

property e:7hi3-kaps t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:7hi3-kaps t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| incident_id | reported_dt         | incident_type | reason           | 
| =========== | =================== | ============= | ================ | 
| 75250       | 2016-01-06T18:55:00 | Use of Force  | Assault on Staff | 
| 76064       | 2016-01-31T14:10:00 | Use of Force  | Assault on Staff | 
| 76092       | 2016-02-01T09:03:00 | Use of Force  | Assault on Staff | 
| 76567       | 2016-02-17T14:41:00 | Use of Force  | Assault on Staff | 
| 79909       | 2016-06-03T11:16:00 | Use of Force  | Assault on Staff | 
| 80035       | 2016-06-07T12:23:00 | Use of Force  | Assault on Staff | 
| 80256       | 2016-06-13T20:00:00 | Use of Force  | Assault on Staff | 
| 80658       | 2016-06-24T20:02:00 | Use of Force  | Assault on Staff | 
| 81400       | 2016-07-20T07:31:00 | Use of Force  | Assault on Staff | 
| 81558       | 2016-07-24T14:55:00 | Use of Force  | Assault on Staff | 
```