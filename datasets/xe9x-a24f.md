# Motor Vehicle Crashes - Vehicle Information: Three Year Window

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/motor-vehicle-crashes-vehicle-information-beginning-2009) |
| Metadata | [Link](https://data.ny.gov/api/views/xe9x-a24f) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/xe9x-a24f/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/xe9x-a24f/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | xe9x-a24f |
| Name | Motor Vehicle Crashes - Vehicle Information: Three Year Window |
| Attribution | NYS Department of Motor Vehicles |
| Category | Transportation |
| Tags | crash, accident, fatalities, vehicle, driver, owner |
| Created | 2013-05-28T19:22:12Z |
| Publication Date | 2016-09-02T19:48:09Z |

## Description

Attributes about each vehicle involved in a crash as reported to NYS DMV

## Columns

```ls
| Included | Schema Type    | Field Name                        | Name                              | Data Type | Render Type |
| ======== | ============== | ================================= | ================================= | ========= | =========== |
| Yes      | time           | year                              | Year                              | number    | number      |
| Yes      | series tag     | case_vehicle_id                   | Case Vehicle ID                   | text      | number      |
| Yes      | series tag     | vehicle_body_type                 | Vehicle Body Type                 | text      | text        |
| Yes      | series tag     | registration_class                | Registration Class                | text      | text        |
| Yes      | series tag     | action_prior_to_accident          | Action Prior to Accident          | text      | text        |
| Yes      | series tag     | type_axles_of_truck_or_bus        | Type / Axles of Truck or Bus      | text      | text        |
| Yes      | series tag     | direction_of_travel               | Direction of Travel               | text      | text        |
| Yes      | series tag     | fuel_type                         | Fuel Type                         | text      | text        |
| Yes      | numeric metric | vehicle_year                      | Vehicle Year                      | number    | text        |
| Yes      | series tag     | state_of_registration             | State of Registration             | text      | text        |
| Yes      | numeric metric | number_of_occupants               | Number of Occupants               | number    | text        |
| Yes      | numeric metric | engine_cylinders                  | Engine Cylinders                  | number    | text        |
| Yes      | series tag     | vehicle_make                      | Vehicle Make                      | text      | text        |
| Yes      | series tag     | contributing_factor_1             | Contributing Factor 1             | text      | text        |
| Yes      | series tag     | contributing_factor_1_description | Contributing Factor 1 Description | text      | text        |
| Yes      | series tag     | contributing_factor_2             | Contributing Factor 2             | text      | text        |
| Yes      | series tag     | contributing_factor_2_description | Contributing Factor 2 Description | text      | text        |
| Yes      | series tag     | event_type                        | Event Type                        | text      | text        |
| Yes      | series tag     | partial_vin                       | Partial VIN                       | text      | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:xe9x-a24f d:2013-01-01T00:00:00.000Z t:action_prior_to_accident=Backing t:type_axles_of_truck_or_bus="Not Entered" t:event_type="Not Applicable" t:vehicle_body_type="2 DOOR SEDAN" t:vehicle_make=HOND t:contributing_factor_2_description="Driver Inattention/Distraction*" t:fuel_type="Not Entered" t:case_vehicle_id=11256149 t:contributing_factor_1_description="Backing Unsafely" t:state_of_registration=NY t:contributing_factor_1=HUMAN t:contributing_factor_2=HUMAN t:direction_of_travel=South t:registration_class="Not Entered" m:vehicle_year=2013 m:number_of_occupants=1

series e:xe9x-a24f d:2013-01-01T00:00:00.000Z t:action_prior_to_accident=Overtaking/Passing t:type_axles_of_truck_or_bus="Not Entered" t:event_type="Overturned, Non-Collision" t:vehicle_body_type="4 DOOR SEDAN" t:vehicle_make=DODG t:contributing_factor_2_description="Passing or Lane Usage Improper" t:fuel_type="Not Entered" t:case_vehicle_id=11330798 t:contributing_factor_1_description="Unsafe Lane Changing" t:state_of_registration=VA t:contributing_factor_1=HUMAN t:contributing_factor_2=HUMAN t:direction_of_travel=North t:registration_class="Not Entered" m:vehicle_year=2013 m:number_of_occupants=1

series e:xe9x-a24f d:2013-01-01T00:00:00.000Z t:action_prior_to_accident="Going Straight Ahead" t:type_axles_of_truck_or_bus="Not Entered" t:event_type="Not Applicable" t:vehicle_body_type="2 DOOR SEDAN" t:vehicle_make=NISS t:contributing_factor_2_description="Not Applicable" t:fuel_type="Not Entered" t:case_vehicle_id=11053659 t:contributing_factor_1_description="Animal's Action" t:state_of_registration=PA t:contributing_factor_1=ENVMT t:contributing_factor_2=HUMAN t:direction_of_travel=East t:registration_class="Not Entered" m:vehicle_year=2010 m:number_of_occupants=1
```

## Meta Commands

```ls
metric m:vehicle_year p:integer l:"Vehicle Year" d:"Manufacture's year of vehicle" t:dataTypeName=number

metric m:number_of_occupants p:integer l:"Number of Occupants" d:"Number of occupants in vehicle at time of crash" t:dataTypeName=number

metric m:engine_cylinders p:integer l:"Engine Cylinders" d:"Number of cylinders the vehicle has" t:dataTypeName=number

entity e:xe9x-a24f l:"Motor Vehicle Crashes - Vehicle Information: Three Year Window" t:attribution="NYS Department of Motor Vehicles" t:url=https://data.ny.gov/api/views/xe9x-a24f

property e:xe9x-a24f t:meta.view v:id=xe9x-a24f v:category=Transportation v:attributionLink=http://www.dmv.ny.gov/stats.htm v:averageRating=0 v:name="Motor Vehicle Crashes - Vehicle Information: Three Year Window" v:attribution="NYS Department of Motor Vehicles"

property e:xe9x-a24f t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:xe9x-a24f t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| year | case_vehicle_id | vehicle_body_type | registration_class | action_prior_to_accident | type_axles_of_truck_or_bus | direction_of_travel | fuel_type   | vehicle_year | state_of_registration | number_of_occupants | engine_cylinders | vehicle_make | contributing_factor_1 | contributing_factor_1_description | contributing_factor_2 | contributing_factor_2_description | event_type                | partial_vin | 
| ==== | =============== | ================= | ================== | ======================== | ========================== | =================== | =========== | ============ | ===================== | =================== | ================ | ============ | ===================== | ================================= | ===================== | ================================= | ========================= | =========== | 
| 2013 | 11256149        | 2 DOOR SEDAN      | Not Entered        | Backing                  | Not Entered                | South               | Not Entered | 2013         | NY                    | 1                   |                  | HOND         | HUMAN                 | Backing Unsafely                  | HUMAN                 | Driver Inattention/Distraction*   | Not Applicable            |             | 
| 2013 | 11330798        | 4 DOOR SEDAN      | Not Entered        | Overtaking/Passing       | Not Entered                | North               | Not Entered | 2013         | VA                    | 1                   |                  | DODG         | HUMAN                 | Unsafe Lane Changing              | HUMAN                 | Passing or Lane Usage Improper    | Overturned, Non-Collision |             | 
| 2013 | 11053659        | 2 DOOR SEDAN      | Not Entered        | Going Straight Ahead     | Not Entered                | East                | Not Entered | 2010         | PA                    | 1                   |                  | NISS         | ENVMT                 | Animal's Action                   | HUMAN                 | Not Applicable                    | Not Applicable            |             | 
| 2013 | 10831549        | POLICE VEHICLE    | Not Entered        | Going Straight Ahead     | Not Entered                | East                | Not Entered | 2012         | NY                    | 1                   |                  | FORD         | ENVMT                 | Animal's Action                   | HUMAN                 | Not Applicable                    | Not Applicable            |             | 
| 2013 | 10890741        | SUBURBAN          | Not Entered        | Changing Lanes           | Not Entered                | North               | Not Entered | 2006         | NJ                    | 3                   |                  | DODG         | ENVMT                 | Pavement Slippery                 | HUMAN                 | Not Applicable                    | Not Applicable            |             | 
| 2013 | 11095421        | 4 DOOR SEDAN      | Not Entered        | Making Left Turn         | Not Entered                | Northwest           | Not Entered | 2013         | TN                    | 1                   |                  | TOYT         | HUMAN                 | Failure to Yield Right-of-Way     | HUMAN                 | Not Applicable                    | Not Applicable            |             | 
| 2012 | 10001283        | 4 DOOR SEDAN      | DEALER             | Going Straight Ahead     | Not Entered                | East                | None        | 2001         | NY                    | 1                   | 0                | DODGE        | HUMAN                 | Not Applicable                    | HUMAN                 | Not Applicable                    | Not Applicable            |             | 
| 2012 | 10454932        | 4 DOOR SEDAN      | DEALER             | Going Straight Ahead     | Not Entered                | East                | None        | 2012         | NY                    | 1                   | 0                | CHRY         | ENVMT                 | Animal's Action                   | HUMAN                 | Not Applicable                    | Not Applicable            |             | 
| 2012 | 10742629        | DUMP              | Not Entered        | Making Right Turn        | Not Entered                | Southwest           | None        | 2001         | NY                    | 1                   | 0                | MAC          | HUMAN                 | Unsafe Lane Changing              | HUMAN                 | Driver Inattention/Distraction*   | Not Applicable            |             | 
| 2012 | 10915394        | 4 DOOR SEDAN      | DEALER             | Going Straight Ahead     | Not Entered                | South               | None        | 2006         | NY                    | 1                   | 0                | ME/BE        | HUMAN                 | Following Too Closely             | HUMAN                 | Not Entered                       | Not Entered               |             | 
```