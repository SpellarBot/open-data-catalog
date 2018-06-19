# Austin Police Stations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/austin-police-stations) |
| Metadata | [Link](https://data.austintexas.gov/api/views/jmp6-p8e2) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/jmp6-p8e2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/jmp6-p8e2/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | jmp6-p8e2 |
| Name | Austin Police Stations |
| Attribution | City of Austin |
| Category | Public Safety |
| Tags | police, apd, stations, police stations |
| Created | 2012-07-18T13:27:53Z |
| Publication Date | 2012-07-18T13:29:53Z |

## Description

Location information for Austin Police stations

## Columns

```ls
| Included | Schema Type | Field Name   | Name         | Data Type | Render Type |
| ======== | =========== | ============ | ============ | ========= | =========== |
| No       | time        | :updated_at  | updated_at   | meta_data | meta_data   |
| Yes      | series tag  | station_name | STATION_NAME | text      | text        |
| No       |             | x            | X            | number    | text        |
| No       |             | y            | Y            | number    | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = x,y
```

## Data Commands

```ls
series e:jmp6-p8e2 d:2012-07-18T06:27:54.000Z t:station_name="Main Headquarters" m:row_number.jmp6-p8e2=1

series e:jmp6-p8e2 d:2012-07-18T06:27:54.000Z t:station_name="North Sub-Station" m:row_number.jmp6-p8e2=2

series e:jmp6-p8e2 d:2012-07-18T06:27:54.000Z t:station_name="East Sub-Station" m:row_number.jmp6-p8e2=3
```

## Meta Commands

```ls
metric m:row_number.jmp6-p8e2 p:long l:"Row Number"

entity e:jmp6-p8e2 l:"Austin Police Stations" t:attribution="City of Austin" t:url=https://data.austintexas.gov/api/views/jmp6-p8e2

property e:jmp6-p8e2 t:meta.view v:id=jmp6-p8e2 v:category="Public Safety" v:attributionLink=http://www.austintexas.gov v:averageRating=0 v:name="Austin Police Stations" v:attribution="City of Austin"

property e:jmp6-p8e2 t:meta.view.owner v:id=99uc-9byy v:screenName=opendataatx v:displayName=opendataatx

property e:jmp6-p8e2 t:meta.view.tableauthor v:id=99uc-9byy v:screenName=opendataatx v:roleName=administrator v:displayName=opendataatx
```

## Top Records

```ls
| :updated_at | station_name      | x          | y         | 
| =========== | ================= | ========== | ========= | 
| 1342592874  | Main Headquarters | -97.735070 | 30.267574 | 
| 1342592874  | North Sub-Station | -97.696183 | 30.414346 | 
| 1342592874  | East Sub-Station  | -97.700263 | 30.259212 | 
| 1342592874  | South Sub-Station | -97.793128 | 30.175455 | 
```