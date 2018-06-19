# Jackson Municipal Polling Locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/jackson-municipal-polling-locations) |
| Metadata | [Link](https://data.jacksonms.gov/api/views/x82b-q8rg) |
| Data: JSON | [100 Rows](https://data.jacksonms.gov/api/views/x82b-q8rg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.jacksonms.gov/api/views/x82b-q8rg/rows.csv?max_rows=100) |
| Host | data.jacksonms.gov |
| Id | x82b-q8rg |
| Name | Jackson Municipal Polling Locations |
| Attribution | City of Jackson - Clerk's Office |
| Category | Government Accountability |
| Tags | election, municipal, government, voting, polls, ballots, city of jackson |
| Created | 2016-03-25T14:25:56Z |
| Publication Date | 2016-03-25T14:31:15Z |

## Description

This data set contains the municipal polling locations within the City of Jackson.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| No       | time           | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | numeric metric | voter_precinct | Voter Precinct | number    | number      |
| Yes      | numeric metric | ward_locations | Ward Locations | number    | number      |
| Yes      | series tag     | buidling_name  | Buidling Name  | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:x82b-q8rg d:2016-03-25T07:25:59.000Z t:buidling_name="Cherry Grove Baptist Church" m:voter_precinct=19 m:ward_locations=3

series e:x82b-q8rg d:2016-03-25T07:25:59.000Z t:buidling_name="Lanier High School" m:voter_precinct=20 m:ward_locations=3

series e:x82b-q8rg d:2016-03-25T07:25:59.000Z t:buidling_name="Raines Elementary School" m:voter_precinct=25 m:ward_locations=4
```

## Meta Commands

```ls
metric m:voter_precinct p:long l:"Voter Precinct" t:dataTypeName=number

metric m:ward_locations p:integer l:"Ward Locations" t:dataTypeName=number

entity e:x82b-q8rg l:"Jackson Municipal Polling Locations" t:attribution="City of Jackson - Clerk's Office" t:url=https://data.jacksonms.gov/api/views/x82b-q8rg

property e:x82b-q8rg t:meta.view v:id=x82b-q8rg v:category="Government Accountability" v:attributionLink=http://www.jacksonms.gov v:averageRating=0 v:name="Jackson Municipal Polling Locations" v:attribution="City of Jackson - Clerk's Office"

property e:x82b-q8rg t:meta.view.owner v:id=6ngd-c2u2 v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:screenName="Justin Bruce" v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:lastNotificationSeenAt=1492180672 v:displayName="Justin Bruce"

property e:x82b-q8rg t:meta.view.tableauthor v:id=6ngd-c2u2 v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:screenName="Justin Bruce" v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492180672 v:displayName="Justin Bruce"
```

## Top Records

```ls
| :updated_at | voter_precinct | ward_locations | buidling_name                               | 
| =========== | ============== | ============== | =========================================== | 
| 1458890759  | 19             | 3              | Cherry Grove Baptist Church                 | 
| 1458890759  | 20             | 3              | Lanier High School                          | 
| 1458890759  | 25             | 4              | Raines Elementary School                    | 
| 1458890759  | 51             | 5              | Blackburn Middle School                     | 
| 1458890759  | 55             | 5              | Police Training Center                      | 
| 1458890759  | 58             | 5              | Pearl Street AME Church - Activity Building | 
| 1458890759  | 84             | 2              | China Grove Baptist church                  | 
| 1458890766  | 21             | 3              | George Kurts Fieldhouse                     | 
| 1458890766  | 52             | 5              | Calvary Baptist Church                      | 
| 1458890766  | 18             | 3              | Wells Memorial United Methodist Church      | 
```