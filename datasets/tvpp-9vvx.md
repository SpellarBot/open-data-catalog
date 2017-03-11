# NYC Permitted Event Information

## Dataset

* [Dataset URL](https://data.cityofnewyork.us/api/views/tvpp-9vvx/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/nyc-permitted-event-information-71bb2)
* Id = tvpp-9vvx
* Name = NYC Permitted Event Information
* Attribution = Office of Citywide Event Coordination and Management (CECM)
* Category = City Government
* Tags = [event, to do, activity, park, block party, festival, nyc permitted event information, otm, office of the mayor]
* Created = 2013-11-06T18:26:59Z
* Publication Date = 2017-03-02T21:31:43Z
* Rows Updated = 2017-03-02T21:31:38Z

## Description

This list contains information on approved event applications that will occur within the next month. Please note that Permitted Film Events only reflect those permits which will impact one or more streets for at least five days.

## Columns

```ls
| Name                | Field Name          | Data Type     | Render Type   | Schema Type | Included | 
| =================== | =================== | ============= | ============= | =========== | ======== | 
| Event ID            | event_id            | text          | number        | series tag  | Yes      | 
| Event Name          | event_name          | text          | text          | series tag  | Yes      | 
| Start Date/Time     | start_date_time     | calendar_date | calendar_date | time        | Yes      | 
| End Date/Time       | end_date_time       | calendar_date | calendar_date |             | No       | 
| Event Agency        | event_agency        | text          | text          | series tag  | Yes      | 
| Event Type          | event_type          | text          | text          | series tag  | Yes      | 
| Event Borough       | event_borough       | text          | text          | series tag  | Yes      | 
| Event Location      | event_location      | text          | text          | series tag  | Yes      | 
| Event Street Side   | event_street_side   | text          | text          | series tag  | Yes      | 
| Street Closure Type | street_closure_type | text          | text          | series tag  | Yes      | 
| Community Board     | community_board     | text          | text          | series tag  | Yes      | 
| Police Precinct     | police_precinct     | text          | text          | series tag  | Yes      | 
```

## Time Field

```ls
Value = start_date_time
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = end_date_time
Annotation Fields = 
```

## Data Commands

```ls





```

## Meta Commands

```ls
entity e:tvpp-9vvx l:"NYC Permitted Event Information" t:attribution="Office of Citywide Event Coordination and Management (CECM)" t:url=https://data.cityofnewyork.us/api/views/tvpp-9vvx

property e:tvpp-9vvx t:meta.view d:2017-03-03T14:03:13.165Z v:id=tvpp-9vvx v:category="City Government" v:averageRating=0 v:name="NYC Permitted Event Information" v:attribution="Office of Citywide Event Coordination and Management (CECM)"

property e:tvpp-9vvx t:meta.view.owner d:2017-03-03T14:03:13.165Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"

property e:tvpp-9vvx t:meta.view.tableauthor d:2017-03-03T14:03:13.165Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"
```