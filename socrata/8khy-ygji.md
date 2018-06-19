# Capital Programs Homepage Banner

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/capital-programs-homepage-banner-e2d2a) |
| Metadata | [Link](https://data.illinois.gov/api/views/8khy-ygji) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/8khy-ygji/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/8khy-ygji/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 8khy-ygji |
| Name | Capital Programs Homepage Banner |
| Created | 2013-12-05T18:53:23Z |
| Publication Date | 2014-04-29T22:08:33Z |

## Description

Socrata dataset

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| No       | time           | :updated_at | updated_at  | meta_data | meta_data   |
| Yes      | numeric metric | order       | Order       | number    | number      |
| Yes      | series tag     | image       | Image       | photo     | photo       |
| Yes      | series tag     | title       | Title       | text      | text        |
| Yes      | series tag     | department  | Department  | text      | text        |
| Yes      | series tag     | description | Description | text      | text        |
| Yes      | series tag     | link        | Link        | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:8khy-ygji d:2014-03-13T16:01:09.000Z t:title="Air, Transit, Roadway Systems" t:description="The Stan Musial Veterans Memorial Bridge, opened February 8, 2014 by the governor and other dignitaries. The new bridge provides a more reliable way for millions of motorists to cross the Mississippi River between Illinois and Missouri." t:department=Transportation t:image=oJN2Hu-5YvC29J0ET7S_Smnj5BK0wFwKaiaitgEsm30 m:order=3

series e:8khy-ygji d:2014-03-20T15:37:24.000Z t:title="Starved Rock State Park" t:description="Capital funds are critical to the protection and maintenance of state parks and natural resources, and the preservation of cultural and historic sites." t:department="Natural and Cultural Resources" t:image=6IFLcBSqN8PfXZxIrwzXnsaA5FpMlLXWsZGQ_P1Z-I0 m:order=4

series e:8khy-ygji d:2014-03-20T15:37:55.000Z t:title="Economic  Development." t:description="Capital funding for economic development attracts private investment, targets urban renewal and enhances community infrastructure." t:image=aZODQwBajypa1gnxf5FKgOqY_Nnw-ZXca65zrc8qBJg m:order=5
```

## Meta Commands

```ls
metric m:order p:integer l:Order t:dataTypeName=number

entity e:8khy-ygji l:"Capital Programs Homepage Banner" t:url=https://data.illinois.gov/api/views/8khy-ygji

property e:8khy-ygji t:meta.view v:id=8khy-ygji v:averageRating=0 v:name="Capital Programs Homepage Banner"

property e:8khy-ygji t:meta.view.owner v:id=vcvp-yass v:profileImageUrlMedium=/api/users/vcvp-yass/profile_images/THUMB v:profileImageUrlLarge=/api/users/vcvp-yass/profile_images/LARGE v:screenName="Dylan Bussone" v:profileImageUrlSmall=/api/users/vcvp-yass/profile_images/TINY v:displayName="Dylan Bussone"

property e:8khy-ygji t:meta.view.tableauthor v:id=vcvp-yass v:profileImageUrlMedium=/api/users/vcvp-yass/profile_images/THUMB v:profileImageUrlLarge=/api/users/vcvp-yass/profile_images/LARGE v:screenName="Dylan Bussone" v:profileImageUrlSmall=/api/users/vcvp-yass/profile_images/TINY v:displayName="Dylan Bussone"
```

## Top Records

```ls
| :updated_at | order | image                                       | title                         | department                     | description                                                                                                                                                                                                                                                 | link | 
| =========== | ===== | =========================================== | ============================= | ============================== | =========================================================================================================================================================================================================================================================== | ==== | 
| 1394726469  | 3     | oJN2Hu-5YvC29J0ET7S_Smnj5BK0wFwKaiaitgEsm30 | Air, Transit, Roadway Systems | Transportation                 | The Stan Musial Veterans Memorial Bridge, opened February 8, 2014 by the governor and other dignitaries. The new bridge provides a more reliable way for millions of motorists to cross the Mississippi River between Illinois and Missouri.                |      | 
| 1395329844  | 4     | 6IFLcBSqN8PfXZxIrwzXnsaA5FpMlLXWsZGQ_P1Z-I0 | Starved Rock State Park       | Natural and Cultural Resources | Capital funds are critical to the protection and maintenance of state parks and natural resources, and the preservation of cultural and historic sites.                                                                                                     |      | 
| 1395329875  | 5     | aZODQwBajypa1gnxf5FKgOqY_Nnw-ZXca65zrc8qBJg | Economic Development.         |                                | Capital funding for economic development attracts private investment, targets urban renewal and enhances community infrastructure.                                                                                                                          |      | 
| 1395329908  | 6     | s0gP4kLi2UvbXWcxMjcgkneRL7fTJkwJZyMnJWKZoNI | Water Infrastructure          |                                | Investments in water infrastructure projects improve drinking water and waste water facilities and upgrade dams and levees. These improvements facilitate economic development and enhance the quality of life for Illinois citizens.                       |      | 
| 1398784110  | 1     | tHhHSRpFzHusUb2KU_rXYcbfS_GrMLchiod8ywbohFg | Illinois Jobs Now!            | Economy                        | On July 13, 2009 Governor Pat Quinn signed into law the Illinois Jobs Now! capital construction program. The largest infrastructure program in the state?s history, Illinois Jobs Now! is creating jobs and promoting economic development across Illinois. |      | 
| 1398784111  | 2     | AsPC0HGIQK_oBEgvZboyU1A88JSKmT0iJC_NthEXAeg | Education Funding             | Education                      | Funding for educational construction projects with an emphasis on technological upgrades helps to ensure the highest levels of student achievement.                                                                                                         |      | 
```