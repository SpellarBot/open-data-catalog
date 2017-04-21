# Housing New York Units by Building

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/housing-new-york-units-by-building) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/hg8x-zxpr) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/hg8x-zxpr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/hg8x-zxpr/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | hg8x-zxpr |
| Name | Housing New York Units by Building |
| Attribution | Department of Housing Preservation and Development (HPD) |
| Category | Housing & Development |
| Tags | housing, hpd, development, building |
| Created | 2016-12-13T18:44:07Z |
| Publication Date | 2017-01-18T23:19:50Z |

## Description

The Department of Housing Preservation and Development (HPD) reports on buildings, units, and projects that began after January 1, 2014 and are counted towards the Housing New York plan. The Housing New York Units by Building file presents this data by building, and includes building-level data, such as house number, street name, BBL, and BIN for each building in a project.  The unit counts are provided by building. For additional documentation, including a data dictionary, review the attachments in the ?About this Dataset? section of the Primer landing page.

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                          | Data Type     | Render Type   |
| ======== | ============== | ============================= | ============================= | ============= | ============= |
| Yes      | series tag     | project_id                    | Project ID                    | text          | text          |
| Yes      | series tag     | project_name                  | Project Name                  | text          | text          |
| Yes      | time           | project_start_date            | Project Start Date            | calendar_date | calendar_date |
| No       |                | project_completion_date       | Project Completion Date       | calendar_date | calendar_date |
| Yes      | series tag     | building_id                   | Building ID                   | text          | number        |
| Yes      | series tag     | house_number                  | House Number                  | text          | text          |
| Yes      | series tag     | street_name                   | Street Name                   | text          | text          |
| Yes      | series tag     | borough                       | Borough                       | text          | text          |
| Yes      | numeric metric | bbl                           | BBL                           | number        | number        |
| Yes      | numeric metric | bin                           | BIN                           | number        | number        |
| Yes      | numeric metric | community_board               | Community Board               | number        | number        |
| Yes      | series tag     | council_district              | Council District              | text          | number        |
| Yes      | series tag     | census_tract                  | Census Tract                  | text          | text          |
| Yes      | series tag     | neighborhood_tabulation_area  | Neighborhood Tabulation Area  | text          | text          |
| No       |                | latitude                      | Latitude                      | number        | number        |
| No       |                | longitude                     | Longitude                     | number        | number        |
| No       |                | latitude_internal             | Latitude (Internal)           | number        | number        |
| No       |                | longitude_internal            | Longitude (Internal)          | number        | number        |
| No       |                | building_completion_date      | Building Completion Date      | calendar_date | calendar_date |
| Yes      | series tag     | reporting_construction_type   | Reporting Construction Type   | text          | text          |
| Yes      | series tag     | extended_affordability_status | Extended Affordability Status | text          | text          |
| Yes      | series tag     | prevailing_wage_status        | Prevailing Wage Status        | text          | text          |
| Yes      | numeric metric | extremely_low_income_units    | Extremely Low Income Units    | number        | number        |
| Yes      | numeric metric | very_low_income               | Very Low Income               | number        | number        |
| Yes      | numeric metric | low_income_units              | Low Income Units              | number        | number        |
| Yes      | numeric metric | moderate_income               | Moderate Income               | number        | number        |
| Yes      | numeric metric | middle_income                 | Middle Income                 | number        | number        |
| Yes      | numeric metric | other                         | Other                         | number        | number        |
| Yes      | numeric metric | counted_rental_units          | Counted Rental Units          | number        | number        |
| Yes      | numeric metric | counted_homeownership_units   | Counted Homeownership Units   | number        | number        |
| Yes      | numeric metric | all_counted_units             | All Counted Units             | number        | number        |
| Yes      | numeric metric | total_units                   | Total Units                   | number        | number        |
```

## Time Field

```ls
Value = project_start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = project_completion_date,latitude,longitude,latitude_internal,longitude_internal,building_completion_date
```

## Data Commands

```ls
series e:hg8x-zxpr d:2016-12-30T00:00:00.000Z t:neighborhood_tabulation_area=BX17 t:house_number=1880 t:extended_affordability_status="Not Extended Affordability" t:project_name="ALEMBIC. 1880 BOSTON ROAD" t:reporting_construction_type="New Construction" t:building_id=972249 t:project_id=58966 t:prevailing_wage_status="Prevailing Wage" t:street_name="BOSTON ROAD" t:borough=Bronx t:council_district=17 t:census_tract=359 m:bbl=2030040020 m:other=1 m:middle_income=0 m:counted_rental_units=168 m:extremely_low_income_units=167 m:moderate_income=0 m:all_counted_units=168 m:very_low_income=0 m:low_income_units=0 m:community_board=206 m:total_units=168 m:counted_homeownership_units=0

