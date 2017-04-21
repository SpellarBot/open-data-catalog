# NYCHA Development Data Book

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nycha-development-data-book-9e35e) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/evjd-dqpz) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/evjd-dqpz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/evjd-dqpz/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | evjd-dqpz |
| Name | NYCHA Development Data Book |
| Attribution | New York City Housing Authority (NYCHA) |
| Category | Housing & Development |
| Tags | nycha, nyc housing, developments, programs, statistics, locations |
| Created | 2013-03-28T19:10:55Z |
| Publication Date | 2016-09-15T21:54:47Z |

## Description

Contains the main body of the ?Development Data Book? as of January 1, 2016. The Development Data Book lists all of the Authority's Developments alphabetically and includes information on the development identification numbers, program and construction type, number of apartments and rental rooms, population, number of buildings and stories, street boundaries, and political districts.

## Columns

```ls
| Included | Schema Type    | Field Name                                | Name                                      | Data Type | Render Type |
| ======== | ============== | ========================================= | ========================================= | ========= | =========== |
| No       | time           | :updated_at                               | updated_at                                | meta_data | meta_data   |
| Yes      | series tag     | data_as_of                                | DATA AS OF                                | text      | text        |
| Yes      | series tag     | development                               | DEVELOPMENT                               | text      | text        |
| Yes      | series tag     | hud_amp_                                  | HUD AMP#                                  | text      | text        |
| Yes      | series tag     | tds_                                      | TDS#                                      | text      | text        |
| Yes      | series tag     | consolidated_tds_                         | CONSOLIDATED TDS#                         | text      | text        |
| Yes      | series tag     | development_edp_                          | DEVELOPMENT EDP#                          | text      | text        |
| Yes      | series tag     | operating_edp_                            | OPERATING EDP#                            | text      | text        |
| Yes      | series tag     | hud__                                     | HUD #                                     | text      | text        |
| Yes      | series tag     | program                                   | PROGRAM                                   | text      | text        |
| Yes      | series tag     | method                                    | METHOD                                    | text      | text        |
| Yes      | series tag     | type                                      | TYPE                                      | text      | text        |
| Yes      | numeric metric | number_of_section_8_transition_apartments | NUMBER OF SECTION 8 TRANSITION APARTMENTS | number    | text        |
| Yes      | numeric metric | number_of_current_apartments              | NUMBER OF CURRENT APARTMENTS              | number    | text        |
| Yes      | numeric metric | total_number_of_apartments                | TOTAL NUMBER OF APARTMENTS                | number    | text        |
| Yes      | numeric metric | number_of_rental_rooms                    | NUMBER OF RENTAL ROOMS                    | number    | text        |
| Yes      | numeric metric | avg_no_r_r_per_apartment                  | AVG NO R/R PER APARTMENT                  | number    | text        |
| Yes      | numeric metric | population_section_8_transition           | POPULATION SECTION 8 TRANSITION           | number    | text        |
| Yes      | numeric metric | population_public_housing                 | POPULATION PUBLIC HOUSING                 | number    | text        |
| Yes      | numeric metric | total_population                          | TOTAL POPULATION                          | number    | text        |
| Yes      | numeric metric | number_of_residential_bldgs               | NUMBER OF RESIDENTIAL BLDGS               | number    | text        |
| Yes      | numeric metric | number_of_non_residential_bldgs           | NUMBER OF NON-RESIDENTIAL BLDGS           | number    | text        |
| Yes      | numeric metric | number_of_stairhalls                      | NUMBER OF STAIRHALLS                      | number    | text        |
| Yes      | series tag     | number_of_stories                         | NUMBER OF STORIES                         | text      | text        |
| Yes      | numeric metric | total_area_sq_ft                          | TOTAL AREA SQ FT                          | number    | text        |
| Yes      | numeric metric | acres                                     | ACRES                                     | number    | text        |
| Yes      | numeric metric | net_dev_area_sq_ft                        | NET DEV AREA SQ FT                        | number    | text        |
| Yes      | numeric metric | excluding_park_acres                      | EXCLUDING PARK ACRES                      | number    | text        |
| Yes      | numeric metric | bldg_coverage_sq_ft                       | BLDG COVERAGE SQ FT                       | number    | text        |
| Yes      | numeric metric | cubage_cu_ft                              | CUBAGE CU FT                              | number    | text        |
| Yes      | numeric metric | bldg_coverage__                           | BLDG COVERAGE %                           | number    | text        |
| Yes      | numeric metric | density                                   | DENSITY                                   | number    | text        |
| Yes      | numeric metric | development_cost                          | DEVELOPMENT COST                          | money     | text        |
| Yes      | numeric metric | per_rental_room                           | PER RENTAL ROOM                           | money     | text        |
| Yes      | numeric metric | avg_monthly_gross_rent                    | AVG MONTHLY GROSS RENT                    | money     | text        |
| Yes      | series tag     | location_street_a                         | LOCATION STREET A                         | text      | text        |
| Yes      | series tag     | location_street_b                         | LOCATION STREET B                         | text      | text        |
| Yes      | series tag     | location_street_c                         | LOCATION STREET C                         | text      | text        |
| Yes      | series tag     | location_street_d                         | LOCATION STREET D                         | text      | text        |
| Yes      | series tag     | borough                                   | BOROUGH                                   | text      | text        |
| Yes      | series tag     | community_distirct                        | COMMUNITY DISTIRCT                        | text      | text        |
| Yes      | series tag     | us_congressional_district                 | US CONGRESSIONAL DISTRICT                 | text      | text        |
| Yes      | series tag     | ny_state_senate_district                  | NY STATE SENATE DISTRICT                  | text      | text        |
| Yes      | series tag     | ny_state_assembly_district                | NY STATE ASSEMBLY DISTRICT                | text      | text        |
| Yes      | series tag     | ny_city_council_district                  | NY CITY COUNCIL DISTRICT                  | text      | text        |
| No       |                | completion_date                           | COMPLETION DATE                           | text      | text        |
| Yes      | series tag     | federalized_development                   | FEDERALIZED DEVELOPMENT                   | text      | text        |
| Yes      | series tag     | senior_development                        | SENIOR DEVELOPMENT                        | text      | text        |
| Yes      | series tag     | electricity_paid_by_residents             | ELECTRICITY PAID BY RESIDENTS             | text      | text        |
| Yes      | series tag     | private_management                        | PRIVATE MANAGEMENT                        | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = completion_date
```

