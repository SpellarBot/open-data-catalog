# FY17 Budget Simulator data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fy17-budget-simulator-data) |
| Metadata | [Link](https://data.austintexas.gov/api/views/2u4b-s8xd) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/2u4b-s8xd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/2u4b-s8xd/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 2u4b-s8xd |
| Name | FY17 Budget Simulator data |
| Category | Financial |
| Tags | public engagement, budget, budget simulator, finance, fy17 |
| Created | 2016-08-31T15:30:56Z |
| Publication Date | 2016-08-31T16:15:23Z |

## Description

This is an upload of Austin Budget Simulator data used in the FY 2016-17 Public Engagement Report. Through use of the online Austin Budget Simulator, participants were able to increase funding by 5% or 10%, maintain current funding, or decrease funding by 5% or 10% in 49 different City of Austin Service Areas. This dataset includes service area responses and open-ended comments. The Austin Budget Simulator was available to general public from April 22 to July 15, 2016. This dataset shows results received from self-selected participants during that period. More information about the Austin Budget Simulator activity and results are available in the FY 2016-17 Public Engagement Report: http://austintexas.gov/sites/default/files/files/Finance/FY_2016-17_Public_Engagement_Report.pdf.

## Columns

```ls
| Included | Schema Type    | Field Name                                                                                  | Name                                                                                              | Data Type | Render Type |
| ======== | ============== | =========================================================================================== | ================================================================================================= | ========= | =========== |
| No       | time           | :updated_at                                                                                 | updated_at                                                                                        | meta_data | meta_data   |
| Yes      | numeric metric | parks_libraries_pools_aquatic_programming                                                   | (PARKS & LIBRARIES) Pools & Aquatic Programming                                                   | number    | text        |
| Yes      | numeric metric | parks_libraries_facility_and_grounds_services_park_planning                                 | (PARKS & LIBRARIES) Facility and Grounds Services & Park Planning                                 | number    | text        |
| Yes      | numeric metric | parks_libraries_athletics_recreation_program_services                                       | (PARKS & LIBRARIES) Athletics & Recreation Program Services                                       | number    | text        |
| Yes      | numeric metric | parks_libraries_forestry_park_rangers_nature_cultural_programs                              | (PARKS & LIBRARIES) Forestry, Park Rangers, Nature & Cultural Programs                            | number    | text        |
| Yes      | numeric metric | parks_libraries_cemeteries                                                                  | (PARKS & LIBRARIES) Cemeteries                                                                    | number    | text        |
| Yes      | numeric metric | parks_libraries_library_materials_collection_acquisition                                    | (PARKS & LIBRARIES) Library Materials Collection & Acquisition                                    | number    | text        |
| Yes      | numeric metric | parks_libraries_library_programming_services                                                | (PARKS & LIBRARIES) Library Programming & Services                                                | number    | text        |
| Yes      | series tag     | parks_libraries_comment                                                                     | (PARKS & LIBRARIES) Comment                                                                       | text      | text        |
| Yes      | numeric metric | public_safety_emergency_communications_9_1_1_call_center                                    | (Public Safety) Emergency Communications: 9-1-1 Call Center                                       | number    | text        |
| Yes      | numeric metric | public_safety_police_investigations                                                         | (Public Safety) Police Investigations                                                             | number    | text        |
| Yes      | numeric metric | public_safety_neighborhood_based_policing_patrol                                            | (Public Safety) Neighborhood-Based Policing / Patrol                                              | number    | text        |
| Yes      | numeric metric | public_safety_victim_services_forensics_and_strategic_support                               | (Public Safety) Victim Services, Forensics, and Strategic Support                                 | number    | text        |
| Yes      | numeric metric | public_safety_emergency_medical_response_operations                                         | (Public Safety) Emergency Medical Response Operations                                             | number    | text        |
| Yes      | numeric metric | public_safety_ems_community_relations_injury_prevention                                     | (Public Safety) EMS Community Relations & Injury Prevention                                       | number    | text        |
| Yes      | numeric metric | public_safety_fire_emergency_prevention_outreach                                            | (Public Safety) Fire/Emergency Prevention & Outreach                                              | number    | text        |
| Yes      | numeric metric | public_safety_fire_emergency_response_operations                                            | (Public Safety) Fire/Emergency Response Operations                                                | number    | text        |
| Yes      | numeric metric | public_safety_municipal_court                                                               | (Public Safety) Municipal Court                                                                   | number    | text        |
| Yes      | numeric metric | public_safety_community_court                                                               | (Public Safety) Community Court                                                                   | number    | text        |
| Yes      | series tag     | public_safety_comment                                                                       | (Public Safety) Comment                                                                           | text      | text        |
| Yes      | numeric metric | planning_development_comprehensive_planning_and_implementation                              | (Planning & Development) Comprehensive Planning and Implementation                                | number    | text        |
| Yes      | numeric metric | planning_development_annexation_zoning_case_management                                      | (Planning & Development) Annexation & Zoning Case Management                                      | number    | text        |
| Yes      | numeric metric | planning_development_one_stop_shop_inspection_plan_review_and_permits                       | (Planning & Development) One Stop Shop - Inspection, Plan Review, and Permits                     | number    | text        |
| Yes      | series tag     | planning_development_comment                                                                | (Planning & Development) Comment                                                                  | text      | text        |
| Yes      | numeric metric | economic_development_cultural_arts_music_entertainment                                      | (Economic Development) Cultural Arts & Music Entertainment                                        | number    | text        |
| Yes      | numeric metric | economic_development_global_business_recruitment_small_business_development                 | (Economic Development) Global Business Recruitment & Small Business Development                   | number    | text        |
| Yes      | numeric metric | economic_development_redevelopment_commercial_stabilization                                 | (Economic Development) Redevelopment & Commercial Stabilization                                   | number    | text        |
| Yes      | series tag     | economic_development_comment                                                                | (Economic Development) Comment                                                                    | text      | text        |
| Yes      | numeric metric | watershed_protection_flood_hazard_mitigation                                                | (Watershed Protection) Flood Hazard Mitigation                                                    | number    | text        |
| Yes      | numeric metric | watershed_protection_waterway_maintenance_stream_restoration                                | (Watershed Protection) Waterway Maintenance & Stream Restoration                                  | number    | text        |
| Yes      | numeric metric | watershed_protection_water_quality_policy_planning_and_protection                           | (Watershed Protection) Water Quality Policy, Planning, and Protection                             | number    | text        |
| Yes      | numeric metric | watershed_protection_transfer_for_capital_improvement_projects                              | (Watershed Protection) Transfer for Capital Improvement Projects                                  | number    | text        |
| Yes      | series tag     | watershed_protection_comment                                                                | (Watershed Protection) Comment                                                                    | text      | text        |
| Yes      | numeric metric | infrastructure_transportation_transportation_arterial_management_traffic_signs_and_markings | (Infrastructure & Transportation) Transportation Arterial Management & Traffic Signs and Markings | number    | text        |
| Yes      | numeric metric | infrastructure_transportation_bicycle_infrastructure_management_transportation_engineering  | (Infrastructure & Transportation) Bicycle Infrastructure Management & Transportation Engineering  | number    | text        |
| Yes      | numeric metric | infrastructure_transportation_street_bridge_preventive_maintenance_and_repair               | (Infrastructure & Transportation) Street & Bridge Preventive Maintenance and Repair               | number    | text        |
| Yes      | numeric metric | infrastructure_transportation_right_of_way_maintenance_sidewalk_management                  | (Infrastructure & Transportation) Right-of-Way Maintenance & Sidewalk Management                  | number    | text        |
| Yes      | series tag     | infrastructure_transportation_comment                                                       | (Infrastructure & Transportation) Comment                                                         | text      | text        |
| Yes      | numeric metric | health_housing_animal_shelter_pet_adoption_services                                         | (Health & Housing) Animal Shelter & Pet Adoption Services                                         | number    | text        |
| Yes      | numeric metric | health_housing_disease_prevention_health_promotion_services                                 | (Health & Housing) Disease Prevention & Health Promotion Services                                 | number    | text        |
| Yes      | numeric metric | health_housing_quality_of_life_initiatives                                                  | (Health & Housing) Quality of Life Initiatives                                                    | number    | text        |
| Yes      | numeric metric | health_housing_youth_family_services_workforce_development                                  | (Health & Housing) Youth/Family Services & Workforce Development                                  | number    | text        |
| Yes      | numeric metric | health_housing_basic_needs_transitional_housing_permanent_supportive_housing                | (Health & Housing) Basic Needs, Transitional Housing, & Permanent Supportive Housing              | number    | text        |
| Yes      | numeric metric | health_housing_behavioral_mental_health                                                     | (Health & Housing) Behavioral & Mental Health                                                     | number    | text        |
| Yes      | numeric metric | health_housing_public_health_inspections                                                    | (Health & Housing) Public Health Inspections                                                      | number    | text        |
| Yes      | numeric metric | health_housing_rental_owner_buyer_developer_assistance_community_development                | (Health & Housing) Rental/Owner/Buyer/Developer Assistance & Community Development                | number    | text        |
| Yes      | series tag     | health_housing_comment                                                                      | (Health & Housing) Comment                                                                        | text      | text        |
| Yes      | numeric metric | clean_community_litter_abatement_waste_diversion                                            | (Clean Community) Litter Abatement & Waste Diversion                                              | number    | text        |
| Yes      | numeric metric | clean_community_austin_code_case_investigations                                             | (Clean Community) Austin Code Case Investigations                                                 | number    | text        |
| Yes      | numeric metric | clean_community_austin_code_licensing_registration_compliance                               | (Clean Community) Austin Code Licensing & Registration Compliance                                 | number    | text        |
| Yes      | series tag     | clean_community_comment                                                                     | (Clean Community) Comment                                                                         | text      | text        |
| Yes      | numeric metric | austin_resource_recovery_trash_and_recycling_collection_services                            | (Austin Resource Recovery) Trash and Recycling Collection Services                                | number    | text        |
| Yes      | series tag     | austin_resource_recovery_comment                                                            | (Austin Resource Recovery) Comment                                                                | text      | text        |
| Yes      | numeric metric | austin_energy_austin_energy_customer_care                                                   | (Austin Energy) Austin Energy Customer Care                                                       | number    | text        |
| Yes      | numeric metric | austin_energy_power_supply_operations                                                       | (Austin Energy) Power Supply Operations                                                           | number    | text        |
| Yes      | numeric metric | austin_energy_energy_efficiency_programs                                                    | (Austin Energy) Energy Efficiency Programs                                                        | number    | text        |
| Yes      | series tag     | austin_energy_comment                                                                       | (Austin Energy) Comment                                                                           | text      | text        |
| Yes      | numeric metric | austin_water_water_environmental_affairs_conservation                                       | (Austin Water) Water Environmental Affairs & Conservation                                         | number    | text        |
| Yes      | numeric metric | austin_water_water_delivery_services                                                        | (Austin Water) Water Delivery Services                                                            | number    | text        |
| Yes      | numeric metric | austin_water_water_treatment_and_resource_management                                        | (Austin Water) Water Treatment and Resource Management                                            | number    | text        |
| Yes      | series tag     | austin_water_comment                                                                        | (Austin Water) Comment                                                                            | text      | text        |
| Yes      | numeric metric | total_income                                                                                | Total Income                                                                                      | number    | text        |
| Yes      | numeric metric | total_expenditure                                                                           | Total Expenditure                                                                                 | number    | text        |
| Yes      | series tag     | city_council_district                                                                       | City Council District                                                                             | text      | text        |
| Yes      | series tag     | any_final_comments_on_this_exercise_or_the_city_of_austin_s_budget                          | Any final comments on this exercise or the City of Austin’s budget?                               | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:2u4b-s8xd d:2016-08-31T15:31:07.000Z t:city_council_district="District 8" m:parks_libraries_pools_aquatic_programming=0 m:watershed_protection_waterway_maintenance_stream_restoration=0 m:parks_libraries_facility_and_grounds_services_park_planning=5 m:public_safety_emergency_medical_response_operations=5 m:planning_development_comprehensive_planning_and_implementation=0 m:planning_development_annexation_zoning_case_management=0 m:health_housing_rental_owner_buyer_developer_assistance_community_development=0 m:parks_libraries_library_materials_collection_acquisition=0 m:health_housing_youth_family_services_workforce_development=5 m:austin_energy_energy_efficiency_programs=0 m:economic_development_global_business_recruitment_small_business_development=5 m:infrastructure_transportation_street_bridge_preventive_maintenance_and_repair=0 m:infrastructure_transportation_bicycle_infrastructure_management_transportation_engineering=5 m:public_safety_victim_services_forensics_and_strategic_support=5 m:health_housing_behavioral_mental_health=5 m:public_safety_municipal_court=0 m:clean_community_austin_code_case_investigations=0 m:health_housing_disease_prevention_health_promotion_services=5 m:health_housing_animal_shelter_pet_adoption_services=5 m:watershed_protection_water_quality_policy_planning_and_protection=0 m:public_safety_ems_community_relations_injury_prevention=0 m:austin_resource_recovery_trash_and_recycling_collection_services=0 m:planning_development_one_stop_shop_inspection_plan_review_and_permits=0 m:public_safety_fire_emergency_response_operations=0 m:total_expenditure=100.66000366210938 m:austin_energy_power_supply_operations=0 m:parks_libraries_athletics_recreation_program_services=0 m:total_income=0 m:public_safety_fire_emergency_prevention_outreach=0 m:infrastructure_transportation_transportation_arterial_management_traffic_signs_and_markings=0 m:public_safety_community_court=0 m:health_housing_basic_needs_transitional_housing_permanent_supportive_housing=0 m:austin_energy_austin_energy_customer_care=0 m:public_safety_police_investigations=0 m:clean_community_litter_abatement_waste_diversion=0 m:public_safety_neighborhood_based_policing_patrol=0 m:austin_water_water_environmental_affairs_conservation=0 m:austin_water_water_treatment_and_resource_management=0 m:economic_development_cultural_arts_music_entertainment=-5 m:parks_libraries_library_programming_services=0 m:watershed_protection_transfer_for_capital_improvement_projects=0 m:public_safety_emergency_communications_9_1_1_call_center=5 m:parks_libraries_cemeteries=0 m:watershed_protection_flood_hazard_mitigation=0 m:austin_water_water_delivery_services=0 m:health_housing_public_health_inspections=0 m:infrastructure_transportation_right_of_way_maintenance_sidewalk_management=0 m:health_housing_quality_of_life_initiatives=5 m:parks_libraries_forestry_park_rangers_nature_cultural_programs=0 m:clean_community_austin_code_licensing_registration_compliance=0 m:economic_development_redevelopment_commercial_stabilization=0

series e:2u4b-s8xd d:2016-08-31T15:31:07.000Z t:city_council_district="District 5" t:parks_libraries_comment=increase m:parks_libraries_pools_aquatic_programming=0 m:watershed_protection_waterway_maintenance_stream_restoration=0 m:parks_libraries_facility_and_grounds_services_park_planning=0 m:public_safety_emergency_medical_response_operations=0 m:planning_development_comprehensive_planning_and_implementation=0 m:planning_development_annexation_zoning_case_management=0 m:health_housing_rental_owner_buyer_developer_assistance_community_development=0 m:parks_libraries_library_materials_collection_acquisition=0 m:health_housing_youth_family_services_workforce_development=0 m:austin_energy_energy_efficiency_programs=0 m:economic_development_global_business_recruitment_small_business_development=0 m:infrastructure_transportation_street_bridge_preventive_maintenance_and_repair=0 m:infrastructure_transportation_bicycle_infrastructure_management_transportation_engineering=0 m:public_safety_victim_services_forensics_and_strategic_support=0 m:health_housing_behavioral_mental_health=0 m:public_safety_municipal_court=0 m:clean_community_austin_code_case_investigations=0 m:health_housing_disease_prevention_health_promotion_services=0 m:health_housing_animal_shelter_pet_adoption_services=0 m:watershed_protection_water_quality_policy_planning_and_protection=0 m:public_safety_ems_community_relations_injury_prevention=0 m:austin_resource_recovery_trash_and_recycling_collection_services=0 m:planning_development_one_stop_shop_inspection_plan_review_and_permits=0 m:public_safety_fire_emergency_response_operations=0 m:total_expenditure=100.08999633789062 m:austin_energy_power_supply_operations=0 m:parks_libraries_athletics_recreation_program_services=0 m:total_income=0 m:public_safety_fire_emergency_prevention_outreach=0 m:infrastructure_transportation_transportation_arterial_management_traffic_signs_and_markings=0 m:public_safety_community_court=0 m:health_housing_basic_needs_transitional_housing_permanent_supportive_housing=0 m:austin_energy_austin_energy_customer_care=0 m:public_safety_police_investigations=0 m:clean_community_litter_abatement_waste_diversion=0 m:public_safety_neighborhood_based_policing_patrol=0 m:austin_water_water_environmental_affairs_conservation=0 m:austin_water_water_treatment_and_resource_management=0 m:economic_development_cultural_arts_music_entertainment=0 m:parks_libraries_library_programming_services=0 m:watershed_protection_transfer_for_capital_improvement_projects=0 m:public_safety_emergency_communications_9_1_1_call_center=0 m:parks_libraries_cemeteries=0 m:watershed_protection_flood_hazard_mitigation=0 m:austin_water_water_delivery_services=0 m:health_housing_public_health_inspections=0 m:infrastructure_transportation_right_of_way_maintenance_sidewalk_management=0 m:health_housing_quality_of_life_initiatives=0 m:parks_libraries_forestry_park_rangers_nature_cultural_programs=10 m:clean_community_austin_code_licensing_registration_compliance=0 m:economic_development_redevelopment_commercial_stabilization=0

series e:2u4b-s8xd d:2016-08-31T15:31:07.000Z t:city_council_district="District 10" t:health_housing_comment="Free adoption for pets may ease the load. 
Get the homeless off the streets.
I don't know what the Developer Assistance is or why we should pay for it." t:parks_libraries_comment="Given the thousands of dollars paid, we should not have to also pay to get into our city parks or pay parking to go there. The city is double dipping and not everyone out here is rich." t:any_final_comments_on_this_exercise_or_the_city_of_austin_s_budget="There should be incentives for city staff to find ways to economize. Budgets should be newly considered each year, and last minute spending should be prohibited." t:planning_development_comment="City planning for more economic uses of our funds is critical. Austin seems to come up with plans that cost 5-10 times more than the national average and only address part of the problem. What a waste of planning time." t:infrastructure_transportation_comment="The percentage of people that ride bikes compared to the amount of money it costs is unreasonable. Meanwhile, we have potholes everywhere. Make the mass transit work by providing parking near the main stations." t:austin_water_comment="Do not place restrictions on what days of the week we can water when there is no water shortage. Mandatory restrictions should only be applied to large water users." t:austin_energy_comment="More rebates to encourage energy savings. They seem to last only a short time." t:austin_resource_recovery_comment="Why do we get less and less service at higher and higher costs? 
There is poor coordination between services, one often interfering with another. Like collecting bulky items on the same day as collecting trash.
No one understands how to recycle properly. An educational campaign with PSAs would really help. They should be offered free by the stations." t:public_safety_comment="I;m not sure what some of these are." m:parks_libraries_pools_aquatic_programming=0 m:watershed_protection_waterway_maintenance_stream_restoration=0 m:parks_libraries_facility_and_grounds_services_park_planning=0 m:public_safety_emergency_medical_response_operations=0 m:planning_development_comprehensive_planning_and_implementation=5 m:planning_development_annexation_zoning_case_management=0 m:health_housing_rental_owner_buyer_developer_assistance_community_development=-5 m:parks_libraries_library_materials_collection_acquisition=5 m:health_housing_youth_family_services_workforce_development=0 m:austin_energy_energy_efficiency_programs=5 m:economic_development_global_business_recruitment_small_business_development=0 m:infrastructure_transportation_street_bridge_preventive_maintenance_and_repair=5 m:infrastructure_transportation_bicycle_infrastructure_management_transportation_engineering=-10 m:public_safety_victim_services_forensics_and_strategic_support=-5 m:health_housing_behavioral_mental_health=0 m:public_safety_municipal_court=0 m:clean_community_austin_code_case_investigations=0 m:health_housing_disease_prevention_health_promotion_services=0 m:health_housing_animal_shelter_pet_adoption_services=5 m:watershed_protection_water_quality_policy_planning_and_protection=0 m:public_safety_ems_community_relations_injury_prevention=-5 m:austin_resource_recovery_trash_and_recycling_collection_services=0 m:planning_development_one_stop_shop_inspection_plan_review_and_permits=0 m:public_safety_fire_emergency_response_operations=0 m:total_expenditure=100.19000244140625 m:austin_energy_power_supply_operations=0 m:parks_libraries_athletics_recreation_program_services=0 m:total_income=0 m:public_safety_fire_emergency_prevention_outreach=5 m:infrastructure_transportation_transportation_arterial_management_traffic_signs_and_markings=0 m:public_safety_community_court=0 m:health_housing_basic_needs_transitional_housing_permanent_supportive_housing=5 m:austin_energy_austin_energy_customer_care=0 m:public_safety_police_investigations=0 m:clean_community_litter_abatement_waste_diversion=0 m:public_safety_neighborhood_based_policing_patrol=0 m:austin_water_water_environmental_affairs_conservation=0 m:austin_water_water_treatment_and_resource_management=0 m:economic_development_cultural_arts_music_entertainment=0 m:parks_libraries_library_programming_services=0 m:watershed_protection_transfer_for_capital_improvement_projects=0 m:public_safety_emergency_communications_9_1_1_call_center=0 m:parks_libraries_cemeteries=-5 m:watershed_protection_flood_hazard_mitigation=0 m:austin_water_water_delivery_services=0 m:health_housing_public_health_inspections=0 m:infrastructure_transportation_right_of_way_maintenance_sidewalk_management=0 m:health_housing_quality_of_life_initiatives=0 m:parks_libraries_forestry_park_rangers_nature_cultural_programs=0 m:clean_community_austin_code_licensing_registration_compliance=0 m:economic_development_redevelopment_commercial_stabilization=0
```

## Meta Commands

```ls
metric m:parks_libraries_pools_aquatic_programming p:float l:"(PARKS & LIBRARIES) Pools & Aquatic Programming" t:dataTypeName=number

metric m:parks_libraries_facility_and_grounds_services_park_planning p:float l:"(PARKS & LIBRARIES) Facility and Grounds Services & Park Planning" t:dataTypeName=number

metric m:parks_libraries_athletics_recreation_program_services p:float l:"(PARKS & LIBRARIES) Athletics & Recreation Program Services" t:dataTypeName=number

metric m:parks_libraries_forestry_park_rangers_nature_cultural_programs p:float l:"(PARKS & LIBRARIES) Forestry, Park Rangers, Nature & Cultural Programs" t:dataTypeName=number

metric m:parks_libraries_cemeteries p:float l:"(PARKS & LIBRARIES) Cemeteries" t:dataTypeName=number

metric m:parks_libraries_library_materials_collection_acquisition p:float l:"(PARKS & LIBRARIES) Library Materials Collection & Acquisition" t:dataTypeName=number

metric m:parks_libraries_library_programming_services p:float l:"(PARKS & LIBRARIES) Library Programming & Services" t:dataTypeName=number

metric m:public_safety_emergency_communications_9_1_1_call_center p:float l:"(Public Safety) Emergency Communications: 9-1-1 Call Center" t:dataTypeName=number

metric m:public_safety_police_investigations p:float l:"(Public Safety) Police Investigations" t:dataTypeName=number

metric m:public_safety_neighborhood_based_policing_patrol p:float l:"(Public Safety) Neighborhood-Based Policing / Patrol" t:dataTypeName=number

metric m:public_safety_victim_services_forensics_and_strategic_support p:float l:"(Public Safety) Victim Services, Forensics, and Strategic Support" t:dataTypeName=number

metric m:public_safety_emergency_medical_response_operations p:float l:"(Public Safety) Emergency Medical Response Operations" t:dataTypeName=number

metric m:public_safety_ems_community_relations_injury_prevention p:float l:"(Public Safety) EMS Community Relations & Injury Prevention" t:dataTypeName=number

metric m:public_safety_fire_emergency_prevention_outreach p:float l:"(Public Safety) Fire/Emergency Prevention & Outreach" t:dataTypeName=number

metric m:public_safety_fire_emergency_response_operations p:float l:"(Public Safety) Fire/Emergency Response Operations" t:dataTypeName=number

metric m:public_safety_municipal_court p:float l:"(Public Safety) Municipal Court" t:dataTypeName=number

metric m:public_safety_community_court p:float l:"(Public Safety) Community Court" t:dataTypeName=number

metric m:planning_development_comprehensive_planning_and_implementation p:float l:"(Planning & Development) Comprehensive Planning and Implementation" t:dataTypeName=number

metric m:planning_development_annexation_zoning_case_management p:float l:"(Planning & Development) Annexation & Zoning Case Management" t:dataTypeName=number

metric m:planning_development_one_stop_shop_inspection_plan_review_and_permits p:float l:"(Planning & Development) One Stop Shop - Inspection, Plan Review, and Permits" t:dataTypeName=number

metric m:economic_development_cultural_arts_music_entertainment p:float l:"(Economic Development) Cultural Arts & Music Entertainment" t:dataTypeName=number

metric m:economic_development_global_business_recruitment_small_business_development p:float l:"(Economic Development) Global Business Recruitment & Small Business Development" t:dataTypeName=number

metric m:economic_development_redevelopment_commercial_stabilization p:float l:"(Economic Development) Redevelopment & Commercial Stabilization" t:dataTypeName=number

metric m:watershed_protection_flood_hazard_mitigation p:float l:"(Watershed Protection) Flood Hazard Mitigation" t:dataTypeName=number

metric m:watershed_protection_waterway_maintenance_stream_restoration p:float l:"(Watershed Protection) Waterway Maintenance & Stream Restoration" t:dataTypeName=number

metric m:watershed_protection_water_quality_policy_planning_and_protection p:float l:"(Watershed Protection) Water Quality Policy, Planning, and Protection" t:dataTypeName=number

metric m:watershed_protection_transfer_for_capital_improvement_projects p:float l:"(Watershed Protection) Transfer for Capital Improvement Projects" t:dataTypeName=number

metric m:infrastructure_transportation_transportation_arterial_management_traffic_signs_and_markings p:float l:"(Infrastructure & Transportation) Transportation Arterial Management & Traffic Signs and Markings" t:dataTypeName=number

metric m:infrastructure_transportation_bicycle_infrastructure_management_transportation_engineering p:float l:"(Infrastructure & Transportation) Bicycle Infrastructure Management & Transportation Engineering" t:dataTypeName=number

metric m:infrastructure_transportation_street_bridge_preventive_maintenance_and_repair p:float l:"(Infrastructure & Transportation) Street & Bridge Preventive Maintenance and Repair" t:dataTypeName=number

metric m:infrastructure_transportation_right_of_way_maintenance_sidewalk_management p:float l:"(Infrastructure & Transportation) Right-of-Way Maintenance & Sidewalk Management" t:dataTypeName=number

metric m:health_housing_animal_shelter_pet_adoption_services p:float l:"(Health & Housing) Animal Shelter & Pet Adoption Services" t:dataTypeName=number

metric m:health_housing_disease_prevention_health_promotion_services p:float l:"(Health & Housing) Disease Prevention & Health Promotion Services" t:dataTypeName=number

metric m:health_housing_quality_of_life_initiatives p:float l:"(Health & Housing) Quality of Life Initiatives" t:dataTypeName=number

metric m:health_housing_youth_family_services_workforce_development p:float l:"(Health & Housing) Youth/Family Services & Workforce Development" t:dataTypeName=number

metric m:health_housing_basic_needs_transitional_housing_permanent_supportive_housing p:float l:"(Health & Housing) Basic Needs, Transitional Housing, & Permanent Supportive Housing" t:dataTypeName=number

metric m:health_housing_behavioral_mental_health p:float l:"(Health & Housing) Behavioral & Mental Health" t:dataTypeName=number

metric m:health_housing_public_health_inspections p:float l:"(Health & Housing) Public Health Inspections" t:dataTypeName=number

metric m:health_housing_rental_owner_buyer_developer_assistance_community_development p:float l:"(Health & Housing) Rental/Owner/Buyer/Developer Assistance & Community Development" t:dataTypeName=number

metric m:clean_community_litter_abatement_waste_diversion p:float l:"(Clean Community) Litter Abatement & Waste Diversion" t:dataTypeName=number

metric m:clean_community_austin_code_case_investigations p:float l:"(Clean Community) Austin Code Case Investigations" t:dataTypeName=number

metric m:clean_community_austin_code_licensing_registration_compliance p:float l:"(Clean Community) Austin Code Licensing & Registration Compliance" t:dataTypeName=number

metric m:austin_resource_recovery_trash_and_recycling_collection_services p:float l:"(Austin Resource Recovery) Trash and Recycling Collection Services" t:dataTypeName=number

metric m:austin_energy_austin_energy_customer_care p:float l:"(Austin Energy) Austin Energy Customer Care" t:dataTypeName=number

metric m:austin_energy_power_supply_operations p:float l:"(Austin Energy) Power Supply Operations" t:dataTypeName=number

metric m:austin_energy_energy_efficiency_programs p:float l:"(Austin Energy) Energy Efficiency Programs" t:dataTypeName=number

metric m:austin_water_water_environmental_affairs_conservation p:float l:"(Austin Water) Water Environmental Affairs & Conservation" t:dataTypeName=number

metric m:austin_water_water_delivery_services p:float l:"(Austin Water) Water Delivery Services" t:dataTypeName=number

metric m:austin_water_water_treatment_and_resource_management p:float l:"(Austin Water) Water Treatment and Resource Management" t:dataTypeName=number

metric m:total_income p:float l:"Total Income" t:dataTypeName=number

metric m:total_expenditure p:float l:"Total Expenditure" t:dataTypeName=number

entity e:2u4b-s8xd l:"FY17 Budget Simulator data" t:url=https://data.austintexas.gov/api/views/2u4b-s8xd

property e:2u4b-s8xd t:meta.view v:id=2u4b-s8xd v:category=Financial v:averageRating=0 v:name="FY17 Budget Simulator data"

property e:2u4b-s8xd t:meta.view.owner v:id=kat7-hf3v v:profileImageUrlMedium=/api/users/kat7-hf3v/profile_images/THUMB v:profileImageUrlLarge=/api/users/kat7-hf3v/profile_images/LARGE v:screenName="Katy Zamesnik" v:profileImageUrlSmall=/api/users/kat7-hf3v/profile_images/TINY v:displayName="Katy Zamesnik"

property e:2u4b-s8xd t:meta.view.tableauthor v:id=kat7-hf3v v:profileImageUrlMedium=/api/users/kat7-hf3v/profile_images/THUMB v:profileImageUrlLarge=/api/users/kat7-hf3v/profile_images/LARGE v:screenName="Katy Zamesnik" v:profileImageUrlSmall=/api/users/kat7-hf3v/profile_images/TINY v:roleName=editor v:displayName="Katy Zamesnik"
```