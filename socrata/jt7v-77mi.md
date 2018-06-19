# Parking Violations Issued - Fiscal Year 2014 (August 2013 ? June 2014)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/parking-violations-issued-fiscal-year-2014-august-2013-june-2014-c1a76) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/jt7v-77mi) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/jt7v-77mi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/jt7v-77mi/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | jt7v-77mi |
| Name | Parking Violations Issued - Fiscal Year 2014 (August 2013 ? June 2014) |
| Attribution | Department of Finance (DOF) |
| Category | City Government |
| Tags | finance, dof, stars, ticket, violation, summons, parking ticket, parking violations issued - fiscal year 2014 (august 2013 ? june 2014) |
| Created | 2013-09-10T14:40:16Z |
| Publication Date | 2013-09-13T18:45:55Z |

## Description

Parking Violations Issued during Fiscal Year 2014 (August 2013 ? June 2014)

?	Parking Violations Issued Fiscal Year 2017 can be found here https://data.cityofnewyork.us/d/pvqr-7yc4
?	Parking Violations Issued Fiscal Year 2016 can be found in the archived dataset here https://data.cityofnewyork.us/d/kiv2-tbus
?	Parking Violations Issued Fiscal Year 2015 can be found in the archived dataset here https://data.cityofnewyork.us/d/c284-tqph

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
series e:jt7v-77mi d:2013-08-04T00:00:00.000Z t:sub_division=F1 t:vehicle_color=GY t:issuing_agency=P t:violation_location=0033 t:street_name="W 175 ST" t:vehicle_body_type=SUBN t:issuer_code=921043 t:issuer_squad=0000 t:plate_type=PAS t:summons_number=1283294138 t:vehicle_make=AUDI t:meter_number=- t:violation_in_front_of_or_opposite=F t:days_parking_in_effect=BBBBBBB t:house_number=712 t:registration_state=NY t:violation_code=46 t:to_hours_in_effect=ALL t:issuer_command=0033 t:street_code1=37250 t:vehicle_year=2013 t:from_hours_in_effect=ALL t:street_code2=13610 t:street_code3=21190 t:plate_id=GBB9093 m:violation_precinct=33 m:unregistered_vehicle=0 m:feet_from_curb=0 m:issuer_precinct=33 m:law_section=408 m:date_first_observed=0

series e:jt7v-77mi d:2013-08-04T00:00:00.000Z t:sub_division=C t:vehicle_color=WH t:issuing_agency=P t:violation_location=0033 t:violation_county=NY t:street_name="W 177 ST" t:vehicle_body_type=VAN t:issuer_code=921043 t:issuer_squad=0000 t:plate_type=COM t:summons_number=1283294151 t:vehicle_make=FORD t:meter_number=- t:violation_in_front_of_or_opposite=O t:days_parking_in_effect=BBBBBBB t:house_number=201 t:registration_state=NY t:violation_code=46 t:to_hours_in_effect=ALL t:issuer_command=0033 t:street_code1=37290 t:vehicle_year=2012 t:from_hours_in_effect=ALL t:street_code2=40404 t:street_code3=40404 t:plate_id=62416MB m:violation_precinct=33 m:unregistered_vehicle=0 m:feet_from_curb=0 m:issuer_precinct=33 m:law_section=408 m:date_first_observed=0

series e:jt7v-77mi d:2013-08-05T00:00:00.000Z t:sub_division=F7 t:issuing_agency=P t:violation_location=0033 t:violation_county=NY t:street_name="W 163 ST" t:vehicle_body_type=P-U t:issuer_code=921043 t:issuer_squad=0000 t:plate_type=COM t:summons_number=1283294163 t:vehicle_make=CHEVR t:meter_number=- t:violation_in_front_of_or_opposite=O t:days_parking_in_effect=BBBBBBB t:house_number=520 t:registration_state=NY t:violation_code=46 t:to_hours_in_effect=ALL t:issuer_command=0033 t:street_code1=37030 t:vehicle_year=0 t:from_hours_in_effect=ALL t:street_code2=31190 t:street_code3=13610 t:plate_id=78755JZ m:violation_precinct=33 m:unregistered_vehicle=0 m:feet_from_curb=0 m:issuer_precinct=33 m:law_section=408 m:date_first_observed=0
```

## Meta Commands

```ls
metric m:violation_precinct p:integer l:"Violation Precinct" t:dataTypeName=number

