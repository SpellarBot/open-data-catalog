# Occupations Licensed or Certified by New York State

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/occupations-licensed-or-certified-by-new-york-state) |
| Metadata | [Link](https://data.ny.gov/api/views/w2w4-tdxt) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/w2w4-tdxt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/w2w4-tdxt/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | w2w4-tdxt |
| Name | Occupations Licensed or Certified by New York State |
| Attribution | New York State Department of Labor |
| Category | Economic Development |
| Tags | occupations, licensed, certified |
| Created | 2014-04-23T21:26:06Z |
| Publication Date | 2015-08-04T18:18:39Z |

## Description

The Occupations Licensed or Certified by New York State dataset contains a list of occupations, which by law are licensed or certified by a New York State agency.

## Columns

```ls
| Included | Schema Type | Field Name                             | Name                                   | Data Type | Render Type |
| ======== | =========== | ====================================== | ====================================== | ========= | =========== |
| No       | time        | :updated_at                            | updated_at                             | meta_data | meta_data   |
| Yes      | series tag  | new_york_state_agency_occupation_title | New York State Agency Occupation Title | text      | text        |
| Yes      | series tag  | agency                                 | Agency                                 | text      | text        |
| Yes      | series tag  | division                               | Division                               | text      | text        |
| Yes      | series tag  | street_address                         | Street Address                         | text      | text        |
| Yes      | series tag  | city                                   | City                                   | text      | text        |
| Yes      | series tag  | state                                  | State                                  | text      | text        |
| Yes      | series tag  | zip                                    | ZIP                                    | text      | text        |
| Yes      | series tag  | telephone                              | Telephone                              | text      | number      |
| Yes      | series tag  | url                                    | URL                                    | url       | url         |
| Yes      | series tag  | occupation_code                        | Occupation Code                        | text      | text        |
| Yes      | series tag  | occupation_title                       | Occupation Title                       | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:w2w4-tdxt d:2015-08-03T15:13:59.000Z t:occupation_code=47-5031 t:zip=12240 t:division="Division of Safety and Health" t:new_york_state_agency_occupation_title=Blaster t:state=NY t:agency="NYS Department of Labor" t:street_address="State Office Campus, Building 12, Room 161" t:telephone=5184857815 t:url=http://labor.ny.gov/stats/olcny/blasters.shtm t:occupation_title="Explosives Workers, Ordnance Handling Experts, and Blasters" t:city=Albany m:row_number.w2w4-tdxt=1

series e:w2w4-tdxt d:2015-08-03T15:13:59.000Z t:occupation_code=47-4011 t:zip=12240 t:division="Division of Safety and Health" t:new_york_state_agency_occupation_title="Boiler Inspector" t:state=NY t:agency="NYS Department of Labor" t:street_address="State Office Campus, Building 12, Room 165" t:telephone=5184572722 t:url=http://labor.ny.gov/stats/olcny/boiler-inspector.shtm t:occupation_title="Construction and Building Inspectors" t:city=Albany m:row_number.w2w4-tdxt=2

series e:w2w4-tdxt d:2015-08-03T15:13:59.000Z t:occupation_code=53-3021 t:zip=12228 t:division="Bus Driver Unit" t:new_york_state_agency_occupation_title="Bus Driver" t:state=NY t:agency="NYS Department of Motor Vehicles" t:street_address="6 Empire State Plaza, Room 220C" t:telephone=5184739455 t:url=http://labor.ny.gov/stats/olcny/bus-driver.shtm t:occupation_title="Bus Drivers, Transit and Intercity" t:city=Albany m:row_number.w2w4-tdxt=3
```

## Meta Commands

```ls
metric m:row_number.w2w4-tdxt p:long l:"Row Number"

entity e:w2w4-tdxt l:"Occupations Licensed or Certified by New York State" t:attribution="New York State Department of Labor" t:url=https://data.ny.gov/api/views/w2w4-tdxt

property e:w2w4-tdxt t:meta.view v:id=w2w4-tdxt v:category="Economic Development" v:attributionLink=http://labor.ny.gov/stats/lstrain.shtm v:averageRating=0 v:name="Occupations Licensed or Certified by New York State" v:attribution="New York State Department of Labor"

property e:w2w4-tdxt t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:w2w4-tdxt t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:w2w4-tdxt t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | new_york_state_agency_occupation_title | agency                           | division                                 | street_address                             | city        | state | zip   | telephone  | url                                                                            | occupation_code | occupation_title                                                          | 
| =========== | ====================================== | ================================ | ======================================== | ========================================== | =========== | ===== | ===== | ========== | ============================================================================== | =============== | ========================================================================= | 
| 1438614839  | Blaster                                | NYS Department of Labor          | Division of Safety and Health            | State Office Campus, Building 12, Room 161 | Albany      | NY    | 12240 | 5184857815 | [http://labor.ny.gov/stats/olcny/blasters.shtm, null]                          | 47-5031         | Explosives Workers, Ordnance Handling Experts, and Blasters               | 
| 1438614839  | Boiler Inspector                       | NYS Department of Labor          | Division of Safety and Health            | State Office Campus, Building 12, Room 165 | Albany      | NY    | 12240 | 5184572722 | [http://labor.ny.gov/stats/olcny/boiler-inspector.shtm, null]                  | 47-4011         | Construction and Building Inspectors                                      | 
| 1438614839  | Bus Driver                             | NYS Department of Motor Vehicles | Bus Driver Unit                          | 6 Empire State Plaza, Room 220C            | Albany      | NY    | 12228 | 5184739455 | [http://labor.ny.gov/stats/olcny/bus-driver.shtm, null]                        | 53-3021         | Bus Drivers, Transit and Intercity                                        | 
| 1438614839  | Certified Examiner - Bus Driver        | NYS Department of Motor Vehicles | Bus Driver Unit                          | 6 Empire State Plaza, Room 524             | Albany      | NY    | 12228 | 5184745485 | [http://labor.ny.gov/stats/olcny/certified-examiner-bus-driver.shtm, null]     | 13-1041         | Licensing Examiners and Inspectors                                        | 
| 1438614839  | Certified Motor Vehicle Inspector      | NYS Department of Motor Vehicles | Bureau of Consumer and Facility Services | P.O Box 2700                               | Albany      | NY    | 12220 | 5184747998 | [http://labor.ny.gov/stats/olcny/certified-motor-vehicle-inspector.shtm, null] | 53-6051         | Transportation Vehicle, Equipment and Systems Inspectors, Except Aviation | 
| 1438614839  | Crane Operator                         | NYS Department of Labor          | Division of Safety and Health            | State Office Campus, Building 12, Room 161 | Albany      | NY    | 12240 | 5184857815 | [http://labor.ny.gov/stats/olcny/crane-operator.shtm, null]                    | 53-7021         | Crane and Tower Operators                                                 | 
| 1438614839  | Driving School Instructor              | NYS Department of Motor Vehicles | Bureau of Driver Training Programs       | 6 Empire State Plaza, Room 412             | Albany      | NY    | 12228 | 5184737746 | [http://labor.ny.gov/stats/olcny/driving-school-instructor.shtm, null]         | 25-2031         | Secondary School Teachers, Except Special and Vocational Education        | 
| 1438614839  | Exercise Rider                         | NYS Racing and Wagering Board    |                                          | One Broadway Center, Suite 600             | Schenectady | NY    | 12305 | 5183955400 | [http://labor.ny.gov/stats/olcny/racetrack-exercise-rider.shtm, null]          | 13-1011         | Agents and Business Managers of Artists, Performers, and Athletes         | 
| 1438614839  | Farrier                                | NYS Racing and Wagering Board    |                                          | One Broadway Center, Suite 600             | Schenectady | NY    | 12305 | 5183955400 | [http://labor.ny.gov/stats/olcny/farriers.shtm, null]                          | 39-2021         | Nonfarm Animal Caretakers                                                 | 
| 1438614839  | Groom                                  | NYS Racing and Wagering Board    |                                          | One Broadway Center, Suite 600             | Schenectady | NY    | 12305 | 5183955400 | [http://labor.ny.gov/stats/olcny/grooms.shtm, null]                            | 39-2021         | Nonfarm Animal Caretakers                                                 | 
```