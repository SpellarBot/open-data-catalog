# IHPA - IL State Historic Site Attendance 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ihpa-il-state-historic-site-attendance-2013-a7a35) |
| Metadata | [Link](https://data.illinois.gov/api/views/ycxu-pahq) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/ycxu-pahq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/ycxu-pahq/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | ycxu-pahq |
| Name | IHPA - IL State Historic Site Attendance 2013 |
| Attribution | IHPA |
| Category | Reference |
| Tags | attendance, historic sites, tourism |
| Created | 2014-07-21T17:05:25Z |
| Publication Date | 2014-07-21T19:20:34Z |

## Description

2013 Attendance Figures for Illinois State Historic Sites

## Columns

```ls
| Included | Schema Type    | Field Name                        | Name                              | Data Type | Render Type |
| ======== | ============== | ================================= | ================================= | ========= | =========== |
| Yes      | series tag     | illinois_state_historic_site_name | Illinois State Historic Site Name | text      | text        |
| Yes      | numeric metric | 2013_attendance                   | 2013 Attendance                   | number    | number      |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ycxu-pahq d:2013-01-01T00:00:00.000Z t:illinois_state_historic_site_name="Abraham Lincoln Presidential Library" m:2013_attendance=51294

series e:ycxu-pahq d:2013-01-01T00:00:00.000Z t:illinois_state_historic_site_name="Abraham Lincoln Presidential Museum" m:2013_attendance=321071

series e:ycxu-pahq d:2013-01-01T00:00:00.000Z t:illinois_state_historic_site_name="Apple River" m:2013_attendance=14035
```

## Meta Commands

```ls
metric m:2013_attendance p:integer l:"2013 Attendance" t:dataTypeName=number

entity e:ycxu-pahq l:"IHPA - IL State Historic Site Attendance 2013" t:attribution=IHPA t:url=https://data.illinois.gov/api/views/ycxu-pahq

property e:ycxu-pahq t:meta.view v:id=ycxu-pahq v:category=Reference v:averageRating=0 v:name="IHPA - IL State Historic Site Attendance 2013" v:attribution=IHPA

property e:ycxu-pahq t:meta.view.license v:name="Public Domain"

property e:ycxu-pahq t:meta.view.owner v:id=5iir-ecwn v:screenName=jtedrow v:displayName=jtedrow

property e:ycxu-pahq t:meta.view.tableauthor v:id=5iir-ecwn v:screenName=jtedrow v:roleName=publisher v:displayName=jtedrow
```

## Top Records

```ls
| illinois_state_historic_site_name    | 2013_attendance | 
| ==================================== | =============== | 
| Abraham Lincoln Presidential Library | 51294           | 
| Abraham Lincoln Presidential Museum  | 321071          | 
| Apple River                          | 14035           | 
| Bishop Hill                          | 28309           | 
| Black Hawk                           | 126046          | 
| Bryant Cottage                       | 7230            | 
| Cahokia Courthouse                   | 3614            | 
| Cahokia Mounds                       | 270733          | 
| Carl Sandburg                        | 1749            | 
| Dana-Thomas House                    | 23893           | 
```