## Data Commands

```ls
series e:evjd-dqpz d:2016-09-15T21:53:18.000Z t:tds_=180 t:ny_state_senate_district=32 t:data_as_of=1/1/16 t:development="1010 EAST 178TH STREET" t:borough=BRONX t:type="NEW CONST" t:development_edp_=289 t:community_distirct=6 t:us_congressional_district=15 t:location_street_a="E TREMONT AVE" t:hud_=NY005090 t:location_street_c="E 178TH ST" t:location_street_b="BRYANT AVE" t:operating_edp_=289 t:location_street_d="BOSTON RD" t:program=FEDERAL t:ny_state_assembly_district=87 t:ny_city_council_district=15 t:method=CONVENTIONAL t:consolidated_tds_=133 t:number_of_stories=21 t:hud_amp_=NY005011330 m:population_public_housing=462 m:cubage_cu_ft=1841787 m:density=228.71 m:bldg_coverage_sq_ft=14961 m:avg_monthly_gross_rent=439.24 m:number_of_residential_bldgs=1 m:total_number_of_apartments=220 m:net_dev_area_sq_ft=88172 m:number_of_stairhalls=1 m:number_of_non_residential_bldgs=0 m:avg_no_r_r_per_apartment=4.21 m:number_of_rental_rooms=918 m:total_population=462 m:total_area_sq_ft=88172 m:per_rental_room=5341 m:development_cost=5031405 m:number_of_current_apartments=218 m:excluding_park_acres=2.02 m:acres=2.02 m:bldg_coverage__=16.969999313354492

series e:evjd-dqpz d:2016-09-15T21:53:18.000Z t:tds_=242 t:ny_state_senate_district=20 t:data_as_of=1/1/16 t:development="104-14 TAPSCOTT STREET" t:borough=BROOKLYN t:type="NEW CONST" t:development_edp_=361 t:community_distirct=16 t:us_congressional_district=9 t:location_street_a="TAPSCOTT ST" t:hud_=NY005174 t:location_street_c="SUTTER AVE" t:location_street_b="UNION ST" t:operating_edp_=283 t:location_street_d="BLAKE AVE" t:program=FEDERAL t:ny_state_assembly_district=55 t:ny_city_council_district=41 t:method=TURNKEY t:consolidated_tds_=167 t:number_of_stories=4 t:hud_amp_=NY005011670 m:population_public_housing=69 m:cubage_cu_ft=351238 m:density=300 m:bldg_coverage_sq_ft=6983 m:avg_monthly_gross_rent=443.53 m:number_of_residential_bldgs=1 m:total_number_of_apartments=30 m:net_dev_area_sq_ft=10000 m:number_of_stairhalls=1 m:number_of_non_residential_bldgs=0 m:avg_no_r_r_per_apartment=4.37 m:number_of_rental_rooms=131 m:total_population=69 m:total_area_sq_ft=10000 m:per_rental_room=6505 m:development_cost=839110 m:number_of_current_apartments=30 m:excluding_park_acres=0.23 m:acres=0.23 m:bldg_coverage__=69.83000183105469

series e:evjd-dqpz d:2016-09-15T21:53:18.000Z t:tds_=233 t:ny_state_senate_district=32 t:data_as_of=1/1/16 t:development="1162-1176 WASHINGTON AVENUE" t:borough=BRONX t:type=REHAB t:development_edp_=354 t:community_distirct=3 t:us_congressional_district=15 t:location_street_a="E 167TH ST" t:hud_=NY005138 t:location_street_c="THIRD AVE" t:location_street_b="E 168TH ST" t:operating_edp_=344 t:location_street_d="WASHINGTON AVE" t:program=FEDERAL t:ny_state_assembly_district=79 t:ny_city_council_district=16 t:method=TURNKEY t:consolidated_tds_=308 t:number_of_stories=6 t:hud_amp_=NY005013080 m:population_public_housing=191 m:cubage_cu_ft=851926 m:density=434.09 m:bldg_coverage_sq_ft=12231 m:avg_monthly_gross_rent=471.03 m:number_of_residential_bldgs=1 m:total_number_of_apartments=66 m:net_dev_area_sq_ft=18987 m:number_of_stairhalls=1 m:number_of_non_residential_bldgs=0 m:avg_no_r_r_per_apartment=4.52 m:number_of_rental_rooms=293.5 m:total_population=191 m:total_area_sq_ft=18987 m:per_rental_room=7302 m:development_cost=2205187 m:number_of_current_apartments=65 m:excluding_park_acres=0.44 m:acres=0.44 m:bldg_coverage__=64.41999816894531
```

