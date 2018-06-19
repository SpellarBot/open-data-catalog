# Iowa Lottery Weekly Sales by Game Type

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/iowa-lottery-weekly-sales-by-game-type) |
| Metadata | [Link](https://data.iowa.gov/api/views/2zsw-fax5) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/2zsw-fax5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/2zsw-fax5/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | 2zsw-fax5 |
| Name | Iowa Lottery Weekly Sales by Game Type |
| Category | Economy |
| Tags | lottery, lotto, sales |
| Created | 2016-09-30T14:08:02Z |
| Publication Date | 2017-03-28T13:44:18Z |

## Description

Ongoing Iowa Lottery sales, from the beginning of fiscal year 2016, aggregated by week (Sunday through Saturday) and by game type (lotto, instant-scratch, instaplay, and pull-tab games);

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type     | Render Type   |
| ======== | ============== | ================ | ================ | ============= | ============= |
| Yes      | time           | week_ending_date | Week Ending Date | calendar_date | calendar_date |
| Yes      | series tag     | game_type        | Game Type        | text          | text          |
| Yes      | numeric metric | sales_amount     | Sales Amount     | money         | money         |
```

## Time Field

```ls
Value = week_ending_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:2zsw-fax5 d:2015-07-04T00:00:00.000Z t:game_type=Lotto m:sales_amount=1477969

series e:2zsw-fax5 d:2015-07-04T00:00:00.000Z t:game_type=Instant m:sales_amount=3829822

series e:2zsw-fax5 d:2015-07-04T00:00:00.000Z t:game_type=Pulltab m:sales_amount=278080
```

## Meta Commands

```ls
metric m:sales_amount p:double l:"Sales Amount" t:dataTypeName=money

entity e:2zsw-fax5 l:"Iowa Lottery Weekly Sales by Game Type" t:url=https://data.iowa.gov/api/views/2zsw-fax5

property e:2zsw-fax5 t:meta.view v:id=2zsw-fax5 v:category=Economy v:averageRating=0 v:name="Iowa Lottery Weekly Sales by Game Type"

property e:2zsw-fax5 t:meta.view.owner v:id=entd-2uif v:profileImageUrlMedium=/api/users/entd-2uif/profile_images/THUMB v:profileImageUrlLarge=/api/users/entd-2uif/profile_images/LARGE v:screenName="Iowa Lottery Authority" v:profileImageUrlSmall=/api/users/entd-2uif/profile_images/TINY v:displayName="Iowa Lottery Authority"

property e:2zsw-fax5 t:meta.view.tableauthor v:id=entd-2uif v:profileImageUrlMedium=/api/users/entd-2uif/profile_images/THUMB v:profileImageUrlLarge=/api/users/entd-2uif/profile_images/LARGE v:screenName="Iowa Lottery Authority" v:profileImageUrlSmall=/api/users/entd-2uif/profile_images/TINY v:roleName=editor v:displayName="Iowa Lottery Authority"
```

## Top Records

```ls
| week_ending_date    | game_type | sales_amount | 
| =================== | ========= | ============ | 
| 2015-07-04T00:00:00 | Lotto     | 1477969      | 
| 2015-07-04T00:00:00 | Instant   | 3829822      | 
| 2015-07-04T00:00:00 | Pulltab   | 278080       | 
| 2015-07-11T00:00:00 | Lotto     | 1459132      | 
| 2015-07-11T00:00:00 | Instant   | 3425039      | 
| 2015-07-11T00:00:00 | Pulltab   | 292275       | 
| 2015-07-18T00:00:00 | Lotto     | 1515182      | 
| 2015-07-18T00:00:00 | Instant   | 3963434      | 
| 2015-07-18T00:00:00 | Pulltab   | 313403       | 
| 2015-07-25T00:00:00 | Lotto     | 1454695      | 
```