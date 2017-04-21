# Sixth (6th) grade immunization data by school, 2015-2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sixth-6th-grade-immunization-data-by-school-2015-2016) |
| Metadata | [Link](https://data.wa.gov/api/views/9vf7-7een) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/9vf7-7een/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/9vf7-7een/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | 9vf7-7een |
| Name | Sixth (6th) grade immunization data by school, 2015-2016 |
| Attribution | Office of Immunization and Child Profile, Department of Health |
| Category | Health |
| Tags | immunization, vaccination, student, child health, department of health, mmr, polio, dtap, hepb, varicella |
| Created | 2016-04-13T18:50:16Z |
| Publication Date | 2016-04-13T18:58:47Z |

## Description

Washington sixth grade immunization rates by school for 2015-2016

## Columns

```ls
| Included | Schema Type    | Field Name                                  | Name                                        | Data Type | Render Type |
| ======== | ============== | =========================================== | =========================================== | ========= | =========== |
| Yes      | series tag     | school_name                                 | School_Name                                 | text      | text        |
| Yes      | series tag     | school_year                                 | School_Year                                 | text      | text        |
| Yes      | numeric metric | reported_enrollment                         | Reported_enrollment                         | number    | number      |
| Yes      | numeric metric | percent_complete_for_all_immunizations      | Percent_complete_for_all_immunizations      | percent   | percent     |
| Yes      | numeric metric | percent_conditional                         | Percent_conditional                         | percent   | percent     |
| Yes      | numeric metric | percent_out_of_compliance                   | Percent_out_of_compliance                   | percent   | percent     |
| Yes      | numeric metric | percent_with_any_exemption                  | Percent_with_any_exemption                  | percent   | percent     |
| Yes      | numeric metric | percent_with_medical_exemption              | Percent_with_medical_exemption              | percent   | percent     |
| Yes      | numeric metric | percent_with_personal_exemption             | Percent_with_personal_exemption             | percent   | percent     |
| Yes      | numeric metric | percent_with_religious_exemption            | Percent_with_religious_exemption            | percent   | percent     |
| Yes      | numeric metric | percent_with_religious_membership_exemption | Percent_with_religious_membership_exemption | percent   | percent     |
| Yes      | numeric metric | percent_complete_for_diphtheria_tetanus     | Percent_complete_for_diphtheria_tetanus     | percent   | percent     |
| Yes      | numeric metric | percent_complete_for_pertussis              | Percent_complete_for_pertussis              | percent   | percent     |
| Yes      | numeric metric | percent_complete_for_measles_mumps_rubella  | Percent_complete_for_measles_mumps_rubella  | percent   | percent     |
| Yes      | numeric metric | percent_complete_for_polio                  | Percent_complete_for_polio                  | percent   | percent     |
| Yes      | numeric metric | percent_complete_for_hepatitisb             | Percent_complete_for_HepatitisB             | percent   | percent     |
| Yes      | numeric metric | percent_complete_for_varicella              | Percent_complete_for_varicella              | percent   | percent     |
| Yes      | numeric metric | number_complete_for_all_immunizations       | Number_complete_for_all_immunizations       | number    | number      |
| Yes      | numeric metric | number_conditional                          | Number_conditional                          | number    | number      |
| Yes      | numeric metric | number_out_of_compliance                    | Number_out_of_compliance                    | number    | number      |
| Yes      | numeric metric | number_with_any_exemption                   | Number_with_any_exemption                   | number    | number      |
| Yes      | numeric metric | number_with_medical_exemption               | Number_with_medical_exemption               | number    | number      |
| Yes      | numeric metric | number_with_personal_exemption              | Number_with_personal_exemption              | number    | number      |
| Yes      | numeric metric | number_with_religious_exemption             | Number_with_religious_exemption             | number    | number      |
| Yes      | numeric metric | number_with_religious_membership_exemption  | Number_with_religious_membership_exemption  | number    | number      |
| Yes      | numeric metric | number_incomplete_for_diphtheria_tetanus    | Number_incomplete_for_diphtheria_tetanus    | number    | number      |
| Yes      | numeric metric | number_incomplete_for_pertussis             | Number_incomplete_for_pertussis             | number    | number      |
| Yes      | numeric metric | number_incomplete_for_measles_mumps_rubella | Number_incomplete_for_measles_mumps_rubella | number    | number      |
| Yes      | numeric metric | number_incomplete_for_polio                 | Number_incomplete_for_polio                 | number    | number      |
| Yes      | numeric metric | number_incomplete_for_hepatitisb            | Number_incomplete_for_HepatitisB            | number    | number      |
| Yes      | numeric metric | number_incomplete_for_varicella             | Number_incomplete_for_varicella             | number    | number      |
| Yes      | series tag     | reported                                    | Reported                                    | text      | text        |
| Yes      | series tag     | school_type                                 | School_Type                                 | text      | text        |
| Yes      | series tag     | school_district                             | School_District                             | text      | text        |
| No       |                | address                                     | Address                                     | text      | text        |
| Yes      | series tag     | city                                        | City                                        | text      | text        |
| Yes      | series tag     | county                                      | County                                      | text      | text        |
| Yes      | series tag     | esd                                         | ESD                                         | text      | text        |
| Yes      | series tag     | grade_levels                                | Grade_Levels                                | text      | text        |
| Yes      | series tag     | has_kindergarten                            | Has_kindergarten                            | text      | text        |
| Yes      | series tag     | has_6thgrade                                | Has_6thGrade                                | text      | text        |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:9vf7-7een d:2015-01-01T00:00:00.000Z t:school_type="PUBLIC SCHOOL" t:reported=Y t:school_name="10TH STREET SCHOOL" t:county=SNOHOMISH t:grade_levels=6-8 t:has_kindergarten=N t:esd="NORTHWEST EDUCATIONAL SERVICE DISTRICT 189" t:has_6thgrade=Y t:school_year=2015-16 t:school_district="MARYSVILLE SCHOOL DISTRICT" t:city=MARYSVILLE m:number_incomplete_for_diphtheria_tetanus=18 m:number_conditional=0 m:number_incomplete_for_polio=4 m:percent_complete_for_hepatitisb=95.1 m:number_incomplete_for_hepatitisb=3 m:number_complete_for_all_immunizations=40 m:percent_complete_for_measles_mumps_rubella=93.4 m:percent_complete_for_polio=93.4 m:percent_complete_for_all_immunizations=65.6 m:number_incomplete_for_varicella=5 m:number_out_of_compliance=15 m:percent_complete_for_diphtheria_tetanus=70.5 m:percent_with_personal_exemption=8.2 m:number_with_any_exemption=6 m:number_with_religious_membership_exemption=0 m:percent_with_medical_exemption=0 m:number_with_personal_exemption=5 m:percent_out_of_compliance=24.6 m:percent_complete_for_varicella=91.8 m:percent_conditional=0 m:reported_enrollment=61 m:number_with_medical_exemption=0 m:percent_complete_for_pertussis=72.1 m:number_with_religious_exemption=1 m:percent_with_religious_exemption=1.6 m:percent_with_religious_membership_exemption=0 m:number_incomplete_for_pertussis=17 m:percent_with_any_exemption=9.8 m:number_incomplete_for_measles_mumps_rubella=4

series e:9vf7-7een d:2015-01-01T00:00:00.000Z t:school_type="PUBLIC SCHOOL" t:reported=Y t:school_name="49TH STREET ACADEMY" t:county=CLARK t:grade_levels="K -12" t:has_kindergarten=Y t:esd="EDUCATIONAL SERVICE DISTRICT 112" t:has_6thgrade=Y t:school_year=2015-16 t:school_district="EVERGREEN SCHOOL DISTRICT (CLARK)" t:city=VANCOUVER m:number_incomplete_for_diphtheria_tetanus=1 m:number_conditional=0 m:number_incomplete_for_polio=1 m:percent_complete_for_hepatitisb=100 m:number_incomplete_for_hepatitisb=0 m:number_complete_for_all_immunizations=1 m:percent_complete_for_measles_mumps_rubella=50 m:percent_complete_for_polio=50 m:percent_complete_for_all_immunizations=50 m:number_incomplete_for_varicella=1 m:number_out_of_compliance=0 m:percent_complete_for_diphtheria_tetanus=50 m:percent_with_personal_exemption=50 m:number_with_any_exemption=1 m:number_with_religious_membership_exemption=0 m:percent_with_medical_exemption=0 m:number_with_personal_exemption=1 m:percent_out_of_compliance=0 m:percent_complete_for_varicella=50 m:percent_conditional=0 m:reported_enrollment=2 m:number_with_medical_exemption=0 m:percent_complete_for_pertussis=50 m:number_with_religious_exemption=0 m:percent_with_religious_exemption=0 m:percent_with_religious_membership_exemption=0 m:number_incomplete_for_pertussis=1 m:percent_with_any_exemption=50 m:number_incomplete_for_measles_mumps_rubella=1

series e:9vf7-7een d:2015-01-01T00:00:00.000Z t:school_type="PUBLIC SCHOOL" t:reported=Y t:school_name="A G WEST BLACK HILLS HIGH SCHOOL" t:county=THURSTON t:grade_levels=9-12 t:has_kindergarten=N t:esd="EDUCATIONAL SERVICE DISTRICT 113" t:has_6thgrade=N t:school_year=2015-16 t:school_district="TUMWATER SCHOOL DISTRICT" t:city=TUMWATER m:number_incomplete_for_diphtheria_tetanus=0 m:number_conditional=0 m:number_incomplete_for_polio=0 m:percent_complete_for_hepatitisb=0 m:number_incomplete_for_hepatitisb=0 m:number_complete_for_all_immunizations=0 m:percent_complete_for_measles_mumps_rubella=0 m:percent_complete_for_polio=0 m:percent_complete_for_all_immunizations=0 m:number_incomplete_for_varicella=0 m:number_out_of_compliance=0 m:percent_complete_for_diphtheria_tetanus=0 m:percent_with_personal_exemption=0 m:number_with_any_exemption=0 m:number_with_religious_membership_exemption=0 m:percent_with_medical_exemption=0 m:number_with_personal_exemption=0 m:percent_out_of_compliance=0 m:percent_complete_for_varicella=0 m:percent_conditional=0 m:reported_enrollment=0 m:number_with_medical_exemption=0 m:percent_complete_for_pertussis=0 m:number_with_religious_exemption=0 m:percent_with_religious_exemption=0 m:percent_with_religious_membership_exemption=0 m:number_incomplete_for_pertussis=0 m:percent_with_any_exemption=0 m:number_incomplete_for_measles_mumps_rubella=0
```

## Meta Commands

```ls
metric m:reported_enrollment p:integer l:Reported_enrollment t:dataTypeName=number

metric m:percent_complete_for_all_immunizations p:float l:Percent_complete_for_all_immunizations t:dataTypeName=percent

metric m:percent_conditional p:float l:Percent_conditional t:dataTypeName=percent

metric m:percent_out_of_compliance p:float l:Percent_out_of_compliance t:dataTypeName=percent

metric m:percent_with_any_exemption p:float l:Percent_with_any_exemption t:dataTypeName=percent

metric m:percent_with_medical_exemption p:float l:Percent_with_medical_exemption t:dataTypeName=percent

metric m:percent_with_personal_exemption p:float l:Percent_with_personal_exemption t:dataTypeName=percent

metric m:percent_with_religious_exemption p:float l:Percent_with_religious_exemption t:dataTypeName=percent

metric m:percent_with_religious_membership_exemption p:float l:Percent_with_religious_membership_exemption t:dataTypeName=percent

metric m:percent_complete_for_diphtheria_tetanus p:float l:Percent_complete_for_diphtheria_tetanus t:dataTypeName=percent

metric m:percent_complete_for_pertussis p:float l:Percent_complete_for_pertussis t:dataTypeName=percent

metric m:percent_complete_for_measles_mumps_rubella p:float l:Percent_complete_for_measles_mumps_rubella t:dataTypeName=percent

metric m:percent_complete_for_polio p:float l:Percent_complete_for_polio t:dataTypeName=percent

metric m:percent_complete_for_hepatitisb p:float l:Percent_complete_for_HepatitisB t:dataTypeName=percent

metric m:percent_complete_for_varicella p:float l:Percent_complete_for_varicella t:dataTypeName=percent

metric m:number_complete_for_all_immunizations p:integer l:Number_complete_for_all_immunizations t:dataTypeName=number

metric m:number_conditional p:integer l:Number_conditional t:dataTypeName=number

metric m:number_out_of_compliance p:integer l:Number_out_of_compliance t:dataTypeName=number

metric m:number_with_any_exemption p:integer l:Number_with_any_exemption t:dataTypeName=number

metric m:number_with_medical_exemption p:integer l:Number_with_medical_exemption t:dataTypeName=number

metric m:number_with_personal_exemption p:integer l:Number_with_personal_exemption t:dataTypeName=number

metric m:number_with_religious_exemption p:integer l:Number_with_religious_exemption t:dataTypeName=number

metric m:number_with_religious_membership_exemption p:integer l:Number_with_religious_membership_exemption t:dataTypeName=number

metric m:number_incomplete_for_diphtheria_tetanus p:integer l:Number_incomplete_for_diphtheria_tetanus t:dataTypeName=number

metric m:number_incomplete_for_pertussis p:integer l:Number_incomplete_for_pertussis t:dataTypeName=number

metric m:number_incomplete_for_measles_mumps_rubella p:integer l:Number_incomplete_for_measles_mumps_rubella t:dataTypeName=number

metric m:number_incomplete_for_polio p:integer l:Number_incomplete_for_polio t:dataTypeName=number

metric m:number_incomplete_for_hepatitisb p:integer l:Number_incomplete_for_HepatitisB t:dataTypeName=number

metric m:number_incomplete_for_varicella p:integer l:Number_incomplete_for_varicella t:dataTypeName=number

entity e:9vf7-7een l:"Sixth (6th) grade immunization data by school, 2015-2016" t:attribution="Office of Immunization and Child Profile, Department of Health" t:url=https://data.wa.gov/api/views/9vf7-7een

property e:9vf7-7een t:meta.view v:id=9vf7-7een v:category=Health v:attributionLink=http://www.doh.wa.gov/DataandStatisticalReports/HealthBehaviors/Immunization/SchoolReports/DataTables v:averageRating=0 v:name="Sixth (6th) grade immunization data by school, 2015-2016" v:attribution="Office of Immunization and Child Profile, Department of Health"

property e:9vf7-7een t:meta.view.owner v:id=3pra-yts3 v:profileImageUrlMedium=/api/users/3pra-yts3/profile_images/THUMB v:profileImageUrlLarge=/api/users/3pra-yts3/profile_images/LARGE v:screenName="Joanna Eavey" v:profileImageUrlSmall=/api/users/3pra-yts3/profile_images/TINY v:displayName="Joanna Eavey"

property e:9vf7-7een t:meta.view.tableauthor v:id=3pra-yts3 v:profileImageUrlMedium=/api/users/3pra-yts3/profile_images/THUMB v:profileImageUrlLarge=/api/users/3pra-yts3/profile_images/LARGE v:screenName="Joanna Eavey" v:profileImageUrlSmall=/api/users/3pra-yts3/profile_images/TINY v:roleName=editor v:displayName="Joanna Eavey"
```

## Top Records

```ls
| school_name                            | school_year | reported_enrollment | percent_complete_for_all_immunizations | percent_conditional | percent_out_of_compliance | percent_with_any_exemption | percent_with_medical_exemption | percent_with_personal_exemption | percent_with_religious_exemption | percent_with_religious_membership_exemption | percent_complete_for_diphtheria_tetanus | percent_complete_for_pertussis | percent_complete_for_measles_mumps_rubella | percent_complete_for_polio | percent_complete_for_hepatitisb | percent_complete_for_varicella | number_complete_for_all_immunizations | number_conditional | number_out_of_compliance | number_with_any_exemption | number_with_medical_exemption | number_with_personal_exemption | number_with_religious_exemption | number_with_religious_membership_exemption | number_incomplete_for_diphtheria_tetanus | number_incomplete_for_pertussis | number_incomplete_for_measles_mumps_rubella | number_incomplete_for_polio | number_incomplete_for_hepatitisb | number_incomplete_for_varicella | reported | school_type    | school_district                   | address                 | city       | county       | esd                                            | grade_levels | has_kindergarten | has_6thgrade | 
| ====================================== | =========== | =================== | ====================================== | =================== | ========================= | ========================== | ============================== | =============================== | ================================ | =========================================== | ======================================= | ============================== | ========================================== | ========================== | =============================== | ============================== | ===================================== | ================== | ======================== | ========================= | ============================= | ============================== | =============================== | ========================================== | ======================================== | =============================== | =========================================== | =========================== | ================================ | =============================== | ======== | ============== | ================================= | ======================= | ========== | ============ | ============================================== | ============ | ================ | ============ | 
| 10TH STREET SCHOOL                     | 2015-16     | 61                  | 65.6                                   | 0.0                 | 24.6                      | 9.8                        | 0.0                            | 8.2                             | 1.6                              | 0.0                                         | 70.5                                    | 72.1                           | 93.4                                       | 93.4                       | 95.1                            | 91.8                           | 40                                    | 0                  | 15                       | 6                         | 0                             | 5                              | 1                               | 0                                          | 18                                       | 17                              | 4                                           | 4                           | 3                                | 5                               | Y        | PUBLIC SCHOOL  | MARYSVILLE SCHOOL DISTRICT        | 7204 27TH AVE NE        | MARYSVILLE | SNOHOMISH    | NORTHWEST EDUCATIONAL SERVICE DISTRICT 189     | 6-8          | N                | Y            | 
| 49TH STREET ACADEMY                    | 2015-16     | 2                   | 50.0                                   | 0.0                 | 0.0                       | 50.0                       | 0.0                            | 50.0                            | 0.0                              | 0.0                                         | 50.0                                    | 50.0                           | 50.0                                       | 50.0                       | 100.0                           | 50.0                           | 1                                     | 0                  | 0                        | 1                         | 0                             | 1                              | 0                               | 0                                          | 1                                        | 1                               | 1                                           | 1                           | 0                                | 1                               | Y        | PUBLIC SCHOOL  | EVERGREEN SCHOOL DISTRICT (CLARK) | 14619B NE 49TH STREET   | VANCOUVER  | CLARK        | EDUCATIONAL SERVICE DISTRICT 112               | K -12        | Y                | Y            | 
| A G WEST BLACK HILLS HIGH SCHOOL       | 2015-16     | 0                   | 0.0                                    | 0.0                 | 0.0                       | 0.0                        | 0.0                            | 0.0                             | 0.0                              | 0.0                                         | 0.0                                     | 0.0                            | 0.0                                        | 0.0                        | 0.0                             | 0.0                            | 0                                     | 0                  | 0                        | 0                         | 0                             | 0                              | 0                               | 0                                          | 0                                        | 0                               | 0                                           | 0                           | 0                                | 0                               | Y        | PUBLIC SCHOOL  | TUMWATER SCHOOL DISTRICT          | 7741 LITTLEROCK ROAD SW | TUMWATER   | THURSTON     | EDUCATIONAL SERVICE DISTRICT 113               | 9-12         | N                | N            | 
| A J WEST ELEMENTARY                    | 2015-16     | 54                  | 64.8                                   | 35.2                | 0.0                       | 0.0                        | 0.0                            | 0.0                             | 0.0                              | 0.0                                         | 64.8                                    | 64.8                           | 100.0                                      | 100.0                      | 100.0                           | 100.0                          | 35                                    | 19                 | 0                        | 0                         | 0                             | 0                              | 0                               | 0                                          | 19                                       | 19                              | 0                                           | 0                           | 0                                | 0                               | Y        | PUBLIC SCHOOL  | ABERDEEN SCHOOL DISTRICT          | 1801 BAY AVE            | ABERDEEN   | GRAYS HARBOR | EDUCATIONAL SERVICE DISTRICT 113               | PK-6         | Y                | Y            | 
| ABRAHAM LINCOLN ELEMENTARY             | 2015-16     | 0                   | 0.0                                    | 0.0                 | 0.0                       | 0.0                        | 0.0                            | 0.0                             | 0.0                              | 0.0                                         | 0.0                                     | 0.0                            | 0.0                                        | 0.0                        | 0.0                             | 0.0                            | 0                                     | 0                  | 0                        | 0                         | 0                             | 0                              | 0                               | 0                                          | 0                                        | 0                               | 0                                           | 0                           | 0                                | 0                               | Y        | PUBLIC SCHOOL  | WENATCHEE SCHOOL DISTRICT         | 1224 METHOW ST          | WENATCHEE  | CHELAN       | NORTH CENTRAL EDUCATIONAL SERVICE DISTRICT 171 | K -5         | Y                | N            | 
| ACADEMIC INSTITUTE                     | 2015-16     |                     |                                        |                     |                           |                            |                                |                                 |                                  |                                             |                                         |                                |                                            |                            |                                 |                                |                                       |                    |                          |                           |                               |                                |                                 |                                            |                                          |                                 |                                             |                             |                                  |                                 | N        | PRIVATE SCHOOL | BELLEVUE SCHOOL DISTRICT          | 13400 NE 20TH SUITE 47  | BELLEVUE   | KING         | PUGET SOUND EDUCATIONAL SERVICE DISTRICT 121   | 7-12         | N                | N            | 
| ACADEMY FOR PRECISION LEARNING         | 2015-16     | 7                   | 85.7                                   | 0.0                 | 0.0                       | 14.3                       | 14.3                           | 0.0                             | 0.0                              | 0.0                                         | 100.0                                   | 100.0                          | 85.7                                       | 100.0                      | 100.0                           | 85.7                           | 6                                     | 0                  | 0                        | 1                         | 1                             | 0                              | 0                               | 0                                          | 0                                        | 0                               | 1                                           | 0                           | 0                                | 1                               | Y        | PRIVATE SCHOOL | SEATTLE PUBLIC SCHOOLS            | 5031 UNIVERSITY WAY NE  | SEATTLE    | KING         | PUGET SOUND EDUCATIONAL SERVICE DISTRICT 121   | K-9          | Y                | Y            | 
| ACADEMY NW/FAMILY ACADEMY              | 2015-16     | 8                   | 87.5                                   | 0.0                 | 0.0                       | 12.5                       | 0.0                            | 12.5                            | 0.0                              | 0.0                                         | 87.5                                    | 87.5                           | 87.5                                       | 87.5                       | 87.5                            | 87.5                           | 7                                     | 0                  | 0                        | 1                         | 0                             | 1                              | 0                               | 0                                          | 1                                        | 1                               | 1                                           | 1                           | 1                                | 1                               | Y        | PRIVATE SCHOOL | ARLINGTON SCHOOL DISTRICT         | 23420 JORDAN RD         | ARLINGTON  | SNOHOMISH    | NORTHWEST EDUCATIONAL SERVICE DISTRICT 189     | K-12         | Y                | Y            | 
| ACADEMY OF CITIZENSHIP AND EMPOWERMENT | 2015-16     | 0                   | 0.0                                    | 0.0                 | 0.0                       | 0.0                        | 0.0                            | 0.0                             | 0.0                              | 0.0                                         | 0.0                                     | 0.0                            | 0.0                                        | 0.0                        | 0.0                             | 0.0                            | 0                                     | 0                  | 0                        | 0                         | 0                             | 0                              | 0                               | 0                                          | 0                                        | 0                               | 0                                           | 0                           | 0                                | 0                               | Y        | PUBLIC SCHOOL  | HIGHLINE SCHOOL DISTRICT          | 4424 SOUTH 188TH STREET | SEATAC     | KING         | PUGET SOUND EDUCATIONAL SERVICE DISTRICT 121   | 9-12         | N                | N            | 
| ACADEMY OF CONST AND ENGINEERING       | 2015-16     | 0                   | 0.0                                    | 0.0                 | 0.0                       | 0.0                        | 0.0                            | 0.0                             | 0.0                              | 0.0                                         | 0.0                                     | 0.0                            | 0.0                                        | 0.0                        | 0.0                             | 0.0                            | 0                                     | 0                  | 0                        | 0                         | 0                             | 0                              | 0                               | 0                                          | 0                                        | 0                               | 0                                           | 0                           | 0                                | 0                               | Y        | PUBLIC SCHOOL  | MARYSVILLE SCHOOL DISTRICT        | 8301 84TH STREET NE     | MARYSVILLE | SNOHOMISH    | NORTHWEST EDUCATIONAL SERVICE DISTRICT 189     | 9-12         | N                | N            | 
```