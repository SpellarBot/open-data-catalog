# ENERGY STAR Certified Water Heaters

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/energy-star-certified-water-heaters) |
| Metadata | [Link](https://data.energystar.gov/api/views/3gp2-af4x) |
| Data: JSON | [100 Rows](https://data.energystar.gov/api/views/3gp2-af4x/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.energystar.gov/api/views/3gp2-af4x/rows.csv?max_rows=100) |
| Host | data.energystar.gov |
| Id | 3gp2-af4x |
| Name | ENERGY STAR Certified Water Heaters |
| Category | Active Specifications |
| Tags | water heaters |
| Created | 2013-01-08T20:59:22Z |
| Publication Date | 2016-08-19T15:15:58Z |

## Description

Certified models meet all ENERGY STAR requirements as listed in the Version 3.0 ENERGY STAR Program Requirements for Water Heaters that are effective April 16, 2015. A detailed listing of key efficiency criteria are available at http://www.energystar.gov/index.cfm?c=water_heat.pr_crit_water_heaters

## Columns

```ls
| Included | Schema Type    | Field Name                                       | Name                                  | Data Type     | Render Type   |
| ======== | ============== | ================================================ | ===================================== | ============= | ============= |
| Yes      | series tag     | pd_id                                            | ENERGY STAR Unique ID                 | text          | number        |
| Yes      | series tag     | energy_star_partner                              | ENERGY STAR Partner                   | text          | text          |
| Yes      | series tag     | brand_name                                       | Brand Name                            | text          | text          |
| Yes      | series tag     | model_name                                       | Model Name                            | text          | text          |
| Yes      | series tag     | model_number                                     | Model Number                          | text          | text          |
| Yes      | series tag     | additional_model_information                     | Additional Model Information          | text          | text          |
| Yes      | series tag     | type                                             | Type                                  | text          | text          |
| Yes      | series tag     | fuel                                             | Fuel                                  | text          | text          |
| Yes      | series tag     | vent_type                                        | Vent Type                             | text          | text          |
| Yes      | numeric metric | storage_volume_gallons                           | Storage Volume (gallons)              | number        | number        |
| Yes      | numeric metric | tank_height_inches                               | Tank Height (in.)                     | number        | number        |
| Yes      | numeric metric | height_to_vent_inches                            | Height to Vent (in.)                  | number        | number        |
| Yes      | numeric metric | tank_diameter_inches                             | Tank Diameter (in.)                   | number        | number        |
| Yes      | numeric metric | vent_size_inches                                 | Vent Size (in.)                       | number        | number        |
| Yes      | numeric metric | vent_size_2_inches                               | Vent Size 2 (in.)                     | number        | number        |
| Yes      | numeric metric | input_kw                                         | Input (kW)                            | number        | number        |
| Yes      | numeric metric | volts                                            | Volts                                 | number        | number        |
| Yes      | numeric metric | kwh_year                                         | kWh/yr                                | number        | number        |
| Yes      | numeric metric | input_rate_thousand_btu_per_hour                 | Input Rate (kBtu/hr)                  | number        | number        |
| Yes      | numeric metric | thermal_efficiency_te                            | Thermal Efficiency (TE)               | number        | text          |
| Yes      | numeric metric | standby_loss                                     | Standby Loss                          | number        | text          |
| Yes      | numeric metric | energy_factor                                    | Energy Factor                         | number        | number        |
| Yes      | numeric metric | therms_year_for_natural_gas                      | Therms/year for Natural Gas           | number        | number        |
| Yes      | numeric metric | gallons_year_for_propane                         | Gallons/year for Propane              | number        | number        |
| Yes      | numeric metric | first_hour_rating_gallons_per_hour               | First Hour Rating (gallons/hr)        | number        | number        |
| Yes      | numeric metric | maximum_gallons_per_minute                       | Maximum Gallons per Minute            | number        | number        |
| Yes      | numeric metric | minimum_gallons_per_minute                       | Minimum Gallons Per Minute            | number        | number        |
| Yes      | numeric metric | recovery_efficiency                              | Recovery Efficiency (%)               | percent       | percent       |
| Yes      | series tag     | solar_system_type                                | Solar System Type                     | text          | text          |
| Yes      | series tag     | solar_collector_type                             | Solar Collector Type                  | text          | text          |
| Yes      | numeric metric | solar_collector_panel_area_sq_feet               | Solar Collector Panel Area (sq. ft.)  | number        | number        |
| Yes      | numeric metric | solar_energy_factor_sef                          | Solar Energy Factor (SEF)             | number        | number        |
| Yes      | numeric metric | freeze_tolerance_limit_f                         | Freeze Tolerance Limit (F)            | number        | number        |
| Yes      | numeric metric | solar_tank_volume_gallons                        | Solar Tank Volume (gallons)           | number        | number        |
| Yes      | series tag     | solar_type_of_backup                             | Solar Type of Backup                  | text          | text          |
| Yes      | numeric metric | solar_auxiliary_tank_volume_gallons              | Solar Auxiliary Tank Volume (gallons) | number        | number        |
| Yes      | numeric metric | solar_auxiliary_tank_input_kw                    | Solar Auxiliary Tank Input (kW)       | number        | number        |
| Yes      | numeric metric | solar_auxiliary_tank_input_thousand_btu_per_hour | Solar Auxiliary Tank Input (kBtu/hr)  | number        | number        |
| Yes      | numeric metric | water_heater_depth_inches                        | Water Heater Depth (in.)              | number        | number        |
| Yes      | numeric metric | water_heater_height_inches                       | Water Heater Height (in.)             | number        | number        |
| Yes      | numeric metric | water_heater_width_inches                        | Water Heater Width (in.)              | number        | number        |
| Yes      | time           | date_available_on_market                         | Date Available On Market              | calendar_date | calendar_date |
| No       |                | date_qualified                                   | Date Qualified                        | calendar_date | calendar_date |
| Yes      | series tag     | markets                                          | Markets                               | text          | text          |
| Yes      | series tag     | energy_star_model_identifier                     | CB Model Identifier                   | text          | text          |
```

## Time Field

```ls
Value = date_available_on_market
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_qualified
```

## Data Commands

```ls
series e:3gp2-af4x d:2014-11-01T00:00:00.000Z t:energy_star_partner="A.O. Smith Corporation" t:model_number="HPE6280H045DV 102" t:markets="United States" t:energy_star_model_identifier=ES_92897_04142015123625_1451663 t:fuel=Electric t:type="Heat Pump" t:model_name="Heat Pump Water Heater" t:brand_name=American t:pd_id=2236853 m:volts=240 m:tank_diameter_inches=25.2 m:first_hour_rating_gallons_per_hour=84 m:recovery_efficiency=100 m:input_kw=2 m:storage_volume_gallons=80 m:kwh_year=1515 m:tank_height_inches=80.8 m:energy_factor=2.33

series e:3gp2-af4x d:2015-05-22T00:00:00.000Z t:energy_star_partner="A.O. Smith Corporation" t:model_number="HPHE10250H045DV 120" t:markets="United States" t:energy_star_model_identifier=ES_92897_05282015114102_1410611 t:fuel=Electric t:type="Heat Pump" t:model_name="Heat Pump Water Heater" t:brand_name=American t:pd_id=2240321 m:volts=240 m:water_heater_height_inches=62.5 m:tank_diameter_inches=22.5 m:first_hour_rating_gallons_per_hour=70 m:recovery_efficiency=100 m:storage_volume_gallons=50 m:kwh_year=1516 m:tank_height_inches=62.5 m:energy_factor=3.24

series e:3gp2-af4x d:2016-05-27T00:00:00.000Z t:energy_star_partner="A.O. Smith Corporation" t:model_number="HPHE10250H045DVN 120" t:markets="United States" t:energy_star_model_identifier=ES_92897_06242016161450_9704196 t:fuel=Electric t:type="Heat Pump" t:model_name="Heat Pump Water Heater" t:brand_name=American t:pd_id=2270603 m:volts=240 m:water_heater_height_inches=62.5 m:tank_diameter_inches=15 m:first_hour_rating_gallons_per_hour=70 m:recovery_efficiency=100 m:input_kw=4.5 m:storage_volume_gallons=50 m:kwh_year=1516 m:tank_height_inches=46 m:energy_factor=3.24
```

## Meta Commands

```ls
metric m:storage_volume_gallons p:double l:"Storage Volume (gallons)" d:"Volume is the capacity of the tank, in gallons. Storage Volume is not applicable for gas tankless, solar with gas backup, or solar with electric backup water heaters." t:dataTypeName=number

metric m:tank_height_inches p:float l:"Tank Height (in.)" d:"Tank height is the distance from the bottom of the water heater?s tank to the top of its tank." t:dataTypeName=number

metric m:height_to_vent_inches p:float l:"Height to Vent (in.)" d:"Height to vent is the distance from the bottom of the water heater?s tank to its vent." t:dataTypeName=number

metric m:tank_diameter_inches p:float l:"Tank Diameter (in.)" d:"Tank diameter is the width or diameter of the water heater?s tank." t:dataTypeName=number

metric m:vent_size_inches p:float l:"Vent Size (in.)" d:"Vent size is the width or diameter of the vent opening." t:dataTypeName=number

metric m:vent_size_2_inches p:float l:"Vent Size 2 (in.)" d:"Vent size 2 is the width or diameter of a second vent opening." t:dataTypeName=number

metric m:input_kw p:double l:"Input (kW)" d:"Electric Input kW refers to the input wattage of the heat pump or supplementary electric elements." t:dataTypeName=number

metric m:volts p:integer l:Volts d:"Volts refer to the potential of an outlet or circuit to provide electrical energy. The standard current in the typical U.S. home is in the range of 110 to 120 volts. However, circuits used for equipment, such as heat pump water heaters, may use voltage in the range of 220 to 240 volts. These heavy-duty circuits can be identified by their non-standard outlet plugs." t:dataTypeName=number

metric m:kwh_year p:integer l:kWh/yr d:"kWh/year, kilowatt hours per year, refers to the amount of electricity consumed by the water heater according to its Energy Factor determined by the DOE test procedure, Code of Federal Regulations, Title 10, Section 430." t:dataTypeName=number

metric m:input_rate_thousand_btu_per_hour p:integer l:"Input Rate (kBtu/hr)" d:"Input refers to the burner size of the water heater, in thousand BTU per hour." t:dataTypeName=number

metric m:thermal_efficiency_te p:integer l:"Thermal Efficiency (TE)" d:"The ratio of the heat transferred to the water flowing through the water heater to the amount of energy consumed by the water heater." t:dataTypeName=number

metric m:standby_loss p:integer l:"Standby Loss" d:"The ratio of useful energy output from the water heater to the total amount of energy delivered to the water heater." t:dataTypeName=number

metric m:energy_factor p:float l:"Energy Factor" d:"Energy Factor is the ratio of useful energy output from the water heater to the total amount of energy delivered to the water heater. EF is a metric used to compare relative efficiencies of water heaters. The higher the EF is, the more efficient the water heater. EF is determined by the DOE test procedure, Code of Federal Regulations, Title 10, Section 430." t:dataTypeName=number

metric m:therms_year_for_natural_gas p:integer l:"Therms/year for Natural Gas" d:"Therms/year refers to the amount of natural gas consumed by the water heater according to its Energy Factor determined by the DOE test procedure, Code of Federal Regulations, Title 10, Section 430." t:dataTypeName=number

metric m:gallons_year_for_propane p:long l:"Gallons/year for Propane" d:"Gallons/year refers to the amount of propane consumed by the water heater according to its Energy Factor determined by the DOE test procedure, Code of Federal Regulations, Title 10, Section 430." t:dataTypeName=number

metric m:first_hour_rating_gallons_per_hour p:integer l:"First Hour Rating (gallons/hr)" d:"First-Hour Rating is the amount of hot water (in gallons) a storage water heater can supply per hour (starting with a tank full of hot water)." t:dataTypeName=number

metric m:maximum_gallons_per_minute p:float l:"Maximum Gallons per Minute" d:"The amount of hot water in gallons a tankless water heater can supply per minute over a 77?F rise." t:dataTypeName=number

metric m:minimum_gallons_per_minute p:float l:"Minimum Gallons Per Minute" d:"The amount of hot water in gallons a tankless water heater can supply per minute over a 77?F rise." t:dataTypeName=number

metric m:recovery_efficiency p:integer l:"Recovery Efficiency (%)" d:"Recovery efficiency refers to how efficiently the heat from the burner is transferred to the water in the tank." t:dataTypeName=percent

metric m:solar_collector_panel_area_sq_feet p:double l:"Solar Collector Panel Area (sq. ft.)" d:"Refers to the total area consumed by the solar collector." t:dataTypeName=number

metric m:solar_energy_factor_sef p:double l:"Solar Energy Factor (SEF)" d:"Solar Energy Factor refers to the energy delivered by the total system divided by the electrical or gas energy put into the system. The higher the SEF, the greater the solar contribution to water heating, which reduces the energy required by the backup water heater. The SEF is presented as a number similar to the Energy Factor (EF) given to conventional water heaters by the DOE test procedure." t:dataTypeName=number

metric m:freeze_tolerance_limit_f p:integer l:"Freeze Tolerance Limit (F)" d:"The limit to the system?s tolerance of freezing weather conditions." t:dataTypeName=number

metric m:solar_tank_volume_gallons p:integer l:"Solar Tank Volume (gallons)" d:"Capacity of the tank, in gallons." t:dataTypeName=number

metric m:solar_auxiliary_tank_volume_gallons p:integer l:"Solar Auxiliary Tank Volume (gallons)" d:"Volume is the capacity of the tank in a solar system, in gallons." t:dataTypeName=number

metric m:solar_auxiliary_tank_input_kw p:float l:"Solar Auxiliary Tank Input (kW)" d:"Electric Input kW refers to the input wattage of the heat pump or supplementary electric elements." t:dataTypeName=number

metric m:solar_auxiliary_tank_input_thousand_btu_per_hour p:long l:"Solar Auxiliary Tank Input (kBtu/hr)" d:"Auxiliary Input refers to the input KBTU per hour rating of the backup gas water heater in the solar system, in thousand BTU per hour." t:dataTypeName=number

metric m:water_heater_depth_inches p:float l:"Water Heater Depth (in.)" d:"The water heater's depth, in inches." t:dataTypeName=number

metric m:water_heater_height_inches p:float l:"Water Heater Height (in.)" d:"The water heater's height, in inches." t:dataTypeName=number

metric m:water_heater_width_inches p:float l:"Water Heater Width (in.)" d:"The water heater's width, in inches." t:dataTypeName=number

entity e:3gp2-af4x l:"ENERGY STAR Certified Water Heaters" t:url=https://data.energystar.gov/api/views/3gp2-af4x

property e:3gp2-af4x t:meta.view v:id=3gp2-af4x v:category="Active Specifications" v:averageRating=0 v:name="ENERGY STAR Certified Water Heaters"

property e:3gp2-af4x t:meta.view.owner v:id=guxy-scz5 v:screenName=ESddas v:lastNotificationSeenAt=1491492552 v:displayName=ESddas

property e:3gp2-af4x t:meta.view.tableauthor v:id=guxy-scz5 v:screenName=ESddas v:roleName=publisher v:lastNotificationSeenAt=1491492552 v:displayName=ESddas

property e:3gp2-af4x t:meta.view.metadata.custom_fields.common_core v:Publisher="U.S. Environmental Protection Agency" v:License=https://edg.epa.gov/EPA_Data_License.html v:Contact_Name="Kathleen Vokes" v:Bureau_Code=020:00 v:Program_Code=020:033
```

## Top Records

```ls
| pd_id   | energy_star_partner    | brand_name | model_name             | model_number         | additional_model_information | type      | fuel     | vent_type | storage_volume_gallons | tank_height_inches | height_to_vent_inches | tank_diameter_inches | vent_size_inches | vent_size_2_inches | input_kw | volts | kwh_year | input_rate_thousand_btu_per_hour | thermal_efficiency_te | standby_loss | energy_factor | therms_year_for_natural_gas | gallons_year_for_propane | first_hour_rating_gallons_per_hour | maximum_gallons_per_minute | minimum_gallons_per_minute | recovery_efficiency | solar_system_type | solar_collector_type | solar_collector_panel_area_sq_feet | solar_energy_factor_sef | freeze_tolerance_limit_f | solar_tank_volume_gallons | solar_type_of_backup | solar_auxiliary_tank_volume_gallons | solar_auxiliary_tank_input_kw | solar_auxiliary_tank_input_thousand_btu_per_hour | water_heater_depth_inches | water_heater_height_inches | water_heater_width_inches | date_available_on_market | date_qualified      | markets       | energy_star_model_identifier    | 
| ======= | ====================== | ========== | ====================== | ==================== | ============================ | ========= | ======== | ========= | ====================== | ================== | ===================== | ==================== | ================ | ================== | ======== | ===== | ======== | ================================ | ===================== | ============ | ============= | =========================== | ======================== | ================================== | ========================== | ========================== | =================== | ================= | ==================== | ================================== | ======================= | ======================== | ========================= | ==================== | =================================== | ============================= | ================================================ | ========================= | ========================== | ========================= | ======================== | =================== | ============= | =============================== | 
| 2236853 | A.O. Smith Corporation | American   | Heat Pump Water Heater | HPE6280H045DV 102    |                              | Heat Pump | Electric |           | 80                     | 80.8               |                       | 25.2                 |                  |                    | 2        | 240   | 1515     |                                  |                       |              | 2.33          |                             |                          | 84                                 |                            |                            | 100                 |                   |                      |                                    |                         |                          |                           |                      |                                     |                               |                                                  |                           |                            |                           | 2014-11-01T00:00:00      | 2015-04-14T00:00:00 | United States | ES_92897_04142015123625_1451663 | 
| 2240321 | A.O. Smith Corporation | American   | Heat Pump Water Heater | HPHE10250H045DV 120  |                              | Heat Pump | Electric |           | 50                     | 62.5               |                       | 22.5                 |                  |                    |          | 240   | 1516     |                                  |                       |              | 3.24          |                             |                          | 70                                 |                            |                            | 100                 |                   |                      |                                    |                         |                          |                           |                      |                                     |                               |                                                  |                           | 62.5                       |                           | 2015-05-22T00:00:00      | 2015-05-28T00:00:00 | United States | ES_92897_05282015114102_1410611 | 
| 2270603 | A.O. Smith Corporation | American   | Heat Pump Water Heater | HPHE10250H045DVN 120 |                              | Heat Pump | Electric |           | 50                     | 46                 |                       | 15                   |                  |                    | 4.5      | 240   | 1516     |                                  |                       |              | 3.24          |                             |                          | 70                                 |                            |                            | 100                 |                   |                      |                                    |                         |                          |                           |                      |                                     |                               |                                                  |                           | 62.5                       |                           | 2016-05-27T00:00:00      | 2016-06-24T00:00:00 | United States | ES_92897_06242016161450_9704196 | 
| 2248443 | A.O. Smith Corporation | American   | Heat Pump Water Heater | HPHE10266H045DV 120  |                              | Heat Pump | Electric |           | 66                     | 44                 |                       | 22.5                 |                  |                    |          | 240   | 1562     |                                  |                       |              | 3.17          |                             |                          | 80                                 |                            |                            | 100                 |                   |                      |                                    |                         |                          |                           |                      |                                     |                               |                                                  |                           |                            |                           | 2015-05-22T00:00:00      | 2015-09-24T00:00:00 | United States | ES_92897_09242015112439_2453188 | 
| 2270640 | A.O. Smith Corporation | American   | Heat Pump Water Heater | HPHE10266H045DVN 120 |                              | Heat Pump | Electric |           | 66                     | 44                 |                       | 22.5                 |                  |                    | 4.5      | 240   | 1562     |                                  |                       |              | 3.17          |                             |                          | 80                                 |                            |                            | 100                 |                   |                      |                                    |                         |                          |                           |                      |                                     |                               |                                                  |                           | 60.5                       |                           | 2016-05-27T00:00:00      | 2016-06-24T00:00:00 | United States | ES_92897_06242016161451_9816075 | 
| 2240310 | A.O. Smith Corporation | American   | Heat Pump Water Heater | HPHE10280H045DV 120  |                              | Heat Pump | Electric |           | 80                     | 68.5               |                       | 26.7                 |                  |                    |          | 240   | 1591     |                                  |                       |              | 3.07          |                             |                          | 95                                 |                            |                            | 100                 |                   |                      |                                    |                         |                          |                           |                      |                                     |                               |                                                  |                           | 68.5                       |                           | 2015-05-22T00:00:00      | 2015-05-28T00:00:00 | United States | ES_92897_05282015114102_2399977 | 
| 2270619 | A.O. Smith Corporation | American   | Heat Pump Water Heater | HPHE10280H045DVN 120 |                              | Heat Pump | Electric |           | 80                     | 52                 |                       | 22.5                 |                  |                    | 4.5      | 240   | 1591     |                                  |                       |              | 3.07          |                             |                          | 95                                 |                            |                            | 100                 |                   |                      |                                    |                         |                          |                           |                      |                                     |                               |                                                  |                           | 68.5                       |                           | 2016-05-27T00:00:00      | 2016-06-24T00:00:00 | United States | ES_92897_06242016161450_7375551 | 
| 2270639 | A.O. Smith Corporation | American   | Heat Pump Water Heater | HPHE6266H045DV 120   |                              | Heat Pump | Electric |           | 66                     | 44                 |                       | 22.5                 |                  |                    | 4.5      | 240   | 1562     |                                  |                       |              | 3.17          |                             |                          | 80                                 |                            |                            | 100                 |                   |                      |                                    |                         |                          |                           |                      |                                     |                               |                                                  |                           | 60.5                       |                           | 2016-05-27T00:00:00      | 2016-06-24T00:00:00 | United States | ES_92897_06242016161451_9438726 | 
| 2270618 | A.O. Smith Corporation | American   | Heat Pump Water Heater | HPHE6280H045DV 120   |                              | Heat Pump | Electric |           | 80                     | 52                 |                       | 22.5                 |                  |                    | 4.5      | 240   | 1591     |                                  |                       |              | 3.07          |                             |                          | 95                                 |                            |                            | 100                 |                   |                      |                                    |                         |                          |                           |                      |                                     |                               |                                                  |                           | 68.5                       |                           | 2016-05-27T00:00:00      | 2016-06-24T00:00:00 | United States | ES_92897_06242016161450_3586970 | 
| 2270602 | A.O. Smith Corporation | American   | Heat Pump Water Heater | HPHE650H045DV 120    |                              | Heat Pump | Electric |           | 50                     | 46                 |                       | 15                   |                  |                    | 4.5      | 240   | 1516     |                                  |                       |              | 3.24          |                             |                          | 70                                 |                            |                            | 100                 |                   |                      |                                    |                         |                          |                           |                      |                                     |                               |                                                  |                           | 62.5                       |                           | 2016-05-27T00:00:00      | 2016-06-24T00:00:00 | United States | ES_92897_06242016161450_6030176 | 
```