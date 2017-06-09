# NYPL Branch Services - Staten Island

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nypl-branch-services-staten-island-a8c05) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/wibz-uqui) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/wibz-uqui/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/wibz-uqui/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | wibz-uqui |
| Name | NYPL Branch Services - Staten Island |
| Attribution | New York Public Library (NYPL) |
| Category | Recreation |
| Tags | libraries, culture, community, recreation, education |
| Created | 2011-10-31T16:25:49Z |
| Publication Date | 2013-06-21T20:27:11Z |

## Description

New York Public Library (NYPL) branch services from July 2010 to June 2011 (Staten Island)

## Columns

```ls
| Included | Schema Type    | Field Name                         | Name                               | Data Type | Render Type |
| ======== | ============== | ================================== | ================================== | ========= | =========== |
| No       | time           | :updated_at                        | updated_at                         | meta_data | meta_data   |
| Yes      | series tag     | boro_central_library               | Boro/Central Library               | text      | text        |
| Yes      | series tag     | network                            | Network                            | text      | text        |
| Yes      | series tag     | branch                             | Branch                             | text      | text        |
| Yes      | numeric metric | adult_program                      | ADULT Program                      | number    | number      |
| Yes      | numeric metric | adult_attendance                   | ADULT Attendance                   | number    | number      |
| Yes      | numeric metric | young_adult_program                | YOUNG ADULT Program                | number    | number      |
| Yes      | numeric metric | young_adult_attendance             | YOUNG ADULT Attendance             | number    | number      |
| Yes      | numeric metric | juvenile_program                   | JUVENILE Program                   | number    | number      |
| Yes      | numeric metric | juvenile_attendance                | JUVENILE Attendance                | number    | number      |
| Yes      | numeric metric | outreach_services_program          | OUTREACH SERVICES Program          | number    | number      |
| Yes      | numeric metric | outreach_services_attendance       | OUTREACH SERVICES Attendance       | number    | number      |
| Yes      | numeric metric | total_program                      | TOTAL Program                      | number    | number      |
| Yes      | numeric metric | total_attendance                   | TOTAL Attendance                   | number    | number      |
| Yes      | numeric metric | reference_transactions_adult       | REFERENCE TRANSACTIONS Adult       | number    | number      |
| Yes      | numeric metric | reference_transactions_young_adult | REFERENCE TRANSACTIONS Young Adult | number    | number      |
| Yes      | numeric metric | reference_transactions_juvenile    | REFERENCE TRANSACTIONS Juvenile    | number    | number      |
| Yes      | numeric metric | reference_transactions             | REFERENCE TRANSACTIONS             | number    | number      |
| Yes      | numeric metric | circulation_adult                  | CIRCULATION Adult                  | number    | number      |
| Yes      | numeric metric | circulation_young_adult            | CIRCULATION Young Adult            | number    | number      |
| Yes      | numeric metric | circulation_juvenile               | CIRCULATION Juvenile               | number    | number      |
| Yes      | numeric metric | circulation                        | CIRCULATION                        | number    | number      |
| Yes      | numeric metric | weekly_hours_of_public_service     | Weekly Hours of Public Service     | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:wibz-uqui d:2011-10-31T09:26:03.000Z t:branch="Dongan Hills" t:boro_central_library="Staten Island" t:network="Staten Island Network" m:outreach_services_attendance=8935 m:total_attendance=15368 m:adult_program=66 m:circulation_young_adult=13544 m:juvenile_program=165 m:circulation_adult=68168 m:weekly_hours_of_public_service=42 m:reference_transactions=36478 m:reference_transactions_juvenile=10764 m:juvenile_attendance=4105 m:circulation_juvenile=70811 m:circulation=152523 m:reference_transactions_young_adult=6318 m:reference_transactions_adult=19396 m:young_adult_program=82 m:young_adult_attendance=1005 m:adult_attendance=1323 m:total_program=480 m:outreach_services_program=167

series e:wibz-uqui d:2011-10-31T09:26:03.000Z t:branch="Great Kills" t:boro_central_library="Staten Island" t:network="Staten Island Network" m:outreach_services_attendance=3030 m:total_attendance=9906 m:adult_program=83 m:circulation_young_adult=14004 m:juvenile_program=215 m:circulation_adult=60629 m:weekly_hours_of_public_service=42 m:reference_transactions=57603 m:reference_transactions_juvenile=9126 m:juvenile_attendance=3809 m:circulation_juvenile=85539 m:circulation=160172 m:reference_transactions_young_adult=9074 m:reference_transactions_adult=39403 m:young_adult_program=60 m:young_adult_attendance=1412 m:adult_attendance=1655 m:total_program=432 m:outreach_services_program=74

series e:wibz-uqui d:2011-10-31T09:26:03.000Z t:branch="Huguenot Park" t:boro_central_library="Staten Island" t:network="Staten Island Network" m:outreach_services_attendance=278 m:total_attendance=5240 m:adult_program=94 m:circulation_young_adult=22124 m:juvenile_program=140 m:circulation_adult=98731 m:weekly_hours_of_public_service=44 m:reference_transactions=71292 m:reference_transactions_juvenile=18941 m:juvenile_attendance=3389 m:circulation_juvenile=124491 m:circulation=245346 m:reference_transactions_young_adult=15652 m:reference_transactions_adult=36699 m:young_adult_program=44 m:young_adult_attendance=400 m:adult_attendance=1173 m:total_program=288 m:outreach_services_program=10
```

