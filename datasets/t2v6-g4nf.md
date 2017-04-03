# ENERGY STAR Certified Imaging Equipment

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/energy-star-certified-imaging-equipment) |
| Metadata | [Link](https://data.energystar.gov/api/views/t2v6-g4nf) |
| Data: JSON | [100 Rows](https://data.energystar.gov/api/views/t2v6-g4nf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.energystar.gov/api/views/t2v6-g4nf/rows.csv?max_rows=100) |
| Host | data.energystar.gov |
| Id | t2v6-g4nf |
| Name | ENERGY STAR Certified Imaging Equipment |
| Category | Active Specifications |
| Tags | imaging equipment |
| Created | 2013-08-28T20:47:59Z |
| Publication Date | 2016-08-19T17:31:12Z |

## Description

Certified models meet all ENERGY STAR requirements as listed in the Version 2.0 ENERGY STAR Program Requirements for Imaging Equipment that are effective as of January 1, 2014. A detailed listing of key efficiency criteria are available at http://www.energystar.gov/index.cfm?c=small_network_equipment.pr_imaging_equipment_key

## Columns

```ls
| Included | Schema Type    | Field Name                                     | Name                                               | Data Type     | Render Type   |
| ======== | ============== | ============================================== | ================================================== | ============= | ============= |
| Yes      | series tag     | pd_id                                          | ENERGY STAR Unique ID                              | text          | number        |
| Yes      | series tag     | energy_star_partner                            | ENERGY STAR Partner                                | text          | text          |
| Yes      | series tag     | brand_name                                     | Brand Name                                         | text          | text          |
| Yes      | series tag     | model_name                                     | Model Name                                         | text          | text          |
| Yes      | series tag     | model_number                                   | Model Number                                       | text          | text          |
| Yes      | series tag     | additional_model_information                   | Additional Model Information                       | text          | text          |
| Yes      | series tag     | product_type                                   | Type                                               | text          | text          |
| Yes      | series tag     | size_format                                    | Page Format Size                                   | text          | text          |
| Yes      | series tag     | marking_technology                             | Marking Technology                                 | text          | text          |
| Yes      | series tag     | color_capability                               | Color Capability                                   | text          | text          |
| Yes      | numeric metric | monochrome_product_speed_ipm_or_mppm           | Print Speed (ipm or mppm)                          | number        | number        |
| Yes      | series tag     | automatic_duplex_output_capable                | Automatic Duplex Output Capable                    | text          | text          |
| Yes      | numeric metric | typical_electricity_consumption_tec_kwh_wk     | Typical Electricity Consumption (TEC) (kWh/wk)     | number        | number        |
| Yes      | numeric metric | typical_electricity_consumption_tec_kwh_yr     | Typical Electricity Consumption (TEC) (kWh/yr)     | number        | number        |
| Yes      | numeric metric | power_in_sleep_w                               | Power in Sleep (Watts)                             | number        | number        |
| Yes      | numeric metric | power_in_standby_w                             | Power in Standby (Watts)                           | number        | number        |
| Yes      | numeric metric | default_delay_time_to_sleep_minutes            | Default Delay Time to Sleep (minutes)              | number        | number        |
| Yes      | numeric metric | print_copy_time_from_ready_state_s             | Print/Copy Time from Ready State (s)               | number        | number        |
| Yes      | numeric metric | print_copy_time_from_sleep_mode_s              | Print/Copy Time from Sleep Mode (s)                | number        | number        |
| Yes      | numeric metric | print_copy_time_from_previous_job_s            | Print/Copy Time from Previous Job (s)              | number        | number        |
| Yes      | series tag     | digital_front_end_dfe_manufacturer             | Digital Front End (DFE) Manufacturer               | text          | text          |
| Yes      | series tag     | dfe_model_number                               | DFE Model Number                                   | text          | text          |
| Yes      | numeric metric | dfe_typical_electricity_consumption_tec_kwh_wk | DFE Typical Electricity Consumption (TEC) (kWh/wk) | number        | number        |
| Yes      | numeric metric | dfe_typical_electricity_consumption_tec_kwh_yr | DFE Typical Electricity Consumption (TEC) (kWh/yr) | number        | number        |
| Yes      | numeric metric | dfe_ready_state_power_w                        | DFE Ready State Power (Watts)                      | number        | number        |
| Yes      | numeric metric | dfe_sleep_mode_power_w                         | DFE Sleep Mode Power (Watts)                       | number        | number        |
| Yes      | series tag     | functional_adders                              | Functional Adders                                  | text          | text          |
| Yes      | time           | date_available_on_market                       | Date Available On Market                           | calendar_date | calendar_date |
| No       |                | date_qualified                                 | Date Qualified                                     | calendar_date | calendar_date |
| Yes      | series tag     | markets                                        | Markets                                            | text          | text          |
| Yes      | series tag     | energy_star_model_identifier                   | CB Model Identifier                                | text          | text          |
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
series e:t2v6-g4nf d:2011-11-15T00:00:00.000Z t:energy_star_partner="Avision Inc." t:model_number=A5150 t:functional_adders="Wired > 20 MHz and < 500 MHz - USB 2.x, None" t:markets="United States, Australia, New Zealand, Switzerland, Europe, Taiwan, Japan, Canada" t:marking_technology="Electro-photographic (EP)" t:energy_star_model_identifier="ES_1105798_AVISION INC (175217) | A5150_01022014075231_9151078" t:product_type=Scanners t:automatic_duplex_output_capable=No t:size_format=Standard t:model_name=A5150 t:brand_name=Avision t:pd_id=2199989 m:power_in_sleep_w=2.17 m:power_in_standby_w=0.28 m:monochrome_product_speed_ipm_or_mppm=120 m:default_delay_time_to_sleep_minutes=15

series e:t2v6-g4nf d:2011-11-15T00:00:00.000Z t:energy_star_partner="Avision Inc." t:model_number=A5250 t:functional_adders="Wired > 20 MHz and < 500 MHz - USB 2.x, None" t:markets="United States, Australia, New Zealand, Switzerland, Europe, Taiwan, Japan, Canada" t:marking_technology="Electro-photographic (EP)" t:energy_star_model_identifier="ES_1105798_AVISION INC (175217) | A5250_01022014075305_9185060" t:product_type=Scanners t:automatic_duplex_output_capable=No t:size_format=Standard t:model_name=A5250 t:brand_name=Avision t:pd_id=2199990 m:power_in_sleep_w=2.17 m:power_in_standby_w=0.28 m:monochrome_product_speed_ipm_or_mppm=120 m:default_delay_time_to_sleep_minutes=15

series e:t2v6-g4nf d:2011-07-30T00:00:00.000Z t:energy_star_partner="Avision Inc." t:model_number=A58 t:functional_adders="Wired > 20 MHz and < 500 MHz - USB 2.x, None" t:markets="United States, Australia, New Zealand, Switzerland, Europe, Taiwan, Japan, Canada" t:marking_technology="Electro-photographic (EP)" t:energy_star_model_identifier="ES_1105798_AVISION INC (175217) | A58_12122013015542_3342130" t:product_type=Scanners t:automatic_duplex_output_capable=No t:size_format=Standard t:model_name=A58 t:brand_name=Avision t:pd_id=2198365 m:power_in_sleep_w=1.06 m:power_in_standby_w=0.12 m:monochrome_product_speed_ipm_or_mppm=5 m:default_delay_time_to_sleep_minutes=2
```

## Meta Commands

```ls
metric m:monochrome_product_speed_ipm_or_mppm p:integer l:"Print Speed (ipm or mppm)" d:"The maximum claimed monochrome (black and white) speed in ipm (images per minute) and mppm (mail pieces per minute) when processing the given media." t:dataTypeName=number

metric m:typical_electricity_consumption_tec_kwh_wk p:float l:"Typical Electricity Consumption (TEC) (kWh/wk)" d:"Typical electricity consumption (measured in kilowatt-hours) during normal operation over a specified period of time. Typical Electricity Consumption (TEC) is a method of testing and comparing the energy performance of certain imaging equipment products and focuses on the typical electricity consumed by a product while in normal operation during a representative period of time. The TEC metric is a proxy for a typical weekly electricity consumption. Please note: the TEC value should be used as a way to compare products' energy consumption values under a set duty cycle and operating conditions. Actual energy consumption will differ, based on how the product is used. TEC is not applicable to all imaging equipment products." t:dataTypeName=number

metric m:typical_electricity_consumption_tec_kwh_yr p:double l:"Typical Electricity Consumption (TEC) (kWh/yr)" t:dataTypeName=number

metric m:power_in_sleep_w p:float l:"Power in Sleep (Watts)" d:"The power measured when a product enters Sleep Mode, either automatically after a period of inactivity, in response to user manual action, or in response to external electrical stimulus." t:dataTypeName=number

metric m:power_in_standby_w p:float l:"Power in Standby (Watts)" d:"The power measured when the product is in the lowest power consumption state which cannot be switched off by the user and that may persist for an indefinite time when the product is connected to the main electricity supply and used in accordance with the manufacturer’s instructions." t:dataTypeName=number

metric m:default_delay_time_to_sleep_minutes p:integer l:"Default Delay Time to Sleep (minutes)" d:"The time set by the manufacturer prior to shipping that determines when the product will enter a lower-power Mode (e.g., Sleep, Auto-off) following completion of its primary function." t:dataTypeName=number

metric m:print_copy_time_from_ready_state_s p:double l:"Print/Copy Time from Ready State (s)" d:"The time between job initiation and first sheet exiting the Imaging Equipment product, with the measurement taken after the product has been powered on and has indicated it is in Ready State." t:dataTypeName=number

metric m:print_copy_time_from_sleep_mode_s p:double l:"Print/Copy Time from Sleep Mode (s)" d:"The time between job initiation and first sheet exiting the Imaging Equipment product, with the measurement taken after the product has been in Sleep Mode for 1 hour." t:dataTypeName=number

metric m:print_copy_time_from_previous_job_s p:double l:"Print/Copy Time from Previous Job (s)" d:"The time between job initiation and first sheet exiting the Imaging Equipment product with the measurement taken 15 minutes after the start of a previous job." t:dataTypeName=number

metric m:dfe_typical_electricity_consumption_tec_kwh_wk p:float l:"DFE Typical Electricity Consumption (TEC) (kWh/wk)" d:"The DFE Typical Electricity Consumption (TECDFE) metric assumes 9 hours in Ready State five days a week and the remainder in Sleep Mode. DFEs without a Sleep Mode are assumed to be in Ready State 168 hours per week." t:dataTypeName=number

metric m:dfe_typical_electricity_consumption_tec_kwh_yr p:float l:"DFE Typical Electricity Consumption (TEC) (kWh/yr)" d:"Annualized TEC of the DFE." t:dataTypeName=number

metric m:dfe_ready_state_power_w p:double l:"DFE Ready State Power (Watts)" d:"The average power of the DFE recorded while the main Imaging Equipment product is in Ready State." t:dataTypeName=number

metric m:dfe_sleep_mode_power_w p:float l:"DFE Sleep Mode Power (Watts)" d:"The average power of the DFE recorded while the main Imaging Equipment product is in Sleep Mode, applicable to DFEs with network-capable Sleep Modes." t:dataTypeName=number

entity e:t2v6-g4nf l:"ENERGY STAR Certified Imaging Equipment" t:url=https://data.energystar.gov/api/views/t2v6-g4nf

property e:t2v6-g4nf t:meta.view v:id=t2v6-g4nf v:category="Active Specifications" v:averageRating=0 v:name="ENERGY STAR Certified Imaging Equipment"

property e:t2v6-g4nf t:meta.view.owner v:id=guxy-scz5 v:screenName=ESddas v:displayName=ESddas

property e:t2v6-g4nf t:meta.view.tableauthor v:id=guxy-scz5 v:screenName=ESddas v:roleName=publisher v:displayName=ESddas

property e:t2v6-g4nf t:meta.view.metadata.custom_fields.common_core v:Publisher="U.S. Environmental Protection Agency" v:License=https://edg.epa.gov/EPA_Data_License.html v:Contact_Name="Kathleen Vokes" v:Bureau_Code=020:00 v:Program_Code=020:033
```

## Top Records

```ls
| pd_id   | energy_star_partner | brand_name | model_name | model_number | additional_model_information                       | product_type | size_format | marking_technology        | color_capability | monochrome_product_speed_ipm_or_mppm | automatic_duplex_output_capable | typical_electricity_consumption_tec_kwh_wk | typical_electricity_consumption_tec_kwh_yr | power_in_sleep_w | power_in_standby_w | default_delay_time_to_sleep_minutes | print_copy_time_from_ready_state_s | print_copy_time_from_sleep_mode_s | print_copy_time_from_previous_job_s | digital_front_end_dfe_manufacturer | dfe_model_number | dfe_typical_electricity_consumption_tec_kwh_wk | dfe_typical_electricity_consumption_tec_kwh_yr | dfe_ready_state_power_w | dfe_sleep_mode_power_w | functional_adders                            | date_available_on_market | date_qualified      | markets                                                                           | energy_star_model_identifier                                   | 
| ======= | =================== | ========== | ========== | ============ | ================================================== | ============ | =========== | ========================= | ================ | ==================================== | =============================== | ========================================== | ========================================== | ================ | ================== | =================================== | ================================== | ================================= | =================================== | ================================== | ================ | ============================================== | ============================================== | ======================= | ====================== | ============================================ | ======================== | =================== | ================================================================================= | ============================================================== | 
| 2199989 | Avision Inc.        | Avision    | A5150      | A5150        |                                                    | Scanners     | Standard    | Electro-photographic (EP) |                  | 120                                  | No                              |                                            |                                            | 2.17             | 0.28               | 15                                  |                                    |                                   |                                     |                                    |                  |                                                |                                                |                         |                        | Wired > 20 MHz and < 500 MHz - USB 2.x, None | 2011-11-15T00:00:00      | 2013-12-24T00:00:00 | United States, Australia, New Zealand, Switzerland, Europe, Taiwan, Japan, Canada | ES_1105798_AVISION INC (175217) | A5150_01022014075231_9151078 | 
| 2199990 | Avision Inc.        | Avision    | A5250      | A5250        |                                                    | Scanners     | Standard    | Electro-photographic (EP) |                  | 120                                  | No                              |                                            |                                            | 2.17             | 0.28               | 15                                  |                                    |                                   |                                     |                                    |                  |                                                |                                                |                         |                        | Wired > 20 MHz and < 500 MHz - USB 2.x, None | 2011-11-15T00:00:00      | 2013-12-24T00:00:00 | United States, Australia, New Zealand, Switzerland, Europe, Taiwan, Japan, Canada | ES_1105798_AVISION INC (175217) | A5250_01022014075305_9185060 | 
| 2198365 | Avision Inc.        | Avision    | A58        | A58          |                                                    | Scanners     | Standard    | Electro-photographic (EP) |                  | 5                                    | No                              |                                            |                                            | 1.06             | 0.12               | 2                                   |                                    |                                   |                                     |                                    |                  |                                                |                                                |                         |                        | Wired > 20 MHz and < 500 MHz - USB 2.x, None | 2011-07-30T00:00:00      | 2013-12-06T00:00:00 | United States, Australia, New Zealand, Switzerland, Europe, Taiwan, Japan, Canada | ES_1105798_AVISION INC (175217) | A58_12122013015542_3342130   | 
| 2195525 | Avision Inc.        | Avision    | A620       | A620         |                                                    | Scanners     | Standard    | Electro-photographic (EP) |                  | 40                                   | No                              |                                            |                                            | 1.95             | 0.24               | 15                                  |                                    |                                   |                                     |                                    |                  |                                                |                                                |                         |                        | Wired > 20 MHz and < 500 MHz - USB 2.x, None | 2012-06-01T00:00:00      | 2013-11-22T00:00:00 | United States, Australia, New Zealand, Switzerland, Europe, Taiwan, Japan, Canada | ES_1105798_AVISION INC (175217) | A620_11262013101444_0884560  | 
| 2195526 | Avision Inc.        | Avision    | A640       | A640         |                                                    | Scanners     | Standard    | Electro-photographic (EP) |                  | 40                                   | No                              |                                            |                                            | 1.95             | 0.24               | 15                                  |                                    |                                   |                                     |                                    |                  |                                                |                                                |                         |                        | Wired > 20 MHz and < 500 MHz - USB 2.x, None | 2012-06-01T00:00:00      | 2013-11-22T00:00:00 | United States, Australia, New Zealand, Switzerland, Europe, Taiwan, Japan, Canada | ES_1105798_AVISION INC (175217) | A640_11262013103348_2028550  | 
| 2221816 | Avision Inc.        | Avision    | AD125      | AD125        | FF-1402B,FF-1402B,                                 | Scanners     | Standard    | Electro-photographic (EP) |                  | 50                                   | No                              |                                            |                                            | 2.35             | 0.33               | 15                                  |                                    |                                   |                                     |                                    |                  |                                                |                                                |                         |                        | Wired > 20 MHz and < 500 MHz - USB 2.x, None | 2014-09-01T00:00:00      | 2014-10-02T00:00:00 | United States, Australia, New Zealand, Switzerland, Europe, Taiwan, Japan, Canada | ES_25313_AD125_10082014022041_4841303                          | 
| 2247903 | Avision Inc.        | Avision    | AD125S     | AD125S       | AD125S,AD125S,; FF-1410B,FF-1410B,                 | Scanners     | Standard    | N/A (Scanner)             |                  | 25                                   | No                              |                                            |                                            | 1.74             | 0.37               | 15                                  |                                    |                                   |                                     |                                    |                  |                                                |                                                |                         |                        | Wired > 20 MHz and < 500 MHz - USB 2.x, None | 2015-09-15T00:00:00      | 2015-09-10T00:00:00 | United States, Australia, New Zealand, Switzerland, Europe, Taiwan, Japan, Canada | ES_25313_AD125S_09142015101737_5857103                         | 
| 2271887 | Avision Inc.        | Avision    | AD215      | AD215        | AD215U,AD215U,; AD215W,AD215W,; FL-1507B,FL-1507B, | Scanners     | Standard    | N/A (Scanner)             |                  | 40                                   | No                              |                                            |                                            | 2.59             | 0.25               | 15                                  |                                    |                                   |                                     |                                    |                  |                                                |                                                |                         |                        | Wired > 20 MHz and < 500 MHz - USB 2.x, None | 2016-07-15T00:00:00      | 2016-07-07T00:00:00 | United States, Australia, New Zealand, Switzerland, Europe, Taiwan, Japan, Canada | ES_25313_AD215_07072016060812_1692587                          | 
| 2272078 | Avision Inc.        | Avision    | AD215L     | AD215L       | FL-1513B,FL-1513B,                                 | Scanners     | Standard    | N/A (Scanner)             |                  | 40                                   | No                              |                                            |                                            | 2.44             | 0.37               | 15                                  |                                    |                                   |                                     |                                    |                  |                                                |                                                |                         |                        | Wired > 20 MHz and < 500 MHz - USB 2.x, None | 2016-07-15T00:00:00      | 2016-07-07T00:00:00 | United States, Australia, New Zealand, Switzerland, Europe, Taiwan, Japan, Canada | ES_25313_AD215L_07112016022953_4193832                         | 
| 2214730 | Avision Inc.        | Avision    | AD240      | AD240        |                                                    | Scanners     | Standard    | Electro-photographic (EP) |                  | 60                                   | No                              |                                            |                                            | 2.44             | 0.32               | 15                                  |                                    |                                   |                                     |                                    |                  |                                                |                                                |                         |                        | Wired > 20 MHz and < 500 MHz - USB 2.x, None | 2014-08-01T00:00:00      | 2014-07-09T00:00:00 | United States, Australia, New Zealand, Switzerland, Europe, Taiwan, Japan, Canada | ES_25313_AD240_07102014005550_3750327                          | 
```