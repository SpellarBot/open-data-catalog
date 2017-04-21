# EMS - FY2016 Top Ten Dispatch Problems

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ems-fy2016-top-ten-dispatch-problems) |
| Metadata | [Link](https://data.austintexas.gov/api/views/etau-83bk) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/etau-83bk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/etau-83bk/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | etau-83bk |
| Name | EMS - FY2016 Top Ten Dispatch Problems |
| Category | Public Safety |
| Tags | ems, atcems, incidents, operations, problem types, fy2016 |
| Created | 2016-10-31T16:01:14Z |
| Publication Date | 2016-10-31T16:02:13Z |

## Description

** Static Data Set ** This table shows the 10 most frequently recorded incident problem types as recorded by communications personnel during fiscal year 2016. THE DATA IN THIS TABLE WILL NOT BE UPDATED.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | series tag     | problem_type   | Problem Type   | text      | text        |
| Yes      | numeric metric | incident_count | Incident Count | number    | number      |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:etau-83bk d:2016-01-01T00:00:00.000Z t:problem_type="Traffic Injury Pri 4F" m:incident_count=12910

series e:etau-83bk d:2016-01-01T00:00:00.000Z t:problem_type="Fall Pri 4" m:incident_count=7649

series e:etau-83bk d:2016-01-01T00:00:00.000Z t:problem_type="Altered Mentation Pri 3" m:incident_count=7147
```

## Meta Commands

```ls
metric m:incident_count p:integer l:"Incident Count" d:"This column shows the count of incidents recorded in CAD for the listed problem type during FY2016." t:dataTypeName=number

entity e:etau-83bk l:"EMS - FY2016 Top Ten Dispatch Problems" t:url=https://data.austintexas.gov/api/views/etau-83bk

property e:etau-83bk t:meta.view v:id=etau-83bk v:category="Public Safety" v:averageRating=0 v:name="EMS - FY2016 Top Ten Dispatch Problems"

property e:etau-83bk t:meta.view.owner v:id=4zcf-8die v:profileImageUrlMedium=/api/users/4zcf-8die/profile_images/THUMB v:profileImageUrlLarge=/api/users/4zcf-8die/profile_images/LARGE v:screenName="Austin-Travis County EMS" v:profileImageUrlSmall=/api/users/4zcf-8die/profile_images/TINY v:displayName="Austin-Travis County EMS"

property e:etau-83bk t:meta.view.tableauthor v:id=4zcf-8die v:profileImageUrlMedium=/api/users/4zcf-8die/profile_images/THUMB v:profileImageUrlLarge=/api/users/4zcf-8die/profile_images/LARGE v:screenName="Austin-Travis County EMS" v:profileImageUrlSmall=/api/users/4zcf-8die/profile_images/TINY v:roleName=publisher_stories v:displayName="Austin-Travis County EMS"
```

## Top Records

```ls
| problem_type            | incident_count | 
| ======================= | ============== | 
| Traffic Injury Pri 4F   | 12910          | 
| Fall Pri 4              | 7649           | 
| Altered Mentation Pri 3 | 7147           | 
| Chest Pain Pri 2        | 6807           | 
| Respiratory Pri 2       | 5420           | 
| Sick Pri 5              | 5379           | 
| Assault Pri 4           | 4841           | 
| Unknown Pri 3           | 4323           | 
| Unconscious Pri 1       | 3864           | 
| Sick Pri 4              | 3567           | 
```