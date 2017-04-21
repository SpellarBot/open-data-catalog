# Police Department Calls for Service

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/police-calls-for-service) |
| Metadata | [Link](https://data.sfgov.org/api/views/hz9m-tj6z) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/hz9m-tj6z/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/hz9m-tj6z/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | hz9m-tj6z |
| Name | Police Department Calls for Service |
| Attribution | City and County of San Francisco |
| Category | Public Safety |
| Tags | crime, 911 |
| Created | 2016-01-11T21:50:28Z |
| Publication Date | 2016-07-18T17:18:22Z |

## Description

Calls for service regarding criminal activity (unverified), from SFPD. Data covers the period 03/31/2016-present.

## Columns

```ls
| Included | Schema Type | Field Name              | Name                     | Data Type     | Render Type   |
| ======== | =========== | ======================= | ======================== | ============= | ============= |
| Yes      | series tag  | crime_id                | Crime Id                 | text          | number        |
| Yes      | series tag  | original_crimetype_name | Original Crime Type Name | text          | text          |
| Yes      | time        | report_date             | Report Date              | calendar_date | calendar_date |
| No       |             | call_date               | Call Date                | calendar_date | calendar_date |
| No       |             | offense_date            | Offense Date             | calendar_date | calendar_date |
| No       |             | call_time               | Call Time                | text          | text          |
| No       |             | call_dttm               | Call Date Time           | calendar_date | calendar_date |
| Yes      | series tag  | disposition             | Disposition              | text          | text          |
| No       |             | address                 | Address                  | text          | text          |
| Yes      | series tag  | city                    | City                     | text          | text          |
| Yes      | series tag  | state                   | State                    | text          | text          |
| Yes      | series tag  | agency_id               | Agency Id                | text          | number        |
| No       |             | address_type            | Address Type             | text          | text          |
| Yes      | series tag  | common_location         | Common Location          | text          | text          |
```

## Time Field

```ls
Value = report_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = call_date,offense_date,call_time,call_dttm,address,address_type
```

## Data Commands

```ls
series e:hz9m-tj6z d:2016-03-31T00:00:00.000Z t:agency_id=1 t:crime_id=160913285 t:original_crimetype_name="Arrest Made" t:state=CA t:disposition=ARR t:city="San Francisco" m:row_number.hz9m-tj6z=1

series e:hz9m-tj6z d:2016-03-31T00:00:00.000Z t:agency_id=1 t:crime_id=160913298 t:original_crimetype_name=Tent t:state=CA t:disposition=ADV t:city="San Francisco" m:row_number.hz9m-tj6z=2

series e:hz9m-tj6z d:2016-03-31T00:00:00.000Z t:agency_id=1 t:crime_id=160913309 t:original_crimetype_name="Intoxicated Person" t:state=CA t:disposition=HAN t:city="San Francisco" m:row_number.hz9m-tj6z=3
```

## Meta Commands

```ls
metric m:row_number.hz9m-tj6z p:long l:"Row Number"

entity e:hz9m-tj6z l:"Police Department Calls for Service" t:attribution="City and County of San Francisco" t:url=https://data.sfgov.org/api/views/hz9m-tj6z

property e:hz9m-tj6z t:meta.view v:id=hz9m-tj6z v:category="Public Safety" v:attributionLink=http://www.sfgov.org v:averageRating=0 v:name="Police Department Calls for Service" v:attribution="City and County of San Francisco"

property e:hz9m-tj6z t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:hz9m-tj6z t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:hz9m-tj6z t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| crime_id  | original_crimetype_name | report_date         | call_date           | offense_date        | call_time | call_dttm           | disposition | address                          | city          | state | agency_id | address_type    | common_location          | 
| ========= | ======================= | =================== | =================== | =================== | ========= | =================== | =========== | ================================ | ============= | ===== | ========= | =============== | ======================== | 
| 160913285 | Arrest Made             | 2016-03-31T00:00:00 | 2016-03-31T00:00:00 | 2016-03-31T00:00:00 | 19:49     | 2016-03-31T19:49:00 | ARR         | Jones St/golden Gate Av          | San Francisco | CA    | 1         | Intersection    |                          | 
| 160913298 | Tent                    | 2016-03-31T00:00:00 | 2016-03-31T00:00:00 | 2016-03-31T00:00:00 | 19:54     | 2016-03-31T19:54:00 | ADV         | 100 Block Of South Van Ness Av   | San Francisco | CA    | 1         | Premise Address |                          | 
| 160913309 | Intoxicated Person      | 2016-03-31T00:00:00 | 2016-03-31T00:00:00 | 2016-03-31T00:00:00 | 19:57     | 2016-03-31T19:57:00 | HAN         | 300 Block Of Ofarrell St         | San Francisco | CA    | 1         | Premise Address |                          | 
| 160921553 | Passing Call            | 2016-04-01T00:00:00 | 2016-04-01T00:00:00 | 2016-04-01T00:00:00 | 12:22     | 2016-04-01T12:22:00 | HAN         | 500 Block Of The Embarcadero Nor | San Francisco | CA    | 1         | Common Location | Pier 7, Sf               | 
| 160921589 | Missing Adult           | 2016-04-01T00:00:00 | 2016-04-01T00:00:00 | 2016-04-01T00:00:00 | 12:33     | 2016-04-01T12:33:00 | CAN         | 1500 Block Of Franklin St        | San Francisco | CA    | 1         | Premise Address |                          | 
| 160921596 | Mentally Disturbed      | 2016-04-01T00:00:00 | 2016-04-01T00:00:00 | 2016-04-01T00:00:00 | 12:33     | 2016-04-01T12:33:00 | GOA         | South Van Ness Av/mission St     | San Francisco | CA    | 1         | Intersection    |                          | 
| 161042258 | Traffic Stop            | 2016-04-13T00:00:00 | 2016-04-13T00:00:00 | 2016-04-13T00:00:00 | 14:33     | 2016-04-13T14:33:00 | CIT         | 9th St/market St                 | San Francisco | CA    | 1         | Intersection    |                          | 
| 161042422 | Poss                    | 2016-04-13T00:00:00 | 2016-04-13T00:00:00 | 2016-04-13T00:00:00 | 15:18     | 2016-04-13T15:18:00 | GOA         | Sumner St/howard St              | San Francisco | CA    | 1         | Intersection    |                          | 
| 161061362 | Noise Nuisance          | 2016-04-15T00:00:00 | 2016-04-15T00:00:00 | 2016-04-15T00:00:00 | 11:08     | 2016-04-15T11:08:00 | HAN         | 0 Block Of Powell St             | San Francisco | CA    | 1         | Common Location | Cable Car Turnaround, Sf | 
| 161063455 | Assault / Battery       | 2016-04-15T00:00:00 | 2016-04-15T00:00:00 | 2016-04-15T00:00:00 | 19:47     | 2016-04-15T19:47:00 | HAN         | 100 Block Of Eddy St             | San Francisco | CA    | 1         | Premise Address |                          | 
```