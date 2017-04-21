# DSNY Graffiti Information

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dsny-graffiti-information-549b7) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/gpwd-npar) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/gpwd-npar/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/gpwd-npar/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | gpwd-npar |
| Name | DSNY Graffiti Information |
| Attribution | Department of Sanitation (DSNY) |
| Category | City Government |
| Tags | dsny graffiti information, dsny |
| Created | 2013-11-22T16:33:37Z |
| Publication Date | 2017-04-08T18:37:12Z |

## Columns

```ls
| Included | Schema Type | Field Name            | Name                  | Data Type     | Render Type   |
| ======== | =========== | ===================== | ===================== | ============= | ============= |
| No       |             | incident_address      | INCIDENT_ADDRESS      | text          | text          |
| Yes      | series tag  | borough               | BOROUGH               | text          | text          |
| Yes      | series tag  | community_board       | COMMUNITY_BOARD       | text          | text          |
| Yes      | series tag  | police_precinct       | POLICE_PRECINCT       | text          | text          |
| Yes      | series tag  | city_council_district | CITY_COUNCIL_DISTRICT | text          | text          |
| Yes      | series tag  | bbl                   | BBL                   | text          | text          |
| Yes      | time        | created_date          | CREATED_DATE          | calendar_date | calendar_date |
| Yes      | series tag  | status                | STATUS                | text          | text          |
| Yes      | series tag  | resolution_action     | RESOLUTION_ACTION     | text          | text          |
| No       |             | closed_date           | CLOSED_DATE           | calendar_date | calendar_date |
| No       |             | x_coordinate          | X_COORDINATE          | number        | text          |
| No       |             | y_coordinate          | Y_COORDINATE          | number        | text          |
```

## Time Field

```ls
Value = created_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = incident_address,closed_date,x_coordinate,y_coordinate
```

## Data Commands

```ls
series e:gpwd-npar d:2016-06-03T00:00:00.000Z t:bbl=3017160018 t:city_council_district=33 t:resolution_action="Cleaning crew dispatched.  Property cleaned." t:status=Closed t:borough=BROOKLYN t:community_board="03 BROOKLYN" t:police_precinct="Precinct 79" m:row_number.gpwd-npar=1

series e:gpwd-npar d:2016-11-27T00:00:00.000Z t:bbl=4101010027 t:city_council_district=27 t:resolution_action="Cleaning crew dispatched.  Property cleaned." t:status=Closed t:borough=QUEENS t:community_board="12 QUEENS" t:police_precinct="Precinct 103" m:row_number.gpwd-npar=2

series e:gpwd-npar d:2016-12-06T00:00:00.000Z t:bbl=3031880056 t:city_council_district=34 t:resolution_action="Cleaning crew dispatched.  Property cleaned." t:status=Closed t:borough=BROOKLYN t:community_board="04 BROOKLYN" t:police_precinct="Precinct 83" m:row_number.gpwd-npar=3
```

## Meta Commands

```ls
metric m:row_number.gpwd-npar p:long l:"Row Number"

entity e:gpwd-npar l:"DSNY Graffiti Information" t:attribution="Department of Sanitation (DSNY)" t:url=https://data.cityofnewyork.us/api/views/gpwd-npar

property e:gpwd-npar t:meta.view v:id=gpwd-npar v:category="City Government" v:averageRating=0 v:name="DSNY Graffiti Information" v:attribution="Department of Sanitation (DSNY)"

property e:gpwd-npar t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:gpwd-npar t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| incident_address        | borough   | community_board | police_precinct | city_council_district | bbl        | created_date        | status | resolution_action                                  | closed_date         | x_coordinate | y_coordinate | 
| ======================= | ========= | =============== | =============== | ===================== | ========== | =================== | ====== | ================================================== | =================== | ============ | ============ | 
| 17 SPENCER STREET       | BROOKLYN  | 03 BROOKLYN     | Precinct 79     | 33                    | 3017160018 | 2016-06-03T00:00:00 | Closed | Cleaning crew dispatched. Property cleaned.        | 2016-09-19T00:00:00 | 996473       | 193713       | 
| 92-32 UNION HALL STREET | QUEENS    | 12 QUEENS       | Precinct 103    | 27                    | 4101010027 | 2016-11-27T00:00:00 | Closed | Cleaning crew dispatched. Property cleaned.        | 2017-02-28T00:00:00 | 1040354      | 195744       | 
| 207 STARR STREET        | BROOKLYN  | 04 BROOKLYN     | Precinct 83     | 34                    | 3031880056 | 2016-12-06T00:00:00 | Closed | Cleaning crew dispatched. Property cleaned.        | 2017-02-22T00:00:00 | 1005533      | 196143       | 
| 227 MADISON STREET      | MANHATTAN | 03 MANHATTAN    | Precinct 7      | 01                    | 1002700032 | 2016-10-19T00:00:00 | Closed | Cleaning crew dispatched. Property cleaned.        | 2017-01-27T00:00:00 | 987461       | 198963       | 
| 6 WEST 125 STREET       | MANHATTAN | 10 MANHATTAN    | Precinct 28     | 09                    | 1017220040 | 2016-10-18T00:00:00 | Closed | Cleaning crew dispatched. No graffiti on property. | 2017-01-26T00:00:00 | 1000138      | 233131       | 
| 373 5 AVENUE            | MANHATTAN | 05 MANHATTAN    | Unspecified     | 04                    | 1008650001 | 2016-07-03T00:00:00 | Closed | Cleaning crew dispatched. No graffiti on property. | 2017-01-25T00:00:00 | 988683       | 212228       | 
| 1355 AMSTERDAM AVENUE   | MANHATTAN | 09 MANHATTAN    | Precinct 26     | 07                    | 1019660107 | 2016-08-10T00:00:00 | Closed | Cleaning crew dispatched. No graffiti on property. | 2016-12-14T00:00:00 | 996480       | 235833       | 
| 36-51 MAIN STREET       | QUEENS    | 07 QUEENS       | Precinct 109    | 20                    | 4049770006 | 2016-09-12T00:00:00 | Closed | Cleaning crew dispatched. Property cleaned.        | 2016-12-07T00:00:00 | 1030932      | 217006       | 
| 1267 UTICA AVENUE       | BROOKLYN  | 17 BROOKLYN     | Precinct 67     | 45                    | 3047810074 | 2016-08-31T00:00:00 | Closed | Cleaning crew dispatched. Property cleaned.        | 2016-12-02T00:00:00 | 1003879      | 172987       | 
| 5601 AVENUE L           | BROOKLYN  | 18 BROOKLYN     | Precinct 63     | 46                    | 3078360008 | 2016-08-07T00:00:00 | Closed | Cleaning crew dispatched. Property cleaned.        | 2016-11-23T00:00:00 | 1006055      | 166603       | 
```