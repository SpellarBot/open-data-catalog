# Campaign Finance - Status of Voluntary Expenditure Ceiling VECs in November 3, 2015 Election

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-finance-status-of-voluntary-expenditure-ceiling-vecs-in-november-3-2015-election) |
| Metadata | [Link](https://data.sfgov.org/api/views/t2mb-q3sb) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/t2mb-q3sb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/t2mb-q3sb/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | t2mb-q3sb |
| Name | Campaign Finance - Status of Voluntary Expenditure Ceiling VECs in November 3, 2015 Election |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Created | 2015-06-26T17:15:33Z |
| Publication Date | 2015-06-26T17:19:42Z |

## Description

Under S.F. Campaign and Governmental Conduct Code 1.128, a candidate who wishes to accept the voluntary expenditure ceiling must file Form SFEC-128 no later than the August 7, 2015 deadline for filing nomination papers.In a race where at least one candidate has accepted the VEC, all candidates running for office in the same race must file Form SFEC 134(b) within 24 hours of receiving contributions, making expenditures, or having funds that exceed 100 percent of the applicable VEC.

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
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:t2mb-q3sb d:2015-01-01T00:00:00.000Z t:status_of_vec="The ceiling is not in place." t:city_elective_office="City Attorney" m:amount_of_vec=243000

series e:t2mb-q3sb d:2015-01-01T00:00:00.000Z t:status_of_vec="The ceiling is not in place." t:city_elective_office="Community College Board" m:amount_of_vec=104000

series e:t2mb-q3sb d:2015-01-01T00:00:00.000Z t:status_of_vec="The ceiling is not in place." t:city_elective_office="District Attorney" m:amount_of_vec=243000
```

## Meta Commands

```ls
metric m:amount_of_vec p:double l:"Amount of VEC" t:dataTypeName=money

entity e:t2mb-q3sb l:"Campaign Finance - Status of Voluntary Expenditure Ceiling VECs in November 3, 2015 Election" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/t2mb-q3sb

property e:t2mb-q3sb t:meta.view v:id=t2mb-q3sb v:category="City Management and Ethics" v:attributionLink=http://www.sfethics.org v:averageRating=0 v:name="Campaign Finance - Status of Voluntary Expenditure Ceiling VECs in November 3, 2015 Election" v:attribution="San Francisco Ethics Commission"

property e:t2mb-q3sb t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:t2mb-q3sb t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:t2mb-q3sb t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```

## Top Records

```ls
| city_elective_office    | amount_of_vec | status_of_vec                | 
| ======================= | ============= | ============================ | 
| City Attorney           | 243000.00     | The ceiling is not in place. | 
| Community College Board | 104000.00     | The ceiling is not in place. | 
| District Attorney       | 243000.00     | The ceiling is not in place. | 
| Sheriff                 | 243000.00     | The ceiling is not in place. | 
| Treasurer               | 243000.00     | The ceiling is not in place. | 
```