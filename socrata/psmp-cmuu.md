# Street Weekly Resurfacing Schedule - Brooklyn

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/street-weekly-resurfacing-schedule-brooklyn-d9c37) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/psmp-cmuu) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/psmp-cmuu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/psmp-cmuu/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | psmp-cmuu |
| Name | Street Weekly Resurfacing Schedule - Brooklyn |
| Attribution | Department of Transportation (DOT) |
| Category | Transportation |
| Tags | dot, street resurfacing, brooklyn, resurfacing schedule |
| Created | 2014-10-22T15:08:45Z |
| Publication Date | 2014-10-22T15:10:50Z |

## Description

Brooklyn Milling and Paving Schedule

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| No       |             | day_date    | Day & Date | text      | text        |
| No       |             | sa          | Sa#        | text      | text        |
| Yes      | series tag  | location    | Location   | text      | text        |
| No       |             | cb          | CB         | number    | number      |
| Yes      | series tag  | area        | Area       | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = day_date,sa,cb
```

## Data Commands

```ls
series e:psmp-cmuu d:2014-10-22T08:08:47.000Z t:location="No Work" m:row_number.psmp-cmuu=1

series e:psmp-cmuu d:2014-10-22T08:08:47.000Z t:area="East Flatbush" t:location="2 Paving Crews
Ave J (Nostrand Ave to Albany Ave)" m:row_number.psmp-cmuu=2

series e:psmp-cmuu d:2014-10-22T08:08:47.000Z t:area="Paerdegat Basin" t:location="85 St (Foster Ave to Seaview Ave)" m:row_number.psmp-cmuu=3
```

## Meta Commands

```ls
metric m:row_number.psmp-cmuu p:long l:"Row Number"

entity e:psmp-cmuu l:"Street Weekly Resurfacing Schedule - Brooklyn" t:attribution="Department of Transportation (DOT)" t:url=https://data.cityofnewyork.us/api/views/psmp-cmuu

property e:psmp-cmuu t:meta.view v:id=psmp-cmuu v:category=Transportation v:attributionLink=http://a841-dotweb01.nyc.gov/datafeeds/Brooklyn%20Milling%20Paving%20Schedule.xml v:averageRating=0 v:name="Street Weekly Resurfacing Schedule - Brooklyn" v:attribution="Department of Transportation (DOT)"

property e:psmp-cmuu t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:psmp-cmuu t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | day_date            | sa          | location                                          | cb | area            | 
| =========== | =================== | =========== | ================================================= | == | =============== | 
| 1413965327  | Sunday, 10/19/2014  |             | No Work                                           |    |                 | 
| 1413965327  | Monday, 10/20/2014  | K2013-18-02 | 2 Paving Crews Ave J (Nostrand Ave to Albany Ave) | 18 | East Flatbush   | 
| 1413965327  | Monday, 10/20/2014  | K2008-18-13 | 85 St (Foster Ave to Seaview Ave)                 | 18 | Paerdegat Basin | 
| 1413965327  | Monday, 10/20/2014  | K2014-18-04 | Ave L (Utica Ave to E 41 St)                      | 18 | Flatlands       | 
| 1413965327  | Monday, 10/20/2014  | K2014-18-01 | 2 Milling Crews Ave K (Troy Ave to Flatlands Ave) | 18 | Flatlands       | 
| 1413965327  | Monday, 10/20/2014  | K2014-10-04 | Shore Rd (87 St to 4 Ave)                         | 10 | Bay Ridge       | 
| 1413965327  | Tuesday, 10/21/2014 | K2013-18-02 | 2 Paving Crews Ave J (Nostrand Ave to Albany Ave) | 18 | East Flatbush   | 
| 1413965327  | Tuesday, 10/21/2014 | K2014-18-04 | Ave L (Utica Ave to E 41 St)                      | 18 | Flatlands       | 
| 1413965327  | Tuesday, 10/21/2014 | K2014-18-01 | 2 Milling Crews Ave K (Troy Ave to Flatlands Ave) | 18 | Flatlands       | 
| 1413965327  | Tuesday, 10/21/2014 | K2014-18-17 | Ave K (Utica Ave to Flatlands Ave)                | 18 | Flatlands       | 
```