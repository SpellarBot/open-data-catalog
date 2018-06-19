# DOB NOW: Build ? Job Application Filings

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dob-now-build-job-application-filings) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/w9ak-ipjd) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/w9ak-ipjd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/w9ak-ipjd/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | w9ak-ipjd |
| Name | DOB NOW: Build ? Job Application Filings |
| Attribution | Department of Buildings (DOB) |
| Category | Housing & Development |
| Tags | dob, job, filings, buildings |
| Created | 2016-05-26T13:34:09Z |
| Publication Date | 2016-05-26T13:35:27Z |

## Description

List of all job filings filed in DOB NOW.

## Columns

```ls
| Included | Schema Type    | Field Name                           | Name                                 | Data Type | Render Type |
| ======== | ============== | ==================================== | ==================================== | ========= | =========== |
| No       | time           | :updated_at                          | updated_at                           | meta_data | meta_data   |
| Yes      | series tag     | job_filing_number                    | Job Filing Number                    | text      | text        |
| Yes      | series tag     | filing_status                        | Filing Status                        | text      | text        |
| Yes      | series tag     | house_no                             | House No                             | text      | text        |
| Yes      | series tag     | street_name                          | Street Name                          | text      | text        |
| Yes      | series tag     | borough                              | Borough                              | text      | text        |
| Yes      | series tag     | block                                | Block                                | text      | text        |
| Yes      | series tag     | lot                                  | LOT                                  | text      | text        |
| Yes      | numeric metric | bin                                  | Bin                                  | number    | text        |
| Yes      | numeric metric | commmunity_board                     | Commmunity - Board                   | number    | text        |
| Yes      | series tag     | work_on_floor                        | Work on Floor                        | text      | text        |
| Yes      | series tag     | apt_condo_no_s                       | Apt./Condo No(s)                     | text      | text        |
| Yes      | series tag     | applicant_professional_title         | Applicant Professional Title         | text      | text        |
| Yes      | series tag     | applicant_license                    | Applicant License #                  | text      | text        |
| Yes      | series tag     | applicant_first_name                 | Applicant First Name                 | text      | text        |
| Yes      | series tag     | applicants_middle_initial            | Applicants Middle Initial            | text      | text        |
| Yes      | series tag     | applicant_last_name                  | Applicant Last Name                  | text      | text        |
| Yes      | series tag     | owner_s_business_name                | Owner's Business Name                | text      | text        |
| Yes      | series tag     | owner_s_street_name                  | Owner's Street Name                  | text      | text        |
| Yes      | series tag     | city                                 | City                                 | text      | text        |
| Yes      | series tag     | state                                | State                                | text      | text        |
| Yes      | series tag     | zip                                  | Zip                                  | text      | text        |
| Yes      | series tag     | filing_representative_first_name     | Filing Representative First Name     | text      | text        |
| Yes      | series tag     | filing_representative_middle_initial | Filing Representative Middle Initial | text      | text        |
| Yes      | series tag     | filing_representative_last_name      | Filing Representative Last Name      | text      | text        |
| Yes      | series tag     | filing_representative_business_name  | Filing Representative Business Name  | text      | text        |
| Yes      | series tag     | filing_representative_street_name    | Filing Representative Street Name    | text      | text        |
| Yes      | series tag     | filing_representative_city           | Filing Representative City           | text      | text        |
| Yes      | series tag     | filing_representative_state          | Filing Representative State          | text      | text        |
| Yes      | series tag     | filing_representative_zip            | Filing Representative Zip            | text      | text        |
| Yes      | series tag     | sprinkler_work_type                  | Sprinkler (Work Type)                | text      | text        |
| Yes      | series tag     | plumbing_work_type                   | Plumbing (Work Type)                 | text      | text        |
| Yes      | numeric metric | initial_cost                         | Initial Cost                         | number    | text        |
| Yes      | numeric metric | total_construction_floor_area        | Total Construction Floor Area        | number    | text        |
| Yes      | series tag     | review_building_code                 | Review Building Code                 | text      | text        |
| Yes      | series tag     | little_e                             | Little E                             | text      | text        |
| Yes      | series tag     | unmapped_cco_street                  | Unmapped/CCO Street                  | text      | text        |
| Yes      | series tag     | request_legalization                 | Request Legalization                 | text      | text        |
| Yes      | series tag     | includes_permanent_removal           | Includes Permanent Removal           | text      | text        |
| Yes      | series tag     | in_compliance_with_nycecc            | In Compliance with NYCECC            | text      | text        |
| Yes      | series tag     | exempt_from_nycecc                   | Exempt from NYCECC                   | text      | text        |
| Yes      | series tag     | building_type                        | Building Type                        | text      | text        |
| Yes      | numeric metric | existing_stories                     | Existing Stories                     | number    | text        |
| Yes      | numeric metric | existing_height                      | Existing Height                      | number    | text        |
| Yes      | numeric metric | existing_dwelling_units              | Existing Dwelling Units              | number    | text        |
| Yes      | numeric metric | proposed_no_of_stories               | Proposed No of Stories               | number    | text        |
| Yes      | numeric metric | proposed_height                      | Proposed Height                      | number    | text        |
| Yes      | numeric metric | proposed_dwelling_units              | Proposed Dwelling Units              | number    | text        |
| Yes      | series tag     | specialinspectionrequirement         | SpecialInspectionRequirement         | text      | text        |
| Yes      | series tag     | special_inspection_agency_number     | Special Inspection Agency Number     | text      | text        |
| Yes      | series tag     | progressinspectionrequirement        | ProgressInspectionRequirement        | text      | text        |
| Yes      | series tag     | built_1_information_value            | Built 1 information value            | text      | text        |
| Yes      | series tag     | built_2_information_value            | Built 2 information value            | text      | text        |
| Yes      | series tag     | built_2_a_information_value          | Built 2 A information value          | text      | text        |
| Yes      | series tag     | built_2_b_information_value          | Built 2 B information value          | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:w9ak-ipjd d:2016-10-28T23:25:24.000Z t:specialinspectionrequirement="Sprinkler Systems" t:review_building_code=2014 t:applicant_last_name=SIDERIS t:street_name="Greene Avenue" t:state=NY t:block=1958 t:in_compliance_with_nycecc=False t:building_type=Other t:city=BAYSIDE t:exempt_from_nycecc=True t:filing_status=Approved t:owner_s_street_name="217-22 NORTHERN BLVD" t:applicant_professional_title=PE t:little_e=No t:zip=11361 t:includes_permanent_removal=No t:applicant_license=065574 t:job_filing_number=B00000043-I1 t:borough=BROOKLYN t:work_on_floor="Cel, Bas, Osp, 1, 2, 3" t:unmapped_cco_street=No t:applicant_first_name=CHRIS t:progressinspectionrequirement="Energy Code Compliance Inspections" t:request_legalization=No t:sprinkler_work_type=True t:house_no=54 t:plumbing_work_type=True t:lot=19 t:special_inspection_agency_number=003434 m:commmunity_board=302 m:initial_cost=56800 m:total_construction_floor_area=3894 m:proposed_height=41 m:proposed_no_of_stories=3 m:existing_dwelling_units=3 m:proposed_dwelling_units=3 m:existing_height=41 m:bin=3055872 m:existing_stories=3

series e:w9ak-ipjd d:2017-01-18T00:18:22.000Z t:specialinspectionrequirement="Sprinkler Systems" t:review_building_code=2014 t:applicant_last_name=SOROKKO t:street_name="SOUTH 2 STREET" t:state=NY t:block=2417 t:in_compliance_with_nycecc=True t:building_type="2 Family" t:city=DOUGLASTON t:exempt_from_nycecc=False t:filing_status=Objections t:owner_s_business_name="VERSATILE ENGINEERING, P.C." t:owner_s_street_name="47-30 244 STREET" t:applicant_professional_title=PE t:little_e=No t:zip=11362 t:includes_permanent_removal=No t:applicant_license=072800 t:job_filing_number=B00000143-I1 t:borough=BROOKLYN t:work_on_floor="CEL, BAS, ROF, 1-4" t:unmapped_cco_street=No t:applicant_first_name=ROMAN t:request_legalization=No t:sprinkler_work_type=True t:house_no=124 t:plumbing_work_type=True t:lot=16 m:commmunity_board=301 m:initial_cost=49500 m:total_construction_floor_area=3542 m:proposed_height=52 m:proposed_no_of_stories=5 m:existing_dwelling_units=3 m:proposed_dwelling_units=2 m:existing_height=39 m:bin=3063093 m:existing_stories=3

series e:w9ak-ipjd d:2017-01-18T00:18:22.000Z t:specialinspectionrequirement="Fire-Resistant Penetrations and Joints" t:review_building_code=2014 t:applicant_last_name=SOROKKO t:street_name="SOUTH 2 STREET" t:state=NY t:block=2417 t:in_compliance_with_nycecc=True t:building_type="2 Family" t:city=DOUGLASTON t:exempt_from_nycecc=False t:filing_status=Objections t:owner_s_business_name="VERSATILE ENGINEERING, P.C." t:owner_s_street_name="47-30 244 STREET" t:applicant_professional_title=PE t:little_e=No t:zip=11362 t:includes_permanent_removal=No t:applicant_license=072800 t:job_filing_number=B00000143-I1 t:borough=BROOKLYN t:work_on_floor="CEL, BAS, ROF, 1-4" t:unmapped_cco_street=No t:applicant_first_name=ROMAN t:request_legalization=No t:sprinkler_work_type=True t:house_no=124 t:plumbing_work_type=True t:lot=16 m:commmunity_board=301 m:initial_cost=49500 m:total_construction_floor_area=3542 m:proposed_height=52 m:proposed_no_of_stories=5 m:existing_dwelling_units=3 m:proposed_dwelling_units=2 m:existing_height=39 m:bin=3063093 m:existing_stories=3
```

