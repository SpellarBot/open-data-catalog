# Local Social Services District (SSD) Staff Counts by Function: Beginning State Fiscal Year 2004-2005

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/local-social-services-district-ssd-staff-counts-by-function-beginning-state-fiscal-ye-2004) |
| Metadata | [Link](https://data.ny.gov/api/views/rcn6-yg9v) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/rcn6-yg9v/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/rcn6-yg9v/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | rcn6-yg9v |
| Name | Local Social Services District (SSD) Staff Counts by Function: Beginning State Fiscal Year 2004-2005 |
| Attribution | New York State Office of Temporary and Disability Assistance (OTDA) |
| Category | Human Services |
| Tags | social services staffing, county social services staffing, ta, pa, public assistance, temporary assistance, welfare, medicaid, heap, snap, home energy assistance program, supplemental nutrition as... |
| Created | 2016-08-08T14:07:04Z |
| Publication Date | 2016-09-28T20:00:47Z |

## Description

The data table provides the State Fiscal Year monthly average count of Local Social Services District full-time equivalent staff positions by functional area.

## Columns

```ls
| Included | Schema Type    | Field Name                                                   | Name                                                         | Data Type | Render Type |
| ======== | ============== | ============================================================ | ============================================================ | ========= | =========== |
| Yes      | numeric metric | state_fiscal_year_ending                                     | State Fiscal Year Ending                                     | number    | number      |
| Yes      | series tag     | district_code                                                | District Code                                                | text      | text        |
| Yes      | series tag     | county                                                       | District                                                     | text      | text        |
| Yes      | numeric metric | total_staffing                                               | Total Staffing                                               | number    | number      |
| Yes      | numeric metric | intake_case_maintenance                                      | Intake/Case Maintenance                                      | number    | number      |
| Yes      | numeric metric | services_program                                             | Services Program                                             | number    | number      |
| Yes      | numeric metric | services_administration                                      | Services Administration                                      | number    | number      |
| Yes      | numeric metric | employment_programs                                          | Employment Programs                                          | number    | number      |
| Yes      | numeric metric | medicaid_eligibility_determination_and_payment_authorization | Medicaid Eligibility Determination and Payment Authorization | number    | number      |
| Yes      | numeric metric | medicaid_policy_planning_and_administration                  | Medicaid Policy Planning and Administration                  | number    | number      |
| Yes      | numeric metric | training                                                     | Training                                                     | number    | number      |
| Yes      | numeric metric | supplemental_nutrition_assistance_program                    | Supplemental Nutrition Assistance Program                    | number    | number      |
| Yes      | numeric metric | child_support                                                | Child Support                                                | number    | number      |
| Yes      | numeric metric | fraud_and_abuse                                              | Fraud and Abuse                                              | number    | number      |
| Yes      | numeric metric | home_energy_assistance_program                               | Home Energy Assistance Program                               | number    | number      |
| Yes      | numeric metric | welfare_management_system                                    | Welfare Management System                                    | number    | number      |
| Yes      | numeric metric | other_reimbursible_programs                                  | Other Reimbursable Programs                                  | number    | number      |
| Yes      | numeric metric | tanf_funded_services                                         | TANF Funded Services                                         | number    | number      |
| Yes      | numeric metric | administative_overhead                                       | Administrative Overhead                                      | number    | number      |
| Yes      | numeric metric | non_administrative_local_program                             | Non-Administrative Local Program                             | number    | number      |
| Yes      | numeric metric | overall_overhead                                             | Overall Overhead                                             | number    | number      |
```

## Time Field

```ls
Value = 2004
Format & Zone = yyyy
```

## Data Commands

```ls
series e:rcn6-yg9v d:2004-01-01T00:00:00.000Z t:district_code=01 t:county=Albany m:administative_overhead=56 m:medicaid_policy_planning_and_administration=4 m:total_staffing=532 m:overall_overhead=3 m:supplemental_nutrition_assistance_program=24 m:training=3 m:fraud_and_abuse=12 m:services_program=167 m:intake_case_maintenance=77 m:state_fiscal_year_ending=2005 m:non_administrative_local_program=64 m:other_reimbursible_programs=14 m:employment_programs=13 m:services_administration=14 m:medicaid_eligibility_determination_and_payment_authorization=52 m:welfare_management_system=1 m:child_support=30

series e:rcn6-yg9v d:2004-01-01T00:00:00.000Z t:district_code=02 t:county=Allegany m:administative_overhead=7 m:medicaid_policy_planning_and_administration=0 m:total_staffing=113 m:overall_overhead=0 m:supplemental_nutrition_assistance_program=13 m:training=0 m:fraud_and_abuse=2 m:services_program=7 m:intake_case_maintenance=16 m:state_fiscal_year_ending=2005 m:non_administrative_local_program=0 m:other_reimbursible_programs=6 m:employment_programs=4 m:services_administration=22 m:medicaid_eligibility_determination_and_payment_authorization=20 m:welfare_management_system=2 m:child_support=15

series e:rcn6-yg9v d:2004-01-01T00:00:00.000Z t:district_code=03 t:county=Broome m:administative_overhead=26 m:medicaid_policy_planning_and_administration=5 m:total_staffing=427 m:overall_overhead=1 m:supplemental_nutrition_assistance_program=20 m:training=2 m:fraud_and_abuse=2 m:services_program=98 m:intake_case_maintenance=38 m:state_fiscal_year_ending=2005 m:non_administrative_local_program=80 m:other_reimbursible_programs=17 m:employment_programs=22 m:services_administration=22 m:medicaid_eligibility_determination_and_payment_authorization=61 m:welfare_management_system=7 m:child_support=27
```

## Meta Commands

```ls
metric m:state_fiscal_year_ending p:integer l:"State Fiscal Year Ending" d:"The ending year of the SFY the data pertains to. The New York State Fiscal Year runs April through March." t:dataTypeName=number

metric m:total_staffing p:integer l:"Total Staffing" d:"Total Full-Time Equivalent (FTE) staff positions claimed by the SSD." t:dataTypeName=number

metric m:intake_case_maintenance p:integer l:"Intake/Case Maintenance" d:"FTEs assigned to Public Assistance intake and case maintenance functions." t:dataTypeName=number

metric m:services_program p:integer l:"Services Program" d:"FTEs assigned to Service Program direct service delivery." t:dataTypeName=number

metric m:services_administration p:integer l:"Services Administration" d:"FTEs assigned to Service Program Administration." t:dataTypeName=number

metric m:employment_programs p:integer l:"Employment Programs" d:"FTEs assigned to operating and administering employment programs." t:dataTypeName=number

metric m:medicaid_eligibility_determination_and_payment_authorization p:integer l:"Medicaid Eligibility Determination and Payment Authorization" d:"FTEs assigned to Medicaid eligibility determination and payment authorization." t:dataTypeName=number

metric m:medicaid_policy_planning_and_administration p:integer l:"Medicaid Policy Planning and Administration" d:"FTEs assigned to Medicaid policy planning and administration." t:dataTypeName=number

metric m:training p:integer l:Training d:"FTEs assigned to training functions" t:dataTypeName=number

metric m:supplemental_nutrition_assistance_program p:integer l:"Supplemental Nutrition Assistance Program" d:"FTEs assigned to administering the Supplemental Nutrition Assistance Program" t:dataTypeName=number

metric m:child_support p:integer l:"Child Support" d:"FTEs assigned to child support establishment and collection functions." t:dataTypeName=number

metric m:fraud_and_abuse p:integer l:"Fraud and Abuse" d:"FTEs assigned to detecting, investigating fraud and abuse and obtaining restitution." t:dataTypeName=number

metric m:home_energy_assistance_program p:integer l:"Home Energy Assistance Program" d:"FTEs assigned to determining eligibility and providing payments under the Home Energy Assistance Program." t:dataTypeName=number

metric m:welfare_management_system p:integer l:"Welfare Management System" d:"FTEs assigned to administrative activities related to operating the Welfare Management System." t:dataTypeName=number

metric m:other_reimbursible_programs p:integer l:"Other Reimbursable Programs" d:"FTEs assigned to miscellaneous and small reimbursable programs including demonstrations or other program requiring reimbursement tracking." t:dataTypeName=number

metric m:tanf_funded_services p:integer l:"TANF Funded Services" d:"FTEs assigned to TANF funded service projects and related overhead." t:dataTypeName=number

metric m:administative_overhead p:integer l:"Administrative Overhead" d:"FTEs assigned to administrative and support staff working in multiple SSD functions that cannot accurately allocate their time to discrete functions." t:dataTypeName=number

metric m:non_administrative_local_program p:integer l:"Non-Administrative Local Program" d:"FTEs assigned to operating local facilities such as public homes and shelters." t:dataTypeName=number

metric m:overall_overhead p:integer l:"Overall Overhead" d:"FTEs assigned to duties not solely related to the previous functions or to multiple functions when it is impractical to do a time study." t:dataTypeName=number

entity e:rcn6-yg9v l:"Local Social Services District (SSD) Staff Counts by Function: Beginning State Fiscal Year 2004-2005" t:attribution="New York State Office of Temporary and Disability Assistance (OTDA)" t:url=https://data.ny.gov/api/views/rcn6-yg9v

property e:rcn6-yg9v t:meta.view v:id=rcn6-yg9v v:category="Human Services" v:attributionLink=https://otda.ny.gov/programs/ v:averageRating=0 v:name="Local Social Services District (SSD) Staff Counts by Function: Beginning State Fiscal Year 2004-2005" v:attribution="New York State Office of Temporary and Disability Assistance (OTDA)"

property e:rcn6-yg9v t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:rcn6-yg9v t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| state_fiscal_year_ending | district_code | county      | total_staffing | intake_case_maintenance | services_program | services_administration | employment_programs | medicaid_eligibility_determination_and_payment_authorization | medicaid_policy_planning_and_administration | training | supplemental_nutrition_assistance_program | child_support | fraud_and_abuse | home_energy_assistance_program | welfare_management_system | other_reimbursible_programs | tanf_funded_services | administative_overhead | non_administrative_local_program | overall_overhead | 
| ======================== | ============= | =========== | ============== | ======================= | ================ | ======================= | =================== | ============================================================ | =========================================== | ======== | ========================================= | ============= | =============== | ============================== | ========================= | =========================== | ==================== | ====================== | ================================ | ================ | 
| 2005                     | 01            | Albany      | 532            | 77                      | 167              | 14                      | 13                  | 52                                                           | 4                                           | 3        | 24                                        | 30            | 12              |                                | 1                         | 14                          |                      | 56                     | 64                               | 3                | 
| 2005                     | 02            | Allegany    | 113            | 16                      | 7                | 22                      | 4                   | 20                                                           | 0                                           | 0        | 13                                        | 15            | 2               |                                | 2                         | 6                           |                      | 7                      | 0                                | 0                | 
| 2005                     | 03            | Broome      | 427            | 38                      | 98               | 22                      | 22                  | 61                                                           | 5                                           | 2        | 20                                        | 27            | 2               |                                | 7                         | 17                          |                      | 26                     | 80                               | 1                | 
| 2005                     | 04            | Cattaraugus | 181            | 24                      | 18               | 26                      | 16                  | 34                                                           | 0                                           | 1        | 14                                        | 19            | 3               |                                | 6                         | 6                           |                      | 14                     | 0                                | 0                | 
| 2005                     | 05            | Cayuga      | 135            | 17                      | 35               | 5                       | 7                   | 22                                                           | 0                                           | 1        | 11                                        | 10            | 5               |                                | 4                         | 6                           |                      | 9                      | 0                                | 1                | 
| 2005                     | 06            | Chautauqua  | 309            | 39                      | 99               | 2                       | 20                  | 42                                                           | 10                                          | 1        | 14                                        | 36            | 7               |                                | 2                         | 11                          |                      | 26                     | 0                                | 0                | 
| 2005                     | 07            | Chemung     | 156            | 14                      | 51               | 11                      | 3                   | 18                                                           | 0                                           | 1        | 8                                         | 18            | 7               |                                | 1                         | 12                          |                      | 13                     | 0                                | 0                | 
| 2005                     | 08            | Chenango    | 107            | 4                       | 27               | 3                       | 5                   | 9                                                            | 0                                           | 3        | 5                                         | 10            | 7               |                                | 3                         | 2                           |                      | 10                     | 19                               | 0                | 
| 2005                     | 09            | Clinton     | 179            | 14                      | 58               | 8                       | 11                  | 22                                                           | 3                                           | 1        | 15                                        | 15            | 4               |                                | 3                         | 8                           |                      | 17                     | 0                                | 0                | 
| 2005                     | 10            | Columbia    | 129            | 8                       | 33               | 11                      | 3                   | 19                                                           | 1                                           | 1        | 6                                         | 11            | 7               |                                | 5                         | 5                           |                      | 19                     | 0                                | 0                | 
```