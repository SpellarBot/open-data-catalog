# ENERGY STAR Certified Pool Pumps

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/energy-star-certified-pool-pumps) |
| Metadata | [Link](https://data.energystar.gov/api/views/2ppn-v3hp) |
| Data: JSON | [100 Rows](https://data.energystar.gov/api/views/2ppn-v3hp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.energystar.gov/api/views/2ppn-v3hp/rows.csv?max_rows=100) |
| Host | data.energystar.gov |
| Id | 2ppn-v3hp |
| Name | ENERGY STAR Certified Pool Pumps |
| Category | Active Specifications |
| Tags | pool pumps |
| Created | 2013-05-02T17:24:12Z |
| Publication Date | 2016-08-23T19:42:14Z |

## Description

Certified models meet all ENERGY STAR requirements as listed in the Version 1.0 ENERGY STAR Program Requirements for Pool Pumps that are effective as of February 15, 2013. A detailed listing of key efficiency criteria are available at http://www.energystar.gov/index.cfm?c=poolpumps.pr_crit_poolpumps

## Columns

```ls
| Included | Schema Type    | Field Name                                             | Name                                                   | Data Type     | Render Type   |
| ======== | ============== | ====================================================== | ====================================================== | ============= | ============= |
| Yes      | series tag     | pd_id                                                  | ENERGY STAR Unique ID                                  | text          | number        |
| Yes      | series tag     | energy_star_partner                                    | ENERGY STAR Partner                                    | text          | text          |
| Yes      | series tag     | brand_name                                             | Brand Name                                             | text          | text          |
| Yes      | series tag     | model_name                                             | Model Name                                             | text          | text          |
| Yes      | series tag     | model_number                                           | Model Number                                           | text          | text          |
| Yes      | series tag     | additional_model_information                           | Additional Model Information                           | text          | text          |
| Yes      | series tag     | motor_design                                           | Motor Design                                           | text          | text          |
| Yes      | series tag     | speed_setting                                          | Speed Setting                                          | text          | text          |
| Yes      | numeric metric | speed_rpm                                              | Speed (RPM)                                            | number        | number        |
| Yes      | numeric metric | curve_a_flow_gpm                                       | Curve-A Flow (GPM)                                     | number        | number        |
| Yes      | numeric metric | curve_a_power_w                                        | Curve-A Power (Watts)                                  | number        | number        |
| Yes      | numeric metric | curve_a_energy_factor_gal_wh                           | Curve-A Energy Factor (gallons/Wh)                     | number        | number        |
| Yes      | numeric metric | curve_c_flow_gpm                                       | Curve-C Flow (GPM)                                     | number        | number        |
| Yes      | numeric metric | curve_c_power_w                                        | Curve-C Power (Watts)                                  | number        | number        |
| Yes      | numeric metric | curve_c_energy_factor_gal_wh                           | Curve-C Energy Factor (gallons/Wh)                     | number        | number        |
| Yes      | numeric metric | curve_b_flow_gpm                                       | Curve-B Flow (GPM)                                     | number        | number        |
| Yes      | numeric metric | curve_b_power_w                                        | Curve-B Power (Watts)                                  | number        | number        |
| Yes      | numeric metric | curve_b_energy_factor_gal_wh                           | Curve-B Energy Factor (gallons/Wh)                     | number        | number        |
| Yes      | numeric metric | standby_average_power_w                                | Standby Average Power (Watts)                          | number        | number        |
| Yes      | series tag     | motor_construction                                     | Motor Construction                                     | text          | text          |
| Yes      | series tag     | frame                                                  | Frame                                                  | text          | text          |
| Yes      | numeric metric | rated_horsepower_hp                                    | Rated Horsepower (HP)                                  | number        | number        |
| Yes      | numeric metric | service_factor                                         | Service Factor                                         | number        | number        |
| Yes      | numeric metric | total_horse_power_hp                                   | Total Horse Power (HP)                                 | number        | number        |
| Yes      | series tag     | connected_functionality                                | Connected Functionality                                | text          | text          |
| Yes      | series tag     | connects_using                                         | Connects Using                                         | text          | text          |
| Yes      | series tag     | communication_standard_application_layer               | Communication Standard Application Layer               | text          | text          |
| Yes      | series tag     | direct_on_premises_open_standard_based_interconnection | Direct on-premises Open-standard Based Interconnection | text          | text          |
| Yes      | time           | date_available_on_market                               | Date Available On Market                               | calendar_date | calendar_date |
| No       |                | date_qualified                                         | Date Qualified                                         | calendar_date | calendar_date |
| Yes      | series tag     | markets                                                | Markets                                                | text          | text          |
| Yes      | series tag     | energy_star_model_identifier                           | CB Model Identifier                                    | text          | text          |
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
series e:2ppn-v3hp d:2007-08-24T00:00:00.000Z t:energy_star_partner="Pentair Aquatic Systems" t:model_number=MPRA6YF-206L t:frame=48 t:speed_setting="Most Efficient Speed" t:markets="United States, Canada" t:energy_star_model_identifier="ES_1105798_PENTAIR WATER POOL AND SPA INC (91308) | MPRA6YF-206L_04102013021003_9803995" t:model_name=Dyna-Pro t:brand_name=STA-RITE t:motor_construction="Capacitor Start - Induction Run" t:motor_design=Multi-speed t:pd_id=2177144 m:curve_a_flow_gpm=30 m:speed_rpm=1725 m:curve_c_energy_factor_gal_wh=7.82 m:curve_b_power_w=255 m:curve_b_energy_factor_gal_wh=4.43 m:standby_average_power_w=0 m:curve_a_power_w=285 m:curve_c_power_w=302 m:curve_b_flow_gpm=18 m:total_horse_power_hp=0.27 m:curve_a_energy_factor_gal_wh=6.35 m:rated_horsepower_hp=0.25 m:curve_c_flow_gpm=39 m:service_factor=1.1

series e:2ppn-v3hp d:2012-05-02T00:00:00.000Z t:energy_star_partner="Pentair Aquatic Systems" t:model_number=MPEAA6YG-208L t:frame=48 t:speed_setting="Most Efficient Speed" t:markets="United States, Canada" t:energy_star_model_identifier="ES_1105798_PENTAIR WATER POOL AND SPA INC (91308) | MPEAA6YG-208L_04192013200212_1732960" t:model_name=Dyna-Pro t:brand_name=STA-RITE t:motor_construction="Permanent Split-capacitor Motor" t:motor_design=Multi-speed t:pd_id=2178088 m:curve_a_flow_gpm=33 m:speed_rpm=1725 m:curve_b_energy_factor_gal_wh=3.61 m:curve_b_power_w=329 m:curve_c_energy_factor_gal_wh=6.46 m:curve_a_power_w=381 m:curve_c_power_w=421 m:curve_b_flow_gpm=19 m:rated_horsepower_hp=0.33 m:curve_a_energy_factor_gal_wh=5.24 m:total_horse_power_hp=0.33 m:curve_c_flow_gpm=45 m:service_factor=1.04

series e:2ppn-v3hp d:2012-05-02T00:00:00.000Z t:energy_star_partner="Pentair Aquatic Systems" t:model_number=MPEAA6YG-208L t:frame=48 t:speed_setting=High-speed t:markets="United States, Canada" t:energy_star_model_identifier="ES_1105798_PENTAIR WATER POOL AND SPA INC (91308) | MPEAA6YG-208L_04192013200225_1745021" t:model_name=Dyna-Pro t:brand_name=STA-RITE t:motor_construction="Permanent Split-capacitor Motor" t:motor_design=Multi-speed t:pd_id=2178258 m:curve_a_flow_gpm=66 m:speed_rpm=3450 m:curve_c_energy_factor_gal_wh=2.47 m:curve_b_power_w=1621 m:curve_b_energy_factor_gal_wh=1.48 m:standby_average_power_w=0 m:curve_a_power_w=1957 m:curve_c_power_w=2210 m:curve_b_flow_gpm=40 m:total_horse_power_hp=2.6 m:curve_a_energy_factor_gal_wh=2.05 m:rated_horsepower_hp=2.5 m:curve_c_flow_gpm=90 m:service_factor=1.04
```

## Meta Commands

```ls
metric m:speed_rpm p:integer l:"Speed (RPM)" d:"The speed in revolutions per minute (RPM) at which the Energy Factor was measured." t:dataTypeName=number

metric m:curve_a_flow_gpm p:integer l:"Curve-A Flow (GPM)" d:"The flow rate in gallons per minute (GPM) at which the Energy Factor was measured." t:dataTypeName=number

metric m:curve_a_power_w p:integer l:"Curve-A Power (Watts)" d:"The power in watts (W) at which the Energy Factor was measured." t:dataTypeName=number

metric m:curve_a_energy_factor_gal_wh p:float l:"Curve-A Energy Factor (gallons/Wh)" d:"The volume of water pumped in gallons per watt hour (Gal/Wh) of electrical energy consumed by the pump motor. Energy Factor is measured and reported at the intersection of the three pool curves and the pump curve for each Speed Setting. The curves that define the relationship between flow and head for three typical pool types. The equations for the three pool performance curves are as follows: Curve A: H = 0.0167 x F2 Curve B: H=0.050 x F2 Curve C: H=0.0082 x F2 Where H is the total system head in feet of head, and F is the flow rate in gallons per minute (GPM)." t:dataTypeName=number

metric m:curve_c_flow_gpm p:integer l:"Curve-C Flow (GPM)" d:"The flow rate in gallons per minute (GPM) at which the Energy Factor was measured." t:dataTypeName=number

metric m:curve_c_power_w p:integer l:"Curve-C Power (Watts)" d:"The power in watts (W) at which the Energy Factor was measured." t:dataTypeName=number

metric m:curve_c_energy_factor_gal_wh p:float l:"Curve-C Energy Factor (gallons/Wh)" d:"The volume of water pumped in gallons per watt hour (Gal/Wh) of electrical energy consumed by the pump motor. Energy Factor is measured and reported at the intersection of the three pool curves and the pump curve for each Speed Setting. The curves that define the relationship between flow and head for three typical pool types. The equations for the three pool performance curves are as follows: Curve A: H = 0.0167 x F2 Curve B: H=0.050 x F2 Curve C: H=0.0082 x F2 Where H is the total system head in feet of head, and F is the flow rate in gallons per minute (GPM)." t:dataTypeName=number

metric m:curve_b_flow_gpm p:integer l:"Curve-B Flow (GPM)" d:"The flow rate in gallons per minute (GPM) at which the Energy Factor was measured." t:dataTypeName=number

metric m:curve_b_power_w p:integer l:"Curve-B Power (Watts)" d:"The power in watts (W) at which the Energy Factor was measured." t:dataTypeName=number

metric m:curve_b_energy_factor_gal_wh p:float l:"Curve-B Energy Factor (gallons/Wh)" d:"The volume of water pumped in gallons per watt hour (Gal/Wh) of electrical energy consumed by the pump motor. Energy Factor is measured and reported at the intersection of the three pool curves and the pump curve for each Speed Setting. The curves that define the relationship between flow and head for three typical pool types. The equations for the three pool performance curves are as follows: Curve A: H = 0.0167 x F2 Curve B: H=0.050 x F2 Curve C: H=0.0082 x F2 Where H is the total system head in feet of head, and F is the flow rate in gallons per minute (GPM)." t:dataTypeName=number

metric m:standby_average_power_w p:integer l:"Standby Average Power (Watts)" d:"The power draw when the pool pump is in Standby Power Mode. Only applicable to pool pumps with Standby Power Mode." t:dataTypeName=number

metric m:rated_horsepower_hp p:double l:"Rated Horsepower (HP)" d:"The motor power output (HP) designed by the manufacturer for rated revolutions per minute (RPM), voltage and frequency. May be less than Total Horsepower where the Service Factor is > 1.0, or equal to Total Horsepower where the Service Factor = 1.0. Also known as Nameplate Horsepower." t:dataTypeName=number

metric m:service_factor p:float l:"Service Factor" d:"A multiplier applied to Rated Horsepower of a motor to indicate the percent above Nameplate Horsepower at which a pump motor may operate continuously without exceeding its allowable insulation class temperature limit, provided the other design parameters such as rated voltage, frequency and ambient temperature are within limits. A 1.5 HP pump with a 1.65 service factor produces 2.475 HP (Total Horsepower) at the maximum Service Factor point." t:dataTypeName=number

metric m:total_horse_power_hp p:float l:"Total Horse Power (HP)" d:"The product of the Rated Horsepower and the Service Factor of a motor used on a Pool Pump (also known as Service Factor horsepower, SFHP) based on the maximum continuous duty motor power output rating allowable for nameplate ambient rating and motor insulation class. Total Horsepower = Rated Horsepower x Service Factor." t:dataTypeName=number

entity e:2ppn-v3hp l:"ENERGY STAR Certified Pool Pumps" t:url=https://data.energystar.gov/api/views/2ppn-v3hp

property e:2ppn-v3hp t:meta.view v:id=2ppn-v3hp v:category="Active Specifications" v:averageRating=0 v:name="ENERGY STAR Certified Pool Pumps"

property e:2ppn-v3hp t:meta.view.owner v:id=guxy-scz5 v:screenName=ESddas v:lastNotificationSeenAt=1491492552 v:displayName=ESddas

property e:2ppn-v3hp t:meta.view.tableauthor v:id=guxy-scz5 v:screenName=ESddas v:roleName=publisher v:lastNotificationSeenAt=1491492552 v:displayName=ESddas

property e:2ppn-v3hp t:meta.view.metadata.custom_fields.common_core v:Publisher="U.S. Environmental Protection Agency" v:License=https://edg.epa.gov/EPA_Data_License.html v:Contact_Name="Kathleen Vokes" v:Bureau_Code=020:00 v:Program_Code=020:033
```

## Top Records

```ls
| pd_id   | energy_star_partner     | brand_name | model_name                  | model_number  | additional_model_information | motor_design   | speed_setting        | speed_rpm | curve_a_flow_gpm | curve_a_power_w | curve_a_energy_factor_gal_wh | curve_c_flow_gpm | curve_c_power_w | curve_c_energy_factor_gal_wh | curve_b_flow_gpm | curve_b_power_w | curve_b_energy_factor_gal_wh | standby_average_power_w | motor_construction              | frame | rated_horsepower_hp | service_factor | total_horse_power_hp | connected_functionality | connects_using | communication_standard_application_layer | direct_on_premises_open_standard_based_interconnection | date_available_on_market | date_qualified      | markets               | energy_star_model_identifier                                                             | 
| ======= | ======================= | ========== | =========================== | ============= | ============================ | ============== | ==================== | ========= | ================ | =============== | ============================ | ================ | =============== | ============================ | ================ | =============== | ============================ | ======================= | =============================== | ===== | =================== | ============== | ==================== | ======================= | ============== | ======================================== | ====================================================== | ======================== | =================== | ===================== | ======================================================================================== | 
| 2177144 | Pentair Aquatic Systems | STA-RITE   | Dyna-Pro                    | MPRA6YF-206L  |                              | Multi-speed    | Most Efficient Speed | 1725      | 30               | 285             | 6.35                         | 39               | 302             | 7.82                         | 18               | 255             | 4.43                         | 0                       | Capacitor Start - Induction Run | 48    | 0.25                | 1.1            | 0.27                 |                         |                |                                          |                                                        | 2007-08-24T00:00:00      | 2016-01-29T00:00:00 | United States, Canada | ES_1105798_PENTAIR WATER POOL AND SPA INC (91308) | MPRA6YF-206L_04102013021003_9803995  | 
| 2178088 | Pentair Aquatic Systems | STA-RITE   | Dyna-Pro                    | MPEAA6YG-208L |                              | Multi-speed    | Most Efficient Speed | 1725      | 33               | 381             | 5.24                         | 45               | 421             | 6.46                         | 19               | 329             | 3.61                         |                         | Permanent Split-capacitor Motor | 48    | 0.33                | 1.04           | 0.33                 |                         |                |                                          |                                                        | 2012-05-02T00:00:00      | 2013-04-18T00:00:00 | United States, Canada | ES_1105798_PENTAIR WATER POOL AND SPA INC (91308) | MPEAA6YG-208L_04192013200212_1732960 | 
| 2178258 | Pentair Aquatic Systems | STA-RITE   | Dyna-Pro                    | MPEAA6YG-208L |                              | Multi-speed    | High-speed           | 3450      | 66               | 1957            | 2.05                         | 90               | 2210            | 2.47                         | 40               | 1621            | 1.48                         | 0                       | Permanent Split-capacitor Motor | 48    | 2.5                 | 1.04           | 2.6                  |                         |                |                                          |                                                        | 2012-05-02T00:00:00      | 2016-01-29T00:00:00 | United States, Canada | ES_1105798_PENTAIR WATER POOL AND SPA INC (91308) | MPEAA6YG-208L_04192013200225_1745021 | 
| 2178296 | Zodiac Pool Systems     | Jandy      | FloPro                      | FHPM 1.0-2    |                              | Multi-speed    | Low-speed            | 1750      | 26               | 266             | 5.94                         | 34               | 272             | 7.43                         | 17               | 250             | 3.99                         | 0                       | Permanent Split-capacitor Motor | 56    | 0.75                | 1.67           | 1.25                 |                         |                |                                          |                                                        | 2008-12-18T00:00:00      | 2013-05-08T00:00:00 | United States, Canada | ES_1122278_FHPM 1.0-2_04172013205751_3075830                                             | 
| 2178368 | Pentair Aquatic Systems | SHASTA     | IntelliProXF Variable Speed | S-011031      |                              | Variable-speed | Most Efficient Speed | 775       | 16               | 87              | 11.43                        | 22               | 92              | 14.52                        | 9                | 84              | 7.03                         | 4                       | Electronically-commutated Motor | 56    | 3                   | 1.32           | 3.96                 |                         |                |                                          |                                                        | 2011-02-17T00:00:00      | 2013-03-01T00:00:00 | United States, Canada | ES_1105798_PENTAIR WATER POOL AND SPA INC (91308) | S-011031_03012013204936_0976977      | 
| 2178369 | Pentair Aquatic Systems | SHASTA     | IntelliProXF Variable Speed | S-011031      |                              | Variable-speed | High-speed           | 3450      | 73               | 2459            | 1.8                          | 100              | 2826            | 2.13                         | 43               | 1991            | 1.32                         | 4                       | Electronically-commutated Motor | 56    | 3                   | 1.32           | 3.96                 |                         |                |                                          |                                                        | 2011-02-17T00:00:00      | 2016-01-29T00:00:00 | United States, Canada | ES_1105798_PENTAIR WATER POOL AND SPA INC (91308) | S-011031_04232013182753_1673596      | 
| 2178370 | Pentair Aquatic Systems | SHASTA     | IntelliProXF Variable Speed | S-011031      |                              | Variable-speed | Low-speed            | 450       | 9                | 101             | 5.86                         | 13               | 102             | 7.95                         | 6                | 101             | 3.58                         | 4                       | Electronically-commutated Motor | 56    | 3                   | 1.32           | 3.96                 |                         |                |                                          |                                                        | 2011-02-17T00:00:00      | 2016-01-29T00:00:00 | United States, Canada | ES_1105798_PENTAIR WATER POOL AND SPA INC (91308) | S-011031_04232013182656_1616815      | 
| 2178402 | Pentair Aquatic Systems | STA-RITE   | IntelliProXF Variable Speed | 023005        |                              | Variable-speed | Most Efficient Speed | 650       | 13               | 69              | 11.71                        | 18               | 73              | 15.49                        | 8                | 69              | 7.07                         | 4                       | Electronically-commutated Motor | 56    | 3                   | 1.32           | 3.96                 |                         |                |                                          |                                                        | 2012-07-19T00:00:00      | 2016-01-29T00:00:00 | United States, Canada | ES_1105798_PENTAIR WATER POOL AND SPA INC (11803) | 023005_04052013200934_2574134        | 
| 2178403 | Pentair Aquatic Systems | STA-RITE   | IntelliProXF Variable Speed | 023005        |                              | Variable-speed | High-speed           | 3450      | 73               | 2534            | 1.73                         | 100              | 2866            | 2.11                         | 43               | 2065            | 1.27                         | 4                       | Electronically-commutated Motor | 56    | 3                   | 1.32           | 3.96                 | No                      |                |                                          |                                                        | 2012-07-19T00:00:00      | 2016-01-29T00:00:00 | United States, Canada | ES_1105798_PENTAIR WATER POOL AND SPA INC (91308) | 023005_04232013222835_6115561        | 
| 2178404 | Pentair Aquatic Systems | STA-RITE   | IntelliProXF Variable Speed | 023005        |                              | Variable-speed | Low-speed            | 450       | 9                | 65              | 8.83                         | 13               | 66              | 11.84                        | 5                | 64              | 5.24                         | 4                       | Electronically-commutated Motor | 56    | 3                   | 1.32           | 3.96                 | No                      |                |                                          |                                                        | 2012-07-19T00:00:00      | 2016-01-29T00:00:00 | United States, Canada | ES_1105798_PENTAIR WATER POOL AND SPA INC (91308) | 023005_04232013222940_6180883        | 
```