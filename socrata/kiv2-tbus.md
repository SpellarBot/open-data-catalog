# Parking Violations Issued - Fiscal Year 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/parking-violations-issued-fiscal-year-2016) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/kiv2-tbus) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/kiv2-tbus/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/kiv2-tbus/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | kiv2-tbus |
| Name | Parking Violations Issued - Fiscal Year 2016 |
| Attribution | Department of Finance (DOF) |
| Category | City Government |
| Tags | finance, dof, stars, ticket, violation, summons, parking ticket, parking violations issued - fiscal year 2015 |
| Created | 2014-08-13T15:04:34Z |
| Publication Date | 2016-07-18T17:07:53Z |

## Description

?	Parking Violations Issued Fiscal Year 2017 can be found here https://data.cityofnewyork.us/d/pvqr-7yc4 

?	Parking Violations Issued Fiscal Year 2015 can be found in the archived dataset here https://data.cityofnewyork.us/d/c284-tqph

?	Parking Violations Issued Fiscal Year 2014  can be found in the archived dataset here https://data.cityofnewyork.us/d/jt7v-77mi

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
| Yes      | series tag     | unregistered_vehicle              | Unregistered Vehicle?             | text          | text          |
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
series e:kiv2-tbus d:2015-07-09T00:00:00.000Z t:sub_division=D1 t:vehicle_color=WHITE t:unregistered_vehicle=0 t:issuing_agency=P t:violation_location=0074 t:violation_county=K t:street_name="MACDOUNGH ST" t:vehicle_body_type=SDN t:issuer_code=358160 t:issuer_squad=0000 t:plate_type=PAS t:summons_number=1363745270 t:vehicle_make=HONDA t:meter_number=- t:violation_in_front_of_or_opposite=F t:days_parking_in_effect=BBBBBBB t:house_number=142 t:registration_state=99 t:violation_code=46 t:to_hours_in_effect=ALL t:issuer_command=T301 t:street_code1=0 t:vehicle_year=2010 t:from_hours_in_effect=ALL t:street_code2=40404 t:street_code3=40404 t:plate_id=GGY6450 m:violation_precinct=74 m:feet_from_curb=0 m:issuer_precinct=301 m:law_section=408 m:date_first_observed=0

series e:kiv2-tbus d:2015-07-09T00:00:00.000Z t:sub_division=F1 t:vehicle_color=RED t:unregistered_vehicle=0 t:issuing_agency=P t:violation_location=0079 t:violation_county=K t:street_name="LEXINGTON AVE" t:vehicle_body_type=SUBN t:issuer_code=358160 t:issuer_squad=0000 t:plate_type=PAS t:summons_number=1363745293 t:vehicle_make=CHEVR t:meter_number=- t:violation_in_front_of_or_opposite=F t:days_parking_in_effect=YBBYBBB t:house_number=331 t:registration_state=SC t:violation_code=21 t:to_hours_in_effect=1230P t:issuer_command=T301 t:street_code1=55730 t:vehicle_year=0 t:from_hours_in_effect=1100A t:street_code2=67030 t:street_code3=58730 t:plate_id=KXD355 m:violation_precinct=79 m:feet_from_curb=0 m:issuer_precinct=301 m:law_section=408 m:date_first_observed=0

series e:kiv2-tbus d:2015-07-09T00:00:00.000Z t:sub_division=D1 t:vehicle_color=WHITE t:unregistered_vehicle=0 t:issuing_agency=P t:violation_location=0079 t:violation_county=K t:street_name="FULTON ST" t:vehicle_body_type=SDN t:issuer_code=358114 t:issuer_squad=0000 t:plate_type=PAS t:summons_number=1363745438 t:vehicle_make=ME/BE t:meter_number=- t:violation_in_front_of_or_opposite=F t:days_parking_in_effect=YBBYBBB t:house_number=1087 t:registration_state=PA t:violation_code=21 t:to_hours_in_effect=0930A t:issuer_command=TEBN t:street_code1=42730 t:vehicle_year=0 t:from_hours_in_effect=0800A t:street_code2=26730 t:street_code3=26830 t:plate_id=JCK7576 m:violation_precinct=79 m:feet_from_curb=0 m:issuer_precinct=0 m:law_section=408 m:date_first_observed=0
```

## Meta Commands

```ls
metric m:violation_precinct p:integer l:"Violation Precinct" t:dataTypeName=number

