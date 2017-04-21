# Traffic Cameras

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/traffic-cameras-1f299) |
| Metadata | [Link](https://data.austintexas.gov/api/views/b4k4-adkb) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/b4k4-adkb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/b4k4-adkb/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | b4k4-adkb |
| Name | Traffic Cameras |
| Attribution | City of Austin Transportation Department |
| Tags | transportation, traffic, cameras, mobility |
| Created | 2016-12-08T19:22:17Z |
| Publication Date | 2016-12-20T19:22:38Z |

## Description

**This dataset is under active development and is subject to change at any time**

This dataset contains information about traffic cameras in Austin, TX. Traffic cameras are owned and operated by the City of Austin Transportation Department and are used to monitor traffic conditions across the city. For information about Austin's Advanced Transportation Management System, visit the department website, here:
http://www.austintexas.gov/department/arterial-management

This product is for informational purposes and may not have been prepared for or be suitable for legal, engineering, or surveying purposes. It does not represent an on-the-ground survey and represents only the approximate relative location of traffic signals.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type     | Render Type   |
| ======== | ============== | ===================== | ===================== | ============= | ============= |
| Yes      | series tag     | atd_camera_id         | ATD_CAMERA_ID         | text          | text          |
| Yes      | series tag     | camera_mfg            | CAMERA_MFG            | text          | text          |
| Yes      | time           | turn_on_date          | TURN_ON_DATE          | calendar_date | calendar_date |
| Yes      | series tag     | atd_location_id       | ATD_LOCATION_ID       | text          | text          |
| Yes      | series tag     | primary_st_segment_id | PRIMARY_ST_SEGMENT_ID | text          | number        |
| Yes      | series tag     | cross_st_segment_id   | CROSS_ST_SEGMENT_ID   | text          | number        |
| Yes      | series tag     | landmark              | LANDMARK              | text          | text          |
| Yes      | series tag     | signal_eng_area       | SIGNAL_ENG_AREA       | text          | text          |
| Yes      | series tag     | council_district      | COUNCIL_DISTRICT      | text          | number        |
| Yes      | series tag     | jurisdiction          | JURISDICTION          | text          | text          |
| Yes      | series tag     | location_type         | LOCATION_TYPE         | text          | text          |
| Yes      | series tag     | location_name         | LOCATION_NAME         | text          | text          |
| Yes      | series tag     | primary_st            | PRIMARY_ST            | text          | text          |
| Yes      | series tag     | cross_st              | CROSS_ST              | text          | text          |
| No       |                | modified_date         | MODIFIED_DATE         | calendar_date | calendar_date |
| Yes      | numeric metric | primary_st_block      | PRIMARY_ST_BLOCK      | number        | number        |
| Yes      | series tag     | coa_intersection_id   | COA_INTERSECTION_ID   | text          | number        |
| Yes      | series tag     | camera_status         | CAMERA_STATUS         | text          | text          |
| Yes      | series tag     | county                | COUNTY                | text          | text          |
| Yes      | series tag     | cross_st_aka          | CROSS_ST_AKA          | text          | text          |
| Yes      | numeric metric | cross_st_block        | CROSS_ST_BLOCK        | number        | number        |
| Yes      | series tag     | primary_st_aka        | PRIMARY_ST_AKA        | text          | text          |
| No       |                | latitude              | LATITUDE              | number        | number        |
| No       |                | longitude             | LONGITUDE             | number        | number        |
```

## Time Field

```ls
Value = turn_on_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = modified_date,latitude,longitude
```

## Data Commands

```ls
series e:b4k4-adkb d:2016-11-15T18:00:00.000Z t:cross_st="51ST ST" t:coa_intersection_id=5160367 t:location_name="AIRPORT BLVD / 51ST ST" t:primary_st="AIRPORT BLVD" t:camera_mfg="Spectra Enhanced" t:cross_st_segment_id=2015777 t:primary_st_segment_id=2015762 t:council_district=9 t:atd_camera_id=25 t:camera_status=TURNED_ON t:atd_location_id=LOC16-000845 m:primary_st_block=5100 m:cross_st_block=806

series e:b4k4-adkb d:2017-04-17T04:55:08.000Z t:cross_st="32ND ST" t:coa_intersection_id=5159577 t:location_name="35 SVRD / 32ND ST" t:primary_st="IH 35 SVRD" t:camera_mfg=Sarix t:cross_st_segment_id=3367455 t:primary_st_segment_id=2017269 t:council_district=9 t:atd_camera_id=287 t:camera_status=TURNED_ON t:atd_location_id=LOC16-004800 m:primary_st_block=3109 m:cross_st_block=1034

series e:b4k4-adkb d:2017-04-17T04:55:08.000Z t:cross_st="32ND ST" t:coa_intersection_id=5159577 t:location_name="35 SVRD / 32ND ST" t:primary_st="IH 35 SVRD" t:camera_mfg=Axis t:cross_st_segment_id=3367455 t:primary_st_segment_id=2017269 t:council_district=9 t:atd_camera_id=286 t:camera_status=TURNED_ON t:atd_location_id=LOC16-004800 m:primary_st_block=3109 m:cross_st_block=1034
```

## Meta Commands

```ls
metric m:primary_st_block p:integer l:PRIMARY_ST_BLOCK t:dataTypeName=number

metric m:cross_st_block p:integer l:CROSS_ST_BLOCK t:dataTypeName=number

entity e:b4k4-adkb l:"Traffic Cameras" t:attribution="City of Austin Transportation Department" t:url=https://data.austintexas.gov/api/views/b4k4-adkb

property e:b4k4-adkb t:meta.view v:id=b4k4-adkb v:attributionLink=http://www.austintexas.gov/department/arterial-management v:averageRating=0 v:name="Traffic Cameras" v:attribution="City of Austin Transportation Department"

property e:b4k4-adkb t:meta.view.license v:name="Public Domain"

property e:b4k4-adkb t:meta.view.owner v:id=8t3r-wq64 v:profileImageUrlMedium=/api/users/8t3r-wq64/profile_images/THUMB v:profileImageUrlLarge=/api/users/8t3r-wq64/profile_images/LARGE v:screenName="Austin Transportation" v:profileImageUrlSmall=/api/users/8t3r-wq64/profile_images/TINY v:displayName="Austin Transportation"

property e:b4k4-adkb t:meta.view.tableauthor v:id=8t3r-wq64 v:profileImageUrlMedium=/api/users/8t3r-wq64/profile_images/THUMB v:profileImageUrlLarge=/api/users/8t3r-wq64/profile_images/LARGE v:screenName="Austin Transportation" v:profileImageUrlSmall=/api/users/8t3r-wq64/profile_images/TINY v:roleName=editor_stories v:displayName="Austin Transportation"
```

## Top Records

```ls
| atd_camera_id | camera_mfg       | turn_on_date        | atd_location_id | primary_st_segment_id | cross_st_segment_id | landmark    | signal_eng_area | council_district | jurisdiction | location_type | location_name                        | primary_st     | cross_st         | modified_date | primary_st_block | coa_intersection_id | camera_status | county | cross_st_aka | cross_st_block | primary_st_aka | latitude   | longitude   | 
| ============= | ================ | =================== | =============== | ===================== | =================== | =========== | =============== | ================ | ============ | ============= | ==================================== | ============== | ================ | ============= | ================ | =================== | ============= | ====== | ============ | ============== | ============== | ========== | =========== | 
| 25            | Spectra Enhanced | 2016-11-15T18:00:00 | LOC16-000845    | 2015762               | 2015777             |             |                 | 9                |              |               | AIRPORT BLVD / 51ST ST               | AIRPORT BLVD   | 51ST ST          |               | 5100             | 5160367             | TURNED_ON     |        |              | 806            |                | 30.3120689 | -97.7153397 | 
| 287           | Sarix            |                     | LOC16-004800    | 2017269               | 3367455             |             |                 | 9                |              |               | 35 SVRD / 32ND ST                    | IH 35 SVRD     | 32ND ST          |               | 3109             | 5159577             | TURNED_ON     |        |              | 1034           |                | 30.2890625 | -97.723053  | 
| 286           | Axis             |                     | LOC16-004800    | 2017269               | 3367455             |             |                 | 9                |              |               | 35 SVRD / 32ND ST                    | IH 35 SVRD     | 32ND ST          |               | 3109             | 5159577             | TURNED_ON     |        |              | 1034           |                | 30.2890625 | -97.723053  | 
| 285           | Spectra Enhanced |                     | LOC16-004705    | 2046381               | 3195185             |             |                 |                  |              |               | ROSS RD / SAINT THOMAS DR            | ROSS RD        | SAINT THOMAS DR  |               | 4500             | 5168394             | TURNED_ON     |        |              | 12818          |                | 30.1783047 | -97.6151962 | 
| 284           | Sarix            |                     | LOC16-004690    | 3267712               | 2011195             |             |                 | 1                |              |               | CAMERON RD / RUNDBERG LN             | CAMERON RD     | RUNDBERG LN      |               | 9210             | 5164535             | TURNED_ON     |        |              | 1414           |                | 30.3507729 | -97.675972  | 
| 283           | Sarix            |                     | LOC16-004555    | 2017560               | 2017559             |             |                 | 9                |              |               | DEAN KEETON ST / LAFAYETTE AVE       | DEAN KEETON ST | LAFAYETTE AVE    |               | 1300             | 5159732             | TURNED_ON     |        |              | 2316           |                | 30.2844238 | -97.7218094 | 
| 282           | Sarix            |                     | LOC16-004525    | 3260017               | 2027870             |             |                 | 5                |              |               | SLAUGHTER LN / FRANCIA TRL           | SLAUGHTER LN   | FRANCIA TRL      |               | 400              | 5150904             | TURNED_ON     |        |              | 9101           |                | 30.1692791 | -97.7958298 | 
| 281           | Sarix            |                     | LOC16-004400    | 2038623               | 2036303             |             |                 | 6                |              |               | PARMER LN / AVERY RANCH BLVD         | PARMER LN      | AVERY RANCH BLVD |               | 10223            | 5151987             | TURNED_ON     |        |              | 15001          |                | 30.4980755 | -97.7756653 | 
| 203           | Sarix            |                     | LOC16-002740    | 3257911               | 2016749             |             |                 | 9                |              |               | AIRPORT BLVD / WILSHIRE BLVD         | AIRPORT BLVD   | WILSHIRE BLVD    |               | 4301             | 5161099             | TURNED_ON     |        |              | 1610           |                | 30.2978573 | -97.7088776 | 
| 204           | Sarix            |                     | LOC16-002895    | 2035911               | 2012278             | E Koenig LN |                 | 4                |              |               | 35 SVRD / 290 HWY SVRD (E Koenig LN) | IH 35 SVRD     | US 290 HWY SVRD  |               | 6100             | 5161309             | TURNED_ON     |        |              | 6100           | KOENIG LN      | 30.3227043 | -97.7060852 | 
```