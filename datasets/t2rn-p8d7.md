# CTA - Ridership - 'L' Station Entries - Monthly Day-Type Averages & Totals

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cta-ridership-l-station-entries-monthly-day-type-averages-totals-26ba4) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/t2rn-p8d7) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/t2rn-p8d7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/t2rn-p8d7/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | t2rn-p8d7 |
| Name | CTA - Ridership - 'L' Station Entries - Monthly Day-Type Averages & Totals |
| Attribution | Chicago Transit Authority |
| Category | Transportation |
| Tags | cta, public transit, ridership |
| Created | 2011-08-05T19:32:43Z |
| Publication Date | 2017-02-16T23:51:23Z |

## Description

This dataset lists monthly station entry averages, by day type (Weekday, Saturday or Sunday/Holiday), as well as monthly totals, beginning in 2001. Note that some stations (such as on the Cermak Branch--now Pink Line) and Skokie did not have Saturday and/or Sunday/holiday service until more recent years, although, in cases where weekday service ran past midnight, late evening fares may appear as part of Saturday tallies.

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type     | Render Type   |
| ======== | ============== | ======================== | ======================== | ============= | ============= |
| Yes      | series tag     | station_id               | station_id               | text          | number        |
| Yes      | series tag     | stationame               | stationame               | text          | text          |
| Yes      | time           | month_beginning          | month_beginning          | calendar_date | calendar_date |
| Yes      | numeric metric | avg_weekday_rides        | avg_weekday_rides        | number        | number        |
| Yes      | numeric metric | avg_saturday_rides       | avg_saturday_rides       | number        | number        |
| Yes      | numeric metric | avg_sunday_holiday_rides | avg_sunday-holiday_rides | number        | number        |
| Yes      | numeric metric | monthtotal               | monthtotal               | number        | number        |
```

## Time Field

```ls
Value = month_beginning
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:t2rn-p8d7 d:2001-01-01T00:00:00.000Z t:stationame=Howard t:station_id=40900 m:avg_weekday_rides=6233.9 m:avg_saturday_rides=3814.5 m:avg_sunday_holiday_rides=2408.6 m:monthtotal=164447

series e:t2rn-p8d7 d:2001-01-01T00:00:00.000Z t:stationame=Jarvis t:station_id=41190 m:avg_weekday_rides=1489.1 m:avg_saturday_rides=1054 m:avg_sunday_holiday_rides=718 m:monthtotal=40567

series e:t2rn-p8d7 d:2001-01-01T00:00:00.000Z t:stationame=Morse t:station_id=40100 m:avg_weekday_rides=4412.5 m:avg_saturday_rides=3064.5 m:avg_sunday_holiday_rides=2087.8 m:monthtotal=119772
```

## Meta Commands

```ls
metric m:avg_weekday_rides p:float l:avg_weekday_rides t:dataTypeName=number

metric m:avg_saturday_rides p:float l:avg_saturday_rides t:dataTypeName=number

metric m:avg_sunday_holiday_rides p:double l:avg_sunday-holiday_rides t:dataTypeName=number

metric m:monthtotal p:integer l:monthtotal t:dataTypeName=number

entity e:t2rn-p8d7 l:"CTA - Ridership - 'L' Station Entries - Monthly Day-Type Averages & Totals" t:attribution="Chicago Transit Authority" t:url=https://data.cityofchicago.org/api/views/t2rn-p8d7

property e:t2rn-p8d7 t:meta.view v:id=t2rn-p8d7 v:category=Transportation v:attributionLink=http://www.transitchicago.com v:averageRating=0 v:name="CTA - Ridership - 'L' Station Entries - Monthly Day-Type Averages & Totals" v:attribution="Chicago Transit Authority"

property e:t2rn-p8d7 t:meta.view.owner v:id=6bsn-5494 v:profileImageUrlMedium=/api/users/6bsn-5494/profile_images/THUMB v:profileImageUrlLarge=/api/users/6bsn-5494/profile_images/LARGE v:screenName="cta web" v:profileImageUrlSmall=/api/users/6bsn-5494/profile_images/TINY v:displayName="cta web"

property e:t2rn-p8d7 t:meta.view.tableauthor v:id=6bsn-5494 v:profileImageUrlMedium=/api/users/6bsn-5494/profile_images/THUMB v:profileImageUrlLarge=/api/users/6bsn-5494/profile_images/LARGE v:screenName="cta web" v:profileImageUrlSmall=/api/users/6bsn-5494/profile_images/TINY v:roleName=designer v:displayName="cta web"
```

## Top Records

```ls
| station_id | stationame | month_beginning     | avg_weekday_rides | avg_saturday_rides | avg_sunday_holiday_rides | monthtotal | 
| ========== | ========== | =================== | ================= | ================== | ======================== | ========== | 
| 40900      | Howard     | 2001-01-01T00:00:00 | 6233.9            | 3814.5             | 2408.6                   | 164447     | 
| 41190      | Jarvis     | 2001-01-01T00:00:00 | 1489.1            | 1054               | 718                      | 40567      | 
| 40100      | Morse      | 2001-01-01T00:00:00 | 4412.5            | 3064.5             | 2087.8                   | 119772     | 
| 41300      | Loyola     | 2001-01-01T00:00:00 | 4664.5            | 3156               | 1952.8                   | 125008     | 
| 40760      | Granville  | 2001-01-01T00:00:00 | 3109.8            | 2126               | 1453.8                   | 84189      | 
| 40880      | Thorndale  | 2001-01-01T00:00:00 | 2977.7            | 1840.3             | 1262.6                   | 79184      | 
| 41380      | Bryn Mawr  | 2001-01-01T00:00:00 | 4425.4            | 2708.3             | 1881.2                   | 117597     | 
| 40340      | Berwyn     | 2001-01-01T00:00:00 | 3329.6            | 2050.8             | 1445.6                   | 88683      | 
| 41200      | Argyle     | 2001-01-01T00:00:00 | 2745.5            | 1874.5             | 1268.2                   | 74240      | 
| 40770      | Lawrence   | 2001-01-01T00:00:00 | 2689.6            | 1869               | 1227.8                   | 72786      | 
```