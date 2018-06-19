# CTA - System Information - Bus Stop Locations in Digital Sign Project

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cta-system-information-bus-stop-shelters-in-digital-sign-project-0d6ff) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/5cq6-qygt) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/5cq6-qygt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/5cq6-qygt/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 5cq6-qygt |
| Name | CTA - System Information - Bus Stop Locations in Digital Sign Project |
| Category | Transportation |
| Tags | cta |
| Created | 2011-09-28T18:53:35Z |
| Publication Date | 2016-03-11T23:25:31Z |

## Description

This dataset shows bus stops in shelters and at CTA rail stations which have digital signs added to them to show upcoming arrivals. The listing is subject to change.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| No       | time           | :updated_at   | updated_at    | meta_data | meta_data   |
| Yes      | series tag     | stop_id       | Stop_ID       | text      | number      |
| Yes      | series tag     | cta_stop_name | CTA Stop Name | text      | text        |
| Yes      | series tag     | direction     | Direction     | text      | text        |
| Yes      | series tag     | routes        | Routes        | text      | text        |
| Yes      | numeric metric | ward          | Ward          | number    | text        |
| No       |                | longitude     | LONGITUDE     | number    | number      |
| No       |                | latitude      | LATITUDE      | number    | number      |
| Yes      | numeric metric | phase         | Phase         | number    | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = longitude,latitude
```

## Data Commands

```ls
series e:5cq6-qygt d:2016-03-11T13:56:46.000Z t:stop_id=68 t:routes=1,7,28,126,130,151,156 t:direction=EB t:cta_stop_name="Jackson & Franklin" m:ward=42 m:phase=2

series e:5cq6-qygt d:2016-03-11T13:56:46.000Z t:stop_id=69 t:routes=1,7,28,126,130,132,151 t:direction=EB t:cta_stop_name="Jackson & Financial Place" m:ward=42 m:phase=1

series e:5cq6-qygt d:2016-03-11T13:56:46.000Z t:stop_id=73 t:routes=1,3,4,7,J14,26,28,126,132,143,147 t:direction=SB t:cta_stop_name="Michigan & Van Buren/Congress" m:ward=42 m:phase=1
```

## Meta Commands

```ls
metric m:ward p:integer l:Ward t:dataTypeName=number

metric m:phase p:integer l:Phase t:dataTypeName=number

entity e:5cq6-qygt l:"CTA - System Information - Bus Stop Locations in Digital Sign Project" t:url=https://data.cityofchicago.org/api/views/5cq6-qygt

property e:5cq6-qygt t:meta.view v:id=5cq6-qygt v:category=Transportation v:attributionLink=http://www.transitchicago.com/sheltersigns v:averageRating=0 v:name="CTA - System Information - Bus Stop Locations in Digital Sign Project"

property e:5cq6-qygt t:meta.view.owner v:id=6bsn-5494 v:profileImageUrlMedium=/api/users/6bsn-5494/profile_images/THUMB v:profileImageUrlLarge=/api/users/6bsn-5494/profile_images/LARGE v:screenName="cta web" v:profileImageUrlSmall=/api/users/6bsn-5494/profile_images/TINY v:displayName="cta web"

property e:5cq6-qygt t:meta.view.tableauthor v:id=6bsn-5494 v:profileImageUrlMedium=/api/users/6bsn-5494/profile_images/THUMB v:profileImageUrlLarge=/api/users/6bsn-5494/profile_images/LARGE v:screenName="cta web" v:profileImageUrlSmall=/api/users/6bsn-5494/profile_images/TINY v:roleName=designer v:displayName="cta web"
```

## Top Records

```ls
| :updated_at | stop_id | cta_stop_name                 | direction | routes                             | ward | longitude  | latitude  | phase | 
| =========== | ======= | ============================= | ========= | ================================== | ==== | ========== | ========= | ===== | 
| 1457704606  | 68      | Jackson & Franklin            | EB        | 1,7,28,126,130,151,156             | 42   | -87.635401 | 41.878051 | 2     | 
| 1457704606  | 69      | Jackson & Financial Place     | EB        | 1,7,28,126,130,132,151             | 42   | -87.632868 | 41.878081 | 1     | 
| 1457704606  | 73      | Michigan & Van Buren/Congress | SB        | 1,3,4,7,J14,26,28,126,132,143,147  | 42   | -87.624396 | 41.876271 | 1     | 
| 1457704606  | 75      | Michigan & Van Buren          | NB        | 1,7,28,126                         | 42   | -87.62416  | 41.87669  | 2     | 
| 1457704606  | 76      | Michigan & Jackson            | NB        | 3,4,6,J14,26,143                   | 42   | -87.624193 | 41.878135 | 1     | 
| 1457704606  | 77      | Adams & Wabash                | WB        | 1,7,28,126,151                     | 42   | -87.625884 | 41.879575 | 2     | 
| 1457704606  | 80      | Adams & Wells                 | WB        | 1,7,28,126,130,134,135,136,151,156 | 42   | -87.634024 | 41.879426 | 2     | 
| 1457704606  | 206     | Harrison & Halsted            | WB        | 7,60,755                           | 25   | -87.64775  | 41.874441 | 2     | 
| 1457704606  | 312     | Roosevelt & Canal             | EB        | 12,18,N62                          | 25   | -87.638826 | 41.867139 | 2     | 
| 1457704606  | 358     | Roosevelt & Homan             | WB        | 12                                 | 24   | -87.71027  | 41.866418 | 1     | 
```