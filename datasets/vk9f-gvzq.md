# DOP Juvenile Investigations Assigned

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dop-juvenile-investigations-assigned) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/vk9f-gvzq) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/vk9f-gvzq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/vk9f-gvzq/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | vk9f-gvzq |
| Name | DOP Juvenile Investigations Assigned |
| Attribution | Department of Probation (DOP) |
| Category | Public Safety |
| Tags | dop, investigation, probation |
| Created | 2016-11-21T15:48:22Z |
| Publication Date | 2017-09-08T16:50:26Z |

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                          | Data Type | Render Type |
| ======== | ============== | ============================= | ============================= | ========= | =========== |
| Yes      | series tag     | borough                       | Borough                       | text      | text        |
| Yes      | series tag     | total_investigations_assigned | Total Investigations Assigned | text      | text        |
| No       |                | month                         | Month                         | text      | text        |
| No       |                | year                          | Year                          | number    | number      |
| Yes      | numeric metric | investigations_assigned_count | Investigations Assigned Count | number    | text        |
```

## Time Field

```ls
Value = year-month
Format & Zone = yyyy-MMMM
```

## Series Fields

```ls
Excluded Fields = year,month
```

## Data Commands

```ls
series e:vk9f-gvzq d:2016-09-01T00:00:00.000Z t:borough=Citywide t:total_investigations_assigned=Total m:investigations_assigned_count=112

series e:vk9f-gvzq d:2016-11-01T00:00:00.000Z t:borough=Citywide t:total_investigations_assigned=Total m:investigations_assigned_count=146

series e:vk9f-gvzq d:2016-12-01T00:00:00.000Z t:borough=Citywide t:total_investigations_assigned=Total m:investigations_assigned_count=166
```

## Meta Commands

```ls
metric m:investigations_assigned_count p:integer l:"Investigations Assigned Count" t:dataTypeName=number

entity e:vk9f-gvzq l:"DOP Juvenile Investigations Assigned" t:attribution="Department of Probation (DOP)" t:url=https://data.cityofnewyork.us/api/views/vk9f-gvzq

property e:vk9f-gvzq t:meta.view d:2017-09-25T07:27:35.373Z v:averageRating=0 v:name="DOP Juvenile Investigations Assigned" v:attribution="Department of Probation (DOP)" v:id=vk9f-gvzq v:category="Public Safety"

property e:vk9f-gvzq t:meta.view.owner d:2017-09-25T07:27:35.373Z v:displayName="NYC OpenData" v:lastNotificationSeenAt=1496414226 v:id=5fuc-pqz2 v:screenName="NYC OpenData"

property e:vk9f-gvzq t:meta.view.tableauthor d:2017-09-25T07:27:35.373Z v:displayName="NYC OpenData" v:lastNotificationSeenAt=1496414226 v:roleName=administrator v:id=5fuc-pqz2 v:screenName="NYC OpenData"
```

## Top Records

```ls
| borough  | total_investigations_assigned | month     | year | investigations_assigned_count | 
| ======== | ============================= | ========= | ==== | ============================= | 
| Citywide | Total                         | September | 2016 | 112                           | 
| Citywide | Total                         | November  | 2016 | 146                           | 
| Citywide | Total                         | December  | 2016 | 166                           | 
| Citywide | Total                         | January   | 2017 | 200                           | 
| Citywide | Total                         | February  | 2017 | 156                           | 
| Citywide | Total                         | March     | 2017 | 191                           | 
| Citywide | Total                         | April     | 2017 | 164                           | 
| Citywide | Total                         | May       | 2017 | 192                           | 
| Citywide | Total                         | June      | 2017 | 165                           | 
| Citywide | Total                         | July      | 2017 | 150                           | 
```