# ENERGY STAR Certified Commercial Fryers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/energy-star-certified-commercial-fryers) |
| Metadata | [Link](https://data.energystar.gov/api/views/edi8-b5vk) |
| Data: JSON | [100 Rows](https://data.energystar.gov/api/views/edi8-b5vk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.energystar.gov/api/views/edi8-b5vk/rows.csv?max_rows=100) |
| Host | data.energystar.gov |
| Id | edi8-b5vk |
| Name | ENERGY STAR Certified Commercial Fryers |
| Category | Active Specifications |
| Tags | comercialk fryers |
| Created | 2013-06-04T19:17:59Z |
| Publication Date | 2016-10-05T16:00:32Z |

## Description

Certified models meet all ENERGY STAR requirements as listed in the Version 3.0 ENERGY STAR Program Requirements for Commercial Fryers that are effective as of  October 1, 2016. A detailed listing of key efficiency criteria are available at http://www.energystar.gov/index.cfm?c=fryers.pr_crit_fryers

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                                   | Data Type     | Render Type   |
| ======== | ============== | =============================== | ====================================== | ============= | ============= |
| Yes      | series tag     | pd_id                           | ENERGY STAR Unique ID                  | text          | number        |
| Yes      | series tag     | energy_star_partner             | ENERGY STAR Partner                    | text          | text          |
| Yes      | series tag     | brand_name                      | Brand Name                             | text          | text          |
| Yes      | series tag     | model_name                      | Model Name                             | text          | text          |
| Yes      | series tag     | model_number                    | Model Number                           | text          | text          |
| Yes      | series tag     | additional_model_information    | Additional Model Information           | text          | text          |
| Yes      | series tag     | product_type                    | Type                                   | text          | text          |
| Yes      | series tag     | installation                    | Installation                           | text          | text          |
| Yes      | series tag     | fuel_type                       | Fuel Type                              | text          | text          |
| Yes      | numeric metric | fryer_width_in                  | Width (in.)                            | number        | number        |
| Yes      | numeric metric | fryer_depth_in                  | Depth (in.)                            | number        | number        |
| Yes      | numeric metric | shortening_capacity_lb          | Shortening Capacity (lbs)              | number        | number        |
| Yes      | numeric metric | cooking_energy_efficiency       | Cooking Energy Efficiency (%)          | number        | number        |
| Yes      | numeric metric | idle_energy_rate_gas_btu_h      | Energy Use (Idle Energy Rate) (Btu/hr) | number        | number        |
| Yes      | numeric metric | idle_energy_rate_electric_watts | Energy Use (Idle Energy Rate) (Watts)  | number        | number        |
| Yes      | time           | date_available_on_market        | Date Available on Market               | calendar_date | calendar_date |
| No       |                | date_qualified                  | Date Qualified                         | calendar_date | calendar_date |
| Yes      | series tag     | markets                         | Markets                                | text          | text          |
| Yes      | series tag     | energy_star_model_identifier    | CB Model Identifier                    | text          | text          |
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
series e:edi8-b5vk d:2011-08-01T00:00:00.000Z t:energy_star_partner="Pitco Frialator" t:installation=Floor t:model_number=SGH50 t:fuel_type=Gas t:markets="United States, Canada" t:energy_star_model_identifier="ES_1105798_PITCO FRIALATOR INC (181040) | SGH50_08132012151617_0977019" t:product_type="Standard Vat" t:brand_name=Pitco t:model_name=SGH50 t:pd_id=2281958 m:fryer_width_in=14 m:shortening_capacity_lb=50 m:fryer_depth_in=14 m:idle_energy_rate_gas_btu_h=6955 m:cooking_energy_efficiency=54

series e:edi8-b5vk d:2011-08-01T00:00:00.000Z t:energy_star_partner="Pitco Frialator" t:installation=Floor t:model_number=MGII t:fuel_type=Gas t:markets="United States, Canada" t:energy_star_model_identifier="ES_1105798_PITCO FRIALATOR INC (181040) | MGII_08132012151542_0942681" t:product_type="Standard Vat" t:brand_name=Pitco t:model_name=MGII t:pd_id=2281959 m:fryer_width_in=14 m:shortening_capacity_lb=50 m:fryer_depth_in=14 m:idle_energy_rate_gas_btu_h=6955 m:cooking_energy_efficiency=54

series e:edi8-b5vk d:2015-11-13T00:00:00.000Z t:energy_star_partner="Pitco Frialator" t:installation=Floor t:model_number=VF65 t:fuel_type=Gas t:markets="United States, Canada" t:energy_star_model_identifier=ES_1017239_VF65_02032016215040_6240540 t:product_type="Large Vat" t:brand_name=Pitco t:model_name=VF65 t:pd_id=2281961 m:fryer_width_in=18 m:shortening_capacity_lb=70 m:fryer_depth_in=18 m:idle_energy_rate_gas_btu_h=9631 m:cooking_energy_efficiency=53
```

## Meta Commands

```ls
metric m:fryer_width_in p:integer l:"Width (in.)" d:"For a standard fryer, the distance between the inner side walls of the frypot. For split vat fryers, the dimensions for twice the width of one side of the frypot." t:dataTypeName=number

metric m:fryer_depth_in p:integer l:"Depth (in.)" d:"The internal vertical distance taken from the bottom of the vat to the oil capacity fill line." t:dataTypeName=number

metric m:shortening_capacity_lb p:integer l:"Shortening Capacity (lbs)" d:"The total amount of shortening the fry can hold in pounds." t:dataTypeName=number

metric m:cooking_energy_efficiency p:integer l:"Cooking Energy Efficiency (%)" d:"The quantity of energy input to the food product (i.e., french fries) during the cooking process; expressed as a percentage of the quantity of energy input to the fryer during the heavy-, medium-, and light-load tests." t:dataTypeName=number

metric m:idle_energy_rate_gas_btu_h p:integer l:"Energy Use (Idle Energy Rate) (Btu/hr)" d:"The average rate of energy consumed in Btu/h by the fryer while ?holding? or ?idling? the frying medium at the thermostat(s) set point." t:dataTypeName=number

metric m:idle_energy_rate_electric_watts p:integer l:"Energy Use (Idle Energy Rate) (Watts)" d:"The average rate of energy consumed in watts by the fryer while ?holding? or ?idling? the frying medium at the thermostat(s) set point." t:dataTypeName=number

entity e:edi8-b5vk l:"ENERGY STAR Certified Commercial Fryers" t:url=https://data.energystar.gov/api/views/edi8-b5vk

property e:edi8-b5vk t:meta.view v:id=edi8-b5vk v:category="Active Specifications" v:averageRating=0 v:name="ENERGY STAR Certified Commercial Fryers"

property e:edi8-b5vk t:meta.view.owner v:id=guxy-scz5 v:screenName=ESddas v:lastNotificationSeenAt=1491492552 v:displayName=ESddas

property e:edi8-b5vk t:meta.view.tableauthor v:id=guxy-scz5 v:screenName=ESddas v:roleName=publisher v:lastNotificationSeenAt=1491492552 v:displayName=ESddas

property e:edi8-b5vk t:meta.view.metadata.custom_fields.common_core v:Publisher="U.S. Environmental Protection Agency" v:License=https://edg.epa.gov/EPA_Data_License.html v:Contact_Name="Kathleen Vokes" v:Bureau_Code=020:00 v:Program_Code=020:033
```

## Top Records

```ls
| pd_id   | energy_star_partner | brand_name | model_name | model_number | additional_model_information | product_type | installation | fuel_type | fryer_width_in | fryer_depth_in | shortening_capacity_lb | cooking_energy_efficiency | idle_energy_rate_gas_btu_h | idle_energy_rate_electric_watts | date_available_on_market | date_qualified      | markets               | energy_star_model_identifier                                             | 
| ======= | =================== | ========== | ========== | ============ | ============================ | ============ | ============ | ========= | ============== | ============== | ====================== | ========================= | ========================== | =============================== | ======================== | =================== | ===================== | ======================================================================== | 
| 2281958 | Pitco Frialator     | Pitco      | SGH50      | SGH50        |                              | Standard Vat | Floor        | Gas       | 14             | 14             | 50                     | 54                        | 6955                       |                                 | 2011-08-01T00:00:00      | 2016-10-20T00:00:00 | United States, Canada | ES_1105798_PITCO FRIALATOR INC (181040) | SGH50_08132012151617_0977019   | 
| 2281959 | Pitco Frialator     | Pitco      | MGII       | MGII         |                              | Standard Vat | Floor        | Gas       | 14             | 14             | 50                     | 54                        | 6955                       |                                 | 2011-08-01T00:00:00      | 2016-10-20T00:00:00 | United States, Canada | ES_1105798_PITCO FRIALATOR INC (181040) | MGII_08132012151542_0942681    | 
| 2281961 | Pitco Frialator     | Pitco      | VF65       | VF65         |                              | Large Vat    | Floor        | Gas       | 18             | 18             | 70                     | 53                        | 9631                       |                                 | 2015-11-13T00:00:00      | 2016-10-20T00:00:00 | United States, Canada | ES_1017239_VF65_02032016215040_6240540                                   | 
| 2281965 | Pitco Frialator     | Pitco      | SFSSH55    | SFSSH55      |                              | Standard Vat | Floor        | Gas       | 14             | 14             | 50                     | 57                        | 7940                       |                                 | 2011-08-01T00:00:00      | 2016-10-20T00:00:00 | United States, Canada | ES_1105798_PITCO FRIALATOR INC (181040) | SFSSH55_08132012151609_0969060 | 
| 2281966 | Pitco Frialator     | Pitco      | SSHF55     | SSHF55       |                              | Standard Vat | Floor        | Gas       | 14             | 14             | 50                     | 57                        | 7940                       |                                 | 2011-08-01T00:00:00      | 2016-10-20T00:00:00 | United States, Canada | ES_1105798_PITCO FRIALATOR INC (181040) | SSHF55_08132012151624_0984141  | 
| 2281967 | Pitco Frialator     | Pitco      | SSH55      | SSH55        |                              | Standard Vat | Floor        | Gas       | 14             | 14             | 50                     | 57                        | 7940                       |                                 | 2011-08-01T00:00:00      | 2016-10-20T00:00:00 | United States, Canada | ES_1105798_PITCO FRIALATOR INC (181040) | SSH55_08132012151618_0978414   | 
| 2281969 | Pitco Frialator     | Pitco      | SGC        | SGC          |                              | Standard Vat | Floor        | Gas       | 14             | 14             | 35                     | 50                        | 7639                       |                                 | 2011-08-01T00:00:00      | 2016-10-20T00:00:00 | United States, Canada | ES_1105798_PITCO FRIALATOR INC (181040) | SGC_08132012151615_0975617     | 
| 2281970 | Pitco Frialator     | Pitco      | VF35       | VF35         |                              | Standard Vat | Floor        | Gas       | 14             | 14             | 35                     | 50                        | 7639                       |                                 | 2011-08-01T00:00:00      | 2016-10-20T00:00:00 | United States, Canada | ES_1105798_PITCO FRIALATOR INC (181040) | VF35_08132012151629_0989772    | 
| 2281971 | Pitco Frialator     | Pitco      | SFSSH60    | SFSSH60      |                              | Standard Vat | Floor        | Gas       | 14             | 18             | 60                     | 58                        | 7856                       |                                 | 2011-08-01T00:00:00      | 2016-10-20T00:00:00 | United States, Canada | ES_1105798_PITCO FRIALATOR INC (181040) | SFSSH60_08132012151610_0970812 | 
| 2281972 | Pitco Frialator     | Pitco      | SSH60      | SSH60        |                              | Standard Vat | Floor        | Gas       | 14             | 18             | 60                     | 58                        | 7856                       |                                 | 2011-08-01T00:00:00      | 2016-10-20T00:00:00 | United States, Canada | ES_1105798_PITCO FRIALATOR INC (181040) | SSH60_08132012151619_0979826   | 
```