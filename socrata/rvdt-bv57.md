# Lobbyist Activity - Activity Expenses

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lobbyist-activity-activity-expenses-ac28c) |
| Metadata | [Link](https://data.sfgov.org/api/views/rvdt-bv57) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/rvdt-bv57/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/rvdt-bv57/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | rvdt-bv57 |
| Name | Lobbyist Activity - Activity Expenses |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | ethics, lobbyist, activity, expense |
| Created | 2012-04-26T23:04:37Z |
| Publication Date | 2014-08-07T18:34:13Z |

## Description

"Activity expenses" means any expense incurred or payment made by a lobbyist or a lobbyist's client at the behest of the lobbyist, or arranged by a lobbyist or a lobbyist's client at the behest of the lobbyist, which benefits in whole or in part any: officer of the City and County; candidate for City and County office; aide to a member of the Board of Supervisors; or member of the immediate family or the registered domestic partner of an officer, candidate, or aide to a member of the Board of Supervisors. An expense or payment is not an "activity expense" unless it is incurred or made within three months of a contact with the officer, candidate, or Supervisor's aide who benefits from the expense or payment, or whose immediate family member or registered domestic partner benefits from the expense or payment. "Activity expenses" include honoraria, consulting fees, salaries, and any other thing of value totaling more than $25 in value in a consecutive three-month period, but do not include political contributions.Activity expenses are disclosed by lobbyists registered with the Ethics Commission on a monthly basis.  This dataset updates automatically every night.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type     | Render Type   |
| ======== | ============== | =================== | =================== | ============= | ============= |
| Yes      | time           | date                | Date                | calendar_date | calendar_date |
| Yes      | series tag     | official            | Official            | text          | text          |
| Yes      | series tag     | official_department | Official_Department | text          | text          |
| Yes      | numeric metric | amount              | Amount              | money         | money         |
| Yes      | series tag     | lobbyist            | Lobbyist            | text          | text          |
| Yes      | series tag     | lobbyist_firm       | Lobbyist_Firm       | text          | text          |
| Yes      | series tag     | payee               | Payee               | text          | text          |
| Yes      | series tag     | description         | Description         | text          | text          |
| Yes      | series tag     | salary              | Salary              | text          | text          |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:rvdt-bv57 d:2015-03-04T00:00:00.000Z t:lobbyist_firm="San Francisco Chamber Of Commerce" t:description="ANNUAL CHAMBER OF COMMERCE CITYBEAT BREAKFAST / ANNUAL CHAMBER OF COMMERCE BREAKFAST" t:lobbyist="Lazarus, Jim" t:payee="San Francisco Chamber Of Commerce" t:official="Montejano, Jess" t:salary=No t:official_department="Board Of Supervisors" m:amount=54.02

series e:rvdt-bv57 d:2016-09-27T00:00:00.000Z t:lobbyist_firm="Google, Inc." t:description="Food and Beverage / Food and Beverage" t:lobbyist="Prozan, Rebecca" t:payee="Google Catering And Events" t:official="Torres, Joaquin" t:salary=No t:official_department="Housing Authority Commission" m:amount=130.69

series e:rvdt-bv57 d:2014-12-31T00:00:00.000Z t:lobbyist_firm="San Francisco Chamber Of Commerce" t:description="$1,000.01 - $10,000 COMM. PROPERTY SHARE SALARY TO CHAMBER EMPLOYEE / COMM. PROPERTY SHARE OF SALARY TO CHAMBER EMPLOYEE" t:lobbyist="Lazarus, Jim" t:payee="Lazarus, James" t:official="Lazarus, Ann" t:salary=Yes t:official_department=None m:amount=0
```

## Meta Commands

```ls
metric m:amount p:double l:Amount t:dataTypeName=money

entity e:rvdt-bv57 l:"Lobbyist Activity - Activity Expenses" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/rvdt-bv57

property e:rvdt-bv57 t:meta.view v:id=rvdt-bv57 v:category="City Management and Ethics" v:attributionLink=http://www.sfethics.org/ethics/2012/01/lobbyist-database-api.html v:averageRating=0 v:name="Lobbyist Activity - Activity Expenses" v:attribution="San Francisco Ethics Commission"

property e:rvdt-bv57 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:rvdt-bv57 t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:rvdt-bv57 t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```

## Top Records

```ls
| date                | official            | official_department          | amount | lobbyist        | lobbyist_firm                     | payee                             | description                                                                                                                               | salary | 
| =================== | =================== | ============================ | ====== | =============== | ================================= | ================================= | ========================================================================================================================================= | ====== | 
| 2015-03-04T00:00:00 | Montejano, Jess     | Board Of Supervisors         | 54.02  | Lazarus, Jim    | San Francisco Chamber Of Commerce | San Francisco Chamber Of Commerce | ANNUAL CHAMBER OF COMMERCE CITYBEAT BREAKFAST / ANNUAL CHAMBER OF COMMERCE BREAKFAST                                                      | No     | 
| 2016-09-27T00:00:00 | Torres, Joaquin     | Housing Authority Commission | 130.69 | Prozan, Rebecca | Google, Inc.                      | Google Catering And Events        | Food and Beverage / Food and Beverage                                                                                                     | No     | 
| 2014-12-31T00:00:00 | Lazarus, Ann        | None                         | 0      | Lazarus, Jim    | San Francisco Chamber Of Commerce | Lazarus, James                    | $1,000.01 - $10,000 COMM. PROPERTY SHARE SALARY TO CHAMBER EMPLOYEE / COMM. PROPERTY SHARE OF SALARY TO CHAMBER EMPLOYEE                  | Yes    | 
| 2016-12-29T00:00:00 | Nuru, Mohammed      | Public Works Department Of   | 100    | Flood, Karin    | Union Square Bid                  | La Cocina                         | HOLIDAY GIFT - TRUE SOURCE BY UNION SQUARE BUSINESS IMPROVEMENT DISTRICT / HOLIDAY GIFT                                                   | No     | 
| 2016-03-31T00:00:00 | Lazarus, Ann        | None                         | 0      | Lazarus, Jim    | San Francisco Chamber Of Commerce | Lazarus, James                    | $1,000.01 - $10,000 COMM. PROPERTY SHARE SALARY TO CHAMBER EMPLOYEE / $1,000.01 - $10,000 COMM. PROPERTY SHARE SALARY TO CHAMBER EMPLOYEE | Yes    | 
| 2016-01-28T00:00:00 | Dorian, Mark        | City Of San Francisco        | 48.46  | Prozan, Rebecca | Google, Inc.                      | Google Catering And Events        | Widely Attended Event / Widely Attended Event                                                                                             | No     | 
| 2015-05-01T00:00:00 | Hayes-White, Joanne | Sffd                         | 88.7   | Flood, Karin    | Karin Flood                       | Usbid                             | 1 for Annual Luncheon at Westin St. Francis / 1 for USBID Annual Luncheon at Westin St. Francis                                           | No     | 
| 2010-06-18T00:00:00 | Jack Knowles, Jack  | Self Employed                | 940    | Lesser, Philip  | Philip Lesser                     | City & County Of San Francisco    | Permit Fee                                                                                                                                | No     | 
| 2015-11-30T00:00:00 | Lazarus, Ann        | None                         | 0      | Lazarus, Jim    | San Francisco Chamber Of Commerce | Lazarus, James                    | $1,000.01 - $10,000 COMM. PROPERTY SHARE SALARY TO CHAMBER EMPLOYEE / $1,000.01 - $10,000 COMM. PROPERTY SHARE SALARY TO CHAMBER EMPLOYEE | No     | 
| 2015-05-31T00:00:00 | Lazarus, Ann        | None                         | 0      | Lazarus, Jim    | San Francisco Chamber Of Commerce | Lazarus, James                    | $1,000.01 - $10,000 COMM. PROPERTY SHARE SALARY TO CHAMBER EMPLOYEE / COMM. PROPERTY SHARE OF SALARY TO CHAMBER EMPLOYEE                  | Yes    | 
```