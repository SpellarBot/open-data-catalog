# Street Weekly Resurfacing Schedule - Manhattan

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/street-weekly-resurfacing-schedule-manhattan-f55b7) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/9gzt-8w5q) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/9gzt-8w5q/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/9gzt-8w5q/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 9gzt-8w5q |
| Name | Street Weekly Resurfacing Schedule - Manhattan |
| Attribution | Department of Transportation (DOT) |
| Category | Transportation |
| Tags | dot, street resurfacing, manhattan, weekly schedule |
| Created | 2014-10-21T20:44:02Z |
| Publication Date | 2014-10-22T14:46:57Z |

## Description

Manhattan Milling and Paving Schedule

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
series e:9gzt-8w5q d:2014-10-21T13:44:04.000Z t:location="No Work" m:row_number.9gzt-8w5q=1

series e:9gzt-8w5q d:2014-10-21T13:44:04.000Z t:area="Upper East Side" t:location="Contractor Milling, York Ave (E 63 St ? E 79 St)" m:row_number.9gzt-8w5q=2

series e:9gzt-8w5q d:2014-10-21T13:44:04.000Z t:area=Harlem t:location="1 Paving Crew, E 105 St (2 Ave ? 5 Ave)" m:row_number.9gzt-8w5q=3
```

## Meta Commands

```ls
metric m:row_number.9gzt-8w5q p:long l:"Row Number"

entity e:9gzt-8w5q l:"Street Weekly Resurfacing Schedule - Manhattan" t:attribution="Department of Transportation (DOT)" t:url=https://data.cityofnewyork.us/api/views/9gzt-8w5q

property e:9gzt-8w5q t:meta.view v:id=9gzt-8w5q v:category=Transportation v:attributionLink=http://a841-dotweb01.nyc.gov/datafeeds/Manhattan%20Milling%20&%20Paving%20Schedule.xml v:averageRating=0 v:name="Street Weekly Resurfacing Schedule - Manhattan" v:attribution="Department of Transportation (DOT)"

property e:9gzt-8w5q t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:9gzt-8w5q t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | day_date              | sa          | location                                              | cb | area            | 
| =========== | ===================== | =========== | ===================================================== | == | =============== | 
| 1413899044  | Sunday, 10/19/2014    |             | No Work                                               |    |                 | 
| 1413899044  | Monday, 10/20/2014    | M2014-08-03 | Contractor Milling, York Ave (E 63 St ? E 79 St)      | 8  | Upper East Side | 
| 1413899044  | Monday, 10/20/2014    | M2014-11-04 | 1 Paving Crew, E 105 St (2 Ave ? 5 Ave)               | 11 | Harlem          | 
| 1413899044  | Tuesday, 10/21/2014   | M2014-08-03 | Contractor Milling, York Ave (E 63 St ? E 79 St)      | 8  | Upper East Side | 
| 1413899044  | Tuesday, 10/21/2014   | M2014-11-04 | 1 Paving Crew, E 105 St (2 Ave ? 5 Ave)               | 11 | Harlem          | 
| 1413899044  | Wednesday, 10/22/2014 | M2014-08-03 | Contractor Milling, York Ave (E 63 St ? E 79 St)      | 8  | Upper East Side | 
| 1413899044  | Wednesday, 10/22/2014 | M2014-11-05 | 1 Paving Crew, Madison Ave (E 125 St ? E 135 St)      | 11 | Harlem          | 
| 1413899044  | Thursday, 10/23/2014  | M2014-08-06 | Contractor Milling, E 80 ST (5 Ave ? Dead End)        | 8  | Upper East Side | 
| 1413899044  | Thursday, 10/23/2014  | M2014-11-05 | 1 Paving Crew, Madison Ave (E 125 St ? E 135 St)      | 11 | Harlem          | 
| 1413899044  | Friday, 10/24/2014    | M2014-06-10 | Contractor Milling, Lexington Ave (E 48 St ? E 42 St) | 6  | Midtown         | 
```