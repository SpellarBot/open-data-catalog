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
| Publication Date | 2017-03-27T19:33:32Z |

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
series e:tvpp-9vvx d:2017-04-16T08:00:00.000Z t:event_borough=Brooklyn t:event_type="Farmers Market" t:event_agency="Street Activity Permit Office" t:event_id=314118 t:event_street_side=North t:event_location="CORTELYOU ROAD between RUGBY ROAD and ARGYLE ROAD" t:street_closure_type="Sidewalk and Curb Lane Closure" t:community_board=14, t:event_name="Cortelyou Greenmarket Sunday" t:police_precinct=70, m:row_number.tvpp-9vvx=1

series e:tvpp-9vvx d:2017-04-23T08:00:00.000Z t:event_borough=Brooklyn t:event_type="Farmers Market" t:event_agency="Street Activity Permit Office" t:event_id=314118 t:event_street_side=North t:event_location="CORTELYOU ROAD between RUGBY ROAD and ARGYLE ROAD" t:street_closure_type="Sidewalk and Curb Lane Closure" t:community_board=14, t:event_name="Cortelyou Greenmarket Sunday" t:police_precinct=70, m:row_number.tvpp-9vvx=2

series e:tvpp-9vvx d:2017-04-02T08:00:00.000Z t:event_borough=Queens t:event_type="Farmers Market" t:event_agency="Street Activity Permit Office" t:event_id=314119 t:event_street_side=South t:event_location="QUEENS BOULEVARD between 70 AVENUE and 69 ROAD" t:street_closure_type="Sidewalk and Curb Lane Closure" t:community_board=6, t:event_name="Forest Hills Greenmarket Sunday" t:police_precinct=112, m:row_number.tvpp-9vvx=3
```

## Meta Commands

```ls
metric m:row_number.tvpp-9vvx p:long l:"Row Number"

entity e:tvpp-9vvx l:"NYC Permitted Event Information" t:attribution="Office of Citywide Event Coordination and Management (CECM)" t:url=https://data.cityofnewyork.us/api/views/tvpp-9vvx

property e:tvpp-9vvx t:meta.view v:id=tvpp-9vvx v:category="City Government" v:averageRating=0 v:name="NYC Permitted Event Information" v:attribution="Office of Citywide Event Coordination and Management (CECM)"

property e:tvpp-9vvx t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:displayName="NYC OpenData"

property e:tvpp-9vvx t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"
```