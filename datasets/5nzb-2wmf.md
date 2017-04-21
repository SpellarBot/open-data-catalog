# COS-Statistics-Gov-Domains-Only

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-of-seattle-webstats-pageviews-by-top-level-domains-1caa9) |
| Metadata | [Link](https://data.seattle.gov/api/views/5nzb-2wmf) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/5nzb-2wmf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/5nzb-2wmf/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | 5nzb-2wmf |
| Name | COS-Statistics-Gov-Domains-Only |
| Attribution | City of Seattle |
| Category | City Business |
| Tags | google, webstats, nre, census-okfn |
| Created | 2015-07-17T20:50:51Z |
| Publication Date | 2015-07-17T20:52:11Z |

## Description

Google Analytics counts for *.seattle.gov domains, non seattle.gov domains managed by the city are added in as the numbers are available. 5nzb-2wmf Content Drill-down from UA report by month.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type     | Render Type   |
| ======== | ============== | ==================== | ==================== | ============= | ============= |
| Yes      | series tag     | domain               | domain               | text          | text          |
| Yes      | numeric metric | pageviews            | pageviews            | number        | number        |
| Yes      | numeric metric | unique_pageviews     | unique-pageviews     | number        | number        |
| Yes      | series tag     | average_time_on_page | average-time-on-page | text          | text          |
| Yes      | numeric metric | bounce_rate          | bounce-rate          | percent       | percent       |
| Yes      | numeric metric | exit_percent         | exit-percent         | percent       | percent       |
| Yes      | time           | month                | month                | calendar_date | calendar_date |
```

## Time Field

```ls
Value = month
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:5nzb-2wmf d:2015-04-01T00:00:00.000Z t:average_time_on_page=0:01:19 t:domain=www.seattle.gov/ m:exit_percent=36.53 m:pageviews=3525737 m:unique_pageviews=2689843 m:bounce_rate=50.86

series e:5nzb-2wmf d:2015-04-01T00:00:00.000Z t:average_time_on_page=0:01:12 t:domain=www2.seattle.gov/ m:exit_percent=4.53 m:pageviews=2158182 m:unique_pageviews=125984 m:bounce_rate=41.69

series e:5nzb-2wmf d:2015-04-01T00:00:00.000Z t:average_time_on_page=0:01:18 t:domain=web6.seattle.gov/ m:exit_percent=23.23 m:pageviews=367871 m:unique_pageviews=204803 m:bounce_rate=40.66
```

## Meta Commands

```ls
metric m:pageviews p:integer l:pageviews t:dataTypeName=number

metric m:unique_pageviews p:integer l:unique-pageviews t:dataTypeName=number

metric m:bounce_rate p:double l:bounce-rate t:dataTypeName=percent

metric m:exit_percent p:double l:exit-percent t:dataTypeName=percent

entity e:5nzb-2wmf l:COS-Statistics-Gov-Domains-Only t:attribution="City of Seattle" t:url=https://data.seattle.gov/api/views/5nzb-2wmf

property e:5nzb-2wmf t:meta.view v:id=5nzb-2wmf v:category="City Business" v:attributionLink=http://www.seattle.gov/ v:averageRating=0 v:name=COS-Statistics-Gov-Domains-Only v:attribution="City of Seattle"

property e:5nzb-2wmf t:meta.view.license v:name="Public Domain"

property e:5nzb-2wmf t:meta.view.owner v:id=seg8-ihrf v:profileImageUrlMedium=/api/users/seg8-ihrf/profile_images/THUMB v:profileImageUrlLarge=/api/users/seg8-ihrf/profile_images/LARGE v:screenName="Eckstine, Nate" v:profileImageUrlSmall=/api/users/seg8-ihrf/profile_images/TINY v:displayName="Eckstine, Nate"

property e:5nzb-2wmf t:meta.view.tableauthor v:id=seg8-ihrf v:profileImageUrlMedium=/api/users/seg8-ihrf/profile_images/THUMB v:profileImageUrlLarge=/api/users/seg8-ihrf/profile_images/LARGE v:screenName="Eckstine, Nate" v:profileImageUrlSmall=/api/users/seg8-ihrf/profile_images/TINY v:roleName=administrator v:displayName="Eckstine, Nate"
```

## Top Records

```ls
| domain                  | pageviews | unique_pageviews | average_time_on_page | bounce_rate | exit_percent | month               | 
| ======================= | ========= | ================ | ==================== | =========== | ============ | =================== | 
| www.seattle.gov/        | 3525737   | 2689843          | 0:01:19              | 50.86       | 36.53        | 2015-04-01T00:00:00 | 
| www2.seattle.gov/       | 2158182   | 125984           | 0:01:12              | 41.69       | 4.53         | 2015-04-01T00:00:00 | 
| web6.seattle.gov/       | 367871    | 204803           | 0:01:18              | 40.66       | 23.23        | 2015-04-01T00:00:00 | 
| spdblotter.seattle.gov/ | 117645    | 91076            | 0:01:14              | 69.29       | 46.42        | 2015-04-01T00:00:00 | 
| web1.seattle.gov/       | 79529     | 32258            | 0:01:09              | 59.57       | 18.76        | 2015-04-01T00:00:00 | 
| find.seattle.gov/       | 78611     | 62516            | 0:00:39              | 25.67       | 21.74        | 2015-04-01T00:00:00 | 
| clerk.seattle.gov/      | 33035     | 11166            | 0:01:12              | 49.03       | 19.43        | 2015-04-01T00:00:00 | 
| sdotblog.seattle.gov/   | 7286      | 5747             | 0:02:53              | 72.84       | 56.59        | 2015-04-01T00:00:00 | 
| fireline.seattle.gov/   | 6647      | 5489             | 0:01:32              | 79.28       | 60.00        | 2015-04-01T00:00:00 | 
| parkways.seattle.gov/   | 6457      | 5581             | 0:02:00              | 69.75       | 49.74        | 2015-04-01T00:00:00 | 
```