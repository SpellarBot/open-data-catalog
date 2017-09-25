# Data Priority List

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/data-priority-list) |
| Metadata | [Link](https://data.jacksonms.gov/api/views/yjnx-i3j5) |
| Data: JSON | [100 Rows](https://data.jacksonms.gov/api/views/yjnx-i3j5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.jacksonms.gov/api/views/yjnx-i3j5/rows.csv?max_rows=100) |
| Host | data.jacksonms.gov |
| Id | yjnx-i3j5 |
| Name | Data Priority List |
| Attribution | City of Jackson |
| Category | Economic Development |
| Tags | accountability, transparency, data governance, open government, integrity, city of jackson |
| Created | 2016-03-28T21:33:50Z |
| Publication Date | 2016-03-28T21:38:32Z |

## Description

This data shows the priority ranking given to each City of Jackson data-set by the Data Governance Committee. The goal is to upload each set of data within the next six (6) months based on its priority.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| No       | time           | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | series tag     | dataset_name   | Dataset Name   | text      | text        |
| Yes      | numeric metric | member_1       | Member 1       | number    | number      |
| Yes      | numeric metric | member_2       | Member 2       | number    | number      |
| Yes      | numeric metric | member_3       | Member 3       | number    | number      |
| Yes      | numeric metric | member_4       | Member 4       | number    | number      |
| Yes      | numeric metric | member_5       | Member 5       | number    | number      |
| Yes      | numeric metric | member_6       | Member 6       | number    | number      |
| Yes      | numeric metric | member_7       | Member 7       | number    | number      |
| Yes      | numeric metric | member_8       | Member 8       | number    | number      |
| Yes      | numeric metric | member_9       | Member 9       | number    | number      |
| Yes      | numeric metric | rank_and_score | Rank and Score | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:yjnx-i3j5 d:2016-03-28T14:33:54.000Z t:dataset_name=Budget m:rank_and_score=9.666666666666666 m:member_3=10 m:member_4=8 m:member_1=9 m:member_2=10 m:member_7=10 m:member_8=10 m:member_5=10 m:member_6=10 m:member_9=10

series e:yjnx-i3j5 d:2016-03-28T14:33:54.000Z t:dataset_name="Crime Stats" m:rank_and_score=8.88888888888889 m:member_3=10 m:member_4=0 m:member_1=10 m:member_2=10 m:member_7=10 m:member_8=10 m:member_5=10 m:member_6=10 m:member_9=10

series e:yjnx-i3j5 d:2016-03-28T14:33:54.000Z t:dataset_name="311 Data" m:rank_and_score=8.777777777777779 m:member_3=10 m:member_4=10 m:member_1=9 m:member_2=10 m:member_7=1 m:member_8=10 m:member_5=10 m:member_6=9 m:member_9=10
```

## Meta Commands

```ls
metric m:member_1 p:integer l:"Member 1" t:dataTypeName=number

metric m:member_2 p:integer l:"Member 2" t:dataTypeName=number

metric m:member_3 p:integer l:"Member 3" t:dataTypeName=number

metric m:member_4 p:integer l:"Member 4" t:dataTypeName=number

metric m:member_5 p:integer l:"Member 5" t:dataTypeName=number

metric m:member_6 p:integer l:"Member 6" t:dataTypeName=number

metric m:member_7 p:integer l:"Member 7" t:dataTypeName=number

metric m:member_8 p:integer l:"Member 8" t:dataTypeName=number

metric m:member_9 p:integer l:"Member 9" t:dataTypeName=number

metric m:rank_and_score p:decimal l:"Rank and Score" t:dataTypeName=number

entity e:yjnx-i3j5 l:"Data Priority List" t:attribution="City of Jackson" t:url=https://data.jacksonms.gov/api/views/yjnx-i3j5

property e:yjnx-i3j5 t:meta.view d:2017-09-25T07:31:06.849Z v:averageRating=0 v:name="Data Priority List" v:attribution="City of Jackson" v:attributionLink=http://www.jacksonms.gov v:id=yjnx-i3j5 v:category="Economic Development"

property e:yjnx-i3j5 t:meta.view.owner d:2017-09-25T07:31:06.849Z v:displayName="Justin Bruce" v:lastNotificationSeenAt=1492180672 v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:id=6ngd-c2u2 v:screenName="Justin Bruce" v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB

property e:yjnx-i3j5 t:meta.view.tableauthor d:2017-09-25T07:31:06.849Z v:displayName="Justin Bruce" v:lastNotificationSeenAt=1492180672 v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:roleName=administrator v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:id=6ngd-c2u2 v:screenName="Justin Bruce" v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB
```

## Top Records

```ls
| :updated_at | dataset_name              | member_1 | member_2 | member_3 | member_4 | member_5 | member_6 | member_7 | member_8 | member_9 | rank_and_score     | 
| =========== | ========================= | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ================== | 
| 1459175634  | Budget                    | 9        | 10       | 10       | 8        | 10       | 10       | 10       | 10       | 10       | 9.6666666666666661 | 
| 1459175634  | Crime Stats               | 10       | 10       | 10       | 0        | 10       | 10       | 10       | 10       | 10       | 8.8888888888888893 | 
| 1459175634  | 311 Data                  | 9        | 10       | 10       | 10       | 10       | 9        | 1        | 10       | 10       | 8.7777777777777786 | 
| 1459175634  | Revenue                   | 9        | 10       | 10       | 8        | 8        | 10       | 10       | 5        | 8        | 8.6666666666666661 | 
| 1459175634  | Elections                 | 8        | 0        | 10       | 10       | 10       | 10       | 8        | 8        | 10       | 8.2222222222222214 | 
| 1459175634  | Sewer Tap List            | 9        | 7        | 10       | 0        | 10       | 9        | 10       | 9        | 8        | 8                  | 
| 1459175634  | Expenditures              | 9        | 7        | 10       | 0        | 10       | 9        | 8        | 10       | 8        | 7.8888888888888893 | 
| 1459175634  | Tip411                    | 10       | 10       | 10       | 9        | 1        | 10       | 1        | 10       | 10       | 7.8888888888888893 | 
| 1459175634  | Fire Reports              | 9        |          | 7        | 0        | 10       | 9        | 9        | 8        | 10       | 7.75               | 
| 1459175634  | Municipal Voter Precincts | 8        | 0        | 10       | 0        | 10       | 10       | 8        | 10       | 10       | 7.333333333333333  | 
```