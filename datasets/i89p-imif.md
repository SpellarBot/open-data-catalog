# Immunization data for all students, kindergarten through 12th grade, 2014-2015 school year

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/immunization-data-for-all-students-kindergarten-through-12th-grade-2014-2015-school-year) |
| Metadata | [Link](https://data.wa.gov/api/views/i89p-imif) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/i89p-imif/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/i89p-imif/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | i89p-imif |
| Name | Immunization data for all students, kindergarten through 12th grade, 2014-2015 school year |
| Attribution | WA Department of Health, Office of Immunziation and Child Profile |
| Category | Health |
| Tags | health, department of health, vaccination, immunization, students |
| Created | 2015-11-24T22:50:17Z |
| Publication Date | 2015-11-24T22:57:51Z |

## Description

Immunization status of Washington State students for school year 2014-15

## Columns

```ls
| Included | Schema Type    | Field Name                                  | Name                                        | Data Type | Render Type |
| ======== | ============== | =========================================== | =========================================== | ========= | =========== |
| Yes      | series tag     | school_name                                 | School_Name                                 | text      | text        |
| Yes      | series tag     | school_year                                 | School_year                                 | text      | text        |
| Yes      | numeric metric | k_12_enrollment                             | K_12_enrollment                             | number    | number      |
| Yes      | numeric metric | percent_complete_for_all_immunizations      | Percent_complete_for_all_immunizations      | percent   | percent     |
| Yes      | numeric metric | percent_with_any_exemption                  | Percent_with_any_exemption                  | percent   | percent     |
| Yes      | numeric metric | percent_with_medical_exemption              | Percent_with_medical_exemption              | percent   | percent     |
| Yes      | numeric metric | percent_with_personal_exemption             | Percent_with_personal_exemption             | percent   | percent     |
| Yes      | numeric metric | percent_with_religious_exemption            | Percent_with_religious_exemption            | percent   | percent     |
| Yes      | numeric metric | percent_with_religious_membership_exemption | Percent_with_religious_membership_exemption | percent   | percent     |
| Yes      | numeric metric | percent_exempt_for_diphtheria_tetanus       | Percent_exempt_for_diphtheria_tetanus       | percent   | percent     |
| Yes      | numeric metric | percent_exempt_for_pertussis                | Percent_exempt_for_pertussis                | percent   | percent     |
| Yes      | numeric metric | percent_exempt_for_measles_mumps_rubella    | Percent_exempt_for_measles_mumps_rubella    | percent   | percent     |
| Yes      | numeric metric | percent_exempt_for_polio                    | Percent_exempt_for_polio                    | percent   | percent     |
| Yes      | numeric metric | percent_exempt_for_hepatitisb               | Percent_exempt_for_HepatitisB               | percent   | percent     |
| Yes      | numeric metric | percent_exempt_for_varicella                | Percent_exempt_for_varicella                | percent   | percent     |
| Yes      | numeric metric | number_complete_for_all_immunizations       | Number_complete_for_all_immunizations       | number    | number      |
| Yes      | numeric metric | number_with_any_exemption                   | Number_with_any_exemption                   | number    | number      |
| Yes      | numeric metric | number_with_medical_exemption               | Number_with_medical_exemption               | number    | number      |
| Yes      | numeric metric | number_with_personal_exemption              | Number_with_personal_exemption              | number    | number      |
| Yes      | numeric metric | number_with_religious_exemption             | Number_with_religious_exemption             | number    | number      |
| Yes      | numeric metric | number_with_religious_membership_exemption  | Number_with_religious_membership_exemption  | number    | number      |
| Yes      | numeric metric | number_exempt_for_diphtheria_tetanus        | Number_exempt_for_diphtheria_tetanus        | number    | number      |
| Yes      | numeric metric | number_exempt_for_pertussis                 | Number_exempt_for_pertussis                 | number    | number      |
| Yes      | numeric metric | number_exempt_for_measles_mumps_rubella     | Number_exempt_for_measles_mumps_rubella     | number    | number      |
| Yes      | numeric metric | number_exempt_for_polio                     | Number_exempt_for_polio                     | number    | number      |
| Yes      | numeric metric | number_exempt_for_hepatitisb                | Number_exempt_for_HepatitisB                | number    | number      |
| Yes      | numeric metric | number_exempt_for_varicella                 | Number_exempt_for_varicella                 | number    | number      |
| Yes      | series tag     | reported                                    | Reported                                    | text      | text        |
| No       |                | address                                     | Address                                     | text      | text        |
| Yes      | series tag     | city                                        | City                                        | text      | text        |
| Yes      | series tag     | school_district                             | School_District                             | text      | text        |
| Yes      | series tag     | county                                      | County                                      | text      | text        |
| Yes      | series tag     | esd                                         | ESD                                         | text      | text        |
| Yes      | series tag     | grade_levels                                | Grade_Levels                                | text      | text        |
| Yes      | series tag     | has_kindergarten                            | Has_kindergarten                            | text      | text        |
| Yes      | series tag     | has_6thgrade                                | Has_6thGrade                                | text      | text        |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:i89p-imif d:2014-01-01T00:00:00.000Z t:reported=Y t:school_name="10TH STREET SCHOOL" t:county=SNOHOMISH t:grade_levels=6-8 t:has_kindergarten=N t:esd="NORTHWEST EDUCATIONAL SERVICE DISTRICT 189" t:has_6thgrade=Y t:school_year=2014-15 t:school_district="MARYSVILLE SCHOOL DISTRICT" t:city=MARYSVILLE m:number_exempt_for_pertussis=4 m:percent_exempt_for_diphtheria_tetanus=1.8 m:number_with_medical_exemption=2 m:percent_exempt_for_varicella=1.2 m:number_exempt_for_hepatitisb=4 m:number_exempt_for_varicella=2 m:percent_exempt_for_pertussis=2.4 m:percent_exempt_for_measles_mumps_rubella=2.4 m:number_complete_for_all_immunizations=153 m:number_exempt_for_diphtheria_tetanus=3 m:percent_complete_for_all_immunizations=91.1 m:percent_exempt_for_polio=2.4 m:percent_exempt_for_hepatitisb=2.4 m:number_exempt_for_measles_mumps_rubella=4 m:number_with_religious_exemption=0 m:percent_with_religious_exemption=0 m:number_exempt_for_polio=4 m:percent_with_personal_exemption=3.6 m:number_with_any_exemption=7 m:percent_with_religious_membership_exemption=0 m:number_with_religious_membership_exemption=0 m:k_12_enrollment=168 m:percent_with_any_exemption=4.2 m:percent_with_medical_exemption=1.2 m:number_with_personal_exemption=6

series e:i89p-imif d:2014-01-01T00:00:00.000Z t:reported=Y t:school_name="49TH STREET ACADEMY" t:county=CLARK t:grade_levels="K -12" t:has_kindergarten=Y t:esd="EDUCATIONAL SERVICE DISTRICT 112" t:has_6thgrade=Y t:school_year=2014-15 t:school_district="EVERGREEN SCHOOL DISTRICT (CLARK)" t:city=VANCOUVER m:number_exempt_for_pertussis=2 m:percent_exempt_for_diphtheria_tetanus=4.6 m:number_with_medical_exemption=1 m:percent_exempt_for_varicella=0.8 m:number_exempt_for_hepatitisb=2 m:number_exempt_for_varicella=1 m:percent_exempt_for_pertussis=1.5 m:percent_exempt_for_measles_mumps_rubella=3.1 m:number_complete_for_all_immunizations=49 m:number_exempt_for_diphtheria_tetanus=6 m:percent_complete_for_all_immunizations=37.4 m:percent_exempt_for_polio=3.1 m:percent_exempt_for_hepatitisb=1.5 m:number_exempt_for_measles_mumps_rubella=4 m:number_with_religious_exemption=1 m:percent_with_religious_exemption=0.8 m:number_exempt_for_polio=4 m:percent_with_personal_exemption=3.1 m:number_with_any_exemption=6 m:percent_with_religious_membership_exemption=0 m:number_with_religious_membership_exemption=0 m:k_12_enrollment=131 m:percent_with_any_exemption=4.6 m:percent_with_medical_exemption=0.8 m:number_with_personal_exemption=4

series e:i89p-imif d:2014-01-01T00:00:00.000Z t:reported=Y t:school_name="A G WEST BLACK HILLS HIGH SCHOOL" t:county=THURSTON t:grade_levels=9-12 t:has_kindergarten=N t:esd="EDUCATIONAL SERVICE DISTRICT 113" t:has_6thgrade=N t:school_year=2014-15 t:school_district="TUMWATER SCHOOL DISTRICT" t:city=TUMWATER m:number_exempt_for_pertussis=32 m:percent_exempt_for_diphtheria_tetanus=4 m:number_with_medical_exemption=1 m:percent_exempt_for_varicella=0 m:number_exempt_for_hepatitisb=28 m:number_exempt_for_varicella=0 m:percent_exempt_for_pertussis=3.6 m:percent_exempt_for_measles_mumps_rubella=4.1 m:number_complete_for_all_immunizations=812 m:number_exempt_for_diphtheria_tetanus=36 m:percent_complete_for_all_immunizations=90.7 m:percent_exempt_for_polio=3 m:percent_exempt_for_hepatitisb=3.1 m:number_exempt_for_measles_mumps_rubella=37 m:number_with_religious_exemption=4 m:percent_with_religious_exemption=0.4 m:number_exempt_for_polio=27 m:percent_with_personal_exemption=5.3 m:number_with_any_exemption=52 m:percent_with_religious_membership_exemption=0 m:number_with_religious_membership_exemption=0 m:k_12_enrollment=895 m:percent_with_any_exemption=5.8 m:percent_with_medical_exemption=0.1 m:number_with_personal_exemption=47
```

## Meta Commands

```ls
metric m:k_12_enrollment p:integer l:K_12_enrollment t:dataTypeName=number

metric m:percent_complete_for_all_immunizations p:float l:Percent_complete_for_all_immunizations t:dataTypeName=percent

metric m:percent_with_any_exemption p:float l:Percent_with_any_exemption t:dataTypeName=percent

metric m:percent_with_medical_exemption p:float l:Percent_with_medical_exemption t:dataTypeName=percent

metric m:percent_with_personal_exemption p:float l:Percent_with_personal_exemption t:dataTypeName=percent

metric m:percent_with_religious_exemption p:float l:Percent_with_religious_exemption t:dataTypeName=percent

metric m:percent_with_religious_membership_exemption p:float l:Percent_with_religious_membership_exemption t:dataTypeName=percent

metric m:percent_exempt_for_diphtheria_tetanus p:float l:Percent_exempt_for_diphtheria_tetanus t:dataTypeName=percent

metric m:percent_exempt_for_pertussis p:float l:Percent_exempt_for_pertussis t:dataTypeName=percent

metric m:percent_exempt_for_measles_mumps_rubella p:float l:Percent_exempt_for_measles_mumps_rubella t:dataTypeName=percent

metric m:percent_exempt_for_polio p:float l:Percent_exempt_for_polio t:dataTypeName=percent

metric m:percent_exempt_for_hepatitisb p:float l:Percent_exempt_for_HepatitisB t:dataTypeName=percent

metric m:percent_exempt_for_varicella p:float l:Percent_exempt_for_varicella t:dataTypeName=percent

metric m:number_complete_for_all_immunizations p:integer l:Number_complete_for_all_immunizations t:dataTypeName=number

metric m:number_with_any_exemption p:integer l:Number_with_any_exemption t:dataTypeName=number

metric m:number_with_medical_exemption p:integer l:Number_with_medical_exemption t:dataTypeName=number

metric m:number_with_personal_exemption p:integer l:Number_with_personal_exemption t:dataTypeName=number

metric m:number_with_religious_exemption p:integer l:Number_with_religious_exemption t:dataTypeName=number

metric m:number_with_religious_membership_exemption p:integer l:Number_with_religious_membership_exemption t:dataTypeName=number

metric m:number_exempt_for_diphtheria_tetanus p:integer l:Number_exempt_for_diphtheria_tetanus t:dataTypeName=number

metric m:number_exempt_for_pertussis p:integer l:Number_exempt_for_pertussis t:dataTypeName=number

metric m:number_exempt_for_measles_mumps_rubella p:integer l:Number_exempt_for_measles_mumps_rubella t:dataTypeName=number

metric m:number_exempt_for_polio p:integer l:Number_exempt_for_polio t:dataTypeName=number

metric m:number_exempt_for_hepatitisb p:integer l:Number_exempt_for_HepatitisB t:dataTypeName=number

metric m:number_exempt_for_varicella p:integer l:Number_exempt_for_varicella t:dataTypeName=number

entity e:i89p-imif l:"Immunization data for all students, kindergarten through 12th grade, 2014-2015 school year" t:attribution="WA Department of Health, Office of Immunziation and Child Profile" t:url=https://data.wa.gov/api/views/i89p-imif

property e:i89p-imif t:meta.view v:id=i89p-imif v:category=Health v:attributionLink=http://www.doh.wa.gov/DataandStatisticalReports/HealthBehaviors/Immunization/SchoolReports v:averageRating=0 v:name="Immunization data for all students, kindergarten through 12th grade, 2014-2015 school year" v:attribution="WA Department of Health, Office of Immunziation and Child Profile"

property e:i89p-imif t:meta.view.license v:name="Public Domain"

property e:i89p-imif t:meta.view.owner v:id=3pra-yts3 v:profileImageUrlMedium=/api/users/3pra-yts3/profile_images/THUMB v:profileImageUrlLarge=/api/users/3pra-yts3/profile_images/LARGE v:screenName="Joanna Eavey" v:profileImageUrlSmall=/api/users/3pra-yts3/profile_images/TINY v:displayName="Joanna Eavey"

property e:i89p-imif t:meta.view.tableauthor v:id=3pra-yts3 v:profileImageUrlMedium=/api/users/3pra-yts3/profile_images/THUMB v:profileImageUrlLarge=/api/users/3pra-yts3/profile_images/LARGE v:screenName="Joanna Eavey" v:profileImageUrlSmall=/api/users/3pra-yts3/profile_images/TINY v:roleName=editor v:displayName="Joanna Eavey"
```

## Top Records

```ls
| school_name                            | school_year | k_12_enrollment | percent_complete_for_all_immunizations | percent_with_any_exemption | percent_with_medical_exemption | percent_with_personal_exemption | percent_with_religious_exemption | percent_with_religious_membership_exemption | percent_exempt_for_diphtheria_tetanus | percent_exempt_for_pertussis | percent_exempt_for_measles_mumps_rubella | percent_exempt_for_polio | percent_exempt_for_hepatitisb | percent_exempt_for_varicella | number_complete_for_all_immunizations | number_with_any_exemption | number_with_medical_exemption | number_with_personal_exemption | number_with_religious_exemption | number_with_religious_membership_exemption | number_exempt_for_diphtheria_tetanus | number_exempt_for_pertussis | number_exempt_for_measles_mumps_rubella | number_exempt_for_polio | number_exempt_for_hepatitisb | number_exempt_for_varicella | reported | address                 | city       | school_district                   | county       | esd                                            | grade_levels | has_kindergarten | has_6thgrade | 
| ====================================== | =========== | =============== | ====================================== | ========================== | ============================== | =============================== | ================================ | =========================================== | ===================================== | ============================ | ======================================== | ======================== | ============================= | ============================ | ===================================== | ========================= | ============================= | ============================== | =============================== | ========================================== | ==================================== | =========================== | ======================================= | ======================= | ============================ | =========================== | ======== | ======================= | ========== | ================================= | ============ | ============================================== | ============ | ================ | ============ | 
| 10TH STREET SCHOOL                     | 2014-15     | 168             | 91.1                                   | 4.2                        | 1.2                            | 3.6                             | 0.0                              | 0.0                                         | 1.8                                   | 2.4                          | 2.4                                      | 2.4                      | 2.4                           | 1.2                          | 153                                   | 7                         | 2                             | 6                              | 0                               | 0                                          | 3                                    | 4                           | 4                                       | 4                       | 4                            | 2                           | Y        | 7204 27TH AVE NE        | MARYSVILLE | MARYSVILLE SCHOOL DISTRICT        | SNOHOMISH    | NORTHWEST EDUCATIONAL SERVICE DISTRICT 189     | 6-8          | N                | Y            | 
| 49TH STREET ACADEMY                    | 2014-15     | 131             | 37.4                                   | 4.6                        | 0.8                            | 3.1                             | 0.8                              | 0.0                                         | 4.6                                   | 1.5                          | 3.1                                      | 3.1                      | 1.5                           | 0.8                          | 49                                    | 6                         | 1                             | 4                              | 1                               | 0                                          | 6                                    | 2                           | 4                                       | 4                       | 2                            | 1                           | Y        | 14619B NE 49TH STREET   | VANCOUVER  | EVERGREEN SCHOOL DISTRICT (CLARK) | CLARK        | EDUCATIONAL SERVICE DISTRICT 112               | K -12        | Y                | Y            | 
| A G WEST BLACK HILLS HIGH SCHOOL       | 2014-15     | 895             | 90.7                                   | 5.8                        | 0.1                            | 5.3                             | 0.4                              | 0.0                                         | 4.0                                   | 3.6                          | 4.1                                      | 3.0                      | 3.1                           | 0.0                          | 812                                   | 52                        | 1                             | 47                             | 4                               | 0                                          | 36                                   | 32                          | 37                                      | 27                      | 28                           | 0                           | Y        | 7741 LITTLEROCK ROAD SW | TUMWATER   | TUMWATER SCHOOL DISTRICT          | THURSTON     | EDUCATIONAL SERVICE DISTRICT 113               | 9-12         | N                | N            | 
| A J WEST ELEMENTARY                    | 2014-15     | 413             | 91.8                                   | 1.0                        | 0.0                            | 1.0                             | 0.0                              | 0.0                                         | 0.7                                   | 0.7                          | 0.2                                      | 0.5                      | 0.2                           | 0.2                          | 379                                   | 4                         | 0                             | 4                              | 0                               | 0                                          | 3                                    | 3                           | 1                                       | 2                       | 1                            | 1                           | Y        | 1801 BAY AVE            | ABERDEEN   | ABERDEEN SCHOOL DISTRICT          | GRAYS HARBOR | EDUCATIONAL SERVICE DISTRICT 113               | PK-6         | Y                | Y            | 
| ABRAHAM LINCOLN ELEMENTARY             | 2014-15     | 515             | 96.9                                   | 2.7                        | 0.0                            | 2.5                             | 0.2                              | 0.0                                         | 1.9                                   | 1.9                          | 2.7                                      | 1.9                      | 1.9                           | 2.7                          | 499                                   | 14                        | 0                             | 13                             | 1                               | 0                                          | 10                                   | 10                          | 14                                      | 10                      | 10                           | 14                          | Y        | 1224 METHOW ST          | WENATCHEE  | WENATCHEE SCHOOL DISTRICT         | CHELAN       | NORTH CENTRAL EDUCATIONAL SERVICE DISTRICT 171 | K -5         | Y                | N            | 
| ACADEMIC INSTITUTE                     | 2014-15     |                 |                                        |                            |                                |                                 |                                  |                                             |                                       |                              |                                          |                          |                               |                              |                                       |                           |                               |                                |                                 |                                            |                                      |                             |                                         |                         |                              |                             | N        | 13400 NE 20TH SUITE 47  | BELLEVUE   | BELLEVUE SCHOOL DISTRICT          | KING         | PUGET SOUND EDUCATIONAL SERVICE DISTRICT 121   | 7-12         | N                | N            | 
| ACADEMY FOR PRECISION LEARNING         | 2014-15     | 97              | 74.2                                   | 16.5                       | 4.1                            | 10.3                            | 1.0                              | 3.1                                         | 12.4                                  | 9.3                          | 12.4                                     | 11.3                     | 10.3                          | 12.4                         | 72                                    | 16                        | 4                             | 10                             | 1                               | 3                                          | 12                                   | 9                           | 12                                      | 11                      | 10                           | 12                          | Y        | 5031 UNIVERSITY WAY NE  | SEATTLE    | SEATTLE PUBLIC SCHOOLS            | KING         | PUGET SOUND EDUCATIONAL SERVICE DISTRICT 121   | K-9          | Y                | Y            | 
| ACADEMY NW/FAMILY ACADEMY              | 2014-15     | 105             | 57.1                                   | 42.9                       | 0.0                            | 36.2                            | 6.7                              | 0.0                                         | 42.9                                  | 42.9                         | 42.9                                     | 42.9                     | 42.9                          | 42.9                         | 60                                    | 45                        | 0                             | 38                             | 7                               | 0                                          | 45                                   | 45                          | 45                                      | 45                      | 45                           | 45                          | Y        | 23420 JORDAN RD         | ARLINGTON  | ARLINGTON SCHOOL DISTRICT         | SNOHOMISH    | NORTHWEST EDUCATIONAL SERVICE DISTRICT 189     | K-12         | Y                | Y            | 
| ACADEMY OF CITIZENSHIP AND EMPOWERMENT | 2014-15     | 441             | 90.9                                   | 0.9                        | 0.0                            | 0.9                             | 0.0                              | 0.0                                         | 0.7                                   | 0.7                          | 0.9                                      | 0.7                      | 0.7                           | 0.7                          | 401                                   | 4                         | 0                             | 4                              | 0                               | 0                                          | 3                                    | 3                           | 4                                       | 3                       | 3                            | 3                           | Y        | 4424 SOUTH 188TH STREET | SEATAC     | HIGHLINE SCHOOL DISTRICT          | KING         | PUGET SOUND EDUCATIONAL SERVICE DISTRICT 121   | 9-12         | N                | N            | 
| ACADEMY OF CONST AND ENGINEERING       | 2014-15     | 321             | 85.4                                   | 3.7                        | 0.3                            | 3.1                             | 0.3                              | 0.0                                         | 2.5                                   | 1.6                          | 1.9                                      | 1.6                      | 2.2                           | 0.0                          | 274                                   | 12                        | 1                             | 10                             | 1                               | 0                                          | 8                                    | 5                           | 6                                       | 5                       | 7                            | 0                           | Y        | 8301 84TH STREET NE     | MARYSVILLE | MARYSVILLE SCHOOL DISTRICT        | SNOHOMISH    | NORTHWEST EDUCATIONAL SERVICE DISTRICT 189     | 9-12         | N                | N            | 
```