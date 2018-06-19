# Thalia Mara Revenue Numbers - Current

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/thalia-mara-revenue-numbers-current) |
| Metadata | [Link](https://data.jacksonms.gov/api/views/n89e-qb3v) |
| Data: JSON | [100 Rows](https://data.jacksonms.gov/api/views/n89e-qb3v/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.jacksonms.gov/api/views/n89e-qb3v/rows.csv?max_rows=100) |
| Host | data.jacksonms.gov |
| Id | n89e-qb3v |
| Name | Thalia Mara Revenue Numbers - Current |
| Attribution | City of Jackson |
| Category | Economic Development |
| Tags | thalia mara, revenue, city of jackson, events, recreational activities |
| Created | 2016-03-01T17:28:13Z |
| Publication Date | 2016-03-01T17:28:52Z |

## Description

This dataset takes the earnings of Thalia Mara Hall and displays revenue in monthly averages. This data is updated monthly.

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type     | Render Type   |
| ======== | ============== | ============ | ============ | ============= | ============= |
| Yes      | series tag     | month        | Month        | text          | text          |
| Yes      | numeric metric | 2015_revenue | 2015 Revenue | number        | number        |
| Yes      | numeric metric | 2016_revenue | 2016 Revenue | number        | number        |
| Yes      | numeric metric | increase     | Increase     | percent       | percent       |
| Yes      | time           | date_tallied | Date Tallied | calendar_date | calendar_date |
```

## Time Field

```ls
Value = date_tallied
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:n89e-qb3v d:2016-01-01T00:00:00.000Z t:month=January m:increase=51 m:2015_revenue=14902.91 m:2016_revenue=30338

series e:n89e-qb3v d:2016-03-01T09:28:17.000Z t:month=February m:2015_revenue=14902.91

series e:n89e-qb3v d:2016-03-01T09:28:17.000Z t:month=March m:2015_revenue=14902.99
```

## Meta Commands

```ls
metric m:2015_revenue p:double l:"2015 Revenue" t:dataTypeName=number

metric m:2016_revenue p:integer l:"2016 Revenue" t:dataTypeName=number

metric m:increase p:double l:Increase t:dataTypeName=percent

entity e:n89e-qb3v l:"Thalia Mara Revenue Numbers - Current" t:attribution="City of Jackson" t:url=https://data.jacksonms.gov/api/views/n89e-qb3v

property e:n89e-qb3v t:meta.view v:id=n89e-qb3v v:category="Economic Development" v:attributionLink=http://www.jacksonms.gov v:averageRating=0 v:name="Thalia Mara Revenue Numbers - Current" v:attribution="City of Jackson"

property e:n89e-qb3v t:meta.view.owner v:id=6ngd-c2u2 v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:screenName="Justin Bruce" v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:lastNotificationSeenAt=1492180672 v:displayName="Justin Bruce"

property e:n89e-qb3v t:meta.view.tableauthor v:id=6ngd-c2u2 v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:screenName="Justin Bruce" v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492180672 v:displayName="Justin Bruce"
```

## Top Records

```ls
| month     | 2015_revenue | 2016_revenue | increase | date_tallied        | 
| ========= | ============ | ============ | ======== | =================== | 
| January   | 14902.91     | 30338        | 51       | 2016-01-01T00:00:00 | 
| February  | 14902.91     |              |          |                     | 
| March     | 14902.99     |              |          |                     | 
| April     | 14902.91     |              |          |                     | 
| May       | 14902.91     |              |          |                     | 
| June      | 14902.91     |              |          |                     | 
| July      | 14902.91     |              |          |                     | 
| August    | 14902.91     |              |          |                     | 
| September | 14902.91     |              |          |                     | 
| October   | 14902.91     | 30338        | 50.87    | 2015-10-01T00:00:00 | 
```