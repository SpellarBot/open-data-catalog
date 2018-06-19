# New York Public Library (NYPL) Branch Services from 7-2010 to 6-2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-york-public-library-nypl-branch-services-from-7-2010-to-6-2011-fd58f) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ne9z-skhf) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ne9z-skhf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ne9z-skhf/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ne9z-skhf |
| Name | New York Public Library (NYPL) Branch Services from 7-2010 to 6-2011 |
| Attribution | New York Public Library (NYPL) |
| Category | Recreation |
| Tags | libraries, culture, community, recreation, education |
| Created | 2011-09-29T17:33:28Z |
| Publication Date | 2013-06-21T20:26:48Z |

## Description

New York Public Library (NYPL) branch services from July 2010 to June 2011, by borough, network, program, attendance, and more.

## Columns

```ls
| Included | Schema Type    | Field Name                         | Name                               | Data Type | Render Type |
| ======== | ============== | ================================== | ================================== | ========= | =========== |
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
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ne9z-skhf d:2010-01-01T00:00:00.000Z t:branch=Allerton t:boro_central_library=Bronx t:network="Bronx Library Center Network" m:outreach_services_attendance=17 m:total_attendance=5401 m:adult_program=25 m:circulation_young_adult=20191 m:juvenile_program=183 m:circulation_adult=62767 m:weekly_hours_of_public_service=46 m:reference_transactions=145886 m:reference_transactions_juvenile=38038 m:juvenile_attendance=4714 m:circulation_juvenile=47961 m:circulation=130919 m:reference_transactions_young_adult=32253 m:young_adult_attendance=420 m:young_adult_program=37 m:reference_transactions_adult=75595 m:adult_attendance=250 m:total_program=246 m:outreach_services_program=1

series e:ne9z-skhf d:2010-01-01T00:00:00.000Z t:branch=Belmont t:boro_central_library=Bronx t:network="Bronx Library Center Network" m:outreach_services_attendance=740 m:total_attendance=12493 m:adult_program=226 m:circulation_young_adult=14614 m:juvenile_program=352 m:circulation_adult=61924 m:weekly_hours_of_public_service=46 m:reference_transactions=284271 m:reference_transactions_juvenile=94263 m:juvenile_attendance=6792 m:circulation_juvenile=42140 m:circulation=118678 m:reference_transactions_young_adult=93028 m:young_adult_attendance=2166 m:young_adult_program=186 m:reference_transactions_adult=96980 m:adult_attendance=2795 m:total_program=826 m:outreach_services_program=62

series e:ne9z-skhf d:2010-01-01T00:00:00.000Z t:branch="Bronx  Library Center" t:boro_central_library=Bronx t:network="Bronx Library Center Network" m:outreach_services_attendance=8151 m:total_attendance=40723 m:adult_program=449 m:circulation_young_adult=75239 m:juvenile_program=379 m:circulation_adult=354231 m:weekly_hours_of_public_service=78 m:reference_transactions=506012 m:reference_transactions_juvenile=173134 m:juvenile_attendance=13069 m:circulation_juvenile=184508 m:circulation=613978 m:reference_transactions_young_adult=78494 m:young_adult_attendance=4324 m:young_adult_program=201 m:reference_transactions_adult=254384 m:adult_attendance=15179 m:total_program=1332 m:outreach_services_program=303
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

entity e:ne9z-skhf l:"New York Public Library (NYPL) Branch Services from 7-2010 to 6-2011" t:attribution="New York Public Library (NYPL)" t:url=https://data.cityofnewyork.us/api/views/ne9z-skhf

property e:ne9z-skhf t:meta.view v:id=ne9z-skhf v:category=Recreation v:averageRating=0 v:name="New York Public Library (NYPL) Branch Services from 7-2010 to 6-2011" v:attribution="New York Public Library (NYPL)"

property e:ne9z-skhf t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ne9z-skhf t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| boro_central_library | network                      | branch               | adult_program | adult_attendance | young_adult_program | young_adult_attendance | juvenile_program | juvenile_attendance | outreach_services_program | outreach_services_attendance | total_program | total_attendance | reference_transactions_adult | reference_transactions_young_adult | reference_transactions_juvenile | reference_transactions | circulation_adult | circulation_young_adult | circulation_juvenile | circulation | weekly_hours_of_public_service | 
| ==================== | ============================ | ==================== | ============= | ================ | =================== | ====================== | ================ | =================== | ========================= | ============================ | ============= | ================ | ============================ | ================================== | =============================== | ====================== | ================= | ======================= | ==================== | =========== | ============================== | 
| Bronx                | Bronx Library Center Network | Allerton             | 25            | 250              | 37                  | 420                    | 183              | 4714                | 1                         | 17                           | 246           | 5401             | 75595                        | 32253                              | 38038                           | 145886                 | 62767             | 20191                   | 47961                | 130919      | 46                             | 
| Bronx                | Bronx Library Center Network | Belmont              | 226           | 2795             | 186                 | 2166                   | 352              | 6792                | 62                        | 740                          | 826           | 12493            | 96980                        | 93028                              | 94263                           | 284271                 | 61924             | 14614                   | 42140                | 118678      | 46                             | 
| Bronx                | Bronx Library Center Network | Bronx Library Center | 449           | 15179            | 201                 | 4324                   | 379              | 13069               | 303                       | 8151                         | 1332          | 40723            | 254384                       | 78494                              | 173134                          | 506012                 | 354231            | 75239                   | 184508               | 613978      | 78                             | 
| Bronx                | Bronx Library Center Network | Francis Martin       | 7             | 108              | 44                  | 506                    | 206              | 3805                | 18                        | 645                          | 275           | 5064             | 27469                        | 8112                               | 11609                           | 47190                  | 43431             | 15379                   | 37966                | 96776       | 46                             | 
| Bronx                | Bronx Library Center Network | Grand Concourse      | 228           | 1841             | 220                 | 2450                   | 349              | 8976                | 368                       | 5097                         | 1165          | 18364            | 44460                        | 17810                              | 17238                           | 79508                  | 77381             | 21413                   | 51671                | 150465      | 50                             | 
| Bronx                | Bronx Library Center Network | High Bridge          | 74            | 693              | 47                  | 591                    | 45               | 3403                | 40                        | 1549                         | 206           | 6236             | 36023                        | 17173                              | 16991                           | 70187                  | 54853             | 26971                   | 62964                | 144788      | 46                             | 
| Bronx                | Bronx Library Center Network | Jerome Park          | 94            | 424              | 106                 | 1828                   | 117              | 2321                | 7                         | 91                           | 324           | 4664             | 11479                        | 7462                               | 7566                            | 26507                  | 48450             | 15534                   | 38205                | 102189      | 46                             | 
| Bronx                | Bronx Library Center Network | Kingsbridge          | 15            | 661              | 82                  | 1066                   | 147              | 2862                | 117                       | 2189                         | 361           | 6778             | 24661                        | 5694                               | 6825                            | 37180                  | 96645             | 20455                   | 45262                | 162362      | 46                             | 
| Bronx                | Bronx Library Center Network | Morrisania           | 84            | 660              | 186                 | 4341                   | 316              | 5881                | 99                        | 2202                         | 685           | 13084            | 52780                        | 15327                              | 33787                           | 101894                 | 49208             | 16005                   | 36447                | 101660      | 46                             | 
| Bronx                | Bronx Library Center Network | Mosholu              | 119           | 1259             | 132                 | 1456                   | 198              | 5709                | 59                        | 1739                         | 508           | 10163            | 47619                        | 18499                              | 16302                           | 82420                  | 100420            | 27057                   | 106836               | 234313      | 46                             | 
```