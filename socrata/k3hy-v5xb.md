# Street Sweeping Schedule - 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/street-sweeping-schedule-2012-1cefd) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/k3hy-v5xb) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/k3hy-v5xb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/k3hy-v5xb/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | k3hy-v5xb |
| Name | Street Sweeping Schedule - 2012 |
| Attribution | City of Chicago |
| Category | Sanitation |
| Tags | street cleaning, schedule, 2012 |
| Created | 2012-03-28T19:56:28Z |
| Publication Date | 2012-04-11T18:26:07Z |

## Description

Street sweeping schedule by Ward and Ward sections number. To find your Ward section, visit http://bit.ly/Hz0aCo. For more information about the City's Street Sweeping program, go to http://bit.ly/H2PHUP.

## Columns

```ls
| Included | Schema Type    | Field Name   | Name                        | Data Type | Render Type |
| ======== | ============== | ============ | =========================== | ========= | =========== |
| Yes      | numeric metric | ward_section | WARD SECTION (CONCATENATED) | number    | text        |
| Yes      | numeric metric | ward         | WARD                        | number    | text        |
| Yes      | series tag     | section      | SECTION                     | text      | text        |
| Yes      | series tag     | month_name   | MONTH NAME                  | text      | text        |
| Yes      | series tag     | month_number | MONTH NUMBER                | text      | number      |
| No       |                | date_text    | DATES                       | text      | text        |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = date_text
```

## Data Commands

```ls
series e:k3hy-v5xb d:2012-01-01T00:00:00.000Z t:month_name=APRIL t:month_number=4 t:section=1 m:ward=1 m:ward_section=101

series e:k3hy-v5xb d:2012-01-01T00:00:00.000Z t:month_name=MAY t:month_number=5 t:section=1 m:ward=1 m:ward_section=101

series e:k3hy-v5xb d:2012-01-01T00:00:00.000Z t:month_name=JUNE t:month_number=6 t:section=1 m:ward=1 m:ward_section=101
```

## Meta Commands

```ls
metric m:ward_section p:integer l:"WARD SECTION (CONCATENATED)" t:dataTypeName=number

metric m:ward p:integer l:WARD t:dataTypeName=number

entity e:k3hy-v5xb l:"Street Sweeping Schedule - 2012" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/k3hy-v5xb

property e:k3hy-v5xb t:meta.view v:id=k3hy-v5xb v:category=Sanitation v:attributionLink=http://www.cityofchicago.org/content/city/en/depts/streets.html v:averageRating=0 v:name="Street Sweeping Schedule - 2012" v:attribution="City of Chicago"

property e:k3hy-v5xb t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:k3hy-v5xb t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| ward_section | ward | section | month_name | month_number | date_text | 
| ============ | ==== | ======= | ========== | ============ | ========= | 
| 101          | 1    | 1       | APRIL      | 4            | 3,4       | 
| 101          | 1    | 1       | MAY        | 5            | 1,2       | 
| 101          | 1    | 1       | JUNE       | 6            | 5,6       | 
| 101          | 1    | 1       | JULY       | 7            | 3         | 
| 101          | 1    | 1       | AUGUST     | 8            | 1,7       | 
| 101          | 1    | 1       | SEPTEMBER  | 9            | 4,5       | 
| 101          | 1    | 1       | OCTOBER    | 10           | 2,3       | 
| 101          | 1    | 1       | NOVEMBER   | 11           | 6,7       | 
| 102          | 1    | 2       | APRIL      | 4            | 5,6       | 
| 102          | 1    | 2       | MAY        | 5            | 3,4,      | 
```