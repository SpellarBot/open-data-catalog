# Parking Violations Issued - Fiscal Year 2017

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/parking-violations-issued-fiscal-year-2017) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/pvqr-7yc4) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/pvqr-7yc4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/pvqr-7yc4/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | pvqr-7yc4 |
| Name | Parking Violations Issued - Fiscal Year 2017 |
| Attribution | Department of Finance (DOF) |
| Category | City Government |
| Tags | finance, dof, stars, ticket, violation, summons, parking ticket, parking violations issued - fiscal year 2015 |
| Created | 2016-07-22T19:06:16Z |
| Publication Date | 2016-07-28T18:22:50Z |

## Description

This dataset is updated on the third week of each month.

?	Parking Violations Issued Fiscal Year 2016 can be found in the archived dataset here https://data.cityofnewyork.us/d/kiv2-tbus

?	Parking Violations Issued Fiscal Year 2015 can be found in the archived dataset here https://data.cityofnewyork.us/d/c284-tqph

?	Parking Violations Issued Fiscal Year 2014 can be found in the archived dataset here https://data.cityofnewyork.us/d/jt7v-77mi

## Columns

```ls
| Included | Schema Type    | Field Name                        | Name                              | Data Type     | Render Type   |
| ======== | ============== | ================================= | ================================= | ============= | ============= |
| Yes      | series tag     | summons_number                    | Summons Number                    | text          | number        |
| Yes      | series tag     | plate_id                          | Plate ID                          | text          | text          |
| Yes      | series tag     | registration_state                | Registration State                | text          | text          |
| Yes      | series tag     | plate_type                        | Plate Type                        | text          | text          |
| Yes      | time           | issue_date                        | Issue Date                        | calendar_date | calendar_date |
| Yes      | series tag     | violation_code                    | Violation Code                    | text          | number        |
| Yes      | series tag     | vehicle_body_type                 | Vehicle Body Type                 | text          | text          |
| Yes      | series tag     | vehicle_make                      | Vehicle Make                      | text          | text          |
| Yes      | series tag     | issuing_agency                    | Issuing Agency                    | text          | text          |
| Yes      | series tag     | street_code1                      | Street Code1                      | text          | number        |
| Yes      | series tag     | street_code2                      | Street Code2                      | text          | number        |
| Yes      | series tag     | street_code3                      | Street Code3                      | text          | number        |
| No       |                | vehicle_expiration_date           | Vehicle Expiration Date           | text          | number        |
| Yes      | series tag     | violation_location                | Violation Location                | text          | text          |
| Yes      | numeric metric | violation_precinct                | Violation Precinct                | number        | number        |
| Yes      | numeric metric | issuer_precinct                   | Issuer Precinct                   | number        | number        |
| Yes      | series tag     | issuer_code                       | Issuer Code                       | text          | number        |
| Yes      | series tag     | issuer_command                    | Issuer Command                    | text          | text          |
| Yes      | series tag     | issuer_squad                      | Issuer Squad                      | text          | text          |
| No       |                | violation_time                    | Violation Time                    | text          | text          |
| No       |                | time_first_observed               | Time First Observed               | text          | text          |
| Yes      | series tag     | violation_county                  | Violation County                  | text          | text          |
| Yes      | series tag     | violation_in_front_of_or_opposite | Violation In Front Of Or Opposite | text          | text          |
| Yes      | series tag     | house_number                      | House Number                      | text          | text          |
| Yes      | series tag     | street_name                       | Street Name                       | text          | text          |
| Yes      | series tag     | intersecting_street               | Intersecting Street               | text          | text          |
| Yes      | numeric metric | date_first_observed               | Date First Observed               | number        | number        |
| Yes      | numeric metric | law_section                       | Law Section                       | number        | number        |
| Yes      | series tag     | sub_division                      | Sub Division                      | text          | text          |
| Yes      | series tag     | violation_legal_code              | Violation Legal Code              | text          | text          |
| Yes      | series tag     | days_parking_in_effect            | Days Parking In Effect            | text          | text          |
| Yes      | series tag     | from_hours_in_effect              | From Hours In Effect              | text          | text          |
| Yes      | series tag     | to_hours_in_effect                | To Hours In Effect                | text          | text          |
| Yes      | series tag     | vehicle_color                     | Vehicle Color                     | text          | text          |
| Yes      | numeric metric | unregistered_vehicle              | Unregistered Vehicle?             | number        | text          |
| Yes      | series tag     | vehicle_year                      | Vehicle Year                      | text          | number        |
| Yes      | series tag     | meter_number                      | Meter Number                      | text          | text          |
| Yes      | numeric metric | feet_from_curb                    | Feet From Curb                    | number        | number        |
| Yes      | series tag     | violation_post_code               | Violation Post Code               | text          | text          |
| Yes      | series tag     | violation_description             | Violation Description             | text          | text          |
| Yes      | series tag     | no_standing_or_stopping_violation | No Standing or Stopping Violation | text          | text          |
| Yes      | series tag     | hydrant_violation                 | Hydrant Violation                 | text          | text          |
| Yes      | series tag     | double_parking_violation          | Double Parking Violation          | text          | text          |
```

