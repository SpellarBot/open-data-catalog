# Performance Dashboard - Multi-Measure - MHEC, IAC, GOMA

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/performance-dashboard-multi-measure-mhec-iac-goma) |
| Metadata | [Link](https://data.maryland.gov/api/views/fvuq-srf8) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/fvuq-srf8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/fvuq-srf8/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | fvuq-srf8 |
| Name | Performance Dashboard - Multi-Measure - MHEC, IAC, GOMA |
| Attribution | Governor's Office of Performance Improvement |
| Category | Education |
| Tags | degrees, degree attainment, maryland higher education commission, mhec, school facility, minority business enterprise, mbe, small business reserve, sbr, census bureau, interagency council on schoo... |
| Created | 2016-09-26T20:04:46Z |
| Publication Date | 2016-10-19T19:19:23Z |

## Description

An aggregated, multi-agency data set with information on college degrees, statewide degree attainment, average school facility age, school facility maintenance evaluation, and Minority Business Enterprise (MBE) and Small-Business Reserve (SBR) program participation.  The data set contains data from the Maryland Higher Education Commission (MHEC), the US Census Bureau, the Inter-Agency Council on School Construction (IAC), and the Governor's Office of Minority Affairs (GOMA)

## Columns

```ls
| Included | Schema Type    | Field Name                                                      | Name                                                                    | Data Type     | Render Type   |
| ======== | ============== | =============================================================== | ======================================================================= | ============= | ============= |
| Yes      | time           | date                                                            | Date                                                                    | calendar_date | calendar_date |
| No       |                | year                                                            | Fiscal Year                                                             | number        | text          |
| Yes      | numeric metric | post_secondary_degrees                                          | Post-secondary Degrees                                                  | number        | number        |
| Yes      | numeric metric | associate_degrees_fy                                            | Associate Degrees - FY                                                  | number        | number        |
| Yes      | numeric metric | bachelor_s_degree_fy                                            | Bachelor's Degree - FY                                                  | number        | number        |
| Yes      | numeric metric | master_s_degree_fy                                              | Master's Degree - FY                                                    | number        | number        |
| Yes      | numeric metric | doctoral_1st_professional_degree_fy                             | Doctoral/1st Professional Degree - FY                                   | number        | number        |
| Yes      | numeric metric | doctoral_degree_fy                                              | Doctoral Degree - FY                                                    | number        | number        |
| Yes      | numeric metric | 1st_professional_degree_fy                                      | 1st Professional Degree - FY                                            | number        | number        |
| Yes      | numeric metric | statewide_average_age_of_facility_square_footage_fy             | Statewide average age of facility square footage - FY                   | number        | number        |
| Yes      | numeric metric | facility_maintainance_inspection_result_superior_or_good_fy     | Facility Maintainance Inspection Result - "Superior" or "Good" - FY     | percent       | percent       |
| Yes      | numeric metric | facility_maintainance_inspection_result_adequate_fy             | Facility Maintainance Inspection Result - "Adequate" - FY               | percent       | percent       |
| Yes      | numeric metric | facility_maintainance_inspection_result_not_adequate_or_poor_fy | Facility Maintainance Inspection Result - "Not Adequate" or "Poor" - FY | percent       | percent       |
| Yes      | numeric metric | percent_awarded_to_mbe_fy                                       | Percent awarded to MBE - FY                                             | percent       | percent       |
| Yes      | numeric metric | percent_paid_to_certified_small_businesses_fy                   | Percent paid to certified small businesses - FY                         | percent       | percent       |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = year
```

## Data Commands

```ls
series e:fvuq-srf8 d:2006-06-30T00:00:00.000Z m:doctoral_degree_fy=1363 m:associate_degrees_fy=10141 m:bachelor_s_degree_fy=25484 m:master_s_degree_fy=13265 m:doctoral_1st_professional_degree_fy=2485 m:1st_professional_degree_fy=1122 m:post_secondary_degrees=53860

series e:fvuq-srf8 d:2007-06-30T00:00:00.000Z m:doctoral_degree_fy=1370 m:associate_degrees_fy=10415 m:bachelor_s_degree_fy=25586 m:master_s_degree_fy=14021 m:percent_paid_to_certified_small_businesses_fy=6 m:doctoral_1st_professional_degree_fy=2509 m:1st_professional_degree_fy=1139 m:post_secondary_degrees=55040 m:percent_awarded_to_mbe_fy=20

series e:fvuq-srf8 d:2008-06-30T00:00:00.000Z m:doctoral_degree_fy=1461 m:associate_degrees_fy=11051 m:bachelor_s_degree_fy=26070 m:master_s_degree_fy=14488 m:percent_paid_to_certified_small_businesses_fy=5.9 m:doctoral_1st_professional_degree_fy=2561 m:1st_professional_degree_fy=1100 m:post_secondary_degrees=56731 m:percent_awarded_to_mbe_fy=20.3
```

## Meta Commands

```ls
metric m:post_secondary_degrees p:integer l:"Post-secondary Degrees" t:dataTypeName=number

metric m:associate_degrees_fy p:integer l:"Associate Degrees - FY" d:"number of Associate's degrees conferred by public and private colleges and universities in Maryland" t:dataTypeName=number

metric m:bachelor_s_degree_fy p:integer l:"Bachelor's Degree - FY" d:"number of Bachelor's degrees conferred by public and private colleges and universities in Maryland" t:dataTypeName=number

metric m:master_s_degree_fy p:integer l:"Master's Degree - FY" d:"number of Master's degrees conferred by public and private colleges and universities in Maryland" t:dataTypeName=number

metric m:doctoral_1st_professional_degree_fy p:integer l:"Doctoral/1st Professional Degree - FY" d:"number of Doctoral and First Professional degrees conferred by public and private colleges and universities in Maryland" t:dataTypeName=number

metric m:doctoral_degree_fy p:integer l:"Doctoral Degree - FY" d:"number of Doctoral degrees conferred by public and private colleges and universities in Maryland" t:dataTypeName=number

metric m:1st_professional_degree_fy p:integer l:"1st Professional Degree - FY" d:"number of 1st Professional degrees conferred by public and private colleges and universities in Maryland" t:dataTypeName=number

metric m:statewide_average_age_of_facility_square_footage_fy p:integer l:"Statewide average age of facility square footage - FY" d:"This represents the average age of Maryland public school facilities" t:dataTypeName=number

metric m:facility_maintainance_inspection_result_superior_or_good_fy p:integer l:"Facility Maintainance Inspection Result - ""Superior"" or ""Good"" - FY" d:"percent of Maryland public school facilities that earn a ""Superior"" or ""Good"" rating on the annual facilities maintenance inspection" t:dataTypeName=percent

metric m:facility_maintainance_inspection_result_adequate_fy p:integer l:"Facility Maintainance Inspection Result - ""Adequate"" - FY" d:"percent of Maryland public school facilities that earn an ""Adequate"" rating on the annual facilities maintenance inspection" t:dataTypeName=percent

metric m:facility_maintainance_inspection_result_not_adequate_or_poor_fy p:integer l:"Facility Maintainance Inspection Result - ""Not Adequate"" or ""Poor"" - FY" d:"percent of Maryland public school facilities that earn a ""Not Adequate"" or ""Poor"" rating on the annual facilities maintenance inspection" t:dataTypeName=percent

metric m:percent_awarded_to_mbe_fy p:float l:"Percent awarded to MBE - FY" d:"percentage of Maryland contracts awarded to certified minority-owned businesses" t:dataTypeName=percent

metric m:percent_paid_to_certified_small_businesses_fy p:float l:"Percent paid to certified small businesses - FY" t:dataTypeName=percent

entity e:fvuq-srf8 l:"Performance Dashboard - Multi-Measure - MHEC, IAC, GOMA" t:attribution="Governor's Office of Performance Improvement" t:url=https://data.maryland.gov/api/views/fvuq-srf8

property e:fvuq-srf8 t:meta.view v:id=fvuq-srf8 v:category=Education v:attributionLink=http://gopi.maryland.gov/ v:averageRating=0 v:name="Performance Dashboard - Multi-Measure - MHEC, IAC, GOMA" v:attribution="Governor's Office of Performance Improvement"

property e:fvuq-srf8 t:meta.view.license v:name="Public Domain"

property e:fvuq-srf8 t:meta.view.owner v:id=9ei4-2q5c v:screenName="Pat Pscherer" v:displayName="Pat Pscherer"

property e:fvuq-srf8 t:meta.view.tableauthor v:id=9ei4-2q5c v:screenName="Pat Pscherer" v:roleName=administrator v:displayName="Pat Pscherer"
```

## Top Records

```ls
| date                | year | post_secondary_degrees | associate_degrees_fy | bachelor_s_degree_fy | master_s_degree_fy | doctoral_1st_professional_degree_fy | doctoral_degree_fy | 1st_professional_degree_fy | statewide_average_age_of_facility_square_footage_fy | facility_maintainance_inspection_result_superior_or_good_fy | facility_maintainance_inspection_result_adequate_fy | facility_maintainance_inspection_result_not_adequate_or_poor_fy | percent_awarded_to_mbe_fy | percent_paid_to_certified_small_businesses_fy | 
| =================== | ==== | ====================== | ==================== | ==================== | ================== | =================================== | ================== | ========================== | =================================================== | =========================================================== | =================================================== | =============================================================== | ========================= | ============================================= | 
| 2006-06-30T00:00:00 | 2006 | 53860                  | 10141                | 25484                | 13265              | 2485                                | 1363               | 1122                       |                                                     |                                                             |                                                     |                                                                 |                           |                                               | 
| 2007-06-30T00:00:00 | 2007 | 55040                  | 10415                | 25586                | 14021              | 2509                                | 1370               | 1139                       |                                                     |                                                             |                                                     |                                                                 | 20                        | 6                                             | 
| 2008-06-30T00:00:00 | 2008 | 56731                  | 11051                | 26070                | 14488              | 2561                                | 1461               | 1100                       |                                                     |                                                             |                                                     |                                                                 | 20.30                     | 5.90                                          | 
| 2009-06-30T00:00:00 | 2009 | 59378                  | 11287                | 28020                | 15055              | 2508                                | 2508               | 0                          |                                                     |                                                             |                                                     |                                                                 | 22.20                     | 5.60                                          | 
| 2010-06-30T00:00:00 | 2010 | 61858                  | 12077                | 28809                | 15644              | 2664                                | 2664               | 0                          |                                                     |                                                             |                                                     |                                                                 | 23.20                     | 6.20                                          | 
| 2011-06-30T00:00:00 | 2011 | 65259                  | 13248                | 30298                | 16357              | 2678                                | 2678               | 0                          | 27                                                  | 64                                                          | 33                                                  | 3                                                               | 23.80                     | 6.10                                          | 
| 2012-06-30T00:00:00 | 2012 | 69356                  | 14427                | 32005                | 17326              | 2799                                | 2799               | 0                          | 27                                                  | 67                                                          | 30                                                  | 3                                                               | 25.20                     | 6.20                                          | 
| 2013-06-30T00:00:00 | 2013 | 71761                  | 14802                | 33045                | 17872              | 3021                                | 3021               | 0                          | 28                                                  | 67                                                          | 30                                                  | 3                                                               | 24.40                     | 9                                             | 
| 2014-06-30T00:00:00 | 2014 | 72177                  | 15122                | 33322                | 17937              | 2898                                | 2898               | 0                          | 28                                                  | 67                                                          | 30                                                  | 3                                                               | 27.30                     | 11.80                                         | 
| 2015-06-30T00:00:00 | 2015 | 75449                  | 16346                | 34896                | 18227              | 2990                                | 2990               | 0                          | 28                                                  |                                                             |                                                     |                                                                 | 26.20                     | 10.60                                         | 
```