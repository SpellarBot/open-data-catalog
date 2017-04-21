# FY2015 Top 10 Problems

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/top-10-problems-fy2015) |
| Metadata | [Link](https://data.austintexas.gov/api/views/7u4f-uwua) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/7u4f-uwua/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/7u4f-uwua/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 7u4f-uwua |
| Name | FY2015 Top 10 Problems |
| Tags | ems, atcems, incidents, problems, fy2015 |
| Created | 2016-08-23T13:55:15Z |
| Publication Date | 2016-08-23T13:56:35Z |

## Description

** Static Data Set ** This table shows the 10 most frequently recorded incident problem types as recorded by communications personnel during fiscal year 2015. THE DATA IN THIS TABLE WILL NOT BE UPDATED.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | series tag     | problem        | Problem        | text      | text        |
| Yes      | numeric metric | incident_count | Incident Count | number    | number      |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:7u4f-uwua d:2015-01-01T00:00:00.000Z t:problem="Unknown Pri 4" m:incident_count=3547

series e:7u4f-uwua d:2015-01-01T00:00:00.000Z t:problem="Sick Pri 4" m:incident_count=3629

series e:7u4f-uwua d:2015-01-01T00:00:00.000Z t:problem="Unconscious Pri 1" m:incident_count=3631
```

## Meta Commands

```ls
metric m:incident_count p:integer l:"Incident Count" t:dataTypeName=number

entity e:7u4f-uwua l:"FY2015 Top 10 Problems" t:url=https://data.austintexas.gov/api/views/7u4f-uwua

property e:7u4f-uwua t:meta.view v:id=7u4f-uwua v:averageRating=0 v:name="FY2015 Top 10 Problems"

property e:7u4f-uwua t:meta.view.owner v:id=4zcf-8die v:profileImageUrlMedium=/api/users/4zcf-8die/profile_images/THUMB v:profileImageUrlLarge=/api/users/4zcf-8die/profile_images/LARGE v:screenName="Austin-Travis County EMS" v:profileImageUrlSmall=/api/users/4zcf-8die/profile_images/TINY v:displayName="Austin-Travis County EMS"

property e:7u4f-uwua t:meta.view.tableauthor v:id=4zcf-8die v:profileImageUrlMedium=/api/users/4zcf-8die/profile_images/THUMB v:profileImageUrlLarge=/api/users/4zcf-8die/profile_images/LARGE v:screenName="Austin-Travis County EMS" v:profileImageUrlSmall=/api/users/4zcf-8die/profile_images/TINY v:roleName=publisher_stories v:displayName="Austin-Travis County EMS"
```

## Top Records

```ls
| problem                 | incident_count | 
| ======================= | ============== | 
| Unknown Pri 4           | 3547           | 
| Sick Pri 4              | 3629           | 
| Unconscious Pri 1       | 3631           | 
| Respiratory Pri 2       | 4399           | 
| Chest Pain Pri 2        | 4673           | 
| Assault Pri 4           | 4713           | 
| Sick Pri 5              | 5720           | 
| Altered Mentation Pri 2 | 6044           | 
| Fall Pri 4              | 7410           | 
| Traffic Injury Pri 4F   | 12039          | 
```