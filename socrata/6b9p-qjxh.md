# Total Pensionable Salary for Teachers Retirement Board Members FY 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/total-pensionable-salary-for-teachers-retirement-board-members-fy-2015) |
| Metadata | [Link](https://data.ct.gov/api/views/6b9p-qjxh) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/6b9p-qjxh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/6b9p-qjxh/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 6b9p-qjxh |
| Name | Total Pensionable Salary for Teachers Retirement Board Members FY 2015 |
| Attribution | Connecticut Teachers Retirement Board |
| Category | Government |
| Tags | teachers, retirement, pension, salary |
| Created | 2016-09-28T15:25:00Z |
| Publication Date | 2016-09-28T15:35:02Z |

## Description

A listing of total salaries paid to all members of the Teachers Retirement Board, by town or district.

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| Yes      | series tag     | town_number              | Town Number              | text      | number      |
| Yes      | series tag     | town_or_district         | Town or District         | text      | text        |
| Yes      | numeric metric | total_pensionable_salary | Total Pensionable Salary | money     | money       |
| Yes      | numeric metric | count_of_members         | Count of members         | number    | number      |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:6b9p-qjxh d:2015-01-01T00:00:00.000Z t:town_number=241 t:town_or_district=ACES m:total_pensionable_salary=21659028.77 m:count_of_members=293

series e:6b9p-qjxh d:2015-01-01T00:00:00.000Z t:town_number=307 t:town_or_district="AF BRIDGEPORT ACADEMY" m:total_pensionable_salary=1859170 m:count_of_members=36

series e:6b9p-qjxh d:2015-01-01T00:00:00.000Z t:town_number=309 t:town_or_district="AF HARTFORD ACADEMY" m:total_pensionable_salary=2641423 m:count_of_members=62
```

## Meta Commands

```ls
metric m:total_pensionable_salary p:double l:"Total Pensionable Salary" t:dataTypeName=money

metric m:count_of_members p:integer l:"Count of members" t:dataTypeName=number

entity e:6b9p-qjxh l:"Total Pensionable Salary for Teachers Retirement Board Members FY 2015" t:attribution="Connecticut Teachers Retirement Board" t:url=https://data.ct.gov/api/views/6b9p-qjxh

property e:6b9p-qjxh t:meta.view v:id=6b9p-qjxh v:category=Government v:attributionLink=http://www.ct.gov/trb v:averageRating=0 v:name="Total Pensionable Salary for Teachers Retirement Board Members FY 2015" v:attribution="Connecticut Teachers Retirement Board"

property e:6b9p-qjxh t:meta.view.license v:name="Public Domain"

property e:6b9p-qjxh t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:6b9p-qjxh t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| town_number | town_or_district      | total_pensionable_salary | count_of_members | 
| =========== | ===================== | ======================== | ================ | 
| 241         | ACES                  | 21659028.77              | 293              | 
| 307         | AF BRIDGEPORT ACADEMY | 1859170.00               | 36               | 
| 309         | AF HARTFORD ACADEMY   | 2641423.00               | 62               | 
| 29          | AMISTAD ACADEMY       | 4334275.56               | 84               | 
| 1           | ANDOVER BD OF ED      | 2142799.90               | 31               | 
| 2           | ANSONIA BD OF ED      | 12465909.32              | 206              | 
| 3           | ASHFORD BD OF ED      | 2841461.66               | 47               | 
| 244         | ASNUNTUCK CTC         | 203125.31                | 8                | 
| 4           | AVON BD OF ED         | 26227525.57              | 301              | 
| 5           | BARKHAMSTED BD OF ED  | 1767181.40               | 27               | 
```