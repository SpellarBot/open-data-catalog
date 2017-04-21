# Synchronized Traffic Signal Corridors

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/synchronized-traffic-signal-corridors) |
| Metadata | [Link](https://data.austintexas.gov/api/views/efct-8fs9) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/efct-8fs9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/efct-8fs9/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | efct-8fs9 |
| Name | Synchronized Traffic Signal Corridors |
| Attribution | City of Austin Transportation Department |
| Tags | transportation, transit, mobility, traffic signals, retiming |
| Created | 2016-09-16T15:48:46Z |
| Publication Date | 2017-03-09T22:28:28Z |

## Description

**This dataset is under active development and is subject to change at any time**

**Detailed Description Coming Soon**

This product is for informational purposes and may not have been prepared for or be suitable for legal, engineering, or surveying purposes. It does not represent an on-the-ground survey and represents only the approximate relative location of traffic signals.

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type | Render Type |
| ======== | =========== | ================== | ================== | ========= | =========== |
| No       | time        | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag  | atd_sync_signal_id | ATD Sync Signal ID | text      | number      |
| Yes      | series tag  | atd_signal_id      | atd_signal_id      | text      | number      |
| Yes      | series tag  | location_name      | Location Name      | text      | text        |
| Yes      | series tag  | system_id          | system_id          | text      | number      |
| Yes      | series tag  | system_name        | system_name        | text      | text        |
| Yes      | series tag  | limit              | limit              | text      | text        |
| Yes      | series tag  | isolated           | isolated           | text      | text        |
| No       |             | latitude           | latitude           | number    | number      |
| No       |             | longitude          | longitude          | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = latitude,longitude
```

## Data Commands

```ls
series e:efct-8fs9 d:2017-04-21T03:49:16.000Z t:limit=NO t:isolated=False t:location_name="LAMAR BLVD / 51ST ST" t:system_name="LAMAR - CENTRAL" t:system_id=45 t:atd_sync_signal_id=671 m:row_number.efct-8fs9=1

series e:efct-8fs9 d:2017-04-21T03:49:16.000Z t:limit=NO t:isolated=False t:location_name="DEAN KEETON ST / WICHITA ST" t:system_name="DEAN KEETON" t:system_id=28 t:atd_sync_signal_id=102 m:row_number.efct-8fs9=2

series e:efct-8fs9 d:2017-04-21T03:49:16.000Z t:limit=NO t:isolated=False t:location_name="DEAN KEETON ST / SAN JACINTO BLVD" t:system_name="DEAN KEETON" t:system_id=28 t:atd_sync_signal_id=101 m:row_number.efct-8fs9=3
```

## Meta Commands

```ls
metric m:row_number.efct-8fs9 p:long l:"Row Number"

entity e:efct-8fs9 l:"Synchronized Traffic Signal Corridors" t:attribution="City of Austin Transportation Department" t:url=https://data.austintexas.gov/api/views/efct-8fs9

property e:efct-8fs9 t:meta.view v:id=efct-8fs9 v:averageRating=0 v:name="Synchronized Traffic Signal Corridors" v:attribution="City of Austin Transportation Department"

property e:efct-8fs9 t:meta.view.license v:name="Public Domain"

property e:efct-8fs9 t:meta.view.owner v:id=8t3r-wq64 v:profileImageUrlMedium=/api/users/8t3r-wq64/profile_images/THUMB v:profileImageUrlLarge=/api/users/8t3r-wq64/profile_images/LARGE v:screenName="Austin Transportation" v:profileImageUrlSmall=/api/users/8t3r-wq64/profile_images/TINY v:displayName="Austin Transportation"

property e:efct-8fs9 t:meta.view.tableauthor v:id=8t3r-wq64 v:profileImageUrlMedium=/api/users/8t3r-wq64/profile_images/THUMB v:profileImageUrlLarge=/api/users/8t3r-wq64/profile_images/LARGE v:screenName="Austin Transportation" v:profileImageUrlSmall=/api/users/8t3r-wq64/profile_images/TINY v:roleName=editor_stories v:displayName="Austin Transportation"
```

## Top Records

```ls
| :updated_at | atd_sync_signal_id | atd_signal_id | location_name                     | system_id | system_name      | limit | isolated | latitude   | longitude   | 
| =========== | ================== | ============= | ================================= | ========= | ================ | ===== | ======== | ========== | =========== | 
| 1492746556  | 671                |               | LAMAR BLVD / 51ST ST              | 45        | LAMAR - CENTRAL  | NO    | False    | 30.3187695 | -97.7308197 | 
| 1492746556  | 102                |               | DEAN KEETON ST / WICHITA ST       | 28        | DEAN KEETON      | NO    | False    | 30.2895603 | -97.7379913 | 
| 1492746556  | 101                |               | DEAN KEETON ST / SAN JACINTO BLVD | 28        | DEAN KEETON      | NO    | False    | 30.2893162 | -97.7346115 | 
| 1492746556  | 107                |               | DEAN KEETON ST / SPEEDWAY         | 28        | DEAN KEETON      | NO    | False    | 30.2894573 | -97.7368088 | 
| 1492746556  | 108                |               | DUVAL ST / SAN JACINTO BLVD       | 28        | DEAN KEETON      | NO    | True     | 30.2909546 | -97.7347336 | 
| 1492746556  | 109                |               | 32ND ST / DUVAL ST                | 28        | DEAN KEETON      | NO    | True     | 30.2945347 | -97.7324677 | 
| 1492746557  | 177                |               | BRODIE LN / SLAUGHTER LN          | 122       | SLAUGHTER        | NO    | False    | 30.1835499 | -97.8497925 | 
| 1492746556  | 632                |               | LAMAR BLVD / NORTH LOOP BLVD      | 45        | LAMAR - CENTRAL  | NO    | False    | 30.3210888 | -97.729393  | 
| 1492746556  | 35                 |               | KOENIG LN / LAMAR BLVD            | 110       | KOENIG/NORTHLAND | NO    | False    | 30.325943  | -97.7263336 | 
| 1492746556  | 630                |               | KOENIG LN / LAMAR BLVD            | 45        | LAMAR - CENTRAL  | NO    | False    | 30.325943  | -97.7263336 | 
```