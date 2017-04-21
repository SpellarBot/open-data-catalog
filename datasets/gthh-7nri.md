# New York State Commission for the Blind (NYSCB) Comprehensive Service Contractors

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-york-state-commission-for-the-blind-nyscb-comprehensive-service-contractors) |
| Metadata | [Link](https://data.ny.gov/api/views/gthh-7nri) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/gthh-7nri/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/gthh-7nri/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | gthh-7nri |
| Name | New York State Commission for the Blind (NYSCB) Comprehensive Service Contractors |
| Attribution | Office of Children and Family Services |
| Category | Human Services |
| Tags | blind, visually handicapped, employment |
| Created | 2014-01-10T15:44:24Z |
| Publication Date | 2016-03-23T14:18:29Z |

## Description

This provides information on the location, contact persons, services provided and capacity of New York State Commission for the Blind (NYSCB) Comprehensive Service Contractors.

## Columns

```ls
| Included | Schema Type | Field Name                         | Name                               | Data Type | Render Type |
| ======== | =========== | ================================== | ================================== | ========= | =========== |
| No       | time        | :updated_at                        | updated_at                         | meta_data | meta_data   |
| Yes      | series tag  | agency_name                        | Agency Name                        | text      | text        |
| No       |             | address                            | Address                            | text      | text        |
| Yes      | series tag  | city                               | City                               | text      | text        |
| Yes      | series tag  | state                              | State                              | text      | text        |
| Yes      | series tag  | zip_code                           | Zip Code                           | text      | text        |
| Yes      | series tag  | phone_number                       | Phone Number                       | text      | text        |
| Yes      | series tag  | fax                                | Fax                                | text      | text        |
| Yes      | series tag  | region_covered                     | Region Covered                     | text      | text        |
| Yes      | series tag  | assisted_living_program_1          | Assisted Living Program 1          | text      | text        |
| Yes      | series tag  | assisted_living_program_2          | Assisted Living Program 2          | text      | text        |
| Yes      | series tag  | assisted_living_program_2e         | Assisted Living Program 2E         | text      | text        |
| Yes      | series tag  | assisted_living_program_3          | Assisted Living Program 3          | text      | text        |
| Yes      | series tag  | vision_rehab                       | Vision Rehabilitation              | text      | text        |
| Yes      | series tag  | orientation_mobility               | Orientation Mobility               | text      | text        |
| Yes      | series tag  | social_casework_level_1            | Social Casework Level 1            | text      | text        |
| Yes      | series tag  | social_casework_level_2            | Social Casework Level 2            | text      | text        |
| Yes      | series tag  | pre_vocationa_young_adults         | Pre Vocational Young Adults        | text      | text        |
| Yes      | series tag  | diagnostic_vocational_evaluation   | Diagnostic Vocational Evaluation   | text      | text        |
| Yes      | series tag  | academic_instruction               | Academic Instruction               | text      | text        |
| Yes      | series tag  | vocational_skills                  | Vocational Skills                  | text      | text        |
| Yes      | series tag  | work_readiness                     | Work Readiness                     | text      | text        |
| Yes      | series tag  | work_experience                    | Work Experience                    | text      | text        |
| Yes      | series tag  | comprehensive_service_contract     | Comprehensive Service Contract     | text      | text        |
| Yes      | series tag  | job_placement_service_dve_contract | Job Placement Service/DVE Contract | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:gthh-7nri d:2016-03-22T12:44:19.000Z t:fax=718-515-2844 t:phone_number=718-515-2800 t:zip_code=10457 t:vocational_skills=N t:state=NY t:region_covered=8 t:assisted_living_program_2e=N t:agency_name="Bronx Independent Living Services" t:pre_vocationa_young_adults=N t:comprehensive_service_contract=N t:city=Bronxville t:diagnostic_vocational_evaluation=Y t:job_placement_service_dve_contract=Y t:assisted_living_program_1=N t:social_casework_level_2=N t:work_readiness=N t:academic_instruction=N t:social_casework_level_1=N t:vision_rehab=N t:assisted_living_program_2=N t:assisted_living_program_3=N t:work_experience=N t:orientation_mobility=N m:row_number.gthh-7nri=1

series e:gthh-7nri d:2016-03-22T12:44:19.000Z t:fax=212-727-4374 t:phone_number=212-727-4200 t:zip_code=10017 t:vocational_skills=N t:state=NY t:region_covered=6,7,8 t:assisted_living_program_2e=N t:agency_name="FEDCAP Rehabilitation Services, Inc." t:pre_vocationa_young_adults=N t:comprehensive_service_contract=Y t:city="New York" t:diagnostic_vocational_evaluation=Y t:job_placement_service_dve_contract=Y t:assisted_living_program_1=N t:social_casework_level_2=N t:work_readiness=N t:academic_instruction=N t:social_casework_level_1=N t:vision_rehab=N t:assisted_living_program_2=N t:assisted_living_program_3=N t:work_experience=N t:orientation_mobility=N m:row_number.gthh-7nri=2

series e:gthh-7nri d:2016-03-22T17:55:34.000Z t:fax=585-232-8265 t:phone_number=585-232-1111 t:zip_code=14620 t:vocational_skills=N t:state=NY t:region_covered=2 t:assisted_living_program_2e=Y t:agency_name=ABVI-Goodwill t:pre_vocationa_young_adults=Y t:comprehensive_service_contract=Y t:city=Rochester t:diagnostic_vocational_evaluation=Y t:job_placement_service_dve_contract=Y t:assisted_living_program_1=Y t:social_casework_level_2=Y t:work_readiness=N t:academic_instruction=N t:social_casework_level_1=Y t:vision_rehab=Y t:assisted_living_program_2=Y t:assisted_living_program_3=Y t:work_experience=Y t:orientation_mobility=Y m:row_number.gthh-7nri=3
```

## Meta Commands

```ls
metric m:row_number.gthh-7nri p:long l:"Row Number"

entity e:gthh-7nri l:"New York State Commission for the Blind (NYSCB) Comprehensive Service Contractors" t:attribution="Office of Children and Family Services" t:url=https://data.ny.gov/api/views/gthh-7nri

property e:gthh-7nri t:meta.view v:id=gthh-7nri v:category="Human Services" v:attributionLink=http://ocfs.ny.gov/main/cbvh/ v:averageRating=0 v:name="New York State Commission for the Blind (NYSCB) Comprehensive Service Contractors" v:attribution="Office of Children and Family Services"

property e:gthh-7nri t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:gthh-7nri t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:gthh-7nri t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | agency_name                                                   | address                     | city       | state | zip_code | phone_number       | fax          | region_covered | assisted_living_program_1 | assisted_living_program_2 | assisted_living_program_2e | assisted_living_program_3 | vision_rehab | orientation_mobility | social_casework_level_1 | social_casework_level_2 | pre_vocationa_young_adults | diagnostic_vocational_evaluation | academic_instruction | vocational_skills | work_readiness | work_experience | comprehensive_service_contract | job_placement_service_dve_contract | 
| =========== | ============================================================= | =========================== | ========== | ===== | ======== | ================== | ============ | ============== | ========================= | ========================= | ========================== | ========================= | ============ | ==================== | ======================= | ======================= | ========================== | ================================ | ==================== | ================= | ============== | =============== | ============================== | ================================== | 
| 1458650659  | Bronx Independent Living Services                             | 4419 2rd Street, Suite 2C   | Bronxville | NY    | 10457    | 718-515-2800       | 718-515-2844 | 8              | N                         | N                         | N                          | N                         | N            | N                    | N                       | N                       | N                          | Y                                | N                    | N                 | N              | N               | N                              | Y                                  | 
| 1458650659  | FEDCAP Rehabilitation Services, Inc.                          | 633 Third Avenue, 6th Floor | New York   | NY    | 10017    | 212-727-4200       | 212-727-4374 | 6,7,8          | N                         | N                         | N                          | N                         | N            | N                    | N                       | N                       | N                          | Y                                | N                    | N                 | N              | N               | Y                              | Y                                  | 
| 1458669334  | ABVI-Goodwill                                                 | 422 South Clinton Avenue    | Rochester  | NY    | 14620    | 585-232-1111       | 585-232-8265 | 2              | Y                         | Y                         | Y                          | Y                         | Y            | Y                    | Y                       | Y                       | Y                          | Y                                | N                    | N                 | N              | Y               | Y                              | Y                                  | 
| 1458669334  | Center for Disability Services                                | 314 South Manning Boulevard | Albany     | NY    | 12208    | 518-482-1548 x3501 | 518-482-1629 | 4              | N                         | N                         | N                          | N                         | N            | N                    | N                       | N                       | N                          | N                                | N                    | N                 | N              | N               | N                              | N                                  | 
| 1458669334  | Goodwill Industries of Greater NY & Northern NJ               | 4-21 27th Avenue            | Astoria    | NY    | 11102    | 718-777-6357       | 718-371-7236 | 8              | N                         | N                         | N                          | N                         | N            | N                    | N                       | N                       | N                          | Y                                | N                    | N                 | N              | N               | N                              | Y                                  | 
| 1458669334  | Jawonio, Inc.                                                 | 260 N. Little Tor Road      | New City   | NY    | 10956    | 845-639-3540       | 845-639-3539 | 5              | N                         | N                         | N                          | N                         | N            | N                    | N                       | N                       | N                          | N                                | N                    | N                 | N              | N               | N                              | Y                                  | 
| 1458669334  | Abilities, Inc                                                | 201 I.U. Willets Road       | Albertson  | NY    | 11507    | 516-465-1491       | 516-465-3757 | 8              | N                         | N                         | N                          | N                         | N            | N                    | N                       | N                       | N                          | Y                                | N                    | N                 | N              | N               | N                              | Y                                  | 
| 1458669334  | Susan B. Todd                                                 | 84 Copperfield Road         | Rochester  | NY    | 14615    | 585-621-5793       | 585-720-1301 | 1              | N                         | N                         | N                          | N                         | N            | N                    | N                       | N                       | N                          | N                                | N                    | N                 | N              | N               | N                              | N                                  | 
| 1458669334  | Elizabeth Pierce Olmsted, MD Center for the Visually Impaired | 1170 Main Street            | Buffalo    | NY    | 14209    | 716-882-1025       | 716-882-5577 | 1              | Y                         | Y                         | Y                          | Y                         | Y            | Y                    | Y                       | Y                       | Y                          | Y                                | N                    | Y                 | Y              | Y               | Y                              | Y                                  | 
| 1458669334  | Liberty Resources, Inc                                        | 1065 James Street           | Syracuse   | NY    | 13203    | 315-425-1004       | 315-479-7884 | 3              | N                         | N                         | N                          | N                         | N            | N                    | N                       | N                       | N                          | N                                | N                    | N                 | N              | N               | N                              | Y                                  | 
```