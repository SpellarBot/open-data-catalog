# JATRAN Ridership

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/jatran-ridership) |
| Metadata | [Link](https://data.jacksonms.gov/api/views/7aht-3yba) |
| Data: JSON | [100 Rows](https://data.jacksonms.gov/api/views/7aht-3yba/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.jacksonms.gov/api/views/7aht-3yba/rows.csv?max_rows=100) |
| Host | data.jacksonms.gov |
| Id | 7aht-3yba |
| Name | JATRAN Ridership |
| Attribution | City of Jackson - Transit Department |
| Category | Transportation and Transit |
| Tags | community, neighborhood associations, connected, city of jackson, super neighborhood, citizen engagment, jatran, transit, ridership |
| Created | 2016-05-06T16:35:28Z |
| Publication Date | 2016-12-01T20:36:55Z |

## Description

This data compiles ridership numbers for JATRAN (the City's public transportation system). This data is updated monthly.

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type     | Render Type   |
| ======== | ============== | =========================== | =========================== | ============= | ============= |
| Yes      | time           | reporting_month             | Reporting Month             | calendar_date | calendar_date |
| Yes      | numeric metric | weekday_service_days        | Weekday - Service Days      | number        | number        |
| Yes      | numeric metric | weekend_service_days        | Weekend - Service Days      | number        | number        |
| Yes      | numeric metric | revenue_mileage             | Revenue Mileage             | number        | number        |
| Yes      | numeric metric | operating_hours             | Operating Hours             | number        | number        |
| Yes      | numeric metric | passenger_ridership         | Passenger Ridership         | number        | number        |
| Yes      | numeric metric | farebox_revenue             | Farebox Revenue             | money         | money         |
| Yes      | numeric metric | passengers_per_revenue_mile | Passengers per Revenue Mile | number        | number        |
| Yes      | numeric metric | passengers_per_hour         | Passengers per Hour         | number        | number        |
| Yes      | numeric metric | revenue_per_revenue_mile    | Revenue per Revenue Mile    | money         | money         |
| Yes      | numeric metric | revenue_per_hour            | Revenue per Hour            | money         | money         |
| Yes      | numeric metric | revenue_per_passenger       | Revenue per Passenger       | money         | money         |
```

## Time Field

```ls
Value = reporting_month
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:7aht-3yba d:2014-10-01T00:00:00.000Z m:revenue_mileage=66161 m:passengers_per_revenue_mile=0.91 m:operating_hours=4288 m:revenue_per_revenue_mile=0.6 m:weekday_service_days=23 m:weekend_service_days=4 m:revenue_per_passenger=0.66 m:revenue_per_hour=9.29 m:passengers_per_hour=13.99 m:passenger_ridership=59987 m:farebox_revenue=39819

series e:7aht-3yba d:2014-11-01T00:00:00.000Z m:revenue_mileage=57367 m:passengers_per_revenue_mile=0.82 m:operating_hours=3718 m:revenue_per_revenue_mile=0.51 m:weekday_service_days=19 m:weekend_service_days=5 m:revenue_per_passenger=0.62 m:revenue_per_hour=7.91 m:passengers_per_hour=12.68 m:passenger_ridership=47144 m:farebox_revenue=29417

series e:7aht-3yba d:2014-12-01T00:00:00.000Z m:revenue_mileage=63563 m:passengers_per_revenue_mile=0.75 m:operating_hours=4119 m:revenue_per_revenue_mile=0.54 m:weekday_service_days=22 m:weekend_service_days=4 m:revenue_per_passenger=0.72 m:revenue_per_hour=8.26 m:passengers_per_hour=11.51 m:passenger_ridership=47397 m:farebox_revenue=34045
```

## Meta Commands

```ls
metric m:weekday_service_days p:integer l:"Weekday - Service Days" t:dataTypeName=number

metric m:weekend_service_days p:integer l:"Weekend - Service Days" t:dataTypeName=number

metric m:revenue_mileage p:integer l:"Revenue Mileage" t:dataTypeName=number

metric m:operating_hours p:integer l:"Operating Hours" t:dataTypeName=number

metric m:passenger_ridership p:integer l:"Passenger Ridership" t:dataTypeName=number

metric m:farebox_revenue p:double l:"Farebox Revenue" t:dataTypeName=money

metric m:passengers_per_revenue_mile p:float l:"Passengers per Revenue Mile" t:dataTypeName=number

metric m:passengers_per_hour p:float l:"Passengers per Hour" t:dataTypeName=number

metric m:revenue_per_revenue_mile p:double l:"Revenue per Revenue Mile" t:dataTypeName=money

metric m:revenue_per_hour p:double l:"Revenue per Hour" t:dataTypeName=money

metric m:revenue_per_passenger p:double l:"Revenue per Passenger" t:dataTypeName=money

entity e:7aht-3yba l:"JATRAN Ridership" t:attribution="City of Jackson - Transit Department" t:url=https://data.jacksonms.gov/api/views/7aht-3yba

property e:7aht-3yba t:meta.view v:id=7aht-3yba v:category="Transportation and Transit" v:attributionLink=http://www.jacksonms.gov v:averageRating=0 v:name="JATRAN Ridership" v:attribution="City of Jackson - Transit Department"

property e:7aht-3yba t:meta.view.owner v:id=6ngd-c2u2 v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:screenName="Justin Bruce" v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:lastNotificationSeenAt=1492180672 v:displayName="Justin Bruce"

property e:7aht-3yba t:meta.view.tableauthor v:id=6ngd-c2u2 v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:screenName="Justin Bruce" v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492180672 v:displayName="Justin Bruce"
```

## Top Records

```ls
| reporting_month     | weekday_service_days | weekend_service_days | revenue_mileage | operating_hours | passenger_ridership | farebox_revenue | passengers_per_revenue_mile | passengers_per_hour | revenue_per_revenue_mile | revenue_per_hour | revenue_per_passenger | 
| =================== | ==================== | ==================== | =============== | =============== | =================== | =============== | =========================== | =================== | ======================== | ================ | ===================== | 
| 2014-10-01T00:00:00 | 23                   | 4                    | 66161           | 4288            | 59987               | 39819.00        | 0.91                        | 13.99               | 0.60                     | 9.29             | 0.66                  | 
| 2014-11-01T00:00:00 | 19                   | 5                    | 57367           | 3718            | 47144               | 29417.00        | 0.82                        | 12.68               | 0.51                     | 7.91             | 0.62                  | 
| 2014-12-01T00:00:00 | 22                   | 4                    | 63563           | 4119            | 47397               | 34045.00        | 0.75                        | 11.51               | 0.54                     | 8.26             | 0.72                  | 
| 2015-01-01T00:00:00 | 21                   | 5                    | 62564           | 4055            | 54199               | 30766.00        | 0.87                        | 13.37               | 0.49                     | 7.59             | 0.57                  | 
| 2015-02-01T00:00:00 | 20                   | 4                    | 58366           | 3783            | 44171               | 29009.00        | 0.76                        | 11.68               | 0.50                     | 7.67             | 0.66                  | 
| 2015-03-01T00:00:00 | 22                   | 4                    | 63563           | 4119            | 84152               | 32938.00        | 1.32                        | 20.43               | 0.52                     | 8.00             | 0.39                  | 
| 2015-04-01T00:00:00 | 22                   | 4                    | 36563           | 4119            | 57313               | 32194.00        | 0.90                        | 13.91               | 0.51                     | 7.82             | 0.56                  | 
| 2015-05-01T00:00:00 | 20                   | 5                    | 59966           | 3887            | 46866               | 29161.00        | 0.78                        | 12.06               | 0.49                     | 7.50             | 0.62                  | 
| 2015-06-01T00:00:00 | 22                   | 4                    | 63563           | 4119            | 48327               | 30406.00        | 0.76                        | 11.73               | 0.48                     | 7.38             | 0.63                  | 
| 2015-07-01T00:00:00 | 23                   | 3                    | 64562           | 4184            | 40853               | 28482.00        | 0.63                        | 9.76                | 0.44                     | 6.81             | 0.70                  | 
```