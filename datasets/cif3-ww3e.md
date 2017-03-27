# RSBS MOM: Multifamily On-Site Survey, Measure Level, New York State Residential Statewide Baseline Study

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/rsbs-mom-multifamily-on-site-survey-measure-level-new-york-state-residential-statewide-bas) |
| Metadata | [Link](https://data.ny.gov/api/views/cif3-ww3e) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/cif3-ww3e/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/cif3-ww3e/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | cif3-ww3e |
| Name | RSBS MOM: Multifamily On-Site Survey, Measure Level, New York State Residential Statewide Baseline Study |
| Attribution | New York State Energy Research and Development Authority |
| Category | Energy & Environment |
| Tags | rsbl study, rsbs, energy efficiency, multifamily homes, market characterization, baseline study |
| Created | 2015-11-03T19:26:35Z |
| Publication Date | 2015-11-17T22:47:29Z |

## Description

The New York State Energy Research and Development Authority (NYSERDA), in collaboration with the New York State Department of Public Service (DPS), conducted a statewide residential baseline study (study) from 2011 to 2014 of the single-family and multifamily residential housing segments, including new construction, and a broad range of energy uses and efficiency measures.  This dataset includes data collected from a total of 67 on-site inspections of multifamily buildings. Data collected during the inspections covers property characteristics, heating and cooling equipment, water heating equipment, appliances, lighting, clothes washing and drying, miscellaneous energy using equipment, and observable operating behavior.  The objective of the on-site inspections was to enhance the residential baseline study with detailed on-site information and, to the degree possible, verify self-reported data from the phone and web surveys. The on-site inspection data is segmented to cover both common space equipment and tenant-unit equipment.

## Columns

```ls
| Included | Schema Type    | Field Name                                                                                          | Name                                                                                                | Data Type | Render Type |
| ======== | ============== | =================================================================================================== | =================================================================================================== | ========= | =========== |
| No       | time           | :updated_at                                                                                         | updated_at                                                                                          | meta_data | meta_data   |
| Yes      | series tag     | equipment_category                                                                                  | Equipment Category                                                                                  | text      | text        |
| Yes      | series tag     | measure_id                                                                                          | Measure ID                                                                                          | text      | text        |
| Yes      | series tag     | area_served                                                                                         | Area Served                                                                                         | text      | text        |
| Yes      | series tag     | unit_id                                                                                             | Unit ID                                                                                             | text      | text        |
| Yes      | series tag     | common_space_id                                                                                     | Common Space ID                                                                                     | text      | text        |
| Yes      | series tag     | site_id                                                                                             | Site ID                                                                                             | text      | text        |
| Yes      | series tag     | multifamily_owner_manager_mom_survey_id                                                             | Multifamily Owner Manager (MOM) Survey ID                                                           | text      | text        |
| Yes      | series tag     | climate_zone                                                                                        | Climate Zone                                                                                        | text      | text        |
| Yes      | series tag     | region                                                                                              | Region                                                                                              | text      | text        |
| Yes      | series tag     | county                                                                                              | County                                                                                              | text      | text        |
| Yes      | series tag     | construction_type                                                                                   | Construction Type                                                                                   | text      | text        |
| Yes      | series tag     | electric_provider                                                                                   | Electric Provider                                                                                   | text      | text        |
| Yes      | series tag     | gas_provider                                                                                        | Gas Provider                                                                                        | text      | text        |
| Yes      | series tag     | appliance_category                                                                                  | Appliance Category                                                                                  | text      | text        |
| Yes      | series tag     | appliance_category_id                                                                               | Appliance Category ID                                                                               | text      | text        |
| Yes      | series tag     | type_style_of_appliance                                                                             | Type/Style of Appliance                                                                             | text      | text        |
| Yes      | series tag     | other_large_appliances                                                                              | Other Large Appliances                                                                              | text      | text        |
| Yes      | series tag     | number_of_units                                                                                     | Number of Appliance Units                                                                           | text      | text        |
| Yes      | series tag     | year_of_appliance_manufacture                                                                       | Year of Appliance Manufacture                                                                       | text      | text        |
| Yes      | series tag     | appliance_manufacture_year_known_or_estimated                                                       | Appliance Manufacture Year Known or Estimated                                                       | text      | text        |
| Yes      | series tag     | appliance_manufacturer                                                                              | Appliance Manufacturer                                                                              | text      | text        |
| Yes      | series tag     | model_number                                                                                        | Appliance Model Number                                                                              | text      | text        |
| Yes      | series tag     | wattage_of_appliance                                                                                | Wattage of Appliance                                                                                | text      | text        |
| Yes      | series tag     | appliance_fuel                                                                                      | Appliance Fuel                                                                                      | text      | text        |
| Yes      | series tag     | energy_star_certified                                                                               | Appliance Energy Star Certified?                                                                    | text      | text        |
| Yes      | series tag     | computer_monitor_type                                                                               | Computer Monitor Type                                                                               | text      | text        |
| Yes      | series tag     | dishwasher_efficiency_energy_factor                                                                 | Dishwasher Efficiency (Energy Factor)                                                               | text      | text        |
| No       |                | dishwasher_usage_pattern_cycles_week                                                                | Dishwasher Usage Pattern (cycles/week)                                                              | text      | text        |
| Yes      | series tag     | fan_usage                                                                                           | Fan Usage                                                                                           | text      | text        |
| Yes      | series tag     | humidifier_dehumidifier_usage                                                                       | Humidifier/Dehumidifier Usage                                                                       | text      | text        |
| Yes      | series tag     | clothes_washing_machine_temperature                                                                 | Clothes Washing Machine Temperature                                                                 | text      | text        |
| No       |                | clothes_washer_usage_pattern_loads_week                                                             | Clothes Washer Usage Pattern (loads/week)                                                           | text      | text        |
| Yes      | series tag     | heated_pool_hot_tub                                                                                 | Heated Pool/Hot Tub                                                                                 | text      | text        |
| Yes      | series tag     | location_of_refrigerator                                                                            | Location of Refrigerator                                                                            | text      | text        |
| Yes      | series tag     | size_of_refrigerator_freezer_cubic_ft                                                               | Size of Refrigerator/Freezer (cubic ft.)                                                            | text      | text        |
| Yes      | series tag     | refrigerator_with_an_indoor_water_dispenser                                                         | Refrigerator with an In-door Water Dispenser                                                        | text      | text        |
| Yes      | series tag     | television_screen_size_inches                                                                       | Television Screen Size (inches)                                                                     | text      | text        |
| Yes      | series tag     | air_duct_insulation_type_in_unconditioned_space                                                     | Air Duct Insulation Type in Unconditioned Space                                                     | text      | text        |
| Yes      | series tag     | air_duct_type_in_unconditioned_space                                                                | Air Duct Type in Unconditioned Space                                                                | text      | text        |
| Yes      | series tag     | visual_inspection_of_air_duct_seal                                                                  | Visual Inspection of Air Duct Seal                                                                  | text      | text        |
| Yes      | series tag     | air_duct_distribution_in_unconditioned                                                              | Air Duct Distribution in Unconditioned (%)                                                          | text      | text        |
| Yes      | series tag     | air_duct_distribution_that_is_insulated_in_unconditioned_space                                      | Air Duct Distribution that is Insulated in Unconditioned Space (%)                                  | text      | text        |
| Yes      | series tag     | thickness_of_insulation_around_the_return_air_duct_inches                                           | Thickness of Insulation Around the Return Air Duct (inches)                                         | text      | text        |
| Yes      | series tag     | air_duct_supply_insulation_thickness_inches                                                         | Air Duct Supply Insulation Thickness (inches)                                                       | text      | text        |
| Yes      | series tag     | no_of_disconnected_air_ducts                                                                        | Number of Disconnected Air Ducts                                                                    | text      | text        |
| Yes      | series tag     | type_of_air_duct_system                                                                             | Type of Air Duct System                                                                             | text      | text        |
| Yes      | series tag     | type_of_building_served_by_dhw                                                                      | Type of Building Served by DHW                                                                      | text      | text        |
| Yes      | series tag     | dhw_type                                                                                            | DHW Type                                                                                            | text      | text        |
| Yes      | series tag     | dhw_fuel_type                                                                                       | DHW Fuel Type                                                                                       | text      | text        |
| Yes      | numeric metric | no_of_water_heaters                                                                                 | Number of Water Heaters                                                                             | number    | number      |
| Yes      | series tag     | dhw_manufacture_year                                                                                | DHW Manufacture Year                                                                                | text      | text        |
| Yes      | series tag     | dhw_manufacture_year_known_or_estimated                                                             | DHW Manufacture Year Known or Estimated                                                             | text      | text        |
| Yes      | series tag     | unit_manufacturer                                                                                   | DHW Unit Manufacturer                                                                               | text      | text        |
| Yes      | series tag     | unit_model                                                                                          | DHW Unit Model                                                                                      | text      | text        |
| Yes      | series tag     | unit_energy_factor                                                                                  | DHW Unit Energy Factor                                                                              | text      | text        |
| Yes      | series tag     | efficiency_data_source                                                                              | DHW Efficiency Data Source                                                                          | text      | text        |
| Yes      | series tag     | water_temperature_setting_dhw                                                                       | Water Temperature Setting (DHW)                                                                     | text      | text        |
| Yes      | series tag     | dhw_venting                                                                                         | DHW Venting                                                                                         | text      | text        |
| Yes      | series tag     | dhw_unit_heat_recovery                                                                              | DHW Unit Heat Recovery                                                                              | text      | text        |
| Yes      | series tag     | efficiency_rating_of_dhw_heat_recovery                                                              | Efficiency rating of DHW heat recovery                                                              | text      | text        |
| Yes      | series tag     | presence_of_orphan_natural_draft_dhw                                                                | Presence of Orphan Natural Draft DHW                                                                | text      | text        |
| Yes      | series tag     | storage_volume_of_the_unit_gallons                                                                  | Storage Volume of the DHW Unit (gallons)                                                            | text      | text        |
| Yes      | series tag     | thickness_of_dhw_pipe_insulation_inches                                                             | Thickness of DHW pipe insulation (inches)                                                           | text      | text        |
| Yes      | series tag     | dhw_insulation_thickness_inches                                                                     | DHW Insulation Thickness (inches)                                                                   | text      | text        |
| Yes      | series tag     | unit_in_conditioned_or_unconditioned_part_of_house                                                  | DHW Unit in Conditioned or Unconditioned Part of House?                                             | text      | text        |
| Yes      | series tag     | surface_type                                                                                        | Surface Type                                                                                        | text      | text        |
| Yes      | series tag     | construction_material_of_envelope                                                                   | Construction Material of Envelope                                                                   | text      | text        |
| Yes      | series tag     | construction_material_of_envelope_categorical                                                       | Construction Material of Envelope (Categorical)                                                     | text      | text        |
| Yes      | series tag     | depth_below_grade_feet                                                                              | Depth Below Grade (feet)                                                                            | text      | text        |
| Yes      | series tag     | ceiling_type                                                                                        | Ceiling Type                                                                                        | text      | text        |
| Yes      | series tag     | attic_access_insulation_level                                                                       | Attic Access Insulation Level                                                                       | text      | text        |
| Yes      | series tag     | attic_access_square_feet                                                                            | Attic Access Square Feet                                                                            | text      | text        |
| Yes      | series tag     | attic_access_weather_stripping                                                                      | Attic Access Weather Stripping                                                                      | text      | text        |
| Yes      | numeric metric | percentage_of_total_exterior_and_interior_surfaces_that_are_insulated                               | Percentage of total exterior and interior surfaces that are insulated                               | number    | number      |
| Yes      | series tag     | exterior_or_continuous_insulation_type                                                              | Exterior or continuous insulation type                                                              | text      | text        |
| Yes      | series tag     | data_source_for_the_on_site_inspector_determining_exterior_or_continuous_insulation_characteristics | Data source for the on-site inspector determining exterior or continuous insulation characteristics | text      | text        |
| Yes      | series tag     | exterior_or_continuous_insulation_quality_grade_i_iii                                               | Exterior or continuous insulation quality (grade I-III)                                             | text      | text        |
| Yes      | series tag     | exterior_or_continuous_insulation_thickness_inches                                                  | Exterior or continuous insulation thickness (inches)                                                | text      | text        |
| Yes      | series tag     | interior_or_cavity_insulation_type                                                                  | Interior or cavity insulation type                                                                  | text      | text        |
| Yes      | series tag     | data_source_for_the_on_site_inspector_determining_interior_or_cavity_insulation_characteristics     | Data source for the on-site inspector determining interior or cavity insulation characteristics     | text      | text        |
| Yes      | series tag     | interior_or_cavity_insulation_quality_grade_i_iii                                                   | Interior or cavity insulation quality (grade I-III)                                                 | text      | text        |
| Yes      | series tag     | interior_or_cavity_insulation_thickness_inches                                                      | Interior or cavity insulation thickness (inches)                                                    | text      | text        |
| Yes      | series tag     | does_the_home_have_perimeter_insulation                                                             | Does the home have perimeter insulation                                                             | text      | text        |
| Yes      | series tag     | window_or_door                                                                                      | Window Or Door                                                                                      | text      | text        |
| Yes      | series tag     | number_of_doors                                                                                     | Number of Doors                                                                                     | text      | text        |
| Yes      | series tag     | door_material                                                                                       | Door Material                                                                                       | text      | text        |
| Yes      | series tag     | door_weather_stripping                                                                              | Door Weather Stripping                                                                              | text      | text        |
| Yes      | series tag     | number_of_windows                                                                                   | Number of Windows                                                                                   | text      | text        |
| Yes      | series tag     | window_size_sqft                                                                                    | Window Size (sqft)                                                                                  | text      | text        |
| Yes      | series tag     | overall_window_condition                                                                            | Overall Window Condition                                                                            | text      | text        |
| Yes      | series tag     | u_factor_of_window_insulation                                                                       | U Factor of Window Insulation                                                                       | text      | text        |
| Yes      | series tag     | window_frame_type                                                                                   | Window Frame Type                                                                                   | text      | text        |
| Yes      | series tag     | window_glazing                                                                                      | Window Glazing                                                                                      | text      | text        |
| Yes      | series tag     | gas_filled_window                                                                                   | Gas Filled Window                                                                                   | text      | text        |
| Yes      | series tag     | presence_of_bay_windows                                                                             | Presence of Bay Windows                                                                             | text      | text        |
| Yes      | series tag     | storm_windows                                                                                       | Storm Windows                                                                                       | text      | text        |
| Yes      | series tag     | window_treatments                                                                                   | Window Treatments                                                                                   | text      | text        |
| Yes      | series tag     | hvac_controls_thermostat_type                                                                       | HVAC Controls Thermostat Type                                                                       | text      | text        |
| Yes      | series tag     | hvac_systems_served                                                                                 | HVAC Systems Served                                                                                 | text      | text        |
| Yes      | series tag     | cooling_setback_hours                                                                               | Cooling Setback Hours                                                                               | text      | text        |
| Yes      | series tag     | cooling_setback_temperature                                                                         | Cooling Setback Temperature                                                                         | text      | text        |
| Yes      | series tag     | heating_setback_hours                                                                               | Heating Setback Hours                                                                               | text      | text        |
| Yes      | series tag     | heating_setback_temperature                                                                         | Heating Setback Temperature                                                                         | text      | text        |
| Yes      | series tag     | set_point_temperature_in_cooling_season                                                             | Set Point Temperature in Cooling Season                                                             | text      | text        |
| Yes      | series tag     | set_point_temperature_in_heating_season                                                             | Set Point Temperature in Heating Season                                                             | text      | text        |
| Yes      | series tag     | status_of_thermostat_at_time_of_inspection                                                          | Status of Thermostat at Time of Inspection                                                          | text      | text        |
| Yes      | series tag     | programmable_thermostats                                                                            | Programmable Thermostats                                                                            | text      | text        |
| Yes      | series tag     | what_unit_does_the_hvac_cooling_system_serve                                                        | What Unit Does the HVAC Cooling System Serve?                                                       | text      | text        |
| Yes      | numeric metric | what_percentage_of_conditioned_space_does_the_hvac_cooling_unit_serve                               | What Percentage of Conditioned Space Does the HVAC Cooling Unit Serve?                              | number    | number      |
| Yes      | series tag     | is_hvac_cooling_primary_or_secondary_source                                                         | Is HVAC Cooling Primary or Secondary Source?                                                        | text      | text        |
| Yes      | series tag     | hvac_cooling_system_type                                                                            | HVAC Cooling System Type                                                                            | text      | text        |
| Yes      | series tag     | year_hvac_cooling_unit_was_manufactured                                                             | Year HVAC Cooling Unit was Manufactured                                                             | text      | text        |
| Yes      | series tag     | hvac_cooling_manufacture_year_known_or_estimated                                                    | HVAC Cooling Manufacture Year Known or Estimated                                                    | text      | text        |
| Yes      | series tag     | hvac_cooling_manufacturer                                                                           | HVAC Cooling Manufacturer                                                                           | text      | text        |
| Yes      | series tag     | hvac_cooling_model                                                                                  | HVAC Cooling System Model                                                                           | text      | text        |
| Yes      | series tag     | hvac_cooling_capacity_btu_hr                                                                        | HVAC Cooling Capacity (BTU/Hr.)                                                                     | text      | text        |
| Yes      | numeric metric | no_ac_units                                                                                         | Number of AC Units                                                                                  | number    | number      |
| Yes      | numeric metric | rated_efficiency_of_hvac_cooling_system                                                             | Rated Efficiency of HVAC Cooling System                                                             | number    | number      |
| Yes      | series tag     | hvac_cooling_efficiency_type                                                                        | HVAC Cooling Efficiency Type                                                                        | text      | text        |
| Yes      | series tag     | hvac_cooling_efficiency_data_source                                                                 | HVAC Cooling Efficiency Data Source                                                                 | text      | text        |
| Yes      | series tag     | is_hvac_cooling_energy_star                                                                         | Is HVAC Cooling Energy Star?                                                                        | text      | text        |
| Yes      | series tag     | observed_visual_condition_of_hvac_cooling_system                                                    | Observed Visual Condition of HVAC Cooling System                                                    | text      | text        |
| Yes      | series tag     | cooling_filter_slot_cover                                                                           | Cooling Filter Slot Cover?                                                                          | text      | text        |
| Yes      | series tag     | condition_of_hvac_cooling_furnace_air_filter                                                        | Condition of HVAC Cooling Furnace Air Filter                                                        | text      | text        |
| Yes      | series tag     | location_of_hvac_cooling_system                                                                     | Location of HVAC Cooling System                                                                     | text      | text        |
| Yes      | series tag     | when_was_hvac_cooling_system_last_serviced                                                          | When was HVAC Cooling System Last Serviced?                                                         | text      | text        |
| Yes      | series tag     | what_unit_does_the_hvac_heating_system_serve                                                        | What Unit Does the HVAC Heating System Serve?                                                       | text      | text        |
| Yes      | numeric metric | what_percentage_of_conditioned_space_does_the_hvac_heating_unit_serve                               | What Percentage of Conditioned Space Does the HVAC Heating Unit Serve?                              | number    | number      |
| Yes      | series tag     | is_heating_primary_or_secondary_source                                                              | Is Heating Primary or Secondary Source?                                                             | text      | text        |
| Yes      | series tag     | hvac_heating_system_type                                                                            | HVAC Heating System Type                                                                            | text      | text        |
| Yes      | series tag     | year_hvac_heating_unit_was_manufactured                                                             | Year HVAC Heating Unit was Manufactured                                                             | text      | text        |
| Yes      | series tag     | hvac_heating_manufacture_year_estimated_or_known                                                    | HVAC Heating Manufacture Year Estimated or Known                                                    | text      | text        |
| Yes      | series tag     | hvac_heating_manufacturer                                                                           | HVAC Heating Manufacturer                                                                           | text      | text        |
| Yes      | series tag     | hvac_heating_model                                                                                  | HVAC Heating Model                                                                                  | text      | text        |
| Yes      | series tag     | hvac_heating_capacity_btu_hr                                                                        | HVAC Heating Capacity (BTU/Hr.)                                                                     | text      | text        |
| Yes      | series tag     | hvac_system_fuel_type                                                                               | HVAC System Fuel Type                                                                               | text      | text        |
| Yes      | numeric metric | number_of_hvac_heating_systems                                                                      | Number of HVAC Heating Systems                                                                      | number    | number      |
| Yes      | series tag     | rated_efficiency_of_hvac_heating_system                                                             | Rated Efficiency of HVAC Heating System                                                             | text      | text        |
| Yes      | series tag     | hvac_heating_efficiency_type                                                                        | HVAC Heating Efficiency Type                                                                        | text      | text        |
| Yes      | series tag     | hvac_heating_efficiency_data_source                                                                 | HVAC Heating Efficiency Data Source                                                                 | text      | text        |
| Yes      | series tag     | is_hvac_heating_energy_star                                                                         | Is HVAC Heating Energy Star?                                                                        | text      | text        |
| Yes      | series tag     | observed_visual_condition_of_hvac_heating_system                                                    | Observed Visual Condition of HVAC Heating System                                                    | text      | text        |
| Yes      | series tag     | is_there_an_hvac_heating_filter_slot_cover                                                          | Is There An HVAC Heating Filter Slot Cover?                                                         | text      | text        |
| Yes      | series tag     | condition_of_hvac_heating_furnace_air_filter                                                        | Condition of HVAC Heating Furnace Air Filter                                                        | text      | text        |
| Yes      | series tag     | does_the_hvac_heating_furnace_have_an_electronically_commutated_motor                               | Does the HVAC Heating Furnace have an Electronically Commutated Motor?                              | text      | text        |
| Yes      | series tag     | location_of_hvac_heating                                                                            | Location of HVAC Heating                                                                            | text      | text        |
| Yes      | series tag     | does_the_hvac_heating_system_have_an_outdoor_reset                                                  | Does the HVAC Heating System Have an Outdoor Reset?                                                 | text      | text        |
| Yes      | series tag     | does_the_hvac_heating_system_have_thermostatic_radiator_valves                                      | Does the HVAC Heating System have Thermostatic Radiator valves?                                     | text      | text        |
| Yes      | series tag     | hvac_heating_venting_type                                                                           | HVAC Heating Venting Type                                                                           | text      | text        |
| Yes      | series tag     | when_was_hvac_heating_system_last_serviced                                                          | When was HVAC Heating System Last Serviced?                                                         | text      | text        |
| Yes      | series tag     | hvac_ventilation_type                                                                               | HVAC Ventilation Type                                                                               | text      | text        |
| Yes      | series tag     | hvac_ventilation_space_served                                                                       | HVAC Ventilation Space Served                                                                       | text      | text        |
| Yes      | series tag     | number_of_hvac_ventilation_operating_hours_per_day                                                  | Number of HVAC Ventilation Operating Hours Per Day                                                  | text      | text        |
| Yes      | series tag     | hvac_ventilation_system_configuration                                                               | HVAC Ventilation System Configuration                                                               | text      | text        |
| Yes      | numeric metric | number_of_lighting_controls                                                                         | Number of Lighting Controls                                                                         | number    | number      |
| Yes      | series tag     | type_of_lighting_controls                                                                           | Type of Lighting Controls                                                                           | text      | text        |
| Yes      | numeric metric | no_efficient_light_bulbs                                                                            | Number of Efficient Light Bulbs                                                                     | number    | number      |
| Yes      | numeric metric | no_halogen_light_bulbs                                                                              | Number of Halogen Light Bulbs                                                                       | number    | number      |
| Yes      | numeric metric | no_incandescent_light_bulbs                                                                         | Number of Incandescent Light Bulbs                                                                  | number    | number      |
| Yes      | numeric metric | no_other_light_bulbs                                                                                | Number of Other Light Bulbs                                                                         | number    | number      |
| Yes      | series tag     | type_of_other_light_bulbs                                                                           | Type of Other Light Bulbs                                                                           | text      | text        |
| Yes      | numeric metric | no_t12_light_bulbs                                                                                  | Number of T12 Light Bulbs                                                                           | number    | number      |
| Yes      | series tag     | location_of_lighting_unit                                                                           | Location of Lighting Unit                                                                           | text      | text        |
| Yes      | series tag     | no_other_plug_loads                                                                                 | Number of Other Plug Loads                                                                          | text      | text        |
| Yes      | series tag     | description_of_other_plug_loads                                                                     | Description of Other Plug Loads                                                                     | text      | text        |
| Yes      | numeric metric | no_cable_boxes_plugged_into_smart_strips_or_outlets                                                 | Number of Cable Boxes Plugged into Smart Strips or Outlets                                          | number    | number      |
| Yes      | numeric metric | no_dvd_players_plugged_into_smart_strips_or_outlets                                                 | Number of DVD Players Plugged into Smart Strips or Outlets                                          | number    | number      |
| Yes      | numeric metric | no_fax_machines_plugged_into_smart_strips_or_outlets                                                | Number of Fax Machines Plugged into Smart Strips or Outlets                                         | number    | number      |
| Yes      | numeric metric | no_gaming_consoles_plugged_into_smart_strips_or_outlets                                             | Number of Gaming Consoles Plugged into Smart Strips or Outlets                                      | number    | number      |
| Yes      | numeric metric | no_home_theater_systems_plugged_into_smart_strips_or_outlets                                        | Number of Home Theater Systems Plugged into Smart Strips or Outlets                                 | number    | number      |
| Yes      | numeric metric | no_printers_and_copiers_plugged_into_smart_strips_or_outlets                                        | Number of Printers and Copiers Plugged into Smart Strips or Outlets                                 | number    | number      |
| Yes      | numeric metric | no_space_heaters_plugged_into_smart_strips_or_outlets                                               | Number of Space Heaters Plugged into Smart Strips or Outlets                                        | number    | number      |
| Yes      | numeric metric | no_stereo_systems_plugged_into_smart_strips_or_outlets                                              | Number of Stereo Systems Plugged into Smart Strips or Outlets                                       | number    | number      |
| Yes      | numeric metric | no_vcr_s_plugged_into_smart_strips_or_outlets                                                       | Number of VCR's Plugged into Smart Strips or Outlets                                                | number    | number      |
| Yes      | numeric metric | no_tier_1_plug_loads_smart_strips_and_outlets                                                       | Number of Tier 1 Plug Loads, Smart Strips and Outlets                                               | number    | number      |
| Yes      | numeric metric | no_tier_2_plug_loads_smart_strips_and_outlets                                                       | Number of Tier 2 Plug Loads, Smart Strips and Outlets                                               | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = dishwasher_usage_pattern_cycles_week,clothes_washer_usage_pattern_loads_week
```

## Data Commands

```ls
```

## Meta Commands

```ls
metric m:no_of_water_heaters p:integer l:"Number of Water Heaters" d:"Number of water heaters in unit or common space [e.g., 0-100]" t:dataTypeName=number

metric m:percentage_of_total_exterior_and_interior_surfaces_that_are_insulated p:integer l:"Percentage of total exterior and interior surfaces that are insulated" d:"Percentage of total exterior and interior surfaces that are insulated [e.g.,0-100]" t:dataTypeName=number

metric m:what_percentage_of_conditioned_space_does_the_hvac_cooling_unit_serve p:integer l:"What Percentage of Conditioned Space Does the HVAC Cooling Unit Serve?" d:"Total percentage of conditioned space that HVAC cooling unit serves [e.g., 10-100]" t:dataTypeName=number

metric m:no_ac_units p:integer l:"Number of AC Units" d:"Number of AC units identified during on-site visit [e.g., 1-20]" t:dataTypeName=number

metric m:rated_efficiency_of_hvac_cooling_system p:double l:"Rated Efficiency of HVAC Cooling System" d:"Rated efficiency of HVAC cooling system based on on-site visit [e.g., 7-23]" t:dataTypeName=number

metric m:what_percentage_of_conditioned_space_does_the_hvac_heating_unit_serve p:integer l:"What Percentage of Conditioned Space Does the HVAC Heating Unit Serve?" d:"What Percentage of Conditioned Space Does the HVAC Heating Unit Serve? [e.g., 10-100]" t:dataTypeName=number

metric m:number_of_hvac_heating_systems p:integer l:"Number of HVAC Heating Systems" d:"Number of heating systems in the unit or building [e.g., 1-100]" t:dataTypeName=number

metric m:number_of_lighting_controls p:integer l:"Number of Lighting Controls" d:"Number of installed lighting controls [e.g., 1-332]" t:dataTypeName=number

metric m:no_efficient_light_bulbs p:integer l:"Number of Efficient Light Bulbs" d:"Number of efficient light bulbs [e.g., 0-1350]" t:dataTypeName=number

metric m:no_halogen_light_bulbs p:integer l:"Number of Halogen Light Bulbs" d:"Number of halogen light bulbs [e.g., 0-55]" t:dataTypeName=number

metric m:no_incandescent_light_bulbs p:integer l:"Number of Incandescent Light Bulbs" d:"Number of incandescent light bulbs [e.g., 0-291]" t:dataTypeName=number

metric m:no_other_light_bulbs p:integer l:"Number of Other Light Bulbs" d:"Number of other light bulbs [e.g., 0-136]" t:dataTypeName=number

metric m:no_t12_light_bulbs p:integer l:"Number of T12 Light Bulbs" d:"Number of T12 light bulbs [e.g., 0-588]" t:dataTypeName=number

metric m:no_cable_boxes_plugged_into_smart_strips_or_outlets p:integer l:"Number of Cable Boxes Plugged into Smart Strips or Outlets" d:"Number of cable boxes plugged into power outlets or smart strips during on-site visit [e.g., 0-20]" t:dataTypeName=number

metric m:no_dvd_players_plugged_into_smart_strips_or_outlets p:integer l:"Number of DVD Players Plugged into Smart Strips or Outlets" d:"Number of DVD Players plugged into power outlets or smart strips during on-site visit [e.g., 0-20]" t:dataTypeName=number

metric m:no_fax_machines_plugged_into_smart_strips_or_outlets p:integer l:"Number of Fax Machines Plugged into Smart Strips or Outlets" d:"Number of fax machines plugged into power outlets or smart strips during on-site visit [e.g., 0-20]" t:dataTypeName=number

metric m:no_gaming_consoles_plugged_into_smart_strips_or_outlets p:integer l:"Number of Gaming Consoles Plugged into Smart Strips or Outlets" d:"Number of gaming consoles plugged into power outlets or smart strips during on-site visit [e.g., 0-20]" t:dataTypeName=number

metric m:no_home_theater_systems_plugged_into_smart_strips_or_outlets p:integer l:"Number of Home Theater Systems Plugged into Smart Strips or Outlets" d:"Number of home theater systems plugged into power outlets or smart strips during on-site visit [e.g., 0-20]" t:dataTypeName=number

metric m:no_printers_and_copiers_plugged_into_smart_strips_or_outlets p:integer l:"Number of Printers and Copiers Plugged into Smart Strips or Outlets" d:"Number of printers and copiers plugged into power outlets or smart strips during on-site visit [e.g., 0-20]" t:dataTypeName=number

metric m:no_space_heaters_plugged_into_smart_strips_or_outlets p:integer l:"Number of Space Heaters Plugged into Smart Strips or Outlets" d:"Number of space heaters plugged into power outlets or smart strips during on-site visit [e.g., 0-20]" t:dataTypeName=number

metric m:no_stereo_systems_plugged_into_smart_strips_or_outlets p:integer l:"Number of Stereo Systems Plugged into Smart Strips or Outlets" d:"Number of stereo systems plugged into power outlets or smart strips during on-site visit [e.g., 0-20]" t:dataTypeName=number

metric m:no_vcr_s_plugged_into_smart_strips_or_outlets p:integer l:"Number of VCR's Plugged into Smart Strips or Outlets" d:"Number of VCR's plugged into power outlets or smart strips during on-site visit [e.g., 0-20]" t:dataTypeName=number

metric m:no_tier_1_plug_loads_smart_strips_and_outlets p:integer l:"Number of Tier 1 Plug Loads, Smart Strips and Outlets" d:"Number of Tier 1 plug loads, smart strips and outlets [e.g., 0-20]" t:dataTypeName=number

metric m:no_tier_2_plug_loads_smart_strips_and_outlets p:integer l:"Number of Tier 2 Plug Loads, Smart Strips and Outlets" d:"Number of Tier 2 plug loads, smart strips and outlets [e.g., 0-20]" t:dataTypeName=number

entity e:cif3-ww3e l:"RSBS MOM: Multifamily On-Site Survey, Measure Level, New York State Residential Statewide Baseline Study" t:attribution="New York State Energy Research and Development Authority" t:url=https://data.ny.gov/api/views/cif3-ww3e

property e:cif3-ww3e t:meta.view v:id=cif3-ww3e v:category="Energy & Environment" v:averageRating=0 v:name="RSBS MOM: Multifamily On-Site Survey, Measure Level, New York State Residential Statewide Baseline Study" v:attribution="New York State Energy Research and Development Authority"

property e:cif3-ww3e t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:cif3-ww3e t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```