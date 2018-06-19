# Profiles For Hawaii State and County Candidates

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/profiles-for-hawaii-state-and-county-candidates-0e03c) |
| Metadata | [Link](https://data.hawaii.gov/api/views/9ewi-sbvu) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/9ewi-sbvu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/9ewi-sbvu/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 9ewi-sbvu |
| Name | Profiles For Hawaii State and County Candidates |
| Attribution | State of Hawaii; Campaign Spending Commission |
| Category | Community |
| Tags | campaign spending commission, campaign finance, candidate, hawaii candidates, contributions, political contributions, campaign contributions, campaign spending |
| Created | 2013-06-21T01:02:11Z |
| Publication Date | 2017-03-13T21:30:04Z |

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type     | Render Type   |
| ======== | =========== | =============== | =============== | ============= | ============= |
| Yes      | series tag  | reg_no          | Reg No          | text          | text          |
| Yes      | series tag  | candidate_name  | Candidate Name  | text          | text          |
| Yes      | series tag  | office          | Office          | text          | text          |
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
series e:9ewi-sbvu d:2012-11-07T00:00:00.000Z t:office="Hawaii Council" t:election_period=2012-2014 t:candidate_name="Abbett, Richard" t:reg_no=CC11028 m:row_number.9ewi-sbvu=1

series e:9ewi-sbvu d:2014-11-05T00:00:00.000Z t:office="Hawaii Council" t:election_period=2014-2016 t:candidate_name="Abbett, Richard" t:reg_no=CC11028 m:row_number.9ewi-sbvu=2

series e:9ewi-sbvu d:2014-11-05T00:00:00.000Z t:office=House t:election_period=2014-2016 t:candidate_name="Abbett, Richard" t:reg_no=CC11314 m:row_number.9ewi-sbvu=3
```

## Meta Commands

```ls
metric m:row_number.9ewi-sbvu p:long l:"Row Number"

entity e:9ewi-sbvu l:"Profiles For Hawaii State and County Candidates" t:attribution="State of Hawaii; Campaign Spending Commission" t:url=https://data.hawaii.gov/api/views/9ewi-sbvu

property e:9ewi-sbvu t:meta.view v:id=9ewi-sbvu v:category=Community v:attributionLink=http://www.hawai.gov/campaign v:averageRating=0 v:name="Profiles For Hawaii State and County Candidates" v:attribution="State of Hawaii; Campaign Spending Commission"

property e:9ewi-sbvu t:meta.view.owner v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:displayName="Hawaii Campaign Spending Commission"

property e:9ewi-sbvu t:meta.view.tableauthor v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:roleName=editor v:displayName="Hawaii Campaign Spending Commission"
```

## Top Records

```ls
| reg_no  | candidate_name    | office         | election_period | ep_start_date       | ep_end_date         | 
| ======= | ================= | ============== | =============== | =================== | =================== | 
| CC11028 | Abbett, Richard   | Hawaii Council | 2012-2014       | 2012-11-07T00:00:00 | 2014-11-04T00:00:00 | 
| CC11028 | Abbett, Richard   | Hawaii Council | 2014-2016       | 2014-11-05T00:00:00 | 2016-11-08T00:00:00 | 
| CC11314 | Abbett, Richard   | House          | 2014-2016       | 2014-11-05T00:00:00 | 2016-11-08T00:00:00 | 
| CC11314 | Abbett, Richard   | House          | 2016-2018       | 2016-11-09T00:00:00 | 2018-11-06T00:00:00 | 
| CC10496 | Abe, Michael      | House          | 2006-2008       | 2006-11-08T00:00:00 | 2008-11-04T00:00:00 | 
| CC10529 | Abercrombie, Neil | Governor       | 2006-2008       | 2006-11-08T00:00:00 | 2010-11-02T00:00:00 | 
| CC10529 | Abercrombie, Neil | Governor       | 2008-2010       | 2006-11-08T00:00:00 | 2010-11-02T00:00:00 | 
| CC10529 | Abercrombie, Neil | Governor       | 2010-2012       | 2010-11-03T00:00:00 | 2014-11-04T00:00:00 | 
| CC10529 | Abercrombie, Neil | Governor       | 2012-2014       | 2010-11-03T00:00:00 | 2014-11-04T00:00:00 | 
| CC10529 | Abercrombie, Neil | Governor       | 2014-2016       | 2014-11-05T00:00:00 | 2018-11-06T00:00:00 | 
```