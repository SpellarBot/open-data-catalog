# IHPA - IL State Historic Site Attendance 2007

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ihpa-il-state-historic-site-attendance-2007-585c7) |
| Metadata | [Link](https://data.illinois.gov/api/views/fhqd-4t4b) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/fhqd-4t4b/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/fhqd-4t4b/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | fhqd-4t4b |
| Name | IHPA - IL State Historic Site Attendance 2007 |
| Category | Economics |
| Tags | attendance, historic sites, tourism |
| Created | 2012-02-22T02:00:01Z |
| Publication Date | 2012-02-22T02:01:22Z |

## Description

2007 Attendance Figures for Illinois State Historic Sites

## Columns

```ls
| Included | Schema Type    | Field Name                           | Name                                 | Data Type | Render Type |
| ======== | ============== | ==================================== | ==================================== | ========= | =========== |
| Yes      | series tag     | state_of_illinois_historic_site_name | State of Illinois Historic Site Name | text      | text        |
| Yes      | numeric metric | attendance                           | 2007 Attendance                      | number    | number      |
```

## Time Field

```ls
Value = 2007
Format & Zone = yyyy
```

## Data Commands

```ls
series e:fhqd-4t4b d:2007-01-01T00:00:00.000Z t:state_of_illinois_historic_site_name="Abraham Lincoln Presidential Library" m:attendance=62342

series e:fhqd-4t4b d:2007-01-01T00:00:00.000Z t:state_of_illinois_historic_site_name="Abraham Lincoln Presidential Museum" m:attendance=424472

series e:fhqd-4t4b d:2007-01-01T00:00:00.000Z t:state_of_illinois_historic_site_name="Apple River Fort" m:attendance=24693
```

## Meta Commands

```ls
metric m:attendance p:integer l:"2007 Attendance" t:dataTypeName=number

entity e:fhqd-4t4b l:"IHPA - IL State Historic Site Attendance 2007" t:url=https://data.illinois.gov/api/views/fhqd-4t4b

property e:fhqd-4t4b t:meta.view v:id=fhqd-4t4b v:category=Economics v:averageRating=0 v:name="IHPA - IL State Historic Site Attendance 2007"

property e:fhqd-4t4b t:meta.view.license v:name="Public Domain"

property e:fhqd-4t4b t:meta.view.owner v:id=e57s-ksvb v:screenName="Trey McGhee" v:displayName="Trey McGhee"

property e:fhqd-4t4b t:meta.view.tableauthor v:id=e57s-ksvb v:screenName="Trey McGhee" v:roleName=publisher v:displayName="Trey McGhee"
```

## Top Records

```ls
| state_of_illinois_historic_site_name | attendance | 
| ==================================== | ========== | 
| Abraham Lincoln Presidential Library | 62342      | 
| Abraham Lincoln Presidential Museum  | 424472     | 
| Apple River Fort                     | 24693      | 
| Bishop Hill                          | 19551      | 
| Black Hawk                           | 138668     | 
| Bryant Cottage                       | 5176       | 
| Cahokia Courthouse                   | 8414       | 
| Cahokia Mounds                       | 329428     | 
| Carl Sandburg                        | 8598       | 
| Dana-Thomas House                    | 41045      | 
```