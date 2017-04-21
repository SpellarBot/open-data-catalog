# Employee giving statistics - 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/employee-giving-statistics-2013-d4777) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/6z8h-tt4v) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/6z8h-tt4v/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/6z8h-tt4v/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | 6z8h-tt4v |
| Name | Employee giving statistics - 2013 |
| Attribution | King County Employee Giving Program |
| Category | Employees |
| Tags | giving, charity, donations |
| Created | 2014-09-06T00:13:02Z |
| Publication Date | 2014-09-06T00:41:19Z |

## Description

Charitable contributions from King County employees

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | series tag     | department              | Department              | text      | text        |
| Yes      | series tag     | division                | Division                | text      | text        |
| No       |                | total_pledged_to_date   | Total pledged to date   | text      | money       |
| Yes      | series tag     | employees_in_department | Employees in department | text      | number      |
| Yes      | numeric metric | employees_participating | Employees participating | number    | number      |
| Yes      | numeric metric | total_participating     | Total % Participating   | percent   | percent     |
| Yes      | numeric metric | new_employees           | New employees           | number    | number      |
| Yes      | numeric metric | 100_opp_goal            | 100 % Opp GOAL          | percent   | percent     |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = total_pledged_to_date
```

## Data Commands

```ls
series e:6z8h-tt4v d:2013-01-01T00:00:00.000Z t:division="Accounting Operations" t:department=Assessor t:employees_in_department=39 m:employees_participating=12 m:new_employees=3 m:total_participating=30.77

series e:6z8h-tt4v d:2013-01-01T00:00:00.000Z t:division="Administrative Services" t:department=Assessor t:employees_in_department=21 m:employees_participating=11 m:new_employees=3 m:total_participating=52.38

series e:6z8h-tt4v d:2013-01-01T00:00:00.000Z t:division="Commercial Property Appraisal" t:department=Assessor t:employees_in_department=53 m:employees_participating=16 m:new_employees=4 m:total_participating=30.19
```

## Meta Commands

```ls
metric m:employees_participating p:integer l:"Employees participating" t:dataTypeName=number

metric m:total_participating p:float l:"Total % Participating" t:dataTypeName=percent

metric m:new_employees p:integer l:"New employees" t:dataTypeName=number

metric m:100_opp_goal p:float l:"100 % Opp GOAL" t:dataTypeName=percent

entity e:6z8h-tt4v l:"Employee giving statistics - 2013" t:attribution="King County Employee Giving Program" t:url=https://data.kingcounty.gov/api/views/6z8h-tt4v

property e:6z8h-tt4v t:meta.view v:id=6z8h-tt4v v:category=Employees v:attributionLink=http://www.kingcounty.gov/employees/giving/ v:averageRating=0 v:name="Employee giving statistics - 2013" v:attribution="King County Employee Giving Program"

property e:6z8h-tt4v t:meta.view.license v:name="Public Domain"

property e:6z8h-tt4v t:meta.view.owner v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"

property e:6z8h-tt4v t:meta.view.tableauthor v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"
```

## Top Records

```ls
| department     | division                      | total_pledged_to_date | employees_in_department | employees_participating | total_participating | new_employees | 100_opp_goal | 
| ============== | ============================= | ===================== | ======================= | ======================= | =================== | ============= | ============ | 
| Assessor       | Accounting Operations         | 6171.119999999999     | 39                      | 12                      | 30.77               | 3             |              | 
| Assessor       | Administrative Services       | 7182.52               | 21                      | 11                      | 52.38               | 3             |              | 
| Assessor       | Commercial Property Appraisal | 5792.39               | 53                      | 16                      | 30.19               | 4             |              | 
| Assessor       | Information Services          | 2812.59               | 15                      | 3                       | 20.00               |               |              | 
| Assessor       | Residential Appraisal         | 3689.8                | 84                      | 9                       | 10.71               | 2             |              | 
| Assessor       | Special Events                | 1233.8399999999999    |                         |                         |                     |               |              | 
| Assessor Total |                               | 26882.26              | 212                     | 51                      | 24.06               | 12            | 0.00         | 
| Council        | Council Administration        | 34557.35              | 87                      | 19                      | 21.84               | 4             |              | 
| Council        | Council Auditor               | 5377.22               | 13                      | 9                       | 69.23               | 4             | 100.00       | 
| Council        | County Council                | 300                   | 9                       | 1                       | 11.11               | 1             |              | 
```