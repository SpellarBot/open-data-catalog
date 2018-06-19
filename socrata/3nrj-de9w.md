# Kindergarten Immunization Data, 2014-2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/kindergarten-immunization-data-2014-2015-69f2d) |
| Metadata | [Link](https://data.wa.gov/api/views/3nrj-de9w) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/3nrj-de9w/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/3nrj-de9w/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | 3nrj-de9w |
| Name | Kindergarten Immunization Data, 2014-2015 |
| Attribution | WA Department of Health, Office of Immunziation and Child Profile |
| Category | Health |
| Tags | ? immunization, vaccination, kindergarten, child health, department of health, mmr, polio, dtap, hepb, varicella |
| Created | 2015-11-24T00:14:30Z |
| Publication Date | 2015-11-24T00:30:46Z |

## Description

Immunization status of Washington State kindergartners for school year 2014-15

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
series e:3nrj-de9w d:2014-01-01T00:00:00.000Z t:reported=Y t:school_name="10TH STREET SCHOOL" t:county=SNOHOMISH t:grade_levels=6-8 t:has_kindergarten=N t:esd="NORTHWEST EDUCATIONAL SERVICE DISTRICT 189" t:has_6thgrade=Y t:school_year=2014-15 t:school_district="MARYSVILLE SCHOOL DISTRICT" t:city=MARYSVILLE m:number_incomplete_for_diphtheria_tetanus=0 m:number_conditional=0 m:number_incomplete_for_polio=0 m:percent_complete_for_hepatitisb=0 m:number_incomplete_for_hepatitisb=0 m:number_complete_for_all_immunizations=0 m:percent_complete_for_measles_mumps_rubella=0 m:percent_complete_for_polio=0 m:percent_complete_for_all_immunizations=0 m:number_incomplete_for_varicella=0 m:number_out_of_compliance=0 m:percent_complete_for_diphtheria_tetanus=0 m:percent_with_personal_exemption=0 m:number_with_any_exemption=0 m:number_with_religious_membership_exemption=0 m:percent_with_medical_exemption=0 m:number_with_personal_exemption=0 m:percent_out_of_compliance=0 m:percent_complete_for_varicella=0 m:percent_conditional=0 m:reported_enrollment=0 m:number_with_medical_exemption=0 m:percent_complete_for_pertussis=0 m:number_with_religious_exemption=0 m:percent_with_religious_exemption=0 m:percent_with_religious_membership_exemption=0 m:number_incomplete_for_pertussis=0 m:percent_with_any_exemption=0 m:number_incomplete_for_measles_mumps_rubella=0

series e:3nrj-de9w d:2014-01-01T00:00:00.000Z t:reported=Y t:school_name="49TH STREET ACADEMY" t:county=CLARK t:grade_levels="K -12" t:has_kindergarten=Y t:esd="EDUCATIONAL SERVICE DISTRICT 112" t:has_6thgrade=Y t:school_year=2014-15 t:school_district="EVERGREEN SCHOOL DISTRICT (CLARK)" t:city=VANCOUVER m:number_incomplete_for_diphtheria_tetanus=0 m:number_conditional=0 m:number_incomplete_for_polio=0 m:percent_complete_for_hepatitisb=0 m:number_incomplete_for_hepatitisb=0 m:number_complete_for_all_immunizations=0 m:percent_complete_for_measles_mumps_rubella=0 m:percent_complete_for_polio=0 m:percent_complete_for_all_immunizations=0 m:number_incomplete_for_varicella=0 m:number_out_of_compliance=0 m:percent_complete_for_diphtheria_tetanus=0 m:percent_with_personal_exemption=0 m:number_with_any_exemption=0 m:number_with_religious_membership_exemption=0 m:percent_with_medical_exemption=0 m:number_with_personal_exemption=0 m:percent_out_of_compliance=0 m:percent_complete_for_varicella=0 m:percent_conditional=0 m:reported_enrollment=0 m:number_with_medical_exemption=0 m:percent_complete_for_pertussis=0 m:number_with_religious_exemption=0 m:percent_with_religious_exemption=0 m:percent_with_religious_membership_exemption=0 m:number_incomplete_for_pertussis=0 m:percent_with_any_exemption=0 m:number_incomplete_for_measles_mumps_rubella=0

series e:3nrj-de9w d:2014-01-01T00:00:00.000Z t:reported=Y t:school_name="A G WEST BLACK HILLS HIGH SCHOOL" t:county=THURSTON t:grade_levels=9-12 t:has_kindergarten=N t:esd="EDUCATIONAL SERVICE DISTRICT 113" t:has_6thgrade=N t:school_year=2014-15 t:school_district="TUMWATER SCHOOL DISTRICT" t:city=TUMWATER m:number_incomplete_for_diphtheria_tetanus=0 m:number_conditional=0 m:number_incomplete_for_polio=0 m:percent_complete_for_hepatitisb=0 m:number_incomplete_for_hepatitisb=0 m:number_complete_for_all_immunizations=0 m:percent_complete_for_measles_mumps_rubella=0 m:percent_complete_for_polio=0 m:percent_complete_for_all_immunizations=0 m:number_incomplete_for_varicella=0 m:number_out_of_compliance=0 m:percent_complete_for_diphtheria_tetanus=0 m:percent_with_personal_exemption=0 m:number_with_any_exemption=0 m:number_with_religious_membership_exemption=0 m:percent_with_medical_exemption=0 m:number_with_personal_exemption=0 m:percent_out_of_compliance=0 m:percent_complete_for_varicella=0 m:percent_conditional=0 m:reported_enrollment=0 m:number_with_medical_exemption=0 m:percent_complete_for_pertussis=0 m:number_with_religious_exemption=0 m:percent_with_religious_exemption=0 m:percent_with_religious_membership_exemption=0 m:number_incomplete_for_pertussis=0 m:percent_with_any_exemption=0 m:number_incomplete_for_measles_mumps_rubella=0
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

entity e:3nrj-de9w l:"Kindergarten Immunization Data, 2014-2015" t:attribution="WA Department of Health, Office of Immunziation and Child Profile" t:url=https://data.wa.gov/api/views/3nrj-de9w

property e:3nrj-de9w t:meta.view v:id=3nrj-de9w v:category=Health v:attributionLink=http://www.doh.wa.gov/DataandStatisticalReports/HealthBehaviors/Immunization/SchoolReports v:averageRating=0 v:name="Kindergarten Immunization Data, 2014-2015" v:attribution="WA Department of Health, Office of Immunziation and Child Profile"

property e:3nrj-de9w t:meta.view.license v:name="Public Domain"

property e:3nrj-de9w t:meta.view.owner v:id=3pra-yts3 v:profileImageUrlMedium=/api/users/3pra-yts3/profile_images/THUMB v:profileImageUrlLarge=/api/users/3pra-yts3/profile_images/LARGE v:screenName="Joanna Eavey" v:profileImageUrlSmall=/api/users/3pra-yts3/profile_images/TINY v:displayName="Joanna Eavey"

property e:3nrj-de9w t:meta.view.tableauthor v:id=3pra-yts3 v:profileImageUrlMedium=/api/users/3pra-yts3/profile_images/THUMB v:profileImageUrlLarge=/api/users/3pra-yts3/profile_images/LARGE v:screenName="Joanna Eavey" v:profileImageUrlSmall=/api/users/3pra-yts3/profile_images/TINY v:roleName=editor v:displayName="Joanna Eavey"
```

## Top Records

```ls
| school_name                            | school_year | reported_enrollment | percent_complete_for_all_immunizations | percent_conditional | percent_out_of_compliance | percent_with_any_exemption | percent_with_medical_exemption | percent_with_personal_exemption | percent_with_religious_exemption | percent_with_religious_membership_exemption | percent_complete_for_diphtheria_tetanus | percent_complete_for_pertussis | percent_complete_for_measles_mumps_rubella | percent_complete_for_polio | percent_complete_for_hepatitisb | percent_complete_for_varicella | number_complete_for_all_immunizations | number_conditional | number_out_of_compliance | number_with_any_exemption | number_with_medical_exemption | number_with_personal_exemption | number_with_religious_exemption | number_with_religious_membership_exemption | number_incomplete_for_diphtheria_tetanus | number_incomplete_for_pertussis | number_incomplete_for_measles_mumps_rubella | number_incomplete_for_polio | number_incomplete_for_hepatitisb | number_incomplete_for_varicella | reported | address                 | city       | school_district                   | county       | esd                                            | grade_levels | has_kindergarten | has_6thgrade | 
| ====================================== | =========== | =================== | ====================================== | =================== | ========================= | ========================== | ============================== | =============================== | ================================ | =========================================== | ======================================= | ============================== | ========================================== | ========================== | =============================== | ============================== | ===================================== | ================== | ======================== | ========================= | ============================= | ============================== | =============================== | ========================================== | ======================================== | =============================== | =========================================== | =========================== | ================================ | =============================== | ======== | ======================= | ========== | ================================= | ============ | ============================================== | ============ | ================ | ============ | 
| 10TH STREET SCHOOL                     | 2014-15     | 0                   | 0.0                                    | 0.0                 | 0.0                       | 0.0                        | 0.0                            | 0.0                             | 0.0                              | 0.0                                         | 0.0                                     | 0.0                            | 0.0                                        | 0.0                        | 0.0                             | 0.0                            | 0                                     | 0                  | 0                        | 0                         | 0                             | 0                              | 0                               | 0                                          | 0                                        | 0                               | 0                                           | 0                           | 0                                | 0                               | Y        | 7204 27TH AVE NE        | MARYSVILLE | MARYSVILLE SCHOOL DISTRICT        | SNOHOMISH    | NORTHWEST EDUCATIONAL SERVICE DISTRICT 189     | 6-8          | N                | Y            | 
| 49TH STREET ACADEMY                    | 2014-15     | 0                   | 0.0                                    | 0.0                 | 0.0                       | 0.0                        | 0.0                            | 0.0                             | 0.0                              | 0.0                                         | 0.0                                     | 0.0                            | 0.0                                        | 0.0                        | 0.0                             | 0.0                            | 0                                     | 0                  | 0                        | 0                         | 0                             | 0                              | 0                               | 0                                          | 0                                        | 0                               | 0                                           | 0                           | 0                                | 0                               | Y        | 14619B NE 49TH STREET   | VANCOUVER  | EVERGREEN SCHOOL DISTRICT (CLARK) | CLARK        | EDUCATIONAL SERVICE DISTRICT 112               | K -12        | Y                | Y            | 
| A G WEST BLACK HILLS HIGH SCHOOL       | 2014-15     | 0                   | 0.0                                    | 0.0                 | 0.0                       | 0.0                        | 0.0                            | 0.0                             | 0.0                              | 0.0                                         | 0.0                                     | 0.0                            | 0.0                                        | 0.0                        | 0.0                             | 0.0                            | 0                                     | 0                  | 0                        | 0                         | 0                             | 0                              | 0                               | 0                                          | 0                                        | 0                               | 0                                           | 0                           | 0                                | 0                               | Y        | 7741 LITTLEROCK ROAD SW | TUMWATER   | TUMWATER SCHOOL DISTRICT          | THURSTON     | EDUCATIONAL SERVICE DISTRICT 113               | 9-12         | N                | N            | 
| A J WEST ELEMENTARY                    | 2014-15     | 72                  | 90.3                                   | 9.7                 | 0.0                       | 0.0                        | 0.0                            | 0.0                             | 0.0                              | 0.0                                         | 97.2                                    | 97.2                           | 90.3                                       | 97.2                       | 97.2                            | 91.7                           | 65                                    | 7                  | 0                        | 0                         | 0                             | 0                              | 0                               | 0                                          | 2                                        | 2                               | 7                                           | 2                           | 2                                | 6                               | Y        | 1801 BAY AVE            | ABERDEEN   | ABERDEEN SCHOOL DISTRICT          | GRAYS HARBOR | EDUCATIONAL SERVICE DISTRICT 113               | PK-6         | Y                | Y            | 
| ABRAHAM LINCOLN ELEMENTARY             | 2014-15     | 84                  | 97.6                                   | 1.2                 | 0.0                       | 1.2                        | 0.0                            | 1.2                             | 0.0                              | 0.0                                         | 98.8                                    | 98.8                           | 98.8                                       | 98.8                       | 98.8                            | 97.6                           | 82                                    | 1                  | 0                        | 1                         | 0                             | 1                              | 0                               | 0                                          | 1                                        | 1                               | 1                                           | 1                           | 1                                | 2                               | Y        | 1224 METHOW ST          | WENATCHEE  | WENATCHEE SCHOOL DISTRICT         | CHELAN       | NORTH CENTRAL EDUCATIONAL SERVICE DISTRICT 171 | K -5         | Y                | N            | 
| ACADEMIC INSTITUTE                     | 2014-15     |                     |                                        |                     |                           |                            |                                |                                 |                                  |                                             |                                         |                                |                                            |                            |                                 |                                |                                       |                    |                          |                           |                               |                                |                                 |                                            |                                          |                                 |                                             |                             |                                  |                                 | N        | 13400 NE 20TH SUITE 47  | BELLEVUE   | BELLEVUE SCHOOL DISTRICT          | KING         | PUGET SOUND EDUCATIONAL SERVICE DISTRICT 121   | 7-12         | N                | N            | 
| ACADEMY FOR PRECISION LEARNING         | 2014-15     | 4                   | 75.0                                   | 0.0                 | 0.0                       | 25.0                       | 0.0                            | 25.0                            | 0.0                              | 0.0                                         | 100.0                                   | 100.0                          | 75.0                                       | 100.0                      | 75.0                            | 75.0                           | 3                                     | 0                  | 0                        | 1                         | 0                             | 1                              | 0                               | 0                                          | 0                                        | 0                               | 1                                           | 0                           | 1                                | 1                               | Y        | 5031 UNIVERSITY WAY NE  | SEATTLE    | SEATTLE PUBLIC SCHOOLS            | KING         | PUGET SOUND EDUCATIONAL SERVICE DISTRICT 121   | K-9          | Y                | Y            | 
| ACADEMY NW/FAMILY ACADEMY              | 2014-15     | 1                   | 100.0                                  | 0.0                 | 0.0                       | 0.0                        | 0.0                            | 0.0                             | 0.0                              | 0.0                                         | 100.0                                   | 100.0                          | 100.0                                      | 100.0                      | 100.0                           | 100.0                          | 1                                     | 0                  | 0                        | 0                         | 0                             | 0                              | 0                               | 0                                          | 0                                        | 0                               | 0                                           | 0                           | 0                                | 0                               | Y        | 23420 JORDAN RD         | ARLINGTON  | ARLINGTON SCHOOL DISTRICT         | SNOHOMISH    | NORTHWEST EDUCATIONAL SERVICE DISTRICT 189     | K-12         | Y                | Y            | 
| ACADEMY OF CITIZENSHIP AND EMPOWERMENT | 2014-15     | 0                   | 0.0                                    | 0.0                 | 0.0                       | 0.0                        | 0.0                            | 0.0                             | 0.0                              | 0.0                                         | 0.0                                     | 0.0                            | 0.0                                        | 0.0                        | 0.0                             | 0.0                            | 0                                     | 0                  | 0                        | 0                         | 0                             | 0                              | 0                               | 0                                          | 0                                        | 0                               | 0                                           | 0                           | 0                                | 0                               | Y        | 4424 SOUTH 188TH STREET | SEATAC     | HIGHLINE SCHOOL DISTRICT          | KING         | PUGET SOUND EDUCATIONAL SERVICE DISTRICT 121   | 9-12         | N                | N            | 
| ACADEMY OF CONST AND ENGINEERING       | 2014-15     | 0                   | 0.0                                    | 0.0                 | 0.0                       | 0.0                        | 0.0                            | 0.0                             | 0.0                              | 0.0                                         | 0.0                                     | 0.0                            | 0.0                                        | 0.0                        | 0.0                             | 0.0                            | 0                                     | 0                  | 0                        | 0                         | 0                             | 0                              | 0                               | 0                                          | 0                                        | 0                               | 0                                           | 0                           | 0                                | 0                               | Y        | 8301 84TH STREET NE     | MARYSVILLE | MARYSVILLE SCHOOL DISTRICT        | SNOHOMISH    | NORTHWEST EDUCATIONAL SERVICE DISTRICT 189     | 9-12         | N                | N            | 
```