# RSBS MOM: Multifamily On-Site Survey, Measure Level, New York State Residential Statewide Baseline Study

## Dataset

* [Dataset URL](https://data.ny.gov/api/views/cif3-ww3e/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/rsbs-mom-multifamily-on-site-survey-measure-level-new-york-state-residential-statewide-bas)
* [Metadata URL](https://data.ny.gov/api/views/cif3-ww3e)
* Id = cif3-ww3e
* Name = RSBS MOM: Multifamily On-Site Survey, Measure Level, New York State Residential Statewide Baseline Study
* Attribution = New York State Energy Research and Development Authority
* Category = Energy & Environment
* Tags = [rsbl study, rsbs, energy efficiency, multifamily homes, market characterization, baseline study]
* Created = 2015-11-03T19:26:35Z
* Publication Date = 2015-11-17T22:47:29Z
* Rows Updated = 2015-11-17T22:45:20Z

## Description

The New York State Energy Research and Development Authority (NYSERDA), in collaboration with the New York State Department of Public Service (DPS), conducted a statewide residential baseline study (study) from 2011 to 2014 of the single-family and multifamily residential housing segments, including new construction, and a broad range of energy uses and efficiency measures.  This dataset includes data collected from a total of 67 on-site inspections of multifamily buildings. Data collected during the inspections covers property characteristics, heating and cooling equipment, water heating equipment, appliances, lighting, clothes washing and drying, miscellaneous energy using equipment, and observable operating behavior.  The objective of the on-site inspections was to enhance the residential baseline study with detailed on-site information and, to the degree possible, verify self-reported data from the phone and web surveys. The on-site inspection data is segmented to cover both common space equipment and tenant-unit equipment.

## Columns

```ls
| Name                                                                                                | Field Name                                                                                          | Data Type | Render Type | Schema Type    | Included | 
| =================================================================================================== | =================================================================================================== | ========= | =========== | ============== | ======== | 
| updated_at                                                                                          | :updated_at                                                                                         | meta_data | meta_data   | time           | No       | 
| Equipment Category                                                                                  | equipment_category                                                                                  | text      | text        | series tag     | Yes      | 
| Measure ID                                                                                          | measure_id                                                                                          | text      | text        | series tag     | Yes      | 
| Area Served                                                                                         | area_served                                                                                         | text      | text        | series tag     | Yes      | 
| Unit ID                                                                                             | unit_id                                                                                             | text      | text        | series tag     | Yes      | 
| Common Space ID                                                                                     | common_space_id                                                                                     | text      | text        | series tag     | Yes      | 
| Site ID                                                                                             | site_id                                                                                             | text      | text        | series tag     | Yes      | 
| Multifamily Owner Manager (MOM) Survey ID                                                           | multifamily_owner_manager_mom_survey_id                                                             | text      | text        | series tag     | Yes      | 
| Climate Zone                                                                                        | climate_zone                                                                                        | text      | text        | series tag     | Yes      | 
| Region                                                                                              | region                                                                                              | text      | text        | series tag     | Yes      | 
| County                                                                                              | county                                                                                              | text      | text        | series tag     | Yes      | 
| Construction Type                                                                                   | construction_type                                                                                   | text      | text        | series tag     | Yes      | 
| Electric Provider                                                                                   | electric_provider                                                                                   | text      | text        | series tag     | Yes      | 
| Gas Provider                                                                                        | gas_provider                                                                                        | text      | text        | series tag     | Yes      | 
| Appliance Category                                                                                  | appliance_category                                                                                  | text      | text        | series tag     | Yes      | 
| Appliance Category ID                                                                               | appliance_category_id                                                                               | text      | text        | series tag     | Yes      | 
| Type/Style of Appliance                                                                             | type_style_of_appliance                                                                             | text      | text        | series tag     | Yes      | 
| Other Large Appliances                                                                              | other_large_appliances                                                                              | text      | text        | series tag     | Yes      | 
| Number of Appliance Units                                                                           | number_of_units                                                                                     | text      | text        | series tag     | Yes      | 
| Year of Appliance Manufacture                                                                       | year_of_appliance_manufacture                                                                       | text      | text        | series tag     | Yes      | 
| Appliance Manufacture Year Known or Estimated                                                       | appliance_manufacture_year_known_or_estimated                                                       | text      | text        | series tag     | Yes      | 
| Appliance Manufacturer                                                                              | appliance_manufacturer                                                                              | text      | text        | series tag     | Yes      | 
| Appliance Model Number                                                                              | model_number                                                                                        | text      | text        | series tag     | Yes      | 
| Wattage of Appliance                                                                                | wattage_of_appliance                                                                                | text      | text        | series tag     | Yes      | 
| Appliance Fuel                                                                                      | appliance_fuel                                                                                      | text      | text        | series tag     | Yes      | 
| Appliance Energy Star Certified?                                                                    | energy_star_certified                                                                               | text      | text        | series tag     | Yes      | 
| Computer Monitor Type                                                                               | computer_monitor_type                                                                               | text      | text        | series tag     | Yes      | 
| Dishwasher Efficiency (Energy Factor)                                                               | dishwasher_efficiency_energy_factor                                                                 | text      | text        | series tag     | Yes      | 
| Dishwasher Usage Pattern (cycles/week)                                                              | dishwasher_usage_pattern_cycles_week                                                                | text      | text        | series tag     | Yes      | 
| Fan Usage                                                                                           | fan_usage                                                                                           | text      | text        | series tag     | Yes      | 
| Humidifier/Dehumidifier Usage                                                                       | humidifier_dehumidifier_usage                                                                       | text      | text        | series tag     | Yes      | 
| Clothes Washing Machine Temperature                                                                 | clothes_washing_machine_temperature                                                                 | text      | text        | series tag     | Yes      | 
| Clothes Washer Usage Pattern (loads/week)                                                           | clothes_washer_usage_pattern_loads_week                                                             | text      | text        | series tag     | Yes      | 
| Heated Pool/Hot Tub                                                                                 | heated_pool_hot_tub                                                                                 | text      | text        | series tag     | Yes      | 
| Location of Refrigerator                                                                            | location_of_refrigerator                                                                            | text      | text        | series tag     | Yes      | 
| Size of Refrigerator/Freezer (cubic ft.)                                                            | size_of_refrigerator_freezer_cubic_ft                                                               | text      | text        | series tag     | Yes      | 
| Refrigerator with an In-door Water Dispenser                                                        | refrigerator_with_an_indoor_water_dispenser                                                         | text      | text        | series tag     | Yes      | 
| Television Screen Size (inches)                                                                     | television_screen_size_inches                                                                       | text      | text        | series tag     | Yes      | 
| Air Duct Insulation Type in Unconditioned Space                                                     | air_duct_insulation_type_in_unconditioned_space                                                     | text      | text        | series tag     | Yes      | 
| Air Duct Type in Unconditioned Space                                                                | air_duct_type_in_unconditioned_space                                                                | text      | text        | series tag     | Yes      | 
| Visual Inspection of Air Duct Seal                                                                  | visual_inspection_of_air_duct_seal                                                                  | text      | text        | series tag     | Yes      | 
| Air Duct Distribution in Unconditioned (%)                                                          | air_duct_distribution_in_unconditioned                                                              | text      | text        | series tag     | Yes      | 
| Air Duct Distribution that is Insulated in Unconditioned Space (%)                                  | air_duct_distribution_that_is_insulated_in_unconditioned_space                                      | text      | text        | series tag     | Yes      | 
| Thickness of Insulation Around the Return Air Duct (inches)                                         | thickness_of_insulation_around_the_return_air_duct_inches                                           | text      | text        | series tag     | Yes      | 
| Air Duct Supply Insulation Thickness (inches)                                                       | air_duct_supply_insulation_thickness_inches                                                         | text      | text        | series tag     | Yes      | 
| Number of Disconnected Air Ducts                                                                    | no_of_disconnected_air_ducts                                                                        | text      | text        | series tag     | Yes      | 
| Type of Air Duct System                                                                             | type_of_air_duct_system                                                                             | text      | text        | series tag     | Yes      | 
| Type of Building Served by DHW                                                                      | type_of_building_served_by_dhw                                                                      | text      | text        | series tag     | Yes      | 
| DHW Type                                                                                            | dhw_type                                                                                            | text      | text        | series tag     | Yes      | 
| DHW Fuel Type                                                                                       | dhw_fuel_type                                                                                       | text      | text        | series tag     | Yes      | 
| Number of Water Heaters                                                                             | no_of_water_heaters                                                                                 | number    | number      | numeric metric | Yes      | 
| DHW Manufacture Year                                                                                | dhw_manufacture_year                                                                                | text      | text        | series tag     | Yes      | 
| DHW Manufacture Year Known or Estimated                                                             | dhw_manufacture_year_known_or_estimated                                                             | text      | text        | series tag     | Yes      | 
| DHW Unit Manufacturer                                                                               | unit_manufacturer                                                                                   | text      | text        | series tag     | Yes      | 
| DHW Unit Model                                                                                      | unit_model                                                                                          | text      | text        | series tag     | Yes      | 
| DHW Unit Energy Factor                                                                              | unit_energy_factor                                                                                  | text      | text        | series tag     | Yes      | 
| DHW Efficiency Data Source                                                                          | efficiency_data_source                                                                              | text      | text        | series tag     | Yes      | 
| Water Temperature Setting (DHW)                                                                     | water_temperature_setting_dhw                                                                       | text      | text        | series tag     | Yes      | 
| DHW Venting                                                                                         | dhw_venting                                                                                         | text      | text        | series tag     | Yes      | 
| DHW Unit Heat Recovery                                                                              | dhw_unit_heat_recovery                                                                              | text      | text        | series tag     | Yes      | 
| Efficiency rating of DHW heat recovery                                                              | efficiency_rating_of_dhw_heat_recovery                                                              | text      | text        | series tag     | Yes      | 
| Presence of Orphan Natural Draft DHW                                                                | presence_of_orphan_natural_draft_dhw                                                                | text      | text        | series tag     | Yes      | 
| Storage Volume of the DHW Unit (gallons)                                                            | storage_volume_of_the_unit_gallons                                                                  | text      | text        | series tag     | Yes      | 
| Thickness of DHW pipe insulation (inches)                                                           | thickness_of_dhw_pipe_insulation_inches                                                             | text      | text        | series tag     | Yes      | 
| DHW Insulation Thickness (inches)                                                                   | dhw_insulation_thickness_inches                                                                     | text      | text        | series tag     | Yes      | 
| DHW Unit in Conditioned or Unconditioned Part of House?                                             | unit_in_conditioned_or_unconditioned_part_of_house                                                  | text      | text        | series tag     | Yes      | 
| Surface Type                                                                                        | surface_type                                                                                        | text      | text        | series tag     | Yes      | 
| Construction Material of Envelope                                                                   | construction_material_of_envelope                                                                   | text      | text        | series tag     | Yes      | 
| Construction Material of Envelope (Categorical)                                                     | construction_material_of_envelope_categorical                                                       | text      | text        | series tag     | Yes      | 
| Depth Below Grade (feet)                                                                            | depth_below_grade_feet                                                                              | text      | text        | series tag     | Yes      | 
| Ceiling Type                                                                                        | ceiling_type                                                                                        | text      | text        | series tag     | Yes      | 
| Attic Access Insulation Level                                                                       | attic_access_insulation_level                                                                       | text      | text        | series tag     | Yes      | 
| Attic Access Square Feet                                                                            | attic_access_square_feet                                                                            | text      | text        | series tag     | Yes      | 
| Attic Access Weather Stripping                                                                      | attic_access_weather_stripping                                                                      | text      | text        | series tag     | Yes      | 
| Percentage of total exterior and interior surfaces that are insulated                               | percentage_of_total_exterior_and_interior_surfaces_that_are_insulated                               | number    | number      | numeric metric | Yes      | 
| Exterior or continuous insulation type                                                              | exterior_or_continuous_insulation_type                                                              | text      | text        | series tag     | Yes      | 
| Data source for the on-site inspector determining exterior or continuous insulation characteristics | data_source_for_the_on_site_inspector_determining_exterior_or_continuous_insulation_characteristics | text      | text        | series tag     | Yes      | 
| Exterior or continuous insulation quality (grade I-III)                                             | exterior_or_continuous_insulation_quality_grade_i_iii                                               | text      | text        | series tag     | Yes      | 
| Exterior or continuous insulation thickness (inches)                                                | exterior_or_continuous_insulation_thickness_inches                                                  | text      | text        | series tag     | Yes      | 
| Interior or cavity insulation type                                                                  | interior_or_cavity_insulation_type                                                                  | text      | text        | series tag     | Yes      | 
| Data source for the on-site inspector determining interior or cavity insulation characteristics     | data_source_for_the_on_site_inspector_determining_interior_or_cavity_insulation_characteristics     | text      | text        | series tag     | Yes      | 
| Interior or cavity insulation quality (grade I-III)                                                 | interior_or_cavity_insulation_quality_grade_i_iii                                                   | text      | text        | series tag     | Yes      | 
| Interior or cavity insulation thickness (inches)                                                    | interior_or_cavity_insulation_thickness_inches                                                      | text      | text        | series tag     | Yes      | 
| Does the home have perimeter insulation                                                             | does_the_home_have_perimeter_insulation                                                             | text      | text        | series tag     | Yes      | 
| Window Or Door                                                                                      | window_or_door                                                                                      | text      | text        | series tag     | Yes      | 
| Number of Doors                                                                                     | number_of_doors                                                                                     | text      | text        | series tag     | Yes      | 
| Door Material                                                                                       | door_material                                                                                       | text      | text        | series tag     | Yes      | 
| Door Weather Stripping                                                                              | door_weather_stripping                                                                              | text      | text        | series tag     | Yes      | 
| Number of Windows                                                                                   | number_of_windows                                                                                   | text      | text        | series tag     | Yes      | 
| Window Size (sqft)                                                                                  | window_size_sqft                                                                                    | text      | text        | series tag     | Yes      | 
| Overall Window Condition                                                                            | overall_window_condition                                                                            | text      | text        | series tag     | Yes      | 
| U Factor of Window Insulation                                                                       | u_factor_of_window_insulation                                                                       | text      | text        | series tag     | Yes      | 
| Window Frame Type                                                                                   | window_frame_type                                                                                   | text      | text        | series tag     | Yes      | 
| Window Glazing                                                                                      | window_glazing                                                                                      | text      | text        | series tag     | Yes      | 
| Gas Filled Window                                                                                   | gas_filled_window                                                                                   | text      | text        | series tag     | Yes      | 
| Presence of Bay Windows                                                                             | presence_of_bay_windows                                                                             | text      | text        | series tag     | Yes      | 
| Storm Windows                                                                                       | storm_windows                                                                                       | text      | text        | series tag     | Yes      | 
| Window Treatments                                                                                   | window_treatments                                                                                   | text      | text        | series tag     | Yes      | 
| HVAC Controls Thermostat Type                                                                       | hvac_controls_thermostat_type                                                                       | text      | text        | series tag     | Yes      | 
| HVAC Systems Served                                                                                 | hvac_systems_served                                                                                 | text      | text        | series tag     | Yes      | 
| Cooling Setback Hours                                                                               | cooling_setback_hours                                                                               | text      | text        | series tag     | Yes      | 
| Cooling Setback Temperature                                                                         | cooling_setback_temperature                                                                         | text      | text        | series tag     | Yes      | 
| Heating Setback Hours                                                                               | heating_setback_hours                                                                               | text      | text        | series tag     | Yes      | 
| Heating Setback Temperature                                                                         | heating_setback_temperature                                                                         | text      | text        | series tag     | Yes      | 
| Set Point Temperature in Cooling Season                                                             | set_point_temperature_in_cooling_season                                                             | text      | text        | series tag     | Yes      | 
| Set Point Temperature in Heating Season                                                             | set_point_temperature_in_heating_season                                                             | text      | text        | series tag     | Yes      | 
| Status of Thermostat at Time of Inspection                                                          | status_of_thermostat_at_time_of_inspection                                                          | text      | text        | series tag     | Yes      | 
| Programmable Thermostats                                                                            | programmable_thermostats                                                                            | text      | text        | series tag     | Yes      | 
| What Unit Does the HVAC Cooling System Serve?                                                       | what_unit_does_the_hvac_cooling_system_serve                                                        | text      | text        | series tag     | Yes      | 
| What Percentage of Conditioned Space Does the HVAC Cooling Unit Serve?                              | what_percentage_of_conditioned_space_does_the_hvac_cooling_unit_serve                               | number    | number      | numeric metric | Yes      | 
| Is HVAC Cooling Primary or Secondary Source?                                                        | is_hvac_cooling_primary_or_secondary_source                                                         | text      | text        | series tag     | Yes      | 
| HVAC Cooling System Type                                                                            | hvac_cooling_system_type                                                                            | text      | text        | series tag     | Yes      | 
| Year HVAC Cooling Unit was Manufactured                                                             | year_hvac_cooling_unit_was_manufactured                                                             | text      | text        | series tag     | Yes      | 
| HVAC Cooling Manufacture Year Known or Estimated                                                    | hvac_cooling_manufacture_year_known_or_estimated                                                    | text      | text        | series tag     | Yes      | 
| HVAC Cooling Manufacturer                                                                           | hvac_cooling_manufacturer                                                                           | text      | text        | series tag     | Yes      | 
| HVAC Cooling System Model                                                                           | hvac_cooling_model                                                                                  | text      | text        | series tag     | Yes      | 
| HVAC Cooling Capacity (BTU/Hr.)                                                                     | hvac_cooling_capacity_btu_hr                                                                        | text      | text        | series tag     | Yes      | 
| Number of AC Units                                                                                  | no_ac_units                                                                                         | number    | number      | numeric metric | Yes      | 
| Rated Efficiency of HVAC Cooling System                                                             | rated_efficiency_of_hvac_cooling_system                                                             | number    | number      | numeric metric | Yes      | 
| HVAC Cooling Efficiency Type                                                                        | hvac_cooling_efficiency_type                                                                        | text      | text        | series tag     | Yes      | 
| HVAC Cooling Efficiency Data Source                                                                 | hvac_cooling_efficiency_data_source                                                                 | text      | text        | series tag     | Yes      | 
| Is HVAC Cooling Energy Star?                                                                        | is_hvac_cooling_energy_star                                                                         | text      | text        | series tag     | Yes      | 
| Observed Visual Condition of HVAC Cooling System                                                    | observed_visual_condition_of_hvac_cooling_system                                                    | text      | text        | series tag     | Yes      | 
| Cooling Filter Slot Cover?                                                                          | cooling_filter_slot_cover                                                                           | text      | text        | series tag     | Yes      | 
| Condition of HVAC Cooling Furnace Air Filter                                                        | condition_of_hvac_cooling_furnace_air_filter                                                        | text      | text        | series tag     | Yes      | 
| Location of HVAC Cooling System                                                                     | location_of_hvac_cooling_system                                                                     | text      | text        | series tag     | Yes      | 
| When was HVAC Cooling System Last Serviced?                                                         | when_was_hvac_cooling_system_last_serviced                                                          | text      | text        | series tag     | Yes      | 
| What Unit Does the HVAC Heating System Serve?                                                       | what_unit_does_the_hvac_heating_system_serve                                                        | text      | text        | series tag     | Yes      | 
| What Percentage of Conditioned Space Does the HVAC Heating Unit Serve?                              | what_percentage_of_conditioned_space_does_the_hvac_heating_unit_serve                               | number    | number      | numeric metric | Yes      | 
| Is Heating Primary or Secondary Source?                                                             | is_heating_primary_or_secondary_source                                                              | text      | text        | series tag     | Yes      | 
| HVAC Heating System Type                                                                            | hvac_heating_system_type                                                                            | text      | text        | series tag     | Yes      | 
| Year HVAC Heating Unit was Manufactured                                                             | year_hvac_heating_unit_was_manufactured                                                             | text      | text        | series tag     | Yes      | 
| HVAC Heating Manufacture Year Estimated or Known                                                    | hvac_heating_manufacture_year_estimated_or_known                                                    | text      | text        | series tag     | Yes      | 
| HVAC Heating Manufacturer                                                                           | hvac_heating_manufacturer                                                                           | text      | text        | series tag     | Yes      | 
| HVAC Heating Model                                                                                  | hvac_heating_model                                                                                  | text      | text        | series tag     | Yes      | 
| HVAC Heating Capacity (BTU/Hr.)                                                                     | hvac_heating_capacity_btu_hr                                                                        | text      | text        | series tag     | Yes      | 
| HVAC System Fuel Type                                                                               | hvac_system_fuel_type                                                                               | text      | text        | series tag     | Yes      | 
| Number of HVAC Heating Systems                                                                      | number_of_hvac_heating_systems                                                                      | number    | number      | numeric metric | Yes      | 
| Rated Efficiency of HVAC Heating System                                                             | rated_efficiency_of_hvac_heating_system                                                             | text      | text        | series tag     | Yes      | 
| HVAC Heating Efficiency Type                                                                        | hvac_heating_efficiency_type                                                                        | text      | text        | series tag     | Yes      | 
| HVAC Heating Efficiency Data Source                                                                 | hvac_heating_efficiency_data_source                                                                 | text      | text        | series tag     | Yes      | 
| Is HVAC Heating Energy Star?                                                                        | is_hvac_heating_energy_star                                                                         | text      | text        | series tag     | Yes      | 
| Observed Visual Condition of HVAC Heating System                                                    | observed_visual_condition_of_hvac_heating_system                                                    | text      | text        | series tag     | Yes      | 
| Is There An HVAC Heating Filter Slot Cover?                                                         | is_there_an_hvac_heating_filter_slot_cover                                                          | text      | text        | series tag     | Yes      | 
| Condition of HVAC Heating Furnace Air Filter                                                        | condition_of_hvac_heating_furnace_air_filter                                                        | text      | text        | series tag     | Yes      | 
| Does the HVAC Heating Furnace have an Electronically Commutated Motor?                              | does_the_hvac_heating_furnace_have_an_electronically_commutated_motor                               | text      | text        | series tag     | Yes      | 
| Location of HVAC Heating                                                                            | location_of_hvac_heating                                                                            | text      | text        | series tag     | Yes      | 
| Does the HVAC Heating System Have an Outdoor Reset?                                                 | does_the_hvac_heating_system_have_an_outdoor_reset                                                  | text      | text        | series tag     | Yes      | 
| Does the HVAC Heating System have Thermostatic Radiator valves?                                     | does_the_hvac_heating_system_have_thermostatic_radiator_valves                                      | text      | text        | series tag     | Yes      | 
| HVAC Heating Venting Type                                                                           | hvac_heating_venting_type                                                                           | text      | text        | series tag     | Yes      | 
| When was HVAC Heating System Last Serviced?                                                         | when_was_hvac_heating_system_last_serviced                                                          | text      | text        | series tag     | Yes      | 
| HVAC Ventilation Type                                                                               | hvac_ventilation_type                                                                               | text      | text        | series tag     | Yes      | 
| HVAC Ventilation Space Served                                                                       | hvac_ventilation_space_served                                                                       | text      | text        | series tag     | Yes      | 
| Number of HVAC Ventilation Operating Hours Per Day                                                  | number_of_hvac_ventilation_operating_hours_per_day                                                  | text      | text        | series tag     | Yes      | 
| HVAC Ventilation System Configuration                                                               | hvac_ventilation_system_configuration                                                               | text      | text        | series tag     | Yes      | 
| Number of Lighting Controls                                                                         | number_of_lighting_controls                                                                         | number    | number      | numeric metric | Yes      | 
| Type of Lighting Controls                                                                           | type_of_lighting_controls                                                                           | text      | text        | series tag     | Yes      | 
| Number of Efficient Light Bulbs                                                                     | no_efficient_light_bulbs                                                                            | number    | number      | numeric metric | Yes      | 
| Number of Halogen Light Bulbs                                                                       | no_halogen_light_bulbs                                                                              | number    | number      | numeric metric | Yes      | 
| Number of Incandescent Light Bulbs                                                                  | no_incandescent_light_bulbs                                                                         | number    | number      | numeric metric | Yes      | 
| Number of Other Light Bulbs                                                                         | no_other_light_bulbs                                                                                | number    | number      | numeric metric | Yes      | 
| Type of Other Light Bulbs                                                                           | type_of_other_light_bulbs                                                                           | text      | text        | series tag     | Yes      | 
| Number of T12 Light Bulbs                                                                           | no_t12_light_bulbs                                                                                  | number    | number      | numeric metric | Yes      | 
| Location of Lighting Unit                                                                           | location_of_lighting_unit                                                                           | text      | text        | series tag     | Yes      | 
| Number of Other Plug Loads                                                                          | no_other_plug_loads                                                                                 | text      | text        | series tag     | Yes      | 
| Description of Other Plug Loads                                                                     | description_of_other_plug_loads                                                                     | text      | text        | series tag     | Yes      | 
| Number of Cable Boxes Plugged into Smart Strips or Outlets                                          | no_cable_boxes_plugged_into_smart_strips_or_outlets                                                 | number    | number      | numeric metric | Yes      | 
| Number of DVD Players Plugged into Smart Strips or Outlets                                          | no_dvd_players_plugged_into_smart_strips_or_outlets                                                 | number    | number      | numeric metric | Yes      | 
| Number of Fax Machines Plugged into Smart Strips or Outlets                                         | no_fax_machines_plugged_into_smart_strips_or_outlets                                                | number    | number      | numeric metric | Yes      | 
| Number of Gaming Consoles Plugged into Smart Strips or Outlets                                      | no_gaming_consoles_plugged_into_smart_strips_or_outlets                                             | number    | number      | numeric metric | Yes      | 
| Number of Home Theater Systems Plugged into Smart Strips or Outlets                                 | no_home_theater_systems_plugged_into_smart_strips_or_outlets                                        | number    | number      | numeric metric | Yes      | 
| Number of Printers and Copiers Plugged into Smart Strips or Outlets                                 | no_printers_and_copiers_plugged_into_smart_strips_or_outlets                                        | number    | number      | numeric metric | Yes      | 
| Number of Space Heaters Plugged into Smart Strips or Outlets                                        | no_space_heaters_plugged_into_smart_strips_or_outlets                                               | number    | number      | numeric metric | Yes      | 
| Number of Stereo Systems Plugged into Smart Strips or Outlets                                       | no_stereo_systems_plugged_into_smart_strips_or_outlets                                              | number    | number      | numeric metric | Yes      | 
| Number of VCR's Plugged into Smart Strips or Outlets                                                | no_vcr_s_plugged_into_smart_strips_or_outlets                                                       | number    | number      | numeric metric | Yes      | 
| Number of Tier 1 Plug Loads, Smart Strips and Outlets                                               | no_tier_1_plug_loads_smart_strips_and_outlets                                                       | number    | number      | numeric metric | Yes      | 
| Number of Tier 2 Plug Loads, Smart Strips and Outlets                                               | no_tier_2_plug_loads_smart_strips_and_outlets                                                       | number    | number      | numeric metric | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
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

metric m:rated_efficiency_of_hvac_cooling_system p:integer l:"Rated Efficiency of HVAC Cooling System" d:"Rated efficiency of HVAC cooling system based on on-site visit [e.g., 7-23]" t:dataTypeName=number

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

property e:cif3-ww3e t:meta.view d:2017-03-07T18:30:30.547Z v:id=cif3-ww3e v:category="Energy & Environment" v:averageRating=0 v:name="RSBS MOM: Multifamily On-Site Survey, Measure Level, New York State Residential Statewide Baseline Study" v:attribution="New York State Energy Research and Development Authority"

property e:cif3-ww3e t:meta.view.owner d:2017-03-07T18:30:30.547Z v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:cif3-ww3e t:meta.view.tableauthor d:2017-03-07T18:30:30.547Z v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```