# IHPA - IL State Historic Site Attendance 2003

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ihpa-il-state-historic-site-attendance-2003-8ef65) |
| Metadata | [Link](https://data.illinois.gov/api/views/6ny2-2cnf) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/6ny2-2cnf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/6ny2-2cnf/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 6ny2-2cnf |
| Name | IHPA - IL State Historic Site Attendance 2003 |
| Category | Economics |
| Tags | attendance, historic sites, tourism |
| Created | 2012-02-22T01:55:47Z |
| Publication Date | 2012-02-22T01:57:21Z |

## Description

2003 Attendance Figures for Illinois State Historic Sites

## Columns

```ls
| Included | Schema Type    | Field Name                           | Name                                 | Data Type | Render Type |
| ======== | ============== | ==================================== | ==================================== | ========= | =========== |
| Yes      | series tag     | state_of_illinois_historic_site_name | State of Illinois Historic Site Name | text      | text        |
| Yes      | numeric metric | attendance                           | 2003 Attendance                      | number    | number      |
```

## Time Field

```ls
Value = 2003
Format & Zone = yyyy
```

## Data Commands

```ls
series e:6ny2-2cnf d:2003-01-01T00:00:00.000Z t:state_of_illinois_historic_site_name="Abraham Lincoln Presidential Library" m:attendance=0

series e:6ny2-2cnf d:2003-01-01T00:00:00.000Z t:state_of_illinois_historic_site_name="Abraham Lincoln Presidential Museum" m:attendance=0

series e:6ny2-2cnf d:2003-01-01T00:00:00.000Z t:state_of_illinois_historic_site_name="Apple River Fort" m:attendance=23472
```

## Meta Commands

```ls
metric m:attendance p:integer l:"2003 Attendance" t:dataTypeName=number

entity e:6ny2-2cnf l:"IHPA - IL State Historic Site Attendance 2003" t:url=https://data.illinois.gov/api/views/6ny2-2cnf

property e:6ny2-2cnf t:meta.view v:id=6ny2-2cnf v:category=Economics v:averageRating=0 v:name="IHPA - IL State Historic Site Attendance 2003"

property e:6ny2-2cnf t:meta.view.license v:name="Public Domain"

property e:6ny2-2cnf t:meta.view.owner v:id=e57s-ksvb v:screenName="Trey McGhee" v:displayName="Trey McGhee"

property e:6ny2-2cnf t:meta.view.tableauthor v:id=e57s-ksvb v:screenName="Trey McGhee" v:roleName=publisher v:displayName="Trey McGhee"
```

## Top Records

```ls
| state_of_illinois_historic_site_name | attendance | 
| ==================================== | ========== | 
| Abraham Lincoln Presidential Library | 0          | 
| Abraham Lincoln Presidential Museum  | 0          | 
| Apple River Fort                     | 23472      | 
| Bishop Hill                          | 59449      | 
| Black Hawk                           | 139533     | 
| Bryant Cottage                       | 3943       | 
| Cahokia Courthouse                   | 25238      | 
| Cahokia Mounds                       | 357022     | 
| Carl Sandburg                        | 10364      | 
| Dana-Thomas House                    | 37428      | 
```