# Street Weekly Resurfacing Schedule - Queens

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/street-weekly-resurfacing-schedule-queens-da712) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/nuxu-5fjs) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/nuxu-5fjs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/nuxu-5fjs/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | nuxu-5fjs |
| Name | Street Weekly Resurfacing Schedule - Queens |
| Attribution | Department of Transportation (DOT) |
| Category | Transportation |
| Tags | dot, street resurfacing, queens, resurfacing schedule |
| Created | 2014-10-22T16:21:19Z |
| Publication Date | 2014-10-22T16:28:30Z |

## Description

Queens Milling and Paving Schedule

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
series e:nuxu-5fjs d:2014-10-22T09:21:22.000Z t:location="No Work" m:row_number.nuxu-5fjs=1

series e:nuxu-5fjs d:2014-10-22T09:21:22.000Z t:area="Middle Village" t:location="Contractor Millings
Caldwell Ave (80 St to 74 St)" m:row_number.nuxu-5fjs=2

series e:nuxu-5fjs d:2014-10-22T09:21:22.000Z t:area="Middle Village" t:location="76 St (58 Ave to Eliot Ave)" m:row_number.nuxu-5fjs=3
```

## Meta Commands

```ls
metric m:row_number.nuxu-5fjs p:long l:"Row Number"

entity e:nuxu-5fjs l:"Street Weekly Resurfacing Schedule - Queens" t:attribution="Department of Transportation (DOT)" t:url=https://data.cityofnewyork.us/api/views/nuxu-5fjs

property e:nuxu-5fjs t:meta.view v:id=nuxu-5fjs v:category=Transportation v:attributionLink=http://a841-dotweb01.nyc.gov/datafeeds/Queens%20Milling%20Paving%20Schedule.xml v:averageRating=0 v:name="Street Weekly Resurfacing Schedule - Queens" v:attribution="Department of Transportation (DOT)"

property e:nuxu-5fjs t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:nuxu-5fjs t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | day_date            | sa          | location                                                  | cb | area           | 
| =========== | =================== | =========== | ========================================================= | == | ============== | 
| 1413969682  | Sunday, 10/19/2014  |             | No Work                                                   |    |                | 
| 1413969682  | Monday, 10/20/2014  | Q2013-05-53 | Contractor Millings Caldwell Ave (80 St to 74 St)         | 5  | Middle Village | 
| 1413969682  | Monday, 10/20/2014  | Q2013-05-46 | 76 St (58 Ave to Eliot Ave)                               | 5  | Middle Village | 
| 1413969682  | Monday, 10/20/2014  | Q2013-05-48 | 79 St (Eliot Ave to Queens Midtown Expwy)                 | 5  | Middle Village | 
| 1413969682  | Monday, 10/20/2014  | Q2013-05-51 | 57 Rd (78 St to Dead End)                                 | 5  | Middle Village | 
| 1413969682  | Monday, 10/20/2014  | Q2014-07-13 | 2 Milling Crews Pidgeon Meadow Rd (164 St to Utopia Pkwy) | 7  | Auburndale     | 
| 1413969682  | Monday, 10/20/2014  | Q2014-02-10 | 3 Paving Crews 58 St (Queens Blvd to Roosevelt Ave)       | 2  | Woodside       | 
| 1413969682  | Monday, 10/20/2014  | Q2014-01-10 | 23 Ave (Astoria Blvd to Steinway St)                      | 1  | Astoria        | 
| 1413969682  | Monday, 10/20/2014  | Q2013-04-51 | Van Horn St (Grand Ave to 57 Ave)                         | 4  | Elmhurst       | 
| 1413969682  | Tuesday, 10/21/2014 | Q2013-05-50 | Contractor Millings Queens Midtown Expwy (78 St to 80 St) | 5  | Middle Village | 
```