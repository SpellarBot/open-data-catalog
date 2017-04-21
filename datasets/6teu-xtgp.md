# Inmate Admissions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/inmate-admissions) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/6teu-xtgp) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/6teu-xtgp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/6teu-xtgp/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 6teu-xtgp |
| Name | Inmate Admissions |
| Attribution | Department of Correction (DOC) |
| Category | Public Safety |
| Created | 2016-03-23T18:28:55Z |
| Publication Date | 2017-04-01T19:35:27Z |

## Description

Inmate admissions with attributes (race, gender, legal status, top charge). This data set excludes Sealed Cases. Resulting summaries may differ slightly from other published statistics.

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type     | Render Type   |
| ======== | =========== | ================== | ================== | ============= | ============= |
| Yes      | series tag  | inmateid           | INMATEID           | text          | number        |
| Yes      | time        | admitted_dt        | ADMITTED_DT        | calendar_date | calendar_date |
| No       |             | discharged_dt      | DISCHARGED_DT      | calendar_date | calendar_date |
| Yes      | series tag  | race               | RACE               | text          | text          |
| Yes      | series tag  | gender             | GENDER             | text          | text          |
| Yes      | series tag  | inmate_status_code | INMATE_STATUS_CODE | text          | text          |
| Yes      | series tag  | top_charge         | TOP_CHARGE         | text          | text          |
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
series e:6teu-xtgp d:2016-02-09T18:46:04.000Z t:top_charge=CO t:gender=M t:inmate_status_code=DE t:inmateid=475 t:race=BLACK m:row_number.6teu-xtgp=1

series e:6teu-xtgp d:2016-02-01T00:36:00.000Z t:top_charge=265.01 t:gender=M t:inmate_status_code=CS t:inmateid=1207 t:race=BLACK m:row_number.6teu-xtgp=2

series e:6teu-xtgp d:2016-02-24T15:55:45.000Z t:top_charge=105.15 t:gender=M t:inmate_status_code=DE t:inmateid=1415 t:race=UNKNOWN m:row_number.6teu-xtgp=3
```

## Meta Commands

```ls
metric m:row_number.6teu-xtgp p:long l:"Row Number"

entity e:6teu-xtgp l:"Inmate Admissions" t:attribution="Department of Correction (DOC)" t:url=https://data.cityofnewyork.us/api/views/6teu-xtgp

property e:6teu-xtgp t:meta.view v:id=6teu-xtgp v:category="Public Safety" v:averageRating=0 v:name="Inmate Admissions" v:attribution="Department of Correction (DOC)"

property e:6teu-xtgp t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:6teu-xtgp t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| inmateid | admitted_dt         | discharged_dt | race    | gender | inmate_status_code | top_charge | 
| ======== | =================== | ============= | ======= | ====== | ================== | ========== | 
| 475      | 2016-02-09T18:46:04 |               | BLACK   | M      | DE                 | CO         | 
| 1207     | 2016-02-01T00:36:00 |               | BLACK   | M      | CS                 | 265.01     | 
| 1415     | 2016-02-24T15:55:45 |               | UNKNOWN | M      | DE                 | 105.15     | 
| 1561     | 2016-02-03T23:52:00 |               | BLACK   | M      | DE                 | 140.25     | 
| 1900     | 2016-02-22T22:13:19 |               | BLACK   | M      | CS                 | 215.50     | 
| 2455     | 2016-02-26T13:09:06 |               | BLACK   | M      | DE                 | 220.03     | 
| 2830     | 2016-02-19T13:07:49 |               | BLACK   | F      | DE                 | 220.39     | 
| 3334     | 2016-02-18T16:05:00 |               | BLACK   | M      | DE                 | 160.15     | 
| 3369     | 2016-02-09T21:15:39 |               | BLACK   | F      | DE                 | 120.00     | 
| 3827     | 2016-02-18T02:52:53 |               | BLACK   | M      | DE                 | 110-140.25 | 
```