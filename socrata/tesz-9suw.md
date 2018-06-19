# Capacity Project Site Location

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/capacity-project-site-location) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/tesz-9suw) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/tesz-9suw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/tesz-9suw/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | tesz-9suw |
| Name | Capacity Project Site Location |
| Attribution | NYC School Construction Authority (SCA) |
| Category | Education |
| Tags | sca, construction, project |
| Created | 2016-05-31T21:48:29Z |
| Publication Date | 2016-05-31T21:54:36Z |

## Description

New or replacement capacity sites.

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | district    | DISTRICT   | text      | number      |
| Yes      | series tag  | school      | SCHOOL     | text      | text        |
| Yes      | series tag  | borough     | BOROUGH    | text      | text        |
| Yes      | series tag  | location    | LOCATION   | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:tesz-9suw d:2016-05-31T14:48:55.000Z t:school="I.S. 323" t:location="75 MORTON STREET" t:borough=M t:district=2 m:row_number.tesz-9suw=1

series e:tesz-9suw d:2016-05-31T14:48:55.000Z t:school="P.S. 464" t:location="28-42 TRINITY PLACE" t:borough=M t:district=2 m:row_number.tesz-9suw=2

series e:tesz-9suw d:2016-05-31T14:48:55.000Z t:school="P.S. 342 (RIVERSIDE CENTER)" t:location="315 WEST 61ST STREET" t:borough=M t:district=3 m:row_number.tesz-9suw=3
```

## Meta Commands

```ls
metric m:row_number.tesz-9suw p:long l:"Row Number"

entity e:tesz-9suw l:"Capacity Project Site Location" t:attribution="NYC School Construction Authority (SCA)" t:url=https://data.cityofnewyork.us/api/views/tesz-9suw

property e:tesz-9suw t:meta.view v:id=tesz-9suw v:category=Education v:averageRating=0 v:name="Capacity Project Site Location" v:attribution="NYC School Construction Authority (SCA)"

property e:tesz-9suw t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:tesz-9suw t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | district | school                                         | borough | location                      | 
| =========== | ======== | ============================================== | ======= | ============================= | 
| 1464706135  | 2        | I.S. 323                                       | M       | 75 MORTON STREET              | 
| 1464706135  | 2        | P.S. 464                                       | M       | 28-42 TRINITY PLACE           | 
| 1464706135  | 3        | P.S. 342 (RIVERSIDE CENTER)                    | M       | 315 WEST 61ST STREET          | 
| 1464706135  | 8        | P.S. 14 ADDITION                               | X       | 3041 BRUCKNER BOULEVARD       | 
| 1464706135  | 10       | P.S. 46 ADDITION                               | X       | 279 EAST 196 STREET           | 
| 1464706135  | 13       | DOCK STREET CAMPUS                             | K       | 19 DOCK STREET                | 
| 1464706135  | 13       | P.S./I.S. 653                                  | K       | 6TH AVENUE AND PACIFIC STREET | 
| 1464706135  | 15       | P.S. 32 ADDITION                               | K       | 317 HOYT STREET               | 
| 1464706135  | 15       | P.S. 516 SUNSET PARK AVENUES ELEMENTARY SCHOOL | K       | 4222 4TH AVENUE               | 
| 1464706135  | 20       | P.S. 746                                       | K       | 256 59TH STREET               | 
```