# IHPA - IL State Historic Site Attendance 2002

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ihpa-il-state-historic-site-attendance-2002-031eb) |
| Metadata | [Link](https://data.illinois.gov/api/views/x2w7-f6iq) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/x2w7-f6iq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/x2w7-f6iq/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | x2w7-f6iq |
| Name | IHPA - IL State Historic Site Attendance 2002 |
| Category | Economics |
| Tags | attendance, historic sites, tourism |
| Created | 2012-02-22T01:52:42Z |
| Publication Date | 2012-02-22T01:53:59Z |

## Description

2002 Attendance Figures for Illinois State Historic Sites

## Columns

```ls
| Included | Schema Type    | Field Name                           | Name                                 | Data Type | Render Type |
| ======== | ============== | ==================================== | ==================================== | ========= | =========== |
| Yes      | series tag     | state_of_illinois_historic_site_name | State of Illinois Historic Site Name | text      | text        |
| Yes      | numeric metric | attendance                           | 2002 Attendance                      | number    | number      |
```

## Time Field

```ls
Value = 2002
Format & Zone = yyyy
```

## Data Commands

```ls
series e:x2w7-f6iq d:2002-01-01T00:00:00.000Z t:state_of_illinois_historic_site_name="Abraham Lincoln Presidential Library" m:attendance=0

series e:x2w7-f6iq d:2002-01-01T00:00:00.000Z t:state_of_illinois_historic_site_name="Abraham Lincoln Presidential Museum" m:attendance=0

series e:x2w7-f6iq d:2002-01-01T00:00:00.000Z t:state_of_illinois_historic_site_name="Apple River Fort" m:attendance=25380
```

## Meta Commands

```ls
metric m:attendance p:integer l:"2002 Attendance" t:dataTypeName=number

entity e:x2w7-f6iq l:"IHPA - IL State Historic Site Attendance 2002" t:url=https://data.illinois.gov/api/views/x2w7-f6iq

property e:x2w7-f6iq t:meta.view v:id=x2w7-f6iq v:category=Economics v:averageRating=0 v:name="IHPA - IL State Historic Site Attendance 2002"

property e:x2w7-f6iq t:meta.view.license v:name="Public Domain"

property e:x2w7-f6iq t:meta.view.owner v:id=e57s-ksvb v:screenName="Trey McGhee" v:displayName="Trey McGhee"

property e:x2w7-f6iq t:meta.view.tableauthor v:id=e57s-ksvb v:screenName="Trey McGhee" v:roleName=publisher v:displayName="Trey McGhee"
```

## Top Records

```ls
| state_of_illinois_historic_site_name | attendance | 
| ==================================== | ========== | 
| Abraham Lincoln Presidential Library | 0          | 
| Abraham Lincoln Presidential Museum  | 0          | 
| Apple River Fort                     | 25380      | 
| Bishop Hill                          | 56346      | 
| Black Hawk                           | 147706     | 
| Bryant Cottage                       | 5528       | 
| Cahokia Courthouse                   | 24104      | 
| Cahokia Mounds                       | 381032     | 
| Carl Sandburg                        | 14262      | 
| Dana-Thomas House                    | 41707      | 
```