## Time Field

```ls
Value = issue_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = vehicle_expiration_date,violation_time,time_first_observed
```

## Data Commands

```ls
series e:pvqr-7yc4 d:2016-06-30T00:00:00.000Z t:sub_division=C3 t:vehicle_color=SILVE t:issuing_agency=P t:violation_location=0043 t:violation_county=BX t:street_name="UNIONPORT RD" t:vehicle_body_type=SUBN t:issuer_code=118 t:issuer_squad=0000 t:plate_type=PAS t:summons_number=1388765056 t:vehicle_make=TOYOT t:meter_number=- t:violation_in_front_of_or_opposite=F t:days_parking_in_effect=BBBBBBB t:house_number=1551 t:registration_state=NY t:violation_code=19 t:to_hours_in_effect=ALL t:issuer_command=0000 t:street_code1=70520 t:vehicle_year=2001 t:from_hours_in_effect=ALL t:street_code2=66520 t:street_code3=50770 t:plate_id=GZH7067 m:violation_precinct=43 m:unregistered_vehicle=0 m:feet_from_curb=0 m:issuer_precinct=0 m:law_section=408 m:date_first_observed=0

series e:pvqr-7yc4 d:2016-07-04T00:00:00.000Z t:sub_division=D t:vehicle_color=WHITE t:issuing_agency=X t:violation_location=0043 t:violation_county=BX t:street_name="UNIONPORT ROAD" t:vehicle_body_type=SDN t:issuer_code=156 t:issuer_squad=0000 t:plate_type=PAS t:summons_number=1388765070 t:vehicle_make=ME/BE t:meter_number=- t:violation_in_front_of_or_opposite=O t:days_parking_in_effect=BBBBBBB t:house_number=1516 t:registration_state=NY t:violation_code=40 t:to_hours_in_effect=ALL t:issuer_command=0000 t:street_code1=70520 t:vehicle_year=2015 t:from_hours_in_effect=ALL t:street_code2=66520 t:street_code3=50770 t:plate_id=GYW7777 m:violation_precinct=43 m:unregistered_vehicle=0 m:feet_from_curb=0 m:issuer_precinct=0 m:law_section=408 m:date_first_observed=0

series e:pvqr-7yc4 d:2016-07-11T00:00:00.000Z t:sub_division=E2 t:vehicle_color=BLACK t:issuing_agency=X t:violation_location=0043 t:violation_county=BX t:street_name="PURDY STREET" t:vehicle_body_type=TAXI t:issuer_code=156 t:issuer_squad=0000 t:plate_type=OMT t:summons_number=1388765081 t:vehicle_make=LINCO t:meter_number=- t:violation_in_front_of_or_opposite=O t:days_parking_in_effect=BBBBBBB t:house_number=1624 t:registration_state=NY t:violation_code=60 t:to_hours_in_effect=ALL t:issuer_command=0000 t:street_code1=59820 t:vehicle_year=2011 t:from_hours_in_effect=ALL t:street_code2=56920 t:street_code3=12550 t:plate_id=T619261C m:violation_precinct=43 m:unregistered_vehicle=0 m:feet_from_curb=0 m:issuer_precinct=0 m:law_section=408 m:date_first_observed=0
```

