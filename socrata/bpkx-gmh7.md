# Alternative Fuel Stations in New York

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/alternative-fuel-stations-in-new-york) |
| Metadata | [Link](https://data.ny.gov/api/views/bpkx-gmh7) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/bpkx-gmh7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/bpkx-gmh7/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | bpkx-gmh7 |
| Name | Alternative Fuel Stations in New York |
| Attribution | U.S. Department of Energy |
| Category | Energy & Environment |
| Tags | alternative fuel, station, biodiesel, natural gas, ethanol, electric, hydrogen |
| Created | 2016-02-19T18:11:05Z |
| Publication Date | 2017-04-20T22:03:14Z |

## Description

Go to http://1.usa.gov/1gPN1u8 to access the full database of alternative fuel station locations nationwide, collected and maintained by the U.S. Department of Energy National Renewable Energy Laboratory.  A station appears as one point in the data and on the map, regardless of the number of fuel dispensers or charging outlets at that location.  For EV charging stations for example, the data includes the number of number of charging ports available at the specific station.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type     | Render Type   |
| ======== | ============== | ======================= | ======================= | ============= | ============= |
| Yes      | series tag     | fuel_type_code          | Fuel Type Code          | text          | text          |
| Yes      | series tag     | station_name            | Station Name            | text          | text          |
| Yes      | series tag     | street_address          | Street Address          | text          | text          |
| Yes      | series tag     | intersection_directions | Intersection Directions | text          | text          |
| Yes      | series tag     | city                    | City                    | text          | text          |
| Yes      | series tag     | state                   | State                   | text          | text          |
| Yes      | series tag     | zip                     | ZIP                     | text          | text          |
| Yes      | series tag     | plus4                   | Plus4                   | text          | text          |
| Yes      | series tag     | station_phone           | Station Phone           | text          | text          |
| Yes      | series tag     | status_code             | Status Code             | text          | text          |
| Yes      | time           | expected_date           | Expected Date           | calendar_date | calendar_date |
| Yes      | series tag     | groups_with_access_code | Groups With Access Code | text          | text          |
| No       |                | access_days_time        | Access Days Time        | text          | text          |
| Yes      | series tag     | cards_accepted          | Cards Accepted          | text          | text          |
| Yes      | series tag     | bd_blends               | BD Blends               | text          | text          |
| Yes      | series tag     | ng_fill_type_code       | NG Fill Type Code       | text          | text          |
| Yes      | series tag     | ng_psi                  | NG PSI                  | text          | text          |
| Yes      | series tag     | ev_level1_evse_num      | EV Level1 EVSE Num      | text          | number        |
| Yes      | series tag     | ev_level2_evse_num      | EV Level2 EVSE Num      | text          | number        |
| Yes      | numeric metric | ev_dc_fast_count        | EV DC Fast Count        | number        | number        |
| Yes      | series tag     | ev_other_info           | EV Other Info           | text          | text          |
| Yes      | series tag     | ev_network              | EV Network              | text          | text          |
| Yes      | series tag     | ev_network_web          | EV Network Web          | url           | url           |
| Yes      | series tag     | geocode_status          | Geocode Status          | text          | text          |
| Yes      | numeric metric | latitude                | Latitude                | number        | number        |
| Yes      | numeric metric | longitude               | Longitude               | number        | number        |
| No       |                | date_last_confirmed     | Date Last Confirmed     | calendar_date | calendar_date |
| No       |                | id                      | ID                      | text          | text          |
| Yes      | series tag     | updated_at              | Updated At              | text          | text          |
| Yes      | series tag     | owner_type_code         | Owner Type Code         | text          | text          |
| Yes      | series tag     | federal_agency_id       | Federal Agency ID       | text          | text          |
| Yes      | series tag     | federal_agency_name     | Federal Agency Name     | text          | text          |
| No       |                | open_date               | Open Date               | calendar_date | calendar_date |
| Yes      | series tag     | hydrogen_status_link    | Hydrogen Status Link    | url           | url           |
| Yes      | series tag     | ng_vehicle_class        | NG Vehicle Class        | text          | text          |
| Yes      | series tag     | lpg_primary             | LPG Primary             | text          | text          |
| Yes      | series tag     | e85_blender_pump        | E85 Blender Pump        | text          | text          |
| Yes      | series tag     | ev_connector_types      | EV Connector Types      | text          | text          |
```

## Time Field

```ls
Value = expected_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = access_days_time,date_last_confirmed,id,open_date
```

## Data Commands

```ls
series e:bpkx-gmh7 d:2017-04-20T22:02:45.000Z t:status_code=E t:station_name="Clean Energy - Greenpoint - National Grid" t:zip=11211 t:owner_type_code=T t:ng_fill_type_code=Q t:state=NY t:ng_psi="3000 3600" t:ng_vehicle_class=MD t:geocode_status=GPS t:cards_accepted="D M V CleanEnergy FuelMan Voyager Wright_Exp" t:groups_with_access_code="Public - Credit card at all times" t:station_phone=866-809-4869 t:fuel_type_code=CNG t:city=Brooklyn t:intersection_directions="I-278/Brooklyn Queens Expy, exit onto Vandervoort Ave S, left onto Maspeth Ave, and the station is on the left" t:updated_at="2016-07-21 13:21:52 UTC" t:street_address="287 Maspeth Ave" m:longitude=-73.931508 m:latitude=40.718053

series e:bpkx-gmh7 d:2017-04-20T22:02:45.000Z t:status_code=E t:station_name="Clean Energy - Canarsie - National Grid" t:zip=11236 t:owner_type_code=T t:ng_fill_type_code=B t:state=NY t:ng_psi="3000 3600" t:ng_vehicle_class=MD t:geocode_status=GPS t:cards_accepted="D M V CleanEnergy FuelMan Voyager Wright_Exp" t:groups_with_access_code="Public - Credit card at all times" t:station_phone=866-809-4869 t:fuel_type_code=CNG t:city=Brooklyn t:intersection_directions="From Shore Pkwy, take Rockaway Pkwy N, left onto Ditmas Ave, and station is on the left" t:updated_at="2017-01-18 02:55:42 UTC" t:street_address="8424 Ditmas Ave" m:longitude=-73.9199237 m:latitude=40.6450546

series e:bpkx-gmh7 d:2017-04-20T22:02:45.000Z t:status_code=E t:zip=10001 t:station_name="Con Edison - W 29th St Service Center" t:intersection_directions="In Manhattan, W 29th Street and 12th Avenue." t:updated_at="2017-02-01 20:08:27 UTC" t:owner_type_code=T t:ng_fill_type_code=Q t:state=NY t:ng_psi=3600 t:ng_vehicle_class=MD t:geocode_status=200-8 t:groups_with_access_code="Public - Card key at all times" t:street_address="281 11th Ave" t:station_phone=212-643-3054 t:city="New York" t:fuel_type_code=CNG m:longitude=-74.005797 m:latitude=40.7528859
```

## Meta Commands

```ls
metric m:ev_dc_fast_count p:long l:"EV DC Fast Count" d:"For electric stations, the number of DC Fast Chargers" t:dataTypeName=number

metric m:latitude p:long l:Latitude d:"The latitude of the station's address (see the ""Geocode Status"" field for details on the latitude's accuracy)" t:dataTypeName=number

metric m:longitude p:long l:Longitude d:"The longitude of the station's address (see the ""Geocode Status"" field for details on the longitude's accuracy)" t:dataTypeName=number

entity e:bpkx-gmh7 l:"Alternative Fuel Stations in New York" t:attribution="U.S. Department of Energy" t:url=https://data.ny.gov/api/views/bpkx-gmh7

property e:bpkx-gmh7 t:meta.view v:id=bpkx-gmh7 v:category="Energy & Environment" v:attributionLink=http://www.afdc.energy.gov/locator/stations/ v:averageRating=0 v:name="Alternative Fuel Stations in New York" v:attribution="U.S. Department of Energy"

property e:bpkx-gmh7 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:bpkx-gmh7 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| fuel_type_code | station_name                              | street_address       | intersection_directions                                                                                                                                                         | city       | state | zip   | plus4 | station_phone | status_code | expected_date | groups_with_access_code           | access_days_time                                                         | cards_accepted                                        | bd_blends | ng_fill_type_code | ng_psi    | ev_level1_evse_num | ev_level2_evse_num | ev_dc_fast_count | ev_other_info | ev_network | ev_network_web | geocode_status | latitude   | longitude   | date_last_confirmed | id  | updated_at              | owner_type_code | federal_agency_id | federal_agency_name | open_date           | hydrogen_status_link | ng_vehicle_class | lpg_primary | e85_blender_pump | ev_connector_types | 
| ============== | ========================================= | ==================== | =============================================================================================================================================================================== | ========== | ===== | ===== | ===== | ============= | =========== | ============= | ================================= | ======================================================================== | ===================================================== | ========= | ================= | ========= | ================== | ================== | ================ | ============= | ========== | ============== | ============== | ========== | =========== | =================== | === | ======================= | =============== | ================= | =================== | =================== | ==================== | ================ | =========== | ================ | ================== | 
| CNG            | Clean Energy - Greenpoint - National Grid | 287 Maspeth Ave      | I-278/Brooklyn Queens Expy, exit onto Vandervoort Ave S, left onto Maspeth Ave, and the station is on the left                                                                  | Brooklyn   | NY    | 11211 |       | 866-809-4869  | E           |               | Public - Credit card at all times | 24 hours daily; call 866-809-4869 for Clean Energy card                  | D M V CleanEnergy FuelMan Voyager Wright_Exp          |           | Q                 | 3000 3600 |                    |                    |                  |               |            | [null, null]   | GPS            | 40.718053  | -73.931508  | 2016-04-04T00:00:00 | 108 | 2016-07-21 13:21:52 UTC | T               |                   |                     | 2016-07-15T00:00:00 | [null, null]         | MD               |             |                  |                    | 
| CNG            | Clean Energy - Canarsie - National Grid   | 8424 Ditmas Ave      | From Shore Pkwy, take Rockaway Pkwy N, left onto Ditmas Ave, and station is on the left                                                                                         | Brooklyn   | NY    | 11236 |       | 866-809-4869  | E           |               | Public - Credit card at all times | 24 hours daily; call 866-809-4869 for Clean Energy card                  | D M V CleanEnergy FuelMan Voyager Wright_Exp          |           | B                 | 3000 3600 |                    |                    |                  |               |            | [null, null]   | GPS            | 40.6450546 | -73.9199237 | 2017-01-11T00:00:00 | 112 | 2017-01-18 02:55:42 UTC | T               |                   |                     | 1988-01-15T00:00:00 | [null, null]         | MD               |             |                  |                    | 
| CNG            | Con Edison - W 29th St Service Center     | 281 11th Ave         | In Manhattan, W 29th Street and 12th Avenue.                                                                                                                                    | New York   | NY    | 10001 |       | 212-643-3054  | E           |               | Public - Card key at all times    | 24 hours daily; call 718-204-4048 to arrange for card key                |                                                       |           | Q                 | 3600      |                    |                    |                  |               |            | [null, null]   | 200-8          | 40.7528859 | -74.005797  | 2017-02-01T00:00:00 | 124 | 2017-02-01 20:08:27 UTC | T               |                   |                     | 2014-05-01T00:00:00 | [null, null]         | MD               |             |                  |                    | 
| CNG            | Con Edison - E 16th St Service Center     | 700 E 16th St        | In Manhattan, at Avenue C and E 16th. Broadway: Turn east onto 14th Street, then left onto 1st Avenue at 16th Street.                                                           | New York   | NY    | 10009 |       | 212-460-6708  | E           |               | Public - Card key at all times    | 24 hours daily; call 718-204-4048 to arrange for card key                |                                                       |           | Q                 | 3600      |                    |                    |                  |               |            | [null, null]   | 200-8          | 40.7295269 | -73.9744623 | 2017-02-01T00:00:00 | 125 | 2017-02-01 20:14:22 UTC | T               |                   |                     | 1998-01-15T00:00:00 | [null, null]         | MD               |             |                  |                    | 
| CNG            | Con Edison - Van Nest Service Center      | 1615 Bronxdale Ave   | Hutchinson River Parkway, exit onto E Tremont Avenue W, right onto Bronxdale Avenue, station on the left. From I-95, take Castle Hill Avenue exit north to E Tremont and Bronx. | Bronx      | NY    | 10462 |       | 718-904-4504  | E           |               | Public - Card key at all times    | 8am-6pm M-F, call 718-204-4048 to arrange for card key                   |                                                       |           | Q                 | 3000      |                    |                    |                  |               |            | [null, null]   | GPS            | 40.8441883 | -73.8615724 | 2017-02-01T00:00:00 | 129 | 2017-02-01 20:08:31 UTC | T               |                   |                     | 1998-01-15T00:00:00 | [null, null]         | MD               |             |                  |                    | 
| CNG            | Clean Energy - OGS Valhalla               | 7 Dana Rd            | Rt 9A & Dana Rd; Rt 87 to Exit 8 Rt 287 east), take Exit 2 to Rt 9A (north)                                                                                                     | Valhalla   | NY    | 10595 |       | 866-809-4869  | E           |               | Public - Credit card at all times | 24 hours daily; call 866-809-4869 for Clean Energy card                  | D M V CleanEnergy FuelMan Voyager Wright_Exp FleetOne |           | Q                 | 3000 3600 |                    |                    |                  |               |            | [null, null]   | 200-8          | 41.0812946 | -73.8181606 | 2017-04-06T00:00:00 | 131 | 2017-04-17 18:27:22 UTC | SG              |                   |                     | 2001-10-29T00:00:00 | [null, null]         | MD               |             |                  |                    | 
| CNG            | Con Edison - College Point Service Center | 124-15 31st Ave      | From I-678/Whitestone Expressway, exit at Linden Place, I-678 service road W, right onto 31st Avenue, station at intersection with College Point Boulevard.                     | Queens     | NY    | 11354 |       | 718-321-4608  | E           |               | Public - Card key at all times    | 7am-11pm M-F, 7am-3pm Sat-Sun; call 718-204-4048 to arrange for card key |                                                       |           | Q                 | 3000      |                    |                    |                  |               |            | [null, null]   | GPS            | 40.7694802 | -73.8462265 | 2017-02-01T00:00:00 | 132 | 2017-02-01 20:13:01 UTC | T               |                   |                     | 1998-01-15T00:00:00 | [null, null]         | MD               |             |                  |                    | 
| CNG            | Clean Energy - Brentwood - National Grid  | 1650 Islip Ave       | I-495, exit onto SR-111 S, and station is on the right in KeySpan yard                                                                                                          | Brentwood  | NY    | 11717 |       | 866-809-4869  | E           |               | Public - Credit card at all times | 24 hours daily; call 866-809-4869 for Clean Energy card                  | D M V CleanEnergy FuelMan Voyager Wright_Exp          |           | Q                 | 3000 3600 |                    |                    |                  |               |            | [null, null]   | 200-8          | 40.7842714 | -73.219801  | 2017-01-11T00:00:00 | 448 | 2017-01-18 02:31:26 UTC | T               |                   |                     | 1995-02-15T00:00:00 | [null, null]         | MD               |             |                  |                    | 
| CNG            | Clean Energy - Hicksville - National Grid | 175 E Old Country Rd | From I-495 exit onto SR-107 S, left onto E Old Country Rd, and the station is on the right in KeySpan yard                                                                      | Hicksville | NY    | 11801 |       | 866-809-4869  | E           |               | Public - Credit card at all times | 24 hours daily; call 866-809-4869 for Clean Energy card                  | D M V CleanEnergy FuelMan Voyager Wright_Exp          |           | Q                 | 3000      |                    |                    |                  |               |            | [null, null]   | 200-8          | 40.7655928 | -73.5120693 | 2016-04-04T00:00:00 | 449 | 2016-07-21 13:25:13 UTC | T               |                   |                     | 1992-07-15T00:00:00 | [null, null]         | MD               |             |                  |                    | 
| CNG            | Clean Energy - Albany - National Grid     | 1125 Broadway        | Just south and west of I-90/I-787 Interchange, between Loudonville Rd and N 1st St                                                                                              | Menands    | NY    | 12204 |       | 866-809-4869  | E           |               | Public - Credit card at all times | 24 hours daily; call 866-809-4869 for Clean Energy card                  | D M V CleanEnergy FuelMan Voyager Wright_Exp          |           | Q                 | 3600      |                    |                    |                  |               |            | [null, null]   | 200-8          | 42.667569  | -73.739345  | 2017-03-03T00:00:00 | 703 | 2017-03-03 19:41:20 UTC | T               |                   |                     | 2011-08-15T00:00:00 | [null, null]         | MD               |             |                  |                    | 
```