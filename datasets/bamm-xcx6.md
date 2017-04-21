# Shellfish Harvesting Waters Sampling Stations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/shellfish-harvesting-waters-sampling-stations-b5c72) |
| Metadata | [Link](https://data.maryland.gov/api/views/bamm-xcx6) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/bamm-xcx6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/bamm-xcx6/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | bamm-xcx6 |
| Name | Shellfish Harvesting Waters Sampling Stations |
| Category | Energy and Environment |
| Tags | shellfish, sampling locations, mde |
| Created | 2014-06-03T17:49:51Z |
| Publication Date | 2014-06-03T17:57:27Z |

## Description

This dataset contains the station ID, station name, and location for the shellfish harvesting waters sampling program. Sample results are available in the Shellfish Harvesting Waters Sample Results dataset.

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| No       | time        | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag  | org_id           | Org ID           | text      | text        |
| Yes      | series tag  | station_id       | Station ID       | text      | text        |
| Yes      | series tag  | station_name     | Station Name     | text      | text        |
| Yes      | series tag  | primary_type     | Primary Type     | text      | text        |
| Yes      | series tag  | horizontal_datum | Horizontal Datum | text      | text        |
| Yes      | series tag  | state            | State            | text      | text        |
| Yes      | series tag  | county           | County           | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:bamm-xcx6 d:2014-06-03T10:49:56.000Z t:horizontal_datum=NAD83 t:org_id=MDEDAT07_WQX t:station_name="Broad Creek" t:county=TALBOT t:state=MARYLAND t:primary_type=Estuary t:station_id=807020 m:row_number.bamm-xcx6=1

series e:bamm-xcx6 d:2014-06-03T10:49:56.000Z t:horizontal_datum=NAD83 t:org_id=MDEDAT07_WQX t:station_name="Broad Creek" t:county=TALBOT t:state=MARYLAND t:primary_type=Estuary t:station_id=807026 m:row_number.bamm-xcx6=2

series e:bamm-xcx6 d:2014-06-03T10:49:56.000Z t:horizontal_datum=NAD83 t:org_id=MDEDAT07_WQX t:station_name="Tangier Sound" t:county=SOMERSET t:state=MARYLAND t:primary_type=Estuary t:station_id=1802207 m:row_number.bamm-xcx6=3
```

## Meta Commands

```ls
metric m:row_number.bamm-xcx6 p:long l:"Row Number"

entity e:bamm-xcx6 l:"Shellfish Harvesting Waters Sampling Stations" t:url=https://data.maryland.gov/api/views/bamm-xcx6

property e:bamm-xcx6 t:meta.view v:id=bamm-xcx6 v:category="Energy and Environment" v:averageRating=0 v:name="Shellfish Harvesting Waters Sampling Stations"

property e:bamm-xcx6 t:meta.view.license v:name="Public Domain"

property e:bamm-xcx6 t:meta.view.owner v:id=6wh5-kegk v:profileImageUrlMedium=/api/users/6wh5-kegk/profile_images/THUMB v:profileImageUrlLarge=/api/users/6wh5-kegk/profile_images/LARGE v:screenName="Andrew Gosden" v:profileImageUrlSmall=/api/users/6wh5-kegk/profile_images/TINY v:lastNotificationSeenAt=1491588421 v:displayName="Andrew Gosden"

property e:bamm-xcx6 t:meta.view.tableauthor v:id=6wh5-kegk v:profileImageUrlMedium=/api/users/6wh5-kegk/profile_images/THUMB v:profileImageUrlLarge=/api/users/6wh5-kegk/profile_images/LARGE v:screenName="Andrew Gosden" v:profileImageUrlSmall=/api/users/6wh5-kegk/profile_images/TINY v:roleName=editor v:lastNotificationSeenAt=1491588421 v:displayName="Andrew Gosden"
```

## Top Records

```ls
| :updated_at | org_id       | station_id | station_name   | primary_type | horizontal_datum | state    | county       | 
| =========== | ============ | ========== | ============== | ============ | ================ | ======== | ============ | 
| 1401792596  | MDEDAT07_WQX | 807020     | Broad Creek    | Estuary      | NAD83            | MARYLAND | TALBOT       | 
| 1401792596  | MDEDAT07_WQX | 807026     | Broad Creek    | Estuary      | NAD83            | MARYLAND | TALBOT       | 
| 1401792596  | MDEDAT07_WQX | 1802207    | Tangier Sound  | Estuary      | NAD83            | MARYLAND | SOMERSET     | 
| 1401792596  | MDEDAT07_WQX | 1803007    | Manokin River  | Estuary      | NAD83            | MARYLAND | SOMERSET     | 
| 1401792596  | MDEDAT07_WQX | 101012     | Patapsco River | Estuary      | NAD83            | MARYLAND | ANNE ARUNDEL | 
| 1401792596  | MDEDAT07_WQX | 905210     | Chesapeake Bay | Estuary      | NAD83            | MARYLAND | ST MARY'S    | 
| 1401792596  | MDEDAT07_WQX | 0302006B   | Chesapeake Bay | Estuary      | NAD83            | MARYLAND | ANNE ARUNDEL | 
| 1401792596  | MDEDAT07_WQX | 701203     | Chesapeake Bay | Estuary      | NAD83            | MARYLAND | CALVERT      | 
| 1401792596  | MDEDAT07_WQX | 501201     | Chesapeake Bay | Estuary      | NAD83            | MARYLAND | CALVERT      | 
| 1401792596  | MDEDAT07_WQX | 1104702    | St Marys River | Estuary      | NAD83            | MARYLAND | ST MARY'S    | 
```