## Meta Commands

```ls
metric m:violation_precinct p:integer l:"Violation Precinct" t:dataTypeName=number

metric m:issuer_precinct p:integer l:"Issuer Precinct" t:dataTypeName=number

metric m:date_first_observed p:integer l:"Date First Observed" t:dataTypeName=number

metric m:law_section p:integer l:"Law Section" t:dataTypeName=number

metric m:unregistered_vehicle p:integer l:"Unregistered Vehicle?" t:dataTypeName=number

metric m:feet_from_curb p:integer l:"Feet From Curb" t:dataTypeName=number

entity e:pvqr-7yc4 l:"Parking Violations Issued - Fiscal Year 2017" t:attribution="Department of Finance (DOF)" t:url=https://data.cityofnewyork.us/api/views/pvqr-7yc4

property e:pvqr-7yc4 t:meta.view v:id=pvqr-7yc4 v:category="City Government" v:averageRating=0 v:name="Parking Violations Issued - Fiscal Year 2017" v:attribution="Department of Finance (DOF)"

property e:pvqr-7yc4 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:pvqr-7yc4 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| summons_number | plate_id | registration_state | plate_type | issue_date          | violation_code | vehicle_body_type | vehicle_make | issuing_agency | street_code1 | street_code2 | street_code3 | vehicle_expiration_date | violation_location | violation_precinct | issuer_precinct | issuer_code | issuer_command | issuer_squad | violation_time | time_first_observed | violation_county | violation_in_front_of_or_opposite | house_number | street_name       | intersecting_street | date_first_observed | law_section | sub_division | violation_legal_code | days_parking_in_effect | from_hours_in_effect | to_hours_in_effect | vehicle_color | unregistered_vehicle | vehicle_year | meter_number | feet_from_curb | violation_post_code | violation_description | no_standing_or_stopping_violation | hydrant_violation | double_parking_violation | 
| ============== | ======== | ================== | ========== | =================== | ============== | ================= | ============ | ============== | ============ | ============ | ============ | ======================= | ================== | ================== | =============== | =========== | ============== | ============ | ============== | =================== | ================ | ================================= | ============ | ================= | =================== | =================== | =========== | ============ | ==================== | ====================== | ==================== | ================== | ============= | ==================== | ============ | ============ | ============== | =================== | ===================== | ================================= | ================= | ======================== | 
| 1388765056     | GZH7067  | NY                 | PAS        | 2016-06-30T00:00:00 | 19             | SUBN              | TOYOT        | P              | 70520        | 66520        | 50770        | 20170827.0              | 0043               | 43                 | 0               | 118         | 0000           | 0000         | 0217A          |                     | BX               | F                                 | 1551         | UNIONPORT RD      |                     | 0                   | 408         | C3           |                      | BBBBBBB                | ALL                  | ALL                | SILVE         | 0                    | 2001         | -            | 0              |                     |                       |                                   |                   |                          | 
| 1388765070     | GYW7777  | NY                 | PAS        | 2016-07-04T00:00:00 | 40             | SDN               | ME/BE        | X              | 70520        | 66520        | 50770        | 20170531.0              | 0043               | 43                 | 0               | 156         | 0000           | 0000         | 0118A          |                     | BX               | O                                 | 1516         | UNIONPORT ROAD    |                     | 0                   | 408         | D            |                      | BBBBBBB                | ALL                  | ALL                | WHITE         | 0                    | 2015         | -            | 0              |                     |                       |                                   |                   |                          | 
| 1388765081     | T619261C | NY                 | OMT        | 2016-07-11T00:00:00 | 60             | TAXI              | LINCO        | X              | 59820        | 56920        | 12550        | 20161130.0              | 0043               | 43                 | 0               | 156         | 0000           | 0000         | 0615A          |                     | BX               | O                                 | 1624         | PURDY STREET      |                     | 0                   | 408         | E2           |                      | BBBBBBB                | ALL                  | ALL                | BLACK         | 0                    | 2011         | -            | 0              |                     |                       |                                   |                   |                          | 
| 1388765100     | GSG2912  | NY                 | PAS        | 2016-07-04T00:00:00 | 40             | SDN               | NISSA        | X              | 50770        | 70520        | 12550        | 20160818.0              | 0043               | 43                 | 0               | 92          | 0000           | 0000         | 0110A          |                     | BX               | F                                 | 7            | METROPOLITAN OVAL |                     | 0                   | 408         | E2           |                      | BBBBBBB                | ALL                  | ALL                | GREY          | 0                    | 2009         | -            | 0              |                     |                       |                                   |                   |                          | 
| 1388765111     | GRH1070  | NY                 | PAS        | 2016-07-01T00:00:00 | 70             | SDN               | VOLKS        | P              | 50020        | 50750        | 59720        | 20160623.0              | 0043               | 43                 | 0               | 92          | 0000           | 0000         | 0630A          |                     | BX               | F                                 | 1935         | MCGRAW AVE        |                     | 0                   | 408         | D            |                      | BBBBBBB                | ALL                  | ALL                | WHITE         | 0                    | 2014         | -            | 0              |                     |                       |                                   |                   |                          | 
| 1388765123     | HEB3247  | NY                 | PAS        | 2016-06-28T00:00:00 | 24             | SDN               | HONDA        | P              | 50770        | 12550        | 12550        | 20180125.0              | 0043               | 43                 | 0               | 92          | 0000           | 0000         | 0622A          |                     | BX               | O                                 | 63           | METROPOLITAN OVAL |                     | 0                   | 408         | J3           |                      | YYYYYYB                | 0600A                | 0700P              | BLACK         | 0                    | 2016         | -            | 0              |                     |                       |                                   |                   |                          | 
| 1388765147     | HAW9085  | NY                 | PAS        | 2016-06-29T00:00:00 | 67             | SDN               | HYUND        | X              | 50020        | 59720        | 12550        | 20170826.0              | 0043               | 43                 | 0               | 135         | 0000           | 0000         | 1116P          |                     |                  | F                                 | 2001         | MCGRAW AVENUE     |                     | 0                   | 408         | C            |                      | BBBBBBB                | ALL                  | ALL                | BLACK         | 0                    | 2005         | -            | 0              |                     |                       |                                   |                   |                          | 
| 1388765160     | GCR3087  | NY                 | PAS        | 2016-07-10T00:00:00 | 20             | SDN               | HONDA        | X              | 50770        | 12550        | 12550        | 20170414.0              | 0043               | 43                 | 0               | 135         | 0000           | 0000         | 1035P          |                     | BX               | F                                 | 14           | METROPOLITAN OVAL |                     | 0                   | 408         | M2           |                      | BBBBBBB                | ALL                  | ALL                | SILVE         | 0                    | 2002         | -            | 0              |                     |                       |                                   |                   |                          | 
| 1388765172     | HBN6619  | NY                 | PAS        | 2016-07-09T00:00:00 | 14             | SDN               | SAAB         | X              | 50020        | 50750        | 59720        | 20171216.0              | 0043               | 43                 | 0               | 110         | 0000           | 0000         | 0534P          |                     | BX               | F                                 | 1949         | MCGRAW AVE        |                     | 0                   | 408         | D            |                      | BBBBBBB                | ALL                  | ALL                | NAVY          | 0                    | 2007         | -            | 0              |                     |                       |                                   |                   |                          | 
| 1388765184     | HAB9889  | NY                 | PAS        | 2016-06-30T00:00:00 | 16             | SUBN              | TOYOT        | P              | 73970        | 78490        | 23800        | 20170809.0              | 0043               | 43                 | 0               | 88          | 0000           | 0000         | 0645P          |                     | BX               | O                                 | 1489         | WEST AVE          |                     | 0                   | 408         | D5           |                      | BBBBBBB                | ALL                  | ALL                | WHITE         | 0                    | 2006         | -            | 0              |                     |                       |                                   |                   |                          | 
```