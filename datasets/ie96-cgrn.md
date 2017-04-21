# All students, kindergarten through 12th grade, immunization data by school, 2015-2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/all-students-kindergarten-through-12th-grade-immunization-data-by-school-2015-2016) |
| Metadata | [Link](https://data.wa.gov/api/views/ie96-cgrn) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/ie96-cgrn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/ie96-cgrn/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | ie96-cgrn |
| Name | All students, kindergarten through 12th grade, immunization data by school, 2015-2016 |
| Attribution | Office of Immunization and Child Profile, Department of Health |
| Category | Health |
| Tags | immunization, vaccination, student, child health, department of health, mmr, polio, dtap, hepb, varicella |
| Created | 2016-04-13T19:02:36Z |
| Publication Date | 2016-04-13T19:10:37Z |

## Description

Washington student immunization rates by school for 2015-2016

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
series e:ie96-cgrn d:2015-01-01T00:00:00.000Z t:reported=Y t:school_name="10TH STREET SCHOOL" t:county=SNOHOMISH t:grade_levels=6-8 t:has_kindergarten=N t:esd="NORTHWEST EDUCATIONAL SERVICE DISTRICT 189" t:has_6thgrade=Y t:school_year=2015-16 t:school_district="MARYSVILLE SCHOOL DISTRICT" t:city=MARYSVILLE m:number_exempt_for_pertussis=4 m:percent_exempt_for_diphtheria_tetanus=2.9 m:number_with_medical_exemption=1 m:percent_exempt_for_varicella=4.1 m:number_exempt_for_hepatitisb=5 m:number_exempt_for_varicella=7 m:percent_exempt_for_pertussis=2.3 m:percent_exempt_for_measles_mumps_rubella=3.5 m:number_complete_for_all_immunizations=116 m:number_exempt_for_diphtheria_tetanus=5 m:percent_complete_for_all_immunizations=67.8 m:percent_exempt_for_polio=3.5 m:percent_exempt_for_hepatitisb=2.9 m:number_exempt_for_measles_mumps_rubella=6 m:number_with_religious_exemption=1 m:percent_with_religious_exemption=0.6 m:number_exempt_for_polio=6 m:percent_with_personal_exemption=5.8 m:number_with_any_exemption=12 m:percent_with_religious_membership_exemption=0 m:number_with_religious_membership_exemption=0 m:k_12_enrollment=171 m:percent_with_any_exemption=7 m:percent_with_medical_exemption=0.6 m:number_with_personal_exemption=10

series e:ie96-cgrn d:2015-01-01T00:00:00.000Z t:reported=Y t:school_name="49TH STREET ACADEMY" t:county=CLARK t:grade_levels="K -12" t:has_kindergarten=Y t:esd="EDUCATIONAL SERVICE DISTRICT 112" t:has_6thgrade=Y t:school_year=2015-16 t:school_district="EVERGREEN SCHOOL DISTRICT (CLARK)" t:city=VANCOUVER m:number_exempt_for_pertussis=1 m:percent_exempt_for_diphtheria_tetanus=2.5 m:number_with_medical_exemption=0 m:percent_exempt_for_varicella=0.8 m:number_exempt_for_hepatitisb=0 m:number_exempt_for_varicella=1 m:percent_exempt_for_pertussis=0.8 m:percent_exempt_for_measles_mumps_rubella=1.7 m:number_complete_for_all_immunizations=49 m:number_exempt_for_diphtheria_tetanus=3 m:percent_complete_for_all_immunizations=40.5 m:percent_exempt_for_polio=0.8 m:percent_exempt_for_hepatitisb=0 m:number_exempt_for_measles_mumps_rubella=2 m:number_with_religious_exemption=0 m:percent_with_religious_exemption=0 m:number_exempt_for_polio=1 m:percent_with_personal_exemption=2.5 m:number_with_any_exemption=3 m:percent_with_religious_membership_exemption=0 m:number_with_religious_membership_exemption=0 m:k_12_enrollment=121 m:percent_with_any_exemption=2.5 m:percent_with_medical_exemption=0 m:number_with_personal_exemption=3

series e:ie96-cgrn d:2015-01-01T00:00:00.000Z t:reported=Y t:school_name="A G WEST BLACK HILLS HIGH SCHOOL" t:county=THURSTON t:grade_levels=9-12 t:has_kindergarten=N t:esd="EDUCATIONAL SERVICE DISTRICT 113" t:has_6thgrade=N t:school_year=2015-16 t:school_district="TUMWATER SCHOOL DISTRICT" t:city=TUMWATER m:number_exempt_for_pertussis=33 m:percent_exempt_for_diphtheria_tetanus=4.3 m:number_with_medical_exemption=14 m:percent_exempt_for_varicella=0 m:number_exempt_for_hepatitisb=35 m:number_exempt_for_varicella=0 m:percent_exempt_for_pertussis=3.7 m:percent_exempt_for_measles_mumps_rubella=4.5 m:number_complete_for_all_immunizations=804 m:number_exempt_for_diphtheria_tetanus=38 m:percent_complete_for_all_immunizations=91.1 m:percent_exempt_for_polio=3.6 m:percent_exempt_for_hepatitisb=4 m:number_exempt_for_measles_mumps_rubella=40 m:number_with_religious_exemption=5 m:percent_with_religious_exemption=0.6 m:number_exempt_for_polio=32 m:percent_with_personal_exemption=5.9 m:number_with_any_exemption=70 m:percent_with_religious_membership_exemption=0 m:number_with_religious_membership_exemption=0 m:k_12_enrollment=883 m:percent_with_any_exemption=7.9 m:percent_with_medical_exemption=1.6 m:number_with_personal_exemption=52
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

entity e:ie96-cgrn l:"All students, kindergarten through 12th grade, immunization data by school, 2015-2016" t:attribution="Office of Immunization and Child Profile, Department of Health" t:url=https://data.wa.gov/api/views/ie96-cgrn

property e:ie96-cgrn t:meta.view v:id=ie96-cgrn v:category=Health v:attributionLink=http://www.doh.wa.gov/DataandStatisticalReports/HealthBehaviors/Immunization/SchoolReports/DataTables v:averageRating=0 v:name="All students, kindergarten through 12th grade, immunization data by school, 2015-2016" v:attribution="Office of Immunization and Child Profile, Department of Health"

property e:ie96-cgrn t:meta.view.owner v:id=3pra-yts3 v:profileImageUrlMedium=/api/users/3pra-yts3/profile_images/THUMB v:profileImageUrlLarge=/api/users/3pra-yts3/profile_images/LARGE v:screenName="Joanna Eavey" v:profileImageUrlSmall=/api/users/3pra-yts3/profile_images/TINY v:displayName="Joanna Eavey"

property e:ie96-cgrn t:meta.view.tableauthor v:id=3pra-yts3 v:profileImageUrlMedium=/api/users/3pra-yts3/profile_images/THUMB v:profileImageUrlLarge=/api/users/3pra-yts3/profile_images/LARGE v:screenName="Joanna Eavey" v:profileImageUrlSmall=/api/users/3pra-yts3/profile_images/TINY v:roleName=editor v:displayName="Joanna Eavey"
```

## Top Records

```ls
| school_name                            | school_year | k_12_enrollment | percent_complete_for_all_immunizations | percent_with_any_exemption | percent_with_medical_exemption | percent_with_personal_exemption | percent_with_religious_exemption | percent_with_religious_membership_exemption | percent_exempt_for_diphtheria_tetanus | percent_exempt_for_pertussis | percent_exempt_for_measles_mumps_rubella | percent_exempt_for_polio | percent_exempt_for_hepatitisb | percent_exempt_for_varicella | number_complete_for_all_immunizations | number_with_any_exemption | number_with_medical_exemption | number_with_personal_exemption | number_with_religious_exemption | number_with_religious_membership_exemption | number_exempt_for_diphtheria_tetanus | number_exempt_for_pertussis | number_exempt_for_measles_mumps_rubella | number_exempt_for_polio | number_exempt_for_hepatitisb | number_exempt_for_varicella | reported | school_district                   | address                 | city       | county       | esd                                            | grade_levels | has_kindergarten | has_6thgrade | 
| ====================================== | =========== | =============== | ====================================== | ========================== | ============================== | =============================== | ================================ | =========================================== | ===================================== | ============================ | ======================================== | ======================== | ============================= | ============================ | ===================================== | ========================= | ============================= | ============================== | =============================== | ========================================== | ==================================== | =========================== | ======================================= | ======================= | ============================ | =========================== | ======== | ================================= | ======================= | ========== | ============ | ============================================== | ============ | ================ | ============ | 
| 10TH STREET SCHOOL                     | 2015-16     | 171             | 67.8                                   | 7.0                        | 0.6                            | 5.8                             | 0.6                              | 0.0                                         | 2.9                                   | 2.3                          | 3.5                                      | 3.5                      | 2.9                           | 4.1                          | 116                                   | 12                        | 1                             | 10                             | 1                               | 0                                          | 5                                    | 4                           | 6                                       | 6                       | 5                            | 7                           | Y        | MARYSVILLE SCHOOL DISTRICT        | 7204 27TH AVE NE        | MARYSVILLE | SNOHOMISH    | NORTHWEST EDUCATIONAL SERVICE DISTRICT 189     | 6-8          | N                | Y            | 
| 49TH STREET ACADEMY                    | 2015-16     | 121             | 40.5                                   | 2.5                        | 0.0                            | 2.5                             | 0.0                              | 0.0                                         | 2.5                                   | 0.8                          | 1.7                                      | 0.8                      | 0.0                           | 0.8                          | 49                                    | 3                         | 0                             | 3                              | 0                               | 0                                          | 3                                    | 1                           | 2                                       | 1                       | 0                            | 1                           | Y        | EVERGREEN SCHOOL DISTRICT (CLARK) | 14619B NE 49TH STREET   | VANCOUVER  | CLARK        | EDUCATIONAL SERVICE DISTRICT 112               | K -12        | Y                | Y            | 
| A G WEST BLACK HILLS HIGH SCHOOL       | 2015-16     | 883             | 91.1                                   | 7.9                        | 1.6                            | 5.9                             | 0.6                              | 0.0                                         | 4.3                                   | 3.7                          | 4.5                                      | 3.6                      | 4.0                           | 0.0                          | 804                                   | 70                        | 14                            | 52                             | 5                               | 0                                          | 38                                   | 33                          | 40                                      | 32                      | 35                           | 0                           | Y        | TUMWATER SCHOOL DISTRICT          | 7741 LITTLEROCK ROAD SW | TUMWATER   | THURSTON     | EDUCATIONAL SERVICE DISTRICT 113               | 9-12         | N                | N            | 
| A J WEST ELEMENTARY                    | 2015-16     | 388             | 92.3                                   | 0.8                        | 0.5                            | 0.3                             | 0.0                              | 0.0                                         | 0.8                                   | 0.8                          | 0.8                                      | 0.8                      | 0.5                           | 0.8                          | 358                                   | 3                         | 2                             | 1                              | 0                               | 0                                          | 3                                    | 3                           | 3                                       | 3                       | 2                            | 3                           | Y        | ABERDEEN SCHOOL DISTRICT          | 1801 BAY AVE            | ABERDEEN   | GRAYS HARBOR | EDUCATIONAL SERVICE DISTRICT 113               | PK-6         | Y                | Y            | 
| ABRAHAM LINCOLN ELEMENTARY             | 2015-16     | 518             | 96.9                                   | 2.1                        | 0.0                            | 2.1                             | 0.0                              | 0.0                                         | 1.2                                   | 1.2                          | 1.7                                      | 1.2                      | 1.0                           | 1.5                          | 502                                   | 11                        | 0                             | 11                             | 0                               | 0                                          | 6                                    | 6                           | 9                                       | 6                       | 5                            | 8                           | Y        | WENATCHEE SCHOOL DISTRICT         | 1224 METHOW ST          | WENATCHEE  | CHELAN       | NORTH CENTRAL EDUCATIONAL SERVICE DISTRICT 171 | K -5         | Y                | N            | 
| ACADEMIC INSTITUTE                     | 2015-16     |                 |                                        |                            |                                |                                 |                                  |                                             |                                       |                              |                                          |                          |                               |                              |                                       |                           |                               |                                |                                 |                                            |                                      |                             |                                         |                         |                              |                             | N        | BELLEVUE SCHOOL DISTRICT          | 13400 NE 20TH SUITE 47  | BELLEVUE   | KING         | PUGET SOUND EDUCATIONAL SERVICE DISTRICT 121   | 7-12         | N                | N            | 
| ACADEMY FOR PRECISION LEARNING         | 2015-16     | 106             | 83.0                                   | 17.0                       | 1.9                            | 13.2                            | 3.8                              | 0.0                                         | 16.0                                  | 16.0                         | 17.0                                     | 15.1                     | 15.1                          | 16.0                         | 88                                    | 18                        | 2                             | 14                             | 4                               | 0                                          | 17                                   | 17                          | 18                                      | 16                      | 16                           | 17                          | Y        | SEATTLE PUBLIC SCHOOLS            | 5031 UNIVERSITY WAY NE  | SEATTLE    | KING         | PUGET SOUND EDUCATIONAL SERVICE DISTRICT 121   | K-9          | Y                | Y            | 
| ACADEMY NW/FAMILY ACADEMY              | 2015-16     | 189             | 78.3                                   | 21.7                       | 0.0                            | 17.5                            | 4.2                              | 0.0                                         | 21.7                                  | 21.7                         | 21.7                                     | 21.7                     | 21.7                          | 21.7                         | 148                                   | 41                        | 0                             | 33                             | 8                               | 0                                          | 41                                   | 41                          | 41                                      | 41                      | 41                           | 41                          | Y        | ARLINGTON SCHOOL DISTRICT         | 23420 JORDAN RD         | ARLINGTON  | SNOHOMISH    | NORTHWEST EDUCATIONAL SERVICE DISTRICT 189     | K-12         | Y                | Y            | 
| ACADEMY OF CITIZENSHIP AND EMPOWERMENT | 2015-16     | 450             | 89.6                                   | 1.6                        | 1.6                            | 0.0                             | 0.0                              | 0.0                                         | 0.0                                   | 0.0                          | 0.7                                      | 0.0                      | 0.9                           | 0.0                          | 403                                   | 7                         | 7                             | 0                              | 0                               | 0                                          | 0                                    | 0                           | 3                                       | 0                       | 4                            | 0                           | Y        | HIGHLINE SCHOOL DISTRICT          | 4424 SOUTH 188TH STREET | SEATAC     | KING         | PUGET SOUND EDUCATIONAL SERVICE DISTRICT 121   | 9-12         | N                | N            | 
| ACADEMY OF CONST AND ENGINEERING       | 2015-16     | 370             | 82.4                                   | 3.0                        | 0.3                            | 2.4                             | 0.3                              | 0.0                                         | 1.6                                   | 1.4                          | 1.4                                      | 1.4                      | 1.6                           | 0.0                          | 305                                   | 11                        | 1                             | 9                              | 1                               | 0                                          | 6                                    | 5                           | 5                                       | 5                       | 6                            | 0                           | Y        | MARYSVILLE SCHOOL DISTRICT        | 8301 84TH STREET NE     | MARYSVILLE | SNOHOMISH    | NORTHWEST EDUCATIONAL SERVICE DISTRICT 189     | 9-12         | N                | N            | 
```