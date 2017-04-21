# Thalia Mara Shows

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/thalia-mara-shows) |
| Metadata | [Link](https://data.jacksonms.gov/api/views/fcrk-mukz) |
| Data: JSON | [100 Rows](https://data.jacksonms.gov/api/views/fcrk-mukz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.jacksonms.gov/api/views/fcrk-mukz/rows.csv?max_rows=100) |
| Host | data.jacksonms.gov |
| Id | fcrk-mukz |
| Name | Thalia Mara Shows |
| Attribution | City of Jackson |
| Category | Economic Development |
| Tags | thalia mara, revenue, city of jackson, events, recreational activities |
| Created | 2016-03-07T20:38:26Z |
| Publication Date | 2016-03-07T20:39:20Z |

## Description

This data set displays the number of shows performed at Thalia Mara Hall on a monthly basis. This data is updated on a monthly basis.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name           | Data Type     | Render Type   |
| ======== | ============== | ============= | ============== | ============= | ============= |
| Yes      | series tag     | month         | Month          | text          | text          |
| Yes      | numeric metric | fy14_15       | FY14-15        | number        | number        |
| Yes      | numeric metric | fy15_16       | FY15-16        | number        | number        |
| Yes      | numeric metric | increase      | Increase       | percent       | percent       |
| Yes      | time           | date_received | Date Received: | calendar_date | calendar_date |
```

## Time Field

```ls
Value = date_received
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:fcrk-mukz d:2016-01-31T00:00:00.000Z t:month=January m:fy15_16=8 m:fy14_15=4 m:increase=50

series e:fcrk-mukz d:2016-03-07T12:38:30.000Z t:month=February m:fy14_15=5

series e:fcrk-mukz d:2016-03-07T12:38:30.000Z t:month=March m:fy14_15=4
```

## Meta Commands

```ls
metric m:fy14_15 p:integer l:FY14-15 t:dataTypeName=number

metric m:fy15_16 p:integer l:FY15-16 t:dataTypeName=number

metric m:increase p:double l:Increase t:dataTypeName=percent

entity e:fcrk-mukz l:"Thalia Mara Shows" t:attribution="City of Jackson" t:url=https://data.jacksonms.gov/api/views/fcrk-mukz

property e:fcrk-mukz t:meta.view v:id=fcrk-mukz v:category="Economic Development" v:attributionLink=http://www.jacksonms.gov v:averageRating=0 v:name="Thalia Mara Shows" v:attribution="City of Jackson"

property e:fcrk-mukz t:meta.view.owner v:id=6ngd-c2u2 v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:screenName="Justin Bruce" v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:lastNotificationSeenAt=1492180672 v:displayName="Justin Bruce"

property e:fcrk-mukz t:meta.view.tableauthor v:id=6ngd-c2u2 v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:screenName="Justin Bruce" v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492180672 v:displayName="Justin Bruce"
```

## Top Records

```ls
| month     | fy14_15 | fy15_16 | increase | date_received       | 
| ========= | ======= | ======= | ======== | =================== | 
| January   | 4       | 8       | 50       | 2016-01-31T00:00:00 | 
| February  | 5       |         |          |                     | 
| March     | 4       |         |          |                     | 
| April     | 5       |         |          |                     | 
| May       | 4       |         |          |                     | 
| June      | 5       |         |          |                     | 
| July      | 4       |         |          |                     | 
| August    | 5       |         |          |                     | 
| September | 4       |         |          |                     | 
| October   | 5       | 8       | 37.50    | 2015-10-31T00:00:00 | 
```