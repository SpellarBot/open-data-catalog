# Shellfish Harvesting Waters Sampling Data for 2000 - 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/shellfish-harvesting-waters-sampling-data-for-2000-2012-aef21) |
| Metadata | [Link](https://data.maryland.gov/api/views/s8j6-5yqp) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/s8j6-5yqp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/s8j6-5yqp/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | s8j6-5yqp |
| Name | Shellfish Harvesting Waters Sampling Data for 2000 - 2012 |
| Category | Energy and Environment |
| Tags | shellfish, water sample, sampling results, fecal coliform, mde |
| Created | 2014-06-03T15:58:44Z |
| Publication Date | 2014-06-03T16:53:49Z |

## Description

The State monitors fecal coliform levels as a requirement of the National Shellfish Sanitation Program (NSSP). The Department of the Environment is responsible for classifying and managing Maryland?s shellfish harvesting areas. The goal of shellfish harvesting area classification and management is to provide maximum utilization of shellfish resources and to reduce the risk of shellfish-borne illness. This dataset covers the time period from 2000 to 2012.

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type     | Render Type   |
| ======== | ============== | ========================= | ========================= | ============= | ============= |
| Yes      | series tag     | sampling_organization     | Sampling Organization     | text          | text          |
| Yes      | series tag     | sampling_station_id       | Sampling Station ID       | text          | text          |
| Yes      | series tag     | county                    | County                    | text          | text          |
| Yes      | series tag     | state                     | State                     | text          | text          |
| Yes      | numeric metric | huc                       | HUC                       | number        | number        |
| Yes      | numeric metric | generated_huc             | Generated HUC             | number        | number        |
| Yes      | series tag     | station_horizontal_datum  | Station Horizontal Datum  | text          | text          |
| Yes      | series tag     | activity_id               | Activity ID               | text          | text          |
| Yes      | time           | activity_start            | Activity Start            | calendar_date | calendar_date |
| Yes      | series tag     | activity_start_time_zone  | Activity Start Time Zone  | text          | text          |
| Yes      | series tag     | activity_medium           | Activity Medium           | text          | text          |
| Yes      | series tag     | activity_type             | Activity Type             | text          | text          |
| Yes      | series tag     | activity_category_rep_num | Activity Category-Rep Num | text          | text          |
| Yes      | numeric metric | activity_depth            | Activity Depth            | number        | number        |
| Yes      | series tag     | activity_depth_unit       | Activity Depth Unit       | text          | text          |
| Yes      | series tag     | characteristic_name       | Characteristic Name       | text          | text          |
| Yes      | series tag     | sample_fraction           | Sample Fraction           | text          | text          |
| Yes      | series tag     | value_type                | Value Type                | text          | text          |
| Yes      | series tag     | statistic_type            | Statistic Type            | text          | text          |
| Yes      | series tag     | result_value_status       | Result Value Status       | text          | text          |
| Yes      | series tag     | result_value              | Result Value              | text          | text          |
| Yes      | series tag     | units                     | Units                     | text          | text          |
| Yes      | series tag     | analytical_proc_id        | Analytical Proc ID        | text          | text          |
```

## Time Field

```ls
Value = activity_start
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:s8j6-5yqp d:2005-06-08T09:02:00.000Z t:value_type=Actual t:analytical_proc_id=~ t:activity_category_rep_num="Field Msr/Obs-Portable Data Logger" t:activity_id=SFISH-45782-SFISH05 t:sampling_station_id=1104041 t:characteristic_name="Dissolved oxygen (DO)" t:state=MARYLAND t:sampling_organization="Maryland Dept. of the  Environment Shellfish Data" t:sample_fraction=Dissolved t:activity_depth_unit=ft t:units=mg/l t:result_value_status=Final t:result_value=8.4 t:county="ST MARY'S" t:activity_medium=Water t:station_horizontal_datum=NAD83 t:activity_type="Field Msr/Obs-Portable Data Logger" t:activity_start_time_zone=EST m:generated_huc=2070011 m:activity_depth=1 m:huc=2070011

series e:s8j6-5yqp d:2005-06-15T11:18:00.000Z t:value_type=Actual t:analytical_proc_id=~ t:activity_category_rep_num="Field Msr/Obs-Portable Data Logger" t:activity_id=SFISH-45995-SFISH05 t:sampling_station_id=1302702 t:characteristic_name="Dissolved oxygen (DO)" t:state=MARYLAND t:sampling_organization="Maryland Dept. of the  Environment Shellfish Data" t:sample_fraction=Dissolved t:activity_depth_unit=ft t:units=mg/l t:result_value_status=Final t:result_value=7.9 t:county="ST MARY'S" t:activity_medium=Water t:station_horizontal_datum=NAD83 t:activity_type="Field Msr/Obs-Portable Data Logger" t:activity_start_time_zone=EST m:generated_huc=2070011 m:activity_depth=1 m:huc=2070011

series e:s8j6-5yqp d:2010-03-08T12:01:00.000Z t:value_type=Actual t:analytical_proc_id=APHA~3.2-B t:activity_category_rep_num=Sample-Routine t:activity_id=2010DATA_50881 t:sampling_station_id=1802101 t:characteristic_name="Wind direction (direction from, expressed 0-360 deg)" t:state=MARYLAND t:sampling_organization="Maryland Dept. of the  Environment Shellfish Data" t:units=Deg t:result_value_status=Final t:county=SOMERSET t:result_value=8 t:activity_medium=Water t:station_horizontal_datum=NAD83 t:activity_type=Sample-Routine t:activity_start_time_zone=EST m:generated_huc=2060009 m:huc=2060009
```

## Meta Commands

```ls
metric m:huc p:integer l:HUC d:"Hydrologic Unit Code - a national identification system" t:dataTypeName=number

metric m:generated_huc p:integer l:"Generated HUC" d:"Hydrologic Unit Code - a national identification system" t:dataTypeName=number

metric m:activity_depth p:integer l:"Activity Depth" d:"Depth at which the sample was taken, where applicable." t:dataTypeName=number

entity e:s8j6-5yqp l:"Shellfish Harvesting Waters Sampling Data for 2000 - 2012" t:url=https://data.maryland.gov/api/views/s8j6-5yqp

property e:s8j6-5yqp t:meta.view v:id=s8j6-5yqp v:category="Energy and Environment" v:averageRating=0 v:name="Shellfish Harvesting Waters Sampling Data for 2000 - 2012"

property e:s8j6-5yqp t:meta.view.license v:name="Public Domain"

property e:s8j6-5yqp t:meta.view.owner v:id=6wh5-kegk v:profileImageUrlMedium=/api/users/6wh5-kegk/profile_images/THUMB v:profileImageUrlLarge=/api/users/6wh5-kegk/profile_images/LARGE v:screenName="Andrew Gosden" v:profileImageUrlSmall=/api/users/6wh5-kegk/profile_images/TINY v:lastNotificationSeenAt=1491588421 v:displayName="Andrew Gosden"

property e:s8j6-5yqp t:meta.view.tableauthor v:id=6wh5-kegk v:profileImageUrlMedium=/api/users/6wh5-kegk/profile_images/THUMB v:profileImageUrlLarge=/api/users/6wh5-kegk/profile_images/LARGE v:screenName="Andrew Gosden" v:profileImageUrlSmall=/api/users/6wh5-kegk/profile_images/TINY v:roleName=editor v:lastNotificationSeenAt=1491588421 v:displayName="Andrew Gosden"
```

## Top Records

```ls
| sampling_organization                            | sampling_station_id | county       | state    | huc     | generated_huc | station_horizontal_datum | activity_id         | activity_start      | activity_start_time_zone | activity_medium | activity_type                      | activity_category_rep_num          | activity_depth | activity_depth_unit | characteristic_name                                  | sample_fraction | value_type | statistic_type | result_value_status | result_value | units | analytical_proc_id | 
| ================================================ | =================== | ============ | ======== | ======= | ============= | ======================== | =================== | =================== | ======================== | =============== | ================================== | ================================== | ============== | =================== | ==================================================== | =============== | ========== | ============== | =================== | ============ | ===== | ================== | 
| Maryland Dept. of the Environment Shellfish Data | 1104041             | ST MARY'S    | MARYLAND | 2070011 | 2070011       | NAD83                    | SFISH-45782-SFISH05 | 2005-06-08T09:02:00 | EST                      | Water           | Field Msr/Obs-Portable Data Logger | Field Msr/Obs-Portable Data Logger | 1              | ft                  | Dissolved oxygen (DO)                                | Dissolved       | Actual     |                | Final               | 8.4          | mg/l  | ~                  | 
| Maryland Dept. of the Environment Shellfish Data | 1302702             | ST MARY'S    | MARYLAND | 2070011 | 2070011       | NAD83                    | SFISH-45995-SFISH05 | 2005-06-15T11:18:00 | EST                      | Water           | Field Msr/Obs-Portable Data Logger | Field Msr/Obs-Portable Data Logger | 1              | ft                  | Dissolved oxygen (DO)                                | Dissolved       | Actual     |                | Final               | 7.9          | mg/l  | ~                  | 
| Maryland Dept. of the Environment Shellfish Data | 1802101             | SOMERSET     | MARYLAND | 2060009 | 2060009       | NAD83                    | 2010DATA_50881      | 2010-03-08T12:01:00 | EST                      | Water           | Sample-Routine                     | Sample-Routine                     |                |                     | Wind direction (direction from, expressed 0-360 deg) |                 | Actual     |                | Final               | 8            | Deg   | APHA~3.2-B         | 
| Maryland Dept. of the Environment Shellfish Data | 1802101             | SOMERSET     | MARYLAND | 2060009 | 2060009       | NAD83                    | 2010DATA_50880      | 2010-03-08T12:01:00 | EST                      | Water           | Sample-Routine                     | Sample-Routine                     |                |                     | Wind velocity                                        |                 | Estimated  |                | Final               | 10           | knots | APHA~3.2-B         | 
| Maryland Dept. of the Environment Shellfish Data | 1404031             | DORCHESTER   | MARYLAND | 2060007 | 2060007       | NAD83                    | 2009DATA_50573      | 2009-09-14T10:39:00 | EST                      | Water           | Sample-Routine                     | Sample-Routine                     |                |                     | Dissolved oxygen (DO)                                |                 | Actual     |                | Final               | 5.8          | mg/l  | APHA~3.2-B         | 
| Maryland Dept. of the Environment Shellfish Data | 601011              | QUEEN ANNE'S | MARYLAND | 2060002 | 2060002       | NAD83                    | 2009DATA_50286      | 2009-09-14T09:40:00 | EST                      | Water           | Sample-Routine                     | Sample-Routine                     |                |                     | Fecal Coliform                                       |                 | Actual     |                | Final               | 1            | MPN   | APHA~3.2-B         | 
| Maryland Dept. of the Environment Shellfish Data | 902019              | ST MARY'S    | MARYLAND | 2060006 | 2060006       | NAD83                    | 2010DATA_30449      | 2010-04-05T10:04:00 | EST                      | Water           | Sample-Routine                     | Sample-Routine                     |                |                     | Temperature, air                                     |                 | Actual     |                | Final               | 18.89        | deg C | APHA~3.2-B         | 
| Maryland Dept. of the Environment Shellfish Data | 1003011             | DORCHESTER   | MARYLAND | 2060005 | 2060005       | NAD83                    | 2010DATA_35174      | 2010-04-05T10:08:00 | EST                      | Water           | Sample-Routine                     | Sample-Routine                     |                |                     | Temperature, air                                     |                 | Actual     |                | Final               | 15           | deg C | APHA~3.2-B         | 
| Maryland Dept. of the Environment Shellfish Data | 1003705             | TALBOT       | MARYLAND | 2060005 | 2060005       | NAD83                    | 2010DATA_35630      | 2010-04-05T09:07:00 | EST                      | Water           | Sample-Routine                     | Sample-Routine                     |                |                     | Temperature, air                                     |                 | Actual     |                | Final               | 12.78        | deg C | APHA~3.2-B         | 
| Maryland Dept. of the Environment Shellfish Data | 903107              | CALVERT      | MARYLAND | 2060006 | 2060006       | NAD83                    | 2010DATA_31868      | 2010-05-20T11:47:00 | EST                      | Water           | Sample-Routine                     | Sample-Routine                     |                |                     | Fecal Coliform                                       |                 | Actual     |                | Final               | 9.1          | MPN   | APHA~3.2-B         | 
```