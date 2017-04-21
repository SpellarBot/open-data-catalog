# Recreation and Parks - Performance Metrics

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/recreation-and-parks-performance-metrics) |
| Metadata | [Link](https://data.lacity.org/api/views/bh4k-73tk) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/bh4k-73tk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/bh4k-73tk/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | bh4k-73tk |
| Name | Recreation and Parks - Performance Metrics |
| Category | A Livable and Sustainable City |
| Created | 2014-08-26T15:58:46Z |
| Publication Date | 2015-04-22T20:09:47Z |

## Columns

```ls
| Included | Schema Type    | Field Name                                                                  | Name                                                                             | Data Type     | Render Type   |
| ======== | ============== | =========================================================================== | ================================================================================ | ============= | ============= |
| Yes      | time           | date_value                                                                  | Date Value                                                                       | calendar_date | calendar_date |
| Yes      | numeric metric | month_year                                                                  | Month-Year                                                                       | number        | text          |
| No       |                | quarter_fy                                                                  | Quarter-FY                                                                       | text          | text          |
| Yes      | series tag     | annual_fy                                                                   | Annual-FY                                                                        | text          | text          |
| Yes      | numeric metric | total_visitors_to_museums_excluding_griffith_observatory_annually_fy        | Total visitors to museums (excluding Griffith Observatory) (Annually-FY)         | number        | number        |
| Yes      | numeric metric | target_total_visitors_to_museums_excluding_griffith_observatory_annually_fy | TARGET: Total visitors to museums (excluding Griffith Observatory) (Annually-FY) | number        | number        |
| Yes      | numeric metric | number_of_visitors_to_griffith_observatory_annually_fy                      | Number of visitors to Griffith Observatory (Annually FY)                         | number        | number        |
| Yes      | numeric metric | target_number_of_visitors_to_griffith_observatory_annually_fy               | TARGET: Number of visitors to Griffith Observatory (Annually FY)                 | number        | number        |
| Yes      | numeric metric | number_of_cultural_program_and_class_registrations_quarterly                | Number of Cultural Program and Class Registrations(Quarterly)                    | number        | number        |
| Yes      | numeric metric | target_number_of_cultural_program_and_class_registrations_quarterly         | TARGET: Number of Cultural Program and Class Registrations(Quarterly)            | number        | number        |
| Yes      | numeric metric | number_of_cultural_program_and_class_participants_quarterly                 | Number of Cultural Program and Class Participants (Quarterly)                    | number        | number        |
| Yes      | numeric metric | target_number_of_cultural_program_and_class_participants_quarterly          | TARGET: Number of Cultural Program and Class Participants (Quarterly)            | number        | number        |
| Yes      | numeric metric | number_of_youth_and_adult_sport_registrations_quarterly                     | Number of Youth and Adult Sport Registrations(Quarterly)                         | number        | number        |
| Yes      | numeric metric | target_number_of_youth_and_adult_sport_registrations_quarterly              | TARGET: Number of Youth and Adult Sport Registrations (Quarterly)                | number        | number        |
| Yes      | numeric metric | number_of_youth_and_adult_sport_participants_quarterly                      | Number of Youth and Adult Sport Participants (Quarterly)                         | number        | number        |
| Yes      | numeric metric | target_number_of_youth_and_adult_sport_participants_quarterly               | TARGET: Number of Youth and Adult Sport Participants (Quarterly)                 | number        | number        |
| Yes      | numeric metric | number_of_golf_rounds_played_quarterly                                      | Number of Golf Rounds Played (Quarterly)                                         | number        | number        |
| Yes      | numeric metric | target_number_of_golf_rounds_played_quarterly                               | TARGET: Number of Golf Rounds Played (Quarterly)                                 | number        | number        |
| Yes      | numeric metric | total_attendance_at_city_aquatic_facilities_annually                        | Total attendance at City aquatic facilities (Annually)                           | number        | number        |
| Yes      | numeric metric | target_total_attendance_at_city_aquatic_facilities_annually                 | TARGET: Total attendance at City aquatic facilities (Annually)                   | number        | number        |
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
series e:bh4k-73tk d:2010-06-30T00:00:00.000Z t:annual_fy="FY 2010" m:month_year=41800

series e:bh4k-73tk d:2010-07-31T00:00:00.000Z m:month_year=41830

series e:bh4k-73tk d:2010-08-31T00:00:00.000Z m:month_year=41861
```

## Meta Commands

```ls
metric m:month_year p:integer l:Month-Year t:dataTypeName=number

metric m:total_visitors_to_museums_excluding_griffith_observatory_annually_fy p:integer l:"Total visitors to museums (excluding Griffith Observatory) (Annually-FY)" t:dataTypeName=number

metric m:target_total_visitors_to_museums_excluding_griffith_observatory_annually_fy p:integer l:"TARGET: Total visitors to museums (excluding Griffith Observatory) (Annually-FY)" t:dataTypeName=number

metric m:number_of_visitors_to_griffith_observatory_annually_fy p:integer l:"Number of visitors to Griffith Observatory (Annually FY)" t:dataTypeName=number

metric m:target_number_of_visitors_to_griffith_observatory_annually_fy p:integer l:"TARGET: Number of visitors to Griffith Observatory (Annually FY)" t:dataTypeName=number

metric m:number_of_cultural_program_and_class_registrations_quarterly p:integer l:"Number of Cultural Program and Class Registrations(Quarterly)" t:dataTypeName=number

metric m:target_number_of_cultural_program_and_class_registrations_quarterly p:integer l:"TARGET: Number of Cultural Program and Class Registrations(Quarterly)" t:dataTypeName=number

metric m:number_of_cultural_program_and_class_participants_quarterly p:integer l:"Number of Cultural Program and Class Participants (Quarterly)" t:dataTypeName=number

metric m:target_number_of_cultural_program_and_class_participants_quarterly p:integer l:"TARGET: Number of Cultural Program and Class Participants (Quarterly)" t:dataTypeName=number

metric m:number_of_youth_and_adult_sport_registrations_quarterly p:integer l:"Number of Youth and Adult Sport Registrations(Quarterly)" t:dataTypeName=number

metric m:target_number_of_youth_and_adult_sport_registrations_quarterly p:integer l:"TARGET: Number of Youth and Adult Sport Registrations (Quarterly)" t:dataTypeName=number

metric m:number_of_youth_and_adult_sport_participants_quarterly p:integer l:"Number of Youth and Adult Sport Participants (Quarterly)" t:dataTypeName=number

metric m:target_number_of_youth_and_adult_sport_participants_quarterly p:integer l:"TARGET: Number of Youth and Adult Sport Participants (Quarterly)" t:dataTypeName=number

metric m:number_of_golf_rounds_played_quarterly p:integer l:"Number of Golf Rounds Played (Quarterly)" t:dataTypeName=number

metric m:target_number_of_golf_rounds_played_quarterly p:integer l:"TARGET: Number of Golf Rounds Played (Quarterly)" t:dataTypeName=number

metric m:total_attendance_at_city_aquatic_facilities_annually p:integer l:"Total attendance at City aquatic facilities (Annually)" t:dataTypeName=number

metric m:target_total_attendance_at_city_aquatic_facilities_annually p:integer l:"TARGET: Total attendance at City aquatic facilities (Annually)" t:dataTypeName=number

entity e:bh4k-73tk l:"Recreation and Parks - Performance Metrics" t:url=https://data.lacity.org/api/views/bh4k-73tk

property e:bh4k-73tk t:meta.view v:id=bh4k-73tk v:category="A Livable and Sustainable City" v:averageRating=0 v:name="Recreation and Parks - Performance Metrics"

property e:bh4k-73tk t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:bh4k-73tk t:meta.view.owner v:id=tyhz-nfmm v:screenName="Miguel Sangalang" v:displayName="Miguel Sangalang"

property e:bh4k-73tk t:meta.view.tableauthor v:id=tyhz-nfmm v:screenName="Miguel Sangalang" v:roleName=publisher v:displayName="Miguel Sangalang"
```

## Top Records

```ls
| date_value          | month_year | quarter_fy | annual_fy | total_visitors_to_museums_excluding_griffith_observatory_annually_fy | target_total_visitors_to_museums_excluding_griffith_observatory_annually_fy | number_of_visitors_to_griffith_observatory_annually_fy | target_number_of_visitors_to_griffith_observatory_annually_fy | number_of_cultural_program_and_class_registrations_quarterly | target_number_of_cultural_program_and_class_registrations_quarterly | number_of_cultural_program_and_class_participants_quarterly | target_number_of_cultural_program_and_class_participants_quarterly | number_of_youth_and_adult_sport_registrations_quarterly | target_number_of_youth_and_adult_sport_registrations_quarterly | number_of_youth_and_adult_sport_participants_quarterly | target_number_of_youth_and_adult_sport_participants_quarterly | number_of_golf_rounds_played_quarterly | target_number_of_golf_rounds_played_quarterly | total_attendance_at_city_aquatic_facilities_annually | target_total_attendance_at_city_aquatic_facilities_annually | 
| =================== | ========== | ========== | ========= | ==================================================================== | =========================================================================== | ====================================================== | ============================================================= | ============================================================ | =================================================================== | =========================================================== | ================================================================== | ======================================================= | ============================================================== | ====================================================== | ============================================================= | ====================================== | ============================================= | ==================================================== | =========================================================== | 
| 2010-06-30T00:00:00 | 41800      | Q4 FY10    | FY 2010   |                                                                      |                                                                             |                                                        |                                                               |                                                              |                                                                     |                                                             |                                                                    |                                                         |                                                                |                                                        |                                                               |                                        |                                               |                                                      |                                                             | 
| 2010-07-31T00:00:00 | 41830      |            |           |                                                                      |                                                                             |                                                        |                                                               |                                                              |                                                                     |                                                             |                                                                    |                                                         |                                                                |                                                        |                                                               |                                        |                                               |                                                      |                                                             | 
| 2010-08-31T00:00:00 | 41861      |            |           |                                                                      |                                                                             |                                                        |                                                               |                                                              |                                                                     |                                                             |                                                                    |                                                         |                                                                |                                                        |                                                               |                                        |                                               |                                                      |                                                             | 
| 2010-09-30T00:00:00 | 41892      | Q1 FY11    |           |                                                                      |                                                                             |                                                        |                                                               |                                                              |                                                                     |                                                             |                                                                    |                                                         |                                                                |                                                        |                                                               |                                        |                                               |                                                      |                                                             | 
| 2010-10-31T00:00:00 | 41922      |            |           |                                                                      |                                                                             |                                                        |                                                               |                                                              |                                                                     |                                                             |                                                                    |                                                         |                                                                |                                                        |                                                               |                                        |                                               |                                                      |                                                             | 
| 2010-11-30T00:00:00 | 41953      |            |           |                                                                      |                                                                             |                                                        |                                                               |                                                              |                                                                     |                                                             |                                                                    |                                                         |                                                                |                                                        |                                                               |                                        |                                               |                                                      |                                                             | 
| 2010-12-31T00:00:00 | 41983      | Q2 FY11    |           |                                                                      |                                                                             |                                                        |                                                               |                                                              |                                                                     |                                                             |                                                                    |                                                         |                                                                |                                                        |                                                               |                                        |                                               |                                                      |                                                             | 
| 2011-01-31T00:00:00 | 41650      |            |           |                                                                      |                                                                             |                                                        |                                                               |                                                              |                                                                     |                                                             |                                                                    |                                                         |                                                                |                                                        |                                                               |                                        |                                               |                                                      |                                                             | 
| 2011-02-28T00:00:00 | 41681      |            |           |                                                                      |                                                                             |                                                        |                                                               |                                                              |                                                                     |                                                             |                                                                    |                                                         |                                                                |                                                        |                                                               |                                        |                                               |                                                      |                                                             | 
| 2011-03-31T00:00:00 | 41709      | Q3 FY11    |           |                                                                      |                                                                             |                                                        |                                                               |                                                              |                                                                     |                                                             |                                                                    |                                                         |                                                                |                                                        |                                                               |                                        |                                               |                                                      |                                                             | 
```