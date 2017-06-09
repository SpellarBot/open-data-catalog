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
series e:t2v6-g4nf d:2014-09-01T00:00:00.000Z t:energy_star_partner="Avision Inc." t:model_number=AD240I t:functional_adders="Wired > 20 MHz and < 500 MHz - USB 2.x, None" t:markets="United States, Australia, New Zealand, Switzerland, Europe, Taiwan, Japan, Canada" t:marking_technology="N/A (Scanner)" t:energy_star_model_identifier=ES_25313_AD240I_07062015033309_3589281 t:product_type=Scanners t:automatic_duplex_output_capable=No t:size_format=Standard t:model_name=AD240I t:brand_name=Avision t:pd_id=2245702 m:power_in_sleep_w=2.44 m:power_in_standby_w=0.32 m:monochrome_product_speed_ipm_or_mppm=60 m:default_delay_time_to_sleep_minutes=15

series e:t2v6-g4nf d:2016-08-01T00:00:00.000Z t:energy_star_partner="Avision Inc." t:additional_model_information=FL-1406B,FL-1406B, t:model_number=AD240S t:functional_adders="Wired > 20 MHz and < 500 MHz - USB 2.x, None" t:markets="United States, Australia, New Zealand, Switzerland, Europe, Taiwan, Japan, Canada" t:marking_technology="N/A (Scanner)" t:energy_star_model_identifier=ES_25313_AD240S_08122016034130_3290716 t:product_type=Scanners t:automatic_duplex_output_capable=No t:size_format=Standard t:model_name=AD240S t:brand_name=Avision t:pd_id=2274718 m:power_in_sleep_w=1.71 m:power_in_standby_w=0.17 m:monochrome_product_speed_ipm_or_mppm=60 m:default_delay_time_to_sleep_minutes=15

series e:t2v6-g4nf d:2017-04-15T00:00:00.000Z t:energy_star_partner="Avision Inc." t:additional_model_information=FL-1603B,FL-1603B, t:model_number=AD240U t:functional_adders="Wired > 20 MHz and < 500 MHz - USB 2.x, None" t:markets="United States, Australia, New Zealand, Switzerland, Europe, Taiwan, Japan, Canada" t:marking_technology="N/A (Scanner)" t:energy_star_model_identifier=ES_25313_AD240U_03312017014635_4795643 t:product_type=Scanners t:automatic_duplex_output_capable=No t:size_format=Standard t:model_name=AD240U t:brand_name=Avision t:pd_id=2293400 m:power_in_sleep_w=2.44 m:power_in_standby_w=0.32 m:monochrome_product_speed_ipm_or_mppm=60 m:default_delay_time_to_sleep_minutes=15
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

property e:t2v6-g4nf t:meta.view d:2017-06-09T13:55:29.213Z v:id=t2v6-g4nf v:category="Active Specifications" v:averageRating=0 v:name="ENERGY STAR Certified Imaging Equipment"

property e:t2v6-g4nf t:meta.view.owner d:2017-06-09T13:55:29.213Z v:id=guxy-scz5 v:screenName=ESddas v:lastNotificationSeenAt=1493126780 v:displayName=ESddas

property e:t2v6-g4nf t:meta.view.tableauthor d:2017-06-09T13:55:29.213Z v:id=guxy-scz5 v:screenName=ESddas v:roleName=publisher v:lastNotificationSeenAt=1493126780 v:displayName=ESddas

