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
| Publication Date | 2017-03-15T20:26:54Z |
| Rows Updated | 2017-03-15T20:26:51Z |

## Description

This list contains information on approved event applications that will occur within the next month. Please note that Permitted Film Events only reflect those permits which will impact one or more streets for at least five days.

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type     | Render Type   |
| ======== | =========== | =================== | =================== | ============= | ============= |
| No       | time        | :updated_at         | updated_at          | meta_data     | meta_data     |
| Yes      | series tag  | event_id            | Event ID            | text          | number        |
| Yes      | series tag  | event_name          | Event Name          | text          | text          |
| No       |             | start_date_time     | Start Date/Time     | calendar_date | calendar_date |
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
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = start_date_time,end_date_time
```

## Data Commands

```ls
series e:tvpp-9vvx d:2017-03-15T20:26:42.000Z t:event_borough=Manhattan t:event_type="Public Program / Exhibitions" t:event_agency="Trust for Governor's Island" t:event_id=248006 t:street_closure_type=N/A t:community_board=N/A t:event_name=play:ground t:police_precinct=N/A m:row_number.tvpp-9vvx=1

series e:tvpp-9vvx d:2017-03-15T20:26:42.000Z t:event_borough=Manhattan t:event_type=Parade t:event_agency="Police Department" t:event_id=282369 t:event_street_side=Full t:event_location="LAFAYETTE STREET between READE STREET and DUANE STREET,  READE STREET between CENTRE STREET and BROADWAY,  BROADWAY between READE STREET and BEAVER STREET,  STONE STREET between BROADWAY and BROAD STREET, Thomas Paine Park (Foley Square): Thomas Paine Park (Foley Square)" t:street_closure_type="Full Street Closure" t:community_board=1, t:event_name="Gift of Life Walk" t:police_precinct="1, 5," m:row_number.tvpp-9vvx=2

series e:tvpp-9vvx d:2017-03-15T20:26:42.000Z t:event_borough=Bronx t:event_type=Parade t:event_agency="Police Department" t:event_id=305458 t:event_street_side=West t:event_location="GRAND CONCOURSE between BEDFORD PARK BOULEVARD and EAST  204 STREET,  GRAND CONCOURSE between BEDFORD PARK BOULEVARD and EAST  204 STREET,  GRAND CONCOURSE between BEDFORD PARK BOULEVARD and EAST  204 STREET" t:street_closure_type="Full Street Closure" t:community_board=7, t:event_name="Good Friday Procession" t:police_precinct=52, m:row_number.tvpp-9vvx=3
```

## Meta Commands

```ls
metric m:row_number.tvpp-9vvx p:long l:"Row Number"

entity e:tvpp-9vvx l:"NYC Permitted Event Information" t:attribution="Office of Citywide Event Coordination and Management (CECM)" t:url=https://data.cityofnewyork.us/api/views/tvpp-9vvx

property e:tvpp-9vvx t:meta.view v:id=tvpp-9vvx v:category="City Government" v:averageRating=0 v:name="NYC Permitted Event Information" v:attribution="Office of Citywide Event Coordination and Management (CECM)"

property e:tvpp-9vvx t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"

property e:tvpp-9vvx t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"
```