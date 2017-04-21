# Street Sweeping Schedule - 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/street-sweeping-schedule-2013-b7d65) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/8h6a-imtk) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/8h6a-imtk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/8h6a-imtk/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 8h6a-imtk |
| Name | Street Sweeping Schedule - 2013 |
| Attribution | City of Chicago |
| Category | Sanitation |
| Tags | street cleaning, schedule, 2013, parking restrictions |
| Created | 2013-04-01T20:54:02Z |
| Publication Date | 2013-04-08T19:36:56Z |

## Description

Street sweeping schedule by Ward and Ward sections number. To find your Ward section, visit http://bit.ly/Hz0aCo. For more information about the City's Street Sweeping program, go to http://bit.ly/H2PHUP.

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                        | Data Type | Render Type |
| ======== | ============== | ========================= | =========================== | ========= | =========== |
| Yes      | numeric metric | ward_section_concatenated | WARD SECTION (CONCATENATED) | number    | text        |
| Yes      | numeric metric | ward                      | WARD                        | number    | text        |
| Yes      | series tag     | section                   | SECTION                     | text      | text        |
| Yes      | series tag     | month_name                | MONTH NAME                  | text      | text        |
| Yes      | series tag     | month_number              | MONTH NUMBER                | text      | number      |
| Yes      | series tag     | dates                     | DATES                       | text      | text        |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:8h6a-imtk d:2013-01-01T00:00:00.000Z t:dates=2,3 t:month_name=APRIL t:month_number=4 t:section=1 m:ward_section_concatenated=101 m:ward=1

series e:8h6a-imtk d:2013-01-01T00:00:00.000Z t:dates=1,7 t:month_name=MAY t:month_number=5 t:section=1 m:ward_section_concatenated=101 m:ward=1

series e:8h6a-imtk d:2013-01-01T00:00:00.000Z t:dates=4,5 t:month_name=JUNE t:month_number=6 t:section=1 m:ward_section_concatenated=101 m:ward=1
```

## Meta Commands

```ls
metric m:ward_section_concatenated p:integer l:"WARD SECTION (CONCATENATED)" t:dataTypeName=number

metric m:ward p:integer l:WARD t:dataTypeName=number

entity e:8h6a-imtk l:"Street Sweeping Schedule - 2013" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/8h6a-imtk

property e:8h6a-imtk t:meta.view v:id=8h6a-imtk v:category=Sanitation v:attributionLink=http://www.cityofchicago.org/city/en/depts/streets/provdrs/streets_san/svcs/street_sweeping.html v:averageRating=0 v:name="Street Sweeping Schedule - 2013" v:attribution="City of Chicago"

property e:8h6a-imtk t:meta.view.owner v:id=3qqc-w7ag v:profileImageUrlMedium=/api/users/3qqc-w7ag/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qqc-w7ag/profile_images/LARGE v:screenName="Tom Schenk Jr" v:profileImageUrlSmall=/api/users/3qqc-w7ag/profile_images/TINY v:lastNotificationSeenAt=1491330280 v:displayName="Tom Schenk Jr"

property e:8h6a-imtk t:meta.view.tableauthor v:id=3qqc-w7ag v:profileImageUrlMedium=/api/users/3qqc-w7ag/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qqc-w7ag/profile_images/LARGE v:screenName="Tom Schenk Jr" v:profileImageUrlSmall=/api/users/3qqc-w7ag/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491330280 v:displayName="Tom Schenk Jr"
```

## Top Records

```ls
| ward_section_concatenated | ward | section | month_name | month_number | dates | 
| ========================= | ==== | ======= | ========== | ============ | ===== | 
| 101                       | 1    | 1       | APRIL      | 4            | 2,3   | 
| 101                       | 1    | 1       | MAY        | 5            | 1,7   | 
| 101                       | 1    | 1       | JUNE       | 6            | 4,5   | 
| 101                       | 1    | 1       | JULY       | 7            | 2,3   | 
| 101                       | 1    | 1       | AUGUST     | 8            | 6,7   | 
| 101                       | 1    | 1       | SEPTEMBER  | 9            | 3,4   | 
| 101                       | 1    | 1       | OCTOBER    | 10           | 1,2   | 
| 101                       | 1    | 1       | NOVEMBER   | 11           | 5,6   | 
| 102                       | 1    | 2       | APRIL      | 4            | 4,5   | 
| 102                       | 1    | 2       | MAY        | 5            | 2,3   | 
```