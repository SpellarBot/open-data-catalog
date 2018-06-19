# Bureau Of Street Lighting (BSL) - Performance Metrics

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bureau-of-street-lighting-bsl-performance-metrics) |
| Metadata | [Link](https://data.lacity.org/api/views/5y5q-d9ew) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/5y5q-d9ew/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/5y5q-d9ew/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | 5y5q-d9ew |
| Name | Bureau Of Street Lighting (BSL) - Performance Metrics |
| Attribution | Bureau of Street Lighting |
| Category | A Livable and Sustainable City |
| Tags | bureau of street lighting, bsl, performance, metrics |
| Created | 2014-07-31T17:23:10Z |
| Publication Date | 2017-03-13T21:09:28Z |

## Description

This dataset contains metrics that measure the operational performance of the Bureau of Street Lighting. These metrics are used on a regular basis by the department and the Mayor to evaluate progress and inform decision making. Performance management forms the foundation of a data-driven culture of innovation and excellence in the City of Los Angeles.

## Columns

```ls
| Included | Schema Type    | Field Name                                                                          | Name                                                                                   | Data Type     | Render Type   |
| ======== | ============== | =================================================================================== | ====================================================================================== | ============= | ============= |
| Yes      | time           | date_value                                                                          | Date Value                                                                             | calendar_date | calendar_date |
| Yes      | series tag     | month_year                                                                          | Month-Year                                                                             | text          | text          |
| No       |                | quarter_fy                                                                          | Quarter-FY                                                                             | text          | text          |
| Yes      | series tag     | annual_fy                                                                           | Annual-FY                                                                              | text          | text          |
| Yes      | numeric metric | cumulative_of_street_lights_converted_to_led_annual_fy                              | Cumulative # of street lights converted to LED (Annual FY)                             | number        | number        |
| Yes      | numeric metric | projected_cumulative_of_street_lights_converted_to_led_annual_fy                    | PROJECTED: Cumulative # of street lights converted to LED (Annual FY)                  | number        | number        |
| Yes      | series tag     | cumulative_of_street_lights_converted_to_led_monthly                                | Cumulative # of street lights converted to LED (Monthly)                               | text          | number        |
| Yes      | series tag     | projected_cumulative_of_street_lights_converted_to_led_monthly                      | PROJECTED: Cumulative # of street lights converted to LED (Monthly)                    | text          | number        |
| Yes      | series tag     | of_streetlights_operating_annual_fy                                                 | % of streetlights operating (Annual FY)                                                | text          | percent       |
| Yes      | series tag     | projected_of_streetlights_operating_annual_fy                                       | PROJECTED: % of streetlights operating (Annual FY)                                     | text          | percent       |
| Yes      | series tag     | average_of_streetlights_operating_citywide_monthly                                  | Average % of streetlights operating Citywide (Monthly)                                 | text          | percent       |
| Yes      | series tag     | projected_average_of_streetlights_operating_citywide_monthly                        | PROJECTED: Average % of streetlights operating Citywide (Monthly)                      | text          | percent       |
| Yes      | series tag     | street_lighting_maintenance_assessment_fund_revenue_in_millions_annual_fy           | Street Lighting Maintenance Assessment Fund revenue in millions (Annual FY)            | text          | number        |
| Yes      | series tag     | projected_street_lighting_maintenance_assessment_fund_revenue_in_millions_annual_fy | PROJECTED: Street Lighting Maintenance Assessment Fund revenue in millions (Annual FY) | text          | number        |
```

## Time Field

```ls
Value = date_value
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = quarter_fy
```

## Data Commands

```ls
series e:5y5q-d9ew d:2012-06-30T00:00:00.000Z t:street_lighting_maintenance_assessment_fund_revenue_in_millions_annual_fy=44.5 t:annual_fy="FY 2012" t:month_year=Jun-12 t:of_streetlights_operating_annual_fy=99.1 m:cumulative_of_street_lights_converted_to_led_annual_fy=95000

series e:5y5q-d9ew d:2013-06-30T00:00:00.000Z t:street_lighting_maintenance_assessment_fund_revenue_in_millions_annual_fy=45.8 t:annual_fy="FY 2013" t:month_year=Jun-13 t:of_streetlights_operating_annual_fy=99.0 m:cumulative_of_street_lights_converted_to_led_annual_fy=140000

series e:5y5q-d9ew d:2011-06-30T00:00:00.000Z t:annual_fy="FY 2011" t:month_year=Jun-11 m:cumulative_of_street_lights_converted_to_led_annual_fy=50000
```

## Meta Commands

```ls
metric m:cumulative_of_street_lights_converted_to_led_annual_fy p:integer l:"Cumulative # of street lights converted to LED (Annual FY)" d:"Cumulative number of streetlights converted to LED (Annual FY)" t:dataTypeName=number

metric m:projected_cumulative_of_street_lights_converted_to_led_annual_fy p:integer l:"PROJECTED: Cumulative # of street lights converted to LED (Annual FY)" d:"Projected target for number of cumulative number of street lights converted to LED (Annual FY)" t:dataTypeName=number

entity e:5y5q-d9ew l:"Bureau Of Street Lighting (BSL) - Performance Metrics" t:attribution="Bureau of Street Lighting" t:url=https://data.lacity.org/api/views/5y5q-d9ew

property e:5y5q-d9ew t:meta.view v:id=5y5q-d9ew v:category="A Livable and Sustainable City" v:averageRating=0 v:name="Bureau Of Street Lighting (BSL) - Performance Metrics" v:attribution="Bureau of Street Lighting"

property e:5y5q-d9ew t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:5y5q-d9ew t:meta.view.owner v:id=kmuv-58sk v:profileImageUrlMedium=/api/users/kmuv-58sk/profile_images/THUMB v:profileImageUrlLarge=/api/users/kmuv-58sk/profile_images/LARGE v:screenName="Public Works: Street Lighting OpenData" v:profileImageUrlSmall=/api/users/kmuv-58sk/profile_images/TINY v:displayName="Public Works: Street Lighting OpenData"

property e:5y5q-d9ew t:meta.view.tableauthor v:id=kmuv-58sk v:profileImageUrlMedium=/api/users/kmuv-58sk/profile_images/THUMB v:profileImageUrlLarge=/api/users/kmuv-58sk/profile_images/LARGE v:screenName="Public Works: Street Lighting OpenData" v:profileImageUrlSmall=/api/users/kmuv-58sk/profile_images/TINY v:roleName=publisher v:displayName="Public Works: Street Lighting OpenData"
```

## Top Records

```ls
| date_value          | month_year | quarter_fy | annual_fy | cumulative_of_street_lights_converted_to_led_annual_fy | projected_cumulative_of_street_lights_converted_to_led_annual_fy | cumulative_of_street_lights_converted_to_led_monthly | projected_cumulative_of_street_lights_converted_to_led_monthly | of_streetlights_operating_annual_fy | projected_of_streetlights_operating_annual_fy | average_of_streetlights_operating_citywide_monthly | projected_average_of_streetlights_operating_citywide_monthly | street_lighting_maintenance_assessment_fund_revenue_in_millions_annual_fy | projected_street_lighting_maintenance_assessment_fund_revenue_in_millions_annual_fy | 
| =================== | ========== | ========== | ========= | ====================================================== | ================================================================ | ==================================================== | ============================================================== | =================================== | ============================================= | ================================================== | ============================================================ | ========================================================================= | =================================================================================== | 
| 2012-06-30T00:00:00 | Jun-12     | Q4 FY12    | FY 2012   | 95000                                                  |                                                                  |                                                      |                                                                | 99.1                                |                                               |                                                    |                                                              | 44.5                                                                      |                                                                                     | 
| 2012-07-31T00:00:00 | Jul-12     |            |           |                                                        |                                                                  |                                                      |                                                                |                                     |                                               |                                                    |                                                              |                                                                           |                                                                                     | 
| 2012-08-31T00:00:00 | Aug-12     |            |           |                                                        |                                                                  |                                                      |                                                                |                                     |                                               |                                                    |                                                              |                                                                           |                                                                                     | 
| 2012-09-30T00:00:00 | Sep-12     | Q1 FY13    |           |                                                        |                                                                  |                                                      |                                                                |                                     |                                               |                                                    |                                                              |                                                                           |                                                                                     | 
| 2012-10-31T00:00:00 | Oct-12     |            |           |                                                        |                                                                  |                                                      |                                                                |                                     |                                               |                                                    |                                                              |                                                                           |                                                                                     | 
| 2012-11-30T00:00:00 | Nov-12     |            |           |                                                        |                                                                  |                                                      |                                                                |                                     |                                               |                                                    |                                                              |                                                                           |                                                                                     | 
| 2012-12-31T00:00:00 | Dec-12     | Q2 FY13    |           |                                                        |                                                                  |                                                      |                                                                |                                     |                                               |                                                    |                                                              |                                                                           |                                                                                     | 
| 2013-01-31T00:00:00 | Jan-13     |            |           |                                                        |                                                                  |                                                      |                                                                |                                     |                                               |                                                    |                                                              |                                                                           |                                                                                     | 
| 2013-02-28T00:00:00 | Feb-13     |            |           |                                                        |                                                                  |                                                      |                                                                |                                     |                                               |                                                    |                                                              |                                                                           |                                                                                     | 
| 2013-03-31T00:00:00 | Mar-13     | Q3 FY13    |           |                                                        |                                                                  |                                                      |                                                                |                                     |                                               |                                                    |                                                              |                                                                           |                                                                                     | 
```