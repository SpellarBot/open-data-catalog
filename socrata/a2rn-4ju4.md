# Community Board Applications

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/community-board-applications-d08ea) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/a2rn-4ju4) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/a2rn-4ju4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/a2rn-4ju4/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | a2rn-4ju4 |
| Name | Community Board Applications |
| Attribution | Manhattan Borough President (MBP) |
| Category | City Government |
| Tags | community board applications, mbp, manhattan borough president (mbp) |
| Created | 2014-03-06T17:42:43Z |
| Publication Date | 2014-03-06T17:43:36Z |

## Description

This list contains information on community board applications.

## Columns

```ls
| Included | Schema Type | Field Name            | Name                  | Data Type | Render Type |
| ======== | =========== | ===================== | ===================== | ========= | =========== |
| No       | time        | :updated_at           | updated_at            | meta_data | meta_data   |
| Yes      | series tag  | community_board_topic | Community Board Topic | text      | text        |
| Yes      | series tag  | url                   | URL                   | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:a2rn-4ju4 d:2014-03-06T09:42:46.000Z t:community_board_topic="To be named to you local Community Board:" t:url=http://manhattanbp.nyc.gov/downloads/pdf/CBNewApp2014.pdf m:row_number.a2rn-4ju4=1

series e:a2rn-4ju4 d:2014-03-06T09:42:46.000Z t:community_board_topic="To seek re-appointment:" t:url=http://manhattanbp.nyc.gov/downloads/pdf/CBReApp2014.pdf m:row_number.a2rn-4ju4=2

series e:a2rn-4ju4 d:2014-03-06T09:42:46.000Z t:community_board_topic="For general information on Community Boards:" t:url=http://manhattanbp.nyc.gov/html/community-boards/community-boards.shtml m:row_number.a2rn-4ju4=3
```

## Meta Commands

```ls
metric m:row_number.a2rn-4ju4 p:long l:"Row Number"

entity e:a2rn-4ju4 l:"Community Board Applications" t:attribution="Manhattan Borough President (MBP)" t:url=https://data.cityofnewyork.us/api/views/a2rn-4ju4

property e:a2rn-4ju4 t:meta.view v:id=a2rn-4ju4 v:category="City Government" v:averageRating=0 v:name="Community Board Applications" v:attribution="Manhattan Borough President (MBP)"

property e:a2rn-4ju4 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:a2rn-4ju4 t:meta.view.tableauthor v:id=txun-eb7e v:screenName="Albert Webber" v:roleName=administrator v:displayName="Albert Webber"
```

## Top Records

```ls
| :updated_at | community_board_topic                                                  | url                                                                     | 
| =========== | ====================================================================== | ======================================================================= | 
| 1394098966  | To be named to you local Community Board:                              | http://manhattanbp.nyc.gov/downloads/pdf/CBNewApp2014.pdf               | 
| 1394098966  | To seek re-appointment:                                                | http://manhattanbp.nyc.gov/downloads/pdf/CBReApp2014.pdf                | 
| 1394098966  | For general information on Community Boards:                           | http://manhattanbp.nyc.gov/html/community-boards/community-boards.shtml | 
| 1394098966  | For a directory of each of Manhattan's 12 Community Boards             | http://www.nyc.gov/html/cau/html/cb/manhattan.shtml                     | 
| 1394098966  | To learn more about Community Boards and NYC Public officials          | http://www.nyc.gov/html/cau/html/cb/about.shtml#board                   | 
| 1394098966  | To reach the scheduling office of the Manhattan Borough President:     | scheduling@manhattanbp.nyc.gov                                          | 
| 1394098966  | To contact the communication staff of the Manhattan Borough President: | press@manhattanbp.nyc.gov                                               | 
| 1394098966  | For general inquiries addressed to the Manhattan Borough President:    | info@manhattanbp.nyc.gov                                                | 
```