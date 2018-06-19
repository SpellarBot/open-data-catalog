# Election District Poll Sites

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/election-district-poll-sites-as-of-09-05-2013-bec3e) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/i3a3-qxkf) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/i3a3-qxkf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/i3a3-qxkf/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | i3a3-qxkf |
| Name | Election District Poll Sites |
| Attribution | Board of Elections (BOENY) |
| Category | City Government |
| Created | 2013-09-05T22:56:47Z |
| Publication Date | 2016-11-01T16:04:48Z |

## Description

This information is up-to-date as of 10/19/2016. Please note that there may be additional changes which are not yet reflected here.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| No       | time           | :updated_at | updated_at  | meta_data | meta_data   |
| Yes      | numeric metric | borough     | BOROUGH     | number    | text        |
| Yes      | series tag     | site_number | SITE_NUMBER | text      | text        |
| No       |                | ad          | AD          | number    | number      |
| No       |                | ed          | ED          | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = ad,ed
```

## Data Commands

```ls
series e:i3a3-qxkf d:2016-11-01T16:03:33.000Z t:site_number=11255 m:borough=1

series e:i3a3-qxkf d:2016-11-01T16:03:33.000Z t:site_number=10657 m:borough=1

series e:i3a3-qxkf d:2016-11-01T16:03:33.000Z t:site_number=M0244 m:borough=1
```

## Meta Commands

```ls
metric m:borough p:integer l:BOROUGH t:dataTypeName=number

entity e:i3a3-qxkf l:"Election District Poll Sites" t:attribution="Board of Elections (BOENY)" t:url=https://data.cityofnewyork.us/api/views/i3a3-qxkf

property e:i3a3-qxkf t:meta.view v:id=i3a3-qxkf v:category="City Government" v:averageRating=0 v:name="Election District Poll Sites" v:attribution="Board of Elections (BOENY)"

property e:i3a3-qxkf t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:i3a3-qxkf t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | borough | site_number | ad | ed | 
| =========== | ======= | =========== | == | == | 
| 1478016213  | 1       | 11255       | 65 | 1  | 
| 1478016213  | 1       | 10657       | 65 | 2  | 
| 1478016213  | 1       | M0244       | 65 | 3  | 
| 1478016213  | 1       | M0244       | 65 | 4  | 
| 1478016213  | 1       | M0244       | 65 | 5  | 
| 1478016213  | 1       | 11399       | 65 | 6  | 
| 1478016213  | 1       | 11399       | 65 | 7  | 
| 1478016213  | 1       | 11399       | 65 | 8  | 
| 1478016213  | 1       | 10611       | 65 | 9  | 
| 1478016213  | 1       | 10611       | 65 | 10 | 
```