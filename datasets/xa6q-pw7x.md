# Data WAsite Metrics

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/data-wasite-metrics-56247) |
| Metadata | [Link](https://data.wa.gov/api/views/xa6q-pw7x) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/xa6q-pw7x/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/xa6q-pw7x/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | xa6q-pw7x |
| Name | Data WAsite Metrics |
| Tags | socrata, administration, resultswa |
| Created | 2014-12-26T22:57:12Z |
| Publication Date | 2014-12-26T23:38:12Z |

## Description

Historical usage of data.wa.gov installation beginning in 2009

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type     | Render Type   |
| ======== | ============== | ====================== | ====================== | ============= | ============= |
| No       |                | start                  | Start                  | calendar_date | calendar_date |
| No       |                | end                    | End                    | calendar_date | calendar_date |
| Yes      | numeric metric | browser_chrome         | browser-chrome         | number        | number        |
| Yes      | numeric metric | browser_firefox        | browser-firefox        | number        | number        |
| Yes      | numeric metric | browser_ie             | browser-ie             | number        | number        |
| Yes      | numeric metric | browser_other          | browser-other          | number        | number        |
| Yes      | numeric metric | browser_safari         | browser-safari         | number        | number        |
| Yes      | numeric metric | bytes_in               | bytes-in               | number        | number        |
| Yes      | numeric metric | bytes_out              | bytes-out              | number        | number        |
| Yes      | numeric metric | charts_created         | charts-created         | number        | number        |
| Yes      | numeric metric | charts_deleted         | charts-deleted         | number        | number        |
| Yes      | numeric metric | datasets               | datasets               | number        | number        |
| Yes      | numeric metric | datasets_created       | datasets-created       | number        | number        |
| Yes      | numeric metric | datasets_deleted       | datasets-deleted       | number        | number        |
| Yes      | numeric metric | datasets_published     | datasets-published     | number        | number        |
| Yes      | numeric metric | datasets_unpublished   | datasets-unpublished   | number        | number        |
| Yes      | numeric metric | disk_usage             | disk-usage             | number        | number        |
| Yes      | numeric metric | geocoding_requests     | geocoding-requests     | number        | number        |
| Yes      | numeric metric | js_page_view           | js-page-view           | number        | number        |
| Yes      | numeric metric | maps_created           | maps-created           | number        | number        |
| Yes      | numeric metric | maps_deleted           | maps-deleted           | number        | number        |
| Yes      | numeric metric | page_views             | page-views             | number        | number        |
| Yes      | numeric metric | ratings_count          | ratings-count          | number        | number        |
| Yes      | numeric metric | ratings_total          | ratings-total          | number        | number        |
| Yes      | numeric metric | rows_accessed_api      | rows-accessed-api      | number        | number        |
| Yes      | numeric metric | rows_accessed_download | rows-accessed-download | number        | number        |
| Yes      | numeric metric | rows_accessed_print    | rows-accessed-print    | number        | number        |
| Yes      | numeric metric | rows_accessed_rss      | rows-accessed-rss      | number        | number        |
| Yes      | numeric metric | rows_accessed_website  | rows-accessed-website  | number        | number        |
| Yes      | numeric metric | rows_accessed_widget   | rows-accessed-widget   | number        | number        |
| Yes      | numeric metric | rows_created           | rows-created           | number        | number        |
| Yes      | numeric metric | rows_deleted           | rows-deleted           | number        | number        |
| Yes      | numeric metric | rows_loaded_api        | rows-loaded-api        | number        | number        |
| Yes      | time           | rows_loaded_download   | rows-loaded-download   | calendar_date | calendar_date |
| Yes      | numeric metric | rows_loaded_print      | rows-loaded-print      | number        | number        |
| Yes      | numeric metric | rows_loaded_rss        | rows-loaded-rss        | number        | number        |
| Yes      | numeric metric | rows_loaded_website    | rows-loaded-website    | number        | number        |
| Yes      | numeric metric | rows_loaded_widget     | rows-loaded-widget     | number        | number        |
| Yes      | numeric metric | shares                 | shares                 | number        | number        |
| Yes      | numeric metric | users_created          | users-created          | number        | number        |
| Yes      | numeric metric | view_loaded            | view-loaded            | number        | number        |
```

## Time Field

```ls
Value = rows_loaded_download
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = start,end
```

## Data Commands

```ls
series e:xa6q-pw7x d:1190044-01-01T00:00:00.000Z m:rows_loaded_print=280 m:rows_accessed_download=1474 m:bytes_in=21545894 m:bytes_out=1959082009 m:rows_loaded_website=46849 m:rows_loaded_api=149974 m:rows_loaded_widget=25896 m:users_created=2 m:rows_accessed_widget=593 m:rows_loaded_rss=8560 m:rows_accessed_print=1 m:maps_created=1 m:rows_accessed_website=1918 m:page_views=177 m:rows_accessed_api=12479 m:maps_deleted=1 m:view_loaded=1404 m:rows_accessed_rss=209

series e:xa6q-pw7x d:818006-01-01T00:00:00.000Z m:rows_loaded_print=76050 m:disk_usage=2214132827 m:rows_accessed_download=691 m:bytes_in=12811810 m:bytes_out=2683626552 m:rows_loaded_website=105152 m:rows_loaded_api=2730 m:rows_loaded_widget=8247 m:users_created=1 m:rows_accessed_widget=235 m:rows_loaded_rss=15872 m:rows_accessed_print=162 m:rows_accessed_website=4696 m:page_views=12446 m:rows_accessed_api=2134 m:view_loaded=1863 m:rows_accessed_rss=427

series e:xa6q-pw7x d:2014-12-26T14:57:29.000Z m:datasets_deleted=9 m:datasets_created=13
```

## Meta Commands

```ls
metric m:browser_chrome p:integer l:browser-chrome t:dataTypeName=number

metric m:browser_firefox p:integer l:browser-firefox t:dataTypeName=number

metric m:browser_ie p:integer l:browser-ie t:dataTypeName=number

metric m:browser_other p:integer l:browser-other t:dataTypeName=number

metric m:browser_safari p:integer l:browser-safari t:dataTypeName=number

metric m:bytes_in p:integer l:bytes-in t:dataTypeName=number

metric m:bytes_out p:long l:bytes-out t:dataTypeName=number

metric m:charts_created p:integer l:charts-created t:dataTypeName=number

metric m:charts_deleted p:integer l:charts-deleted t:dataTypeName=number

metric m:datasets p:integer l:datasets t:dataTypeName=number

metric m:datasets_created p:integer l:datasets-created t:dataTypeName=number

metric m:datasets_deleted p:integer l:datasets-deleted t:dataTypeName=number

metric m:datasets_published p:integer l:datasets-published t:dataTypeName=number

metric m:datasets_unpublished p:integer l:datasets-unpublished t:dataTypeName=number

metric m:disk_usage p:long l:disk-usage t:dataTypeName=number

metric m:geocoding_requests p:integer l:geocoding-requests t:dataTypeName=number

metric m:js_page_view p:integer l:js-page-view t:dataTypeName=number

metric m:maps_created p:integer l:maps-created t:dataTypeName=number

metric m:maps_deleted p:integer l:maps-deleted t:dataTypeName=number

metric m:page_views p:integer l:page-views t:dataTypeName=number

metric m:ratings_count p:integer l:ratings-count t:dataTypeName=number

metric m:ratings_total p:integer l:ratings-total t:dataTypeName=number

metric m:rows_accessed_api p:integer l:rows-accessed-api t:dataTypeName=number

metric m:rows_accessed_download p:integer l:rows-accessed-download t:dataTypeName=number

metric m:rows_accessed_print p:integer l:rows-accessed-print t:dataTypeName=number

metric m:rows_accessed_rss p:integer l:rows-accessed-rss t:dataTypeName=number

metric m:rows_accessed_website p:integer l:rows-accessed-website t:dataTypeName=number

metric m:rows_accessed_widget p:integer l:rows-accessed-widget t:dataTypeName=number

metric m:rows_created p:integer l:rows-created t:dataTypeName=number

metric m:rows_deleted p:integer l:rows-deleted t:dataTypeName=number

metric m:rows_loaded_api p:integer l:rows-loaded-api t:dataTypeName=number

metric m:rows_loaded_print p:integer l:rows-loaded-print t:dataTypeName=number

metric m:rows_loaded_rss p:integer l:rows-loaded-rss t:dataTypeName=number

metric m:rows_loaded_website p:integer l:rows-loaded-website t:dataTypeName=number

metric m:rows_loaded_widget p:integer l:rows-loaded-widget t:dataTypeName=number

metric m:shares p:integer l:shares t:dataTypeName=number

metric m:users_created p:integer l:users-created t:dataTypeName=number

metric m:view_loaded p:integer l:view-loaded t:dataTypeName=number

entity e:xa6q-pw7x l:"Data WAsite Metrics" t:url=https://data.wa.gov/api/views/xa6q-pw7x

property e:xa6q-pw7x t:meta.view v:id=xa6q-pw7x v:averageRating=0 v:name="Data WAsite Metrics"

property e:xa6q-pw7x t:meta.view.owner v:id=h2ue-vnnt v:profileImageUrlMedium=/api/users/h2ue-vnnt/profile_images/THUMB v:profileImageUrlLarge=/api/users/h2ue-vnnt/profile_images/LARGE v:screenName="OCIO-Will Saunders" v:profileImageUrlSmall=/api/users/h2ue-vnnt/profile_images/TINY v:displayName="OCIO-Will Saunders"

property e:xa6q-pw7x t:meta.view.tableauthor v:id=h2ue-vnnt v:profileImageUrlMedium=/api/users/h2ue-vnnt/profile_images/THUMB v:profileImageUrlLarge=/api/users/h2ue-vnnt/profile_images/LARGE v:screenName="OCIO-Will Saunders" v:profileImageUrlSmall=/api/users/h2ue-vnnt/profile_images/TINY v:roleName=publisher v:displayName="OCIO-Will Saunders"
```

## Top Records

```ls
| start | end | browser_chrome | browser_firefox | browser_ie | browser_other | browser_safari | bytes_in | bytes_out  | charts_created | charts_deleted | datasets | datasets_created | datasets_deleted | datasets_published | datasets_unpublished | disk_usage | geocoding_requests | js_page_view | maps_created | maps_deleted | page_views | ratings_count | ratings_total | rows_accessed_api | rows_accessed_download | rows_accessed_print | rows_accessed_rss | rows_accessed_website | rows_accessed_widget | rows_created | rows_deleted | rows_loaded_api | rows_loaded_download   | rows_loaded_print | rows_loaded_rss | rows_loaded_website | rows_loaded_widget | shares | users_created | view_loaded | 
| ===== | === | ============== | =============== | ========== | ============= | ============== | ======== | ========== | ============== | ============== | ======== | ================ | ================ | ================== | ==================== | ========== | ================== | ============ | ============ | ============ | ========== | ============= | ============= | ================= | ====================== | =================== | ================= | ===================== | ==================== | ============ | ============ | =============== | ====================== | ================= | =============== | =================== | ================== | ====== | ============= | =========== | 
|       |     |                |                 |            |               |                | 21545894 | 1959082009 |                |                |          |                  |                  |                    |                      |            |                    |              | 1            | 1            | 177        |               |               | 12479             | 1474                   | 1                   | 209               | 1918                  | 593                  |              |              | 149974          | 1190044-01-01T00:00:00 | 280               | 8560            | 46849               | 25896              |        | 2             | 1404        | 
|       |     |                |                 |            |               |                |          |            |                |                |          |                  |                  |                    |                      |            |                    |              |              |              |            |               |               |                   |                        |                     |                   |                       |                      |              |              |                 |                        |                   |                 |                     |                    |        |               |             | 
|       |     |                |                 |            |               |                | 12811810 | 2683626552 |                |                |          |                  |                  |                    |                      | 2214132827 |                    |              |              |              | 12446      |               |               | 2134              | 691                    | 162                 | 427               | 4696                  | 235                  |              |              | 2730            | 818006-01-01T00:00:00  | 76050             | 15872           | 105152              | 8247               |        | 1             | 1863        | 
|       |     |                |                 |            |               |                |          |            |                |                |          | 13               | 9                |                    |                      |            |                    |              |              |              |            |               |               |                   |                        |                     |                   |                       |                      |              |              |                 |                        |                   |                 |                     |                    |        |               |             | 
|       |     |                |                 |            |               |                |          |            |                |                |          |                  |                  |                    |                      |            |                    |              |              |              |            |               |               |                   |                        |                     |                   |                       |                      |              |              |                 |                        |                   |                 |                     |                    |        |               |             | 
|       |     |                |                 |            |               |                |          |            |                |                |          |                  |                  |                    |                      |            |                    |              |              |              |            |               |               |                   |                        |                     |                   |                       |                      |              |              |                 |                        |                   |                 |                     |                    |        |               |             | 
|       |     |                |                 |            |               |                |          |            |                |                |          |                  |                  |                    |                      |            |                    |              |              |              |            |               |               |                   |                        |                     |                   |                       |                      |              |              |                 |                        |                   |                 |                     |                    |        |               |             | 
|       |     |                |                 |            |               |                |          |            |                |                |          |                  |                  |                    |                      |            |                    |              |              |              |            |               |               |                   |                        |                     |                   |                       |                      |              |              |                 |                        |                   |                 |                     |                    |        |               |             | 
|       |     |                |                 |            |               |                |          |            |                |                |          |                  |                  |                    |                      |            |                    |              |              |              |            |               |               |                   |                        |                     |                   |                       |                      |              |              |                 |                        |                   |                 |                     |                    |        |               |             | 
|       |     |                |                 |            |               |                | 1413336  | 98079234   |                |                |          | 8                | 2                |                    |                      |            | 281                |              |              |              |            |               |               | 128               | 33                     |                     | 8                 | 502                   | 9                    | 39306        | 13564        | 5866            | 26978-01-01T00:00:00   |                   | 358             | 17971               | 450                |        |               | 325         | 
```