metric m:issuer_precinct p:integer l:"Issuer Precinct" t:dataTypeName=number

metric m:date_first_observed p:integer l:"Date First Observed" t:dataTypeName=number

metric m:law_section p:integer l:"Law Section" t:dataTypeName=number

metric m:unregistered_vehicle p:integer l:"Unregistered Vehicle?" t:dataTypeName=number

metric m:feet_from_curb p:integer l:"Feet From Curb" t:dataTypeName=number

entity e:jt7v-77mi l:"Parking Violations Issued - Fiscal Year 2014 (August 2013 ? June 2014)" t:attribution="Department of Finance (DOF)" t:url=https://data.cityofnewyork.us/api/views/jt7v-77mi

property e:jt7v-77mi t:meta.view v:id=jt7v-77mi v:category="City Government" v:averageRating=50 v:name="Parking Violations Issued - Fiscal Year 2014 (August 2013 ? June 2014)" v:attribution="Department of Finance (DOF)"

property e:jt7v-77mi t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:jt7v-77mi t:meta.view.tableauthor v:id=ew5s-ts2p v:screenName=Venkat v:displayName=Venkat
```

## Top Records

```ls
| summons_number | plate_id | registration_state | plate_type | issue_date          | violation_code | vehicle_body_type | vehicle_make | issuing_agency | street_code1 | street_code2 | street_code3 | vehicle_expiration_date | violation_location | violation_precinct | issuer_precinct | issuer_code | issuer_command | issuer_squad | violation_time | time_first_observed | violation_county | violation_in_front_of_or_opposite | house_number | street_name          | intersecting_street | date_first_observed | law_section | sub_division | violation_legal_code | days_parking_in_effect | from_hours_in_effect | to_hours_in_effect | vehicle_color | unregistered_vehicle | vehicle_year | meter_number | feet_from_curb | violation_post_code | violation_description | no_standing_or_stopping_violation | hydrant_violation | double_parking_violation | 
| ============== | ======== | ================== | ========== | =================== | ============== | ================= | ============ | ============== | ============ | ============ | ============ | ======================= | ================== | ================== | =============== | =========== | ============== | ============ | ============== | =================== | ================ | ================================= | ============ | ==================== | =================== | =================== | =========== | ============ | ==================== | ====================== | ==================== | ================== | ============= | ==================== | ============ | ============ | ============== | =================== | ===================== | ================================= | ================= | ======================== | 
| 1283294138     | GBB9093  | NY                 | PAS        | 2013-08-04T00:00:00 | 46             | SUBN              | AUDI         | P              | 37250        | 13610        | 21190        | 20140831.0              | 0033               | 33                 | 33              | 921043      | 0033           | 0000         | 0752A          |                     |                  | F                                 | 712          | W 175 ST             |                     | 0                   | 408         | F1           |                      | BBBBBBB                | ALL                  | ALL                | GY            | 0                    | 2013         | -            | 0              |                     |                       |                                   |                   |                          | 
| 1283294151     | 62416MB  | NY                 | COM        | 2013-08-04T00:00:00 | 46             | VAN               | FORD         | P              | 37290        | 40404        | 40404        | 20140430.0              | 0033               | 33                 | 33              | 921043      | 0033           | 0000         | 1240P          |                     | NY               | O                                 | 201          | W 177 ST             |                     | 0                   | 408         | C            |                      | BBBBBBB                | ALL                  | ALL                | WH            | 0                    | 2012         | -            | 0              |                     |                       |                                   |                   |                          | 
| 1283294163     | 78755JZ  | NY                 | COM        | 2013-08-05T00:00:00 | 46             | P-U               | CHEVR        | P              | 37030        | 31190        | 13610        | 20140228.0              | 0033               | 33                 | 33              | 921043      | 0033           | 0000         | 1243P          |                     | NY               | O                                 | 520          | W 163 ST             |                     | 0                   | 408         | F7           |                      | BBBBBBB                | ALL                  | ALL                |               | 0                    | 0            | -            | 0              |                     |                       |                                   |                   |                          | 
| 1283294175     | 63009MA  | NY                 | COM        | 2013-08-05T00:00:00 | 46             | VAN               | FORD         | P              | 37270        | 11710        | 12010        | 20141031.0              | 0033               | 33                 | 33              | 921043      | 0033           | 0000         | 0232P          |                     | NY               | O                                 | 517          | W 176 ST             |                     | 0                   | 408         | F1           |                      | BBBBBBB                | ALL                  | ALL                | WH            | 0                    | 2010         | -            | 0              |                     |                       |                                   |                   |                          | 
| 1283294187     | 91648MC  | NY                 | COM        | 2013-08-08T00:00:00 | 41             | TRLR              | GMC          | P              | 37240        | 12010        | 31190        | 0.00000000              | 0033               | 33                 | 33              | 921043      | 0033           | 0000         | 1239P          |                     | NY               | F                                 | 590          | W 174 ST             |                     | 0                   | 408         | E1           |                      | BBBBBBB                | ALL                  | ALL                | BR            | 0                    | 2012         | -            | 0              |                     |                       |                                   |                   |                          | 
| 1283294217     | T60DAR   | NJ                 | PAS        | 2013-08-11T00:00:00 | 14             | P-U               | DODGE        | P              | 37250        | 10495        | 12010        | 0.00000000              | 0033               | 33                 | 33              | 921043      | 0033           | 0000         | 0617P          |                     | NY               | F                                 | 525          | W 175 ST             |                     | 0                   | 408         | F1           |                      | BBBBBBB                | ALL                  | ALL                | RD            | 0                    | 0            | -            | 0              |                     |                       |                                   |                   |                          | 
| 1283294229     | GCR2838  | NY                 | PAS        | 2013-08-11T00:00:00 | 14             | VAN               |              | P              | 37250        | 12010        | 31190        | 20141223.0              | 0033               | 33                 | 33              | 921043      | 0033           | 0000         | 0741P          |                     | NY               | F                                 | 551          | W 175 ST             |                     | 0                   | 408         | C            |                      | BBBBBBB                | ALL                  | ALL                | GN            | 0                    | 2011         | -            | 0              |                     |                       |                                   |                   |                          | 
| 1283983620     | XZ764G   | NJ                 | PAS        | 2013-08-07T00:00:00 | 24             | DELV              | FORD         | X              | 63430        | 0            | 0            | 0.00000000              | 0088               | 88                 | 976             | 101079      | 0976           | 0000         | 0425A          |                     | K                | F                                 | 100          | N.PORTLAND AVE       | BROOKLYN NY 11206   | 0                   | 408         | E5           |                      | BBBBBBB                | ALL                  | ALL                | WHITE         | 0                    | 0            | -            | 0              |                     |                       |                                   |                   |                          | 
| 1283983631     | GBH9379  | NY                 | PAS        | 2013-08-07T00:00:00 | 24             | SDN               | TOYOT        | X              | 63430        | 0            | 0            | 20140722.0              | 0088               | 88                 | 976             | 101079      | 0976           | 0000         | 0437A          |                     | K                | F                                 | 100          | N.PORTLAND AVE       | BROOKLYN NY 11206   | 0                   | 408         | D5           |                      | BBBBBBB                | ALL                  | ALL                | WHITE         | 0                    | 2001         | -            | 0              |                     |                       |                                   |                   |                          | 
| 1283983667     | MCL78B   | NJ                 | PAS        | 2013-07-18T00:00:00 | 24             | SDN               | SUBAR        | H              | 0            | 0            | 0            | 0.00000000              | 0079               | 79                 | 976             | 101043      | 0976           | 0000         | 0839A          |                     | K                | F                                 |              | 760 BROADWAY ,BROOKL | WOODHULL HOSPITAL   | 0                   | 408         | D            |                      | BBBBBBB                | ALL                  | ALL                | BLACK         | 0                    | 2005         | -            | 0              |                     |                       |                                   |                   |                          | 
```