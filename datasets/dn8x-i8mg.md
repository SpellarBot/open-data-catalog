# IHPA - IL State Historic Site Attendance 2005

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ihpa-il-state-historic-site-attendance-2005-a76fc) |
| Metadata | [Link](https://data.illinois.gov/api/views/dn8x-i8mg) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/dn8x-i8mg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/dn8x-i8mg/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | dn8x-i8mg |
| Name | IHPA - IL State Historic Site Attendance 2005 |
| Category | Economics |
| Tags | attendance, historic sites, tourism |
| Created | 2012-02-22T01:58:10Z |
| Publication Date | 2012-02-22T01:59:16Z |

## Description

2005 Attendance Figures for Illinois State Historic Sites

## Columns

```ls
| Included | Schema Type    | Field Name                           | Name                                 | Data Type | Render Type |
| ======== | ============== | ==================================== | ==================================== | ========= | =========== |
| Yes      | series tag     | state_of_illinois_historic_site_name | State of Illinois Historic Site Name | text      | text        |
| Yes      | numeric metric | attendance                           | 2005 Attendance                      | number    | number      |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:dn8x-i8mg d:2005-01-01T00:00:00.000Z t:state_of_illinois_historic_site_name="Abraham Lincoln Presidential Library" m:attendance=91586

series e:dn8x-i8mg d:2005-01-01T00:00:00.000Z t:state_of_illinois_historic_site_name="Abraham Lincoln Presidential Museum" m:attendance=488968

series e:dn8x-i8mg d:2005-01-01T00:00:00.000Z t:state_of_illinois_historic_site_name="Apple River Fort" m:attendance=25461
```

## Meta Commands

```ls
metric m:attendance p:integer l:"2005 Attendance" t:dataTypeName=number

entity e:dn8x-i8mg l:"IHPA - IL State Historic Site Attendance 2005" t:url=https://data.illinois.gov/api/views/dn8x-i8mg

property e:dn8x-i8mg t:meta.view v:id=dn8x-i8mg v:category=Economics v:averageRating=0 v:name="IHPA - IL State Historic Site Attendance 2005"

property e:dn8x-i8mg t:meta.view.license v:name="Public Domain"

property e:dn8x-i8mg t:meta.view.owner v:id=e57s-ksvb v:screenName="Trey McGhee" v:displayName="Trey McGhee"

property e:dn8x-i8mg t:meta.view.tableauthor v:id=e57s-ksvb v:screenName="Trey McGhee" v:roleName=publisher v:displayName="Trey McGhee"
```

## Top Records

```ls
| state_of_illinois_historic_site_name | attendance | 
| ==================================== | ========== | 
| Abraham Lincoln Presidential Library | 91586      | 
| Abraham Lincoln Presidential Museum  | 488968     | 
| Apple River Fort                     | 25461      | 
| Bishop Hill                          | 35865      | 
| Black Hawk                           | 147110     | 
| Bryant Cottage                       | 5219       | 
| Cahokia Courthouse                   | 13719      | 
| Cahokia Mounds                       | 323117     | 
| Carl Sandburg                        | 15393      | 
| Dana-Thomas House                    | 37884      | 
```