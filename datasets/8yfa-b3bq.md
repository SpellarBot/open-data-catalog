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
| Publication Date | 2017-01-09T18:16:53Z |
| Rows Updated | 2017-01-09T18:16:40Z |

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
series e:8yfa-b3bq d:2017-01-09T18:16:32.000Z t:avg_time_on_page=0:01:34 t:page=http://www.austintexas.gov/ m:entrances=380306 m:pageviews=547656 m:unique_pageviews=439779 m:exit=51.1 m:bounce_rate=56.4

series e:8yfa-b3bq d:2017-01-09T18:16:32.000Z t:avg_time_on_page=0:00:28 t:page="http://www.austintexas.gov/web/permit/public-search-other?p_p_id=SmartPortletJSR286_WAR_smartlets_INSTANCE_chpyJJVwH9kC&p_p_lifecycle=1&p_p_state=normal&p_p_mode=view&p_p_col_id=column-1&p_p_col_count=1" m:entrances=3310 m:pageviews=164537 m:unique_pageviews=31025 m:exit=5.29 m:bounce_rate=15.65

series e:8yfa-b3bq d:2017-01-09T18:16:32.000Z t:avg_time_on_page=0:03:38 t:page=http://www.austintexas.gov/adoptablepets m:entrances=50425 m:pageviews=149008 m:unique_pageviews=105224 m:exit=59.05 m:bounce_rate=60.7
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