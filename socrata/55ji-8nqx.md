# Austintexas.gov - Social Media Network Referrals

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/austintexas-gov-social-media-network-referrals) |
| Metadata | [Link](https://data.austintexas.gov/api/views/55ji-8nqx) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/55ji-8nqx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/55ji-8nqx/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 55ji-8nqx |
| Name | Austintexas.gov - Social Media Network Referrals |
| Attribution | City of Austin |
| Category | Government |
| Tags | google analytics, analytics, social referrals, social, referrals, pageviews, session duration, sessions |
| Created | 2015-04-17T14:57:12Z |
| Publication Date | 2015-07-13T19:42:14Z |

## Description

This data, exported from Google Analytics, demonstrates group of interactions that took place on Austintexas.gov pages. A single session can contain multiple screen or page views, events, social interactions, and ecommerce transactions. Pageviews represent a view of a single page. The session duration is the length of time that a visitor remained on Austintexas.gov, and the pages per session show the number of pages they visited during that time. This data represents April 5, 2015 to July 5, 2015.

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| No       | time           | :updated_at              | updated_at               | meta_data | meta_data   |
| Yes      | series tag     | social_network_name      | Social Network Name      | text      | text        |
| Yes      | numeric metric | sessions                 | Sessions                 | number    | number      |
| Yes      | numeric metric | pageviews                | Pageviews                | number    | number      |
| Yes      | series tag     | average_session_duration | Average Session Duration | text      | text        |
| Yes      | numeric metric | pages_session            | Pages / Session          | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:55ji-8nqx d:2015-07-13T12:40:28.000Z t:social_network_name=Facebook t:average_session_duration=0:01:00 m:sessions=71266 m:pages_session=1.65 m:pageviews=117367

series e:55ji-8nqx d:2015-07-13T12:40:28.000Z t:social_network_name=Twitter t:average_session_duration=0:01:09 m:sessions=11589 m:pages_session=1.58 m:pageviews=18346

series e:55ji-8nqx d:2015-07-13T12:40:28.000Z t:social_network_name=reddit t:average_session_duration=0:00:59 m:sessions=4002 m:pages_session=1.64 m:pageviews=6576
```

## Meta Commands

```ls
metric m:sessions p:integer l:Sessions t:dataTypeName=number

metric m:pageviews p:integer l:Pageviews t:dataTypeName=number

metric m:pages_session p:float l:"Pages / Session" d:"Number of pages visited per session." t:dataTypeName=number

entity e:55ji-8nqx l:"Austintexas.gov - Social Media Network Referrals" t:attribution="City of Austin" t:url=https://data.austintexas.gov/api/views/55ji-8nqx

property e:55ji-8nqx t:meta.view v:id=55ji-8nqx v:category=Government v:attributionLink=http://www.google.com/analytics v:averageRating=0 v:name="Austintexas.gov - Social Media Network Referrals" v:attribution="City of Austin"

property e:55ji-8nqx t:meta.view.license v:name="Public Domain"

property e:55ji-8nqx t:meta.view.owner v:id=czye-wfgc v:profileImageUrlMedium=/api/users/czye-wfgc/profile_images/THUMB v:profileImageUrlLarge=/api/users/czye-wfgc/profile_images/LARGE v:screenName=AustinGo v:profileImageUrlSmall=/api/users/czye-wfgc/profile_images/TINY v:displayName=AustinGo

property e:55ji-8nqx t:meta.view.tableauthor v:id=czye-wfgc v:profileImageUrlMedium=/api/users/czye-wfgc/profile_images/THUMB v:profileImageUrlLarge=/api/users/czye-wfgc/profile_images/LARGE v:screenName=AustinGo v:profileImageUrlSmall=/api/users/czye-wfgc/profile_images/TINY v:roleName=publisher v:displayName=AustinGo
```

## Top Records

```ls
| :updated_at | social_network_name | sessions | pageviews | average_session_duration | pages_session | 
| =========== | =================== | ======== | ========= | ======================== | ============= | 
| 1436791228  | Facebook            | 71266    | 117367    | 0:01:00                  | 1.65          | 
| 1436791228  | Twitter             | 11589    | 18346     | 0:01:09                  | 1.58          | 
| 1436791228  | reddit              | 4002     | 6576      | 0:00:59                  | 1.64          | 
| 1436791228  | Yelp                | 3171     | 7579      | 0:01:57                  | 2.39          | 
| 1436791228  | TripAdvisor         | 2218     | 4011      | 0:01:31                  | 1.81          | 
| 1436791228  | BuzzFeed            | 847      | 1577      | 0:01:27                  | 1.86          | 
| 1436791228  | Weebly              | 529      | 1328      | 0:02:33                  | 2.51          | 
| 1436791228  | Pinterest           | 501      | 700       | 0:00:32                  | 1.4           | 
| 1436791228  | Meetup              | 316      | 588       | 0:01:46                  | 1.86          | 
| 1436791228  | WordPress           | 290      | 2826      | 0:08:03                  | 9.74          | 
```