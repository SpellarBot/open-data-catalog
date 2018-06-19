# IHPA - IL State Historic Site Attendance 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ihpa-il-state-historic-site-attendance-2009-85c40) |
| Metadata | [Link](https://data.illinois.gov/api/views/4d2s-7ddh) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/4d2s-7ddh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/4d2s-7ddh/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 4d2s-7ddh |
| Name | IHPA - IL State Historic Site Attendance 2009 |
| Tags | attendance, historic sites, tourism |
| Created | 2012-02-22T02:12:56Z |
| Publication Date | 2012-02-22T02:14:46Z |

## Description

2009 Attendance Figures for Illinois State Historic Sites

## Columns

```ls
| Included | Schema Type    | Field Name                           | Name                                 | Data Type | Render Type |
| ======== | ============== | ==================================== | ==================================== | ========= | =========== |
| Yes      | series tag     | state_of_illinois_historic_site_name | State of Illinois Historic Site Name | text      | text        |
| Yes      | numeric metric | attendance                           | 2009 Attendance                      | number    | number      |
```

## Time Field

```ls
Value = 2009
Format & Zone = yyyy
```

## Data Commands

```ls
series e:4d2s-7ddh d:2009-01-01T00:00:00.000Z t:state_of_illinois_historic_site_name="Abraham Lincoln Presidential Library" m:attendance=64112

series e:4d2s-7ddh d:2009-01-01T00:00:00.000Z t:state_of_illinois_historic_site_name="Abraham Lincoln Presidential Museum" m:attendance=410825

series e:4d2s-7ddh d:2009-01-01T00:00:00.000Z t:state_of_illinois_historic_site_name="Apple River Fort" m:attendance=11440
```

## Meta Commands

```ls
metric m:attendance p:integer l:"2009 Attendance" t:dataTypeName=number

entity e:4d2s-7ddh l:"IHPA - IL State Historic Site Attendance 2009" t:url=https://data.illinois.gov/api/views/4d2s-7ddh

property e:4d2s-7ddh t:meta.view v:id=4d2s-7ddh v:averageRating=0 v:name="IHPA - IL State Historic Site Attendance 2009"

property e:4d2s-7ddh t:meta.view.license v:name="Public Domain"

property e:4d2s-7ddh t:meta.view.owner v:id=e57s-ksvb v:screenName="Trey McGhee" v:displayName="Trey McGhee"

property e:4d2s-7ddh t:meta.view.tableauthor v:id=e57s-ksvb v:screenName="Trey McGhee" v:roleName=publisher v:displayName="Trey McGhee"
```

## Top Records

```ls
| state_of_illinois_historic_site_name | attendance | 
| ==================================== | ========== | 
| Abraham Lincoln Presidential Library | 64112      | 
| Abraham Lincoln Presidential Museum  | 410825     | 
| Apple River Fort                     | 11440      | 
| Bishop Hill                          | 25685      | 
| Black Hawk                           | 114448     | 
| Bryant Cottage                       | 5609       | 
| Cahokia Courthouse                   | 4653       | 
| Cahokia Mounds                       | 317002     | 
| Carl Sandburg                        | 3027       | 
| Dana-Thomas House                    | 30380      | 
```