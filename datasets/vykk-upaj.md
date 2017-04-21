# Racial Profiling Dataset 2015- Arrests

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/racial-profiling-dataset-2015-arrests) |
| Metadata | [Link](https://data.austintexas.gov/api/views/vykk-upaj) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/vykk-upaj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/vykk-upaj/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | vykk-upaj |
| Name | Racial Profiling Dataset 2015- Arrests |
| Attribution | Austin Police Department |
| Category | Public Safety |
| Tags | police, public safety, racial profiling, arrests |
| Created | 2016-03-10T15:49:31Z |
| Publication Date | 2016-03-10T15:57:22Z |

## Description

This Racial Profiling dataset provides the raw data needed to identify trends in traffic stops. It is used to help identify potential improvements in department policy, tactics, and training.  This data is used to produce the annual Racial Profiling report, posted on APD's website here:	
http://www.austintexas.gov/page/racial-profiling-reports

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type     | Render Type   |
| ======== | ============== | ==================== | ==================== | ============= | ============= |
| Yes      | numeric metric | primary_key          | PRIMARY_KEY          | number        | number        |
| Yes      | time           | rep_date             | REP_DATE             | calendar_date | calendar_date |
| No       |                | rep_time             | REP_TIME             | number        | number        |
| Yes      | series tag     | sex                  | SEX                  | text          | text          |
| Yes      | numeric metric | age_at_offense       | AGE_AT_OFFENSE       | number        | number        |
| Yes      | series tag     | apd_race_desc        | APD_RACE_DESC        | text          | text          |
| Yes      | series tag     | location             | LOCATION             | text          | text          |
| Yes      | series tag     | person_searched_desc | PERSON_SEARCHED_DESC | text          | text          |
| Yes      | series tag     | reason_for_stop_desc | REASON_FOR_STOP_DESC | text          | text          |
| Yes      | series tag     | search_based_on_desc | SEARCH_BASED_ON_DESC | text          | text          |
| Yes      | series tag     | search_disc_desc     | SEARCH_DISC_DESC     | text          | text          |
| Yes      | series tag     | race_known           | RACE_KNOWN           | text          | text          |
| No       |                | x_coordinate         | X_COORDINATE         | number        | number        |
| No       |                | y_coordinate         | Y_COORDINATE         | number        | number        |
| Yes      | series tag     | sector               | SECTOR               | text          | text          |
| Yes      | numeric metric | local_field1         | LOCAL_FIELD1         | number        | number        |
```

## Time Field

```ls
Value = rep_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = rep_time,x_coordinate,y_coordinate
```

## Data Commands

```ls
series e:vykk-upaj d:2015-01-01T00:00:00.000Z t:person_searched_desc="YES = 1" t:sector=GEORGE t:search_based_on_desc="INCIDENTAL TO ARREST" t:sex=M t:search_disc_desc=NOTHING t:apd_race_desc="HISPANIC OR LATINO" t:location="701 N IH 35 NB" t:race_known="NO - RACE OR ETHNICITY WAS NOT KNOWN BEFORE STOP" t:reason_for_stop_desc="CALL FOR SERVICE" m:local_field1=1 m:age_at_offense=22 m:primary_key=201510010

series e:vykk-upaj d:2015-01-01T00:00:00.000Z t:person_searched_desc="YES = 1" t:sector=DAVID t:search_based_on_desc="INCIDENTAL TO ARREST" t:sex=M t:search_disc_desc=DRUGS t:apd_race_desc=WHITE t:location="1100 W BEN WHITE BLVD EB" t:race_known="NO - RACE OR ETHNICITY WAS NOT KNOWN BEFORE STOP" t:reason_for_stop_desc="VIOLATION OF TRANSPORTATION CODE/VEHICLE LAWS" m:local_field1=5 m:age_at_offense=27 m:primary_key=201510140

series e:vykk-upaj d:2015-01-01T00:00:00.000Z t:person_searched_desc="YES = 1" t:sector=DAVID t:search_based_on_desc="INCIDENTAL TO ARREST" t:sex=F t:search_disc_desc=DRUGS t:apd_race_desc=WHITE t:location="1100 W BEN WHITE BLVD EB" t:race_known="NO - RACE OR ETHNICITY WAS NOT KNOWN BEFORE STOP" t:reason_for_stop_desc="VIOLATION OF TRANSPORTATION CODE/VEHICLE LAWS" m:local_field1=5 m:age_at_offense=19 m:primary_key=201510140
```

## Meta Commands

```ls
metric m:primary_key p:long l:PRIMARY_KEY t:dataTypeName=number

metric m:age_at_offense p:integer l:AGE_AT_OFFENSE t:dataTypeName=number

metric m:local_field1 p:integer l:LOCAL_FIELD1 t:dataTypeName=number

entity e:vykk-upaj l:"Racial Profiling Dataset 2015- Arrests" t:attribution="Austin Police Department" t:url=https://data.austintexas.gov/api/views/vykk-upaj

property e:vykk-upaj t:meta.view v:id=vykk-upaj v:category="Public Safety" v:averageRating=0 v:name="Racial Profiling Dataset 2015- Arrests" v:attribution="Austin Police Department"

property e:vykk-upaj t:meta.view.owner v:id=q374-e9d9 v:screenName="Ron MacKay" v:displayName="Ron MacKay"

property e:vykk-upaj t:meta.view.tableauthor v:id=q374-e9d9 v:screenName="Ron MacKay" v:roleName=publisher_stories v:displayName="Ron MacKay"
```

## Top Records

```ls
| primary_key | rep_date            | rep_time | sex | age_at_offense | apd_race_desc      | location                  | person_searched_desc | reason_for_stop_desc                          | search_based_on_desc | search_disc_desc | race_known                                       | x_coordinate | y_coordinate | sector | local_field1 | 
| =========== | =================== | ======== | === | ============== | ================== | ========================= | ==================== | ============================================= | ==================== | ================ | ================================================ | ============ | ============ | ====== | ============ | 
| 201510010   | 2015-01-01T00:00:00 | 2        | M   | 22             | HISPANIC OR LATINO | 701 N IH 35 NB            | YES = 1              | CALL FOR SERVICE                              | INCIDENTAL TO ARREST | NOTHING          | NO - RACE OR ETHNICITY WAS NOT KNOWN BEFORE STOP | 3117044      | 10070236     | GEORGE | 1            | 
| 201510140   | 2015-01-01T00:00:00 | 317      | M   | 27             | WHITE              | 1100 W BEN WHITE BLVD EB  | YES = 1              | VIOLATION OF TRANSPORTATION CODE/VEHICLE LAWS | INCIDENTAL TO ARREST | DRUGS            | NO - RACE OR ETHNICITY WAS NOT KNOWN BEFORE STOP | 3103640      | 10055808     | DAVID  | 5            | 
| 201510140   | 2015-01-01T00:00:00 | 317      | F   | 19             | WHITE              | 1100 W BEN WHITE BLVD EB  | YES = 1              | VIOLATION OF TRANSPORTATION CODE/VEHICLE LAWS | INCIDENTAL TO ARREST | DRUGS            | NO - RACE OR ETHNICITY WAS NOT KNOWN BEFORE STOP | 3103640      | 10055808     | DAVID  | 5            | 
| 201510262   | 2015-01-01T00:00:00 | 426      | M   | 28             | WHITE              | 1400 W 6TH ST             | YES = 1              | VIOLATION OF TRANSPORTATION CODE/VEHICLE LAWS | INCIDENTAL TO ARREST | NOTHING          | NO - RACE OR ETHNICITY WAS NOT KNOWN BEFORE STOP | 3108779      | 10072861     | BAKER  | 9            | 
| 201510324   | 2015-01-01T00:00:00 | 106      | F   | 55             | WHITE              | 500 TRINITY ST            | YES = 1              | CONSENSUAL CONTACT                            | INCIDENTAL TO ARREST | OTHER            | NO - RACE OR ETHNICITY WAS NOT KNOWN BEFORE STOP | 3115301      | 10070114     | GEORGE | 9            | 
| 201510491   | 2015-01-01T00:00:00 | 526      | M   | 20             | ASIAN              | W YAGER LN / N LAMAR BLVD | YES = 1              | VIOLATION OF TRANSPORTATION CODE/VEHICLE LAWS | INCIDENTAL TO ARREST | NOTHING          | NO - RACE OR ETHNICITY WAS NOT KNOWN BEFORE STOP | 3133236      | 10119845     | EDWARD | 7            | 
| 201510541   | 2015-01-01T00:00:00 | 201      | M   | 30             | HISPANIC OR LATINO | 3000 BLOCK NORTHLAND DR   | YES = 1              | VIOLATION OF TRANSPORTATION CODE/VEHICLE LAWS | INCIDENTAL TO ARREST | OTHER            | NO - RACE OR ETHNICITY WAS NOT KNOWN BEFORE STOP | 3110504      | 10095151     | BAKER  | 7            | 
| 201510587   | 2015-01-01T00:00:00 | 1745     | M   | 21             | WHITE              | 500 SAN JACINTO BLVD      | YES = 1              | VIOLATION OF TRANSPORTATION CODE/VEHICLE LAWS | INCIDENTAL TO ARREST | ALCOHOL          | NO - RACE OR ETHNICITY WAS NOT KNOWN BEFORE STOP | 3114905      | 10070325     | GEORGE | 9            | 
| 201510603   | 2015-01-01T00:00:00 | 221      | M   | 31             | HISPANIC OR LATINO | 7800 S IH 35 SVRD NB      | YES = 1              | VIOLATION OF TRANSPORTATION CODE/VEHICLE LAWS | INCIDENTAL TO ARREST | NOTHING          | NO - RACE OR ETHNICITY WAS NOT KNOWN BEFORE STOP | 3103979      | 10038055     | FRANK  | 2            | 
| 201510627   | 2015-01-01T00:00:00 | 229      | M   | 21             | HISPANIC OR LATINO | 900 BLOCK S IH 35 SVRD NB | YES = 1              | VIOLATION OF TRANSPORTATION CODE/VEHICLE LAWS | INCIDENTAL TO ARREST | CASH             | NO - RACE OR ETHNICITY WAS NOT KNOWN BEFORE STOP | 3116808      | 10064059     | HENR   | 9            | 
```