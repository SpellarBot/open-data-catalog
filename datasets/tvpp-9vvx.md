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
| Publication Date | 2017-04-02T19:42:48Z |

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
series e:tvpp-9vvx d:2016-05-14T10:00:00.000Z t:event_borough=Manhattan t:event_type="Public Program / Exhibitions" t:event_agency="Trust for Governor's Island" t:event_id=248006 t:street_closure_type=N/A t:community_board=N/A t:event_name=play:ground t:police_precinct=N/A m:row_number.tvpp-9vvx=1

series e:tvpp-9vvx d:2017-04-22T17:00:00.000Z t:event_borough=Manhattan t:event_type="Special Event" t:event_agency="Hudson River Park Trust" t:event_id=290714 t:event_location="HRPT Piers: Pier 46" t:street_closure_type=N/A t:community_board=2, t:event_name="Claypoole - Scuro Wedding" t:police_precinct=6, m:row_number.tvpp-9vvx=2

series e:tvpp-9vvx d:2017-04-14T13:00:00.000Z t:event_borough=Bronx t:event_type=Parade t:event_agency="Police Department" t:event_id=305458 t:event_street_side=West t:event_location="GRAND CONCOURSE between BEDFORD PARK BOULEVARD and EAST  204 STREET,  GRAND CONCOURSE between BEDFORD PARK BOULEVARD and EAST  204 STREET,  GRAND CONCOURSE between BEDFORD PARK BOULEVARD and EAST  204 STREET" t:street_closure_type="Full Street Closure" t:community_board=7, t:event_name="Good Friday Procession" t:police_precinct=52, m:row_number.tvpp-9vvx=3
```

## Meta Commands

```ls
metric m:row_number.tvpp-9vvx p:long l:"Row Number"

entity e:tvpp-9vvx l:"NYC Permitted Event Information" t:attribution="Office of Citywide Event Coordination and Management (CECM)" t:url=https://data.cityofnewyork.us/api/views/tvpp-9vvx

property e:tvpp-9vvx t:meta.view v:id=tvpp-9vvx v:category="City Government" v:averageRating=0 v:name="NYC Permitted Event Information" v:attribution="Office of Citywide Event Coordination and Management (CECM)"

property e:tvpp-9vvx t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:displayName="NYC OpenData"

property e:tvpp-9vvx t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"
```

## Top Records

```ls
| event_id | event_name                | start_date_time     | end_date_time       | event_agency                | event_type                   | event_borough | event_location                                                                                                                                                                                             | event_street_side | street_closure_type | community_board | police_precinct | 
| ======== | ========================= | =================== | =================== | =========================== | ============================ | ============= | ========================================================================================================================================================================================================== | ================= | =================== | =============== | =============== | 
| 248006   | play:ground               | 2016-05-14T10:00:00 | 2020-09-27T17:00:00 | Trust for Governor's Island | Public Program / Exhibitions | Manhattan     |                                                                                                                                                                                                            |                   | N/A                 | N/A             | N/A             | 
| 290714   | Claypoole - Scuro Wedding | 2017-04-22T17:00:00 | 2017-04-22T17:30:00 | Hudson River Park Trust     | Special Event                | Manhattan     | HRPT Piers: Pier 46                                                                                                                                                                                        |                   | N/A                 | 2,              | 6,              | 
| 305458   | Good Friday Procession    | 2017-04-14T13:00:00 | 2017-04-14T15:00:00 | Police Department           | Parade                       | Bronx         | GRAND CONCOURSE between BEDFORD PARK BOULEVARD and EAST 204 STREET, GRAND CONCOURSE between BEDFORD PARK BOULEVARD and EAST 204 STREET, GRAND CONCOURSE between BEDFORD PARK BOULEVARD and EAST 204 STREET | West              | Full Street Closure | 7,              | 52,             | 
| 309497   | Lawn Closure              | 2017-04-02T01:00:00 | 2017-04-02T23:00:00 | Parks Department            | Construction                 | Manhattan     | J. Hood Wright Park: Center Lawn                                                                                                                                                                           |                   | N/A                 | 12,             | 33,             | 
| 309497   | Lawn Closure              | 2017-04-03T01:00:00 | 2017-04-03T23:00:00 | Parks Department            | Construction                 | Manhattan     | J. Hood Wright Park: Center Lawn                                                                                                                                                                           |                   | N/A                 | 12,             | 33,             | 
| 309497   | Lawn Closure              | 2017-04-04T01:00:00 | 2017-04-04T23:00:00 | Parks Department            | Construction                 | Manhattan     | J. Hood Wright Park: Center Lawn                                                                                                                                                                           |                   | N/A                 | 12,             | 33,             | 
| 309497   | Lawn Closure              | 2017-04-05T01:00:00 | 2017-04-05T23:00:00 | Parks Department            | Construction                 | Manhattan     | J. Hood Wright Park: Center Lawn                                                                                                                                                                           |                   | N/A                 | 12,             | 33,             | 
| 309497   | Lawn Closure              | 2017-04-06T01:00:00 | 2017-04-06T23:00:00 | Parks Department            | Construction                 | Manhattan     | J. Hood Wright Park: Center Lawn                                                                                                                                                                           |                   | N/A                 | 12,             | 33,             | 
| 309497   | Lawn Closure              | 2017-04-07T01:00:00 | 2017-04-07T23:00:00 | Parks Department            | Construction                 | Manhattan     | J. Hood Wright Park: Center Lawn                                                                                                                                                                           |                   | N/A                 | 12,             | 33,             | 
| 309497   | Lawn Closure              | 2017-04-08T01:00:00 | 2017-04-08T23:00:00 | Parks Department            | Construction                 | Manhattan     | J. Hood Wright Park: Center Lawn                                                                                                                                                                           |                   | N/A                 | 12,             | 33,             | 
```