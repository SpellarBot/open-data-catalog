# Upcoming contracts to be awarded (CAP)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/upcoming-contracts-to-be-awarded-cap-77253) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/6m3u-8rbh) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/6m3u-8rbh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/6m3u-8rbh/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 6m3u-8rbh |
| Name | Upcoming contracts to be awarded (CAP) |
| Attribution | School Construction Authority (SCA) |
| Category | Housing & Development |
| Tags | school, construction, authority, sca, capital, improvement, project, design, complete, completion, bid, education |
| Created | 2013-08-22T19:00:41Z |
| Publication Date | 2017-03-08T21:23:25Z |

## Description

New school projects (Capacity) that will complete design within the next 6 months and will be available for bid.

## Columns

```ls
| Included | Schema Type    | Field Name                              | Name                                    | Data Type | Render Type |
| ======== | ============== | ======================================= | ======================================= | ========= | =========== |
| No       | time           | :updated_at                             | updated_at                              | meta_data | meta_data   |
| Yes      | series tag     | upcoming_project_name                   | Upcoming Project Name                   | text      | text        |
| Yes      | series tag     | upcoming_project_borough_               | Upcoming Project Borough                | text      | text        |
| Yes      | series tag     | upcoming_project_geographic_district    | Upcoming Project Geographic District    | text      | text        |
| Yes      | series tag     | upcoming_project_description            | Upcoming Project Description            | text      | text        |
| Yes      | series tag     | upcoming_project_budget_range           | Upcoming Project Budget Range           | text      | text        |
| No       |                | upcoming_project_design_completion_date | Upcoming Project Design Completion Date | text      | text        |
| Yes      | series tag     | upcoming_project_category               | Upcoming Project Category               | text      | text        |
| Yes      | series tag     | upcoming_project_status_                | Upcoming Project Status                 | text      | text        |
| Yes      | numeric metric | upcoming_project_square_footage         | Upcoming Project Square Footage         | number    | number      |
| Yes      | numeric metric | upcoming_project_seat_count             | Upcoming Project Seat Count             | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = upcoming_project_design_completion_date
```

## Data Commands

```ls
series e:6m3u-8rbh d:2017-03-08T21:23:17.000Z t:upcoming_project_budget_range="4 M OVER" t:upcoming_project_category=Additions t:upcoming_project_name="P.S. 19 - BRONX" t:upcoming_project_borough_=BRONX t:upcoming_project_description=Addition t:upcoming_project_status_=Design t:upcoming_project_geographic_district=11 m:upcoming_project_seat_count=400 m:upcoming_project_square_footage=55600

series e:6m3u-8rbh d:2017-03-08T21:23:17.000Z t:upcoming_project_budget_range="$0- $250K" t:upcoming_project_category=Additions t:upcoming_project_name="P.S. 97 - BRONX" t:upcoming_project_borough_=BRONX t:upcoming_project_description=Demo t:upcoming_project_status_=Scope t:upcoming_project_geographic_district=11 m:upcoming_project_seat_count=0 m:upcoming_project_square_footage=0

series e:6m3u-8rbh d:2017-03-08T21:23:17.000Z t:upcoming_project_budget_range="4 M OVER" t:upcoming_project_category=Additions t:upcoming_project_name="P.S. 32 ADDITION - BROOKLYN" t:upcoming_project_borough_=BROOKLYN t:upcoming_project_description=Addition t:upcoming_project_status_=Design t:upcoming_project_geographic_district=15 m:upcoming_project_seat_count=436 m:upcoming_project_square_footage=57579
```

## Meta Commands

```ls
metric m:upcoming_project_square_footage p:integer l:"Upcoming Project Square Footage" d:"Square footage for the building to be built" t:dataTypeName=number

metric m:upcoming_project_seat_count p:integer l:"Upcoming Project Seat Count" d:"Number of student seats" t:dataTypeName=number

entity e:6m3u-8rbh l:"Upcoming contracts to be awarded (CAP)" t:attribution="School Construction Authority (SCA)" t:url=https://data.cityofnewyork.us/api/views/6m3u-8rbh

property e:6m3u-8rbh t:meta.view v:id=6m3u-8rbh v:category="Housing & Development" v:attributionLink=http://www.nycsca.org/Business/WorkingWithTheSCA/Construction/ContractAwards/Pages/CAPAwards.aspx v:averageRating=0 v:name="Upcoming contracts to be awarded (CAP)" v:attribution="School Construction Authority (SCA)"

property e:6m3u-8rbh t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:6m3u-8rbh t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | upcoming_project_name                           | upcoming_project_borough_ | upcoming_project_geographic_district | upcoming_project_description | upcoming_project_budget_range | upcoming_project_design_completion_date | upcoming_project_category | upcoming_project_status_ | upcoming_project_square_footage | upcoming_project_seat_count | 
| =========== | =============================================== | ========================= | ==================================== | ============================ | ============================= | ======================================= | ========================= | ======================== | =============================== | =========================== | 
| 1489008197  | P.S. 19 - BRONX                                 | BRONX                     | 11                                   | Addition                     | 4 M OVER                      | 2017/04                                 | Additions                 | Design                   | 55600                           | 400                         | 
| 1489008197  | P.S. 97 - BRONX                                 | BRONX                     | 11                                   | Demo                         | $0- $250K                     | 2017/07                                 | Additions                 | Scope                    | 0                               | 0                           | 
| 1489008197  | P.S. 32 ADDITION - BROOKLYN                     | BROOKLYN                  | 15                                   | Addition                     | 4 M OVER                      | 2017/03                                 | Additions                 | Design                   | 57579                           | 436                         | 
| 1489008197  | P.S. 746 - BROOKLYN                             | BROOKLYN                  | 20                                   | New                          | 4 M OVER                      | 2017/03                                 | New Schools               | Design                   | 118431                          | 976                         | 
| 1489008197  | EDUCATIONAL CAMPUS @ 500 19TH STREET - BROOKLYN | BROOKLYN                  | 15                                   | Lease                        | 4 M OVER                      | 2017/04                                 | Leases                    | Design                   | 64911                           | 0                           | 
| 1489008197  | P.S./I.S. @ 3269 ATLANTIC AVENUE - BROOKLYN     | BROOKLYN                  | 19                                   | New                          | 4 M OVER                      | 2017/07                                 | New Schools               | Design                   | 118986                          | 1000                        | 
| 1489008197  | P.S. 143 - QUEENS                               | QUEENS                    | 24                                   | Addition                     | 4 M OVER                      | 2017/05                                 | Additions                 | Design                   | 99890                           | 980                         | 
| 1489008197  | P.S. 66 - QUEENS                                | QUEENS                    | 27                                   | Addition                     | 4 M OVER                      | 2017/01                                 | Additions                 | Design                   | 22900                           | 124                         | 
| 1489008197  | P.S. 144 - QUEENS                               | QUEENS                    | 28                                   | Addition                     | 4 M OVER                      | 2017/03                                 | Additions                 | Design                   | 55600                           | 590                         | 
| 1489008197  | P.S. 128 - QUEENS                               | QUEENS                    | 24                                   | Addition                     | 4 M OVER                      | 2017/04                                 | Additions                 | Design                   | 33608                           | 440                         | 
```