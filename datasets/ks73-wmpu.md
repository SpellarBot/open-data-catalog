# Iowa Veterans Home - Average Census

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/iowa-veterans-home-average-census) |
| Metadata | [Link](https://data.iowa.gov/api/views/ks73-wmpu) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/ks73-wmpu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/ks73-wmpu/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | ks73-wmpu |
| Name | Iowa Veterans Home - Average Census |
| Attribution | Iowa Veterans Home |
| Category | Government |
| Tags | iowa veterans home, census |
| Created | 2016-07-05T17:55:42Z |
| Publication Date | 2016-07-05T17:59:44Z |

## Description

Data starts in 1999 and is updated every year.

## Columns

```ls
| Included | Schema Type    | Field Name | Name    | Data Type | Render Type |
| ======== | ============== | ========== | ======= | ========= | =========== |
| Yes      | series tag     | type       | TYPE    | text      | text        |
| Yes      | time           | year       | YEAR    | number    | text        |
| Yes      | numeric metric | average    | AVERAGE | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ks73-wmpu d:1999-01-01T00:00:00.000Z t:type=DORM m:average=98

series e:ks73-wmpu d:1999-01-01T00:00:00.000Z t:type=NURSING m:average=594

series e:ks73-wmpu d:1999-01-01T00:00:00.000Z t:type=HOSPITAL m:average=18
```

## Meta Commands

```ls
metric m:average p:integer l:AVERAGE t:dataTypeName=number

entity e:ks73-wmpu l:"Iowa Veterans Home - Average Census" t:attribution="Iowa Veterans Home" t:url=https://data.iowa.gov/api/views/ks73-wmpu

property e:ks73-wmpu t:meta.view v:id=ks73-wmpu v:category=Government v:averageRating=0 v:name="Iowa Veterans Home - Average Census" v:attribution="Iowa Veterans Home"

property e:ks73-wmpu t:meta.view.owner v:id=7aqt-vm7i v:profileImageUrlMedium=/api/users/7aqt-vm7i/profile_images/THUMB v:profileImageUrlLarge=/api/users/7aqt-vm7i/profile_images/LARGE v:screenName="Iowa Veterans Home" v:profileImageUrlSmall=/api/users/7aqt-vm7i/profile_images/TINY v:displayName="Iowa Veterans Home"

property e:ks73-wmpu t:meta.view.tableauthor v:id=7aqt-vm7i v:profileImageUrlMedium=/api/users/7aqt-vm7i/profile_images/THUMB v:profileImageUrlLarge=/api/users/7aqt-vm7i/profile_images/LARGE v:screenName="Iowa Veterans Home" v:profileImageUrlSmall=/api/users/7aqt-vm7i/profile_images/TINY v:roleName=editor v:displayName="Iowa Veterans Home"
```

## Top Records

```ls
| type     | year | average | 
| ======== | ==== | ======= | 
| DORM     | 1999 | 98      | 
| NURSING  | 1999 | 594     | 
| HOSPITAL | 1999 | 18      | 
| DORM     | 2000 | 93      | 
| NURSING  | 2000 | 596     | 
| HOSPITAL | 2000 | 17      | 
| DORM     | 2001 | 88      | 
| NURSING  | 2001 | 579     | 
| HOSPITAL | 2001 | 15      | 
| DORM     | 2002 | 89      | 
```