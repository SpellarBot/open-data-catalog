# ENERGY STAR Certified Ventilating Fans

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/energy-star-certified-ventilating-fans) |
| Metadata | [Link](https://data.energystar.gov/api/views/8dv7-nngq) |
| Data: JSON | [100 Rows](https://data.energystar.gov/api/views/8dv7-nngq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.energystar.gov/api/views/8dv7-nngq/rows.csv?max_rows=100) |
| Host | data.energystar.gov |
| Id | 8dv7-nngq |
| Name | ENERGY STAR Certified Ventilating Fans |
| Category | Active Specifications |
| Tags | ventilating fans, vent fans |
| Created | 2013-05-01T17:09:56Z |
| Publication Date | 2016-12-29T15:49:20Z |

## Description

Certified models meet all ENERGY STAR requirements as listed in the Version 4.0 ENERGY STAR Program Requirements for Ventilating Fans that are effective as of October 1, 2015. A detailed listing of key efficiency criteria are available at http://www.energystar.gov/index.cfm?c=vent_fans.pr_crit_vent_fans

## Columns

```ls
| Included | Schema Type    | Field Name                                  | Name                                                    | Data Type     | Render Type   |
| ======== | ============== | =========================================== | ======================================================= | ============= | ============= |
| Yes      | series tag     | pd_id                                       | ENERGY STAR Unique ID                                   | text          | number        |
| Yes      | series tag     | energy_star_partner                         | ENERGY STAR Partner                                     | text          | text          |
| Yes      | series tag     | brand_name                                  | Brand Name                                              | text          | text          |
| Yes      | series tag     | model_name                                  | Model Name                                              | text          | text          |
| Yes      | series tag     | model_number                                | Model Number                                            | text          | text          |
| Yes      | series tag     | additional_model_information                | Additional Model Information                            | text          | text          |
| Yes      | series tag     | unit_type                                   | Type                                                    | text          | text          |
| Yes      | series tag     | number_of_speeds                            | Number of Speeds                                        | text          | text          |
| Yes      | series tag     | duct_size                                   | Duct Size                                               | text          | text          |
| Yes      | series tag     | sound_level_sones                           | Sound Level (sones)                                     | text          | text          |
| Yes      | series tag     | lighting_technology_used                    | Lighting Technology                                     | text          | text          |
| Yes      | numeric metric | light_output_lumens                         | Light Output (lumens)                                   | number        | number        |
| Yes      | numeric metric | total_input_power_watts                     | Total Input Power (Watts)                               | number        | number        |
| Yes      | numeric metric | luminaire_efficacy                          | Energy Efficiency - Measured Outside the Fixture (lm/W) | number        | number        |
| Yes      | numeric metric | power_factor                                | Power Factor                                            | number        | number        |
| Yes      | series tag     | correlated_color_temperature_kelvin         | Appearance (CCT)                                        | text          | text          |
| Yes      | numeric metric | color_rendering_index_cri                   | Color Quality (CRI)                                     | number        | number        |
| Yes      | numeric metric | life_source_life_hours                      | Light Source Life (Hours)                               | number        | number        |
| Yes      | series tag     | special_features_dimming_motion_sensing_etc | Special Features (Dimming, Motion Sensing, etc.)        | text          | text          |
| Yes      | series tag     | notes                                       | Notes                                                   | text          | text          |
| Yes      | time           | date_available_on_market                    | Date Available On Market                                | calendar_date | calendar_date |
| No       |                | date_qualified                              | Date Qualified                                          | calendar_date | calendar_date |
| Yes      | series tag     | markets                                     | Markets                                                 | text          | text          |
| Yes      | series tag     | energy_star_model_identifier                | CB Model Identifier                                     | text          | text          |
| Yes      | series tag     | lighting                                    | Lighting                                                | text          | text          |
| Yes      | numeric metric | airflow_1_cfm                               | Airflow 1 (cfm)                                         | number        | number        |
| Yes      | numeric metric | airflow_2_cfm                               | Airflow 2 (cfm)                                         | number        | number        |
| Yes      | numeric metric | airflow_3_cfm                               | Airflow 3 (cfm)                                         | number        | number        |
| Yes      | numeric metric | efficacy_1_cfm_w                            | Efficacy 1 (cfm/Watt)                                   | number        | number        |
| Yes      | numeric metric | efficacy_2_cfm_w                            | Efficacy 2 (cfm/Watt)                                   | number        | number        |
| Yes      | numeric metric | efficacy_3_cfm_w                            | Efficacy 3 (cfm/Watt)                                   | number        | number        |
| Yes      | series tag     | meets_most_efficient_criteria               | Meets ENERGY STAR Most Efficient 2017 Criteria          | text          | text          |
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
series e:8dv7-nngq d:2016-11-15T00:00:00.000Z t:correlated_color_temperature_kelvin=4000/4100K t:duct_size="3.25 inch diameter" t:markets="United States, Canada" t:meets_most_efficient_criteria=No t:brand_name="Air King" t:model_name="Air King" t:pd_id=2285471 t:special_features_dimming_motion_sensing_etc=Non-Dimmable t:energy_star_partner="Air-King, Ltd." t:model_number=ECQ303 t:number_of_speeds="3 or more" t:lighting=Yes t:sound_level_sones="0.6 - 0.6" t:energy_star_model_identifier=ES_30227_ECQ303_12022016000000_4504633 t:unit_type="Range Hood" m:efficacy_1_cfm_w=3.6 m:airflow_2_cfm=150 m:efficacy_2_cfm_w=3.9 m:airflow_1_cfm=150 m:life_source_life_hours=36000 m:luminaire_efficacy=96.1 m:color_rendering_index_cri=84

series e:8dv7-nngq d:2016-11-15T00:00:00.000Z t:correlated_color_temperature_kelvin=4000/4100K t:duct_size="3.25 inch diameter" t:markets="United States, Canada" t:meets_most_efficient_criteria=No t:brand_name="Air King" t:model_name="Air King" t:pd_id=2285469 t:special_features_dimming_motion_sensing_etc=Non-Dimmable t:energy_star_partner="Air-King, Ltd." t:model_number=ECQ306 t:number_of_speeds="3 or more" t:lighting=Yes t:sound_level_sones="0.6 - 0.6" t:energy_star_model_identifier=ES_30227_ECQ306_12022016000000_4504635 t:unit_type="Range Hood" m:efficacy_1_cfm_w=3.6 m:airflow_2_cfm=150 m:efficacy_2_cfm_w=3.9 m:airflow_1_cfm=150 m:life_source_life_hours=36000 m:luminaire_efficacy=96.1 m:color_rendering_index_cri=84

series e:8dv7-nngq d:2016-11-15T00:00:00.000Z t:correlated_color_temperature_kelvin=4000/4100K t:duct_size="3.25 inch diameter" t:markets="United States, Canada" t:meets_most_efficient_criteria=No t:brand_name="Air King" t:model_name="Air King" t:pd_id=2285473 t:special_features_dimming_motion_sensing_etc=Non-Dimmable t:energy_star_partner="Air-King, Ltd." t:model_number=ECQ308 t:number_of_speeds="3 or more" t:lighting=Yes t:sound_level_sones="0.6 - 0.6" t:energy_star_model_identifier=ES_30227_ECQ308_12022016000000_4504631 t:unit_type="Range Hood" m:efficacy_1_cfm_w=3.6 m:airflow_2_cfm=150 m:efficacy_2_cfm_w=3.9 m:airflow_1_cfm=150 m:life_source_life_hours=36000 m:luminaire_efficacy=96.1 m:color_rendering_index_cri=84
```

## Meta Commands

```ls
metric m:light_output_lumens p:long l:"Light Output (lumens)" d:"The amount of light emitted by the light source or light fixture. Non directional fixtures (with removable light sources i.e. GU24 base bulbs) are measured at the light source and do not account for light lost from the fixture, while other fixtures meant to put light on a specific application (e.g. recessed downlights, under cabinet lights, accent lights, cove lights) are measured at the fixture level, only counting the light that escapes the fixture." t:dataTypeName=number

metric m:total_input_power_watts p:long l:"Total Input Power (Watts)" d:"Total power consumed by the luminaire while in use." t:dataTypeName=number

metric m:luminaire_efficacy p:double l:"Energy Efficiency - Measured Outside the Fixture (lm/W)" d:"The quotient of the total luminous flux (lumens) emitted by the fixture over the total power input (Watts). It is expressed in lumens per watt (lm/W). For ENERGY STAR qualified fixtures this applies to light fixtures that are considered directional and are measured at the fixture level. This includes the following residential grade directional fixture types: line-voltage track lights, ceiling fan light kits, undercabinet and cove lighting, downlights, recessed, pendant or surface mounted and includes retrofit kits for existing recessed cans. This also includes the following LIMITED commercial fixture types: Accent lights such as line-voltage track lights, under cabinet task lights, portable desk task lights, downlights, recessed, pendant or surface-mounts BUT EXCLUDES typical commercial and industrial fixtures such as recessed troffers or linear forms (e.g. linear fluorescent pendants) typically used in office spaces." t:dataTypeName=number

metric m:power_factor p:float l:"Power Factor" d:"Ratio of real power flowing to the lamp to the apparent power in the circuit. A lamp with a lower power factor will draw more current than a lamp with a higher power factor of the same wattage." t:dataTypeName=number

metric m:color_rendering_index_cri p:integer l:"Color Quality (CRI)" d:"Measure of the degree of color shift objects undergo when illuminated by the light source as compared with the color of those same objects when illuminated by a reference source of comparable color temperature." t:dataTypeName=number

metric m:life_source_life_hours p:integer l:"Light Source Life (Hours)" d:"The expected useful life of the light source. Measured differently depending on the technology of the light source. For example, LED lighting expected useful life is based on the estimated point at which only 70% of the original light output remains, while for older technologies, like fluorescent and halogen, estimated useful life is based on the measured median sample life." t:dataTypeName=number

metric m:airflow_1_cfm p:integer l:"Airflow 1 (cfm)" d:"It is standard industry practice to round down airflow to the nearest 10 cfm when publishing this metric in product directories as the Airflow Certified Rating. For this reason, Airflow Certified Rating and As-Tested Airflow may occasionally differ on this list. In the case of a range hood, Airflow Certified Rating represents performance at working speed, while in the case of a bathroom or utility room fan, or an in-line ventilating fan, it represents maximum speed." t:dataTypeName=number

metric m:airflow_2_cfm p:integer l:"Airflow 2 (cfm)" d:"It is standard industry practice to round down airflow to the nearest 10 cfm when publishing this metric in product directories as the Airflow Certified Rating. For this reason, Airflow Certified Rating and As-Tested Airflow may occasionally differ on this list. In the case of a range hood, Airflow Certified Rating represents performance at working speed, while in the case of a bathroom or utility room fan, or an in-line ventilating fan, it represents maximum speed." t:dataTypeName=number

metric m:airflow_3_cfm p:integer l:"Airflow 3 (cfm)" d:"It is standard industry practice to round down airflow to the nearest 10 cfm when publishing this metric in product directories as the Airflow Certified Rating. For this reason, Airflow Certified Rating and As-Tested Airflow may occasionally differ on this list. In the case of a range hood, Airflow Certified Rating represents performance at working speed, while in the case of a bathroom or utility room fan, or an in-line ventilating fan, it represents maximum speed." t:dataTypeName=number

metric m:efficacy_1_cfm_w p:double l:"Efficacy 1 (cfm/Watt)" d:"Efficacy is calculated by using airflow and fan motor electrical power values as tested per the requirements of this specification. Fan motor electrical usage is the only energy consumption considered for the fan efficacy calculation. Energy used for other fan auxiliaries (e.g., lights, sensors, heaters, timers, or night lights) is not included in the determination of fan efficacy." t:dataTypeName=number

metric m:efficacy_2_cfm_w p:float l:"Efficacy 2 (cfm/Watt)" d:"Efficacy is calculated by using airflow and fan motor electrical power values as tested per the requirements of this specification. Fan motor electrical usage is the only energy consumption considered for the fan efficacy calculation. Energy used for other fan auxiliaries (e.g., lights, sensors, heaters, timers, or night lights) is not included in the determination of fan efficacy." t:dataTypeName=number

metric m:efficacy_3_cfm_w p:float l:"Efficacy 3 (cfm/Watt)" d:"Efficacy is calculated by using airflow and fan motor electrical power values as tested per the requirements of this specification. Fan motor electrical usage is the only energy consumption considered for the fan efficacy calculation. Energy used for other fan auxiliaries (e.g., lights, sensors, heaters, timers, or night lights) is not included in the determination of fan efficacy." t:dataTypeName=number

entity e:8dv7-nngq l:"ENERGY STAR Certified Ventilating Fans" t:url=https://data.energystar.gov/api/views/8dv7-nngq

property e:8dv7-nngq t:meta.view v:id=8dv7-nngq v:category="Active Specifications" v:averageRating=0 v:name="ENERGY STAR Certified Ventilating Fans"

property e:8dv7-nngq t:meta.view.owner v:id=guxy-scz5 v:screenName=ESddas v:lastNotificationSeenAt=1491492552 v:displayName=ESddas

property e:8dv7-nngq t:meta.view.tableauthor v:id=guxy-scz5 v:screenName=ESddas v:roleName=publisher v:lastNotificationSeenAt=1491492552 v:displayName=ESddas

property e:8dv7-nngq t:meta.view.metadata.custom_fields.common_core v:Publisher="U.S. Environmental Protection Agency" v:License=https://edg.epa.gov/EPA_Data_License.html v:Contact_Name="Kathleen Vokes" v:Bureau_Code=020:00 v:Program_Code=020:033
```

## Top Records

```ls
| pd_id   | energy_star_partner | brand_name | model_name | model_number | additional_model_information | unit_type  | number_of_speeds | duct_size          | sound_level_sones | lighting_technology_used | light_output_lumens | total_input_power_watts | luminaire_efficacy | power_factor | correlated_color_temperature_kelvin | color_rendering_index_cri | life_source_life_hours | special_features_dimming_motion_sensing_etc | notes | date_available_on_market | date_qualified      | markets               | energy_star_model_identifier           | lighting | airflow_1_cfm | airflow_2_cfm | airflow_3_cfm | efficacy_1_cfm_w | efficacy_2_cfm_w | efficacy_3_cfm_w | meets_most_efficient_criteria | 
| ======= | =================== | ========== | ========== | ============ | ============================ | ========== | ================ | ================== | ================= | ======================== | =================== | ======================= | ================== | ============ | =================================== | ========================= | ====================== | =========================================== | ===== | ======================== | =================== | ===================== | ====================================== | ======== | ============= | ============= | ============= | ================ | ================ | ================ | ============================= | 
| 2285471 | Air-King, Ltd.      | Air King   | Air King   | ECQ303       |                              | Range Hood | 3 or more        | 3.25 inch diameter | 0.6 - 0.6         |                          |                     |                         | 96.1               |              | 4000/4100K                          | 84                        | 36000                  | Non-Dimmable                                |       | 2016-11-15T00:00:00      | 2016-12-02T00:00:00 | United States, Canada | ES_30227_ECQ303_12022016000000_4504633 | Yes      | 150           | 150           |               | 3.6              | 3.9              |                  | No                            | 
| 2285469 | Air-King, Ltd.      | Air King   | Air King   | ECQ306       |                              | Range Hood | 3 or more        | 3.25 inch diameter | 0.6 - 0.6         |                          |                     |                         | 96.1               |              | 4000/4100K                          | 84                        | 36000                  | Non-Dimmable                                |       | 2016-11-15T00:00:00      | 2016-12-02T00:00:00 | United States, Canada | ES_30227_ECQ306_12022016000000_4504635 | Yes      | 150           | 150           |               | 3.6              | 3.9              |                  | No                            | 
| 2285473 | Air-King, Ltd.      | Air King   | Air King   | ECQ308       |                              | Range Hood | 3 or more        | 3.25 inch diameter | 0.6 - 0.6         |                          |                     |                         | 96.1               |              | 4000/4100K                          | 84                        | 36000                  | Non-Dimmable                                |       | 2016-11-15T00:00:00      | 2016-12-02T00:00:00 | United States, Canada | ES_30227_ECQ308_12022016000000_4504631 | Yes      | 150           | 150           |               | 3.6              | 3.9              |                  | No                            | 
| 2285470 | Air-King, Ltd.      | Air King   | Air King   | ECQ363       |                              | Range Hood | 3 or more        | 3.25 inch diameter | 0.6 - 0.6         |                          |                     |                         | 96.1               |              | 4000/4100K                          | 84                        | 36000                  | Non-Dimmable                                |       | 2016-11-15T00:00:00      | 2016-12-02T00:00:00 | United States, Canada | ES_30227_ECQ363_12022016000000_4504634 | Yes      | 150           | 150           |               | 3.6              | 3.9              |                  | No                            | 
| 2285468 | Air-King, Ltd.      | Air King   | Air King   | ECQ366       |                              | Range Hood | 3 or more        | 3.25 inch diameter | 0.6 - 0.6         |                          |                     |                         | 96.1               |              | 4000/4100K                          | 84                        | 36000                  | Non-Dimmable                                |       | 2016-11-15T00:00:00      | 2016-12-02T00:00:00 | United States, Canada | ES_30227_ECQ366_12022016000000_4504636 | Yes      | 150           | 150           |               | 3.6              | 3.9              |                  | No                            | 
| 2285472 | Air-King, Ltd.      | Air King   | Air King   | ECQ368       |                              | Range Hood | 3 or more        | 3.25 inch diameter | 0.6 - 0.6         |                          |                     |                         | 96.1               |              | 4000/4100K                          | 84                        | 36000                  | Non-Dimmable                                |       | 2016-11-15T00:00:00      | 2016-12-02T00:00:00 | United States, Canada | ES_30227_ECQ368_12022016000000_4504632 | Yes      | 150           | 150           |               | 3.6              | 3.9              |                  | No                            | 
| 2288007 | Air-King, Ltd.      | Air King   | Air King   | ECV303       |                              | Range Hood | 3 or more        | 3.25 inch diameter | 0.6 - 0.6         |                          |                     |                         | 76.9               |              |                                     |                           |                        |                                             |       | 2017-01-06T00:00:00      | 2017-01-06T00:00:00 | United States, Canada | ES_30227_ECV303_01062017000000_4504696 | Yes      | 150           | 150           |               | 3.6              | 3.9              |                  | No                            | 
| 2288008 | Air-King, Ltd.      | Air King   | Air King   | ECV306       |                              | Range Hood | 3 or more        | 3.25 inch diameter | 0.6 - 0.6         |                          |                     |                         | 76.9               |              |                                     |                           |                        |                                             |       | 2017-01-06T00:00:00      | 2017-01-06T00:00:00 | United States, Canada | ES_30227_ECV306_01062017000000_4504697 | Yes      | 150           | 150           |               | 3.6              | 3.9              |                  | No                            | 
| 2285475 | Air-King, Ltd.      | Air King   | Air King   | ECV308       |                              | Range Hood | 3 or more        | 3.25 inch diameter | 0.6 - 0.6         |                          |                     |                         | 76.9               |              |                                     |                           |                        |                                             |       | 2016-11-30T00:00:00      | 2016-12-02T00:00:00 | United States, Canada | ES_30227_ECV308_12022016000000_4504650 | Yes      | 150           | 150           |               | 3.6              | 3.9              |                  | No                            | 
| 2288010 | Air-King, Ltd.      | Air King   | Air King   | ECV363       |                              | Range Hood | 3 or more        | 3.25 inch diameter | 0.6 - 0.6         |                          |                     |                         | 76.9               |              |                                     |                           |                        |                                             |       | 2017-01-06T00:00:00      | 2017-01-06T00:00:00 | United States, Canada | ES_30227_ECV363_01062017000000_4504698 | Yes      | 150           | 150           |               | 3.6              | 3.9              |                  | No                            | 
```