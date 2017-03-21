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
| Rows Updated | 2013-06-21T20:27:07Z |

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
series e:wibz-uqui d:2011-10-31T09:26:03.000Z t:branch="Dongan Hills" t:boro_central_library="Staten Island" t:network="Staten Island Network" m:outreach_services_attendance=8935 m:total_attendance=15368 m:adult_program=66 m:circulation_young_adult=13544 m:juvenile_program=165 m:circulation_adult=68168 m:weekly_hours_of_public_service=42 m:reference_transactions=36478 m:reference_transactions_juvenile=10764 m:juvenile_attendance=4105 m:circulation_juvenile=70811 m:circulation=152523 m:reference_transactions_young_adult=6318 m:young_adult_attendance=1005 m:young_adult_program=82 m:reference_transactions_adult=19396 m:adult_attendance=1323 m:total_program=480 m:outreach_services_program=167

series e:wibz-uqui d:2011-10-31T09:26:03.000Z t:branch="Great Kills" t:boro_central_library="Staten Island" t:network="Staten Island Network" m:outreach_services_attendance=3030 m:total_attendance=9906 m:adult_program=83 m:circulation_young_adult=14004 m:juvenile_program=215 m:circulation_adult=60629 m:weekly_hours_of_public_service=42 m:reference_transactions=57603 m:reference_transactions_juvenile=9126 m:juvenile_attendance=3809 m:circulation_juvenile=85539 m:circulation=160172 m:reference_transactions_young_adult=9074 m:young_adult_attendance=1412 m:young_adult_program=60 m:reference_transactions_adult=39403 m:adult_attendance=1655 m:total_program=432 m:outreach_services_program=74

series e:wibz-uqui d:2011-10-31T09:26:03.000Z t:branch="Huguenot Park" t:boro_central_library="Staten Island" t:network="Staten Island Network" m:outreach_services_attendance=278 m:total_attendance=5240 m:adult_program=94 m:circulation_young_adult=22124 m:juvenile_program=140 m:circulation_adult=98731 m:weekly_hours_of_public_service=44 m:reference_transactions=71292 m:reference_transactions_juvenile=18941 m:juvenile_attendance=3389 m:circulation_juvenile=124491 m:circulation=245346 m:reference_transactions_young_adult=15652 m:young_adult_attendance=400 m:young_adult_program=44 m:reference_transactions_adult=36699 m:adult_attendance=1173 m:total_program=288 m:outreach_services_program=10
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

property e:wibz-uqui t:meta.view v:id=wibz-uqui v:category=Recreation v:averageRating=0 v:name="NYPL Branch Services - Staten Island" v:attribution="New York Public Library (NYPL)"

property e:wibz-uqui t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:displayName="NYC OpenData"

property e:wibz-uqui t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"
```