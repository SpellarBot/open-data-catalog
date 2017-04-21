# Published Datasets

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/published-datasets) |
| Metadata | [Link](https://data.jacksonms.gov/api/views/4atw-h7q2) |
| Data: JSON | [100 Rows](https://data.jacksonms.gov/api/views/4atw-h7q2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.jacksonms.gov/api/views/4atw-h7q2/rows.csv?max_rows=100) |
| Host | data.jacksonms.gov |
| Id | 4atw-h7q2 |
| Name | Published Datasets |
| Attribution | City of Jackson |
| Category | Government Accountability |
| Tags | data, governance, open data, city of jackson, transparency, accountability, published |
| Created | 2016-03-09T22:37:03Z |
| Publication Date | 2016-09-07T15:48:09Z |

## Description

This is simply a list of published datasets on the City of Jackson's Open Data Portal. This information is updated weekly.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type     | Render Type   |
| ======== | ============== | =============== | =============== | ============= | ============= |
| Yes      | series tag     | dataset_name    | Dataset Name    | text          | text          |
| Yes      | series tag     | dataset_owner   | Dataset Owner   | text          | text          |
| Yes      | time           | data_entry_date | Data Entry Date | calendar_date | calendar_date |
| Yes      | numeric metric | data_value      | Data Value      | number        | number        |
```

## Time Field

```ls
Value = data_entry_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:4atw-h7q2 d:2016-03-08T00:00:00.000Z t:dataset_owner="Jackson Police Department" t:dataset_name="Community Improvement Unit" m:data_value=1

series e:4atw-h7q2 d:2016-03-06T00:00:00.000Z t:dataset_owner="Office of Innovation and Performance" t:dataset_name="Meeting Log" m:data_value=1

series e:4atw-h7q2 d:2016-03-03T00:00:00.000Z t:dataset_owner="Office of Innovation and Performance" t:dataset_name="Healthcare Taskforce" m:data_value=1
```

## Meta Commands

```ls
metric m:data_value p:integer l:"Data Value" t:dataTypeName=number

entity e:4atw-h7q2 l:"Published Datasets" t:attribution="City of Jackson" t:url=https://data.jacksonms.gov/api/views/4atw-h7q2

property e:4atw-h7q2 t:meta.view v:id=4atw-h7q2 v:category="Government Accountability" v:attributionLink=http://www.jacksonms.gov v:averageRating=0 v:name="Published Datasets" v:attribution="City of Jackson"

property e:4atw-h7q2 t:meta.view.owner v:id=6ngd-c2u2 v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:screenName="Justin Bruce" v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:lastNotificationSeenAt=1492180672 v:displayName="Justin Bruce"

property e:4atw-h7q2 t:meta.view.tableauthor v:id=6ngd-c2u2 v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:screenName="Justin Bruce" v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492180672 v:displayName="Justin Bruce"
```

## Top Records

```ls
| dataset_name                    | dataset_owner                        | data_entry_date     | data_value | 
| =============================== | ==================================== | =================== | ========== | 
| Community Improvement Unit      | Jackson Police Department            | 2016-03-08T00:00:00 | 1          | 
| Meeting Log                     | Office of Innovation and Performance | 2016-03-06T00:00:00 | 1          | 
| Healthcare Taskforce            | Office of Innovation and Performance | 2016-03-03T00:00:00 | 1          | 
| 311 Closure Rates - Maintenance | Office of Innovation and Performance | 2016-03-01T00:00:00 | 1          | 
| 311 Closure Rates - Repairs     | Office of Innovation and Performance | 2016-03-02T00:00:00 | 1          | 
| 311 Closure Rates               | Office of Innovation and Performance | 2016-03-02T00:00:00 | 1          | 
| Financial Integrity Benchmarks  | Finance and Adminstration            | 2016-03-01T00:00:00 | 1          | 
| Super Neighborhood Tracker      | Special Projects Office              | 2016-02-28T00:00:00 | 1          | 
| Citizen Participation           | Human and Cultural Services          | 2016-02-26T00:00:00 | 1          | 
| Jobs for Jacksonians            | Economic Development                 | 2016-02-25T00:00:00 | 1          | 
```