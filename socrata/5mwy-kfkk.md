# Zoo - Performance Metrics

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/zoo-performance-metrics) |
| Metadata | [Link](https://data.lacity.org/api/views/5mwy-kfkk) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/5mwy-kfkk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/5mwy-kfkk/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | 5mwy-kfkk |
| Name | Zoo - Performance Metrics |
| Tags | zoo, performance, metrics |
| Created | 2014-08-01T00:06:18Z |
| Publication Date | 2015-04-22T21:22:10Z |

## Description

This dataset contains metrics that measure the operational performance of the Zoo. These metrics are used on a regular basis by the department and the Mayor to evaluate progress and inform decision making. Performance management forms the foundation of a data-driven culture of innovation and excellence in the City of Los Angeles.

## Columns

```ls
| Included | Schema Type    | Field Name                                                                                | Name                                                                                           | Data Type     | Render Type   |
| ======== | ============== | ========================================================================================= | ============================================================================================== | ============= | ============= |
| Yes      | time           | date_value                                                                                | Date Value                                                                                     | calendar_date | calendar_date |
| Yes      | series tag     | month_year                                                                                | Month-Year                                                                                     | text          | text          |
| No       |                | quarter_fy                                                                                | Quarter-FY                                                                                     | text          | text          |
| Yes      | series tag     | annual_fy                                                                                 | Annual-FY                                                                                      | text          | text          |
| Yes      | numeric metric | of_international_conservation_programs_supported_monthly                                  | # of international conservation programs supported (Monthly)                                   | number        | number        |
| Yes      | numeric metric | of_international_conservation_programs_supported_annually_fy                              | # of international conservation programs supported (Cumulative FY)                             | number        | number        |
| Yes      | numeric metric | projected_of_international_conservation_programs_supported_annually_fy                    | PROJECTED: # of international conservation programs supported (Annually FY)                    | number        | number        |
| Yes      | numeric metric | animal_preventative_health_procedures                                                     | Animal Preventative Health Procedures                                                          | number        | number        |
| Yes      | numeric metric | target_tbd                                                                                | TARGET: In development                                                                         | number        | number        |
| Yes      | numeric metric | projected_of_online_ticket_transactions_annually_fy                                       | PROJECTED: % of online ticket transactions (Annually FY)                                       | percent       | percent       |
| Yes      | numeric metric | of_online_ticket_sale_transactions_monthly                                                | ACTUAL: % of online ticket sale transactions (Monthly)                                         | percent       | percent       |
| Yes      | numeric metric | of_online_ticket_sale_transactions_annually_fy                                            | ACTUAL: % of online ticket sale transactions (Year-to-Date FY)                                 | percent       | percent       |
| Yes      | numeric metric | zoo_grounds_in_compliance_with_the_city_s_brush_clearance_ordinance_annually_fy           | % zoo grounds in compliance with the City's brush clearance ordinance (Annually FY)            | percent       | percent       |
| Yes      | numeric metric | projected_zoo_grounds_in_compliance_with_the_city_s_brush_clearance_ordinance_annually_fy | PROJECTED: % zoo grounds in compliance with the City's brush clearance ordinance (Annually FY) | percent       | percent       |
| Yes      | numeric metric | projected_of_excellent_rating_for_facility_cleanliness_annually_fy                        | PROJECTED: % of "excellent" rating for facility cleanliness (Annually FY)                      | percent       | percent       |
| Yes      | numeric metric | of_excellent_rating_for_facility_cleanliness_annually_fy                                  | ACTUAL: % of "excellent" rating for facility cleanliness (Annually FY)                         | percent       | percent       |
| Yes      | numeric metric | projected_of_commercial_films_shot_at_the_zoo_annually_fy                                 | PROJECTED: # of commercial films shot at the zoo (Annually FY)                                 | number        | number        |
| Yes      | numeric metric | of_commercial_film_shoots_at_the_zoo_monthly                                              | ACTUAL: # of commercial film shoots at the zoo (Monthly)                                       | number        | number        |
| Yes      | numeric metric | of_commercial_film_shoots_at_the_zoo_annually_fy                                          | ACTUAL: # of commercial film shoots at the zoo (Cumulative FYTD)                               | number        | number        |
| Yes      | numeric metric | projected_of_education_programs_filled_annually_fy                                        | PROJECTED:% of education programs filled (Annually FY)                                         | percent       | percent       |
| Yes      | numeric metric | of_education_programs_filled_monthly                                                      | ACTUAL: % of education programs filled (Monthly)                                               | percent       | percent       |
| Yes      | numeric metric | of_education_programs_filled_annually_fy                                                  | ACTUAL: % of education programs filled (Cumulative FYTD)                                       | percent       | percent       |
| Yes      | numeric metric | projected_of_educational_visits_annually_fy                                               | PROJECTED: # of Educational Visits (Monthly)                                                   | number        | number        |
| Yes      | numeric metric | of_educational_visits_monthly                                                             | ACTUAL: # of Educational Visits (Monthly)                                                      | number        | number        |
| Yes      | numeric metric | target_of_cumulative_educational_visits_monthly                                           | PROJECTED: # of Educational Visits (Cumulative FYTD)                                           | number        | number        |
| Yes      | numeric metric | of_cumulative_educational_visits_monthly                                                  | ACTUAL: # of Educational Visits (Cumulative FYTD)                                              | number        | number        |
| Yes      | numeric metric | projected_of_restrooms_inspected_weekly_annually_fy                                       | PROJECTED: % of restrooms inspected weekly (Annually FY)                                       | percent       | percent       |
| Yes      | numeric metric | of_restrooms_inspected_weekly_annually_fy                                                 | ACTUAL: % of restrooms inspected weekly (Annually FY)                                          | percent       | percent       |
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
series e:5mwy-kfkk d:2010-06-30T00:00:00.000Z t:annual_fy="FY 2010" t:month_year=Jun-10 m:zoo_grounds_in_compliance_with_the_city_s_brush_clearance_ordinance_annually_fy=100 m:of_restrooms_inspected_weekly_annually_fy=100 m:of_international_conservation_programs_supported_annually_fy=24

series e:5mwy-kfkk d:2011-06-30T00:00:00.000Z t:annual_fy="FY 2011" t:month_year=Jun-11 m:zoo_grounds_in_compliance_with_the_city_s_brush_clearance_ordinance_annually_fy=100 m:of_online_ticket_sale_transactions_annually_fy=1 m:of_restrooms_inspected_weekly_annually_fy=90 m:of_international_conservation_programs_supported_annually_fy=31

series e:5mwy-kfkk d:2012-06-30T00:00:00.000Z t:annual_fy="FY 2012" t:month_year=Jun-12 m:of_education_programs_filled_monthly=93 m:of_education_programs_filled_annually_fy=93 m:zoo_grounds_in_compliance_with_the_city_s_brush_clearance_ordinance_annually_fy=100 m:of_online_ticket_sale_transactions_annually_fy=3.6 m:of_restrooms_inspected_weekly_annually_fy=85 m:of_international_conservation_programs_supported_annually_fy=24
```

## Meta Commands

```ls
metric m:of_international_conservation_programs_supported_monthly p:float l:"# of international conservation programs supported (Monthly)" t:dataTypeName=number

metric m:of_international_conservation_programs_supported_annually_fy p:float l:"# of international conservation programs supported (Cumulative FY)" t:dataTypeName=number

metric m:projected_of_international_conservation_programs_supported_annually_fy p:float l:"PROJECTED: # of international conservation programs supported (Annually FY)" t:dataTypeName=number

metric m:animal_preventative_health_procedures p:long l:"Animal Preventative Health Procedures" t:dataTypeName=number

metric m:target_tbd p:long l:"TARGET: In development" t:dataTypeName=number

metric m:projected_of_online_ticket_transactions_annually_fy p:float l:"PROJECTED: % of online ticket transactions (Annually FY)" t:dataTypeName=percent

metric m:of_online_ticket_sale_transactions_monthly p:float l:"ACTUAL: % of online ticket sale transactions (Monthly)" t:dataTypeName=percent

metric m:of_online_ticket_sale_transactions_annually_fy p:float l:"ACTUAL: % of online ticket sale transactions (Year-to-Date FY)" t:dataTypeName=percent

metric m:zoo_grounds_in_compliance_with_the_city_s_brush_clearance_ordinance_annually_fy p:float l:"% zoo grounds in compliance with the City's brush clearance ordinance (Annually FY)" t:dataTypeName=percent

metric m:projected_zoo_grounds_in_compliance_with_the_city_s_brush_clearance_ordinance_annually_fy p:float l:"PROJECTED: % zoo grounds in compliance with the City's brush clearance ordinance (Annually FY)" t:dataTypeName=percent

metric m:projected_of_excellent_rating_for_facility_cleanliness_annually_fy p:float l:"PROJECTED: % of ""excellent"" rating for facility cleanliness (Annually FY)" t:dataTypeName=percent

metric m:of_excellent_rating_for_facility_cleanliness_annually_fy p:float l:"ACTUAL: % of ""excellent"" rating for facility cleanliness (Annually FY)" t:dataTypeName=percent

metric m:projected_of_commercial_films_shot_at_the_zoo_annually_fy p:float l:"PROJECTED: # of commercial films shot at the zoo (Annually FY)" t:dataTypeName=number

metric m:of_commercial_film_shoots_at_the_zoo_monthly p:float l:"ACTUAL: # of commercial film shoots at the zoo (Monthly)" t:dataTypeName=number

metric m:of_commercial_film_shoots_at_the_zoo_annually_fy p:float l:"ACTUAL: # of commercial film shoots at the zoo (Cumulative FYTD)" t:dataTypeName=number

metric m:projected_of_education_programs_filled_annually_fy p:float l:"PROJECTED:% of education programs filled (Annually FY)" t:dataTypeName=percent

metric m:of_education_programs_filled_monthly p:float l:"ACTUAL: % of education programs filled (Monthly)" t:dataTypeName=percent

metric m:of_education_programs_filled_annually_fy p:float l:"ACTUAL: % of education programs filled (Cumulative FYTD)" t:dataTypeName=percent

metric m:projected_of_educational_visits_annually_fy p:float l:"PROJECTED: # of Educational Visits (Monthly)" t:dataTypeName=number

metric m:of_educational_visits_monthly p:float l:"ACTUAL: # of Educational Visits (Monthly)" t:dataTypeName=number

metric m:target_of_cumulative_educational_visits_monthly p:float l:"PROJECTED: # of Educational Visits (Cumulative FYTD)" t:dataTypeName=number

metric m:of_cumulative_educational_visits_monthly p:float l:"ACTUAL: # of Educational Visits (Cumulative FYTD)" t:dataTypeName=number

metric m:projected_of_restrooms_inspected_weekly_annually_fy p:float l:"PROJECTED: % of restrooms inspected weekly (Annually FY)" t:dataTypeName=percent

metric m:of_restrooms_inspected_weekly_annually_fy p:float l:"ACTUAL: % of restrooms inspected weekly (Annually FY)" t:dataTypeName=percent

entity e:5mwy-kfkk l:"Zoo - Performance Metrics" t:url=https://data.lacity.org/api/views/5mwy-kfkk

property e:5mwy-kfkk t:meta.view v:id=5mwy-kfkk v:averageRating=0 v:name="Zoo - Performance Metrics"

property e:5mwy-kfkk t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:5mwy-kfkk t:meta.view.owner v:id=tgn6-4379 v:profileImageUrlMedium=/api/users/tgn6-4379/profile_images/THUMB v:profileImageUrlLarge=/api/users/tgn6-4379/profile_images/LARGE v:screenName="Mayor's Office OpenData" v:profileImageUrlSmall=/api/users/tgn6-4379/profile_images/TINY v:displayName="Mayor's Office OpenData"

property e:5mwy-kfkk t:meta.view.tableauthor v:id=tgn6-4379 v:profileImageUrlMedium=/api/users/tgn6-4379/profile_images/THUMB v:profileImageUrlLarge=/api/users/tgn6-4379/profile_images/LARGE v:screenName="Mayor's Office OpenData" v:profileImageUrlSmall=/api/users/tgn6-4379/profile_images/TINY v:roleName=administrator v:displayName="Mayor's Office OpenData"
```

## Top Records

```ls
| date_value          | month_year | quarter_fy | annual_fy | of_international_conservation_programs_supported_monthly | of_international_conservation_programs_supported_annually_fy | projected_of_international_conservation_programs_supported_annually_fy | animal_preventative_health_procedures | target_tbd | projected_of_online_ticket_transactions_annually_fy | of_online_ticket_sale_transactions_monthly | of_online_ticket_sale_transactions_annually_fy | zoo_grounds_in_compliance_with_the_city_s_brush_clearance_ordinance_annually_fy | projected_zoo_grounds_in_compliance_with_the_city_s_brush_clearance_ordinance_annually_fy | projected_of_excellent_rating_for_facility_cleanliness_annually_fy | of_excellent_rating_for_facility_cleanliness_annually_fy | projected_of_commercial_films_shot_at_the_zoo_annually_fy | of_commercial_film_shoots_at_the_zoo_monthly | of_commercial_film_shoots_at_the_zoo_annually_fy | projected_of_education_programs_filled_annually_fy | of_education_programs_filled_monthly | of_education_programs_filled_annually_fy | projected_of_educational_visits_annually_fy | of_educational_visits_monthly | target_of_cumulative_educational_visits_monthly | of_cumulative_educational_visits_monthly | projected_of_restrooms_inspected_weekly_annually_fy | of_restrooms_inspected_weekly_annually_fy | 
| =================== | ========== | ========== | ========= | ======================================================== | ============================================================ | ====================================================================== | ===================================== | ========== | =================================================== | ========================================== | ============================================== | =============================================================================== | ========================================================================================= | ================================================================== | ======================================================== | ========================================================= | ============================================ | ================================================ | ================================================== | ==================================== | ======================================== | =========================================== | ============================= | =============================================== | ======================================== | =================================================== | ========================================= | 
| 2009-06-30T00:00:00 | Jun-09     | Q4 FY09    | FY 2009   |                                                          |                                                              |                                                                        |                                       |            |                                                     |                                            |                                                |                                                                                 |                                                                                           |                                                                    |                                                          |                                                           |                                              |                                                  |                                                    |                                      |                                          |                                             |                               |                                                 |                                          |                                                     |                                           | 
| 2010-06-30T00:00:00 | Jun-10     | Q4 FY10    | FY 2010   |                                                          | 24.00                                                        |                                                                        |                                       |            |                                                     |                                            |                                                | 100.00                                                                          |                                                                                           |                                                                    |                                                          |                                                           |                                              |                                                  |                                                    |                                      |                                          |                                             |                               |                                                 |                                          |                                                     | 100.0                                     | 
| 2011-06-30T00:00:00 | Jun-11     | Q4 FY11    | FY 2011   |                                                          | 31.00                                                        |                                                                        |                                       |            |                                                     |                                            | 1.00                                           | 100.00                                                                          |                                                                                           |                                                                    |                                                          |                                                           |                                              |                                                  |                                                    |                                      |                                          |                                             |                               |                                                 |                                          |                                                     | 90.0                                      | 
| 2012-06-30T00:00:00 | Jun-12     | Q4 FY12    | FY 2012   |                                                          | 24.00                                                        |                                                                        |                                       |            |                                                     |                                            | 3.60                                           | 100.00                                                                          |                                                                                           |                                                                    |                                                          |                                                           |                                              |                                                  |                                                    | 93.00                                | 93.00                                    |                                             |                               |                                                 |                                          |                                                     | 85.0                                      | 
| 2013-06-30T00:00:00 | Jun-13     | Q4 FY13    | FY 2013   |                                                          | 30.00                                                        |                                                                        |                                       |            |                                                     |                                            | 4.60                                           | 100.00                                                                          |                                                                                           |                                                                    |                                                          |                                                           | 8.00                                         | 8.00                                             |                                                    | 91.00                                | 91.00                                    |                                             |                               |                                                 |                                          |                                                     | 80.0                                      | 
| 2013-07-31T00:00:00 | Jul-13     |            |           |                                                          |                                                              |                                                                        |                                       |            |                                                     | 4.60                                       |                                                |                                                                                 |                                                                                           |                                                                    |                                                          |                                                           | 1.00                                         |                                                  |                                                    | 97.60                                |                                          |                                             | 783.00                        | 500.00                                          | 783.00                                   |                                                     |                                           | 
| 2013-08-31T00:00:00 | Aug-13     |            |           |                                                          |                                                              |                                                                        |                                       |            |                                                     | 4.70                                       |                                                |                                                                                 |                                                                                           |                                                                    |                                                          |                                                           | 2.00                                         |                                                  |                                                    | 93.40                                |                                          |                                             | 216.00                        | 1000.00                                         | 999.00                                   |                                                     |                                           | 
| 2013-09-30T00:00:00 | Sep-13     | Q1 FY14    |           |                                                          |                                                              |                                                                        |                                       |            |                                                     | 3.90                                       |                                                |                                                                                 |                                                                                           |                                                                    |                                                          |                                                           | 1.00                                         |                                                  |                                                    | 65.30                                |                                          |                                             | 1901.00                       | 3000.00                                         | 2900.00                                  |                                                     |                                           | 
| 2013-10-31T00:00:00 | Oct-13     |            |           |                                                          |                                                              |                                                                        |                                       |            |                                                     | 4.70                                       |                                                |                                                                                 |                                                                                           |                                                                    |                                                          |                                                           | 1.00                                         |                                                  |                                                    | 77.00                                |                                          |                                             | 6004.00                       | 9000.00                                         | 8904.00                                  |                                                     |                                           | 
| 2013-11-30T00:00:00 | Nov-13     |            |           |                                                          |                                                              |                                                                        |                                       |            |                                                     | 4.10                                       |                                                |                                                                                 |                                                                                           |                                                                    |                                                          |                                                           | 2.00                                         |                                                  |                                                    | 108.20                               |                                          |                                             | 7827.00                       | 15000.00                                        | 16731.00                                 |                                                     |                                           | 
```