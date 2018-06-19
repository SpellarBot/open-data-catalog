# Council Committees And Meetings

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/council-committees-and-meetings) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/m48u-yjt8) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/m48u-yjt8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/m48u-yjt8/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | m48u-yjt8 |
| Name | Council Committees And Meetings |
| Attribution | New York City Council (NYCC) |
| Category | City Government |
| Tags | council committees and meetings, city council, schedule |
| Created | 2015-02-17T17:44:02Z |
| Publication Date | 2015-02-17T17:49:57Z |

## Description

This list contains information on committee and full Council meetings

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type     | Render Type   |
| ======== | =========== | ================ | ================ | ============= | ============= |
| Yes      | series tag  | name             | Name             | text          | text          |
| Yes      | time        | meeting_date     |  Meeting Date    | calendar_date | calendar_date |
| No       |             | meeting_time     | Meeting Time     | text          | text          |
| Yes      | series tag  | meeting_location | Meeting Location | text          | text          |
| Yes      | series tag  | meeting_topic    | Meeting Topic    | text          | text          |
```

## Time Field

```ls
Value = meeting_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = meeting_time
```

## Data Commands

```ls
series e:m48u-yjt8 d:2014-12-17T00:00:00.000Z t:meeting_topic="Multiple meeting items, please see Meeting Details for more information" t:name="City Council Stated Meeting" t:meeting_location="Council Chambers - City Hall" m:row_number.m48u-yjt8=1

series e:m48u-yjt8 d:2014-12-17T00:00:00.000Z t:meeting_topic="Multiple meeting items, please see Meeting Details for more information" t:name="Committee on Rules, Privileges and Elections" t:meeting_location="Council Chambers - City Hall" m:row_number.m48u-yjt8=2

series e:m48u-yjt8 d:2014-12-17T00:00:00.000Z t:meeting_topic="Multiple meeting items, please see Meeting Details for more information" t:name="Committee on Finance" t:meeting_location="Committee Room - City Hall" m:row_number.m48u-yjt8=3
```

## Meta Commands

```ls
metric m:row_number.m48u-yjt8 p:long l:"Row Number"

entity e:m48u-yjt8 l:"Council Committees And Meetings" t:attribution="New York City Council (NYCC)" t:url=https://data.cityofnewyork.us/api/views/m48u-yjt8

property e:m48u-yjt8 t:meta.view v:id=m48u-yjt8 v:category="City Government" v:averageRating=0 v:name="Council Committees And Meetings" v:attribution="New York City Council (NYCC)"

property e:m48u-yjt8 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:m48u-yjt8 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| name                                                                            | meeting_date        | meeting_time | meeting_location                      | meeting_topic                                                                                    | 
| =============================================================================== | =================== | ============ | ===================================== | ================================================================================================ | 
| City Council Stated Meeting                                                     | 2014-12-17T00:00:00 | 1:30 PM      | Council Chambers - City Hall          | Multiple meeting items, please see Meeting Details for more information                          | 
| Committee on Rules, Privileges and Elections                                    | 2014-12-17T00:00:00 | 10:30 AM     | Council Chambers - City Hall          | Multiple meeting items, please see Meeting Details for more information                          | 
| Committee on Finance                                                            | 2014-12-17T00:00:00 | 10:00 AM     | Committee Room - City Hall            | Multiple meeting items, please see Meeting Details for more information                          | 
| Committee on Health                                                             | 2014-12-16T00:00:00 | 1:00 PM      | Committee Room - City Hall            | Multiple meeting items, please see Meeting Details for more information                          | 
| Committee on Cultural Affairs, Libraries and International Intergroup Relations | 2014-12-16T00:00:00 | 12:45 PM     | Committee Room - City Hall            | Recognizing and commemorating January 13th as Korean American Day in NYC.                        | 
| Committee on Land Use                                                           | 2014-12-16T00:00:00 | 11:00 AM     | Committee Room - City Hall            | Multiple meeting items, please see Meeting Details for more information                          | 
| Subcommittee on Landmarks, Public Siting and Maritime Uses                      | 2014-12-16T00:00:00 | Deferred     | Committee Room - City Hall            | Landmarks, South Brooklyn Marine Terminal, 81 39th St, Brooklyn (20155247 PNK)                   | 
| Committee on Public Housing                                                     | 2014-12-16T00:00:00 | 10:00 AM     | Council Chambers - City Hall          | Oversight: The Relationship between Lighting and Safety in the Wake of the Akai Gurley Shooting. | 
| Committee on Parks and Recreation                                               | 2014-12-16T00:00:00 | 10:00 AM     | 250 Broadway - Committee Rm, 14th Fl. | Oversight - The State of Natural Areas Under the Care of the Parks Department.                   | 
| Committee on Recovery and Resiliency                                            | 2014-12-16T00:00:00 | 10:00 AM     | 250 Broadway - Committee Rm, 16th Fl. | Creation of a Hurricane Sandy community groups and houses of worship recovery task force.        | 
```