# Employee Giving Statistics - 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/employee-giving-statistics-2016) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/fnym-8mh8) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/fnym-8mh8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/fnym-8mh8/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | fnym-8mh8 |
| Name | Employee Giving Statistics - 2016 |
| Category | Employees |
| Created | 2016-09-12T16:49:45Z |
| Publication Date | 2017-01-30T18:15:48Z |

## Description

Department statistics for the 2016 Employee Giving drive.

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
Value = 2016
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = total_pledged_to_date
```

## Data Commands

```ls
series e:fnym-8mh8 d:2016-01-01T00:00:00.000Z t:division="Administrative Services" t:department="DAJD-Adult & Juvnile Detention" t:employees_in_department=24 m:employees_participating=16 m:new_employees=6 m:total_participating=66.67

series e:fnym-8mh8 d:2016-01-01T00:00:00.000Z t:division="Community Corrections" t:department="DAJD-Adult & Juvnile Detention" t:employees_in_department=43 m:employees_participating=7 m:total_participating=16.28

series e:fnym-8mh8 d:2016-01-01T00:00:00.000Z t:division=Juvenile t:department="DAJD-Adult & Juvnile Detention" t:employees_in_department=125 m:employees_participating=15 m:new_employees=12 m:total_participating=12
```

## Meta Commands

```ls
metric m:employees_participating p:integer l:"Employees participating" t:dataTypeName=number

metric m:total_participating p:float l:"Total % Participating" t:dataTypeName=percent

metric m:new_employees p:integer l:"New employees" t:dataTypeName=number

entity e:fnym-8mh8 l:"Employee Giving Statistics - 2016" t:url=https://data.kingcounty.gov/api/views/fnym-8mh8

property e:fnym-8mh8 t:meta.view v:id=fnym-8mh8 v:category=Employees v:averageRating=0 v:name="Employee Giving Statistics - 2016"

property e:fnym-8mh8 t:meta.view.owner v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:displayName="King County Webteam"

property e:fnym-8mh8 t:meta.view.tableauthor v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:roleName=administrator v:displayName="King County Webteam"
```

## Top Records

```ls
| department                                    | division                   | total_pledged_to_date | employees_in_department | employees_participating | total_participating | new_employees | 100_opp_goal | 
| ============================================= | ========================== | ===================== | ======================= | ======================= | =================== | ============= | ============ | 
| DAJD-Adult & Juvnile Detention                | Administrative Services    | 8614.75               | 24                      | 16                      | 66.67               | 6             |              | 
| DAJD-Adult & Juvnile Detention                | Community Corrections      | 6506.42               | 43                      | 7                       | 16.28               |               |              | 
| DAJD-Adult & Juvnile Detention                | Juvenile                   | 4711.20               | 125                     | 15                      | 12.00               | 12            |              | 
| DAJD-Adult & Juvnile Detention                | KCCF                       | 12610.85              | 438                     | 28                      | 6.39                | 9             |              | 
| DAJD-Adult & Juvnile Detention                | MRJC                       | 4017.91               | 226                     | 10                      | 4.42                | 3             |              | 
| DAJD-Adult & Juvnile Detention Special Events |                            | 131.80                |                         |                         |                     |               |              | 
| DAJD-Adult & Juvnile Detention Total          |                            | 36592.93              | 856                     | 76                      | 8.88                | 30            |              | 
| DCHS - Community & Human Srvcs                | Community Services         | 22273.56              | 130                     | 34                      | 26.15               | 9             |              | 
| DCHS - Community & Human Srvcs                | Developmental Disabilities | 6904.05               | 19                      | 13                      | 68.42               | 4             |              | 
| DCHS - Community & Human Srvcs                | Director's Office          | 10188.73              | 26                      | 17                      | 65.38               | 7             |              | 
```