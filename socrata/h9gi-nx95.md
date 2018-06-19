# NYPD Motor Vehicle Collisions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nypd-motor-vehicle-collisions-07420) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/h9gi-nx95) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/h9gi-nx95/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/h9gi-nx95/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | h9gi-nx95 |
| Name | NYPD Motor Vehicle Collisions |
| Attribution | Police Department (NYPD) |
| Category | Public Safety |
| Tags | nypd, collisions, bigapps, big apps, visionzero, vision, zero, nycopendata |
| Created | 2014-04-28T16:41:44Z |
| Publication Date | 2017-04-19T23:12:58Z |

## Description

Details of Motor Vehicle Collisions in New York City provided by the Police Department (NYPD).

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                          | Data Type     | Render Type   |
| ======== | ============== | ============================= | ============================= | ============= | ============= |
| Yes      | time           | date                          | DATE                          | calendar_date | calendar_date |
| Yes      | series tag     | time                          | TIME                          | text          | text          |
| Yes      | series tag     | borough                       | BOROUGH                       | text          | text          |
| Yes      | series tag     | zip_code                      | ZIP CODE                      | text          | text          |
| No       |                | latitude                      | LATITUDE                      | number        | number        |
| Yes      | numeric metric | longitude                     | LONGITUDE                     | number        | number        |
| Yes      | series tag     | on_street_name                | ON STREET NAME                | text          | text          |
| Yes      | series tag     | off_street_name               | CROSS STREET NAME             | text          | text          |
| Yes      | series tag     | cross_street_name             | OFF STREET NAME               | text          | text          |
| Yes      | numeric metric | number_of_persons_injured     | NUMBER OF PERSONS INJURED     | number        | number        |
| Yes      | numeric metric | number_of_persons_killed      | NUMBER OF PERSONS KILLED      | number        | number        |
| Yes      | numeric metric | number_of_pedestrians_injured | NUMBER OF PEDESTRIANS INJURED | number        | number        |
| Yes      | numeric metric | number_of_pedestrians_killed  | NUMBER OF PEDESTRIANS KILLED  | number        | number        |
| Yes      | numeric metric | number_of_cyclist_injured     | NUMBER OF CYCLIST INJURED     | number        | number        |
| Yes      | numeric metric | number_of_cyclist_killed      | NUMBER OF CYCLIST KILLED      | number        | number        |
| Yes      | numeric metric | number_of_motorist_injured    | NUMBER OF MOTORIST INJURED    | number        | number        |
| Yes      | numeric metric | number_of_motorist_killed     | NUMBER OF MOTORIST KILLED     | number        | number        |
| Yes      | series tag     | contributing_factor_vehicle_1 | CONTRIBUTING FACTOR VEHICLE 1 | text          | text          |
| Yes      | series tag     | contributing_factor_vehicle_2 | CONTRIBUTING FACTOR VEHICLE 2 | text          | text          |
| Yes      | series tag     | contributing_factor_vehicle_3 | CONTRIBUTING FACTOR VEHICLE 3 | text          | text          |
| Yes      | series tag     | contributing_factor_vehicle_4 | CONTRIBUTING FACTOR VEHICLE 4 | text          | text          |
| Yes      | series tag     | contributing_factor_vehicle_5 | CONTRIBUTING FACTOR VEHICLE 5 | text          | text          |
| Yes      | numeric metric | unique_key                    | UNIQUE KEY                    | number        | number        |
| Yes      | series tag     | vehicle_type_code1            | VEHICLE TYPE CODE 1           | text          | text          |
| Yes      | series tag     | vehicle_type_code2            | VEHICLE TYPE CODE 2           | text          | text          |
| Yes      | series tag     | vehicle_type_code_3           | VEHICLE TYPE CODE 3           | text          | text          |
| Yes      | series tag     | vehicle_type_code_4           | VEHICLE TYPE CODE 4           | text          | text          |
| Yes      | series tag     | vehicle_type_code_5           | VEHICLE TYPE CODE 5           | text          | text          |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = latitude
```

## Data Commands

```ls
series e:h9gi-nx95 d:2017-04-16T00:00:00.000Z t:contributing_factor_vehicle_1="Turning Improperly" t:time=0:00 t:on_street_name="EAST 172 STREET" t:zip_code=10472 t:vehicle_type_code1="PASSENGER VEHICLE" t:vehicle_type_code2="PICK-UP TRUCK" t:contributing_factor_vehicle_2=Unspecified t:borough=BRONX t:off_street_name="BRONX RIVER AVENUE" m:number_of_persons_killed=0 m:number_of_cyclist_injured=0 m:number_of_motorist_killed=0 m:number_of_persons_injured=0 m:number_of_motorist_injured=0 m:number_of_pedestrians_injured=0 m:number_of_cyclist_killed=0 m:unique_key=3651861 m:longitude=-73.88173 m:number_of_pedestrians_killed=0

