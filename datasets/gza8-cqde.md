# Total Pensionable Salary for Teachers Retirement Board Members FY 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/total-pensionable-salary-for-teachers-retirement-board-members-fy-2016) |
| Metadata | [Link](https://data.ct.gov/api/views/gza8-cqde) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/gza8-cqde/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/gza8-cqde/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | gza8-cqde |
| Name | Total Pensionable Salary for Teachers Retirement Board Members FY 2016 |
| Attribution | Connecticut Teachers Retirement Board |
| Tags | teachers, retirement, pension, salary |
| Created | 2016-09-28T15:36:17Z |
| Publication Date | 2016-09-28T15:52:42Z |

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
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:gza8-cqde d:2016-01-01T00:00:00.000Z t:town_number=241 t:town_or_district=ACES m:total_pensionable_salary=22736206.5 m:count_of_members=302

series e:gza8-cqde d:2016-01-01T00:00:00.000Z t:town_number=307 t:town_or_district="AF BRIDGEPORT ACADEMY" m:total_pensionable_salary=1303248.74 m:count_of_members=31

series e:gza8-cqde d:2016-01-01T00:00:00.000Z t:town_number=309 t:town_or_district="AF HARTFORD ACADEMY" m:total_pensionable_salary=4088994.33 m:count_of_members=81
```

## Meta Commands

```ls
metric m:total_pensionable_salary p:double l:"Total Pensionable Salary" t:dataTypeName=money

metric m:count_of_members p:integer l:"Count of members" t:dataTypeName=number

entity e:gza8-cqde l:"Total Pensionable Salary for Teachers Retirement Board Members FY 2016" t:attribution="Connecticut Teachers Retirement Board" t:url=https://data.ct.gov/api/views/gza8-cqde

property e:gza8-cqde t:meta.view v:id=gza8-cqde v:attributionLink=http://www.ct.gov/trb v:averageRating=0 v:name="Total Pensionable Salary for Teachers Retirement Board Members FY 2016" v:attribution="Connecticut Teachers Retirement Board"

property e:gza8-cqde t:meta.view.license v:name="Public Domain"

property e:gza8-cqde t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:gza8-cqde t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| town_number | town_or_district      | total_pensionable_salary | count_of_members | 
| =========== | ===================== | ======================== | ================ | 
| 241         | ACES                  | 22736206.50              | 302              | 
| 307         | AF BRIDGEPORT ACADEMY | 1303248.74               | 31               | 
| 309         | AF HARTFORD ACADEMY   | 4088994.33               | 81               | 
| 29          | AMISTAD ACADEMY       | 4224533.34               | 77               | 
| 1           | ANDOVER BD OF ED      | 2076994.08               | 30               | 
| 2           | ANSONIA BD OF ED      | 13028441.66              | 214              | 
| 3           | ASHFORD BD OF ED      | 3017490.90               | 50               | 
| 244         | ASNUNTUCK CTC         | 227625.79                | 8                | 
| 4           | AVON BD OF ED         | 26711928.01              | 305              | 
| 5           | BARKHAMSTED BD OF ED  | 1712921.00               | 25               | 
```