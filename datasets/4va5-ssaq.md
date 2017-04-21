# Campaign Finance - Status Of Voluntary Expenditure Ceiling VECs in November 8, 2016 Election

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-finance-status-of-voluntary-expenditure-ceiling-vecs-in-november-8-2016-election) |
| Metadata | [Link](https://data.sfgov.org/api/views/4va5-ssaq) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/4va5-ssaq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/4va5-ssaq/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | 4va5-ssaq |
| Name | Campaign Finance - Status Of Voluntary Expenditure Ceiling VECs in November 8, 2016 Election |
| Attribution | San Francisco |
| Category | City Management and Ethics |
| Tags | campaign finance, election, vec |
| Created | 2016-03-03T21:59:40Z |
| Publication Date | 2016-03-03T22:03:54Z |

## Description

Under S.F. Campaign and Governmental Conduct Code 1.128, a candidate who wishes to accept the voluntary expenditure ceiling must file Form SFEC-128 no later than the August 12, 2016 deadline for filing nomination papers.In a race where at least one candidate has accepted the VEC, all candidates running for office in the same race must file Form SFEC 134(b) within 24 hours of receiving contributions, making expenditures, or having funds that exceed 100 percent of the applicable VEC.

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
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:4va5-ssaq d:2016-01-01T00:00:00.000Z t:status_of_vec="The ceiling is not in place." t:city_elective_office="Board of Education" m:amount_of_vec=104000

series e:4va5-ssaq d:2016-01-01T00:00:00.000Z t:status_of_vec="The ceiling is not in place." t:city_elective_office="Community College Board" m:amount_of_vec=104000
```

## Meta Commands

```ls
metric m:amount_of_vec p:integer l:"Amount of VEC" t:dataTypeName=money

entity e:4va5-ssaq l:"Campaign Finance - Status Of Voluntary Expenditure Ceiling VECs in November 8, 2016 Election" t:attribution="San Francisco" t:url=https://data.sfgov.org/api/views/4va5-ssaq

property e:4va5-ssaq t:meta.view v:id=4va5-ssaq v:category="City Management and Ethics" v:attributionLink=http://www.sfethics.org v:averageRating=0 v:name="Campaign Finance - Status Of Voluntary Expenditure Ceiling VECs in November 8, 2016 Election" v:attribution="San Francisco"

property e:4va5-ssaq t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:4va5-ssaq t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:4va5-ssaq t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```

## Top Records

```ls
| city_elective_office    | amount_of_vec | status_of_vec                | 
| ======================= | ============= | ============================ | 
| Board of Education      | 104000        | The ceiling is not in place. | 
| Community College Board | 104000        | The ceiling is not in place. | 
```