## Meta Commands

```ls
metric m:number_of_section_8_transition_apartments p:integer l:"NUMBER OF SECTION 8 TRANSITION APARTMENTS" d:"The total number of apartments transitioned to the Section 8 Program in the LLC1 and LLC2 developments." t:dataTypeName=number

metric m:number_of_current_apartments p:long l:"NUMBER OF CURRENT APARTMENTS" d:"The number of apartments available for occupancy in the development as per the January 1, 2012. Dwelling Unit Inventory which is used to track the number of apartments on the rent roll. Units temporarily vacant and not permanently removed from the rent ro" t:dataTypeName=number

metric m:total_number_of_apartments p:long l:"TOTAL NUMBER OF APARTMENTS" d:"The total number of apartments at the development including the Section 8 Transition apartments at the LLC1 and LLC2 developments." t:dataTypeName=number

metric m:number_of_rental_rooms p:float l:"NUMBER OF RENTAL ROOMS" d:"Rental room count per apartment is equal to 2 ? plus the number of bedrooms. The number of rental rooms includes balconies and half-baths as half-rooms." t:dataTypeName=number

metric m:avg_no_r_r_per_apartment p:float l:"AVG NO R/R PER APARTMENT" d:"The average number of rental rooms per apartment is the number of rental rooms divided by the number of current apartments. The Section 8 Apartments in the LLC1 & LLC2 Developments are included." t:dataTypeName=number

metric m:population_section_8_transition p:integer l:"POPULATION SECTION 8 TRANSITION" d:"The number of persons living in the Section 8 Transition apartments in the LLC1 and LLC2 developments based on the January 1, 2012 Resident Data Files." t:dataTypeName=number

metric m:population_public_housing p:long l:"POPULATION PUBLIC HOUSING" d:"The number of persons living in the public housing units in the LLC1 and LLC2 developments based on the January 1, 2012 Resident Data Files. The residents living in the Section 8 Transition apartments in the LLC1and LLC2 developments are not included in t" t:dataTypeName=number

metric m:total_population p:long l:"TOTAL POPULATION" d:"The total number of persons living at the development based on the January 1, 2012 Resident Data Files including the Section 8 Transition apartments in the LLC1 and LLC2 developments." t:dataTypeName=number

metric m:number_of_residential_bldgs p:integer l:"NUMBER OF RESIDENTIAL BLDGS" d:"The number of residential buildings on the grounds that are used for dwelling units." t:dataTypeName=number

metric m:number_of_non_residential_bldgs p:integer l:"NUMBER OF NON-RESIDENTIAL BLDGS" d:"The number of non-residential buildings at a development." t:dataTypeName=number

metric m:number_of_stairhalls p:integer l:"NUMBER OF STAIRHALLS" d:"The number of individual entrances in each Development." t:dataTypeName=number

metric m:total_area_sq_ft p:long l:"TOTAL AREA SQ FT" d:"This number includes land acquired and developed as part of the development for a park or playground to be operated and maintained by the NYC Department of Parks. At State and City Developments, the park or playground is owned by the City of New York. At" t:dataTypeName=number

metric m:acres p:float l:ACRES d:"The land area of the development including buildings and grounds is shown in acres (one acre equals 43,560 square feet)." t:dataTypeName=number

metric m:net_dev_area_sq_ft p:long l:"NET DEV AREA SQ FT" d:"This is square feet at a development less the land set aside for a park or playground. For the majority of developments this figure is the same acreage." t:dataTypeName=number

metric m:excluding_park_acres p:float l:"EXCLUDING PARK ACRES" d:"This is the number of acres at a development less the land set aside for a park or playground. For the majority of developments this figure is the same as ?acres?." t:dataTypeName=number

metric m:bldg_coverage_sq_ft p:long l:"BLDG COVERAGE SQ FT" d:"The total ground floor area of the building footprints of a development." t:dataTypeName=number

metric m:cubage_cu_ft p:long l:"CUBAGE CU FT" d:"Cubic Space (height x length x width of residential buildings) in all the buildings at a development, expressed as cubic feet." t:dataTypeName=number

metric m:bldg_coverage__ p:float l:"BLDG COVERAGE %" d:"This is the building coverage, divided by a development?s total area in square feet. This figure is presented as a percentage." t:dataTypeName=number

metric m:density p:float l:DENSITY d:"Measure of development density as represented by the number of persons per acre." t:dataTypeName=number

metric m:development_cost p:long l:"DEVELOPMENT COST" d:"The sum of the land cost, construction cost and site improvement cost, including fees for architects and engineers at the time of original construction." t:dataTypeName=money

metric m:per_rental_room p:long l:"PER RENTAL ROOM" d:"Cost to develop the property divided by the number of rental rooms at the time of original construction." t:dataTypeName=money

metric m:avg_monthly_gross_rent p:long l:"AVG MONTHLY GROSS RENT" d:"This is the average gross monthly rent of the households in each development as of January 1, 2012. The average tenant share of rent for the Section 8 households in the LLC1 & LLC2 Developments is included." t:dataTypeName=money

entity e:evjd-dqpz l:"NYCHA Development Data Book" t:attribution="New York City Housing Authority (NYCHA)" t:url=https://data.cityofnewyork.us/api/views/evjd-dqpz

property e:evjd-dqpz t:meta.view v:id=evjd-dqpz v:category="Housing & Development" v:attributionLink=http://www.nyc.gov/html/nycha/html/resources/development-data-book.shtml v:averageRating=0 v:name="NYCHA Development Data Book" v:attribution="New York City Housing Authority (NYCHA)"

property e:evjd-dqpz t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:evjd-dqpz t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | data_as_of | development                 | hud_amp_    | tds_ | consolidated_tds_ | development_edp_ | operating_edp_ | hud__    | program            | method       | type      | number_of_section_8_transition_apartments | number_of_current_apartments | total_number_of_apartments | number_of_rental_rooms | avg_no_r_r_per_apartment | population_section_8_transition | population_public_housing | total_population | number_of_residential_bldgs | number_of_non_residential_bldgs | number_of_stairhalls | number_of_stories | total_area_sq_ft | acres              | net_dev_area_sq_ft | excluding_park_acres | bldg_coverage_sq_ft | cubage_cu_ft | bldg_coverage__ | density            | development_cost | per_rental_room | avg_monthly_gross_rent | location_street_a  | location_street_b  | location_street_c | location_street_d | borough   | community_distirct | us_congressional_district | ny_state_senate_district | ny_state_assembly_district | ny_city_council_district | completion_date | federalized_development | senior_development | electricity_paid_by_residents | private_management | 
| =========== | ========== | =========================== | =========== | ==== | ================= | ================ | ============== | ======== | ================== | ============ | ========= | ========================================= | ============================ | ========================== | ====================== | ======================== | =============================== | ========================= | ================ | =========================== | =============================== | ==================== | ================= | ================ | ================== | ================== | ==================== | =================== | ============ | =============== | ================== | ================ | =============== | ====================== | ================== | ================== | ================= | ================= | ========= | ================== | ========================= | ======================== | ========================== | ======================== | =============== | ======================= | ================== | ============================= | ================== | 
| 1473976398  | 1/1/16     | 1010 EAST 178TH STREET      | NY005011330 | 180  | 133               | 289              | 289            | NY005090 | FEDERAL            | CONVENTIONAL | NEW CONST |                                           | 218                          | 220                        | 918.0                  | 4.21                     |                                 | 462                       | 462              | 1                           | 0                               | 1                    | 21                | 88,172           | 2.02               | 88,172             | 2.02                 | 14,961              | 1,841,787    | 16.97%          | 228.71             | $5,031,405       | $5,341          | $439.24                | E TREMONT AVE      | BRYANT AVE         | E 178TH ST        | BOSTON RD         | BRONX     | 6                  | 15                        | 32                       | 87                         | 15                       | 3/31/71         |                         |                    |                               |                    | 
| 1473976398  | 1/1/16     | 104-14 TAPSCOTT STREET      | NY005011670 | 242  | 167               | 361              | 283            | NY005174 | FEDERAL            | TURNKEY      | NEW CONST |                                           | 30                           | 30                         | 131.0                  | 4.37                     |                                 | 69                        | 69               | 1                           | 0                               | 1                    | 4                 | 10,000           | 0.23               | 10,000             | 0.23                 | 6,983               | 351,238      | 69.83%          | 300                | $839,110         | $6,505          | $443.53                | TAPSCOTT ST        | UNION ST           | SUTTER AVE        | BLAKE AVE         | BROOKLYN  | 16                 | 9                         | 20                       | 55                         | 41                       | 10/31/72        |                         |                    |                               |                    | 
| 1473976398  | 1/1/16     | 1162-1176 WASHINGTON AVENUE | NY005013080 | 233  | 308               | 354              | 344            | NY005138 | FEDERAL            | TURNKEY      | REHAB     |                                           | 65                           | 66                         | 293.5                  | 4.5199999999999996       |                                 | 191                       | 191              | 1                           | 0                               | 1                    | 6                 | 18,987           | 0.44               | 18,987             | 0.44                 | 12,231              | 851,926      | 64.42%          | 434.09             | $2,205,187       | $7,302          | $471.03                | E 167TH ST         | E 168TH ST         | THIRD AVE         | WASHINGTON AVE    | BRONX     | 3                  | 15                        | 32                       | 79                         | 16                       | 12/31/75        |                         |                    |                               |                    | 
| 1473976398  | 1/1/16     | 131 SAINT NICHOLAS AVENUE   | NY005010970 | 154  | 097               | 264              | 261            | NY005065 | FEDERAL            | CONVENTIONAL | NEW CONST |                                           | 98                           | 100                        | 386.0                  | 3.94                     |                                 | 171                       | 171              | 1                           | 0                               | 1                    | 17                | 29,359           | 0.67               | 29,359             | 0.67                 | 5,759               | 771,591      | 19.62%          | 255.22             | $1,880,013       | $4,694          | $480.30                | SAINT NICHOLAS AVE | W 116TH ST         | W 117TH ST        |                   | MANHATTAN | 10                 | 13                        | 30                       | 70                         | 9                        | 3/31/65         |                         |                    |                               |                    | 
| 1473976398  | 1/1/16     | 1471 WATSON AVENUE          | NY005010670 | 214  | 067               | 332              | 222            | NY005162 | FEDERAL            | TURNKEY      | NEW CONST |                                           | 96                           | 96                         | 386.0                  | 4.0199999999999996       |                                 | 166                       | 166              | 1                           | 0                               | 1                    | 6                 | 39,937           | 0.92               | 39,937             | 0.92                 | 13,337              | 810,629      | 33.40%          | 180.43             | $2,278,928       | $5,814          | $403.10                | WATSON AVE         | COLGATE AVE        | EVERGREEN AVE     |                   | BRONX     | 9                  | 15                        | 32                       | 85                         | 17                       | 12/31/70        |                         |                    |                               |                    | 
| 1473976398  | 1/1/16     | 154 WEST 84TH STREET        | NY005013590 | 359  | 359               | 840              | 840            | NY005270 | FEDERAL            | TURNKEY      | NEW CONST |                                           | 35                           | 35                         | 157.5                  | 4.5                      |                                 | 83                        | 83               | 1                           | 0                               | 1                    | 7                 | 9,621            | 0.22               | 9,621              | 0.22                 | 5,774               | 361,857      | 60.01%          | 377.27             | $4,503,296       | $28,412         | $534.00                | AMSTERDAM AVE      | W 84TH ST          | COLUMBUS AVE      |                   | MANHATTAN | 7                  | 10                        | 29                       | 69                         | 6                        | 3/31/96         |                         |                    | YES                           | YES                | 
| 1473976398  | 1/1/16     | 303 VERNON AVENUE           | NY005010730 | 156  | 073               | 267              | 267            | NY005068 | FEDERAL            | CONVENTIONAL | NEW CONST |                                           | 234                          | 234                        | 1101.0                 | 4.71                     |                                 | 552                       | 552              | 1                           | 0                               | 1                    | 24                | 110,000          | 2.5299999999999998 | 110,000            | 2.5299999999999998   | 11,311              | 2,207,369    | 10.28%          | 218.18             | $4,703,702       | $4,272          | $489.27                | VERNON AVE         | MARCUS GARVEY BLVD | MYRTLE AVE        |                   | BROOKLYN  | 3                  | 8                         | 18                       | 54                         | 36                       | 5/31/67         |                         |                    |                               |                    | 
| 1473976398  | 1/1/16     | 335 EAST 111TH STREET       | NY005010640 | 203  | 064               | 320              | 219            | NY005126 | FEDERAL            | TURNKEY      | NEW CONST |                                           | 66                           | 66                         | 259.0                  | 3.92                     |                                 | 118                       | 118              | 1                           | 0                               | 1                    | 6                 | 20,205           | 0.46               | 20,205             | 0.46                 | 9,143               | 530,550      | 45.25%          | 256.52             | $1,241,825       | $4,651          | $423.00                | SECOND AVE         | E 111TH ST         | FIRST AVE         | E 112TH ST        | MANHATTAN | 11                 | 13                        | 29                       | 68                         | 8                        | 6/30/69         |                         |                    |                               |                    | 
| 1473976398  | 1/1/16     | 344 EAST 28TH STREET        | NY005021850 | 185  | 153               | 452              | 452            | NY005374 | MIXED FINANCE/LLC2 | CONVENTIONAL | NEW CONST | 56                                        | 225                          | 225                        | 985.5                  | 4.38                     | 132                             | 314                       | 446              | 1                           | 0                               | 1                    | 26                | 44,644           | 1.02               | 44,644             | 1.02                 | 7,889               | 1,946,457    | 17.67%          | 437.25             | $4,980,000       | $5,053          | $441.98                | E 27TH ST          | NEW ST             | E 28TH ST         | FIRST AVE         | MANHATTAN | 6                  | 12                        | 27                       | 74                         | 2                        | 3/31/71         |                         |                    |                               |                    | 
| 1473976398  | 1/1/16     | 45 ALLEN STREET             | NY005011000 | 265  | 100               | 380              | 312            | NY005186 | FEDERAL            | TURNKEY      | NEW CONST |                                           | 106                          | 107                        | 533.0                  | 5.03                     |                                 | 241                       | 241              | 1                           | 1                               | 2                    | 14                | 39,609           | 0.91               | 39,609             | 0.91                 | 8,031               | 950,162      | 20.28%          | 264.83999999999997 | $4,290,021       | $7,981          | $657.66                | GRAND ST           | ALLEN ST           | HESTER ST         | ELDRIDGE ST       | MANHATTAN | 3                  | 7                         | 26                       | 65                         | 1                        | 7/31/74         |                         |                    |                               |                    | 
```