## Meta Commands

```ls
metric m:adult_program p:integer l:"ADULT Program" t:dataTypeName=number

metric m:adult_attendance p:integer l:"ADULT Attendance" t:dataTypeName=number

metric m:young_adult_program p:integer l:"YOUNG ADULT Program" t:dataTypeName=number

metric m:young_adult_attendance p:integer l:"YOUNG ADULT Attendance" t:dataTypeName=number

metric m:juvenile_program p:integer l:"JUVENILE Program" t:dataTypeName=number

metric m:juvenile_attendance p:integer l:"JUVENILE Attendance" t:dataTypeName=number

metric m:outreach_services_program p:integer l:"OUTREACH SERVICES Program" t:dataTypeName=number

metric m:outreach_services_attendance p:integer l:"OUTREACH SERVICES Attendance" t:dataTypeName=number

metric m:total_program p:integer l:"TOTAL Program" t:dataTypeName=number

metric m:total_attendance p:integer l:"TOTAL Attendance" t:dataTypeName=number

metric m:reference_transactions_adult p:integer l:"REFERENCE TRANSACTIONS Adult" t:dataTypeName=number

metric m:reference_transactions_young_adult p:integer l:"REFERENCE TRANSACTIONS Young Adult" t:dataTypeName=number

metric m:reference_transactions_juvenile p:integer l:"REFERENCE TRANSACTIONS Juvenile" t:dataTypeName=number

metric m:reference_transactions p:integer l:"REFERENCE TRANSACTIONS" t:dataTypeName=number

metric m:circulation_adult p:integer l:"CIRCULATION Adult" t:dataTypeName=number

metric m:circulation_young_adult p:integer l:"CIRCULATION Young Adult" t:dataTypeName=number

metric m:circulation_juvenile p:integer l:"CIRCULATION Juvenile" t:dataTypeName=number

metric m:circulation p:integer l:CIRCULATION t:dataTypeName=number

metric m:weekly_hours_of_public_service p:integer l:"Weekly Hours of Public Service" t:dataTypeName=number

entity e:wibz-uqui l:"NYPL Branch Services - Staten Island" t:attribution="New York Public Library (NYPL)" t:url=https://data.cityofnewyork.us/api/views/wibz-uqui

property e:wibz-uqui t:meta.view d:2017-06-09T13:52:18.002Z v:id=wibz-uqui v:category=Recreation v:averageRating=0 v:name="NYPL Branch Services - Staten Island" v:attribution="New York Public Library (NYPL)"

property e:wibz-uqui t:meta.view.owner d:2017-06-09T13:52:18.002Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1496414226 v:displayName="NYC OpenData"

property e:wibz-uqui t:meta.view.tableauthor d:2017-06-09T13:52:18.002Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1496414226 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | boro_central_library | network               | branch                                                       | adult_program | adult_attendance | young_adult_program | young_adult_attendance | juvenile_program | juvenile_attendance | outreach_services_program | outreach_services_attendance | total_program | total_attendance | reference_transactions_adult | reference_transactions_young_adult | reference_transactions_juvenile | reference_transactions | circulation_adult | circulation_young_adult | circulation_juvenile | circulation | weekly_hours_of_public_service | 
| =========== | ==================== | ===================== | ============================================================ | ============= | ================ | =================== | ====================== | ================ | =================== | ========================= | ============================ | ============= | ================ | ============================ | ================================== | =============================== | ====================== | ================= | ======================= | ==================== | =========== | ============================== | 
| 1320053163  | Staten Island        | Staten Island Network | Dongan Hills                                                 | 66            | 1323             | 82                  | 1005                   | 165              | 4105                | 167                       | 8935                         | 480           | 15368            | 19396                        | 6318                               | 10764                           | 36478                  | 68168             | 13544                   | 70811                | 152523      | 42                             | 
| 1320053163  | Staten Island        | Staten Island Network | Great Kills                                                  | 83            | 1655             | 60                  | 1412                   | 215              | 3809                | 74                        | 3030                         | 432           | 9906             | 39403                        | 9074                               | 9126                            | 57603                  | 60629             | 14004                   | 85539                | 160172      | 42                             | 
| 1320053163  | Staten Island        | Staten Island Network | Huguenot Park                                                | 94            | 1173             | 44                  | 400                    | 140              | 3389                | 10                        | 278                          | 288           | 5240             | 36699                        | 15652                              | 18941                           | 71292                  | 98731             | 22124                   | 124491               | 245346      | 44                             | 
| 1320053163  | Staten Island        | Staten Island Network | New Dorp                                                     | 141           | 1570             | 72                  | 873                    | 181              | 4312                | 217                       | 5319                         | 611           | 12074            | 152763                       | 77844                              | 98735                           | 329342                 | 125685            | 23400                   | 108050               | 257135      | 46                             | 
| 1320053163  | Staten Island        | Staten Island Network | Port Richmond                                                | 35            | 543              | 109                 | 1130                   | 177              | 5298                | 138                       | 1957                         | 459           | 8928             | 18811                        | 6422                               | 8840                            | 34073                  | 43650             | 11198                   | 35952                | 90800       | 46                             | 
| 1320053163  | Staten Island        | Staten Island Network | Richmondtown                                                 | 47            | 1170             | 61                  | 563                    | 182              | 4701                | 20                        | 618                          | 310           | 7052             | 179179                       | 17732                              | 38844                           | 235755                 | 123762            | 17813                   | 100290               | 241865      | 46                             | 
| 1320053163  | Staten Island        | Staten Island Network | South Beach                                                  | 59            | 929              | 44                  | 287                    | 212              | 5003                | 57                        | 3392                         | 372           | 9611             | 29809                        | 8684                               | 20982                           | 59475                  | 59069             | 13752                   | 66888                | 139709      | 42                             | 
| 1320053163  | Staten Island        | Staten Island Network | St. George Library Center                                    | 112           | 1299             | 365                 | 2862                   | 207              | 3604                | 368                       | 3801                         | 1052          | 11566            | 63089                        | 18005                              | 19461                           | 100555                 | 167522            | 25978                   | 75200                | 268700      | 62                             | 
| 1320053163  | Staten Island        | Staten Island Network | Stapleton* * Closed for major renovation - effective 4/15/10 | 0             | 0                | 0                   | 0                      | 0                | 0                   | 0                         | 0                            | 0             | 0                | 0                            | 0                                  | 0                               | 0                      | 170               | 32                      | 141                  | 343         | 0                              | 
| 1320053163  | Staten Island        | Staten Island Network | Todt-Hill Westerleigh                                        | 57            | 458              | 35                  | 507                    | 147              | 3257                | 52                        | 1664                         | 291           | 5886             | 82589                        | 23517                              | 22516                           | 128622                 | 258937            | 53328                   | 295016               | 607281      | 50                             | 
```