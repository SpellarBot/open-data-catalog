# ENERGY STAR Certified Ceiling Fans

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/energy-star-certified-ceiling-fans) |
| Metadata | [Link](https://data.energystar.gov/api/views/mj8j-2jhz) |
| Data: JSON | [100 Rows](https://data.energystar.gov/api/views/mj8j-2jhz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.energystar.gov/api/views/mj8j-2jhz/rows.csv?max_rows=100) |
| Host | data.energystar.gov |
| Id | mj8j-2jhz |
| Name | ENERGY STAR Certified Ceiling Fans |
| Category | Active Specifications |
| Tags | ceiling fans |
| Created | 2013-05-01T16:08:51Z |
| Publication Date | 2016-12-29T15:31:30Z |

## Description

Certified models meet all ENERGY STAR requirements as listed in the Version 3.0 ENERGY STAR Program Requirements for Ceiling Fans that are effective as of April 1, 2012. A detailed listing of key efficiency criteria are available at http://www.energystar.gov/index.cfm?c=ceiling_fans.pr_crit_ceiling_fans

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
| Yes      | series tag     | product_type                                | Product Type                                            | text          | text          |
| Yes      | numeric metric | ceiling_fan_size_diameters_in_inches        | Size (Diameter) (in.)                                   | number        | number        |
| Yes      | numeric metric | airflow_efficiency_cfm_watt_low             | Airflow Efficiency (cfm/Watt) - Low                     | number        | number        |
| Yes      | numeric metric | airflow_efficiency_cfm_watt_medium          | Airflow Efficiency (cfm/Watt) - Medium                  | number        | number        |
| Yes      | numeric metric | airflow_efficiency_cfm_watt_high            | Airflow Efficiency (cfm/Watt) - High                    | number        | number        |
| Yes      | series tag     | ceiling_fan_motor_warranty_years            | Ceiling Fan Motor Warranty (yrs)                        | text          | text          |
| Yes      | series tag     | ceiling_fan_components_warranty_years       | Ceiling Fan Components Warranty (yrs)                   | text          | text          |
| Yes      | series tag     | lighting_technology_used                    | Lighting Technology                                     | text          | text          |
| Yes      | numeric metric | light_output_lumens                         | Light Output (lumens)                                   | number        | number        |
| Yes      | numeric metric | total_input_power_watts                     | Total Input Power (Watts)                               | number        | number        |
| Yes      | numeric metric | luminaire_efficacy                          | Energy Efficiency - Measured Outside the Fixture (lm/W) | number        | number        |
| Yes      | numeric metric | power_factor                                | Power Factor                                            | number        | number        |
| Yes      | series tag     | correlated_color_temperature_kelvin         | Appearance (CCT)                                        | text          | text          |
| Yes      | numeric metric | color_rendering_index_cri                   | Color Quality (CRI)                                     | number        | number        |
| Yes      | numeric metric | life_source_life_hours                      | Light Source Life (hrs)                                 | number        | number        |
| Yes      | series tag     | special_features_dimming_motion_sensing_etc | Special Features (Dimming, Motion Sensing, etc.)        | text          | text          |
| Yes      | series tag     | notes                                       | Notes                                                   | text          | text          |
| Yes      | time           | date_available_on_market                    | Date Available on Market                                | calendar_date | calendar_date |
| No       |                | date_qualified                              | Date Certified                                          | calendar_date | calendar_date |
| Yes      | series tag     | markets                                     | Markets                                                 | text          | text          |
| Yes      | series tag     | energy_star_model_identifier                | CB Model Identifier                                     | text          | text          |
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
series e:mj8j-2jhz d:2014-08-14T00:00:00.000Z t:energy_star_partner="Big Ass Fans" t:additional_model_information="H Series,S3150-A2-BC-04-02-C, S3150-A2-BCW-04-02-C," t:model_number=S3150-A2-BW-04-02-C t:markets="United States, Canada" t:energy_star_model_identifier=ES_1113298_S3150-A2-BW-04-02-C_07062016020505_70077879 t:product_type="Ceiling Fan Only" t:ceiling_fan_motor_warranty_years=Lifetime t:meets_most_efficient_criteria=Yes t:model_name="H Series" t:brand_name=Haiku t:ceiling_fan_components_warranty_years=1 t:pd_id=2271813 m:airflow_efficiency_cfm_watt_low=700 m:airflow_efficiency_cfm_watt_high=388 m:airflow_efficiency_cfm_watt_medium=595 m:ceiling_fan_size_diameters_in_inches=60

series e:mj8j-2jhz d:2014-08-14T00:00:00.000Z t:energy_star_partner="Big Ass Fans" t:additional_model_information="H Series,S3150-A2-BC-04-03-C, S3150-A2-BCW-04-03-C," t:model_number=S3150-A2-BW-04-03-C t:markets="United States, Canada" t:energy_star_model_identifier=ES_1113298_S3150-A2-BW-04-03-C_12102014081004_8888888 t:product_type="Ceiling Fan Only" t:ceiling_fan_motor_warranty_years=Lifetime t:meets_most_efficient_criteria=Yes t:model_name="H Series" t:brand_name=Haiku t:ceiling_fan_components_warranty_years=1 t:pd_id=2229124 m:airflow_efficiency_cfm_watt_low=938 m:airflow_efficiency_cfm_watt_high=504 m:airflow_efficiency_cfm_watt_medium=708 m:ceiling_fan_size_diameters_in_inches=60

series e:mj8j-2jhz d:2014-08-14T00:00:00.000Z t:energy_star_partner="Big Ass Fans" t:additional_model_information="H Series,S3150-S0-AW-04-02-C-F421," t:model_number=S3150-S0-AB-04-02-C-F421 t:markets="United States, Canada" t:energy_star_model_identifier=ES_0000000_S3150-S0-AB-04-02-C-F421_08132015065950_70035905 t:product_type="Ceiling Fan Only" t:ceiling_fan_motor_warranty_years=Lifetime t:meets_most_efficient_criteria=Yes t:model_name="H Series" t:brand_name=Haiku t:ceiling_fan_components_warranty_years=1 t:pd_id=2245587 m:airflow_efficiency_cfm_watt_low=727 m:airflow_efficiency_cfm_watt_high=392 m:airflow_efficiency_cfm_watt_medium=565 m:ceiling_fan_size_diameters_in_inches=60
```

## Meta Commands

```ls
metric m:ceiling_fan_size_diameters_in_inches p:integer l:"Size (Diameter) (in.)" d:"The diameter (in inches) of a ceiling fan tip to tip." t:dataTypeName=number

metric m:airflow_efficiency_cfm_watt_low p:integer l:"Airflow Efficiency (cfm/Watt) - Low" d:"The ratio of airflow divided by power at a specific residential ceiling fan setting expressed in cubic feet per minute/Watt (CFM/watt) at low speed." t:dataTypeName=number

metric m:airflow_efficiency_cfm_watt_medium p:integer l:"Airflow Efficiency (cfm/Watt) - Medium" d:"The ratio of airflow divided by power at a specific residential ceiling fan setting expressed in cubic feet per minute/Watt (CFM/watt) at medium speed." t:dataTypeName=number

metric m:airflow_efficiency_cfm_watt_high p:integer l:"Airflow Efficiency (cfm/Watt) - High" d:"The ratio of airflow divided by power at a specific residential ceiling fan setting expressed in cubic feet per minute/Watt (CFM/watt) at high speed." t:dataTypeName=number

metric m:light_output_lumens p:integer l:"Light Output (lumens)" d:"The amount of light emitted by the light source or light fixture. Non directional fixtures (with removable light sources i.e. GU24 base bulbs) are measured at the light source and do not account for light lost from the fixture, while other fixtures meant to put light on a specific application (e.g. recessed downlights, under cabinet lights, accent lights, cove lights) are measured at the fixture level, only counting the light that escapes the fixture." t:dataTypeName=number

metric m:total_input_power_watts p:double l:"Total Input Power (Watts)" d:"Total power consumed by the light kit (luminaire) while in use." t:dataTypeName=number

metric m:luminaire_efficacy p:float l:"Energy Efficiency - Measured Outside the Fixture (lm/W)" d:"The quotient of the total luminous flux (lumens) emitted by the fixture or light source over the total power input (Watts). It is expressed in lumens per watt (lm/W)." t:dataTypeName=number

metric m:power_factor p:double l:"Power Factor" d:"Ratio of real power flowing to the lamp to the apparent power in the circuit. A lamp with a lower power factor will draw more current than a lamp with a higher power factor of the same wattage." t:dataTypeName=number

metric m:color_rendering_index_cri p:integer l:"Color Quality (CRI)" d:"The Color Rendering Index (CRI) of a light source represents the degree of color shift objects undergo when illuminated by the light source as compared with the color of those same objects when illuminated by a reference source of comparable color temperature. The ENERGY STAR specifications require a CRI of at least 80. Incandescent lighting has a CRI of 100. Early fluorescent lighting had CRIs in the 60s, resulting in unpleasant appearance of skin tones." t:dataTypeName=number

metric m:life_source_life_hours p:integer l:"Light Source Life (hrs)" d:"The expected useful life of the light source. Measured differently depending on the technology of the light source. For example, LED lighting expected useful life is based on the estimated point at which only 70% of the original light output remains, while for older technologies, like fluorescent and halogen, estimated useful life is based on the measured median sample life." t:dataTypeName=number

entity e:mj8j-2jhz l:"ENERGY STAR Certified Ceiling Fans" t:url=https://data.energystar.gov/api/views/mj8j-2jhz

property e:mj8j-2jhz t:meta.view v:id=mj8j-2jhz v:category="Active Specifications" v:averageRating=0 v:name="ENERGY STAR Certified Ceiling Fans"

property e:mj8j-2jhz t:meta.view.owner v:id=guxy-scz5 v:screenName=ESddas v:lastNotificationSeenAt=1491492552 v:displayName=ESddas

property e:mj8j-2jhz t:meta.view.tableauthor v:id=guxy-scz5 v:screenName=ESddas v:roleName=publisher v:lastNotificationSeenAt=1491492552 v:displayName=ESddas

property e:mj8j-2jhz t:meta.view.metadata.custom_fields.common_core v:Publisher="U.S. Environmental Protection Agency" v:License=https://edg.epa.gov/EPA_Data_License.html v:Contact_Name="Kathleen Vokes" v:Bureau_Code=020:00 v:Program_Code=020:033
```

## Top Records

```ls
| pd_id   | energy_star_partner | brand_name | model_name | model_number             | additional_model_information                        | product_type     | ceiling_fan_size_diameters_in_inches | airflow_efficiency_cfm_watt_low | airflow_efficiency_cfm_watt_medium | airflow_efficiency_cfm_watt_high | ceiling_fan_motor_warranty_years | ceiling_fan_components_warranty_years | lighting_technology_used | light_output_lumens | total_input_power_watts | luminaire_efficacy | power_factor | correlated_color_temperature_kelvin | color_rendering_index_cri | life_source_life_hours | special_features_dimming_motion_sensing_etc | notes | date_available_on_market | date_qualified      | markets               | energy_star_model_identifier                                | meets_most_efficient_criteria | 
| ======= | =================== | ========== | ========== | ======================== | =================================================== | ================ | ==================================== | =============================== | ================================== | ================================ | ================================ | ===================================== | ======================== | =================== | ======================= | ================== | ============ | =================================== | ========================= | ====================== | =========================================== | ===== | ======================== | =================== | ===================== | =========================================================== | ============================= | 
| 2271813 | Big Ass Fans        | Haiku      | H Series   | S3150-A2-BW-04-02-C      | H Series,S3150-A2-BC-04-02-C, S3150-A2-BCW-04-02-C, | Ceiling Fan Only | 60                                   | 700                             | 595                                | 388                              | Lifetime                         | 1                                     |                          |                     |                         |                    |              |                                     |                           |                        |                                             |       | 2014-08-14T00:00:00      | 2016-06-21T00:00:00 | United States, Canada | ES_1113298_S3150-A2-BW-04-02-C_07062016020505_70077879      | Yes                           | 
| 2229124 | Big Ass Fans        | Haiku      | H Series   | S3150-A2-BW-04-03-C      | H Series,S3150-A2-BC-04-03-C, S3150-A2-BCW-04-03-C, | Ceiling Fan Only | 60                                   | 938                             | 708                                | 504                              | Lifetime                         | 1                                     |                          |                     |                         |                    |              |                                     |                           |                        |                                             |       | 2014-08-14T00:00:00      | 2014-11-10T00:00:00 | United States, Canada | ES_1113298_S3150-A2-BW-04-03-C_12102014081004_8888888       | Yes                           | 
| 2245587 | Big Ass Fans        | Haiku      | H Series   | S3150-S0-AB-04-02-C-F421 | H Series,S3150-S0-AW-04-02-C-F421,                  | Ceiling Fan Only | 60                                   | 727                             | 565                                | 392                              | Lifetime                         | 1                                     |                          |                     |                         |                    |              |                                     |                           |                        |                                             |       | 2014-08-14T00:00:00      | 2015-07-24T00:00:00 | United States, Canada | ES_0000000_S3150-S0-AB-04-02-C-F421_08132015065950_70035905 | Yes                           | 
| 2245588 | Big Ass Fans        | Haiku      | H Series   | S3150-S0-AB-04-03-C-F421 | H Series,S3150-S0-AW-04-03-C-F421,                  | Ceiling Fan Only | 60                                   | 958                             | 879                                | 467                              | Lifetime                         | 1                                     |                          |                     |                         |                    |              |                                     |                           |                        |                                             |       | 2014-08-14T00:00:00      | 2015-07-24T00:00:00 | United States, Canada | ES_0000000_S3150-S0-AB-04-03-C-F421_08132015065950_70035905 | Yes                           | 
| 2271801 | Big Ass Fans        | Haiku      | H Series   | S3150-S0-BC              | H Series,S3150-S0-BCW, S3150-S0-BW,                 | Ceiling Fan Only | 60                                   | 786                             | 583                                | 419                              | Lifetime                         | 1                                     |                          |                     |                         |                    |              |                                     |                           |                        |                                             |       | 2014-08-14T00:00:00      | 2016-06-21T00:00:00 | United States, Canada | ES_1113298_S3150-S0-BC_07062016020505_70077879              | Yes                           | 
| 2271810 | Big Ass Fans        | Haiku      | H Series   | S3150-S0-BC-00-01-A      | H Series,S3150-S0-BCW-00-01-A, S3150-S0-BW-00-01-A, | Ceiling Fan Only | 60                                   | 579                             | 565                                | 392                              | Lifetime                         | 1                                     |                          |                     |                         |                    |              |                                     |                           |                        |                                             |       | 2014-08-14T00:00:00      | 2016-06-21T00:00:00 | United States, Canada | ES_1113298_S3150-S0-BC-00-01-A_07062016020505_70077879      | Yes                           | 
| 2271814 | Big Ass Fans        | Haiku      | H Series   | S3150-S0-BW-04-02-C      | H Series,S3150-S0-BC-04-02-C, S3150-S0-BCW-04-02-C, | Ceiling Fan Only | 60                                   | 854                             | 635                                | 395                              | Lifetime                         | 1                                     |                          |                     |                         |                    |              |                                     |                           |                        |                                             |       | 2014-08-14T00:00:00      | 2016-06-21T00:00:00 | United States, Canada | ES_1113298_S3150-S0-BW-04-02-C_07062016020505_70077879      | Yes                           | 
| 2229125 | Big Ass Fans        | Haiku      | H Series   | S3150-S0-BW-04-03-C      | H Series,S3150-S0-BC-04-03-C, S3150-S0-BCW-04-03-C, | Ceiling Fan Only | 60                                   | 923                             | 674                                | 398                              | Lifetime                         | 1                                     |                          |                     |                         |                    |              |                                     |                           |                        |                                             |       | 2014-08-14T00:00:00      | 2014-11-10T00:00:00 | United States, Canada | ES_1113298_S3150-S0-BW-04-03-C_12102014081004_8888888       | Yes                           | 
| 2245589 | Big Ass Fans        | Haiku      | H Series   | S3150-X2-AB-04-02-C-F421 | H Series,S3150-X2-AW-04-02-C-F421,                  | Ceiling Fan Only | 60                                   | 841                             | 811                                | 434                              | Lifetime                         | 1                                     |                          |                     |                         |                    |              |                                     |                           |                        |                                             |       | 2014-08-14T00:00:00      | 2015-07-24T00:00:00 | United States, Canada | ES_0000000_S3150-X2-AB-04-02-C-F421_08132015065950_70035905 | Yes                           | 
| 2245590 | Big Ass Fans        | Haiku      | H Series   | S3150-X2-AB-04-03-C-F421 | H Series,S3150-X2-AW-04-03-C-F421,                  | Ceiling Fan Only | 60                                   | 1010                            | 919                                | 451                              | Lifetime                         | 1                                     |                          |                     |                         |                    |              |                                     |                           |                        |                                             |       | 2014-08-14T00:00:00      | 2015-07-24T00:00:00 | United States, Canada | ES_0000000_S3150-X2-AB-04-03-C-F421_08132015065950_70035905 | Yes                           | 
```