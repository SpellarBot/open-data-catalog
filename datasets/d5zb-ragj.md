# NYC.gov Web Analytics

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nyc-gov-web-analytics) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/d5zb-ragj) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/d5zb-ragj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/d5zb-ragj/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | d5zb-ragj |
| Name | NYC.gov Web Analytics |
| Attribution | Department of Information Technology & Telecommunications (DoITT) |
| Category | City Government |
| Created | 2015-08-06T14:56:56Z |
| Publication Date | 2016-11-30T23:20:35Z |

## Description

Web traffic statistics for the top 2000 most visited pages on nyc.gov by month.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name                          | Data Type | Render Type |
| ======== | ============== | ================= | ============================= | ========= | =========== |
| No       | time           | :updated_at       | updated_at                    | meta_data | meta_data   |
| No       |                | time_period       | Time Period                   | text      | text        |
| Yes      | series tag     | page              | Page                          | url       | url         |
| Yes      | series tag     | title             | Title                         | text      | text        |
| Yes      | numeric metric | visits            | Visits                        | number    | number      |
| Yes      | numeric metric | page_views        | Views                         | number    | number      |
| Yes      | numeric metric | avg_view_time_sec | Average Time Viewed (seconds) | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = time_period
```

## Data Commands

```ls
series e:d5zb-ragj d:2016-03-07T14:57:53.000Z m:page_views=23123911 m:avg_view_time_sec=96.5

series e:d5zb-ragj d:2016-03-07T14:57:53.000Z t:title="Welcome to NYC.gov | City of New York" t:page=http://www1.nyc.gov/ m:page_views=715124 m:visits=551941 m:avg_view_time_sec=68.02

series e:d5zb-ragj d:2016-03-07T14:57:53.000Z t:title="Pay Online Now" t:page=http://www1.nyc.gov/site/finance/pay-now/online.page m:page_views=903463 m:visits=470528 m:avg_view_time_sec=41.9
```

## Meta Commands

```ls
metric m:visits p:integer l:Visits d:"A visit is a series of page views, beginning when a visitor?s browser requests the first page from the server, and ending when the visitor leaves the site or remains idle beyond the idle-time limit." t:dataTypeName=number

metric m:page_views p:integer l:Views d:"A page that is displayed by a browser. This term is often used loosely to include page files that are delivered to a browser, whether or not they are displayed on the screen. An example of a page view that is not actually displayed is a redirect page." t:dataTypeName=number

metric m:avg_view_time_sec p:double l:"Average Time Viewed (seconds)" t:dataTypeName=number

entity e:d5zb-ragj l:"NYC.gov Web Analytics" t:attribution="Department of Information Technology & Telecommunications (DoITT)" t:url=https://data.cityofnewyork.us/api/views/d5zb-ragj

property e:d5zb-ragj t:meta.view v:id=d5zb-ragj v:category="City Government" v:averageRating=0 v:name="NYC.gov Web Analytics" v:attribution="Department of Information Technology & Telecommunications (DoITT)"

property e:d5zb-ragj t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:d5zb-ragj t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | time_period | page                                                                               | title                                                        | visits | page_views | avg_view_time_sec  | 
| =========== | =========== | ================================================================================== | ============================================================ | ====== | ========== | ================== | 
| 1457362673  | Jul-15      | [null, null]                                                                       |                                                              |        | 23123911   | 96.5               | 
| 1457362673  | Jul-15      | [http://www1.nyc.gov/, null]                                                       | Welcome to NYC.gov | City of New York                        | 551941 | 715124     | 68.02              | 
| 1457362673  | Jul-15      | [http://www1.nyc.gov/site/finance/pay-now/online.page, null]                       | Pay Online Now                                               | 470528 | 903463     | 41.9               | 
| 1457362673  | Jul-15      | [http://www1.nyc.gov/assets/finance/jump/pay_parking_camera_violations.html, null] | Pay Parking and Camera Violations Online                     | 361846 | 548096     | 313                | 
| 1457362673  | Jul-15      | [http://www.nyc.gov/html/dob/html/home/home.shtml, null]                           | Department of Buildings                                      | 321598 | 589963     | 193.77             | 
| 1457362673  | Jul-15      | [http://www1.nyc.gov/site/finance/, null]                                          | NYC Department of Finance                                    | 296965 | 410435     | 75.41              | 
| 1457362673  | Jul-15      | [http://www1.nyc.gov/jobs/, null]                                                  | Jobs | City of New York                                      | 219977 | 536295     | 129.61000000000001 | 
| 1457362673  | Jul-15      | [http://www.nyc.gov/html/dcas/html/work/exam_monthly.shtml, null]                  | DCAS - Work for the City - DCAS Monthly Exam Schedule        | 216068 | 400999     | 145.88             | 
| 1457362673  | Jul-15      | [http://www1.nyc.gov/home/search/, null]                                           | Search Results | City of New York                            | 180387 | 469624     | 30.52              | 
| 1457362673  | Jul-15      | [http://www.nyc.gov/html/dob/html/bis/bis.shtml, null]                             | Department of Buildings - Buildings Information System (BIS) | 152489 | 254334     | 245.17             | 
```