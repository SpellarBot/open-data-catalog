# Power Partner Thermostat Program

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/power-partner-thermostat-program) |
| Metadata | [Link](https://data.austintexas.gov/api/views/7jgb-hbdr) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/7jgb-hbdr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/7jgb-hbdr/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 7jgb-hbdr |
| Name | Power Partner Thermostat Program |
| Attribution | Austin Energy |
| Category | Utility |
| Tags | thermostat, energy, cooling, heating, rebate |
| Created | 2016-10-21T14:59:04Z |
| Publication Date | 2016-11-14T21:34:06Z |

## Description

Power Partner was launched in 2013 and is a voluntary program for residential customers who use internet-connected thermostats. View dates and times, starting in calendar year 2006, when we used either this or its predecessor voluntary program to reduce residential energy demand. Go to austinenergy.com/go/powerpartner to learn more.

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type     | Render Type   |
| ======== | =========== | ================== | ================== | ============= | ============= |
| Yes      | series tag  | weekday            | Weekday            | text          | text          |
| Yes      | time        | start_cycling_time | Start Cycling Time | calendar_date | calendar_date |
| No       |             | end_cycling_time   | End Cycling Time   | calendar_date | calendar_date |
```

## Time Field

```ls
Value = start_cycling_time
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = end_cycling_time
```

## Data Commands

```ls
series e:7jgb-hbdr d:2016-06-16T16:00:00.000Z t:weekday=Thursday m:row_number.7jgb-hbdr=1

series e:7jgb-hbdr d:2016-06-27T16:00:00.000Z t:weekday=Monday m:row_number.7jgb-hbdr=2

series e:7jgb-hbdr d:2016-07-06T16:00:00.000Z t:weekday=Wednesday m:row_number.7jgb-hbdr=3
```

## Meta Commands

```ls
metric m:row_number.7jgb-hbdr p:long l:"Row Number"

entity e:7jgb-hbdr l:"Power Partner Thermostat Program" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/7jgb-hbdr

property e:7jgb-hbdr t:meta.view v:id=7jgb-hbdr v:category=Utility v:averageRating=0 v:name="Power Partner Thermostat Program" v:attribution="Austin Energy"

property e:7jgb-hbdr t:meta.view.license v:name="Public Domain"

property e:7jgb-hbdr t:meta.view.owner v:id=c433-zrb5 v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:screenName="Sarah Lambert" v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:displayName="Sarah Lambert"

property e:7jgb-hbdr t:meta.view.tableauthor v:id=c433-zrb5 v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:screenName="Sarah Lambert" v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:roleName=publisher v:displayName="Sarah Lambert"
```

## Top Records

```ls
| weekday   | start_cycling_time  | end_cycling_time    | 
| ========= | =================== | =================== | 
| Thursday  | 2016-06-16T16:00:00 | 2016-06-16T18:00:00 | 
| Monday    | 2016-06-27T16:00:00 | 2016-06-27T18:00:00 | 
| Wednesday | 2016-07-06T16:00:00 | 2016-07-06T18:00:00 | 
| Wednesday | 2016-07-13T16:00:00 | 2016-07-13T18:00:00 | 
| Thursday  | 2016-07-14T16:00:00 | 2016-07-14T18:00:00 | 
| Thursday  | 2016-07-21T16:00:00 | 2016-07-21T18:00:00 | 
| Friday    | 2016-07-22T16:00:00 | 2016-07-22T18:00:00 | 
| Wednesday | 2016-08-03T16:00:00 | 2016-08-03T18:00:00 | 
| Thursday  | 2016-08-04T16:00:00 | 2016-08-04T18:00:00 | 
| Wednesday | 2016-08-10T16:00:00 | 2016-08-10T18:00:00 | 
```