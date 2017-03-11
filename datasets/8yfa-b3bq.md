# Austintexas.gov - Top 50 Pages By Pageviews

## Dataset

* [Dataset URL](https://data.austintexas.gov/api/views/8yfa-b3bq/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/austintexas-gov-top-50-pages-by-pageviews)
* [Metadata URL](https://data.austintexas.gov/api/views/8yfa-b3bq)
* Id = 8yfa-b3bq
* Name = Austintexas.gov - Top 50 Pages By Pageviews
* Attribution = City of Austin
* [Attribution Link](http://www.google.com/analytics)
* Tags = [austintexas.gov, popular pages, percent exit, bounce rate, entrances, average time on page, unique pageviews, pageviews]
* Created = 2015-04-21T15:45:40Z
* Publication Date = 2017-01-09T18:16:53Z
* Rows Updated = 2017-01-09T18:16:40Z

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
| Name              | Field Name       | Data Type | Render Type | Schema Type    | Included | 
| ================= | ================ | ========= | =========== | ============== | ======== | 
| updated_at        | :updated_at      | meta_data | meta_data   | time           | No       | 
| Page              | page             | url       | url         | series tag     | Yes      | 
| Pageviews         | pageviews        | number    | text        | numeric metric | Yes      | 
| Unique Pageviews  | unique_pageviews | number    | text        | numeric metric | Yes      | 
| Avg. Time on Page | avg_time_on_page | text      | text        | series tag     | Yes      | 
| Entrances         | entrances        | number    | text        | numeric metric | Yes      | 
| Bounce Rate       | bounce_rate      | percent   | percent     | numeric metric | Yes      | 
| % Exit            | exit             | percent   | percent     | numeric metric | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls
series e:8yfa-b3bq d:2017-01-09T18:16:32.000Z t:avg_time_on_page=0:01:34 m:entrances=380306 m:pageviews=547656 m:unique_pageviews=439779 m:exit=51.1 m:bounce_rate=56.4

series e:8yfa-b3bq d:2017-01-09T18:16:32.000Z t:avg_time_on_page=0:00:28 m:entrances=3310 m:pageviews=164537 m:unique_pageviews=31025 m:exit=5.29 m:bounce_rate=15.65

series e:8yfa-b3bq d:2017-01-09T18:16:32.000Z t:avg_time_on_page=0:03:38 m:entrances=50425 m:pageviews=149008 m:unique_pageviews=105224 m:exit=59.05 m:bounce_rate=60.7
```

## Meta Commands

```ls
metric m:pageviews l:Pageviews t:dataTypeName=number

metric m:unique_pageviews l:"Unique Pageviews" t:dataTypeName=number

metric m:entrances l:Entrances t:dataTypeName=number

entity e:8yfa-b3bq l:"Austintexas.gov  - Top 50 Pages By Pageviews" t:attribution="City of Austin" t:url=https://data.austintexas.gov/api/views/8yfa-b3bq

property e:8yfa-b3bq t:meta.view d:2017-03-08T02:24:00.362Z v:id=8yfa-b3bq v:attributionLink=http://www.google.com/analytics v:averageRating=0 v:name="Austintexas.gov  - Top 50 Pages By Pageviews" v:attribution="City of Austin"

property e:8yfa-b3bq t:meta.view.license d:2017-03-08T02:24:00.362Z v:name="Public Domain"

property e:8yfa-b3bq t:meta.view.owner d:2017-03-08T02:24:00.362Z v:id=czye-wfgc v:profileImageUrlMedium=/api/users/czye-wfgc/profile_images/THUMB v:profileImageUrlLarge=/api/users/czye-wfgc/profile_images/LARGE v:screenName=AustinGo v:profileImageUrlSmall=/api/users/czye-wfgc/profile_images/TINY v:roleName=publisher v:displayName=AustinGo

property e:8yfa-b3bq t:meta.view.tableauthor d:2017-03-08T02:24:00.362Z v:id=czye-wfgc v:profileImageUrlMedium=/api/users/czye-wfgc/profile_images/THUMB v:profileImageUrlLarge=/api/users/czye-wfgc/profile_images/LARGE v:screenName=AustinGo v:profileImageUrlSmall=/api/users/czye-wfgc/profile_images/TINY v:roleName=publisher v:displayName=AustinGo
```