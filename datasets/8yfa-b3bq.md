# Austintexas.gov - Top 50 Pages By Pageviews

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/austintexas-gov-top-50-pages-by-pageviews) |
| Metadata | [Link](https://data.austintexas.gov/api/views/8yfa-b3bq) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/8yfa-b3bq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/8yfa-b3bq/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 8yfa-b3bq |
| Name | Austintexas.gov - Top 50 Pages By Pageviews |
| Attribution | City of Austin |
| Tags | austintexas.gov, popular pages, percent exit, bounce rate, entrances, average time on page, unique pageviews, pageviews |
| Created | 2015-04-21T15:45:40Z |
| Publication Date | 2017-04-07T20:55:08Z |

## Description

This data, exported from Google Analytics displays the most popular 50 pages on Austintexas.gov based on the following: 
Pageviews: The total number of times the page was viewed. Repeated views of a single page are counted.
Unique Pageviews: The number of visits during which the specified page was viewed at least once. A unique pageview is counted for each page URL + page Title combination.
Average Time on Page: The average amount of time users spent viewing a specified page or screen, or set of pages or screens.
Entrances: The number of times visitors entered your site through a specified page or set of pages.
Bounce Rate: The percentage of single-page visits (i.e. visits in which the person left your site from the entrance page without interacting with the page).
Percent Exit: (number of exits) / (number of pageviews) for the page or set of pages. It indicates how often users exit from that page or set of pages when they view the page(s). This demonstrates the top 50 pages for a three-month period.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name              | Data Type | Render Type |
| ======== | ============== | ================ | ================= | ========= | =========== |
| No       | time           | :updated_at      | updated_at        | meta_data | meta_data   |
| Yes      | series tag     | page             | Page              | url       | url         |
| Yes      | numeric metric | pageviews        | Pageviews         | number    | text        |
| Yes      | numeric metric | unique_pageviews | Unique Pageviews  | number    | text        |
| Yes      | series tag     | avg_time_on_page | Avg. Time on Page | text      | text        |
| Yes      | numeric metric | entrances        | Entrances         | number    | text        |
| Yes      | numeric metric | bounce_rate      | Bounce Rate       | percent   | percent     |
| Yes      | numeric metric | exit             | % Exit            | percent   | percent     |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:8yfa-b3bq d:2017-04-07T20:54:50.000Z t:avg_time_on_page=0:01:33 t:page=http://austintexas.gov/ m:entrances=145559 m:pageviews=212584 m:unique_pageviews=171097 m:exit=52.19 m:bounce_rate=58.75

series e:8yfa-b3bq d:2017-04-07T20:54:50.000Z t:avg_time_on_page=0:00:30 t:page="http://austintexas.gov/web/permit/public-search-other?p_p_id=SmartPortletJSR286_WAR_smartlets_INSTANCE_chpyJJVwH9kC&p_p_lifecycle=1&p_p_state=normal&p_p_mode=view&p_p_col_id=column-1&p_p_col_count=1" m:entrances=4624 m:pageviews=193299 m:unique_pageviews=35564 m:exit=5.39 m:bounce_rate=15.86

series e:8yfa-b3bq d:2017-04-07T20:54:50.000Z t:avg_time_on_page=0:00:33 t:page="http://austintexas.gov/web/permit/folder-select?p_p_id=SmartPortletJSR286_WAR_smartlets_INSTANCE_r7TftPdFzOLO&p_p_lifecycle=1&p_p_state=normal&p_p_mode=view&p_p_col_id=column-1&p_p_col_count=1" m:entrances=1189 m:pageviews=70403 m:unique_pageviews=12165 m:exit=4.51 m:bounce_rate=9
```

## Meta Commands

```ls
metric m:pageviews p:long l:Pageviews t:dataTypeName=number

metric m:unique_pageviews p:long l:"Unique Pageviews" t:dataTypeName=number

metric m:entrances p:long l:Entrances t:dataTypeName=number

metric m:bounce_rate p:float l:"Bounce Rate" t:dataTypeName=percent

metric m:exit p:float l:"% Exit" t:dataTypeName=percent

entity e:8yfa-b3bq l:"Austintexas.gov  - Top 50 Pages By Pageviews" t:attribution="City of Austin" t:url=https://data.austintexas.gov/api/views/8yfa-b3bq

property e:8yfa-b3bq t:meta.view v:id=8yfa-b3bq v:attributionLink=http://www.google.com/analytics v:averageRating=0 v:name="Austintexas.gov  - Top 50 Pages By Pageviews" v:attribution="City of Austin"

property e:8yfa-b3bq t:meta.view.license v:name="Public Domain"

property e:8yfa-b3bq t:meta.view.owner v:id=czye-wfgc v:profileImageUrlMedium=/api/users/czye-wfgc/profile_images/THUMB v:profileImageUrlLarge=/api/users/czye-wfgc/profile_images/LARGE v:screenName=AustinGo v:profileImageUrlSmall=/api/users/czye-wfgc/profile_images/TINY v:displayName=AustinGo

property e:8yfa-b3bq t:meta.view.tableauthor v:id=czye-wfgc v:profileImageUrlMedium=/api/users/czye-wfgc/profile_images/THUMB v:profileImageUrlLarge=/api/users/czye-wfgc/profile_images/LARGE v:screenName=AustinGo v:profileImageUrlSmall=/api/users/czye-wfgc/profile_images/TINY v:roleName=publisher v:displayName=AustinGo
```

## Top Records

```ls
| :updated_at | page                                                                                                                                                                                                           | pageviews | unique_pageviews | avg_time_on_page | entrances | bounce_rate | exit  | 
| =========== | ============================================================================================================================================================================================================== | ========= | ================ | ================ | ========= | =========== | ===== | 
| 1491598490  | [http://austintexas.gov/, null]                                                                                                                                                                                | 212,584   | 171,097          | 0:01:33          | 145,559   | 58.75       | 52.19 | 
| 1491598490  | [http://austintexas.gov/web/permit/public-search-other?p_p_id=SmartPortletJSR286_WAR_smartlets_INSTANCE_chpyJJVwH9kC&p_p_lifecycle=1&p_p_state=normal&p_p_mode=view&p_p_col_id=column-1&p_p_col_count=1, null] | 193,299   | 35,564           | 0:00:30          | 4,624     | 15.86       | 5.39  | 
| 1491598490  | [http://austintexas.gov/web/permit/folder-select?p_p_id=SmartPortletJSR286_WAR_smartlets_INSTANCE_r7TftPdFzOLO&p_p_lifecycle=1&p_p_state=normal&p_p_mode=view&p_p_col_id=column-1&p_p_col_count=1, null]       | 70,403    | 12,165           | 0:00:33          | 1,189     | 9.00        | 4.51  | 
| 1491598490  | [http://austintexas.gov/web/permit/folder-select?reset=true, null]                                                                                                                                             | 61,763    | 27,704           | 0:00:39          | 3,306     | 9.44        | 6.29  | 
| 1491598490  | [http://austintexas.gov/department/barton-springs-pool, null]                                                                                                                                                  | 42,950    | 34,850           | 0:02:41          | 32,291    | 70.48       | 67.89 | 
| 1491598490  | [http://austintexas.gov/department/aac, null]                                                                                                                                                                  | 42,204    | 30,205           | 0:00:30          | 27,369    | 10.04       | 15.25 | 
| 1491598490  | [http://austintexas.gov/adoptablepets, null]                                                                                                                                                                   | 39,184    | 30,028           | 0:04:05          | 13,162    | 63.94       | 65.05 | 
| 1491598490  | [http://austintexas.gov/web/permit/public-search-other, null]                                                                                                                                                  | 35,917    | 27,490           | 0:00:45          | 19,657    | 9.66        | 8.50  | 
| 1491598490  | [http://austintexas.gov/pay_online, null]                                                                                                                                                                      | 32,574    | 17,206           | 0:00:35          | 3,962     | 19.86       | 15.54 | 
| 1491598490  | [http://austintexas.gov/airport, null]                                                                                                                                                                         | 28,373    | 22,751           | 0:00:58          | 20,977    | 26.85       | 36.72 | 
```