property e:t2v6-g4nf t:meta.view.metadata.custom_fields.common_core d:2017-06-09T13:55:29.213Z v:Publisher="U.S. Environmental Protection Agency" v:License=https://edg.epa.gov/EPA_Data_License.html v:Contact_Name="Kathleen Vokes" v:Bureau_Code=020:00 v:Program_Code=020:033
```

## Top Records

```ls
| pd_id   | energy_star_partner | brand_name | model_name | model_number | additional_model_information                                                         | product_type | size_format | marking_technology        | color_capability | monochrome_product_speed_ipm_or_mppm | automatic_duplex_output_capable | typical_electricity_consumption_tec_kwh_wk | typical_electricity_consumption_tec_kwh_yr | power_in_sleep_w | power_in_standby_w | default_delay_time_to_sleep_minutes | print_copy_time_from_ready_state_s | print_copy_time_from_sleep_mode_s | print_copy_time_from_previous_job_s | digital_front_end_dfe_manufacturer | dfe_model_number | dfe_typical_electricity_consumption_tec_kwh_wk | dfe_typical_electricity_consumption_tec_kwh_yr | dfe_ready_state_power_w | dfe_sleep_mode_power_w | functional_adders                            | date_available_on_market | date_qualified      | markets                                                                           | energy_star_model_identifier            | 
| ======= | =================== | ========== | ========== | ============ | ==================================================================================== | ============ | =========== | ========================= | ================ | ==================================== | =============================== | ========================================== | ========================================== | ================ | ================== | =================================== | ================================== | ================================= | =================================== | ================================== | ================ | ============================================== | ============================================== | ======================= | ====================== | ============================================ | ======================== | =================== | ================================================================================= | ======================================= | 
| 2245702 | Avision Inc.        | Avision    | AD240I     | AD240I       |                                                                                      | Scanners     | Standard    | N/A (Scanner)             |                  | 60                                   | No                              |                                            |                                            | 2.44             | 0.32               | 15                                  |                                    |                                   |                                     |                                    |                  |                                                |                                                |                         |                        | Wired > 20 MHz and < 500 MHz - USB 2.x, None | 2014-09-01T00:00:00      | 2015-07-02T00:00:00 | United States, Australia, New Zealand, Switzerland, Europe, Taiwan, Japan, Canada | ES_25313_AD240I_07062015033309_3589281  | 
| 2274718 | Avision Inc.        | Avision    | AD240S     | AD240S       | FL-1406B,FL-1406B,                                                                   | Scanners     | Standard    | N/A (Scanner)             |                  | 60                                   | No                              |                                            |                                            | 1.71             | 0.17               | 15                                  |                                    |                                   |                                     |                                    |                  |                                                |                                                |                         |                        | Wired > 20 MHz and < 500 MHz - USB 2.x, None | 2016-08-01T00:00:00      | 2016-08-05T00:00:00 | United States, Australia, New Zealand, Switzerland, Europe, Taiwan, Japan, Canada | ES_25313_AD240S_08122016034130_3290716  | 
| 2293400 | Avision Inc.        | Avision    | AD240U     | AD240U       | FL-1603B,FL-1603B,                                                                   | Scanners     | Standard    | N/A (Scanner)             |                  | 60                                   | No                              |                                            |                                            | 2.44             | 0.32               | 15                                  |                                    |                                   |                                     |                                    |                  |                                                |                                                |                         |                        | Wired > 20 MHz and < 500 MHz - USB 2.x, None | 2017-04-15T00:00:00      | 2017-03-28T00:00:00 | United States, Australia, New Zealand, Switzerland, Europe, Taiwan, Japan, Canada | ES_25313_AD240U_03312017014635_4795643  | 
| 2246392 | Avision Inc.        | Avision    | AD250      | AD250        | AD250,AD250,; AD250I,AD250I,; FL-1501B,FL-1501B,                                     | Scanners     | Standard    | N/A (Scanner)             |                  | 80                                   | No                              |                                            |                                            | 1.43             | 0.23               | 15                                  |                                    |                                   |                                     |                                    |                  |                                                |                                                |                         |                        | Wired > 20 MHz and < 500 MHz - USB 2.x, None | 2015-07-24T00:00:00      | 2015-08-24T00:00:00 | United States, Australia, New Zealand, Switzerland, Europe, Taiwan, Japan, Canada | ES_25313_AD250_08242015034114_7674607   | 
| 2246109 | Avision Inc.        | Avision    | AD250F     | AD250F       | AD250F,AD250F,; AD250FI,AD250FI,; DL-1409B,DL-1409B,                                 | Scanners     | Standard    | N/A (Scanner)             |                  | 80                                   | No                              |                                            |                                            | 1.62             | 0.23               | 15                                  |                                    |                                   |                                     |                                    |                  |                                                |                                                |                         |                        | Wired > 20 MHz and < 500 MHz - USB 2.x, None | 2015-07-30T00:00:00      | 2015-08-21T00:00:00 | United States, Australia, New Zealand, Switzerland, Europe, Taiwan, Japan, Canada | ES_25313_AD250F_08212015095653_1013427  | 
| 2253762 | Avision Inc.        | Avision    | AD250FB    | AD250FB      | AD250FB,AD250FB,; AD260F,AD260F,; DL-1510B,DL-1510B,; DL-1511B,DL-1511B,             | Scanners     | Standard    | N/A (Scanner)             |                  | 120                                  | No                              |                                            |                                            | 2.32             | 0.24               | 15                                  |                                    |                                   |                                     |                                    |                  |                                                |                                                |                         |                        | Wired > 20 MHz and < 500 MHz - USB 2.x, None | 2015-11-25T00:00:00      | 2015-11-26T00:00:00 | United States, Australia, New Zealand, Switzerland, Europe, Taiwan, Japan, Canada | ES_25313_AD250FB_11272015035252_6372686 | 
| 2292434 | Avision Inc.        | Avision    | AD260U     | AD260U       | AD280U,AD280U,                                                                       | Scanners     | Standard    | N/A (Scanner)             |                  | 160                                  | No                              |                                            |                                            | 1.05             | 0.23               | 15                                  |                                    |                                   |                                     |                                    |                  |                                                |                                                |                         |                        | Wired > 20 MHz and < 500 MHz - USB 2.x, None | 2017-04-30T00:00:00      | 2017-03-08T00:00:00 | United States, Australia, New Zealand, Switzerland, Europe, Taiwan, Japan, Canada | ES_25313_AD260U_03132017055335_4415982  | 
| 2217870 | Avision Inc.        | Avision    | AD280      | AD280        | AD260,AD260,; AD260I,AD260I,; AD280I,AD280I,; FL-1314B,FL-1314B,; FL-1315B,FL-1315B, | Scanners     | Standard    | Electro-photographic (EP) |                  | 160                                  | No                              |                                            |                                            | 1.05             | 0.23               | 15                                  |                                    |                                   |                                     |                                    |                  |                                                |                                                |                         |                        | Wired > 20 MHz and < 500 MHz - USB 2.x, None | 2014-09-01T00:00:00      | 2014-08-26T00:00:00 | United States, Australia, New Zealand, Switzerland, Europe, Taiwan, Japan, Canada | ES_25313_AD280_08262014062129_4089736   | 
| 2253511 | Avision Inc.        | Avision    | AD280F     | AD280F       | AD280F,AD280F,; DL-1509B,DL-1509B,                                                   | Scanners     | Standard    | N/A (Scanner)             |                  | 160                                  | No                              |                                            |                                            | 1.9              | 0.25               | 15                                  |                                    |                                   |                                     |                                    |                  |                                                |                                                |                         |                        | Wired > 500 MHz - USB 3.x, None              | 2015-11-24T00:00:00      | 2015-11-24T00:00:00 | United States, Australia, New Zealand, Switzerland, Europe, Taiwan, Japan, Canada | ES_25313_AD280F_11252015034610_3170622  | 
| 2274424 | Avision Inc.        | Avision    | AD520S     | AD520S       | AD120S,AD120S,; DF-1508B,DF-1508B,                                                   | Scanners     | Standard    | N/A (Scanner)             |                  | 20                                   | No                              |                                            |                                            | 2.56             | 0.18               | 15                                  |                                    |                                   |                                     |                                    |                  |                                                |                                                |                         |                        | Wired > 20 MHz and < 500 MHz - USB 2.x, None | 2016-08-01T00:00:00      | 2016-08-05T00:00:00 | United States, Australia, New Zealand, Switzerland, Europe, Taiwan, Japan, Canada | ES_25313_AD520S_08092016074854_8934226  | 
```