# NYC Permitted Event Information

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nyc-permitted-event-information-71bb2) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/tvpp-9vvx) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/tvpp-9vvx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/tvpp-9vvx/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | tvpp-9vvx |
| Name | NYC Permitted Event Information |
| Attribution | Office of Citywide Event Coordination and Management (CECM) |
| Category | City Government |
| Tags | event, to do, activity, park, block party, festival, nyc permitted event information, otm, office of the mayor |
| Created | 2013-11-06T18:26:59Z |
| Publication Date | 2017-06-08T19:42:07Z |

## Description

This list contains information on approved event applications that will occur within the next month. Please note that Permitted Film Events only reflect those permits which will impact one or more streets for at least five days.

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type     | Render Type   |
| ======== | =========== | =================== | =================== | ============= | ============= |
| Yes      | series tag  | event_id            | Event ID            | text          | number        |
| Yes      | series tag  | event_name          | Event Name          | text          | text          |
| Yes      | time        | start_date_time     | Start Date/Time     | calendar_date | calendar_date |
| No       |             | end_date_time       | End Date/Time       | calendar_date | calendar_date |
| Yes      | series tag  | event_agency        | Event Agency        | text          | text          |
| Yes      | series tag  | event_type          | Event Type          | text          | text          |
| Yes      | series tag  | event_borough       | Event Borough       | text          | text          |
| Yes      | series tag  | event_location      | Event Location      | text          | text          |
| Yes      | series tag  | event_street_side   | Event Street Side   | text          | text          |
| Yes      | series tag  | street_closure_type | Street Closure Type | text          | text          |
| Yes      | series tag  | community_board     | Community Board     | text          | text          |
| Yes      | series tag  | police_precinct     | Police Precinct     | text          | text          |
```

## Time Field

```ls
Value = start_date_time
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = end_date_time
```

## Data Commands

```ls
series e:tvpp-9vvx d:2017-06-08T10:00:00.000Z t:event_borough=Manhattan t:event_type="Special Event" t:event_agency="Parks Department" t:event_id=317055 t:event_location="Riverside Park South: Locomotive Picnic Area" t:street_closure_type=N/A t:community_board=7, t:event_name="Locomotive Lawn Live" t:police_precinct=20, m:row_number.tvpp-9vvx=1

series e:tvpp-9vvx d:2017-06-15T10:00:00.000Z t:event_borough=Manhattan t:event_type="Special Event" t:event_agency="Parks Department" t:event_id=317055 t:event_location="Riverside Park South: Locomotive Picnic Area" t:street_closure_type=N/A t:community_board=7, t:event_name="Locomotive Lawn Live" t:police_precinct=20, m:row_number.tvpp-9vvx=2

series e:tvpp-9vvx d:2017-06-22T10:00:00.000Z t:event_borough=Manhattan t:event_type="Special Event" t:event_agency="Parks Department" t:event_id=317055 t:event_location="Riverside Park South: Locomotive Picnic Area" t:street_closure_type=N/A t:community_board=7, t:event_name="Locomotive Lawn Live" t:police_precinct=20, m:row_number.tvpp-9vvx=3
```

## Meta Commands

```ls
metric m:row_number.tvpp-9vvx p:long l:"Row Number"

entity e:tvpp-9vvx l:"NYC Permitted Event Information" t:attribution="Office of Citywide Event Coordination and Management (CECM)" t:url=https://data.cityofnewyork.us/api/views/tvpp-9vvx

property e:tvpp-9vvx t:meta.view d:2017-06-09T14:00:21.238Z v:id=tvpp-9vvx v:category="City Government" v:averageRating=0 v:name="NYC Permitted Event Information" v:attribution="Office of Citywide Event Coordination and Management (CECM)"

property e:tvpp-9vvx t:meta.view.owner d:2017-06-09T14:00:21.238Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1496414226 v:displayName="NYC OpenData"

property e:tvpp-9vvx t:meta.view.tableauthor d:2017-06-09T14:00:21.238Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1496414226 v:displayName="NYC OpenData"
```

## Top Records

```ls
| event_id | event_name                                       | start_date_time     | end_date_time       | event_agency     | event_type    | event_borough | event_location                                             | event_street_side | street_closure_type | community_board | police_precinct | 
| ======== | ================================================ | =================== | =================== | ================ | ============= | ============= | ========================================================== | ================= | =================== | =============== | =============== | 
| 317055   | Locomotive Lawn Live                             | 2017-06-08T10:00:00 | 2017-06-08T11:00:00 | Parks Department | Special Event | Manhattan     | Riverside Park South: Locomotive Picnic Area               |                   | N/A                 | 7,              | 20,             | 
| 317055   | Locomotive Lawn Live                             | 2017-06-15T10:00:00 | 2017-06-15T11:00:00 | Parks Department | Special Event | Manhattan     | Riverside Park South: Locomotive Picnic Area               |                   | N/A                 | 7,              | 20,             | 
| 317055   | Locomotive Lawn Live                             | 2017-06-22T10:00:00 | 2017-06-22T11:00:00 | Parks Department | Special Event | Manhattan     | Riverside Park South: Locomotive Picnic Area               |                   | N/A                 | 7,              | 20,             | 
| 317055   | Locomotive Lawn Live                             | 2017-06-29T10:00:00 | 2017-06-29T11:00:00 | Parks Department | Special Event | Manhattan     | Riverside Park South: Locomotive Picnic Area               |                   | N/A                 | 7,              | 20,             | 
| 317060   | Harlem Dances                                    | 2017-06-16T18:00:00 | 2017-06-16T20:00:00 | Parks Department | Special Event | Manhattan     | West Harlem Piers: Marginal Street Between 125th 123rd St. |                   | N/A                 | 9,              | 26,             | 
| 317065   | Only in Queens Festival - Queens Summer Festival | 2017-06-11T13:00:00 | 2017-06-11T20:30:00 | Parks Department | Special Event | Queens        | Flushing Meadows Corona Park: Festival Site                |                   | N/A                 | 81,             | 110,            | 
| 317071   | Friday Freshen Up                                | 2017-06-30T19:00:00 | 2017-06-30T20:00:00 | Parks Department | Special Event | Manhattan     | West Harlem Piers: Marginal Street Between 125th 123rd St. |                   | N/A                 | 9,              | 26,             | 
| 317081   | Celebration                                      | 2017-06-24T11:30:00 | 2017-06-24T13:30:00 | Parks Department | Special Event | Manhattan     | Central Park: Cop Cot                                      |                   | N/A                 | 64,             | 22,             | 
| 317086   | Celebration                                      | 2017-06-24T12:00:00 | 2017-06-24T16:00:00 | Parks Department | Special Event | Manhattan     | Riverside Park: Skate Park Plaza-RSP                       |                   | N/A                 | 9,              | 24,             | 
| 317093   | B-SIDE MUSIC                                     | 2017-06-10T15:00:00 | 2017-06-10T19:00:00 | Parks Department | Special Event | Brooklyn      | Fulton Park: Plaza                                         |                   | N/A                 | 3,              | 81,             | 
```