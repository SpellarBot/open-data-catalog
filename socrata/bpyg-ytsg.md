# 311 Service Request Data historical

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ita-311-data-309bd) |
| Metadata | [Link](https://data.lacity.org/api/views/bpyg-ytsg) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/bpyg-ytsg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/bpyg-ytsg/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | bpyg-ytsg |
| Name | 311 Service Request Data historical |
| Category | A Well Run City |
| Tags | 311, myla311, 311 app |
| Created | 2014-05-30T21:33:02Z |
| Publication Date | 2014-05-30T21:38:59Z |

## Description

This data shows the source of 311 requests and the wait time to speak to an agent when dialing 311 for years 2013-2014.
For the new 311 dataset (refreshed daily), see https://data.lacity.org/A-Well-Run-City/MyLA311-Service-Request-Data-2016/ndkd-k878

## Columns

```ls
| Included | Schema Type    | Field Name                                | Name                                         | Data Type     | Render Type   |
| ======== | ============== | ========================================= | ============================================ | ============= | ============= |
| Yes      | time           | date_name                                 | Date Name                                    | calendar_date | calendar_date |
| No       |                | date_value                                | Date Value                                   | calendar_date | calendar_date |
| Yes      | numeric metric | total_311_contacts                        | Total 311 Contacts                           | number        | number        |
| Yes      | numeric metric | total_311_requests_using_app_web          | Total 311 Requests Using App/Web             | number        | number        |
| Yes      | numeric metric | of_311_requests_by_app_web                | % of 311 Requests by App/Web                 | percent       | percent       |
| Yes      | numeric metric | 311_avg_call_wait_times_seconds           | 311 Avg Call Wait Times (seconds)            | number        | number        |
| Yes      | numeric metric | 311_avg_call_wait_time_change_yoy_seconds | 311 Avg. Call Wait Time Change YOY (seconds) | number        | number        |
```

## Time Field

```ls
Value = date_name
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_value
```

## Data Commands

```ls
series e:bpyg-ytsg d:2013-01-01T00:00:00.000Z m:total_311_requests_using_app_web=0 m:of_311_requests_by_app_web=0 m:total_311_contacts=101138 m:311_avg_call_wait_times_seconds=306

series e:bpyg-ytsg d:2013-02-01T00:00:00.000Z m:total_311_requests_using_app_web=0 m:of_311_requests_by_app_web=0 m:total_311_contacts=87039 m:311_avg_call_wait_times_seconds=354

series e:bpyg-ytsg d:2013-03-01T00:00:00.000Z m:total_311_requests_using_app_web=89 m:of_311_requests_by_app_web=0.1 m:total_311_contacts=88848 m:311_avg_call_wait_times_seconds=222
```

## Meta Commands

```ls
metric m:total_311_contacts p:integer l:"Total 311 Contacts" t:dataTypeName=number

metric m:total_311_requests_using_app_web p:integer l:"Total 311 Requests Using App/Web" t:dataTypeName=number

metric m:of_311_requests_by_app_web p:float l:"% of 311 Requests by App/Web" t:dataTypeName=percent

metric m:311_avg_call_wait_times_seconds p:integer l:"311 Avg Call Wait Times (seconds)" t:dataTypeName=number

metric m:311_avg_call_wait_time_change_yoy_seconds p:integer l:"311 Avg. Call Wait Time Change YOY (seconds)" t:dataTypeName=number

entity e:bpyg-ytsg l:"311 Service Request Data historical" t:url=https://data.lacity.org/api/views/bpyg-ytsg

property e:bpyg-ytsg t:meta.view v:id=bpyg-ytsg v:category="A Well Run City" v:averageRating=0 v:name="311 Service Request Data historical"

property e:bpyg-ytsg t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:bpyg-ytsg t:meta.view.owner v:id=yb4r-dcys v:profileImageUrlMedium=/api/users/yb4r-dcys/profile_images/THUMB v:profileImageUrlLarge=/api/users/yb4r-dcys/profile_images/LARGE v:screenName="ITA OpenData" v:profileImageUrlSmall=/api/users/yb4r-dcys/profile_images/TINY v:displayName="ITA OpenData"

property e:bpyg-ytsg t:meta.view.tableauthor v:id=yb4r-dcys v:profileImageUrlMedium=/api/users/yb4r-dcys/profile_images/THUMB v:profileImageUrlLarge=/api/users/yb4r-dcys/profile_images/LARGE v:screenName="ITA OpenData" v:profileImageUrlSmall=/api/users/yb4r-dcys/profile_images/TINY v:roleName=publisher v:displayName="ITA OpenData"
```

## Top Records

```ls
| date_name           | date_value          | total_311_contacts | total_311_requests_using_app_web | of_311_requests_by_app_web | 311_avg_call_wait_times_seconds | 311_avg_call_wait_time_change_yoy_seconds | 
| =================== | =================== | ================== | ================================ | ========================== | =============================== | ========================================= | 
| 2013-01-01T00:00:00 | 2013-01-31T00:00:00 | 101138             | 0                                | 0                          | 306                             |                                           | 
| 2013-02-01T00:00:00 | 2013-02-28T00:00:00 | 87039              | 0                                | 0                          | 354                             |                                           | 
| 2013-03-01T00:00:00 | 2013-03-31T00:00:00 | 88848              | 89                               | 0.1                        | 222                             |                                           | 
| 2013-04-01T00:00:00 | 2013-04-30T00:00:00 | 90185              | 2525                             | 2.8                        | 60                              |                                           | 
| 2013-05-01T00:00:00 | 2013-05-31T00:00:00 | 95481              | 1910                             | 2                          | 60                              |                                           | 
| 2013-06-01T00:00:00 | 2013-06-30T00:00:00 | 99806              | 2296                             | 2.3                        | 210                             |                                           | 
| 2013-07-01T00:00:00 | 2013-07-31T00:00:00 | 112257             | 3368                             | 3                          | 222                             |                                           | 
| 2013-08-01T00:00:00 | 2013-08-31T00:00:00 | 103262             | 4544                             | 4.4                        | 84                              |                                           | 
| 2013-09-01T00:00:00 | 2013-09-30T00:00:00 | 99630              | 4683                             | 4.7                        | 96                              |                                           | 
| 2013-10-01T00:00:00 | 2013-10-31T00:00:00 | 98963              | 3563                             | 3.6                        | 90                              |                                           | 
```