# El Pueblo - Performance Metrics

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/el-pueblo-performance-metrics-9e463) |
| Metadata | [Link](https://data.lacity.org/api/views/i6yd-dz6m) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/i6yd-dz6m/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/i6yd-dz6m/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | i6yd-dz6m |
| Name | El Pueblo - Performance Metrics |
| Attribution | El Pueblo |
| Tags | el pueblo |
| Created | 2014-08-26T17:47:03Z |
| Publication Date | 2015-04-22T18:25:59Z |

## Description

This dataset contains metrics that measure the operational performance of the El Pueblo. These metrics are used on a regular basis by the department and the Mayor to evaluate progress and inform decision making.  Performance management forms the foundation of a data-driven culture of innovation and excellence in the City of Los Angeles.

## Columns

```ls
| Included | Schema Type    | Field Name                                                             | Name                                                                                 | Data Type     | Render Type   |
| ======== | ============== | ====================================================================== | ==================================================================================== | ============= | ============= |
| Yes      | time           | date_value                                                             | Date Value                                                                           | calendar_date | calendar_date |
| Yes      | series tag     | month_year                                                             | Month-Year                                                                           | text          | text          |
| No       |                | quarter_fy                                                             | Quarter-FY                                                                           | text          | text          |
| Yes      | series tag     | annual_fy                                                              | Annual-FY                                                                            | text          | text          |
| Yes      | numeric metric | of_tours_at_the_el_pueblo_monument_annually_fy                         | # of tourists who took tours at the El Pueblo Monument (Annually FY)                 | number        | number        |
| Yes      | numeric metric | projected_of_tours_at_the_el_pueblo_monument_annually_fy               | PROJECTED: # of tourists who will take tours at the El Pueblo Monument (Annually FY) | number        | number        |
| Yes      | numeric metric | total_of_el_pueblo_tours_monthly                                       | Total # tourists who took tours of El Pueblo tours (Monthly)                         | number        | number        |
| Yes      | numeric metric | target_total_of_el_pueblo_tours_monthly                                | TARGET: Total # of El Pueblo tours (Monthly)                                         | number        | number        |
| Yes      | numeric metric | total_of_museum_visits_monthly                                         | total # of museum visits (Monthly)                                                   | number        | number        |
| Yes      | numeric metric | target_of_museum_visits_monthly                                        | TARGET: # of museum visits (Monthly)                                                 | number        | number        |
| Yes      | numeric metric | of_cultural_traditional_and_informational_events_annually_fy           | # of cultural, traditional and informational events (Annually FY)                    | number        | number        |
| Yes      | numeric metric | projected_of_cultural_traditional_and_informational_events_annually_fy | PROJECTED: # of cultural, traditional and informational events (Annually FY)         | number        | number        |
| Yes      | numeric metric | of_cultural_traditional_and_informational_events_monthly               | # of cultural, traditional and informational events (Monthly)                        | number        | number        |
| Yes      | numeric metric | of_cultural_traditional_and_informational_event_attendees_monthly      | # of cultural, traditional and informational event attendees (Monthly)               | number        | number        |
| Yes      | numeric metric | of_work_orders_completed_annually_fy                                   | # of Work Orders Completed (Monthly)                                                 | number        | number        |
| Yes      | numeric metric | projected_of_work_orders_completed_annually_fy                         | PROJECTED: # of Work Orders Completed (Annually FY)                                  | number        | number        |
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
series e:i6yd-dz6m d:2012-06-30T00:00:00.000Z t:annual_fy="FY 2012" t:month_year=Jun-12 m:of_cultural_traditional_and_informational_events_annually_fy=20

series e:i6yd-dz6m d:2013-06-30T00:00:00.000Z t:annual_fy="FY 2013" t:month_year=Jun-13 m:of_cultural_traditional_and_informational_events_annually_fy=20 m:of_work_orders_completed_annually_fy=420 m:of_tours_at_the_el_pueblo_monument_annually_fy=11296

series e:i6yd-dz6m d:2014-01-31T00:00:00.000Z t:month_year=Jan-14 m:of_cultural_traditional_and_informational_event_attendees_monthly=1266 m:of_cultural_traditional_and_informational_events_monthly=6 m:total_of_museum_visits_monthly=42612 m:total_of_el_pueblo_tours_monthly=754 m:of_work_orders_completed_annually_fy=35
```

## Meta Commands

```ls
metric m:of_tours_at_the_el_pueblo_monument_annually_fy p:integer l:"# of tourists who took tours at the El Pueblo Monument (Annually FY)" t:dataTypeName=number

metric m:projected_of_tours_at_the_el_pueblo_monument_annually_fy p:integer l:"PROJECTED: # of tourists who will take tours at the El Pueblo Monument (Annually FY)" t:dataTypeName=number

metric m:total_of_el_pueblo_tours_monthly p:integer l:"Total # tourists who took tours of El Pueblo tours (Monthly)" t:dataTypeName=number

metric m:target_total_of_el_pueblo_tours_monthly p:integer l:"TARGET: Total # of El Pueblo tours (Monthly)" t:dataTypeName=number

metric m:total_of_museum_visits_monthly p:integer l:"total # of museum visits (Monthly)" t:dataTypeName=number

metric m:target_of_museum_visits_monthly p:integer l:"TARGET: # of museum visits (Monthly)" t:dataTypeName=number

metric m:of_cultural_traditional_and_informational_events_annually_fy p:integer l:"# of cultural, traditional and informational events (Annually FY)" t:dataTypeName=number

metric m:projected_of_cultural_traditional_and_informational_events_annually_fy p:integer l:"PROJECTED: # of cultural, traditional and informational events (Annually FY)" t:dataTypeName=number

metric m:of_cultural_traditional_and_informational_events_monthly p:integer l:"# of cultural, traditional and informational events (Monthly)" t:dataTypeName=number

metric m:of_cultural_traditional_and_informational_event_attendees_monthly p:integer l:"# of cultural, traditional and informational event attendees (Monthly)" t:dataTypeName=number

metric m:of_work_orders_completed_annually_fy p:float l:"# of Work Orders Completed (Monthly)" t:dataTypeName=number

metric m:projected_of_work_orders_completed_annually_fy p:float l:"PROJECTED: # of Work Orders Completed (Annually FY)" t:dataTypeName=number

entity e:i6yd-dz6m l:"El Pueblo - Performance Metrics" t:attribution="El Pueblo" t:url=https://data.lacity.org/api/views/i6yd-dz6m

property e:i6yd-dz6m t:meta.view v:id=i6yd-dz6m v:averageRating=0 v:name="El Pueblo - Performance Metrics" v:attribution="El Pueblo"

property e:i6yd-dz6m t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:i6yd-dz6m t:meta.view.owner v:id=tyhz-nfmm v:screenName="Miguel Sangalang" v:displayName="Miguel Sangalang"

property e:i6yd-dz6m t:meta.view.tableauthor v:id=tyhz-nfmm v:screenName="Miguel Sangalang" v:roleName=publisher v:displayName="Miguel Sangalang"
```

## Top Records

```ls
| date_value          | month_year | quarter_fy | annual_fy | of_tours_at_the_el_pueblo_monument_annually_fy | projected_of_tours_at_the_el_pueblo_monument_annually_fy | total_of_el_pueblo_tours_monthly | target_total_of_el_pueblo_tours_monthly | total_of_museum_visits_monthly | target_of_museum_visits_monthly | of_cultural_traditional_and_informational_events_annually_fy | projected_of_cultural_traditional_and_informational_events_annually_fy | of_cultural_traditional_and_informational_events_monthly | of_cultural_traditional_and_informational_event_attendees_monthly | of_work_orders_completed_annually_fy | projected_of_work_orders_completed_annually_fy | 
| =================== | ========== | ========== | ========= | ============================================== | ======================================================== | ================================ | ======================================= | ============================== | =============================== | ============================================================ | ====================================================================== | ======================================================== | ================================================================= | ==================================== | ============================================== | 
| 2010-06-30T00:00:00 | Jun-10     | Q4 FY10    | FY 2010   |                                                |                                                          |                                  |                                         |                                |                                 |                                                              |                                                                        |                                                          |                                                                   |                                      |                                                | 
| 2011-06-30T00:00:00 | Jun-11     | Q4 FY11    | FY 2011   |                                                |                                                          |                                  |                                         |                                |                                 |                                                              |                                                                        |                                                          |                                                                   |                                      |                                                | 
| 2012-06-30T00:00:00 | Jun-12     | Q4 FY12    | FY 2012   |                                                |                                                          |                                  |                                         |                                |                                 | 20                                                           |                                                                        |                                                          |                                                                   |                                      |                                                | 
| 2013-06-30T00:00:00 | Jun-13     | Q4 FY13    | FY 2013   | 11296                                          |                                                          |                                  |                                         |                                |                                 | 20                                                           |                                                                        |                                                          |                                                                   | 420.00                               |                                                | 
| 2013-07-31T00:00:00 | Jul-13     |            |           |                                                |                                                          |                                  |                                         |                                |                                 |                                                              |                                                                        |                                                          |                                                                   |                                      |                                                | 
| 2013-08-31T00:00:00 | Aug-13     |            |           |                                                |                                                          |                                  |                                         |                                |                                 |                                                              |                                                                        |                                                          |                                                                   |                                      |                                                | 
| 2013-09-30T00:00:00 | Sep-13     | Q1 FY14    |           |                                                |                                                          |                                  |                                         |                                |                                 |                                                              |                                                                        |                                                          |                                                                   |                                      |                                                | 
| 2013-10-31T00:00:00 | Oct-13     |            |           |                                                |                                                          |                                  |                                         |                                |                                 |                                                              |                                                                        |                                                          |                                                                   |                                      |                                                | 
| 2013-11-30T00:00:00 | Nov-13     |            |           |                                                |                                                          |                                  |                                         |                                |                                 |                                                              |                                                                        |                                                          |                                                                   |                                      |                                                | 
| 2013-12-31T00:00:00 | Dec-13     | Q2 FY14    |           |                                                |                                                          |                                  |                                         |                                |                                 |                                                              |                                                                        |                                                          |                                                                   |                                      |                                                | 
```