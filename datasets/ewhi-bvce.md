# ENERGY STAR Certified Audio Video

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/energy-star-certified-audio-video) |
| Metadata | [Link](https://data.energystar.gov/api/views/ewhi-bvce) |
| Data: JSON | [100 Rows](https://data.energystar.gov/api/views/ewhi-bvce/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.energystar.gov/api/views/ewhi-bvce/rows.csv?max_rows=100) |
| Host | data.energystar.gov |
| Id | ewhi-bvce |
| Name | ENERGY STAR Certified Audio Video |
| Attribution | U.S. Environmental Protection Agency |
| Category | Active Specifications |
| Tags | active specification, consumer electronics |
| Created | 2013-06-03T13:35:14Z |
| Publication Date | 2016-08-19T17:48:32Z |

## Description

Certified models meet all ENERGY STAR requirements as listed in the Version 3.0 ENERGY STAR Program Requirements for Audio Video Equipment that are effective as of May 1, 2013. A detailed listing of key efficiency criteria are available at http://www.energystar.gov/index.cfm?c=audio_dvd.pr_crit_audio_dvd

## Columns

```ls
| Included | Schema Type    | Field Name                                                   | Name                                                           | Data Type     | Render Type   |
| ======== | ============== | ============================================================ | ============================================================== | ============= | ============= |
| Yes      | series tag     | pd_id                                                        | ENERGY STAR Unique ID                                          | text          | number        |
| Yes      | series tag     | energy_star_partner                                          | ENERGY STAR Partner                                            | text          | text          |
| Yes      | series tag     | brand_name                                                   | Brand Name                                                     | text          | text          |
| Yes      | series tag     | model_name                                                   | Model Name                                                     | text          | text          |
| Yes      | series tag     | model_number                                                 | Model Number                                                   | text          | text          |
| Yes      | series tag     | additional_model_information                                 | Additional Model Information                                   | text          | text          |
| Yes      | series tag     | product_type                                                 | Product Type                                                   | text          | text          |
| Yes      | series tag     | amplifier_channels                                           | Amplifier Channels                                             | text          | text          |
| Yes      | series tag     | video_player_type                                            | Video Player Type                                              | text          | text          |
| Yes      | series tag     | tuner_included                                               | Tuner Included                                                 | text          | text          |
| Yes      | series tag     | connected_technology                                         | Connected Technology                                           | text          | text          |
| Yes      | numeric metric | default_auto_power_down_apd_timing_minutes                   | Default Auto Power Down (APD) Timing (min.)                    | number        | number        |
| Yes      | numeric metric | average_power_consumption_2_minutes_before_apd_watts         | Average Power Consumption 2 Minutes Before APD (Watts)         | number        | number        |
| Yes      | numeric metric | average_power_consumption_2_minutes_after_apd_watts          | Average Power Consumption 2 Minutes After APD (Watts)          | number        | number        |
| Yes      | numeric metric | idle_state_power_consumption_watts                           | Energy Use (Idle) (Watts)                                      | number        | number        |
| Yes      | numeric metric | sleep_mode_power_consumption_watts                           | Energy Use (Sleep Mode) (Watts)                                | number        | number        |
| Yes      | numeric metric | video_playback_power_consumption_watts                       | Energy Use (Video Playback) (Watts)                            | number        | number        |
| Yes      | numeric metric | audio_playback_power_consumption_watts                       | Energy Use (Audio Playback) (Watts)                            | number        | number        |
| Yes      | series tag     | is_amplifier_consumer_or_commercial                          | Is Amplifier Consumer or Commercial?                           | text          | text          |
| Yes      | numeric metric | amplifier_input_power_at_1_8_maximum_undistorted_power_watts | Amplifier Input Power at 1/8 Maximum Undistorted Power (Watts) | number        | number        |
| Yes      | numeric metric | on_mode_amplifier_efficiency                                 | Amplifier Efficiency %                                         | percent       | percent       |
| Yes      | numeric metric | total_idle_state_allowance_w                                 | Total Idle State Allowance (W)                                 | number        | text          |
| Yes      | numeric metric | total_sleep_mode_allowance_w                                 | Total Sleep Mode Allowance (W)                                 | number        | number        |
| Yes      | time           | date_available_on_market                                     | Date Available On Market                                       | calendar_date | calendar_date |
| No       |                | date_qualified                                               | Date Certified                                                 | calendar_date | calendar_date |
| Yes      | series tag     | markets                                                      | Markets                                                        | text          | text          |
| Yes      | series tag     | energy_star_model_identifier                                 | CB Model Identifier                                            | text          | text          |
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
series e:ewhi-bvce d:2016-10-01T00:00:00.000Z t:energy_star_partner="Extron Electronics" t:model_number="XPA 1002-100V" t:video_player_type=N/A t:amplifier_channels=2 t:markets="United States, Australia, New Zealand, Switzerland, Europe, Taiwan, Japan, Canada" t:energy_star_model_identifier="ES_1041015.0_XPA 1002-100V_09212016171843_8323718" t:total_idle_state_allowance_w=N/A t:product_type="Audio Amplifier - Full Spectrum" t:connected_technology=N/A t:tuner_included=No t:model_name="XPA 1002-100V" t:brand_name=Extron t:pd_id=2279804 t:is_amplifier_consumer_or_commercial=Commercial m:idle_state_power_consumption_watts=9 m:average_power_consumption_2_minutes_after_apd_watts=0.4 m:average_power_consumption_2_minutes_before_apd_watts=8.9 m:default_auto_power_down_apd_timing_minutes=28 m:on_mode_amplifier_efficiency=62 m:sleep_mode_power_consumption_watts=0.4 m:amplifier_input_power_at_1_8_maximum_undistorted_power_watts=46.7 m:total_sleep_mode_allowance_w=1

series e:ewhi-bvce d:2016-03-15T00:00:00.000Z t:energy_star_partner="Extron Electronics" t:model_number="XPA 1002-70V" t:video_player_type=N/A t:amplifier_channels=2 t:markets="United States, Australia, New Zealand, Switzerland, Europe, Taiwan, Japan, Canada" t:energy_star_model_identifier="ES_1041015.0_XPA 1002-70V_03172016182352_9032228" t:total_idle_state_allowance_w=N/A t:product_type="Audio Amplifier - Full Spectrum" t:connected_technology=N/A t:tuner_included=No t:model_name="XPA 1002-70V" t:brand_name=Extron t:pd_id=2262547 t:is_amplifier_consumer_or_commercial=Commercial m:idle_state_power_consumption_watts=12.9 m:average_power_consumption_2_minutes_after_apd_watts=0.5 m:average_power_consumption_2_minutes_before_apd_watts=12.9 m:default_auto_power_down_apd_timing_minutes=27 m:on_mode_amplifier_efficiency=60 m:sleep_mode_power_consumption_watts=0.5 m:amplifier_input_power_at_1_8_maximum_undistorted_power_watts=43.7 m:total_sleep_mode_allowance_w=1

series e:ewhi-bvce d:2010-07-15T00:00:00.000Z t:amplifier_channels=2 t:markets="United States, Australia, New Zealand, Switzerland, Europe, Taiwan, Japan, Canada" t:product_type="Audio Amplifier - Full Spectrum" t:brand_name=Extron t:model_name="XPA 1002 PLUS" t:tuner_included=No t:is_amplifier_consumer_or_commercial=Commercial t:pd_id=2216146 t:energy_star_partner="Extron Electronics" t:additional_model_information=",XPA 1002," t:model_number="XPA 1002 PLUS" t:video_player_type=N/A t:total_idle_state_allowance_w=N/A t:energy_star_model_identifier="ES_1041015_EXTRON ELECTRONICS (156892) | XPA 1002 PLUS_11182013055128_3888054" t:connected_technology=N/A m:idle_state_power_consumption_watts=14.6 m:average_power_consumption_2_minutes_after_apd_watts=0.3 m:video_playback_power_consumption_watts=14.6 m:average_power_consumption_2_minutes_before_apd_watts=14.7 m:default_auto_power_down_apd_timing_minutes=26 m:on_mode_amplifier_efficiency=53 m:sleep_mode_power_consumption_watts=0.4 m:amplifier_input_power_at_1_8_maximum_undistorted_power_watts=51.2 m:total_sleep_mode_allowance_w=1 m:audio_playback_power_consumption_watts=0.4
```

## Meta Commands

```ls
metric m:default_auto_power_down_apd_timing_minutes p:integer l:"Default Auto Power Down (APD) Timing (min.)" d:"The predetermined time in minutes after which the device automatically switches from On Mode to Sleep Mode." t:dataTypeName=number

metric m:average_power_consumption_2_minutes_before_apd_watts p:float l:"Average Power Consumption 2 Minutes Before APD (Watts)" d:"Required if APD is enabled by default." t:dataTypeName=number

metric m:average_power_consumption_2_minutes_after_apd_watts p:float l:"Average Power Consumption 2 Minutes After APD (Watts)" d:"Required if APD is enabled by default." t:dataTypeName=number

metric m:idle_state_power_consumption_watts p:float l:"Energy Use (Idle) (Watts)" d:"A state within On Mode in which a product is not performing a Primary Function and no content is actively being delivered to the end-user." t:dataTypeName=number

metric m:sleep_mode_power_consumption_watts p:float l:"Energy Use (Sleep Mode) (Watts)" d:"The condition where the product is connected to a power source, produces neither sound nor picture, neither transmits nor receives program information and/or data (excluding data transmitted to change the unit's condition from Sleep Mode to On Mode), and is waiting to be switched to On Mode by a direct or indirect signal from the consumer (e.g., with the remote control)." t:dataTypeName=number

metric m:video_playback_power_consumption_watts p:float l:"Energy Use (Video Playback) (Watts)" d:"The average On Mode power during video playback. For High Definition (HD) devices, this is the average of the power when playing HD and Standard Definition (SD) content." t:dataTypeName=number

metric m:audio_playback_power_consumption_watts p:float l:"Energy Use (Audio Playback) (Watts)" d:"The average On Mode power during audio playback." t:dataTypeName=number

metric m:amplifier_input_power_at_1_8_maximum_undistorted_power_watts p:double l:"Amplifier Input Power at 1/8 Maximum Undistorted Power (Watts)" d:"The input power at which the efficiency of an amplifier is tested, equal to 1/8 of the power at which the total harmonic distortion of all the channels is 1% or greater." t:dataTypeName=number

metric m:on_mode_amplifier_efficiency p:float l:"Amplifier Efficiency %" d:"The efficiency of the amplifier at 1/8 Maximum Undistorted Power. Excludes the audio playback power of any embedded disc players used during the test." t:dataTypeName=percent

metric m:total_sleep_mode_allowance_w p:integer l:"Total Sleep Mode Allowance (W)" t:dataTypeName=number

entity e:ewhi-bvce l:"ENERGY STAR Certified Audio Video" t:attribution="U.S. Environmental Protection Agency" t:url=https://data.energystar.gov/api/views/ewhi-bvce

property e:ewhi-bvce t:meta.view v:id=ewhi-bvce v:category="Active Specifications" v:averageRating=0 v:name="ENERGY STAR Certified Audio Video" v:attribution="U.S. Environmental Protection Agency"

property e:ewhi-bvce t:meta.view.owner v:id=guxy-scz5 v:screenName=ESddas v:lastNotificationSeenAt=1491492552 v:displayName=ESddas

property e:ewhi-bvce t:meta.view.tableauthor v:id=guxy-scz5 v:screenName=ESddas v:roleName=publisher v:lastNotificationSeenAt=1491492552 v:displayName=ESddas

property e:ewhi-bvce t:meta.view.metadata.custom_fields.common_core v:Publisher="U.S. Environmental Protection Agency" v:License=https://edg.epa.gov/EPA_Data_License.html v:Contact_Name="Kathleen Vokes" v:Bureau_Code=020:00 v:Program_Code=020:033
```

## Top Records

```ls
| pd_id   | energy_star_partner | brand_name | model_name      | model_number   | additional_model_information | product_type                    | amplifier_channels | video_player_type | tuner_included | connected_technology | default_auto_power_down_apd_timing_minutes | average_power_consumption_2_minutes_before_apd_watts | average_power_consumption_2_minutes_after_apd_watts | idle_state_power_consumption_watts | sleep_mode_power_consumption_watts | video_playback_power_consumption_watts | audio_playback_power_consumption_watts | is_amplifier_consumer_or_commercial | amplifier_input_power_at_1_8_maximum_undistorted_power_watts | on_mode_amplifier_efficiency | total_idle_state_allowance_w | total_sleep_mode_allowance_w | date_available_on_market | date_qualified      | markets                                                                           | energy_star_model_identifier                                                  | 
| ======= | =================== | ========== | =============== | ============== | ============================ | =============================== | ================== | ================= | ============== | ==================== | ========================================== | ==================================================== | =================================================== | ================================== | ================================== | ====================================== | ====================================== | =================================== | ============================================================ | ============================ | ============================ | ============================ | ======================== | =================== | ================================================================================= | ============================================================================= | 
| 2279804 | Extron Electronics  | Extron     | XPA 1002-100V   | XPA 1002-100V  |                              | Audio Amplifier - Full Spectrum | 2                  | N/A               | No             | N/A                  | 28                                         | 8.9                                                  | 0.4                                                 | 9                                  | 0.4                                |                                        |                                        | Commercial                          | 46.7                                                         | 62.00                        | N/A                          | 1                            | 2016-10-01T00:00:00      | 2016-09-21T00:00:00 | United States, Australia, New Zealand, Switzerland, Europe, Taiwan, Japan, Canada | ES_1041015.0_XPA 1002-100V_09212016171843_8323718                             | 
| 2262547 | Extron Electronics  | Extron     | XPA 1002-70V    | XPA 1002-70V   |                              | Audio Amplifier - Full Spectrum | 2                  | N/A               | No             | N/A                  | 27                                         | 12.9                                                 | 0.5                                                 | 12.9                               | 0.5                                |                                        |                                        | Commercial                          | 43.7                                                         | 60.00                        | N/A                          | 1                            | 2016-03-15T00:00:00      | 2016-03-17T00:00:00 | United States, Australia, New Zealand, Switzerland, Europe, Taiwan, Japan, Canada | ES_1041015.0_XPA 1002-70V_03172016182352_9032228                              | 
| 2216146 | Extron Electronics  | Extron     | XPA 1002 PLUS   | XPA 1002 PLUS  | ,XPA 1002,                   | Audio Amplifier - Full Spectrum | 2                  | N/A               | No             | N/A                  | 26                                         | 14.7                                                 | 0.3                                                 | 14.6                               | 0.4                                | 14.6                                   | 0.4                                    | Commercial                          | 51.2                                                         | 53.00                        | N/A                          | 1                            | 2010-07-15T00:00:00      | 2014-07-17T00:00:00 | United States, Australia, New Zealand, Switzerland, Europe, Taiwan, Japan, Canada | ES_1041015_EXTRON ELECTRONICS (156892) | XPA 1002 PLUS_11182013055128_3888054 | 
| 2180872 | Extron Electronics  | Extron     | Audio Amplifier | XPA 2001-100V  |                              | Audio Amplifier - Full Spectrum | 1                  | N/A               | No             | N/A                  | 22                                         | 12.5                                                 | 0.3                                                 | 12.5                               | 0.3                                |                                        |                                        | Commercial                          | 45.7                                                         | 78.00                        | N/A                          | 1                            | 2013-05-01T00:00:00      | 2013-05-10T00:00:00 | United States, Australia, New Zealand, Switzerland, Europe, Taiwan, Japan, Canada | ES_1105798_EXTRON ELECTRONICS (16856) | XPA 2001-100V_05132013232806_7686504  | 
| 2180873 | Extron Electronics  | Extron     | Audio Amplifier | XPA 2001-70V   |                              | Audio Amplifier - Full Spectrum | 1                  | N/A               | No             | N/A                  | 23                                         | 11.7                                                 | 0.3                                                 | 11.6                               | 0.3                                |                                        |                                        | Commercial                          | 46.3                                                         | 58.00                        | N/A                          | 1                            | 2013-05-01T00:00:00      | 2013-05-10T00:00:00 | United States, Australia, New Zealand, Switzerland, Europe, Taiwan, Japan, Canada | ES_1105798_EXTRON ELECTRONICS (16856) | XPA 2001-70V_05132013232816_7696719   | 
| 2180874 | Extron Electronics  | Extron     | Audio Amplifier | XPA 2002-100V  |                              | Audio Amplifier - Full Spectrum | 2                  | N/A               | No             | N/A                  | 25                                         | 25.8                                                 | 0.9                                                 | 24.2                               | 0.4                                |                                        |                                        | Commercial                          | 92.3                                                         | 59.00                        | N/A                          | 1                            | 2011-05-12T00:00:00      | 2013-05-10T00:00:00 | United States, Australia, New Zealand, Switzerland, Europe, Taiwan, Japan, Canada | ES_1105798_EXTRON ELECTRONICS (16856) | XPA 2002-100V_05132013221520_3320702  | 
| 2180875 | Extron Electronics  | Extron     | Audio Amplifier | XPA 2002-70V   |                              | Other                           | 2                  | N/A               | No             | N/A                  | 23                                         | 20.5                                                 | 0.5                                                 | 20.6                               | 0.5                                |                                        |                                        | Commercial                          | 88.4                                                         | 61.00                        | N/A                          | 1                            | 2013-05-01T00:00:00      | 2013-05-10T00:00:00 | United States, Australia, New Zealand, Switzerland, Europe, Taiwan, Japan, Canada | ES_1105798_EXTRON ELECTRONICS (16856) | XPA 2002-70V_05132013221532_3332961   | 
| 2180879 | Extron Electronics  | Extron     | Audio Amplifier | XPA 2003C-100V |                              | Audio Amplifier - Full Spectrum | 3                  | N/A               | No             | N/A                  | 23                                         | 28.9                                                 | 0.4                                                 | 29.8                               | 0.5                                |                                        |                                        | Commercial                          | 122                                                          | 60.00                        | N/A                          | 1                            | 2013-05-14T00:00:00      | 2013-05-10T00:00:00 | United States, Australia, New Zealand, Switzerland, Europe, Taiwan, Japan, Canada | ES_1105798_EXTRON ELECTRONICS (16856) | XPA 2003C-100V_05132013233013_7813235 | 
| 2180876 | Extron Electronics  | Extron     | Audio Amplifier | XPA 2003C-70V  |                              | Audio Amplifier - Full Spectrum | 3                  | N/A               | No             | N/A                  | 24                                         | 31.1                                                 | 0.5                                                 | 31.1                               | 0.5                                |                                        |                                        | Commercial                          | 119.5                                                        | 58.00                        | N/A                          | 1                            | 2013-05-01T00:00:00      | 2013-05-10T00:00:00 | United States, Australia, New Zealand, Switzerland, Europe, Taiwan, Japan, Canada | ES_1105798_EXTRON ELECTRONICS (16856) | XPA 2003C-70V_05132013233025_7825496  | 
| 2180877 | Extron Electronics  | Extron     | Audio Amplifier | XPA 2004       |                              | Audio Amplifier - Full Spectrum | 4                  | N/A               | No             | N/A                  | 24                                         | 28.7                                                 | 0.5                                                 | 28.7                               | 0.5                                |                                        |                                        | Commercial                          | 150                                                          | 65.00                        | N/A                          | 1                            | 2010-10-15T00:00:00      | 2013-05-10T00:00:00 | United States, Australia, New Zealand, Switzerland, Europe, Taiwan, Japan, Canada | ES_1105798_EXTRON ELECTRONICS (16856) | XPA 2004_05132013233151_7911931       | 
```