metric m:issuer_precinct p:integer l:"Issuer Precinct" t:dataTypeName=number

metric m:date_first_observed p:integer l:"Date First Observed" t:dataTypeName=number

metric m:law_section p:integer l:"Law Section" t:dataTypeName=number

metric m:feet_from_curb p:integer l:"Feet From Curb" t:dataTypeName=number

entity e:kiv2-tbus l:"Parking Violations Issued - Fiscal Year 2016" t:attribution="Department of Finance (DOF)" t:url=https://data.cityofnewyork.us/api/views/kiv2-tbus

property e:kiv2-tbus t:meta.view v:id=kiv2-tbus v:category="City Government" v:averageRating=0 v:name="Parking Violations Issued - Fiscal Year 2016" v:attribution="Department of Finance (DOF)"

property e:kiv2-tbus t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:kiv2-tbus t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| summons_number | plate_id | registration_state | plate_type | issue_date          | violation_code | vehicle_body_type | vehicle_make | issuing_agency | street_code1 | street_code2 | street_code3 | vehicle_expiration_date | violation_location | violation_precinct | issuer_precinct | issuer_code | issuer_command | issuer_squad | violation_time | time_first_observed | violation_county | violation_in_front_of_or_opposite | house_number | street_name   | intersecting_street | date_first_observed | law_section | sub_division | violation_legal_code | days_parking_in_effect | from_hours_in_effect | to_hours_in_effect | vehicle_color | unregistered_vehicle | vehicle_year | meter_number | feet_from_curb | violation_post_code | violation_description | no_standing_or_stopping_violation | hydrant_violation | double_parking_violation | 
| ============== | ======== | ================== | ========== | =================== | ============== | ================= | ============ | ============== | ============ | ============ | ============ | ======================= | ================== | ================== | =============== | =========== | ============== | ============ | ============== | =================== | ================ | ================================= | ============ | ============= | =================== | =================== | =========== | ============ | ==================== | ====================== | ==================== | ================== | ============= | ==================== | ============ | ============ | ============== | =================== | ===================== | ================================= | ================= | ======================== | 
| 1363745270     | GGY6450  | 99                 | PAS        | 2015-07-09T00:00:00 | 46             | SDN               | HONDA        | P              | 0            | 40404        | 40404        | 20170602.0              | 0074               | 74                 | 301             | 358160      | T301           | 0000         | 1037A          |                     | K                | F                                 | 142          | MACDOUNGH ST  |                     | 0                   | 408         | D1           |                      | BBBBBBB                | ALL                  | ALL                | WHITE         | 0                    | 2010         | -            | 0              |                     |                       |                                   |                   |                          | 
| 1363745293     | KXD355   | SC                 | PAS        | 2015-07-09T00:00:00 | 21             | SUBN              | CHEVR        | P              | 55730        | 67030        | 58730        | 20160288.0              | 0079               | 79                 | 301             | 358160      | T301           | 0000         | 1206P          |                     | K                | F                                 | 331          | LEXINGTON AVE |                     | 0                   | 408         | F1           |                      | YBBYBBB                | 1100A                | 1230P              | RED           | 0                    | 0            | -            | 0              |                     |                       |                                   |                   |                          | 
| 1363745438     | JCK7576  | PA                 | PAS        | 2015-07-09T00:00:00 | 21             | SDN               | ME/BE        | P              | 42730        | 26730        | 26830        | 0.00000000              | 0079               | 79                 | 0               | 358114      | TEBN           | 0000         | 0820A          |                     | K                | F                                 | 1087         | FULTON ST     |                     | 0                   | 408         | D1           |                      | YBBYBBB                | 0800A                | 0930A              | WHITE         | 0                    | 0            | -            | 0              |                     |                       |                                   |                   |                          | 
| 1363745475     | GYK7658  | NY                 | OMS        | 2015-07-09T00:00:00 | 21             | SUBN              | NISSA        | P              | 58130        | 18630        | 67030        | 0.00000000              | 0079               | 79                 | 301             | 358114      | T301           | 0000         | 0918A          |                     | K                | F                                 | 207          | MADISON ST    |                     | 0                   | 408         | D1           |                      | YBBYBBB                | 0900A                | 1030               | BK            | 0                    | 2015         | -            | 0              |                     |                       |                                   |                   |                          | 
| 1363745487     | GMT8141  | NY                 | PAS        | 2015-07-09T00:00:00 | 21             | P-U               | LINCO        | P              | 58130        | 67030        | 58730        | 20160206.0              | 0079               | 79                 | 301             | 358114      | T301           | 0000         | 0925A          |                     | K                | F                                 | 237          | MADISON ST    |                     | 0                   | 408         | D1           |                      | YBBYBBB                | 0900A                | 1030A              | BLK           | 0                    | 2006         | -            | 0              |                     |                       |                                   |                   |                          | 
| 1363745517     | GYK3760  | NY                 | PAS        | 2015-07-09T00:00:00 | 21             | SUBN              | HONDA        | P              | 46730        | 58730        | 85730        | 20160709.0              | 0079               | 79                 | 301             | 358114      | T301           | 0000         | 0948A          |                     | K                | F                                 | 201          | HALSEY ST     |                     | 0                   | 408         | D1           |                      | YBBYBBB                | 0900A                | 1030A              | OTHER         | 0                    | 2006         | -            | 0              |                     |                       |                                   |                   |                          | 
| 1363745529     | GYK3760  | NY                 | PAS        | 2015-07-09T00:00:00 | 75             | SUBN              | HONDA        | P              | 46730        | 58730        | 85730        | 20160709.0              |                    | 0                  | 301             | 358114      | T301           | 0000         | 0949A          |                     | K                | F                                 | 201          | HALSEY ST     |                     | 0                   | 408         | D1           |                      | BBBBBBB                | ALL                  | ALL                | OTHER         | 0                    | 2006         | -            | 0              |                     |                       |                                   |                   |                          | 
| 1363745542     | GWL9925  | NY                 | PAS        | 2015-07-09T00:00:00 | 71             | SDN               | TOYOT        | P              | 85730        | 59530        | 32030        | 20170602.0              | 0079               | 79                 | 301             | 358114      | T301           | 0000         | 1043A          |                     | K                | O                                 | 482          | TOMPKINS AVE  |                     | 0                   | 408         | D1           |                      | BBBBBBB                | ALL                  | ALL                | OTHER         | 0                    | 2006         | -            | 0              |                     |                       |                                   |                   |                          | 
| 1363745554     | GPH9963  | PA                 | PAS        | 2015-07-09T00:00:00 | 21             | SDN               | MITSU        | P              | 55730        | 67030        | 58730        | 20150288.0              | 0079               | 79                 | 301             | 358114      | T301           | 0000         | 1204P          |                     | K                | F                                 | 317          | LEXINGTON AVE |                     | 0                   | 408         | J6           |                      | YBBYBBB                | 1100A                | 1230P              | OTHER         | 0                    | 0            | -            | 0              |                     |                       |                                   |                   |                          | 
| 1363745578     | GWF8627  | NY                 | PAS        | 2015-07-09T00:00:00 | 21             | SUBN              | LINCO        | P              | 31530        | 58730        | 85730        | 20170407.0              | 0079               | 79                 | 301             | 358114      | T301           | 0000         | 1227P          |                     | K                | F                                 | 739          | DEKALB AVE    |                     | 0                   | 408         | D1           |                      | YBBYBBB                | 1200P                | 0130P              | OTHER         | 0                    | 2002         | -            | 0              |                     |                       |                                   |                   |                          | 
```