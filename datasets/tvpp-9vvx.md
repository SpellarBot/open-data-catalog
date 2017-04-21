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
| Publication Date | 2017-04-20T19:25:31Z |

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
series e:tvpp-9vvx d:2017-05-20T08:00:00.000Z t:event_borough=Manhattan t:event_type="Special Event" t:event_agency="Parks Department" t:event_id=317499 t:event_location="Union Square Park: North Plaza" t:street_closure_type=N/A t:community_board=5, t:event_name="(2017) Green Market (Jan - Dec)" t:police_precinct=13, m:row_number.tvpp-9vvx=1

series e:tvpp-9vvx d:2017-04-20T08:00:00.000Z t:event_borough=Manhattan t:event_type="Special Event" t:event_agency="Parks Department" t:event_id=317527 t:event_location="Union Square Park: Gandhi Statue ,Union Square Park: South Plaza ,Union Square Park: North Plaza" t:street_closure_type=N/A t:community_board=5, t:event_name="(2017) NO AMPLIFIED SOUND" t:police_precinct=13, m:row_number.tvpp-9vvx=2

series e:tvpp-9vvx d:2017-04-21T08:00:00.000Z t:event_borough=Manhattan t:event_type="Special Event" t:event_agency="Parks Department" t:event_id=317527 t:event_location="Union Square Park: Gandhi Statue ,Union Square Park: South Plaza ,Union Square Park: North Plaza" t:street_closure_type=N/A t:community_board=5, t:event_name="(2017) NO AMPLIFIED SOUND" t:police_precinct=13, m:row_number.tvpp-9vvx=3
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
| event_id | event_name                      | start_date_time     | end_date_time       | event_agency     | event_type    | event_borough | event_location                                                                                   | event_street_side | street_closure_type | community_board | police_precinct | 
| ======== | =============================== | =================== | =================== | ================ | ============= | ============= | ================================================================================================ | ================= | =================== | =============== | =============== | 
| 317499   | (2017) Green Market (Jan - Dec) | 2017-05-20T08:00:00 | 2017-05-20T20:00:00 | Parks Department | Special Event | Manhattan     | Union Square Park: North Plaza                                                                   |                   | N/A                 | 5,              | 13,             | 
| 317527   | (2017) NO AMPLIFIED SOUND       | 2017-04-20T08:00:00 | 2017-04-20T20:00:00 | Parks Department | Special Event | Manhattan     | Union Square Park: Gandhi Statue ,Union Square Park: South Plaza ,Union Square Park: North Plaza |                   | N/A                 | 5,              | 13,             | 
| 317527   | (2017) NO AMPLIFIED SOUND       | 2017-04-21T08:00:00 | 2017-04-21T20:00:00 | Parks Department | Special Event | Manhattan     | Union Square Park: Gandhi Statue ,Union Square Park: South Plaza ,Union Square Park: North Plaza |                   | N/A                 | 5,              | 13,             | 
| 317527   | (2017) NO AMPLIFIED SOUND       | 2017-04-22T08:00:00 | 2017-04-22T20:00:00 | Parks Department | Special Event | Manhattan     | Union Square Park: Gandhi Statue ,Union Square Park: South Plaza ,Union Square Park: North Plaza |                   | N/A                 | 5,              | 13,             | 
| 317527   | (2017) NO AMPLIFIED SOUND       | 2017-04-23T08:00:00 | 2017-04-23T20:00:00 | Parks Department | Special Event | Manhattan     | Union Square Park: Gandhi Statue ,Union Square Park: South Plaza ,Union Square Park: North Plaza |                   | N/A                 | 5,              | 13,             | 
| 317527   | (2017) NO AMPLIFIED SOUND       | 2017-04-24T08:00:00 | 2017-04-24T20:00:00 | Parks Department | Special Event | Manhattan     | Union Square Park: Gandhi Statue ,Union Square Park: South Plaza ,Union Square Park: North Plaza |                   | N/A                 | 5,              | 13,             | 
| 317527   | (2017) NO AMPLIFIED SOUND       | 2017-04-25T08:00:00 | 2017-04-25T20:00:00 | Parks Department | Special Event | Manhattan     | Union Square Park: Gandhi Statue ,Union Square Park: South Plaza ,Union Square Park: North Plaza |                   | N/A                 | 5,              | 13,             | 
| 317527   | (2017) NO AMPLIFIED SOUND       | 2017-04-26T08:00:00 | 2017-04-26T20:00:00 | Parks Department | Special Event | Manhattan     | Union Square Park: Gandhi Statue ,Union Square Park: South Plaza ,Union Square Park: North Plaza |                   | N/A                 | 5,              | 13,             | 
| 317527   | (2017) NO AMPLIFIED SOUND       | 2017-04-27T08:00:00 | 2017-04-27T20:00:00 | Parks Department | Special Event | Manhattan     | Union Square Park: Gandhi Statue ,Union Square Park: South Plaza ,Union Square Park: North Plaza |                   | N/A                 | 5,              | 13,             | 
| 317527   | (2017) NO AMPLIFIED SOUND       | 2017-04-28T08:00:00 | 2017-04-28T20:00:00 | Parks Department | Special Event | Manhattan     | Union Square Park: Gandhi Statue ,Union Square Park: South Plaza ,Union Square Park: North Plaza |                   | N/A                 | 5,              | 13,             | 
```