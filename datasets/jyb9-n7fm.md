# CTA - Ridership - Bus Routes - Daily Totals by Route

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cta-ridership-bus-routes-daily-totals-by-route-bbc83) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/jyb9-n7fm) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/jyb9-n7fm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/jyb9-n7fm/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | jyb9-n7fm |
| Name | CTA - Ridership - Bus Routes - Daily Totals by Route |
| Attribution | Chicago Transit Authority |
| Category | Transportation |
| Tags | cta, public transit, ridership, sustainability, chicago transit authority |
| Created | 2011-08-05T19:35:20Z |
| Publication Date | 2017-02-16T23:52:24Z |

## Description

This dataset shows total daily ridership on a per-route basis dating back to 2001. Daytypes are as follows: W=Weekday, A=Saturday, U=Sunday/Holiday. See attached readme file for more detailed information.

## Columns

```ls
| Included | Schema Type    | Field Name | Name    | Data Type     | Render Type   |
| ======== | ============== | ========== | ======= | ============= | ============= |
| Yes      | series tag     | route      | route   | text          | text          |
| Yes      | time           | date       | date    | calendar_date | calendar_date |
| Yes      | series tag     | daytype    | daytype | text          | text          |
| Yes      | numeric metric | rides      | rides   | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:jyb9-n7fm d:2001-01-01T00:00:00.000Z t:route=3 t:daytype=U m:rides=7354

series e:jyb9-n7fm d:2001-01-01T00:00:00.000Z t:route=4 t:daytype=U m:rides=9288

series e:jyb9-n7fm d:2001-01-01T00:00:00.000Z t:route=6 t:daytype=U m:rides=6048
```

## Meta Commands

```ls
metric m:rides p:integer l:rides t:dataTypeName=number

entity e:jyb9-n7fm l:"CTA - Ridership - Bus Routes - Daily Totals by Route" t:attribution="Chicago Transit Authority" t:url=https://data.cityofchicago.org/api/views/jyb9-n7fm

property e:jyb9-n7fm t:meta.view v:id=jyb9-n7fm v:category=Transportation v:attributionLink=http://www.transitchicago.com v:averageRating=0 v:name="CTA - Ridership - Bus Routes - Daily Totals by Route" v:attribution="Chicago Transit Authority"

property e:jyb9-n7fm t:meta.view.owner v:id=6bsn-5494 v:profileImageUrlMedium=/api/users/6bsn-5494/profile_images/THUMB v:profileImageUrlLarge=/api/users/6bsn-5494/profile_images/LARGE v:screenName="cta web" v:profileImageUrlSmall=/api/users/6bsn-5494/profile_images/TINY v:displayName="cta web"

property e:jyb9-n7fm t:meta.view.tableauthor v:id=6bsn-5494 v:profileImageUrlMedium=/api/users/6bsn-5494/profile_images/THUMB v:profileImageUrlLarge=/api/users/6bsn-5494/profile_images/LARGE v:screenName="cta web" v:profileImageUrlSmall=/api/users/6bsn-5494/profile_images/TINY v:roleName=designer v:displayName="cta web"
```

## Top Records

```ls
| route | date                | daytype | rides | 
| ===== | =================== | ======= | ===== | 
| 3     | 2001-01-01T00:00:00 | U       | 7354  | 
| 4     | 2001-01-01T00:00:00 | U       | 9288  | 
| 6     | 2001-01-01T00:00:00 | U       | 6048  | 
| 8     | 2001-01-01T00:00:00 | U       | 6309  | 
| 9     | 2001-01-01T00:00:00 | U       | 11207 | 
| 10    | 2001-01-01T00:00:00 | U       | 385   | 
| 11    | 2001-01-01T00:00:00 | U       | 610   | 
| 12    | 2001-01-01T00:00:00 | U       | 3678  | 
| 18    | 2001-01-01T00:00:00 | U       | 375   | 
| 20    | 2001-01-01T00:00:00 | U       | 7096  | 
```