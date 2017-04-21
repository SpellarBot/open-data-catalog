# Directory Of Homeless Drop- In Centers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/directory-of-homeless-drop-in-centers-0786e) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/bmxf-3rd4) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/bmxf-3rd4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/bmxf-3rd4/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | bmxf-3rd4 |
| Name | Directory Of Homeless Drop- In Centers |
| Attribution | Department of Homeless Services (DHS) |
| Category | Social Services |
| Tags | dhs, homeless, shelter, drop-in, center |
| Created | 2013-01-30T22:39:37Z |
| Publication Date | 2013-01-30T22:43:56Z |

## Description

List of centers where homeless people are provided with hot meals, showers, medical help and a place to sleep

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type | Render Type |
| ======== | =========== | =========== | =========== | ========= | =========== |
| No       | time        | :updated_at | updated_at  | meta_data | meta_data   |
| Yes      | series tag  | center_name | Center Name | text      | text        |
| Yes      | series tag  | borough     | Borough     | text      | text        |
| Yes      | series tag  | comments    | Comments    | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:bmxf-3rd4 d:2013-01-30T14:39:38.000Z t:center_name=Mainchance t:borough=Manhattan t:comments="Open 24 hours" m:row_number.bmxf-3rd4=1

series e:bmxf-3rd4 d:2013-01-30T14:39:38.000Z t:center_name="The Living Room" t:borough=Bronx t:comments="Open 24 hours" m:row_number.bmxf-3rd4=2

series e:bmxf-3rd4 d:2013-01-30T14:39:38.000Z t:center_name="Olivieri Center" t:borough=Manhattan t:comments="Open from 7:30 a.m.-8:30 p.m. This program remain open 24 hours during winter months" m:row_number.bmxf-3rd4=3
```

## Meta Commands

```ls
metric m:row_number.bmxf-3rd4 p:long l:"Row Number"

entity e:bmxf-3rd4 l:"Directory Of Homeless Drop- In Centers" t:attribution="Department of Homeless Services (DHS)" t:url=https://data.cityofnewyork.us/api/views/bmxf-3rd4

property e:bmxf-3rd4 t:meta.view v:id=bmxf-3rd4 v:category="Social Services" v:attributionLink=http://www.nyc.gov/html/dhs/html/outreach/outreach.shtml v:averageRating=0 v:name="Directory Of Homeless Drop- In Centers" v:attribution="Department of Homeless Services (DHS)"

property e:bmxf-3rd4 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:bmxf-3rd4 t:meta.view.tableauthor v:id=8b43-zkvh v:screenName="Ram S." v:displayName="Ram S."
```

## Top Records

```ls
| :updated_at | center_name         | borough       | comments                                                                             | 
| =========== | =================== | ============= | ==================================================================================== | 
| 1359556778  | Mainchance          | Manhattan     | Open 24 hours                                                                        | 
| 1359556778  | The Living Room     | Bronx         | Open 24 hours                                                                        | 
| 1359556778  | Olivieri Center     | Manhattan     | Open from 7:30 a.m.-8:30 p.m. This program remain open 24 hours during winter months | 
| 1359556778  | The Gathering Place | Brooklyn      | Open from 7:30 a.m.-8:30 p.m. This program remain open 24 hours during winter months | 
| 1359556778  | Project Hospitality | Staten Island | Open from 7:30 a.m.-8:30 p.m. This program remain open 24 hours during winter months | 
```