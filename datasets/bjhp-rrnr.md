# IHPA - IL State Historic Site Attendance 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ihpa-il-state-historic-site-attendance-2011-267f4) |
| Metadata | [Link](https://data.illinois.gov/api/views/bjhp-rrnr) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/bjhp-rrnr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/bjhp-rrnr/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | bjhp-rrnr |
| Name | IHPA - IL State Historic Site Attendance 2011 |
| Category | Economics |
| Tags | attendance, historic sites, tourism |
| Created | 2012-02-22T02:17:06Z |
| Publication Date | 2012-02-22T02:19:09Z |

## Description

2011 Attendance Figures for Illinois State Historic Sites

## Columns

```ls
| Included | Schema Type    | Field Name                        | Name                              | Data Type | Render Type |
| ======== | ============== | ================================= | ================================= | ========= | =========== |
| Yes      | series tag     | illinois_state_historic_site_name | Illinois State Historic Site Name | text      | text        |
| Yes      | numeric metric | attendance                        | 2011 Attendance                   | number    | number      |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:bjhp-rrnr d:2011-01-01T00:00:00.000Z t:illinois_state_historic_site_name="Abraham Lincoln Presidential Library" m:attendance=54396

series e:bjhp-rrnr d:2011-01-01T00:00:00.000Z t:illinois_state_historic_site_name="Abraham Lincoln Presidential Museum" m:attendance=293135

series e:bjhp-rrnr d:2011-01-01T00:00:00.000Z t:illinois_state_historic_site_name="Apple River Fort" m:attendance=13465
```

## Meta Commands

```ls
metric m:attendance p:integer l:"2011 Attendance" t:dataTypeName=number

entity e:bjhp-rrnr l:"IHPA - IL State Historic Site Attendance 2011" t:url=https://data.illinois.gov/api/views/bjhp-rrnr

property e:bjhp-rrnr t:meta.view v:id=bjhp-rrnr v:category=Economics v:averageRating=0 v:name="IHPA - IL State Historic Site Attendance 2011"

property e:bjhp-rrnr t:meta.view.license v:name="Public Domain"

property e:bjhp-rrnr t:meta.view.owner v:id=e57s-ksvb v:screenName="Trey McGhee" v:displayName="Trey McGhee"

property e:bjhp-rrnr t:meta.view.tableauthor v:id=e57s-ksvb v:screenName="Trey McGhee" v:roleName=publisher v:displayName="Trey McGhee"
```

## Top Records

```ls
| illinois_state_historic_site_name    | attendance | 
| ==================================== | ========== | 
| Abraham Lincoln Presidential Library | 54396      | 
| Abraham Lincoln Presidential Museum  | 293135     | 
| Apple River Fort                     | 13465      | 
| Bishop Hill                          | 23601      | 
| Black Hawk                           | 123772     | 
| Bryant Cottage                       | 6294       | 
| Cahokia Courthouse                   | 2779       | 
| Cahokia Mounds                       | 287525     | 
| Carl Sandburg                        | 2455       | 
| Dana-Thomas House*                   | 5625       | 
```