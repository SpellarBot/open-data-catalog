# NYPL Branch Services - Manhattan

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nypl-branch-services-manhattan-abae8) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/3nja-bsch) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/3nja-bsch/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/3nja-bsch/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 3nja-bsch |
| Name | NYPL Branch Services - Manhattan |
| Attribution | New York Public Library (NYPL) |
| Category | Recreation |
| Tags | libraries, culture, community, recreation, education |
| Created | 2011-10-31T15:38:37Z |
| Publication Date | 2013-06-21T20:26:56Z |

## Description

New York Public Library (NYPL) branch services from July 2010 to June 2011(Manhattan)

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
series e:3nja-bsch d:2011-10-31T08:38:56.000Z t:branch="67th Street" t:boro_central_library=Manhattan t:network="Countee Cullen Network" m:outreach_services_attendance=834 m:total_attendance=12020 m:adult_program=146 m:circulation_young_adult=20149 m:juvenile_program=253 m:circulation_adult=173087 m:weekly_hours_of_public_service=42 m:reference_transactions=75049 m:reference_transactions_juvenile=5343 m:juvenile_attendance=9004 m:circulation_juvenile=112878 m:circulation=306114 m:reference_transactions_young_adult=3497 m:young_adult_attendance=884 m:young_adult_program=80 m:reference_transactions_adult=66209 m:adult_attendance=1298 m:total_program=550 m:outreach_services_program=71

series e:3nja-bsch d:2011-10-31T08:38:56.000Z t:branch="96th Street" t:boro_central_library=Manhattan t:network="Countee Cullen Network" m:outreach_services_attendance=706 m:total_attendance=13352 m:adult_program=154 m:circulation_young_adult=39402 m:juvenile_program=276 m:circulation_adult=228111 m:weekly_hours_of_public_service=50 m:reference_transactions=100542 m:reference_transactions_juvenile=9503 m:juvenile_attendance=8470 m:circulation_juvenile=105718 m:circulation=373231 m:reference_transactions_young_adult=19591 m:young_adult_attendance=1710 m:young_adult_program=90 m:reference_transactions_adult=71448 m:adult_attendance=2466 m:total_program=548 m:outreach_services_program=28

series e:3nja-bsch d:2011-10-31T08:38:56.000Z t:branch="115th Street" t:boro_central_library=Manhattan t:network="Countee Cullen Network" m:outreach_services_attendance=708 m:total_attendance=7623 m:adult_program=53 m:circulation_young_adult=16783 m:juvenile_program=142 m:circulation_adult=77833 m:weekly_hours_of_public_service=42 m:reference_transactions=25298 m:reference_transactions_juvenile=6903 m:juvenile_attendance=5382 m:circulation_juvenile=65517 m:circulation=160133 m:reference_transactions_young_adult=3471 m:young_adult_attendance=1036 m:young_adult_program=75 m:reference_transactions_adult=14924 m:adult_attendance=497 m:total_program=282 m:outreach_services_program=12
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

entity e:3nja-bsch l:"NYPL Branch Services - Manhattan" t:attribution="New York Public Library (NYPL)" t:url=https://data.cityofnewyork.us/api/views/3nja-bsch

property e:3nja-bsch t:meta.view v:id=3nja-bsch v:category=Recreation v:averageRating=0 v:name="NYPL Branch Services - Manhattan" v:attribution="New York Public Library (NYPL)"

property e:3nja-bsch t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:3nja-bsch t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | boro_central_library | network                | branch          | adult_program | adult_attendance | young_adult_program | young_adult_attendance | juvenile_program | juvenile_attendance | outreach_services_program | outreach_services_attendance | total_program | total_attendance | reference_transactions_adult | reference_transactions_young_adult | reference_transactions_juvenile | reference_transactions | circulation_adult | circulation_young_adult | circulation_juvenile | circulation | weekly_hours_of_public_service | 
| =========== | ==================== | ====================== | =============== | ============= | ================ | =================== | ====================== | ================ | =================== | ========================= | ============================ | ============= | ================ | ============================ | ================================== | =============================== | ====================== | ================= | ======================= | ==================== | =========== | ============================== | 
| 1320050336  | Manhattan            | Countee Cullen Network | 67th Street     | 146           | 1298             | 80                  | 884                    | 253              | 9004                | 71                        | 834                          | 550           | 12020            | 66209                        | 3497                               | 5343                            | 75049                  | 173087            | 20149                   | 112878               | 306114      | 42                             | 
| 1320050336  | Manhattan            | Countee Cullen Network | 96th Street     | 154           | 2466             | 90                  | 1710                   | 276              | 8470                | 28                        | 706                          | 548           | 13352            | 71448                        | 19591                              | 9503                            | 100542                 | 228111            | 39402                   | 105718               | 373231      | 50                             | 
| 1320050336  | Manhattan            | Countee Cullen Network | 115th Street    | 53            | 497              | 75                  | 1036                   | 142              | 5382                | 12                        | 708                          | 282           | 7623             | 14924                        | 3471                               | 6903                            | 25298                  | 77833             | 16783                   | 65517                | 160133      | 42                             | 
| 1320050336  | Manhattan            | Countee Cullen Network | 125th Street    | 116           | 1008             | 46                  | 345                    | 142              | 1311                | 67                        | 1015                         | 371           | 3679             | 23400                        | 8632                               | 11479                           | 43511                  | 45516             | 14352                   | 20366                | 80234       | 42                             | 
| 1320050336  | Manhattan            | Countee Cullen Network | Aguilar         | 29            | 524              | 28                  | 450                    | 364              | 8143                | 247                       | 3343                         | 668           | 12460            | 34502                        | 9711                               | 21281                           | 65494                  | 92228             | 26945                   | 89477                | 208650      | 44                             | 
| 1320050336  | Manhattan            | Countee Cullen Network | Bloomingdale    | 107           | 1241             | 105                 | 1245                   | 340              | 10626               | 21                        | 327                          | 573           | 13439            | 36608                        | 7527                               | 6019                            | 50154                  | 236267            | 30858                   | 133536               | 400661      | 44                             | 
| 1320050336  | Manhattan            | Countee Cullen Network | Countee Cullen  | 199           | 2330             | 159                 | 1676                   | 254              | 4053                | 20                        | 557                          | 632           | 8616             | 52780                        | 18941                              | 13182                           | 84903                  | 118246            | 21545                   | 59759                | 199550      | 54                             | 
| 1320050336  | Manhattan            | Countee Cullen Network | Fort Washington | 97            | 1387             | 124                 | 1544                   | 336              | 8990                | 158                       | 2911                         | 715           | 14832            | 29211                        | 9113                               | 13767                           | 52091                  | 170872            | 37962                   | 110765               | 319599      | 44                             | 
| 1320050336  | Manhattan            | Countee Cullen Network | George Bruce    | 81            | 833              | 94                  | 1432                   | 208              | 3607                | 42                        | 1058                         | 425           | 6930             | 327119                       | 256360                             | 282750                          | 866229                 | 67313             | 14443                   | 38463                | 120219      | 42                             | 
| 1320050336  | Manhattan            | Countee Cullen Network | Hamilton Grange | 137           | 2779             | 94                  | 1138                   | 115              | 3037                | 38                        | 996                          | 384           | 7950             | 77246                        | 30212                              | 35412                           | 142870                 | 110572            | 25338                   | 73395                | 209305      | 44                             | 
```