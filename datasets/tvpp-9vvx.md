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
| Publication Date | 2017-04-17T19:32:44Z |

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
series e:tvpp-9vvx d:2017-04-30T08:00:00.000Z t:event_borough=Manhattan t:event_type="Farmers Market" t:event_agency="Street Activity Permit Office" t:event_id=314114 t:event_street_side=East t:event_location="BROADWAY between WEST  114 STREET and WEST  116 STREET" t:street_closure_type="Sidewalk and Curb Lane Closure" t:community_board=9, t:event_name="Columbia Greenmarket Sunday" t:police_precinct=26, m:row_number.tvpp-9vvx=1

series e:tvpp-9vvx d:2017-05-07T08:00:00.000Z t:event_borough=Manhattan t:event_type="Farmers Market" t:event_agency="Street Activity Permit Office" t:event_id=314114 t:event_street_side=East t:event_location="BROADWAY between WEST  114 STREET and WEST  116 STREET" t:street_closure_type="Sidewalk and Curb Lane Closure" t:community_board=9, t:event_name="Columbia Greenmarket Sunday" t:police_precinct=26, m:row_number.tvpp-9vvx=2

series e:tvpp-9vvx d:2017-05-14T08:00:00.000Z t:event_borough=Manhattan t:event_type="Farmers Market" t:event_agency="Street Activity Permit Office" t:event_id=314114 t:event_street_side=East t:event_location="BROADWAY between WEST  114 STREET and WEST  116 STREET" t:street_closure_type="Sidewalk and Curb Lane Closure" t:community_board=9, t:event_name="Columbia Greenmarket Sunday" t:police_precinct=26, m:row_number.tvpp-9vvx=3
```

## Meta Commands

```ls
metric m:row_number.tvpp-9vvx p:long l:"Row Number"

entity e:tvpp-9vvx l:"NYC Permitted Event Information" t:attribution="Office of Citywide Event Coordination and Management (CECM)" t:url=https://data.cityofnewyork.us/api/views/tvpp-9vvx

property e:tvpp-9vvx t:meta.view v:id=tvpp-9vvx v:category="City Government" v:averageRating=0 v:name="NYC Permitted Event Information" v:attribution="Office of Citywide Event Coordination and Management (CECM)"

property e:tvpp-9vvx t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:tvpp-9vvx t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| event_id | event_name                      | start_date_time     | end_date_time       | event_agency                  | event_type     | event_borough | event_location                                       | event_street_side | street_closure_type            | community_board | police_precinct | 
| ======== | =============================== | =================== | =================== | ============================= | ============== | ============= | ==================================================== | ================= | ============================== | =============== | =============== | 
| 314114   | Columbia Greenmarket Sunday     | 2017-04-30T08:00:00 | 2017-04-30T05:00:00 | Street Activity Permit Office | Farmers Market | Manhattan     | BROADWAY between WEST 114 STREET and WEST 116 STREET | East              | Sidewalk and Curb Lane Closure | 9,              | 26,             | 
| 314114   | Columbia Greenmarket Sunday     | 2017-05-07T08:00:00 | 2017-05-07T05:00:00 | Street Activity Permit Office | Farmers Market | Manhattan     | BROADWAY between WEST 114 STREET and WEST 116 STREET | East              | Sidewalk and Curb Lane Closure | 9,              | 26,             | 
| 314114   | Columbia Greenmarket Sunday     | 2017-05-14T08:00:00 | 2017-05-14T05:00:00 | Street Activity Permit Office | Farmers Market | Manhattan     | BROADWAY between WEST 114 STREET and WEST 116 STREET | East              | Sidewalk and Curb Lane Closure | 9,              | 26,             | 
| 314118   | Cortelyou Greenmarket Sunday    | 2017-04-23T08:00:00 | 2017-04-23T17:00:00 | Street Activity Permit Office | Farmers Market | Brooklyn      | CORTELYOU ROAD between RUGBY ROAD and ARGYLE ROAD    | North             | Sidewalk and Curb Lane Closure | 14,             | 70,             | 
| 314118   | Cortelyou Greenmarket Sunday    | 2017-04-30T08:00:00 | 2017-04-30T17:00:00 | Street Activity Permit Office | Farmers Market | Brooklyn      | CORTELYOU ROAD between RUGBY ROAD and ARGYLE ROAD    | North             | Sidewalk and Curb Lane Closure | 14,             | 70,             | 
| 314118   | Cortelyou Greenmarket Sunday    | 2017-05-07T08:00:00 | 2017-05-07T17:00:00 | Street Activity Permit Office | Farmers Market | Brooklyn      | CORTELYOU ROAD between RUGBY ROAD and ARGYLE ROAD    | North             | Sidewalk and Curb Lane Closure | 14,             | 70,             | 
| 314118   | Cortelyou Greenmarket Sunday    | 2017-05-14T08:00:00 | 2017-05-14T17:00:00 | Street Activity Permit Office | Farmers Market | Brooklyn      | CORTELYOU ROAD between RUGBY ROAD and ARGYLE ROAD    | North             | Sidewalk and Curb Lane Closure | 14,             | 70,             | 
| 314119   | Forest Hills Greenmarket Sunday | 2017-04-23T08:00:00 | 2017-04-23T17:00:00 | Street Activity Permit Office | Farmers Market | Queens        | QUEENS BOULEVARD between 70 AVENUE and 69 ROAD       | South             | Sidewalk and Curb Lane Closure | 6,              | 112,            | 
| 314119   | Forest Hills Greenmarket Sunday | 2017-04-30T08:00:00 | 2017-04-30T17:00:00 | Street Activity Permit Office | Farmers Market | Queens        | QUEENS BOULEVARD between 70 AVENUE and 69 ROAD       | South             | Sidewalk and Curb Lane Closure | 6,              | 112,            | 
| 314119   | Forest Hills Greenmarket Sunday | 2017-05-07T08:00:00 | 2017-05-07T17:00:00 | Street Activity Permit Office | Farmers Market | Queens        | QUEENS BOULEVARD between 70 AVENUE and 69 ROAD       | South             | Sidewalk and Curb Lane Closure | 6,              | 112,            | 
```