series e:hg8x-zxpr d:2016-12-30T00:00:00.000Z t:neighborhood_tabulation_area=BX27 t:house_number=1000 t:extended_affordability_status="Not Extended Affordability" t:project_name="FOX STREET PRC" t:reporting_construction_type="New Construction" t:building_id=971150 t:project_id=60249 t:prevailing_wage_status="Non Prevailing Wage" t:street_name="FOX STREET" t:borough=Bronx t:council_district=17 t:census_tract=159 m:other=1 m:middle_income=0 m:counted_rental_units=120 m:extremely_low_income_units=0 m:moderate_income=0 m:all_counted_units=120 m:very_low_income=60 m:low_income_units=59 m:community_board=202 m:total_units=120 m:counted_homeownership_units=0

series e:hg8x-zxpr d:2016-12-30T00:00:00.000Z t:neighborhood_tabulation_area=BX27 t:house_number=960 t:extended_affordability_status="Not Extended Affordability" t:project_name="FOX STREET PRC" t:reporting_construction_type="New Construction" t:building_id=975072 t:project_id=60249 t:prevailing_wage_status="Non Prevailing Wage" t:street_name="SIMPSON STREET" t:borough=Bronx t:council_district=17 t:census_tract=159 m:bbl=2027240103 m:other=0 m:middle_income=0 m:counted_rental_units=80 m:extremely_low_income_units=8 m:moderate_income=0 m:all_counted_units=80 m:very_low_income=32 m:low_income_units=40 m:community_board=202 m:total_units=80 m:counted_homeownership_units=0
```

## Meta Commands

```ls
metric m:bbl p:long l:BBL d:"The BBL (Borough, Block, and Lot) is a unique identifier for each tax lot in the City." t:dataTypeName=number

metric m:bin p:integer l:BIN d:"The BIN (Building Identification Number) is a unique identifier for each building in the City." t:dataTypeName=number

metric m:community_board p:integer l:"Community Board" d:"The Community Board field indicates the New York City Community District where the building is located." t:dataTypeName=number

metric m:extremely_low_income_units p:integer l:"Extremely Low Income Units" d:"Extremely Low Income Units are units with rents that are affordable to households earning 0 to 30% of the area median income (AMI)." t:dataTypeName=number

metric m:very_low_income p:integer l:"Very Low Income" d:"Very Low Income Units are units with rents that are affordable to households earning 31 to 50% of the area median income (AMI)." t:dataTypeName=number

metric m:low_income_units p:integer l:"Low Income Units" d:"Low Income Units are units with rents that are affordable to households earning 51 to 80% of the area median income (AMI)." t:dataTypeName=number

metric m:moderate_income p:integer l:"Moderate Income" d:"Moderate Income Units are units with rents that are affordable to households earning 81 to 120% of the area median income (AMI)." t:dataTypeName=number

metric m:middle_income p:integer l:"Middle Income" d:"Middle Income Units are units with rents that are affordable to households earning 121 to 165% of the area median income (AMI)." t:dataTypeName=number

metric m:other p:integer l:Other d:"Other Units are units reserved for building superintendents." t:dataTypeName=number

metric m:counted_rental_units p:integer l:"Counted Rental Units" d:"Counted Rental Units are the units in the building, counted toward the Housing New York plan, where assistance has been provided to landlords in exchange for a requirement for affordable units." t:dataTypeName=number

metric m:counted_homeownership_units p:integer l:"Counted Homeownership Units" d:"Counted Homeownership Units are the units in the building, counted toward the Housing New York Plan, where assistance has been provided directly to homeowners." t:dataTypeName=number

metric m:all_counted_units p:integer l:"All Counted Units" d:"The Counted Units field indicates the total number of affordable units, counted towards the Housing New York plan, that are in the building." t:dataTypeName=number

metric m:total_units p:integer l:"Total Units" d:"The Total Units field indicates the total number of units, affordable and market rate, in each building." t:dataTypeName=number

entity e:hg8x-zxpr l:"Housing New York Units by Building" t:attribution="Department of Housing Preservation and Development (HPD)" t:url=https://data.cityofnewyork.us/api/views/hg8x-zxpr

property e:hg8x-zxpr t:meta.view v:id=hg8x-zxpr v:category="Housing & Development" v:averageRating=0 v:name="Housing New York Units by Building" v:attribution="Department of Housing Preservation and Development (HPD)"

