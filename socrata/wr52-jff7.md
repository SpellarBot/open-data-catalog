# Thalia Mara Numbers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/thalia-mara-numbers) |
| Metadata | [Link](https://data.jacksonms.gov/api/views/wr52-jff7) |
| Data: JSON | [100 Rows](https://data.jacksonms.gov/api/views/wr52-jff7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.jacksonms.gov/api/views/wr52-jff7/rows.csv?max_rows=100) |
| Host | data.jacksonms.gov |
| Id | wr52-jff7 |
| Name | Thalia Mara Numbers |
| Attribution | City of Jackson |
| Category | City Services |
| Tags | thalia mara, revenue, visitors, numbers |
| Created | 2016-04-26T12:56:49Z |
| Publication Date | 2016-10-17T13:31:24Z |

## Description

This dataset gives an overview of Thalia Mara Hall actions per month. This data is updated monthly.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name          | Data Type     | Render Type   |
| ======== | ============== | =========== | ============= | ============= | ============= |
| Yes      | time           | month       | Month         | calendar_date | calendar_date |
| Yes      | numeric metric | revenue     | Revenue       | money         | money         |
| Yes      | numeric metric | of_shows    | # of Shows    | number        | number        |
| Yes      | numeric metric | of_visitors | # of Visitors | number        | number        |
```

## Time Field

```ls
Value = month
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:wr52-jff7 d:2015-01-31T00:00:00.000Z m:of_shows=3 m:revenue=19326 m:of_visitors=5127

series e:wr52-jff7 d:2015-02-28T00:00:00.000Z m:of_shows=4 m:revenue=18765 m:of_visitors=5495

series e:wr52-jff7 d:2015-03-31T00:00:00.000Z m:of_shows=3 m:revenue=12979 m:of_visitors=4585
```

## Meta Commands

```ls
metric m:revenue p:double l:Revenue t:dataTypeName=money

metric m:of_shows p:float l:"# of Shows" t:dataTypeName=number

metric m:of_visitors p:float l:"# of Visitors" t:dataTypeName=number

entity e:wr52-jff7 l:"Thalia Mara Numbers" t:attribution="City of Jackson" t:url=https://data.jacksonms.gov/api/views/wr52-jff7

property e:wr52-jff7 t:meta.view d:2017-09-25T07:28:48.348Z v:averageRating=0 v:name="Thalia Mara Numbers" v:attribution="City of Jackson" v:attributionLink=http://www.jacksonms.gov v:id=wr52-jff7 v:category="City Services"

property e:wr52-jff7 t:meta.view.owner d:2017-09-25T07:28:48.348Z v:displayName="Justin Bruce" v:lastNotificationSeenAt=1492180672 v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:id=6ngd-c2u2 v:screenName="Justin Bruce" v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB

property e:wr52-jff7 t:meta.view.tableauthor d:2017-09-25T07:28:48.348Z v:displayName="Justin Bruce" v:lastNotificationSeenAt=1492180672 v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:roleName=administrator v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:id=6ngd-c2u2 v:screenName="Justin Bruce" v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB
```

## Top Records

```ls
| month               | revenue  | of_shows | of_visitors | 
| =================== | ======== | ======== | =========== | 
|                     |          |          |             | 
|                     |          |          |             | 
|                     |          |          |             | 
| 2015-01-31T00:00:00 | 19326.00 | 3.00     | 5127.00     | 
| 2015-02-28T00:00:00 | 18765.00 | 4.00     | 5495.00     | 
| 2015-03-31T00:00:00 | 12979.00 | 3.00     | 4585.00     | 
| 2015-04-30T00:00:00 | 13909.00 | 6.00     | 4745.00     | 
| 2015-05-31T00:00:00 | 6050.00  | 6.00     | 6883.00     | 
| 2015-06-30T00:00:00 | 15132.00 | 5.00     | 6716.00     | 
| 2015-07-31T00:00:00 | 20404.00 | 3.00     | 5222.00     | 
```