series e:h9gi-nx95 d:2017-04-16T00:00:00.000Z t:contributing_factor_vehicle_1="Turning Improperly" t:time=0:00 t:on_street_name="BERGEN STREET" t:zip_code=11201 t:vehicle_type_code1=TAXI t:vehicle_type_code2="PASSENGER VEHICLE" t:contributing_factor_vehicle_2=Unspecified t:borough=BROOKLYN t:off_street_name="SMITH STREET" m:number_of_persons_killed=0 m:number_of_cyclist_injured=0 m:number_of_motorist_killed=0 m:number_of_persons_injured=0 m:number_of_motorist_injured=0 m:number_of_pedestrians_injured=0 m:number_of_cyclist_killed=0 m:unique_key=3651519 m:longitude=-73.99047 m:number_of_pedestrians_killed=0

series e:h9gi-nx95 d:2017-04-16T00:00:00.000Z t:contributing_factor_vehicle_1=Unspecified t:time=0:00 t:zip_code=11201 t:vehicle_type_code1="SPORT UTILITY / STATION WAGON" t:vehicle_type_code2="SPORT UTILITY / STATION WAGON" t:contributing_factor_vehicle_2=Unspecified t:cross_street_name="57        FRONT STREET" t:borough=BROOKLYN m:number_of_persons_killed=0 m:number_of_cyclist_injured=0 m:number_of_motorist_killed=0 m:number_of_persons_injured=0 m:number_of_motorist_injured=0 m:number_of_pedestrians_injured=0 m:number_of_cyclist_killed=0 m:unique_key=3651522 m:longitude=-73.99114 m:number_of_pedestrians_killed=0
```

## Meta Commands

```ls
metric m:longitude p:float l:LONGITUDE t:dataTypeName=number

metric m:number_of_persons_injured p:integer l:"NUMBER OF PERSONS INJURED" t:dataTypeName=number

metric m:number_of_persons_killed p:integer l:"NUMBER OF PERSONS KILLED" t:dataTypeName=number

metric m:number_of_pedestrians_injured p:integer l:"NUMBER OF PEDESTRIANS INJURED" t:dataTypeName=number

metric m:number_of_pedestrians_killed p:integer l:"NUMBER OF PEDESTRIANS KILLED" t:dataTypeName=number

metric m:number_of_cyclist_injured p:integer l:"NUMBER OF CYCLIST INJURED" t:dataTypeName=number

metric m:number_of_cyclist_killed p:integer l:"NUMBER OF CYCLIST KILLED" t:dataTypeName=number

metric m:number_of_motorist_injured p:integer l:"NUMBER OF MOTORIST INJURED" t:dataTypeName=number

metric m:number_of_motorist_killed p:integer l:"NUMBER OF MOTORIST KILLED" t:dataTypeName=number

metric m:unique_key p:integer l:"UNIQUE KEY" t:dataTypeName=number

entity e:h9gi-nx95 l:"NYPD Motor Vehicle Collisions" t:attribution="Police Department (NYPD)" t:url=https://data.cityofnewyork.us/api/views/h9gi-nx95

property e:h9gi-nx95 t:meta.view v:id=h9gi-nx95 v:category="Public Safety" v:averageRating=0 v:name="NYPD Motor Vehicle Collisions" v:attribution="Police Department (NYPD)"

