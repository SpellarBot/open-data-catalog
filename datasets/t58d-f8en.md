# CTA - Performance - Bus Runs Held Due to Absenteeism (2011, Jan-Aug)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cta-performance-bus-runs-held-due-to-absenteeism-2011-jan-aug-100ee) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/t58d-f8en) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/t58d-f8en/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/t58d-f8en/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | t58d-f8en |
| Name | CTA - Performance - Bus Runs Held Due to Absenteeism (2011, Jan-Aug) |
| Attribution | Chicago Transit Authority |
| Category | Transportation |
| Tags | cta, chicago transit authority |
| Created | 2011-10-03T20:26:27Z |
| Publication Date | 2011-10-05T04:15:32Z |

## Description

This dataset shows bus runs held unfulfilled as a result of absenteeism. Absent, in this context, indicates unscheduled days off work. Note: Total does not include bus hold-ins caused by absenteeism related to the blizzard of February, 2011.

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | series tag     | weekday_type | Weekday Type | text      | text        |
| Yes      | numeric metric | runs_held    | Runs Held    | number    | number      |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:t58d-f8en d:2011-01-01T00:00:00.000Z t:weekday_type=Wednesday m:runs_held=50

series e:t58d-f8en d:2011-01-01T00:00:00.000Z t:weekday_type=Saturday m:runs_held=44

series e:t58d-f8en d:2011-01-01T00:00:00.000Z t:weekday_type=Sunday m:runs_held=36
```

## Meta Commands

```ls
metric m:runs_held p:integer l:"Runs Held" t:dataTypeName=number

entity e:t58d-f8en l:"CTA - Performance - Bus Runs Held Due to Absenteeism (2011, Jan-Aug)" t:attribution="Chicago Transit Authority" t:url=https://data.cityofchicago.org/api/views/t58d-f8en

property e:t58d-f8en t:meta.view v:id=t58d-f8en v:category=Transportation v:averageRating=0 v:name="CTA - Performance - Bus Runs Held Due to Absenteeism (2011, Jan-Aug)" v:attribution="Chicago Transit Authority"

property e:t58d-f8en t:meta.view.owner v:id=6bsn-5494 v:profileImageUrlMedium=/api/users/6bsn-5494/profile_images/THUMB v:profileImageUrlLarge=/api/users/6bsn-5494/profile_images/LARGE v:screenName="cta web" v:profileImageUrlSmall=/api/users/6bsn-5494/profile_images/TINY v:displayName="cta web"

property e:t58d-f8en t:meta.view.tableauthor v:id=6bsn-5494 v:profileImageUrlMedium=/api/users/6bsn-5494/profile_images/THUMB v:profileImageUrlLarge=/api/users/6bsn-5494/profile_images/LARGE v:screenName="cta web" v:profileImageUrlSmall=/api/users/6bsn-5494/profile_images/TINY v:roleName=designer v:displayName="cta web"
```

## Top Records

```ls
| weekday_type | runs_held | 
| ============ | ========= | 
| Wednesday    | 50        | 
| Saturday     | 44        | 
| Sunday       | 36        | 
| Monday       | 137       | 
| Tuesday      | 109       | 
| Thursday     | 39        | 
| Friday       | 104       | 
```