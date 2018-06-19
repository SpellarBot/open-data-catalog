# IHPA - IL State Historic Site Attendance 2008

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ihpa-il-state-historic-site-attendance-2008-0f6d4) |
| Metadata | [Link](https://data.illinois.gov/api/views/29wj-tkxe) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/29wj-tkxe/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/29wj-tkxe/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 29wj-tkxe |
| Name | IHPA - IL State Historic Site Attendance 2008 |
| Category | Economics |
| Tags | attendance, historic sites, tourism |
| Created | 2012-02-22T02:02:11Z |
| Publication Date | 2012-02-22T02:03:43Z |

## Description

2008 Attendance Figures for Illinois State Historic Sites

## Columns

```ls
| Included | Schema Type    | Field Name                           | Name                                 | Data Type | Render Type |
| ======== | ============== | ==================================== | ==================================== | ========= | =========== |
| Yes      | series tag     | state_of_illinois_historic_site_name | State of Illinois Historic Site Name | text      | text        |
| Yes      | numeric metric | attendance                           | 2008 Attendance                      | number    | number      |
| Yes      | series tag     | closed_november_through_december     | Closed November through December     | text      | text        |
```

## Time Field

```ls
Value = 2008
Format & Zone = yyyy
```

## Data Commands

```ls
series e:29wj-tkxe d:2008-01-01T00:00:00.000Z t:state_of_illinois_historic_site_name="Abraham Lincoln Presidential Library" m:attendance=62658

series e:29wj-tkxe d:2008-01-01T00:00:00.000Z t:state_of_illinois_historic_site_name="Abraham Lincoln Presidential Museum" m:attendance=350551

series e:29wj-tkxe d:2008-01-01T00:00:00.000Z t:closed_november_through_december=Yes t:state_of_illinois_historic_site_name="Apple River Fort" m:attendance=20016
```

## Meta Commands

```ls
metric m:attendance p:integer l:"2008 Attendance" t:dataTypeName=number

entity e:29wj-tkxe l:"IHPA - IL State Historic Site Attendance 2008" t:url=https://data.illinois.gov/api/views/29wj-tkxe

property e:29wj-tkxe t:meta.view v:id=29wj-tkxe v:category=Economics v:averageRating=0 v:name="IHPA - IL State Historic Site Attendance 2008"

property e:29wj-tkxe t:meta.view.license v:name="Public Domain"

property e:29wj-tkxe t:meta.view.owner v:id=e57s-ksvb v:screenName="Trey McGhee" v:displayName="Trey McGhee"

property e:29wj-tkxe t:meta.view.tableauthor v:id=e57s-ksvb v:screenName="Trey McGhee" v:roleName=publisher v:displayName="Trey McGhee"
```

## Top Records

```ls
| state_of_illinois_historic_site_name | attendance | closed_november_through_december | 
| ==================================== | ========== | ================================ | 
| Abraham Lincoln Presidential Library | 62658      |                                  | 
| Abraham Lincoln Presidential Museum  | 350551     |                                  | 
| Apple River Fort                     | 20016      | Yes                              | 
| Bishop Hill                          | 23538      | Yes                              | 
| Black Hawk                           | 109492     | Yes                              | 
| Bryant Cottage                       | 5076       | Yes                              | 
| Cahokia Courthouse                   | 7975       | Yes                              | 
| Cahokia Mounds                       | 258527     | Yes                              | 
| Carl Sandburg                        | 15060      | Yes                              | 
| Dana-Thomas House                    | 35714      | Yes                              | 
```