# Employee giving statistics - 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/employee-giving-statistics-2014-edc92) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/szvh-rcw5) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/szvh-rcw5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/szvh-rcw5/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | szvh-rcw5 |
| Name | Employee giving statistics - 2014 |
| Attribution | King County Employee Giving Program |
| Category | Employees |
| Tags | giving, charity, donations |
| Created | 2014-09-16T23:18:52Z |
| Publication Date | 2015-01-23T19:43:21Z |

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
Value = 2014
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = total_pledged_to_date
```

## Data Commands

```ls
series e:szvh-rcw5 d:2014-01-01T00:00:00.000Z t:division=Administration t:department="KCE - King County Elections" t:employees_in_department=14 m:employees_participating=7 m:new_employees=2 m:total_participating=50

series e:szvh-rcw5 d:2014-01-01T00:00:00.000Z t:division="Ballot Processing & Delivery" t:department="KCE - King County Elections" t:employees_in_department=13 m:employees_participating=5 m:total_participating=38.46

series e:szvh-rcw5 d:2014-01-01T00:00:00.000Z t:division="Technical Services" t:department="KCE - King County Elections" t:employees_in_department=15 m:employees_participating=3 m:new_employees=1 m:total_participating=20
```

## Meta Commands

```ls
metric m:employees_participating p:integer l:"Employees participating" t:dataTypeName=number

metric m:total_participating p:float l:"Total % Participating" t:dataTypeName=percent

metric m:new_employees p:integer l:"New employees" t:dataTypeName=number

metric m:100_opp_goal p:float l:"100 % Opp GOAL" t:dataTypeName=percent

entity e:szvh-rcw5 l:"Employee giving statistics - 2014" t:attribution="King County Employee Giving Program" t:url=https://data.kingcounty.gov/api/views/szvh-rcw5

property e:szvh-rcw5 t:meta.view v:id=szvh-rcw5 v:category=Employees v:attributionLink=http://www.kingcounty.gov/employees/giving/ v:averageRating=0 v:name="Employee giving statistics - 2014" v:attribution="King County Employee Giving Program"

property e:szvh-rcw5 t:meta.view.license v:name="Public Domain"

property e:szvh-rcw5 t:meta.view.owner v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"

property e:szvh-rcw5 t:meta.view.tableauthor v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"
```

## Top Records

```ls
| department                          | division                     | total_pledged_to_date | employees_in_department | employees_participating | total_participating | new_employees | 100_opp_goal | 
| =================================== | ============================ | ===================== | ======================= | ======================= | =================== | ============= | ============ | 
| KCE - King County Elections         | Administration               | 3587.56               | 14                      | 7                       | 50.00               | 2             |              | 
| KCE - King County Elections         | Ballot Processing & Delivery | 4656.18               | 13                      | 5                       | 38.46               |               |              | 
| KCE - King County Elections         | Technical Services           | 1560.34               | 15                      | 3                       | 20.00               | 1             |              | 
| KCE - King County Elections         | Voter Services               | 2775.12               | 22                      | 13                      | 59.09               | 3             |              | 
| KCE - King County Elections         | Special Events               | 4895.56               |                         |                         |                     |               |              | 
| KCE - King County Elections Total   |                              | 17474.76              | 64                      | 28                      | 43.75               | 6             |              | 
| DPER-Permitting & Environ Rev       | Dept Administration          | 10091.15              | 11                      | 7                       | 63.64               | 5             |              | 
| DPER-Permitting & Environ Rev       | Permitting                   | 16736.29              | 75                      | 30                      | 40.00               | 14            |              | 
| DPER-Permitting & Environ Rev       | Special Events               | 1251.5                |                         |                         |                     |               |              | 
| DPER-Permitting & Environ Rev Total |                              | 28078.94              | 86                      | 37                      | 43.02               | 19            |              | 
```