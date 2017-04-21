# CTA - Ridership - Bus Routes - Monthly Day-Type Averages & Totals

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cta-ridership-bus-routes-monthly-day-type-averages-totals-7a070) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/bynn-gwxy) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/bynn-gwxy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/bynn-gwxy/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | bynn-gwxy |
| Name | CTA - Ridership - Bus Routes - Monthly Day-Type Averages & Totals |
| Attribution | Chicago Transit Authority |
| Category | Transportation |
| Tags | cta, public transit, ridership, sustainability |
| Created | 2011-08-05T19:25:49Z |
| Publication Date | 2017-02-16T23:51:11Z |

## Description

This dataset shows monthly averages, by day type (weekday, Saturday or Sunday/Holiday) and monthly totals for all CTA bus routes, back to 2001. See attached readme file for information on how these numbers are calculated.

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type     | Render Type   |
| ======== | ============== | ======================== | ======================== | ============= | ============= |
| Yes      | series tag     | route                    | route                    | text          | text          |
| Yes      | series tag     | routename                | routename                | text          | text          |
| Yes      | time           | month_beginning          | Month_Beginning          | calendar_date | calendar_date |
| Yes      | numeric metric | avg_weekday_rides        | Avg_Weekday_Rides        | number        | number        |
| Yes      | numeric metric | avg_saturday_rides       | Avg_Saturday_Rides       | number        | number        |
| Yes      | numeric metric | avg_sunday_holiday_rides | Avg_Sunday-Holiday_Rides | number        | number        |
| Yes      | numeric metric | monthtotal               | MonthTotal               | number        | number        |
```

## Time Field

```ls
Value = month_beginning
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:bynn-gwxy d:2001-01-01T00:00:00.000Z t:route=1 t:routename="Indiana/Hyde Park" m:avg_weekday_rides=6982.6 m:avg_saturday_rides=0 m:avg_sunday_holiday_rides=0 m:monthtotal=153617

series e:bynn-gwxy d:2001-01-01T00:00:00.000Z t:route=2 t:routename="Hyde Park Express" m:avg_weekday_rides=1000 m:avg_saturday_rides=0 m:avg_sunday_holiday_rides=0 m:monthtotal=22001

series e:bynn-gwxy d:2001-01-01T00:00:00.000Z t:route=3 t:routename="King Drive" m:avg_weekday_rides=21406.5 m:avg_saturday_rides=13210.7 m:avg_sunday_holiday_rides=8725.3 m:monthtotal=567413
```

## Meta Commands

```ls
metric m:avg_weekday_rides p:float l:Avg_Weekday_Rides t:dataTypeName=number

metric m:avg_saturday_rides p:float l:Avg_Saturday_Rides t:dataTypeName=number

metric m:avg_sunday_holiday_rides p:float l:Avg_Sunday-Holiday_Rides t:dataTypeName=number

metric m:monthtotal p:integer l:MonthTotal t:dataTypeName=number

entity e:bynn-gwxy l:"CTA - Ridership - Bus Routes - Monthly Day-Type Averages & Totals" t:attribution="Chicago Transit Authority" t:url=https://data.cityofchicago.org/api/views/bynn-gwxy

property e:bynn-gwxy t:meta.view v:id=bynn-gwxy v:category=Transportation v:attributionLink=http://www.transitchicago.com v:averageRating=0 v:name="CTA - Ridership - Bus Routes - Monthly Day-Type Averages & Totals" v:attribution="Chicago Transit Authority"

property e:bynn-gwxy t:meta.view.owner v:id=6bsn-5494 v:profileImageUrlMedium=/api/users/6bsn-5494/profile_images/THUMB v:profileImageUrlLarge=/api/users/6bsn-5494/profile_images/LARGE v:screenName="cta web" v:profileImageUrlSmall=/api/users/6bsn-5494/profile_images/TINY v:displayName="cta web"

property e:bynn-gwxy t:meta.view.tableauthor v:id=6bsn-5494 v:profileImageUrlMedium=/api/users/6bsn-5494/profile_images/THUMB v:profileImageUrlLarge=/api/users/6bsn-5494/profile_images/LARGE v:screenName="cta web" v:profileImageUrlSmall=/api/users/6bsn-5494/profile_images/TINY v:roleName=designer v:displayName="cta web"
```

## Top Records

```ls
| route | routename            | month_beginning     | avg_weekday_rides | avg_saturday_rides | avg_sunday_holiday_rides | monthtotal | 
| ===== | ==================== | =================== | ================= | ================== | ======================== | ========== | 
| 1     | Indiana/Hyde Park    | 2001-01-01T00:00:00 | 6982.6            | 0                  | 0                        | 153617     | 
| 2     | Hyde Park Express    | 2001-01-01T00:00:00 | 1000              | 0                  | 0                        | 22001      | 
| 3     | King Drive           | 2001-01-01T00:00:00 | 21406.5           | 13210.7            | 8725.3                   | 567413     | 
| 4     | Cottage Grove        | 2001-01-01T00:00:00 | 22432.2           | 17994              | 10662.2                  | 618796     | 
| 6     | Jackson Park Express | 2001-01-01T00:00:00 | 18443             | 13088.2            | 7165.6                   | 493926     | 
| 7     | Harrison             | 2001-01-01T00:00:00 | 5504.4            | 0                  | 0                        | 121097     | 
| 8     | Halsted              | 2001-01-01T00:00:00 | 19582.2           | 12420              | 8280.8                   | 521892     | 
| 8A    | South Halsted        | 2001-01-01T00:00:00 | 3196.5            | 3006.6             | 1336.2                   | 89030      | 
| 9     | Ashland              | 2001-01-01T00:00:00 | 29265.4           | 22621.7            | 15336.1                  | 811006     | 
| 10    | Museum of S & I      | 2001-01-01T00:00:00 | 0                 | 562.6              | 372.9                    | 4115       | 
```