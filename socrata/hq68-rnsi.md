# Housing New York Units by Project

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/housing-new-york-units-by-project) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/hq68-rnsi) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/hq68-rnsi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/hq68-rnsi/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | hq68-rnsi |
| Name | Housing New York Units by Project |
| Attribution | Department of Housing Preservation and Development (HPD) |
| Category | Housing & Development |
| Tags | housing, hpd, development, building |
| Created | 2016-12-13T20:48:56Z |
| Publication Date | 2017-01-18T23:19:48Z |

## Description

The Department of Housing Preservation and Development (HPD) reports on buildings, units, and projects that began after January 1, 2014 and are counted towards the Housing New York plan. The Housing New York Units by Project file presents this data by project, and includes project-level data, such as senior units, but does not include building-level data.  The unit counts are provided for each project, rather than by building. For additional documentation, including a data dictionary, review the attachments in the ?About this Dataset? section of the Primer landing page.

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                          | Data Type     | Render Type   |
| ======== | ============== | ============================= | ============================= | ============= | ============= |
| Yes      | series tag     | project_id                    | Project ID                    | text          | text          |
| Yes      | series tag     | project_name                  | Project Name                  | text          | text          |
| Yes      | time           | project_start_date            | Project Start Date            | calendar_date | calendar_date |
| No       |                | project_completion_date       | Project Completion Date       | calendar_date | calendar_date |
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
| Yes      | numeric metric | senior_units                  | Senior Units                  | number        | number        |
```

## Time Field

```ls
Value = project_start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = project_completion_date
```

## Data Commands

```ls
series e:hq68-rnsi d:2016-12-30T00:00:00.000Z t:extended_affordability_status="Not Extended Affordability" t:project_name="ALEMBIC. 1880 BOSTON ROAD" t:project_id=58966 t:prevailing_wage_status="Prevailing Wage" m:other=1 m:middle_income=0 m:counted_rental_units=168 m:moderate_income=0 m:extremely_low_income_units=167 m:all_counted_units=168 m:very_low_income=0 m:senior_units=167 m:low_income_units=0 m:counted_homeownership_units=0 m:total_units=168

series e:hq68-rnsi d:2016-12-30T00:00:00.000Z t:extended_affordability_status="Not Extended Affordability" t:project_name="FOX STREET PRC" t:project_id=60249 t:prevailing_wage_status="Non Prevailing Wage" m:other=1 m:middle_income=0 m:counted_rental_units=200 m:moderate_income=0 m:extremely_low_income_units=8 m:all_counted_units=200 m:very_low_income=92 m:senior_units=0 m:low_income_units=99 m:counted_homeownership_units=0 m:total_units=200

series e:hq68-rnsi d:2016-12-30T00:00:00.000Z t:extended_affordability_status="Not Extended Affordability" t:project_name=CONFIDENTIAL t:project_id=63348 t:prevailing_wage_status="Non Prevailing Wage" m:other=0 m:middle_income=0 m:counted_rental_units=0 m:moderate_income=0 m:extremely_low_income_units=0 m:all_counted_units=2 m:very_low_income=0 m:senior_units=0 m:low_income_units=2 m:counted_homeownership_units=2 m:total_units=2
```

## Meta Commands

```ls
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

metric m:senior_units p:integer l:"Senior Units" d:"Senior Units are units that are created or preserved for senior households. Senior Units are a subset of the Counted Units in a building, and are also included in the appropriate Extremely Low Income, Low Income, Moderate Income, Middle Income, or Other category." t:dataTypeName=number

entity e:hq68-rnsi l:"Housing New York Units by Project" t:attribution="Department of Housing Preservation and Development (HPD)" t:url=https://data.cityofnewyork.us/api/views/hq68-rnsi

property e:hq68-rnsi t:meta.view v:id=hq68-rnsi v:category="Housing & Development" v:averageRating=0 v:name="Housing New York Units by Project" v:attribution="Department of Housing Preservation and Development (HPD)"

property e:hq68-rnsi t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:hq68-rnsi t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| project_id | project_name                     | project_start_date  | project_completion_date | extended_affordability_status | prevailing_wage_status | extremely_low_income_units | very_low_income | low_income_units | moderate_income | middle_income | other | counted_rental_units | counted_homeownership_units | all_counted_units | total_units | senior_units | 
| ========== | ================================ | =================== | ======================= | ============================= | ====================== | ========================== | =============== | ================ | =============== | ============= | ===== | ==================== | =========================== | ================= | =========== | ============ | 
| 58966      | ALEMBIC. 1880 BOSTON ROAD        | 2016-12-30T00:00:00 |                         | Not Extended Affordability    | Prevailing Wage        | 167                        | 0               | 0                | 0               | 0             | 1     | 168                  | 0                           | 168               | 168         | 167          | 
| 60249      | FOX STREET PRC                   | 2016-12-30T00:00:00 |                         | Not Extended Affordability    | Non Prevailing Wage    | 8                          | 92              | 99               | 0               | 0             | 1     | 200                  | 0                           | 200               | 200         | 0            | 
| 63348      | CONFIDENTIAL                     | 2016-12-30T00:00:00 |                         | Not Extended Affordability    | Non Prevailing Wage    | 0                          | 0               | 2                | 0               | 0             | 0     | 0                    | 2                           | 2                 | 2           | 0            | 
| 63349      | CONFIDENTIAL                     | 2016-12-30T00:00:00 |                         | Not Extended Affordability    | Non Prevailing Wage    | 0                          | 0               | 2                | 0               | 0             | 0     | 2                    | 0                           | 2                 | 2           | 0            | 
| 55264      | THESSALONIA MANOR                | 2016-12-29T00:00:00 |                         | Not Extended Affordability    | Non Prevailing Wage    | 36                         | 0               | 83               | 0               | 0             | 1     | 120                  | 0                           | 120               | 120         | 0            | 
| 58625      | ONE FLUSHING                     | 2016-12-29T00:00:00 |                         | Not Extended Affordability    | Non Prevailing Wage    | 0                          | 66              | 105              | 60              | 0             | 1     | 232                  | 0                           | 232               | 232         | 66           | 
| 60319      | VILLA GARDENS                    | 2016-12-29T00:00:00 |                         | Not Extended Affordability    | Non Prevailing Wage    | 0                          | 0               | 27               | 25              | 0             | 1     | 53                   | 0                           | 53                | 53          | 0            | 
| 60342      | TILDEN TOWERS HOUSING CO. INC.   | 2016-12-29T00:00:00 |                         | Not Extended Affordability    | Non Prevailing Wage    | 1                          | 53              | 72               | 0               | 0             | 0     | 0                    | 126                         | 126               | 126         | 0            | 
| 60777      | 477 LENOX AVENUE HDFC.HUDMF.FY17 | 2016-12-29T00:00:00 | 2016-12-29T00:00:00     | Extended Affordability        | Non Prevailing Wage    | 8                          | 3               | 0                | 1               | 0             | 0     | 12                   | 0                           | 12                | 12          | 0            | 
| 63372      | Village East Towers (HDC)        | 2016-12-29T00:00:00 |                         | Not Extended Affordability    | Non Prevailing Wage    | 0                          | 0               | 0                | 0               | 434           | 0     | 0                    | 434                         | 434               | 434         | 0            | 
```