property e:h9gi-nx95 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:h9gi-nx95 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| date                | time | borough  | zip_code | latitude   | longitude   | on_street_name  | off_street_name    | cross_street_name       | number_of_persons_injured | number_of_persons_killed | number_of_pedestrians_injured | number_of_pedestrians_killed | number_of_cyclist_injured | number_of_cyclist_killed | number_of_motorist_injured | number_of_motorist_killed | contributing_factor_vehicle_1        | contributing_factor_vehicle_2  | contributing_factor_vehicle_3 | contributing_factor_vehicle_4 | contributing_factor_vehicle_5 | unique_key | vehicle_type_code1            | vehicle_type_code2            | vehicle_type_code_3           | vehicle_type_code_4           | vehicle_type_code_5 | 
| =================== | ==== | ======== | ======== | ========== | =========== | =============== | ================== | ======================= | ========================= | ======================== | ============================= | ============================ | ========================= | ======================== | ========================== | ========================= | ==================================== | ============================== | ============================= | ============================= | ============================= | ========== | ============================= | ============================= | ============================= | ============================= | =================== | 
| 2017-04-16T00:00:00 | 0:00 | BRONX    | 10472    | 40.8312870 | -73.8817300 | EAST 172 STREET | BRONX RIVER AVENUE |                         | 0                         | 0                        | 0                             | 0                            | 0                         | 0                        | 0                          | 0                         | Turning Improperly                   | Unspecified                    |                               |                               |                               | 3651861    | PASSENGER VEHICLE             | PICK-UP TRUCK                 |                               |                               |                     | 
| 2017-04-16T00:00:00 | 0:00 | BROOKLYN | 11201    | 40.6867260 | -73.9904700 | BERGEN STREET   | SMITH STREET       |                         | 0                         | 0                        | 0                             | 0                            | 0                         | 0                        | 0                          | 0                         | Turning Improperly                   | Unspecified                    |                               |                               |                               | 3651519    | TAXI                          | PASSENGER VEHICLE             |                               |                               |                     | 
| 2017-04-16T00:00:00 | 0:00 | BROOKLYN | 11201    | 40.7025600 | -73.9911400 |                 |                    | 57 FRONT STREET         | 0                         | 0                        | 0                             | 0                            | 0                         | 0                        | 0                          | 0                         | Unspecified                          | Unspecified                    |                               |                               |                               | 3651522    | SPORT UTILITY / STATION WAGON | SPORT UTILITY / STATION WAGON |                               |                               |                     | 
| 2017-04-16T00:00:00 | 0:00 | QUEENS   | 11429    | 40.7125900 | -73.7331540 |                 |                    | 220-20 HEMPSTEAD AVENUE | 0                         | 0                        | 0                             | 0                            | 0                         | 0                        | 0                          | 0                         | Failure to Yield Right-of-Way        | Passing or Lane Usage Improper |                               |                               |                               | 3651540    | PASSENGER VEHICLE             | SPORT UTILITY / STATION WAGON |                               |                               |                     | 
| 2017-04-16T00:00:00 | 0:00 |          |          | 40.7014400 | -73.9847700 | BRIDGE STREET   |                    |                         | 0                         | 0                        | 0                             | 0                            | 0                         | 0                        | 0                          | 0                         | Driver Inattention/Distraction       | Unspecified                    |                               |                               |                               | 3651521    | PASSENGER VEHICLE             | SPORT UTILITY / STATION WAGON |                               |                               |                     | 
| 2017-04-16T00:00:00 | 0:00 |          |          | 40.6637270 | -73.9538600 | ROGERS AVENUE   |                    |                         | 0                         | 0                        | 0                             | 0                            | 0                         | 0                        | 0                          | 0                         | Reaction to Other Uninvolved Vehicle | Unspecified                    |                               |                               |                               | 3651951    | PASSENGER VEHICLE             | PASSENGER VEHICLE             |                               |                               |                     | 
| 2017-04-16T00:00:00 | 0:00 | BROOKLYN | 11220    | 40.6379620 | -74.0105800 | 7 AVENUE        | 58 STREET          |                         | 1                         | 0                        | 0                             | 0                            | 0                         | 0                        | 1                          | 0                         | Driver Inattention/Distraction       | Unspecified                    |                               |                               |                               | 3652716    | SPORT UTILITY / STATION WAGON | SPORT UTILITY / STATION WAGON | SPORT UTILITY / STATION WAGON |                               |                     | 
| 2017-04-16T00:00:00 | 0:00 | BROOKLYN | 11221    | 40.6983450 | -73.9215800 | WILSON AVENUE   | HIMROD STREET      |                         | 2                         | 0                        | 1                             | 0                            | 1                         | 0                        | 0                          | 0                         | Failure to Yield Right-of-Way        |                                |                               |                               |                               | 3652873    | BICYCLE                       |                               |                               |                               |                     | 
| 2017-04-16T00:00:00 | 0:00 |          |          |            |             | KINGS HIGHWAY   | AVENUE K           |                         | 3                         | 0                        | 0                             | 0                            | 0                         | 0                        | 3                          | 0                         | Unsafe Lane Changing                 | Unspecified                    | Unspecified                   | Unspecified                   |                               | 3652693    | SPORT UTILITY / STATION WAGON | PASSENGER VEHICLE             | SPORT UTILITY / STATION WAGON | PASSENGER VEHICLE             |                     | 
| 2017-04-16T00:00:00 | 0:05 | BROOKLYN | 11207    | 40.6700600 | -73.8905640 | SUTTER AVENUE   | MILLER AVENUE      |                         | 0                         | 0                        | 0                             | 0                            | 0                         | 0                        | 0                          | 0                         | Other Electronic Device              | Unspecified                    | Unspecified                   | Unspecified                   |                               | 3652730    | PASSENGER VEHICLE             | PASSENGER VEHICLE             | PASSENGER VEHICLE             | SPORT UTILITY / STATION WAGON |                     | 
```