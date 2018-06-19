# Affidavits Filed By Hawaii State and County Candidates

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/affidavits-filed-by-hawaii-state-and-county-candidates-2560c) |
| Metadata | [Link](https://data.hawaii.gov/api/views/3fbc-bviy) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/3fbc-bviy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/3fbc-bviy/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 3fbc-bviy |
| Name | Affidavits Filed By Hawaii State and County Candidates |
| Attribution | State of Hawaii; Campaign Spending Commission |
| Category | Community |
| Tags | ampaign spending commission, campaign finance, candidate, hawaii candidates, affidavit, expenditure limits |
| Created | 2014-07-19T23:56:04Z |
| Publication Date | 2016-12-12T20:11:15Z |

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                             | Data Type     | Render Type   |
| ======== | ============== | ============================== | ================================ | ============= | ============= |
| Yes      | series tag     | candidate_name                 | Candidate Name                   | text          | text          |
| Yes      | time           | affidavit_filing_date          | Affidavit Filing Date            | calendar_date | calendar_date |
| Yes      | numeric metric | expenditure_limit_per_election | Expenditure Limit (Per Election) | money         | money         |
| Yes      | series tag     | office                         | Office                           | text          | text          |
| Yes      | series tag     | district                       | District                         | text          | text          |
| Yes      | series tag     | county                         | County                           | text          | text          |
| Yes      | series tag     | reg_no                         | Reg No                           | text          | text          |
| Yes      | series tag     | election_period                | Election Period                  | text          | text          |
| Yes      | numeric metric | election                       | Election                         | number        | text          |
| No       |                | np                             | NP                               | calendar_date | calendar_date |
```

## Time Field

```ls
Value = affidavit_filing_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = np
```

## Data Commands

```ls
series e:3fbc-bviy d:2014-01-21T00:00:00.000Z t:office=OHA t:election_period=2010-2014 t:candidate_name="Lum Lee, Christopher-Travis" t:district=Oahu t:reg_no=CC10992 m:expenditure_limit_per_election=127777 m:election=2014

series e:3fbc-bviy d:2014-01-27T00:00:00.000Z t:office="Maui Council" t:election_period=2012-2014 t:county=Maui t:candidate_name="Baisa, Gladys" t:district=Upcountry t:reg_no=CC10330 m:expenditure_limit_per_election=106736 m:election=2014

series e:3fbc-bviy d:2014-02-03T00:00:00.000Z t:office=House t:election_period=2012-2014 t:candidate_name="Grace, Janet" t:district=22 t:reg_no=CC11015 m:expenditure_limit_per_election=14421 m:election=2014
```

## Meta Commands

```ls
metric m:expenditure_limit_per_election p:integer l:"Expenditure Limit (Per Election)" t:dataTypeName=money

metric m:election p:integer l:Election t:dataTypeName=number

entity e:3fbc-bviy l:"Affidavits Filed By Hawaii State and County Candidates" t:attribution="State of Hawaii; Campaign Spending Commission" t:url=https://data.hawaii.gov/api/views/3fbc-bviy

property e:3fbc-bviy t:meta.view v:id=3fbc-bviy v:category=Community v:attributionLink=http://www.hawaii.gov/campaign v:averageRating=0 v:name="Affidavits Filed By Hawaii State and County Candidates" v:attribution="State of Hawaii; Campaign Spending Commission"

property e:3fbc-bviy t:meta.view.owner v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:displayName="Hawaii Campaign Spending Commission"

property e:3fbc-bviy t:meta.view.tableauthor v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:roleName=editor v:displayName="Hawaii Campaign Spending Commission"
```

## Top Records

```ls
| candidate_name              | affidavit_filing_date | expenditure_limit_per_election | office           | district  | county   | reg_no  | election_period | election | np                  | 
| =========================== | ===================== | ============================== | ================ | ========= | ======== | ======= | =============== | ======== | =================== | 
| Lum Lee, Christopher-Travis | 2014-01-21T00:00:00   | 127777                         | OHA              | Oahu      |          | CC10992 | 2010-2014       | 2014     | 2014-02-12T00:00:00 | 
| Baisa, Gladys               | 2014-01-27T00:00:00   | 106736                         | Maui Council     | Upcountry | Maui     | CC10330 | 2012-2014       | 2014     | 2014-02-07T00:00:00 | 
| Grace, Janet                | 2014-02-03T00:00:00   | 14421                          | House            | 22        |          | CC11015 | 2012-2014       | 2014     | 2014-03-24T00:00:00 | 
| Iwasa, Natalie              | 2014-02-05T00:00:00   | 84652                          | Honolulu Council | 4         | Honolulu | CC10998 | 2010-2014       | 2014     | 2014-02-06T00:00:00 | 
| Kualii, KipuKai             | 2014-02-05T00:00:00   | 52118                          | Kauai Council    | At-Large  | Kauai    | CC10353 | 2012-2014       | 2014     | 2014-02-05T00:00:00 | 
| San Buenaventura, Joy       | 2014-02-10T00:00:00   | 18218                          | House            | 4         |          | CC11014 | 2012-2014       | 2014     | 2014-02-10T00:00:00 | 
| Makekau, Kealii             | 2014-02-11T00:00:00   | 127777                         | OHA              | At-Large  |          | CC10705 | 2010-2014       | 2014     | 2014-02-19T00:00:00 | 
| Greene, Madeline            | 2014-02-12T00:00:00   | 14381                          | Hawaii Council   | 4         | Hawaii   | CC11039 | 2012-2014       | 2014     | 2014-02-12T00:00:00 | 
| Poti, LuAnn                 | 2014-02-14T00:00:00   | 14757                          | House            | 35        |          | CC11018 | 2012-2014       | 2014     | 2014-06-02T00:00:00 | 
| Paltin, Tamara              | 2014-02-18T00:00:00   | 152480                         | Mayor            |           | Maui     | CC11010 | 2010-2014       | 2014     | 2014-02-18T00:00:00 | 
```