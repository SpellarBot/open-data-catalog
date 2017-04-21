# Inmate Discharges

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/inmate-discharges) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/94ri-3ium) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/94ri-3ium/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/94ri-3ium/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 94ri-3ium |
| Name | Inmate Discharges |
| Attribution | Department of Correction (DOC) |
| Category | Public Safety |
| Created | 2016-03-23T18:28:40Z |
| Publication Date | 2017-04-01T19:35:47Z |

## Description

Inmate discharges with attributes (race, gender, legal status, top charge). This data set excludes Sealed Cases. Resulting summaries may differ slightly from other published statistics.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type     | Render Type   |
| ======== | ============== | ================== | ================== | ============= | ============= |
| Yes      | series tag     | inmateid           | INMATEID           | text          | number        |
| Yes      | time           | admitted_dt        | ADMITTED_DT        | calendar_date | calendar_date |
| No       |                | discharged_dt      | DISCHARGED_DT      | calendar_date | calendar_date |
| Yes      | series tag     | race               | RACE               | text          | text          |
| Yes      | series tag     | gender             | GENDER             | text          | text          |
| Yes      | numeric metric | age                | AGE                | number        | number        |
| Yes      | series tag     | inmate_status_code | INMATE_STATUS_CODE | text          | text          |
| Yes      | series tag     | top_charge         | TOP_CHARGE         | text          | text          |
```

## Time Field

```ls
Value = admitted_dt
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = discharged_dt
```

## Data Commands

```ls
series e:94ri-3ium d:2016-02-04T11:05:35.000Z t:top_charge=165.15 t:gender=M t:inmate_status_code=DE t:inmateid=987 t:race=BLACK m:age=50

series e:94ri-3ium d:2016-02-04T16:30:06.000Z t:top_charge=220.03 t:gender=M t:inmate_status_code=CS t:inmateid=997 t:race=BLACK m:age=39

series e:94ri-3ium d:2016-02-12T18:45:43.000Z t:top_charge=CO t:gender=M t:inmate_status_code=SCO t:inmateid=1285 t:race=BLACK m:age=36
```

## Meta Commands

```ls
metric m:age p:integer l:AGE d:"Calculated Age of the inmate." t:dataTypeName=number

entity e:94ri-3ium l:"Inmate Discharges" t:attribution="Department of Correction (DOC)" t:url=https://data.cityofnewyork.us/api/views/94ri-3ium

property e:94ri-3ium t:meta.view v:id=94ri-3ium v:category="Public Safety" v:averageRating=0 v:name="Inmate Discharges" v:attribution="Department of Correction (DOC)"

property e:94ri-3ium t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:94ri-3ium t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| inmateid | admitted_dt         | discharged_dt       | race    | gender | age | inmate_status_code | top_charge | 
| ======== | =================== | =================== | ======= | ====== | === | ================== | ========== | 
| 987      | 2016-02-04T11:05:35 | 2016-02-17T19:02:01 | BLACK   | M      | 50  | DE                 | 165.15     | 
| 997      | 2016-02-04T16:30:06 | 2016-03-11T05:16:01 | BLACK   | M      | 39  | CS                 | 220.03     | 
| 1285     | 2016-02-12T18:45:43 | 2016-03-09T00:14:05 | BLACK   | M      | 36  | SCO                | CO         | 
| 2574     | 2016-02-28T12:00:00 | 2016-03-04T04:18:02 | UNKNOWN | M      | 45  | CS                 | 155.25     | 
| 2900     | 2016-02-19T10:45:00 | 2016-03-04T04:40:01 | BLACK   | M      | 48  | SSR                | 265.03     | 
| 3485     | 2016-02-03T18:34:00 | 2016-03-03T06:36:00 | BLACK   | M      | 51  | CS                 | 120.15     | 
| 3518     | 2016-02-12T20:23:00 | 2016-02-13T06:01:01 | UNKNOWN | M      | 39  | CS                 | 140.35     | 
| 3518     | 2016-02-13T06:01:33 | 2016-02-18T11:50:00 | UNKNOWN | M      | 39  | CS                 | CCW        | 
| 3819     | 2016-02-27T13:06:33 | 2016-03-03T02:59:03 | UNKNOWN | M      | 34  | CS                 | 220.03     | 
| 4030     | 2016-02-07T11:53:07 | 2016-02-11T04:50:04 | UNKNOWN | M      | 43  | CS                 | 220.03     | 
```