# Parking Violations Issued - Fiscal Year 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/parking-violations-issued-fiscal-year-2015) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/c284-tqph) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/c284-tqph/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/c284-tqph/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | c284-tqph |
| Name | Parking Violations Issued - Fiscal Year 2015 |
| Attribution | Department of Finance (DOF) |
| Tags | finance, dof, stars, ticket, violation, summons, parking ticket, parking violations issued - fiscal year 2015 |
| Created | 2015-08-25T00:48:09Z |
| Publication Date | 2015-08-25T00:48:41Z |

## Description

Parking Violations Issued - Fiscal Year 2015

?	Parking Violations Issued Fiscal Year 2017 can be found here https://data.cityofnewyork.us/d/pvqr-7yc4
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
| No       |                | vehicle_expiration_date           | Vehicle Expiration Date           | calendar_date | calendar_date |
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
| No       |                | date_first_observed               | Date First Observed               | calendar_date | calendar_date |
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
Excluded Fields = vehicle_expiration_date,violation_time,time_first_observed,date_first_observed
```

## Data Commands

```ls
series e:c284-tqph d:2015-05-19T00:00:00.000Z t:sub_division=B t:vehicle_color=BK t:issuing_agency=V t:street_name="NB KINGS HWY @ AVE N" t:violation_legal_code=T t:vehicle_body_type=4DSD t:issuer_code=0 t:violation_description="PHTO SCHOOL ZN SPEED VIOLATION" t:plate_type=PAS t:summons_number=4607287003 t:vehicle_make=NISSA t:registration_state=NY t:violation_code=36 t:street_code1=0 t:vehicle_year=2014 t:street_code2=40404 t:street_code3=40404 t:plate_id=GRE6525 m:violation_precinct=0 m:feet_from_curb=0 m:issuer_precinct=0 m:law_section=1180

series e:c284-tqph d:2014-10-07T00:00:00.000Z t:sub_division=F1 t:vehicle_color=WHITE t:issuing_agency=P t:violation_location=0076 t:violation_county=K t:street_name="COURT ST" t:vehicle_body_type=DELV t:issuer_code=945237 t:issuer_squad=0000 t:plate_type=COM t:summons_number=1371786434 t:vehicle_make=MERCU t:meter_number=- t:violation_in_front_of_or_opposite=F t:days_parking_in_effect=BBBBBBB t:house_number=352 t:registration_state=NY t:violation_code=46 t:to_hours_in_effect=ALL t:issuer_command=0076 t:street_code1=29830 t:vehicle_year=0 t:from_hours_in_effect=ALL t:street_code2=86530 t:street_code3=72230 t:plate_id=36371ME m:violation_precinct=76 m:unregistered_vehicle=0 m:feet_from_curb=0 m:issuer_precinct=76 m:law_section=408

series e:c284-tqph d:2014-07-26T00:00:00.000Z t:sub_division=K6 t:vehicle_color=BK t:issuing_agency=P t:violation_location=102 t:violation_county=Q t:street_name="S/E 125 ST" t:vehicle_body_type=TRTR t:issuer_code=948736 t:issuer_squad=0000 t:plate_type=PAS t:summons_number=1369386308 t:vehicle_make=ECOLA t:meter_number=- t:days_parking_in_effect=BBBBBBB t:registration_state=NJ t:violation_code=78 t:to_hours_in_effect=ALL t:issuer_command=0102 t:street_code1=0 t:vehicle_year=0 t:from_hours_in_effect=ALL t:street_code2=0 t:street_code3=0 t:intersecting_street="C/O ATLANTIC AVE" t:plate_id=AP202W m:violation_precinct=102 m:unregistered_vehicle=0 m:feet_from_curb=0 m:issuer_precinct=102 m:law_section=408
```

## Meta Commands

```ls
metric m:violation_precinct p:integer l:"Violation Precinct" t:dataTypeName=number

metric m:issuer_precinct p:integer l:"Issuer Precinct" t:dataTypeName=number

