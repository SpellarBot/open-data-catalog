# Campaign Consultants - List of Registered Campaign Consultants and their Respective Clients

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-consultants-list-of-registered-campaign-consultants-and-their-respective-clients-cfd72) |
| Metadata | [Link](https://data.sfgov.org/api/views/wchi-36a5) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/wchi-36a5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/wchi-36a5/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | wchi-36a5 |
| Name | Campaign Consultants - List of Registered Campaign Consultants and their Respective Clients |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | campaign, consultant, client, registered, ethics |
| Created | 2012-08-14T23:46:14Z |
| Publication Date | 2014-03-19T21:58:49Z |

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type     | Render Type   |
| ======== | =========== | =================== | =================== | ============= | ============= |
| Yes      | series tag  | campaign_consultant | Campaign Consultant | text          | text          |
| Yes      | series tag  | client_name         | Client              | text          | text          |
| Yes      | time        | quarter_start_date  | Quarter Start Date  | calendar_date | calendar_date |
| No       |             | quarter_end_date    | Quarter End Date    | calendar_date | calendar_date |
| No       |             | quarter             | Quarter             | number        | text          |
| No       |             | year                | Year                | number        | text          |
```

## Time Field

```ls
Value = quarter_start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = quarter_end_date,quarter,year
```

## Data Commands

```ls
series e:wchi-36a5 d:2016-09-01T00:00:00.000Z t:campaign_consultant="50+1 Strategies" t:client_name="Joshua Arce" m:row_number.wchi-36a5=1

series e:wchi-36a5 d:2016-09-01T00:00:00.000Z t:campaign_consultant="50+1 Strategies" t:client_name="Matt Haney" m:row_number.wchi-36a5=2

series e:wchi-36a5 d:2016-09-01T00:00:00.000Z t:campaign_consultant="50+1 Strategies" t:client_name="Alex Randolph" m:row_number.wchi-36a5=3
```

## Meta Commands

```ls
metric m:row_number.wchi-36a5 p:long l:"Row Number"

entity e:wchi-36a5 l:"Campaign Consultants - List of Registered Campaign Consultants and their Respective Clients" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/wchi-36a5

property e:wchi-36a5 t:meta.view v:id=wchi-36a5 v:category="City Management and Ethics" v:attributionLink=http://www.sfethics.org v:averageRating=0 v:name="Campaign Consultants - List of Registered Campaign Consultants and their Respective Clients" v:attribution="San Francisco Ethics Commission"

property e:wchi-36a5 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:wchi-36a5 t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:wchi-36a5 t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```

## Top Records

```ls
| campaign_consultant | client_name                                               | quarter_start_date  | quarter_end_date    | quarter | year | 
| =================== | ========================================================= | =================== | =================== | ======= | ==== | 
| 50+1 Strategies     | Joshua Arce                                               | 2016-09-01T00:00:00 | 2016-11-30T00:00:00 | 4       | 2016 | 
| 50+1 Strategies     | Matt Haney                                                | 2016-09-01T00:00:00 | 2016-11-30T00:00:00 | 4       | 2016 | 
| 50+1 Strategies     | Alex Randolph                                             | 2016-09-01T00:00:00 | 2016-11-30T00:00:00 | 4       | 2016 | 
| 50+1 Strategies     | San Franciscans for the Arts & Ending Family Homelessness | 2016-09-01T00:00:00 | 2016-11-30T00:00:00 | 4       | 2016 | 
| Allbee, Nathan      | Dean Preston                                              | 2016-09-01T00:00:00 | 2016-11-30T00:00:00 | 4       | 2016 | 
| Allbee, Nathan      | Hillary Ronen                                             | 2016-09-01T00:00:00 | 2016-11-30T00:00:00 | 4       | 2016 | 
| Allbee, Nathan      | Tom Temprano                                              | 2016-09-01T00:00:00 | 2016-11-30T00:00:00 | 4       | 2016 | 
| Arroyo, Gustavo     |                                                           | 2016-09-01T00:00:00 | 2016-11-30T00:00:00 | 4       | 2016 | 
| Bedford Grove       | Scott Wiener for State Senate                             | 2016-09-01T00:00:00 | 2016-11-30T00:00:00 | 4       | 2016 | 
| Bedford Grove       | London Breed for Democratic Central Committee             | 2016-09-01T00:00:00 | 2016-11-30T00:00:00 | 4       | 2016 | 
```