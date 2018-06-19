# Campaign Consultants - Political Contributions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-consultants-political-contributions-5f9f7) |
| Metadata | [Link](https://data.sfgov.org/api/views/tv94-tvke) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/tv94-tvke/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/tv94-tvke/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | tv94-tvke |
| Name | Campaign Consultants - Political Contributions |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | ethics, campaign consultant, contributions, political |
| Created | 2013-07-19T18:05:39Z |
| Publication Date | 2014-01-15T19:22:35Z |

## Description

Filers must report each political contribution of $100 or more to a candidate for local office, a committee controlled by a local officeholder or a candidate for local office, or a ballot measure committee whether or not the committee is controlled by a local officeholder or a candidate for local office.  Filers must report contributions of $100 or more made or delivered by the filer, or made by the filer??s client at the filer??s behest, or for which the filer acted as an agent or intermediary during the reporting period. This chart indicates the political contributions made by campaign consultants during the reporting period.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type     | Render Type   |
| ======== | ============== | ================== | ================== | ============= | ============= |
| Yes      | series tag     | committee_name     | Committee  Name    | text          | text          |
| Yes      | series tag     | consultant_name    | Consultant Name    | text          | text          |
| Yes      | numeric metric | amount             | Amount             | money         | money         |
| Yes      | time           | quarter_start_date | Quarter Start Date | calendar_date | calendar_date |
| No       |                | quarter_end_date   | Quarter End Date   | calendar_date | calendar_date |
| No       |                | quarter            | Quarter            | number        | text          |
| No       |                | year               | Year               | number        | text          |
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
series e:tv94-tvke d:2016-06-01T00:00:00.000Z t:committee_name="Joshua Arce for Supervisor" t:consultant_name="Wedge, Julie" m:amount=100

series e:tv94-tvke d:2016-06-01T00:00:00.000Z t:committee_name="Scott Wiener for State Senate" t:consultant_name="LaPointe Group" m:amount=2500

series e:tv94-tvke d:2016-06-01T00:00:00.000Z t:committee_name="San Franciscans for Sunshine" t:consultant_name="Comstock, Doug" m:amount=250
```

## Meta Commands

```ls
metric m:amount p:integer l:Amount t:dataTypeName=money

entity e:tv94-tvke l:"Campaign Consultants - Political Contributions" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/tv94-tvke

property e:tv94-tvke t:meta.view v:id=tv94-tvke v:category="City Management and Ethics" v:attributionLink=http://www.sfethics.org v:averageRating=0 v:name="Campaign Consultants - Political Contributions" v:attribution="San Francisco Ethics Commission"

property e:tv94-tvke t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:tv94-tvke t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:tv94-tvke t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```

## Top Records

```ls
| committee_name                            | consultant_name      | amount | quarter_start_date  | quarter_end_date    | quarter | year | 
| ========================================= | ==================== | ====== | =================== | =================== | ======= | ==== | 
| Joshua Arce for Supervisor                | Wedge, Julie         | 100    | 2016-06-01T00:00:00 | 2016-08-31T00:00:00 | 3       | 2016 | 
| Scott Wiener for State Senate             | LaPointe Group       | 2500   | 2016-06-01T00:00:00 | 2016-08-31T00:00:00 | 3       | 2016 | 
| San Franciscans for Sunshine              | Comstock, Doug       | 250    | 2016-06-01T00:00:00 | 2016-08-31T00:00:00 | 3       | 2016 | 
| Re-Elect London Breed for Supervisor 2016 | SCN Strategies, Inc. | 500    | 2016-06-01T00:00:00 | 2016-08-31T00:00:00 | 3       | 2016 | 
| Scott Wiener for State Senate 2016        | SCN Strategies, Inc. | 500    | 2016-06-01T00:00:00 | 2016-08-31T00:00:00 | 3       | 2016 | 
| Tom Temprano for College Board            | Golinger, Jon        | 100    | 2016-06-01T00:00:00 | 2016-08-31T00:00:00 | 3       | 2016 | 
| Shanell Williams for College Board        | Golinger, Jon        | 100    | 2016-06-01T00:00:00 | 2016-08-31T00:00:00 | 3       | 2016 | 
| Tom Temprano for City College 2016        | Lester Connect       | 250    | 2016-06-01T00:00:00 | 2016-08-31T00:00:00 | 3       | 2016 | 
| Josh Arce for D9 Supervisor               | King, Angelo         | 500    | 2016-06-01T00:00:00 | 2016-08-31T00:00:00 | 3       | 2016 | 
| London Breed for Supervisor               | Cunnie, Chris        | 500    | 2016-06-01T00:00:00 | 2016-08-31T00:00:00 | 3       | 2016 | 
```