metric m:law_section p:integer l:"Law Section" t:dataTypeName=number

metric m:unregistered_vehicle p:integer l:"Unregistered Vehicle?" t:dataTypeName=number

metric m:feet_from_curb p:integer l:"Feet From Curb" t:dataTypeName=number

entity e:c284-tqph l:"Parking Violations Issued - Fiscal Year 2015" t:attribution="Department of Finance (DOF)" t:url=https://data.cityofnewyork.us/api/views/c284-tqph

property e:c284-tqph t:meta.view v:id=c284-tqph v:averageRating=0 v:name="Parking Violations Issued - Fiscal Year 2015" v:attribution="Department of Finance (DOF)"

property e:c284-tqph t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:c284-tqph t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| summons_number | plate_id | registration_state | plate_type | issue_date          | violation_code | vehicle_body_type | vehicle_make | issuing_agency | street_code1 | street_code2 | street_code3 | vehicle_expiration_date | violation_location | violation_precinct | issuer_precinct | issuer_code | issuer_command | issuer_squad | violation_time | time_first_observed | violation_county | violation_in_front_of_or_opposite | house_number | street_name          | intersecting_street | date_first_observed | law_section | sub_division | violation_legal_code | days_parking_in_effect | from_hours_in_effect | to_hours_in_effect | vehicle_color | unregistered_vehicle | vehicle_year | meter_number | feet_from_curb | violation_post_code | violation_description          | no_standing_or_stopping_violation | hydrant_violation | double_parking_violation | 
| ============== | ======== | ================== | ========== | =================== | ============== | ================= | ============ | ============== | ============ | ============ | ============ | ======================= | ================== | ================== | =============== | =========== | ============== | ============ | ============== | =================== | ================ | ================================= | ============ | ==================== | =================== | =================== | =========== | ============ | ==================== | ====================== | ==================== | ================== | ============= | ==================== | ============ | ============ | ============== | =================== | ============================== | ================================= | ================= | ======================== | 
| 4607287003     | GRE6525  | NY                 | PAS        | 2015-05-19T00:00:00 | 36             | 4DSD              | NISSA        | V              | 0            | 40404        | 40404        | 0001-01-03T12:00:00     |                    | 0                  | 0               | 0           |                |              | 0859A          |                     |                  |                                   |              | NB KINGS HWY @ AVE N |                     | 0001-01-03T12:00:00 | 1180        | B            | T                    |                        |                      |                    | BK            |                      | 2014         |              | 0              |                     | PHTO SCHOOL ZN SPEED VIOLATION |                                   |                   |                          | 
| 1371786434     | 36371ME  | NY                 | COM        | 2014-10-07T00:00:00 | 46             | DELV              | MERCU        | P              | 29830        | 86530        | 72230        | 0001-01-03T12:00:00     | 0076               | 76                 | 76              | 945237      | 0076           | 0000         | 0337P          |                     | K                | F                                 | 352          | COURT ST             |                     | 0001-01-03T12:00:00 | 408         | F1           |                      | BBBBBBB                | ALL                  | ALL                | WHITE         | 0                    | 0            | -            | 0              |                     |                                |                                   |                   |                          | 
| 1369386308     | AP202W   | NJ                 | PAS        | 2014-07-26T00:00:00 | 78             | TRTR              | ECOLA        | P              | 0            | 0            | 0            | 0001-01-03T12:00:00     | 102                | 102                | 102             | 948736      | 0102           | 0000         | 1201A          |                     | Q                |                                   |              | S/E 125 ST           | C/O ATLANTIC AVE    | 0001-01-03T12:00:00 | 408         | K6           |                      | BBBBBBB                | ALL                  | ALL                | BK            | 0                    | 0            | -            | 0              |                     |                                |                                   |                   |                          | 
| 5081587564     | FANS4    | NY                 | SPO        | 2014-07-14T00:00:00 | 7              | SUBN              | VOLVO        | V              | 0            | 0            | 0            | 0001-01-03T12:00:00     |                    | 0                  | 0               | 0           |                |              | 0646P          |                     |                  |                                   |              | CADMAN PLAZA (E/B) @ | PROSPECT ST         | 0001-01-03T12:00:00 | 1111        | D            | T                    |                        |                      |                    | BR            |                      | 2012         |              | 0              |                     | FAILURE TO STOP AT RED LIGHT   |                                   |                   |                          | 
| 1377548569     | 14489JY  | NY                 | COM        | 2015-02-10T00:00:00 | 46             | VAN               | FRUEH        | P              | 24690        | 36250        | 36270        | 0001-01-03T12:00:00     | 0028               | 28                 | 28              | 949853      | 0028           | 0000         | 1130A          |                     | NY               | F                                 | 290          | LENOX AVE            |                     | 0001-01-03T12:00:00 | 408         | F1           |                      | BBBBBBB                | ALL                  | ALL                | WHITE         | 0                    | 2007         | -            | 0              |                     |                                |                                   |                   |                          | 
| 4602944747     | GAR3514  | NY                 | PAS        | 2014-10-08T00:00:00 | 36             | 4DSD              | HONDA        | V              | 0            | 0            | 0            | 0001-01-03T12:00:00     |                    | 0                  | 0               | 0           |                |              | 1113A          |                     |                  |                                   |              | NB KINGS HWY @ E 94T | H ST                | 0001-01-03T12:00:00 | 1180        | B            | T                    |                        |                      |                    | BK            |                      | 2007         |              | 0              |                     | PHTO SCHOOL ZN SPEED VIOLATION |                                   |                   |                          | 
| 4604342430     | FTJ3552  | NY                 | PAS        | 2014-12-18T00:00:00 | 36             | 4DSD              | MAZDA        | V              | 0            | 0            | 0            | 0001-01-03T12:00:00     |                    | 0                  | 0               | 0           |                |              | 1041A          |                     |                  |                                   |              | SB BAYCHESTER AVE @  | CRAWFORD AVE        | 0001-01-03T12:00:00 | 1180        | B            | T                    |                        |                      |                    | GY            |                      | 2012         |              | 0              |                     | PHTO SCHOOL ZN SPEED VIOLATION |                                   |                   |                          | 
| 1368289990     | 2028313  | IN                 | PAS        | 2014-12-22T00:00:00 | 41             | DELV              | ISUZU        | P              | 34630        | 10610        | 10810        | 0001-01-03T12:00:00     | 0018               | 18                 | 420             | 927266      | 0420           | 0000         | 0932A          |                     | NY               | F                                 | 229          | W 43RD ST            |                     | 0001-01-03T12:00:00 | 408         | C            |                      | BBBBBBB                | ALL                  | ALL                | BLK           | 0                    | 0            | -            | 0              |                     |                                |                                   |                   |                          | 
| 1368289990     | 2028313  | IN                 | PAS        | 2014-12-22T00:00:00 | 41             | DELV              | ISUZU        | P              | 34630        | 10610        | 10810        | 0001-01-03T12:00:00     | 0018               | 18                 | 420             | 927266      | 0420           | 0000         | 0932A          |                     | NY               | F                                 | 229          | W 43RD ST            |                     | 0001-01-03T12:00:00 | 408         | C            |                      | BBBBBBB                | ALL                  | ALL                | BLK           | 0                    | 0            | -            | 0              |                     |                                |                                   |                   |                          | 
| 4003034296     | GEM8340  | NY                 | PAS        | 2014-04-14T00:00:00 | 5              | 2DSD              | HONDA        | V              | 0            | 0            | 0            | 0001-01-03T12:00:00     |                    | 0                  | 0               | 0           |                |              | 0656P          |                     |                  |                                   |              | NB ROGERS AVE @ MONT | GOMERY ST           | 0001-01-03T12:00:00 | 1111        | C            | T                    |                        |                      |                    | BK            |                      | 2008         |              | 0              |                     | BUS LANE VIOLATION             |                                   |                   |                          | 
```