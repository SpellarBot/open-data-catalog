# Google Analytics Sessions on Austintexas.gov

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/google-analytics-sessions-on-austintexas-gov) |
| Metadata | [Link](https://data.austintexas.gov/api/views/dcfk-vk6w) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/dcfk-vk6w/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/dcfk-vk6w/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | dcfk-vk6w |
| Name | Google Analytics Sessions on Austintexas.gov |
| Attribution | City of Austin |
| Tags | analytics, website, www.austintexas.gov, austintexas.gov |
| Created | 2015-04-16T20:19:13Z |
| Publication Date | 2017-04-07T20:44:37Z |

## Description

This data, exported from Google Analytics, demonstrates group of interactions that took place on Austintexas.gov pages within a one-month time frame. A single session can contain multiple screen or page views, events, social interactions, and ecommerce transactions.

## Columns

```ls
| Included | Schema Type    | Field Name | Name     | Data Type     | Render Type   |
| ======== | ============== | ========== | ======== | ============= | ============= |
| Yes      | time           | date       | Date     | calendar_date | calendar_date |
| Yes      | numeric metric | sessions   | Sessions | number        | text          |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:dcfk-vk6w d:2012-01-01T00:00:00.000Z m:sessions=9965

series e:dcfk-vk6w d:2012-01-02T00:00:00.000Z m:sessions=12007

series e:dcfk-vk6w d:2012-01-03T00:00:00.000Z m:sessions=17110
```

## Meta Commands

```ls
metric m:sessions p:long l:Sessions t:dataTypeName=number

entity e:dcfk-vk6w l:"Google Analytics Sessions on Austintexas.gov" t:attribution="City of Austin" t:url=https://data.austintexas.gov/api/views/dcfk-vk6w

property e:dcfk-vk6w t:meta.view v:id=dcfk-vk6w v:attributionLink=http://www.austintexas.gov v:averageRating=0 v:name="Google Analytics Sessions on Austintexas.gov" v:attribution="City of Austin"

property e:dcfk-vk6w t:meta.view.license v:name="Public Domain"

property e:dcfk-vk6w t:meta.view.owner v:id=czye-wfgc v:profileImageUrlMedium=/api/users/czye-wfgc/profile_images/THUMB v:profileImageUrlLarge=/api/users/czye-wfgc/profile_images/LARGE v:screenName=AustinGo v:profileImageUrlSmall=/api/users/czye-wfgc/profile_images/TINY v:displayName=AustinGo

property e:dcfk-vk6w t:meta.view.tableauthor v:id=czye-wfgc v:profileImageUrlMedium=/api/users/czye-wfgc/profile_images/THUMB v:profileImageUrlLarge=/api/users/czye-wfgc/profile_images/LARGE v:screenName=AustinGo v:profileImageUrlSmall=/api/users/czye-wfgc/profile_images/TINY v:roleName=publisher v:displayName=AustinGo
```

## Top Records

```ls
| date                | sessions | 
| =================== | ======== | 
| 2012-01-01T00:00:00 | 9,965    | 
| 2012-01-02T00:00:00 | 12,007   | 
| 2012-01-03T00:00:00 | 17,110   | 
| 2012-01-04T00:00:00 | 24,607   | 
| 2012-01-05T00:00:00 | 22,079   | 
| 2012-01-06T00:00:00 | 19,836   | 
| 2012-01-07T00:00:00 | 14,542   | 
| 2012-01-08T00:00:00 | 12,427   | 
| 2012-01-09T00:00:00 | 24,355   | 
| 2012-01-10T00:00:00 | 23,691   | 
```