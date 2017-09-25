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
| Category | City Government |
| Tags | austintexas.gov, popular pages, percent exit, bounce rate, entrances, average time on page, unique pageviews, pageviews |
| Created | 2015-04-21T15:45:40Z |
| Publication Date | 2017-07-07T16:29:10Z |

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
series e:8yfa-b3bq d:2017-07-07T16:28:54.000Z t:avg_time_on_page=0:01:34 t:page=http://austintexas.gov/ m:exit=51.72 m:pageviews=591385 m:unique_pageviews=474794 m:bounce_rate=58.34 m:entrances=403277

series e:8yfa-b3bq d:2017-07-07T16:28:54.000Z t:avg_time_on_page=0:00:31 t:page="http://austintexas.gov/web/permit/public-search-other?p_p_id=SmartPortletJSR286_WAR_smartlets_INSTANCE_chpyJJVwH9kC&p_p_lifecycle=1&p_p_state=normal&p_p_mode=view&p_p_col_id=column-1&p_p_col_count=1" m:exit=5.68 m:pageviews=527221 m:unique_pageviews=100454 m:bounce_rate=17.1 m:entrances=13470

series e:8yfa-b3bq d:2017-07-07T16:28:54.000Z t:avg_time_on_page=0:00:34 t:page="http://austintexas.gov/web/permit/folder-select?p_p_id=SmartPortletJSR286_WAR_smartlets_INSTANCE_r7TftPdFzOLO&p_p_lifecycle=1&p_p_state=normal&p_p_mode=view&p_p_col_id=column-1&p_p_col_count=1" m:exit=4.62 m:pageviews=215145 m:unique_pageviews=36630 m:bounce_rate=9.01 m:entrances=3373
```

## Meta Commands

```ls
metric m:pageviews p:long l:Pageviews t:dataTypeName=number

metric m:unique_pageviews p:long l:"Unique Pageviews" t:dataTypeName=number

metric m:entrances p:long l:Entrances t:dataTypeName=number

metric m:bounce_rate p:float l:"Bounce Rate" t:dataTypeName=percent

metric m:exit p:float l:"% Exit" t:dataTypeName=percent

entity e:8yfa-b3bq l:"Austintexas.gov  - Top 50 Pages By Pageviews" t:attribution="City of Austin" t:url=https://data.austintexas.gov/api/views/8yfa-b3bq

property e:8yfa-b3bq t:meta.view d:2017-09-25T07:23:27.308Z v:averageRating=0 v:name="Austintexas.gov  - Top 50 Pages By Pageviews" v:attribution="City of Austin" v:attributionLink=http://www.google.com/analytics v:id=8yfa-b3bq v:category="City Government"

property e:8yfa-b3bq t:meta.view.license d:2017-09-25T07:23:27.308Z v:name="Public Domain"

property e:8yfa-b3bq t:meta.view.owner d:2017-09-25T07:23:27.308Z v:displayName=AustinGo v:profileImageUrlLarge=/api/users/czye-wfgc/profile_images/LARGE v:profileImageUrlSmall=/api/users/czye-wfgc/profile_images/TINY v:id=czye-wfgc v:screenName=AustinGo v:profileImageUrlMedium=/api/users/czye-wfgc/profile_images/THUMB

property e:8yfa-b3bq t:meta.view.tableauthor d:2017-09-25T07:23:27.308Z v:displayName=AustinGo v:profileImageUrlLarge=/api/users/czye-wfgc/profile_images/LARGE v:roleName=publisher v:profileImageUrlSmall=/api/users/czye-wfgc/profile_images/TINY v:id=czye-wfgc v:screenName=AustinGo v:profileImageUrlMedium=/api/users/czye-wfgc/profile_images/THUMB
```

## Top Records

```ls
| :updated_at | page                                                                                                                                                                                                           | pageviews | unique_pageviews | avg_time_on_page | entrances | bounce_rate | exit  | 
| =========== | ============================================================================================================================================================================================================== | ========= | ================ | ================ | ========= | =========== | ===== | 
| 1499444934  | [http://austintexas.gov/, null]                                                                                                                                                                                | 591,385   | 474,794          | 0:01:34          | 403,277   | 58.34       | 51.72 | 
| 1499444934  | [http://austintexas.gov/web/permit/public-search-other?p_p_id=SmartPortletJSR286_WAR_smartlets_INSTANCE_chpyJJVwH9kC&p_p_lifecycle=1&p_p_state=normal&p_p_mode=view&p_p_col_id=column-1&p_p_col_count=1, null] | 527,221   | 100,454          | 0:00:31          | 13,470    | 17.10       | 5.68  | 
| 1499444934  | [http://austintexas.gov/web/permit/folder-select?p_p_id=SmartPortletJSR286_WAR_smartlets_INSTANCE_r7TftPdFzOLO&p_p_lifecycle=1&p_p_state=normal&p_p_mode=view&p_p_col_id=column-1&p_p_col_count=1, null]       | 215,145   | 36,630           | 0:00:34          | 3,373     | 9.01        | 4.62  | 
| 1499444934  | [http://austintexas.gov/department/barton-springs-pool, null]                                                                                                                                                  | 187,876   | 153,209          | 0:03:02          | 143,139   | 72.04       | 69.38 | 
| 1499444934  | [http://austintexas.gov/web/permit/folder-select?reset=true, null]                                                                                                                                             | 185,292   | 83,583           | 0:00:39          | 10,212    | 8.48        | 6.17  | 
| 1499444934  | [http://austintexas.gov/department/aac, null]                                                                                                                                                                  | 142,161   | 103,370          | 0:00:31          | 94,019    | 10.33       | 15.09 | 
| 1499444934  | [http://austintexas.gov/adoptablepets, null]                                                                                                                                                                   | 137,724   | 101,944          | 0:04:00          | 41,979    | 64.14       | 63.33 | 
| 1499444934  | [http://austintexas.gov/web/permit/public-search-other, null]                                                                                                                                                  | 98,825    | 76,033           | 0:00:46          | 54,920    | 9.19        | 8.24  | 
| 1499444934  | [http://austintexas.gov/department/animal-adoption, null]                                                                                                                                                      | 92,267    | 69,707           | 0:00:28          | 3,150     | 42.91       | 7.52  | 
| 1499444934  | [http://austintexas.gov/pay_online, null]                                                                                                                                                                      | 89,848    | 47,839           | 0:00:35          | 10,590    | 21.44       | 15.94 | 
```