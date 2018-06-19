# Campaign Finance - Status Of Voluntary Expenditure Ceiling VECs In November 4, 2014 Election

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-finance-status-of-voluntary-expenditure-ceiling-vecs-in-november-4-2014-election-f4b60) |
| Metadata | [Link](https://data.sfgov.org/api/views/4qsp-ix5t) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/4qsp-ix5t/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/4qsp-ix5t/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | 4qsp-ix5t |
| Name | Campaign Finance - Status Of Voluntary Expenditure Ceiling VECs In November 4, 2014 Election |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | voluntary, expenditure, ceiling, campaign, finance, ethics, vec, november 4, 2014, election |
| Created | 2013-12-09T20:43:48Z |
| Publication Date | 2014-08-11T21:03:47Z |

## Description

Under S.F. Campaign and Governmental Conduct Code 1.128, a candidate who wishes to accept the voluntary expenditure ceiling must file Form SFEC-128 no later than the August 8, 2014 deadline for filing nomination papers. In a race where at least one candidate has accepted the VEC, all candidates running for office in the same race must file Form SFEC 134(b) within 24 hours of receiving contributions, making expenditures, or having funds that exceed 100 percent of the applicable VEC. In addition, any person other than a candidate committee who makes or incurs expenditures for the purpose of distributing independent expenditures, electioneering communications, or member communications that clearly identify any candidate that equals or exceeds $5,000 per candidate, must within 24 hours of each time it reaches the $5,000 threshold file a Third Party Disclosure Form.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| Yes      | series tag     | city_elective_office | City Elective Office | text      | text        |
| Yes      | numeric metric | amount_of_vec        | Amount of VEC        | money     | money       |
| Yes      | series tag     | status_of_vec        | Status of VEC        | text      | text        |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:4qsp-ix5t d:2014-01-01T00:00:00.000Z t:status_of_vec="The ceiling is not in place." t:city_elective_office=Assessor m:amount_of_vec=243000

series e:4qsp-ix5t d:2014-01-01T00:00:00.000Z t:status_of_vec="The ceiling is in place." t:city_elective_office="Board of Education" m:amount_of_vec=104000

series e:4qsp-ix5t d:2014-01-01T00:00:00.000Z t:status_of_vec="The ceiling is not in place." t:city_elective_office="Community College Board" m:amount_of_vec=104000
```

## Meta Commands

```ls
metric m:amount_of_vec p:integer l:"Amount of VEC" t:dataTypeName=money

entity e:4qsp-ix5t l:"Campaign Finance - Status Of Voluntary Expenditure Ceiling VECs In November 4, 2014 Election" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/4qsp-ix5t

property e:4qsp-ix5t t:meta.view v:id=4qsp-ix5t v:category="City Management and Ethics" v:attributionLink=http://www.sfethics.org v:averageRating=0 v:name="Campaign Finance - Status Of Voluntary Expenditure Ceiling VECs In November 4, 2014 Election" v:attribution="San Francisco Ethics Commission"

property e:4qsp-ix5t t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:4qsp-ix5t t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:4qsp-ix5t t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```

## Top Records

```ls
| city_elective_office    | amount_of_vec | status_of_vec                | 
| ======================= | ============= | ============================ | 
| Assessor                | 243000        | The ceiling is not in place. | 
| Board of Education      | 104000        | The ceiling is in place.     | 
| Community College Board | 104000        | The ceiling is not in place. | 
| Public Defender         | 243000        | The ceiling is not in place. | 
```