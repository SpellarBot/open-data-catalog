# COS-Statistics-Mobile Sessions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-of-seattle-webstats-mobile-sessions) |
| Metadata | [Link](https://data.seattle.gov/api/views/2u47-byfn) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/2u47-byfn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/2u47-byfn/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | 2u47-byfn |
| Name | COS-Statistics-Mobile Sessions |
| Attribution | City of Seattle |
| Category | City Business |
| Tags | google, mobile, nre, stats, census-okfn, gatc |
| Created | 2015-07-20T20:57:51Z |
| Publication Date | 2015-07-20T21:00:00Z |

## Description

Mobile Sessions by Operating System from Google Analytics. By Month. 2u47-byfn

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type     | Render Type   |
| ======== | ============== | ================== | ================== | ============= | ============= |
| Yes      | series tag     | operating_system   | Operating_System   | text          | text          |
| Yes      | numeric metric | sessions           | Sessions           | number        | number        |
| Yes      | numeric metric | new_sessions       | New_Sessions       | percent       | percent       |
| Yes      | numeric metric | new_users          | New_Users          | number        | number        |
| Yes      | numeric metric | bounce_rate        | Bounce_Rate        | percent       | percent       |
| Yes      | numeric metric | pagespersession    | PagesPerSession    | number        | number        |
| Yes      | series tag     | avgsessionduration | AvgSessionDuration | text          | text          |
| Yes      | time           | month              | Month              | calendar_date | calendar_date |
```

## Time Field

```ls
Value = month
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:2u47-byfn d:2015-01-01T00:00:00.000Z t:avgsessionduration=0:02:11 t:operating_system=iOS m:new_sessions=47.75 m:new_users=158674 m:sessions=332291 m:pagespersession=2.34 m:bounce_rate=60.79

series e:2u47-byfn d:2015-01-01T00:00:00.000Z t:avgsessionduration=0:03:53 t:operating_system=Android m:new_sessions=45.53 m:new_users=77453 m:sessions=170107 m:pagespersession=2.98 m:bounce_rate=58.14

series e:2u47-byfn d:2015-01-01T00:00:00.000Z t:avgsessionduration=0:02:40 t:operating_system=Windows m:new_sessions=44.76 m:new_users=12231 m:sessions=27325 m:pagespersession=3.26 m:bounce_rate=44.6
```

## Meta Commands

```ls
metric m:sessions p:integer l:Sessions t:dataTypeName=number

metric m:new_sessions p:float l:New_Sessions t:dataTypeName=percent

metric m:new_users p:integer l:New_Users t:dataTypeName=number

metric m:bounce_rate p:float l:Bounce_Rate t:dataTypeName=percent

metric m:pagespersession p:double l:PagesPerSession t:dataTypeName=number

entity e:2u47-byfn l:"COS-Statistics-Mobile Sessions" t:attribution="City of Seattle" t:url=https://data.seattle.gov/api/views/2u47-byfn

property e:2u47-byfn t:meta.view v:id=2u47-byfn v:category="City Business" v:attributionLink=http://www.seattle.gov/ v:averageRating=0 v:name="COS-Statistics-Mobile Sessions" v:attribution="City of Seattle"

property e:2u47-byfn t:meta.view.license v:name="Public Domain"

property e:2u47-byfn t:meta.view.owner v:id=seg8-ihrf v:profileImageUrlMedium=/api/users/seg8-ihrf/profile_images/THUMB v:profileImageUrlLarge=/api/users/seg8-ihrf/profile_images/LARGE v:screenName="Eckstine, Nate" v:profileImageUrlSmall=/api/users/seg8-ihrf/profile_images/TINY v:displayName="Eckstine, Nate"

property e:2u47-byfn t:meta.view.tableauthor v:id=seg8-ihrf v:profileImageUrlMedium=/api/users/seg8-ihrf/profile_images/THUMB v:profileImageUrlLarge=/api/users/seg8-ihrf/profile_images/LARGE v:screenName="Eckstine, Nate" v:profileImageUrlSmall=/api/users/seg8-ihrf/profile_images/TINY v:roleName=administrator v:displayName="Eckstine, Nate"
```

## Top Records

```ls
| operating_system | sessions | new_sessions | new_users | bounce_rate | pagespersession | avgsessionduration | month               | 
| ================ | ======== | ============ | ========= | =========== | =============== | ================== | =================== | 
| iOS              | 332291   | 47.75        | 158674    | 60.79       | 2.34            | 0:02:11            | 2015-01-01T00:00:00 | 
| Android          | 170107   | 45.53        | 77453     | 58.14       | 2.98            | 0:03:53            | 2015-01-01T00:00:00 | 
| Windows          | 27325    | 44.76        | 12231     | 44.60       | 3.26            | 0:02:40            | 2015-01-01T00:00:00 | 
| Windows Phone    | 10109    | 45.71        | 4621      | 59.01       | 2.14            | 0:01:45            | 2015-01-01T00:00:00 | 
| BlackBerry       | 1375     | 39.27        | 540       | 62.98       | 2.1             | 0:02:24            | 2015-01-01T00:00:00 | 
| (not set)        | 408      | 83.09        | 339       | 72.30       | 1.82            | 0:01:01            | 2015-01-01T00:00:00 | 
| Series40         | 151      | 91.39        | 138       | 66.23       | 1.37            | 0:00:09            | 2015-01-01T00:00:00 | 
| Samsung          | 44       | 86.36        | 38        | 56.82       | 1.57            | 0:00:20            | 2015-01-01T00:00:00 | 
| Nokia            | 25       | 100.00       | 25        | 100.00      | 1               | 0:00:00            | 2015-01-01T00:00:00 | 
| LG               | 13       | 100.00       | 13        | 46.15       | 1.92            | 0:02:52            | 2015-01-01T00:00:00 | 
```