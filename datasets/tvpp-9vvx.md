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
| Publication Date | 2017-09-24T20:32:02Z |

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
series e:tvpp-9vvx d:2017-10-14T00:00:00.000Z t:event_agency="Parks Department" t:event_borough=Manhattan t:event_id=317411 t:event_type="Special Event" t:police_precinct="20, 24," t:event_location="Riverside Park: Promenade Lower - 79th-95th Streets ,Riverside Park: Promenade 100th-110th Street-RSP" t:community_board="7, 9," t:event_name="CaringKind Alzheimer's Walk" t:street_closure_type=N/A m:row_number.tvpp-9vvx=1

series e:tvpp-9vvx d:2017-10-15T00:00:00.000Z t:event_agency="Parks Department" t:event_borough=Manhattan t:event_id=317411 t:event_type="Special Event" t:police_precinct="20, 24," t:event_location="Riverside Park: Promenade Lower - 79th-95th Streets ,Riverside Park: Promenade 100th-110th Street-RSP" t:community_board="7, 9," t:event_name="CaringKind Alzheimer's Walk" t:street_closure_type=N/A m:row_number.tvpp-9vvx=2

series e:tvpp-9vvx d:2017-09-28T18:00:00.000Z t:event_agency="Parks Department" t:event_borough=Manhattan t:event_id=317494 t:event_type="Special Event" t:police_precinct=5, t:event_location="Thomas Paine Park (Foley Square): Thomas Paine Park (Foley Square)" t:community_board=1, t:event_name="The Lesbian and Gay Big Apple Corps Rehearsal" t:street_closure_type=N/A m:row_number.tvpp-9vvx=3
```

## Meta Commands

```ls
metric m:row_number.tvpp-9vvx p:long l:"Row Number"

entity e:tvpp-9vvx l:"NYC Permitted Event Information" t:attribution="Office of Citywide Event Coordination and Management (CECM)" t:url=https://data.cityofnewyork.us/api/views/tvpp-9vvx

property e:tvpp-9vvx t:meta.view d:2017-09-25T07:31:39.192Z v:averageRating=0 v:name="NYC Permitted Event Information" v:attribution="Office of Citywide Event Coordination and Management (CECM)" v:id=tvpp-9vvx v:category="City Government"

property e:tvpp-9vvx t:meta.view.owner d:2017-09-25T07:31:39.192Z v:displayName="NYC OpenData" v:lastNotificationSeenAt=1496414226 v:id=5fuc-pqz2 v:screenName="NYC OpenData"

property e:tvpp-9vvx t:meta.view.tableauthor d:2017-09-25T07:31:39.192Z v:displayName="NYC OpenData" v:lastNotificationSeenAt=1496414226 v:roleName=administrator v:id=5fuc-pqz2 v:screenName="NYC OpenData"
```

## Top Records

```ls
| event_id | event_name                                    | start_date_time     | end_date_time       | event_agency     | event_type    | event_borough | event_location                                                                                        | event_street_side | street_closure_type | community_board | police_precinct | 
| ======== | ============================================= | =================== | =================== | ================ | ============= | ============= | ===================================================================================================== | ================= | =================== | =============== | =============== | 
| 317411   | CaringKind Alzheimer's Walk                   | 2017-10-14T00:00:00 | 2017-10-14T23:59:00 | Parks Department | Special Event | Manhattan     | Riverside Park: Promenade Lower - 79th-95th Streets ,Riverside Park: Promenade 100th-110th Street-RSP |                   | N/A                 | 7, 9,           | 20, 24,         | 
| 317411   | CaringKind Alzheimer's Walk                   | 2017-10-15T00:00:00 | 2017-10-15T23:59:00 | Parks Department | Special Event | Manhattan     | Riverside Park: Promenade Lower - 79th-95th Streets ,Riverside Park: Promenade 100th-110th Street-RSP |                   | N/A                 | 7, 9,           | 20, 24,         | 
| 317494   | The Lesbian and Gay Big Apple Corps Rehearsal | 2017-09-28T18:00:00 | 2017-09-28T22:00:00 | Parks Department | Special Event | Manhattan     | Thomas Paine Park (Foley Square): Thomas Paine Park (Foley Square)                                    |                   | N/A                 | 1,              | 5,              | 
| 317499   | (2017) Green Market (Jan - Dec)               | 2017-09-25T08:00:00 | 2017-09-25T20:00:00 | Parks Department | Special Event | Manhattan     | Union Square Park: North Plaza                                                                        |                   | N/A                 | 5,              | 13,             | 
| 317499   | (2017) Green Market (Jan - Dec)               | 2017-09-27T08:00:00 | 2017-09-27T20:00:00 | Parks Department | Special Event | Manhattan     | Union Square Park: North Plaza                                                                        |                   | N/A                 | 5,              | 13,             | 
| 317499   | (2017) Green Market (Jan - Dec)               | 2017-09-29T08:00:00 | 2017-09-29T20:00:00 | Parks Department | Special Event | Manhattan     | Union Square Park: North Plaza                                                                        |                   | N/A                 | 5,              | 13,             | 
| 317499   | (2017) Green Market (Jan - Dec)               | 2017-09-30T08:00:00 | 2017-09-30T20:00:00 | Parks Department | Special Event | Manhattan     | Union Square Park: North Plaza                                                                        |                   | N/A                 | 5,              | 13,             | 
| 317499   | (2017) Green Market (Jan - Dec)               | 2017-10-02T08:00:00 | 2017-10-02T20:00:00 | Parks Department | Special Event | Manhattan     | Union Square Park: North Plaza                                                                        |                   | N/A                 | 5,              | 13,             | 
| 317499   | (2017) Green Market (Jan - Dec)               | 2017-10-04T08:00:00 | 2017-10-04T20:00:00 | Parks Department | Special Event | Manhattan     | Union Square Park: North Plaza                                                                        |                   | N/A                 | 5,              | 13,             | 
| 317499   | (2017) Green Market (Jan - Dec)               | 2017-10-06T08:00:00 | 2017-10-06T20:00:00 | Parks Department | Special Event | Manhattan     | Union Square Park: North Plaza                                                                        |                   | N/A                 | 5,              | 13,             | 
```