property e:hg8x-zxpr t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:hg8x-zxpr t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| project_id | project_name                     | project_start_date  | project_completion_date | building_id | house_number | street_name     | borough   | bbl        | bin     | community_board | council_district | census_tract | neighborhood_tabulation_area | latitude    | longitude    | latitude_internal | longitude_internal | building_completion_date | reporting_construction_type | extended_affordability_status | prevailing_wage_status | extremely_low_income_units | very_low_income | low_income_units | moderate_income | middle_income | other | counted_rental_units | counted_homeownership_units | all_counted_units | total_units | 
| ========== | ================================ | =================== | ======================= | =========== | ============ | =============== | ========= | ========== | ======= | =============== | ================ | ============ | ============================ | =========== | ============ | ================= | ================== | ======================== | =========================== | ============================= | ====================== | ========================== | =============== | ================ | =============== | ============= | ===== | ==================== | =========================== | ================= | =========== | 
| 58966      | ALEMBIC. 1880 BOSTON ROAD        | 2016-12-30T00:00:00 |                         | 972249      | 1880         | BOSTON ROAD     | Bronx     | 2030040020 |         | 206             | 17               | 359          | BX17                         | 40.83956987 | -73.8827829  | 40.8392129        | -73.88262813       |                          | New Construction            | Not Extended Affordability    | Prevailing Wage        | 167                        | 0               | 0                | 0               | 0             | 1     | 168                  | 0                           | 168               | 168         | 
| 60249      | FOX STREET PRC                   | 2016-12-30T00:00:00 |                         | 971150      | 1000         | FOX STREET      | Bronx     |            |         | 202             | 17               | 159          | BX27                         | 40.82295039 | -73.89388639 |                   |                    |                          | New Construction            | Not Extended Affordability    | Non Prevailing Wage    | 0                          | 60              | 59               | 0               | 0             | 1     | 120                  | 0                           | 120               | 120         | 
| 60249      | FOX STREET PRC                   | 2016-12-30T00:00:00 |                         | 975072      | 960          | SIMPSON STREET  | Bronx     | 2027240103 |         | 202             | 17               | 159          | BX27                         | 40.82180215 | -73.8928585  | 40.82165366       | -73.89256246       |                          | New Construction            | Not Extended Affordability    | Non Prevailing Wage    | 8                          | 32              | 40               | 0               | 0             | 0     | 80                   | 0                           | 80                | 80          | 
| 63348      | CONFIDENTIAL                     | 2016-12-30T00:00:00 |                         |             | ----         | ----            | Brooklyn  |            |         | 317             | 41               |              |                              |             |              |                   |                    |                          | Preservation                | Not Extended Affordability    | Non Prevailing Wage    | 0                          | 0               | 2                | 0               | 0             | 0     | 0                    | 2                           | 2                 | 2           | 
| 63349      | CONFIDENTIAL                     | 2016-12-30T00:00:00 |                         |             | ----         | ----            | Brooklyn  |            |         | 318             | 46               |              |                              |             |              |                   |                    |                          | Preservation                | Not Extended Affordability    | Non Prevailing Wage    | 0                          | 0               | 2                | 0               | 0             | 0     | 2                    | 0                           | 2                 | 2           | 
| 55264      | THESSALONIA MANOR                | 2016-12-29T00:00:00 |                         | 966135      | 960          | PROSPECT AVENUE | Bronx     | 2026900109 |         | 202             | 17               | 12901        | BX33                         | 40.82284084 | -73.90029622 | 40.82266749       | -73.8998051        |                          | New Construction            | Not Extended Affordability    | Non Prevailing Wage    | 36                         | 0               | 83               | 0               | 0             | 1     | 120                  | 0                           | 120               | 120         | 
| 58625      | ONE FLUSHING                     | 2016-12-29T00:00:00 |                         | 967648      | 133-45       | 41 AVENUE       | Queens    | 4050370064 |         | 407             | 20               | 871          | QN22                         | 40.75785422 | -73.83025197 | 40.75788784       | -73.83071391       |                          | New Construction            | Not Extended Affordability    | Non Prevailing Wage    | 0                          | 66              | 105              | 60              | 0             | 1     | 232                  | 0                           | 232               | 232         | 
| 60319      | VILLA GARDENS                    | 2016-12-29T00:00:00 |                         | 970855      | 16           | EAST 204 STREET | Bronx     | 2033210038 |         | 207             | 11               | 411          | BX05                         | 40.87511923 | -73.88828518 | 40.87481977       | -73.88798918       |                          | New Construction            | Not Extended Affordability    | Non Prevailing Wage    | 0                          | 0               | 27               | 25              | 0             | 1     | 53                   | 0                           | 53                | 53          | 
| 60342      | TILDEN TOWERS HOUSING CO. INC.   | 2016-12-29T00:00:00 |                         | 47636       | 3511         | BARNES AVENUE   | Bronx     | 2046590031 | 2057725 | 212             | 12               | 380          | BX44                         | 40.87717634 | -73.8616494  | 40.87720181       | -73.86228578       |                          | Preservation                | Not Extended Affordability    | Non Prevailing Wage    | 1                          | 53              | 72               | 0               | 0             | 0     | 0                    | 126                         | 126               | 126         | 
| 60777      | 477 LENOX AVENUE HDFC.HUDMF.FY17 | 2016-12-29T00:00:00 | 2016-12-29T00:00:00     | 23625       | 477          | LENOX AVENUE    | Manhattan | 1019180036 | 1058228 | 110             | 9                | 226          | MN03                         | 40.81327355 | -73.94147965 | 40.81349604       | -73.94181542       | 2016-12-29T00:00:00      | Preservation                | Extended Affordability        | Non Prevailing Wage    | 8                          | 3               | 0                | 1               | 0             | 0     | 12                   | 0                           | 12                | 12          | 
```