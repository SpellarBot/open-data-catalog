# Equivalent Availability Factor

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/equivalent-availability-factor) |
| Metadata | [Link](https://data.austintexas.gov/api/views/mpip-i8mq) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/mpip-i8mq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/mpip-i8mq/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | mpip-i8mq |
| Name | Equivalent Availability Factor |
| Attribution | Austin Energy |
| Category | Utility |
| Tags | equivalent availability factor, austin energy, energy |
| Created | 2016-09-12T13:58:00Z |
| Publication Date | 2016-10-18T13:48:48Z |

## Description

A common measure of reliability for generating units is the Equivalent Availability Factor (EAF). The EAF is a measure of the number of hours the full capacity of a generating unit is available per the total period hours.  
 
Availability targets for baseload facilities (South Texas Project and Fayette Power Project) are adjusted annually depending on the duration of any planned outages for that year. For intermediate and peaking facilities, Austin Energy?s peak season availability target is greater than or equal to 95%.

The target numbers are: South Texas Project ? 94.8%, Fayette Power Project ? 94.2%, and (Sand Hill Energy Center  Unit 5A , Sand Hill Energy Center Units 1-4, Decker Creek Power Station  GT 1-4,  Decker Creek Power Station  D1-2) all ? 95%

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                           | Data Type     | Render Type   |
| ======== | ============== | =============================== | ============================== | ============= | ============= |
| Yes      | time           | fiscal_year_2                   | Fiscal Year                    | calendar_date | calendar_date |
| Yes      | series tag     | generating_unit                 | Generating Unit                | text          | text          |
| Yes      | numeric metric | decker_creek_power_station_d1_2 | Equivalent Availability Factor | percent       | percent       |
```

## Time Field

```ls
Value = fiscal_year_2
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:mpip-i8mq d:2006-01-01T00:00:00.000Z t:generating_unit="South Texas Project" m:decker_creek_power_station_d1_2=95.3

series e:mpip-i8mq d:2006-01-01T00:00:00.000Z t:generating_unit="Fayette Power Project" m:decker_creek_power_station_d1_2=87

series e:mpip-i8mq d:2006-01-01T00:00:00.000Z t:generating_unit="Sand Hill Energy Center  Unit 5A" m:decker_creek_power_station_d1_2=87.65
```

## Meta Commands

```ls
metric m:decker_creek_power_station_d1_2 p:float l:"Equivalent Availability Factor" t:dataTypeName=percent

entity e:mpip-i8mq l:"Equivalent Availability Factor" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/mpip-i8mq

property e:mpip-i8mq t:meta.view v:id=mpip-i8mq v:category=Utility v:averageRating=0 v:name="Equivalent Availability Factor" v:attribution="Austin Energy"

property e:mpip-i8mq t:meta.view.license v:name="Public Domain"

property e:mpip-i8mq t:meta.view.owner v:id=c433-zrb5 v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:screenName="Sarah Lambert" v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:displayName="Sarah Lambert"

property e:mpip-i8mq t:meta.view.tableauthor v:id=c433-zrb5 v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:screenName="Sarah Lambert" v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:roleName=publisher v:displayName="Sarah Lambert"
```

## Top Records

```ls
| fiscal_year_2       | generating_unit                   | decker_creek_power_station_d1_2 | 
| =================== | ================================= | =============================== | 
| 2006-01-01T00:00:00 | South Texas Project               | 95.30                           | 
| 2006-01-01T00:00:00 | Fayette Power Project             | 87.00                           | 
| 2006-01-01T00:00:00 | Sand Hill Energy Center Unit 5A   | 87.65                           | 
| 2006-01-01T00:00:00 | Sand Hill Energy Center Units 1-4 | 96.52                           | 
| 2006-01-01T00:00:00 | Decker Creek Power Station GT 1-4 | 94.67                           | 
| 2006-01-01T00:00:00 | Decker Creek Power Station D1-2   | 90.96                           | 
| 2007-01-01T00:00:00 | South Texas Project               | 90.60                           | 
| 2007-01-01T00:00:00 | Fayette Power Project             | 93.10                           | 
| 2007-01-01T00:00:00 | Sand Hill Energy Center Unit 5A   | 99.96                           | 
| 2007-01-01T00:00:00 | Sand Hill Energy Center Units 1-4 | 88.88                           | 
```