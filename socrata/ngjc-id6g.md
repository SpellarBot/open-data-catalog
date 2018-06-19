# Election Periods for Hawaii Noncandidate Committees

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/election-periods-for-hawaii-noncandidate-committees-de7e5) |
| Metadata | [Link](https://data.hawaii.gov/api/views/ngjc-id6g) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/ngjc-id6g/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/ngjc-id6g/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | ngjc-id6g |
| Name | Election Periods for Hawaii Noncandidate Committees |
| Attribution | State of Hawaii; Campaign Spending Commission |
| Category | Community |
| Tags | campaign spending commission, campaign finance, candidate, hawaii candidates, contributions, political contributions, campaign contributions, campaign spending |
| Created | 2013-06-24T21:32:01Z |
| Publication Date | 2016-12-14T02:30:06Z |

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type     | Render Type   |
| ======== | =========== | =============== | =============== | ============= | ============= |
| Yes      | series tag  | election_period | Election Period | text          | text          |
| Yes      | time        | ep_start_date   | EP Start Date   | calendar_date | calendar_date |
| No       |             | ep_end_date     | EP End Date     | calendar_date | calendar_date |
```

## Time Field

```ls
Value = ep_start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = ep_end_date
```

## Data Commands

```ls
series e:ngjc-id6g d:2004-11-03T00:00:00.000Z t:election_period=2004-2006 m:row_number.ngjc-id6g=1

series e:ngjc-id6g d:2006-11-08T00:00:00.000Z t:election_period=2006-2008 m:row_number.ngjc-id6g=2

series e:ngjc-id6g d:2008-11-05T00:00:00.000Z t:election_period=2008-2010 m:row_number.ngjc-id6g=3
```

## Meta Commands

```ls
metric m:row_number.ngjc-id6g p:long l:"Row Number"

entity e:ngjc-id6g l:"Election Periods for Hawaii Noncandidate Committees" t:attribution="State of Hawaii; Campaign Spending Commission" t:url=https://data.hawaii.gov/api/views/ngjc-id6g

property e:ngjc-id6g t:meta.view v:id=ngjc-id6g v:category=Community v:attributionLink=http://www.hawaii.gov/campaign v:averageRating=0 v:name="Election Periods for Hawaii Noncandidate Committees" v:attribution="State of Hawaii; Campaign Spending Commission"

property e:ngjc-id6g t:meta.view.owner v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:displayName="Hawaii Campaign Spending Commission"

property e:ngjc-id6g t:meta.view.tableauthor v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:roleName=editor v:displayName="Hawaii Campaign Spending Commission"
```

## Top Records

```ls
| election_period | ep_start_date       | ep_end_date         | 
| =============== | =================== | =================== | 
| 2004-2006       | 2004-11-03T00:00:00 | 2006-11-07T00:00:00 | 
| 2006-2008       | 2006-11-08T00:00:00 | 2008-11-04T00:00:00 | 
| 2008-2010       | 2008-11-05T00:00:00 | 2010-11-02T00:00:00 | 
| 2010-2012       | 2010-11-03T00:00:00 | 2012-11-06T00:00:00 | 
| 2012-2014       | 2012-11-07T00:00:00 | 2014-11-04T00:00:00 | 
| 2014-2016       | 2014-11-05T00:00:00 | 2016-11-08T00:00:00 | 
| 2016-2018       | 2016-11-09T00:00:00 | 2018-11-06T00:00:00 | 
```