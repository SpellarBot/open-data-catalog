# Inmate Incidents - Slashing and Stabbing

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/inmate-incidents-slashing-and-stabbing) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/gakf-suji) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/gakf-suji/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/gakf-suji/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | gakf-suji |
| Name | Inmate Incidents - Slashing and Stabbing |
| Attribution | Department of Correction (DOC) |
| Category | Public Safety |
| Created | 2016-03-23T18:28:11Z |
| Publication Date | 2016-03-23T18:56:04Z |

## Description

Violent inmate-on-inmate incidents (Slashings and Stabbings).

## Columns

```ls
| Included | Schema Type | Field Name    | Name          | Data Type     | Render Type   |
| ======== | =========== | ============= | ============= | ============= | ============= |
| Yes      | series tag  | incident_id   | INCIDENT_ID   | text          | text          |
| Yes      | time        | reported_dt   | REPORTED_DT   | calendar_date | calendar_date |
| Yes      | series tag  | incident_type | INCIDENT_TYPE | text          | text          |
```

## Time Field

```ls
Value = reported_dt
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:gakf-suji d:2016-01-31T21:17:00.000Z t:incident_type=Slashing t:incident_id=76075 m:row_number.gakf-suji=1

series e:gakf-suji d:2016-02-02T09:43:00.000Z t:incident_type=Slashing t:incident_id=76130 m:row_number.gakf-suji=2

series e:gakf-suji d:2016-02-03T15:56:00.000Z t:incident_type=Slashing t:incident_id=76177 m:row_number.gakf-suji=3
```

## Meta Commands

```ls
metric m:row_number.gakf-suji p:long l:"Row Number"

entity e:gakf-suji l:"Inmate Incidents - Slashing and Stabbing" t:attribution="Department of Correction (DOC)" t:url=https://data.cityofnewyork.us/api/views/gakf-suji

property e:gakf-suji t:meta.view v:id=gakf-suji v:category="Public Safety" v:averageRating=0 v:name="Inmate Incidents - Slashing and Stabbing" v:attribution="Department of Correction (DOC)"

property e:gakf-suji t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:gakf-suji t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| incident_id | reported_dt         | incident_type | 
| =========== | =================== | ============= | 
| 76075       | 2016-01-31T21:17:00 | Slashing      | 
| 76130       | 2016-02-02T09:43:00 | Slashing      | 
| 76177       | 2016-02-03T15:56:00 | Slashing      | 
| 76348       | 2016-02-10T02:49:00 | Stabbing      | 
| 76488       | 2016-02-14T19:34:00 | Slashing      | 
| 76518       | 2016-02-15T19:39:00 | Slashing      | 
| 76527       | 2016-02-16T11:15:00 | Slashing      | 
| 76665       | 2016-02-20T19:48:00 | Slashing      | 
| 76714       | 2016-02-22T09:12:00 | Slashing      | 
| 76766       | 2016-02-24T11:20:00 | Slashing      | 
```