## Meta Commands

```ls
metric m:bin p:integer l:Bin t:dataTypeName=number

metric m:commmunity_board p:integer l:"Commmunity - Board" t:dataTypeName=number

metric m:initial_cost p:integer l:"Initial Cost" t:dataTypeName=number

metric m:total_construction_floor_area p:integer l:"Total Construction Floor Area" t:dataTypeName=number

metric m:existing_stories p:integer l:"Existing Stories" t:dataTypeName=number

metric m:existing_height p:integer l:"Existing Height" t:dataTypeName=number

metric m:existing_dwelling_units p:integer l:"Existing Dwelling Units" t:dataTypeName=number

metric m:proposed_no_of_stories p:integer l:"Proposed No of Stories" t:dataTypeName=number

metric m:proposed_height p:integer l:"Proposed Height" t:dataTypeName=number

metric m:proposed_dwelling_units p:integer l:"Proposed Dwelling Units" t:dataTypeName=number

entity e:w9ak-ipjd l:"DOB NOW: Build ? Job Application Filings" t:attribution="Department of Buildings (DOB)" t:url=https://data.cityofnewyork.us/api/views/w9ak-ipjd

property e:w9ak-ipjd t:meta.view v:id=w9ak-ipjd v:category="Housing & Development" v:averageRating=0 v:name="DOB NOW: Build ? Job Application Filings" v:attribution="Department of Buildings (DOB)"

property e:w9ak-ipjd t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:w9ak-ipjd t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | job_filing_number | filing_status | house_no | street_name     | borough  | block | lot | bin     | commmunity_board | work_on_floor          | apt_condo_no_s | applicant_professional_title | applicant_license | applicant_first_name | applicants_middle_initial | applicant_last_name | owner_s_business_name       | owner_s_street_name  | city       | state | zip   | filing_representative_first_name | filing_representative_middle_initial | filing_representative_last_name | filing_representative_business_name | filing_representative_street_name | filing_representative_city | filing_representative_state | filing_representative_zip | sprinkler_work_type | plumbing_work_type | initial_cost | total_construction_floor_area | review_building_code | little_e | unmapped_cco_street | request_legalization | includes_permanent_removal | in_compliance_with_nycecc | exempt_from_nycecc | building_type | existing_stories | existing_height | existing_dwelling_units | proposed_no_of_stories | proposed_height | proposed_dwelling_units | specialinspectionrequirement             | special_inspection_agency_number | progressinspectionrequirement      | built_1_information_value | built_2_information_value | built_2_a_information_value | built_2_b_information_value | 
| =========== | ================= | ============= | ======== | =============== | ======== | ===== | === | ======= | ================ | ====================== | ============== | ============================ | ================= | ==================== | ========================= | =================== | =========================== | ==================== | ========== | ===== | ===== | ================================ | ==================================== | =============================== | =================================== | ================================= | ========================== | =========================== | ========================= | =================== | ================== | ============ | ============================= | ==================== | ======== | =================== | ==================== | ========================== | ========================= | ================== | ============= | ================ | =============== | ======================= | ====================== | =============== | ======================= | ======================================== | ================================ | ================================== | ========================= | ========================= | =========================== | =========================== | 
| 1477697124  | B00000043-I1      | Approved      | 54       | Greene Avenue   | BROOKLYN | 1958  | 19  | 3055872 | 302              | Cel, Bas, Osp, 1, 2, 3 |                | PE                           | 065574            | CHRIS                |                           | SIDERIS             |                             | 217-22 NORTHERN BLVD | BAYSIDE    | NY    | 11361 |                                  |                                      |                                 |                                     |                                   |                            |                             |                           | True                | True               | 56800        | 3894                          | 2014                 | No       | No                  | No                   | No                         | False                     | True               | Other         | 3                | 41              | 3                       | 3                      | 41              | 3                       | Sprinkler Systems                        | 003434                           | Energy Code Compliance Inspections |                           |                           |                             |                             | 
| 1484698702  | B00000143-I1      | Objections    | 124      | SOUTH 2 STREET  | BROOKLYN | 2417  | 16  | 3063093 | 301              | CEL, BAS, ROF, 1-4     |                | PE                           | 072800            | ROMAN                |                           | SOROKKO             | VERSATILE ENGINEERING, P.C. | 47-30 244 STREET     | DOUGLASTON | NY    | 11362 |                                  |                                      |                                 |                                     |                                   |                            |                             |                           | True                | True               | 49500        | 3542                          | 2014                 | No       | No                  | No                   | No                         | True                      | False              | 2 Family      | 3                | 39              | 3                       | 5                      | 52              | 2                       | Sprinkler Systems                        |                                  |                                    |                           |                           |                             |                             | 
| 1484698702  | B00000143-I1      | Objections    | 124      | SOUTH 2 STREET  | BROOKLYN | 2417  | 16  | 3063093 | 301              | CEL, BAS, ROF, 1-4     |                | PE                           | 072800            | ROMAN                |                           | SOROKKO             | VERSATILE ENGINEERING, P.C. | 47-30 244 STREET     | DOUGLASTON | NY    | 11362 |                                  |                                      |                                 |                                     |                                   |                            |                             |                           | True                | True               | 49500        | 3542                          | 2014                 | No       | No                  | No                   | No                         | True                      | False              | 2 Family      | 3                | 39              | 3                       | 5                      | 52              | 2                       | Fire-Resistant Penetrations and Joints   |                                  |                                    |                           |                           |                             |                             | 
| 1484698702  | B00000143-I1      | Objections    | 124      | SOUTH 2 STREET  | BROOKLYN | 2417  | 16  | 3063093 | 301              | CEL, BAS, ROF, 1-4     |                | PE                           | 072800            | ROMAN                |                           | SOROKKO             | VERSATILE ENGINEERING, P.C. | 47-30 244 STREET     | DOUGLASTON | NY    | 11362 |                                  |                                      |                                 |                                     |                                   |                            |                             |                           | True                | True               | 49500        | 3542                          | 2014                 | No       | No                  | No                   | No                         | True                      | False              | 2 Family      | 3                | 39              | 3                       | 5                      | 52              | 2                       | Post-Installed Anchors                   |                                  |                                    |                           |                           |                             |                             | 
| 1485303202  | B00000136-I1      | Permit Entire | 379      | Lefferts Avenue | BROOKLYN | 1321  | 48  | 3393507 | 309              | 1st                    |                | PE                           | 095837            | DMITRY               |                           | LEVIN               | LEVIN ENGINEERING PLLC      | 28 DOOLEY STREET     | BROOKLYN   | NY    | 11235 |                                  |                                      |                                 |                                     |                                   |                            |                             |                           | True                | False              | 5000         | 0                             | 2014                 | No       | No                  | No                   | No                         | False                     | True               | Other         | 8                | 80              | 16                      | 8                      | 80              | 16                      | Sprinkler Systems                        | 001267                           |                                    |                           |                           |                             |                             | 
| 1485303202  | B00000150-I1      | Permit Entire | 904      | RUTLAND ROAD    | BROOKLYN | 4606  | 1   | 3099712 | 317              | cel, 1                 |                | PE                           | 095837            | DMITRY               |                           | LEVIN               | LEVIN ENGINEERING PLLC      | 28 DOOLEY STREET     | BROOKLYN   | NY    | 11235 |                                  |                                      |                                 |                                     |                                   |                            |                             |                           | False               | True               | 5000         | 0                             | 2014                 | No       | No                  | No                   | No                         | True                      |                    | Other         | 2                | 30              | 1                       | 2                      | 30              | 1                       | Fire-Resistant Penetrations and Joints   | 1267                             | HVAC insulation and sealing        |                           |                           |                             |                             | 
| 1485303202  | B00000139-I1      | Permit Entire | 48       | Cedar Street    | BROOKLYN | 3232  | 1   | 3387647 | 304              | 7, 8                   |                | PE                           | 095837            | DMITRY               |                           | LEVIN               | LEVIN ENGINEERING PLLC      | 28 DOOLEY STREET     | BROOKLYN   | NY    | 11235 |                                  |                                      |                                 |                                     |                                   |                            |                             |                           | True                | False              | 8000         | 0                             | 2014                 | No       | No                  | No                   | No                         | False                     | True               | Other         | 8                | 84              | 0                       | 8                      | 84              | 0                       | Sprinkler Systems                        | 1267                             |                                    |                           |                           |                             |                             | 
| 1485908874  | B00000119-I1      | Permit Entire | 642      | DRIGGS AVENUE   | BROOKLYN | 2352  | 25  | 3321245 | 301              | CEL                    |                | RA                           | 036490            | YOUNG SAM            |                           | YU                  | SOYU ARCHITECTURE, INC.     | 162-19 DEPOT ROAD    | FLUSHING   | NY    | 11358 | JI YOUNG                         |                                      | CHOI                            |                                     | 41-23 MURRAY STREET               | FLUSHING                   | NY                          | 11355                     | False               | True               | 16000        | 0                             | 2014                 | No       | No                  | No                   | No                         | False                     | True               | Other         | 4                | 45              | 8                       | 4                      | 45              | 8                       | Fire-Resistant Penetrations and Joints   | 005252                           | Final                              |                           |                           |                             |                             | 
| 1485908874  | B00000119-I1      | Permit Entire | 642      | DRIGGS AVENUE   | BROOKLYN | 2352  | 25  | 3321245 | 301              | CEL                    |                | RA                           | 036490            | YOUNG SAM            |                           | YU                  | SOYU ARCHITECTURE, INC.     | 162-19 DEPOT ROAD    | FLUSHING   | NY    | 11358 | JI YOUNG                         |                                      | CHOI                            |                                     | 41-23 MURRAY STREET               | FLUSHING                   | NY                          | 11355                     | False               | True               | 16000        | 0                             | 2014                 | No       | No                  | No                   | No                         | False                     | True               | Other         | 4                | 45              | 8                       | 4                      | 45              | 8                       | High Pressure Fuel- Gas Piping (Welding) | 5252                             | Final                              |                           |                           |                             |                             | 
| 1485908874  | B00000119-P1      | Approved      | 642      | DRIGGS AVENUE   | BROOKLYN | 2352  | 25  | 3321245 | 301              | CEL                    |                | RA                           | 036490            | YOUNG SAM            |                           | YU                  | SOYU ARCHITECTURE, INC.     | 162-19 DEPOT ROAD    | FLUSHING   | NY    | 11358 | JI YOUNG                         |                                      | CHOI                            |                                     | 41-23 MURRAY STREET               | FLUSHING                   | NY                          | 11355                     | False               | True               | 16000        | 0                             | 2014                 | No       | No                  | No                   | No                         | False                     | True               | Other         | 4                | 45              | 8                       | 4                      | 45              | 8                       | High Pressure Fuel- Gas Piping (Welding) | 5252                             | Final                              |                           |                           |                             |                             | 
```