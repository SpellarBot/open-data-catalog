# IHPA - IL State Historic Site Attendance 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ihpa-il-state-historic-site-attendance-2010-d91dc) |
| Metadata | [Link](https://data.illinois.gov/api/views/4tfy-cb5j) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/4tfy-cb5j/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/4tfy-cb5j/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 4tfy-cb5j |
| Name | IHPA - IL State Historic Site Attendance 2010 |
| Category | Economics |
| Tags | attendance, historic sites, tourism |
| Created | 2012-02-22T02:15:19Z |
| Publication Date | 2012-02-22T02:16:28Z |

## Description

2010 Attendance Figures for Illinois State Historic Sites

## Columns

```ls
| Included | Schema Type    | Field Name                           | Name                                 | Data Type | Render Type |
| ======== | ============== | ==================================== | ==================================== | ========= | =========== |
| Yes      | series tag     | state_of_illinois_historic_site_name | State of Illinois Historic Site Name | text      | text        |
| Yes      | numeric metric | attendance                           | 2010 Attendance                      | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:4tfy-cb5j d:2010-01-01T00:00:00.000Z t:state_of_illinois_historic_site_name="Abraham Lincoln Presidential Library" m:attendance=34647

series e:4tfy-cb5j d:2010-01-01T00:00:00.000Z t:state_of_illinois_historic_site_name="Abraham Lincoln Presidential Museum" m:attendance=311837

series e:4tfy-cb5j d:2010-01-01T00:00:00.000Z t:state_of_illinois_historic_site_name="Apple River Fort" m:attendance=14338
```

## Meta Commands

```ls
metric m:attendance p:integer l:"2010 Attendance" t:dataTypeName=number

entity e:4tfy-cb5j l:"IHPA - IL State Historic Site Attendance 2010" t:url=https://data.illinois.gov/api/views/4tfy-cb5j

property e:4tfy-cb5j t:meta.view v:id=4tfy-cb5j v:category=Economics v:averageRating=0 v:name="IHPA - IL State Historic Site Attendance 2010"

property e:4tfy-cb5j t:meta.view.license v:name="Public Domain"

property e:4tfy-cb5j t:meta.view.owner v:id=e57s-ksvb v:screenName="Trey McGhee" v:displayName="Trey McGhee"

property e:4tfy-cb5j t:meta.view.tableauthor v:id=e57s-ksvb v:screenName="Trey McGhee" v:roleName=publisher v:displayName="Trey McGhee"
```

## Top Records

```ls
| state_of_illinois_historic_site_name | attendance | 
| ==================================== | ========== | 
| Abraham Lincoln Presidential Library | 34647      | 
| Abraham Lincoln Presidential Museum  | 311837     | 
| Apple River Fort                     | 14338      | 
| Bishop Hill                          | 24557      | 
| Black Hawk                           | 134099     | 
| Bryant Cottage                       | 6244       | 
| Cahokia Courthouse                   | 8125       | 
| Cahokia Mounds                       | 308447     | 
| Carl Sandburg                        | 2620       | 
| Dana-Thomas House                    | 32771      | 
```