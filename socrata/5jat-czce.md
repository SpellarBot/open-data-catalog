# Topographical Bureau Maps

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/topographical-bureau-maps-27b1f) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/5jat-czce) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/5jat-czce/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/5jat-czce/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 5jat-czce |
| Name | Topographical Bureau Maps |
| Attribution | Manhattan Borough President (MBP) |
| Category | City Government |
| Tags | topographical bureau maps, city government, mbp |
| Created | 2014-10-21T21:43:00Z |
| Publication Date | 2014-10-21T21:47:39Z |

## Description

This list contains information on maps maintained by the topographical bureau

## Columns

```ls
| Included | Schema Type | Field Name                | Name                      | Data Type | Render Type |
| ======== | =========== | ========================= | ========================= | ========= | =========== |
| Yes      | series tag  | acc                       | ACC                       | text      | text        |
| Yes      | series tag  | sheets                    | Sheets                    | text      | text        |
| Yes      | series tag  | cp_number                 | CP Number                 | text      | text        |
| Yes      | time        | map_year                  | Map Year                  | number    | number      |
| Yes      | series tag  | dimensions                | Dimensions                | text      | text        |
| Yes      | series tag  | map_title_and_information | Map Title and information | text      | text        |
```

## Time Field

```ls
Value = map_year
Format & Zone = yyyy
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:5jat-czce l:"Topographical Bureau Maps" t:attribution="Manhattan Borough President (MBP)" t:url=https://data.cityofnewyork.us/api/views/5jat-czce

property e:5jat-czce t:meta.view v:id=5jat-czce v:category="City Government" v:averageRating=0 v:name="Topographical Bureau Maps" v:attribution="Manhattan Borough President (MBP)"

property e:5jat-czce t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:5jat-czce t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| acc   | sheets | cp_number | map_year | dimensions | map_title_and_information                             | 
| ===== | ====== | ========= | ======== | ========== | ===================================================== | 
| 30085 | 1      |           | 1983     |            | WITHDRAWN 3/30/84                                     | 
| 30101 | 1      |           | 1984     |            | NOT FILED                                             | 
| 30106 | 1      |           |          |            | NOT FILED/TORN                                        | 
| 1294  | 1      |           | 1852     |            | DAMAGED (NO DATA ON FILE) D-TIMOTHY                   | 
| 1840  | 2      |           |          | 35 x 26    |                                                       | 
| ----- | SET    |           | 1997     |            | HALF SIZE DRAWINGS                                    | 
| 4555  | 1      |           | 1888     | 54 x 36    | EXTRA COPY                                            | 
| 6010  | 3      |           | 1897     | 54 x 39    |                                                       | 
| 6293  | 1      |           | 1898     |            | DAMAGED                                               | 
| 6703  |        |           | 1815     | 36 x 24    | TREATED AT NEDCC--DISBOUND, RELINED, FOLDERED & BOXED | 
```