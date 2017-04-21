# ARTS Public Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/arts-public-data) |
| Metadata | [Link](https://data.wa.gov/api/views/mcr6-ujqw) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/mcr6-ujqw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/mcr6-ujqw/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | mcr6-ujqw |
| Name | ARTS Public Data |
| Attribution | WA State Department of Labor & Industries |
| Category | Labor |
| Tags | apprentice, apprenticeship |
| Created | 2016-06-09T21:40:36Z |
| Publication Date | 2017-04-03T18:01:58Z |

## Description

Apprenticeship Registration and Training System Data

## Columns

```ls
| Included | Schema Type    | Field Name                           | Name                                 | Data Type     | Render Type   |
| ======== | ============== | ==================================== | ==================================== | ============= | ============= |
| Yes      | series tag     | apprentice_id                        | Apprentice ID                        | text          | number        |
| Yes      | series tag     | last_name                            | Last Name                            | text          | text          |
| Yes      | series tag     | first_name                           | First Name                           | text          | text          |
| Yes      | series tag     | middle_initial                       | Middle Initial                       | text          | text          |
| Yes      | series tag     | program_id                           | Program ID                           | text          | number        |
| Yes      | series tag     | program_name                         | Program Name                         | text          | text          |
| Yes      | series tag     | occupation_id                        | Occupation ID                        | text          | number        |
| Yes      | series tag     | occupation_name                      | Occupation Name                      | text          | text          |
| Yes      | series tag     | standard_occupational_classification | Standard Occupational Classification | text          | text          |
| Yes      | time           | registration_date                    | Registration Date                    | calendar_date | calendar_date |
| No       |                | transfer_date                        | Transfer Date                        | calendar_date | calendar_date |
| No       |                | work_start_date                      | Work Start Date                      | calendar_date | calendar_date |
| Yes      | series tag     | current_status                       | Current Status                       | text          | text          |
| No       |                | current_status_date                  | Current Status Date                  | calendar_date | calendar_date |
| Yes      | numeric metric | term_in_hours                        | Term in Hours                        | number        | number        |
| Yes      | numeric metric | previous_work_hours_credit           | Previous Work Hours Credit           | number        | number        |
| Yes      | numeric metric | additional_work_hours_credit         | Additional Work Hours Credit         | number        | number        |
| Yes      | numeric metric | ojt_work_hours_reported              | OJT Work Hours Reported              | number        | number        |
| Yes      | numeric metric | work_hours_not_recorded_elsewhere    | Work Hours Not Recorded Elsewhere    | number        | number        |
| Yes      | numeric metric | total_ojt_hours                      | Total OJT Hours                      | number        | number        |
| Yes      | numeric metric | rsi_reported_hours                   | RSI Reported Hours                   | number        | number        |
| Yes      | numeric metric | rsi_other_hours                      | RSI Other Hours                      | number        | number        |
| Yes      | numeric metric | total_rsi_hours                      | Total RSI Hours                      | number        | number        |
| Yes      | series tag     | sex                                  | Sex                                  | text          | text          |
| Yes      | series tag     | race                                 | Race                                 | text          | text          |
| Yes      | series tag     | ethnicity                            | Ethnicity                            | text          | text          |
| Yes      | series tag     | veteran                              | Veteran                              | text          | text          |
| Yes      | series tag     | education_level                      | Education Level                      | text          | text          |
| Yes      | numeric metric | initial_step                         | Initial Step                         | number        | number        |
| No       |                | initial_step_eff_date                | Initial Step Eff Date                | calendar_date | calendar_date |
| Yes      | numeric metric | current_step                         | Current Step                         | number        | number        |
| No       |                | current_step_eff_date                | Current Step Eff Date                | calendar_date | calendar_date |
| No       |                | probation_start_date                 | Probation Start Date                 | calendar_date | calendar_date |
| No       |                | probation_end_date                   | Probation End Date                   | calendar_date | calendar_date |
| No       |                | hours_at_time_of_probation_end_date  | Hours at Time of Probation End Date  | text          | number        |
| Yes      | series tag     | employer_id                          | Employer ID                          | text          | number        |
| Yes      | series tag     | employer_name                        | Employer Name                        | text          | text          |
| No       |                | employment_start_date                | Employment Start Date                | calendar_date | calendar_date |
| Yes      | series tag     | special_registration_reason          | Special Registration Reason          | text          | text          |
| Yes      | series tag     | special_program_identification       | Special Program Identification       | text          | text          |
| Yes      | series tag     | other_license                        | Other License                        | text          | text          |
| Yes      | series tag     | county                               | County                               | text          | text          |
| Yes      | series tag     | zip_code                             | Zip Code                             | text          | text          |
| Yes      | series tag     | direct_entry_flag                    | Direct Entry Flag                    | text          | text          |
| Yes      | series tag     | public_employee                      | Public Employee                      | text          | text          |
| Yes      | series tag     | city                                 | City                                 | text          | text          |
| Yes      | series tag     | state                                | State                                | text          | text          |
```

## Time Field

```ls
Value = registration_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = transfer_date,work_start_date,current_status_date,initial_step_eff_date,current_step_eff_date,probation_start_date,probation_end_date,hours_at_time_of_probation_end_date,employment_start_date
```

## Data Commands

```ls
series e:mcr6-ujqw d:2006-01-17T00:00:00.000Z t:sex=Male t:apprentice_id=1689 t:zip_code=98058 t:middle_initial=T t:program_name="Washington State Fire Fighters Apprenticeship Committee" t:state=WA t:public_employee=Yes t:occupation_name="Fire Fighter" t:current_status=Completed t:race=White t:city=RENTON t:education_level=GED t:first_name=David t:standard_occupational_classification=33-2011.01 t:veteran="Vietnam era vet" t:county=KING t:last_name=Lawrence t:occupation_id=112 t:program_id=1499 t:ethnicity="Not of Hispanic Origin" m:total_rsi_hours=0 m:previous_work_hours_credit=5000 m:current_step=3 m:term_in_hours=6000 m:work_hours_not_recorded_elsewhere=1000 m:total_ojt_hours=6000 m:initial_step=3

series e:mcr6-ujqw d:1998-07-14T00:00:00.000Z t:sex=Female t:apprentice_id=4281 t:zip_code=98276 t:middle_initial=A t:program_name="Northwest Washington Electrical Industry Joint Apprenticeship and Training Committee" t:state=WA t:public_employee=No t:occupation_name="Construction Electrician" t:current_status=Completed t:race=White t:city=Nooksack t:education_level="Some High School (9th-12th)" t:first_name=Rebecca t:standard_occupational_classification=47-2111.00 t:veteran=No t:county=WHATCOM t:last_name=Cobb t:occupation_id=36 t:program_id=65 t:ethnicity="Not of Hispanic Origin" m:total_rsi_hours=0 m:previous_work_hours_credit=4000 m:total_ojt_hours=4000

series e:mcr6-ujqw d:2001-05-31T00:00:00.000Z t:sex=Female t:apprentice_id=6007 t:zip_code=99207 t:middle_initial=C t:program_name="Western States Operating Engineers Training Institute" t:state=WA t:public_employee=No t:occupation_name="Construction Equipment Operator" t:current_status=Cancelled t:race=Black t:city=SPOKANE t:education_level="Some High School (9th-12th)" t:first_name=DANIECE t:standard_occupational_classification=47-2073.00 t:veteran=No t:county=SPOKANE t:last_name=WALLS t:occupation_id=68 t:program_id=155 t:ethnicity="Not of Hispanic Origin" m:total_rsi_hours=580 m:rsi_reported_hours=580 m:current_step=6 m:ojt_work_hours_reported=4493 m:work_hours_not_recorded_elsewhere=5015 m:total_ojt_hours=9508 m:initial_step=2
```

## Meta Commands

```ls
metric m:term_in_hours p:integer l:"Term in Hours" t:dataTypeName=number

metric m:previous_work_hours_credit p:float l:"Previous Work Hours Credit" t:dataTypeName=number

metric m:additional_work_hours_credit p:float l:"Additional Work Hours Credit" t:dataTypeName=number

metric m:ojt_work_hours_reported p:float l:"OJT Work Hours Reported" t:dataTypeName=number

metric m:work_hours_not_recorded_elsewhere p:float l:"Work Hours Not Recorded Elsewhere" t:dataTypeName=number

metric m:total_ojt_hours p:float l:"Total OJT Hours" t:dataTypeName=number

metric m:rsi_reported_hours p:float l:"RSI Reported Hours" t:dataTypeName=number

metric m:rsi_other_hours p:float l:"RSI Other Hours" t:dataTypeName=number

metric m:total_rsi_hours p:float l:"Total RSI Hours" t:dataTypeName=number

metric m:initial_step p:integer l:"Initial Step" t:dataTypeName=number

metric m:current_step p:integer l:"Current Step" t:dataTypeName=number

entity e:mcr6-ujqw l:"ARTS Public Data" t:attribution="WA State Department of Labor & Industries" t:url=https://data.wa.gov/api/views/mcr6-ujqw

property e:mcr6-ujqw t:meta.view v:id=mcr6-ujqw v:category=Labor v:averageRating=0 v:name="ARTS Public Data" v:attribution="WA State Department of Labor & Industries"

property e:mcr6-ujqw t:meta.view.license v:name="Public Domain"

property e:mcr6-ujqw t:meta.view.owner v:id=7tg3-kuwr v:screenName="Leonard Sherman" v:displayName="Leonard Sherman"

property e:mcr6-ujqw t:meta.view.tableauthor v:id=7tg3-kuwr v:screenName="Leonard Sherman" v:roleName=publisher v:displayName="Leonard Sherman"
```

## Top Records

```ls
| apprentice_id | last_name | first_name | middle_initial | program_id | program_name                                                                                                    | occupation_id | occupation_name                 | standard_occupational_classification | registration_date   | transfer_date | work_start_date     | current_status | current_status_date | term_in_hours | previous_work_hours_credit | additional_work_hours_credit | ojt_work_hours_reported | work_hours_not_recorded_elsewhere | total_ojt_hours | rsi_reported_hours | rsi_other_hours | total_rsi_hours | sex    | race  | ethnicity              | veteran         | education_level             | initial_step | initial_step_eff_date | current_step | current_step_eff_date | probation_start_date | probation_end_date | hours_at_time_of_probation_end_date | employer_id | employer_name | employment_start_date | special_registration_reason | special_program_identification | other_license | county    | zip_code | direct_entry_flag | public_employee | city      | state | 
| ============= | ========= | ========== | ============== | ========== | =============================================================================================================== | ============= | =============================== | ==================================== | =================== | ============= | =================== | ============== | =================== | ============= | ========================== | ============================ | ======================= | ================================= | =============== | ================== | =============== | =============== | ====== | ===== | ====================== | =============== | =========================== | ============ | ===================== | ============ | ===================== | ==================== | ================== | =================================== | =========== | ============= | ===================== | =========================== | ============================== | ============= | ========= | ======== | ================= | =============== | ========= | ===== | 
| 1689          | Lawrence  | David      | T              | 1499       | Washington State Fire Fighters Apprenticeship Committee                                                         | 112           | Fire Fighter                    | 33-2011.01                           | 2006-01-17T00:00:00 |               | 2006-01-17T00:00:00 | Completed      | 2006-11-21T00:00:00 | 6000          | 5000.00                    |                              |                         | 1000.00                           | 6000.00         |                    |                 | 0.00            | Male   | White | Not of Hispanic Origin | Vietnam era vet | GED                         | 3            | 2006-01-17T00:00:00   | 3            | 2006-01-17T00:00:00   |                      |                    |                                     |             |               |                       |                             |                                |               | KING      | 98058    |                   | Yes             | RENTON    | WA    | 
| 4281          | Cobb      | Rebecca    | A              | 65         | Northwest Washington Electrical Industry Joint Apprenticeship and Training Committee                            | 36            | Construction Electrician        | 47-2111.00                           | 1998-07-14T00:00:00 |               | 1998-07-06T00:00:00 | Completed      | 2001-10-19T00:00:00 |               | 4000.00                    |                              |                         |                                   | 4000.00         |                    |                 | 0.00            | Female | White | Not of Hispanic Origin | No              | Some High School (9th-12th) |              |                       |              |                       |                      |                    |                                     |             |               |                       |                             |                                |               | WHATCOM   | 98276    |                   | No              | Nooksack  | WA    | 
| 6007          | WALLS     | DANIECE    | C              | 155        | Western States Operating Engineers Training Institute                                                           | 68            | Construction Equipment Operator | 47-2073.00                           | 2001-05-31T00:00:00 |               | 2001-05-22T00:00:00 | Cancelled      | 2003-03-25T00:00:00 |               |                            |                              | 4493.00                 | 5015.00                           | 9508.00         | 580.00             |                 | 580.00          | Female | Black | Not of Hispanic Origin | No              | Some High School (9th-12th) | 2            | 2004-03-29T00:00:00   | 6            | 2006-08-15T00:00:00   |                      |                    |                                     |             |               |                       |                             |                                |               | SPOKANE   | 99207    |                   | No              | SPOKANE   | WA    | 
| 6007          | WALLS     | DANIECE    | C              | 155        | Western States Operating Engineers Training Institute                                                           | 68            | Construction Equipment Operator | 47-2073.00                           | 2004-05-03T00:00:00 |               | 2004-03-29T00:00:00 | Completed      | 2008-10-07T00:00:00 | 8000          | 2017.00                    |                              | 4493.00                 | 5015.00                           | 11525.00        | 580.00             |                 | 580.00          | Female | Black | Not of Hispanic Origin | No              | High School Graduate        | 2            | 2004-03-29T00:00:00   | 6            | 2006-08-15T00:00:00   |                      |                    |                                     |             |               |                       |                             |                                |               | SPOKANE   | 99207    |                   | No              | SPOKANE   | WA    | 
| 7020          | Imboden   | Deangela   |                | 1812       | Seattle Heat Frost Insulators & Allied Workers & Employers Firestop/Containment Worker Apprenticeship Committee | 1010          | Firestop/Containment Worker     | 47-4099.99                           | 2015-02-05T00:00:00 |               | 2015-02-02T00:00:00 | Cancelled      | 2017-02-14T00:00:00 | 8000          | 0.00                       |                              | 757.00                  |                                   | 757.00          | 208.00             |                 | 208.00          | Female | White | Not of Hispanic Origin | No              | High School Graduate        | 1            | 2015-02-02T00:00:00   | 1            | 2015-02-02T00:00:00   | 2015-02-05T00:00:00  |                    |                                     |             |               |                       | None                        | None                           |               | KING      | 98122    | Yes               | No              | SEATTLE   | WA    | 
| 7896          | COLE      | CHRIS      | D              | 58         | Operating Engineers Regional Training Program JATC                                                              | 68            | Construction Equipment Operator | 47-2073.00                           | 1996-08-01T00:00:00 |               | 1996-07-08T00:00:00 | Completed      | 2000-05-10T00:00:00 |               | 1091.00                    |                              |                         |                                   | 1091.00         |                    |                 | 0.00            | Female | White | Not of Hispanic Origin | No              | Some High School (9th-12th) |              |                       |              |                       |                      |                    |                                     |             |               |                       |                             |                                |               | SNOHOMISH | 98296    |                   | No              | SNOHOMISH | WA    | 
| 8037          | EDDY      | MARC       | C              | 150        | Southwest Washington Electrical Joint Apprenticeship and Training Committee                                     | 36            | Construction Electrician        | 47-2111.00                           | 1996-06-17T00:00:00 |               | 1996-06-12T00:00:00 | Cancelled      | 2000-04-11T00:00:00 |               |                            |                              |                         |                                   | 0.00            |                    |                 | 0.00            | Male   | White | Not of Hispanic Origin | No              | Some High School (9th-12th) |              |                       |              |                       |                      |                    |                                     |             |               |                       |                             |                                |               | PIERCE    | 98405    |                   | No              | Tacoma    | WA    | 
| 8390          | ROBLES    | JORGE      | V              | 65         | Northwest Washington Electrical Industry Joint Apprenticeship and Training Committee                            | 36            | Construction Electrician        | 47-2111.00                           | 1996-08-14T00:00:00 |               | 1996-08-13T00:00:00 | Completed      | 2000-04-17T00:00:00 |               | 3500.00                    |                              |                         |                                   | 3500.00         |                    |                 | 0.00            | Male   | Asian | Hispanic Origin        | No              | Some High School (9th-12th) |              |                       |              |                       |                      |                    |                                     |             |               |                       | None                        | None                           |               | SNOHOMISH | 98203    |                   | No              | EVERETT   | WA    | 
| 8439          | BARNES    | BRENNAN    | D              | 150        | Southwest Washington Electrical Joint Apprenticeship and Training Committee                                     | 36            | Construction Electrician        | 47-2111.00                           | 1996-09-26T00:00:00 |               | 1996-08-30T00:00:00 | Completed      | 2000-03-03T00:00:00 |               | 2000.00                    |                              |                         |                                   | 2000.00         |                    |                 | 0.00            | Male   | White | Not of Hispanic Origin | No              | Some High School (9th-12th) |              |                       |              |                       |                      |                    |                                     |             |               |                       |                             |                                |               | THURSTON  | 98516    |                   | No              | OLYMPIA   | WA    | 
| 8469          | HARRIS    | LARRY      | A              | 474        | Washington State Department of Corrections                                                                      | 277           | Corrections Officer             | 33-3012.00                           | 1992-12-10T00:00:00 |               | 1992-10-18T00:00:00 | Cancelled      | 2002-10-18T00:00:00 |               |                            |                              |                         |                                   | 0.00            |                    |                 | 0.00            | Male   | Black | Not of Hispanic Origin | Not Specified   | Some High School (9th-12th) |              |                       |              |                       |                      |                    |                                     |             |               |                       |                             |                                |               | PIERCE    | 98409    |                   | Yes             | TACOMA    | WA    | 
```