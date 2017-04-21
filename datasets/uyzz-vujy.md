# Employee Giving Statistics - 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/employee-giving-statistics-2015) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/uyzz-vujy) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/uyzz-vujy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/uyzz-vujy/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | uyzz-vujy |
| Name | Employee Giving Statistics - 2015 |
| Attribution | King County Employee Giving Program |
| Category | Employees |
| Tags | giving, charity, donations |
| Created | 2015-10-01T19:21:44Z |
| Publication Date | 2016-09-30T18:37:20Z |

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
| Yes      | series tag     | 100_opp_goal            | 100 % Opp GOAL          | text      | text        |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = total_pledged_to_date
```

## Data Commands

```ls
series e:uyzz-vujy d:2015-01-01T00:00:00.000Z t:division="Administrative Services" t:department="DAJD-Adult & Juvnile Detention" t:employees_in_department=27 m:employees_participating=15 m:new_employees=5 m:total_participating=55.56

series e:uyzz-vujy d:2015-01-01T00:00:00.000Z t:division="Community Corrections" t:department="DAJD-Adult & Juvnile Detention" t:employees_in_department=46 m:employees_participating=9 m:new_employees=2 m:total_participating=19.57

series e:uyzz-vujy d:2015-01-01T00:00:00.000Z t:division=Juvenile t:department="DAJD-Adult & Juvnile Detention" t:employees_in_department=126 m:employees_participating=6 m:total_participating=4.76
```

## Meta Commands

```ls
metric m:employees_participating p:integer l:"Employees participating" t:dataTypeName=number

metric m:total_participating p:float l:"Total % Participating" t:dataTypeName=percent

metric m:new_employees p:integer l:"New employees" t:dataTypeName=number

entity e:uyzz-vujy l:"Employee Giving Statistics - 2015" t:attribution="King County Employee Giving Program" t:url=https://data.kingcounty.gov/api/views/uyzz-vujy

property e:uyzz-vujy t:meta.view v:id=uyzz-vujy v:category=Employees v:attributionLink=http://www.kingcounty.gov/audience/employees/giving/ v:averageRating=0 v:name="Employee Giving Statistics - 2015" v:attribution="King County Employee Giving Program"

property e:uyzz-vujy t:meta.view.license v:name="Public Domain"

property e:uyzz-vujy t:meta.view.owner v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"

property e:uyzz-vujy t:meta.view.tableauthor v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"
```

## Top Records

```ls
| department                           | division                   | total_pledged_to_date | employees_in_department | employees_participating | total_participating | new_employees | 100_opp_goal | 
| ==================================== | ========================== | ===================== | ======================= | ======================= | =================== | ============= | ============ | 
| DAJD-Adult & Juvnile Detention       | Administrative Services    | 9051.51               | 27                      | 15                      | 55.56               | 5             |              | 
| DAJD-Adult & Juvnile Detention       | Community Corrections      | 8303.21               | 46                      | 9                       | 19.57               | 2             |              | 
| DAJD-Adult & Juvnile Detention       | Juvenile                   | 1749.11               | 126                     | 6                       | 4.76                |               |              | 
| DAJD-Adult & Juvnile Detention       | KCCF                       | 11832.26              | 435                     | 25                      | 5.75                | 11            |              | 
| DAJD-Adult & Juvnile Detention       | MRJC                       | 6384.22               | 227                     | 14                      | 6.17                | 8             |              | 
| DAJD-Adult & Juvnile Detention       | Special Events             | 0.00                  |                         |                         |                     |               |              | 
| DAJD-Adult & Juvnile Detention Total |                            | 37320.31              | 861                     | 69                      | 8.01                | 26            |              | 
| DCHS - Community & Human Srvcs       | Community Services         | 22944.44              | 115                     | 43                      | 37.39               | 16            |              | 
| DCHS - Community & Human Srvcs       | Developmental Disabilities | 8105.17               | 16                      | 11                      | 68.75               | 2             |              | 
| DCHS - Community & Human Srvcs       | Director's Office          | 8028.76               | 16                      | 9                       | 56.25               | 3             |              | 
```